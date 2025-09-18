### **2.6.6. Bounded Context: Identity & Access Management (IAM)**

#### **2.6.6.1. Domain Layer**

Este bounded context cubre la gestión de identidades y accesos: registro, autenticación, autorización basada en roles y permisos, verificación de correo electrónico y recuperación de credenciales. Es transversal y provee mecanismos de seguridad para el resto de bounded contexts.

---

### **Aggregates**

- **UserAccount**  
  **Propósito:** Representa la cuenta de un usuario.  
  **Atributos:**  
  - userId: UUID  
  - email: Email  
  - passwordHash: PasswordHash  
  - status: UserStatus (Active, Inactive, Locked, Deleted, PendingVerification)  
  - roles: List<RoleAssignment>  
  - createdAt: DateTime  
  - lastLoginAt: DateTime?  
  **Métodos:**  
  - register(email: Email, passwordHash: PasswordHash)  
  - authenticate(candidateHash: PasswordHash)  
  - changePassword(newHash: PasswordHash)  
  - assignRole(role: Role) / revokeRole(role: Role)  
  - lock(reason: string) / deactivate() / activate()  
  - markEmailVerified()  
  **Relaciones:**  
  - 1 ⟶ * con RoleAssignment

- **Session**  
  **Propósito:** Gestiona una sesión autenticada y su token.  
  **Atributos:**  
  - sessionId: UUID  
  - userId: UUID  
  - token: Token  
  - issuedAt: DateTime  
  - expiresAt: DateTime  
  - status: SessionStatus (Active, Expired, Revoked)  
  **Métodos:**  
  - revoke()  
  - refresh(newExpiresAt: DateTime)

---

### **Entities**

- **Role**  
  **Propósito:** Agrupa permisos.  
  **Atributos:**  
  - roleId: UUID  
  - name: string  
  - permissions: List<Permission>

- **RoleAssignment**  
  **Propósito:** Vincula un usuario con un rol.  
  **Atributos:**  
  - assignmentId: UUID  
  - userId: UUID  
  - roleId: UUID  
  - assignedAt: DateTime

- **Permission**  
  **Propósito:** Define acciones permitidas sobre recursos.  
  **Atributos:**  
  - permissionId: UUID  
  - name: string  
  - description: string

- **VerificationRequest**  
  **Propósito:** Gestiona el proceso de verificación de email.  
  **Atributos:**  
  - verificationId: UUID  
  - userId: UUID  
  - codeOrToken: string  
  - sentAt: DateTime  
  - expiresAt: DateTime  
  - status: VerificationStatus (Pending, Verified, Expired)  
  **Métodos:**  
  - verify(codeOrToken: string)  
  - expire()

- **RecoveryRequest**  
  **Propósito:** Gestiona la recuperación de contraseña.  
  **Atributos:**  
  - recoveryId: UUID  
  - userId: UUID  
  - codeOrToken: string  
  - requestedAt: DateTime  
  - expiresAt: DateTime  
  - status: RecoveryStatus (Pending, Completed, Expired, Revoked)  
  **Métodos:**  
  - complete(newHash: PasswordHash)  
  - expire()  
  - revoke(reason: string)

---

### **Value Objects**

- **Email** – valida formato y unicidad.  
- **PasswordHash** – encapsula el hash y su algoritmo.  
- **Token** – valor opaco emitido para sesiones.  
- **OtpCode** – valor de un solo uso con longitud y política de expiración.

---

### **Events (Domain Events)**

- UserRegisteredEvent(userId, email, occurredAt)  
  **Propósito:** Se registró un usuario y quedó pendiente de verificación si aplica.
- EmailVerificationRequestedEvent(userId, verificationId, occurredAt)  
  **Propósito:** Se generó una solicitud de verificación y se envió el código o enlace.
- EmailVerifiedEvent(userId, verificationId, occurredAt)  
  **Propósito:** El correo fue verificado y la cuenta queda habilitada según política.
- EmailVerificationExpiredEvent(verificationId, occurredAt)  
  **Propósito:** La solicitud de verificación caducó.
- UserAuthenticatedEvent(userId, sessionId, occurredAt)  
  **Propósito:** Inicio de sesión exitoso.
- UserAuthenticationFailedEvent(email, reason, occurredAt)  
  **Propósito:** Intento fallido de autenticación.
- SessionStartedEvent(sessionId, userId, occurredAt)  
  **Propósito:** Se emitió un token de sesión.
- SessionRevokedEvent(sessionId, userId, occurredAt)  
  **Propósito:** Se revocó la sesión.
- PasswordResetRequestedEvent(userId, recoveryId, occurredAt)  
  **Propósito:** Se solicitó recuperación de contraseña y se envió código o enlace.
- PasswordResetCompletedEvent(userId, recoveryId, occurredAt)  
  **Propósito:** Se cambió la contraseña correctamente.
- PasswordResetExpiredEvent(recoveryId, occurredAt)  
  **Propósito:** La solicitud de recuperación expiró sin completarse.
- UserPasswordChangedEvent(userId, occurredAt)  
  **Propósito:** Se actualizó la contraseña desde una sesión autenticada.
- UserLockedEvent(userId, reason, occurredAt)  
  **Propósito:** La cuenta fue bloqueada por política.
- RoleAssignedEvent(userId, roleId, occurredAt) / RoleRevokedEvent(userId, roleId, occurredAt)  
  **Propósito:** Cambió la matriz de permisos efectivos.

---

### **Services (Domain Interfaces)**

- **AuthenticationService**  
  **Métodos:** authenticate(email, password) → Token; refreshToken(token) → Token; revokeToken(token).  
  **Propósito:** Autenticación y ciclo de vida de sesiones.

- **AuthorizationService**  
  **Métodos:** hasPermission(userId, permission) → bool; getRoles(userId) → List<Role>.  
  **Propósito:** Evaluación de permisos basada en roles.

- **EmailVerificationService**  
  **Métodos:** request(userId) → VerificationRequest; verify(verificationId, codeOrToken) → bool.  
  **Propósito:** Orquesta el flujo de verificación de correo.

- **CredentialRecoveryService**  
  **Métodos:** request(userIdOrEmail) → RecoveryRequest; reset(recoveryId, codeOrToken, newHash) → bool.  
  **Propósito:** Orquesta el flujo de recuperación de contraseña.

- **PasswordPolicy**  
  **Métodos:** validate(rawPassword) → bool.  
  **Propósito:** Reglas de complejidad y caducidad.

- **OtpPolicy**  
  **Métodos:** generate() → OtpCode; validate(codeOrToken, scope) → bool; ttl(scope) → Duration.  
  **Propósito:** Política de códigos y tokens de un solo uso.

---

### **Commands (visión global)**

Son records inmutables que expresan intención de cambio. Activan métodos de agregados, validan políticas y emiten eventos.

**Ejemplos:**  
- RegisterUser(email: string, password: string)  
- AuthenticateUser(email: string, password: string)  
- StartSession(userId: UUID)  
- RevokeSession(sessionId: UUID)  
- RequestEmailVerification(userId: UUID)  
- VerifyEmail(verificationId: UUID, codeOrToken: string)  
- RequestPasswordReset(userIdOrEmail: string)  
- CompletePasswordReset(recoveryId: UUID, codeOrToken: string, newPassword: string)  
- ChangePassword(userId: UUID, currentPassword: string, newPassword: string)  
- AssignRole(userId: UUID, roleId: UUID) / RevokeRole(userId: UUID, roleId: UUID)  
- LockUser(userId: UUID, reason: string) / ActivateUser(userId: UUID)

---

### **Queries (visión global)**

Consultas inmutables orientadas a lectura.

**Ejemplos:**  
- GetUserById(userId: UUID)  
- GetUserByEmail(email: string)  
- GetUserRoles(userId: UUID)  
- GetActiveSessions(userId: UUID)  
- GetVerificationStatus(userId: UUID)  
- GetRecoveryStatus(recoveryId: UUID)

---

#### **2.6.6.2. Interface Layer**

Capa de exposición de APIs y DTOs.

- **Controllers:** AuthController, UserController, RoleController, VerificationController, RecoveryController  
- **Resources:**  
  - UserResource { userId, email, status, roles, createdAt, lastLoginAt }  
  - SessionResource { sessionId, userId, token, expiresAt, status }  
  - RoleResource { roleId, name, permissions }  
  - VerificationResource { verificationId, userId, status, expiresAt }  
  - RecoveryResource { recoveryId, userId, status, expiresAt }  
- **Assemblers:** UserAssembler, SessionAssembler, RoleAssembler, VerificationAssembler, RecoveryAssembler

---

#### **2.6.6.3. Application Layer**

Implementa casos de uso y orquestación con servicios externos.

- **Command Services:**  
  - UserCommandService  
  - SessionCommandService  
  - RoleCommandService  
  - VerificationCommandService  
  - RecoveryCommandService

- **Query Services:**  
  - UserQueryService  
  - RoleQueryService  
  - SessionQueryService  
  - VerificationQueryService  
  - RecoveryQueryService

- **Event Handlers:**  
  - OnUserRegistered → crea VerificationRequest y dispara EmailVerificationRequestedEvent.  
  - OnEmailVerified → cambia estado de usuario a Active o mantiene según política.  
  - OnPasswordResetRequested → genera RecoveryRequest y envía notificación.  
  - OnPasswordResetCompleted → invalida sesiones previas y registra UserPasswordChangedEvent.  
  - OnUserPasswordChanged → revoca sesiones activas excepto la actual según política.  
  - OnAuthenticationFailedThresholdReached → bloquea cuenta y emite UserLockedEvent.

- **ACLs / Integraciones:**  
  - NotificationAcl (envío de emails/SMS para verificación y recuperación).  
  - ExternalIdProviderAcl (SSO/OAuth).  
  - TokenProviderAcl (emisión/validación de JWT o similar).  
  - AuditTrailAcl (registro de auditoría de seguridad).

---

#### **2.6.6.4. Infrastructure Layer**

Implementaciones concretas de repositorios y adaptadores.

- **Repositories:**  
  - UserRepository : IUserRepository  
  - SessionRepository : ISessionRepository  
  - RoleRepository : IRoleRepository  
  - VerificationRepository : IVerificationRepository  
  - RecoveryRepository : IRecoveryRepository

- **External Adapters:**  
  - EmailProviderAdapter  
  - SmsProviderAdapter  
  - TokenProviderAdapter  
  - MessageBrokerPublisher  
  - AuditLogAdapter

---

#### **2.6.6.5. Bounded Context Software Architecture Component Level Diagrams**

Se incluirá diagrama C4-Component posteriormente.

---

#### **2.6.6.6. Bounded Context Software Architecture Code Level Diagrams**

##### **2.6.6.6.1. Bounded Context Domain Layer Class Diagrams**

UML de aggregates, entities, value objects, services e interfaces de repositorio.

##### **2.6.6.6.2. Bounded Context Database Design Diagram**

Tablas sugeridas y PK/FK:  
- users (user_id PK, email UNIQUE, password_hash, status, created_at, last_login_at)  
- sessions (session_id PK, user_id FK, token, issued_at, expires_at, status)  
- roles (role_id PK, name UNIQUE, description)  
- user_roles (assignment_id PK, user_id FK, role_id FK, assigned_at)  
- permissions (permission_id PK, name UNIQUE, description)  
- role_permissions (role_id FK, permission_id FK)  
- verifications (verification_id PK, user_id FK, code_or_token, sent_at, expires_at, status)  
- recoveries (recovery_id PK, user_id FK, code_or_token, requested_at, expires_at, status)

---
