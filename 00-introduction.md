# <center>Project Report</center>
<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Ingeniería de Software - 2025-20</strong><br>
    <strong>Aplicaciones para Dispositivos Móviles - 1798</strong><br>
    <strong>Profesor: Jorge Luis Mayta Guillermo</strong><br>
    <br><strong>Informe del Trabajo Final</strong>
</p>

<p align="center">
    <strong>Startup: ATG</strong><br>
    <strong>Producto: Autonexo</strong>
</p>

<div style="text-align:center;">
    <h3>Team Members:</h3>
    <table align="center">
        <tr>
            <th style="text-align:center;">Member</th>
            <th style="text-align:center;">Code</th>
        </tr>
       <tr>
    <td>Cruz Ibarra, Victor Andres</td>
    <td>u202311053</td>
</tr>
<tr>
    <td>Iglesias Pérez, Sergio Sebastián</td>
    <td>u202316118</td>
</tr>
<tr>
    <td>Roman Esteban, Henry Kalet</td>
    <td>u202310210</td>
</tr>
<tr>
    <td>Solano Armas, Angelo Hector</td>
    <td>u20231B775</td>
</tr>
<tr>
    <td>Vivanco Salazar, Rafael Andres</td>
    <td>u202311064</td>
</tr>
    </table>
</div>

<p align="center">
    <strong>Septiembre, 2025</strong>
</p>
<br>

# <font color="skyblue">**Registro de Versiones del Informe**</font>

<table border="1">
  <tr>
    <th>Versión</th>
    <th>Fecha</th>
    <th>Autor</th>
    <th>Descripción de modificación</th>
  </tr>
  <tr>
    <td>TB1</td>
    <td>07/09/2025</td>
    <td>Todos los integrantes del grupo aportaron</td>
    <td>Reporte, capítulos 1 y 2</td>
  </tr>
</table>


# <font color="skyblue">**Project Report Collaboration Insights**</font>

Enlace de la organización del proyecto: https://github.com/ATG-UPC

**TB1**

Para el desarrollo del informe correspondiente a la entrega TB1, se repartieron las tareas de la siguiente manera para cada integrante del equipo:

<table border="1">
  <tr>
    <th>Integrante</th>
    <th>Tareas Asignadas</th>
  </tr>
  <tr>
    <td>Victor Andres Cruz Ibarra</td>
    <td>Descripción de la Startup, Perfiles de integrantes del equipo, Lean UX Problem Statements, Lean UX Assumptions, User Stories, Impact Mapping, Product Backlog, Application Layer, Infrastructure Layer</td>
  </tr>
  <tr>
    <td>Rafael Andres Vivanco Salazar</td>
    <td>Antecedentes y problemática, Lean UX Hypothesis Statements, Lean UX Canvas, EventStorming, Candidate Context Discovery, Domain Message Flows Modeling, Bounded Context Software Architecture Component Level Diagrams, Software Architecture Code Level Diagrams</td>
  </tr>
  <tr>
    <td>Sergio Sebastián Iglesias Pérez</td>
    <td>Segmentos objetivo, Análisis competitivo, Estrategias frente a competidores, Bounded Context Canvases, Context Mapping, Software Architecture Context Level Diagrams, Software Architecture Container Level Diagrams</td>
  </tr>
  <tr>
    <td>Henry Kalet Esteban Roman</td>
    <td>Diseño de entrevistas, Registro de entrevistas, Análisis de entrevistas, Software Architecture Deployment Diagrams</td>
  </tr>
  <tr>
    <td>Angelo Hector Solano Armas</td>
    <td>Needfinding, User Personas, User Task Matrix, User Journey Mapping, Empathy Mapping, Ubiquitous Language, Bounded Context: <Bounded Context Name>, Domain Layer, Interface Layer</td>
  </tr>
</table>


# <font color="skyblue">**Contenido**</font>

### Tabla de contenidos

- [**Contenido**](#contenido)
    - [Tabla de contenidos](#tabla-de-contenidos)
- [**Student Outcome**](#student-outcome)
- [**Objetivos SMART**](#objetivos-smart)

- [ **Capítulo I: Presentación** ](#-capítulo-i-presentación)
  - [**1.1. Startup Profile**](#11-startup-profile)
    - [**1.1.1. Descripción de la Startup**](#111-descripción-de-la-startup)
    - [**1.1.2. Perfiles de integrantes del equipo**](#112-perfiles-de-integrantes-del-equipo)
  - [**1.2. Solution Profile**](#12-solution-profile)
    - [**1.2.1. Antecedentes y problemática**](#121-antecedentes-y-problemática)
    - [**1.2.2. Lean UX Process**](#122-lean-ux-process)
      - [**1.2.2.1. Lean UX Problem Statements**](#1221-lean-ux-problem-statements)
      - [**1.2.2.2. Lean UX Assumptions**](#1222-lean-ux-assumptions)
      - [**1.2.2.3. Lean UX Hypothesis Statements**](#1223-lean-ux-hypothesis-statements)
      - [**1.2.2.4. Lean UX Canvas**](#1224-lean-ux-canvas)
  - [**1.3. Segmentos objetivo**](#13-segmentos-objetivo)

- [ **Capítulo II: Requirements Development and Software Solution Design** ](#-capítulo-ii-requirements-development-and-software-solution-design)
  - [**2.1. Competidores**](#21-competidores)
    - [**2.1.1. Análisis competitivo**](#211-análisis-competitivo)
    - [**2.1.2. Estrategias y tácticas frente a competidores**](#212-estrategias-y-tácticas-frente-a-competidores)
  - [**2.2. Entrevistas**](#22-entrevistas)
    - [**2.2.1. Diseño de entrevistas**](#221-diseño-de-entrevistas)
    - [**2.2.2. Registro de entrevistas**](#222-registro-de-entrevistas)
    - [**2.2.3. Análisis de entrevistas**](#223-análisis-de-entrevistas)
  - [**2.3. Needfinding**](#23-needfinding)
    - [**2.3.1. User Personas**](#231-user-personas)
    - [**2.3.2. User Task Matrix**](#232-user-task-matrix)
    - [**2.3.3. User Journey Mapping**](#233-user-journey-mapping)
    - [**2.3.4. Empathy Mapping**](#234-empathy-mapping)
    - [**2.3.5. Ubiquitous Language**](#235-ubiquitous-language)
  - [**2.4. Requirements specification**](#24-Requirements-specification)
    - [**2.4.1 User Stories**](#241-user-stories)
    - [**2.4.2 Impact Mapping**](#242-impact-mapping)
    - [**2.4.3 Product Backlog**](#243-product-backlog)
  - [**2.5. Strategic-Level Domain-Driven Design**](#25-strategic-level-domain-driven-design)
    - [**2.5.1. EventStorming**](#251-eventstorming)
        - [**2.5.1.1 Candidate Context Discovery**](#2511-candidate-context-discovery)
        - [**2.5.1.2 Domain Message Flows Modeling**](#2512-domain-message-flows-modeling)
        - [**2.5.1.3 Bounded Context Canvases**](#2513-bounded-context-canvases)
    - [**2.5.2. Context Mapping**](#252-context-mapping)
    - [**2.5.3. Software Architecture**](#253-software-architecture)
        - [**2.5.3.1 Software Architecture Context Level Diagrams**](#2531-software-architecture-context-level-diagrams)
        - [**2.5.3.2 Software Architecture Container Level Diagrams**](#2532-software-architecture-container-level-diagrams)
        - [**2.5.3.3 Software Architecture Deployment Diagrams**](#2533-software-architecture-deployment-diagrams)
  - [**2.6 Tactical-Level Domain-Driven Design**](#26-tactical-level-domain-driven-design)
    - [**2.6.1 Bounded Context: Vehicle&Maintenance**](#261-bounded-context-bounded-context-vehicle-maintenance)
        - [**2.6.1.1 Domain Layer**](#2611-domain-laye>)
        - [**2.6.1.2 Interface Layer**](#2612-interface-layer)
        - [**2.6.1.3 Application Layer**](#2613-application-layer)
        - [**2.6.1.4 Infrastructure Layer**](#2614-infrastructure-layer)
        - [**2.6.1.5 Bounded Context Software Architecture Component Level Diagrams**](#2615-bounded-context-software-architecture-component-level-diagrams)
        - [**2.6.1.6 Bounded Context Software Architecture Code Level Diagrams**](#2616-bounded-context-software-architecture-code-level-diagrams)
             - [**2.6.1.6.1 Bounded Context Domain Layer Class Diagrams**](#26161-bounded-context-domain-layer-class-diagrams)
             - [**2.6.1.6.2 Bounded Context Database Design Diagram**](#26162-bounded-context-database-design-diagram)
    - [**2.6.2 Bounded Context: Trusting&Reputation**](#261-bounded-context-bounded-context-trusting-reputation)
        - [**2.6.2.1 Domain Layer**](#2611-domain-laye>)
        - [**2.6.2.2 Interface Layer**](#2612-interface-layer)
        - [**2.6.2.3 Application Layer**](#2613-application-layer)
        - [**2.6.2.4 Infrastructure Layer**](#2614-infrastructure-layer)
        - [**2.6.2.5 Bounded Context Software Architecture Component Level Diagrams**](#2615-bounded-context-software-architecture-component-level-diagrams)
        - [**2.6.2.6 Bounded Context Software Architecture Code Level Diagrams**](#2616-bounded-context-software-architecture-code-level-diagrams)
             - [**2.6.2.6.1 Bounded Context Domain Layer Class Diagrams**](#26161-bounded-context-domain-layer-class-diagrams)
             - [**2.6.2.6.2 Bounded Context Database Design Diagram**](#26162-bounded-context-database-design-diagram)
    - [**2.6.3 Bounded Context: Matching&Booking**](#261-bounded-context-bounded-context-matching-booking)
        - [**2.6.3.1 Domain Layer**](#2611-domain-laye>)
        - [**2.6.3.2 Interface Layer**](#2612-interface-layer)
        - [**2.6.3.3 Application Layer**](#2613-application-layer)
        - [**2.6.3.4 Infrastructure Layer**](#2614-infrastructure-layer)
        - [**2.6.3.5 Bounded Context Software Architecture Component Level Diagrams**](#2615-bounded-context-software-architecture-component-level-diagrams)
        - [**2.6.3.6 Bounded Context Software Architecture Code Level Diagrams**](#2616-bounded-context-software-architecture-code-level-diagrams)
             - [**2.6.3.6.1 Bounded Context Domain Layer Class Diagrams**](#26161-bounded-context-domain-layer-class-diagrams)
             - [**2.6.3.6.2 Bounded Context Database Design Diagram**](#26162-bounded-context-database-design-diagram)
    - [**2.6.4 Bounded Context: Workshop**](#261-bounded-context-bounded-context-workshop)
        - [**2.6.4.1 Domain Layer**](#2611-domain-laye>)
        - [**2.6.4.2 Interface Layer**](#2612-interface-layer)
        - [**2.6.4.3 Application Layer**](#2613-application-layer)
        - [**2.6.4.4 Infrastructure Layer**](#2614-infrastructure-layer)
        - [**2.6.4.5 Bounded Context Software Architecture Component Level Diagrams**](#2615-bounded-context-software-architecture-component-level-diagrams)
        - [**2.6.4.6 Bounded Context Software Architecture Code Level Diagrams**](#2616-bounded-context-software-architecture-code-level-diagrams)
             - [**2.6.4.6.1 Bounded Context Domain Layer Class Diagrams**](#26161-bounded-context-domain-layer-class-diagrams)
             - [**2.6.4.6.2 Bounded Context Database Design Diagram**](#26162-bounded-context-database-design-diagram)
    - [**2.6.5 Bounded Context: Payment**](#261-bounded-context-bounded-context-payment)
        - [**2.6.5.1 Domain Layer**](#2611-domain-laye>)
        - [**2.6.5.2 Interface Layer**](#2612-interface-layer)
        - [**2.6.5.3 Application Layer**](#2613-application-layer)
        - [**2.6.5.4 Infrastructure Layer**](#2614-infrastructure-layer)
        - [**2.6.5.5 Bounded Context Software Architecture Component Level Diagrams**](#2615-bounded-context-software-architecture-component-level-diagrams)
        - [**2.6.5.6 Bounded Context Software Architecture Code Level Diagrams**](#2616-bounded-context-software-architecture-code-level-diagrams)
             - [**2.6.5.6.1 Bounded Context Domain Layer Class Diagrams**](#26161-bounded-context-domain-layer-class-diagrams)
             - [**2.6.5.6.2 Bounded Context Database Design Diagram**](#26162-bounded-context-database-design-diagram)
    - [**2.6.6 Bounded Context: Identity & Access Management (IAM)**](#261-bounded-context-bounded-context-IAM)
        - [**2.6.6.1 Domain Layer**](#2611-domain-laye>)
        - [**2.6.6.2 Interface Layer**](#2612-interface-layer)
        - [**2.6.6.3 Application Layer**](#2613-application-layer)
        - [**2.6.6.4 Infrastructure Layer**](#2614-infrastructure-layer)
        - [**2.6.6.5 Bounded Context Software Architecture Component Level Diagrams**](#2615-bounded-context-software-architecture-component-level-diagrams)
        - [**2.6.6.6 Bounded Context Software Architecture Code Level Diagrams**](#2616-bounded-context-software-architecture-code-level-diagrams)
             - [**2.6.6.6.1 Bounded Context Domain Layer Class Diagrams**](#26161-bounded-context-domain-layer-class-diagrams)
             - [**2.6.6.6.2 Bounded Context Database Design Diagram**](#26162-bounded-context-database-design-diagram)

- [ **Capítulo III: Solution UI/UX Design** ](#-capítulo-iii-solution-ui/ux-design)
  - [**3.1. Product design**](#31-product-design)
    - [**3.1.1. Style Guidelines**](#311-style-guidelines)
      - [**3.1.1.1 General Style Guidelines**](#3111-general-style-guidelines)
    - [**3.1.2. Information Architecture**](#312-information-architecture)
      - [**3.1.2.1 Organization Systems**](#3121-organization-systems)
      - [**3.1.2.2 Labeling Systems**](#3122-labeling-systems)
      - [**3.1.2.3 SEO Tags and Meta Tags**](#3123-seo-tags-and-meta-tags)
      - [**3.1-2.4. Searching Systems**](#3124-searching-systems)
      - [**3.1.2.5. Navigation Systems**](#3125-navigation-systems)
    - [**3.1.3. Landing Page UI Design**](#313-landing-page-ui-design)
      - [**3.1.3.1. Landing Page Wireframe**](#3131-landing-page-wireframe)
      - [**3.1.3.2. Landing Page Mock-up**](#3132-landing-page-mock-up)
    - [**3.1.4. Mobile Applications UX/UI Design**](#314-mobile-application-ux/ui-design)
      - [**3.1.4.1. Mobile Applications Wireframes**](#3141-mobile-applications-wireframes)
      - [**3.1.4.2. Mobile Applications Wireflow Diagrams**](#3142-mobile-applications-wireflow-diagrams)
      - [**3.1.4.3. Mobile Applications Mock-ups**](#3143-mobile-applications-mock-ups)
      - [**3.1.4.4. Mobile Applications User Flow Diagram**](#3144-mobile-applications-user-flow-diagram)
      - [**3.1.4.5. Mobile Applications Prototyping**](#3145-mobile-applications-prototyping)
  
- [ **Capítulo IV: Product Implementation & Validation** ](#-capítulo-iv-product-implementation-&-validation )
  - [**4.1. Software Configuration Management**](#41-software-configuration-management)
    - [**4.1.1. Software Development Environment Configuration**](#411-software-development-environment-configuration)
    - [**4.1.2. Source Code Management**](#412-source-code-management)
    - [**4.1.3. Source Code Style Guide \& Conventions**](#413-source-code-style-guide--conventions)
    - [**4.1.4. Software Deployment Configuration**](#414-software-deployment-configuration)
  - [**4.2. Landing Page, Services & Mobile Implementation**](#42-landing-page-services-mobile-implementation)
    - [**4.2.1. Sprint 1**](#421-sprint-1)
      - [**4.2.1.1. Sprint Planning 1**](#4211-sprint-planning-1)
      - [**4.2.1.2. Sprint Backlog 1**](#4212-sprint-backlog)
      - [**4.2.1.3. Development Evidence for Sprint Review**](#4213-development-evidence-for-sprint-review)
      - [**4.2.1.4. Testing Suite Evidence for Sprint Review**](#4214-testing-suite-evidence-for-sprint-review)
      - [**4.2.1.5. Execution Evidence for Sprint Review**](#4215-execution-evidence-for-sprint-review)
      - [**4.2.1.6. Services Documentation Evidence for Sprint Review**](#4216-services-documentation-evidence-for-sprint-review)
      - [**4.2.1.7. Software Deployment Evidence for Sprint Review**](#4217-software-deployment-evidence-for-sprint-review)
      - [**4.2.1.8. Team Collaboration Insights during Sprint**](#4218-team-collaboration-insights-during-sprint)
  - [**4.3. Validation Interviews**](#43-validation-interviews)
    - [**4.3.1. Diseño de Entrevistas**](#431-diseño-de-entrevistas)
    - [**4.3.2. Registro de Entrevistas.**](#432-registro-de-entrevistas)
    - [**4.3.3. Evaluaciones según heurísticas**](#433-evaluaciones-según-heurísticas)
  
- [**Conclusiones**](#conclusiones)
  - [**Conclusiones y recomendaciones**](#conclusiones-y-recomendaciones)
  - [**Video App-Validation**](#video-app-validation)
  - [**Video About-the-Product**](#video-about-the-product)
  - [**Video About-the-Team**](#video-about-the-team)

- [**Glosario**](#glosario)
- [**Bibliografía**](#bibliografía)
- [**Anexos**](#anexos)

# <font color="skyblue">**Student Outcome**</font>

El curso contribuye al cumplimiento del Student Outcome ABET: </br> 
**ABET – EAC - Student Outcome 7** 
**Criterio:** La capacidad de adquirir y aplicar nuevos
conocimientos según sea necesario,
utilizando estrategias de aprendizaje
apropiadas.
</br>

<table style="border-collapse:collapse;border-spacing:0" class="tg"><thead><tr><th style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;font-weight:normal;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal"><span style="font-weight:normal">Criterio específico</span></th><th style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;font-weight:normal;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal"><span style="font-weight:normal">Acciones realizadas</span></th><th style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;font-weight:normal;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal"><span style="font-weight:normal">Conclusiones</span></th></tr></thead>
<tbody>
<tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal">Actualiza conceptos y
conocimientos necesarios para su
desarrollo profesional y en especial para
su proyecto en soluciones de ingeniería
de software </td>
<td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal"><b>Andres Cruz:</b> <br> TB1: <br> Al desarrollar la descripción de la startup y estructurar el Product Backlog con herramientas como Lean UX e Impact Mapping, actualicé mis conocimientos en metodologías ágiles y arquitectura de software, lo cual fortalece mis capacidades para aplicar soluciones en proyectos reales de ingeniería de software. <br> <b>Angelo Solano:</b> <br> TB1: <br> Al realizar Needfinding, User Personas, Journey Maps y modelar la capa de dominio, actualicé mis conocimientos sobre experiencia de usuario y diseño de software en capas, lo que me permitió integrar la visión del usuario con la solución técnica en el proyecto. <br><b>Henry Esteban: </b> <br> TB1: <br> Mediante el diseño, registro y análisis de entrevistas, y la construcción del Deployment Diagram, reforcé mis conocimientos sobre técnicas de recolección de requerimientos y despliegue de software, actualizando competencias claves para el desarrollo de proyectos de ingeniería. <br><b>Rafael Vivanco:</b><br> TB1: <br> Al analizar los segmentos objetivos, la competencia y mapear los contextos, actualicé mis conocimientos en análisis estratégico y en arquitectura de software a nivel de contenedores y contexto, lo que me permitió integrar tanto la visión de negocio como la técnica en el proyecto. <br><b>Sergio Iglesias </b><br> TB1: <br> Al analizar los segmentos objetivos, la competencia y mapear los contextos, actualicé mis conocimientos en análisis estratégico y en arquitectura de software a nivel de contenedores y contexto, lo que me permitió integrar tanto la visión de negocio como la técnica en el proyecto. <br><br><b>Víctor Andrés Cruz Ibarra:</b> <br> TP1: <br> Al desarrollar el Product Design, las Style Guidelines y la Information Architecture de AutoNexo, actualicé mis conocimientos en diseño de interfaces, jerarquización de información y aplicación de guías visuales modernas. Esto fortaleció mi comprensión sobre la relación entre estética y usabilidad en proyectos de ingeniería de software. <br><br><b>Ángelo Héctor Solano Armas:</b> <br> TP1: <br> Al diseñar la experiencia UX/UI móvil, crear wireframes, mock-ups y prototipos, actualicé mis conocimientos sobre herramientas de diseño interactivo y metodologías centradas en el usuario, fortaleciendo mi habilidad para transformar requerimientos funcionales en experiencias digitales efectivas. <br><br><b>Henry Kalet Esteban Román:</b> <br> TP1: <br> Mediante la configuración de software, la implementación de la landing page y la aplicación móvil, reforcé mis conocimientos sobre control de versiones, despliegue y gestión de entornos de desarrollo. La corrección de entregas previas me permitió actualizar conceptos sobre integración continua y metodologías ágiles aplicadas a proyectos reales. <br><br><b>Rafael Andrés Vivanco Salazar:</b> <br> TP1: <br> En la elaboración de sistemas de organización, etiquetado, SEO y Sprint Planning, actualicé mis conocimientos en arquitectura de información, optimización web y planificación ágil, consolidando mi capacidad para integrar la perspectiva técnica con la estrategia de desarrollo. <br><br><b>Sergio Sebastián Iglesias Pérez:</b> <br> TP1: <br> Mediante la creación de Mobile Applications Wireflow y User Flow Diagrams, además de evidencias de Testing Suite y Deployment, actualicé mis conocimientos en pruebas de software y despliegue, fortaleciendo mis competencias en control de calidad y desarrollo móvil. </td>
<td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal">TB1: <br> Como grupo, actualizamos y fortalecimos nuestros conocimientos en metodologías ágiles, diseño de experiencia de usuario y arquitectura de software en diferentes niveles. Cada integrante aplicó conceptos actualizados que permitieron enriquecer el proyecto y avanzar en una solución más profesional y estructurada. <br><br>TP1: <br> Como grupo, actualizamos y fortalecimos nuestros conocimientos en metodologías ágiles, diseño de experiencia de usuario y arquitectura de software en distintos niveles. Cada integrante aplicó conceptos actualizados que permitieron enriquecer el proyecto y avanzar hacia una solución más profesional, estructurada y alineada con las buenas prácticas de la ingeniería de software. </td>
</tr>
<tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal">Reconoce la necesidad del
aprendizaje permanente para el
desempeño profesional y el desarrollo
de proyectos en soluciones de
tecnologías de ingeniería de software.</td>
<td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal"><b>Andres Cruz:</b> <br> TB1: <br> Comprendí que siempre debo seguir aprendiendo sobre nuevas metodologías ágiles, backlog prioritization y herramientas de arquitectura, ya que estas prácticas evolucionan constantemente y son esenciales para responder a las demandas cambiantes de la industria. <br><b>Angelo Solano: </b><br> TB1: <br> Trabajar en la definición de usuarios, journey maps y en la capa de interfaz me permitió reconocer que el aprendizaje permanente es fundamental para mantenerme actualizado en metodologías de diseño centrado en el usuario y en tecnologías de desarrollo de software.<br><b>Henry Esteban: </b> <br> TB1: <br> Durante la preparación y análisis de entrevistas reconocí que el aprendizaje permanente es clave para perfeccionar técnicas de levantamiento de información y adaptación de arquitecturas de despliegue a entornos modernos de software.<br><b>Rafael Vivanco:</b><br> TB1: <br> Al aplicar técnicas avanzadas de modelado de dominios, reconocí la importancia del aprendizaje continuo para mantenerme actualizado en arquitecturas modernas y metodologías de diseño que impactan directamente en la calidad de los proyectos de software.<br><b>Sergio Iglesias </b><br> TB1: <br> Al investigar sobre context mapping y estrategias frente a competidores, entendí que el aprendizaje permanente es necesario para responder a escenarios competitivos y tecnológicos que cambian rápidamente en la industria del software.<br><br><b>Víctor Andrés Cruz Ibarra:</b> <br> TP1: <br> Comprendí que el aprendizaje permanente es esencial para mantenerme actualizado en tendencias de diseño digital, guías de estilo y herramientas de prototipado, necesarias para responder a los cambios tecnológicos del entorno profesional. <br><br><b>Ángelo Héctor Solano Armas:</b> <br> TP1: <br> Durante el desarrollo del prototipo móvil, comprendí la importancia de mantener una mejora continua en conocimientos de UX Research, UI Trends y herramientas colaborativas, reconociendo que el aprendizaje constante es la base del crecimiento profesional. <br><br><b>Henry Kalet Esteban Román:</b> <br> TP1: <br> Al enfrentar desafíos en la configuración e implementación, reconocí que el aprendizaje permanente es fundamental para adaptarme a nuevas tecnologías, frameworks y prácticas DevOps, garantizando un mejor desempeño profesional. <br><br><b>Rafael Andrés Vivanco Salazar:</b> <br> TP1: <br> Reconocí la importancia del aprendizaje continuo al trabajar en arquitectura de información y SEO, comprendiendo que la evolución de los algoritmos y frameworks exige actualización constante para mantener la competitividad en el desarrollo de soluciones sostenibles. <br><br><b>Sergio Sebastián Iglesias Pérez:</b> <br> TP1: <br> Durante la implementación de flujos de usuario y pruebas de software, reconocí que el aprendizaje permanente es necesario para adaptarme a metodologías y herramientas cambiantes, lo que refuerza mi compromiso con la mejora técnica continua. </td>
<td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal">TB1: <br> Reconocimos como equipo la importancia del aprendizaje permanente en ingeniería de software. Las herramientas, metodologías y técnicas que aplicamos en esta entrega (desde entrevistas y journey maps hasta diagramas arquitectónicos y event storming) nos mostraron que el conocimiento en este campo evoluciona constantemente, y que debemos mantenernos en actualización continua para garantizar soluciones de calidad en proyectos reales. <br><br>TP1: <br> El grupo reconoció la necesidad del aprendizaje permanente como parte esencial del desarrollo profesional. La diversidad de tareas abordadas permitió evidenciar que las tecnologías, metodologías ágiles y prácticas de diseño evolucionan constantemente, por lo que la actualización continua resulta indispensable para mantener la calidad e innovación en las soluciones de software. </td>
</tr>
</tbody></table>
</br></br>
**Objetivos SMART**

**Rafael Andres Vivanco Salazar**: 
* Obtener una certificación internacional en AWS Cloud Practitioner en un plazo máximo de 18 meses después de mi graduación, dedicando al menos 6 horas semanales de estudio autodidacta y aplicando los conocimientos adquiridos en proyectos personales y laborales, con el fin de fortalecer mi perfil profesional en computación en la nube.

* Integrarme en una empresa de desarrollo de software antes de cumplir un año de egresado, participando en al menos tres proyectos colaborativos en entornos ágiles (Scrum o Kanban) que me permitan aplicar mis competencias técnicas y mejorar mis habilidades de trabajo en equipo y comunicación profesional.

**Cruz Ibarra, Victor Andres**: 
* Alcanzar un puesto como ingeniero de software full stack en una empresa tecnológica dentro de los primeros 10 meses después de graduarme, completando tres proyectos personales que integren frontend (Angular o React) y backend (Node.js o Java Spring Boot), y publicándolos en mi portafolio profesional en GitHub y LinkedIn.

* Fortalecer mis competencias en gestión de proyectos ágiles obteniendo la certificación Scrum Master en un plazo máximo de un año tras la graduación, participando en al menos dos equipos de desarrollo con metodología Scrum para aplicar los conocimientos adquiridos y mejorar mi liderazgo técnico.

**Roman Esteban, Henry Kalet**: 
* Obtener la certificación internacional Professional Scrum Master (PSM I) en un plazo máximo de 9 meses después de la graduación, dedicando 5 horas semanales al estudio de metodologías ágiles y aplicando los conocimientos adquiridos en al menos un proyecto académico o freelance que utilice la metodología Scrum.

* Desarrollar habilidades de liderazgo y gestión de equipos ágiles participando como Scrum Master en tres proyectos colaborativos durante el primer año posterior a la graduación, con el fin de mejorar la eficiencia del equipo en al menos un 20% mediante la implementación de retrospectivas efectivas y seguimiento de métricas ágiles (velocidad y burndown chart).

**Solano Armas, Angelo Hector**: 
* Convertirme en desarrollador backend especializado en Python y bases de datos SQL en un plazo de 12 meses después de graduarme, completando al menos dos certificaciones en tecnologías backend (como Django y PostgreSQL) y participando en un proyecto freelance o de código abierto que me permita aplicar mis conocimientos en entornos reales.

* Mejorar mis habilidades de comunicación y colaboración profesional al participar activamente en comunidades tecnológicas y eventos de networking (al menos cuatro durante el primer año de egresado), con el fin de ampliar mi red de contactos y fortalecer mi capacidad para trabajar eficazmente en equipos multidisciplinarios.

**Iglesias Pérez, Sergio Sebastián**: 
* Conseguir un puesto como desarrollador front-end junior en una empresa tecnológica dentro de los seis meses posteriores a la graduación, fortaleciendo mis conocimientos en Angular y React mediante la finalización de dos cursos especializados online y la creación de un portafolio con al menos tres proyectos web personales.

* Desarrollar mis habilidades de trabajo en equipo y liderazgo técnico participando en al menos dos proyectos colaborativos de código abierto durante el primer año de egresada, contribuyendo con un mínimo de cinco commits significativos por proyecto, para mejorar mi experiencia profesional y visibilidad en comunidades de desarrollo.
