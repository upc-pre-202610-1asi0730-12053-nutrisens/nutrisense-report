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

En esta sección, el equipo presenta y explica los diagramas que presentan un mayor detalle sobre la implementación de componentes para cada bounded context. Los diagramas de clases están organizados en dos nutrisenss: **FrontEnd** (Vue 3 + PrimeVue) y **Backend** (ASP.NET Core + C#), con un diagrama por cada uno de los 7 bounded contexts definidos en la arquitectura DDD de NutriSense. Las principales características consideradas en los diagramas son las siguientes.

**Arquitectura en capas DDD.** Cada bounded context sigue la estructura de capas `dofeature/diagrams`, `application`, `interfaces` e `infrastructure`. Las clases del dominio (aggregates, value objects, dofeature/diagrams events, repositories) residen en `dofeature/diagrams.model`; los application services coordinan los casos de uso en la capa `application`; los controllers, assemblers y resources conforman la capa `interfaces.REST` en el backend; y los API services, stores y componentes Vue conforman las capas `application.services`, `infrastructure.stores` y `presentation` en el frontend.

**Estereotipos UML.** Se utilizan los estereotipos `«Aggregate Root»`, `«Value Object»`, `«Dofeature/diagrams Event»`, `«Repository»`, `«Application Service»`, `«Controller»`, `«Assembler»`, `«Component»` y `«Service»` para distinguir el rol DDD de cada elemento.

**Visibilidad explícita.** Todos los miembros de cada clase incluyen su modificador de acceso: `+` (público), `-` (privado) y `#` (protegido).

**Relaciones tipificadas.** Los diagramas emplean composición (`*--`), agregación (`o--`), dependencia (`..>`), realización (`..|>`), herencia (`--|>`) y asociación con nombre, dirección y multiplicidad según corresponda.

### 4.7.1. Class Diagrams

#### FrontEnd

#### Identity & Access Management

![IAM Frontend](https://www.plantuml.com/plantuml/proxy?src=upc-pre-202610-1asi0730-12053-nutrisens/nutrisense-report/refs/heads/nutrisense-report/feature/diagrams/docs/class-diagrams/frontend/iam.puml)

#### Nutrition Tracking

![Nutrition Frontend](https://www.plantuml.com/plantuml/proxy?src=upc-pre-202610-1asi0730-12053-nutrisens/nutrisense-report/refs/heads/nutrisense-report/feature/diagrams/docs/class-diagrams/frontend/nutrition.puml)

#### Body & Health Metrics

![Body Metrics Frontend](https://www.plantuml.com/plantuml/proxy?src=upc-pre-202610-1asi0730-12053-nutrisens/nutrisense-report/refs/heads/nutrisense-report/feature/diagrams/docs/class-diagrams/frontend/body-metrics.puml)

#### Smart Recommendations

![Recommendations Frontend](https://www.plantuml.com/plantuml/proxy?src=upc-pre-202610-1asi0730-12053-nutrisens/nutrisense-report/refs/heads/nutrisense-report/feature/diagrams/docs/class-diagrams/frontend/recommendations.puml)

#### Activity & Wearable Sync

![Activity Frontend](https://www.plantuml.com/plantuml/proxy?src=upc-pre-202610-1asi0730-12053-nutrisens/nutrisense-report/refs/heads/nutrisense-report/feature/diagrams/docs/class-diagrams/frontend/activity.puml)

#### Analytics & Reporting

![Analytics Frontend](https://www.plantuml.com/plantuml/proxy?src=upc-pre-202610-1asi0730-12053-nutrisens/nutrisense-report/refs/heads/nutrisense-report/feature/diagrams/docs/class-diagrams/frontend/analytics.puml)

#### Subscriptions & Billing

![Billing Frontend](https://www.plantuml.com/plantuml/proxy?src=upc-pre-202610-1asi0730-12053-nutrisens/nutrisense-report/refs/heads/nutrisense-report/feature/diagrams/docs/class-diagrams/frontend/billing.puml)

#### Backend

#### Identity & Access Management

![IAM Backend](https://www.plantuml.com/plantuml/proxy?src=upc-pre-202610-1asi0730-12053-nutrisens/nutrisense-report/refs/heads/nutrisense-report/feature/diagrams/docs/class-diagrams/backend/iam.puml)

#### Nutrition Tracking

![Nutrition Backend](https://www.plantuml.com/plantuml/proxy?src=upc-pre-202610-1asi0730-12053-nutrisens/nutrisense-report/refs/heads/nutrisense-report/feature/diagrams/docs/class-diagrams/backend/nutrition.puml)

#### Body & Health Metrics

![Body Metrics Backend](https://www.plantuml.com/plantuml/proxy?src=upc-pre-202610-1asi0730-12053-nutrisens/nutrisense-report/refs/heads/nutrisense-report/feature/diagrams/docs/class-diagrams/backend/body-metrics.puml)

#### Smart Recommendations

![Recommendations Backend](https://www.plantuml.com/plantuml/proxy?src=upc-pre-202610-1asi0730-12053-nutrisens/nutrisense-report/refs/heads/nutrisense-report/feature/diagrams/docs/class-diagrams/backend/recommendations.puml)

#### Activity & Wearable Sync

![Activity Backend](https://www.plantuml.com/plantuml/proxy?src=upc-pre-202610-1asi0730-12053-nutrisens/nutrisense-report/refs/heads/nutrisense-report/feature/diagrams/docs/class-diagrams/backend/activity.puml)

#### Analytics & Reporting

![Analytics Backend](https://www.plantuml.com/plantuml/proxy?src=upc-pre-202610-1asi0730-12053-nutrisens/nutrisense-report/refs/heads/nutrisense-report/feature/diagrams/docs/class-diagrams/backend/analytics.puml)

#### Subscriptions & Billing

![Billing Backend](https://www.plantuml.com/plantuml/proxy?src=upc-pre-202610-1asi0730-12053-nutrisens/nutrisense-report/refs/heads/nutrisense-report/feature/diagrams/docs/class-diagrams/backend/billing.puml)

## 4.8. Database Design

Los diagramas de base de datos de NutriSense se presentan a nivel físico, detallando la estructura completa de cada tabla junto con sus columnas, tipos de datos nativos de PostgreSQL, restricciones de integridad referencial y relaciones entre entidades. El diseño está organizado por Bounded Context, de modo que cada contexto delimitado agrupa sus propias tablas con una nomenclatura consistente con el lenguaje ubicuo del dominio.

**Características principales consideradas en los diagramas**

**Primary Keys con UUID.** Todas las tablas utilizan `UUID` como tipo de dato para sus claves primarias. Esta decisión es consistente con los Value Objects de identidad definidos en el modelo de dominio (`UserId`, `ConsumptionLogId`, `HealthProfileId`, etc.) y permite la generación distribuida de identificadores en el application server sin depender de secuencias de base de datos. En el backend ASP.NET Core se emplea `Guid.NewGuid()` para la creación de estos identificadores antes de persistir cada aggregate.

**`user_accounts` como tabla central.** La tabla `user_accounts` del bounded context Identity & Access Management actúa como referencia central del sistema. Todos los demás bounded contexts referencian a esta tabla mediante la columna `user_id`, respetando el principio de que la identidad del usuario es gestionada exclusivamente por el contexto IAM. Las demás tablas no exponen ni replican atributos de identidad propios del usuario.

**Foreign Keys e integridad referencial.** Las relaciones entre tablas se establecen mediante `FOREIGN KEY`, aplicando `ON DELETE CASCADE` cuando los registros hijos no tienen sentido sin su padre (por ejemplo, `food_entries` respecto a `consumption_logs`). Las relaciones entre bounded contexts distintos referencian únicamente a `user_accounts.id`, evitando el acoplamiento estructural directo entre contextos.

**Value Objects aplanados como columnas.** Los Value Objects del modelo de dominio (como `Email`, `HashedPassword`, `WeightKg`, `BillingPeriod`, `NutritionalInfo`) se persisten como columnas escalares dentro de la tabla del aggregate al que pertenecen, dado que no tienen identidad propia y su ciclo de vida está ligado al aggregate root. Este patrón es el estándar para la persistencia de aggregates DDD en bases de datos relacionales, implementado en ASP.NET Core mediante Entity Framework Core con el soporte de `OwnsOne` y mapeo de columnas propias.

**Normalización en tercera forma normal (3NF).** El diseño evita la redundancia de datos. Las entidades subordinadas de un aggregate (como `food_entries` dentro de `consumption_logs`, o `weight_records` dentro de `health_profiles`) se persisten en tablas separadas con clave foránea hacia su aggregate root, reflejando la estructura `List<T>` del modelo de dominio.

**Columnas de auditoría.** Todas las tablas raíz de aggregate incluyen `created_at TIMESTAMP WITH TIME ZONE NOT NULL DEFAULT now()` y `updated_at TIMESTAMP WITH TIME ZONE NOT NULL DEFAULT now()` para trazabilidad temporal de cada registro. En el backend, Entity Framework Core actualiza automáticamente `updated_at` mediante interceptors en el `DbContext`.

**Tipos de datos PostgreSQL.** Se utilizan tipos nativos: `UUID` para identificadores, `DECIMAL(p,s)` para medidas con precisión decimal (peso, calorías, porcentajes de macros), `VARCHAR(n)` para cadenas con restricción de longitud conocida, `DATE` para fechas sin componente horario, `TIMESTAMP WITH TIME ZONE` para marcas de tiempo completas con zona horaria UTC, `INTEGER` para conteos enteros y `BOOLEAN` para flags binarios.

**CHECK constraints.** Se definen `CHECK` constraints sobre las columnas que representan enumeraciones del dominio (roles, tipos de actividad, objetivos, planes de suscripción, estados), codificando en la base de datos las mismas reglas de negocio que los value objects y enumeraciones del modelo de dominio, añadiendo una capa extra de integridad más allá de la validación de la aplicación.

**UNIQUE constraints.** Se define `UNIQUE (user_id, log_date)` en `consumption_logs` para garantizar que el aggregate `ConsumptionLog` sea único por usuario y día. Se define `UNIQUE (user_id)` en `health_profiles` y `subscriptions` para reflejar la cardinalidad 1:1 del dominio: un usuario tiene exactamente un perfil de salud y una suscripción activa.

**Índices.** Se definen índices sobre las columnas de búsqueda más frecuentes: `user_id` en todas las tablas asociadas a un usuario, `email` en `user_accounts`, y la combinación `(user_id, log_date)` en `consumption_logs`, optimizando las consultas del dashboard diario y los reportes de progreso.

## 4.8.1. Database Diagrams

El diagrama a continuación presenta el modelo entidad-relación físico general de NutriSense, consolidando las 11 tablas de los siete Bounded Contexts y sus relaciones de integridad referencial.

![NutriSense ERD](https://www.plantuml.com/plantuml/proxy?src=upc-pre-202610-1asi0730-12053-nutrisens/nutrisense-report/refs/heads/nutrisense-report/feature/diagrams/docs/database-diagrams/nutrisense-erd.puml)