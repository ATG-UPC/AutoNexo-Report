### **2.6.5. Bounded Context: Payment**

#### **2.6.5.1. Domain Layer**

Este bounded context cubre la **gestión de suscripciones a la plataforma**, incluyendo la activación, renovación, cancelación y facturación asociada.  
No gestiona pagos directos entre propietarios y talleres. Su alcance se limita a planes de suscripción de los distintos actores (owners, workshops, administradores).

---

### **Aggregates**

- **Subscription**  
  **Propósito:** Representa una suscripción activa en la plataforma.  
  **Atributos:**  
  - subscriptionId: UUID  
  - subscriberId: UUID (puede ser ownerId o workshopId)  
  - planId: UUID  
  - status: SubscriptionStatus (Active, Suspended, Cancelled, Expired)  
  - startDate: DateTime  
  - endDate: DateTime  
  - renewalDate: DateTime  
  - paymentMethod: PaymentMethod  
  **Métodos:**  
  - activate(planId, paymentMethod)  
  - renew()  
  - cancel(reason: string)  
  - suspend(reason: string)  
  - expire()  
  **Relaciones:**  
  - 1 ⟶ 1 con Plan

- **Invoice**  
  **Propósito:** Documento de facturación generado en cada ciclo de suscripción.  
  **Atributos:**  
  - invoiceId: UUID  
  - subscriptionId: UUID  
  - amount: Money  
  - periodStart: DateTime  
  - periodEnd: DateTime  
  - issuedAt: DateTime  
  - status: InvoiceStatus (Issued, Paid, Failed)  
  **Métodos:**  
  - markPaid()  
  - markFailed(reason: string)  

---

##### **Entities**

- **Plan**  
  **Propósito:** Define las características de un plan de suscripción.  
  **Atributos:**  
  - planId: UUID  
  - name: string  
  - description: string  
  - price: Money  
  - duration: Duration (ej. mensual, anual)  
  - features: List<Feature>  
  **Métodos:**  
  - updateDetails(name, description, price, duration, features)  

---

##### **Value Objects**

- **Money** – amount, currency.  
- **PaymentMethod** – tipo (Card, PayPal, Transfer), tokenizado.  
- **Feature** – nombre, descripción.  

---

##### **Events (Domain Events)**

- SubscriptionActivatedEvent(subscriptionId, subscriberId, planId, occurredAt)  
  **Propósito:** Se activó una nueva suscripción.  
- SubscriptionRenewedEvent(subscriptionId, planId, renewalDate, occurredAt)  
  **Propósito:** Se renovó una suscripción existente.  
- SubscriptionCancelledEvent(subscriptionId, reason, occurredAt)  
  **Propósito:** Una suscripción fue cancelada.  
- SubscriptionSuspendedEvent(subscriptionId, reason, occurredAt)  
  **Propósito:** La suscripción fue suspendida por incumplimiento o fallo de pago.  
- SubscriptionExpiredEvent(subscriptionId, occurredAt)  
  **Propósito:** La suscripción llegó a su fin y no fue renovada.  
- InvoiceIssuedEvent(invoiceId, subscriptionId, amount, occurredAt)  
  **Propósito:** Se generó una factura.  
- InvoicePaidEvent(invoiceId, occurredAt)  
  **Propósito:** Una factura fue pagada correctamente.  
- InvoiceFailedEvent(invoiceId, reason, occurredAt)  
  **Propósito:** Falló el cobro de la factura.  

---

##### **Services (Domain Interfaces)**

- **BillingService**  
  Métodos:  
  - generateInvoice(subscriptionId: UUID) → Invoice  
  - charge(invoiceId: UUID, paymentMethod: PaymentMethod) → bool  
  **Propósito:** Gestiona la facturación y cobro de suscripciones.  

- **SubscriptionPolicy**  
  Métodos:  
  - canRenew(subscriptionId: UUID) → bool  
  - canCancel(subscriptionId: UUID) → bool  
  **Propósito:** Define reglas de negocio sobre renovación y cancelación.  

---

#### **2.6.5.2. Interface Layer**

Expone endpoints REST/GraphQL para gestión de suscripciones.  

- **Controllers:** SubscriptionController, BillingController  
- **Resources:**  
  - SubscriptionResource { subscriptionId, subscriberId, planId, status, startDate, endDate, renewalDate }  
  - InvoiceResource { invoiceId, subscriptionId, amount, periodStart, periodEnd, status }  
  - PlanResource { planId, name, description, price, duration, features }  
- **Assemblers:** SubscriptionAssembler, InvoiceAssembler, PlanAssembler  

---

#### **2.6.5.3. Application Layer**

- **Command Services:**  
  - SubscriptionCommandService  
  - BillingCommandService  

- **Query Services:**  
  - SubscriptionQueryService  
  - InvoiceQueryService  
  - PlanQueryService  

- **Event Handlers:**  
  - OnInvoicePaid → renueva suscripción si aplica.  
  - OnInvoiceFailed → suspende suscripción.  
  - OnSubscriptionExpired → genera evento para notificar al usuario.  

- **ACLs:**  
  - ExternalPaymentGatewayAcl (integra con proveedor de pagos externo).  

---

#### **2.6.5.4. Infrastructure Layer**

Implementaciones de repositorios y adaptadores externos.  

- **Repositories:**  
  - SubscriptionRepository : ISubscriptionRepository  
  - InvoiceRepository : IInvoiceRepository  
  - PlanRepository : IPlanRepository  

- **External Adapters:**  
  - PaymentGatewayAdapter (Stripe/PayPal/etc.)  
  - MessageBrokerPublisher (publicación de eventos a otros BCs)  

---

#### **2.6.5.5. Bounded Context Software Architecture Component Level Diagrams**



#### **2.6.5.6. Bounded Context Software Architecture Code Level Diagrams**

##### **2.6.5.6.1. Bounded Context Domain Layer Class Diagrams**


##### **2.6.5.6.2. Bounded Context Database Design Diagram**

