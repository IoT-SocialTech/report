<div align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" alt="logo"  width="20%"/>

**Universidad Peruana de Ciencias Aplicadas** <br>
**Ingeniería de Software** <br>
**Ciclo 2024-2** <br>

<h4>Desarrollo de Soluciones IoT</h4>

**Sección:** WS71
**Profesor:** Angel Augusto Velasquez Nuñez

<h3>INFORME DEL TRABAJO FINAL</h3>

**Startup:** SocialTech

**Producto:** MIAM (Monitoreo Inteligente para Adultos Mayores)

**Integrantes:**

Achamizo Huamani, Jean Carlos <br>
Aliaga Trevejo, Lucía Guadalupe <br>
Raymundo Guevara, Rodrigo Alejandro <br>
Sagastegui Rodriguez, Luis Jesús <br>
Siancas Reategui, Luis Alberto <br>
Trujillo Lopez, Luis Alberto <br>

**Setiembre, 2024**

</div>

---

# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de la modificación |
| ------- | ----- | ----- | ------------------------------ |
|   1.0     |   06/09/2024   |  Achamizo Huamani Jean Carlos,  Aliaga Trevejo Lucía Guadalupe, Raymundo Guevara Rodrigo Alejandro, Siancas Reategui Luis Alberto, Trujillo Lopez Luis Alberto  |   Se añadieron los elementos correspondientes al entregable de la TB1 (capítulos 1 al 4)|
|   1.1   |   25/09/2024   |  Aliaga Trevejo Lucía Guadalupe |   Se añadieron y corrigieron los elementos correspondientes en el capítulo de Needfinding |
|   1.2     |   25/09/2024   |  Achamizo Huamani Jean Carlos, Siancas Reategui Luis Alberto |   Se añadieron y corrigieron los elementos correspondientes en el capítulo strategic level software design, como la descripcion y las imagenes de cada diagrama. |
|   1.3     |   26/09/2024   |  Achamizo Huamani Jean Carlos|   Se corrigieron los elementos correspondientes del Lean UX Process, los apartados de Lean UX Assumptions y Lean UX Hypothesis Statements |
| 1.3     | 27/09/2024  | Raymundo Guevara Rodrigo Alejandro                                                                               | Se añadieron los mockups y wireframes en la sección de diseño de interfaz.                                                     |
| 1.4     | 27/09/2024  | Sagastegui Rodriguez Luis Jesus                                                                                      | Se añadieron los cuadros de planificación del sprint en la sección de metodología ágil.                                        |
| 1.5     | 27/09/2024  | Trujillo Lopez Luis Alberto                                                                                      | Se completaron los cuadros de planificación del sprint con detalles adicionales y se validaron las fechas y tareas.            |
| 2.0    | 31/10/2024  | Aliaga Trevejo Lucía Guadalupe                                                                   | Se agregó el capítulo correspondiente al Sprint 2            |


# Project Report Collaboration Insights

URL del repositorio: 
<a href="https://github.com/IoT-SocialTech/iot-report"> https://github.com/IoT-SocialTech/iot-report </a>

**TB1**

El equipo colaboró activamente en el repositorio de GitHub para la elaboración del informe, realizando un total de 38 commits para el primer entregable.

![Insights TB1](./assets/insights-tb1.PNG)

El uso de ramas paralelas permitió a los miembros del equipo trabajar simultáneamente en diferentes secciones del informe, integrando cambios de manera eficiente y reduciendo conflictos. Este enfoque colaborativo garantizó que todos los miembros contribuyeran al desarrollo del informe de manera equilibrada.

![Network TB1](./assets/network-tb1.PNG)

**TP1**

Para la segunda entrega, el equipo logró un total de 78 commits en todas las ramas.

![Insights TP1](./assets/insights-tp1.PNG)

Se continuó el trabajo en ramas paralelas para integrar las correcciones y nuevos elementos. Gracias a este enfoque se evitaron conflictos entre las nuevas versiones del reporte.

![Network TP1](./assets/network-tp1.PNG)

**TB2**

Para la tercera entrega se adicionan los commits en los repositorios de los productos: 

*Web Application*

![Web App Network Graph](assets/network-web.PNG)

*Mobile Application*

![Web App Pulse](assets/pulse-mobile.PNG)

![Mobile App Network Graph](assets/network-mobile.PNG)

*Embedded Application*

![Embedded App Pulse](assets/pulse-embedded.PNG)

![Embedded App Network Graph](assets/network-embedded.PNG)

*Edge API*

![Edge API Network Graph](assets/network-edgeapi.PNG)

*Cloud API*

![Cloud API Pulse](assets/pulse-cloudapi.PNG)

![Cloud API Network Graph](assets/network-cloudapi.PNG)


Se continuó el trabajo en ramas paralelas para integrar las correcciones y nuevos elementos. Gracias a este enfoque se evitaron conflictos entre las nuevas versiones del reporte.


---

# Contenido

## Tabla de Contenidos

- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Contenido](#contenido)
  - [Tabla de Contenidos](#tabla-de-contenidos)
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)
- [Capítulo IV: Strategic-Level Software Design](#capítulo-iv-strategic-level-software-design)
  - [4.1. Strategic-Level Attribute-Driven Design](#41-strategic-level-attribute-driven-design)
    - [4.1.1. Event Storming](#411-event-storming)
      - [4.1.1.1. Candidate Context Discovery](#4111-candidate-context-discovery)
      - [4.1.1.2 Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
      - [4.1.1.3 Bounded Context Canvases](#4113-bounded-context-canvases)
    - [4.1.2. Context Mapping](#412-context-mapping)
      - [Proceso para Crear el Context Mapping y Análisis de Alternativas](#proceso-para-crear-el-context-mapping-y-análisis-de-alternativas)
        - [1. Pasos para Crear el Context Mapping](#1-pasos-para-crear-el-context-mapping)
          - [1.1. Identificación de los Bounded Contexts](#11-identificación-de-los-bounded-contexts)
          - [1.2. Identificación de Relaciones Iniciales](#12-identificación-de-relaciones-iniciales)
        - [2. Análisis de Alternativas y Preguntas Clave](#2-análisis-de-alternativas-y-preguntas-clave)
          - [2.1. ¿Qué pasaría si movemos este capability a otro bounded context?](#21-qué-pasaría-si-movemos-este-capability-a-otro-bounded-context)
          - [2.2. ¿Qué pasaría si descomponemos este capability y movemos uno de los sub-capabilities a otro bounded context?](#22-qué-pasaría-si-descomponemos-este-capability-y-movemos-uno-de-los-sub-capabilities-a-otro-bounded-context)
          - [2.3. ¿Qué pasaría si partimos el bounded context en múltiples bounded contexts?](#23-qué-pasaría-si-partimos-el-bounded-context-en-múltiples-bounded-contexts)
          - [2.4. ¿Qué pasaría si tomamos este capability de estos 3 contexts y lo usamos para formar un nuevo context?](#24-qué-pasaría-si-tomamos-este-capability-de-estos-3-contexts-y-lo-usamos-para-formar-un-nuevo-context)
          - [2.5. ¿Qué pasaría si duplicamos una funcionalidad para romper la dependencia?](#25-qué-pasaría-si-duplicamos-una-funcionalidad-para-romper-la-dependencia)
          - [2.6. ¿Qué pasaría si creamos un shared service para reducir la duplicación entre múltiples bounded contexts?](#26-qué-pasaría-si-creamos-un-shared-service-para-reducir-la-duplicación-entre-múltiples-bounded-contexts)
          - [2.7. ¿Qué pasaría si aislamos los core capabilities y movemos los otros a un context aparte?](#27-qué-pasaría-si-aislamos-los-core-capabilities-y-movemos-los-otros-a-un-context-aparte)
        - [3. Alternativa Recomendada de Context Mapping](#3-alternativa-recomendada-de-context-mapping)
        - [4. Patrones de Relaciones Sugeridos](#4-patrones-de-relaciones-sugeridos)
    - [4.1.3. Software Architecture](#413-software-architecture)
      - [4.1.3.1. Software Architecture System Landscape Diagram](#4131-software-architecture-system-landscape-diagram)
      - [4.1.3.2. Software Architecture Context Level Diagrams](#4132-software-architecture-context-level-diagrams)
      - [4.1.3.3. Software Architecture Container Level Diagrams](#4133-software-architecture-container-level-diagrams)
      - [4.1.3..4. Software Architecture Deployment Diagrams](#4134-software-architecture-deployment-diagrams)
  - [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
  - [4.2.1. Bounded Context: Device Context](#421-bounded-context-device-context)
    - [4.2.1.1. Domain Layer](#4211-domain-layer)
      - [Entities](#entities)
      - [Value Objects](#value-objects)
      - [Domain Services](#domain-services)
      - [Aggregates y Aggregate Root](#aggregates-y-aggregate-root)
      - [Repositories (Interfaces)](#repositories-interfaces)
    - [4.2.1.2. Interface Layer](#4212-interface-layer)
      - [Controllers](#controllers)
    - [4.2.1.3. Application Layer](#4213-application-layer)
      - [Command Handlers](#command-handlers)
      - [Event Handlers](#event-handlers)
      - [Query Handlers](#query-handlers)
    - [4.2.1.4. Infrastructure Layer](#4214-infrastructure-layer)
      - [Repositories (Implementaciones)](#repositories-implementaciones)
    - [4.2.1.6. Bounded Context Software Architecture Component Level Diagrams](#4216-bounded-context-software-architecture-component-level-diagrams)
      - [Components (Edge API):](#components-edge-api)
    - [4.2.1.7. Bounded Context Software Architecture Code Level Diagrams](#4217-bounded-context-software-architecture-code-level-diagrams)
      - [4.2.1.7.1. Bounded Context Domain Layer Class Diagrams](#42171-bounded-context-domain-layer-class-diagrams)
      - [4.2.1.7.2. Bounded Context Database Design Diagram](#42172-bounded-context-database-design-diagram)
  - [4.2.2. Bounded Context: Edge Context](#422-bounded-context-edge-context)
    - [4.2.2.1. Domain Layer](#4221-domain-layer)
      - [Entities](#entities-1)
      - [Value Objects](#value-objects-1)
      - [Domain Services](#domain-services-1)
      - [Aggregates y Aggregate Root](#aggregates-y-aggregate-root-1)
      - [Repositories (Interfaces)](#repositories-interfaces-1)
    - [4.2.2.2. Interface Layer](#4222-interface-layer)
      - [Controllers](#controllers-1)
    - [4.2.2.3. Application Layer](#4223-application-layer)
      - [Command Handlers](#command-handlers-1)
      - [Event Handlers](#event-handlers-1)
      - [Query Handlers](#query-handlers-1)
    - [4.2.2.4. Infrastructure Layer](#4224-infrastructure-layer)
      - [Repositories (Implementaciones)](#repositories-implementaciones-1)
    - [4.2.2.6. Bounded Context Software Architecture Component Level Diagrams](#4226-bounded-context-software-architecture-component-level-diagrams)
      - [Components (Edge API):](#components-edge-api-1)
    - [4.2.2.7. Bounded Context Software Architecture Code Level Diagrams](#4227-bounded-context-software-architecture-code-level-diagrams)
      - [4.2.2.7.1. Bounded Context Domain Layer Class Diagrams](#42271-bounded-context-domain-layer-class-diagrams)
      - [4.2.2.7.2. Bounded Context Database Design Diagram](#42272-bounded-context-database-design-diagram)
  - [](#)
  - [4.2.3. Bounded Context: Notification Context](#423-bounded-context-notification-context)
    - [4.2.3.1. Domain Layer](#4231-domain-layer)
      - [Entities](#entities-2)
      - [Value Objects](#value-objects-2)
      - [Domain Services](#domain-services-2)
      - [Aggregates y Aggregate Root](#aggregates-y-aggregate-root-2)
      - [Repositories (Interfaces)](#repositories-interfaces-2)
    - [4.2.3.2. Interface Layer](#4232-interface-layer)
      - [Controllers](#controllers-2)
    - [4.2.3.3. Application Layer](#4233-application-layer)
      - [Command Handlers](#command-handlers-2)
      - [Event Handlers](#event-handlers-2)
      - [Query Handlers](#query-handlers-2)
    - [4.2.3.4. Infrastructure Layer](#4234-infrastructure-layer)
      - [Repositories (Implementaciones)](#repositories-implementaciones-2)
    - [4.2.3.6. Bounded Context Software Architecture Component Level Diagrams](#4236-bounded-context-software-architecture-component-level-diagrams)
      - [Components (Web API):](#components-web-api)
    - [4.2.3.7. Bounded Context Software Architecture Code Level Diagrams](#4237-bounded-context-software-architecture-code-level-diagrams)
      - [4.2.3.7.1. Bounded Context Domain Layer Class Diagrams](#42371-bounded-context-domain-layer-class-diagrams)
      - [4.2.3.7.2. Bounded Context Database Design Diagram](#42372-bounded-context-database-design-diagram)
  - [](#-1)
  - [4.2.4. Bounded Context: Metrics Context](#424-bounded-context-metrics-context)
    - [4.2.4.1. Domain Layer](#4241-domain-layer)
      - [Entities](#entities-3)
      - [Value Objects](#value-objects-3)
      - [Domain Services](#domain-services-3)
      - [Aggregates y Aggregate Root](#aggregates-y-aggregate-root-3)
      - [Repositories (Interfaces)](#repositories-interfaces-3)
    - [4.2.4.2. Interface Layer](#4242-interface-layer)
      - [Controllers](#controllers-3)
    - [4.2.4.3. Application Layer](#4243-application-layer)
      - [Command Handlers](#command-handlers-3)
      - [Event Handlers](#event-handlers-3)
      - [Query Handlers](#query-handlers-3)
    - [4.2.4.4. Infrastructure Layer](#4244-infrastructure-layer)
      - [Repositories (Implementaciones)](#repositories-implementaciones-3)
    - [4.2.4.6. Bounded Context Software Architecture Component Level Diagrams](#4246-bounded-context-software-architecture-component-level-diagrams)
      - [Components (Edge API):](#components-edge-api-2)
    - [4.2.4.7. Bounded Context Software Architecture Code Level Diagrams](#4247-bounded-context-software-architecture-code-level-diagrams)
      - [4.2.4.7.1. Bounded Context Domain Layer Class Diagrams](#42471-bounded-context-domain-layer-class-diagrams)
      - [4.2.4.7.2. Bounded Context Database Design Diagram](#42472-bounded-context-database-design-diagram)
  - [4.2.5. Bounded Context: Payment Context](#425-bounded-context-payment-context)
    - [4.2.5.1. Domain Layer](#4251-domain-layer)
      - [Entities](#entities-4)
      - [Value Objects](#value-objects-4)
      - [Domain Services](#domain-services-4)
      - [Aggregates y Aggregate Root](#aggregates-y-aggregate-root-4)
      - [Repositories (Interfaces)](#repositories-interfaces-4)
    - [4.2.5.2. Interface Layer](#4252-interface-layer)
      - [Controllers](#controllers-4)
    - [4.2.5.3. Application Layer](#4253-application-layer)
      - [Command Handlers](#command-handlers-4)
      - [Event Handlers](#event-handlers-4)
      - [Query Handlers](#query-handlers-4)
    - [4.2.5.4. Infrastructure Layer](#4254-infrastructure-layer)
      - [Repositories (Implementaciones)](#repositories-implementaciones-4)
    - [4.2.5.6. Bounded Context Software Architecture Component Level Diagrams](#4256-bounded-context-software-architecture-component-level-diagrams)
      - [Components (Web API):](#components-web-api-1)
    - [4.2.5.7. Bounded Context Software Architecture Code Level Diagrams](#4257-bounded-context-software-architecture-code-level-diagrams)
      - [4.2.5.7.1. Bounded Context Domain Layer Class Diagrams](#42571-bounded-context-domain-layer-class-diagrams)
      - [4.2.5.7.2. Bounded Context Database Design Diagram](#42572-bounded-context-database-design-diagram)
  - [](#-2)
  - [4.2.6. Bounded Context: Configuration Context](#426-bounded-context-configuration-context)
    - [4.2.6.1. Domain Layer](#4261-domain-layer)
      - [Entities](#entities-5)
      - [Value Objects](#value-objects-5)
      - [Domain Services](#domain-services-5)
      - [Aggregates y Aggregate Root](#aggregates-y-aggregate-root-5)
      - [Repositories (Interfaces)](#repositories-interfaces-5)
    - [4.2.6.2. Interface Layer](#4262-interface-layer)
      - [Controllers](#controllers-5)
    - [4.2.6.3. Application Layer](#4263-application-layer)
      - [Command Handlers](#command-handlers-5)
      - [Event Handlers](#event-handlers-5)
      - [Query Handlers](#query-handlers-5)
    - [4.2.6.4. Infrastructure Layer](#4264-infrastructure-layer)
      - [Repositories (Implementaciones)](#repositories-implementaciones-5)
    - [4.2.6.6. Bounded Context Software Architecture Component Level Diagrams](#4266-bounded-context-software-architecture-component-level-diagrams)
      - [Components (Edge API):](#components-edge-api-3)
    - [4.2.6.7. Bounded Context Software Architecture Code Level Diagrams](#4267-bounded-context-software-architecture-code-level-diagrams)
      - [4.2.6.7.1. Bounded Context Domain Layer Class Diagrams](#42671-bounded-context-domain-layer-class-diagrams)
      - [4.2.6.7.2. Bounded Context Database Design Diagram](#42672-bounded-context-database-design-diagram)
  - [4.2.7. Bounded Context: Account Context](#427-bounded-context-account-context)
    - [4.2.7.1. Domain Layer](#4271-domain-layer)
      - [Entities](#entities-6)
      - [Value Objects](#value-objects-6)
      - [Domain Services](#domain-services-6)
      - [Aggregates y Aggregate Root](#aggregates-y-aggregate-root-6)
      - [Repositories (Interfaces)](#repositories-interfaces-6)
    - [4.2.7.2. Interface Layer](#4272-interface-layer)
      - [Controllers](#controllers-6)
    - [4.2.7.3. Application Layer](#4273-application-layer)
      - [Command Handlers](#command-handlers-6)
      - [Event Handlers](#event-handlers-6)
      - [Query Handlers](#query-handlers-6)
    - [4.2.7.4. Infrastructure Layer](#4274-infrastructure-layer)
      - [Repositories (Implementaciones)](#repositories-implementaciones-6)
    - [4.2.7.6. Bounded Context Software Architecture Component Level Diagrams](#4276-bounded-context-software-architecture-component-level-diagrams)
      - [Components (Web API):](#components-web-api-2)
    - [4.2.7.7. Bounded Context Software Architecture Code Level Diagrams](#4277-bounded-context-software-architecture-code-level-diagrams)
      - [4.2.7.7.1. Bounded Context Domain Layer Class Diagrams](#42771-bounded-context-domain-layer-class-diagrams)
      - [4.2.7.7.2. Bounded Context Database Design Diagram](#42772-bounded-context-database-design-diagram)
- [Capítulo V:Solution UI/UX Design](#capítulo-vsolution-uiux-design)
  - [5.1. Strategic-Level Attribute-Driven Design](#51-strategic-level-attribute-driven-design)
    - [5.1.1. General Style Guidelines](#511-general-style-guidelines)
      - [5.1.1.1. Branding](#5111-branding)
      - [5.1.1.2. Logotipo](#5112-logotipo)
      - [5.1.1.3. Typography](#5113-typography)
      - [5.1.1.4. Colors](#5114-colors)
      - [5.1.1.5. Spacing](#5115-spacing)
    - [5.1.2. Web, Mobile and IoT Style Guidelines](#512-web-mobile-and-iot-style-guidelines)
    - [5.1.2.1. Web Style Guidelines](#5121-web-style-guidelines)
    - [5.1.2.2. Mobile Style Guidelines](#5122-mobile-style-guidelines)
  - [5.2. Information Architecture](#52-information-architecture)
    - [5.2.1. Organization Systems.](#521-organization-systems)
    - [5.2.2. Labeling Systems.](#522-labeling-systems)
    - [5.2.3. SEO Tags and Meta Tags.](#523-seo-tags-and-meta-tags)
    - [5.2.4. Navigation Systems.](#524-navigation-systems)
    - [5.2.5. Navigation Systems.](#525-navigation-systems)
    - [5.2.3. SEO Tags and Meta Tags](#523-seo-tags-and-meta-tags-1)
    - [5.2.4. Searching Systems.](#524-searching-systems)
    - [5.2.5. Navigation Systems.](#525-navigation-systems-1)
  - [5.3. Landing Page UI Design](#53-landing-page-ui-design)
    - [5.3.1. Landing Page Wireframe](#531-landing-page-wireframe)
    - [5.3.2. Landing Page Mock-up](#532-landing-page-mock-up)
  - [5.4. Applications UX/UI Design](#54-applications-uxui-design)
    - [5.4.1. Applications Wireframes](#541-applications-wireframes)
      - [5.4.1.1. Web Application Wireframes](#5411-web-application-wireframes)
      - [5.4.1.2. Mobile Application Wireframes](#5412-mobile-application-wireframes)
    - [5.4.2. Applications Wireflow Diagrams](#542-applications-wireflow-diagrams)
      - [5.4.2.1. Web Application Wireflow Diagrams](#5421-web-application-wireflow-diagrams)
      - [5.4.2.2. Mobile Application Wireflow Diagrams](#5422-mobile-application-wireflow-diagrams)
    - [5.4.3. Applications Mock-ups](#543-applications-mock-ups)
      - [5.4.3.1. Web Application Mock-ups](#5431-web-application-mock-ups)
      - [5.4.3.2. Mobile Application Mock-ups](#5432-mobile-application-mock-ups)
    - [5.4.4. Applications User Flow Diagrams](#544-applications-user-flow-diagrams)
      - [5.4.4.1. Web Application User Flow Diagrams](#5441-web-application-user-flow-diagrams)
      - [5.4.4.2. Mobile Application User Flow Diagrams](#5442-mobile-application-user-flow-diagrams)
  - [5.5 Applications Prototyping](#55-applications-prototyping)
- [Capítulo VI: Product Implementation, Validation \& Deployment](#capítulo-vi-product-implementation-validation--deployment)
  - [6.1. Software Configuration Management](#61-software-configuration-management)
    - [6.1.1. Software Development Environment Configuration](#611-software-development-environment-configuration)
    - [6.1.2. Source Code Management](#612-source-code-management)
    - [6.1.3. Source Code Style Guide \& Conventions](#613-source-code-style-guide--conventions)
    - [6.1.4. Software Deployment Configuration](#614-software-deployment-configuration)
    - [6.2.1. Sprint 1](#621-sprint-1)
      - [6.2.1.1. Sprint Planning 1](#6211-sprint-planning-1)
      - [6.2.1.2. Sprint Backlog 1](#6212-sprint-backlog-1)
      - [6.2.1.3. Development Evidence for Sprint Review](#6213-development-evidence-for-sprint-review)
      - [6.2.1.4. Testing Suite Evidence for Sprint Review](#6214-testing-suite-evidence-for-sprint-review)
      - [6.2.1.5. Execution Evidence for Sprint Review](#6215-execution-evidence-for-sprint-review)
      - [6.2.1.6. Services Documentation Evidence for Sprint Review](#6216-services-documentation-evidence-for-sprint-review)
      - [6.2.1.7. Software Deployment Evidence for Sprint Review](#6217-software-deployment-evidence-for-sprint-review)
      - [6.2.1.8. Team Collaboration Insights during Sprint](#6218-team-collaboration-insights-during-sprint)
    - [6.2.2. Sprint 2](#622-sprint-2)
      - [6.2.2.1. Sprint Planning 2](#6221-sprint-planning-2)
      - [6.2.2.2. Sprint Backlog 2](#6222-sprint-backlog-2)
      - [6.2.2.3. Development Evidence for Sprint Review](#6223-development-evidence-for-sprint-review)
      - [6.2.2.4. Testing Suite Evidence for Sprint Review](#6224-testing-suite-evidence-for-sprint-review)
      - [6.2.2.5. Execution Evidence for Sprint Review](#6225-execution-evidence-for-sprint-review)
      - [6.2.2.6. Services Documentation Evidence for Sprint Review](#6226-services-documentation-evidence-for-sprint-review)
      - [6.2.2.7. Software Deployment Evidence for Sprint Review](#6227-software-deployment-evidence-for-sprint-review)
      - [6.2.2.8. Team Collaboration Insights during Sprint](#6228-team-collaboration-insights-during-sprint)
      - [6.3 Validation Interviews.](#63-validation-interviews)
      - [6.3.1. Diseño de Entrevistas.](#631-diseño-de-entrevistas)
      - [6.3.2. Registro de Entrevistas.](#632-registro-de-entrevistas)
      - [6.3.3. Evaluaciones según heurísticas.](#633-evaluaciones-según-heurísticas)
      - [6.4. Video About-the-Product.](#64-video-about-the-product)
- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)
  - [Videos de Exposición](#videos-de-exposición)
  - [Diagrama C4 MIAM](#diagrama-c4-miam)
    - [6.2.2. Sprint 3](#622-sprint-3)
      - [6.2.2.1. Sprint Planning 3](#6221-sprint-planning-3)
      - [6.2.2.2. Sprint Backlog 3](#6222-sprint-backlog-3)




---

# Student Outcome
| Criterio específico                                              | Acciones realizadas                                                                                                                   | Conclusión                                                                                                                       |
|------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------|
| Trabaja en equipo para proporcionar liderazgo en forma conjunta  | **Jean Carlos Achamizo Huamani** <br> TB1: <br> Implementé inicialmente los apartados de assumptions e hipótesis, estructurando las bases del proyecto y facilitando la comprensión común de los objetivos. Esta acción ayudó a definir un enfoque claro y unificado para el equipo, asegurando que todos los miembros estuvieran alineados desde el principio. <br> TP1: <br> Corregí los assumptions originales, añadiendo cinco nuevos y elaboré hipótesis detalladas utilizando la plantilla proporcionada. Esto permitió al equipo validar los objetivos del proyecto y adaptar las actividades según los requerimientos específicos, lo que mejoró la toma de decisiones conjunta y la planificación estratégica. <br> TB2: <br> Colaboré en el desarrollo de funcionalidades del backend, optimizando las llamadas de API y estructurando la lógica de negocio. En el frontend, implementé componentes interactivos para mejorar la experiencia de usuario en la landing page, lo que reforzó el liderazgo conjunto y permitió una visión integral del proyecto. <br><br> **Luis Alberto Trujillo Lopez** <br> TB1: <br> Añadí las páginas web de los competidores y sus logos, proporcionando una base inicial para el análisis competitivo. Esto facilitó la comprensión del panorama del mercado y permitió al equipo definir estrategias de manera más informada. <br> TP1: <br> Expandí esta información agregando descripciones detalladas de cada competidor y reorganizando las imágenes del Event Storming en secciones claras con descripciones para cada fase. Al hacer esto, ayudé a clarificar los roles y responsabilidades dentro del equipo, promoviendo un liderazgo compartido y un trabajo en equipo más cohesivo. <br> TB2: <br> Participé en la implementación del diseño de la landing page y colaboré en el backend configurando los endpoints necesarios para la funcionalidad de los dispositivos, fortaleciendo el liderazgo compartido y garantizando un trabajo en equipo cohesivo. <br><br> **Lucía Guadalupe Aliaga Trevejo** <br> TB1: <br> Realicé los primeros resúmenes de entrevistas y la descripción inicial de los User Personas. Facilitando las discusiones del equipo, me aseguré de que todas las opiniones fueran consideradas, promoviendo un entorno de trabajo colaborativo. <br> TP1: <br> Mejoré los enlaces y resúmenes de entrevistas, incluyendo detalles sobre marcas y personalidad del entrevistado. Corregí la descripción de los User Personas basándome en el análisis de entrevistas. Esto ayudó a alinear la visión del equipo con las necesidades reales de los usuarios, fortaleciendo el liderazgo conjunto en la toma de decisiones. <br> TB2: <br> Apoyé en el frontend en la creación de formularios interactivos en la landing page y colaboré en el device, asegurando que la comunicación entre frontend y backend fuera eficiente, facilitando un entorno de liderazgo compartido. <br><br> **Luis Alberto Siancas Reategui** <br> TB1: <br> Comencé el análisis inicial de entrevistas, incluyendo detalles generales sobre los entrevistados y tecnologías utilizadas. Esto proporcionó al equipo una comprensión básica del perfil de usuario. <br> TP1: <br> Añadí detalles específicos sobre las tecnologías utilizadas por los entrevistados, sus marcas preferidas y las influencias que afectan su toma de decisiones. Esta información fue clave para que el equipo pudiera tomar decisiones informadas y desarrollar estrategias que respondieran efectivamente a las necesidades identificadas. <br> TB2: <br> Desarrollé configuraciones adicionales en el backend para mejorar la gestión de dispositivos y ayudé en el frontend para asegurar una estructura visual consistente en la landing page, promoviendo la colaboración y el liderazgo cohesivo. <br><br> **Rodrigo Alejandro Raymundo Guevara** <br> TB1: <br> Definí las primeras User Stories y Epics, estableciendo la base del backlog del proyecto. Esto permitió al equipo organizar el trabajo en tareas claras y priorizadas, promoviendo una coordinación efectiva. <br> TP1: <br> Unifiqué el cuadro de User Stories y Epics, mejoré la redacción de las User Stories y sus escenarios en español, e incluí las User Stories de la landing page. Esto ayudó a estructurar mejor el trabajo del equipo, asegurando que todos estuvieran alineados con las prioridades del proyecto y facilitando un liderazgo compartido. <br> TB2: <br> Realicé ajustes en las User Stories para incluir nuevos requisitos del device y aseguré que la lógica de backend fuera compatible con el frontend en la landing page, promoviendo la sinergia del equipo y el liderazgo compartido. <br><br> **Luis Jesús Sagastegui Rodríguez** <br> TB1: <br> Empecé la definición de las reglas de negocio básicas para los aggregates y el diseño inicial de la base de datos. Esto proporcionó una base técnica para la planificación del proyecto. <br> TP1: <br> Añadí reglas de negocio detalladas para los aggregates, elaboré diagramas de clases y de base de datos. Estas acciones facilitaron una mejor comprensión técnica del proyecto, permitiendo al equipo tomar decisiones técnicas de manera más colaborativa y eficiente. <br> TB2: <br> Aporté en la creación y ajuste de las reglas de negocio en el backend, permitiendo una comunicación fluida con el frontend para la funcionalidad del device y desarrollé el diseño de base de datos para la landing page, fortaleciendo la colaboración y el liderazgo técnico compartido. <br><br> | **Conclusión TB1:** El equipo estableció una base sólida para el proyecto al definir claramente las responsabilidades y objetivos iniciales, promoviendo un liderazgo conjunto y una toma de decisiones participativa. Se crearon los apartados iniciales y se definieron roles, lo que facilitó el trabajo en equipo. <br><br> **Conclusión TP1:** El equipo mejoró la planificación y ejecución del proyecto al revisar y corregir los elementos iniciales. Cada miembro contribuyó a profundizar y perfeccionar sus responsabilidades, permitiendo una mayor coordinación y efectividad en la consecución de los objetivos. Todos los roles estuvieron alineados, lo que reforzó el liderazgo conjunto y la cohesión del equipo. <br><br> **Conclusión TB2:** El equipo trabajó de manera integrada en diversas áreas del proyecto (frontend, backend, device y landing page), fortaleciendo el liderazgo compartido. Esta colaboración permitió que todos los miembros estuvieran alineados con los objetivos generales, facilitando una visión integral del desarrollo y una toma de decisiones en conjunto.  |
| Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos | **Jean Carlos Achamizo Huamani** <br> TB1: <br> Facilitó la creación de un entorno inclusivo al asegurar que todas las voces fueran escuchadas durante las discusiones del equipo. Definí metas claras y organicé la planificación de tareas iniciales. Esto ayudó a establecer una base sólida para que el equipo trabajara de manera coordinada hacia objetivos comunes. <br> TP1: <br> Corregí y expandí los assumptions, añadiendo cinco nuevos y elaborando hipótesis más específicas para guiar el trabajo del equipo. Estas acciones permitieron establecer objetivos más precisos y alineados con la visión del proyecto, facilitando un entorno colaborativo donde todos entendieron claramente su rol. <br> TB2: <br> Promoví un entorno inclusivo para asegurar que todos los miembros contribuyeran en el frontend y backend, colaborando en la planificación de tareas para garantizar que todos comprendieran sus responsabilidades y los objetivos comunes. <br><br> **Luis Alberto Trujillo Lopez** <br> TB1: <br> Promoví la inclusión en el equipo al proporcionar la base del análisis competitivo con las páginas web y logos de competidores, facilitando la planificación inicial del análisis. Esto ayudó al equipo a comprender mejor el entorno competitivo y a definir metas realistas. <br> TP1: <br> Añadí descripciones detalladas de los competidores, mejorando la calidad del análisis y facilitando la colaboración del equipo en la definición de metas estratégicas. Al clarificar las diferencias y similitudes con la competencia, ayudé a que el equipo pudiera enfocar sus esfuerzos en áreas de oportunidad específicas. <br> TB2: <br> Definí metas en conjunto con el equipo, dividiendo las tareas para frontend, backend y device, asegurando que se cumplieran los objetivos en tiempo, facilitando una planificación coordinada. <br><br> **Lucía Guadalupe Aliaga Trevejo** <br> TB1: <br> Garantizé que las tareas y objetivos fueran distribuidos equitativamente. Realicé los resúmenes iniciales de entrevistas y la descripción de User Personas, maximizando el potencial de cada miembro del equipo. Esto permitió al equipo tener un punto de partida claro para entender las necesidades de los usuarios. <br> TP1: <br> Mejoré los resúmenes de entrevistas, incluyendo detalles importantes, y consolidé la User Task Matrix en un solo cuadro, describiendo tareas comunes y corrigiendo el User Journey Mapping. Estas acciones permitieron al equipo tener una visión más clara de las tareas y su importancia, facilitando la planificación y el cumplimiento de objetivos. <br> TB2: <br> Apoyé en la organización y planificación de las tareas, asignando objetivos claros en cada área (device y frontend) para asegurar que el equipo mantuviera un enfoque inclusivo y colaborativo. <br><br> **Luis Alberto Siancas Reategui** <br> TB1: <br> Supervisé el progreso del equipo en relación con las metas establecidas y facilité la planificación de tareas iniciales basadas en el análisis preliminar de entrevistas. Esto aseguró que el equipo estuviera alineado y enfocado en las actividades prioritarias. <br> TP1: <br> Completé el análisis de entrevistas, detallando las tecnologías utilizadas, marcas preferidas e influencias de los entrevistados. Esta información fue crucial para ajustar las metas y estrategias del equipo, asegurando que las tareas planificadas respondieran a las expectativas de los usuarios y cumplieran con los objetivos del proyecto. <br> TB2: <br> Colaboré en la planificación de tareas para el backend y device, asegurando que los miembros del equipo entendieran sus roles y responsabilidades, fortaleciendo la colaboración y cumplimiento de objetivos. <br><br> **Rodrigo Alejandro Raymundo Guevara** <br> TB1: <br> Colaboré en la creación de un ambiente de trabajo respetuoso y colaborativo, donde cada miembro pudo contribuir con sus ideas en la planificación de tareas iniciales y la redacción de User Stories. Esto permitió al equipo organizar el trabajo de manera efectiva desde el inicio. <br> TP1: <br> Mejoré la redacción de las User Stories y sus criterios de aceptación, prioricé las User Stories de la landing page y unifiqué las Epics y User Stories. Estas acciones ayudaron al equipo a tener una dirección clara y a organizar las tareas de manera que todos entendieran qué se esperaba de cada uno, facilitando el cumplimiento de objetivos. <br> TB2: <br> Apoyé en la organización y división de tareas entre frontend y backend, estableciendo objetivos claros para la landing page y device, manteniendo al equipo alineado en un entorno inclusivo. <br><br> **Luis Jesús Sagastegui Rodríguez** <br> TB1: <br> Implementé prácticas colaborativas e inclusivas, asegurando que todos los miembros estuvieran enfocados en las tareas iniciales establecidas y facilitando la planificación de objetivos. Esto permitió una mejor organización y claridad en el trabajo del equipo. <br> TP1: <br> Añadí reglas detalladas de los aggregates, diagramas de clases y estructura de la base de datos, organizando mejor la planificación de tareas y el cumplimiento de objetivos técnicos del proyecto. Estas acciones proporcionaron un marco técnico sólido para el equipo, permitiendo una colaboración más efectiva en el desarrollo de la solución. <br> TB2: <br> Participé en la planificación de tareas del backend y colaboré en la integración de las reglas de negocio con el frontend, manteniendo un entorno colaborativo y alineado en las metas y objetivos de la landing page y device. <br><br> | **Conclusión TB1:** El equipo trabajó de manera efectiva en la planificación inicial del proyecto, estableciendo metas claras y asegurando la participación equitativa de todos los miembros. Cada miembro contribuyó a la creación de un entorno colaborativo e inclusivo, estableciendo las bases para un trabajo coordinado y enfocado en objetivos comunes. <br><br> **Conclusión TP1:** Se consolidó la colaboración y la inclusión, revisando y mejorando los elementos iniciales y planificando de manera detallada las tareas. Cada miembro del equipo ajustó sus responsabilidades y contribuciones en función de los datos y análisis obtenidos, lo que permitió una mejor planificación y ejecución de los objetivos establecidos. <br><br> **Conclusión TB2:** En esta fase, el equipo trabajó de manera colaborativa en frontend, backend, device y landing page, estableciendo metas y tareas claras para cada área. Se promovió un entorno inclusivo que facilitó el cumplimiento de los objetivos y permitió una planificación efectiva, asegurando que cada miembro contribuyera de manera significativa a la consecución de los objetivos del proyecto. |

---

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup


### 1.1.2. Perfiles de integrantes del equipo


<table>
    <tr>
        <td>Perfil</td>
        <td>Foto</td>
    </tr>
    <tr>
        <td><b>Nombre:</b> Achamizo Huamani, Jean Carlos<br>
            <b>Carrera:</b> Ingenieria de Software <br>
        <b>Descripcion:</b> Como estudiante de Ingeniería de Software en la Universidad UPC, mi entusiasmo por el aprendizaje constante me impulsa a buscar siempre nuevas maneras de perfeccionar mis habilidades académicas y aplicarlas en situaciones prácticas, también poseo aptitudes en comunicación asertiva y escucha activa. Reconozco la importancia de una comunicación clara y efectiva en cualquier proyecto de software, y cuento con la capacidad de escuchar de manera atenta para comprender las necesidades y expectativas de los clientes y colegas de equipo.  
        <td><img src="./assets/JeanFoto.jpg" alt="Jean Achamizo" width="600"></td>
    </tr>
    <tr>
        <td><b>Nombre:</b> Aliaga Trevejo, Lucía Guadalupe <br>
            <b>Carrera:</b> Ingenieria de Software <br>
        <b>Descripcion:</b> Soy una estudiante de Ingeniería de Software, actualmente interesada en el desarrollo web front y back end. Me gusta crear interfaces intuitivas y llamativas para mejorar la experiencia de usuario. Me considero una persona responsable y centrada. Mis habilidades blandas incluyen comunicación efectiva, trabajo en equipo, liderazgo y adaptabilidad. Aspiro a contribuir de manera significativa en proyectos innovadores para seguir expandiendo mis conocimientos técnicos y capacidades. 
        <td><img src="./assets/Lucia-Aliaga.jpg" alt="Lucía Aliaga"  width="600"></td>
    </tr>
    <tr>
        <td><b>Nombre:</b> Raymundo Guevara, Rodrigo Alejandro <br>
            <b>Carrera:</b> Ingenieria de Software <br>
        <b>Descripcion:</b> Soy estudiante de la carrera de Ingeniería de Software y un apasionado de la tecnología. Me gusta descubrir nuevas formas de solucionar problemas con diversos frameworks y algoritmos. Me considero una persona responsable y empática. Me gusta mucho trabajar en equipo y ayudar a mis compañeros 
        <td><img src="./assets/RodrigoFoto.jpg" alt="Rodrigo Raymundo"  width="600"></td>
    </tr>
    <tr>
        <td><b>Nombre:</b> Siancas Reategui, Luis Alberto<br>
            <b>Carrera:</b> Ingenieria de Software <br>
        <b>Descripcion:</b> Soy estudiante de la carrera de Ingeniería de Software enfocado en el desarrollo backend. Me gusta crear API’s las cuales uso para mis proyectos, por otro lado, me gusta realizar el despliegue de mis aplicaciones así como también usar diferentes diseños de arquitectura para que mi aplicación tenga un funcionamiento estable y tenga alta disponibilidad. En cuanto a mis habilidades blandas, soy empático y tengo escucha activa, esto me ayuda en gran parte a la hora de trabajar en equipos ya que facilita la comunicación y por ende los resultados son mejores. 
        <td><img src="./assets/luis_siancas.png" alt="Luis Siancas" width="600"></td>
    </tr>
    <tr>
        <td><b>Nombre:</b> Trujillo Lopez, Luis Alberto<br>
            <b>Carrera:</b> Ingenieria de Software <br>
        <b>Descripcion:</b> Soy un estudiante de Ingeniería de Software interesado en las tecnologías de aprendizaje autónomo. Me gusta desarrollar en un entorno web páginas que se vean llamativas y que tengan múltiples funcionalidades enfocándome en la experiencia del usuario y en la creación de API’s. Poseo algunas habilidades que me permiten relacionarme en equipo, soy una persona responsable, con un enfoque centrado, comunicación asertiva, liderazgo y adaptabilidad. Mi meta es contribuir en el desarrollo de proyectos que me permitan mejorar y encontrar nuevas habilidades para adquirir mayores conocimientos laboral y profesionalmente.
        <td><img src="./assets/Luis-Trujillo.png" alt="Luis Trujillo" width="600"></td>
    </tr>
    <tr>
        <td><b>Nombre:</b> Sagastegui Rodriguez, Luis Jesus<br>
            <b>Carrera:</b> Ingenieria de Software <br>
        <b>Descripcion:</b> Soy un estudiante de la carrera de ingenieria de Software y me apasiona mucho lo que hago. Siempre estoy interesado en aprender nuevas tecnologias y lenguajes de programacion. Me gusta ver proyectos de las demas personas y poder compartir ideas. Me considero una persona responsable y muy amable que siempre le gusta ayudar a las demas personas. Siempre trato de dar lo mejor de mi para poder destacar.
           <td><img src="./assets/Jesus-Sagastegui.jpg" alt="Luis Trujillo" width="600"></td>
    </tr>
   <table>

## 1.2. Solution Profile

### 1.2.1 Antecedentes y problemática

Los adultos mayores representan una población vulnerable no solo a enfermedades relacionadas con el envejecimiento, sino también a lesiones que pueden deteriorar significativamente su calidad de vida (Dorri, Zabolinezhad, & Sattari, 2023). De acuerdo con la Organización Mundial de la Salud, las caídas son la principal causa de lesiones y mortalidad en personas mayores de 75 años (Giulianelli et al., 2017). Ante este panorama, es esencial proporcionarles un entorno seguro que contribuya a prevenir discapacidades y complicaciones en su salud (Dorri, Zabolinezhad, & Sattari, 2023).

A continuación, se presenta un análisis detallado de esta problemática empleando la metodología ‘5W2H’.

**Who** <br>
Los adultos mayores en Perú, especialmente aquellos que viven en casas de reposo o en sus propios domicilios, representan una población vulnerable debido a las limitaciones propias del envejecimiento, como la pérdida de reflejos y del equilibrio (Suárez et al., 2020). Por otro lado, los cuidadores, tanto formales (como enfermeros y técnicos) como informales (familiares), son los responsables de brindar atención diaria. Estos cuidadores a menudo enfrentan desafíos adicionales como las exigencias de su trabajo y los recursos limitados. Esta situación puede dificultar la supervisión y la atención constante que los adultos mayores necesitan.

**What** <br>
La principal problemática es la alta incidencia de caídas entre los adultos mayores, que no solo provoca lesiones físicas como fracturas y traumatismos, sino que también tiene consecuencias psicológicas como el miedo a caer de nuevo, lo cual reduce aún más su movilidad e independencia. Para los cuidadores, cada caída significa un aumento significativo en la carga de trabajo, implicando cuidados adicionales.

**Where** <br>
Las caídas ocurren principalmente en las casas de reposo y domicilios de los adultos mayores. En las casas de reposo, la falta de personal y la infraestructura deficiente pueden contribuir al riesgo de caídas. En los domicilios, los adultos mayores a menudo se enfrentan a condiciones peligrosas como escaleras sin barandas, pisos resbaladizos, y la ausencia de dispositivos de asistencia como andadores o bastones.

**When** <br>
Las caídas pueden suceder en cualquier momento del día, pero son más comunes durante actividades cotidianas como levantarse de la cama, caminar al baño, o asearse. Las noches y madrugadas son momentos críticos debido a la disminución de la visibilidad y la menor capacidad de reacción tanto de los adultos mayores como de los cuidadores.

**Why** <br>
Las caídas suelen suceder por una combinación de factores, como la fragilidad del adulto mayor y una supervisión insuficiente. 

**How** <br>
Los adultos mayores pueden perder el equilibrio al realizar actividades diarias sin la asistencia adecuada. Los cuidadores no son capaces de realizar supervisión constante debido a que tienen varios pacientes a cargo, en especial en las casas de reposo, lo que puede llevar a descuidos involuntarios, aumentando el riesgo de caídas.

**How Much** <br>
Uno de cada tres adultos mayores de 65 años sufre caídas, de las cuales el 68% resultan en lesiones, incluyendo fracturas. Además, el 60% de las caídas ocurren en el hogar, 30% en sitios públicos y 10% en instituciones de salud, teniendo consecuencias físicas y psicológicas para el adulto mayor (Ministerio de Salud, 2018). 


### 1.2.2 Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

El estado actual de la seguridad para adultos mayores se ha centrado principalmente en productos como botones de emergencia y sensores de movimiento básicos. Sin embargo, estos productos no logran ofrecer una supervisión continua ni adaptarse a los entornos específicos en los que viven los adultos mayores. Esto deja una brecha crítica en la prevención de caídas, lo que resulta en lesiones físicas y una reducción en la calidad de vida de los adultos mayores. Los cuidadores se enfrentan a la dificultad de supervisar constantemente y gestionar los riesgos sin herramientas adecuadas para ser más proactivos.

Nuestro producto abordará esta brecha mediante el desarrollo de un sistema innovador de monitoreo basado en IoT, diseñado para ofrecer una supervisión continua y alertas en tiempo real adaptadas a los entornos específicos de cada adulto mayor. Nuestro enfoque inicial serán los cuidadores y dueños de casas de reposo, con el objetivo de mejorar la seguridad y la calidad de vida de los adultos mayores.

Sabremos que tenemos éxito cuando veamos una reducción en los incidentes de caídas, una mayor satisfacción de los cuidadores y una mejora significativa en la calidad de vida de los adultos mayores.


#### 1.2.2.2. Lean UX Assumptions
En esta sección se formulan las hipótesis basadas en las suposiciones previas, estableciendo relaciones claras entre las características del producto, los comportamientos esperados de los usuarios y los resultados de negocio deseados. Con puntos 

1. Business Assumptions:
Asumimos que los dueños de casas de reposo y cuidadores profesionales requieren una solución integrada y confiable para monitorear la salud y seguridad de los adultos mayores, reduciendo el riesgo de incidentes y mejorando la eficiencia en el cuidado diario.
2. Business Outcome Assumptions:
 Asumimos que los dueños de casas de reposo y cuidadores medirán el éxito de nuestro servicio por su capacidad para reducir en un 30% los incidentes de caídas y mejorar la respuesta a emergencias en un 50% durante el primer año de implementación.
3. User Assumptions:
 Asumimos que los cuidadores profesionales y los administradores de casas de reposo estarán dispuestos a adoptar nuevas tecnologías si estas les permiten monitorear de manera proactiva la salud de los residentes y reducir la carga laboral asociada a la supervisión manual.
4. User Outcome Assumptions:
 Asumimos que los cuidadores y administradores de casas de reposo experimentarán una mejora en la satisfacción laboral, una disminución del 20% en las tareas repetitivas de supervisión y un aumento del 40% en la percepción de seguridad por parte de los familiares de los residentes durante el primer semestre de uso del sistema.
5. Feature Assumptions:
 Asumimos que la combinación de sensores de movimiento y signos vitales, junto con alertas en tiempo real personalizables según el estado de salud de cada residente, será la característica clave que diferenciará nuestra solución de la competencia y captará al menos el 25% del mercado objetivo en el primer año.

#### 1.2.2.3. Lean UX Hypothesis Statements
En esta sección se presentan las suposiciones clave que sustentan el diseño y desarrollo del producto. Estas suposiciones se basan en el entendimiento actual de las necesidades y comportamientos de los usuarios, así como en las condiciones del mercado. Identificar y documentar estas suposiciones permite al equipo alinearse en torno a expectativas comunes y establecer una base sólida para el proceso de validación a través de pruebas e iteraciones futuras.

**Hypothesis Statements 1:**
Creemos que al implementar un sistema de monitoreo integrado, los dueños de casas de reposo y cuidadores verán una reducción del 30% en los incidentes de caídas y una mejora del 20% en la eficiencia operativa dentro de los primeros seis meses. Sabremos que esto es cierto cuando se observe una disminución documentada en los reportes de incidentes y una mejora en la satisfacción y eficiencia reportada por los usuarios.

**Hypothesis Statements 2:**
Creemos que al utilizar nuestro sistema, los dueños de casas de reposo y cuidadores notarán una disminución del 30% en los incidentes de caídas y un 50% de mejora en el tiempo de respuesta a emergencias dentro del primer año. Sabremos que hemos tenido éxito cuando se registren mejoras documentadas en los reportes de incidentes y tiempos de respuesta durante este período.

**Hypothesis Statements 3:**
Creemos que al ofrecer una solución tecnológica que facilite la supervisión proactiva, al menos el 70% de los cuidadores profesionales y administradores adoptarán nuestro sistema en los primeros seis meses. Sabremos que esto es cierto cuando el 70% de los usuarios registrados utilicen activamente la solución y reporten una disminución significativa en la carga laboral.

**Hypothesis Statements 4:**
Creemos que al usar nuestro sistema de monitoreo, los cuidadores y administradores de casas de reposo reportarán una mejora del 30% en su satisfacción laboral y una disminución del 20% en las tareas de supervisión repetitivas dentro del primer semestre. Sabremos que hemos tenido éxito cuando los resultados de encuestas de satisfacción y reportes de tiempo de trabajo lo reflejen, y al menos el 40% de los familiares indiquen una mayor percepción de seguridad.

**Hypothesis Statements 5:**
Creemos que la integración de sensores de movimiento y signos vitales con alertas personalizables en tiempo real aumentará la adopción de nuestro sistema en un 25% del mercado objetivo durante el primer año. Sabremos que hemos tenido éxito cuando el 25% del mercado potencial (casas de reposo y cuidadores profesionales) hayan adquirido y utilicen activamente nuestra solución, reportando mejoras en la seguridad y satisfacción del cuidado.

#### 1.2.2.4. Lean UX Canvas

<table>
    <tr>
        <th colspan="1" valign="top">
            <p><b>Business Problem</b></p>
            <p>Los cuidadores de personas mayores enfrentan dificultades para monitorear el estado de salud de sus pacientes en tiempo real. Los familiares y cuidadores necesitan una forma eficiente de ser notificados sobre emergencias, como caídas o problemas de salud, para brindar atención inmediata y prevenir complicaciones graves.</p>
        </th>
        <th colspan="1" rowspan="2" valign="top">
            <p><b>Solution Ideas</b></p>
            <p>Monitorear la temperatura y el ritmo cardíaco de las personas mayores en tiempo real.</p>
            <p>Recibir notificaciones inmediatas en caso de emergencias o valores fuera de rango.</p>
            <p>Permitir a los usuarios solicitar ayuda a través de un botón en el brazalete.</p>
            <p>Generar reportes automáticos con datos de salud y patrones a lo largo del tiempo.</p>
            <p>Acceso al sistema desde dispositivos móviles y web para cuidadores y familiares.</p>
        </th>
        <th colspan="1" valign="top">
            <p><b>Business Outcomes</b></p>
            <p>Mejorar la capacidad de respuesta ante emergencias en un 25%.</p>
            <p>Reducir el tiempo de respuesta a incidentes de salud en personas mayores en un 20%.</p>
            <p>Incrementar la satisfacción de los clientes mediante la integración de reportes y notificaciones automatizadas.</p>
        </th>
    </tr>
    <tr>
        <td colspan="1" valign="top">
            <p><b>User & Customers</b></p>
            <p><b>Usuarios</b>: Cuidadores y familiares de personas mayores que necesitan monitoreo constante.</p>
            <p><b>Clientes</b>: Clínicas geriátricas, residencias de ancianos, y familias con personas mayores que requieren monitoreo continuo.</p>
        </td>
        <td colspan="1" valign="top">
            <p><b>User Benefits</b></p>
            <p><b>Cuidadores:</b> Mayor visibilidad en tiempo real del estado de salud de las personas mayores, mejor toma de decisiones basadas en datos y reducción en la necesidad de monitoreo físico constante.</p>
            <p><b>Personas Mayores:</b> Mayor seguridad y tranquilidad al saber que están siendo monitoreados de manera constante, y facilidad para solicitar ayuda en caso de emergencia.</p>
        </td>
    </tr>
    <tr>
        <td colspan="1" valign="top">
            <p><b>Hypotheses</b></p>
            <p><b>Monitoreo en Tiempo Real:</b> Implementar un sistema de monitoreo en tiempo real reducirá los incidentes de salud no detectados en un 25% y mejorará la capacidad de respuesta de los cuidadores en un 20%.</p>
            <p><b>Notificaciones Instantáneas:</b> Las notificaciones instantáneas mejorarán la capacidad de los cuidadores para actuar rápidamente, reduciendo los riesgos de complicaciones.</p>
            <p><b>Reportes Automáticos:</b> La generación de reportes automáticos ayudará a los cuidadores y familiares a tomar decisiones mejor informadas sobre el estado de salud de las personas mayores.</p>
        </td>
        <td colspan="1" valign="top">
            <p><b>What’s the most important thing we need to learn first?</b></p>
            <p>Lo más importante que necesitamos aprender primero es: La efectividad del sistema de monitoreo en tiempo real para detectar y notificar problemas de salud en personas mayores.</p>
        </td>
        <td colspan="1" valign="top">
            <p><b>What’s the least amount of work we need to do to learn the most important thing?</b></p>
            <p><b>Mínimo trabajo necesario:</b> Desarrollar un prototipo básico del sistema de monitoreo que incluya monitoreo de temperatura, ritmo cardíaco y un botón de solicitud de ayuda. Realizar pruebas piloto en un entorno controlado para validar la efectividad del sistema y recopilar retroalimentación de los usuarios antes del lanzamiento completo.</p>
        </td>
    </tr>
</table>


## 1.3. Segmentos objetivo

---

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

| Nombre del Competidor | Descripción |
| :-------------------: | :---------- |
| Life Alert ![](https://www.seniorliving.org/app/uploads/2019/01/Life-Alert-Logo.png) https://www.lifealert.com/ | Life Alert es una de las marcas más reconocidas en sistemas de alerta médica, famosa por su eslogan “¡He caído y no puedo levantarme!”. Ofrece sistemas de emergencia diseñados para ayudar a personas mayores a solicitar asistencia rápidamente. Su principal dispositivo es un botón de emergencia que puede usarse en el hogar o fuera de él, enviando alertas a un centro de monitoreo disponible las 24 horas del día. |
| MobileHelp ![](https://mma.prnewswire.com/media/782992/MobileHelp_Logo.jpg?p=facebook) https://www.mobilehelp.com/  | MobileHelp es un proveedor líder de sistemas de alerta médica que ofrece dispositivos portátiles y basados en el hogar para personas mayores. Sus dispositivos están diseñados para alertar a los servicios de emergencia en caso de una caída u otro incidente. Además de las soluciones de emergencia en el hogar, MobileHelp destaca por su cobertura fuera de casa gracias a su integración con redes móviles, lo que ofrece a los usuarios mayor independencia y movilidad. |
| CarePredict ![](https://mma.prnewswire.com/media/1217082/CarePredict_Logo.jpg?p=facebook) https://www.carepredict.com/  | CarePredict es una empresa tecnológica que se enfoca en el monitoreo preventivo para adultos mayores. Utiliza dispositivos portátiles equipados con sensores para rastrear patrones de comportamiento y signos vitales. A través de la inteligencia artificial, CarePredict predice posibles problemas de salud antes de que ocurran, como caídas o infecciones, y permite la intervención proactiva de cuidadores y familiares. |

### 2.1.1. Análisis competitivo

<table>
  <tr>
    <th colspan="7" valign="top"><b>Competitive Analysis Landscape</b></th>
  </tr>
  <tr>
    <td colspan="2" rowspan="2">¿Por qué llevar a cabo este análisis?</td>
  </tr>
  <tr>
    <td colspan="5">Comparar las características y funcionalidades clave de nuestra solución con las de la competencia para identificar ventajas competitivas y posibles áreas de mejora.</td>
  </tr>
  <tr>
    <td colspan="3">Competidores</td>
    <td colspan="1" valign="top" style="font-weight: bold;text-align: center">
        MIAM 
        <img src="assets/MIAM-Logov1.png" alt="Logo" class="logo-img">
        <div style="text-align: center; margin-top: 10px;">
        </div>
    <td colspan="1" valign="top" style="font-weight: bold;text-align: center">
        Life Alert 
        <img src="assets/Life-Alert.png" alt="Logo" class="logo-img">
        https://www.lifealert.com/ 
        <div style="text-align: center; margin-top: 10px;">
        </div>
    </td>
    <td colspan="1" valign="top" style="font-weight: bold;text-align: center" >
        Carepredict
        <img src="assets/CarePredict.jpg" alt="Logo" class="logo-img">
        https://www.mobilehelp.com/
        <div style="text-align: center; margin-top: 10px;">
        </div>
      </td>
    <td colspan="1" valign="top" style="font-weight: bold;text-align: center" >
        MobileHelp
        <img src="assets/MobileHelp.jpg" alt="Logo" class="logo-img">
        https://www.carepredict.com/ 
        <div style="text-align: center; margin-top: 10px;">
        </div>
    </td>
  </tr>
  <tr>
    <td colspan="1" rowspan="2"><p>Perfil</p></td>
    <td colspan="2">Overview</td>
    <td colspan="1" valign="top">MIAM ofrece un avanzado sistema de monitoreo inteligente para la prevención de accidentes en adultos mayores, a través del seguimiento de su movimiento y signos vitales de manera rápida y precisa, genera  reportes de los datos del adulto mayor y proporciona un fácil monitoreo por su interfaz.
    </td>
    <td colspan="1" valign="top">Life Alert es un sistema de alerta médica diseñado para proteger a las personas mayores en caso de emergencia sanitaria en el hogar, les permite ser independientes y enviar ayuda rápidamente en caso de una emergencia médica.
    </td>
    <td colspan="1" valign="top">CarePredict es una empresa de tecnología que ofrece soluciones de monitoreo para el cuidado de adultos mayores, usando inteligencia artificial y sensores. Su sistema predice cambios en el comportamiento para prevenir problemas de salud como caídas o infecciones.
    </td>
    <td colspan="1" valign="top">MobileHelp ofrece dispositivos médicos que permiten a los adultos mayores vivir de forma independiente mientras brindan tranquilidad a sus familiares, incluyen sistemas de alerta de emergencia médica que funcionan en el hogar y en exteriores.
    </td>
  </tr>
  <tr>
    <td colspan="2">Ventaja competitiva</td>
    <td colspan="1" valign="top">Ofrece un enfoque detallado e íntegro para el monitoreo completo del adulto mayor evitando posibles accidentes.
    </td>
    <td colspan="1" valign="top">Envía la ayuda que necesita rápidamente, las 24 horas del día, los 7 días de la semana.
    </td>
    <td colspan="1" valign="top">Tecnología avanzada de sensores portátiles y el uso de inteligencia artificial que predice problemas de salud antes de que ocurran.
    </td>
    <td colspan="1" valign="top">Combinación de dispositivos médicos avanzados con opciones de movilidad, es decir, sus sistemas no están limitados al hogar y ofrecen cobertura en cualquier lugar donde haya señal celular.
    </td>
  </tr>
  <tr>
    <td colspan="1" rowspan="2"><p>Perfil de Marketing</p></td>
    <td colspan="2">Mercado objetivo</td>
    <td colspan="1" valign="top"> MIAM ofrece una solución completa para ayudar en el cuidado del adulto mayor, dirigidas a aquellos familiares que poseen familia con una edad avanzada y deseen un cuidado especializado para sus seres queridos.
    </td>
    <td colspan="1" valign="top">Ofrece una solución especializada en la respuesta rápida ante los distintos accidentes que pueda sufrir un adulto mayor que se encuentre solo.
    </td>
    <td colspan="1" valign="top">CarePredict se posiciona como una solución innovadora en el sector de salud para personas mayores, enfocándose en la prevención de problemas de salud a través de tecnología avanzada.
    </td>
    <td colspan="1" valign="top">MobileHelp se posiciona como una solución accesible y fiable en el mercado de dispositivos de seguridad para personas mayores, suelen centrarse en la seguridad y tranquilidad que brindan a los usuarios.
    </td>
  </tr>
  <tr>
    <td colspan="2">Estrategias de marketing</td>
    <td colspan="1" valign="top">Usará el marketing digital, realizará posts, campañas publicitarias y colaboración con influences en internet para atraer a familiares que quieran un aparato que ayude en el cuidado de su adulto mayor.
    </td>
    <td colspan="1" valign="top">Campañas publicitarias en televisión y videos con testimonios de los adultos mayores a los que le ayudó el producto ante una emergencia.
    </td>
    <td colspan="1" valign="top">Utilizan contenido educativo y testimonios de clientes para atraer a los usuarios. Además, aprovechan redes sociales y asociaciones con organizaciones de atención médica para ampliar su alcance.
    </td>
    <td colspan="1" valign="top">Utilizan una estrategia multicanal, que incluye anuncios en televisión, redes sociales y asociaciones con proveedores de atención médica..
    </td>
  </tr>
  <tr>
    <td colspan="1" rowspan="3"><p>Perfil de Producto</p></td>
    <td colspan="2">Productos & Servicios</td>
    <td colspan="1" valign="top">Ofrecemos un plan de suscripción mensual de bajo costo para el plan básico o un plan de suscripción personalizado para el plan empresarial
    </td>
    <td colspan="1" valign="top">Ofrece 3 productos para la respuesta rápida ante una emergencia, "help button", "micro voice pendant system" y "on-the-go + GPS".
    </td>
    <td colspan="1" valign="top">Ofrecen sensores portátiles que monitorean las actividades diarias y detectan cambios en los patrones de comportamiento.
    </td>
    <td colspan="1" valign="top">MobileHelp ofrece sistemas de alerta médica, monitores de salud, y accesorios como sensores de caídas y relojes inteligentes con capacidades de monitoreo.
    </td>
  </tr>
  <tr>
    <td colspan="2">Precios y Costos</td>
    <td colspan="1" valign="top">Ofrecemos un plan de suscripción mensual de bajo costo para el plan básico o un plan de suscripción personalizado para el plan empresarial.
    </td>
    <td colspan="1" valign="top">Entregan el producto después de realizar una llamada al número proporcionado en su página web.
    </td>
    <td colspan="1" valign="top">El modelo de precios se basa en suscripciones mensuales por el uso de los dispositivos y el acceso a la plataforma de monitoreo.
    </td>
    <td colspan="1" valign="top">Sus precios varían según el tipo de dispositivo y plan de servicio, generalmente en formato de suscripción mensual.
    </td>
  </tr>
  <tr>
    <td colspan="2">Canales de distribución</td>
    <td colspan="1" valign="top">Ventas directas a partir de los canales de la aplicación web y móvil.
    </td>
    <td colspan="1" valign="top">Ventas directas y personalizadas para cada llamada al número proporcionado por la página web.
    </td>
    <td colspan="1" valign="top">Acceso a través de una plataforma web y aplicaciones móviles que permiten a los cuidadores y familiares monitorear la salud de los adultos mayores en tiempo real.
    </td>
    <td colspan="1" valign="top">MobileHelp distribuye sus productos principalmente a través de su sitio web y socios minoristas.
    </td>
  </tr>
  <tr>
    <td colspan="1" rowspan="5"><p>Análisis SWOT</p></td>
    
  </tr>
  <tr>
    <td colspan="2">Fortalezas</td>
    <td colspan="1" valign="top">Tecnología IoT avanzada para un monitoreo preciso del adulto mayor, acompañado de aplicativo móvil y web intuitivo con una gran personalización y proporciona información recolectada.
    </td>
    <td colspan="1" valign="top">Enfoque centrado en la respuesta rápida ante los accidentes del adulto mayor, solución sencilla y simple pero eficiente.
    </td>
    <td colspan="1" valign="top">Tecnología avanzada, predicción proactiva de problemas de salud.
    </td>
    <td colspan="1" valign="top">Amplia cobertura fuera del hogar, sistemas fáciles de usar y monitoreo 24/7.
    </td>
  </tr>
  <tr>
    <td colspan="2">Debilidades</td>
    <td colspan="1" valign="top">Posible alta inversión en el área de investigación y desarrollo, necesidad de establecerse en un mercado altamente competitivo.
    </td>
    <td colspan="1" valign="top">Limitación en solo enviar alertas cuando el botón sea presionado, posible dependencia de su reputación.
    </td>
    <td colspan="1" valign="top">Dependencia de la tecnología, lo que puede limitar la adopción por parte de usuarios menos tecnológicos.
    </td>
    <td colspan="1" valign="top">Dependencia de las redes celulares para algunas funciones, lo que puede limitar la cobertura en áreas rurales.
    </td>
  </tr>
  <tr>
    <td colspan="2">Oportunidades</td>
    <td colspan="1" valign="top">Creciente población de adultos mayores en el mundo, promedio de vida en alsa, mejoras en la respuesta de salud, demanda de soluciones tecnológicas en el área y expansión a mercados globales.
    </td>
    <td colspan="1" valign="top">Expansión del área de salud y cuidado de adultos mayores, promedio de vida de las personas más alta, expansión en mercados globales
    </td>
    <td colspan="1" valign="top">Creciente demanda de soluciones de cuidado para personas mayores.
    </td>
    <td colspan="1" valign="top">Creciente demanda de soluciones de salud para la población envejecida.
    </td>
  </tr>
  <tr>
    <td colspan="2">Amenazas</td>
    <td colspan="1" valign="top">Competencia fuerte de empresas ya establecidas y consolidadas en el campo, cambios en las tendencias tecnológicas que puedan cambiar o afectar a la demanda del servicio.
    </td>
    <td colspan="1" valign="top">Competencia de otras soluciones más completas en el mercado, creciente avance de la tecnología puede dejar anticuado el simple sistema.
    </td>
    <td colspan="1" valign="top">Competencia de otros dispositivos de monitoreo y avances en tecnología​.
    </td>
    <td colspan="1" valign="top">Competencia creciente de dispositivos de alerta médica portátiles y cambios en las regulaciones del sector.
    </td>
  </tr>
</table>


### 2.1.2. Estrategias y tácticas frente a competidores

<table>
  <tr>
    <th colspan="3" valign="top"></th>
    <th colspan="4" valign="top"><b>OPORTUNIDADES</b></th>
    <th colspan="4" valign="top"><b>AMENAZAS</b></th>
  </tr>
  <tr>
    <th colspan="3" valign="top"></th>
    <td colspan="4" valign="top">
      <li> Creciente población de adultos mayores a nivel mundial.
      <li> Aumento en la demanda de soluciones tecnológicas para el cuidado de la salud.
      <li> Expansión global hacia mercados con alta demanda de productos de salud y monitoreo.
      <li> Mejoras en la expectativa de vida y respuesta de salud preventiva.
    </td>
    <td colspan="4" valign="top">
      <li> Competencia fuerte de empresas establecidas en el mercado.
      <li> Rápido cambio tecnológico, lo que puede requerir actualizaciones constantes.
      <li> Baja barrera de entrada para nuevos competidores en el sector de monitoreo.
      <li> Cambios en las tendencias de salud y políticas que afecten la demanda del servicio.
    </td>
  </tr>

  <tr>
    <th colspan="3" valign="top"><b>FORTALEZAS</b></th>
    <th colspan="4" valign="top"><b>ESTRATEGIAS FO (Ofensivas)</b></th>
    <th colspan="4" valign="top"><b>ESTRATEGIAS FA (Defensiva)</b></th>
  </tr>
  <tr>
    <td colspan="3" valign="top">
      <li> Tecnología IoT avanzada para el monitoreo preciso de adultos mayores.
      <li> Aplicación web y móvil intuitiva con gran personalización.
      <li> Capacidad de monitoreo en tiempo real de signos vitales y movimiento.
      <li> Generación de reportes detallados para cuidadores y familiares.
    </td>
    <td colspan="4" valign="top">
      <li> F1 + O1/O2: Aprovechar la avanzada tecnología IoT para expandirse en el mercado global de cuidado de adultos mayores, resaltando las capacidades de monitoreo proactivo en campañas dirigidas a mercados en crecimiento.
      <li> F3 + O3: Utilizar el monitoreo en tiempo real y los reportes personalizados para formar alianzas estratégicas con hospitales y centros de salud, ingresando a nuevos mercados internacionales donde la demanda de tecnología de salud está en aumento.
    </td>
    <td colspan="4" valign="top">
      <li> F2 + A1: Usar la ventaja de la interfaz intuitiva para diferenciarse de competidores más tradicionales, enfocando las campañas de marketing en la facilidad de uso y el soporte continuo que MIAM ofrece a las familias.
      <li> F4 + A3: Generar innovaciones en los reportes y análisis de datos para mantenerse a la vanguardia frente a nuevos competidores que puedan entrar al mercado. Añadir funcionalidades basadas en inteligencia artificial para mejorar la calidad del servicio.
    </td>
  </tr>

  <tr>
    <th colspan="3" valign="top"><b>DEBILIDADES</b></th>
    <th colspan="4" valign="top"><b>ESTRATEGIAS DO (Reorientación)</b></th>
    <th colspan="4" valign="top"><b>ESTRATEGIAS DA (Supervivencia)</b></th>
  </tr>
  <tr>
    <td colspan="3" valign="top">
      <li> Alta inversión en I+D para mantenerse competitivos.
      <li> Falta de reconocimiento frente a competidores ya establecidos.
      <li> Necesidad de una estrategia sólida de penetración de mercado.
      <li> Dependencia de la tecnología y conectividad para un monitoreo eficiente.
    </td>
    <td colspan="4" valign="top">
      <li> D1 + O2: Invertir en investigación y desarrollo de manera escalonada, comenzando con mejoras en los productos más demandados, para capitalizar el aumento en la demanda de soluciones tecnológicas para adultos mayores.
      <li> D3 + O3: Desarrollar una estrategia de marketing digital sólida para aumentar la penetración en el mercado, aprovechando la tendencia creciente de la atención a adultos mayores para ganar visibilidad frente a competidores más grandes.
    </td>
    <td colspan="4" valign="top">
      <li> D2 + A1/A2: Trabajar en la mejora del reconocimiento de marca a través de colaboraciones con influencers y campañas publicitarias que resalten las características distintivas de MIAM, mitigando la fuerte competencia y la posible obsolescencia tecnológica.
      <li> D4 + A4: Implementar sistemas de monitoreo basados en la nube que puedan adaptarse fácilmente a cambios tecnológicos y políticas, reduciendo la dependencia de la infraestructura tecnológica y asegurando una respuesta ágil a cualquier cambio en las tendencias de salud.
    </td>

  </tr>

</table>

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

**Segmento 1:** Cuidadores de adultos mayores (Caregivers)

- ¿Cuál es su nombre?
- ¿Cuántos años tiene y cuál es su estado civil?
- ¿En qué distrito vive?
- ¿Cuál es su profesión?
- ¿Qué dispositivos tecnológicos utiliza regularmente? 
- ¿Hay alguna marca de dispositivos que prefiera o utilice más? ¿Por qué?
- ¿Usa alguno para el monitoreo de los adultos mayores? (Ej. pulseras inteligentes, cámaras de vigilancia, etc.)
- ¿Qué medios o redes sociales utiliza para informarse sobre temas relacionados a su trabajo o comunicarse? (Ej. WhatsApp, Facebook, foros especializados, etc.)
- ¿Se considera una persona que se adapta fácilmente a las nuevas tecnologías?
- ¿En su labor, prefiere seguir procedimientos establecidos o es más de buscar soluciones tecnológicas?
- ¿Cuáles son los principales desafíos que enfrenta al monitorear y cuidar a un adulto mayor?
- ¿Qué aspectos de su trabajo le generan más satisfacción o facilitan su labor?
- ¿Podría describir cómo es un día típico cuidando a un adulto mayor, en particular en relación con la prevención de caídas?
- ¿Qué pasos sigue o qué herramientas utiliza para asegurarse de que el adulto mayor esté seguro en todo momento?
- Si pudiera diseñar una herramienta para ayudarle en el monitoreo de adultos mayores, ¿qué características considera que serían imprescindibles?
- ¿Qué funciones adicionales le gustaría que tuviera esta herramienta?

**Segmento 2:** Dueños de casas de reposo (Nursing Home Owners)

- ¿Cuál es su nombre?
- ¿Cuántos años tiene y cuál es su estado civil?
- ¿En qué distrito vive?
- ¿Cuál es su profesión y su rol dentro de la casa de reposo?
- ¿Qué dispositivos tecnológicos utiliza regularmente?
- ¿Hay alguna marca de dispositivos que prefiera o utilice más? ¿Por qué?
- ¿Utiliza actualmente alguna herramienta para el monitoreo de los adultos mayores residentes? (Ej. sistemas de alarma, sensores, cámaras, etc.)
- ¿Qué medios o redes sociales utiliza para estar al tanto de información y comunicarse? (Ej. LinkedIn, WhatsApp , etc.)
- ¿Cómo se describe en cuanto a la adopción de nuevas tecnologías en su establecimiento? 
- ¿Estaría interesado en invertir en tecnología de punta para el monitoreo de los residentes? ¿Por qué?
- ¿Cuáles son los principales desafíos que enfrenta al gestionar la seguridad y bienestar de los residentes?
- ¿Qué mejoras o innovaciones le han resultado más útiles en la gestión de la casa de reposo?
- ¿Podría describir el proceso que sigue en un día típico de trabajo?
- ¿Qué protocolos o herramientas son esenciales en su día a día para garantizar la seguridad y prevenir caídas de los residentes?
- Si pudiera integrar un nuevo sistema de monitoreo en su casa de reposo, ¿qué características serían imprescindibles para usted?
- ¿Qué otras funciones le gustaría que tuviera este sistema para mejorar la seguridad y de los residentes?


### 2.2.2. Registro de entrevistas

**Segmento 1:** Cuidadores de adultos mayores (Caregivers)

<table border=1>
  <tr>
    <td>
      <b>Nombres y apellidos:</b> Katty Salgado <br>
      <b>Edad: </b> 29 años <br>
      <b>Distrito:</b> Los Olivos <br>
      <b>Timing:</b> 0:00 - 10:06 minutos
      <b>Duración:</b> 10:06 minutos
    </td>
    <td align=center>
      <img src="./assets/entrevista-katty.PNG" alt="img"  width="80%"/>
    </td>
  </tr>
  <tr>
    <td colspan=2>
      <b>Enlace:</b> <a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u20211a452_upc_edu_pe/EWWyf1Bu04dOsC3RR-_KVokBMygONZKUg7Lctfhx9M4qYg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=dGXh8b">https://goo.su/Ao2Pm</a>
      <br>
      <b>Resumen:</b> Katty es una enfermera que se dedica al cuidado de los adultos mayores. En la entrevista se muestra como una persona amable y empática. Ella comenta que sus dispositivos más usados son su celular, su tablet y laptop, los cuales utiliza para comunicarse y gestionar sus horarios de trabajo. Asimismo, sus marcas preferidas son las de sus dispositivos de uso diario: Xiaomi y Apple. No utiliza dispositivos tecnológicos para el cuidado de los adultos mayores, pero ha identificado que en algunos hogares las familias utilizan cámaras para monitorearlos. Las redes sociales que más usa son Whatsapp, Facebook e Instagram y considera que se adapta a las nuevas tecnologías fácilmente. Dentro de su rutina de trabajo realiza funciones como la toma de signos vitales, aseo del adulto mayor, tendido de cama y apoyo con la alimentación. Katty considera que uno de los desafíos en su trabajo es evitar las caídas de los adultos mayores, por lo cual tiene que ayudarlos constantemente a movilizarse. Por otra parte, lo que le causa más satisfacción es el agradecimiento del paciente y su familia. Considera que un sistema de monitoreo debería ayudarle a monitorear los signos vitales (pulso, temperatura, saturación de oxígeno, etc.) y prevenir las caídas. También considera útil el envío de notificaciones cuando alguno de los signos vitales esté alterado y recordatorios del tratamiento (medicación) del paciente.
    </td>
  </tr>
</table>

<table border=1>
  <tr>
    <td>
      <b>Nombres y apellidos:</b> Sara Villanueva <br>
      <b>Edad: </b> 39 años <br>
      <b>Distrito:</b> Callao <br>
      <b>Timing:</b> 10:06 - 13:42 minutos
      <b>Duración:</b> 3:36 minutos
    </td>
    <td align=center>
      <img src="./assets/entrevista-sara.PNG" alt="img"  width="80%"/>
    </td>
  </tr>
  <tr>
    <td colspan=2>
      <b>Enlace:</b> <a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u20211a452_upc_edu_pe/EWWyf1Bu04dOsC3RR-_KVokBMygONZKUg7Lctfhx9M4qYg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=dGXh8b">https://goo.su/Ao2Pm</a>
      <br>
      <b>Resumen:</b> Sara es una enfermera que trabaja cuidando adultos mayores. Se muestra como una persona seria, concisa y práctica, adaptada al uso de la tecnología en su trabajo. El dispositivo que más utiliza en su día a día es su celular, ya que le ayuda a crear alarmas para administrar a tiempo el tratamiento a sus pacientes. Su marca favorita es Motorola. Sara considera que se adapta a la tecnología y le gusta incorporar soluciones tecnológicas en su labor. Su medio de comunicación más frecuente es a través de Whatsapp y también utiliza Instagram y TikTok. Uno de los principales desafíos que enfrenta al cuidar a los adultos mayores son las caídas, en especial en aquellos que no son independientes, y algo que le causa satisfacción es el agradecimiento y cariño que le dan sus pacientes. Con el fin de evitar caídas realiza procedimientos como colocar almohadas y ubicarlos en una posición adecuada, además de estar siempre pendiente todo el tiempo de ellos. Ella considera que un sistema de monitoreo del adulto mayor debe incluir cámaras para supervisarlos y el envío de alertas al cuidador.
    </td>
  </tr>
</table>

<table border=1>
  <tr>
    <td>
      <b>Nombres y apellidos:</b> William Ramos<br>
      <b>Edad: </b> 22 años <br>
      <b>Distrito:</b> Jesus Maria <br>
      <b>Timing:</b> 13:42 - 22:03 minutos
      <b>Duración:</b> 8:21 minutos
    </td>
    <td align=center>
      <img src="./assets/entrevista-WilliamRamos.png" alt="png"  width="80%"/>
    </td>
  </tr>
  <tr>
    <td colspan=2>
      <b>Enlace:</b> <a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u20211a452_upc_edu_pe/EWWyf1Bu04dOsC3RR-_KVokBMygONZKUg7Lctfhx9M4qYg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=dGXh8b">https://goo.su/Ao2Pm</a>
      <br>
      <b>Resumen:</b> William Ramos es una persona que terminó su carrera profesional y se dedica a trabajar de forma parcial en el cuidado de su vecina que es una adulta mayor. Es un joven extrovertido y práctico que muestra preocupación por el cuidado del adulto a su cargo. Los dispositivos que más utiliza son su computadora y celular, siendo sus marcas preferidas Samsung, Xiaomi y Asus. Las redes que más usa son Instagram y Whatsapp. Menciona que es una persona que se relaciona mucho con la tecnología a diferencia del adulto mayor al que se encarga de cuidar. Comenta que es una tarea un tanto complicada el hecho de cuidar al adulto mayor por la constante supervisión que se debe hacer y la preocupación de que pueda pasar algo. Menciona que en ocasiones el adulto mayor que cuida le gusta ser independiente y hacer varias acciones por su cuenta, le parece llamativo una solución que le permita monitorear si la persona que cuida se encuentra en perfecto estado y en qué ubicación está, ya que de esa manera podría darle autonomía sin descuidar el correcto cuidado que debe realizar. Comenta que le interesa una aplicación que permita saber el estado del adulto mayor y que permita al adulto mayor dar mensajes ante cualquier emergencia.
    </td>
  </tr>
</table>



**Segmento 2:** Dueños de casas de reposo (Nursing Home Owners)

<table border="1">
  <tr>
    <td>
      <b>Nombres y apellidos:</b> Gabriel Hachamizo<br>
      <b>Edad:</b> 27 años <br>
      <b>Distrito:</b> Los Aquijes - Ica <br>
      <b>Timing:</b> 22:03 - 28:14 minutos<br>
      <b>Duración:</b> 06:11 minutos
    </td>
    <td align="center">
      <img src="./assets/entrevista-gabriel.png" alt="img" width="80%"/>
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <b>Enlace:</b> <a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u20211a452_upc_edu_pe/EWWyf1Bu04dOsC3RR-_KVokBMygONZKUg7Lctfhx9M4qYg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=dGXh8b">https://goo.su/Ao2Pm</a>
      <br>
      <b>Resumen:</b> Gabriel es un licenciado en enfermería que trabaja en una casa de reposo para adultos mayores, desempeñando un rol administrativo. Es una persona organizada y práctica que busca mejorar la eficiencia en su labor. En la entrevista, comentó que sus dispositivos más utilizados son celulares y laptops y su marca preferida es Lenovo, ya que nunca ha tenido imprevistos con sus dispositivos. Para el monitoreo de los pacientes, se utilizan cámaras de seguridad, mientras que la comunicación con los familiares se realiza principalmente a través de WhatsApp. Facebook se emplea para promocionar los servicios de la casa de reposo. Gabriel considera que la adopción de nuevas tecnologías es positiva y puede mejorar el cuidado de los pacientes. Sin embargo, enfrenta desafíos como el manejo de una gran cantidad de pacientes y la insuficiencia del protocolo de atención para garantizar una atención adecuada. También describe su rol en la empresa, incluyendo la priorización de actividades según su importancia. Además, Gabriel sugiere el desarrollo de un software para optimizar la administración y el registro de pacientes, así como para recopilar datos que contribuyan a una mejor atención.
    </td>
  </tr>
</table>

<table border=1>
  <tr>
    <td>
      <b>Nombres y apellidos:</b> Miriam Guevara<br>
      <b>Edad: </b> 54 <br>
      <b>Distrito:</b> Trujillo <br>
      <b>Timing:</b> 28:14 - 36:29 minutos
      <b>Duración:</b> 7:54 minutos
    </td>
    <td align=center>
      <img src="./assets/entrevista-miriam.png" alt="img"  width="80%"/>
    </td>
  </tr>
  <tr>
    <td colspan=2>
      <b>Enlace:</b> <a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u20211a452_upc_edu_pe/EWWyf1Bu04dOsC3RR-_KVokBMygONZKUg7Lctfhx9M4qYg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=dGXh8b">https://goo.su/Ao2Pm</a>
      <br>
      <b>Resumen:</b> Miriam es una enfermera que ha puesto su casa de reposo para adultos mayores llamdo Divino Amor. Se muestra como una persona empática, amable y extrovertida que valora la organización. Durante la entrevista, comenta que utiliza con frecuencia su celular y laptop, siendo sus marcas favoritas Apple y Lenovo. El canal que más usa para comunicarse es a través de WhatsApp. Considera que la tecnologia es importante, así que en su casa de reposo utiliza cámaras de seguridad para el monitoreo de los pacientes. Sin embargo, comenta que para los adulyos mayores es complicado adaptarse. Por el momento, ellos disponen de una pequeña campana que hacen sonar cuando necesitan ayuda de sus cuidadores. Uno de los desafíos que identifica es el monitoreo constante del adulto mayor, para lo cuál las cámaras han sido de ayuda. La labor del personal inicia antes de que los pacientes se levanten por la mañana, ya que deben organizar qué actividades realizarán y verificar los medicamentos que administrarán a los adultos mayores. Considera que lo mas dificil es tratar a todos los adultos mayores al mismo tiempo, sobre todo cuando despiertan. 
    </td>
  </tr>
</table>

### 2.2.3. Análisis de entrevistas

**Segmento Objetivo -> Cuidadores:**

- Características Objetivas: 

![Caracteristicas Objeticas1](./assets/S1_CO_01.png)

La gráfica muestra el porcentaje de cuidadores que han adoptado un sistema de monitoreo para personas mayores, comparado con aquellos que no lo han hecho. Se observa que una gran mayoría de cuidadores ya utiliza algún tipo de tecnología para supervisar la salud y seguridad de los adultos mayores, lo que sugiere una tendencia creciente hacia la digitalización y automatización en el cuidado de la tercera edad.

![Caracteristicas Objeticas2](./assets/S1_CO_02.png)

Indica el porcentaje de cuidadores que realizan un monitoreo activo de los signos vitales, como el pulso, de los adultos mayores bajo su cuidado, frente a aquellos que no realizan estas mediciones. Esto refleja la importancia que se le da al seguimiento de la salud en tiempo real para prevenir posibles complicaciones y mantener un control constante de la condición física del adulto mayor.

![Caracteristicas Objeticas3](./assets/S1_CO_03.png)

Muestra el porcentaje de cuidadores que enfrentan desafíos significativos en su labor diaria. Los desafíos más comunes incluyen la falta de tiempo, el estrés emocional y la necesidad de equilibrar el cuidado con otras responsabilidades personales. Esta gráfica resalta la necesidad de brindar más apoyo y recursos a los cuidadores.

![Caracteristicas Objeticas4](./assets/S1_CO_04.png)

Representa el porcentaje de cuidadores que consideran las caídas como uno de los mayores riesgos para las personas mayores, en comparación con aquellos que no le dan tanta importancia a este factor. Las caídas son una causa principal de hospitalizaciones y lesiones graves en adultos mayores, por lo que es crucial implementar medidas preventivas.

- Características Subjetivas: 

![Caracteristicas Subjetivas1](./assets/S1_CS_01.png)

Compara la satisfacción personal de los cuidadores que reciben gratitud por parte de los adultos mayores, frente a aquellos que no experimentan este tipo de reconocimiento. La gratitud tiene un impacto positivo en la motivación y bienestar emocional del cuidador, subrayando la importancia del reconocimiento y apoyo en su rol.

![Caracteristicas Subjetivas2](./assets/S1_CS_02.png)

Refleja la capacidad de adaptabilidad de los cuidadores hacia el uso de tecnología en el cuidado de adultos mayores. Aquellos con alta adaptabilidad suelen sentirse más cómodos utilizando dispositivos y aplicaciones para monitorear la salud, mientras que los de baja adaptabilidad pueden requerir capacitación adicional para integrar la tecnología en su rutina.

![Caracteristicas Subjetivas3](./assets/S1_CS_03.png)

Muestra la preferencia en el uso de sistemas operativos móviles entre los cuidadores, comparando el uso de Android frente a iOS. Esta preferencia puede influir en la adopción de ciertas aplicaciones o herramientas de monitoreo, y es importante considerarlo al desarrollar soluciones tecnológicas para el cuidado.

![Caracteristicas Subjetivas4](./assets/S1_CS_04.png)

Compara la personalidad de los cuidadores, destacando la proporción de extrovertidos frente a introvertidos. Los extrovertidos pueden encontrar más satisfacción en roles que implican interacción constante con los adultos mayores y otros cuidadores, mientras que los introvertidos pueden preferir tareas más orientadas al seguimiento y administración.

![Caracteristicas Subjetivas5](./assets/S1_CS_05.png)

Indica el uso de diferentes redes sociales entre los cuidadores, incluyendo WhatsApp, Facebook, Instagram y TikTok. Esta información es útil para diseñar estrategias de comunicación y apoyo, así como para entender las preferencias de interacción social de los cuidadores en plataformas digitales.

![Caracteristicas Subjetivas6](./assets/S1_CS_06.png)

Compara la preferencia por marcas de dispositivos móviles, mostrando una alta presencia de marcas como Xiaomi, Apple y Motorola. Este dato es relevante para el desarrollo de aplicaciones móviles, asegurando compatibilidad y optimización en las marcas más utilizadas por los cuidadores.

**Segmento Objetivo -> Dueños de casas de reposo:**

- Características Objetivas: 

![Caracteristicas Objeticas1](./assets/S2_CO_01.png)

Muestra el uso de cámaras de monitoreo en casas de reposo, resaltando la importancia de la vigilancia para la seguridad de los residentes. Los propietarios de casas de reposo que implementan sistemas de cámaras suelen tener un mejor control y respuesta ante situaciones de emergencia.

![Caracteristicas Objeticas2](./assets/S2_CO_02.png)

Indica los principales desafíos que enfrentan los dueños de casas de reposo, como la gestión eficiente del personal y la implementación de tecnología para mejorar la atención. Este gráfico destaca la necesidad de soluciones tecnológicas que simplifiquen la administración y mejoren la calidad del servicio.

![Caracteristicas Objeticas3](./assets/S2_CO_03.png)

Resalta el interés de los dueños de casas de reposo en implementar tecnología para mejorar sus servicios. La mayoría está abierta a adoptar nuevas herramientas que les permitan monitorear mejor a los residentes y optimizar los recursos disponibles.

- Características Subjetivas: 

![Caracteristicas Subjetivas1](./assets/S2_CS_01.png)

Muestra el nivel de satisfacción de los dueños de casas de reposo al brindar cuidado a los adultos mayores. La satisfacción personal es un indicador de la calidad del servicio y la motivación para continuar mejorando el entorno y la atención brindada.

![Caracteristicas Subjetivas2](./assets/S2_CS_02.png)

Indica el grado de adaptabilidad a nuevas tecnologías de los dueños de casas de reposo. Aquellos con alta adaptabilidad suelen estar más dispuestos a implementar sistemas avanzados de monitoreo y gestión en sus instalaciones.

![Caracteristicas Subjetivas3](./assets/S2_CS_03.png)

Refleja el interés en mejorar el uso de la tecnología en el entorno laboral de las casas de reposo. La mayoría busca soluciones que integren funciones como monitoreo de salud, administración de medicamentos y comunicación con familiares.

![Caracteristicas Subjetivas4](./assets/S2_CS_04.png)

Compara la preferencia por dispositivos Lenovo y Apple entre los dueños de casas de reposo. Esta información puede influir en la decisión de adquirir herramientas tecnológicas compatibles y optimizadas para los dispositivos más utilizados.

![Caracteristicas Subjetivas5](./assets/S2_CS_05.png)

Muestra la proporción de dueños de casas de reposo que son extrovertidos frente a introvertidos. Los extrovertidos tienden a liderar con un enfoque más comunicativo y abierto, mientras que los introvertidos pueden centrarse más en la organización interna y la eficiencia operativa.

![Caracteristicas Subjetivas6](./assets/S2_CS_06.png)

Indica el uso de redes sociales como WhatsApp y Facebook entre los dueños de casas de reposo. Estas plataformas son clave para la comunicación con familiares y el equipo de trabajo, facilitando el intercambio de información y la coordinación.

![Caracteristicas Subjetivas7](./assets/S2_CS_07.png)

Compara el uso de celulares Android frente a iOS entre los dueños de casas de reposo. Esta preferencia tecnológica puede afectar la adopción de aplicaciones y sistemas de gestión diseñados para dispositivos móviles, destacando la importancia de crear soluciones multiplataforma.

## 2.3. Needfinding

### 2.3.1. User Personas

**Segmento 1:** Cuidadores de adultos mayores (Caregivers)

Ana Martinez es una enfermera de 32 años que trabaja en Lima, Perú, especializada en el cuidado de adultos mayores. Ella es una cuidadora comprometida que se siente motivada por el bienestar y la seguridad de sus pacientes, y siempre busca ofrecer el mejor servicio posible. Su enfoque está en mejorar la eficiencia en el cuidado de sus pacientes, a pesar de enfrentar desafíos como las caídas y la falta de tecnología para facilitar su trabajo. A Ana le interesa incorporar nuevas tecnologías en su rutina para monitorear signos vitales de manera más eficiente y se siente frustrada por la dependencia de métodos manuales. Utiliza canales de comunicación como WhatsApp e Instagram para conectarse con los demás y sigue marcas tecnológicas como Xiaomi.

![User Persona](./assets/user-persona-ana-martinez.png)

**Segmento 2:** Dueños de casas de reposo (Nursing Home Owners)

Gabriel Lopez es un enfermero de 40 años que dirige una casa de reposo para adultos mayores en Lima, Perú. Como dueño y administrador, su principal objetivo es mejorar la eficiencia en la atención a los pacientes a través de un sistema que le permita gestionar el estado de estos de manera más efectiva. Aunque tiene una amplia experiencia en la gestión de personal y pacientes, uno de sus mayores retos es atender a todos sus pacientes simultáneamente, especialmente durante los momentos de mayor actividad. Gabriel valora profundamente la tecnología y busca constantemente formas de integrarla para optimizar tanto la calidad de los cuidados como la administración en su lugar de trabajo. Utiliza WhatsApp como su principal canal de comunicación y se siente influenciado por marcas como Lenovo.

![User Persona](./assets/user-persona-gabriel-lopez.png)


### 2.3.2. User Task Matrix

El User Task Matriz presenta las actividades en común que más realizan los usuarios Ana Martinez y Gabriel Lopez. Entre las más importantes se encuentran la supervisión del estado de los adultos mayores, gestión de los cuidados y medicación y la revisión de actividades diarias. Esto sugiere que tienen prioridades similares en su trabajo.

<table>
  <tr>
    <th style="text-align: center;">User Task</th>
    <th colspan="2" style="text-align: center;">Ana Martinez</th>
    <th colspan="2" style="text-align: center;">Gabriel Lopez</th>
  </tr>
  <tr>
    <th></th>
    <th style="text-align: center;">Frequency</th>
    <th style="text-align: center;">Importance</th>
    <th style="text-align: center;">Frequency</th>
    <th style="text-align: center;">Importance</th>
  </tr>
  <tr>
    <td style="text-align: center;">Supervisión del estado de los pacientes</td>
    <td style="text-align: center;">SIEMPRE</td>
    <td style="text-align: center;">ALTA</td>
    <td style="text-align: center;">SIEMPRE</td>
    <td style="text-align: center;">ALTA</td>
  </tr>
  <tr>
    <td style="text-align: center;">Comunicación y coordinación con familias de los pacientes</td>
    <td style="text-align: center;">USUALMENTE</td>
    <td style="text-align: center;">ALTA</td>
    <td style="text-align: center;">USUALMENTE</td>
    <td style="text-align: center;">MEDIA</td>
  </tr>
  <tr>
    <td style="text-align: center;">Gestión de cuidados y medicación de los pacientes</td>
    <td style="text-align: center;">SIEMPRE</td>
    <td style="text-align: center;">ALTA</td>
    <td style="text-align: center;">SIEMPRE</td>
    <td style="text-align: center;">ALTA</td>
  </tr>
  <tr>
    <td style="text-align: center;">Revisar y priorizar actividades diarias</td>
    <td style="text-align: center;">SIEMPRE</td>
    <td style="text-align: center;">ALTA</td>
    <td style="text-align: center;">SIEMPRE</td>
    <td style="text-align: center;">ALTA</td>
  </tr>
</table>


### 2.3.3. User Journey Mapping

**User Persona:** Ana Martinez

El User Journey Mapping de Ana Martínez destaca las dificultades que enfrenta a lo largo de su labor diaria. Durante todo el proceso, Ana experimenta una carga significativa debido a la falta de herramientas eficientes que faciliten el monitoreo continuo de los pacientes. Esta situación genera estrés y preocupación constante, especialmente en relación con la prevención de caídas y la precisión en la toma de signos vitales. 

![User Journey Mapping](./assets/user-journey-mapping-caregiver.png)

**User Persona:** Gabriel Lopez

El User Journey Mapping de Gabriel López uestra su enfoque en la eficiencia de su personal y la mejora del bienestar de los pacientes. A lo largo de las fases, Gabriel se enfrenta a desafíos como la falta de un protocolo adecuado y la carga de trabajo, pero valora la adopción de nuevas tecnologías para optimizar la atención. Aunque se comunica activamente con los familiares y monitorea a los pacientes mediante cámaras, aún percibe la necesidad de una solución tecnológica que automatice estos procesos, mejorando tanto la atención de los pacientes como la tranquilidad de sus familias y cuidadores.

![User Journey Mapping](./assets/user-journey-mapping-owner.png)

### 2.3.4. Empathy Mapping

**User Persona:** Ana Martinez

En el mapa de empatía de Ana Martinez, observamos que es una persona profundamente comprometida con la seguridad y bienestar de sus pacientes, pero que se siente frustrada por la falta de herramientas tecnológicas que faciliten su labor. A diario, organiza su trabajo mediante horarios y recordatorios, realiza el monitoreo de signos vitales, y ayuda a los pacientes a evitar caídas, mientras escucha tanto las necesidades de estos como el agradecimiento de sus familias. Aunque enfrenta dificultades para garantizar que los pacientes se movilicen con seguridad, ve en la tecnología una oportunidad para optimizar sus tareas y mejorar la calidad de su trabajo.

![Empathy Mapping](./assets/empathy-mapping-ana-martinez.png)

**User Persona:** Gabriel Lopez

En el mapa de empatía de Gabriel Lopez, observamos que está preocupado por cómo gestionar eficientemente la atención de todos sus pacientes y asegurar que todos reciban el cuidado adecuado. Escucha al personal expresar dificultades en el monitoreo y en la atención de los pacientes, así como comentarios sobre la necesidad de mejorar la atención y la comunicación. Observa un entorno con múltiples tareas y una carga de trabajo alta, y nota que las tecnologías pueden ser difíciles de usar para los pacientes. Su objetivo es elevar la calidad del cuidado y aumentar la satisfacción de los pacientes y sus familias.

![Empathy Mapping](./assets/empathy-mapping-gabriel-lopez.png)

### 2.3.5. As-is Scenario Mapping

**User Persona:** Ana Martinez

Este mapa muestra el flujo de trabajo de Ana Martínez en la actualidad, desde el inicio de su turno hasta la comunicación con las familias. En cada fase, Ana realiza tareas como la revisión de su agenda, monitoreo de signos vitales (pulso, presión arterial y temperatura), ajustes en las posiciones de los pacientes para evitar las caídas y la comunicación constante con sus familias. Sus pensamientos están centrados en la organización y la precisión, mientras que sus emociones varían entre alivio cuando todo está en orden, estrés y preocupación constante por la prevención de caídas.

![As-Is Scenario Mapping](./assets/asis-scenario-mapping-ana-martinez.jpg)

**Áreas Positivas**
- Comunicación con las familias
- Stasifacción por hacer bien su trabajo
- Responsabilidad y compromiso con su labor

**Áreas Negativas**
- Información dispersa en diferentes dispositivos
- El monitoreo constante del adulto mayor es desafiante

**Blank Areas**
- Qué tecnologías se pueden emplear para mejorar su trabajo

**User Persona:** Gabriel Lopez

Este mapa muestra el flujo de trabajo de Gabriel Lopez en la actualidad. Sus principales actividades son la asignación de tareas a su personal, supervición y la comunicación con los familiares de sus pacientes. En cada fase realiza tareas como priorizar las tareas de los cuidadores, supervisión a través de cámaras de seguridad e informar a las familias sobre el estado de los adultos mayores. Sus pensamientos están centrados en la efectividad del cuidado que se brinda en su casa de reposo, mientras que sus emociones varían entre frustración, insatisfacción y preocupación. 

![As-Is Scenario Mapping](./assets/asis-scenario-mapping-gabriel-lopez.jpg)

**Áreas Positivas**
- Apertura a la implementación de tecnología
- Compromiso con el bienestar de los pacientes
- Evaluación de oportunidades de mejora

**Áreas Negativas**
- El monitoreo constante del adulto mayor es desafiante
- Las herramientas actuales no son muy eficientes

**Blank Areas**
- Con qué frecuencia presenta problemas con los dispositivos que usa actualmente

## 2.4. Ubiquitous Language

| **Término**      | **Definición**                                           |
|----------------------------|---------------------------------------------------------------------|
| **Elderly**                | Personas mayores que son el objetivo principal del sistema.         |
| **Vital Signs**            | Indicadores de salud como la frecuencia cardíaca y la temperatura. |
| **Caregiver**              | Persona encargada de cuidar y asistir al adulto mayor.               |
| **Health Data**            | Información sobre el estado de salud del adulto mayor. |
| **Emergency Response**     | Acciones tomadas en caso de una situación urgente, como una caída o un cambio en los signos vitales. |
| **Activity Tracking**      | Seguimiento de las actividades del adulto mayor para detectar patrones inusuales. |
| **Safety Protocol**        | Conjunto de reglas y procedimientos para asegurar la seguridad del adulto mayor. |
| **Wellness**               | Estado general de salud y bienestar del adulto mayor.                |
| **Medication Reminders**   | Notificaciones para recordar al adulto mayor que tome sus medicamentos. |
| **Heart Rate**                   | Frecuencia con la que late el corazón, medida en pulsaciones por minuto (ppm).                     |
| **Body Temperature**             | Medida de la temperatura corporal, que puede indicar fiebre o infecciones.                          |
| **Fall Risk**                    | Riesgo de caídas del adulto mayor.     |


---

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

**Segmento 1:** Cuidadores de adultos mayores (Caregivers)

![To-Be Scenario Mapping](./assets/tobe-scenario-mapping-ana-martinez.jpg)

**Segmento 2:** Dueños de casas de reposo (Nursing Home Owners)

![To-Be Scenario Mapping](./assets/tobe-scenario-mapping-gabriel-lopez.jpg)

## 3.2. User Stories

| Epic/Story ID | Título                                   | Descripción                                                                                                                                                         | Criterios de Aceptación                                                                                                                                                                                                                                                                                                                                                   | Relacionado con Epic ID |
|---------------|------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------|
| EP001         | Información del Producto                 | Como Visitante, quiero desplazarme entre las secciones de la Página de Inicio para leer la información sobre el producto.                                           |                                                                                                                                                                                                                                                                                                                                                                          |                         |
| US001         | Beneficios del Producto                  | Como Visitante, quiero leer información sobre los beneficios del producto para evaluar cómo satisface mis necesidades.                                              | **Dado que** el visitante está en la Página de Inicio,<br>**cuando** se desplaza por la sección de beneficios,<br>**entonces** se muestra la información de los beneficios del producto.                                                                                                                                                                                | EP001                   |
| US002         | Modelo de Negocio                        | Como Visitante, quiero leer información sobre el modelo de negocio para evaluar si el producto beneficia mis objetivos y necesidades.                                | **Dado que** el visitante está en la Página de Inicio,<br>**cuando** se desplaza por la sección de modelo de negocio,<br>**entonces** se muestra la información del modelo de negocio del producto.                                                                                                                                                                       | EP001                   |
| US003         | Reseñas de Clientes                      | Como Visitante, quiero leer reseñas de clientes para tomar una decisión informada sobre si comprar o usar un producto o servicio.                                   | **Dado que** el visitante está en la Página de Inicio,<br>**cuando** se desplaza por la sección de reseñas,<br>**entonces** se muestran las reseñas de clientes.<br>**Dado que** no hay reseñas disponibles,<br>**cuando** no se encuentren datos,<br>**entonces** se muestra un mensaje indicando la ausencia de reseñas.                                               | EP001                   |
| US004         | Contactar a Miembros de la Compañía      | Como Visitante, quiero contactar a los miembros de la compañía para solicitar más información o recibir soporte antes de completar una compra.                      | **Dado que** el visitante está en la sección de contacto,<br>**cuando** se envía una solicitud de contacto,<br>**entonces** el sistema muestra un mensaje de confirmación.<br>**Dado que** no se puede enviar la solicitud,<br>**cuando** ocurre un error,<br>**entonces** el sistema muestra un mensaje indicando el problema.                                           | EP001                   |
| US005         | Información de Miembros de la Compañía   | Como Visitante, quiero leer información sobre los miembros de la compañía para entender su experiencia y antecedentes.                                               | **Dado que** el visitante está en la Página de Inicio,<br>**cuando** se desplaza por la sección de miembros de la compañía,<br>**entonces** se muestra la información de cada miembro.<br>**Dado que** no hay información disponible,<br>**cuando** no se encuentran datos,<br>**entonces** el sistema muestra un mensaje indicando la ausencia de información.               | EP001                   |
| EP002         | Monitoreo de Salud                       | Como Caregiver, quiero que la pulsera monitoree la temperatura y el ritmo cardíaco en tiempo real para recibir alertas en caso de valores anormales. |                                                                                                                                                                                                                                                                                                                                                                          |                         |
| US006         | Monitoreo de Temperatura en Tiempo Real  | Como Caregiver, quiero que el sistema monitoree la temperatura en tiempo real para recibir alertas si la temperatura está fuera del rango saludable. | **Dado que** la pulsera está en uso,<br>**cuando** la temperatura es monitoreada,<br>**entonces** el sistema muestra el valor actual y envía una alerta si está fuera del rango predefinido. <br>**Dado que** el rango de temperatura no está configurado,<br>**cuando** el sistema no encuentra un rango,<br>**entonces** se muestra un mensaje solicitando la configuración. | EP002                   |
| US007         | Monitoreo del Ritmo Cardíaco en Tiempo Real | Como Caregiver, quiero que el sistema monitoree el ritmo cardíaco en tiempo real para recibir alertas si está fuera del rango saludable.           | **Dado que** la pulsera está en uso,<br>**cuando** el ritmo cardíaco es monitoreado,<br>**entonces** el sistema muestra el valor actual y envía una alerta si está fuera del rango predefinido. <br>**Dado que** el sensor de ritmo cardíaco no funciona correctamente,<br>**cuando** el sistema detecta un fallo,<br>**entonces** se muestra un mensaje indicando el problema. | EP002                   |
| US008         | Alertas de Salud                         | Como Caregiver, quiero recibir alertas en caso de valores anormales de temperatura o ritmo cardíaco para tomar acciones rápidamente.            | **Dado que** se detectan valores anormales,<br>**cuando** el sistema envía una alerta,<br>**entonces** el cuidador recibe una notificación en su dispositivo móvil. <br>**Dado que** el dispositivo no está vinculado,<br>**cuando** el sistema no puede enviar la alerta,<br>**entonces** se muestra un mensaje solicitando la vinculación.                            | EP002                   |
| US009         | Historial de Datos de Salud              | Como Caregiver, quiero ver el historial de datos de salud para tener un registro completo de la temperatura y ritmo cardíaco a lo largo del tiempo. | **Dado que** el cuidador está en la sección de historial,<br>**cuando** selecciona una fecha específica,<br>**entonces** el sistema muestra el historial con gráficos o tablas de la temperatura y el ritmo cardíaco. <br>**Dado que** no hay datos disponibles,<br>**cuando** se selecciona un rango sin información,<br>**entonces** se muestra un mensaje indicando la ausencia de datos.               | EP002                   |
| US010         | Configuración de Alertas Personalizadas  | Como Caregiver, quiero configurar alertas personalizadas para temperatura y ritmo cardíaco para adaptar las notificaciones a necesidades específicas. | **Dado que** el cuidador está en la sección de configuración,<br>**cuando** se configuran los umbrales de temperatura y ritmo cardíaco,<br>**entonces** el sistema guarda los umbrales personalizados para enviar alertas. <br>**Dado que** se intenta guardar un umbral no válido,<br>**cuando** se ingresa un valor incorrecto,<br>**entonces** se muestra un mensaje de error indicando la configuración incorrecta.    | EP002                   |
| EP003         | Solicitud de Ayuda                       | Como Caregiver, quiero que los usuarios puedan solicitar ayuda rápidamente en caso de necesidad para poder actuar de manera oportuna.            |                                                                                                                                                                                                                                                                                                                                                                          |                         |
| US011         | Envío de Notificación de Emergencia      | Como Caregiver, quiero que se envíe una notificación cuando se presione el botón de emergencia para recibir ayuda rápidamente en caso de necesidad. | **Dado que** el usuario presiona el botón de emergencia,<br>**cuando** se envía la notificación,<br>**entonces** el cuidador recibe un mensaje con la ubicación actual y el estado de emergencia. <br>**Dado que** no se registra la confirmación de recepción,<br>**cuando** el sistema no recibe respuesta,<br>**entonces** intenta reenviar la notificación y registra el fallo.                        | EP003                   |
| US012         | Recepción de Notificaciones de Ayuda     | Como Caregiver, quiero recibir notificaciones en mi dispositivo móvil cuando se presione el botón de emergencia para actuar rápidamente.          | **Dado que** el botón de emergencia es presionado,<br>**cuando** se envía la notificación,<br>**entonces** el cuidador recibe la notificación con la ubicación y detalles de la emergencia. <br>**Dado que** la notificación no es recibida,<br>**cuando** el sistema detecta un fallo,<br>**entonces** informa al administrador y registra el problema.                                                | EP003                   |
| US013         | Gestión de Notificaciones                | Como Caregiver, quiero gestionar las notificaciones recibidas para revisar y dar seguimiento a las alertas de emergencia.                        | **Dado que** el cuidador está en la sección de notificaciones,<br>**cuando** se revisa el historial,<br>**entonces** se muestran todas las notificaciones de emergencia recibidas con sus detalles. <br>**Dado que** no se encuentran notificaciones,<br>**cuando** no hay datos en el historial,<br>**entonces** se muestra un mensaje indicando la ausencia de alertas.                            | EP003                   |
| US014         | Configuración de Alertas de Emergencia   | Como Caregiver, quiero configurar alertas de emergencia para ajustar los parámetros según necesidades y preferencias.                             | **Dado que** el cuidador está en la sección de configuración de emergencias,<br>**cuando** se configuran las preferencias de notificación,<br>**entonces** el sistema guarda y aplica estas preferencias a futuras emergencias. <br>**Dado que** se intenta guardar una configuración no válida,<br>**cuando** se ingresa un valor incorrecto,<br>**entonces** se muestra un mensaje de error solicitando la corrección. | EP003                   |
| EP004         | Gestión de Pulseras                      | Como Nursing Home Owner, quiero gestionar las pulseras alquiladas para actualizar la información de alquiler, rastrear pulseras disponibles y generar informes de uso para la facturación. |                                                                                                                                                                                                                                                                                                                                                                          |                         |
| US015         | Acceso a Datos de Usuario                | Como Nursing Home Owner, quiero acceder a los datos de usuario para generar informes y realizar un seguimiento del uso de las pulseras.                                | **Dado que** el administrador está en la sección de datos de usuario,<br>**cuando** selecciona los datos de temperatura o ritmo cardíaco,<br>**entonces** el sistema muestra el historial del usuario. <br>**Dado que** no hay datos disponibles,<br>**cuando** se selecciona un usuario sin información,<br>**entonces** se muestra un mensaje indicando la ausencia de información.                                   | EP004                   |
| US016         | Gestión de Pulseras Alquiladas           | Como Nursing Home Owner, quiero gestionar las pulseras alquiladas para actualizar información, rastrear su uso y emitir facturas.                                      | **Dado que** el administrador está en la sección de gestión de pulseras,<br>**cuando** se actualiza el estado de una pulsera alquilada,<br>**entonces** el sistema refleja el cambio en el inventario y en la facturación. <br>**Dado que** el inventario no coincide,<br>**cuando** el sistema detecta una discrepancia,<br>**entonces** se muestra un mensaje de error indicando el problema.                    | EP004                   |
| US017         | Visualización de Pulseras Disponibles    | Como Nursing Home Owner, quiero ver una lista de pulseras disponibles para saber cuáles están en alquiler y cuáles están disponibles para nuevos usuarios.             | **Dado que** el administrador está en la sección de pulseras,<br>**cuando** selecciona la opción de pulseras disponibles,<br>**entonces** el sistema muestra una lista de pulseras con su estado actual. <br>**Dado que** la lista no se actualiza,<br>**cuando** el sistema detecta un error,<br>**entonces** muestra un mensaje solicitando la verificación manual.                                | EP004                   |
| US018         | Generación de Informes de Uso            | Como Nursing Home Owner, quiero generar informes sobre el uso de las pulseras para analizar su utilización y rendimiento.                                             | **Dado que** el administrador está en la sección de informes,<br>**cuando** selecciona generar un informe de uso,<br>**entonces** el sistema muestra un informe detallado con la información de uso de las pulseras. <br>**Dado que** no se puede exportar el informe,<br>**cuando** el sistema detecta un fallo,<br>**entonces** muestra un mensaje indicando el problema y solicita un nuevo intento.                      | EP004                   |
| US019         | Monitoreo de Sensores de Pulseras        | Como Nursing Home Owner, quiero monitorear el estado de los sensores de las pulseras para asegurarme de que funcionen correctamente en todo momento.                   | **Dado que** el administrador está en la sección de monitoreo de sensores,<br>**cuando** selecciona una pulsera específica,<br>**entonces** el sistema muestra el estado de sus sensores, incluyendo batería, conectividad y precisión. <br>**Dado que** se detecta una falla,<br>**cuando** el sistema encuentra un problema en el sensor,<br>**entonces** envía una alerta al administrador indicando el fallo. | EP004                   |
| US020         | Asignación de Pulsera a un Usuario       | Como Nursing Home Owner, quiero asignar una pulsera a un nuevo usuario para que pueda comenzar a utilizar el sistema de monitoreo de salud de inmediato.               | **Dado que** el administrador está en la sección de asignación,<br>**cuando** selecciona un nuevo usuario y una pulsera disponible,<br>**entonces** el sistema asigna la pulsera al usuario y actualiza el estado en el inventario. <br>**Dado que** la asignación no se realiza correctamente,<br>**cuando** el sistema detecta un error,<br>**entonces** muestra un mensaje solicitando la verificación manual.                          | EP004                   |
| US021         | Generación de Informes Financieros       | Como Nursing Home Owner, quiero generar informes financieros para analizar los ingresos generados por el alquiler de pulseras.                                        | **Dado que** el administrador está en la sección de informes financieros,<br>**cuando** selecciona generar un informe,<br>**entonces** el sistema muestra un informe financiero detallado con ingresos por alquiler y pagos recibidos. <br>**Dado que** no hay datos en el rango seleccionado,<br>**cuando** el sistema no encuentra información,<br>**entonces** muestra un mensaje indicando la ausencia de información.               | EP004                   |
| US022         | Configuración de Pagos Automatizados     | Como Nursing Home Owner, quiero configurar pagos automatizados para facilitar la gestión de los cobros por el alquiler de pulseras.                                   | **Dado que** el administrador está en la sección de configuración,<br>**cuando** selecciona configurar pagos automáticos,<br>**entonces** el sistema procesa los pagos automáticamente según el intervalo configurado. <br>**Dado que** no se puede procesar un pago,<br>**cuando** el sistema detecta un fallo en el proceso,<br>**entonces** muestra una alerta indicando el problema y solicita la verificación manual.                   | EP004                   |
| US023         | Cancelación de Alquiler de Pulseras      | Como Nursing Home Owner, quiero cancelar el alquiler de una pulsera para liberar la pulsera y actualizar el estado en el inventario.                                   | **Dado que** el administrador está en la sección de gestión de alquileres,<br>**cuando** selecciona cancelar un alquiler,<br>**entonces** el sistema libera la pulsera en el inventario y actualiza el estado del alquiler. <br>**Dado que** no se puede liberar la pulsera,<br>**cuando** el sistema detecta un fallo,<br>**entonces** muestra un mensaje solicitando la verificación manual.                                             | EP004                   |
| US024         | Actualización de Tarifas de Alquiler     | Como Nursing Home Owner, quiero actualizar las tarifas de alquiler de pulseras para reflejar cambios en los costos actuales de alquiler.                              | **Dado que** el administrador está en la sección de tarifas,<br>**cuando** selecciona actualizar una tarifa,<br>**entonces** el sistema aplica la nueva tarifa a futuros alquileres. <br>**Dado que** se intenta aplicar la tarifa retroactivamente,<br>**cuando** el sistema detecta una inconsistencia,<br>**entonces** muestra un mensaje solicitando la verificación manual.                                | EP004                   |
| EP005         | Interfaz de Usuario                      | Como Visitor, Caregiver o Nursing Home Owner, quiero una interfaz fácil de usar para visualizar y entender los datos de la pulsera, acceder a informes y gestionar notificaciones de manera intuitiva.      |                                                                                                                                                                                                                                                                                                                                                                          |                         |
| US025         | Acceso Rápido a Datos de la Pulsera      | Como Caregiver, quiero acceder rápidamente a los datos actuales de la pulsera desde la pantalla principal para ver información de salud sin navegar por múltiples páginas.              | **Dado que** el cuidador está en la pantalla principal de la aplicación,<br>**cuando** abre la aplicación,<br>**entonces** el sistema muestra la temperatura y el ritmo cardíaco actuales sin necesidad de navegar por diferentes menús. <br>**Dado que** no se pueden actualizar los datos en tiempo real,<br>**cuando** el sistema detecta una pérdida de conexión,<br>**entonces** muestra un mensaje indicando el problema y solicita un nuevo intento. | EP005                   |
| US026         | Navegación Intuitiva                     | Como Caregiver, quiero una navegación intuitiva en la aplicación para acceder fácilmente a las diferentes funcionalidades sin confusión.                                             | **Dado que** el cuidador está navegando en la aplicación,<br>**cuando** selecciona una sección,<br>**entonces** puede cambiar de una sección a otra a través de una barra de navegación o botones accesibles. <br>**Dado que** se intenta acceder a una sección no disponible,<br>**cuando** el sistema detecta un acceso indebido,<br>**entonces** muestra un mensaje indicando la opción no habilitada.                                | EP005                   |
| US027         | Visualización Clara de Alertas          | Como Caregiver, quiero que las alertas importantes se destaquen visualmente para identificar rápidamente las notificaciones críticas.                                                 | **Dado que** el cuidador está en la aplicación,<br>**cuando** se recibe una alerta crítica,<br>**entonces** el sistema destaca visualmente la alerta utilizando colores y tamaño de texto. <br>**Dado que** la alerta no se visualiza correctamente,<br>**cuando** el sistema detecta un fallo en la visualización,<br>**entonces** muestra un mensaje indicando el problema y solicita la verificación manual.                              | EP005                   |
| US028         | Personalización de la Interfaz          | Como Caregiver, quiero personalizar algunos aspectos de la interfaz para adaptarla a mis preferencias de visualización.                                                                | **Dado que** el cuidador está en la sección de configuración,<br>**cuando** selecciona opciones de personalización,<br>**entonces** el sistema permite cambiar el esquema de colores y el tamaño de texto. <br>**Dado que** el sistema no guarda las preferencias,<br>**cuando** se intenta guardar la configuración,<br>**entonces** se muestra un mensaje indicando el problema y solicita un nuevo intento.                              | EP005                   |
| US029         | Notificaciones en Tiempo Real           | Como Caregiver, quiero recibir notificaciones en tiempo real sobre cambios en la salud para reaccionar rápidamente en caso de emergencias.                                            | **Dado que** el sistema detecta un cambio significativo en la salud,<br>**cuando** se envía la notificación,<br>**entonces** el cuidador recibe una notificación instantánea en su dispositivo móvil o aplicación web. <br>**Dado que** la notificación no llega al dispositivo,<br>**cuando** el sistema detecta un fallo en la entrega,<br>**entonces** registra el fallo e intenta reenviar la notificación.                    | EP005                   |
| US030         | Resumen Diario de Salud                 | Como Caregiver, quiero recibir un resumen diario del estado de salud para estar informado sobre el bienestar general sin revisar constantemente los datos.                             | **Dado que** el sistema está registrando los datos de salud,<br>**cuando** finaliza el día,<br>**entonces** se genera y envía un resumen diario con los datos de salud clave al usuario. <br>**Dado que** el resumen no se genera correctamente,<br>**cuando** el sistema detecta un problema,<br>**entonces** muestra un mensaje indicando el fallo y solicita la verificación manual.                                           | EP005                   |
| EP006         | Generación de Informes                  | Como Nursing Home Owner, quiero generar informes detallados con los datos de la pulsera para analizar la salud de los usuarios, generar informes de uso y hacer recomendaciones basadas en los datos recopilados. |                                                                                                                                                                                                                                                                                                                                                                          |                         |
| US031         | Generación de Informes de Salud         | Como Nursing Home Owner, quiero generar informes detallados sobre la salud de los usuarios para analizar patrones y tendencias a lo largo del tiempo.                                                       | **Dado que** el administrador está en la sección de informes,<br>**cuando** selecciona un período de tiempo,<br>**entonces** el sistema genera un informe con gráficos y análisis de los datos de salud recopilados. <br>**Dado que** no hay datos en el período seleccionado,<br>**cuando** el sistema detecta la ausencia de información,<br>**entonces** muestra un mensaje indicando la falta de datos.                      | EP006                   |
| US032         | Filtros Avanzados en Informes           | Como Nursing Home Owner, quiero aplicar filtros avanzados al generar informes para obtener la información más relevante de manera rápida y efectiva.                                                        | **Dado que** el administrador está generando un informe,<br>**cuando** selecciona filtros como fecha, tipo de alerta y rango de valores,<br>**entonces** el sistema muestra los datos relevantes basados en los filtros aplicados. <br>**Dado que** los filtros no producen resultados,<br>**cuando** el sistema no encuentra datos coincidentes,<br>**entonces** muestra un mensaje indicando la ausencia de información.         | EP006                   |
| US033         | Análisis de Tendencias de Salud         | Como Nursing Home Owner, quiero ver un análisis de tendencias basado en los datos recopilados para identificar posibles problemas de salud a largo plazo.                                                   | **Dado que** el administrador está en la sección de informes,<br>**cuando** selecciona análisis de tendencias,<br>**entonces** el sistema genera gráficos que muestran patrones y posibles riesgos de salud a partir de los datos de los usuarios. <br>**Dado que** no hay datos suficientes,<br>**cuando** el sistema detecta la ausencia de datos,<br>**entonces** muestra un mensaje indicando la falta de información para el análisis. | EP006                   |
| US034         | Comparación de Datos entre Usuarios     | Como Nursing Home Owner, quiero comparar los datos de salud de múltiples usuarios para identificar patrones comunes o diferencias importantes en sus condiciones de salud.                                  | **Dado que** el administrador tiene múltiples usuarios en el sistema,<br>**cuando** selecciona usuarios específicos,<br>**entonces** el sistema genera un informe comparativo con gráficos y datos fáciles de interpretar. <br>**Dado que** no hay datos suficientes para la comparación,<br>**cuando** el sistema no encuentra información,<br>**entonces** muestra un mensaje indicando la falta de datos para la comparación.     | EP006                   |
| US035         | Exportación de Datos para Análisis Externo| Como Nursing Home Owner, quiero exportar todos los datos de salud en formato bruto para un análisis más detallado con herramientas externas.                                                                | **Dado que** el administrador necesita realizar un análisis externo,<br>**cuando** selecciona exportar datos,<br>**entonces** el sistema permite la exportación de todos los datos de salud en formato CSV o JSON. <br>**Dado que** la exportación no se realiza correctamente,<br>**cuando** el sistema detecta un problema,<br>**entonces** muestra un mensaje indicando el fallo y solicita un nuevo intento.                             | EP006                   |
| EP007         | Desarrollo de API                       | Como desarrollador integrador, quiero una API bien documentada con funcionalidades clave para integrar la aplicación con otros sistemas, gestionar datos de la pulsera, recibir notificaciones y acceder a informes de manera eficiente. |                                                                                                                                                                                                                                                                                                                                                                          |                         |
| TS036         | Implementación de API para Integración  | Como desarrollador, quiero implementar una API para integrar los datos de la pulsera con otros sistemas de monitoreo para asegurar que los datos sean accesibles desde otras plataformas.                                                        | **Dado que** el desarrollador necesita acceder a datos de la pulsera,<br>**cuando** la API recibe una solicitud de datos,<br>**entonces** devuelve los datos de temperatura y ritmo cardíaco en tiempo real. <br>**Dado que** no se permite el acceso,<br>**cuando** la API detecta un problema de acceso,<br>**entonces** muestra un mensaje indicando la falta de acceso a los datos solicitados.                                     | EP007                   |
| TS037         | Creación de Endpoints de Notificación   | Como desarrollador, quiero crear endpoints para gestionar notificaciones en la API para que las alertas de salud se configuren y envíen correctamente.                                                     | **Dado que** el desarrollador está implementando la API,<br>**cuando** se configura una alerta,<br>**entonces** los endpoints permiten la creación, edición y eliminación de notificaciones. <br>**Dado que** no se permiten notificaciones,<br>**cuando** la API detecta un problema,<br>**entonces** muestra un mensaje indicando la falta de acceso a la funcionalidad y solicita un nuevo intento.                          | EP007                   |
| TS038         | Seguridad de la API                     | Como desarrollador, quiero asegurarme de que la API tenga la autenticación y autorización adecuadas para proteger los datos sensibles de los usuarios de la pulsera.                                       | **Dado que** el usuario intenta acceder a los datos de la API,<br>**cuando** se realiza una solicitud,<br>**entonces** la API requiere un token de autenticación válido para acceder a los datos de salud. <br>**Dado que** un usuario intenta acceder sin autenticación,<br>**cuando** la API detecta el acceso no autorizado,<br>**entonces** bloquea la solicitud e informa la necesidad de autenticación.                       | EP007                   |
| TS039         | Documentación de la API                 | Como desarrollador, quiero que la API esté documentada de manera clara y completa para que otros desarrolladores puedan integrarse fácilmente.                                                              | **Dado que** la API está lista para su uso,<br>**cuando** un desarrollador necesita información,<br>**entonces** la documentación incluye ejemplos de uso de todos los endpoints y parámetros disponibles. <br>**Dado que** no se encuentra la documentación completa,<br>**cuando** un desarrollador intenta acceder a un endpoint,<br>**entonces** se muestra un mensaje solicitando la actualización de la documentación.                         | EP007                   |
| TS040         | Optimización del Rendimiento de la API  | Como desarrollador, quiero optimizar la API para que las respuestas sean rápidas y eficientes, mejorando la experiencia del usuario final.                                                                  | **Dado que** la API está en producción,<br>**cuando** se realizan consultas,<br>**entonces** la API tiene tiempos de respuesta inferiores a 200ms. <br>**Dado que** se realizan consultas repetitivas,<br>**cuando** la API detecta patrones de uso,<br>**entonces** utiliza técnicas de caché para mejorar el rendimiento.                                                                                                                | EP007                   |
| EP006         | Autenticación de Usuario                 | Como Visitante, quiero poder iniciar sesión de manera segura en la aplicación para acceder a las funcionalidades personalizadas.                                    |                                                                                                                                                                                                                                                                                                                                                                          |                         |
| US006         | Inicio de Sesión                         | Como Visitante, quiero iniciar sesión utilizando mi correo electrónico y contraseña para acceder a las funcionalidades personalizadas de la aplicación.             | **Dado que** el usuario está en la pantalla de login,<br>**cuando** ingresa su correo y contraseña correctos,<br>**entonces** se permite el acceso a su cuenta y se redirige a la página principal.<br>**Dado que** el usuario ingresa credenciales incorrectas,<br>**cuando** se realiza este error,<br>**entonces** se muestra un mensaje de error indicando la falla en el ingreso. | EP002                   |
| US007         | Recuperación de Contraseña               | Como Visitante, quiero recuperar mi contraseña en caso de haberla olvidado para poder acceder nuevamente a mi cuenta.                                               | **Dado que** el usuario ha olvidado su contraseña,<br>**cuando** selecciona la opción de "Recuperar Contraseña" e ingresa su correo electrónico,<br>**entonces** el sistema envía un enlace de recuperación a su correo.<br>**Dado que** se intenta recuperar con un correo no registrado,<br>**cuando** se produce este error,<br>**entonces** se muestra un mensaje indicando la ausencia de cuenta asociada. | EP002                   |




## 3.3. Impact Mapping
Este Impact Mapping se desarrolló para el bussiness goal de alcanzar 600 usuarios suscritos al plan premium en los próximos 8 meses. Se identificaron dos actores clave: Ana Martínez (Caregiver) y Gabriel López (Nursing Home Owner)

![Impact Mapping](./assets/ImpactMapping1.png)

Este Impact Mapping se desarrolló para el bussiness goal de mejorar la retención de usuarios suscritos en un 20% en 12 meses.. Se identificaron dos actores clave: Ana Martínez (Caregiver) y Gabriel López (Nursing Home Owner)

![Impact Mapping](./assets/ImpactMapping2.png)

## 3.4. Product Backlog

| **Orden** | **User Story Id** | **Título**                                    | **Descripción**                                                                                                                                                                                                                             | **Story Points(1 / 2 / 3 / 5 / 8)** |
|-----------|-------------------|-----------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------|
| 1         | US001             | Beneficios del Producto                       | Como Visitante, quiero leer información sobre los beneficios del producto para evaluar cómo satisface mis necesidades.                                                                                                                     | 2                                  |
| 2         | US002             | Modelo de Negocio                             | Como Visitante, quiero leer información sobre el modelo de negocio para evaluar si el producto beneficia mis objetivos y necesidades.                                                                                                       | 2                                  |
| 3         | US003             | Reseñas de Clientes                           | Como Visitante, quiero leer reseñas de clientes para tomar una decisión informada sobre si comprar o usar un producto o servicio.                                                                                                          | 2                                  |
| 4         | US004             | Contactar a Miembros de la Compañía           | Como Visitante, quiero contactar a los miembros de la compañía para solicitar más información o recibir soporte antes de completar una compra.                                                                                             | 3                                  |
| 5         | US005             | Información de Miembros de la Compañía        | Como Visitante, quiero leer información sobre los miembros de la compañía para entender su experiencia y antecedentes.                                                                                                                      | 3                                  |
| 6         | US006             | Monitoreo de Temperatura en Tiempo Real       | Como Caregiver, quiero que el sistema monitoree la temperatura en tiempo real para recibir alertas si la temperatura está fuera del rango saludable.                                                                                         | 5                                  |
| 7         | US007             | Monitoreo del Ritmo Cardíaco en Tiempo Real   | Como Caregiver, quiero que el sistema monitoree el ritmo cardíaco en tiempo real para recibir alertas si está fuera del rango saludable.                                                                                                    | 5                                  |
| 8         | US008             | Alertas de Salud                              | Como Caregiver, quiero recibir alertas en caso de valores anormales de temperatura o ritmo cardíaco para tomar acciones rápidamente.                                                                                                        | 5                                  |
| 9         | US009             | Historial de Datos de Salud                   | Como Caregiver, quiero ver el historial de datos de salud para tener un registro completo de la temperatura y ritmo cardíaco a lo largo del tiempo.                                                                                         | 5                                  |
| 10        | US010             | Configuración de Alertas Personalizadas       | Como Caregiver, quiero configurar alertas personalizadas para temperatura y ritmo cardíaco para adaptar las notificaciones a necesidades específicas.                                                                                       | 5                                  |
| 11        | US011             | Envío de Notificación de Emergencia           | Como Caregiver, quiero que se envíe una notificación cuando se presione el botón de emergencia para recibir ayuda rápidamente en caso de necesidad.                                                                                          | 3                                  |
| 12        | US012             | Recepción de Notificaciones de Ayuda          | Como Caregiver, quiero recibir notificaciones en mi dispositivo móvil cuando se presione el botón de emergencia para actuar rápidamente.                                                                                                    | 3                                  |
| 13        | US013             | Gestión de Notificaciones                     | Como Caregiver, quiero gestionar las notificaciones recibidas para revisar y dar seguimiento a las alertas de emergencia.                                                                                                                  | 5                                  |
| 14        | US014             | Configuración de Alertas de Emergencia        | Como Caregiver, quiero configurar alertas de emergencia para ajustar los parámetros según necesidades y preferencias.                                                                                                                      | 5                                  |
| 15        | US025             | Acceso Rápido a Datos de la Pulsera           | Como Caregiver, quiero acceder rápidamente a los datos actuales de la pulsera desde la pantalla principal para ver información de salud sin navegar por múltiples páginas.                                                                  | 3                                  |
| 16        | US026             | Navegación Intuitiva                          | Como Caregiver, quiero una navegación intuitiva en la aplicación para acceder fácilmente a las diferentes funcionalidades sin confusión.                                                                                                    | 3                                  |
| 17        | US027             | Visualización Clara de Alertas                | Como Caregiver, quiero que las alertas importantes se destaquen visualmente para identificar rápidamente las notificaciones críticas.                                                                                                       | 3                                  |
| 18        | US028             | Personalización de la Interfaz                | Como Caregiver, quiero personalizar algunos aspectos de la interfaz para adaptarla a mis preferencias de visualización.                                                                                                                     | 3                                  |
| 19        | US029             | Notificaciones en Tiempo Real                 | Como Caregiver, quiero recibir notificaciones en tiempo real sobre cambios en la salud para reaccionar rápidamente en caso de emergencias.                                                                                                   | 5                                  |
| 20        | US030             | Resumen Diario de Salud                       | Como Caregiver, quiero recibir un resumen diario del estado de salud para estar informado sobre el bienestar general sin revisar constantemente los datos.                                                                                   | 5                                  |
| 21        | US015             | Acceso a Datos de Usuario                     | Como Nursing Home Owner, quiero acceder a los datos de usuario para generar informes y realizar un seguimiento del uso de las pulseras.                                                                                                     | 5                                  |
| 22        | US016             | Gestión de Pulseras Alquiladas                | Como Nursing Home Owner, quiero gestionar las pulseras alquiladas para actualizar información, rastrear su uso y emitir facturas.                                                                                                           | 5                                  |
| 23        | US017             | Visualización de Pulseras Disponibles         | Como Nursing Home Owner, quiero ver una lista de pulseras disponibles para saber cuáles están en alquiler y cuáles están disponibles para nuevos usuarios.                                                                                   | 3                                  |
| 24        | US018             | Generación de Informes de Uso                 | Como Nursing Home Owner, quiero generar informes sobre el uso de las pulseras para analizar su utilización y rendimiento.                                                                                                                   | 5                                  |
| 25        | US019             | Monitoreo de Sensores de Pulseras             | Como Nursing Home Owner, quiero monitorear el estado de los sensores de las pulseras para asegurarme de que funcionen correctamente en todo momento.                                                                                        | 5                                  |
| 26        | US020             | Asignación de Pulsera a un Usuario            | Como Nursing Home Owner, quiero asignar una pulsera a un nuevo usuario para que pueda comenzar a utilizar el sistema de monitoreo de salud de inmediato.                                                                                      | 5                                  |
| 27        | US021             | Generación de Informes Financieros            | Como Nursing Home Owner, quiero generar informes financieros para analizar los ingresos generados por el alquiler de pulseras.                                                                                                             | 5                                  |
| 28        | US022             | Configuración de Pagos Automatizados          | Como Nursing Home Owner, quiero configurar pagos automatizados para facilitar la gestión de los cobros por el alquiler de pulseras.                                                                                                         | 5                                  |
| 29        | US023             | Cancelación de Alquiler de Pulseras           | Como Nursing Home Owner, quiero cancelar el alquiler de una pulsera para liberar la pulsera y actualizar el estado en el inventario.                                                                                                         | 5                                  |
| 30        | US024             | Actualización de Tarifas de Alquiler          | Como Nursing Home Owner, quiero actualizar las tarifas de alquiler de pulseras para reflejar cambios en los costos actuales de alquiler.                                                                                                     | 3                                  |
| 31        | US031             | Generación de Informes de Salud               | Como Nursing Home Owner, quiero generar informes detallados sobre la salud de los usuarios para analizar patrones y tendencias a lo largo del tiempo.                                                                                        | 5                                  |
| 32        | US032             | Filtros Avanzados en Informes                 | Como Nursing Home Owner, quiero aplicar filtros avanzados al generar informes para obtener la información más relevante de manera rápida y efectiva.                                                                                          | 3                                  |
| 33        | US033             | Análisis de Tendencias de Salud               | Como Nursing Home Owner, quiero ver un análisis de tendencias basado en los datos recopilados para identificar posibles problemas de salud a largo plazo.                                                                                    | 5                                  |
| 34        | US034             | Comparación de Datos entre Usuarios           | Como Nursing Home Owner, quiero comparar los datos de salud de múltiples usuarios para identificar patrones comunes o diferencias importantes en sus condiciones de salud.                                                                    | 5                                  |
| 35        | US035             | Exportación de Datos para Análisis Externo    | Como Nursing Home Owner, quiero exportar todos los datos de salud en formato bruto para un análisis más detallado con herramientas externas.                                                                                                 | 3                                  |
| 36        | TS036             | Implementación de API para Integración        | Como desarrollador, quiero implementar una API para integrar los datos de la pulsera con otros sistemas de monitoreo para asegurar que los datos sean accesibles desde otras plataformas.                                                    | 5                                  |
| 37        | TS037             | Creación de Endpoints de Notificación         | Como desarrollador, quiero crear endpoints para gestionar notificaciones en la API para que las alertas de salud se configuren y envíen correctamente.                                                                                       | 5                                  |
| 38        | TS038             | Seguridad de la API                           | Como desarrollador, quiero asegurarme de que la API tenga la autenticación y autorización adecuadas para proteger los datos sensibles de los usuarios de la pulsera.                                                                        | 8                                  |
| 39        | TS039             | Documentación de la API                       | Como desarrollador, quiero que la API esté documentada de manera clara y completa para que otros desarrolladores puedan integrarse fácilmente.                                                                                               | 3                                  |
| 40        | TS040             | Optimización del Rendimiento de la API        | Como desarrollador, quiero optimizar la API para que las respuestas sean rápidas y eficientes, mejorando la experiencia del usuario final.                                                                                                    | 5                                  |


# Capítulo IV: Strategic-Level Software Design

## 4.1. Strategic-Level Attribute-Driven Design

### 4.1.1. Event Storming

EventStorming es una técnica colaborativa e iterativa de modelado que permite explorar en profundidad una problemática compleja y de gran escala, facilitando la identificación de la mayor cantidad de detalles y desafíos posibles.

![EventStorming](./assets/EventStorming.png)

Enlace del Miroo para verlo completo:
https://miro.com/app/board/uXjVKldWbQI=/?share_link_id=811519345320

#### 4.1.1.1. Candidate Context Discovery

**Step 1: Unstructured Exploration**

En el primer paso del EventStorming, se inicia con una sesión de lluvia de ideas enfocada en identificar los eventos del dominio relacionados con el negocio en estudio. Es fundamental formular estos eventos en tiempo pasado, describiendo lo que ha ocurrido en el sistema o proceso.

![ES-Step1](./assets/EV-Step1.png)

Realizamos una lluvia de ideas para identificar todos los eventos, datos y acciones relevantes que el sistema IoT para el cuidado de adultos mayores debería manejar utilizando una pulsera inteligente y aplicaciones web. Se incluyeron eventos relacionados con la activación de sensores y monitoreo de signos vitales, como la detección de movimiento, ritmo cardíaco y temperatura, para garantizar el seguimiento de la salud del usuario. También se consideraron acciones del sistema, como envío de alertas, notificaciones a familiares y cuidadores, así como la gestión de cuentas y configuración del dispositivo. Se añadieron posibles fallos en la conexión o en los sensores para asegurar la robustez del sistema ante fallos técnicos. Además, se contemplaron aspectos de gestión de datos y sus actualizaciones en diferentes plataformas, así como la interacción con servicios adicionales como suscripciones y pagos. Estos pos-its reflejan un mapeo inicial de todas las posibles interacciones y eventos que el sistema debería manejar para brindar una solución integral y segura para el cuidado de adultos mayores.

**Step 2: Timelines**

En este segundo paso, se revisan los eventos de dominio generados y se organizan en el orden en que ocurren dentro del dominio. Primero, se debe construir un happy path, es decir, un escenario en el que todo funciona correctamente y el proceso comercial es exitoso. Una vez que se ha completado este camino ideal, se pueden agregar escenarios alternativos que contemplen variaciones, fallos, o situaciones excepcionales.

![ES-Step2-1](./assets/event1.jpg)

![ES-Step2-2](./assets/event2.jpg)

![ES-Step2-3](./assets/event3.jpg)

![ES-Step2-4](./assets/event4.jpg)

![ES-Step2-5](./assets/event5.jpg)

Hemos organizado la información generada en la fase de exploración no estructurada mediante flujos de eventos específicos, identificando así cómo debería reaccionar el sistema ante distintas situaciones relacionadas con el monitoreo de salud y seguridad del adulto mayor. Cada flujo visualiza un conjunto de eventos y acciones correlacionadas, desde la activación de sensores y la medición de parámetros vitales hasta la generación de alertas y la notificación a familiares o cuidadores. Se detallan diferentes escenarios como la detección de movimientos inusuales, alteraciones en la frecuencia cardíaca o temperatura, así como la gestión de fallos en el sistema. Además, se incluye la actualización de datos en distintas plataformas (nube, aplicaciones móviles y web) y la generación de reportes de salud. Este paso permite visualizar las posibles trayectorias que seguiría el sistema en respuesta a cada evento, estableciendo la base para desarrollar un flujo de trabajo eficiente y cohesivo que garantice una respuesta rápida y adecuada a cada situación monitorizada.


**Step 3: Paint Points**

Después de organizar los eventos en una línea de tiempo, aprovechamos esta vista general para identificar puntos de interés a lo largo del proceso. Estos puntos de interés pueden incluir cuellos de botella, pasos manuales que podrían ser automatizados, falta de documentación o carencias de conocimiento del dominio.

![ES-Step3-1](./assets/event6.jpg)

![ES-Step3-2](./assets/event7.jpg)

![ES-Step3-3](./assets/event8.jpg)

![ES-Step3-4](./assets/event9.jpg)

![ES-Step3-5](./assets/event10.jpg)

![ES-Step3-6](./assets/event11.jpg)

Hemos identificado y documentado los puntos críticos y decisiones clave en cada flujo de eventos. Estos flujos se detallan con preguntas clave que deben ser respondidas para garantizar el correcto funcionamiento del sistema, como la forma de detectar un pulso estable, la verificación de un movimiento repentino o la identificación de una temperatura normal. Además, se analiza cómo se registran y actualizan los datos en la nube, y cómo se notifica al cuidador en caso de eventos anómalos. Se incluyen flujos adicionales para la gestión de la conexión de la banda IoT, la configuración y vinculación de cuentas, así como la verificación de usuarios y renovaciones de suscripción. Este paso permite una mayor claridad sobre los requerimientos específicos del sistema, asegurando que se cubran todos los posibles escenarios y puntos de fallo, y se establezcan procesos claros para la toma de decisiones en situaciones críticas, mejorando así la robustez y la confiabilidad de la solución IoT propuesta.

**Step 4: Pivotal Points**

Una vez que tenemos nuestra línea de eventos completa, incluyendo los pain points, buscamos eventos comerciales clave que marquen un cambio en el contexto o en la fase del proceso. Estos se denominan eventos principales y los señalamos con una barra vertical que separa los eventos anteriores de los posteriores a dicho evento.

![ES-Step4-1](./assets/event12.jpg)

![ES-Step4-2](./assets/event13.jpg)

![ES-Step4-3](./assets/event14.jpg)

![ES-Step4-4](./assets/event15.jpg)

![ES-Step4-5](./assets/event16.jpg)

![ES-Step4-6](./assets/event17.jpg)

Hemos identificado los puntos críticos (pivotal points) que son esenciales para la correcta operación y toma de decisiones del sistema IoT de cuidado de adultos mayores. Estos puntos son momentos donde se requiere validar decisiones importantes para garantizar que el sistema funcione de manera adecuada. Por ejemplo, se definieron puntos de verificación como la detección de ritmo cardíaco y temperatura estables, la actualización de datos en la nube y la generación de alertas a cuidadores y familiares. También se incluyeron decisiones sobre la configuración de la banda IoT, la verificación de usuarios y la gestión de suscripciones. Estos puntos críticos permiten asegurar que, ante cualquier eventualidad, el sistema tenga claras las acciones a seguir para brindar una respuesta eficiente y oportuna, minimizando el riesgo de fallos y mejorando la confiabilidad del sistema.

**Step 5: Commands**

En este paso también introducimos los comandos, los cuales describen la causa de un evento o el flujo de eventos. A diferencia de los eventos de dominio, los comandos son expresados en modo imperativo, describiendo las operaciones que deben ejecutarse en el sistema.

![ES-Step5-1](./assets/event18.jpg)

![ES-Step5-2](./assets/event19.jpg)

![ES-Step5-3](./assets/event20.jpg)

![ES-Step5-4](./assets/event21.jpg)

![ES-Step5-5](./assets/event22.jpg)

![ES-Step5-6](./assets/event23.jpg)

Estructuramos las funcionalidades y acciones clave del sistema IoT para el cuidado de adultos mayores, identificando los actores involucrados y sus interacciones con el sistema. Se definieron procesos específicos para la recolección de datos de los sensores, su visualización y almacenamiento en la base de datos, y la generación de alertas en caso de situaciones anómalas. Además, se detallaron los flujos de registro, vinculación y desvinculación de usuarios, cuidadores y familiares, así como la configuración de la banda IoT y su sincronización. Este paso permitió mapear con claridad cómo cada actor interactúa con el sistema y cómo se gestionan los datos críticos, asegurando que todas las funcionalidades necesarias estén integradas para ofrecer una solución completa y eficiente.

**Step 6: Policies**

En este punto, buscamos automation policies (políticas de automatización) que puedan ejecutar estos comandos. Esto significa que un evento específico del dominio desencadena automáticamente la ejecución de un comando. En otras palabras, cuando ocurre un evento determinado, el comando correspondiente se ejecuta de manera automática.

![ES-Step6-1](./assets/event24.jpg)

![ES-Step6-2](./assets/event25.jpg)

![ES-Step6-3](./assets/event26.jpg)

![ES-Step6-4](./assets/event27.jpg)

![ES-Step6-5](./assets/event28.jpg)

![ES-Step6-6](./assets/event29.jpg)

![ES-Step6-7](./assets/event30.jpg)

Definimos y organizamos las políticas de recolección y envío de datos, alertas, registro de usuarios y gestión de suscripciones. Se establecieron los eventos para la activación de sensores, detección de condiciones críticas, generación de alertas y notificaciones a cuidadores y familiares, así como el manejo de fallos de sensores. También se estructuraron los procesos para la creación, verificación y administración de cuentas, y la actualización de planes de suscripción, asegurando una correcta integración y flujo de información en la aplicación.


**Step 7: Read Models**

En este paso, introducimos el modelo de lectura, que es la representación de datos del dominio que un agente utiliza para decidir si debe ejecutar o no un comando. Por esta razón, definimos una vista de datos para cada comando, como monitores del sistema, informes, notificaciones, entre otros.

![ES-Step7-1](./assets/event31.jpg)

![ES-Step7-2](./assets/event32.jpg)

![ES-Step7-3](./assets/event33.jpg)

![ES-Step7-4](./assets/event34.jpg)

![ES-Step7-5](./assets/event35.jpg)

![ES-Step7-6](./assets/event36.jpg)

Identificamos las políticas de negocio y cómo interactúan con los eventos y comandos ya establecidos. Cada política fue colocada en relación con un evento o comando específico, con el objetivo de definir reglas y restricciones que deben cumplirse para la ejecución de ciertas acciones. Estas políticas incluyen aspectos como la recolección de datos, el envío de alertas y el registro de cuentas, garantizando que las operaciones del sistema se realicen bajo ciertos parámetros. Además, se introdujeron políticas para la gestión de registros, suscripciones y actualizaciones de planes, detallando cómo y cuándo deben aplicarse estas reglas en función del contexto y estado del sistema.

**Step 8: External Systems**

A continuación, completamos el modelo incluyendo los sistemas externos. Un sistema externo es cualquier sistema que no pertenece al dominio en el que estamos trabajando. Estos sistemas pueden ejecutar comandos (entrada) o recibir notificaciones sobre eventos (salida).

![ES-Step8](./assets/event37.jpg)

![ES-Step8](./assets/event38.jpg)

![ES-Step8](./assets/event39.jpg)

![ES-Step8](./assets/event40.jpg)

![ES-Step8](./assets/event41.jpg)

![ES-Step8](./assets/event42.jpg)

Incorporamos eventos relacionados con el encendido del equipo y el inicio de la recolección de datos, representados con etiquetas verdes. Además, se añadieron interacciones adicionales para diferentes sistemas de monitoreo, como sensores de movimiento, ritmo cardíaco y temperatura, destacando la política de colección de datos en color morado y la política de alertas en color lila. También se detallaron las acciones de inicio de sesión, enlace y desenlace de familiares y cuidadores, junto con la configuración del dispositivo IoT, resaltando la importancia del menú de navegación y los métodos de autenticación como el sistema de Google. En general, se completó la visualización de procesos desde la recolección de datos hasta la gestión de alertas y la actualización de información en la nube y plataformas web, estructurando el flujo de eventos para cada subsistema involucrado.

**Step 9: Aggregates**

Luego de presentar todos los eventos y comandos, comenzamos a agrupar los conceptos relacionados en agregados, que son las unidades que reciben comandos y generan eventos.

![ES-Step9](./assets/event43.jpg)

![ES-Step9](./assets/event44.jpg)

![ES-Step9](./assets/event45.jpg)

![ES-Step9](./assets/event46.jpg)

![ES-Step9](./assets/event47.jpg)

![ES-Step9](./assets/event48.jpg)

Cada diagrama inicia con la activación del equipo y la recolección de datos correspondientes (frecuencia cardíaca, temperatura, movimiento), procediendo a la detección de eventos normales o anormales. Si se detecta una anomalía, se sigue una política de recolección de datos y de alerta, que conlleva la generación de alertas y notificaciones hacia cuidadores y familiares a través de distintas plataformas (web, aplicación móvil). Además, se introdujo el flujo de inicio de sesión y creación de cuentas para configurar el sistema y asociar cuidadores o familiares con los pacientes, facilitando la personalización de alertas y la administración de las notificaciones.

**Step 10: Bounded Contexts**

Finalmente, identificamos los agregados que están relacionados entre sí y que son relevantes por representar funciones estrechamente vinculadas o porque están conectados según ciertas políticas. Estos grupos de agregados sirven como candidatos naturales para definir los Bounded Contexts (contextos delimitados) dentro del sistema.

![ES-Step10](./assets/EV-Step10.png)

Identificamos y agrupamos los eventos del sistema en diferentes Bounded Contexts para definir áreas funcionales específicas: Device gestiona la interacción con dispositivos y sensores; Edge procesa datos en tiempo real y genera alertas; Notifications envía notificaciones a cuidadores y familiares; Metrics recolecta y gestiona métricas del sistema; Payment maneja suscripciones y pagos; Account se encarga de la autenticación y gestión de usuarios; y Planning (antes Configuration) permite la planificación y configuración del sistema. Estos contextos delimitan claramente las responsabilidades y facilitan la modularidad del sistema.

#### 4.1.1.2 Domain Message Flows Modeling

**Scenario: Detection of Heart Rhythm Abnormality**

![DomianMessage-S1](./assets/DMFM-S1.png)

**Scenario: Activating the Panic Button**

![DomianMessage-S2](./assets/DMFM-S2.png)

**Scenario: Setting up an IoT Band**

![DomianMessage-S3](./assets/DMFM-S3.png)

**Scenario: Daily Health Report Generation**

![DomianMessage-S4](./assets/DMFM-S4.png)

**Scenario: Subscription and Payment Update**

![DomianMessage-S5](./assets/DMFM-S5.png)

Enlace del Miroo para verlo completo:
https://miro.com/app/board/uXjVKhkf7G8=/?share_link_id=819060613108 

#### 4.1.1.3 Bounded Context Canvases

![BC-Device](./assets/BC-Device.png)

![BC-Edge](./assets/BC-Edge.png)

![BC-Notifications](./assets/BC-Notifications.png)

![BC-Metrics](./assets/BC-Metrics.png)

![BC-Payment](./assets/BC-Payment.png)

![BC-Account](./assets/BC-Account.png)

![BC-Configuration](./assets/BC-Configuration.png)

Enlace del Miroo para verlo completo:
https://miro.com/app/board/uXjVKhkFAVo=/?share_link_id=337128963652  


### 4.1.2. Context Mapping

#### Proceso para Crear el Context Mapping y Análisis de Alternativas

##### 1. Pasos para Crear el Context Mapping

###### 1.1. Identificación de los Bounded Contexts
- **Configuration**
- **Notification**
- **Account**
- **Metrics**
- **Payment**
- **Edge**
- **Device**

###### 1.2. Identificación de Relaciones Iniciales
1. **Account** ⟷ **Configuration**: Relación de **Customer/Supplier**.
   - *Account* provee la configuración inicial de usuarios, mientras *Configuration* consume y ajusta las preferencias.
2. **Notification** ⟷ **Device**: Relación de **Conformist**.
   - *Notification* se adapta a las características del *Device* para enviar alertas específicas.
3. **Metrics** ⟷ **Device**: Relación de **Shared Kernel**.
   - Comparten datos comunes sobre el estado y rendimiento del dispositivo.
4. **Payment** ⟷ **Account**: Relación de **Customer/Supplier**.
   - *Account* proporciona la información de facturación y el estado de la suscripción, mientras que *Payment* gestiona los pagos.
5. **Edge** ⟷ **Device**: Relación de **Published Language**.
   - *Edge* se comunica con *Device* utilizando un lenguaje de mensajes estandarizado para gestionar la integración.

##### 2. Análisis de Alternativas y Preguntas Clave

###### 2.1. ¿Qué pasaría si movemos este capability a otro bounded context?
- **Caso Considerado:** Mover la capacidad de gestión de notificaciones desde *Notification* hacia *Account*.
- **Impacto:**
  - *Account* tendría la responsabilidad completa de administrar las preferencias y notificaciones de usuario.
  - Incrementaría el acoplamiento y la complejidad de *Account*.
- **Discusión:**
  - Se recomienda mantener la separación, ya que *Notification* debe ser independiente y responder a eventos de otros contextos.

###### 2.2. ¿Qué pasaría si descomponemos este capability y movemos uno de los sub-capabilities a otro bounded context?
- **Caso Considerado:** Descomponer *Notification* en sub-capabilities como *EmailNotification* y *PushNotification* y mover *EmailNotification* a *Account*.
- **Impacto:**
  - Permitirá a *Account* gestionar las notificaciones relacionadas con el usuario de manera más específica.
  - *PushNotification* seguirá dependiendo de eventos generados por dispositivos.
- **Discusión:**
  - La descomposición permitiría un enfoque más específico en la entrega de notificaciones, pero incrementaría la complejidad de *Account*. Podría ser una buena opción dividirlo en dos bounded contexts independientes, pero no moverlo completamente a *Account*.

###### 2.3. ¿Qué pasaría si partimos el bounded context en múltiples bounded contexts?
- **Caso Considerado:** Partir *Configuration* en *UserPreferences* y *SystemSettings*.
- **Impacto:**
  - Separar las configuraciones específicas del usuario de las configuraciones del sistema permitiría una gestión más eficiente y clara de las configuraciones, evitando la sobrecarga de un solo contexto.
- **Discusión:**
  - Se recomienda realizar esta separación para reducir la complejidad y mejorar la escalabilidad, evitando mezclar configuraciones que puedan tener diferentes ciclos de vida y dependencias.

###### 2.4. ¿Qué pasaría si tomamos este capability de estos 3 contexts y lo usamos para formar un nuevo context?
- **Caso Considerado:** Crear un nuevo contexto llamado *SubscriptionManagement* que combine capacidades de *Account*, *Payment* y *Notification* relacionadas con la gestión de suscripciones y pagos.
- **Impacto:**
  - Centralizaría la lógica de gestión de suscripciones, pagos y notificaciones relacionadas.
  - Reduciría la duplicación y simplificaría la integración de capacidades.
- **Discusión:**
  - La creación de un nuevo contexto es viable y podría simplificar la arquitectura. Se debe evaluar si la complejidad de integración se reduce suficientemente para justificar la creación de este nuevo contexto.

###### 2.5. ¿Qué pasaría si duplicamos una funcionalidad para romper la dependencia?
- **Caso Considerado:** Duplicar la funcionalidad de gestión de dispositivos en *Edge* y *Device* para reducir la dependencia mutua.
- **Impacto:**
  - Rompería la dependencia, pero aumentaría la duplicación de lógica y datos, lo que puede generar inconsistencias.
- **Discusión:**
  - No se recomienda la duplicación, ya que aumentaría la complejidad de mantenimiento. Mejor optar por la utilización de un servicio compartido o una capa anticorrupción.

###### 2.6. ¿Qué pasaría si creamos un shared service para reducir la duplicación entre múltiples bounded contexts?
- **Caso Considerado:** Crear un servicio compartido de notificaciones para *Notification* y *Account*.
- **Impacto:**
  - Reduciría la duplicación en la lógica de envío y manejo de notificaciones, centralizando esta capacidad en un único servicio reutilizable.
- **Discusión:**
  - Se recomienda implementar un servicio compartido de notificaciones que permita reducir la duplicación de lógica y simplifique la integración con otros contextos.

###### 2.7. ¿Qué pasaría si aislamos los core capabilities y movemos los otros a un context aparte?
- **Caso Considerado:** Aislar las capacidades core de monitoreo de salud en *Device* y mover capacidades de gestión de dispositivos a un contexto aparte llamado *DeviceManagement*.
- **Impacto:**
  - Se reduciría la sobrecarga en el contexto de *Device*, permitiendo una mayor flexibilidad y escalabilidad en el manejo de dispositivos.
- **Discusión:**
  - Aislar capacidades core puede mejorar la escalabilidad y el mantenimiento del sistema. Se recomienda implementar esta alternativa para simplificar el contexto *Device*.

##### 3. Alternativa Recomendada de Context Mapping

1. **Crear un contexto independiente de *SubscriptionManagement*** que maneje suscripciones, pagos y notificaciones relacionadas con suscripciones. Esto simplificaría las dependencias entre *Account*, *Payment* y *Notification*.
2. **Separar *Configuration* en *UserPreferences* y *SystemSettings*** para reducir la complejidad al separar configuraciones de usuario y de sistema.
3. **Implementar un servicio compartido de notificaciones** para centralizar la lógica de envío de notificaciones.
4. **Aislar las capacidades core de monitoreo de salud en *Device* y mover la gestión de dispositivos a *DeviceManagement*** para mejorar la escalabilidad y la gestión de dispositivos.

##### 4. Patrones de Relaciones Sugeridos

- **Anti-corruption Layer (ACL):** Para proteger el contexto *Device* de cambios en *DeviceManagement*.
- **Conformist:** Para que *Notification* se adapte a los datos que recibe de *SubscriptionManagement*.
- **Shared Kernel:** Entre *Device* y *Metrics* para compartir información de monitoreo.
- **Customer/Supplier:** Relación entre *Account* y *SubscriptionManagement*.

![ContextMapping](./assets/ContextMapping.png)


### 4.1.3. Software Architecture

#### 4.1.3.1. Software Architecture System Landscape Diagram

![System Landscape Diagram](./assets/context-diagram.png)

#### 4.1.3.2. Software Architecture Context Level Diagrams

![Context Diagram](./assets/context-diagram.png)

#### 4.1.3.3. Software Architecture Container Level Diagrams
En este apartado se presenta un diagrama con una una visión detallada de la arquitectura interna de MIAM, mostrando cómo se organiza el sistema en diferentes contenedores que manejan distintas responsabilidades. Los servicios externos de Google API y Paypal aseguran una experiencia de usuario fluida y segura para la creación de cuentas y la realización de pagos, integrándose perfectamente con la arquitectura del sistema.

**Contenedores Principales del Sistema MIAM:**

- Web Application: Proporciona el contenido estático y sirve como punto de entrada para la Single-Page Application (SPA). Permite a los usuarios ver información relevante y realizar acciones en la plataforma a través del navegador web.
- Single-Page Application (SPA): Permite a los usuarios visualizar alertas, información de salud y configurar dispositivos. Es la interfaz interactiva principal que se ejecuta en el navegador del usuario.
- Mobile Application: Ofrece una versión adaptada de la funcionalidad de la SPA en dispositivos móviles, permitiendo a los usuarios visualizar alertas e información de salud de manera cómoda en sus teléfonos móviles.
- Web API: Maneja las solicitudes de las aplicaciones web y móviles. Proporciona acceso a la lógica de negocio y los datos, actuando como intermediario entre el frontend y las bases de datos en la nube.
- Edge API: Interactúa directamente con los dispositivos IoT y gestiona el almacenamiento de datos locales. Este contenedor está diseñado para operar en el entorno local del centro de cuidadores, reduciendo la latencia y permitiendo respuestas rápidas.
- IoT Application: Gestiona la comunicación y la recopilación de datos desde dispositivos IoT, como pulseras inteligentes utilizadas por los pacientes.
- Flash Memory Database: Almacena datos localmente en el entorno de Edge API para acceso rápido y sin conexión, asegurando la continuidad del servicio incluso en caso de problemas de conectividad.
- Cloud Database: Almacena los datos de la aplicación en la nube. Actúa como el repositorio principal para toda la información relevante de la aplicación.

![Container Diagram](./assets/structurizr-95614-ContainerView.png)

#### 4.1.3..4. Software Architecture Deployment Diagrams
La Web Application se despliega en el Cloud Web Server y entrega el contenido estático al User's Web Browser, que ejecuta la Single-Page Application.
La Mobile Application y la Single-Page Application consultan la Web API para obtener datos y ejecutar lógica de negocio.
La Web API se comunica con la Cloud Database para almacenar y recuperar datos.
La Edge API, desplegada localmente, se comunica con los dispositivos IoT y la Flash Memory Database para gestionar datos en tiempo real y almacenamiento local.
![Deployment Diagram](./assets/structurizr-95614-DeploymentView.png)

## 4.2. Tactical-Level Domain-Driven Design

## 4.2.1. Bounded Context: Device Context

### 4.2.1.1. Domain Layer

#### Entities

1. **Device:**
   - **Descripción:** Representa un dispositivo IoT en el sistema, el cual recopila datos de salud y permite la comunicación con la infraestructura de borde.
   - **Atributos:**
     - `id`: Identificador único del dispositivo.
     - `model`: Modelo del dispositivo.
     - `status`: Estado actual del dispositivo (activo, inactivo).
     - `heartRate`: Frecuencia cardíaca registrada por el dispositivo.
     - `temperature`: Temperatura registrada por el dispositivo.
     - `location`: Ubicación actual del dispositivo.

2. **IoTBand:**
   - **Descripción:** Representa la banda IoT que se usa en el dispositivo para recopilar y transmitir datos de salud.
   - **Atributos:**
     - `id`: Identificador único de la banda.
     - `firmwareVersion`: Versión del firmware de la banda.
     - `status`: Estado actual de la banda (operativa, no operativa).

3. **Configuration:**
   - **Descripción:** Almacena las configuraciones específicas de un dispositivo IoT, como umbrales de alertas y parámetros de monitoreo.
   - **Atributos:**
     - `id`: Identificador único de la configuración.
     - `configName`: Nombre de la configuración.
     - `value`: Valor de la configuración.
     - `Device_id`: Referencia al dispositivo al que pertenece la configuración.

#### Value Objects

1. **DeviceStatus:**
   - **Descripción:** Objeto de valor que representa el estado de un dispositivo. Asegura que el estado cumpla con ciertas reglas de negocio (por ejemplo, solo valores como 'activo' o 'inactivo').
   - **Atributos:**
     - `status`: Estado del dispositivo (activo, inactivo, mantenimiento).

#### Domain Services

1. **DeviceDomainService:**
   - **Descripción:** Contiene la lógica de negocio relacionada con los dispositivos, como el cambio de estado y la verificación de configuraciones.
   - **Métodos:**
     - `updateDeviceStatus(Device device, String status)`: Actualiza el estado del dispositivo después de validar que es un estado permitido.

#### Aggregates y Aggregate Root

1. **DeviceAggregateRoot:**
   - **Justificación:** `Device` es el aggregate root que controla la consistencia y la lógica de negocio de los dispositivos y sus configuraciones. Asegura que las configuraciones aplicadas a un dispositivo sean válidas y consistentes.

#### Repositories (Interfaces)

1. **DeviceRepository:**
   - **Descripción:** Interfaz para interactuar con la base de datos de dispositivos.
   - **Métodos:**
     - `findById(String id)`: Busca un dispositivo por su ID.
     - `save(Device device)`: Guarda o actualiza un dispositivo en la base de datos.
     - `delete(String id)`: Elimina un dispositivo de la base de datos.

2. **IoTBandRepository:**
   - **Descripción:** Interfaz para interactuar con la base de datos de bandas IoT.
   - **Métodos:**
     - `findById(String id)`: Busca una banda por su ID.
     - `save(IoTBand band)`: Guarda o actualiza una banda en la base de datos.
     - `delete(String id)`: Elimina una banda de la base de datos.

3. **ConfigurationRepository:**
   - **Descripción:** Interfaz para interactuar con la base de datos de configuraciones.
   - **Métodos:**
     - `findById(String id)`: Busca una configuración por su ID.
     - `save(Configuration config)`: Guarda o actualiza una configuración en la base de datos.
     - `delete(String id)`: Elimina una configuración de la base de datos.

### 4.2.1.2. Interface Layer

#### Controllers

1. **DeviceController:**
   - **Descripción:** Expone endpoints para la gestión de dispositivos, incluyendo la creación, actualización y recuperación de dispositivos.
   - **Métodos:**
     - `registerDevice(Device device)`: Endpoint para registrar un nuevo dispositivo.
     - `updateDeviceStatus(String id, String status)`: Endpoint para actualizar el estado de un dispositivo.
     - `getDeviceById(String id)`: Endpoint para obtener los detalles de un dispositivo por su ID.

2. **IoTBandController:**
   - **Descripción:** Controlador que gestiona las bandas IoT, permitiendo su registro, actualización y consulta.
   - **Métodos:**
     - `registerIoTBand(IoTBand band)`: Endpoint para registrar una nueva banda IoT.
     - `updateIoTBand(String id, IoTBand band)`: Endpoint para actualizar una banda IoT.
     - `getIoTBandById(String id)`: Endpoint para obtener los detalles de una banda por su ID.

3. **ConfigurationController:**
   - **Descripción:** Controlador que gestiona las configuraciones de dispositivos, permitiendo su creación, actualización y consulta.
   - **Métodos:**
     - `createConfiguration(Configuration configuration)`: Endpoint para crear una nueva configuración.
     - `updateConfiguration(Configuration configuration)`: Endpoint para actualizar una configuración.
     - `getConfigurationById(String id)`: Endpoint para obtener los detalles de una configuración por su ID.

### 4.2.1.3. Application Layer

#### Command Handlers

1. **UpdateDeviceStatusHandler:**
   - **Descripción:** Maneja el comando que actualiza el estado de un dispositivo específico.
   - **Métodos:**
     - `handle(UpdateDeviceStatusCommand command)`: Valida y aplica el comando para actualizar el estado de un dispositivo.

2. **RegisterIoTBandHandler:**
   - **Descripción:** Maneja el comando para registrar una nueva banda IoT en el sistema.
   - **Métodos:**
     - `handle(RegisterIoTBandCommand command)`: Valida y registra una nueva banda IoT en el sistema.

3. **UpdateConfigurationHandler:**
   - **Descripción:** Maneja el comando para actualizar la configuración de un dispositivo específico.
   - **Métodos:**
     - `handle(UpdateConfigurationCommand command)`: Valida y aplica el comando para actualizar la configuración de un dispositivo.

#### Event Handlers

1. **DeviceUpdatedEventHandler:**
   - **Descripción:** Maneja los eventos que se disparan cuando un dispositivo es actualizado, asegurando que cualquier cambio sea procesado adecuadamente.
   - **Métodos:**
     - `handle(DeviceUpdatedEvent event)`: Procesa las acciones necesarias después de que un dispositivo ha sido actualizado.

2. **IoTBandRegisteredEventHandler:**
   - **Descripción:** Maneja los eventos que se disparan cuando se registra una nueva banda IoT, realizando tareas de inicialización.
   - **Métodos:**
     - `handle(IoTBandRegisteredEvent event)`: Ejecuta las acciones necesarias después del registro de una nueva banda IoT.

#### Query Handlers

1. **GetDeviceDetailsHandler:**
   - **Descripción:** Maneja las consultas para obtener los detalles de un dispositivo específico.
   - **Métodos:**
     - `handle(GetDeviceDetailsQuery query)`: Devuelve los detalles del dispositivo solicitado.

2. **GetIoTBandDetailsHandler:**
   - **Descripción:** Maneja las consultas para obtener los detalles de una banda IoT específica.
   - **Métodos:**
     - `handle(GetIoTBandDetailsQuery query)`: Devuelve los detalles de la banda solicitada.

3. **GetConfigurationDetailsHandler:**
   - **Descripción:** Maneja las consultas para obtener los detalles de una configuración específica.
   - **Métodos:**
     - `handle(GetConfigurationDetailsQuery query)`: Devuelve los detalles de la configuración solicitada.

### 4.2.1.4. Infrastructure Layer

#### Repositories (Implementaciones)

1. **DeviceRepositoryImpl:**
   - **Descripción:** Implementación de `DeviceRepository` que define cómo se almacenan y recuperan los dispositivos desde la base de datos.
   - **Métodos:**
     - `findById(String id)`: Implementación para buscar un dispositivo por su ID.
     - `save(Device device)`: Implementación para guardar o actualizar un dispositivo en la base de datos.
     - `delete(String id)`: Implementación para eliminar un dispositivo de la base de datos.

2. **IoTBandRepositoryImpl:**
   - **Descripción:** Implementación de `IoTBandRepository` que define cómo se almacenan y recuperan las bandas IoT desde la base de datos.
   - **Métodos:**
     - `findById(String id)`: Implementación para buscar una banda por su ID.
     - `save(IoTBand band)`: Implementación para guardar o actualizar una banda en la base de datos.
     - `delete(String id)`: Implementación para eliminar una banda de la base de datos.

3. **ConfigurationRepositoryImpl:**
   - **Descripción:** Implementación de `ConfigurationRepository` que define cómo se almacenan y recuperan las configuraciones desde la base de datos.
   - **Métodos:**
     - `findById(String id)`: Implementación para buscar una configuración por su ID.
     - `save(Configuration config)`: Implementación para guardar o actualizar una configuración en la base de datos.
     - `delete(String id)`: Implementación para eliminar una configuración de la base de datos.

### 4.2.1.6. Bounded Context Software Architecture Component Level Diagrams

#### Components (Edge API):

1. **DeviceService Component:**
   - **Descripción:** Componente que encapsula la lógica de negocio relacionada con la gestión de dispositivos. Interactúa con el `DeviceRepository` para registrar y actualizar dispositivos.

2. **IoTBandService Component:**
   - **Descripción:** Componente encargado de la gestión de bandas IoT. Interactúa con el `IoTBandRepository` para gestionar el registro y la actualización de bandas.

3. **ConfigurationService Component:**
   - **Descripción:** Componente que encapsula la lógica de negocio relacionada con la gestión de configuraciones. Interactúa con el `ConfigurationRepository` para registrar y actualizar configuraciones.

![alt text](assets/structurizr-95614-DeviceContext.png)

### 4.2.1.7. Bounded Context Software Architecture Code Level Diagrams

#### 4.2.1.7.1. Bounded Context Domain Layer Class Diagrams

- **Clases importantes:**
  - `Device`
  - `IoTBand`
  - `Configuration`

- **Repositories:**
  - `DeviceRepository`
  - `IoTBandRepository`
  - `ConfigurationRepository`

  ![alt text](assets/device-context-class-diagram.png)

#### 4.2.1.7.2. Bounded Context Database Design Diagram

- **Tablas:**
  - **Device:**
    - Columnas: `id`, `model`, `status`, `Patient_id`.
    - Llave Foránea: `Patient_id`.
  - **IoTBand:**
    - Columnas: `id`, `firmwareVersion`, `status`.
  - **Configuration:**
    - Columnas: `id`, `configName`, `value`, `Device_id`.
    - Llave Foránea: `Device_id`.

![alt text](assets/device_context.png)

- **Relaciones:**
  - `Configuration` se relaciona con `Device` a través de `Device_id`.
  - `Device` puede tener varias configuraciones asociadas.

---

## 4.2.2. Bounded Context: Edge Context

### 4.2.2.1. Domain Layer

#### Entities

1. **Metrics:**
   - **Descripción:** Representa los datos de salud recopilados por un dispositivo, incluyendo frecuencia cardíaca y temperatura.
   - **Atributos:**
     - `id`: Identificador único de las métricas.
     - `averageHeartRate`: Frecuencia cardíaca promedio registrada.
     - `averageTemperature`: Temperatura promedio registrada.
     - `alertsGenerated`: Número de alertas generadas basadas en las métricas.

2. **Patient:**
   - **Descripción:** Representa al paciente al que se le realiza el monitoreo de salud a través del dispositivo IoT.
   - **Atributos:**
     - `id`: Identificador único del paciente.
     - `name`: Nombre del paciente.
     - `age`: Edad del paciente.
     - `address`: Dirección del paciente.
     - `emergencyContact`: Contacto de emergencia para el paciente.

3. **Device:**
   - **Descripción:** Representa un dispositivo IoT en el sistema, utilizado para recopilar datos de salud del paciente.
   - **Atributos:**
     - `id`: Identificador único del dispositivo.
     - `model`: Modelo del dispositivo.
     - `status`: Estado actual del dispositivo (activo, inactivo, en mantenimiento).
     - `Patient_id`: Referencia al paciente al que está asignado el dispositivo.

#### Value Objects

1. **HealthMetric:**
   - **Descripción:** Objeto de valor que representa una métrica de salud específica, como la frecuencia cardíaca o la temperatura. Asegura que las métricas de salud cumplan con los requisitos establecidos.
   - **Atributos:**
     - `metricName`: Nombre de la métrica de salud (por ejemplo, frecuencia cardíaca, temperatura).
     - `value`: Valor de la métrica.

#### Domain Services

1. **MetricsDomainService:**
   - **Descripción:** Contiene la lógica de negocio relacionada con las métricas de salud, como el cálculo de promedios y la generación de alertas.
   - **Métodos:**
     - `calculateAverage(Metric metric)`: Calcula el promedio de una métrica de salud.
     - `generateAlertIfNecessary(Metric metric)`: Genera una alerta si la métrica supera ciertos umbrales.

#### Aggregates y Aggregate Root

1. **PatientAggregateRoot:**
   - **Justificación:** `Patient` es el aggregate root que controla la consistencia y la lógica de negocio de los datos del paciente y sus métricas. Asegura que las métricas asociadas a un paciente sean válidas y consistentes.

#### Repositories (Interfaces)

1. **MetricsRepository:**
   - **Descripción:** Interfaz para interactuar con la base de datos de métricas de salud.
   - **Métodos:**
     - `findById(String id)`: Busca una métrica por su ID.
     - `save(Metric metric)`: Guarda o actualiza una métrica en la base de datos.
     - `delete(String id)`: Elimina una métrica de la base de datos.

2. **PatientRepository:**
   - **Descripción:** Interfaz para interactuar con la base de datos de pacientes.
   - **Métodos:**
     - `findById(String id)`: Busca un paciente por su ID.
     - `save(Patient patient)`: Guarda o actualiza un paciente en la base de datos.
     - `delete(String id)`: Elimina un paciente de la base de datos.

3. **DeviceRepository:**
   - **Descripción:** Interfaz para interactuar con la base de datos de dispositivos.
   - **Métodos:**
     - `findById(String id)`: Busca un dispositivo por su ID.
     - `save(Device device)`: Guarda o actualiza un dispositivo en la base de datos.
     - `delete(String id)`: Elimina un dispositivo de la base de datos.

### 4.2.2.2. Interface Layer

#### Controllers

1. **MetricsController:**
   - **Descripción:** Expone endpoints para la gestión de métricas, permitiendo crear, actualizar y consultar métricas de salud.
   - **Métodos:**
     - `createMetric(Metric metric)`: Endpoint para crear una nueva métrica de salud.
     - `updateMetric(String id, Metric metric)`: Endpoint para actualizar una métrica existente.
     - `getMetricById(String id)`: Endpoint para obtener los detalles de una métrica por su ID.

2. **PatientController:**
   - **Descripción:** Expone endpoints para la gestión de pacientes, permitiendo crear, actualizar y consultar información del paciente.
   - **Métodos:**
     - `registerPatient(Patient patient)`: Endpoint para registrar un nuevo paciente.
     - `updatePatient(String id, Patient patient)`: Endpoint para actualizar la información de un paciente.
     - `getPatientById(String id)`: Endpoint para obtener los detalles de un paciente por su ID.

### 4.2.2.3. Application Layer

#### Command Handlers

1. **UpdateMetricsHandler:**
   - **Descripción:** Maneja el comando para actualizar las métricas de salud de un paciente específico.
   - **Métodos:**
     - `handle(UpdateMetricsCommand command)`: Valida y aplica el comando para actualizar las métricas de salud.

2. **RegisterPatientHandler:**
   - **Descripción:** Maneja el comando para registrar un nuevo paciente en el sistema.
   - **Métodos:**
     - `handle(RegisterPatientCommand command)`: Valida y registra un nuevo paciente en el sistema.

#### Event Handlers

1. **MetricAlertEventHandler:**
   - **Descripción:** Maneja los eventos de alerta generados por métricas de salud. Asegura que las alertas se procesen y se notifique a los contactos de emergencia si es necesario.
   - **Métodos:**
     - `handle(MetricAlertEvent event)`: Procesa las acciones necesarias después de que se genere una alerta basada en las métricas de salud.

#### Query Handlers

1. **GetPatientMetricsHandler:**
   - **Descripción:** Maneja las consultas para obtener las métricas de salud de un paciente específico.
   - **Métodos:**
     - `handle(GetPatientMetricsQuery query)`: Devuelve las métricas de salud del paciente solicitado.

2. **GetDeviceDetailsHandler:**
   - **Descripción:** Maneja las consultas para obtener los detalles de un dispositivo específico.
   - **Métodos:**
     - `handle(GetDeviceDetailsQuery query)`: Devuelve los detalles del dispositivo solicitado.

### 4.2.2.4. Infrastructure Layer

#### Repositories (Implementaciones)

1. **MetricsRepositoryImpl:**
   - **Descripción:** Implementación de `MetricsRepository` que define cómo se almacenan y recuperan las métricas de salud desde la base de datos.
   - **Métodos:**
     - `findById(String id)`: Implementación para buscar una métrica por su ID.
     - `save(Metric metric)`: Implementación para guardar o actualizar una métrica en la base de datos.
     - `delete(String id)`: Implementación para eliminar una métrica de la base de datos.

2. **PatientRepositoryImpl:**
   - **Descripción:** Implementación de `PatientRepository` que define cómo se almacenan y recuperan los pacientes desde la base de datos.
   - **Métodos:**
     - `findById(String id)`: Implementación para buscar un paciente por su ID.
     - `save(Patient patient)`: Implementación para guardar o actualizar un paciente en la base de datos.
     - `delete(String id)`: Implementación para eliminar un paciente de la base de datos.

3. **DeviceRepositoryImpl:**
   - **Descripción:** Implementación de `DeviceRepository` que define cómo se almacenan y recuperan los dispositivos desde la base de datos.
   - **Métodos:**
     - `findById(String id)`: Implementación para buscar un dispositivo por su ID.
     - `save(Device device)`: Implementación para guardar o actualizar un dispositivo en la base de datos.
     - `delete(String id)`: Implementación para eliminar un dispositivo de la base de datos.

### 4.2.2.6. Bounded Context Software Architecture Component Level Diagrams

#### Components (Edge API):

1. **MetricsService Component:**
   - **Descripción:** Componente que encapsula la lógica de negocio relacionada con la gestión de métricas de salud. Interactúa con el `MetricsRepository` para registrar y actualizar métricas.

2. **PatientService Component:**
   - **Descripción:** Componente encargado de la gestión de pacientes. Interactúa con el `PatientRepository` para gestionar el registro y la actualización de pacientes.

3. **DeviceService Component:**
   - **Descripción:** Componente encargado de la gestión de dispositivos IoT. Interactúa con el `DeviceRepository` para gestionar el registro y la actualización de dispositivos.

![alt text](assets/structurizr-95614-EdgeContext.png)


### 4.2.2.7. Bounded Context Software Architecture Code Level Diagrams

#### 4.2.2.7.1. Bounded Context Domain Layer Class Diagrams

- **Clases importantes:**
  - `Metric`
  - `Patient`
  - `Device`

- **Repositories:**
  - `MetricsRepository`
  - `PatientRepository`
  - `DeviceRepository`

   ![alt text](assets/edge-class-diagram.png)

#### 4.2.2.7.2. Bounded Context Database Design Diagram

- **Tablas:**
  - **Metric:**
    - Columnas: `id`, `averageHeartRate`, `averageTemperature`, `alertsGenerated`, `Patient_id`.
    - Llave Foránea: `Patient_id`.
  - **Patient:**
    - Columnas: `id`, `name`, `age`, `address`, `emergencyContact`.
  - **Device:**
    - Columnas: `id`, `model`, `status`, `Patient_id`.
    - Llave Foránea: `Patient_id`.

- **Relaciones:**
  - `Metric` se relaciona con `Patient` a través de `Patient_id`.
  - `Device` se relaciona con `Patient` a través de `Patient_id`.
  - `Patient` puede tener varias métricas y dispositivos asociados.

![alt text](assets/edge_context.png)
---

## 4.2.3. Bounded Context: Notification Context

### 4.2.3.1. Domain Layer

#### Entities

1. **Notification:**
   - **Descripción:** Representa una notificación enviada a los cuidadores y familiares en caso de anomalías detectadas en la salud del paciente.
   - **Atributos:**
     - `id`: Identificador único de la notificación.
     - `message`: Mensaje de la notificación.
     - `notificationType`: Tipo de notificación (emergencia, recordatorio, informe).
     - `sentDate`: Fecha de envío de la notificación.
     - `Caregiver_id`: Referencia al cuidador que recibe la notificación.

2. **Caregiver:**
   - **Descripción:** Representa al cuidador asignado para monitorear la salud del paciente y recibir notificaciones en caso de emergencia.
   - **Atributos:**
     - `id`: Identificador único del cuidador.
     - `name`: Nombre del cuidador.
     - `phone`: Número de teléfono del cuidador.

#### Value Objects

1. **NotificationMessage:**
   - **Descripción:** Objeto de valor que representa el mensaje de una notificación. Asegura que el mensaje cumpla con ciertos requisitos (por ejemplo, longitud máxima, formato adecuado).
   - **Atributos:**
     - `message`: Contenido del mensaje de la notificación.

#### Domain Services

1. **NotificationDomainService:**
   - **Descripción:** Contiene la lógica de negocio relacionada con la gestión de notificaciones, como la validación y el envío de mensajes.
   - **Métodos:**
     - `sendNotification(Notification notification)`: Envía una notificación a un cuidador específico.
     - `validateNotification(Notification notification)`: Valida que la notificación cumpla con los requisitos establecidos.

#### Aggregates y Aggregate Root

1. **NotificationAggregateRoot:**
   - **Justificación:** `Notification` es el aggregate root que controla la consistencia y la lógica de negocio para la gestión de notificaciones. Asegura que las notificaciones sean válidas antes de enviarlas a los cuidadores.

#### Repositories (Interfaces)

1. **NotificationRepository:**
   - **Descripción:** Interfaz para interactuar con la base de datos de notificaciones.
   - **Métodos:**
     - `findById(String id)`: Busca una notificación por su ID.
     - `save(Notification notification)`: Guarda o actualiza una notificación en la base de datos.
     - `delete(String id)`: Elimina una notificación de la base de datos.

2. **CaregiverRepository:**
   - **Descripción:** Interfaz para interactuar con la base de datos de cuidadores.
   - **Métodos:**
     - `findById(String id)`: Busca un cuidador por su ID.
     - `save(Caregiver caregiver)`: Guarda o actualiza un cuidador en la base de datos.
     - `delete(String id)`: Elimina un cuidador de la base de datos.

### 4.2.3.2. Interface Layer

#### Controllers

1. **NotificationController:**
   - **Descripción:** Expone endpoints para la gestión de notificaciones, permitiendo crear, actualizar y consultar notificaciones.
   - **Métodos:**
     - `createNotification(Notification notification)`: Endpoint para crear una nueva notificación.
     - `updateNotification(String id, Notification notification)`: Endpoint para actualizar una notificación existente.
     - `getNotificationById(String id)`: Endpoint para obtener los detalles de una notificación por su ID.

2. **CaregiverController:**
   - **Descripción:** Expone endpoints para la gestión de cuidadores, permitiendo registrar, actualizar y consultar información del cuidador.
   - **Métodos:**
     - `registerCaregiver(Caregiver caregiver)`: Endpoint para registrar un nuevo cuidador.
     - `updateCaregiver(String id, Caregiver caregiver)`: Endpoint para actualizar la información de un cuidador.
     - `getCaregiverById(String id)`: Endpoint para obtener los detalles de un cuidador por su ID.

### 4.2.3.3. Application Layer

#### Command Handlers

1. **SendNotificationHandler:**
   - **Descripción:** Maneja el comando para enviar una notificación a un cuidador específico.
   - **Métodos:**
     - `handle(SendNotificationCommand command)`: Valida y aplica el comando para enviar una notificación.

2. **RegisterCaregiverHandler:**
   - **Descripción:** Maneja el comando para registrar un nuevo cuidador en el sistema.
   - **Métodos:**
     - `handle(RegisterCaregiverCommand command)`: Valida y registra un nuevo cuidador en el sistema.

#### Event Handlers

1. **NotificationSentEventHandler:**
   - **Descripción:** Maneja los eventos que se disparan cuando una notificación es enviada. Asegura que cualquier acción posterior se realice de manera adecuada.
   - **Métodos:**
     - `handle(NotificationSentEvent event)`: Procesa las acciones necesarias después de que una notificación ha sido enviada.

#### Query Handlers

1. **GetNotificationDetailsHandler:**
   - **Descripción:** Maneja las consultas para obtener los detalles de una notificación específica.
   - **Métodos:**
     - `handle(GetNotificationDetailsQuery query)`: Devuelve los detalles de la notificación solicitada.

2. **GetCaregiverDetailsHandler:**
   - **Descripción:** Maneja las consultas para obtener los detalles de un cuidador específico.
   - **Métodos:**
     - `handle(GetCaregiverDetailsQuery query)`: Devuelve los detalles del cuidador solicitado.

### 4.2.3.4. Infrastructure Layer

#### Repositories (Implementaciones)

1. **NotificationRepositoryImpl:**
   - **Descripción:** Implementación de `NotificationRepository` que define cómo se almacenan y recuperan las notificaciones desde la base de datos.
   - **Métodos:**
     - `findById(String id)`: Implementación para buscar una notificación por su ID.
     - `save(Notification notification)`: Implementación para guardar o actualizar una notificación en la base de datos.
     - `delete(String id)`: Implementación para eliminar una notificación de la base de datos.

2. **CaregiverRepositoryImpl:**
   - **Descripción:** Implementación de `CaregiverRepository` que define cómo se almacenan y recuperan los cuidadores desde la base de datos.
   - **Métodos:**
     - `findById(String id)`: Implementación para buscar un cuidador por su ID.
     - `save(Caregiver caregiver)`: Implementación para guardar o actualizar un cuidador en la base de datos.
     - `delete(String id)`: Implementación para eliminar un cuidador de la base de datos.

### 4.2.3.6. Bounded Context Software Architecture Component Level Diagrams

#### Components (Web API):

1. **NotificationService Component:**
   - **Descripción:** Componente que encapsula la lógica de negocio relacionada con la gestión de notificaciones. Interactúa con el `NotificationRepository` para registrar y enviar notificaciones.

2. **CaregiverService Component:**
   - **Descripción:** Componente encargado de la gestión de cuidadores. Interactúa con el `CaregiverRepository` para gestionar el registro y la actualización de cuidadores.


![alt text](assets/structurizr-95614-NotificationContext.png)

### 4.2.3.7. Bounded Context Software Architecture Code Level Diagrams

#### 4.2.3.7.1. Bounded Context Domain Layer Class Diagrams

- **Clases importantes:**
  - `Notification`
  - `Caregiver`

- **Repositories:**
  - `NotificationRepository`
  - `CaregiverRepository`

   ![alt text](assets/notification-class-diagram.png)

#### 4.2.3.7.2. Bounded Context Database Design Diagram

- **Tablas:**
  - **Notification:**
    - Columnas: `id`, `message`, `notificationType`, `sentDate`, `Caregiver_id`.
    - Llave Foránea: `Caregiver_id`.
  - **Caregiver:**
    - Columnas: `id`, `name`, `phone`.

- **Relaciones:**
  - `Notification` se relaciona con `Caregiver` a través de `Caregiver_id`.
  - `Caregiver` puede recibir varias notificaciones.

![alt text](assets/notification_context.png)
---

## 4.2.4. Bounded Context: Metrics Context

### 4.2.4.1. Domain Layer

#### Entities

1. **Metrics:**
   - **Descripción:** Representa los datos de salud recopilados por un dispositivo, incluyendo frecuencia cardíaca y temperatura.
   - **Atributos:**
     - `id`: Identificador único de las métricas.
     - `averageHeartRate`: Frecuencia cardíaca promedio registrada.
     - `averageTemperature`: Temperatura promedio registrada.
     - `alertsGenerated`: Número de alertas generadas basadas en las métricas.
     - `Patient_id`: Referencia al paciente al que pertenecen las métricas.

2. **Patient:**
   - **Descripción:** Representa al paciente al que se le realiza el monitoreo de salud a través del dispositivo IoT.
   - **Atributos:**
     - `id`: Identificador único del paciente.
     - `name`: Nombre del paciente.
     - `age`: Edad del paciente.
     - `address`: Dirección del paciente.
     - `emergencyContact`: Contacto de emergencia para el paciente.

#### Value Objects

1. **HealthMetric:**
   - **Descripción:** Objeto de valor que representa una métrica de salud específica, como la frecuencia cardíaca o la temperatura. Asegura que las métricas de salud cumplan con los requisitos establecidos.
   - **Atributos:**
     - `metricName`: Nombre de la métrica de salud (por ejemplo, frecuencia cardíaca, temperatura).
     - `value`: Valor de la métrica.

#### Domain Services

1. **MetricsDomainService:**
   - **Descripción:** Contiene la lógica de negocio relacionada con las métricas de salud, como el cálculo de promedios y la generación de alertas.
   - **Métodos:**
     - `calculateAverage(Metric metric)`: Calcula el promedio de una métrica de salud.
     - `generateAlertIfNecessary(Metric metric)`: Genera una alerta si la métrica supera ciertos umbrales.

#### Aggregates y Aggregate Root

1. **PatientAggregateRoot:**
   - **Justificación:** `Patient` es el aggregate root que controla la consistencia y la lógica de negocio de los datos del paciente y sus métricas. Asegura que las métricas asociadas a un paciente sean válidas y consistentes.

#### Repositories (Interfaces)

1. **MetricsRepository:**
   - **Descripción:** Interfaz para interactuar con la base de datos de métricas de salud.
   - **Métodos:**
     - `findById(String id)`: Busca una métrica por su ID.
     - `save(Metric metric)`: Guarda o actualiza una métrica en la base de datos.
     - `delete(String id)`: Elimina una métrica de la base de datos.

2. **PatientRepository:**
   - **Descripción:** Interfaz para interactuar con la base de datos de pacientes.
   - **Métodos:**
     - `findById(String id)`: Busca un paciente por su ID.
     - `save(Patient patient)`: Guarda o actualiza un paciente en la base de datos.
     - `delete(String id)`: Elimina un paciente de la base de datos.

### 4.2.4.2. Interface Layer

#### Controllers

1. **MetricsController:**
   - **Descripción:** Expone endpoints para la gestión de métricas, permitiendo crear, actualizar y consultar métricas de salud.
   - **Métodos:**
     - `createMetric(Metric metric)`: Endpoint para crear una nueva métrica de salud.
     - `updateMetric(String id, Metric metric)`: Endpoint para actualizar una métrica existente.
     - `getMetricById(String id)`: Endpoint para obtener los detalles de una métrica por su ID.

2. **PatientController:**
   - **Descripción:** Expone endpoints para la gestión de pacientes, permitiendo crear, actualizar y consultar información del paciente.
   - **Métodos:**
     - `registerPatient(Patient patient)`: Endpoint para registrar un nuevo paciente.
     - `updatePatient(String id, Patient patient)`: Endpoint para actualizar la información de un paciente.
     - `getPatientById(String id)`: Endpoint para obtener los detalles de un paciente por su ID.

### 4.2.4.3. Application Layer

#### Command Handlers

1. **UpdateMetricsHandler:**
   - **Descripción:** Maneja el comando para actualizar las métricas de salud de un paciente específico.
   - **Métodos:**
     - `handle(UpdateMetricsCommand command)`: Valida y aplica el comando para actualizar las métricas de salud.

2. **RegisterPatientHandler:**
   - **Descripción:** Maneja el comando para registrar un nuevo paciente en el sistema.
   - **Métodos:**
     - `handle(RegisterPatientCommand command)`: Valida y registra un nuevo paciente en el sistema.

#### Event Handlers

1. **MetricAlertEventHandler:**
   - **Descripción:** Maneja los eventos de alerta generados por métricas de salud. Asegura que las alertas se procesen y se notifique a los contactos de emergencia si es necesario.
   - **Métodos:**
     - `handle(MetricAlertEvent event)`: Procesa las acciones necesarias después de que se genere una alerta basada en las métricas de salud.

#### Query Handlers

1. **GetPatientMetricsHandler:**
   - **Descripción:** Maneja las consultas para obtener las métricas de salud de un paciente específico.
   - **Métodos:**
     - `handle(GetPatientMetricsQuery query)`: Devuelve las métricas de salud del paciente solicitado.

2. **GetMetricsDetailsHandler:**
   - **Descripción:** Maneja las consultas para obtener los detalles de una métrica específica.
   - **Métodos:**
     - `handle(GetMetricsDetailsQuery query)`: Devuelve los detalles de la métrica solicitada.

### 4.2.4.4. Infrastructure Layer

#### Repositories (Implementaciones)

1. **MetricsRepositoryImpl:**
   - **Descripción:** Implementación de `MetricsRepository` que define cómo se almacenan y recuperan las métricas de salud desde la base de datos.
   - **Métodos:**
     - `findById(String id)`: Implementación para buscar una métrica por su ID.
     - `save(Metric metric)`: Implementación para guardar o actualizar una métrica en la base de datos.
     - `delete(String id)`: Implementación para eliminar una métrica de la base de datos.

2. **PatientRepositoryImpl:**
   - **Descripción:** Implementación de `PatientRepository` que define cómo se almacenan y recuperan los pacientes desde la base de datos.
   - **Métodos:**
     - `findById(String id)`: Implementación para buscar un paciente por su ID.
     - `save(Patient patient)`: Implementación para guardar o actualizar un paciente en la base de datos.
     - `delete(String id)`: Implementación para eliminar un paciente de la base de datos.

### 4.2.4.6. Bounded Context Software Architecture Component Level Diagrams

#### Components (Edge API):

1. **MetricsService Component:**
   - **Descripción:** Componente que encapsula la lógica de negocio relacionada con la gestión de métricas de salud. Interactúa con el `MetricsRepository` para registrar y actualizar métricas.

2. **PatientService Component:** 
   - **Descripción:** Componente encargado de la gestión de información de los pacientes.
Interactúa con el `PatientRepository`.
Cada componente interactúa con sus respectivos repositorios y handlers para ejecutar la lógica de negocio y responder a las solicitudes de forma coherente con el patrón CQRS.


![alt text](assets/structurizr-95614-MetricsContext.png)

### 4.2.4.7. Bounded Context Software Architecture Code Level Diagrams
#### 4.2.4.7.1. Bounded Context Domain Layer Class Diagrams
En esta sección se detallan las clases del Domain Layer, sus atributos, métodos y relaciones. Clases importantes:

**Metrics:**

- `Atributos`: id, averageHeartRate, averageTemperature, alertsGenerated, Patient_id.
- `Métodos`: calculateAverage(), generateAlert(threshold).

**Patient:**
- `Atributos`: id, name, age, address, emergencyContact.
- `Métodos`: updateContact(newContact).

**Repositories:**

`MetricsRepository`, `PatientRepository`.

![alt text](assets/metrics-class-diagram.png)

#### 4.2.4.7.2. Bounded Context Database Design Diagram
En esta sección se define el diseño de la base de datos para persistir las entidades de este contexto.

**Tablas:**

- **Metrics**:
`Columnas`: id, averageHeartRate, averageTemperature, alertsGenerated, Patient_id.
`Llave Foránea`: Patient_id.
- **Patient**:
`Columnas`: id, name, age, address, emergencyContact.
`Relaciones`: Metrics se relaciona con Patient a través de Patient_id.

![alt text](assets/metrics_context.png)

## 4.2.5. Bounded Context: Payment Context

### 4.2.5.1. Domain Layer

#### Entities

1. **Account:**
   - **Descripción:** Representa la cuenta de usuario en el sistema, incluyendo información de contacto y métodos de pago.
   - **Atributos:**
     - `id`: Identificador único de la cuenta.
     - `username`: Nombre de usuario asociado a la cuenta.
     - `password`: Contraseña de la cuenta.
     - `role`: Rol del usuario dentro del sistema.
     - `phoneNumber`: Número de teléfono del usuario.

2. **Payment:**
   - **Descripción:** Representa un pago realizado por el usuario para la suscripción del servicio.
   - **Atributos:**
     - `id`: Identificador único del pago.
     - `amount`: Monto del pago realizado.
     - `paymentDate`: Fecha en la que se realizó el pago.
     - `paymentStatus`: Estado actual del pago (pendiente, completado, fallido).
     - `Account_id`: Referencia a la cuenta asociada al pago.

3. **Subscription:**
   - **Descripción:** Representa una suscripción al servicio que tiene un usuario, incluyendo fechas de inicio y fin, y el plan asociado.
   - **Atributos:**
     - `id`: Identificador único de la suscripción.
     - `startDate`: Fecha de inicio de la suscripción.
     - `endDate`: Fecha de finalización de la suscripción.
     - `status`: Estado de la suscripción (activa, inactiva, cancelada).
     - `Account_id`: Referencia a la cuenta a la que pertenece la suscripción.
     - `Plan_id`: Referencia al plan al que está suscrito el usuario.

4. **Plan:**
   - **Descripción:** Representa un plan de suscripción disponible en el sistema, con sus características y precio.
   - **Atributos:**
     - `id`: Identificador único del plan.
     - `planName`: Nombre del plan de suscripción.
     - `description`: Descripción del plan.
     - `price`: Precio del plan de suscripción.

5. **CreditCard:**
   - **Descripción:** Representa la tarjeta de crédito asociada a una cuenta para realizar los pagos.
   - **Atributos:**
     - `id`: Identificador único de la tarjeta.
     - `number`: Número de la tarjeta de crédito.
     - `cvv`: Código de seguridad de la tarjeta.
     - `expirationDate`: Fecha de expiración de la tarjeta.
     - `Account_id`: Referencia a la cuenta asociada a la tarjeta.

#### Value Objects

1. **PaymentAmount:**
   - **Descripción:** Objeto de valor que representa el monto del pago. Asegura que el monto sea positivo y esté dentro de los límites permitidos.
   - **Atributos:**
     - `amount`: Monto del pago.

2. **SubscriptionStatus:**
   - **Descripción:** Objeto de valor que representa el estado de una suscripción (activa, inactiva, cancelada).
   - **Atributos:**
     - `status`: Estado de la suscripción.

#### Domain Services

1. **PaymentDomainService:**
   - **Descripción:** Contiene la lógica de negocio relacionada con la gestión de pagos, como la validación de montos y la gestión del estado de los pagos.
   - **Métodos:**
     - `processPayment(Payment payment)`: Procesa el pago después de validar que todos los datos son correctos.
     - `validatePaymentAmount(PaymentAmount amount)`: Valida que el monto del pago esté dentro de los límites permitidos.

2. **SubscriptionDomainService:**
   - **Descripción:** Contiene la lógica de negocio relacionada con la gestión de suscripciones, como la activación y cancelación de suscripciones.
   - **Métodos:**
     - `activateSubscription(Subscription subscription)`: Activa una suscripción después de verificar que el pago fue completado.
     - `cancelSubscription(Subscription subscription)`: Cancela una suscripción y gestiona los reembolsos si corresponde.

#### Aggregates y Aggregate Root

1. **AccountAggregateRoot:**
   - **Justificación:** `Account` es el aggregate root que controla la consistencia y la lógica de negocio para la gestión de cuentas, pagos y suscripciones. Asegura que todos los pagos y suscripciones relacionados con una cuenta sean válidos y consistentes.

#### Repositories (Interfaces)

1. **AccountRepository:**
   - **Descripción:** Interfaz para interactuar con la base de datos de cuentas de usuario.
   - **Métodos:**
     - `findById(String id)`: Busca una cuenta por su ID.
     - `save(Account account)`: Guarda o actualiza una cuenta en la base de datos.
     - `delete(String id)`: Elimina una cuenta de la base de datos.

2. **PaymentRepository:**
   - **Descripción:** Interfaz para interactuar con la base de datos de pagos.
   - **Métodos:**
     - `findById(String id)`: Busca un pago por su ID.
     - `save(Payment payment)`: Guarda o actualiza un pago en la base de datos.
     - `delete(String id)`: Elimina un pago de la base de datos.

3. **SubscriptionRepository:**
   - **Descripción:** Interfaz para interactuar con la base de datos de suscripciones.
   - **Métodos:**
     - `findById(String id)`: Busca una suscripción por su ID.
     - `save(Subscription subscription)`: Guarda o actualiza una suscripción en la base de datos.
     - `delete(String id)`: Elimina una suscripción de la base de datos.

4. **PlanRepository:**
   - **Descripción:** Interfaz para interactuar con la base de datos de planes de suscripción.
   - **Métodos:**
     - `findById(String id)`: Busca un plan por su ID.
     - `save(Plan plan)`: Guarda o actualiza un plan en la base de datos.
     - `delete(String id)`: Elimina un plan de la base de datos.

5. **CreditCardRepository:**
   - **Descripción:** Interfaz para interactuar con la base de datos de tarjetas de crédito.
   - **Métodos:**
     - `findById(String id)`: Busca una tarjeta de crédito por su ID.
     - `save(CreditCard creditCard)`: Guarda o actualiza una tarjeta en la base de datos.
     - `delete(String id)`: Elimina una tarjeta de la base de datos.

### 4.2.5.2. Interface Layer

#### Controllers

1. **AccountController:**
   - **Descripción:** Expone endpoints para la gestión de cuentas de usuario, permitiendo registrar, actualizar y consultar cuentas.
   - **Métodos:**
     - `registerAccount(Account account)`: Endpoint para registrar una nueva cuenta.
     - `updateAccount(String id, Account account)`: Endpoint para actualizar la información de una cuenta.
     - `getAccountById(String id)`: Endpoint para obtener los detalles de una cuenta por su ID.

2. **PaymentController:**
   - **Descripción:** Expone endpoints para la gestión de pagos, permitiendo realizar, consultar y actualizar pagos.
   - **Métodos:**
     - `processPayment(Payment payment)`: Endpoint para realizar un pago.
     - `updatePayment(String id, Payment payment)`: Endpoint para actualizar la información de un pago.
     - `getPaymentById(String id)`: Endpoint para obtener los detalles de un pago por su ID.

3. **SubscriptionController:**
   - **Descripción:** Expone endpoints para la gestión de suscripciones, permitiendo registrar, actualizar y consultar suscripciones.
   - **Métodos:**
     - `createSubscription(Subscription subscription)`: Endpoint para crear una nueva suscripción.
     - `updateSubscription(String id, Subscription subscription)`: Endpoint para actualizar la información de una suscripción.
     - `getSubscriptionById(String id)`: Endpoint para obtener los detalles de una suscripción por su ID.

4. **PlanController:**
   - **Descripción:** Expone endpoints para la gestión de planes de suscripción, permitiendo registrar, actualizar y consultar planes.
   - **Métodos:**
     - `createPlan(Plan plan)`: Endpoint para crear un nuevo plan de suscripción.
     - `updatePlan(String id, Plan plan)`: Endpoint para actualizar la información de un plan.
     - `getPlanById(String id)`: Endpoint para obtener los detalles de un plan por su ID.

### 4.2.5.3. Application Layer

#### Command Handlers

1. **ProcessPaymentHandler:**
   - **Descripción:** Maneja el comando para procesar un pago en el sistema.
   - **Métodos:**
     - `handle(ProcessPaymentCommand command)`: Valida y aplica el comando para procesar el pago.

2. **CreateSubscriptionHandler:**
   - **Descripción:** Maneja el comando para crear una nueva suscripción en el sistema.
   - **Métodos:**
     - `handle(CreateSubscriptionCommand command)`: Valida y crea una nueva suscripción en el sistema.

3. **CreateAccountHandler:**
   - **Descripción:** Maneja el comando para registrar una nueva cuenta en el sistema.
   - **Métodos:**
     - `handle(CreateAccountCommand command)`: Valida y crea una nueva cuenta en el sistema.

4. **CreatePlanHandler:**
   - **Descripción:** Maneja el comando para registrar un nuevo plan de suscripción en el sistema.
   - **Métodos:**
     - `handle(CreatePlanCommand command)`: Valida y crea un nuevo plan en el sistema.

#### Event Handlers

1. **PaymentProcessedEventHandler:**
   - **Descripción:** Maneja los eventos que se disparan cuando un pago ha sido procesado, actualizando el estado de la suscripción asociada.
   - **Métodos:**
     - `handle(PaymentProcessedEvent event)`: Procesa las acciones necesarias después de que un pago ha sido procesado.

2. **SubscriptionCreatedEventHandler:**
   - **Descripción:** Maneja los eventos que se disparan cuando se crea una nueva suscripción.
   - **Métodos:**
     - `handle(SubscriptionCreatedEvent event)`: Ejecuta las acciones necesarias después de la creación de una suscripción.

#### Query Handlers

1. **GetAccountDetailsHandler:**
   - **Descripción:** Maneja las consultas para obtener los detalles de una cuenta específica.
   - **Métodos:**
     - `handle(GetAccountDetailsQuery query)`: Devuelve los detalles de la cuenta solicitada.

2. **GetPaymentDetailsHandler:**
   - **Descripción:** Maneja las consultas para obtener los detalles de un pago específico.
   - **Métodos:**
     - `handle(GetPaymentDetailsQuery query)`: Devuelve los detalles del pago solicitado.

3. **GetSubscriptionDetailsHandler:**
   - **Descripción:** Maneja las consultas para obtener los detalles de una suscripción específica.
   - **Métodos:**
     - `handle(GetSubscriptionDetailsQuery query)`: Devuelve los detalles de la suscripción solicitada.

4. **GetPlanDetailsHandler:**
   - **Descripción:** Maneja las consultas para obtener los detalles de un plan específico.
   - **Métodos:**
     - `handle(GetPlanDetailsQuery query)`: Devuelve los detalles del plan solicitado.

### 4.2.5.4. Infrastructure Layer

#### Repositories (Implementaciones)

1. **AccountRepositoryImpl:**
   - **Descripción:** Implementación de `AccountRepository` que define cómo se almacenan y recuperan las cuentas desde la base de datos.
   - **Métodos:**
     - `findById(String id)`: Implementación para buscar una cuenta por su ID.
     - `save(Account account)`: Implementación para guardar o actualizar una cuenta en la base de datos.
     - `delete(String id)`: Implementación para eliminar una cuenta de la base de datos.

2. **PaymentRepositoryImpl:**
   - **Descripción:** Implementación de `PaymentRepository` que define cómo se almacenan y recuperan los pagos desde la base de datos.
   - **Métodos:**
     - `findById(String id)`: Implementación para buscar un pago por su ID.
     - `save(Payment payment)`: Implementación para guardar o actualizar un pago en la base de datos.
     - `delete(String id)`: Implementación para eliminar un pago de la base de datos.

3. **SubscriptionRepositoryImpl:**
   - **Descripción:** Implementación de `SubscriptionRepository` que define cómo se almacenan y recuperan las suscripciones desde la base de datos.
   - **Métodos:**
     - `findById(String id)`: Implementación para buscar una suscripción por su ID.
     - `save(Subscription subscription)`: Implementación para guardar o actualizar una suscripción en la base de datos.
     - `delete(String id)`: Implementación para eliminar una suscripción de la base de datos.

4. **PlanRepositoryImpl:**
   - **Descripción:** Implementación de `PlanRepository` que define cómo se almacenan y recuperan los planes desde la base de datos.
   - **Métodos:**
     - `findById(String id)`: Implementación para buscar un plan por su ID.
     - `save(Plan plan)`: Implementación para guardar o actualizar un plan en la base de datos.
     - `delete(String id)`: Implementación para eliminar un plan de la base de datos.

5. **CreditCardRepositoryImpl:**
   - **Descripción:** Implementación de `CreditCardRepository` que define cómo se almacenan y recuperan las tarjetas de crédito desde la base de datos.
   - **Métodos:**
     - `findById(String id)`: Implementación para buscar una tarjeta de crédito por su ID.
     - `save(CreditCard creditCard)`: Implementación para guardar o actualizar una tarjeta en la base de datos.
     - `delete(String id)`: Implementación para eliminar una tarjeta de la base de datos.

### 4.2.5.6. Bounded Context Software Architecture Component Level Diagrams

#### Components (Web API):

1. **PaymentService Component:**
   - **Descripción:** Componente que encapsula la lógica de negocio relacionada con la gestión de pagos. Interactúa con el `PaymentRepository` para registrar y actualizar pagos.

2. **SubscriptionService Component:**
   - **Descripción:** Componente encargado de la gestión de suscripciones. Interactúa con el `SubscriptionRepository` para gestionar el registro y la actualización de suscripciones.

3. **AccountService Component:**
   - **Descripción:** Componente encargado de la gestión de cuentas de usuario. Interactúa con el `AccountRepository` para gestionar el registro y la actualización de cuentas.

4. **PlanService Component:**
   - **Descripción:** Componente encargado de la gestión de planes de suscripción. Interactúa con el `PlanRepository` para gestionar el registro y la actualización de planes.

![PaymentContext](assets/structurizr-95614-PaymentContext.png)


### 4.2.5.7. Bounded Context Software Architecture Code Level Diagrams

#### 4.2.5.7.1. Bounded Context Domain Layer Class Diagrams

- **Clases importantes:**
  - `Account`
  - `Payment`
  - `Subscription`
  - `Plan`
  - `CreditCard`

- **Repositories:**
  - `AccountRepository`
  - `PaymentRepository`
  - `SubscriptionRepository`
  - `PlanRepository`
  - `CreditCardRepository`

![alt text](assets/payment-class-diagram.png)

#### 4.2.5.7.2. Bounded Context Database Design Diagram

- **Tablas:**
  - **Account:**
    - Columnas: `id`, `username`, `password`, `role`, `phoneNumber`.
  - **Payment:**
    - Columnas: `id`, `amount`, `paymentDate`, `paymentStatus`, `Account_id`.
    - Llave Foránea: `Account_id`.
  - **Subscription:**
    - Columnas: `id`, `startDate`, `endDate`, `status`, `Account_id`, `Plan_id`.
    - Llave Foránea: `Account_id`, `Plan_id`.
  - **Plan:**
    - Columnas: `id`, `planName`, `description`, `price`.
  - **CreditCard:**
    - Columnas: `id`, `number`, `cvv`, `expirationDate`, `Account_id`.
    - Llave Foránea: `Account_id`.

- **Relaciones:**
  - `Payment` se relaciona con `Account` a través de `Account_id`.
  - `Subscription` se relaciona con `Account` y `Plan` a través de `Account_id` y `Plan_id`.
  - `CreditCard` se relaciona con `Account` a través de `Account_id`.

![alt text](assets/payment_context.jpg)
---

## 4.2.6. Bounded Context: Configuration Context

### 4.2.6.1. Domain Layer

#### Entities

1. **Configuration:**
   - **Descripción:** Representa las configuraciones específicas de un dispositivo IoT, como umbrales de alertas y parámetros de monitoreo.
   - **Atributos:**
     - `id`: Identificador único de la configuración.
     - `configName`: Nombre de la configuración.
     - `value`: Valor de la configuración.
     - `Device_id`: Referencia al dispositivo al que pertenece la configuración.

2. **Device:**
   - **Descripción:** Representa un dispositivo IoT en el sistema, utilizado para recopilar datos de salud del paciente.
   - **Atributos:**
     - `id`: Identificador único del dispositivo.
     - `model`: Modelo del dispositivo.
     - `status`: Estado actual del dispositivo (activo, inactivo).
     - `location`: Ubicación del dispositivo.

#### Value Objects

1. **ConfigParameter:**
   - **Descripción:** Objeto de valor que representa un parámetro de configuración específico. Asegura que el valor del parámetro esté dentro de los límites permitidos.
   - **Atributos:**
     - `name`: Nombre del parámetro.
     - `value`: Valor del parámetro.

#### Domain Services

1. **ConfigurationDomainService:**
   - **Descripción:** Contiene la lógica de negocio relacionada con la gestión de configuraciones, como la validación de parámetros y la aplicación de cambios.
   - **Métodos:**
     - `applyConfiguration(Device device, Configuration config)`: Aplica una configuración a un dispositivo después de validar que todos los parámetros son correctos.
     - `validateConfigParameter(ConfigParameter param)`: Valida que un parámetro de configuración esté dentro de los límites permitidos.

#### Aggregates y Aggregate Root

1. **ConfigurationAggregateRoot:**
   - **Justificación:** `Configuration` es el aggregate root que controla la consistencia y la lógica de negocio para la gestión de configuraciones. Asegura que todas las configuraciones aplicadas a un dispositivo sean válidas y consistentes.

#### Repositories (Interfaces)

1. **ConfigurationRepository:**
   - **Descripción:** Interfaz para interactuar con la base de datos de configuraciones.
   - **Métodos:**
     - `findById(String id)`: Busca una configuración por su ID.
     - `save(Configuration config)`: Guarda o actualiza una configuración en la base de datos.
     - `delete(String id)`: Elimina una configuración de la base de datos.

2. **DeviceRepository:**
   - **Descripción:** Interfaz para interactuar con la base de datos de dispositivos.
   - **Métodos:**
     - `findById(String id)`: Busca un dispositivo por su ID.
     - `save(Device device)`: Guarda o actualiza un dispositivo en la base de datos.
     - `delete(String id)`: Elimina un dispositivo de la base de datos.

### 4.2.6.2. Interface Layer

#### Controllers

1. **ConfigurationController:**
   - **Descripción:** Expone endpoints para la gestión de configuraciones, permitiendo crear, actualizar y consultar configuraciones.
   - **Métodos:**
     - `createConfiguration(Configuration configuration)`: Endpoint para crear una nueva configuración.
     - `updateConfiguration(String id, Configuration configuration)`: Endpoint para actualizar una configuración existente.
     - `getConfigurationById(String id)`: Endpoint para obtener los detalles de una configuración por su ID.

2. **DeviceController:**
   - **Descripción:** Expone endpoints para la gestión de dispositivos, permitiendo crear, actualizar y consultar dispositivos.
   - **Métodos:**
     - `registerDevice(Device device)`: Endpoint para registrar un nuevo dispositivo.
     - `updateDeviceStatus(String id, String status)`: Endpoint para actualizar el estado de un dispositivo.
     - `getDeviceById(String id)`: Endpoint para obtener los detalles de un dispositivo por su ID.

### 4.2.6.3. Application Layer

#### Command Handlers

1. **UpdateConfigurationHandler:**
   - **Descripción:** Maneja el comando para actualizar una configuración de un dispositivo específico.
   - **Métodos:**
     - `handle(UpdateConfigurationCommand command)`: Valida y aplica el comando para actualizar la configuración.

2. **RegisterDeviceHandler:**
   - **Descripción:** Maneja el comando para registrar un nuevo dispositivo en el sistema.
   - **Métodos:**
     - `handle(RegisterDeviceCommand command)`: Valida y registra un nuevo dispositivo en el sistema.

#### Event Handlers

1. **ConfigurationUpdatedEventHandler:**
   - **Descripción:** Maneja los eventos que se disparan cuando se actualiza una configuración. Asegura que cualquier cambio sea procesado adecuadamente.
   - **Métodos:**
     - `handle(ConfigurationUpdatedEvent event)`: Procesa las acciones necesarias después de que una configuración ha sido actualizada.

2. **DeviceRegisteredEventHandler:**
   - **Descripción:** Maneja los eventos que se disparan cuando se registra un nuevo dispositivo.
   - **Métodos:**
     - `handle(DeviceRegisteredEvent event)`: Ejecuta las acciones necesarias después del registro de un dispositivo.

#### Query Handlers

1. **GetConfigurationDetailsHandler:**
   - **Descripción:** Maneja las consultas para obtener los detalles de una configuración específica.
   - **Métodos:**
     - `handle(GetConfigurationDetailsQuery query)`: Devuelve los detalles de la configuración solicitada.

2. **GetDeviceDetailsHandler:**
   - **Descripción:** Maneja las consultas para obtener los detalles de un dispositivo específico.
   - **Métodos:**
     - `handle(GetDeviceDetailsQuery query)`: Devuelve los detalles del dispositivo solicitado.

### 4.2.6.4. Infrastructure Layer

#### Repositories (Implementaciones)

1. **ConfigurationRepositoryImpl:**
   - **Descripción:** Implementación de `ConfigurationRepository` que define cómo se almacenan y recuperan las configuraciones desde la base de datos.
   - **Métodos:**
     - `findById(String id)`: Implementación para buscar una configuración por su ID.
     - `save(Configuration config)`: Implementación para guardar o actualizar una configuración en la base de datos.
     - `delete(String id)`: Implementación para eliminar una configuración de la base de datos.

2. **DeviceRepositoryImpl:**
   - **Descripción:** Implementación de `DeviceRepository` que define cómo se almacenan y recuperan los dispositivos desde la base de datos.
   - **Métodos:**
     - `findById(String id)`: Implementación para buscar un dispositivo por su ID.
     - `save(Device device)`: Implementación para guardar o actualizar un dispositivo en la base de datos.
     - `delete(String id)`: Implementación para eliminar un dispositivo de la base de datos.

### 4.2.6.6. Bounded Context Software Architecture Component Level Diagrams

#### Components (Edge API):

1. **ConfigurationService Component:**
   - **Descripción:** Componente que encapsula la lógica de negocio relacionada con la gestión de configuraciones. Interactúa con el `ConfigurationRepository` para registrar y actualizar configuraciones.

2. **DeviceService Component:**
   - **Descripción:** Componente encargado de la gestión de dispositivos IoT. Interactúa con el `DeviceRepository` para gestionar el registro y la actualización de dispositivos.

![ConfigurationContext](assets/structurizr-95614-ConfigurationContext.png)

### 4.2.6.7. Bounded Context Software Architecture Code Level Diagrams

#### 4.2.6.7.1. Bounded Context Domain Layer Class Diagrams

- **Clases importantes:**
  - `Configuration`
  - `Device`

- **Repositories:**
  - `ConfigurationRepository`
  - `DeviceRepository`

![alt text](assets/configuration-class-diagram.png)

#### 4.2.6.7.2. Bounded Context Database Design Diagram

- **Tablas:**
  - **Configuration:**
    - Columnas: `id`, `configName`, `value`, `Device_id`.
    - Llave Foránea: `Device_id`.
  - **Device:**
    - Columnas: `id`, `model`, `status`, `location`.

- **Relaciones:**
  - `Configuration` se relaciona con `Device` a través de `Device_id`.
  - `Device` puede tener varias configuraciones asociadas.

![alt text](assets/configuration_context.png)

## 4.2.7. Bounded Context: Account Context

### 4.2.7.1. Domain Layer

#### Entities

1. **Account:**
   - **Descripción:** Representa la cuenta de usuario en el sistema, incluyendo información personal, roles y métodos de pago.
   - **Atributos:**
     - `id`: Identificador único de la cuenta.
     - `username`: Nombre de usuario asociado a la cuenta.
     - `password`: Contraseña de la cuenta.
     - `email`: Dirección de correo electrónico asociada a la cuenta.
     - `phoneNumber`: Número de teléfono del usuario.
     - `role`: Rol del usuario dentro del sistema.

2. **Role:**
   - **Descripción:** Define los roles de usuario dentro del sistema, como administrador, cuidador, etc.
   - **Atributos:**
     - `id`: Identificador único del rol.
     - `roleName`: Nombre del rol (por ejemplo, Admin, Caregiver).
     - `description`: Descripción del rol y sus permisos.

3. **Patient:**
   - **Descripción:** Representa al paciente que es monitoreado mediante la plataforma.
   - **Atributos:**
     - `id`: Identificador único del paciente.
     - `name`: Nombre del paciente.
     - `age`: Edad del paciente.
     - `address`: Dirección del paciente.
     - `emergencyContact`: Contacto de emergencia para el paciente.
     - `Account_id`: Referencia a la cuenta a la que pertenece el paciente.

4. **Caregiver:**
   - **Descripción:** Representa a la persona encargada de cuidar al paciente, que tiene acceso a la información de salud del paciente.
   - **Atributos:**
     - `id`: Identificador único del cuidador.
     - `name`: Nombre del cuidador.
     - `phone`: Número de teléfono del cuidador.
     - `address`: Dirección del cuidador.
     - `Account_id`: Referencia a la cuenta a la que pertenece el cuidador.

#### Value Objects

1. **ContactInformation:**
   - **Descripción:** Objeto de valor que encapsula la información de contacto de un usuario, asegurando que los datos como el correo y el teléfono sean válidos.
   - **Atributos:**
     - `email`: Dirección de correo electrónico válida.
     - `phoneNumber`: Número de teléfono válido.

#### Domain Services

1. **AccountDomainService:**
   - **Descripción:** Contiene la lógica de negocio relacionada con la gestión de cuentas, como la verificación de roles y la actualización de información.
   - **Métodos:**
     - `verifyRole(Account account, String role)`: Verifica si una cuenta tiene un rol específico.
     - `updateContactInformation(Account account, ContactInformation contactInfo)`: Actualiza la información de contacto de la cuenta.

#### Aggregates y Aggregate Root

1. **AccountAggregateRoot:**
   - **Justificación:** `Account` es el aggregate root que controla la consistencia y la lógica de negocio de los usuarios y sus roles. Asegura que todos los roles y datos de contacto relacionados con una cuenta sean válidos y consistentes.

#### Repositories (Interfaces)

1. **AccountRepository:**
   - **Descripción:** Interfaz para interactuar con la base de datos de cuentas de usuario.
   - **Métodos:**
     - `findById(String id)`: Busca una cuenta por su ID.
     - `save(Account account)`: Guarda o actualiza una cuenta en la base de datos.
     - `delete(String id)`: Elimina una cuenta de la base de datos.

2. **RoleRepository:**
   - **Descripción:** Interfaz para interactuar con la base de datos de roles.
   - **Métodos:**
     - `findById(String id)`: Busca un rol por su ID.
     - `save(Role role)`: Guarda o actualiza un rol en la base de datos.
     - `delete(String id)`: Elimina un rol de la base de datos.

3. **PatientRepository:**
   - **Descripción:** Interfaz para interactuar con la base de datos de pacientes.
   - **Métodos:**
     - `findById(String id)`: Busca un paciente por su ID.
     - `save(Patient patient)`: Guarda o actualiza un paciente en la base de datos.
     - `delete(String id)`: Elimina un paciente de la base de datos.

4. **CaregiverRepository:**
   - **Descripción:** Interfaz para interactuar con la base de datos de cuidadores.
   - **Métodos:**
     - `findById(String id)`: Busca un cuidador por su ID.
     - `save(Caregiver caregiver)`: Guarda o actualiza un cuidador en la base de datos.
     - `delete(String id)`: Elimina un cuidador de la base de datos.

### 4.2.7.2. Interface Layer

#### Controllers

1. **AccountController:**
   - **Descripción:** Expone endpoints para la gestión de cuentas de usuario, permitiendo registrar, actualizar y consultar cuentas.
   - **Métodos:**
     - `registerAccount(Account account)`: Endpoint para registrar una nueva cuenta.
     - `updateAccount(String id, Account account)`: Endpoint para actualizar la información de una cuenta.
     - `getAccountById(String id)`: Endpoint para obtener los detalles de una cuenta por su ID.

2. **RoleController:**
   - **Descripción:** Expone endpoints para la gestión de roles de usuario, permitiendo registrar, actualizar y consultar roles.
   - **Métodos:**
     - `createRole(Role role)`: Endpoint para crear un nuevo rol.
     - `updateRole(String id, Role role)`: Endpoint para actualizar la información de un rol.
     - `getRoleById(String id)`: Endpoint para obtener los detalles de un rol por su ID.

3. **PatientController:**
   - **Descripción:** Expone endpoints para la gestión de pacientes, permitiendo registrar, actualizar y consultar pacientes.
   - **Métodos:**
     - `registerPatient(Patient patient)`: Endpoint para registrar un nuevo paciente.
     - `updatePatient(String id, Patient patient)`: Endpoint para actualizar la información de un paciente.
     - `getPatientById(String id)`: Endpoint para obtener los detalles de un paciente por su ID.

4. **CaregiverController:**
   - **Descripción:** Expone endpoints para la gestión de cuidadores, permitiendo registrar, actualizar y consultar cuidadores.
   - **Métodos:**
     - `registerCaregiver(Caregiver caregiver)`: Endpoint para registrar un nuevo cuidador.
     - `updateCaregiver(String id, Caregiver caregiver)`: Endpoint para actualizar la información de un cuidador.
     - `getCaregiverById(String id)`: Endpoint para obtener los detalles de un cuidador por su ID.

### 4.2.7.3. Application Layer

#### Command Handlers

1. **CreateAccountHandler:**
   - **Descripción:** Maneja el comando para registrar una nueva cuenta en el sistema.
   - **Métodos:**
     - `handle(CreateAccountCommand command)`: Valida y crea una nueva cuenta en el sistema.

2. **CreateRoleHandler:**
   - **Descripción:** Maneja el comando para crear un nuevo rol en el sistema.
   - **Métodos:**
     - `handle(CreateRoleCommand command)`: Valida y crea un nuevo rol en el sistema.

3. **RegisterPatientHandler:**
   - **Descripción:** Maneja el comando para registrar un nuevo paciente en el sistema.
   - **Métodos:**
     - `handle(RegisterPatientCommand command)`: Valida y registra un nuevo paciente en el sistema.

4. **RegisterCaregiverHandler:**
   - **Descripción:** Maneja el comando para registrar un nuevo cuidador en el sistema.
   - **Métodos:**
     - `handle(RegisterCaregiverCommand command)`: Valida y registra un nuevo cuidador en el sistema.

#### Event Handlers

1. **AccountCreatedEventHandler:**
   - **Descripción:** Maneja los eventos que se disparan cuando se crea una nueva cuenta.
   - **Métodos:**
     - `handle(AccountCreatedEvent event)`: Ejecuta las acciones necesarias después de la creación de una cuenta.

2. **RoleCreatedEventHandler:**
   - **Descripción:** Maneja los eventos que se disparan cuando se crea un nuevo rol.
   - **Métodos:**
     - `handle(RoleCreatedEvent event)`: Ejecuta las acciones necesarias después de la creación de un rol.

#### Query Handlers

1. **GetAccountDetailsHandler:**
   - **Descripción:** Maneja las consultas para obtener los detalles de una cuenta específica.
   - **Métodos:**
     - `handle(GetAccountDetailsQuery query)`: Devuelve los detalles de la cuenta solicitada.

2. **GetRoleDetailsHandler:**
   - **Descripción:** Maneja las consultas para obtener los detalles de un rol específico.
   - **Métodos:**
     - `handle(GetRoleDetailsQuery query)`: Devuelve los detalles del rol solicitado.

3. **GetPatientDetailsHandler:**
   - **Descripción:** Maneja las consultas para obtener los detalles de un paciente específico.
   - **Métodos:**
     - `handle(GetPatientDetailsQuery query)`: Devuelve los detalles del paciente solicitado.

4. **GetCaregiverDetailsHandler:**
   - **Descripción:** Maneja las consultas para obtener los detalles de un cuidador específico.
   - **Métodos:**
     - `handle(GetCaregiverDetailsQuery query)`: Devuelve los detalles del cuidador solicitado.

### 4.2.7.4. Infrastructure Layer

#### Repositories (Implementaciones)

1. **AccountRepositoryImpl:**
   - **Descripción:** Implementación de `AccountRepository` que define cómo se almacenan y recuperan las cuentas desde la base de datos.
   - **Métodos:**
     - `findById(String id)`: Implementación para buscar una cuenta por su ID.
     - `save(Account account)`: Implementación para guardar o actualizar una cuenta en la base de datos.
     - `delete(String id)`: Implementación para eliminar una cuenta de la base de datos.

2. **RoleRepositoryImpl:**
   - **Descripción:** Implementación de `RoleRepository` que define cómo se almacenan y recuperan los roles desde la base de datos.
   - **Métodos:**
     - `findById(String id)`: Implementación para buscar un rol por su ID.
     - `save(Role role)`: Implementación para guardar o actualizar un rol en la base de datos.
     - `delete(String id)`: Implementación para eliminar un rol de la base de datos.

3. **PatientRepositoryImpl:**
   - **Descripción:** Implementación de `PatientRepository` que define cómo se almacenan y recuperan los pacientes desde la base de datos.
   - **Métodos:**
     - `findById(String id)`: Implementación para buscar un paciente por su ID.
     - `save(Patient patient)`: Implementación para guardar o actualizar un paciente en la base de datos.
     - `delete(String id)`: Implementación para eliminar un paciente de la base de datos.

4. **CaregiverRepositoryImpl:**
   - **Descripción:** Implementación de `CaregiverRepository` que define cómo se almacenan y recuperan los cuidadores desde la base de datos.
   - **Métodos:**
     - `findById(String id)`: Implementación para buscar un cuidador por su ID.
     - `save(Caregiver caregiver)`: Implementación para guardar o actualizar un cuidador en la base de datos.
     - `delete(String id)`: Implementación para eliminar un cuidador de la base de datos.

### 4.2.7.6. Bounded Context Software Architecture Component Level Diagrams

#### Components (Web API):

1. **AccountService Component:**
   - **Descripción:** Componente encargado de la lógica de negocio relacionada con la gestión de cuentas. Interactúa con el `AccountRepository` para gestionar el registro y la actualización de cuentas.

2. **RoleService Component:**
   - **Descripción:** Componente encargado de la lógica de negocio relacionada con la gestión de roles. Interactúa con el `RoleRepository` para gestionar el registro y la actualización de roles.

3. **PatientService Component:**
   - **Descripción:** Componente encargado de la lógica de negocio relacionada con la gestión de pacientes. Interactúa con el `PatientRepository` para gestionar el registro y la actualización de pacientes.

4. **CaregiverService Component:**
   - **Descripción:** Componente encargado de la lógica de negocio relacionada con la gestión de cuidadores. Interactúa con el `CaregiverRepository` para gestionar el registro y la actualización de cuidadores.

![AccountContext](assets/structurizr-95614-AccountContext.png)

### 4.2.7.7. Bounded Context Software Architecture Code Level Diagrams

#### 4.2.7.7.1. Bounded Context Domain Layer Class Diagrams

- **Clases importantes:**
  - `Account`
  - `Role`
  - `Patient`
  - `Caregiver`

- **Repositories:**
  - `AccountRepository`
  - `RoleRepository`
  - `PatientRepository`
  - `CaregiverRepository`

![alt text](assets/account-diagram-class.png)

#### 4.2.7.7.2. Bounded Context Database Design Diagram

- **Tablas:**
  - **Account:**
    - Columnas: `id`, `username`, `password`, `email`, `phoneNumber`, `role`.
  - **Role:**
    - Columnas: `id`, `roleName`, `description`.
  - **Patient:**
    - Columnas: `id`, `name`, `age`, `address`, `emergencyContact`, `Account_id`.
    - Llave Foránea: `Account_id`.
  - **Caregiver:**
    - Columnas: `id`, `name`, `phone`, `address`, `Account_id`.
    - Llave Foránea: `Account_id`.

- **Relaciones:**
  - `Patient` se relaciona con `Account` a través de `Account_id`.
  - `Caregiver` se relaciona con `Account` a través de `Account_id`.
  - `Account` puede tener múltiples pacientes y cuidadores asociados.

![alt text](assets/account_context.png)

# Capítulo V:Solution UI/UX Design

## 5.1. Strategic-Level Attribute-Driven Design

### 5.1.1. General Style Guidelines 

#### 5.1.1.1. Branding

El sistema de Monitoreo Integral del Adulto Mayor está diseñado para transmitir una sensación de confianza y profesionalismo, fundamental en el contexto de la salud. Se busca un estilo visual que sea accesible y amigable tanto para cuidadores como para usuarios con menos experiencia tecnológica, sin perder el rigor necesario para una aplicación de monitoreo.

El diseño busca reflejar valores como seguridad, precisión, y cuidado. Esto se observa a través de:
- Paleta de colores: Tonos suaves pero contrastantes, alineados con el contexto de la salud, que generan una sensación de calma y confianza.
- Tipografía moderna: Elegida por su legibilidad clara y estética limpia, contribuyendo a una experiencia visual armónica.
- Diseño minimalista: Enfocado en la funcionalidad, reduciendo la sobrecarga visual para que los usuarios puedan interactuar fácilmente con la interfaz.

Tanto en las aplicaciones como el landing page, se adopta un tono de comunicación respetuoso y sereno, alineado con la naturaleza sensible del cuidado de la salud. El lenguaje es formal, pero sin llegar a ser excesivamente técnico, para que tanto profesionales de la salud como cuidadores y usuarios con menor experiencia tecnológica puedan entender fácilmente la información proporcionada.

#### 5.1.1.2. Logotipo

El logo sigue un diseño minimalista, con líneas limpias y formas simples. El logotipo es fácilmente reconocible y se integra bien en la interfaz sin distraer del contenido principal. 

Se presentan dos variaciones principales:

![MIAM logo color](assets/miam_logo_color.png)

La versión a color, utilizada en fondos claros, resalta la identidad de la marca. Es ideal para el uso en el Landing Page, donde el contraste con el fondo es fundamental para captar la atención del usuario.

![MIAM logo white](assets/miam_logo_white.png)

La versión en blanco,diseñada para fondos oscuros o más complejos. Esta versión asegura que la marca se mantenga presente de manera elegante y sin perder visibilidad. Se utiliza principalmente en situaciones donde el logo necesita integrarse sin competir visualmente con otros elementos, como en el sidebar o áreas más visualmente cargadas.


#### 5.1.1.3. Typography

La tipografía principal utilizada en los encabezados y el cuerpo es Inter, una fuente sans-serif moderna y versátil, reconocida por su excelente legibilidad tanto en dispositivos móviles como en pantallas de alta resolución. Inter se caracteriza por su diseño limpio y espaciado óptimo

![INTER Font](assets/font_inter.png)

La estructura tipográfica se organiza mediante variaciones en el tamaño, grosor y estilo de la fuente, estableciendo una jerarquía visual clara que facilita la navegación. 

Los títulos se presentan en negrita y con un tamaño mayor, destacándose para captar la atención del usuario de inmediato. En contraste, el cuerpo del texto y las descripciones utilizan tamaños más pequeños y estilos regulares, lo que ofrece una lectura fluida y cómoda en bloques más extensos de información.

#### 5.1.1.4. Colors

Las aplicaciones web y móvil emplean una paleta cuidadosamente seleccionada que equilibra profesionalismo y tranquilidad, con un enfoque en la accesibilidad y la funcionalidad visual.

<b>Paleta Principal</b>

![Main Palette](assets/main_palette.png)

- <b>#5C9BD5:</b> Actúa como el color principal, utilizado en títulos y elementos como enlaces o botones de acción secundarios. Este tono de azul está asociado con la tecnología y la seguridad, lo que transmite confianza y estabilidad.
- <b>#F2F7FC:</b> Se utiliza como color de fondo tanto en las pantallas de la versión web como móvil, creando un entorno limpio que facilita la lectura y mejora la experiencia de usuario.
- <b>#1C2D3D:</b> Se emplea para proporcionar un contraste oscuro que resalta los íconos y las opciones de navegación.

<b>Colores neutros:</b>

![Neutral Colors Palette](assets/neutral_colors.png)

- <b>#4F4F4F:</b> Es la elección predominante para todo el texto principal y algunos títulos, asegurando una legibilidad cómoda.
- <b>#959595:</b> Se utiliza para textos pequeños o información que no debe competir visualmente con otros elementos.
- <b>#FFFFFF:</b> El color blanco se emplea para textos y elementos sobre fondos oscuros.

<b>Colores de estado:</b>

![State Colors Palette](assets/state_colors.png)

- <b>#80CD83:</b> Representa estabilidad y situaciones normales, siendo empleado en indicadores de salud, como los signos vitales.
- <b>#FBBC05:</b> Indica advertencias o situaciones que requieren precaución.
- <b>#FE5E81:</b> Se utiliza para notificar estados críticos o de alto riesgo.

#### 5.1.1.5. Spacing

Se utiliza un espaciado amplio y consistente entre los diferentes elementos de la interfaz, de al menos 10px entre cada elemento. Esto facilita la lectura y la navegación, y evita que la interfaz se vea sobrecargada. 

![Spacing](assets/spacing.PNG)

En cuanto a la aplicación móvil, los botones y áreas interactivas son lo suficientemente grandes como para ser utilizados fácilmente en pantallas táctiles.

### 5.1.2. Web, Mobile and IoT Style Guidelines 

### 5.1.2.1. Web Style Guidelines

<b>Paleta de Colores:</b> Se utilizó la paleta de colores principal para los elementos de la aplicación web. Está compuesta de colores que facilitan la legibilidad y usabilidad.

- <b>#5C9BD5:</b> Usado para títulos, enlaces y botones de acción menos importantes.
- <b>#1C2D3D:</b> Color del sidebar, proporcionando un contraste fuerte con el fondo.
- <b>#F2F7FC:</b> Color de fondo que crea un ambiente ligero y limpio en la interfaz.

<b>Tipografía:</b> Se eligió la fuente Inter. Los títulos se presentan en un tamaño mayor (24px) y un peso más fuerte, mientras que el texto del cuerpo se establece en 16px.

<b>Espaciado y alineación:</b> El diseño mantiene un espaciado consistente entre elementos, con márgenes de al menos 16px para evitar la saturación visual y mejorar la experiencia del usuario.

<b>Botones: </b> Los botones tienen un diseño rectángulo con bordes redondeados, proporcionando una sensación amigable.

![Buttons](assets/buttons.png)

<b>Gráficos y Visualización de Datos:</b> Los gráficos de signos vitales (temperatura y frecuencia cardíaca) se presentan con líneas claras y colores contrastantes para facilitar su interpretación.

![Graphics](assets/graphics.png)


<b>Navegación:</b> La navegación se organiza mediante un menú lateral, permitiendo un acceso fácil a todas las secciones de la aplicación. Las opciones de menú se destacan con iconos intuitivos y etiquetas que mejoran la usabilidad.

![Sidebar](assets/sidebar.png)

### 5.1.2.2. Mobile Style Guidelines

<b>Paleta de Colores:</b> Se utilizó la paleta de colores principal para los elementos de la aplicación web. Está compuesta de colores que facilitan la legibilidad y usabilidad.

- <b>#5C9BD5:</b> Usado para títulos, enlaces y botones de acción menos importantes.
- <b>#1C2D3D:</b> Color del sidebar, proporcionando un contraste fuerte con el fondo.
- <b>#F2F7FC:</b> Color de fondo que crea un ambiente ligero y limpio en la interfaz.

<b>Tipografía:</b> Las fuentes son consistentes con las de la versión web, asegurando que el texto sea claro y fácil de leer en pantallas más pequeñas. Los títulos se presentan en 20px y el texto de cuerpo en 14px.

<b>Espaciado y alineación:</b> El diseño mantiene un espaciado adecuado entre elementos, con un margen mínimo de 12px, evitando la saturación en pantallas reducidas.

<b>Botones: </b> Los botones son amplios y accesibles, con un tamaño mínimo de 44px de alto para facilitar la interacción táctil. Se implementan colores de estado claros que indican interacciones.

![Buttons Mobile](assets/button-mobile.PNG)

![Buttons Mobile](assets/button-mobile-2.PNG)

<b>Gráficos y Visualización de Datos:</b> Los gráficos de signos vitales se adaptan a la pantalla, utilizando líneas y etiquetas legibles. Se asegura que la información sea fácilmente interpretable en dispositivos móviles.

<b>Navegación:</b> La navegación se coloca en una barra inferior, ofreciendo accesibilidad a las funciones principales de la aplicación. Los iconos son grandes y fáciles de reconocer, permitiendo una navegación intuitiva.

![Navbar Mobile](assets/mobile-navbar.png)

## 5.2. Information Architecture

### 5.2.1. Organization Systems.
Se utilizaron los tres sistemas de organización visual: jerárquica, secuencial y matricial. Cada uno de estos enfoques se aplica según la naturaleza de la información o tarea a realizar, asegurando que la navegación y la experiencia del usuario sean claras, eficientes y optimizadas para diferentes contextos.

- <b> Visual Hierarchy:</b> La organización jerárquica se utiliza principalmente en el dashboard y las pantallas de visualización de información clave, como el monitoreo de signos vitales y las alertas. La finalidad de usar una jerarquía visual en estas áreas es priorizar la información importante para los cuidadores. 

![Dashboard](assets/mockups_dashboard.png)

- <b>Step-by-Step to Accomplish:</b> La organización secuencial se aplica en las funciones que requieren la ejecución de tareas que siguen un proceso definido y donde cada etapa depende de la anterior, como es el caso de la sección Billing & Plans. 

![Billing](assets/mockups_billing.png)

- <b>Matricial:</b> Se utilizó este tipo de organización para la vista de tablas en la sección de Alerts y Billing History. Esta proporciona una vista global de los datos que ayuda a manejar la información de manera simultánea.

![Alerts](assets/mockups_alerts.png)

### 5.2.2. Labeling Systems.

- <b> a. Etiquetas Simplificadas y Claras: <b>
	El uso de etiquetas simples y claras será clave para facilitar la navegación y comprensión 	de los usuarios. Algunas etiquetas propuestas:

	Home → "Inicio" 
	Our Service → "Nuestros Servicios"
	Plan → "Planes"
	Log In → "Iniciar Sesión"
	Contact → "Contáctanos"

- <b> b. Asociaciones Clave: <b>
	Relacionar términos de monitoreo como "seguridad", "alertas", "reporte en tiempo real" con 	los beneficios principales para que los usuarios los identifiquen rápidamente.
	Usar un mínimo de palabras en las etiquetas, evitando tecnicismos innecesarios.

### 5.2.3. SEO Tags and Meta Tags.

- <b> a. SEO para el sitio web: <b>

  Landing Page:

	Title: Sistema de Monitoreo Avanzado para Pacientes - Seguridad y Tranquilidad
	Meta Description: Nuestro sistema de monitoreo todo en uno mejora la seguridad y el 	bienestar de pacientes y seres queridos con monitoreo en tiempo real y alertas 	personalizadas.
	Keywords: monitoreo de pacientes, sistema de seguridad, alertas personalizadas, cuidado 	remoto, monitoreo en tiempo real
	Author: Nombre de la startup

  Our Service Page:

  Title: Nuestros Servicios de Monitoreo - Seguridad 24/7 para Pacientes
	Meta Description: Descubre los servicios que ofrecemos para el monitoreo en tiempo real de 	pacientes y seres queridos, con alertas automáticas y reportes detallados.
	Keywords: monitoreo de salud, servicios de cuidado remoto, alertas de seguridad, monitoreo 	de pacientes, bienestar de pacientes.

### 5.2.4. Navigation Systems.  

- <b>El sistema de navegación debe ser claro y directo. Algunas estrategias para guiar a los 	usuarios: <b>

	Barra de navegación principal (Navbar en la parte superior) con las rutas clave:
	Inicio, Nuestros Servicios, Planes, Contáctanos, Iniciar Sesión

	Breadcrumbs (Migas de pan) para ayudar al usuario a saber dónde está en todo momento dentro 	del sitio.

	Navegación de pie de página: Repetir las rutas clave como "Términos y condiciones", 	"Política de privacidad", "Soporte", y enlaces a redes sociales.

### 5.2.5. Navigation Systems.

- <b>La implementación de un sistema de búsqueda sólido ayudará a los usuarios a encontrar 	información específica sin perderse en la plataforma. Este sistema debe incluir: <b>

	Barra de búsqueda visible en la parte superior de todas las páginas.

	Resultados claros: Presentar los resultados con un resumen breve que contenga enlaces directos a las páginas correspondientes.

### 5.2.3. SEO Tags and Meta Tags

### 5.2.4. Searching Systems.

### 5.2.5. Navigation Systems.

## 5.3. Landing Page UI Design

Se diseñó el Landing Page con un enfoque centrado en la experiencia del usuario, donde las decisiones de diseño y la arquitectura de la información se han basado en principios clave como la simplicidad, la accesibilidad y la claridad de comunicación. 

Cada componente de la interfaz responde a la necesidad de brindar confianza y facilitar la comprensión del servicio ofrecido, tanto en versiones de escritorio como en dispositivos móviles.

### 5.3.1. Landing Page Wireframe

El wireframe para el navegador de escritorio presenta una estructura organizada en bloques que prioriza el flujo de información y facilita la exploración de contenido de manera natural. En la parte superior, se encuentra un encabezado con el menú de navegación, manteniendo visibles las secciones más relevantes.

El diseño sigue los principios de la jerarquía visual al posicionar la información más importante en el área superior de la pantalla, lo que mejora la usabilidad. También se aplican principios de diseño inclusivo, con un enfoque en la legibilidad de los textos y la facilidad para navegar por el contenido.

![Wireframe Hero section](assets/wireframe-hero-section.PNG)
![Wireframe How it works section](assets/wireframe-how-it-works-section.PNG)
![Wireframe Why choose us section](assets/wireframe-why-choose-us-section.PNG)
![Wireframe Plans section](assets/wireframe-plans-section.PNG)
![Wireframe Testimonials section](assets/wireframe-testimonials-section.PNG)
![Wireframe Team section](assets/wireframe-team-section.PNG)
![Wireframe Contact and footer section](assets/wireframe-contact-footer-section.PNG)

###  5.3.2. Landing Page Mock-up 

El mock-up para la versión de escritorio del Landing Page refleja la aplicación concreta de los principios de diseño establecidos, como la consistencia visual, con el uso de una paleta de colores neutros y azulados que generan una atmósfera de confianza y tranquilidad. Se han empleado tipografías legibles y contrastes adecuados para mejorar la accesibilidad, siguiendo las pautas de diseño inclusivo.

Además, el Hero Section incluye el Call to action "How it Works", que invita a los usuarios a conocer más el sistema.

![Hero section](assets/hero-section.PNG)
![How it works section](assets/how-it-works-section.PNG)
![Why choose us section](assets/why-choose-us-section.PNG)
![Plans section](assets/plans-section.PNG)
![Testimonials section](assets/testimonials-section.PNG)
![Team section](assets/team-section.PNG)
![Contact and footer section](assets/contact-footer-section.PNG)

## 5.4. Applications UX/UI Design

### 5.4.1. Applications Wireframes

#### 5.4.1.1. Web Application Wireframes

Los wireframes sirven como una representación inicial del diseño. En ellos se ha aplicado cuidadosamente la arquitectura de información, asegurando que los elementos clave se ubiquen de manera lógica y accesible para los usuarios. 

Los principios de jerarquía visual y alineación sirven para guiar al usuario a través de la interfaz de forma intuitiva, destacando las acciones más importantes y asegurando una fácil navegación entre las diferentes secciones.

A continuación, se muestran los wireframes de las secciones más importantes de la aplicación: 

- Log in

![Wireframe Login](assets/wireframes_login.png)

- Dashboard

![Wireframe Dashboard 1](assets/wireframes_dashboard_1.png)
![Wireframe Dashboard 2](assets/wireframes_dashboard_2.png)
![Wireframe Dashboard 3](assets/wireframes_dashboard_3.png)

- Band configuration

![Wireframe Band Configuration 1](assets/wireframes_bandconfiguration_1.png)
![Wireframe Band Configuration 2](assets/wireframes_bandconfiguration_2.png)

- Alerts 

![Wireframe Alerts 1](assets/wireframes_alerts_1.png)
![Wireframe Alerts 2](assets/wireframes_alerts_2.png)

- Patients

![Wireframe Patients 1](assets/wireframes_patients_1.png)
![Wireframe Patients 2](assets/wireframes_patients_2.png)

- Billing

![Wireframe Billing 1](assets/wireframes_billing_1.png)
![Wireframe Billing 2](assets/wireframes_billing_2.png)
![Wireframe Billing 3](assets/wireframes_billing_3.png)


#### 5.4.1.2. Mobile Application Wireframes

Los wireframes móviles representan una versión preliminar del diseño de la aplicación, mostrando cómo se organizará la información en una pantalla más pequeña. Se ha aplicado de manera cuidadosa la arquitectura de información para garantizar que los elementos clave estén ubicados de forma lógica y accesible para los usuarios en sus dispositivos móviles.

Se han utilizado principios de jerarquía visual y alineación para guiar al usuario a través de la interfaz de forma intuitiva, destacando las acciones más importantes y asegurando una navegación fluida entre las diferentes secciones de la aplicación. El diseño responsivo asegura que la experiencia del usuario sea consistente, fácil de usar y sin comprometer la funcionalidad en dispositivos móviles.

A continuación, se presentan los wireframes de las secciones más importantes de la aplicación móvil, mostrando la disposición de los menús, botones de acción y secciones de contenido en un formato optimizado para pantallas de smartphones:

- Log in

![Wireframe Login](assets/wireframe-mobile-login.png)

- Dashboard

![Wireframe Dashboard 1](assets/wireframe-mobile-dashboard.png)

- Band configuration

![Wireframe Band Configuration 1](assets/wireframe-mobile-configuration.png)

- Alerts 

![Wireframe Alerts 1](assets/wireframe-mobile-alert.png)

- Patients

![Wireframe Patients 1](assets/wireframe-mobile-patients.png)

- Billing

![Wireframe Billing 1](assets/wireframe-mobile-billing1.png)

![Wireframe Billing 2](assets/wireframe-mobile-billing2.png)

![Wireframe Billing 3](assets/wireframe-mobile-billing3.png)


### 5.4.2. Applications Wireflow Diagrams

#### 5.4.2.1. Web Application Wireflow Diagrams

<b>Wireflow 1</b> <br>
<b>User Persona:</b> Ana Martinez <br>
<b>User Goal:</b> Crear una alerta de recordatorio de medicamento del paciente para ser notificada <br>
<b>Descripción:</b> Este flujo ilustra la secuencia de pasos a seguir por Ana cuando quiere crear una alerta de medicamento para ser notificada. El flujo inicia en la pantalla "Patients". Ana, quien es el cuidador, selecciona un paciente y hace clic en el botón "Add alert". Luego, visualiza un formulario y agrega la información de la alerta. El happy path ocurre la alerta es creada exitosamente y Ana recibe el recordatorio de administración del medicamento. 

![Wireflow 1](assets/wireflow-1.png)

<b>Wireflow 2</b> <br>
<b>User Persona:</b> Ana Martinez <br>
<b>User Goal:</b> Mejorar su plan actual para obtener los beneficios como dueña de una casa de reposo <br>
<b>Descripción:</b> Este flujo ilustra la secuencia de pasos a seguir por Ana al mejorar su plan actual. Inicia cuando Ana ingresa a la pantalla "Billing & Payment", donde se muestra su historial de facturas y datos del plan actual. Cuando Ana hace clic en "Upgrade now", visualiza una sección con la información de los planes disponibles. Al mejorar su plan de Básico a Enterprise, tiene la opción de agregar más Health Bands, lo que se refleja en la pantalla de pago. El happy path ocurre cuando Ana realiza el pago y este es procesado exitosamente, redirigiéndola a una pantalla de confirmación.

![Wireflow 2](assets/wireflow-2.png)

<b>Wireflow 3</b> <br>
<b>User Persona:</b> Ana Martinez & Gabriel Lopez <br>
<b>User Goal:</b> Visualizar los datos vitales de un paciente para tener un monitoreo continuo <br>
<b>Descripción:</b> Este flujo ilustra la secuencia de pasos a seguir, tanto para Ana como para Gabriel, cuando quieren visualizar un resumen de los datos vitales de un paciente. El flujo inicia cuando los usuarios se encuentran en el dashboard, visualizando el apartado de Vital Signs Monitoring. Al hacer clic en el menú desplegable, aparece una lista con todos los pacientes registrados. El happy path ocurre cuando se selecciona un paciente y la gráfica del dashboard se actualiza con los datos de sus funciones vitales.

![Wireflow 3](assets/wireflow-3.png)

<b>Wireflow 4</b> <br>
<b>User Persona:</b> Ana Martinez & Gabriel Lopez <br>
<b>User Goal:</b> Vincular una banda a un paciente creado <br>
<b>Descripción:</b> Este flujo ilustra la secuencia de pasos a seguir, tanto para Ana como para Gabriel, cuando quieren vincular una banda a un paciente para monitorearlo. El flujo inicia cuando el usuario se encuentra en la vista "Band Configuration" y selecciona una banda que no ha sido configurada. El siguiente paso es elegir un paciente previamente credo del menú desplegable de la sección "Patient". El happy path ocurre cuando, al hacer clic en "Save", la información del paciente se vincula a la banda y esta se sincroniza, empezando a monitorear los signos vitales.

![Wireflow 4](assets/wireflow-4.png)


<b>Wireflow 5</b> <br>
<b>User Persona:</b> Gabriel Lopez <br>
<b>User Goal:</b> Vincular una paciente a un cuidador para que reciba las notificaciones <br>
<b>Descripción:</b> Este flujo ilustra la secuencia de pasos a seguir por Gabriel, como dueño de una casa de reposo, para vincular un paciente a un cuidador. El flujo inicia cuando se encuentra en la pantalla "Patients" y selecciona alguno de los pacientes de su lista. Luego, selecciona un cuidador del menú desplegable en la sección "Caregiver", el cual cambia de "No configurado" a mostrar el nombre del cuidador. El happy path ocurre cuando los cambios se guardan exitosamente, el cuidador es vinculado al paciente y puede recibir las alertas. 

![Wireflow 5](assets/wireflow-5.png)


#### 5.4.2.2. Mobile Application Wireflow Diagrams



### 5.4.3. Applications Mock-ups

#### 5.4.3.1. Web Application Mock-ups

En esta sección se presentan los mock-ups de la aplicación móvil, mostrando una representación visual más detallada y cercana a la versión final para dispositivos móviles.

Estos mock-ups integran todos los principios de diseño adaptados a la experiencia móvil, como la consistencia visual y la combinación equilibrada de colores, asegurando que la experiencia de usuario sea cohesiva y atractiva en pantallas pequeñas. Cada componente, como botones, tipografías y otros elementos, está diseñado siguiendo las pautas establecidas en el design system, garantizando que se mantenga una coherencia visual a lo largo de toda la aplicación móvil.

A continuación, se muestran los mock-ups de las secciones más importantes de la aplicación móvil, donde se destacan la disposición de los menús, los accesos rápidos y las interacciones táctiles optimizadas para ofrecer una navegación intuitiva y fluida en smartphones:

- Log in

![Mockup Login 1](assets/mockups_login_1.png)
![Mockup Login 1](assets/mockups_login_2.png)

- Dashboard

![Mockup Dashboard 1](assets/mockups_dashboard.png)
![Mockup Dashboard 1](assets/mockups_dashboard_1.png)
![Mockup Dashboard 1](assets/mockups_dashboard_1.png)

- Band configuration

![Mockup Band Configuration 1](assets/mockups_bandconfiguration_1.png)
![Mockup Band Configuration 1](assets/mockups_bandconfiguration_2.png)

- Alerts 

![Mockup Alerts 1](assets/mockups_alerts_1.png)
![Mockup Alerts 1](assets/mockups_alerts_2.png)

- Patients

![Mockup Patients 1](assets/mockups_patients_1.png)
![Mockup Patients 1](assets/mockups_patients_2.png)
![Mockup Patients 1](assets/mockups_patients_3.png)
![Mockup Patients 1](assets/mockups_patients_4.png)

- Billing

![Mockup Billing 1](assets/mockups_billing_1.png)
![Mockup Billing 2](assets/mockups_billing_2.png)
![Mockup Billing 3](assets/mockups_billing_3.png)

#### 5.4.3.2. Mobile Application Mock-ups

- Log in

![Wireframe Login](assets/wireframe-mobile-login.png)

- Dashboard

![Wireframe Dashboard 1](assets/wireframes_dashboard_1.png)
![Wireframe Dashboard 2](assets/wireframes_dashboard_2.png)
![Wireframe Dashboard 3](assets/wireframes_dashboard_3.png)

- Band configuration

![Wireframe Band Configuration 1](assets/wireframes_bandconfiguration_1.png)
![Wireframe Band Configuration 2](assets/wireframes_bandconfiguration_2.png)

- Alerts 

![Wireframe Alerts 1](assets/wireframes_alerts_1.png)
![Wireframe Alerts 2](assets/wireframes_alerts_2.png)

- Patients

![Wireframe Patients 1](assets/wireframes_patients_1.png)
![Wireframe Patients 2](assets/wireframes_patients_2.png)

- Billing

![Wireframe Billing 1](assets/wireframes_billing_1.png)
![Wireframe Billing 2](assets/wireframes_billing_2.png)
![Wireframe Billing 3](assets/wireframes_billing_3.png)

### 5.4.4. Applications User Flow Diagrams

#### 5.4.4.1. Web Application User Flow Diagrams

<b>User Flow 1</b> <br>
<b>User Persona:</b> Ana Martinez <br>
<b>User Goal:</b> Crear una alerta de recordatorio de medicamento del paciente para ser notificada <br>
<b>Descripción:</b> Este flujo ilustra la secuencia de pasos a seguir por Ana cuando quiere crear una alerta de medicamento para ser notificada. El flujo inicia en la pantalla "Patients". Ana, quien es el cuidador, selecciona un paciente y hace clic en el botón "Add alert". Luego, visualiza un formulario y agrega la información de la alerta. El happy path ocurre la alerta es creada exitosamente y Ana recibe el recordatorio de administración del medicamento. 

![User Flow 1](assets/user-flow-1.png)

<b>User Flow 2</b> <br>
<b>User Persona:</b> Ana Martinez <br>
<b>User Goal:</b> Mejorar su plan actual para obtener los beneficios como dueña de una casa de reposo <br>
<b>Descripción:</b> Este flujo ilustra la secuencia de pasos a seguir por Ana al mejorar su plan actual. Inicia cuando Ana ingresa a la pantalla "Billing & Payment", donde se muestra su historial de facturas y datos del plan actual. Cuando Ana hace clic en "Upgrade now", visualiza una sección con la información de los planes disponibles. Al mejorar su plan de Básico a Enterprise, tiene la opción de agregar más Health Bands, lo que se refleja en la pantalla de pago. El happy path ocurre cuando Ana realiza el pago y este es procesado exitosamente, redirigiéndola a una pantalla de confirmación.

![User Flow 2](assets/user-flow-2.png)

<b>User Flow 3</b> <br>
<b>User Persona:</b> Ana Martinez & Gabriel Lopez <br>
<b>User Goal:</b> Visualizar los datos vitales de un paciente para tener un monitoreo continuo <br>
<b>Descripción:</b> Este flujo ilustra la secuencia de pasos a seguir, tanto para Ana como para Gabriel, cuando quieren visualizar un resumen de los datos vitales de un paciente. El flujo inicia cuando los usuarios se encuentran en el dashboard, visualizando el apartado de Vital Signs Monitoring. Al hacer clic en el menú desplegable, aparece una lista con todos los pacientes registrados. El happy path ocurre cuando se selecciona un paciente y la gráfica del dashboard se actualiza con los datos de sus funciones vitales.

![User Flow 3](assets/user-flow-3.png)

<b>User Flow 4</b> <br>
<b>User Persona:</b> Ana Martinez & Gabriel Lopez <br>
<b>User Goal:</b> Vincular una banda a un paciente creado <br>
<b>Descripción:</b> Este flujo ilustra la secuencia de pasos a seguir, tanto para Ana como para Gabriel, cuando quieren vincular una banda a un paciente para monitorearlo. El flujo inicia cuando el usuario se encuentra en la vista "Band Configuration" y selecciona una banda que no ha sido configurada. El siguiente paso es elegir un paciente previamente credo del menú desplegable de la sección "Patient". El happy path ocurre cuando, al hacer clic en "Save", la información del paciente se vincula a la banda y esta se sincroniza, empezando a monitorear los signos vitales.

![User Flow 4](assets/user-flow-4.png)


<b>User Flow 5</b> <br>
<b>User Persona:</b> Gabriel Lopez <br>
<b>User Goal:</b> Vincular una paciente a un cuidador para que reciba las notificaciones <br>
<b>Descripción:</b> Este flujo ilustra la secuencia de pasos a seguir por Gabriel, como dueño de una casa de reposo, para vincular un paciente a un cuidador. El flujo inicia cuando se encuentra en la pantalla "Patients" y selecciona alguno de los pacientes de su lista. Luego, selecciona un cuidador del menú desplegable en la sección "Caregiver", el cual cambia de "No configurado" a mostrar el nombre del cuidador. El happy path ocurre cuando los cambios se guardan exitosamente, el cuidador es vinculado al paciente y puede recibir las alertas. 

![User Flow 5](assets/user-flow-5.png)

#### 5.4.4.2. Mobile Application User Flow Diagrams


## 5.5 Applications Prototyping

![Web Application Prototype](assets/prototype.PNG)

Enlace del prototipo:
<a href="https://www.figma.com/proto/HWNBsScQ1yZIRQxCTpWjoF/Mockups?node-id=43-15&node-type=canvas&t=UWTR3uKyOwZLyNxc-1&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=43%3A15&show-proto-sidebar=1">https://www.figma.com/proto/HWNBsScQ1yZIRQxCTpWjoF/Mockups?node-id=43-15&node-type=canvas&t=UWTR3uKyOwZLyNxc-1&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=43%3A15&show-proto-sidebar=1</a>

# Capítulo VI: Product Implementation, Validation & Deployment

## 6.1. Software Configuration Management

### 6.1.1. Software Development Environment Configuration

<table border="1">

  <tr>
    <td>Project Management</td>
    <td>Microsoft 365<br>Alojamiento de los videos de entrevistas, explicación de prototipos y otros relacionados al proyecto</td>
  </tr>
  <tr>
    <td></td>
    <td>Discord<br>Plataforma de mensajería instantánea donde se realizaron las reuniones, repartición de tarea y desarrollo del proyecto colaborativo.</td>
  </tr>
  <tr>
    <td></td>
    <td>Whatsapp<br>Aplicación de mensajería instantánea donde se realizaron recordatorios de las reuniones.</td>
  </tr>
  <tr>
    <td></td>
    <td>Trello<br>Software de administración Y gestión de proyectos que se utilizó para establecer y designar las tareas</td>
  </tr>
  <tr>
    <td>Requirements Management</td>
    <td>Structurizr<br>Structurizr es una herramienta de modelado y documentación que permitió el desarrollo de los diagramas C4</td>
  </tr>
  <tr>
    <td></td>
    <td>MySQL Workbench<br>Herramienta de diseño para el modelado de diagrama de bases de datos.</td>
  </tr>
  <tr>
    <td></td>
    <td>LucidChart<br>Herramienta de diseño para el modelado de diagramas UML.</td>
  </tr>
  <tr>
    <td></td>
    <td>Miro<br>Herramienta de diseño para la creación de los As-Is y To-Be Scenario Mapping</td>
  </tr>
  <tr>
    <td>Product UX/UI Design</td>
    <td>Figma<br>Herramienta que se utilizó para la creación de wireframes, mockups y prototipos.</td>
  </tr>
  <tr>
    <td>Software Development</td>
    <td>Git<br>Es un software de control de versiones para los trabajos en equipos y confiabilidad del desarrollo.</td>
  </tr>
  <tr>
    <td></td>
    <td>Node.js<br>Node.js es un entorno de ejecución de JavaScript del lado del servidor, que permite desarrollar aplicaciones web escalables y de alto rendimiento fuera del navegador.</td>
  </tr>
  <tr>
    <td></td>
    <td>GitHub<br>Sistema de control de versiones Git.</td>
  </tr>
  <tr>
    <td></td>
    <td>HTML5<br>Lenguaje de etiquetas, utilizado para la estructuración y la presentación de contenido.</td>
  </tr>
  <tr>
    <td></td>
    <td>CSS<br>CSS es un lenguaje utilizado para estilizar y dar formato a documentos HTML.</td>
  </tr>
  <tr>
    <td></td>
    <td>JavaScript<br>JavaScript es un lenguaje de programación de alto nivel, interpretado y multi-paradigma, utilizado para crear interactividad en páginas web.</td>
  </tr>
  <tr>
    <td></td>
    <td>VScode<br>Es un editor de código fuente con extensiones que ayudan al desarrollo.</td>
  </tr>
  <tr>
    <td></td>
    <td>Angular Framework<br>Framework para el desarrollo de frontend</td>
  </tr>
  <tr>
    <td>Software Deployment</td>
    <td>Github Pages<br>Plataforma que nos facilitó realizar el despliegue de nuestro landing page de manera rápida y práctica.</td>
  </tr>
</table>

### 6.1.2. Source Code Management

Utilizamos la metodología de git flow con finalidad es tener un control mayor sobre la gestión del proyecto, avanzar el proyecto de forma simultanea tanto como en la implementación del la aplicación y creación del reporte.

Esto nos permitio separar el proyecto en la rama principal (main) en la que se encuentra la versión presentable del proyecto, que a la vez no cuenta con errores. También tenemos la rama secundario (develop) que sirve para unificar los cambios de las demás ramas. También contamos con más branches una para determinadas fuincionalidades amplias de la aplicación y una para cada chapter del reporte.

<td><img src="" alt="Imagen del gitflow" width="1500"></td>


URL del repositorio del Report en GitHub:

URL del repositorio del Landing Page en GitHub: 

URL del repositorio del Frontend en Github:

### 6.1.3. Source Code Style Guide & Conventions

HTML: Lenguaje utilizado para diseñar páginas web. Este lenguaje utiliza etiquetas para marcar y definir el contenido de la página web; Como un texto, imagenes, videos, etc.

Convenciones:

- Se tiene que declarar el tipo de documento en la primera línea de la siguiente manera:
- Las etiquetas siempre tienen que esta en minúscula, ya que es más claro a la vista y es de facil escritura para los desarrolladores.
- Usar las comillas para darle un valor a los atributos para una mejor legibilidad.

CSS: Lenguaje que permite dar formatos o estilos a los elementos html. Con este lenguaje se pueden crear diseños web agradables e intuitivos para el usuario.

Convenciones:

- Unir los nombres de las clases compuestas con guiones: box-container{}
- Usar la unidad de medida rem para mantener un diseño responsive: 1rem

### 6.1.4. Software Deployment Configuration

Para despliegar el landing page, usamos las siguientes herraminetas.

- Git: Para realizar el manejo de las versiones del proyecto.
- GitHub: Dentro de la plataforma tenemos un repositorio, lo usamos para almacenar todo el proyecto con sus respectivas versiones.
- GitFlow: Esto permite visualizar y controlar el flujo de trabajo hecho por el equipo de desarrollo.

### 6.2.1. Sprint 1

#### 6.2.1.1. Sprint Planning 1

<table align="center"  border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td>
            <b>Sprint #</b>
        </td>
        <td>
            <b>Sprint 1</b>           
        </td>
    </tr>
    <tr align="left">
        <td colspan="2">
            <b>Sprint Planning Background</b>
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Date</b>
        </td>
        <td>
            05/09/24         
        </td>
    </tr>
       <tr align="left">
        <td>
            <b>Time</b>
        </td>
        <td>
            16:00         
        </td>
    </tr>
       <tr align="left">
        <td>
            <b>Location</b>
        </td>
        <td>
            Modalidad remota por Discord      
        </td>
    </tr>
     </tr>
       <tr align="left">
        <td>
            <b>Prepared By</b>
        </td>
        <td>
            Aliaga Trevejo, Lucía Guadalupe 
        </td>
    </tr>
    </tr>
       <tr align="left">
        <td>
            <b>Attendess (to planning meeting)</b>
        </td>
        <td>
            - Achamizo Huamani, Jean Carlos <br/>
            - Aliaga Trevejo, Lucía Guadalupe <br/>
            - Raymundo Guevara, Rodrigo Alejandro <br/>
            - Siancas Reategui, Luis Alberto <br/>    
            - Trujillo Lopez, Luis Alberto <br/> 
            - Sagastegui Rodriguez, Luis Jesus <br/> 
        </td>
    </tr>
     <tr align="left">
        <td colspan="2">
            <b>Sprint Goal & User Stories</b>
        </td>
    </tr>
      <tr align="left">
        <td>
            <b>Sprint 1 Velocity</b>
        </td>
        <td>
            12
        </td>
    </tr>
       <tr align="left">
        <td>
            <b>Sum of Story Points</b>
        </td>
        <td>
            12
        </td>
    </tr>
</table> 

#### 6.2.1.2. Sprint Backlog 1

En esta sección se especifican los detalles del Sprint Backlog, que es una lista de tareas que se han realizado para completar el Sprint.

<table align="center" border="1" width="90%" style="text-align:center">
    <tr>
       <td colspan="1"><b>Sprint #</b></td>
       <td colspan="7"><b>Sprint 1</b></td>
     </tr>
     <tr>
       <td colspan="2"><b>User Story</b></td>
       <td colspan="6"><b>Work-Item / Task</b></td>
     </tr>
     <tr>
       <td><b>Id</b></td>
       <td><b>Title</b></td>
       <td><b>Id</b></td>
       <td><b>Title</b></td>
       <td><b>Description</b></td>
       <td><b>Estimation(Hours)</b></td>
       <td><b>Assigned To</b></td>
       <td><b>Status(To-do/ In-Process/ To-Review/ Done)</b></td>
     </tr>
     <tr>
       <td rowspan="2">US01</td>
       <td rowspan="2">Beneficios del Producto</td>
       <td>US001-TSK01</td>
       <td>Implementar la sección de beneficios</td>
       <td>Programar la estructura HTML de la sección de beneficios del producto </td>
       <td>1 hora</td>
       <td>Jean Achamizo</td>
       <td>Done</td>
    </tr>
    <tr>
       <td>US001-TSK02</td>
       <td>Agregar estilos de la sección de beneficios Why choose us</td>
       <td>Programar estilos de la sección beneficios</td>
       <td>0.5 horas</td>
       <td>Luis Trujillo</td>
       <td>Done</td>
    </tr>
   <tr>
       <td rowspan="2">US002</td>
       <td rowspan="2">Modelo de Negocio</td>
       <td>US002-TSK01</td>
       <td>Implementar la sección Our Service</td>
       <td>Programar la estructura HTML de la sección Our Service</td>
       <td>1 hora</td>
      <td>Luis Siancas</td>       
      <td>Done</td>
    </tr>
    <tr>
       <td>US002-TSK02</td>
       <td>Agregar estilos de la sección Our Service</td>
       <td>Programar estilos de la sección Our Service</td>
       <td>0.5 horas</td>
        <td>Luis Siancas</td>       
        <td>Done</td>
    </tr>
    <tr>
       <td rowspan="2">US003</td>
       <td rowspan="2">Reseñas de Clientes</td>
       <td>US003-TSK01</td>
       <td>Implementar la sección de reseñas</td>
       <td>Programar la estructura HTML de la sección de reseñas</td>
       <td>1 hora</td>
       <td>Jesus Sagastegui</td>
       <td>Done</td>
    </tr>
    <tr>
       <td>US003-TSK02</td>
       <td>Agregar estilos de la sección de reseñas</td>
       <td>Programar estilos de la sección de reseñas</td>
       <td>0.5 horas</td>
       <td>Lucía Aliaga</td>
       <td>Done</td>
    </tr>
    <tr>
       <td rowspan="2">US004</td>
       <td rowspan="2">Contactar a Miembros de la Compañía</td>
       <td>US004-TSK01</td>
      <td>Implementar la sección Contact</td>
       <td>Programar la estructura HTML de la sección Contact</td>
       <td>1 hora</td>
       <td>Rodrigo Raymundo</td>
       <td>Done</td>
    </tr>
    <tr>
       <td>US004-TSK-02</td>
        <td>Agregar estilos de la sección Contact</td>
       <td>Programar estilos de la sección Contact</td>
       <td>1 hora</td>
       <td>Rodrigo Raymundo</td>
       <td>Done</td>
    </tr>
     <tr>
       <td rowspan="2">US005</td>
       <td rowspan="2">Información de Miembros de la Compañía</td>
       <td>US005-TSK01</td>
       <td>Implementar la sección Meet the team</td>
       <td>Programar la estructura HTML de la sección Meet the team</td>
       <td>1.5 horas</td>
       <td>Luis Trujillo</td>
       <td>Done</td>
    </tr>
    <tr>
       <td>US005-TSK02</td>
       <td>Agregar estilos de la sección Meet the team</td>
       <td>Programar estilos de la sección Meet the team</td>
       <td>1 hora</td>
       <td>Lucía Aliaga</td>
       <td>Done</td>
    </tr>
</table>

#### 6.2.1.3. Development Evidence for Sprint Review

En esta sección se presentan los commits realizados en el repositorio de GitHub, donde se puede observar el trabajo colaborativo de cada integrante del equipo en el desarrollo de la Landing Page. A continuación, se detallan las contribuciones individuales en diversas ramas del proyecto, incluyendo las implementaciones de las funcionalidades principales y las integraciones necesarias para el despliegue final del producto.

<table  align="left" border="1" width="100%">
    <tr>
        <th>Repository</th>
        <th>Branch</th>
        <th>Commit ID</th>
        <th>Commit Message</th>
        <th>Commit Message Body</th>
        <th>Committed on (Date)</th>
    </tr>
    <tr>
        <td rowspan=19>IoT-SocialTech/miam-landing-page</td>
        <td>/development</td>
        <td>9cc795b</td>
        <td>Initial commit</td>
        <td>Initial commit</td>
        <td>25/09/2024</td>
    </tr>
     <tr>
        <td>/development</td>
        <td>41a2388</td>
        <td>Feature: NavBar and product information</td>
        <td>Feature: NavBar and product information</td>
        <td>27/09/2024</td>
    </tr>
    <tr>
        <td>/US01-Product-Information</td>
        <td>6aecf7a</td>
        <td>Feature: Product benefits and footer</td>
        <td>Feature: Product benefits and footer</td>
        <td>27/09/2024</td>
    </tr>
    <tr>
        <td>/US02-Business-Model</td>
        <td>90281dc</td>
        <td>Feature: Information about our Business Model</td>
        <td>Feature: Information about our Business Model</td>
        <td>27/09/2024</td>
    </tr>
    <tr>
        <td>/US03-CustomerReviews</td>
        <td>c2dc9a2</td>
        <td>Feature: User Reviews Section</td>
        <td>Feature: User Reviews Section</td>
        <td>27/09/2024</td>
    </tr>
    <tr>
        <td>/US04-Contact</td>
        <td>d407ea8</td>
        <td>Feature: Contact Company Members</td>
        <td>Feature: Contact Company Members</td>
        <td>27/09/2024</td>
    </tr>
    <tr>
        <td>/US05-Company-Member-Information</td>
        <td>a8e6e9e</td>
        <td>Feature: Company Member Information Section</td>
        <td>Feature: Company Member Information Section</td>
        <td>27/09/2024</td>
    </tr>
    <tr>
        <td>/development</td>
        <td>b2015d6</td>
        <td>Fix: responsive</td>
        <td>Fix: responsive</td>
        <td>27/09/2024</td>
    </tr>
     <tr>
        <td>/development</td>
        <td>b160848</td>
        <td>fix: responsiveness issues</td>
        <td>fix: responsiveness issues</td>
        <td>05/10/2024</td>
    </tr>
</table>

#### 6.2.1.4. Testing Suite Evidence for Sprint Review

#### 6.2.1.5. Execution Evidence for Sprint Review

Como resultado del primer sprint, se presenta el despliegue de la Landing Page.
<a href="https://iot-socialtech.github.io/miam-landing-page/">https://iot-socialtech.github.io/miam-landing-page/</a>

![MIAM Landing Page](assets/miam-landingpage.PNG)

#### 6.2.1.6. Services Documentation Evidence for Sprint Review

**Link de la landing page:**
<a href="https://iot-socialtech.github.io/miam-landing-page/">https://iot-socialtech.github.io/miam-landing-page/</a>

#### 6.2.1.7. Software Deployment Evidence for Sprint Review

Para el desarrollo de la Landing page, se utilizaron las siguientes texnologías:

- HTML: Lenguaje de marcado para crear la estructura de una página web. Define la organización del contenido (encabezados, párrafos, imágenes, etc.).
- CSS: Lenguaje de estilo para darle forma y diseño a las páginas web. Controla la apariencia del contenido (colores, tipografías, fondos, etc.).
- Git: Sistema de control de versiones para gestionar el desarrollo de software. Permite realizar un seguimiento de los cambios en el código y colaborar con otros. Sistema de control de versiones que nos ayudó a trabajar en equipo durante el desarrollo del landing page
- GitHub: Plataforma online para alojar repositorios Git. Permite compartir código, colaborar en proyectos y acceder a una gran comunidad de desarrolladores. Plataforma que nos ayudó al desarrollo colaborativo del equipo para almacenar las versiones de nuestro proyecto.

Igualmente, para el correcto control de versiones y el adecuado desarrollo de la página, se empleó la metodología de trabajo GitFlow Workflow. Es un método para gestionar el desarrollo de software con Git. Define roles y ramas específicas para cada etapa del proceso, como desarrollo, pruebas y lanzamiento. Esto ayuda a organizar el código, facilita la colaboración y reduce el riesgo de errores.

#### 6.2.1.8. Team Collaboration Insights during Sprint

La StartUp ha realizado el presente sprint usando Git y Github como herramientas principales para el control de versiones y GitFlow como metodología de trabajo.

En primer lugar, se creó una organización en Github con el nombre de la StartUp. Luego, se creó un repositorio para la Landing page. En dicho repositorio, el equipo ha creado diferentes ramas (branchs) para diferenciar el tipo de trabajo que se realiza. Por ejemplo, la rama `main` se empleó únicamente para el despliegue final de la aplicación; `develop`, para hacer _merge_ con demás ramas incluída la `main`; `feature`, para implementar alguna funcionalidad. De esta manera se protege el código funcional y se diferencia de features en desarrollo por los miembros. Después de la creación de cada rama, uno o más usuario pueden acceder a esta y realizar cambios y guardarlos como commits.

![Landing Page Network Graph](assets/network-cloudapi.PNG)

### 6.2.2. Sprint 2

#### 6.2.2.1. Sprint Planning 2

<table align="center"  border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td>
            <b>Sprint #</b>
        </td>
        <td>
            <b>Sprint 2</b>           
        </td>
    </tr>
    <tr align="left">
        <td colspan="2">
            <b>Sprint Planning Background</b>
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Date</b>
        </td>
        <td>
            04/10/2024        
        </td>
    </tr>
       <tr align="left">
        <td>
            <b>Time</b>
        </td>
        <td>
            168:30         
        </td>
    </tr>
       <tr align="left">
        <td>
            <b>Location</b>
        </td>
        <td>
            Modalidad remota por Discord      
        </td>
    </tr>
     </tr>
       <tr align="left">
        <td>
            <b>Prepared By</b>
        </td>
        <td>
           Aliaga Trevejo, Lucía Guadalupe  
        </td>
    </tr>
    </tr>
       <tr align="left">
        <td>
            <b>Attendess (to planning meeting)</b>
        </td>
        <td>
            - Achamizo Huamani, Jean Carlos <br/>
            - Aliaga Trevejo, Lucía Guadalupe <br/>
            - Raymundo Guevara, Rodrigo Alejandro <br/>
            - Siancas Reategui, Luis Alberto <br/>    
            - Trujillo Lopez, Luis Alberto <br/> 
            - Sagastegui Rodriguez, Luis Jesus <br/> 
        </td>
    </tr>
      </tr>
       <tr align="left">
        <td>
            <b>Sprint 1</b>
            <b>Review Summary</b>
        </td>
        <td>
            En el sprint anterior, se completó el desarrollo de las secciones de la landing page. Esto incluyó el diseño visual, la estructura de navegación y la implementación de los componentes necesarios para una experiencia de usuario funcional. 
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Sprint 1</b>
            <b>Retrospective Summary</b>
        </td>
        <td>
          La organización de las tareas para el desarrollo de la landing page fue efectiva y permitió cumplir con el objetivo del sprint. Uno de los principales desafíos fue la gestión del tiempo. Se identificó la necesidad de priorizar y segmentar las tareas complejas para evitar sobrecargas y distribuir el trabajo de manera más equilibrada en el equipo
        </td>
    </tr>
     <tr align="left">
        <td colspan="2">
            <b>Sprint Goal & User Stories</b>
        </td>
        </tr>
    <tr align="left">
      <td>
        <b>Sprint 2 Goal</b>
      </td>
      <td>
            Our focus is on establishing the foundational features for user onboarding, bracelet configuration, and initial data collection. We believe it delivers a seamless entry experience for caregivers and nursing home owners, enabling them to begin using the monitoring system effectively and gather essential health data from the start. This will be confirmed when users can successfully register, log in, configure their bracelets, and view initial health data collected from the bracelets in real time.
      </td>
    </tr>
    </tr>
      <tr align="left">
        <td>
            <b>Sprint 1 Velocity</b>
        </td>
        <td>
            80
        </td>
    </tr>
       <tr align="left">
        <td>
            <b>Sum of Story Points</b>
        </td>
        <td>
            102
        </td>
    </tr>
</table> 

#### 6.2.2.2. Sprint Backlog 2

En esta sección se especifican los detalles del Sprint Backlog, que es una lista de tareas que se han realizado para completar el Sprint 2.

El objetivo de este sprint es establecer las características fundamentales necesarias para la creación de usuarios y pacientes en el sistema de monitoreo. Este sprint se enfocará en el desarrollo de funcionalidades para el registro de cuidadores, la configuración de los brazaletes (health band) y la recolección inicial de datos de salud. Al implementar estas características, se busca proporcionar una experiencia de entrada fluida para los cuidadores y propietarios de las casas de reposo, facilitando así el uso efectivo del sistema desde su inicio.

![Sprint Backlog 2](assets/sprint2_trello.PNG)

<br> Enlace del tablero: </br>
<a href="https://trello.com/invite/b/67127f4727ed7ccde1bbbc90/ATTI96acb467f4e57fe2509686befd5449c2E7848092/sprint-backlog-2"> https://trello.com/invite/b/67127f4727ed7ccde1bbbc90/ATTI96acb467f4e57fe2509686befd5449c2E7848092/sprint-backlog-2 </a>

<table align="center" border="1" width="90%" style="text-align:center">
    <tr>
        <td colspan="1"><b>Sprint #</b></td>
        <td colspan="7"><b>Sprint 2</b></td>
    </tr>
    <tr>
        <td colspan="2"><b>User Story</b></td>
        <td colspan="6"><b>Work-Item / Task</b></td>
    </tr>
    <tr>
        <td><b>Id</b></td>
        <td><b>Title</b></td>
        <td><b>Id</b></td>
        <td><b>Title</b></td>
        <td><b>Description</b></td>
        <td><b>Estimation(Hours)</b></td>
        <td><b>Assigned To</b></td>
        <td><b>Status(To-do/ In-Process/ To-Review/ Done)</b></td>
    </tr>
    <tr>
        <td rowspan="3">US006</td>
        <td rowspan="3">Monitoreo de Temperatura en Tiempo Real</td>
        <td>US06-TSK01</td>
        <td>Toma de temperatura en embedded application</td>
        <td>Implementar la lógica en el embedded application para tomar la temperatura</td>
        <td>2 horas</td>
        <td>Luis Trujillo</td>
        <td>Done</td>
    </tr>
    <tr>
        <td>US06-TSK02</td>
        <td>Implementar la interfaz de usuario de la aplicación móvil para mostrar la temperatura</td>
        <td>Implementar la interfaz de usuario de la aplicación móvil y lógica para mostrar la temperatura en tiempo real</td>
        <td>3 horas</td>
        <td>Jean Achamizo</td>
        <td>To fix</td>
    </tr>
    <tr>
        <td>US06-TSK03</td>
        <td>Implementar la interfaz de usuario de la aplicación web para mostrar la temperatura</td>
        <td>Implementar la interfaz de usuario de la aplicación web y lógica para mostrar la temperatura en tiempo real</td>
        <td>3 horas</td>
        <td>Rodrigo Raymundo</td>
        <td>To fix</td>
    </tr>
    <tr>
        <td rowspan="3">US007</td>
        <td rowspan="3">Monitoreo del Ritmo Cardíaco en Tiempo Real</td>
        <td>US07-TSK01</td>
        <td>Toma de pulso en embedded application</td>
        <td>Implementar la lógica en el embedded applicaton para tomar el pulso</td>
        <td>2 horas</td>
        <td>Luis Trujillo</td>
        <td>Done</td>
    </tr>
    <tr>
        <td>T12</td>
        <td>Implementar la interfaz de usuario de la aplicación móvil para mostrar el ritmo cardíaco</td>
        <td>Implementar la interfaz de usuario de la aplicación móvil y lógica para mostrar el ritmo cardíaco en tiempo real</td>
        <td>2 horas</td>
        <td></td>
        <td>To fix</td>
    </tr>
    <tr>
        <td>T13</td>
        <td>Implementar la interfaz de usuario de la aplicación web para mostrar el ritmo cardíaco</td>
        <td>Implementar la interfaz de usuario de la aplicación web y lógica para mostrar el ritmo cardíaco en tiempo real</td>
        <td>2 horas</td>
        <td>Lucía Aliaga</td>
        <td>To fix</td>
    </tr>
    <tr>
        <td rowspan="3">US011</td>
        <td rowspan="3">Envío de Notificación de Emergencia</td>
        <td>US011-TSK01</td>
        <td>Implementar el botón de emergencia en el embedded application</td>
        <td>Implementar la lógica para el uso del botón de emergencia en el embedded application</td>
        <td>Luis Trujillo</td>
        <td> </td>
        <td>Done</td>
    </tr>
    <tr>
        <td>US011-TSK02</td>
        <td>Implementar notificaciones en aplicación móvil</td>
        <td>Implementar la lógica para recibir notificaciones en la aplicación móvil</td>
        <td>2 horas</td>
        <td>Luis Sagastegui</td>
        <td>Done</td>
    </tr>
    <tr>
        <td>US011-TSK03</td>
        <td>Recibir notificaciones en la aplicación web</td>
        <td>Implementar la lógica para recibir notificaciones en la aplicación web</td>
        <td>2 horas</td>
        <td>Rodrigo Raymundo</td>
        <td>In Process</td>
    </tr>
    <tr>
        <td rowspan="2">US012</td>
        <td rowspan="2">Recepción de Notificaciones de Ayuda</td>
        <td>US012-TSK01</td>
        <td>Implementar interfaz de notificaciones de ayuda en aplicación móvil</td>
        <td>Implementar interfaz de notificaciones de ayuda en aplicación móvil</td>
        <td>3 horas</td>
        <td>Jen Achamizo</td>
        <td>Done</td>
    </tr>
    <tr>
        <td>US012-TSK02</td>
        <td>Interfaz de notificaciones en la aplicación web</td>
        <td>Implementar la interfaz de notificaciones en la aplicación web</td>
        <td>3 horas</td>
        <td>Lucía Aliaga</td>
        <td>In Process</td>
    </tr>
    <tr>
        <td rowspan="3">US015</td>
        <td rowspan="3">Acceso a datos de Usuario</td>
        <td>US15-TSK01</td>
        <td>Implementar formulario para agregar pacientes</td>
        <td>Implementar el formulario para poder agregar la información de los pacientes con los datos necesarios</td>
        <td> 1.5 horas</td>
        <td>Luis Trujillo </td>
        <td>Done</td>
    </tr>
    <tr>
        <td>US15-TSK02</td>
        <td>Implementar CRUD para pacientes</td>
        <td>Implementar las opciones para poder agregar, editar y eliminar la información de los pacientes luego de haberlos agregado</td>
        <td>4 horas</td>
        <td>Rodrigo Raymundo</td>
        <td>Done</td>
    </tr>
    <tr>
        <td>US15-TSK03</td>
        <td>Implementar el apartado de los pacientes</td>
        <td>Implementar el apartado de los pacientes en donde se guarde toda la información de los pacientes</td>
        <td> 2 horas</td>
        <td> Jesus Sagastegui</td>
        <td>To fix</td>
    </tr>
    <tr>
        <td rowspan="2">US019</td>
        <td rowspan="2">Recepción de Notificaciones de Ayuda</td>
        <td>US19-TSK01</td>
        <td>Interfaz móvi para visualizar el estado de los sensores</td>
        <td>Implementar la interfaz móvil y lógica para visualizar el estado de los sensores</td>
        <td> 2 horas </td>
        <td> Luis Siancas </td>
        <td>In Process</td>
    </tr>
    <tr>
        <td>US19-TSK02</td>
        <td>Interfaz web para visualizar el estado de los sensores</td>
        <td>Implementar la interfaz web y lógica para visualizar el estado de los sensores</td>
        <td> 3 horas </td>
        <td> Luis Trujillo </td>
        <td>In Process</td>
    </tr>
    <tr>
        <td rowspan="2">US020</td>
        <td rowspan="2">Asignación de Pulsera a un Usuario</td>
        <td>US20-TSK01</td>
        <td>Creación de paciente en aplicación web</td>
        <td>Implementar la lógica en la aplicación web para crear un paciente</td>
        <td> 2 horas </td>
        <td> Lucía Aliaga </td>
        <td>Done</td>
    </tr>
    <tr>
        <td>US20-TSK02</td>
        <td>Mostrar la configuración de la banda</td>
        <td>Implementar la interfaz de usuario de la aplicación móvil y lógica para mostrar la configuración de la banda</td>
        <td> 2 horas </td>
        <td> Jean Achamizo </td>
        <td>Done</td>
    </tr>
     <tr>
        <td rowspan="2">US022</td>
        <td rowspan="2">Configuración de Pagos Automatizados</td>
        <td>US22-TSK01</td>
        <td>Implementar interfaz móvil  para la configuración de pagos</td>
        <td>Implementar la interfaz móvil y lógica para la configuración de pagos</td>
        <td> 3 horas </td>
        <td> Luis Sagastegui</td>
        <td>In Process</td>
    </tr>
    <tr>
        <td>US22-TSK02</td>
        <td>Implementar interfaz web para la configuración de pagos</td>
        <td>Implementar la interfaz web y lógica para la configuración de pagos</td>
        <td> 4 horas </td>
        <td> Luis Siancas</td>
        <td>In Process</td>
    </tr>
     <tr>
        <td rowspan="2">TS07</td>
        <td rowspan="2">Endpoint para Monitoreo de Temperatura</td>
        <td>TS07-TSK01</td>
        <td>Obtener temperatura según healthbandId</td>
        <td>Implementar la lógica para obtener la temperatura actual de la pulsera usando el healthbandId</td>
        <td> 2 horas </td>
        <td> Luis Siancas</td>
        <td>Done</td>
    </tr>
    <tr>
        <td>TS07-TSK02</td>
        <td>Pruebas unitarias para validar la obtención de  temperatura </td>
        <td>Crear pruebas unitarias para validar la correcta obtención de la temperatura y manejo de errores</td>
        <td> 3 horas</td>
        <td> Rodrigo Raymundo </td>
        <td>In Process</td>
    </tr>
    <tr>
        <td rowspan="2">TS08</td>
        <td rowspan="2">Endpoint para Monitoreo de Ritmo Cardíaco</td>
        <td>TS08-TSK01</td>
        <td>Obtener ritmo cardíaco según healthbandId</td>
        <td>Desarrollar el servicio para recuperar el ritmo cardíaco actual de la pulsera usando el healthbandId</td>
        <td> 2 horas </td>
        <td> Luis Trujillo</td>
        <td>Done</td>
    </tr>
    <tr>
        <td>TS08-TSK02</td>
        <td>Implementar manejo de errores </td>
        <td>Implementar manejo de errores para situaciones como healthbandId inválido o falta de datos</td>
        <td> 0.5 horas </td>
        <td> Luis Trujillo</td>
        <td>In Process</td>
    </tr>
    <tr>
        <td rowspan="2">TS09</td>
        <td rowspan="2">Endpoint para Alertas de Salud</td>
        <td>TS09-TSK01</td>
        <td>Enviar alertas de salud cuando se detecten valores anormales</td>
        <td>Implementar la funcionalidad para enviar alertas de salud cuando se detecten valores anormales</td>
        <td> 2 horas </td>
        <td> Jean Achamizo </td>
        <td>In Process</td>
    </tr>
    <tr>
        <td>TS09-TSK02</td>
        <td>Integración del sistema de alertas </td>
        <td>Integrar el sistema de notificaciones para enviar alertas en tiempo real a los usuarios</td>
        <td> 2 horas </td>
        <td> Luis Siancas </td>
        <td>In Process</td>
    </tr>
    <tr>
        <td rowspan="2">TS16</td>
        <td rowspan="2">Endpoints para acceso a datos del usuario</td>
        <td>TS16-TSK01</td>
        <td>Creación de los Endpoints CRUD para roles</td>
        <td>Creación de los Endpoints CRUD para la creacion, modificación y visualización de</td>
        <td> 2 horas </td>
        <td> Luis Trujillo</td>
        <td>Done</td>
    </tr>
    <tr>
        <td>TS09-TSK02</td>
        <td>Creación de los Endpoints CRUD para pacientes</td>
        <td>Creación de los Endpoints CRUD para la creacion, modificación y visualización de pacientes</td>
        <td> 2.5 horas </td>
        <td> Lucía Aliaga </td>
        <td>Done</td>
    </tr>
    <tr>
        <td rowspan="1">TS19</td>
        <td rowspan="1">Endpoint para Promedio de Pulso Cardiaco</td>
        <td>TS19-TSK01</td>
        <td>Implementar la lógica para calcular el promedio de las últimas mediciones de pulso cardiaco</td>
        <td>Implementar la lógica para calcular el promedio de las últimas mediciones de pulso cardiaco</td>
        <td> 1 hora </td>
        <td> Rodrigo Raymundo </td>
        <td>Done</td>
    </tr>
    <tr>
        <td rowspan="1">TS20</td>
        <td rowspan="1">Endpoint para Promedio de Temperatura</td>
        <td>TS20-TSK01</td>
        <td>Calcular el promedio de las últimas mediciones de temperatura</td>
        <td>Implementar la lógica para calcular el promedio de las últimas mediciones de temperatura</td>
        <td> 1 hora </td>
        <td> Rodrigo Raymundo </td>
        <td>Done</td>
    </tr>
    <tr>
        <td rowspan="1">TS21</td>
        <td rowspan="1">Lógica para leer y almacenar mensajes de la cola</td>
        <td>TS21-TSK01</td>
        <td>Lectura de la cola y almacenamiento en la base de datos</td>
        <td>Implementar logica de lectura de la cola y almacenamiento en la base de datos</td>
        <td> 3.5 horas </td>
        <td> Luis Siancas </td>
        <td>Done</td>
    </tr>
      <tr>
        <td rowspan="4">TS22</td>
        <td rowspan="4">Consultas de Cloud Api hacia Edge Api</td>
        <td>TS22-TSK01</td>
        <td>Creación de consultas para el endpoint del promedio del pulso cardiaco en Cloud</td>
        <td>Creación de consultas para el endpoint del promedio del pulso cardiaco en Cloud</td>
        <td> 2 horas </td>
        <td> Lucía Aliaga </td>
        <td>Done</td>
    </tr>
    <tr>
        <td>TS22-TSK02</td>
        <td>Creación de consultas para el endpoint del promedio del temperatura en Cloud</td>
        <td>ICreación de consultas para el endpoint del promedio del temperatura en Cloud</td>
        <td> 2 horas </td>
        <td> Lucía Aliaga </td>
        <td>Done</td>
    </tr>
    <tr>
        <td>TS22-TSK03</td>
        <td>Creación de consultas para el endpoint del pulso cardiaco actual en Cloud</td>
        <td>Creación de consultas para el endpoint del pulso cardiaco actual en Cloud</td>
        <td> 2 horas </td>
        <td> Luis Siancas </td>
        <td>Done</td>
    </tr>
    <tr>
        <td>TS22-TSK04</td>
        <td>Creación de consultas para el endpoint de la temperatura actual en Cloud</td>
        <td>Creación de consultas para el endpoint de la temperatura actual en Cloud</td>
        <td> 2 horas </td>
        <td> Luis Siancas </td>
        <td>Done</td>
    </tr>
     <tr>
        <td rowspan="1">TS23</td>
        <td rowspan="1">Despliegue de la aplicación web</td>
        <td>TS23-TSK01</td>
        <td>Despliegue de la aplicación web </td>
        <td>Configuración y despliegue de la aplicación web en Netlify</td>
        <td> 0.5 horas </td>
        <td> Lucía Aliaga y Luis Trujillo </td>
        <td>Done</td>
    </tr>
     <tr>
        <td rowspan="1">TS24</td>
        <td rowspan="1">Despliegue de la aplicación móvil </td>
        <td>TS24-TSK01</td>
        <td>Despliegue de la aplicación móvil </td>
        <td>Configuración y despliegue de la aplicación móvil en Firebase App Distribution</td>
        <td> 1 hora </td>
        <td> Jean Achamizo y Luis Sagastegui </td>
        <td>Done</td>
    </tr>
    <tr>
        <td rowspan="2">TS25</td>
        <td rowspan="2">Despliegue del edge API</td>
        <td>TS25-TSK01</td>
        <td>Despliegue del Edge API</td>
        <td>Configuración y despliegue del Edge API en Render</td>
        <td> 1 hora </td>
        <td> Luis Siancas </td>
        <td>Done</td>
    </tr>
    <tr>
        <td>TS25-TSK02</td>
        <td>Despliegue de la base de datos del Edge API</td>
        <td>Despliegue de la base de datos del Edge API</td>
        <td> 1 hora </td>
        <td> Luis Siancas </td>
        <td> Done </td>
    </tr>
    <tr>
        <td rowspan="2">TS26</td>
        <td rowspan="2">Despliegue del cloud  API</td>
        <td>TS26-TSK01</td>
        <td>Despliegue del Edge API</td>
        <td>Configuración y despliegue del cloud  API en Render</td>
         <td> 1 hora </td>
        <td> Luis Siancas </td>
        <td>Done</td>
    </tr>
    <tr>
        <td>TS26-TSK02</td>
        <td>Despliegue de la base de datos del cloud  API</td>
        <td>Despliegue de la base de datos del cloud  API</td>
         <td> 1 hora </td>
        <td> Luis Siancas </td>
        <td>Done</td>
    </tr>
    <tr>
        <td rowspan="1">TS27</td>
        <td rowspan="1">Despliegue del embedded application</td>
        <td>TS27-TSK01</td>
        <td>Despliegue del embedded application</td>
        <td>Despliegue del embedded application</td>
        <td> 0.5 horas </td>
        <td> Luis Trujillo </td>
        <td>Done</td>
    </tr>
    <tr>
        <td rowspan="2">TS28</td>
        <td rowspan="2">Endpoints para obtener los planes y suscripciones</td>
        <td>TS28-TSK01</td>
        <td>Creación y obtención de planes</td>
        <td>Implementacion de logica para la creación y la obtenciones de plane</td>
        <td> 2 horas</td>
        <td> Rodrigo Raymundo </td>
        <td>In Process</td>
    </tr>
    <tr>
        <td>TS28-TSK02</td>
        <td>Creacion y obtencion de planes en los que esta suscrito el cliente</td>
        <td>Implementacion de logica para la creacion y obtencion de los planes en los que esta suscrito el cliente</td>
        <td> 2 horas</td>
        <td> Rodrigo Raymundo </td>
        <td>In Process</td>
    </tr>
    <tr>
        <td rowspan="3">TS29</td>
        <td rowspan="3">Generación de notificaciones</td>
        <td>TS29-TSK01</td>
        <td>Almacenar notificaciones generadas</td>
        <td>Implementar logica par almacenar las notificaciones generadas</td>
        <td> 1 hora </td>
        <td> Luis Trujillo </td>
        <td>In Process</td>
    </tr>
    <tr>
        <td>TS29-TSK02</td>
        <td>Enviar notificaciones a usuario</td>
        <td>Crear funcionalidad para que las notificaciones sean enviadas hacia el usuario</td>
        <td> 1 hora </td>
        <td> Luis Siancas</td>
        <td>In Process</td>
    </tr>
    <tr>
        <td>TS29-TSK02</td>
        <td>Modificacion del status de la notificacion</td>
        <td>Crear ndpoints para la modificacion del status de la notificacion</td>
         <td> 1 hora </td>
        <td> Luis Siancas</td>
        <td>In Process</td>
    </tr>
    <tr>
        <td rowspan="2">TS30</td>
        <td rowspan="2">Configuración del dispositivo</td>
        <td>TS30-TSK01</td>
        <td>Configuración de dispositivos del embedded application</td>
        <td>Implementar lógica para la configuración de los dispositivos del embedded application</td>
        <td> 2 horas </td>
        <td> Jean Achamizo</td>
        <td>Done</td>
    </tr>
    <tr>
        <td>TS30-TSK02</td>
        <td>Implementar apartado de auditoria</td>
        <td>Implementar apartado de auditoria para monitoreo constante</td>
        <td> 2 horas </td>
        <td> Luis Trujillo </td>
        <td>In Process</td>
    </tr>
    <tr>
        <td rowspan="3">TS31</td>
        <td rowspan="3">Generar alertas desde el device</td>
        <td>TS31-TSK01</td>
        <td>Proximidad con objetos peligrosos en embedded application</td>
        <td>Implementar la logica en el embedded application para la proximidad con objetos peligrosos</td>
        <td> 2 horas </td>
        <td> Lucía Aliaga </td>
        <td>Done</td>
    </tr>
    <tr>
        <td>TS31-TSK02</td>
        <td>Implementar alerta frente algun accidente o parametro riesgoso</td>
        <td>Implementar logica visual de la alerta frente algun accidente o parametro riesgoso</td>
        <td> 1 hora </td>
        <td> Luis Trujillo </td>
        <td>Done</td>
    </tr>
    <tr>
        <td>TS31-TSK02</td>
        <td>Generar alerta en cloud con boton de panico</td>
        <td>Implementar funcionalidad de boton de panico que genere una alerta en cloud</td>
        <td> 1 hora </td>
        <td> Luis Trujillo </td>
        <td>In Process</td>
    </tr>
    <tr>
        <td rowspan="1">TS32</td>
        <td rowspan="1">Envío de información del device al edge API</td>
        <td>TS32-TSK01</td>
        <td>Envio de informacion del embedded application al edge API</td>
        <td>Envio de informacion de los datos recogidos por el embedded application  al edge AP</td>
        <td> 1 hora </td>
        <td> Rodrigo Raymundo</td>
        <td>Done</td>
    </tr>
</table>



#### 6.2.2.3. Development Evidence for Sprint Review

En esta sección se presentan los commits realizados en el repositorio de GitHub, donde se puede observar el trabajo colaborativo de cada integrante del equipo en el desarrollo de los productos: Web Application, Mobile Application, Edge API, Cloud API y Embedded Application. 

A continuación, se detallan las contribuciones individuales en diversas ramas del proyecto, incluyendo las implementaciones de las funcionalidades principales y las integraciones necesarias para el despliegue final del producto.

<table  align="left" border="1" width="100%">
    <tr>
        <th>Repository</th>
        <th>Branch</th>
        <th>Commit ID</th>
        <th>Commit Message</th>
        <th>Commit Message Body</th>
        <th>Commited On (Date)</th>
    </tr>
    <tr>
        <td rowspan=19>IoT-SocialTech/Front-MIAM</td>
        <td>/main</td>
        <td>1c57dd1</td>
        <td>Initial commit</td>
        <td>Initial commit</td>
        <td>26/09/2024</td>
    </tr>
    <tr>
        <td>/US06-Account</td>
        <td>5906720</td>
        <td>Feature: Account registration view completed</td>
        <td>Feature: Account registration view completed</td>
        <td>26/09/2024</td>
    </tr>
    <tr>
        <td>/US06-Account</td>
        <td>e69fbf5</td>
        <td>Feature: Creating fake API for testing</td>
        <td>Feature: Creating fake API for testing</td>
        <td>26/09/2024</td>
    </tr>
    <tr>
        <td>/US06-Account</td>
        <td>0500cb3</td>
        <td>Feature: Creating the dashboard</td>
        <td>Feature: Creating the dashboard</td>
        <td>26/09/2024</td>
    </tr>
    <tr>
        <td>/US06-Account</td>
        <td>7e85538</td>
        <td>Feature: Authentication Settings</td>
        <td>Feature: Authentication Settings</td>
        <td>26/09/2024</td>
    </tr>
    <tr>
        <td>/US06-Account</td>
        <td>f2717f7</td>
        <td>Feature: Password recovery form completed</td>
        <td>Feature: Password recovery form completed</td>
        <td>26/09/2024</td>
    </tr>
    <tr>
        <td>/development</td>
        <td>e79d4ca</td>
        <td>Feature: SideNav Component</td>
        <td>Feature: SideNav Component</td>
        <td>26/09/2024</td>
    </tr>
    <tr>
        <td>/US010-AlertsConfiguration</td>
        <td>6003c15</td>
        <td>Feature: Added band configuration interface</td>
        <td>Feature: Added band configuration interface</td>
        <td>23/10/2024</td>
    </tr>
    <tr>
        <td>/US06-US07-Temperature-Pulse-Monitoring</td>
        <td>122aeda</td>
        <td>Feature: Vital signs chart added</td>
        <td>Feature: Vital signs chart added</td>
        <td>24/10/2024</td>
    </tr>
    <tr>
        <td>/US008-Alerts-History</td>
        <td>59ea9d7</td>
        <td>Feature: Updated table and alerts information</td>
        <td>Feature: Updated table and alerts information</td>
        <td>25/10/2024</td>
    </tr>
    <tr>
        <td>/US020-Assign-Band</td>
        <td>24fcecc</td>
        <td>Feature: Patient information interface added</td>
        <td>Feature: Patient information interface added</td>
        <td>24/10/2024</td>
    </tr>
    <tr>
        <td>/US020-Assign-Band</td>
        <td>13ec953</td>
        <td>feat: US020 Integration with fake api</td>
        <td>feat: US020 Integration with fake api</td>
        <td>25/10/2024</td>
    </tr>
    <tr>
        <td>/US020-Assign-Band</td>
        <td>076aee9</td>
        <td>fix: mockup api integration</td>
        <td>fixed mockup api integration</td>
        <td>02/11/2024</td>
    </tr>
    
</table>

<table align="left" border="1" width="100%">
    <tr>
        <th>Repository</th>
        <th>Branch</th>
        <th>Commit ID</th>
        <th>Commit Message</th>
        <th>Commit Message Body</th>
        <th>Commited On (Date)</th>
    </tr>
    <tr>
        <td rowspan=50>IoT-SocialTech/miam-edge-api</td>
        <td>/TS07-TSK01</td>
        <td>8ef9c2a</td>
        <td>feat: added get temperature functionality</td>
        <td>feat: added functionality to return current patient temperature and included shared files</td>
        <td>20/10/2024</td>
    </tr>
    <tr>
        <td>/TS07-TSK01</td>
        <td>923d98f</td>
        <td>feat: added JPA configuration and established connection with database</td>
        <td>feat: added JPA configuration and established connection with database</td>
        <td>20/10/2024</td>
    </tr>
    <tr>
        <td>/TS07-TSK01</td>
        <td>49996fa</td>
        <td>Merge pull request #2 from IoT-SocialTech/jpa-conf</td>
        <td>Added JPA configuration</td>
        <td>20/10/2024</td>
    </tr>
    <tr>
        <td>/TS07-TSK01</td>
        <td>695887f</td>
        <td>feat: added JMS configuration and established connection with IBM MQ queues</td>
        <td>feat: added JMS configuration and established connection with IBM MQ queues</td>
        <td>20/10/2024</td>
    </tr>
    <tr>
        <td>/TS07-TSK01</td>
        <td>d5a5e9e</td>
        <td>feat: added JMS configuration and established connection with IBM MQ queues</td>
        <td>feat: added JMS configuration and established connection with IBM MQ queues</td>
        <td>20/10/2024</td>
    </tr>
    <tr>
        <td>/TS07-TSK01</td>
        <td>2cf7dc7</td>
        <td>Initial commit: added base files</td>
        <td>Initial commit: added base files</td>
        <td>30/09/2024</td>
    </tr>
    <tr>
        <td>/TS08-TSK01</td>
        <td>4bd451d</td>
        <td>feat: added get heart rate functionality</td>
        <td>feat: added functionality to return current patient heart rate</td>
        <td>20/10/2024</td>
    </tr>
    <tr>
        <td>/TS08-TSK01</td>
        <td>1306aa3</td>
        <td>feat: added get temperature functionality</td>
        <td>feat: added functionality to return current patient temperature and included shared files</td>
        <td>20/10/2024</td>
    </tr>
    <tr>
        <td>/TS08-TSK01</td>
        <td>0f970fb</td>
        <td>Merge pull request #4 from IoT-SocialTech/TS08-TSK01</td>
        <td>feat: added get heart rate functionality</td>
        <td>20/10/2024</td>
    </tr>
    <tr>
        <td>/TS19-TSK01</td>
        <td>5ab3960</td>
        <td>feat: added get average heart rate functionality</td>
        <td>feat: added functionality to return average patient heart rate</td>
        <td>20/10/2024</td>
    </tr>
    <tr>
        <td>/TS19-TSK01</td>
        <td>684cdfe</td>
        <td>Merge pull request #7 from IoT-SocialTech/TS19-TSK01</td>
        <td>feat: added get average heart rate functionality</td>
        <td>20/10/2024</td>
    </tr>
    <tr>
        <td>/TS19-TSK01</td>
        <td>4dd6029</td>
        <td>feat: added get average heart rate functionality</td>
        <td>feat: added functionality to return average patient heart rate</td>
        <td>20/10/2024</td>
    </tr>
    <tr>
        <td>/TS20-TSK01</td>
        <td>e1b80c7</td>
        <td>feat: added get average temperature functionality</td>
        <td>feat: added functionality to return average patient temperature</td>
        <td>20/10/2024</td>
    </tr>
    <tr>
        <td>/TS20-TSK01</td>
        <td>3797c40</td>
        <td>fix: error</td>
        <td>fix: error</td>
        <td>20/10/2024</td>
    </tr>
    <tr>
        <td>/TS20-TSK01</td>
        <td>59385b5</td>
        <td>Merge remote-tracking branch 'origin/develop' into develop</td>
        <td>Conflicts resolved in MetricsController.java</td>
        <td>20/10/2024</td>
    </tr>
    <tr>
        <td>/TS20-TSK01</td>
        <td>d7aeee0</td>
        <td>feat: added get average heart rate functionality</td>
        <td>feat: added functionality to return average patient heart rate</td>
        <td>20/10/2024</td>
    </tr>
    <tr>
        <td>/TS20-TSK01</td>
        <td>b43eed1</td>
        <td>feat: added get average heart rate functionality</td>
        <td>feat: added functionality to return average patient heart rate</td>
        <td>20/10/2024</td>
    </tr>
    <tr>
        <td>/TS21-TSK01</td>
        <td>5d79f14</td>
        <td>feat: added functionality to store device measurements in the database</td>
        <td>feat: added functionality to store device measurements in the database</td>
        <td>20/10/2024</td>
    </tr>
    <tr>
        <td>/TS21-TSK01</td>
        <td>5291ed4</td>
        <td>Merge pull request #9 from IoT-SocialTech/TS20-TSK01</td>
        <td>feat: added get average temperature functionality</td>
        <td>20/10/2024</td>
    </tr>
    <tr>
        <td>/TS21-TSK01</td>
        <td>e1b80c7</td>
        <td>feat: added get average temperature functionality</td>
        <td>feat: added functionality to return average patient temperature</td>
        <td>20/10/2024</td>
    </tr>
    <tr>
        <td>/TS21-TSK01</td>
        <td>03dda9c</td>
        <td>Merge pull request #10 from IoT-SocialTech/TS21-TSK01</td>
        <td>feat: added functionality to store device measurements in the database</td>
        <td>20/10/2024</td>
    </tr>
    <tr>
        <td>/develop</td>
        <td>03dda9c</td>
        <td>Merge pull request #10 from IoT-SocialTech/TS21-TSK01</td>
        <td>feat: added functionality to store device measurements in the database</td>
        <td>20/10/2024</td>
    </tr>
    <tr>
        <td>/develop</td>
        <td>5d79f14</td>
        <td>feat: added functionality to store device measurements in the database</td>
        <td>feat: added functionality to store device measurements in the database</td>
        <td>20/10/2024</td>
    </tr>
    <tr>
        <td>/develop</td>
        <td>5291ed4</td>
        <td>Merge pull request #9 from IoT-SocialTech/TS20-TSK01</td>
        <td>feat: added get average temperature functionality</td>
        <td>20/10/2024</td>
    </tr>
    <tr>
        <td>/develop</td>
        <td>e1b80c7</td>
        <td>feat: added get average temperature functionality</td>
        <td>feat: added functionality to return average patient temperature</td>
        <td>20/10/2024</td>
    </tr>
    <tr>
        <td>/develop</td>
        <td>3797c40</td>
        <td>fix: error</td>
        <td>fix: error</td>
        <td>20/10/2024</td>
    </tr>
    <tr>
        <td>/develop</td>
        <td>59385b5</td>
        <td>Merge remote-tracking branch 'origin/develop' into develop</td>
        <td>Conflicts resolved in MetricsController.java</td>
        <td>20/10/2024</td>
    </tr>
</table>

Implementación Movile IoT-SocialTech mobile-application-miam

<table align="left" border="1" width="100%"> <tr> <th>Repository</th> <th>Branch</th> <th>Commit ID</th> <th>Commit Message</th> <th>Commit Message Body</th> <th>Commited On (Date)</th> </tr> <tr> <td rowspan=18>IoT-SocialTech/mobile-application-miam</td> <td>/ts24-mobile-app-implementation</td> <td>2af1951</td> <td>feat: seach dependence for change name</td> <td>Búsqueda de dependencias para cambiar el nombre</td> <td>01/11/2024</td> </tr> <tr> <td>/ts24-mobile-app-implementation</td> <td>34a4200</td> <td>feat: change name for integrate firebase</td> <td>Cambio de nombre para integración con Firebase</td> <td>01/11/2024</td> </tr> <tr> <td>/ts24-mobile-app-implementation</td> <td>469c2eb</td> <td>feat: add dependence for change name aplication:change_app_package_name</td> <td>Agregar dependencia para cambio de nombre de la aplicación: change_app_package_name</td> <td>01/11/2024</td> </tr> <tr> <td>/ts24-mobile-app-implementation</td> <td>3286872</td> <td>Merge pull request #3 from IoT-SocialTech/us012-reception-notifications</td> <td>Integración de notificaciones de recepción</td> <td>31/10/2024</td> </tr> <tr> <td>/ts24-mobile-app-implementation</td> <td>b5e7960</td> <td>feat: add API logic</td> <td>Añadir lógica de API</td> <td>31/10/2024</td> </tr> <tr> <td>/ts24-mobile-app-implementation</td> <td>3831621</td> <td>fix: routing in BottomNavigationBarItem</td> <td>Corregir la ruta en BottomNavigationBarItem</td> <td>27/10/2024</td> </tr> <tr> <td>/ts24-mobile-app-implementation</td> <td>3013760</td> <td>feat: add BottomNavigationBarItem</td> <td>Añadir BottomNavigationBarItem</td> <td>27/10/2024</td> </tr> <tr> <td>/ts24-mobile-app-implementation</td> <td>97ceabe</td> <td>Merge pull request #2 from IoT-SocialTech/us012-reception-notifications</td> <td>Integración de notificaciones de recepción</td> <td>25/10/2024</td> </tr> <tr> <td>/ts24-mobile-app-implementation</td> <td>5d678bd</td> <td>feat-tsk01: implementation of interfast notifications</td> <td>Implementación de notificaciones de interfaz</td> <td>25/10/2024</td> </tr> <tr> <td>/us020-assignment-of-bracelets</td> <td>6e213c8</td> <td>fix: fix login screen, configure main screen</td> <td>Corrección de la pantalla de inicio de sesión y configuración de la pantalla principal</td> <td>01/11/2024</td> </tr> <tr> <td>/us020-assignment-of-bracelets</td> <td>8b107f4</td> <td>fix: screen configuration, The cards are modified to display it differently</td> <td>Configuración de pantalla, las tarjetas se modifican para mostrarse de manera diferente</td> <td>31/10/2024</td> </tr> <tr> <td>/us020-assignment-of-bracelets</td> <td>0eea0f7</td> <td>feat: screen configuration, add connection</td> <td>Configuración de pantalla, se añade conexión</td> <td>31/10/2024</td> </tr> <tr> <td>/us020-assignment-of-bracelets</td> <td>10a8874</td> <td>feat: add configuration screen</td> <td>Añadir pantalla de configuración</td> <td>31/10/2024</td> </tr> <tr> <td>/us020-assignment-of-bracelets</td> <td>3286872</td> <td>Merge pull request #3 from IoT-SocialTech/us012-reception-notifications</td> <td>Integración de notificaciones de recepción</td> <td>31/10/2024</td> </tr> <tr> <td>/us020-assignment-of-bracelets</td> <td>b5e7960</td> <td>feat: add API logic</td> <td>Añadir lógica de API</td> <td>31/10/2024</td> </tr> </table>


#### 6.2.2.4. Testing Suite Evidence for Sprint Review
En esta sección se presenta la evidencia de la suite de pruebas utilizada para la revisión del sprint. Para asegurar la funcionalidad y el cumplimiento de los criterios de aceptación de cada historia de usuario (US) en esta entrega, se implementaron pruebas automáticas con el uso de Gherkin. Cada historia de usuario se describe en lenguaje Gherkin

Repositorio: https://github.com/IoT-SocialTech/features

TS21_LogicaLeerAlmacenarMensajesCola.feature
![alt text](code.png)

US007_MonitoreoRitmoCardiaco.feature
![alt text](cap-2.png)

#### 6.2.2.5. Execution Evidence for Sprint Review

*Web Application*

En este Sprint, logramos implementar varias vistas clave en la aplicación web, enfocándonos en mejorar la experiencia de configuración, gestión y monitoreo de los pacientes y sus datos de salud. A continuación, se detalla cada vista y su funcionalidad implementada:

![Login](assets/login-view.PNG)

- Band Configuration: Desarrollamos la vista para configurar la health band de cada paciente. Esta sección permite seleccionar y ajustar las alertas que recibirán el caregiver y el relative, personalizando así las notificaciones y el tipo de seguimiento que recibirán según las necesidades del paciente.

![Band Configuration Web App](assets/band-configuration-view.PNG)

- Patients: Implementamos la vista de creación y gestión de pacientes, donde se pueden registrar nuevos pacientes y vincularlos tanto a un caregiver como a un relative. Esta funcionalidad permite gestionar de forma centralizada la información relevante de cada paciente.

![Patients Web App](assets/patients-view.PNG)

- Alerts: En esta sección, añadimos un historial de alertas para cada paciente, donde se pueden visualizar las notificaciones pasadas y su información detallada, permitiendo un seguimiento preciso de los eventos críticos que han ocurrido en cada caso.

![Alerts Web App](assets/alerts-view.PNG)

![Alerts Info Web App](assets/alerts-info-view.PNG)

- Dashboard: Avanzamos en el desarrollo del Dashboard, incluyendo gráficos de temperatura y pulso para facilitar el monitoreo de estos parámetros en tiempo real. También se añadió la visualización de los caregivers y sus pacientes.

![Dashboard Web App](assets/dashboard-view.PNG)

<br> Enlace al video: </br>
<a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u20211a452_upc_edu_pe/EZJY3UCOxHJJh2amSyocaoYBQjKLvHMUlhnFMNzpdL4I3Q?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=XIAQ8s"> https://goo.su/orFzn6 </a>

*Mobile Application*

Para la realización de la aplicación móvil se abarcaron varios User Stories, para este Sprint se realizó la pantalla de Login en donde el usuario podrá crearse una cuenta o entrar con su cuenta de Google. Al ingresar a la aplicación, podremos visualizar como primera instancia la creación del Dashboard, en donde se visualiza varios datos importantes de los pacientes como su medicación y el monitoreo de las señales vitales. También se pudo implementar de manera correcta las Alertas de los pacientes en caso suceda algo fuera de lo habitual. La pantalla que más consideramos importante es el Band Configuration. Donde se muestra una lista de Pacientes y en donde se puede gestionar las alertas en base a la temperatura o el pulso del paciente. Para el siguiente Sprint hemos avanzado en distintos User Stories que aún faltan corregir ya que siguen con problemas mínimos, pero consideramos que es un gran avance para este Sprint.

![Mobile Evidence](assets/evidence.jpg)

<br> Enlace al video: </br>

https://upcedupe-my.sharepoint.com/:v:/g/personal/u202014249_upc_edu_pe/ETL5B6zfuiNJv6oH_idvWjMBmnbkiGAgobXl4jsWpWPQSA?e=bB71qy&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

#### 6.2.2.6. Services Documentation Evidence for Sprint Review

En este Sprint, avanzamos en la documentación de los Endpoints desarrollados, asegurando claridad y facilidad de integración mediante OpenAPI. A continuación, se presenta una tabla con las acciones soportadas para cada Endpoint, incluyendo los métodos HTTP, parámetros, ejemplos de llamadas y respuestas.

#### 6.2.2.7. Software Deployment Evidence for Sprint Review

*Web Application*

Durante este Sprint se realizó el despliegue de la aplicación web en Netlify. Este proceso incluyó la creación y configuración de los recursos necesarios en la plataforma, asegurando la disponibilidad y accesibilidad de la aplicación en un entorno de producción.

Para llevar a cabo el despliegue en Netlify, se realizaron los siguientes pasos:

**1. Configuración de la Cuenta y Proyecto en Netlify:** Se accedió a una cuenta ya existente y se configuró el repositorio con el código fuente de la aplicación web.

**2. Conexión del Repositorio:** Se configuró la rama `development` para el despliegue.

**3. Configuración de las Opciones de Build y Deployment:** Se configurarion  las opciones de build en Netlify, especificando el comando de compilación

**4. Ejecución del Despliegue Inicial:** Una vez configurados los detalles de compilación, Netlify ejecuta automáticamente el primer despliegue. En este paso, Netlify toma el código del repositorio, lo construye y publica la aplicación en un dominio temporal. Posteriormente se configuró el dominio.

![Web App Deployment on Netlify](assets/netlify-miam.PNG)
![Web App Deployment on Netlify](assets/last-deploy-web.PNG)

Enlace: <a href="https://miam-site.netlify.app/">https://miam-site.netlify.app/ </a>

*Mobile Application*

Durante este Sprint, se realizó el despliegue de la aplicación móvil utilizando Firebase App Distribution. Este proceso incluyó la configuración y publicación de la aplicación, asegurando que los usuarios de prueba y los equipos de desarrollo pudieran acceder a la versión más reciente en un entorno de pruebas controlado.

Para llevar a cabo el despliegue en Firebase App Distribution, se siguieron los siguientes pasos:

**1. Configuración de la Cuenta y Proyecto en Firebase:** Se accedió a una cuenta ya existente en Firebase y se configuró el proyecto para el despliegue de la aplicación móvil.
![alt text](image-4.png)
![alt text](image.png)

**2. Integración del Repositorio de Código:** Se configuró la rama de desarrollo en el repositorio para generar automáticamente builds de la aplicación y enviarlas a Firebase.

**3. Configuración de las Opciones de Build:** En el archivo de configuración, se especificaron los detalles de compilación para que la aplicación se genere correctamente antes de ser distribuida. Este proceso incluyó la configuración de los scripts necesarios para la integración continua.

Enlace: <a href="https://appdistribution.firebase.dev/i/bc9e72d1b2b27dd6">https://appdistribution.firebase.dev/i/bc9e72d1b2b27dd6</a>


**4. Ejecución del Despliegue a Firebase App Distribution:** Una vez que se completó la configuración, el proceso de CI/CD envió automáticamente el build a Firebase App Distribution. Desde allí, los usuarios de prueba y el equipo de desarrollo recibieron invitaciones por correo electrónico para descargar e instalar la aplicación en sus dispositivos.

![alt text](image-1.png)


*Miam Edge API*

![Miam Edge API on Render](assets/edge.PNG)

*Miam Cloud API*

![Miam cloud API on Render](assets/cloud.PNG)

#### 6.2.2.8. Team Collaboration Insights during Sprint

En este Sprint, el equipo trabajó de manera colaborativa en la implementación de los distintos componentes del proyecto, abarcando los Web Services y las Aplicaciones. La contribución de cada miembro quedó reflejada en la actividad de commits y los analíticos de colaboración en GitHub, los cuales se presentan en esta sección con capturas de pantalla.

Para cada producto, se detalla la participación de los miembros del equipo, quienes han contribuido en la implementación de funcionalidades clave.

*Web Application*

![Web App Network Graph](assets/network-web.PNG)

*Mobile Application*

![Web App Pulse](assets/pulse-mobile.PNG)

![Mobile App Network Graph](assets/network-mobile.PNG)

*Embedded Application*

![Embedded App Pulse](assets/pulse-embedded.PNG)

![Embedded App Network Graph](assets/network-embedded.PNG)

*Edge API*

![Edge API Network Graph](assets/network-edgeapi.PNG)

*Cloud API*

![Cloud API Pulse](assets/pulse-cloudapi.PNG)

![Cloud API Network Graph](assets/network-cloudapi.PNG)

#### 6.3 Validation Interviews.

#### 6.3.1. Diseño de Entrevistas.

*Para Cuidadores de Adultos Mayores (Caregivers)*

<br>¿Cuáles son los mayores desafíos que enfrentas al monitorear los signos vitales de los adultos mayores a tu cargo?</br>
<br>¿Con qué frecuencia monitoreas la temperatura y el pulso de tus pacientes? ¿Cuál es tu método actual para registrar estos datos?</br>
<br>¿Qué tan importante sería para ti tener acceso a estos datos en tiempo real?</br>
<br>¿Qué valor le darías a una alerta inmediata si los signos vitales de un paciente están fuera de los rangos normales?</br>
<br>¿Cómo prefieres acceder a los datos de los pacientes (móvil, tablet, computadora)?</br>
<br>¿Qué problemas o preocupaciones te gustaría que esta aplicación te ayudara a resolver?</br>
<br>¿Te resultaría útil una opción para revisar los historiales de signos vitales de los pacientes en la aplicación? ¿Cómo la usarías en tu rutina?</br>
<br>¿Qué características crees que le faltarían a una herramienta que solo monitorea pulso y temperatura para que sea completa?</br>
<br>¿Hay otras métricas o información sobre el paciente que te gustaría poder rastrear o visualizar desde la misma plataforma?</br>
<br>¿Cuáles son tus expectativas en cuanto a la facilidad de uso de la aplicación? ¿Prefieres una interfaz más simple o más detallada?</br>

<br>*Para Dueños de Casas de Reposo (Nursing Home Owners)*

<br>¿Cuáles son los principales problemas que experimentan los cuidadores de tu institución al monitorear los signos vitales de los residentes?</br>
<br>¿Qué métodos utilizan actualmente para llevar el control de los signos vitales y cómo se almacenan estos datos?</br>
<br>¿Consideras importante tener acceso centralizado y en tiempo real a la información de salud de tus residentes?</br>
<br>¿Qué impacto crees que tendría la capacidad de recibir alertas sobre signos vitales en el bienestar de los pacientes y en la eficiencia del personal?</br>
<br>¿Cómo se integraría una aplicación de este tipo en la rutina diaria de tu casa de reposo?</br>
<br>¿Cuáles son tus preocupaciones en cuanto a la privacidad y seguridad de los datos de los residentes?</br>
<br>¿Consideras importante que esta información esté disponible en una plataforma web además de la móvil? ¿Por qué?</br>
<br>¿Qué tipo de reportes o análisis te gustaría recibir sobre el estado de salud de tus residentes?</br>
<br>¿Qué funcionalidades crees que serían esenciales en una herramienta de monitoreo de salud para una casa de reposo?</br>
<br>¿Qué tan dispuestos estarían a adoptar esta tecnología si mejora la calidad de atención y facilita el trabajo de los cuidadores?</br>

#### 6.3.2. Registro de Entrevistas.

#### 6.3.3. Evaluaciones según heurísticas.

#### 6.4. Video About-the-Product.

En esta sección se incluye un video promocional que ofrece un primer vistazo a nuestro producto. El video está diseñado para comunicar de manera atractiva y concisa el valor que ofrece nuestro producto, mencionando el público objetivo y beneficios.

![About The Product](assets/about-the-product.PNG)
<br> Enlace al video: </br>
<a href="https://goo.su/KlSALD2"> https://goo.su/KlSALD2 </a>

# Conclusiones

El sistema de pulseras IoT contribuye significativamente a la mejora de la calidad de vida de las personas mayores al ofrecerles una solución de monitoreo constante de sus signos vitales. A través de la detección en tiempo real de anomalías en la temperatura o el ritmo cardíaco, los cuidadores pueden reaccionar rápidamente ante posibles emergencias, lo que proporciona una mayor sensación de seguridad tanto para los usuarios como para sus familiares.

El proyecto tiene un impacto social positivo al ofrecer una solución tecnológica que permite a las personas mayores vivir de manera más independiente, mientras que los cuidadores y familiares pueden estar tranquilos al saber que las personas bajo su cuidado están siendo monitoreadas constantemente. Además, el sistema fomenta la prevención y rápida respuesta ante emergencias, reduciendo el riesgo de incidentes graves y mejorando la seguridad general de los usuarios.

# Bibliografía
 
 Dorri, S., Zabolinezhad, H., & Sattari, M. (2023). *The application of Internet of Things for the elderly health safety: A systematic review*. Advances in Biomedical Research, 12, 109. https://doi.org/10.4103/abr.abr_197_22 

Giulianelli, D., De Luca, G., De Luca, S., García, G., Carnuccio, E., Valiente, W., & Volker, M. (2017). *Diseño de sistema IoT de monitoreo y alarma para personas mayores*. Repositorio institucional de la UNLP, Universidad Nacional de La Plata.  https://sedici.unlp.edu.ar/handle/10915/62406 

Ministerio de Salud. (2018, 13 de diciembre). *Uno de cada tres adultos mayores de 65 años sufre una caída*. https://www.gob.pe/institucion/minsa/noticias/23629-uno-de-cada-tres-adultos-mayores-de-65-anos-sufre-una-caida

Suárez, G., Velasco, V., Limones, M. , Reyes, H., & Delgado, V. (2020). *Caídas en el adulto mayor y factores de riesgo*. European Journal of Child Development, Education and Psychopathology, 8(1), 47–56. https://doi.org/10.30552/ejpad.v8i1.130 

--- 

# Anexos

## Videos de Exposición

| Enlace                                             | Fecha        | Entregable                       |
|----------------------------------------------------|--------------|----------------------------------|
| https://goo.su/sorVJws   | 07/09/2024   | TB1         |
| https://goo.su/8Zz305      | 26/09/2024   | TP        |
| https://goo.su/tYkZtN      | 02/11/2024   | TB2        |

## Diagrama C4 MIAM
https://structurizr.com/share/95614/diagrams#SystemContext

### 6.2.2. Sprint 3

#### 6.2.2.1. Sprint Planning 3

<table align="center"  border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td>
            <b>Sprint #</b>
        </td>
        <td>
            <b>Sprint 3</b>           
        </td>
    </tr>
    <tr align="left">
        <td colspan="2">
            <b>Sprint Planning Background</b>
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Date</b>
        </td>
        <td>
            14/10/2024        
        </td>
    </tr>
       <tr align="left">
        <td>
            <b>Time</b>
        </td>
        <td>
            20:30         
        </td>
    </tr>
       <tr align="left">
        <td>
            <b>Location</b>
        </td>
        <td>
            Modalidad remota por Discord      
        </td>
    </tr>
     </tr>
       <tr align="left">
        <td>
            <b>Prepared By</b>
        </td>
        <td>
           Aliaga Trevejo, Lucía Guadalupe  
        </td>
    </tr>
    </tr>
       <tr align="left">
        <td>
            <b>Attendess (to planning meeting)</b>
        </td>
        <td>
            - Achamizo Huamani, Jean Carlos <br/>
            - Aliaga Trevejo, Lucía Guadalupe <br/>
            - Raymundo Guevara, Rodrigo Alejandro <br/>
            - Siancas Reategui, Luis Alberto <br/>    
            - Trujillo Lopez, Luis Alberto <br/> 
            - Sagastegui Rodriguez, Luis Jesus <br/> 
        </td>
    </tr>
      </tr>
       <tr align="left">
        <td>
            <b>Sprint 2</b>
            <b>Review Summary</b>
        </td>
        <td>
            En el sprint anterior, se completó la mayoria de las caracteristicas fundamentales para la creacion de usuarios y pacientes en el sistema de monitoreo. 
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Sprint 2</b>
            <b>Retrospective Summary</b>
        </td>
        <td>
          La organizacion de las tareas para el desarrollo de las caracteristicas fundamentales fue correctamente realizada, la realizacion de esta misma fue realizada en los tiempos adecuados. En este sprint consideramos que aun nos faltaba un intervalo de tiempo en donde todos nos podamos reunir como equipo. Se priorizaba las tareas mas complejas y la perfecta distribucion. 	
        </td>
    </tr>
     <tr align="left">
        <td colspan="2">
            <b>Sprint Goal & User Stories</b>
        </td>
        </tr>
    <tr align="left">
      <td>
        <b>Sprint 3 Goal</b>
      </td>
      <td>
           Our focus is on enabling users to generate detailed health reports, view real-time notifications and alerts, and update their subscription plans. We believe this enhances the user experience by providing important insights into the health data, immediate awareness of system alerts, and flexibility in managing their subscription. This will be confirmed when users can successfully generate reports, view notifications and alerts in real time, and update their subscription plans using the implemented endpoints.
      </td>
    </tr>
    </tr>
      <tr align="left">
        <td>
            <b>Sprint 1 Velocity</b>
        </td>
        <td>
            -
        </td>
    </tr>
       <tr align="left">
        <td>
            <b>Sum of Story Points</b>
        </td>
        <td>
            -
        </td>
    </tr>
</table> 

#### 6.2.2.2. Sprint Backlog 3

En esta sección se especifican los detalles del Sprint Backlog, que es una lista de tareas que se han realizado para completar el Sprint 2.


![Sprint Backlog 3](assets/sprint3_trello.png)

<br> Enlace del tablero: </br>
<a href="https://trello.com/invite/b/67127f4727ed7ccde1bbbc90/ATTI96acb467f4e57fe2509686befd5449c2E7848092/sprint-backlog-2"> https://trello.com/invite/b/67127f4727ed7ccde1bbbc90/ATTI96acb467f4e57fe2509686befd5449c2E7848092/sprint-backlog-2 </a>

<table align="center" border="1" width="90%" style="text-align:center">
    <tr>
        <td colspan="1"><b>Sprint #</b></td>
        <td colspan="7"><b>Sprint 3</b></td>
    </tr>
    <tr>
        <td colspan="2"><b>User Story</b></td>
        <td colspan="6"><b>Work-Item / Task</b></td>
    </tr>
    <tr>
        <td><b>Id</b></td>
        <td><b>Title</b></td>
        <td><b>Id</b></td>
        <td><b>Title</b></td>
        <td><b>Description</b></td>
        <td><b>Estimation(Hours)</b></td>
        <td><b>Assigned To</b></td>
        <td><b>Status(To-do/ In-Process/ To-Review/ Done)</b></td>
    </tr>
    <tr>
        <td rowspan="4">US008</td>
        <td rowspan="4">Alertas de Salud</td>
        <td>US08-TSK01</td>
        <td>Implementar la interfaz en la aplicacion web para alertas</td>
        <td>Implementar la interfaz en la aplicacion web para visualizar las alertas recibidas</td>
        <td>- horas</td>
        <td>abc</td>
        <td>To Fix </td>
    </tr>
    <tr>
        <td>US08-TSK02</td>
        <td>Implementar los mensajes de error en la aplicacion web</td>
        <td>Implementar los mensajes de error en la aplicacion web cuando el dispositivo no esta vinculado</td>
        <td>- horas</td>
        <td>abc</td>
        <td>To fix</td>
    </tr>
    <tr>
        <td>US08-TSK03</td>
        <td>Implementar la interfaz en la aplicacion movil para alertas</td>
        <td>Implementar la interfaz en la aplicacion movil para visualizar las alertas recibidas</td>
        <td>- horas</td>
        <td>abc</td>
        <td>In Process</td>
    </tr>
    <tr>
        <td>US08-TSK04</td>
        <td>Implementar los mensajes de error en la aplicacion movil</td>
        <td>Implementar los mensajes de error en la aplicacion movil cuando el dispositivo no esta vinculado</td>
        <td>- horas</td>
        <td>abc</td>
        <td>In Process</td>
    </tr>
    <tr>
        <td rowspan="2">US009</td>
        <td rowspan="2">Historial de Datos de Salud</td>
        <td>US09-TSK01</td>
        <td>Implementar filtro de datos por fecha en la aplicacion web</td>
        <td>Implementar el filtrado de datos de temperatura y ritmo cardiaco por fecha en la aplicacion web</td>
        <td>-</td>
        <td>-</td>
        <td>In Process</td>
    </tr>
    <tr>
        <td>US09-TSK02</td>
        <td>Implementar filtro de datos por fecha en la aplicacion movil</td>
        <td>Implementar el filtrado de datos de temperatura y ritmo cardiaco por fecha en la aplicacion movil</td>
        <td>- horas</td>
        <td>-</td>
        <td>In Process</td>
    </tr>
    <tr>
        <td rowspan="4">US010</td>
        <td rowspan="4">Configuración de Alertas Personalizadas</td>
        <td>US010-TSK01</td>
        <td>Implementar la interfaz web para configurar el umbral de temperatura</td>
        <td>Implementar la interfaz en la aplicacion web para configurar el umbral de temperatura</td>
        <td>- horas</td>
        <td>-</td>
        <td>Done</td>
    </tr>
    <tr>
        <td>US010-TSK02</td>
        <td>Implementar la interfaz movil para configurar el umbral de temperatura</td>
        <td>Implementar la interfaz en la aplicacion movil para configurar el umbral de temperatura</td>
        <td>- horas</td>
        <td>-</td>
        <td>Done</td>
    </tr>
    <tr>
        <td>US010-TSK03</td>
        <td>Implementar la interfaz web para configurar el umbral de ritmo cardiaco</td>
        <td>Implementar la interfaz en la aplicacion web para configurar el umbral de ritmo cardiaco</td>
        <td>- horas</td>
        <td>-</td>
        <td>Done</td>
    </tr>
    <tr>
        <td>US010-TSK04</td>
        <td>Implementar la interfaz movil para configurar el umbral de ritmo cardiaco</td>
        <td>Implementar la interfaz en la aplicacion movil para configurar el umbral de ritmo cardiaco</td>
        <td>- horas</td>
        <td>-</td>
        <td>Done</td>
    </tr>
    <tr>
        <td rowspan="2">US013</td>
        <td rowspan="2">Gestión de Notificaciones</td>
        <td>US013-TSK01</td>
        <td>Implementar la interfaz en la aplicacion web para la visualizacion de alertas</td>
        <td>Implementar la interfaz en la aplicacion web para la visualizacion de alertas e informacion adicional</td>
        <td>- horas</td>
        <td>-</td>
        <td>To Review</td>
    </tr>
    <tr>
        <td>US013-TSK02</td>
        <td>Implementar la interfaz en la aplicacion movil para la visualizacion de alertas</td>
        <td>Implementar la interfaz en la aplicacion movil para la visualizacion de alertas e informacion adicional</td>
        <td>- horas</td>
        <td>-</td>
        <td>To Review</td>
    </tr>
    <tr>
        <td rowspan="2">US014</td>
        <td rowspan="2">Configuración de Alertas de Emergencia</td>
        <td>US14-TSK01</td>
        <td>Implementar la interfaz movil para configurar las alertas</td>
        <td>Implementar la interfaz en la aplicacion movil para configurar las notificaciones de alertas de emergencia</td>
        <td>- horas</td>
        <td>- </td>
        <td>To Review</td>
    </tr>
    <tr>
        <td>US14-TSK02</td>
        <td>Implementar la interfaz web para configurar las alertas</td>
        <td>Implementar la interfaz en la aplicacion web para configurar las notificaciones de alertas de emergencia</td>
        <td>- horas</td>
        <td>-</td>
        <td>To Review</td>
    </tr>
    <tr>
        <td rowspan="2">US016</td>
        <td rowspan="2">Gestión de Pulseras Alquiladas</td>
        <td>US16-TSK01</td>
        <td>Implementar la logica en la aplicacion web para cambiar el estado de una pulsera</td>
        <td>Implementar la logica en la aplicacion web para cambiar el estado de una pulsera</td>
        <td> - horas </td>
        <td> - </td>
        <td>To Review</td>
    </tr>
    <tr>
        <td>US16-TSK02</td>
        <td>Implementar la logica en la aplicacion web para cambiar el estado de una pulsera</td>
        <td>Implementar la logica en la aplicacion web para cambiar el estado de una pulsera</td>
        <td> - horas </td>
        <td> -</td>
        <td>To Review</td>
    </tr>
    <tr>
        <td rowspan="2">US017</td>
        <td rowspan="2">Visualización de Pulseras Disponibles</td>
        <td>US17-TSK01</td>
        <td>Implementar la interfaz web para listar las pulseras disponibles</td>
        <td>Implementar la interfaz y logica en la aplicacion web para listar las pulseras disponibles</td>
        <td>- horas </td>
        <td>-</td>
        <td>In Process</td>
    </tr>
    <tr>
        <td>US17-TSK02</td>
        <td>Implementar la interfaz movil para listar las pulseras disponibles</td>
        <td>Implementar la interfaz y logica en la aplicacion movil para listar las pulseras disponibles</td>
        <td>- horas </td>
        <td>-</td>
        <td>To Review</td>
    </tr>
     <tr>
        <td rowspan="4">US018</td>
        <td rowspan="4">Generación de Informes de Uso</td>
        <td>US18-TSK01</td>
        <td>Implementar la logica en la aplicacion web para generar un informe de uso</td>
        <td>Implementar la logica en la aplicacion web para generar un informe de uso</td>
        <td>- horas</td>
        <td>-</td>
        <td>To Review</td>
    </tr>
    <tr>
        <td>US18-TSK02</td>
        <td>Implementar la interfaz en la aplicacion web para mostrar un informe de uso</td>
        <td>Implementar la interfaz en la aplicacion web para mostrar un informe de uso</td>
        <td>- horas </td>
        <td>-</td>
        <td>To Review</td>
    </tr>
    <tr>
        <td>US18-TSK03</td>
        <td>Implementar la logica en la aplicacion movil para generar un informe de uso</td>
        <td>Implementar la logica en la aplicacion movil para generar un informe de uso</td>
        <td>- horas </td>
        <td>-</td>
        <td>To Review</td>
    </tr>
    <tr>
        <td>US18-TSK04</td>
        <td>Implementar la interfaz en la aplicacion movil para mostrar un informe de uso</td>
        <td>Implementar la interfaz en la aplicacion movil para mostrar un informe de uso</td>
        <td>- horas </td>
        <td>-</td>
        <td>To Review</td>
    </tr>
    <tr>
        <td rowspan="2">US021</td>
        <td rowspan="2">Generación de Informes Financieros</td>
        <td>US021-TSK01</td>
        <td>Implementar la interfaz web y logica para generar un informe financiero</td>
        <td>Implementar la interfaz en la aplicacion web y logica para generar un informe financiero</td>
        <td>- horas </td>
        <td>-</td>
        <td>In Process</td>
    </tr>
    <tr>
        <td>US021-TSK02</td>
        <td>Implementar la interfaz movil y logica para generar un informe financiero</td>
        <td>Implementar la interfaz en la aplicacion movil y logica para generar un informe financiero</td>
        <td>- horas</td>
        <td>- </td>
        <td>In Process</td>
    </tr>
    <tr>
        <td rowspan="4">US025</td>
        <td rowspan="4">Acceso Rápido a Datos de la Pulsera</td>
        <td>US025-TSK01</td>
        <td>Implementar la logica en la aplicacion web para mostrar la temperatura</td>
        <td>Implementar la logica en la interfaz de la aplicacion web para mostrar el ultimo registro de temperatura del paciente</td>
        <td>- horas </td>
        <td>-</td>
        <td>To Fix</td>
    </tr>
    <tr>
        <td>US025-TSK02</td>
        <td>Implementar la logica en la aplicacion web para mostrar el ritmo cardiaco</td>
        <td>Implementar la logica en la interfaz de la aplicacion web para mostrar el ultimo registro del ritmo cardiaco del paciente</td>
        <td>- horas</td>
        <td>- </td>
        <td>To Fix</td>
    </tr>
    <tr>
        <td>US025-TSK03</td>
        <td>Implementar mensaje de error en la aplicacion web</td>
        <td>Implementar mensaje de error en la aplicacion web cuando se pierde la conexion con la banda</td>
        <td>- horas</td>
        <td>- </td>
        <td>To Fix</td>
    </tr>
    <tr>
        <td>US025-TSK04</td>
        <td>Implementar mensaje de error en la aplicacion movil</td>
        <td>Implementar mensaje de error en la aplicacion movil cuando se pierde la conexion con la banda</td>
        <td>- horas</td>
        <td>- </td>
        <td>To Fix</td>
    </tr>
    <tr>
        <td rowspan="2">US026</td>
        <td rowspan="2">Navegación Intuitiva</td>
        <td>US026-TSK01</td>
        <td>Implementar barra de navegacion en la aplicacion web</td>
        <td>Implementar la barra de navegacion y redireccion de rutas en la aplicacion web</td>
        <td>- horas </td>
        <td>-</td>
        <td>Done</td>
    </tr>
    <tr>
        <td>US026-TSK02</td>
        <td>Implementar barra de navegacion en la aplicacion movil</td>
        <td>Implementar la barra de navegacion y redireccion de rutas en la aplicacion movil</td>
        <td>- horas</td>
        <td>- </td>
        <td>Done</td>
    </tr>
    <tr>
        <td rowspan="4">US027</td>
        <td rowspan="4">Visualización Clara de Alertas</td>
        <td>US027-TSK01</td>
        <td>Implementar la interfaz web para mostrar de manera clara las alertas criticas</td>
        <td>Implementar la interfaz web para mostrar de manera clara las alertas criticas</td>
        <td>- horas </td>
        <td>-</td>
        <td>To Review</td>
    </tr>
    <tr>
        <td>US027-TSK02</td>
        <td>Implementar el mensaje de error de las alertas criticas en la aplicacion web</td>
        <td>Implementar el mensaje de error de las alertas criticas en la aplicacion web</td>
        <td>- horas</td>
        <td>- </td>
        <td>In Process</td>
    </tr>
    <tr>
        <td>US027-TSK03</td>
        <td>Implementar la interfaz móvil para mostrar de manera clara las alertas criticas</td>
        <td>Implementar la interfaz móvil para mostrar de manera clara las alertas criticas</td>
        <td>- horas</td>
        <td>- </td>
        <td>To Review</td>
    </tr>
    <tr>
        <td>US027-TSK04</td>
        <td>Implementar el mensaje de error de las alertas criticas en la aplicacion movil</td>
        <td>Implementar el mensaje de error de las alertas criticas en la aplicacion movil</td>
        <td>- horas</td>
        <td>- </td>
        <td>In Process</td>
    </tr>
    <tr>
        <td rowspan="2">US028</td>
        <td rowspan="2">Personalización de la Interfaz</td>
        <td>US028-TSK01</td>
        <td>Implementar la interfaz web para implementar las adaptaciones de visualizacion</td>
        <td>Implementar la interfaz web para implementar las adaptaciones de visualizacion</td>
        <td>- horas </td>
        <td>-</td>
        <td>To Do</td>
    </tr>
    <tr>
        <td>US028-TSK02</td>
        <td>Implementar la interfaz movil para implementar las adaptaciones de visualizacion</td>
        <td>Implementar la interfaz movil para implementar las adaptaciones de visualizacion</td>
        <td>- horas</td>
        <td>- </td>
        <td>To Do</td>
    </tr>
    <tr>
        <td rowspan="4">US029</td>
        <td rowspan="4">Notificaciones en Tiempo Real</td>
        <td>US029-TSK01</td>
        <td>Implementar las notificaciones instantaneas en la aplicacion web</td>
        <td>Implementar las notificaciones instantaneas en la aplicacion web</td>
        <td>- horas </td>
        <td>-</td>
        <td>In Process</td>
    </tr>
    <tr>
        <td>US029-TSK02</td>
        <td>Implementar el registro y reenvío de la notificación instantanea en caso de fallos de la aplicación web</td>
        <td>Implementar el registro y reenvío de la notificación instantanea en caso de fallos de la aplicación web</td>
        <td>- horas</td>
        <td>- </td>
        <td>In Process</td>
    </tr>
    <tr>
        <td>US029-TSK03</td>
        <td>Implementar las notificaciones instantaneas en la aplicacion movil</td>
        <td>Implementar las notificaciones instantaneas en la aplicacion movil</td>
        <td>- horas</td>
        <td>- </td>
        <td>In Process</td>
    </tr>
    <tr>
        <td>US029-TSK04</td>
        <td>Implementar el registro y reenvío de la notificación instantánea en caso de fallos de la aplicación movil</td>
        <td>Implementar el registro y reenvío de la notificación instantánea en caso de fallos de la aplicación movil</td>
        <td>- horas</td>
        <td>- </td>
        <td>In Process</td>
    </tr>
    <tr>
        <td rowspan="4">US030</td>
        <td rowspan="4">Resumen Diario de Salud</td>
        <td>US030-TSK01</td>
        <td>Implementar la interfaz de la aplicacion web que muestre el resumen del dia</td>
        <td>Implementar la interfaz de la aplicacion web que muestre el resumen del dia</td>
        <td>- horas </td>
        <td>-</td>
        <td>In Process</td>
    </tr>
    <tr>
        <td>US030-TSK02</td>
        <td>Implementar el mensaje de error del resumen del dia en la aplicacion web</td>
        <td>Implementar el mensaje de error del resumen del dia en la aplicacion web</td>
        <td>- horas</td>
        <td>- </td>
        <td>In Process</td>
    </tr>
    <tr>
        <td>US030-TSK03</td>
        <td>Implementar la interfaz de la aplicacion movil que muestre el resumen del dia</td>
        <td>Implementar la interfaz de la aplicacion movil que muestre el resumen del dia</td>
        <td>- horas</td>
        <td>- </td>
        <td>In Process</td>
    </tr>
    <tr>
        <td>US030-TSK04</td>
        <td>Implementar el mensaje de error del resumen del dia en la aplicacion movil</td>
        <td>Implementar el mensaje de error del resumen del dia en la aplicacion movil</td>
        <td>- horas</td>
        <td>- </td>
        <td>In Process</td>
    </tr>

</table>

#### 6.2.3.3. Development Evidence for Sprint Review

En esta sección se presentan los commits realizados en el repositorio de GitHub, donde se puede observar el trabajo colaborativo de cada integrante del equipo en el desarrollo de los productos: Web Application, Mobile Application, Edge API, Cloud API y Embedded Application. 

A continuación, se detallan las contribuciones individuales en diversas ramas del proyecto, incluyendo las implementaciones de las funcionalidades principales y las integraciones necesarias para el despliegue final del producto.

<table  align="left" border="1" width="100%">
    <tr>
        <th>Repository</th>
        <th>Branch</th>
        <th>Commit ID</th>
        <th>Commit Message</th>
        <th>Commit Message Body</th>
        <th>Commited On (Date)</th>
    </tr>
    <tr>
        <td rowspan=19>IoT-SocialTech/Front-MIAM</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    
</table>

<table align="left" border="1" width="100%">
    <tr>
        <th>Repository</th>
        <th>Branch</th>
        <th>Commit ID</th>
        <th>Commit Message</th>
        <th>Commit Message Body</th>
        <th>Commited On (Date)</th>
    </tr>
    <tr>
        <td rowspan=50>IoT-SocialTech/miam-edge-api</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
</table>

Implementación Movile IoT-SocialTech mobile-application-miam

<table align="left" border="1" width="100%"> 
	<tr> 
		<th>Repository</th> 
		<th>Branch</th> 
		<th>Commit ID</th> 
		<th>Commit Message</th> 
		<th>Commit Message Body</th> 
		<th>Commited On (Date)</th> 
	</tr> 
	<tr> 
		<td rowspan=18>IoT-SocialTech/mobile-application-miam</td> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
	</tr> 
	<tr> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
	</tr> 
	<tr> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
	</tr> 
	<tr> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
	</tr> 
	<tr> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
	</tr> 
	<tr> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
	</tr> 
	<tr> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
	</tr> 
	<tr> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
	</tr> 
	<tr> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
	</tr> 
	<tr> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
	</tr> 
	<tr> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
	</tr> 
	<tr> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
	</tr> 
	<tr> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
	</tr> 
	<tr> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
	</tr> 
	<tr> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
		<td>-</td> 
	</tr> 
</table>
