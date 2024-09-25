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

- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1 Startup Profile](#11-startup-profile)
    - [1.1.1 Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2 Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2 Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1 Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2 Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3 Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4 Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3 Segmentos objetivo](#13-segmentos-objetivo)

- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1 Competidores](#21-competidores)
    - [2.1.1 Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2 Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2 Entrevistas](#22-entrevistas)
    - [2.2.1 Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2 Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3 Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3 Needfinding](#23-needfinding)
    - [2.3.1 User Personas](#231-user-personas)
    - [2.3.2 User Task Matrix](#232-user-task-matrix)
    - [2.3.3 User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4 Empathy Mapping](#234-empathy-mapping)
    - [2.3.5 As-is Scenario Mapping](#235-as-is-scenario-mapping)
  - [2.4 Ubiquitous Language](#24-ubiquitous-language)

- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1 To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2 User Stories](#32-user-stories)
  - [3.3 Impact Mapping](#33-impact-mapping)
  - [3.4 Product Backlog](#34-product-backlog)

- [Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
  - [4.1 Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
    - [4.1.1 EventStorming](#411-eventstorming)
      - [4.1.1.1 Candidate Context Discovery](#4111-candidate-context-discovery)
      - [4.1.1.2 Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
      - [4.1.1.3 Bounded Context Canvases](#4113-bounded-context-canvases)
    - [4.1.2 Context Mapping](#412-context-mapping)
    - [4.1.3 Software Architecture](#413-software-architecture)
      - [4.1.3.1 Software Architecture System Landscape Diagram](#4131-software-architecture-system-landscape-diagram)
      - [4.1.3.2 Software Architecture Context Level Diagrams](#4132-software-architecture-context-level-diagrams)
      - [4.1.3.3 Software Architecture Container Level Diagrams](#4133-software-architecture-container-level-diagrams)
      - [4.1.3.4 Software Architecture Deployment Diagrams](#4134-software-architecture-deployment-diagrams)
  - [4.2 Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
    - [4.2.1 Bounded Context: <Bounded Context Name>](#421-bounded-context-bounded-context-name)
      - [4.2.1.1 Domain Layer](#4211-domain-layer)
      - [4.2.1.2 Interface Layer](#4212-interface-layer)
      - [4.2.1.3 Application Layer](#4213-application-layer)
      - [4.2.1.4 Infrastructure Layer](#4214-infrastructure-layer)
      - [4.2.1.5 Bounded Context Software Architecture Component Level Diagrams](#4215-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.1.6 Bounded Context Software Architecture Code Level Diagrams](#4216-bounded-context-software-architecture-code-level-diagrams)
        - [4.2.1.6.1 Bounded Context Domain Layer Class Diagrams](#42161-bounded-context-domain-layer-class-diagrams)
        - [4.2.1.6.2 Bounded Context Database Design Diagram](#42162-bounded-context-database-design-diagram)
    - [4.2.2 Bounded Context: <Bounded Context Name>](#422-bounded-context-bounded-context-name)
      - [4.2.2.1 Domain Layer](#4221-domain-layer)
      - [4.2.2.2 Interface Layer](#4222-interface-layer)
      - [4.2.2.3 Application Layer](#4223-application-layer)
      - [4.2.2.4 Infrastructure Layer](#4224-infrastructure-layer)
      - [4.2.2.5 Bounded Context Software Architecture Component Level Diagrams](#4225-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.2.6 Bounded Context Software Architecture Code Level Diagrams](#4226-bounded-context-software-architecture-code-level-diagrams)
        - [4.2.2.6.1 Bounded Context Domain Layer Class Diagrams](#42261-bounded-context-domain-layer-class-diagrams)
        - [4.2.2.6.2 Bounded Context Database Design Diagram](#42262-bounded-context-database-design-diagram)
    - [4.2.3 Bounded Context: <Bounded Context Name>](#423-bounded-context-bounded-context-name)
      - [4.2.3.1 Domain Layer](#4231-domain-layer)
      - [4.2.3.2 Interface Layer](#4232-interface-layer)
      - [4.2.3.3 Application Layer](#4233-application-layer)
      - [4.2.3.4 Infrastructure Layer](#4234-infrastructure-layer)
      - [4.2.3.5 Bounded Context Software Architecture Component Level Diagrams](#4235-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.3.6 Bounded Context Software Architecture Code Level Diagrams](#4236-bounded-context-software-architecture-code-level-diagrams)
        - [4.2.3.6.1 Bounded Context Domain Layer Class Diagrams](#42361-bounded-context-domain-layer-class-diagrams)
        - [4.2.3.6.2 Bounded Context Database Design Diagram](#42362-bounded-context-database-design-diagram)
    - [4.2.4 Bounded Context: <Bounded Context Name>](#424-bounded-context-bounded-context-name)
      - [4.2.4.1 Domain Layer](#4241-domain-layer)
      - [4.2.4.2 Interface Layer](#4242-interface-layer)
      - [4.2.4.3 Application Layer](#4243-application-layer)
      - [4.2.4.4 Infrastructure Layer](#4244-infrastructure-layer)
      - [4.2.4.5 Bounded Context Software Architecture Component Level Diagrams](#4245-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.4.6 Bounded Context Software Architecture Code Level Diagrams](#4246-bounded-context-software-architecture-code-level-diagrams)
        - [4.2.4.6.1 Bounded Context Domain Layer Class Diagrams](#42461-bounded-context-domain-layer-class-diagrams)
        - [4.2.4.6.2 Bounded Context Database Design Diagram](#42462-bounded-context-database-design-diagram)

  
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
        <b>Descripcion:</b> Descripción 
        <td><img src="" alt="Luis Siancas" width="600"></td>
    </tr>
    <tr>
        <td><b>Nombre:</b> Trujillo Lopez, Luis Alberto<br>
            <b>Carrera:</b> Ingenieria de Software <br>
        <b>Descripcion:</b> Descripción 
        <td><img src="" alt="Luis Trujillo" width="600"></td>
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


#### 1.2.2.3. Lean UX Hypothesis Statements


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

**Segmento 2:** Dueños de casas de reposo (Nursing Home Owners)

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

#### 4.2.4. Bounded Context: <Bounded Context Name>

##### 4.2.4.1. Domain Layer

##### 4.2.4.2. Interface Layer

##### 4.2.4.3. Application Layer

##### 4.2.4.4. Infrastructure Layer

##### 4.2.4.6. Bounded Context Software Architecture Component Level Diagrams

##### 4.2.4.7. Bounded Context Software Architecture Code Level Diagrams

###### 4.2.4.7.1. Bounded Context Domain Layer Class Diagrams

###### 4.2.4.7.2. Bounded Context Database Design Diagram

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