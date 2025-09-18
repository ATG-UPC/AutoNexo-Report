### **2.6.2. Bounded Context: Trusting&Reputation**

#### **2.6.2.1. Domain Layer**

Este bounded context cubre la gestión de reseñas, calificaciones y el cálculo de la reputación o confianza, aplicable a distintos objetivos: propietarios (owner), talleres (workshop) o service orders. Consume eventos de otros bounded contexts para validar la elegibilidad y ajustar los puntajes de confianza.

---

### **Aggregates**

- **TrustProfile**  
  **Propósito:** Perfil de confianza/reputación asociado a un objetivo (owner, workshop o service order). Consolida puntajes y métricas.  
  **Atributos:**  
  - trustProfileId: UUID  
  - targetRef: TargetRef  
  - currentScore: ScoreValue  
  - ratingCount: int  
  - lastRecalculatedAt: DateTime  
  - breakdown: RatingBreakdown  
  **Métodos:**  
  - applyRating(rating: Rating)  
  - removeRating(ratingId: UUID)  
  - recalculate(scores: List<ScoreValue>, breakdowns: List<RatingBreakdown>)  
  **Relaciones:**  
  - 1 ⟶ * con Rating  
  - 1 ⟶ * con Review (opcional)

- **Review**  
  **Propósito:** Reseña textual asociada a una calificación. Puede editarse o eliminarse bajo políticas.  
  **Atributos:**  
  - reviewId: UUID  
  - targetRef: TargetRef  
  - authorId: UUID  
  - comment: Comment  
  - createdAt: DateTime  
  - editedAt: DateTime?  
  **Métodos:**  
  - edit(newComment: Comment)  
  - delete()  
  **Relaciones:**  
  - 1 ⟶ 1 con Rating

---

### **Entities**

- **Rating**  
  **Propósito:** Calificación numérica dirigida a un objetivo.  
  **Atributos:**  
  - ratingId: UUID  
  - targetRef: TargetRef  
  - authorId: UUID  
  - overall: ScoreValue  
  - breakdown: RatingBreakdown  
  - createdAt: DateTime  
  **Métodos:**  
  - updateBreakdown(newBreakdown: RatingBreakdown)  
  **Relaciones:**  
  - * ⟶ 1 con TrustProfile  
  - 0..1 ⟶ 1 con Review

- **TrustAdjustment**  
  **Propósito:** Ajuste al score por eventos (fraude, cancelación, no-show).  
  **Atributos:**  
  - adjustmentId: UUID  
  - targetRef: TargetRef  
  - delta: decimal  
  - reason: string  
  - occurredAt: DateTime  
  **Métodos:**  
  - describe()  
  **Relaciones:**  
  - * ⟶ 1 con TrustProfile

---

### **Value Objects**

- **TargetRef**  
  **Propósito:** Referencia polimórfica al objetivo calificado.  
  **Atributos:**  
  - targetType: TargetType (enum: Owner, Workshop, ServiceOrder)  
  - targetId: UUID

- **ScoreValue**  
  **Propósito:** Valor de puntuación acotado.  
  **Atributos:**  
  - value: decimal

- **RatingBreakdown**  
  **Propósito:** Desglose de puntuación por dimensiones.  
  **Atributos:**  
  - punctuality: ScoreValue  
  - quality: ScoreValue  
  - communication: ScoreValue  
  - transparency: ScoreValue

- **Comment**  
  **Propósito:** Texto validado de la reseña.  
  **Atributos:**  
  - text: string

---

### **Events (Domain Events)**

- ReviewSubmittedEvent(reviewId, targetRef, authorId, occurredAt)  
- ReviewEditedEvent(reviewId, targetRef, occurredAt)  
- ReviewDeletedEvent(reviewId, targetRef, occurredAt)  
- RatingSubmittedEvent(ratingId, targetRef, overall, occurredAt)  
- RatingUpdatedEvent(ratingId, targetRef, occurredAt)  
- TrustAdjustmentAppliedEvent(adjustmentId, targetRef, delta, occurredAt)  
- TrustScoreRecalculatedEvent(trustProfileId, targetRef, newScore, occurredAt)  
- OwnerRatedEvent(ownerId, ratingId, occurredAt)  
- WorkshopRatedEvent(workshopId, ratingId, occurredAt)  
- ServiceOrderRatedEvent(serviceOrderId, ratingId, occurredAt)

---

### **Services (Domain Interfaces)**

- ReputationCalculator  
  **Métodos:**  
  - compute(ratings, adjustments) → ScoreValue  
  - computeBreakdown(ratings) → RatingBreakdown  

- ReviewPolicy  
  **Métodos:**  
  - canEdit(reviewId, requesterId)  
  - canDelete(reviewId, requesterId)

- EligibilityPolicy  
  **Métodos:**  
  - canRate(targetRef, authorId)

---

### **Commands (visión global)**

Son records inmutables que expresan intención de cambio. Activan métodos de agregados, validan políticas y emiten eventos.  

Ejemplos:  
- SubmitReview(targetRef, authorId, comment)  
- EditReview(reviewId, authorId, newComment)  
- DeleteReview(reviewId, authorId)  
- SubmitRating(targetRef, authorId, overall, breakdown)  
- UpdateRating(ratingId, authorId, breakdown)  
- ApplyTrustAdjustment(targetRef, delta, reason)  
- RecalculateTrustScore(targetRef)

---

### **Queries (visión global)**

Son records inmutables de lectura. No modifican estado.  

Ejemplos:  
- GetTrustProfileByTarget(targetRef)  
- GetAverageScoreByTarget(targetRef)  
- ListReviewsByTarget(targetRef, from?, to?)  
- ListRatingsByTarget(targetRef, from?, to?)

---

#### **2.6.2.2. Interface Layer**

Capa de presentación con Controllers, Resources y Assemblers.

- Controllers: ReviewController, RatingController, TrustProfileController  
- Resources:  
  - SubmitReviewResource { targetType, targetId, comment }  
  - SubmitRatingResource { targetType, targetId, overall, RatingBreakdownResource }  
  - TrustProfileResource { trustProfileId, targetType, targetId, currentScore, ratingCount, lastRecalculatedAt, breakdown }  
  - ReviewResource { reviewId, targetType, targetId, authorId, comment, createdAt, editedAt }  
  - RatingResource { ratingId, targetType, targetId, authorId, overall, breakdown, createdAt }  
- Assemblers: ReviewAssembler, RatingAssembler, TrustProfileAssembler

---

#### **2.6.2.3. Application Layer**

Implementa servicios de aplicación y manejadores de eventos.

- Command Services: ReviewCommandService, RatingCommandService, TrustProfileCommandService  
- Query Services: TrustProfileQueryService, ReviewQueryService, RatingQueryService  
- Event Handlers:  
  - OnRatingSubmitted → aplica rating y recalcula TrustProfile  
  - OnReviewSubmitted → vincula review con rating  
  - OnTrustAdjustmentApplied → recalcula TrustProfile  
  - OnServiceCompleted (externo) → habilita EligibilityPolicy  
- ACL / Outbound: BookingAcl, IdentityAcl, MaintenanceAcl, DomainEventPublisher, ReputationAnalyticsExporter

---

#### **2.6.2.4. Infrastructure Layer**

Implementaciones de persistencia y adaptadores externos.

- Repositories: TrustProfileRepository, ReviewRepository, RatingRepository, TrustAdjustmentRepository  
- External Services Adapters: MessageBrokerPublisher, IdentityProviderAdapter, AnalyticsExportAdapter

---

#### **2.6.2.5. Bounded Context Software Architecture Component Level Diagrams**

(Se incluirá diagrama C4-Component posteriormente.)

---

#### **2.6.2.6. Bounded Context Software Architecture Code Level Diagrams**

##### **2.6.2.6.1. Bounded Context Domain Layer Class Diagrams**
(UML de aggregates, entities, value objects, services e interfaces de repositorio.)

##### **2.6.2.6.2. Bounded Context Database Design Diagram**
(Tablas sugeridas y relaciones PK/FK):  
- trust_profiles (trust_profile_id PK, target_type, target_id, current_score, rating_count, last_recalculated_at, avg_punctuality, avg_quality, avg_communication, avg_transparency, unique(target_type, target_id))  
- ratings (rating_id PK, target_type, target_id, author_id, overall, punctuality, quality, communication, transparency, created_at, FK(target_type,target_id) → trust_profiles)  
- reviews (review_id PK, target_type, target_id, author_id, comment, created_at, edited_at, FK(target_type,target_id) → trust_profiles)  
- trust_adjustments (adjustment_id PK, target_type, target_id, delta, reason, occurred_at, FK(target_type,target_id) → trust_profiles)
