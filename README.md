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
Siancas Reategui, Luis Alberto <br>
Trujillo Lopez, Luis Alberto <br>

**Setiembre, 2024**

</div>

---

# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de la modificación |
| ------- | ----- | ----- | ------------------------------ |
|   1.0     |   06/09/2024   |  Achamizo Huamani Jean Carlos,  Aliaga Trevejo Lucía Guadalupe, Raymundo Guevara Rodrigo Alejandro, Siancas Reategui Luis Alberto, Trujillo Lopez Luis Alberto  |   Se añadieron los elementos correspondientes al entregable de la TB1 (capítulos 1 al 4)|

---

# Project Report Collaboration Insights

URL del repositorio: 
<a href="https://github.com/IoT-SocialTech/iot-report"> https://github.com/IoT-SocialTech/iot-report </a>

**TB1**

El equipo colaboró activamente en el repositorio de GitHub para la elaboración del informe, realizando un total de 38 commits para el primer entregable.

![Insights TB1](./assets/insights-tb1.PNG)

El uso de ramas paralelas permitió a los miembros del equipo trabajar simultáneamente en diferentes secciones del informe, integrando cambios de manera eficiente y reduciendo conflictos. Este enfoque colaborativo garantizó que todos los miembros contribuyeran al desarrollo del informe de manera equilibrada.

![Network TB1](./assets/network-tb1.PNG)

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
      - [Assumptions worksheet](#assumptions-worksheet)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [Features Hypothesis](#features-hypothesis)
      - [Business Hypothesis](#business-hypothesis)
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
  - [](#-3)
- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)
  - [Videos de Exposición](#videos-de-exposición)
  - [Diagrama C4 MIAM](#diagrama-c4-miam)

  
---

# Student Outcome

| Criterio específico                                              | Acciones realizadas                                                                 | Conclusiones |
|------------------------------------------------------------------|-------------------------------------------------------------------------------------|--------------|
| Trabaja en equipo para proporcionar liderazgo en forma conjunta | *Achamizo Huamani Jean Carlos* <br> TB1: <br> Participó activamente en la planificación y ejecución de las actividades del equipo. Coordinó las reuniones para discutir el progreso del proyecto y tomó la iniciativa en la resolución de conflictos. <br><br> *Aliaga Trevejo Lucía Guadalupe* <br> TB1: <br> Facilitó las discusiones del equipo, asegurando que todos los miembros pudieran expresar sus opiniones. Tomó la responsabilidad de consolidar la información y presentar el avance del proyecto a los stakeholders. <br><br> *Raymundo Guevara Rodrigo Alejandro* <br> TB1: <br> Contribuyó al liderazgo del equipo al proporcionar soporte técnico y orientación durante la implementación de las tareas. Coordinó con otros miembros del equipo para asegurar la alineación de los objetivos del proyecto. <br><br> *Siancas Reategui Luis Alberto* <br> TB1: <br> Asumió un rol activo en la definición de metas y en la planificación de tareas, manteniendo a todos los miembros del equipo enfocados en los objetivos comunes. <br><br> *Trujillo Lopez Luis Alberto* <br> TB1: <br> Lideró la revisión de las tareas y ayudó a motivar al equipo a cumplir con los plazos establecidos. Estableció un entorno de trabajo colaborativo que facilitó la cooperación entre todos los miembros del equipo. <br><br>|  *TB1* <br> El trabajo en equipo fue efectivo en proporcionar un liderazgo colaborativo, facilitando una comunicación abierta y un enfoque compartido hacia la consecución de objetivos. Cada miembro del equipo contribuyó significativamente a la planificación y ejecución del proyecto, mejorando la dinámica y eficiencia del grupo. |
| Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos | *Achamizo Huamani Jean Carlos* <br> TB1: <br> Facilitó la creación de un entorno inclusivo al asegurar que todas las voces fueran escuchadas durante las discusiones del equipo. Colaboró en la definición de metas claras y en la planificación de tareas para alcanzar los objetivos del proyecto. <br><br> *Aliaga Trevejo Lucía Guadalupe* <br> TB1: <br> Promovió la inclusión en el equipo al garantizar que las tareas y objetivos fueran distribuidos equitativamente. Ayudó a planificar y asignar tareas de manera que se maximizara el potencial de cada miembro del equipo. <br><br> *Raymundo Guevara Rodrigo Alejandro* <br> TB1: <br> Colaboró en la creación de un ambiente de trabajo abierto y respetuoso, donde cada miembro del equipo pudo contribuir con sus ideas. Participó activamente en la planificación y en el establecimiento de objetivos alcanzables. <br><br> *Siancas Reategui Luis Alberto* <br> TB1: <br> Se encargó de supervisar el progreso del equipo en relación con las metas establecidas, asegurando que todos los miembros estuvieran alineados con los objetivos del proyecto. Facilitó la planificación de tareas y la resolución de problemas para mantener el proyecto en camino. <br><br> *Trujillo Lopez Luis Alberto* <br> TB1: <br> Implementó prácticas para fomentar un entorno colaborativo y inclusivo, realizando sesiones de planificación y seguimiento para asegurar el cumplimiento de los objetivos. Supervisó el progreso y la realización de tareas, ayudando al equipo a mantenerse enfocado. <br><br>|   *TB1* <br> Se logró establecer un entorno de trabajo colaborativo e inclusivo, con una planificación efectiva y cumplimiento de metas. La distribución equitativa de tareas y la supervisión continua ayudaron a mantener al equipo alineado y motivado para alcanzar los objetivos del proyecto. |


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
#### Assumptions worksheet

**¿Quién es el usuario?**
El usuario principal son los dueños de casas de reposo y cuidadores de adultos mayores que buscan mejorar la seguridad y bienestar de los residentes.

**¿Qué problemas tiene nuestro producto? ¿Resolver?**
MIAM resuelve la necesidad de un monitoreo constante y efectivo de los adultos mayores, ayudando a prevenir caídas, detectar cambios en signos vitales y garantizar que los residentes estén en áreas seguras y obtengan un mejor cuidado.

**¿Qué características son importantes?**
Monitoreo en tiempo real de movimientos y signos vitales.
Alertas instantáneas en caso de caídas o presencia en zonas riesgosas.
Interfaz fácil de usar en la plataforma web y aplicación móvil.
Botón de alerta para solicitar asistencia

**¿Dónde encaja nuestro producto en su trabajo o vida?**
MIAM se integra en el trabajo diario de los administradores y cuidadores como una herramienta de software esencial para supervisar la salud y en los adultos se presentarán pulseras para su monitoreo de estado, minimizando riesgos y mejorando la calidad del cuidado.
**¿Cuándo y cómo es nuestro producto? ¿Usado?**
El producto es utilizado como una pulsera continuamente a lo largo del día para monitorear en tiempo real la ubicación y salud de los residentes. Los cuidadores y administradores lo  administran tanto desde dispositivos móviles como desde la plataforma web.
**¿Cómo debe verse nuestro producto y cómo comportarse?**
El producto software debe tener una interfaz intuitiva y accesible, con gráficos claros que muestren el estado de los residentes y notificaciones visibles para alertas urgentes. Debe ser confiable, fácil de usar y responder rápidamente a cualquier evento crítico y en los residentes la pulsera debe ser ligera y de un diseño simple que no incomode a los residentes.

**Creo que mis clientes necesitan** un sistema fiable y fácil de usar para monitorear la seguridad y salud de los adultos mayores.
**Estas necesidades se pueden resolver con** una combinación de tecnología de sensores, monitoreo de signos vitales y una plataforma accesible para la gestión de datos y alertas.
**Mis clientes iniciales son (o serán)** dueños de casas de reposo y cuidadores de adultos mayores que valoran la seguridad y calidad de vida de sus residentes.
**El valor #1**que un cliente quiere de mi servicio es la capacidad de prevenir accidentes y responder rápidamente a emergencias, garantizando la seguridad de los residentes.
**El cliente también puede obtener estos beneficios adicionales** como la tranquilidad de los familiares, una mayor eficiencia en la gestión del cuidado y una reducción en los incidentes graves.
**Voy a adquirir la mayoría de mis clientes a través de** estrategias de marketing directo a casas de reposo y promociones en eventos de la industria geriátrica.
**Haré dinero a través de** la venta de los equipos  de pulsera y la suscripción al sistema de monitoreo.
**Mi competencia principal en el mercado serán** otros proveedores de sistemas de monitoreo para adultos mayores, así como dispositivos de salud y seguridad específicos.
Los venceremos debido a nuestra integración completa de sensores de movimiento, monitoreo de signos vitales y una plataforma fácil de usar que ofrece alertas en tiempo real.
**Mi mayor riesgo de producto es** la posibilidad de que los sensores o la plataforma no funcionen correctamente en situaciones críticas.
Resolveremos esto a través de pruebas exhaustivas, mantenimiento regular y la implementación de redundancias en el sistema para asegurar su fiabilidad.
**¿Qué otras suposiciones tenemos? ¿Eso, si se prueba que es falso, causará que nuestro negocio/proyecto no funcione?**
Asumimos que los clientes estarán dispuestos a pagar una suscripción mensual para mantener el servicio. Si no es así, podríamos enfrentar dificultades financieras.

#### 1.2.2.3. Lean UX Hypothesis Statements
#### Features Hypothesis

**Statement 1:**
Creemos que la incorporación de un botón de alerta en la banda de monitoreo que los residentes puedan activar manualmente reducirá el tiempo de reacción en situaciones de emergencia.
Sabremos que hemos tenido éxito cuando el 90% de las alertas manuales se respondan en menos de 2 minutos durante los primeros 6 meses de uso.
**Statement 2:** 											Creemos que el incluir alertas instantáneas en la aplicación móvil para notificar a los cuidadores sobre caídas o cambios anómalos en signos vitales mejorará la respuesta a emergencias.
Sabremos que hemos tenido éxito cuando veamos una reducción del 30% en el tiempo de respuesta ante emergencias registradas en los primeros 3 meses de uso.
**Statement 3:**
Creemos que la integración de un historial de salud y actividad en la plataforma web permitirá a los cuidadores tomar decisiones más informadas sobre el bienestar de los residentes.
Sabremos que hemos tenido éxito cuando el 80% de los usuarios informen que revisan el historial de salud al menos una vez por semana para ajustar el plan de cuidado.

#### Business Hypothesis

**Statement 1:**
Creemos que el alquiler de equipos junto con la suscripción al sistema de monitoreo MIAM será la mejor estrategia para obtener ingresos sostenibles.
Sabremos que esto es cierto cuando el 70% de las casas de reposo que prueben el sistema opten por continuar con la suscripción después del periodo de prueba inicial.
**Statement 2:**
Creemos que ofrecer un periodo de prueba gratuito de 30 días aumentará la tasa de adopción inicial de nuestro sistema entre nuevas casas de reposo.
Sabremos que esto es cierto cuando al menos el 60% de los usuarios que completen el periodo de prueba decidan suscribirse al servicio.
**Statement 3:**
Creemos que al asociarnos con organizaciones de cuidado geriátrico y hospitales locales podremos ampliar nuestro mercado objetivo y generar más leads calificados.
Sabremos que esto es cierto cuando el 50% de las nuevas suscripciones provengan de referencias o asociaciones con estas instituciones dentro de los primeros 6 meses

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

![Caracteristicas Objeticas2](./assets/S1_CO_02.png)

![Caracteristicas Objeticas3](./assets/S1_CO_03.png)

![Caracteristicas Objeticas4](./assets/S1_CO_04.png)

- Características Subjetivas: 

![Caracteristicas Subjetivas1](./assets/S1_CS_01.png)

![Caracteristicas Subjetivas2](./assets/S1_CS_02.png)

**Segmento Objetivo -> Dueños de casas de reposo:**

- Características Objetivas: 

![Caracteristicas Objeticas1](./assets/S2_CO_01.png)

![Caracteristicas Objeticas2](./assets/S2_CO_02.png)

![Caracteristicas Objeticas3](./assets/S2_CO_03.png)

- Características Subjetivas: 

![Caracteristicas Subjetivas1](./assets/S2_CS_01.png)

![Caracteristicas Subjetivas2](./assets/S2_CS_02.png)

![Caracteristicas Subjetivas2](./assets/S2_CS_03.png)

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

| Epic ID | Título                | Descripción                                                                                                                                                |
|---------|-----------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| EP001 | Health Monitoring| As an app user, I want the bracelet to monitor my temperature and heart rate in real time so that I can receive alerts if abnormal values ​​are detected and keep my health under control.|
| EP002 | Help Request | As a bracelet user, I want to have an emergency button that notifies caregivers so that I can quickly call for help if needed, and caregivers receive an immediate notification on their mobile devices. |
| EP003 | Bracelet Management | As a system administrator, I want to manage rented wristbands so that I can update rental information, track available wristbands, and generate usage reports for billing. |
| EP004 | User Interface | As a mobile or web app user, I want an easy-to-use interface so that I can easily view and understand bracelet data, access reports, and manage notifications intuitively. |
| EP005 | Report Generation | As a system administrator, I want to generate detailed reports with the bracelet data so that I can analyze the health of the users, generate usage reports and make recommendations based on the collected data. |
| EP006 | API Development | As an integrative developer, I want a well-documented API with key functionalities so that I can integrate the application with other systems, manage bracelet data, receive notifications and access reports efficiently. |

| Story ID | Título                                    | Descripción                                                                                                                                                            | Criterios de Aceptación                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | Relacionado con Epic ID |
|----------|-------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------|
| US001 | Real Time Temperature Monitoring | As for the bracelet<br>I want to monitor my user temperature in real time<br>To receive alerts if the temperature is outside the healthy range.                 | --- Scenario: Check Temperature<br>Since the user is wearing the bracelet,<br>When the temperature is measured,<br>Then the system should display the current temperature and send an alert if it is outside the predefined range. < br><br>--- Scenario: Setting the temperature range<br>Since the user is in the bracelet setting,<br>When the user sets the temperature range,<br>Then the system should save Range and usage for alerts.                                                                                                  | EP001 |
| US002 | Real-Time Heart Rate Monitoring | Like the bracelet<br>I want to monitor my user's heart rate in real time<br>To receive alerts if the heart rate is outside the healthy range.           | --- Scenario: Check heart rate<br>Since the user is wearing the bracelet,<br>When the heart rate is measured,<br>Then the system should display the current heart rate and send an alert if it is out of range preset range.<br><br>--- Scenario: Heart rate range setting<br>Since the user is in the bracelet setting,<br>When the user sets the heart rate range,<br >Then the system should save the range and use it for alerts.                                                                                                  | EP001                   |
| US003 | Health Alerts | As a user of the bracelet<br>I want to receive alerts in case of abnormal temperature or heart rate values<br>To take action quickly if a health problem is detected. | --- Scenario: Receive temperature alert<br>Given the system detects an abnormal temperature,<br>When the alert is activated,<br>Then the user receives a notification on his mobile device.<br><br>- -- Scenario: Receive heart rate alert<br>Given the system detects an abnormal heart rate,<br>When the alert is activated,<br>Then the user receives a notification on their mobile device.                                                                                                                  | EP001 |
| US004 | Health Data History | As a bracelet user<br>I want to see the history of my health data<br>To have a complete record of my temperature and heart rate over time. | --- Scenario: Display temperature history<br>Given the user is in the history section,<br>When he selects the temperature option,<br>Then the system displays a graph or table with the temperature history.<br> br><br>--- Scenario: Display heart rate history<br>Given the user is in the history section,<br>When he selects the heart rate option,<br>Then the system displays a graph or table with history of heart rhythms.                                                                                       | EP001                   |
| US005 | Custom Alert Settings | As a bracelet user<br>I want to set up custom alerts for temperature and heart rate<br>To tailor notifications to my specific needs. | --- Scenario: Configure Temperature Alerts<br>Given the user is in the alert configuration section,<br>When he sets the temperature thresholds,<br>Then the system should save these thresholds and use them for alerts. <br><br>--- Scenario: Configure heart rate alerts<br>Given the user is in the alert configuration section,<br>When you set the heart rate thresholds,<br>Then the system should save these thresholds and use them for alerts.                                                                          | EP001 |
| US006 | Send Emergency Notification | As a bracelet user<br>I want a notification to be sent to caregivers when pressing the emergency button<br>So that I can receive quick help if necessary. | --- Scenario: Press the emergency button<br>Given the user is wearing the bracelet,<br>When the user presses the emergency button,<br>Then the system sends a notification to the caregivers with the current location of the user and an emergency message.<br><br>--- Scenario: Confirm receipt of notification<br>Given the emergency notification has been sent,<br>When the caregiver receives the notification,<br>Then the caregiver you should see the user's emergency information and location.                               | EP002 |
| US007 | Help Notification | As a caregiver<br>I want to receive notifications on my mobile device when the user presses the emergency button<br>So I can act quickly and assist the user. | --- Scenario: Receive emergency notification<br>Given the caregiver is waiting for notifications,<br>When the user presses the emergency button,<br>Then the caregiver receives a notification on his mobile device with the location and emergency details.<br><br>--- Scenario: View emergency details<br>Given the caregiver receives the notification,<br>When you select the notification,<br>Then the caregiver should see the location and the details of the emergency message.                                         | EP002 |
| US008 | Notification Management | As a caregiver<br>I want to manage notifications received<br>To review and follow up on emergency alerts received.                             | --- Scenario: View notification history<br>Given the caregiver is in the notification section,<br>When you check the history,<br>Then you should see a list of all the emergency notifications received with their details.<br> br><br>--- Scenario: Filter notifications<br>Given the caregiver is in the notifications section,<br>When you filter the notifications by date or type,<br>Then the system displays the notifications that match the selected filters.                                                                                                     | EP002 |
| US009 | Emergency Setting Alerts | As a user of the bracelet<br>I want to configure emergency alerts<br>To adjust the parameters according to my needs and preferences.                          | --- Scenario: Set up emergency notifications<br>Given the user is in the emergency settings section,<br>When he sets his notification preferences,<br>Then the system saves these preferences and applies them to future emergencies. <br><br>--- Scenario: Adjust notification parameters<br>Given the user has configured the alerts,<br>When you want to modify the parameters,<br>Then the system allows you to adjust the parameters and save the changes.                                                                                           | EP002 |
| US010 | Access to User Data | As an administrator<br>I want to access user data<br>To generate reports and track bracelet usage.                       | --- Scenario: Access to temperature data<br>Given the administrator is in the user data section,<br>When he selects the temperature option,<br>Then he should see the user's historical temperature data.< br><br>--- Scenario: Access to heart rate data<br>Given the administrator is in the user data section,<br>When he selects the heart rate option,<br>Then he should see the data user's heart rate history.                                                                                      | EP003                   |
| US011 | Management of Rented Bracelets | As an administrator<br>I want to manage rented bracelets<br>To update information, track and issue invoices.                                | --- Scenario: Update rental status<br>Given the administrator is in the bracelet management section,<br>When he updates the status of a bracelet,<br>Then the system should reflect the change in inventory and in billing.<br><br>--- Scenario: Generate invoice<br>Given the manager has updated the rental status,<br>When you request an invoice,<br>Then the system should generate an invoice with the details of rent and cost.                                                                                                                                           | EP003 |
| US012 | Viewing Available Bracelets | As an administrator<br>I want to see a list of available bracelets<br>To know which ones are for rent and which ones are available for new users.             | --- Scenario: View Bracelet List<br>Given the administrator is in the bracelets section,<br>When he selects the available bracelets option,<br>Then the system displays a list of available bracelets with their current status. <br><br>--- Scenario: Update availability<br>Given the administrator is in the bracelets section,<br>When he updates the availability of a bracelet,<br>Then the system reflects the changes in the list of bracelets available.                                                                                              | EP003 |
| US013 | Generate Usage Reports | As an administrator<br>I want to generate reports on the use of the bracelets<br>To analyze their use and performance.                                              | --- Scenario: Generate usage report<br>Given the administrator is in the reports section,<br>When he selects to generate a usage report,<br>Then the system displays a detailed report with the usage information of the bracelets, including the time in use, the number of users and the status of the devices.<br><br>--- Scenario: Export report<br>Given the administrator has generated a usage report,<br>When you select export the report,<br>Then the system allows you to export the report in PDF or Excel format.                                           | EP003 |
| US014 | Bracelet Sensor Monitoring | As an administrator<br>I want to monitor the status of the bracelets' sensors<br>To make sure they are working correctly at all times.           | --- Scenario: Monitor sensors<br>Given the administrator is in the bracelet monitoring section,<br>When you select a bracelet,<br>Then the system shows the status of its sensors, including battery, connectivity and accuracy data.<br><br>--- Scenario: Receive sensor failure alerts<br>Given a bracelet sensor is failing,<br>When the system detects the failure,<br>Then the administrator receives a alert notifying the problem with the sensor.                                                                                               | EP003 |
| US015 | Assign Bracelet to a User | As an administrator<br>I want to assign a bracelet to a new user<br>So that they can start using the health monitoring system immediately.                 | --- Scenario: Assign bracelet to user<br>Given the administrator is in the bracelet assignment section,<br>When he selects a new user and an available bracelet,<br>Then the system assigns the bracelet to the user and updates the status of the device in the inventory.<br><br>--- Scenario: Verify assignment<br>Given the administrator has assigned a bracelet to a user,<br>When checking the status of the bracelets,<br>Then the system correctly reflects the new allocation in inventory and user data.                                      | EP003 |
| US016 | Generate Financial Reports | As an administrator<br>I want to generate financial reports<br>To analyze the income generated by the rental of bracelets.                   | --- Scenario: Generate financial report<br>Given the administrator is in the financial reports section,<br>When he requests a report,<br>Then the system generates a detailed report with rental income and payments received.<br <br>--- Scenario: Filter report by dates<br>Given the administrator is in the financial reports section,<br>When he applies date filters,<br>Then the system displays the financial data filtered by range of dates selected. | EP003 |
| US017 | Setting up Automated Payments | As an administrator<br>I want to set up automated payments<br>To facilitate the management of bracelet rental charges.          | --- Scenario: Set up automatic payments<br>Given the administrator is in the configuration section,<br>When you set up automatic payments,<br>Then the system should process the payments automatically according to the configured interval.<br><br >--- Scenario: Update automatic payments<br>Given the administrator has an automatic payment configured,<br>When you modify the settings,<br>Then the system should save the changes and adjust future payments. | EP003 |
| US018 | Cancel Bracelet Rental | As an administrator<br>I want to cancel the rental of a bracelet<br>To release the bracelet and update the status in the inventory.             | --- Scenario: Cancel rental<br>Given the manager is in the bracelet management section,<br>When you select cancel a rental,<br>Then the system should release the bracelet in the inventory and update the rental status .<br><br>--- Scenario: Generate Cancellation Report<br>Given the manager has canceled a rental,<br>When you request a cancellation report,<br>Then the system should generate a detailed report with the Canceled rental details. | EP003 |
| US019 | Update Rental Rates | As an administrator<br>I want to update the rental rates for wristbands<br>To reflect changes in current rental costs. | --- Scenario: Edit Rental Rates<br>Given the manager is in the rates section,<br>When he updates a rate,<br>Then the system should apply the new rate to future rentals.<br><br >--- Scenario: Apply rates retroactively<br>Given the administrator has updated a rate,<br>When you want to apply the rate retroactively,<br>Then the system should apply the new rate to ongoing contracts if allowed the configuration. | EP003               |
| US020 | Quick Access to Bracelet Data | As a user<br>I want to quickly access the current bracelet data from the main screen<br>To view health information without browsing multiple pages. | --- Scenario: Quick access from home screen<br>Given the user is in the app,<br>When they open the home screen,<br>Then they can see the current temperature and heart rate without searching between different menus .<br><br>--- Scenario: Updated information<br>Given the bracelet is connected,<br>When the health data is updated,<br>Then the main screen should reflect the changes in real time. | EP004 |
| US021 | Intuitive Navigation | As a user<br>I want intuitive navigation in the application<br>To easily access the different functionalities without confusion.                             | --- Scenario: Clear Navigation<br>Given the user is in the application,<br>When they want to switch from one section to another,<br>Then they should be able to do so without complications through a navigation bar or accessible buttons. <br><br>--- Scenario: Consistent navigation elements<br>Given the user is browsing,<br>When accessing different parts of the application,<br>Then the navigation elements should be consistent throughout the application application. | EP004 |
| US022 | Clear Alert Display | As a user<br>I want important alerts to stand out visually<br>So that I can quickly identify critical notifications.                      | --- Scenario: Featured Alerts<br>Given the user receives a critical alert,<br>When they are browsing the application,<br>Then the alert should be highlighted visually, using colors and text size that make it stand out. <br><br>--- Scenario: Differentiation of Alerts<br>Given there are different types of alerts,<br>When the system sends a critical alert,<br>Then this must be clearly differentiated from the less important alerts. | EP004 |
| US023 | Interface Customization | As a user<br>I want to be able to customize some aspects of the interface<br>To adapt it to my viewing preferences.                                        | --- Scenario: Basic Customization<br>Given the user is in the settings,<br>When he selects the customization options,<br>Then he can change the color scheme and text size according to his preferences.<br> <br>--- Scenario: Saving Preferences<br>Given the user has customized the interface,<br>When they return to the application in the future,<br>Then the application should remember the saved preferences. | EP004 |
| US024 | Real Time Notifications | As a user<br>I want to receive real-time notifications about changes in health<br>So I can react quickly in case of emergencies.                    | --- Scenario: Real-time notification<br>Given the user is monitoring the senior's health,<br>When there is a significant change,<br>Then they receive an instant notification on their mobile device or web application.<br <br>--- Scenario: Accurate information<br>Given the system has sent a notification,<br>When the user receives it,<br>Then the information must be accurate and clear for quick interpretation. | EP004 |
| US025 | Daily Health Summary | As a user<br>I want to receive a daily summary of the senior's health<br>To be informed about general well-being without constantly reviewing the data.  | --- Scenario: Automated Daily Summary<br>Given the system is recording health data,<br>When the day ends,<br>Then the system generates and sends a daily summary with key health data to the user. <br><br>--- Scenario: Clear and simple summary<br>Given the user receives the daily summary,<br>When they review it,<br>Then it should be structured in a clear and easy to understand way, highlighting any anomaly. | EP005 |
| US026 | Generation of Health Reports | As an administrator<br>I want to generate detailed reports on users' health<br>To analyze patterns and trends over time.                  | --- Scenario: Report Generation<br>Given the administrator needs a report,<br>When he selects a time period,<br>Then the system generates a report with graphs and analysis of the collected health data.<br ><br>--- Scenario: Exporting reports<br>Given the administrator reviews a report,<br>When he decides to share it,<br>Then he can export it in PDF or Excel formats. | EP005 |
| US027 | Advanced Filters in Reports | As an administrator<br>I want to be able to apply advanced filters when generating reports<br>To obtain the most relevant information quickly and effectively.            | --- Scenario: Apply filters<br>Given the administrator is generating a report,<br>When he selects the filters (date, alert type, etc.),<br>Then the system must adjust the report to show only the filtered relevant data.<br><br>--- Scenario: Combining filters<br>Given the administrator is applying multiple filters,<br>When you select the advanced options,<br>Then the system must correctly combine the selected filters to generate the appropriate report. | EP005 |
| US028 | Health Trend Analysis | As an administrator<br>I want to see a trend analysis based on the data collected<br>To identify possible long-term health problems.            | --- Scenario: Analyze trends<br>Given the administrator has access to the health reports,<br>When he requests a trend analysis,<br>Then the system generates graphs that show patterns and possible health risks.<br <br>--- Scenario: Automatic anomaly detection<br>Given the health data is consistent,<br>When the system detects a significant deviation,<br>Then the system alerts about possible future health problems. | EP005 |
| US029 | Comparison of Data between Users | As an administrator<br>I want to compare the health data of multiple users<br>To identify common patterns or important differences in their health conditions. | --- Scenario: Compare health data<br>Given the administrator has multiple users in the system,<br>When he selects the users,<br>Then he can generate a report that compares their health data in an easy-to-interpret format .<br><br>--- Scenario: Differentiation by user type<br>Given the users have different characteristics,<br>When the administrator compares them,<br>Then the system should highlight the most relevant differences based on the selected parameters. | EP005 |
| US030 | Data Export for External Analysis | As an administrator<br>I want to export all health data in raw format<br>For further analysis with external tools.                  | --- Scenario: Export data in raw format<br>Given the administrator needs to perform external analysis,<br>When you select the export option,<br>Then you can download all the health data in CSV or JSON formats.< br><br>--- Scenario: Export Confirmation<br>Given the data has been exported,<br>When the administrator reviews the files,<br>Then they should be able to confirm that all the data has been exported successfully. | EP005 |
| TS031 | API implementation for integration with external systems | As a developer<br>I want to implement an API to integrate the bracelet data with other monitoring systems<br>To ensure that the data is accessible from other platforms. | --- Scenario: Develop API<br>Given the developer is creating the API,<br>When other systems request data from the bracelet,<br>Then the API should return the temperature and heart rate data in real time.<br> br><br>--- Scenario: Document API<br>Given the API is implemented,<br>When the developer consults the documentation,<br>Then the documentation should be clear and show examples of use of the endpoints. | EP006 |
| TS032 | Creating notification endpoints | As a developer<br>I want to create endpoints to manage notifications in the API<br>So that health alerts are configured and sent correctly. | --- Scenario: Create notification endpoints<br>Given the developer is implementing the functionality,<br>When an alert is configured,<br>Then the endpoints must allow creating, editing and deleting notifications.<br><br> --- Scenario: Notification management<br>Given the notifications are active,<br>When the system detects an anomaly,<br>Then a notification should be sent to the caregiver application. | EP006 |
| TS033 | API Security | As a developer<br>I want to ensure that the API has proper authentication and authorization<br>To protect the sensitive data of the bracelet users. | --- Scenario: Implement OAuth authentication<br>Given the developer is integrating security into the API,<br>When a user tries to access the data,<br>Then the API should require a valid authentication token.<br> <br>--- Scenario: Data Protection<br>Given the API has sensitive data,<br>When an unauthorized user tries to access it,<br>Then the API must block the unauthorized access. | EP006 |
| TS034 | API Documentation | As a developer<br>I want the API to be documented clearly and completely<br>So that other developers can integrate easily. | --- Scenario: Document all endpoints<br>Given that the API is ready,<br>When a developer needs information,<br>Then the documentation should include examples of all the functionalities and parameters.<br><br> --- Scenario: Access to documentation<br>Given that other developers need to use the API,<br>When they consult the documentation,<br>Then they should find it accessible and well structured. | EP006 |
| TS035 | API performance optimization | As a developer<br>I want to optimize the API so that responses are fast and efficient<br>To improve the end-user experience. | --- Scenario: Measure response times<br>Given that the API is in production,<br>When queries are made,<br>Then response times should be less than 200ms.<br><br>-- - Scenario: Implement caching<br>Given that the data is queried frequently,<br>When the system receives the same request multiple times,<br>Then the API should use caching techniques to improve performance. | EP006 |
## 3.3. Impact Mapping

![Impact Mapping](./assets/impactmapping.jpg)

## 3.4. Product Backlog

| **Orden** | **User Story Id** | **Título**                                    | **Descripción**                                                                                                                                                                                                                             | **Story Points(1 / 2 / 3 / 5 / 8)** |
|-----------|-------------------|-----------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------|
| 1 | US020 | Quick Access to Bracelet Data | As a user, I want to quickly access the current bracelet data from the main screen, to view health information without browsing multiple pages.                                                                    | 3 |
| 2 | US021 | Intuitive Navigation | As a user, I want intuitive navigation in the app, to easily access the different functionalities without confusion.                                                                                                      | 3 |
| 3 | US022 | Clear Alert Display | As a user, I want important alerts to stand out visually, so I can quickly identify critical notifications.                                                                                              | 2                                  |
| 4 | US023 | Interface Customization | As a user, I want to be able to customize some aspects of the interface, to adapt it to my viewing preferences.                                                                                                                | 3 |
| 5 | US024 | Real Time Notifications | As a user, I want to receive real-time notifications about changes in health, so I can react quickly in case of emergencies.                                                                                              | 5 |
| 6 | US025 | Daily Health Summary | As a user, I want to receive a daily summary of the senior's health, to be informed about general well-being without constantly reviewing the data.                                                                           | 3                                  |
| 7 | US026 | Generation of Health Reports | As an administrator, I want to generate detailed reports on users' health, to analyze patterns and trends over time.                                                                                           | 5 |
| 8 | US027 | Advanced Filters in Reports | As an administrator, I want to be able to apply advanced filters when generating reports, to obtain the most relevant information quickly and effectively.                                                                                       | 5 |
| 9 | US028 | Health Trend Analysis | As an administrator, I want to see a trend analysis based on the data collected, to identify potential long-term health problems.                                                                                      | 5 |
| 10 | US029 | Comparison of Data between Users | As an administrator, I want to compare the health data of multiple users, to identify common patterns or important differences in their health conditions.                                                                          | 5 |
| 11 | US030 | Data Export for External Analysis | As an administrator, I want to export all health data in raw format, for further analysis with external tools.                                                                                           | 3 |
| 12 | US015 | Automatic Emergency Notifications | As a user, I want the system to send automatic emergency notifications to registered contacts when a fall or critical condition is detected, so they can act quickly.                                        | 5                                  |
| 13 | US016 | Personalized Emergency Alerts | As a user, I want to customize emergency alerts, so that push notifications reach the right people in case of critical situations.                                                                       | 3 |
| 14 | US017 | Schedule Medication Reminders | As a user, I want to schedule medication reminders in the app, to make sure the senior takes their medications on time.                                                                                            | 5 |
| 15 | US018 | Confirmation of Medication Taking | As a user, I want to receive confirmation when the older adult has taken their medication, so I can rest assured that they are continuing their treatment.                                                                                            | 3                                  |
| 16 | US019 | Send Automatic Reports to Family Members | As a user, I want to send automatic health reports to authorized family members, so that they are informed of the senior's status without having to constantly request it.                                                           | 3 |
| 17 | US006 | Critical Alert Notifications | As an administrator, I want to receive immediate notifications when anomalies are detected in the senior's health, so I can react quickly.                                                                                   | 5 |
| 18 | US004 | Login | As a user, I want to log in with my registered account, to access my data and personalized functionalities.                                                                                                                     | 3                                  |
| 19 | US003 | New User Registration | As a user, I want to register in the application with my personal data, to be able to use all the features.                                                                                                                      | 3 |
| 20 | US005 | Reset Password | As a user, I want to reset my password if I forget it, so I can regain access to my account.                                                                                                                            | 3 |
| 21 | US007 | Update Profile | As a user, I want to update my personal data in my profile, to keep my information up to date.                                                                                                                                    | 2                                  |
| 22 | US009 | Confirm Identity with SMS Code | As a user, I want to confirm my identity with a code sent by SMS when registering or changing important data, to protect my account.                                                                                            | 5 |
| 23        | US010 | Connect Bracelet with the Application | As a user, I want to connect the bracelet to the system through the mobile application, to start monitoring my health.                                                                                                                    | 5 |
| 24 | US011 | View Historical Data in Charts | As a user, I want to see historical health data presented in graphs, to analyze trends in my fitness over time.                                                                                      | 3                                  |
| 25 | US008 | Logout | As a user, I want to log out easily, to protect my account after using the app.                                                                                                                                       | 1 |
| 26 | US012 | Send Health Reports to the Doctor | As a user, I want to send the complete health report for a period of time to my doctor, to receive a professional opinion based on the data recorded by the bracelet.                                                           | 5 |
| 27 | US002 | See General Information Pages | As a user, I want to be able to access general information pages about the app and its benefits, to understand how to use it correctly.                                                                                           | 2                                  |
| 28 | US001 | See Home Page | As a visitor, I want to see a home page with relevant information about the service the application offers, to learn how it can help me.                                                                                      | 2 |
| 29 | US013 | Low Battery Notifications | As a user, I want to receive notifications when the bracelet's battery is low, to avoid interruptions in health monitoring.                                                                                              | 2 |
| 30 | US014 | Lost Connection Notifications | As a user, I want to receive notifications when the connection between the bracelet and the app is lost, to ensure that health data is always being monitored.                                                          | 3                                 |
| 31 | TS031 | API implementation for integration | Implementation of API for integration with external systems, allowing efficient communication between applications.                                                                                                                 | 5 |
| 32 | TS032 | Creation of Notification Endpoints | Creation of the necessary endpoints to handle notifications in the API, ensuring proper delivery of alerts and messages.                                                                                                 | 3 |
| 33 | TS033 | API Security | Implementation of security measures in the API, ensuring that only authorized users can access sensitive data.                                                                                                           | 8                                  |
| 34 | TS034 | API Documentation | Create API documentation, ensuring that developers can understand and use integration functionalities with ease.                                                                                            | 2 |
| 35 | TS035 | API Performance Optimization | Improve API performance to ensure a fast and efficient response, optimizing queries and resource usage.                                                                                                                   | 5                                  |

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

**Step 2: Timelines**

En este segundo paso, se revisan los eventos de dominio generados y se organizan en el orden en que ocurren dentro del dominio. Primero, se debe construir un happy path, es decir, un escenario en el que todo funciona correctamente y el proceso comercial es exitoso. Una vez que se ha completado este camino ideal, se pueden agregar escenarios alternativos que contemplen variaciones, fallos, o situaciones excepcionales.

![ES-Step2](./assets/EV-Step2.png)

**Step 3: Paint Points**

Después de organizar los eventos en una línea de tiempo, aprovechamos esta vista general para identificar puntos de interés a lo largo del proceso. Estos puntos de interés pueden incluir cuellos de botella, pasos manuales que podrían ser automatizados, falta de documentación o carencias de conocimiento del dominio.

![ES-Step3](./assets/EV-Step3.png)

**Step 4: Pivotal Points**

Una vez que tenemos nuestra línea de eventos completa, incluyendo los pain points, buscamos eventos comerciales clave que marquen un cambio en el contexto o en la fase del proceso. Estos se denominan eventos principales y los señalamos con una barra vertical que separa los eventos anteriores de los posteriores a dicho evento.

![ES-Step4](./assets/EV-Step4.png)

**Step 5: Commands**

En este paso también introducimos los comandos, los cuales describen la causa de un evento o el flujo de eventos. A diferencia de los eventos de dominio, los comandos son expresados en modo imperativo, describiendo las operaciones que deben ejecutarse en el sistema.

![ES-Step5](./assets/EV-Step5.png)

**Step 6: Policies**

En este punto, buscamos automation policies (políticas de automatización) que puedan ejecutar estos comandos. Esto significa que un evento específico del dominio desencadena automáticamente la ejecución de un comando. En otras palabras, cuando ocurre un evento determinado, el comando correspondiente se ejecuta de manera automática.

![ES-Step6](./assets/EV-Step6.png)

**Step 7: Read Models**

En este paso, introducimos el modelo de lectura, que es la representación de datos del dominio que un agente utiliza para decidir si debe ejecutar o no un comando. Por esta razón, definimos una vista de datos para cada comando, como monitores del sistema, informes, notificaciones, entre otros.

![ES-Step7](./assets/EV-Step7.png)

**Step 8: External Systems**

A continuación, completamos el modelo incluyendo los sistemas externos. Un sistema externo es cualquier sistema que no pertenece al dominio en el que estamos trabajando. Estos sistemas pueden ejecutar comandos (entrada) o recibir notificaciones sobre eventos (salida).

![ES-Step8](./assets/EV-Step8.png)

**Step 9: Aggregates**

Luego de presentar todos los eventos y comandos, comenzamos a agrupar los conceptos relacionados en agregados, que son las unidades que reciben comandos y generan eventos.

![ES-Step9](./assets/EV-Step9.png)

**Step 10: Bounded Contexts**

Finalmente, identificamos los agregados que están relacionados entre sí y que son relevantes por representar funciones estrechamente vinculadas o porque están conectados según ciertas políticas. Estos grupos de agregados sirven como candidatos naturales para definir los Bounded Contexts (contextos delimitados) dentro del sistema.

![ES-Step10](./assets/EV-Step10.png)

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

![ContextMapping](./assets/ContextMapping.jpg)

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

  ![alt text](assets/device-class.png)

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

![alt text](assets/diagram-db.png)

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

   ![alt text](assets/edge-class.png)

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

![alt text](assets/diagram-db.png)
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

   ![alt text](assets/notification-class.png)

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

![alt text](assets/diagram-db.png)
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

![alt text](assets/metric-class.png)

#### 4.2.4.7.2. Bounded Context Database Design Diagram
En esta sección se define el diseño de la base de datos para persistir las entidades de este contexto.

**Tablas:**

- **Metrics**:
`Columnas`: id, averageHeartRate, averageTemperature, alertsGenerated, Patient_id.
`Llave Foránea`: Patient_id.
- **Patient**:
`Columnas`: id, name, age, address, emergencyContact.
`Relaciones`: Metrics se relaciona con Patient a través de Patient_id.

![alt text](assets/diagram-db.png)

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

![alt text](assets/payment-class.png)

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

![alt text](assets/diagram-db.png)
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

![alt text](assets/configurations-class.png)

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

![alt text](assets/diagram-db.png)

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

![alt text](assets/account-class.png)

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

![alt text](assets/diagram-db.png)
---

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
| [TB1](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20211a452_upc_edu_pe/EXzPKFFOnR5Mq2strIjYv_ABHHmMLD8uwcRHKCLaIeRl8w?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=7VLfOg)       | 07/09/2024   | TB1         |

## Diagrama C4 MIAM
https://structurizr.com/share/95614/diagrams#SystemContext