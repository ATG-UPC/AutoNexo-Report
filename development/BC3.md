### **2.6.X. Bounded Context: Matching&Booking**

#### **2.6.x.1. Domain Layer**

Este bounded context cubre desde la solicitud de servicio hasta la creación/confirmación del booking, la gestión de ofertas y reprogramaciones, y la apertura de la service order para el handover hacia Vehicle&Maintenance.  
---

### **Aggregates**

- **ServiceRequest**  
  **Propósito:** Intención del propietario de recibir un servicio (tipo, ventana deseada, ubicación).  
  **Atributos:**  
  - serviceRequestId: UUID  
  - ownerId: UUID  
  - vehicleId: UUID  
  - serviceType: ServiceType  
  - preferredWindow: TimeRange  
  - location: GeoLocation  
  - status: ServiceRequestStatus (Open, Matching, Offered, Archived, Cancelled)  
  **Métodos:**  
  - startMatching()  
  - archive(reason: string)  
  - cancel(reason: string)  
  **Relaciones:**  
  - 1 ⟶ * con Offer  
  - 1 ⟶ 0..1 con Booking

- **Offer**  
  **Propósito:** Propuesta desde un workshop (referencia externa por workshopId) para atender el ServiceRequest.  
  **Atributos:**  
  - offerId: UUID  
  - serviceRequestId: UUID  
  - workshopId: UUID  
  - proposedSlot: TimeRange  
  - price: Money  
  - terms: Terms  
  - status: OfferStatus (Submitted, Withdrawn, Accepted, Rejected, Expired)  
  **Métodos:**  
  - withdraw(reason: string)  
  - accept()  
  - reject()  
  **Relaciones:**  
  - * ⟶ 1 con ServiceRequest  
  - 0..1 ⟶ 1 con Booking

- **Booking**  
  **Propósito:** Reserva formal entre owner y workshop basada en una Offer aceptada.  
  **Atributos:**  
  - bookingId: UUID  
  - serviceRequestId: UUID  
  - offerId: UUID  
  - workshopId: UUID  
  - vehicleId: UUID  
  - slot: TimeRange  
  - status: BookingStatus (Created, Confirmed, RescheduleRequested, Rescheduled, Cancelled)  
  - cancellationPolicy: CancellationPolicy  
  - createdAt: DateTime  
  **Métodos:**  
  - confirm()  
  - requestReschedule(newSlot: TimeRange, reason: string)  
  - reschedule(approvedSlot: TimeRange)  
  - cancel(reason: string)  
  **Relaciones:**  
  - 1 ⟶ 1 con Offer  
  - 1 ⟶ 1 con ServiceRequest  
  - 1 ⟶ 0..1 con ServiceOrder

- **ServiceOrder**  
  **Propósito:** Orden operativa creada al confirmar un Booking; artefacto de handover hacia Vehicle&Maintenance.  
  **Atributos:**  
  - serviceOrderId: UUID  
  - bookingId: UUID  
  - workshopId: UUID  
  - vehicleId: UUID  
  - scheduledSlot: TimeRange  
  - status: ServiceOrderStatus (Opened, Closed, Cancelled)  
  - openedAt: DateTime  
  **Métodos:**  
  - open()  
  - close()  
  - cancel(reason: string)  
  **Relaciones:**  
  - 1 ⟶ 1 con Booking

---

### **Entities**

- **RescheduleRequest**  
  **Propósito:** Solicitud de reprogramación sobre un Booking existente.  
  **Atributos:**  
  - rescheduleRequestId: UUID  
  - bookingId: UUID  
  - requestedSlot: TimeRange  
  - reason: string  
  - status: RescheduleStatus (Requested, Approved, Declined)  
  **Métodos:**  
  - approve(approvedSlot: TimeRange)  
  - decline(reason: string)  
  **Relaciones:**  
  - * ⟶ 1 con Booking

---

### **Value Objects**

- **TimeRange:** start: DateTime, end: DateTime  
- **Money:** amount: decimal, currency: string  
- **GeoLocation:** lat: decimal, lon: decimal  
- **Terms:** summary: string, detailsUrl: string?  
- **CancellationPolicy:** freeUntilHours: int, penaltyAfter: Money  
- **ServiceType:** enum (Inspection, OilChange, Tires, Brakes, Bodywork, Other)

---

### **Events (Domain Events)**

- ServiceRequestSubmittedEvent(serviceRequestId, ownerId, vehicleId, serviceType, occurredAt)  
- MatchingProcessStartedEvent(serviceRequestId, occurredAt)  
- WorkshopRecommendationsGeneratedEvent(serviceRequestId, workshopIds, occurredAt)  
- OfferSubmittedEvent(offerId, serviceRequestId, workshopId, occurredAt)  
- OfferWithdrawnEvent(offerId, occurredAt)  
- OfferAcceptedEvent(offerId, serviceRequestId, occurredAt)  
- BookingCreatedEvent(bookingId, serviceRequestId, offerId, occurredAt)  
- BookingConfirmedEvent(bookingId, occurredAt)  
- BookingRescheduleRequestedEvent(bookingId, rescheduleRequestId, requestedSlot, occurredAt)  
- BookingRescheduledEvent(bookingId, newSlot, occurredAt)  
- BookingCancelledEvent(bookingId, reason, occurredAt)  
- ServiceOrderOpenedEvent(serviceOrderId, bookingId, occurredAt)  
- ServiceOrderClosedEvent(serviceOrderId, bookingId, occurredAt)  
- ServiceRequestArchivedEvent(serviceRequestId, occurredAt)

---

### **Services (Domain Interfaces)**

**Nota:** Aquí solo se definen interfaces. **Sus implementaciones que interactúan con otros BCs se ubican en Application Layer** mediante ACL/adapters.

- **MatchingEngine**  
  Métodos:  
  - findCandidates(serviceRequest: ServiceRequest) → List<UUID>  (workshopId)

- **AvailabilityService**  
  Métodos:  
  - isAvailable(workshopId: UUID, slot: TimeRange) → bool  
  - suggestSlots(workshopId: UUID, constraints: TimeRange) → List<TimeRange>

- **PricingService**  
  Métodos:  
  - quote(serviceType: ServiceType, workshopId: UUID) → Money

- **OfferPolicy**  
  Métodos:  
  - canSubmit(workshopId: UUID, serviceRequestId: UUID) → bool  
  - canAccept(offerId: UUID) → bool

- **BookingPolicy**  
  Métodos:  
  - canConfirm(bookingId: UUID) → bool  
  - canCancel(bookingId: UUID, when: DateTime) → bool

- **ScheduleAllocator**  
  Métodos:  
  - reserve(workshopId: UUID, slot: TimeRange) → bool  
  - release(workshopId: UUID, slot: TimeRange)

---

#### **2.6.x.2. Interface Layer**

- **Controllers:** ServiceRequestController, MatchingController, OfferController, BookingController, ServiceOrderController, RescheduleController  
- **Resources:**  
  - SubmitServiceRequestResource { ownerId, vehicleId, serviceType, preferredWindow, location }  
  - OfferResource { offerId, serviceRequestId, workshopId, proposedSlot, price, status }  
  - BookingResource { bookingId, serviceRequestId, offerId, workshopId, vehicleId, slot, status, createdAt }  
  - RescheduleRequestResource { rescheduleRequestId, bookingId, requestedSlot, reason, status }  
  - ServiceOrderResource { serviceOrderId, bookingId, workshopId, vehicleId, scheduledSlot, status, openedAt }  
- **Assemblers:** ServiceRequestAssembler, OfferAssembler, BookingAssembler, ServiceOrderAssembler, RescheduleAssembler

---

#### **2.6.x.3. Application Layer**

**Aquí se implementan las integraciones con otros bounded contexts (ACL) y los servicios concretos.**

- **Command Services:**  
  - ServiceRequestCommandService  
  - OfferCommandService  
  - BookingCommandService  
  - RescheduleCommandService  
  - ServiceOrderCommandService

- **Query Services:**  
  - ServiceRequestQueryService  
  - OfferQueryService  
  - BookingQueryService  
  - ServiceOrderQueryService

- **Event Handlers:**  
  - OnOfferAccepted → crea Booking y emite BookingCreatedEvent  
  - OnBookingConfirmed → usa ScheduleAllocator (ACL) para reservar slot y emite ServiceOrderOpenedEvent  
  - OnBookingCancelled → usa ScheduleAllocator (ACL) para liberar slot; puede emitir ServiceOrderClosedEvent  
  - OnWorkshopProjectionUpdated (evento externo proyectado) → ajusta sugerencias de Matching

- **ACL Implementations (implementaciones concretas de las interfaces del Domain Layer):**  
  - WorkshopCalendarAclAvailabilityService (implementa AvailabilityService)  
  - WorkshopCalendarAclScheduleAllocator (implementa ScheduleAllocator)  
  - WorkshopPricingAcl (implementa PricingService)  
  - PaymentsAcl (si BookingPolicy depende de pago)  
  - IdentityAcl, NotificationsAcl  
  - TrustingReputationAcl (dispara invitación a calificar tras cierre)

- **Outbound Services:**  
  - DomainEventPublisher  
  - BookingNotificationSender

---

#### **2.6.x.4. Infrastructure Layer**

- **Repositories (implementaciones):**  
  - ServiceRequestRepository : IServiceRequestRepository  
  - OfferRepository : IOfferRepository  
  - BookingRepository : IBookingRepository  
  - ServiceOrderRepository : IServiceOrderRepository

- **External Services Adapters (utilizados por la Application Layer/ACL):**  
  - WorkshopCalendarAdapter (conecta con Workshop BC)  
  - PaymentGatewayAdapter  
  - MessageBrokerPublisher  
  - NotificationAdapter

---

#### **2.6.x.5. Bounded Context Software Architecture Component Level Diagrams**

(Se incluirá diagrama C4-Component posteriormente.)

---

#### **2.6.x.6. Bounded Context Software Architecture Code Level Diagrams**

##### **2.6.x.6.1. Bounded Context Domain Layer Class Diagrams**
(UML de aggregates, entities, value objects, services e interfaces de repositorio, con multiplicidades.)

##### **2.6.x.6.2. Bounded Context Database Design Diagram**
(Tablas sugeridas y PK/FK):  
- service_requests (service_request_id PK, owner_id, vehicle_id, service_type, preferred_start, preferred_end, lat, lon, status)  
- offers (offer_id PK, service_request_id FK, workshop_id, proposed_start, proposed_end, price_amount, price_currency, terms, status)  
- bookings (booking_id PK, service_request_id FK, offer_id FK, workshop_id, vehicle_id, slot_start, slot_end, status, created_at, cancellation_policy_json)  
- reschedule_requests (reschedule_request_id PK, booking_id FK, requested_start, requested_end, reason, status)  
- service_orders (service_order_id PK, booking_id FK, workshop_id, vehicle_id, scheduled_start, scheduled_end, status, opened_at)

Notas:  
- La disponibilidad del taller no se persiste aquí como entidad de dominio; si se almacena, es como read model/proyección para queries, fuera del Domain Layer.
