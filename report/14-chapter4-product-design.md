# CAPÍTULO IV: PRODUCT DESIGN

## 4.1. Style Guidelines

### 4.1.1. General Style Guidelines

### 4.1.2. Web Style Guidelines

## 4.2. Information Architecture

### 4.2.1. Organization Systems

### 4.2.2. Labeling Systems

### 4.2.3. SEO Tags and Meta Tags

### 4.2.4. Searching Systems

### 4.2.5. Navigation Systems

## 4.3. Landing Page UI Design

### 4.3.1. Landing Page Wireframe

### 4.3.2. Landing Page Mock-up

## 4.4. Web Applications UX/UI Design

### 4.4.1. Web Applications Wireframes

### 4.4.2. Web Applications Wireflow Diagrams

### 4.4.2. Web Applications Mock-ups

### 4.4.3. Web Applications User Flow Diagrams

## 4.5. Web Applications Prototyping

## 4.6. Domain-Driven Software Architecture

### 4.6.1. Design-Level EventStorming

### 4.6.2. Software Architecture Context Diagram

### 4.6.3. Software Architecture Container Diagrams

### 4.6.4. Software Architecture Components Diagrams

## 4.7. Software Object-Oriented Design


Esta sección presenta los diagramas de clases UML que detallan la implementación de componentes para cada Bounded Context de NutriSense. Los diagramas se elaboraron con PlantUML siguiendo los principios de Domain-Driven Design (DDD) y la arquitectura en capas definida para el proyecto.
 
Para el **frontend** (Vue + PrimeVue) se aplica la estructura de carpetas DDD: `domain/model`, `application` (incluye stores de Pinia), `infrastructure` (clientes HTTP con Axios) y `presentation` (componentes Vue). Cada Bounded Context expone sus modelos de dominio como clases planas de JavaScript, su store en la capa `application`, su servicio HTTP en `infrastructure` y sus componentes en `presentation`.
 
Para el **backend** (ASP.NET Core + C#) se aplica la arquitectura en capas DDD: `Interfaces` (controllers REST), `Application` (command/query services), `Domain` (aggregates, entities, value objects, domain events, repository interfaces) e `Infrastructure` (implementaciones EF Core y clientes de APIs externas). Las interfaces de repositorio pertenecen al `Domain`; las implementaciones concretas, a `Infrastructure`.

### 4.7.1. Class Diagrams


### 4.7.1. Class Diagrams

**FrontEnd**

**Identity & Access Management**

![IAM Frontend](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/upc-pre-202610-1asi0730-12053-nutrisens/nutrisense-report/main/docs/class-diagrams/frontend/iam.puml)

**Nutrition**

![Nutrition Frontend](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/upc-pre-202610-1asi0730-12053-nutrisens/nutrisense-report/main/docs/class-diagrams/frontend/nutrition.puml)

**Body-metrics**

![Body-metrics Frontend](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/upc-pre-202610-1asi0730-12053-nutrisens/nutrisense-report/main/docs/class-diagrams/frontend/body-metrics.puml)

**Recommendations**

![Recommendations Frontend](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/upc-pre-202610-1asi0730-12053-nutrisens/nutrisense-report/main/docs/class-diagrams/frontend/recommendations.puml)

**Activity**

![Activity Frontend](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/upc-pre-202610-1asi0730-12053-nutrisens/nutrisense-report/main/docs/class-diagrams/frontend/activity.puml)

**Analytics**

![Analytics Frontend](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/upc-pre-202610-1asi0730-12053-nutrisens/nutrisense-report/main/docs/class-diagrams/frontend/analytics.puml)

**Billing**

![Activity Frontend](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/upc-pre-202610-1asi0730-12053-nutrisens/nutrisense-report/main/docs/class-diagrams/frontend/billing.puml)

**Backend**

**Identity & Access Management**

![IAM Backend](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/upc-pre-202610-1asi0730-12053-nutrisens/nutrisense-report/main/docs/class-diagrams/backend/iam.puml)

**Nutrition**

![Nutrition Backend](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/upc-pre-202610-1asi0730-12053-nutrisens/nutrisense-report/main/docs/class-diagrams/backend/nutrition.puml)

**Body-metrics**

![Body-metrics Backend](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/upc-pre-202610-1asi0730-12053-nutrisens/nutrisense-report/main/docs/class-diagrams/backend/body-metrics.puml)

**Recommendations**

![Recommendations Backend](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/upc-pre-202610-1asi0730-12053-nutrisens/nutrisense-report/main/docs/class-diagrams/backend/recommendations.puml)

**Activity**

![Activity Backend](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/upc-pre-202610-1asi0730-12053-nutrisens/nutrisense-report/main/docs/class-diagrams/backend/activity.puml)

**Analytics**

![Analytics Backend](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/upc-pre-202610-1asi0730-12053-nutrisens/nutrisense-report/main/docs/class-diagrams/backend/analytics.puml)

**Billing**

![Activity Backend](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/upc-pre-202610-1asi0730-12053-nutrisens/nutrisense-report/main/docs/class-diagrams/backend/billing.puml)

## 4.8. Database Design

Los diagramas de base de datos de NutriSense se presentan a nivel físico, detallando la estructura completa de cada tabla junto con sus columnas, tipos de datos nativos de PostgreSQL, restricciones de integridad referencial y relaciones entre entidades. El diseño está organizado por Bounded Context, de modo que cada contexto delimitado agrupa sus propias tablas con una nomenclatura consistente con el lenguaje ubicuo del dominio.

**Características principales consideradas en los diagramas**

**Primary Keys con UUID.** Todas las tablas utilizan `UUID` como tipo de dato para sus claves primarias. Esta decisión es consistente con los Value Objects de identidad definidos en el modelo de dominio (`UserId`, `ConsumptionLogId`, `HealthProfileId`, etc.) y permite la generación distribuida de identificadores en el application server sin depender de secuencias de base de datos. En el backend ASP.NET Core se emplea `Guid.NewGuid()` para la creación de estos identificadores antes de persistir cada aggregate.

**`user_accounts` como tabla central.** La tabla `user_accounts` del bounded context Identity & Access Management actúa como referencia central del sistema. Todos los demás bounded contexts referencian a esta tabla mediante la columna `user_id`, respetando el principio de que la identidad del usuario es gestionada exclusivamente por el contexto IAM. Las demás tablas no exponen ni replican atributos de identidad propios del usuario.

**Foreign Keys e integridad referencial.** Las relaciones entre tablas se establecen mediante `FOREIGN KEY`, aplicando `ON DELETE CASCADE` cuando los registros hijos no tienen sentido sin su padre (por ejemplo, `food_entries` respecto a `consumption_logs`). Las relaciones entre bounded contexts distintos referencian únicamente a `user_accounts.id`, evitando el acoplamiento estructural directo entre contextos.

**Value Objects aplanados como columnas.** Los Value Objects del modelo de dominio (como `Email`, `HashedPassword`, `WeightKg`, `BillingPeriod`, `NutritionalInfo`) se persisten como columnas escalares dentro de la tabla del aggregate al que pertenecen, dado que no tienen identidad propia y su ciclo de vida está ligado al aggregate root. Este patrón es el estándar para la persistencia de aggregates DDD en bases de datos relacionales, implementado en ASP.NET Core mediante Entity Framework Core con el soporte de `OwnsOne` y mapeo de columnas propias.

**Tipos de datos PostgreSQL.** Se utilizan tipos nativos: `UUID` para identificadores, `DECIMAL(p,s)` para medidas con precisión decimal (peso, calorías, porcentajes de macros), `VARCHAR(n)` para cadenas con restricción de longitud conocida, `DATE` para fechas sin componente horario, `TIMESTAMP WITH TIME ZONE` para marcas de tiempo completas con zona horaria UTC, `INTEGER` para conteos enteros y `BOOLEAN` para flags binarios.

**UNIQUE constraints.** Se define `UNIQUE (user_id, log_date)` en `consumption_logs` para garantizar que el aggregate `ConsumptionLog` sea único por usuario y día. Se define `UNIQUE (user_id)` en `health_profiles` y `subscriptions` para reflejar la cardinalidad 1:1 del dominio: un usuario tiene exactamente un perfil de salud y una suscripción activa.

**Índices.** Se definen índices sobre las columnas de búsqueda más frecuentes: `user_id` en todas las tablas asociadas a un usuario, `email` en `user_accounts`, y la combinación `(user_id, log_date)` en `consumption_logs`, optimizando las consultas del dashboard diario y los reportes de progreso.

## 4.8.1. Database Diagrams

El diagrama a continuación presenta el modelo entidad-relación físico de NutriSense, organizado por Bounded Context, consolidando las tablas de cada contexto y sus relaciones de integridad referencial.

**Identity & Access Management**

![IAM Database Diagram](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/upc-pre-202610-1asi0730-12053-nutrisens/nutrisense-report/refs/heads/feature/diagrams/docs/database-diagrams/iam.puml)

**Nutrition**

![Nutrition Database Diagram](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/upc-pre-202610-1asi0730-12053-nutrisens/nutrisense-report/refs/heads/feature/diagrams/docs/database-diagrams/nutrition.puml)

**Body-metrics**

![Body-metrics Database Diagram](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/upc-pre-202610-1asi0730-12053-nutrisens/nutrisense-report/refs/heads/feature/diagrams/docs/database-diagrams/body.puml)

**Recommendations**

![Recommendations Database Diagram](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/upc-pre-202610-1asi0730-12053-nutrisens/nutrisense-report/refs/heads/feature/diagrams/docs/database-diagrams/smart.puml)

**Activity**

![Activity Database Diagram](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/upc-pre-202610-1asi0730-12053-nutrisens/nutrisense-report/refs/heads/feature/diagrams/docs/database-diagrams/activity.puml)

**Analytics**

![Analytics Database Diagram](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/upc-pre-202610-1asi0730-12053-nutrisens/nutrisense-report/refs/heads/feature/diagrams/docs/database-diagrams/analytics.puml)

**Billing**

![Billing Database Diagram](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/upc-pre-202610-1asi0730-12053-nutrisens/nutrisense-report/refs/heads/feature/diagrams/docs/database-diagrams/billing.puml)