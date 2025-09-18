### **2.6.1. Bounded Context: Vehicle&Maintenance**

#### **2.6.1.1. Domain Layer**

Este bounded context cubre la ejecución técnica del mantenimiento del vehículo y su registro histórico auditable, excluyendo matching/booking/pagos.

---

### **Aggregates**

- **Vehicle**  
  **Propósito:** Representa un vehículo y gobierna su información técnica relevante al mantenimiento.  
  **Atributos:**  
  - vehicleId: UUID  
  - licensePlate: LicensePlate  
  - brand: string  
  - model: string  
  - year: int  
  - ownerId: UUID  
  **Métodos:**  
  - assignOwner(ownerId: UUID)  
  - updateDetails(brand: string, model: string, year: int)  
  **Relaciones:**  
  - 1 ⟶ * con MaintenanceRecord.

- **MaintenanceRecord**  
  **Propósito:** Registro auditable del mantenimiento del vehículo; consolida solo tareas registrables en el historial.  
  **Atributos:**  
  - recordId: UUID  
  - vehicleId: UUID  
  - openedAt: DateTime  
  - closedAt: DateTime?  
  - status: MaintenanceStatus  
  **Métodos:**  
  - addTask(task: MaintenanceTask)  
  - approve()  
  - amend(note: string)  
  - complete()  
  **Relaciones:**  
  - 1 ⟶ * con MaintenanceTask.  
  - 1 ⟶ 0..1 con DiagnosticReport (puede existir un informe por record).

---

##### **Entities**

- **MaintenanceTask**  
  **Propósito:** Tarea técnica ejecutada durante el mantenimiento. Puede ser registrable o no registrable.  
  **Atributos:**  
  - taskId: UUID  
  - description: string  
  - category: TaskCategory (enum: Maintenance, Inspection, Cleaning, Other)  
  - recordable: bool  
  - status: TaskStatus (enum: Planned, InProgress, Completed, IssueReported)  
  **Métodos:**  
  - markInProgress()  
  - markCompleted()  
  - reportIssue(details: string)  
  **Relaciones:**  
  - * ⟶ * con PartUsage.  
  - * ⟶ 1 con MaintenanceRecord (pertenencia).

- **PartUsage**  
  **Propósito:** Uso de repuestos/piezas dentro de una tarea.  
  **Atributos:**  
  - partUsageId: UUID  
  - taskId: UUID  
  - partNumber: string  
  - quantity: int  
  **Métodos:**  
  - sin reglas de negocio complejas  
  **Relaciones:**  
  - * ⟶ 1 con MaintenanceTask (pertenencia).

- **DiagnosticReport**  
  **Propósito:** Informe técnico de diagnóstico asociado al mantenimiento.  
  **Atributos:**  
  - reportId: UUID  
  - recordId: UUID  
  - summary: string  
  - createdAt: DateTime  
  **Métodos:**  
  - creación/generación a través de servicio de dominio DiagnosticService  
  **Relaciones:**  
  - 1 ⟶ 1 con MaintenanceRecord.

---

##### **Value Objects**

- **LicensePlate**  
  **Propósito:** Encapsula y valida la matrícula.  
  **Atributos:**  
  - value: string  
  **Métodos:**  
  - validatePlate()  
  **Relaciones:**  
  - Usado por Vehicle.

- **Mileage**  
  **Propósito:** Kilometraje con marca de tiempo (útil para trazabilidad del mantenimiento).  
  **Atributos:**  
  - value: int  
  - measuredAt: DateTime

---

##### **Events (Domain Events)**

- VehicleCheckedInEvent(vehicleId: UUID, occurredAt: DateTime)  
  **Propósito:** El vehículo ingresó al taller.
- VehicleCheckedOutEvent(vehicleId: UUID, occurredAt: DateTime)  
  **Propósito:** El vehículo salió del taller.

- MaintenanceRecordOpenedEvent(recordId: UUID, vehicleId: UUID, occurredAt: DateTime)  
  **Propósito:** Se abrió un registro de mantenimiento.
- MaintenanceTaskAddedEvent(recordId: UUID, taskId: UUID, recordable: bool, occurredAt: DateTime)  
  **Propósito:** Se añadió una tarea al mantenimiento.
- MaintenanceTaskCompletedEvent(recordId: UUID, taskId: UUID, occurredAt: DateTime)  
  **Propósito:** Se completó una tarea. Puede desencadenar verificación de cierre.
- MaintenanceTaskIssueReportedEvent(recordId: UUID, taskId: UUID, issue: string, occurredAt: DateTime)  
  **Propósito:** Se reportó un problema en una tarea.

- ServiceProgressUpdatedEvent(recordId: UUID, note: string, occurredAt: DateTime)  
  **Propósito:** Se actualizó el progreso del servicio.
- MaintenanceRecordApprovedEvent(recordId: UUID, occurredAt: DateTime)  
  **Propósito:** Se aprobó el registro (cumple políticas).
- MaintenanceRecordAmendedEvent(recordId: UUID, note: string, occurredAt: DateTime)  
  **Propósito:** Se anotó/ajustó el registro.
- MaintenanceCompletedEvent(recordId: UUID, occurredAt: DateTime)  
  **Propósito:** Se completó el mantenimiento (tareas registrables completas).
- ServiceReportGeneratedEvent(recordId: UUID, reportId: UUID, occurredAt: DateTime)  
  **Propósito:** Se generó el reporte del servicio (entregable).

---

##### **Services (Domain Interfaces)**

- interface DiagnosticService { DiagnosticReport run(UUID recordId); }  
  **Propósito:** Ejecuta diagnósticos técnicos y retorna un DiagnosticReport.  
  **Relaciones:**  
  - Colabora con MaintenanceRecord para persistir el informe.

- interface MaintenancePolicy { bool canAmend(UUID recordId); bool isTaskRecordable(TaskCategory category); }  
  **Propósito:** Reglas del dominio para determinar si es posible enmendar y cuándo una tarea es registrable.  
  **Relaciones:**  
  - Consultado por MaintenanceRecord durante amend(...) y addTask(...).

- interface PartsCatalogService { bool checkAvailability(string partNumber, int qty); }  
  **Propósito:** Verifica disponibilidad de repuestos (sin detalles de infraestructura aquí).  
  **Relaciones:**  
  - Usado por MaintenanceTask/MaintenanceRecord antes de confirmar PartUsage.

---

##### **Commands (visión global)**

Son records inmutables que expresan intención de cambio. No se documentan uno por uno en detalle por ser auxiliares; su rol global es activar métodos de agregados, validar políticas y emitir eventos.  
**Ejemplos:**  
- OpenMaintenanceRecord(recordId: UUID, vehicleId: UUID)  
- AddMaintenanceTask(recordId: UUID, description: string, category: TaskCategory, recordable: bool)  
- CompleteMaintenanceTask(recordId: UUID, taskId: UUID)  
- ReportMaintenanceTaskIssue(recordId: UUID, taskId: UUID, issue: string)  
- ApproveMaintenanceRecord(recordId: UUID) / AmendMaintenanceRecord(recordId: UUID, note: string)  
- CompleteMaintenance(recordId: UUID) / GenerateServiceReport(recordId: UUID)  
- CheckInVehicle(vehicleId: UUID) / CheckOutVehicle(vehicleId: UUID)

##### **Queries (visión global)**

Son records inmutables para lectura. No modifican estado; no ameritan diccionario individual.  
**Ejemplos:**  
- GetVehicleById(vehicleId: UUID)  
- GetMaintenanceRecordDetails(recordId: UUID)  
- ListMaintenanceRecords(vehicleId: UUID, from?: DateTime, to?: DateTime)  
- GetDiagnosticReport(recordId: UUID)

---

#### **2.6.1.2. Interface Layer**

Capa de presentación con Controllers, Resources y Assemblers (mapeo). Dado que son auxiliares, se describe su rol global y ejemplos principales.

- **Controllers** (endpoints): VehicleController, MaintenanceRecordController.  
  - Orquestan comandos/consultas y devuelven Resources.

- **Resources**  
  Ejemplos:  
  - VehicleResource { uuid vehicleId; string licensePlate; string brand; string model; int year; uuid ownerId; }  
  - OpenMaintenanceRecordResource { uuid vehicleId; }  
  - MaintenanceRecordResource { uuid recordId; uuid vehicleId; string status; DateTime openedAt; DateTime? closedAt; List<MaintenanceTaskResource> items; }  
  - MaintenanceTaskResource { uuid taskId; string description; string category; bool recordable; string status; List<PartUsageResource> parts; }  
  - DiagnosticReportResource { uuid reportId; uuid recordId; string summary; DateTime createdAt; }

- **Assemblers**  
  - Rol: mapear Resources ⇆ Commands/Entities, mantener consistencia del Ubiquitous Language.  
  - Ejemplos: VehicleAssembler, MaintenanceRecordAssembler, MaintenanceTaskAssembler, DiagnosticReportAssembler.

---

#### **2.6.1.3. Application Layer**

Implementa servicios de aplicación y manejadores de eventos.

- **Command Services**  
  - VehicleCommandService  
  - MaintenanceRecordCommandService

- **Query Services**  
  - VehicleQueryService → GetVehicleById  
  - MaintenanceRecordQueryService → GetMaintenanceRecordDetails, ListMaintenanceRecords  
  - DiagnosticReportQueryService → GetDiagnosticReport

- **Event Handlers**  
  - OnMaintenanceTaskCompleted → al completar todas las tareas registrables, dispara MaintenanceCompletedEvent  
  - OnMaintenanceCompleted → genera ServiceReportGeneratedEvent

- **ACL / Outbound**  
  - CatalogAcl (consulta piezas), NotificationsAcl  
  - DomainEventPublisher, ReportGenerator

---

#### **2.6.1.4. Infrastructure Layer**

Implementaciones concretas de persistencia y adaptadores externos. Se detallan a nivel de rol (no por clase) por ser soporte técnico.

- **Repositories (implementaciones de interfaces del dominio)**  
  - VehicleRepository : IVehicleRepository  
  - MaintenanceRecordRepository : IMaintenanceRecordRepository  
  - DiagnosticReportRepository : IDiagnosticReportRepository  
  - Rol: mapeo ORM, transacciones, UoW.

- **External Services Adapters**  
  - PartsCatalogAdapter (catálogo de repuestos)  
  - EmailNotificationAdapter (notificaciones)  
  - MessageBrokerPublisher (publicación de eventos)

---

#### **2.6.1.5. Bounded Context Software Architecture Component Level Diagrams**

#### **2.6.1.6. Bounded Context Software Architecture Code Level Diagrams**

##### **2.6.1.6.1. Bounded Context Domain Layer Class Diagrams**

##### **2.6.1.6.2. Bounded Context Database Design Diagram**
