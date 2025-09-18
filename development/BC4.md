### **2.6.4. Bounded Context: Workshop**

#### **2.6.4.1. Domain Layer**

Este bounded context cubre la **gestión integral de los talleres (workshops)**: identidad, catálogo de servicios, disponibilidad operativa y personal técnico.  
Su rol es mantener la información canónica del taller y exponerla a otros bounded contexts como Matching&Booking (para reservas) y Trusting&Reputation (para proyecciones de reputación).  
No ejecuta procesos de matching, booking ni reputación, pero **publica eventos** que permiten integraciones.

---

### **Aggregates**

- **Workshop**  
  **Propósito:** Entidad raíz que representa un taller registrado en la plataforma.  
  **Atributos:**  
  - workshopId: UUID  
  - legalName: string  
  - tradeName: string  
  - taxId: string  
  - status: WorkshopStatus (Active, Suspended, Deactivated)  
  - contacts: List<Contact>  
  - addresses: List<Address>  
  - certifications: List<Certification>  
  - operatingPolicy: OperatingPolicy  
  - capabilities: Capabilities  
  - services: List<WorkshopService>  
  **Métodos:**  
  - amendInformation(delta: WorkshopDelta)  
  - addService(service: WorkshopService)  
  - removeService(serviceId: UUID)  
  - setCapabilities(c: Capabilities)  
  - activate() / suspend(reason) / deactivate(reason)  
  **Relaciones:**  
  - 1 ⟶ * con WorkshopService  
  - 1 ⟶ 1 con WorkshopSchedule

- **WorkshopSchedule**  
  **Propósito:** Calendario operativo del taller, con reglas de disponibilidad y excepciones.  
  **Atributos:**  
  - workshopId: UUID  
  - businessHours: List<BusinessWindow>  
  - exceptions: List<ExceptionWindow>  
  - timezone: string  
  **Métodos:**  
  - updateBusinessHours(windows: List<BusinessWindow>)  
  - addException(window: ExceptionWindow)  
  - proposeSlots(constraints: SlotConstraints) → List<AvailabilitySlot>  
  **Relaciones:**  
  - 1 ⟶ * con AvailabilitySlot

---

##### **Entities**

- **Mechanic**  
  **Propósito:** Representa un técnico/mecánico asociado al taller.  
  **Atributos:**  
  - mechanicId: UUID  
  - fullName: string  
  - skills: List<Skill>  
  - certifications: List<Certification>  
  - active: bool  
  **Métodos:**  
  - assignSkill(skill: Skill)  
  - revokeSkill(skill: Skill)

- **WorkshopService**  
  **Propósito:** Define un servicio que el taller ofrece a los clientes.  
  **Atributos:**  
  - serviceId: UUID  
  - serviceType: ServiceType  
  - stdDuration: Duration  
  - basePrice: Money  
  - requirements: List<Requirement>  
  - active: bool  
  **Métodos:**  
  - changePrice(newPrice: Money)  
  - activate() / deactivate()

---

##### **Value Objects**

- **Contact** – tipo (Phone, Email, WhatsApp) y valor.  
- **Address** – line1, city, region, postalCode, country.  
- **GeoPoint** – latitud, longitud.  
- **Certification** – código, entidad emisora, vigencia.  
- **OperatingPolicy** – políticas de operación (cancelación, leadTime, etc.).  
- **Capabilities** – marcas, tipos de vehículo, equipamiento, capacidad máxima concurrente.  
- **Equipment** – nombre del equipo, servicios para los que aplica.  
- **AvailabilitySlot** – slotId, start, end, state (Free, Blocked, Unavailable), reason.  
- **BusinessWindow** – dayOfWeek, openTime, closeTime.  
- **ExceptionWindow** – start, end, reason.  

---

##### **Events (Domain Events)**

- WorkshopRegisteredEvent(workshopId, occurredAt)  
  **Propósito:** Se registró un nuevo taller en la plataforma.  
- WorkshopInformationAmendedEvent(workshopId, delta, occurredAt)  
  **Propósito:** Se modificó la información del taller.  
- WorkshopScheduleUpdatedEvent(workshopId, occurredAt)  
  **Propósito:** Se actualizó el calendario operativo.  
- WorkshopAvailabilityBlockedEvent(workshopId, slotId, occurredAt)  
  **Propósito:** Un slot quedó bloqueado (ej. por booking confirmado).  
- WorkshopAvailabilityReleasedEvent(workshopId, slotId, occurredAt)  
  **Propósito:** Un slot bloqueado fue liberado.  
- MechanicAssignedEvent(workshopId, mechanicId, occurredAt)  
  **Propósito:** Se asignó un mecánico al taller.  
- MechanicUnassignedEvent(workshopId, mechanicId, occurredAt)  
  **Propósito:** Se desasignó un mecánico.  
- WorkshopDeactivatedEvent(workshopId, occurredAt)  
  **Propósito:** El taller quedó inactivo.  

---

##### **Services (Domain Interfaces)**

- **ScheduleService**  
  Métodos:  
  - isAvailable(workshopId: UUID, slot: TimeRange) → bool  
  - reserveSlot(workshopId: UUID, slot: TimeRange)  
  - releaseSlot(workshopId: UUID, slot: TimeRange)  
  **Propósito:** Gestionar disponibilidad del calendario de talleres.  

- **WorkshopPolicy**  
  Métodos:  
  - canActivate(workshopId: UUID) → bool  
  - canAssignMechanic(workshopId: UUID, mechanicId: UUID) → bool  
  **Propósito:** Validar reglas de negocio específicas de talleres.  

---

#### **2.6.4.2. Interface Layer**

Capa de exposición de APIs y DTOs para integración con otros contexts.  

- **Controllers**: WorkshopController, ScheduleController, MechanicController.  
- **Resources**:  
  - WorkshopResource { workshopId, legalName, status, services, capabilities }  
  - WorkshopScheduleResource { workshopId, businessHours, exceptions }  
  - MechanicResource { mechanicId, fullName, skills, active }  
  - WorkshopServiceResource { serviceId, serviceType, stdDuration, basePrice, active }  
- **Assemblers**: WorkshopAssembler, ScheduleAssembler, MechanicAssembler, ServiceAssembler.  

---

#### **2.6.4.3. Application Layer**

Implementa los casos de uso del negocio y la orquestación con otros contexts.  

- **Command Services**: WorkshopCommandService, ScheduleCommandService, MechanicCommandService.  
- **Query Services**: WorkshopQueryService, ScheduleQueryService.  
- **Event Handlers**:  
  - OnBookingConfirmed → bloquea slot (ScheduleService).  
  - OnBookingCancelled → libera slot.  
  - OnServiceOrderClosed → libera slot.  
  - OnReviewSubmitted (Trusting&Reputation) → actualiza proyección de reputación.  
- **ACLs / Adaptadores**:  
  - MatchingAcl (exposición de servicios y disponibilidad hacia Matching&Booking).  
  - TrustingReputationAcl (publica información de talleres hacia Trusting&Reputation).  

---

#### **2.6.4.4. Infrastructure Layer**

Implementaciones de persistencia y adaptadores externos.  

- **Repositories**:  
  - WorkshopRepository : IWorkshopRepository  
  - ScheduleRepository : IScheduleRepository  
  - MechanicRepository : IMechanicRepository  
- **External Adapters**:  
  - ExternalCertificationAdapter (validación de certificaciones)  
  - MessageBrokerPublisher (publicación de eventos a otros BCs)  

---

#### **2.6.4.5. Bounded Context Software Architecture Component Level Diagrams**

(Se incluirá diagrama C4-Component posteriormente.)  

---

#### **2.6.4.6. Bounded Context Software Architecture Code Level Diagrams**

##### **2.6.4.6.1. Bounded Context Domain Layer Class Diagrams**

(UML de aggregates, entities, value objects, services e interfaces de repositorio).  

##### **2.6.4.6.2. Bounded Context Database Design Diagram**

(Tablas sugeridas y PK/FK):  
- workshops (workshop_id PK, legal_name, trade_name, tax_id, status, operating_policy_json)  
- workshop_services (service_id PK, workshop_id FK, service_type, std_duration, base_price_amount, base_price_currency, active)  
- workshop_schedules (schedule_id PK, workshop_id FK, business_hours_json, timezone)  
- availability_slots (slot_id PK, schedule_id FK, start, end, state, reason)  
- mechanics (mechanic_id PK, workshop_id FK, full_name, skills_json, certifications_json, active)  

---
