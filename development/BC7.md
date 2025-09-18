### **2.6.7. Bounded Context: Notifications**

#### **2.6.7.1. Domain Layer**

Este bounded context gestiona la orquestación y entrega de notificaciones en tres canales: **Push, Email y SMS**.  
Soporta mensajes transaccionales  y mensajes programados
No incorpora lógica de negocio de otros BCs; consume sus eventos y aplica plantillas, preferencias y políticas de envío.
---

### **Aggregates**

- **Notification**  
  **Propósito:** Representa una notificación a uno o más destinatarios, con plantillas y rutas por canal.  
  **Atributos:**  
  - notificationId: UUID  
  - correlationId: string  
  - type: NotificationType (Transactional, Security, Reminder)  
  - recipients: List<UserId>  
  - templateId: UUID  
  - locale: string  
  - payload: Map<string,string>  
  - channelPlan: List<ChannelRoute>  
  - scheduledAt: DateTime?  
  - priority: Priority (High, Normal, Low)  
  - status: NotificationStatus (Pending, Scheduled, Sending, Sent, Failed, Cancelled)  
  **Métodos:**  
  - schedule(at: DateTime)  
  - send()  
  - cancel(reason: string)  
  - recordAttempt(result: DeliveryResult)

- **Template**  
  **Propósito:** Contenido parametrizable por **canal** e **idioma**.  
  **Atributos:**  
  - templateId: UUID  
  - key: string (ej. booking.confirmed)  
  - version: int  
  - channels: Map<Channel, ChannelTemplate>  
  - variables: List<VariableSpec>  
  - defaultLocale: string  
  **Métodos:**  
  - render(channel: Channel, locale: string, payload: Map) → RenderedMessage  
  - newVersion(changes)

---

### **Entities**

- **DeliveryAttempt**  
  **Propósito:** Trazabilidad por canal/proveedor.  
  **Atributos:**  
  - attemptId: UUID  
  - notificationId: UUID  
  - channel: Channel (Email, Push, SMS)  
  - provider: string  
  - requestedAt: DateTime  
  - status: AttemptStatus (Queued, Sent, Delivered, Opened, Clicked, Bounced, Failed)  
  - error?: string  
  **Métodos:**  
  - markDelivered()/markOpened()/markClicked(url)  
  - markBounced(reason)/markFailed(reason)

- **Preference**  
  **Propósito:** Preferencias por usuario y por tipo/canal.  
  **Atributos:**  
  - preferenceId: UUID  
  - userId: UUID  
  - locale: string  
  - channelOptIn: Map<Channel,bool>  
  - typeOptIn: Map<NotificationType,bool>  
  - quietHours?: TimeRange  
  **Métodos:**  
  - setOptIn(scope, enabled: bool)  
  - setQuietHours(range: TimeRange)

---

### **Value Objects**

- **ChannelRoute** – channel, primaryProvider, fallbackProviders[], retries, timeoutMs  
- **RenderedMessage** – subject?, body, richBody?, data?  
- **VariableSpec** – name, required, description  
- **DeliveryResult** – status, providerMessageId?, error?  
- **TimeRange** – startTime, endTime

---

### **Events (Domain Events)**

- NotificationRequestedEvent(notificationId, type, occurredAt)  
  **Propósito:** Se solicitó una notificación (por evento externo o API).
- NotificationScheduledEvent(notificationId, scheduledAt, occurredAt)  
  **Propósito:** Quedó programada para envío futuro.
- NotificationSentEvent(notificationId, occurredAt)  
  **Propósito:** Todos los intentos fueron despachados.
- DeliveryStatusUpdatedEvent(notificationId, attemptId, channel, status, occurredAt)  
  **Propósito:** Actualización de estado por canal/proveedor.
- NotificationFailedEvent(notificationId, reason, occurredAt)  
  **Propósito:** Falló definitivamente tras reintentos.
- PreferenceChangedEvent(userId, occurredAt)  
  **Propósito:** Cambiaron las preferencias y afectan el enrutamiento.

---

### **Services (Domain Interfaces)**

- **TemplateRenderer**  
  - render(templateId, channel, locale, payload) → RenderedMessage  
  **Propósito:** Resuelve versión/idioma y genera el contenido final.

- **ChannelRouter**  
  - route(notification: Notification) → List<ChannelRoute>  
  - dispatch(route, message) → DeliveryResult  
  **Propósito:** Selección de canal/proveedor, reintentos y failover.

- **PreferenceService**  
  - check(userId, type, channel, at: DateTime) → bool  
  **Propósito:** Respeta opt-in/out y quiet hours.

- **SchedulerService**  
  - enqueue(notificationId, at: DateTime)  
  **Propósito:** Programa recordatorios y ventanas de envío.

---

#### **2.6.7.2. Interface Layer**

- **Controllers:** NotificationController, TemplateController, PreferenceController  
- **Resources:**  
  - NotificationResource { notificationId, type, recipients, templateId, scheduledAt, status }  
  - TemplateResource { templateId, key, version, channels, variables }  
  - PreferenceResource { userId, channelOptIn, typeOptIn, quietHours }  
- **Assemblers:** NotificationAssembler, TemplateAssembler, PreferenceAssembler

---

#### **2.6.7.3. Application Layer**

- **Command Services:** NotificationCommandService, TemplateCommandService, PreferenceCommandService  
- **Query Services:** NotificationQueryService, TemplateQueryService  
- **Event Handlers (ejemplos):**  
  - OnBookingConfirmed (Matching&Booking) → NotificationRequestedEvent (Transactional)  
  - OnInvoiceIssued (Payment) → NotificationRequestedEvent (Transactional)  
  - ScheduledReminderTick → envía recordatorios de mantenimiento (Reminder)  
- **ACLs:**  
  - EmailProviderAcl, PushProviderAcl, SmsProviderAcl  
  - IAMAcl (para obtener correos/tokens push verificados)

---

#### **2.6.7.4. Infrastructure Layer**

- **Repositories:** NotificationRepository, TemplateRepository, PreferenceRepository, DeliveryAttemptRepository  
- **External Adapters:** EmailAdapter, PushAdapter, SmsAdapter, MessageBrokerPublisher, SchedulerAdapter

---

#### **2.6.7.5. Bounded Context Software Architecture Component Level Diagrams**

#### **2.6.7.6. Bounded Context Software Architecture Code Level Diagrams**

##### **2.6.7.6.1. Bounded Context Domain Layer Class Diagrams**


##### **2.6.7.6.2. Bounded Context Database Design Diagram**

