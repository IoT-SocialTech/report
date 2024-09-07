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

URL del repositorio: https://github.com/IoT-SocialTech/iot-report

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
- [Product Backlog](#product-backlog)
  - [Tabla de Product Backlog](#tabla-de-product-backlog)
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
      - [4.2.1. Bounded Context: ](#421-bounded-context-)
        - [4.2.1.1. Domain Layer](#4211-domain-layer)
        - [4.2.1.2. Interface Layer](#4212-interface-layer)
        - [4.2.1.3. Application Layer](#4213-application-layer)
        - [4.2.1.4. Infrastructure Layer](#4214-infrastructure-layer)
        - [4.2.1.6. Bounded Context Software Architecture Component Level Diagrams](#4216-bounded-context-software-architecture-component-level-diagrams)
        - [4.2.1.7. Bounded Context Software Architecture Code Level Diagrams](#4217-bounded-context-software-architecture-code-level-diagrams)
          - [4.2.1.7.1. Bounded Context Domain Layer Class Diagrams](#42171-bounded-context-domain-layer-class-diagrams)
          - [4.2.1.7.2. Bounded Context Database Design Diagram](#42172-bounded-context-database-design-diagram)
      - [4.2.2. Bounded Context: ](#422-bounded-context-)
        - [4.2.2.1. Domain Layer](#4221-domain-layer)
        - [4.2.2.2. Interface Layer](#4222-interface-layer)
        - [4.2.2.3. Application Layer](#4223-application-layer)
        - [4.2.2.4. Infrastructure Layer](#4224-infrastructure-layer)
        - [4.2.2.6. Bounded Context Software Architecture Component Level Diagrams](#4226-bounded-context-software-architecture-component-level-diagrams)
        - [4.2.2.7. Bounded Context Software Architecture Code Level Diagrams](#4227-bounded-context-software-architecture-code-level-diagrams)
          - [4.2.2.7.1. Bounded Context Domain Layer Class Diagrams](#42271-bounded-context-domain-layer-class-diagrams)
          - [4.2.2.7.2. Bounded Context Database Design Diagram](#42272-bounded-context-database-design-diagram)
      - [4.2.3. Bounded Context: ](#423-bounded-context-)
        - [4.2.3.1. Domain Layer](#4231-domain-layer)
        - [4.2.3.2. Interface Layer](#4232-interface-layer)
        - [4.2.3.3. Application Layer](#4233-application-layer)
        - [4.2.3.4. Infrastructure Layer](#4234-infrastructure-layer)
        - [4.2.3.6. Bounded Context Software Architecture Component Level Diagrams](#4236-bounded-context-software-architecture-component-level-diagrams)
        - [4.2.3.7. Bounded Context Software Architecture Code Level Diagrams](#4237-bounded-context-software-architecture-code-level-diagrams)
          - [4.2.3.7.1. Bounded Context Domain Layer Class Diagrams](#42371-bounded-context-domain-layer-class-diagrams)
          - [4.2.3.7.2. Bounded Context Database Design Diagram](#42372-bounded-context-database-design-diagram)
      - [4.2.4. Bounded Context: ](#424-bounded-context-)
        - [4.2.4.1. Domain Layer](#4241-domain-layer)
        - [4.2.4.2. Interface Layer](#4242-interface-layer)
        - [4.2.4.3. Application Layer](#4243-application-layer)
        - [4.2.4.4. Infrastructure Layer](#4244-infrastructure-layer)
        - [4.2.4.6. Bounded Context Software Architecture Component Level Diagrams](#4246-bounded-context-software-architecture-component-level-diagrams)
        - [4.2.4.7. Bounded Context Software Architecture Code Level Diagrams](#4247-bounded-context-software-architecture-code-level-diagrams)
          - [4.2.4.7.1. Bounded Context Domain Layer Class Diagrams](#42471-bounded-context-domain-layer-class-diagrams)
          - [4.2.4.7.2. Bounded Context Database Design Diagram](#42472-bounded-context-database-design-diagram)
- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

  
---

# Student Outcome

| Criterio específico                                              | Acciones realizadas                                                                 | Conclusiones |
|------------------------------------------------------------------|-------------------------------------------------------------------------------------|--------------|
| Trabaja en equipo para proporcionar liderazgo en forma conjunta | *Achamizo Huamani Jean Carlos* <br> TB1: <br> Escribir outcome <br><br> *Aliaga Trevejo Lucía Guadalupe* <br> TB1: <br> Escribir outcome <br><br> *Raymundo Guevara Rodrigo Alejandro* <br> TB1: <br> Escribir outcome <br><br> *Siancas Reategui Luis Alberto* <br> TB1: <br> Escribir outcome <br><br> *Trujillo Lopez Luis Alberto* <br> TB1: <br> Escribir outcome <br><br>|  *TB1* <br>            |
| Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos | *Achamizo Huamani Jean Carlos* <br> TB1: <br> Escribir outcome <br><br> *Aliaga Trevejo Lucía Guadalupe* <br> TB1: <br> Escribir outcome <br><br> *Raymundo Guevara Rodrigo Alejandro* <br> TB1: <br> Escribir outcome <br><br> *Siancas Reategui Luis Alberto* <br> TB1: <br> Escribir outcome <br><br> *Trujillo Lopez Luis Alberto* <br> TB1: <br> Escribir outcome <br><br>|   *TB1* <br>               |


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


## 1.3. Segmentos objetivo

---

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

| Nombre del Competidor | Descripción |
| :-------------------: | :---------- |
| Competidor 1 | Descripcion |
| Competidor 2 | Descripcion |
| Competidor 3 | Descripcion |

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
        Nuestro producto
        <div style="text-align: center; margin-top: 10px;">
        </div>
    <td colspan="1" valign="top" style="font-weight: bold;text-align: center">
        Competidor1
        <div style="text-align: center; margin-top: 10px;">
        </div>
    </td>
    <td colspan="1" valign="top" style="font-weight: bold;text-align: center" >
        Competidor2
        <div style="text-align: center; margin-top: 10px;">
        </div>
      </td>
    <td colspan="1" valign="top" style="font-weight: bold;text-align: center" >
        Competidor3
        <div style="text-align: center; margin-top: 10px;">
        </div>
    </td>
  </tr>
  <tr>
    <td colspan="1" rowspan="2"><p>Perfil</p></td>
    <td colspan="2">Overview</td>
    <td colspan="1" valign="top"> Nuestro producto
    </td>
    <td colspan="1" valign="top">Competidor1
    </td>
    <td colspan="1" valign="top">Competidor2
    </td>
    <td colspan="1" valign="top">Competidor3
    </td>
  </tr>
  <tr>
    <td colspan="2">Ventaja competitiva</td>
    <td colspan="1" valign="top"> Nuestro producto
    </td>
    <td colspan="1" valign="top">Competidor1
    </td>
    <td colspan="1" valign="top">Competidor2
    </td>
    <td colspan="1" valign="top">Competidor3
    </td>
  </tr>
  <tr>
    <td colspan="1" rowspan="2"><p>Perfil de Marketing</p></td>
    <td colspan="2">Mercado objetivo</td>
    <td colspan="1" valign="top"> Nuestro producto
    </td>
    <td colspan="1" valign="top">Competidor1
    </td>
    <td colspan="1" valign="top">Competidor2
    </td>
    <td colspan="1" valign="top">Competidor3
    </td>
  </tr>
  <tr>
    <td colspan="2">Estrategias de marketing</td>
    <td colspan="1" valign="top"> Nuestro producto
    </td>
    <td colspan="1" valign="top">Competidor1
    </td>
    <td colspan="1" valign="top">Competidor2
    </td>
    <td colspan="1" valign="top">Competidor3
    </td>
  </tr>
  <tr>
    <td colspan="1" rowspan="3"><p>Perfil de Producto</p></td>
    <td colspan="2">Productos & Servicios</td>
    <td colspan="1" valign="top"> Nuestro producto
    </td>
    <td colspan="1" valign="top">Competidor1
    </td>
    <td colspan="1" valign="top">Competidor2
    </td>
    <td colspan="1" valign="top">Competidor3
    </td>
  </tr>
  <tr>
    <td colspan="2">Precios y Costos</td>
    <td colspan="1" valign="top"> Nuestro producto
    </td>
    <td colspan="1" valign="top">Competidor1
    </td>
    <td colspan="1" valign="top">Competidor2
    </td>
    <td colspan="1" valign="top">Competidor3
    </td>
  </tr>
  <tr>
    <td colspan="2">Canales de distribución</td>
    <td colspan="1" valign="top"> Nuestro producto
    </td>
    <td colspan="1" valign="top">Competidor1
    </td>
    <td colspan="1" valign="top">Competidor2
    </td>
    <td colspan="1" valign="top">Competidor3
    </td>
  </tr>
  <tr>
    <td colspan="1" rowspan="5"><p>Análisis SWOT</p></td>
    
  </tr>
  <tr>
    <td colspan="2">Fortalezas</td>
    <td colspan="1" valign="top"> Nuestro producto
    </td>
    <td colspan="1" valign="top">Competidor1
    </td>
    <td colspan="1" valign="top">Competidor2
    </td>
    <td colspan="1" valign="top">Competidor3
    </td>
  </tr>
  <tr>
    <td colspan="2">Debilidades</td>
    <td colspan="1" valign="top"> Nuestro producto
    </td>
    <td colspan="1" valign="top">Competidor1
    </td>
    <td colspan="1" valign="top">Competidor2
    </td>
    <td colspan="1" valign="top">Competidor3
    </td>
  </tr>
  <tr>
    <td colspan="2">Oportunidades</td>
    <td colspan="1" valign="top"> Nuestro producto
    </td>
    <td colspan="1" valign="top">Competidor1
    </td>
    <td colspan="1" valign="top">Competidor2
    </td>
    <td colspan="1" valign="top">Competidor3
    </td>
  </tr>
  <tr>
    <td colspan="2">Amenazas</td>
    <td colspan="1" valign="top"> Nuestro producto
    </td>
    <td colspan="1" valign="top">Competidor1
    </td>
    <td colspan="1" valign="top">Competidor2
    </td>
    <td colspan="1" valign="top">Competidor3
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
        Colocar oportunidades
        </td>
    <td colspan="4" valign="top">
        Colocar amenazas
    </td>
  </tr>

  <tr>
    <th colspan="3" valign="top"><b>FORTALEZAS</b></th>
    <th colspan="4" valign="top"><b>ESTRATEGIAS FO (Ofensivas)</b></th>
    <th colspan="4" valign="top"><b>ESTRATEGIAS FA (Defensiva)</b></th>
  </tr>
  <tr>
    <td colspan="3" valign="top">
    Colocar fortalezas
    </td>
    <td colspan="4" valign="top">
    Colocar estrategias FO
    </td>
    <td colspan="4" valign="top">
    Colocar estrategias FA
    </td>
  </tr>

  <tr>
    <th colspan="3" valign="top"><b>DEBILIDADES</b></th>
    <th colspan="4" valign="top"><b>ESTRATEGIAS DO (Reorientación)</b></th>
    <th colspan="4" valign="top"><b>ESTRATEGIAS DA (Supervivencia)</b></th>
  </tr>
  <tr>
    <td colspan="3" valign="top">
    Colocar debilidades
    </td>
    <td colspan="4" valign="top">
    Colocar estrategias DO
    </td>
    <td colspan="4" valign="top">
    Colocar estrategias DA
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
      <b>Nombres y <br>apellidos:</b> Katty Salgado <br>
      <b>Edad: </b> 29 años <br>
      <b>Distrito:</b> Los Olivos <br>
      <b>Timing:</b> 0:00 - 0:00 minutos
      <b>Duración:</b> 10:06 minutos
    </td>
    <td align=center>
      <img src="./assets/entrevista-katty.PNG" alt="img"  width="80%"/>
    </td>
  </tr>
  <tr>
    <td colspan=2>
      <b>Enlace:</b> <a></a>
      <br>
      <b>Resumen:</b> Katty es una enfermera que se dedica al cuidado de los adultos mayores. En la entrevista comenta que sus dispositivos más usados son su celular (Xiaomi), su tablet y laptop (Apple), los cuales utiliza para comunicarse y gestionar sus horarios de trabajo. No utiliza dispositivos tecnológicos para el cuidado de los adultos mayores, pero ha identificado que en algunos hogares las familias utilizan cámaras para monitorearlos. Las redes sociales que más usa son Whatsapp, Facebook e Instagram y considera que se adapta a las nuevas tecnologías fácilmente. Dentro de su rutina de trabajo realiza funciones como la toma de signos vitales, aseo del adulto mayor, tendido de cama y apoyo con la alimentación. Katty considera que uno de los desafíos en su trabajo es evitar las caídas de los adultos mayores, por lo cual tiene que ayudarlos constantemente a movilizarse. Por otra parte, lo que le causa más satisfacción es el agradecimiento del paciente y su familia. Considera que un sistema de monitoreo debería ayudarle a monitorear los signos vitales (pulso, temperatura, saturación de oxígeno, etc.) y prevenir las caídas. También considera útil el envío de notificaciones cuando alguno de los signos vitales esté alterado y recordatorios del tratamiento (medicación) del paciente.
    </td>
  </tr>
</table>

<table border=1>
  <tr>
    <td>
      <b>Nombres y <br>apellidos:</b> Sara Villanueva <br>
      <b>Edad: </b> 39 años <br>
      <b>Distrito:</b> Callao <br>
      <b>Timing:</b> 0:00 - 0:00 minutos
      <b>Duración:</b> 3:36 minutos
    </td>
    <td align=center>
      <img src="./assets/entrevista-sara.PNG" alt="img"  width="80%"/>
    </td>
  </tr>
  <tr>
    <td colspan=2>
      <b>Enlace:</b> <a></a>
      <br>
      <b>Resumen:</b> Sara es una enfermera que trabaja cuidando adultos mayores. El dispositivo que más utiliza en su día a día es su celular (Motorola), el cual utiliza para crear alarmas y así dar a tiempo el tratamiento a sus pacientes. Sara considera que se adapta a la tecnología y le gusta incorporar soluciones tecnológicas en su labor. Su medio de comunicación más frecuente es a través de Whatsapp y también utiliza Instagram y TikTok. Uno de los principales desafíos que enfrenta al cuidar a los adultos mayores son las caídas, en especial en aquellos que no son independientes, y algo que le causa satisfacción es el agradecimiento y cariño que le dan sus pacientes. Con el fin de evitar caídas realiza procedimientos como colocar almohadas y ubicarlos en una posición adecuada, además de estar siempre pendiente todo el tiempo de ellos. Ella considera que un sistema de monitoreo del adulto mayor debe incluir cámaras para supervisarlos y el envío de alertas al cuidador.
    </td>
  </tr>
</table>

<table border=1>
  <tr>
    <td>
      <b>Nombres y <br>apellidos:</b> Miriam Guevara<br>
      <b>Edad: </b> 54 <br>
      <b>Distrito:</b> Trujillo <br>
      <b>Timing:</b> 0:00 - 0:00 minutos
      <b>Duración:</b>  minutos
    </td>
    <td align=center>
      <img src="./assets/entrevista-miriam.png" alt="img"  width="80%"/>
    </td>
  </tr>
  <tr>
    <td colspan=2>
      <b>Enlace:</b> <a></a>
      <br>
      <b>Resumen:</b> Miriam es una enfermera que ha puesto su casa de reposo para adultos mayores llamdo Divino Amor, utiliza celular y laptop. Considera que la tecnologia es importante pero siempre debe ser facil de usar en caso sea para el uso de los adultos mayores. Considera que lo mas dificil es tratar a todos los adultos mayores al mismo tiempo, sobre todo cuando despiertan. 
    </td>
  </tr>
</table>

**Segmento 2:** Dueños de casas de reposo (Nursing Home Owners)

<table border="1">
  <tr>
    <td>
      <b>Nombres y <br>apellidos:</b> Gabriel Hachamizo<br>
      <b>Edad:</b> 27 años <br>
      <b>Distrito:</b> Los Aquijes - Ica <br>
      <b>Timing:</b> 0:00 - 0:00 minutos<br>
      <b>Duración:</b> minutos
    </td>
    <td align="center">
      <img src="./assets/entrevista-gabriel.png" alt="img" width="80%"/>
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <b>Enlace:</b> <a href="#"></a>
      <br>
      <b>Resumen:</b> Gabriel es un licenciado en enfermería que trabaja en una casa de reposo para adultos mayores, desempeñando un rol administrativo. En la entrevista, comentó que los dispositivos más utilizados son celulares y laptops. Para el monitoreo de los pacientes, se utilizan cámaras de seguridad, mientras que la comunicación con los familiares se realiza principalmente a través de WhatsApp. Facebook se emplea para promocionar los servicios de la casa de reposo. Gabriel considera que la adopción de nuevas tecnologías es positiva y puede mejorar el cuidado de los pacientes. Sin embargo, enfrenta desafíos como el manejo de una gran cantidad de pacientes y la insuficiencia del protocolo de atención para garantizar una atención adecuada. También describe su rol en la empresa, incluyendo la priorización de actividades según su importancia. Además, Gabriel sugiere el desarrollo de un software para optimizar la administración y el registro de pacientes, así como para recopilar datos que contribuyan a una mejor atención.
    </td>
  </tr>
</table>

<table border=1>
  <tr>
    <td>
      <b>Nombres y <br>apellidos:</b> Nombre<br>
      <b>Edad: </b> años <br>
      <b>Distrito:</b> distrito <br>
      <b>Timing:</b> 0:00 - 0:00 minutos
      <b>Duración:</b>  minutos
    </td>
    <td align=center>
      <img src="./assets/Entrevista_PieroValverde.png" alt="img"  width="80%"/>
    </td>
  </tr>
  <tr>
    <td colspan=2>
      <b>Enlace:</b> <a></a>
      <br>
      <b>Resumen:</b> resumen
    </td>
  </tr>
</table>

<table border=1>
  <tr>
    <td>
      <b>Nombres y <br>apellidos:</b> Nombre<br>
      <b>Edad: </b> años <br>
      <b>Distrito:</b> distrito <br>
      <b>Timing:</b> 0:00 - 0:00 minutos
      <b>Duración:</b>  minutos
    </td>
    <td align=center>
      <img src="./assets/Entrevista_PieroValverde.png" alt="img"  width="80%"/>
    </td>
  </tr>
  <tr>
    <td colspan=2>
      <b>Enlace:</b> <a></a>
      <br>
      <b>Resumen:</b> resumen
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

![User Persona](./assets/user-persona-ana-martinez.png)

**Segmento 2:** Dueños de casas de reposo (Nursing Home Owners)

![User Persona](./assets/user-persona-gabriel-lopez.png)


### 2.3.2. User Task Matrix

**Segmento 1:** Cuidadores de adultos mayores (Caregivers)

<table>
  <tr>
    <th>User Task</th>
    <th>Frequency</th>
    <th>Importance</th>
  </tr>
  <tr>
    <td>Monitoreo de signos vitales</td>
    <td>SIEMPRE</td>
    <td>ALTA</td>
  </tr>
  <tr>
    <td>Prevención de caídas</td>
    <td>SIEMPRE</td>
    <td>ALTA</td>
  </tr>
  <tr>
    <td>Comunicación con familias</td>
    <td>USUALMENTE</td>
    <td>MEDIA</td>
  </tr>
  <tr>
    <td>Gestión de medicación del paciente</td>
    <td>USUALMENTE</td>
    <td>ALTA</td>
  </tr>
  <tr>
    <td>Aseo y cuidado del paciente</td>
    <td>SIEMPRE</td>
    <td>ALTA</td>
  </tr>
</table>


**Segmento 2:** Dueños de casas de reposo (Nursing Home Owners)

<table>
  <tr>
    <th>User Task</th>
    <th colspan="2">Gabriel Lopez</th>
  </tr>
  <tr>
    <th></th>
    <th>Frequency</th>
    <th>Importance</th>
  </tr>
  <tr>
    <td>Administrar y coordinar al personal de la casa de reposo</td>
    <td>SIEMPRE</td>
    <td>ALTA</td>
  </tr>
  <tr>
    <td>Revisar y priorizar actividades diarias según su importancia</td>
    <td>SIEMPRE</td>
    <td>ALTA</td>
  </tr>
  <tr>
    <td>Implementar y evaluar protocolos de atención</td>
    <td>A VECES</td>
    <td>MEDIA</td>
  </tr>
  <tr>
    <td>Comunicar información a los familiares</td>
    <td>SIEMPRE</td>
    <td>ALTA</td>
  </tr>
  <tr>
    <td>Monitorear el estado de los pacientes mediante cámaras de seguridad</td>
    <td>SIEMPRE</td>
    <td>ALTA</td>
  </tr>
</table>

### 2.3.3. User Journey Mapping

**Segmento 1:** Cuidadores de adultos mayores (Caregivers)

![User Journey Mapping](./assets/user-journey-mapping-caregiver.png)

**Segmento 2:** Dueños de casas de reposo (Nursing Home Owners)

![User Journey Mapping](./assets/user-journey-mapping-owner.png)

### 2.3.4. Empathy Mapping

**Segmento 1:** Cuidadores de adultos mayores (Caregivers)

![Empathy Mapping](./assets/empathy-mapping-ana-martinez.png)

**Segmento 2:** Dueños de casas de reposo (Nursing Home Owners)

![Empathy Mapping](./assets/empathy-mapping-gabriel-lopez.png)

### 2.3.5. As-is Scenario Mapping

**Segmento 1:** Cuidadores de adultos mayores (Caregivers)

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

**Segmento 2:** Dueños de casas de reposo (Nursing Home Owners)

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


---

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

**Segmento 1:** Cuidadores de adultos mayores (Caregivers)

![To-Be Scenario Mapping](./assets/tobe-scenario-mapping-ana-martinez.jpg)

**Segmento 2:** Dueños de casas de reposo (Nursing Home Owners)

![To-Be Scenario Mapping](./assets/tobe-scenario-mapping.png)

## 3.2. User Stories

| **Epic / User Story ID** | **Título**                                    | **Descripción**                                                                                                                                                                                                                             | **Criterios de Aceptación**                                                                                                                                                                                                                                                                                                          | **Relacionado con (Epic ID)** |
|---------------------------|-----------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------|
| **EP01**                  | **Nombre Epic 01**          | Descripción epic 1                        |                                                                                                                                                                                                                                                                                                                |                               |
| **US01**                  | **Nombre de US01**            | Descripción de US01                                                                                              | - **Scenario 1:** US scenario 1 <br> - **Scenario 2:** US scenario 2             | EP01 |



## 3.3. Impact Mapping

![Impact Mapping](./assets/impactmapping.svg)

## 3.4. Product Backlog

# Product Backlog

## Tabla de Product Backlog

| **Orden** | **User Story Id** | **Título**                                    | **Descripción**                                                                                                                                                                                                                             | **Story Points** |
|-----------|----------------|-----------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------|
| 1         | US01| Nombre US01   | Descripción US01                                                                          | Story points              |


# Capítulo IV: Strategic-Level Software Design

## 4.1. Strategic-Level Attribute-Driven Design

### 4.1.1. Event Storming

#### 4.1.1.1. Candidate Context Discovery

#### 4.1.1.2 Domain Message Flows Modeling

#### 4.1.1.3 Bounded Context Canvases

### 4.1.2. Context Mapping

### 4.1.3. Software Architecture

#### 4.1.3.1. Software Architecture System Landscape Diagram

#### 4.1.3.2. Software Architecture Context Level Diagrams

#### 4.1.3.3. Software Architecture Container Level Diagrams

#### 4.1.3..4. Software Architecture Deployment Diagrams

## 4.2. Tactical-Level Domain-Driven Design

#### 4.2.1. Bounded Context: <Bounded Context Name>

##### 4.2.1.1. Domain Layer

##### 4.2.1.2. Interface Layer

##### 4.2.1.3. Application Layer

##### 4.2.1.4. Infrastructure Layer

##### 4.2.1.6. Bounded Context Software Architecture Component Level Diagrams

##### 4.2.1.7. Bounded Context Software Architecture Code Level Diagrams

###### 4.2.1.7.1. Bounded Context Domain Layer Class Diagrams

###### 4.2.1.7.2. Bounded Context Database Design Diagram

#### 4.2.2. Bounded Context: <Bounded Context Name>

##### 4.2.2.1. Domain Layer

##### 4.2.2.2. Interface Layer

##### 4.2.2.3. Application Layer

##### 4.2.2.4. Infrastructure Layer

##### 4.2.2.6. Bounded Context Software Architecture Component Level Diagrams

##### 4.2.2.7. Bounded Context Software Architecture Code Level Diagrams

###### 4.2.2.7.1. Bounded Context Domain Layer Class Diagrams

###### 4.2.2.7.2. Bounded Context Database Design Diagram

#### 4.2.3. Bounded Context: <Bounded Context Name>

##### 4.2.3.1. Domain Layer

##### 4.2.3.2. Interface Layer

##### 4.2.3.3. Application Layer

##### 4.2.3.4. Infrastructure Layer

##### 4.2.3.6. Bounded Context Software Architecture Component Level Diagrams

##### 4.2.3.7. Bounded Context Software Architecture Code Level Diagrams

###### 4.2.3.7.1. Bounded Context Domain Layer Class Diagrams

###### 4.2.3.7.2. Bounded Context Database Design Diagram

### 4.2.1. Bounded Context Account: 

El contexto Account se encarga de gestionar el acceso de los usuarios al sistema de monitoreo, incluyendo el registro, inicio de sesión, verificación de cuentas y la actualización de suscripciones. Además, permite la gestión de acceso para cuidadores y familiares con diferentes roles y permisos.

#### 4.2.1.1. Domain Layer. 

- **Entities:**
  - **User:** Representa a un usuario registrado en el sistema.
  - **Account:** Contiene la información de la cuenta, como el correo electrónico, nombre, y detalles de suscripción.
  - **Role:** Define los roles asociados a cada cuenta (cuidador, familiar, administrador).
- **Value Objects:**
  - **Email:** Dirección de correo del usuario.
  - **Password:** Contraseña cifrada del usuario.
  - **Subscription:** Detalles del plan de suscripción del usuario.
- **Aggregates:**
  - **AccountAggregate:** Encapsula las entidades User y Account, gestionando la lógica de acceso y actualización de cuentas.
- **Repositories:**
  - **UserRepository:** Almacena y recupera información de los usuarios.
  - **AccountRepository:** Almacena y recupera la información relacionada con las cuentas y sus suscripciones.
- **Domain Services:**
  - **AccountManagementService:** Gestiona la lógica de registro, autenticación y actualización de cuentas de usuario.
  - **RoleAssignmentService:** Gestiona la asignación de roles y permisos a los usuarios.

#### 4.2.1.2. Interface Layer. 

- **API Endpoints:**
  - **POST /accounts/register:** Registra un nuevo usuario.
  - **POST /accounts/login:** Autentica un usuario en el sistema.
  - **GET /accounts/{id}:** Obtiene la información de una cuenta específica.
- **DTOs:**
  - **UserDTO:** Contiene información del usuario (ID, nombre, correo electrónico).
  - **AccountDTO:** Incluye detalles sobre la cuenta, como suscripción y roles asignados.
- **Controllers:**
  - **AccountController:** Gestiona las solicitudes relacionadas con el acceso y actualización de cuentas.
  - **RoleController:** Gestiona las solicitudes relacionadas con la asignación de roles.

#### 4.2.1.3. Application Layer. 

- **Application Services:**
  - **AccountApplicationService:** Gestiona la lógica de negocio para el manejo de cuentas de usuario.
  - **RoleApplicationService:** Gestiona la lógica de roles y permisos.
- **Commands/Queries:**
  - **RegisterUserCommand:** Comando para registrar un nuevo usuario.
  - **LoginUserCommand:** Comando para autenticar un usuario.
  - **AssignRoleCommand:** Comando para asignar un rol a un usuario.
- **Command Handlers:**
  - **RegisterUserHandler:** Maneja el comando de registro de usuarios.
  - **LoginUserHandler:** Maneja el comando de autenticación.
  - **AssignRoleHandler:** Maneja el comando de asignación de roles.

#### 4.2.1.4. Infrastructure Layer. 

- **Repository Implementation:**
  - **UserSQLRepository:** Implementación de UserRepository usando SQL.
  - **AccountSQLRepository:** Implementación de AccountRepository en SQL.
- **External Services:**
  - Integración con servicios de autenticación y autorización externos.
- **Factories:**
  - **AccountFactory:** Crea instancias de la entidad Account y sus agregados.
- **ORM / Database Access:**
  - Utiliza un ORM como Hibernate para mapear las entidades a la base de datos.

#### 4.2.1.5. Bounded Context Software Architecture Component Level Diagrams. 

- **Componentes:**
  - User
  - Account
  - Role
  - Subscription

#### 4.2.1.6. Bounded Context Software Architecture Code Level Diagrams. 

#### 4.2.1.6.1. Bounded Context Domain Layer Class Diagrams. 

#### 4.2.1.6.2. Bounded Context Database Design Diagram

![](assets/Aspose.Words.0aa7c52a-00df-4dbb-9dff-cdeae2d27982.001.png)

### 4.2.2. Bounded Context Payment: 

Este bounded context gestiona las suscripciones y los pagos de los usuarios para el servicio de monitoreo.

#### 4.2.2.1. Domain Layer. 

- **Entities**:
  - **Subscription**: Representa un plan de suscripción que un usuario ha adquirido.
  - **Payment**: Contiene la información de los pagos realizados por los usuarios.
- **Value Objects**:
  - **PaymentDetails**: Contiene los detalles del pago, como el monto, la fecha y el método.
  - **SubscriptionPlan**: Describe las características del plan de suscripción, como la duración y el costo.
- **Aggregates**:
  - **SubscriptionAggregate**: Encapsula la lógica relacionada con la suscripción y su renovación.
  - **PaymentAggregate**: Maneja la lógica relacionada con los pagos.
- **Repositories**:
  - **SubscriptionRepository**: Gestiona el acceso y almacenamiento de las suscripciones.
  - **PaymentRepository**: Gestiona los pagos realizados por los usuarios.
- **Domain Services**:
  - **PaymentService**: Servicio que coordina los pagos y actualiza las suscripciones según el estado del pago.

#### 4.2.2.2. Interface Layer. 

- **API Endpoints**:
  - POST /payment/process: Procesa un nuevo pago.
  - GET /subscription/{userId}: Consulta el estado de la suscripción del usuario.
- **DTOs**:
  - **SubscriptionDTO**: Estructura que contiene los detalles de la suscripción.
  - **PaymentDTO**: Estructura que contiene los detalles del pago.
- **Controllers**:
  - **PaymentController**: Controlador para gestionar las solicitudes de pago.

**SubscriptionController**: Controlador para manejar la información de suscripción.

#### 4.2.2.3. Application Layer. 

- **Application Services**:
  - **PaymentApplicationService**: Gestiona la lógica de negocio relacionada con los pagos.
  - **SubscriptionApplicationService**: Gestiona las operaciones relacionadas con las suscripciones.
- **Commands/Queries**:
  - **ProcessPaymentCommand**: Comando que procesa un nuevo pago.
  - **QuerySubscriptionStatus**: Consulta el estado de una suscripción específica.
- **Command Handlers**:
  - **ProcessPaymentHandler**: Maneja el comando de procesamiento de pagos.
  - **QuerySubscriptionHandler**: Maneja la consulta sobre el estado de suscripción.

#### 4.2.2.4. Infrastructure Layer. 

- **Repository Implementation**:
  - **SubscriptionSQLRepository**: Implementación concreta de SubscriptionRepository utilizando SQL.
  - **PaymentSQLRepository**: Implementación concreta de PaymentRepository utilizando SQL.
- **External Services**:

Integración con servicios de pago como Stripe o PayPal.

#### 4.2.2.5. Bounded Context Software Architecture Component Level Diagrams. 

Componentes clave:

- **Subscription**: Representa la suscripción del usuario al servicio.
- **Payment**: Representa los pagos realizados por los usuarios.

#### 4.2.2.6. Bounded Context Software Architecture Code Level Diagrams. 

#### 4.2.2.6.1. Bounded Context Domain Layer Class Diagrams. 

#### 4.2.2.6.2. Bounded Context Database Design Diagram. 

![](assets/Aspose.Words.0aa7c52a-00df-4dbb-9dff-cdeae2d27982.002.png)

### 4.2.3. Bounded Context Device: 

Este bounded context es responsable de recopilar y procesar los datos obtenidos desde los sensores del dispositivo portátil que utiliza el adulto mayor. El dispositivo monitorea signos vitales (como frecuencia cardíaca y temperatura), movimiento, y también incluye un botón de pánico.

#### 4.2.3.1. Domain Layer. 

- **Entities**:
  - **Device**: Representa la pulsera inteligente que recopila los datos del adulto mayor.
  - **SensorData**: Almacena los datos de los diferentes sensores del dispositivo, como frecuencia cardíaca, temperatura, y movimiento.
  - **PanicAlert**: Representa la activación del botón de pánico en el dispositivo.
- **Value Objects**:
  - **HeartRate**: Valor que indica la frecuencia cardíaca medida por el dispositivo.
  - **Temperature**: Valor de la temperatura corporal medida.
  - **Movement**: Representa la cantidad o tipo de movimiento detectado.
- **Aggregates**:
  - **DeviceAggregate**: Encapsula las entidades Device y SensorData, y mantiene la lógica de negocio relacionada con el manejo de los datos del dispositivo.
- **Repositories**:
  - **DeviceRepository**: Acceso a los datos del dispositivo, incluido el estado de sus sensores.
  - **SensorDataRepository**: Almacena y accede a los datos de los sensores recopilados por el dispositivo.
  - **PanicAlertRepository**: Almacena las alertas generadas por la activación del botón de pánico.
- **Domain Services**:
  - **DeviceMonitoringService**: Gestiona la lógica de negocio relacionada con el monitoreo y la actualización de los datos del dispositivo.
  - **AlertService**: Gestiona la lógica para la creación de alertas cuando los valores del dispositivo están fuera de los rangos normales.

#### 4.2.3.2. Interface Layer. 

- **API Endpoints**:
  - POST /devices/{id}/sensor-data: Recibe los datos de los sensores y los almacena.
  - GET /devices/{id}/status: Obtiene el estado actual del dispositivo.
  - POST /devices/{id}/panic-alert: Activa una alerta de pánico en el sistema.
- **DTOs**:
  - **DeviceDTO**: Contiene información sobre el dispositivo (ID, tipo de dispositivo, usuario asignado, etc.).
  - **SensorDataDTO**: Contiene los datos de los sensores (frecuencia cardíaca, temperatura, movimiento, etc.).
  - **PanicAlertDTO**: Contiene los detalles de la alerta de pánico generada por el dispositivo.
- **Controllers**:
  - **DeviceController**: Controlador que gestiona las solicitudes relacionadas con el estado y los datos del dispositivo.
  - **SensorDataController**: Controlador que recibe y gestiona los datos de los sensores.
  - **PanicAlertController**: Controlador que gestiona las alertas de pánico generadas por el dispositivo.

#### 4.2.3.3. Application Layer. 

- **Application Services**:
  - **DeviceApplicationService**: Gestiona la lógica de negocio a nivel de aplicación para el manejo de dispositivos.
  - **SensorDataApplicationService**: Procesa los datos recibidos por los sensores y los pasa a la capa de dominio.
  - **PanicAlertApplicationService**: Gestiona la activación y el procesamiento de las alertas de pánico.
- **Commands/Queries**:
  - **RegisterSensorDataCommand**: Comando para registrar los datos de los sensores.
  - **TriggerPanicAlertCommand**: Comando para activar una alerta de pánico.
- **Command Handlers**:
  - **RegisterSensorDataHandler**: Maneja el comando para registrar los datos de los sensores.
  - **TriggerPanicAlertHandler**: Maneja el comando para activar una alerta de pánico.

#### 4.2.3.4. Infrastructure Layer. 

- **Repository Implementation**:
  - **DeviceSQLRepository**: Implementación concreta de la interfaz DeviceRepository usando SQL para almacenar y recuperar información sobre dispositivos.
  - **SensorDataSQLRepository**: Implementación de SensorDataRepository para manejar los datos de sensores en una base de datos SQL.
  - **PanicAlertSQLRepository**: Implementación de PanicAlertRepository que almacena las alertas en una base de datos relacional.
- **External Services**:
  - Integración con un servicio externo para almacenar los datos en la nube y analizar las alertas generadas por el dispositivo.
- **Factories**:
  - **DeviceFactory**: Crea instancias del agregado DeviceAggregate y las entidades relacionadas como SensorData.
- **ORM / Database Access**:
  - Utiliza un ORM como **Hibernate** o **JPA** para mapear las entidades a una base de datos SQL.

#### 4.2.3.5. Bounded Context Software Architecture Component Level Diagrams. 

El diagrama en el **Nivel de Componentes** de este bounded context incluiría los siguientes componentes:

- **Device**: Representando el dispositivo y sus atributos clave.
- **SensorData**: Representando los datos de los sensores (frecuencia cardíaca, temperatura, movimiento).
- **PanicAlert**: Representando las alertas de pánico.

(Usamos un enfoque C4 para modelar la relación entre estos componentes).

#### 4.2.3.6. Bounded Context Software Architecture Code Level Diagrams. 

#### 4.2.3.6.1. Bounded Context Domain Layer Class Diagrams. 

#### 4.2.3.6.2. Bounded Context Database Design Diagram

![](assets/Aspose.Words.0aa7c52a-00df-4dbb-9dff-cdeae2d27982.003.png)

### 4.2.4. Bounded Context Configuration: 

Este bounded context permite la configuración de las bandas que se utilizan para el monitoreo de salud, gestionando la vinculación de cuidadores y familiares, la actualización de firmware y la sincronización con el sistema.

#### 4.2.4.1. Domain Layer. 

- **Entities:**
  - **Band:** Representa la pulsera vinculada a un usuario para el monitoreo de salud.
  - **Firmware:** Información relacionada con la versión de firmware instalada en la pulsera.
  - **CaretakerAssignment:** Asocia cuidadores o familiares con la banda del usuario.
- **Value Objects:**
  - **FirmwareVersion:** Número de versión del firmware.
  - **ConfigurationSettings:** Configuración específica del usuario para la banda.
- **Aggregates:**
  - **BandAggregate:** Encapsula las entidades Band, Firmware y CaretakerAssignment, gestionando la lógica de configuración.
- **Repositories:**
  - **BandRepository:** Almacena y recupera información sobre las bandas y su configuración.
  - **FirmwareRepository:** Gestiona las actualizaciones y versiones del firmware.
- **Domain Services:**
  - **BandConfigurationService:** Gestiona la lógica de configuración de la banda, como la asignación de cuidadores o la actualización de firmware.

#### 4.2.4.2. Interface Layer. 

- **API Endpoints:**
  - **POST /bands/{id}/configuration:** Configura una banda específica.
  - **POST /bands/{id}/firmware:** Actualiza el firmware de una banda.
  - **GET /bands/{id}/status:** Obtiene el estado de configuración y firmware de una banda.
- **DTOs:**
  - **BandDTO:** Contiene la información de la banda (ID, usuario asignado, versión de firmware).
  - **FirmwareDTO:** Detalles sobre la versión y estado del firmware.
- **Controllers:**
  - **BandController:** Gestiona las solicitudes relacionadas con la configuración de las bandas.
  - **FirmwareController:** Gestiona las solicitudes de actualización de firmware.

#### 4.2.4.3. Application Layer. 

- **Application Services:**
  - **BandApplicationService:** Gestiona la lógica de configuración de las bandas.
  - **FirmwareApplicationService:** Gestiona la lógica de actualización del firmware.
- **Commands/Queries:**
  - **ConfigureBandCommand:** Comando para configurar una banda.
  - **UpdateFirmwareCommand:** Comando para actualizar el firmware.
- **Command Handlers:**
  - **ConfigureBandHandler:** Maneja el comando de configuración de la banda.
  - **UpdateFirmwareHandler:** Maneja el comando de actualización de firmware.

#### 4.2.4.4. Infrastructure Layer. 

- **Repository Implementation:**
  - **BandSQLRepository:** Implementación de BandRepository en SQL.
  - **FirmwareSQLRepository:** Implementación de FirmwareRepository en SQL.
- **External Services:**
  - Servicios externos para actualizaciones de firmware y configuración remota.
- **Factories:**
  - **BandFactory:** Crea instancias del agregado BandAggregate y las entidades asociadas.
- **ORM / Database Access:**
  - Utiliza un ORM para mapear las entidades Band y Firmware a una base de datos SQL.

#### 4.2.4.5. Bounded Context Software Architecture Component Level Diagrams.

- **Componentes:**
  - Band
  - Firmware
  - CaretakerAssignment



#### 4.2.4.6. Bounded Context Software Architecture Code Level Diagrams. 

#### 4.2.4.6.1. Bounded Context Domain Layer Class Diagrams. 

#### 4.2.4.6.2. Bounded Context Database Design Diagram. 

![](assets/Aspose.Words.0aa7c52a-00df-4dbb-9dff-cdeae2d27982.004.png)

### 4.2.5. Bounded Context Edge: 

Este bounded context gestiona el procesamiento de datos en tiempo real recibidos desde el dispositivo, permitiendo un análisis inicial a nivel local.

#### 4.2.5.1. Domain Layer. 

- **Entities**:
  - **EdgeProcessor**: Representa el nodo de procesamiento local que recibe los datos del dispositivo.
  - **ProcessedData**: Datos ya analizados por el nodo Edge, como patrones de movimiento y análisis de frecuencia cardíaca.
- **Value Objects**:
  - **RealTimeData**: Valor que encapsula los datos procesados en tiempo real.
  - **AlertThresholds**: Define los límites que, al ser superados, generan alertas.
- **Aggregates**:
  - **EdgeProcessingAggregate**: Agregado que gestiona el procesamiento y análisis de los datos recibidos del dispositivo.
- **Repositories**:
  - **EdgeProcessorRepository**: Accede y almacena el estado de los procesadores Edge.
  - **ProcessedDataRepository**: Gestiona el almacenamiento de los datos procesados localmente.
- **Domain Services**:
  - **EdgeProcessingService**: Gestiona la lógica de procesamiento local de los datos, generando alertas cuando se exceden ciertos umbrales.

#### 4.2.5.2. Interface Layer. 

- **API Endpoints**:
  - POST /edge/{id}/process: Recibe los datos del dispositivo y los procesa.
  - GET /edge/{id}/processed-data: Obtiene los datos procesados por el nodo Edge.
- **DTOs**:
  - **EdgeProcessorDTO**: Contiene información del nodo Edge.
  - **ProcessedDataDTO**: Contiene los datos procesados.
- **Controllers**:
  - **EdgeProcessorController**: Controlador que gestiona la interacción con el nodo Edge.
  - **ProcessedDataController**: Controlador que expone los datos ya procesados.

#### 4.2.5.3. Application Layer. 

- **Application Services**:
  - **EdgeProcessingApplicationService**: Gestiona la lógica de negocio relacionada con el procesamiento local de los datos.
- **Commands/Queries**:
  - **ProcessDataCommand**: Comando para procesar los datos en tiempo real.
  - **QueryProcessedData**: Consulta los datos ya procesados.
- **Command Handlers**:
  - **ProcessDataHandler**: Maneja el comando de procesamiento de datos.
  - **QueryProcessedDataHandler**: Maneja la consulta de datos procesados.

#### 4.2.5.4. Infrastructure Layer. 

- **Repository Implementation**:
  - **EdgeProcessorSQLRepository**: Implementación de EdgeProcessorRepository usando SQL.
  - **ProcessedDataSQLRepository**: Implementación de ProcessedDataRepository en SQL.
- **External Services**:
  - Integración con servicios en la nube para sincronizar los datos procesados.
- **Factories**:
  - **EdgeProcessorFactory**: Crea instancias de EdgeProcessingAggregate.

### 4.2.5.5. Bounded Context Software Architecture Component Level Diagrams. 

Este diagrama incluiría componentes como:

•	**EdgeProcessor**: Nodo de procesamiento de datos.

•	**ProcessedData**: Representando los datos procesados localmente.

#### 4.2.5.6. Bounded Context Software Architecture Code Level Diagrams. 

#### 4.2.5.6.1. Bounded Context Domain Layer Class Diagrams. 

#### 4.2.5.6.2. Bounded Context Database Design Diagram

![](assets/Aspose.Words.0aa7c52a-00df-4dbb-9dff-cdeae2d27982.005.png)

#### 4.2.6. Bounded Context Metrics: 

Este contexto gestiona la generación de informes de datos de salud del usuario.

#### 4.2.6.1. Domain Layer. 

- **Entities**:
  - **HealthReport**: Representa un informe de los datos de salud del usuario.
- **Value Objects**:
  - **ReportPeriod**: Define el periodo del informe (diario, semanal, mensual).
  - **HealthMetrics**: Datos de salud como frecuencia cardíaca y temperatura.
- **Aggregates**:
  - **HealthReportAggregate**: Encapsula la lógica relacionada con la generación de informes.
- **Repositories**:
  - **HealthReportRepository**: Gestiona el acceso y almacenamiento de los informes generados.

#### 4.2.6.2. Interface Layer. 

- **API Endpoints**:
  - GET /metrics/{id}/report: Obtiene un informe de salud específico.
  - POST /metrics/generate: Genera un nuevo informe de salud.
- **DTOs**:
  - **HealthReportDTO**: Estructura del informe de salud.
- **Controllers**:
  - **MetricsController**: Controlador que maneja las solicitudes de generación de informes.

#### 4.2.6.3. Application Layer. 

- **Application Services**:
  - **MetricsApplicationService**: Gestiona la lógica para la generación de informes de salud.
- **Commands/Queries**:
  - **GenerateReportCommand**: Comando para generar un informe de salud.

#### 4.2.6.4. Infrastructure Layer. 

- **Repository Implementation**:
  - **HealthReportSQLRepository**: Implementación de HealthReportRepository en SQL.

### 4.2.6.5. Bounded Context Software Architecture Component Level Diagrams.

Componentes clave:

- **HealthReport**: Representando los informes de salud.

#### 4.2.6.6. Bounded Context Software Architecture Code Level Diagrams. 

#### 4.2.6.6.1. Bounded Context Domain Layer Class Diagrams. 

#### 4.2.6.6.2. Bounded Context Database Design Diagram. 

![](assets/Aspose.Words.0aa7c52a-00df-4dbb-9dff-cdeae2d27982.006.png)

### 4.2.7. Bounded Context Notification: 

Este bounded context gestiona el envío de alertas y notificaciones a los cuidadores o familiares.

#### 4.2.7.1. Domain Layer. 

- **Entities**:
  - **Notification**: Representa una notificación o alerta enviada a los cuidadores o familiares.
- **Value Objects**:
  - **Recipient**: Define a quién va dirigida la notificación.
  - **NotificationType**: Tipo de notificación (por ejemplo, alerta crítica o actualización).
- **Aggregates**:
  - **NotificationAggregate**: Encapsula las entidades relacionadas con las notificaciones y la lógica de negocio asociada.
- **Repositories**:
  - **NotificationRepository**: Gestiona el almacenamiento y acceso a las notificaciones.
- **Domain Services**:
  - **NotificationService**: Gestiona la lógica de negocio para el envío y manejo de notificaciones.

#### 4.2.7.2. Interface Layer. 

- **API Endpoints**:
  - POST /notifications/send: Envía una notificación a los destinatarios.
  - GET /notifications/{id}: Obtiene el estado de una notificación específica.
- **DTOs**:
  - **NotificationDTO**: Estructura de la notificación a ser enviada.
- **Controllers**:
  - **NotificationController**: Controlador que maneja las solicitudes de notificación.

#### 4.2.7.3. Application Layer. 

- **Application Services**:
  - **NotificationApplicationService**: Gestiona la lógica de negocio para la gestión de notificaciones.
- **Commands/Queries**:
  - **SendNotificationCommand**: Comando para enviar una notificación.
- **Command Handlers**:
  - **SendNotificationHandler**: Maneja el comando de envío de notificaciones.

#### 4.2.7.4. Infrastructure Layer. 

- **Repository Implementation**:
  - **NotificationSQLRepository**: Implementación concreta de NotificationRepository usando SQL.
- **External Services**:
  - Integración con servicios externos como SMS o correo electrónico para el envío de notificaciones.

#### 4.2.7.5. Bounded Context Software Architecture Component Level Diagrams. 

Componentes clave:

- **Notification**: Representando las notificaciones y alertas.
- **Recipient**: Los destinatarios de las notificaciones.

#### 4.2.7.6. Bounded Context Software Architecture Code Level Diagrams. 

#### 4.2.7.6.1. Bounded Context Domain Layer Class Diagrams. 

#### 4.2.7.6.2. Bounded Context Database Design Diagram. 

![](assets/Aspose.Words.0aa7c52a-00df-4dbb-9dff-cdeae2d27982.007.png)
---

# Conclusiones

--- 

# Bibliografía
 
 Dorri, S., Zabolinezhad, H., & Sattari, M. (2023). *The application of Internet of Things for the elderly health safety: A systematic review*. Advances in Biomedical Research, 12, 109. https://doi.org/10.4103/abr.abr_197_22 

Giulianelli, D., De Luca, G., De Luca, S., García, G., Carnuccio, E., Valiente, W., & Volker, M. (2017). *Diseño de sistema IoT de monitoreo y alarma para personas mayores*. Repositorio institucional de la UNLP, Universidad Nacional de La Plata.  https://sedici.unlp.edu.ar/handle/10915/62406 

Ministerio de Salud. (2018, 13 de diciembre). *Uno de cada tres adultos mayores de 65 años sufre una caída*. https://www.gob.pe/institucion/minsa/noticias/23629-uno-de-cada-tres-adultos-mayores-de-65-anos-sufre-una-caida

Suárez, G., Velasco, V., Limones, M. , Reyes, H., & Delgado, V. (2020). *Caídas en el adulto mayor y factores de riesgo*. European Journal of Child Development, Education and Psychopathology, 8(1), 47–56. https://doi.org/10.30552/ejpad.v8i1.130 

--- 

# Anexos