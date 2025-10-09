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
    - [**2.6.1 Bounded Context: Bounded Context Name**](#261-bounded-context:-bounded-context-name)
        - [**2.6.1.1 Domain Layer**](#2611-domain-laye>)
        - [**2.6.1.2 Interface Layer**](#2612-interface-layer)
        - [**2.6.1.3 Application Layer**](#2613-application-layer)
        - [**2.6.1.4 Infrastructure Layer**](#2614-infrastructure-layer)
        - [**2.6.1.5 Bounded Context Software Architecture Component Level Diagrams**](#2615-bounded-context-software-architecture-component-level-diagrams)
        - [**2.6.1.6 Bounded Context Software Architecture Code Level Diagrams**](#2616-bounded-context-software-architecture-code-level-diagrams)
             - [**2.6.1.6.1 Bounded Context Domain Layer Class Diagrams**](#26161-bounded-context-domain-layer-class-diagrams)
             - [**2.6.1.6.2 Bounded Context Database Design Diagram**](#26162-bounded-context-database-design-diagram)

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
<td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal"><b>Andres Cruz:</b> <br> TB1: <br> Al desarrollar la descripción de la startup y estructurar el Product Backlog con herramientas como Lean UX e Impact Mapping, actualicé mis conocimientos en metodologías ágiles y arquitectura de software, lo cual fortalece mis capacidades para aplicar soluciones en proyectos reales de ingeniería de software. <br> <b>Angelo Solano:</b> <br> TB1: <br> Al realizar Needfinding, User Personas, Journey Maps y modelar la capa de dominio, actualicé mis conocimientos sobre experiencia de usuario y diseño de software en capas, lo que me permitió integrar la visión del usuario con la solución técnica en el proyecto. <br><b>Henry Esteban: </b> <br> TB1: <br> Mediante el diseño, registro y análisis de entrevistas, y la construcción del Deployment Diagram, reforcé mis conocimientos sobre técnicas de recolección de requerimientos y despliegue de software, actualizando competencias claves para el desarrollo de proyectos de ingeniería. <br><b>Rafael Vivanco:</b><br> TB1: <br> Al analizar los segmentos objetivos, la competencia y mapear los contextos, actualicé mis conocimientos en análisis estratégico y en arquitectura de software a nivel de contenedores y contexto, lo que me permitió integrar tanto la visión de negocio como la técnica en el proyecto. <br><b>Sergio Iglesias </b><br> TB1: <br> Al analizar los segmentos objetivos, la competencia y mapear los contextos, actualicé mis conocimientos en análisis estratégico y en arquitectura de software a nivel de contenedores y contexto, lo que me permitió integrar tanto la visión de negocio como la técnica en el proyecto. </td>
<td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal">TB1: <br> Como grupo, actualizamos y fortalecimos nuestros conocimientos en metodologías ágiles, diseño de experiencia de usuario y arquitectura de software en diferentes niveles. Cada integrante aplicó conceptos actualizados que permitieron enriquecer el proyecto y avanzar en una solución más profesional y estructurada. </td>
</tr>
<tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal">Reconoce la necesidad del
aprendizaje permanente para el
desempeño profesional y el desarrollo
de proyectos en soluciones de
tecnologías de ingeniería de software.</td>
<td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal"><b>Andres Cruz:</b> <br> TB1: <br> Comprendí que siempre debo seguir aprendiendo sobre nuevas metodologías ágiles, backlog prioritization y herramientas de arquitectura, ya que estas prácticas evolucionan constantemente y son esenciales para responder a las demandas cambiantes de la industria. <br><b>Angelo Solano: </b><br> TB1: <br> Trabajar en la definición de usuarios, journey maps y en la capa de interfaz me permitió reconocer que el aprendizaje permanente es fundamental para mantenerme actualizado en metodologías de diseño centrado en el usuario y en tecnologías de desarrollo de software.<br><b>Henry Esteban: </b> <br> TB1: <br> Durante la preparación y análisis de entrevistas reconocí que el aprendizaje permanente es clave para perfeccionar técnicas de levantamiento de información y adaptación de arquitecturas de despliegue a entornos modernos de software.<br><b>Rafael Vivanco:</b><br> TB1: <br> Al aplicar técnicas avanzadas de modelado de dominios, reconocí la importancia del aprendizaje continuo para mantenerme actualizado en arquitecturas modernas y metodologías de diseño que impactan directamente en la calidad de los proyectos de software.<br><b>Sergio Iglesias </b><br> TB1: <br> Al investigar sobre context mapping y estrategias frente a competidores, entendí que el aprendizaje permanente es necesario para responder a escenarios competitivos y tecnológicos que cambian rápidamente en la industria del software.</td>
<td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal">TB1: <br> Reconocimos como equipo la importancia del aprendizaje permanente en ingeniería de software. Las herramientas, metodologías y técnicas que aplicamos en esta entrega (desde entrevistas y journey maps hasta diagramas arquitectónicos y event storming) nos mostraron que el conocimiento en este campo evoluciona constantemente, y que debemos mantenernos en actualización continua para garantizar soluciones de calidad en proyectos reales. </td>
</tr>
</tbody></table>
</br></br>


---



<div style="page-break-after: always;"></div>

# <font color="skyblue"> **Capítulo I: Introducción** </font>

## **1.1. Startup Profile**

### **1.1.1. Descripción de la Startup**

Autonexo es una aplicación diseñada para conectar a los propietarios de vehículos con mecánicos especializados en todo tipo de mantenimiento vehicular, ya sea preventivo, correctivo o cualquier otro tipo de servicio automotriz. La aplicación actúa como un intermediario eficiente, proporcionando una solución integral que facilita la interacción entre los conductores y los profesionales del sector automotriz.

La plataforma permite a los propietarios acceder a un catálogo de mecánicos certificados y servicios disponibles, con la posibilidad de elegir en función de la especialización, reputación y proximidad del servicio. Por otro lado, los mecánicos tienen la oportunidad de promocionar sus servicios, gestionar su agenda de forma eficiente y recibir solicitudes de mantenimiento en tiempo real, lo que les permite maximizar su tiempo y la eficiencia de sus operaciones.

Según el estudio realizado por Innocar y Roshfrans (2022), solo el 23.5% de los talleres en América Latina utilizan software especializado para gestionar sus operaciones, lo que evidencia una escasa adopción tecnológica en el sector. Esta brecha tecnológica no solo limita la eficiencia interna de los talleres, sino que también reduce la calidad y transparencia percibida por los clientes..

La plataforma no solo mejora la accesibilidad al servicio automotriz, sino que también permite un registro detallado del historial de mantenimiento de cada vehículo, optimizando la gestión preventiva y reduciendo los costos a largo plazo para los conductores. Además, la capacidad de recibir atención personalizada y el acceso a mecánicos especializados en diversas áreas del mantenimiento incrementan la confianza y la satisfacción del usuario.

El objetivo de Autonexo es transformar la experiencia de mantenimiento vehicular, ofreciendo una solución accesible, transparente y efectiva tanto para los conductores como para los mecánicos. Al mismo tiempo, fomenta la adopción de la tecnología en un sector que históricamente ha dependido de métodos tradicionales y manuales, mejorando la eficiencia y el control sobre los costos de mantenimiento.

### **1.1.2. Perfiles de integrantes del equipo**

<table border="1">
  <tr>
      <td style="text-align:center;"><img alt="Angelo Solano" src="assets/chapter-I-assets/foto3.png" /></td>
      <td><strong>Angelo Solano - u20231B775</strong><br>Mi nombre es Angelo Solano, soy estudiante de Ingeniería de Software en la UPC. Me apasiona la tecnología y todo lo relacionado con el desarrollo de software. Me gusta enfrentarme a desafíos complejos y encontrar soluciones creativas. Estoy en constante aprendizaje, siempre buscando mejorar mis habilidades en programación y análisis de sistemas. Me considero una persona comprometida con mis proyectos y con ganas de crecer tanto profesionalmente como personalmente. Disfruto trabajar en equipo y siempre trato de aportar lo mejor de mí en todo lo que hago.</td>
  </tr>
  <tr>
      <td style="text-align:center;"><img alt="Henry Esteban" src="assets/chapter-I-assets/foto4.png" /></td>
      <td><strong>Henry Esteban - u202310210</strong><br>Mi nombre es Henry Esteban, tengo 20 años y estoy cursando mi 6to ciclo de la carrera de Ingeniería de Software en la UPC. Soy una persona dedicada, analítica y con gran interés en el desarrollo de soluciones tecnológicas innovadoras. Me caracterizo por mi capacidad de trabajo en equipo y mi compromiso con la excelencia en cada proyecto que realizo. Estoy enfocado en aprender constantemente y aplicar mis conocimientos para crear aplicaciones que generen un impacto positivo en la sociedad.</td>
  </tr>
  <tr>
      <td style="text-align:center;"><img alt="Sergio Iglesias " src="assets/chapter-I-assets/foto1.png" /></td>
      <td><strong>Sergio Iglesias - u202316118</strong><br>Mi nombre es Sergio Iglesias, tengo 19 años y estoy cursando mi 6to ciclo de la carrera de Ingeniería de Software en la UPC. Soy una persona proactiva, creativa y con gran pasión por la tecnología. Me destaco por mi capacidad de resolver problemas de manera eficiente y mi habilidad para trabajar colaborativamente en proyectos complejos. Estoy comprometido con el aprendizaje continuo y siempre busco aplicar las mejores prácticas en el desarrollo de software. Mi objetivo es contribuir significativamente al éxito de este proyecto y crecer profesionalmente en el campo de la ingeniería de software.</td>
  </tr>
  <tr>
      <td style="text-align:center;"><img alt="Victor Cruz" src="assets/chapter-I-assets/foto2.png" /></td>
      <td><strong>Victor Cruz - u202311053</strong><br>Mi nombre es Victor Cruz, tengo 19 años y estoy cursando mi 6to ciclo de la carrera de Ingeniería de Software en la UPC. Soy una persona entusiasta, creativa y comprometida con cada actividad que realizo. Estoy decidido a dar lo mejor de mí en este proyecto para lograr resultados de calidad.</td>
  </tr>
  <tr>
      <td style="text-align:center;"><img width="200" height="200" alt="Rafael Vivanco" src="https://github.com/ATG-UPC/AutoNexo-Report/blob/acfeb463d4d95b34589fc359d589992ccfb8465b/assets/chapter-I-assets/photo-Rafael-Vivanco.jpg?raw=true" /></td>
      <td><strong>Rafael Vivanco - u202311064</strong><br>Mi nombre es Rafael Vivanco, tengo 19 años y actualmente curso el 6to ciclo de la carrera de Ingeniería de Software en la UPC. Me considero una persona responsable con facilidad para adaptarme a distintos entornos y manejar varias tareas a la vez. Siempre doy lo mejor de mí en cada proyecto, aportando dedicación, esfuerzo y actitud positiva.</td>
  </tr>
</table>

## **1.2. Solution Profile**

### **1.2.1. Antecedentes y problemática**

#### **Who (¿Quién?)**

Afecta principalmente a **mecánicos y propietarios de vehículos**, quienes necesitan gestionar y acceder a servicios de mantenimiento de manera eficiente.

#### **What (¿Qué?)**

Actualmente, los mecánicos enfrentan dificultades para organizar, planificar y dar seguimiento a los mantenimientos de los vehículos. La ausencia de un registro centralizado y estandarizado provoca errores en el control de historial, retrasos en los servicios y decisiones poco informadas. Por su parte, los propietarios tienen dificultad para encontrar mecánicos confiables y servicios adecuados a sus necesidades, lo que genera desconfianza y pérdida de tiempo.

#### **Where (¿Dónde?)**

Esta problemática se observa en **talleres mecánicos tradicionales** y entre propietarios de vehículos que buscan servicios automotrices confiables, especialmente en entornos urbanos donde la demanda de mantenimiento es alta.

#### **When (¿Cuándo?)**

El problema es constante y se intensifica en periodos críticos, como fechas de mantenimiento preventivo recomendado, estaciones de alto uso del vehículo y ante situaciones donde un vehículo requiere reparación inmediata.


#### **Why (¿Por qué?)**

La raíz del problema es la **falta de digitalización y centralización** en la gestión de servicios automotrices. Muchos talleres dependen de métodos manuales como hojas de cálculo, cuadernos o aplicaciones genéricas que no están diseñadas para el sector automotriz. Esto provoca ineficiencia operativa, aumento de costos y baja satisfacción del cliente.

#### **How (¿Cómo?)**

**Autonexo** propone una solución mediante una **aplicación móvil** que conecta directamente a propietarios con mecánicos certificados. La app permite registrar vehículos, historial de mantenimiento y servicios solicitados, al mismo tiempo que los mecánicos pueden gestionar sus agendas y responder a solicitudes en tiempo real, optimizando tiempos y recursos.

#### **How Much (¿Cuánto?)**

Uno de los principales desafíos en el sector automotriz es la ineficiencia en la gestión del mantenimiento vehicular, lo que genera sobrecostos y pérdida de productividad. Según UpKeep (2023), el mantenimiento puede representar entre el 15 % y 40 % de los costos totales de producción, lo que evidencia su impacto directo en la sostenibilidad financiera de las organizaciones. De igual forma, Infraspeak (2024) señala que hasta un 50 % de los costos de mantenimiento corresponden a desperdicios, ya sea por trabajos innecesarios, duplicación de esfuerzos o falta de planificación estratégica.

### **1.2.2. Lean UX Process**

#### **1.2.2.1. Lean UX Problem Statements**

Autonexo tiene como objetivo ofrecer a talleres mecánicos y propietarios de vehículos una **solución digital integral** que permita centralizar los procesos clave del mantenimiento vehicular, incluyendo el registro de unidades, la planificación de mantenimientos, el control de repuestos, el cálculo de presupuestos y el seguimiento histórico de intervenciones.

Actualmente, la mayoría de talleres y propietarios gestionan el mantenimiento de forma **manual, fragmentada y desorganizada**. Muchos dependen de hojas de Excel, cuadernos o herramientas genéricas que no están adaptadas a las necesidades específicas del sector automotriz. Esto provoca **fallas en el control de registros históricos, mayores costos por mantenimientos correctivos, retrasos en la atención de servicios y decisiones poco informadas** respecto al cuidado de los vehículos.

La falta de estandarización y centralización **limita la eficiencia de los talleres**, reduce la confianza de los propietarios y afecta la calidad del servicio. Además, genera **gastos imprevistos y tiempos muertos** tanto para mecánicos como para propietarios. La ausencia de un sistema unificado impide llevar un seguimiento transparente y ordenado del estado de cada vehículo, impactando negativamente en la productividad de los técnicos y en la satisfacción de los clientes.

**Pregunta clave de diseño:**

> ¿Cómo podríamos centralizar y digitalizar la gestión del mantenimiento vehicular de forma escalable y accesible, permitiendo a mecánicos y propietarios **ahorrar tiempo, reducir costos, mejorar la trazabilidad y asegurar un mantenimiento constante sin complicaciones**?

#### **1.2.2.2. Lean UX Assumptions**

### **Business Assumptions**

1. Nuestros clientes necesitan una plataforma digital centralizada que les permita gestionar de manera integral el mantenimiento de sus vehículos y talleres, ya que actualmente dependen de métodos manuales que generan retrasos y errores, y buscan optimizar la eficiencia y control de sus operaciones.

2. Estas necesidades se pueden resolver mediante un software especializado que integre procesos clave como el registro de vehículos, historial de mantenimiento, planificación de servicios preventivos y correctivos, control de repuestos, cálculo de presupuestos y seguimiento de intervenciones en tiempo real, permitiendo centralizar toda la información y mejorar la trazabilidad de los servicios.

3. Los clientes iniciales serán propietarios de vehículos particulares y mecánicos independientes o de talleres pequeños que actualmente utilizan hojas de Excel, cuadernos o aplicaciones genéricas, y que requieren un sistema confiable para organizar sus mantenimientos y brindar un mejor servicio.

4. El valor más importante que buscan nuestros clientes es un control confiable, eficiente y accesible del mantenimiento vehicular y de los servicios del taller, reduciendo errores, retrasos y gastos innecesarios, mientras aumentan la confianza y satisfacción de los usuarios.

5. Adicionalmente, los usuarios pueden obtener beneficios tangibles como ahorro de tiempo y dinero en mantenimientos correctivos y preventivos, presupuestos claros y detallados para cada servicio, así como acceso a una red de mecánicos o propietarios disponibles en tiempo real según proximidad, especialización y reputación.

6. La adquisición de clientes se realizará mediante marketing digital en redes sociales como Facebook, Instagram y TikTok, campañas en Google Ads enfocadas en búsquedas de servicios automotrices, programas de referidos que incentiven la recomendación de la app, así como alianzas estratégicas con talleres automotrices para fomentar la adopción temprana.

7. El modelo de monetización será a través de suscripción mensual para mecánicos y talleres, otorgándoles acceso a herramientas avanzadas de gestión del taller, listado de propietarios y vehículos registrados en la plataforma, funcionalidades de planificación, presupuesto y seguimiento de historial.

8. La competencia principal incluye aplicaciones como Drivvo, Fleetio y otros softwares genéricos de gestión vehicular, pero nuestro diferencial radica en una interfaz amigable, localización precisa y funcionalidades adaptadas tanto para talleres como para propietarios, incluyendo búsqueda de mecánicos en tiempo real, historial completo y trazable de cada vehículo, y agenda optimizada para talleres.

9. Los venceremos gracias a nuestro enfoque local, la facilidad de uso de la plataforma y las funcionalidades específicas diseñadas para satisfacer tanto a propietarios individuales como a técnicos mecánicos, proporcionando eficiencia operativa y trazabilidad completa del mantenimiento vehicular.

10. El mayor riesgo es que los usuarios no adopten la plataforma debido a la preferencia por métodos tradicionales o a la falta de familiaridad con herramientas digitales, lo que podría limitar el crecimiento y uso del sistema.

11. Para mitigar este riesgo, se implementará una interfaz simple e intuitiva, acompañada de capacitaciones básicas y materiales de apoyo para mecánicos y propietarios, demostraciones gratuitas y pruebas piloto, así como testimonios de clientes satisfechos que incentiven la confianza y la adopción de la plataforma, asegurando que Autonexo cumpla con su objetivo de centralizar y digitalizar la gestión del mantenimiento vehicular de manera eficiente, accesible y confiable.

### **User Assumptions**

1. **¿Quién es el usuario?**

Nuestros usuarios son principalmente **propietarios de vehículos particulares** que buscan cuidar su inversión y optimizar los costos de mantenimiento, así como **mecánicos independientes o de talleres pequeños** que desean llevar un control digital eficiente de múltiples mantenimientos y agendas de servicio, ya que actualmente dependen de métodos manuales o herramientas poco integradas.

2. **¿Qué problema tiene nuestro producto que debe resolver?**

El problema principal que Autonexo debe resolver es la **desorganización y fragmentación en la gestión del mantenimiento vehicular**, que genera sobrecostos, retrasos, fallas mecánicas evitables y pérdida de tiempo en tareas repetitivas o manuales, afectando tanto la eficiencia de los talleres como la satisfacción de los propietarios.

3. **¿Qué características son importantes?**

Para cubrir estas necesidades, el producto debe ofrecer **registro integral de vehículos y usuarios**, una **plataforma de búsqueda de mecánico en tiempo real**, **cálculo de presupuestos de mantenimientos**, **historial detallado de intervenciones por vehículo** y **servicio de mensajería directa entre usuario y mecánico**, todo accesible desde dispositivos móviles para gestionar mantenimientos de manera centralizada y eficiente.

4. **¿Dónde encaja nuestro producto en su trabajo o vida?**

El producto encaja directamente en el **día a día de los propietarios y mecánicos**: los propietarios lo utilizan para planificar, registrar y dar seguimiento a los mantenimientos de sus vehículos, mientras que los mecánicos gestionan múltiples unidades y presupuestos desde un solo lugar, optimizando su tiempo y reduciendo errores operativos.

5. **¿Cuándo y cómo es usado nuestro producto?**

Autonexo será utilizado **cada vez que un usuario necesite planificar, registrar o dar seguimiento a un mantenimiento**, accediendo principalmente desde dispositivos móviles para garantizar flexibilidad, disponibilidad inmediata y control en tiempo real, sin importar si se encuentran en el taller, en ruta o en casa.

6. **¿Cómo debe verse nuestro producto y cómo debe comportarse?**

El diseño y comportamiento del producto deben reflejar un **diseño moderno, limpio y amigable**, con menús intuitivos y fáciles de navegar, garantizando que el sistema responda rápidamente, evite interrupciones y proporcione una **experiencia fluida y confiable**, apta tanto para usuarios con experiencia digital como para aquellos que prefieren soluciones sencillas y accesibles.

#### **1.2.2.3. Lean UX Hypothesis Statements**

### **Hypothesis 01**

**Creemos que** al ofrecer una plataforma centralizada para registrar vehículos, usuarios y mantenimientos, ayudaremos a los usuarios a organizar sus procesos de mantenimiento de manera más eficiente y reducir errores o pérdidas de información.

**Sabremos que hemos tenido éxito**

**Cuando al menos** el 70% de los usuarios registre y mantenga actualizado el historial de sus vehículos y mantenimientos durante el primer mes de uso.

### **Hypothesis 02**

**Creemos que** al integrar herramientas de registro de mantenimiento y cálculo automático de presupuestos, facilitaremos la gestión operativa y financiera de los mecánicos y propietarios de vehículos, permitiéndoles planificar y ejecutar mantenimientos con mayor precisión.

**Sabremos que hemos tenido éxito**

**Cuando al menos** el 60% de los usuarios utilicen estas funciones para planificar o ejecutar mantenimientos dentro de la plataforma.

### **Hypothesis 03**

**Creemos que** al diseñar una interfaz móvil intuitiva, clara y accesible, incentivaremos el uso constante de Autonexo incluso por usuarios con poca experiencia digital.

**Sabremos que hemos tenido éxito**

**Cuando al menos** el 75% de los usuarios activos utilicen la plataforma semanalmente para gestionar sus vehículos.

### **Hypothesis 04**

**Creemos que** al permitir el acceso al historial completo de mantenimiento de cada vehículo, incrementaremos la confianza de los usuarios en sus decisiones de reparación, mantenimiento preventivo o venta de vehículos.

**Sabremos que hemos tenido éxito**

**Cuando al menos** el 50% de los usuarios consulten el historial como parte del proceso de evaluación del estado de sus vehículos.

#### **1.2.2.4. Lean UX Canvas**

- Lean Ux Canvas
<img alt="Lean Ux Canvas" src="assets/chapter-I-assets/lean-ux-canvas-autonexo.jpg" />

<!--[Ver Lean UX Canvas hecho en UxPressia]()-->

## **1.3. Segmentos objetivo**

Con el propósito de llegar de manera efectiva a posibles clientes, Autonexo ha definido dos segmentos principales como público objetivo.

---

### **Segmento objetivo #1: Propietarios**

Personas que poseen uno o más vehículos personales y desean gestionar de forma eficiente el mantenimiento, control de gastos y estado general de su unidad, evitando olvidos o problemas mecánicos por falta de seguimiento.

**Aspectos demográficos:**

Sexo: Masculino y femenino,

Rango de edad: 25–50 años,

Nivel socioeconómico: Clases B y C (media-alta y media).

**Aspectos geográficos:**

Nacionalidad: Perú,

Zona geográfica: Urbana (principalmente Lima Metropolitana y otras ciudades con alta concentración vehicular).

**Aspectos psicográficos:**

Intereses: Cuidado del vehículo, control financiero, tecnología práctica, seguridad vial, soluciones digitales simples,

Estilo de vida: Conducen regularmente, valoran la comodidad y buscan evitar gastos imprevistos o pérdidas de tiempo por fallas mecánicas,

Actitudes: Son conscientes de la importancia del mantenimiento vehicular y están abiertos a herramientas digitales que les faciliten llevar un control ordenado y accesible desde su celular.

**Necesidades clave:**

Recordatorios de mantenimiento, historial de mantenimiento accesible, planificación de servicios, reducción de costos por mantenimientos imprevistos.

**Comportamiento digital:**

Uso de apps móviles, notificaciones y alertas, búsqueda de información y servicios de manera digital y rápida.

---

### **Segmento objetivo #2: Mecánicos**

Profesionales que trabajan en talleres y desean gestionar mejor sus servicios y acceder a historiales de mantenimiento para brindar un mejor servicio a sus clientes.

**Aspectos demográficos:**

Sexo: Masculino (en su mayoría),

Rango de edad: 20–50 años,

Nivel socioeconómico: Clases C y D (media y media-baja).

**Aspectos geográficos:**

Nacionalidad: Perú,

Zona geográfica: Urbana (distritos con concentración de talleres y servicios automotrices).

**Aspectos psicográficos:**

Intereses: Reparación automotriz, optimización de tiempo, atención al cliente, soluciones digitales simples,

Estilo de vida: Profesionales prácticos, con un enfoque técnico, acostumbrados al trabajo manual, pero abiertos a soluciones tecnológicas si son simples y funcionales,

Actitudes: Desean mejorar la calidad de su servicio y organización interna, valoran plataformas que les permitan brindar un servicio más profesional sin complicaciones adicionales.

**Necesidades clave:**

Gestión eficiente de mantenimientos, acceso rápido a historiales de vehículos, reducción de errores en la planificación de servicios, optimización del tiempo de trabajo.

**Comportamiento digital:**

Familiaridad básica con smartphones, uso de aplicaciones simples y rápidas, disposición a digitalizar procesos si la herramienta es intuitiva y confiable.

---



<div style="page-break-after: always;"></div>

# Capítulo II: Requirements Development and Software Solution Design

## 2.1. Competidores
### 2.1.1. Análisis competitivo
<table border="1">
  <thead>
    <tr>
      <th colspan="7" style="text-align: center;"><b>Competitive Analysis Landscape</b></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td colspan="2" align="center">¿Por qué llevar a cabo este análisis?</td>
      <td colspan="5" align="center">El objetivo es definir el posicionamiento de Autonexo frente a soluciones de gestión de flotas y mantenimiento vehicular, identificando diferenciadores de valor y riesgos competitivos para el mercado local.</td>
    </tr>
    <tr>
      <th></th>
      <th></th>
      <th>AutoNexo <img src="assets\chapter-II-assets\logo-1.png.jpg" alt="Fleetio Logo" height="70" width="120"></th>
      <th>Fleetio <img src="assets\chapter-II-assets\competidor_1.png" alt="Drivvo Logo" height="70" width="120"></th>
      <th>Drivvo <img src="assets\chapter-II-assets\competidor_2.png" alt="Drivvo Logo" height="70" width="120"></th>
      <th>Whip Around <img src="assets\chapter-II-assets\competidor_3.png" alt="Whip Around Logo" height="70" width="120"></th>
    </tr>
    <tr>
      <td><strong>Perfil</strong></td>
      <td>Overview</td>
      <td>Autonexo es una aplicación móvil que conecta propietarios de vehículos con mecánicos especializados, facilitando la gestión integral del mantenimiento vehicular mediante un sistema centralizado que incluye registro de vehículos, historial de mantenimientos, búsqueda de servicios y comunicación directa entre usuarios.</td>
      <td>Fleetio es una plataforma SaaS integral de gestión de flotas empresariales que ofrece herramientas avanzadas para el mantenimiento preventivo, seguimiento de combustible, gestión de activos, inspecciones digitales y análisis de datos para optimizar operaciones de flotas comerciales.</td>
      <td>Drivvo es una aplicación móvil orientada a conductores particulares y pequeñas empresas que permite registrar gastos de vehículo, programar recordatorios de mantenimiento, controlar consumo de combustible y generar reportes básicos de costos vehiculares de forma simple e intuitiva.</td>
      <td>Whip Around es una plataforma especializada en inspecciones digitales y mantenimiento para flotas comerciales, enfocada en cumplimiento regulatorio, inspecciones DVIR personalizables, gestión de órdenes de reparación y reporting para compliance con normas de seguridad vehicular.</td>
    </tr>
    <tr>
      <td></td>
      <td><strong>Ventaja competitiva – ¿Qué valor ofrece al cliente?</strong></td>
      <td>Digitaliza y automatiza el proceso de mantenimiento; conecta demanda (conductores) con oferta (mecánicos) y da trazabilidad del historial.</td>
      <td>Gestión centralizada y basada en datos para reducir costos (mantenimiento, combustible) y mejorar decisiones; módulos de inspección, órdenes de trabajo y fuel tracking.</td>
      <td>Accesibilidad y simplicidad móvil para controlar gastos y recordatorios de servicio; apta para usuarios individuales.</td>
      <td>Cumplimiento y seguridad: inspecciones digitalizadas y flujos mecánico–conductor para atender defectos rápido y cumplir normas (CSA/DOT).</td>
    </tr>
    <tr>
      <td><strong>Perfil de marketing</strong></td>
      <td><strong>Mercado objetivo</strong></td>
      <td>Dueños de flotas o conductores individuales y mecánicos/talleres.</td>
      <td>Gestores de flota en transporte, construcción, servicios y sector público.</td>
      <td>Conductores y pequeños negocios que desean controlar gastos/consumo del vehículo.</td>
      <td>Gerentes de flota, supervisores de operaciones y conductores en flotas comerciales.</td>
    </tr>
    <tr>
      <td></td>
      <td><strong>Estrategias de marketing</strong></td>
      <td>Performance en redes, programa de referidos y alianzas con talleres.</td>
      <td>Contenido y recursos para fleet managers (guías, plantillas, blog), demos y pruebas gratuitas.</td>
      <td>Web/app store pages + educación ligera (contenido de uso, ventajas).</td>
      <td>Campañas orientadas a cumplimiento y reducción de riesgos; trial/demo.</td>
    </tr>
    <tr>
      <td><strong>Perfil de producto</strong></td>
      <td><strong>Productos & servicios</strong></td>
      <td>Registro de vehículos/usuarios, planificación y seguimiento de mantenimientos, búsqueda de mecánico, mensajería y presupuestos.</td>
      <td>Gestión de activos, mantenimiento preventivo/WO, inspecciones, combustible, partes/inventario, reportes y mobile app Fleetio Go.</td>
      <td>Registro de gastos, combustible, recordatorios de servicio, reportes; opciones de Fleet para múltiples vehículos.</td>
      <td>Inspecciones DVIR personalizables, mantenimiento, órdenes de reparación y reporting para compliance.</td>
    </tr>
    <tr>
      <td></td>
      <td><strong>Precios & costos</strong></td>
      <td>Suscripción por plan (accesible) para talleres y mecánicos; conductor gratuito o incluido (definición interna).</td>
      <td>Suscripción mensual por plan (Essential/Professional) con usuarios ilimitados; add-ons por herramienta/activo; precios varían por tamaño.</td>
      <td>Gratis (básico) + in-app purchases para Pro; en App Store figuran opciones mensuales/anuales y tiers de flota.</td>
      <td>Suscripción por plan; mínimo mensual publicado: USD $120 (Standard) y $220 (Pro) en mes a mes; opciones "FixedUnlimited" para activos ilimitados.</td>
    </tr>
    <tr>
      <td></td>
      <td><strong>Canales de distribución</strong></td>
      <td>Web y app móvil.</td>
      <td>Web + app móvil; usuarios ilimitados incluidos.</td>
      <td>App móvil (iOS/Android); web principalmente informativa.</td>
      <td>Web y app móvil.</td>
    </tr>
    <tr>
      <td><strong>Análisis SWOT</strong></td>
      <td><strong>Fortalezas</strong></td>
      <td>Enfoque local, matching conductor–mecánico, trazabilidad del historial.</td>
      <td>Cobertura funcional amplia y ecosistema maduro; fuerte orientación a datos.</td>
      <td>Barrera de entrada baja y usabilidad móvil para usuario individual.</td>
      <td>Especialista en inspecciones y cumplimiento; valor claro para safety/compliance.</td>
    </tr>
    <tr>
      <td></td>
      <td><strong>Debilidades</strong></td>
      <td>Requiere onboarding/educación para talleres no digitalizados.</td>
      <td>Coste total puede crecer con activos/add-ons en flotas grandes.</td>
      <td>Menor cobertura "enterprise"; dependiente del móvil.</td>
      <td>Menor foco en gestión integral de costos/combustible vs. suites completas.</td>
    </tr>
    <tr>
      <td></td>
      <td><strong>Oportunidades</strong></td>
      <td>Digitalización del sector y integraciones (facturación, GPS).</td>
      <td>Creciente adopción SaaS en LATAM/SMBs.</td>
      <td>Extender funciones de flota ligera/pequeñas empresas.</td>
      <td>Integrarse con plataformas de gestión de flotas y TMS.</td>
    </tr>
    <tr>
      <td></td>
      <td><strong>Amenazas</strong></td>
      <td>UX inicial: si es compleja, podría afectar adopción temprana.</td>
      <td>Competidores de menor costo o suites verticales.</td>
      <td>Usuarios migran a soluciones más completas a medida que crecen.</td>
      <td>Cambios normativos que reduzcan inspecciones obligatorias.</td>
    </tr>
  </tbody>
</table>



## 2.1.2. Estrategias y tácticas frente a competidores

Para competir eficazmente frente a suites de gestión de flotas, apps personales de control vehicular y plataformas de inspecciones, Autonexo aplicará las siguientes estrategias y tácticas preliminares, considerando nuestras fortalezas (gestión integral del mantenimiento y conexión conductor–mecánico) y la oportunidad de mercado (demanda creciente de transparencia, trazabilidad y control).

### Diferenciación por enfoque especializado en mantenimiento 

**Estrategia:** Posicionar a Autonexo como la plataforma especializada en mantenimiento vehicular que conecta a conductores/flotas con mecánicos locales, y que centraliza historial, presupuestos y comunicación.

**Tácticas:**
- Desarrollar el buscador de mecánico con filtros por especialidad, SLA y calificación.
- Ofrecer historial técnico unificado (diagnóstico, OT, evidencias) compartible entre taller y conductor.
- Implementar mensajería in-app y cotizaciones rápidas con plantillas.

### Modelo de precios escalables y accesibles

**Estrategia:** Mantener un esquema competitivo con planes por taller/mecánico (nº de vehículos, módulos) y freemium para conductores, mejorando relación valor/precio frente a suites completas.

**Tácticas:**
- Prueba gratuita (n días) y descuento por anualidad; cupones por referidos.
- Add-ons (p. ej., inventario, analítica avanzada, multi-sede).
- Opción pay-per-lead para talleres en el marketplace.

### Mejora progresiva del producto y adaptabilidad 

**Estrategia:** Competir con un ritmo de entrega ágil y modular, priorizando feedback de talleres piloto.

**Tácticas:**
- Sprints mensuales con roadmap público y Beta Program.
- Importadores desde Excel/WhatsApp para acelerar onboarding.

### Seguridad, confianza y cumplimiento

**Estrategia:** Reducir la percepción de riesgo y aumentar la confianza desde etapas tempranas.

**Tácticas:**
- Cifrado en tránsito y en reposo, backups automáticos, control de accesos por roles.
- Auditoría básica externa y pruebas de penetración anuales.
- Bitácora de cambios en historiales y descarga de datos (portabilidad) para transparencia.

### Ecosistema e integraciones 

**Estrategia:** Construir un ecosistema digital que conecte mantenimiento y operaciones para optimizar decisiones con datos.

**Tácticas:**
- APIs RESTful para módulos internos; conectores con facturación, pasarelas de pago, GPS/telemática y WhatsApp Business.
- Alertas inteligentes (kilometraje/horas, tiempo, códigos OBD, garantías de repuesto).
- Dashboard de salud de flota y forecasts de mantenimiento.

### Alianzas estratégicas

**Estrategia:** Acelerar adquisición con presencia local y pruebas guiadas.

**Tácticas:**
- Alianzas con cadenas de talleres, aseguradoras/SOAT y escuelas de mecánica.
- Workshops "Digitaliza tu taller en 3 pasos con Autonexo" y casos de éxito locales.
- Programa de Embajadores de Taller (beneficios por referidos y feedback).

### Adquisición y retención por educación y valor continuo

**Estrategia:** Minimizar barreras de adopción en segmentos poco digitalizados.

**Tácticas:**
- Onboarding guiado y centro de ayuda con micro-videos.
- Plantillas de presupuestos, OT y checklist de inspección.
- NPS trimestral y cohortes de retención con playbooks de reactivación.

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

Se realizó investigación cualitativa mediante entrevistas a los segmentos objetivo del proyecto: mecánicos/talleres y conductores de vehículos. El objetivo fue comprender las herramientas, procesos y problemas actuales en su gestión de mantenimiento vehicular, y validar posibles soluciones digitales basadas en sus experiencias.

Se desarrollaron dos bloques de preguntas, diferenciados por el segmento objetivo. Las preguntas buscaron recopilar tanto información objetiva (contexto de trabajo, herramientas utilizadas) como información subjetiva (percepciones, frustraciones y expectativas respecto a posibles soluciones).

#### Segmento 1: Propietarios de vehículos

**Preguntas sobre la problemática**

1. ¿Cuáles son tus principales problemas al buscar o gestionar mantenimientos de tu vehículo?
2. ¿Cómo sueles pedir actualmente un mantenimiento y en qué parte del proceso se complica más?

**Preguntas sobre la solución**

1. ¿Cómo te gustaría crear la solicitud de mantenimiento en la app (voz, formulario, chat, llamada)?
2. ¿Qué información mínima debería incluir tu solicitud (placa, síntomas, fotos/video, ubicación, presupuesto)?
3. ¿Cómo preferirías ver y comparar mecánicos (lista, mapa, filtros) y qué criterios decidirían tu elección?
4. ¿Qué datos o preferencias te gustaría poder personalizar (mecánico favorito, horarios, precio máximo)?
5. ¿Qué formato de interfaz te resultaría más claro para revisar el estado del trabajo (checklist, porcentaje, fotos)?
6. ¿Qué información debería guardarse en el historial de tu vehículo y cómo te gustaría consultarla?
7. ¿Cómo prefieres realizar el pago de los servicios (Yape/Plin, tarjeta, efectivo) y en qué momento del proceso?
8. ¿Qué criterios usarías para calificar al mecánico después de un servicio (puntualidad, precio, confianza, claridad)?
9. Al abrir la app, ¿qué información te gustaría ver primero (urgencias, citas del día, presupuestos pendientes)?

#### Segmento 2: Mecánicos

**Preguntas sobre la problemática**

1. ¿Cuáles son los problemas más comunes que enfrentas al gestionar los mantenimientos de los vehículos?
2. ¿Qué dificultades actuales en el mantenimiento de vehículos crees que la app debería resolver primero para facilitar tu trabajo?

**Preguntas sobre la solución**

1. ¿Qué procesos consideras esenciales para que una app te ayude a administrar las solicitudes de mantenimiento?
2. ¿Cómo te gustaría que la app recibiera las solicitudes de mantenimiento y qué información debería incluir cada solicitud?
3. ¿Qué funcionalidades te gustaría que tuviera la app para organizar y asignar los trabajos de mantenimiento entre los mecánicos disponibles?
4. ¿Qué opciones de personalización debería ofrecer la app para adaptarse a tus necesidades específicas como mecánico?
5. ¿Qué tipo de interfaz te resultaría más fácil y eficiente para consultar el estado de un vehículo y las reparaciones necesarias?
6. ¿Cómo debería la app manejar el seguimiento de los trabajos realizados y el historial de mantenimiento de cada vehículo?
7. ¿Qué funcionalidades consideras necesarias para que los clientes puedan interactuar con la app de manera clara y efectiva?
8. ¿Qué tipo de alertas o notificaciones serían más útiles para recordarte mantenimientos programados o trabajos pendientes?
9. ¿Qué opciones de pago te gustaría que la app integrara para que el cobro de los servicios sea rápido y seguro?
10. ¿Qué información o herramientas adicionales (p. ej., apoyo a diagnóstico) te gustaría que la app incluyera para hacer diagnósticos más rápidos y sugerir mantenimientos precisos?
11. ¿Qué tipo de retroalimentación o valoraciones te gustaría que los clientes pudieran dejar sobre tu trabajo?
12. ¿Qué información debería mostrar la app al inicio para ayudarte a priorizar los mantenimientos más urgentes?
13. ¿Cómo debería la app ayudarte a coordinar trabajos entre varios mecánicos si un vehículo requiere más de un tipo de mantenimiento?




### 2.2.2. Registro de entrevistas

**Segmento 1: Propietarios de vehículos**

<table border="1">
  <tr>
    <th>Entrevista</th>
    <td>1</td>
    <th>Nombre</th>
    <td>Diego Ignacio Ricra Falla</td>
  </tr>
  <tr>
    <th>Edad</th>
    <td>20</td>
    <th>Distrito</th>
    <td>La molina </td>
  </tr>
  <tr>
    <th>Captura de la entrevista: <img src="assets/chapter-II-assets/Entrevista 1 Propietario.jpg" alt="Captura de la entrevista" width="200"></th>
    <td colspan="3">
        Diego Ricra, estudiante de 19 años, utiliza un CR-V 2012 y enfrenta problemas para encontrar talleres cercanos, confiables y con precios justos. Actualmente depende de un mecánico de confianza recomendado por terceros, pero valora la posibilidad de una app que le permita crear solicitudes personalizadas con fotos, ubicación y presupuesto. Prefiere comparar mecánicos por precio y cercanía, pagar con Yape/Plin o efectivo, y recibir actualizaciones constantes mediante fotos o checklist. Considera clave la confianza, la comunicación clara y las experiencias previas de otros usuarios. Espera que la app le brinde rapidez, transparencia y control en todo el proceso de mantenimiento
    </td>
  </tr>
  <tr>
    <th>URL de la grabación</th>
    <td colspan="3">
      <a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310210_upc_edu_pe/ERJ8Xb5H93hGrCMlwwGrXAoBQhQYCzamRvJsaONqWyGJLw?e=NDdOwH&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D">
        Ver grabación
      </a>
    </td>
  </tr>
  <tr>
   <th>Timing</th>
    <td colspan="3">
        00:00 -08:02
    </td>
  </tr>
</table>
<br>

<table border="1">
  <tr>
    <th>Entrevista</th>
    <td>2</td>
    <th>Nombre</th>
    <td>Freddy Fernandez Camacho</td>
  </tr>
  <tr>
    <th>Edad</th>
    <td>22</td>
    <th>Distrito</th>
    <td>Ate</td>
  </tr>
  <tr>
    <th>Captura de la entrevista: <img src="assets/chapter-II-assets/Entrevista 2 Propietario.jpg" alt="Captura de la entrevista" width="200"></th>
    <td colspan="3">
        Carlos Fredy Camayo, conductor de un Nissan Sunny 2001, enfrenta problemas al encontrar mecánicos confiables, ya que los precios varían y no tiene un taller de confianza. Actualmente se guía por referencias en Facebook, pero valora que una app le permita contactar rápidamente, comparar precios y acceder a soluciones rápidas para problemas comunes. Prefiere personalizar con mecánico favorito, historial de mantenimientos y comparador de repuestos. Pagaría con Yape/QR y espera funciones como buscador de repuestos, citas y soluciones rápidas. Considera esenciales las recomendaciones, precios justos y calificación simple con estrellas y etiquetas.
    </td>
  </tr>
  <tr>
    <th>URL de la grabación</th>
    <td colspan="3">
      <a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310210_upc_edu_pe/ERJ8Xb5H93hGrCMlwwGrXAoBQhQYCzamRvJsaONqWyGJLw?e=NDdOwH&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D">
        Ver grabación
      </a>
    </td>
  </tr>
  <tr>
   <th>Timing</th>
    <td colspan="3">
        08:07 - 14:58
    </td>
  </tr>
</table>
<br>


**Segmento 2: Mecánicos**

<table border="1">
  <tr>
    <th>Entrevista</th>
    <td>3</td>
    <th>Nombre</th>
    <td>José Angel Castillo Miranda</td>
  </tr>
  <tr>
    <th>Edad</th>
    <td>40</td>
    <th>Distrito</th>
    <td>San Luis</td>
  </tr>
  <tr>
    <th>Captura de la entrevista: <img src="assets\chapter-II-assets\Entrevista 3 Mecánico.png" alt="Captura de la entrevista" width="200"></th>
    <td colspan="3">
        El entrevistado, ingeniero en mantenimiento mecánico, señaló como problemas principales la falta de planificación preventiva, la mala comunicación con los conductores y la ausencia de historial organizado de cada vehículo. Consideró esenciales procesos como registro de solicitudes, calendario de mantenimientos, alertas automáticas y reportes de avance. Prefiere interfaces visuales tipo panel con indicadores y acceso rápido al historial, así como notificaciones en tiempo real. También valoró funcionalidades de seguimiento de solicitudes, métodos de pago variados (digitales o tarjeta), retroalimentación clara mediante calificaciones y la posibilidad de organizar trabajos según especialidad y disponibilidad. 
    </td>
  </tr>
  <tr>
    <th>URL de la grabación</th>
    <td colspan="3">
      <a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310210_upc_edu_pe/ERJ8Xb5H93hGrCMlwwGrXAoBQhQYCzamRvJsaONqWyGJLw?e=NDdOwH&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D">
        Ver grabación
      </a>
    </td>
  </tr>
  <tr>
   <th>Timing</th>
    <td colspan="3">
        14:59 - 30:08
    </td>
  </tr>
</table>

<table border="1">
  <tr>
    <th>Entrevista</th>
    <td>4</td>
    <th>Nombre</th>
    <td>Rando Calero</td>
  </tr>
  <tr>
    <th>Edad</th>
    <td>45</td>
    <th>Distrito</th>
    <td>Suquillo</td>
  </tr>
  <tr>
    <th>Captura de la entrevista: <img src="assets\chapter-II-assets\Entrevista 4 Mecánico.jpg" alt="Captura de la entrevista" width="200"></th>
    <td colspan="3">
        Rando Calero, mecánico especialista en la marca Scania y dueño de un taller con un año en el mercado, destacó que los principales problemas en la gestión del mantenimiento son la falta de planificación preventiva y la dependencia de recordatorios manuales o escáneres del vehículo. Actualmente utilizan WhatsApp y registros básicos para coordinar mantenimientos, pero considera que una app debería centralizar el historial por placa, facilitar la comunicación y agilizar el flujo de trabajo. También valoró que la aplicación sea sencilla, con lenguaje accesible, opciones de retroalimentación de clientes, alertas de mantenimientos próximos y reportes claros para dueños, conductores y talleres. Además, ve como oportunidad incluir funciones de promoción de talleres, estadísticas de satisfacción y un flujo automatizado que informe al cliente en cada etapa del servicio.
    </td>
  </tr>
  <tr>
    <th>URL de la grabación</th>
    <td colspan="3">
      <a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310210_upc_edu_pe/ERJ8Xb5H93hGrCMlwwGrXAoBQhQYCzamRvJsaONqWyGJLw?e=NDdOwH&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D">
        Ver grabación
      </a>
    </td>
  </tr>
  <tr>
   <th>Timing</th>
    <td colspan="3">
        30:09 - 40:34
    </td>
  </tr>
</table>

### 2.2.3. Análisis de entrevistas

Las entrevistas se realizaron entre el 5 y el 15 de septiembre de 2025 a un total de 4 participantes: dos conductores y dos mecánicos capacitados de Peru y Venezuela. El objetivo fue identificar patrones comunes en sus frustraciones, expectativas y criterios soluciones digitales en aplicaciones móviles.

**Segmento: Propietarios de vehículos**

**Total entrevistados**: 2

**Edades**: 19 y 21 años

**Distritos**: Ate y La Molina

**Universidad**: Estudiantes universitarios de la UPC

**Vehículos**: Honda CRV 2012 (familiar), Nissan Sunny 2001 (propio)

**Fechas**: Entre el 5 y 9 de septiembre

**Características objetivas**

• Tienen dificultades para encontrar mecánicos de confianza con precios justos: 2/2 (100%)

• Usan referencias de terceros / redes sociales (Facebook, recomendaciones boca a boca) para decidir mecánico: 2/2 (100%)

• Prefieren medios de pago digitales o efectivos (Yape, Plin, QR o efectivo): 2/2 (100%)

• Desean un historial digital de mantenimientos de su vehículo: 2/2 (100%)

• Consideran importante comparar precios antes de aceptar el servicio: 2/2 (100%)

• Valoran que la app permita personalizar opciones (mecánico favorito, horarios, precio máximo, repuestos): 2/2 (100%)

**Características subjetivas**

• Desconfianza hacia los talleres locales por precios inflados o falta de transparencia: 2/2 (100%)

• Consideran que la ubicación del mecánico es un factor clave al decidir (cercanía): 1/2 (50%)

• Priorizan la rapidez en la comunicación con el mecánico (chat, llamada, videollamada): 2/2 (100%)

• Prefieren ver el avance del trabajo con fotos o checklist para mayor control: 2/2 (100%)

• Desean que la plataforma incluya valoraciones y comentarios de otros usuarios como guía: 2/2 (100%)

• Muestran disposición a usar una app siempre que sea intuitiva y rápida: 2/2 (100%)

**Segmento: Mecánicos**

**Total entrevistados**: 2

**Edades**: 40 y 45 años

**Distritos**: San Luis  y Surquillo


**Experiencia**:
- José Castillo: Ingeniero en mantenimiento mecánico con experiencia en diagnósticos, mantenimientos preventivos y gestión operativa.
- Rando Calero: Mecánico especialista en Scania, dueño de taller con 1 año en el mercado.

**Fechas**: Entre el 13 y 15 de septiembre

**Características objetivas**

• Identifican la falta de planificación preventiva como el principal problema de gestión: 2/2 (100%)  
• Consideran esencial el historial digital de cada vehículo para diagnósticos más rápidos: 2/2 (100%)  
• Utilizan actualmente métodos básicos de comunicación (WhatsApp, llamadas): 2/2 (100%)  
• Valoran procesos como registro de solicitudes, seguimiento, alertas y reportes: 2/2 (100%)  
• Prefieren una interfaz clara e intuitiva, con indicadores y paneles visuales: 2/2 (100%)  
• Están abiertos a que los clientes dejen valoraciones y comentarios sobre el servicio: 2/2 (100%)  
• Usan o han considerado usar herramientas digitales complementarias (escáner de vehículos, páginas web, redes sociales): 2/2 (100%)

**Características subjetivas**

• Perciben que la mala comunicación con conductores aumenta costos y retrasa soluciones: 2/2 (100%)  
• Valoran la organización de solicitudes para evitar confusiones o duplicaciones: 2/2 (100%)  
• Consideran clave las notificaciones automáticas de mantenimientos: 2/2 (100%)  
• Desean que la app tenga lenguaje accesible y no excesivamente técnico, para facilitar la adopción: 1/2 (50%)  
• Piensan que la plataforma debe incluir flujo automatizado de trabajo (inicio, mantenimiento en proceso, finalización): 1/2 (50%)  
• Ven con buenos ojos la idea de un sistema de membresías o suscripción para cobros recurrentes: 1/2 (50%)  
• Reconocen que las reseñas negativas pueden dañar la reputación, pero aun así valoran su utilidad para mejorar: 1/2 (50%)

## 2.3. Needfinding

En el siguiente apartado, analizaremos a nuestros segmentos objetivos para identificar sus necesidades y en base a esto ofrecerles soluciones óptimas a sus problemas.


### 2.3.1. User Personas
Las siguientes User Persona representan a los diferentes tipos de usuarios que interactúan con nuestra aplicación. Estos perfiles nos permiten comprender sus características, motivaciones, necesidades y comportamientos, lo que facilita identificar cómo se relacionan con la solución desde su contexto personal hasta el uso activo de la misma.
<br>

- User Persona de José Quispe (mecánico)
<img alt="User-Persona-José-Quispe" src="assets\chapter-II-assets\user-persona-jose.jpg" />

[Ver mapa user persona hecho en UxPressia guardado en Drive](https://drive.google.com/drive/folders/1Ng0UPewRqDezQuOSRunusah6vk5xM6lg?usp=sharing)

<br>

- User Persona de Marina Salinas (propietaria)
<img alt="User-Persona-Marina-Salinas" src="assets\chapter-II-assets\user-persona-marina.jpg" />

[Ver mapa user persona hecho en UxPressia guardado en Drive](https://drive.google.com/drive/folders/1Ng0UPewRqDezQuOSRunusah6vk5xM6lg?usp=sharing)


### 2.3.2. User Task Matrix

<p>En esta sección se presenta el User Task Matrix, que concentra las tareas que los User Persona (que representan a cada segmento) realizan para cumplir sus objetivos. No confundir tareas (tasks) con opciones o características de software, pues las tareas deben ser realizadas por los segmentos independientemente de la existencia de su solución de software.</p>

<table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th rowspan="2">TASK</th>
      <th colspan="2">Propietario de vehículo</th>
      <th colspan="2">Mecánico</th>
    </tr>
    <tr>
      <th>Frecuencia</th>
      <th>Importancia</th>
      <th>Frecuencia</th>
      <th>Importancia</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Iniciar sesión en la app</td>
      <td>Always</td>
      <td>High</td>
      <td>Always</td>
      <td>High</td>
    </tr>
    <tr>
      <td>Consultar historial de mantenimiento</td>
      <td>Often</td>
      <td>High</td>
      <td>Rarely</td>
      <td>Medium</td>
    </tr>
    <tr>
      <td>Solicitar cita de mantenimiento</td>
      <td>Always</td>
      <td>High</td>
      <td>Sometimes</td>
      <td>Medium</td>
    </tr>
    <tr>
      <td>Confirmar cita de mantenimiento</td>
      <td>Always</td>
      <td>High</td>
      <td>Always</td>
      <td>High</td>
    </tr>
    <tr>
      <td>Ver estado de mantenimiento</td>
      <td>Often</td>
      <td>High</td>
      <td>Always</td>
      <td>High</td>
    </tr>
    <tr>
      <td>Dejar reseña de taller</td>
      <td>Sometimes</td>
      <td>Medium</td>
      <td>Rarely</td>
      <td>Low</td>
    </tr>
    <tr>
      <td>Recibir notificación de avance de mantenimiento</td>
      <td>Always</td>
      <td>High</td>
      <td>Always</td>
      <td>High</td>
    </tr>
    <tr>
      <td>Consultar disponibilidad de mecánicos</td>
      <td>Always</td>
      <td>High</td>
      <td>Sometimes</td>
      <td>Medium</td>
    </tr>
    <tr>
      <td>Ver precios de servicios de taller</td>
      <td>Often</td>
      <td>High</td>
      <td>Sometimes</td>
      <td>Medium</td>
    </tr>
    <tr>
      <td>Recibir confirmación de cita</td>
      <td>Always</td>
      <td>High</td>
      <td>Always</td>
      <td>High</td>
    </tr>
    <tr>
      <td>Registrar un incidente o reclamo</td>
      <td>Sometimes</td>
      <td>High</td>
      <td>Sometimes</td>
      <td>High</td>
    </tr>
    <tr>
      <td>Consultar mapa de talleres cercanos</td>
      <td>Often</td>
      <td>Medium</td>
      <td>Rarely</td>
      <td>Low</td>
    </tr>
    <tr>
      <td>Ver promociones de talleres favoritos</td>
      <td>Sometimes</td>
      <td>Medium</td>
      <td>Rarely</td>
      <td>Low</td>
    </tr>
    <tr>
      <td>Confirmar disponibilidad de citas con mecánicos</td>
      <td>Never</td>
      <td>Low</td>
      <td>Always</td>
      <td>High</td>
    </tr>
    <tr>
      <td>Ver historial de calificaciones de talleres</td>
      <td>Often</td>
      <td>Medium</td>
      <td>Rarely</td>
      <td>Low</td>
    </tr>
    <tr>
      <td>Ver detalles del mantenimiento realizado</td>
      <td>Sometimes</td>
      <td>High</td>
      <td>Always</td>
      <td>High</td>
    </tr>
    <tr>
      <td>Comunicación con el propietario (mensaje/chat)</td>
      <td>Never</td>
      <td>Low</td>
      <td>Always</td>
      <td>High</td>
    </tr>
    <tr>
      <td>Consultar disponibilidad de mecánicos por ubicación geográfica</td>
      <td>Often</td>
      <td>High</td>
      <td>Sometimes</td>
      <td>Medium</td>
    </tr>
    <tr>
      <td>Recibir alertas de cambios en mantenimiento o citas</td>
      <td>Sometimes</td>
      <td>High</td>
      <td>Always</td>
      <td>High</td>
    </tr>
    <tr>
      <td>Ver estado de pagos y facturación</td>
      <td>Always</td>
      <td>High</td>
      <td>Never</td>
      <td>Low</td>
    </tr>
    <tr>
      <td>Actualizar datos personales (vehículo, dirección)</td>
      <td>Rarely</td>
      <td>Medium</td>
      <td>Never</td>
      <td>Low</td>
    </tr>
  </tbody>
</table>



### 2.3.3. User Journey Mapping
Los siguientes User Journey Maps corresponden a cada User Persona. Estos diagramas nos ayudarán a identificar y comprender las dificultades que enfrentan en cada fase, desde el momento en que conocen nuestra aplicación hasta la etapa en la que comparten sus experiencias y opiniones sobre su uso.
<br>

- User Journey Map de José Quispe (mecánico)
<br>

<img alt="Journey-Map-José-Quispe" src="assets\chapter-II-assets\journey-map-jose.png" />

[Ver mapa completo hecho en UxPressia guardado en Drive](https://drive.google.com/drive/folders/10U-cHuHY3O-ueZ04tsT49D_9nUT28R7v?usp=drive_link)
<br>

- User Journey Map de Marina Salinas (propietaria)
<br>

<img alt="Journey-Map-Maria-Salinas" src="assets\chapter-II-assets\journey-map-marina.png" />

[Ver mapa completo hecho en UxPressia guardado en Drive](https://drive.google.com/drive/folders/10U-cHuHY3O-ueZ04tsT49D_9nUT28R7v?usp=drive_link)
<br>

### 2.3.4. Empathy Mapping
En esta sección, se elaboró un Empathy Map para analizar a nuestros usuarios, comprendiendo completamente el entorno en el que se desenvuelven. Este proceso nos permitirá profundizar en sus necesidades y orientarnos hacia la oferta de servicios que realmente les sean útiles.
<br>

Para la construcción de los Empathy Maps, el equipo siguió los siguientes pasos:

1.-Preparación: Se revisó la ficha de cada User Persona creada previamente (José Quispe y María Salinas).

2.-Colocar al centro el User Persona: Cada mapa fue desarrollado teniendo al usuario en el centro del análisis, asegurando que sus características, contexto y metas guíen el proceso.

3.-Lluvia de ideas en equipo: Cada integrante compartió observaciones y percepciones sobre el comportamiento, necesidades y frustraciones de los usuarios.

4.-Distribución en secciones: En la herramienta de mapeo se organizaron los aportes respondiendo las preguntas clave:

- ¿Con quién estamos empatizando?
- ¿Qué necesita hacer?
- ¿Qué está diciendo?
- ¿Qué está viendo?
- ¿Qué está haciendo?
- ¿Qué está escuchando?
- ¿Cómo se siente y qué piensa?


5.-Identificación de Pains y Gains: Se clasificaron las preocupaciones, frustraciones y motivaciones que influyen en la experiencia del usuario.

6.-Síntesis: Se consolidaron los hallazgos en un mapa final para cada persona.

<br>

- Empathy Map de José Quispe (mecánico)
<br>

<img alt="Empathy-Map-José-Quispe" src="assets\chapter-II-assets\empathy-map-jose.png" />

[Ver mapa completo hecho en UxPressia guardado en Drive](https://drive.google.com/drive/folders/1SIQ263bxvb-gNEhv7TxBklQGdferWbHq?usp=sharing)
<br>

- Empathy Map de Marina Salinas (propietaria)
<br>

<img alt="Empathy-Map-Maria-Salinas" src="assets\chapter-II-assets\empathy-map-marina.png" />

[Ver mapa completo hecho en UxPressia guardado en Drive](https://drive.google.com/drive/folders/1SIQ263bxvb-gNEhv7TxBklQGdferWbHq?usp=sharing)
<br>

### 2.3.5. Ubiquitous Language
<br>
1. Matching & Booking Context

- Service Request (Solicitud de servicio): Pedido inicial que realiza un cliente para atender una necesidad de mantenimiento o reparación.

- Offer (Oferta): Propuesta realizada por un taller (workshop) para cubrir un Service Request, incluyendo condiciones de precio y tiempo.

- Booking (Reserva): Confirmación de una oferta aceptada por el cliente.

- Booking Confirmation (Confirmación de reserva): Estado en el que el cliente valida definitivamente la reserva y queda registrada en el sistema.

- Booking Reschedule (Reprogramación de reserva): Cambio de la fecha o franja horaria de una reserva existente.

2. Trust & Reputation Context

- Review (Reseña): Valoración escrita y numérica de un servicio recibido por parte de un cliente.

- Trust Score (Puntaje de confianza): Métrica compuesta que refleja la reputación de un taller, un cliente o un servicio específico, en base a reseñas y comportamientos.

- Reputation (Reputación): Percepción acumulada de la calidad y confiabilidad de un taller u oferente, basada en interacciones previas.

3. Workshop Context

- Workshop (Taller): Negocio o entidad que ofrece servicios de reparación y mantenimiento de vehículos.

- Workshop Schedule (Agenda del taller): Plan de disponibilidad de un taller para aceptar reservas.

- Service Order (Orden de servicio): Documento operativo que organiza y detalla el trabajo a realizar sobre un vehículo dentro de un taller.

- Service Item (Ítem de servicio): Actividad o tarea específica incluida dentro de una orden de servicio (ej. cambio de aceite, alineación de ruedas).

4. Vehicle & Maintenance Context

- Vehicle (Vehículo): Bien físico perteneciente a un cliente, sobre el cual se realizan operaciones de mantenimiento o reparación.

- Maintenance Record (Registro de mantenimiento): Histórico auditable de todas las intervenciones realizadas a un vehículo.

- Check-in (Ingreso): Momento en el cual un vehículo es recibido en el taller para iniciar un servicio.

- Check-out (Salida): Momento en el cual un vehículo es entregado de vuelta al cliente tras completar los servicios.

5. Payment & Subscription Context

- Subscription (Suscripción): Acuerdo recurrente mediante el cual un cliente paga para acceder a beneficios o servicios de la plataforma.

- Payment (Pago): Transacción monetaria realizada por un cliente para activar o renovar una suscripción.

- Invoice (Factura): Documento que refleja el detalle de un pago realizado por un cliente.

- Billing Cycle (Ciclo de facturación): Periodo de tiempo que define cuándo corresponde realizar un cobro por la suscripción.

6. IAM (Identity & Access Management) Context

- User (Usuario): Persona que accede a la plataforma con credenciales únicas.

- Role (Rol): Conjunto de permisos asignados a un usuario que define qué acciones puede realizar.

- Permission (Permiso): Autorización concreta para ejecutar una acción en el sistema.

- Authentication (Autenticación): Proceso de verificar la identidad de un usuario mediante credenciales.

- Authorization (Autorización): Proceso de validar que un usuario tiene permisos para acceder a un recurso o realizar una acción.

7. Notifications Context

- Notification (Notificación): Mensaje enviado a uno o más destinatarios para informar sobre un evento o recordatorio.

- Channel (Canal): Medio a través del cual se entrega una notificación (Push, Email, SMS).

- Template (Plantilla): Formato predefinido de un mensaje utilizado en las notificaciones.

- Reminder (Recordatorio): Tipo de notificación programada que recuerda al cliente un evento próximo (ej. revisión del vehículo).

- Transactional Notification (Notificación transaccional): Mensaje generado automáticamente por un evento del sistema (ej. confirmación de reserva).


## 2.4. Requirements specification

### 2.4.1. User Stories

Las historias de usuario constituyen una herramienta fundamental para traducir las necesidades detectadas en entrevistas con usuarios potenciales en especificaciones funcionales del sistema. Su adecuada formulación permite estructurar requisitos claros, priorizados y orientados al usuario final, facilitando así su interpretación por parte del equipo de desarrollo. Esta práctica no solo garantiza una mejor alineación entre las expectativas del cliente y las funcionalidades desarrolladas, sino que también mejora la planificación y asignación de tareas en el ciclo de vida del software. En el caso del proyecto TrackLab, se ha definido un conjunto estructurado de épicas e historias de usuario que sirven como base para el diseño de la landing page, el desarrollo de la aplicación web y la definición de los requerimientos técnicos asociados.

<table border="1">
    <thead>
        <tr>
            <th>Story ID</th>
            <th>Título</th>
            <th>Descripción</th>
            <th>Acceptance Criteria</th>
            <th>Linked ID</th>
        </tr>
    </thead>
    <tbody>
            <tr>
            <td>EP01</td>
            <td>Registro y organización inicial</td>
            <td>Como propietario y taller, quiero registrar vehículos e historiales, para organizar la información base de mantenimiento.</td>
            <td>No corresponde</td>
            <td>US01, US02, US03, US04</td>
        </tr>
        <tr>
            <td>EP02</td>
            <td>Gestión de servicios y reservas</td>
            <td>Como taller y propietario, quiero gestionar ofertas de mantenimiento y reservas, para asegurar que las tareas se coordinen en tiempo y forma.</td>
            <td>No corresponde</td>
            <td>US05, US06, US07</td>
        </tr>
        <tr>
            <td>EP03</td>
            <td>Descubrimiento y personalización</td>
            <td>Como propietario, quiero encontrar talleres y servicios mediante filtros, ubicación y promociones, para elegir la mejor opción.</td>
            <td>No corresponde</td>
            <td>US08, US09, US10, US11</td>
        </tr>
        <tr>
            <td>EP04</td>
            <td>Comunicación y coordinación</td>
            <td>Como usuario, quiero comunicarme y coordinar con el taller en tiempo real, para asegurar un servicio claro y sin errores.</td>
            <td>No corresponde</td>
            <td>US12, US13, US14</td>
        </tr>
        <tr>
            <td>EP05</td>
            <td>Gestión de mantenimientos</td>
            <td>Como usuario, quiero gestionar los mantenimientos desde la creación hasta la finalización, para asegurar el control y trazabilidad de cada servicio.</td>
            <td>No corresponde</td>
            <td>US15, US16, US17, US18, US19</td>
        </tr>
        <tr>
            <td>EP06</td>
            <td>Calificaciones y reputación</td>
            <td>Como usuarios (propietario y taller), queremos calificarnos mutuamente y consultar reputaciones, para fomentar confianza y calidad en el servicio.</td>
            <td>No corresponde</td>
            <td>US20, US21, US22, US23</td>
        </tr>
        <tr>
            <td>EP07</td>
            <td>Landing Page (visitantes)</td>
            <td>Como visitante, quiero acceder a información, registro y soporte desde la landing page, para conocer y empezar a usar la aplicación.</td>
            <td>No corresponde</td>
            <td>US24, US25, US26, US27</td>
        </tr>
           <tr>
            <td>EP08</td>
            <td>Servicios técnicos y APIs REST</td>
            <td>Como equipo de desarrollo, quiero exponer endpoints REST bien documentados y seguros, para facilitar la integración, el mantenimiento y la escalabilidad del sistema.</td>
            <td>No corresponde</td>
            <td>TS01, TS02, TS03, TS04, TS05, TS06, TS07, TS08, TS09, TS10, TS11, TS12, TS13, TS14, TS15</td>
        </tr>
    <tr>
      <td>US01</td>
      <td>Visualizar información y beneficios (Landing Page)</td>
      <td>Como visitante, quiero visualizar la información general de la aplicación y sus beneficios, para entender qué ofrece antes de registrarme.</td>
      <td>
        <p><strong>Scenario 1 — Landing informativa:</strong><br>
          • Given que un visitante accede a la landing page<br>
          • When navega por la sección de información<br>
          • Then el sistema (o la página) presenta claramente los beneficios, secciones y llamados a la acción con información completa sobre el servicio.
        </p>
      </td>
      <td>EP07</td>
    </tr>
    <tr>
      <td>US02</td>
      <td>Catálogo de servicios de taller</td>
      <td>Como taller, quiero publicar ofertas de mantenimiento (ej. cambio de aceite, frenos, afinamiento) con precio, duración y cobertura, para que los propietarios las encuentren y reserven.</td>
      <td>
        <p><strong>Scenario 1 — Publicación válida:</strong><br>
          • Given que el taller proporciona título, descripción, precio, duración, categorías y compatibilidades mínimas<br>
          • When solicita publicar la oferta<br>
          • Then el sistema guarda la oferta con estado publicada, registra timestamps y la hace visible en el catálogo.
        </p>
        <p><strong>Scenario 2 — Campos obligatorios incompletos:</strong><br>
          • Given que el taller omite campos obligatorios (ej. precio o categoría)<br>
          • When intenta publicar la oferta<br>
          • Then el sistema rechaza la publicación y devuelve la lista de campos obligatorios faltantes.
        </p>
        <p><strong>Scenario 3 — Imágenes/validación:</strong><br>
          • Given que el taller adjunta imágenes que exceden límites permitidos<br>
          • When intenta subir las imágenes<br>
          • Then el sistema rechaza las imágenes que exceden el tamaño y acepta las válidas.
        </p>
      </td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US03</td>
      <td>Explorar catálogo y búsqueda</td>
      <td>Como propietario, quiero explorar y buscar ofertas de mantenimiento por palabras clave y categorías, para comparar opciones.</td>
      <td>
        <p><strong>Scenario 1 — Búsqueda con resultados:</strong><br>
          • Given que existen ofertas que coinciden con término o categoría<br>
          • When el propietario busca por palabra clave, categoría o filtro<br>
          • Then el sistema devuelve una lista de ofertas coincidentes paginada y ordenable por distancia, precio, rating o relevancia.
        </p>
        <p><strong>Scenario 2 — Sin resultados:</strong><br>
          • Given que no hay ofertas que coincidan con los criterios de búsqueda<br>
          • When el propietario realiza la búsqueda<br>
          • Then el sistema devuelve una lista vacía y sugiere alternativas (otras categorías o ampliar rango).
        </p>
        <p><strong>Scenario 3 — Vista detalle:</strong><br>
          • Given que el propietario solicita info de una oferta<br>
          • When solicita ver el detalle de la oferta<br>
          • Then el sistema entrega la información completa de la oferta y los datos del taller (rating, ubicación, términos).
        </p>
      </td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US04</td>
      <td>Filtrar por servicio</td>
      <td>Como usuario, quiero filtrar por categorías de servicio (ej. cambio de aceite, frenos, afinamiento), para ver solo ofertas relevantes.</td>
      <td>
        <p><strong>Scenario 1 — Filtros básicos:</strong><br>
          • Given que existen ofertas con distintas categorías<br>
          • When el usuario aplica filtros por categoría o subcategoría<br>
          • Then el sistema devuelve únicamente las ofertas que cumplen los criterios seleccionados.
        </p>
        <p><strong>Scenario 2 — Filtros avanzados:</strong><br>
          • Given que el usuario aplica filtros por compatibilidad (marca/motor/combustible)<br>
          • When aplica dichos filtros<br>
          • Then el sistema muestra las ofertas compatibles y oculta las no compatibles.
        </p>
      </td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US05</td>
      <td>Recomendación por geolocalización</td>
      <td>Como propietario, quiero ver talleres cercanos según rango, para coordinar fácil.</td>
      <td>
        <p><strong>Scenario 1 — Talleres dentro del rango:</strong><br>
          • Given que existen talleres disponibles dentro del rango definido por el propietario<br>
          • When solicita ver talleres cercanos<br>
          • Then el sistema lista los talleres ordenados por distancia.
        </p>
        <p><strong>Scenario 2 — Fallback por código postal:</strong><br>
          • Given que el propietario no permite ubicación por GPS o GPS falla<br>
          • When el propietario suministra código postal o ciudad<br>
          • Then el sistema busca talleres dentro del área indicada y devuelve resultados.
        </p>
        <p><strong>Scenario 3 — Sin talleres en rango:</strong><br>
          • Given que no hay talleres en el rango definido<br>
          • When solicita buscar<br>
          • Then el sistema muestra un mensaje indicando ausencia de talleres en ese rango y sugiere ampliar búsqueda.
        </p>
      </td>
      <td>EP03</td>
    </tr>
    <!-- FASE 2: CONFIGURACIÓN BÁSICA -->
    <tr>
      <td>US06</td>
      <td>Registro de vehículo</td>
      <td>Como propietario, quiero registrar mi vehículo ingresando sus datos básicos, para que quede vinculado a mi perfil.</td>
      <td>
        <p><strong>Scenario 1 — Registro exitoso:</strong><br>
          • Given que el propietario proporciona todos los datos requeridos del vehículo (marca, modelo, año, placa, etc.)<br>
          • When solicita guardar el registro<br>
          • Then el sistema asocia y almacena el vehículo en el perfil del propietario.
        </p>
        <p><strong>Scenario 2 — Registro incompleto:</strong><br>
          • Given que el propietario omite uno o más campos obligatorios<br>
          • When intenta guardar el registro<br>
          • Then el sistema devuelve un error indicando los campos faltantes y no crea el registro.
        </p>
      </td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>US07</td>
      <td>Adjuntar historial inicial</td>
      <td>Como propietario, quiero adjuntar el historial de mantenimiento de mi vehículo, para que el taller conozca trabajos previos.</td>
      <td>
        <p><strong>Scenario 1 — Historial adjuntado:</strong><br>
          • Given que el propietario dispone de documentos o datos de mantenimientos previos<br>
          • When incorpora la información o adjunta los documentos y confirma el registro del vehículo<br>
          • Then el sistema guarda el historial asociado al vehículo y lo marca como disponible para talleres autorizados.
        </p>
        <p><strong>Scenario 2 — Sin historial:</strong><br>
          • Given que el propietario no tiene historial disponible<br>
          • When finaliza el registro del vehículo<br>
          • Then el sistema crea el registro del vehículo sin historial asociado y lo deja marcado como “sin historial”.
        </p>
      </td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>US08</td>
      <td>Visualizar historial de vehículo</td>
      <td>Como taller, quiero visualizar el historial de mantenimientos de un vehículo registrado, para conocer antecedentes y diagnósticos previos.</td>
      <td>
        <p><strong>Scenario 1 — Vehículo con historial:</strong><br>
          • Given que el vehículo tiene registros previos de mantenimiento<br>
          • When el taller solicita consultar el historial del vehículo<br>
          • Then el sistema entrega la lista de registros previos (fechas, tipo de servicio, taller, notas) de forma completa y ordenada.
        </p>
        <p><strong>Scenario 2 — Vehículo sin historial:</strong><br>
          • Given que el vehículo no tiene registros previos<br>
          • When el taller solicita el historial<br>
          • Then el sistema indica que no existen registros previos para ese vehículo.
        </p>
      </td>
      <td>EP01</td>
    </tr>
    <!-- FASE 3: COMUNICACIÓN Y COORDINACIÓN -->
    <tr>
      <td>US09</td>
      <td>Sistema de mensajería</td>
      <td>Como usuario, quiero contar con un chat integrado, para coordinar detalles del mantenimiento.</td>
      <td>
        <p><strong>Scenario 1 — Envío / recepción de mensajes:</strong><br>
          • Given que dos usuarios (propietario y taller) desean comunicarse<br>
          • When uno envía un mensaje<br>
          • Then el sistema entrega el mensaje al destinatario y registra la conversación.
        </p>
        <p><strong>Scenario 2 — Adjuntar fotos:</strong><br>
          • Given que el remitente adjunta imágenes del vehículo<br>
          • When envía el mensaje con adjuntos<br>
          • Then el sistema acepta imágenes dentro de los límites establecidos y las asocia a la conversación.
        </p>
        <p><strong>Scenario 3 — Notificación de nuevo mensaje:</strong><br>
          • Given que llega un nuevo mensaje<br>
          • When el destinatario está offline o en otra sección<br>
          • Then el sistema genera una notificación que informa la llegada del nuevo mensaje.
        </p>
        <p><strong>Scenario 4 — Reporte de abuso:</strong><br>
          • Given que un usuario recibe mensajes inapropiados<br>
          • When reporta la conversación por abuso<br>
          • Then el sistema registra la denuncia y marca la conversación para revisión.
        </p>
      </td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>US10</td>
      <td>Coordinación de citas de mantenimiento</td>
      <td>Como usuario, quiero proponer/aceptar una cita con fecha/hora, para agendar el servicio.</td>
      <td>
        <p><strong>Scenario 1 — Proponer y aceptar cita:</strong><br>
          • Given que el taller dispone de slots y el propietario solicita servicio<br>
          • When el taller propone una fecha/hora y el propietario la acepta<br>
          • Then el sistema registra la cita en ambas agendas y la confirma a ambas partes.
        </p>
        <p><strong>Scenario 2 — Reprogramación:</strong><br>
          • Given que existe una cita programada<br>
          • When una de las partes solicita reprogramar y la otra acepta un nuevo slot disponible<br>
          • Then el sistema actualiza la cita y notifica los cambios.
        </p>
        <p><strong>Scenario 3 — Conflicto de agenda:</strong><br>
          • Given que el slot propuesto ya está ocupado en la agenda del taller<br>
          • When se intenta confirmar una cita que choca con otra<br>
          • Then el sistema rechaza la confirmación y solicita seleccionar otro slot.
        </p>
      </td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>US11</td>
      <td>Notificaciones push</td>
      <td>Como usuario, quiero recibir notificaciones push, para estar informado de eventos relacionados con mis vehículos y mantenimientos.</td>
      <td>
        <p><strong>Scenario 1 — Mensaje nuevo:</strong><br>
          • Given que llega un mensaje nuevo al usuario<br>
          • When el mensaje es enviado por el remitente<br>
          • Then el sistema notifica al destinatario mediante notificación push.
        </p>
        <p><strong>Scenario 2 — Reserva confirmada:</strong><br>
          • Given que una reserva o cita es confirmada<br>
          • When la confirmación queda registrada<br>
          • Then el sistema notifica push a ambas partes.
        </p>
        <p><strong>Scenario 3 — Avance del mantenimiento:</strong><br>
          • Given que el taller actualiza la checklist con un hito relevante<br>
          • When el hito se marca como completado<br>
          • Then el sistema notifica al propietario el avance del servicio.
        </p>
      </td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>US12</td>
      <td>Actualización de checklist en mantenimiento</td>
      <td>Como taller, quiero marcar tareas en la checklist de un mantenimiento en tiempo real, para registrar los avances del servicio.</td>
      <td>
        <p><strong>Scenario 1 — Actualización de tareas (taller):</strong><br>
          • Given que el taller está realizando un mantenimiento y existe una checklist asociada<br>
          • When el taller marca una o varias tareas como realizadas<br>
          • Then el sistema actualiza el estado del mantenimiento y registra la marcación en la trazabilidad del servicio, además notifica el cambio al propietario.
        </p>
      </td>
      <td>EP05</td>
    </tr>
    <tr>
      <td>US13</td>
      <td>Creación de mantenimiento confirmado</td>
      <td>Como taller, quiero crear un mantenimiento confirmado a partir de una reserva aceptada, para dar inicio al servicio.</td>
      <td>
        <p><strong>Scenario 1 — Creación desde reserva aceptada:</strong><br>
          • Given que el propietario ha aceptado una propuesta o reserva<br>
          • When el taller confirma el inicio del servicio<br>
          • Then el sistema crea el registro de mantenimiento pendiente, genera la checklist inicial y asocia la reserva al mantenimiento.
        </p>
        <p><strong>Scenario 2 — Validación de datos antes de crear:</strong><br>
          • Given que el taller intenta crear un mantenimiento desde una reserva<br>
          • When el sistema valida que la reserva esté en estado "aceptada" y que todos los datos requeridos estén completos<br>
          • Then el sistema verifica la validez de la reserva antes de proceder con la creación del mantenimiento.
        </p>
        <p><strong>Scenario 3 — Generación automática de checklist:</strong><br>
          • Given que se está creando un mantenimiento confirmado<br>
          • When el sistema genera la checklist inicial basada en el tipo de servicio solicitado<br>
          • Then el sistema crea automáticamente las tareas estándar para ese tipo de mantenimiento y las marca como pendientes.
        </p>
      </td>
      <td>EP05</td>
    </tr>
    <tr>
      <td>US14</td>
      <td>Visualización de mantenimientos pendientes</td>
      <td>Como usuario, quiero visualizar los mantenimientos pendientes, para dar seguimiento al servicio.</td>
      <td>
        <p><strong>Scenario 1 — Taller: lista de pendientes:</strong><br>
          • Given que el taller tiene mantenimientos asignados<br>
          • When consulta su listado de trabajos<br>
          • Then el sistema muestra la lista de servicios pendientes con su estado y prioridades.
        </p>
        <p><strong>Scenario 2 — Propietario: detalle de su mantenimiento:</strong><br>
          • Given que el vehículo del propietario está en mantenimiento<br>
          • When el propietario consulta el detalle del servicio en curso<br>
          • Then el sistema muestra el estado actual y la checklist asociada en tiempo real.
        </p>
      </td>
      <td>EP05</td>
    </tr>
    <tr>
      <td>US15</td>
      <td>Visualización de checklist en mantenimiento</td>
      <td>Como propietario, quiero visualizar en tiempo real el progreso de la checklist del mantenimiento, para conocer el avance del servicio.</td>
      <td>
        <p><strong>Scenario 1 — Visualización Completa de Checklist:</strong><br>
          • Given que el vehículo está en mantenimiento y la checklist está completa<br>
          • When el propietario solicita el detalle del servicio<br>
          • Then el sistema muestra todas las tareas completadas y las pendientes, con marcas temporales de cada avance, y resalta las tareas que han sido completadas.
        </p>
        <p><strong>Scenario 2 — Checklist en Progreso:</strong><br>
          • Given que el vehículo está en mantenimiento y la checklist tiene tareas en progreso<br>
          • When el propietario solicita el detalle del servicio<br>
          • Then el sistema muestra las tareas pendientes y las que están en progreso, con un indicador visual de progreso (por ejemplo, barra de progreso o porcentaje completado).
        </p>
        <p><strong>Scenario 3 — Actualización en Tiempo Real:</strong><br>
          • Given que el vehículo está siendo atendido y las tareas de la checklist están siendo actualizadas<br>
          • When el propietario visualiza la checklist<br>
          • Then el sistema actualiza la información en tiempo real, reflejando cualquier cambio en el estado de las tareas sin necesidad de recargar la página.
        </p>
      </td>
      <td>EP05</td>
    </tr>
    <tr>
      <td>US16</td>
      <td>Finalización de mantenimiento</td>
      <td>Como taller, quiero finalizar un mantenimiento y registrar los resultados, para cerrar correctamente el servicio.</td>
      <td>
        <p><strong>Scenario 1 — Confirmación de Finalización:</strong><br>
          • Given que el taller ha completado todas las tareas de la checklist<br>
          • When el taller marca el mantenimiento como finalizado<br>
          • Then el sistema solicita una confirmación de la finalización antes de cerrar el servicio, asegurando que no falten tareas.
        </p>
        <p><strong>Scenario 2 — Generación de Informe de Mantenimiento:</strong><br>
          • Given que el mantenimiento ha sido finalizado y los resultados registrados<br>
          • When el taller finaliza el servicio<br>
          • Then el sistema genera un informe final que incluye todos los detalles del mantenimiento (trabajos realizados, repuestos, observaciones, fechas) y lo guarda para su futura consulta en el historial del vehículo.
        </p>
      </td>
      <td>EP05</td>
    </tr>
    <!-- FASE 5: PERSONALIZACIÓN Y CONVENIENCIA -->
    <tr>
      <td>US17</td>
      <td>Taller favorito</td>
      <td>Como propietario, quiero marcar un taller como favorito, para priorizarlo en futuras reservas.</td>
      <td>
        <p><strong>Scenario 1 — Agregar a favoritos:</strong><br>
          • Given que el propietario identifica un taller que desea priorizar<br>
          • When añade el taller a su lista de favoritos<br>
          • Then el sistema almacena el taller en la lista de favoritos del propietario.
        </p>
        <p><strong>Scenario 2 — Quitar de favoritos:</strong><br>
          • Given que el taller está en la lista de favoritos<br>
          • When el propietario lo elimina<br>
          • Then el sistema lo retira de la lista de favoritos.
        </p>
      </td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US18</td>
      <td>Promociones de taller de confianza</td>
      <td>Como propietario, quiero ver promociones de mis talleres favoritos, para decidir antes que el resto.</td>
      <td>
        <p><strong>Scenario 1 — Promos disponibles de favoritos:</strong><br>
          • Given que existen promociones activas de los talleres favoritos del propietario<br>
          • When el propietario consulta el feed de promociones<br>
          • Then el sistema destaca las promociones de favoritos con datos de vigencia, cupos y precio promocional.
        </p>
        <p><strong>Scenario 2 — Mostrar condiciones de promo:</strong><br>
          • Given que una promoción tiene condiciones (cupos limitados, vigencia)<br>
          • When el propietario revisa la promo<br>
          • Then el sistema muestra las condiciones completas y la disponibilidad actual.
        </p>
      </td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US19</td>
      <td>Cancelar reserva de mantenimiento</td>
      <td>Como propietario, quiero cancelar una reserva de mantenimiento programada, para reprogramar si tengo un imprevisto.</td>
      <td>
        <p><strong>Scenario 1 — Cancelación dentro de ventana permitida:</strong><br>
          • Given que la cancelación se realiza dentro de la ventana configurable (ej. >3h antes de la cita)<br>
          • When el propietario solicita cancelar la reserva<br>
          • Then el sistema cambia el estado a cancelada, notifica al taller y aplica la política sin penalidad.
        </p>
        <p><strong>Scenario 2 — Cancelación fuera de ventana:</strong><br>
          • Given que la cancelación se realiza fuera de la ventana permitida (ej. <3h antes)<br>
          • When el propietario solicita cancelar<br>
          • Then el sistema rechaza o aplica la política de penalidad según reglas y notifica al taller.
        </p>
      </td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US20</td>
      <td>Actualización automática del historial</td>
      <td>Como taller, quiero que el historial del vehículo se actualice automáticamente al finalizar un mantenimiento, para mantener la información al día sin tener que hacerlo manualmente.</td>
      <td>
        <p><strong>Scenario 1 — Mantenimiento finalizado:</strong><br>
          • Given que el taller marca un mantenimiento como finalizado y registra los resultados (servicios realizados, repuestos, observaciones)<br>
          • When el registro de cierre queda confirmado<br>
          • Then el sistema añade automáticamente ese mantenimiento al historial del vehículo y lo hace visible en el historial.
        </p>
        <p><strong>Scenario 2 — Mantenimiento cancelado:</strong><br>
          • When que un mantenimiento es cancelado antes de su finalización<br>
          • When el taller registra la cancelación con motivo<br>
          • Then el sistema no añade el mantenimiento al historial y marca el evento como cancelado (sin entrada en historial de servicios realizados).
        </p>
      </td>
      <td>EP01</td>
    </tr>
    <!-- FASE 6: REGISTRO Y SOPORTE -->
    <tr>
      <td>US21</td>
      <td>Registro de usuario (propietario o taller)</td>
      <td>Como visitante, quiero registrarme como propietario o taller desde la landing page, para poder empezar a usar la aplicación.</td>
      <td>
        <p><strong>Scenario 1 — Registro exitoso:</strong><br>
          • Given que el visitante proporciona los datos necesarios y usa un email único<br>
          • When confirma el registro<br>
          • Then el sistema crea la cuenta, la asocia al rol elegido y envía confirmación por correo.
        </p>
        <p><strong>Scenario 2 — Email duplicado:</strong><br>
          • Given que el email ya está registrado en el sistema<br>
          • When el visitante intenta registrarse con ese email<br>
          • Then el sistema impide la duplicación y sugiere recuperar la cuenta o usar otro email.
        </p>
      </td>
      <td>EP07</td>
    </tr>
        <tr>
      <td>US22</td>
      <td>Preguntas frecuentes y soporte</td>
      <td>Como visitante, quiero consultar una sección de preguntas frecuentes y soporte, para resolver dudas comunes antes de usar la aplicación.</td>
      <td>
        <p><strong>Scenario 1 — Acceso a FAQ y contacto:</strong><br>
          • Given que el visitante necesita información o tiene una duda común<br>
          • When accede a la sección de FAQ o al enlace de soporte<br>
          • Then el sistema presenta respuestas categorizadas y ofrece un medio de contacto para soporte en caso de requerir atención personalizada.
        </p>
      </td>
      <td>EP07</td>
    </tr>
    <tr>
      <td>US23</td>
      <td>Contacto y descarga de la app</td>
      <td>Como visitante, quiero acceder a una sección de contacto y call to action para descargar la app, para comunicarme con el equipo o instalar la aplicación fácilmente.</td>
      <td>
        <p><strong>Scenario 1 — Contacto y CTA de descarga:</strong><br>
          • Given que el visitante busca contactar al equipo o descargar la app<br>
          • When consulta la sección de contacto y descarga<br>
          • Then el sistema (la landing) muestra un formulario de contacto funcional y enlaces claros para descargar la app en tiendas compatibles.
        </p>
        <p><strong>Scenario 2 — Envío de formulario de contacto:</strong><br>
          • Given que el visitante completa el formulario de contacto con datos válidos<br>
          • When envía el formulario<br>
          • Then el sistema procesa el mensaje, envía confirmación al visitante y notifica al equipo de soporte sobre la nueva consulta.
        </p>
        <p><strong>Scenario 3 — Descarga según dispositivo:</strong><br>
          • Given que el visitante accede desde diferentes dispositivos (iOS, Android, desktop)<br>
          • When hace clic en el enlace de descarga<br>
          • Then el sistema redirige automáticamente a la tienda de aplicaciones correspondiente (App Store, Google Play) o muestra opciones para ambos sistemas.
        </p>
      </td>
      <td>EP07</td>
    </tr>
    <tr>
      <td>US24</td>
      <td>Calificación de taller</td>
      <td>Como propietario, quiero calificar al taller después de un mantenimiento, para reflejar la calidad del servicio recibido.</td>
      <td>
        <p><strong>Scenario 1 — Calificación válida:</strong><br>
          • Given que el mantenimiento está finalizado y el servicio está asociado al propietario<br>
          • When el propietario registra una calificación (1–5) y un comentario para ese servicio<br>
          • Then el sistema guarda la reseña, la asocia al servicio y actualiza la calificación promedio del taller.
        </p>
        <p><strong>Scenario 2 — Restricción de una reseña por servicio:</strong><br>
          • Given que el propietario ya calificó ese servicio<br>
          • When intenta agregar una segunda reseña para el mismo servicio<br>
          • Then el sistema impide la duplicación y sugiere editar la reseña existente.
        </p>
      </td>
      <td>EP06</td>
    </tr>
    <tr>
      <td>US25</td>
      <td>Calificación de propietario</td>
      <td>Como taller, quiero calificar al propietario después de un mantenimiento, para reflejar mi experiencia trabajando con él.</td>
      <td>
        <p><strong>Scenario 1 — Calificación de propietario:</strong><br>
          • Given que el mantenimiento fue finalizado y corresponde al taller que presta el servicio<br>
          • When el taller registra una calificación y comentario sobre el propietario para ese servicio<br>
          • Then el sistema guarda la evaluación y la asocia al perfil del propietario, contribuyendo a su reputación.
        </p>
        <p><strong>Scenario 2 — Restricción de calificación duplicada:</strong><br>
          • Given que el taller ya calificó al propietario para un servicio específico<br>
          • When intenta calificar nuevamente al mismo propietario para el mismo servicio<br>
          • Then el sistema impide la calificación duplicada y sugiere editar la calificación existente.
        </p>
        <p><strong>Scenario 3 — Calificación con comentario opcional:</strong><br>
          • Given que el taller desea calificar al propietario<br>
          • When proporciona una calificación numérica (1-5) y opcionalmente un comentario<br>
          • Then el sistema acepta la calificación con o sin comentario y actualiza la reputación promedio del propietario.
        </p>
      </td>
      <td>EP06</td>
    </tr>
    <tr>
      <td>US26</td>
      <td>Consulta de reputación de taller</td>
      <td>Como propietario, quiero consultar la reputación de un taller antes de reservar, para decidir si es confiable.</td>
      <td>
        <p><strong>Scenario 1 — Consulta de reputación:</strong><br>
          • Given que el taller tiene reseñas y calificaciones previas<br>
          • When el propietario solicita la reputación del taller<br>
          • Then el sistema muestra calificación promedio, número de reseñas, comentarios recientes y total de servicios realizados, con opciones de ordenar/comparar.
        </p>
        <p><strong>Scenario 2 — Filtro por Rango de Calificación:</strong><br>
          • Given que el propietario desea consultar talleres con cierta calificación<br>
          • When el propietario aplica un filtro de calificación<br>
          • Then el sistema muestra únicamente los talleres que cumplen con el rango de calificación seleccionado (por ejemplo, calificación de 4 estrellas o más).
        </p>
      </td>
      <td>EP06</td>
    </tr>
    <tr>
      <td>US27</td>
      <td>Consulta de reputación de propietario</td>
      <td>Como taller, quiero consultar la reputación de un propietario antes de aceptar su reserva, para saber si es confiable.</td>
      <td>
        <p><strong>Scenario 1 — Consulta de reputación del propietario:</strong><br>
          • Given que el propietario tiene calificaciones previas de otros talleres<br>
          • When el taller solicita la reputación del propietario asociada a la reserva<br>
          • Then el sistema muestra la calificación promedio, comentarios y número de mantenimientos previos.
        </p>
        <p><strong>Scenario 2 — Propietario sin historial:</strong><br>
          • Given que el propietario no tiene calificaciones previas en el sistema<br>
          • When el taller consulta la reputación del propietario<br>
          • Then el sistema indica que es un usuario nuevo sin historial de calificaciones y muestra información básica del perfil.
        </p>
        <p><strong>Scenario 3 — Filtrado por tipo de servicio:</strong><br>
          • Given que el propietario tiene calificaciones de diferentes tipos de servicios<br>
          • When el taller consulta la reputación específica para el tipo de servicio solicitado<br>
          • Then el sistema muestra calificaciones relevantes al tipo de servicio y un promedio específico para esa categoría.
        </p>
      </td>
      <td>EP06</td>
    </tr>
            <td>TS01</td>
            <td>Implementar endpoint para registrar y gestionar vehículos (POST, PUT, DELETE /vehicles)</td>
            <td>Como developer, quiero exponer endpoints para registrar, actualizar y eliminar vehículos, para que los propietarios puedan gestionar sus datos básicos.</td>
            <td>
                <p><strong>Scenario 1 — Registro exitoso:</strong><br>
                    • Given que el cuerpo contiene datos válidos<br>
                    • When se envía la solicitud<br>
                    • Then se responde con 201 Created y el vehículo queda vinculado al propietario.
                </p>
                <p><strong>Scenario 2 — Registro incompleto:</strong><br>
                    • Given que faltan campos obligatorios<br>
                    • When se envía la solicitud<br>
                    • Then se responde con 400 Bad Request indicando los campos faltantes.
                </p>
                <p><strong>Scenario 3 — Actualización exitosa:</strong><br>
                    • Given que el ID del vehículo existe<br>
                    • When se actualiza con datos válidos<br>
                    • Then se responde con 200 OK y los datos se reflejan.
                </p>
                <p><strong>Scenario 4 — Eliminación exitosa:</strong><br>
                    • Given que el ID existe<br>
                    • When se solicita eliminar<br>
                    • Then se responde con 204 No Content.
                </p>
                <p><strong>Scenario 5 — ID no encontrado:</strong><br>
                    • Given que el vehículo no existe<br>
                    • When se intenta actualizar o eliminar<br>
                    • Then se responde con 404 Not Found.
                </p>
            </td>
            <td>EP08</td>
        </tr>
        <tr>
            <td>TS02</td>
            <td>Implementar endpoint para adjuntar y consultar historial de mantenimiento (POST, GET /vehicles/{id}/history)</td>
            <td>Como developer, quiero exponer endpoints para adjuntar y consultar historiales, para que talleres y propietarios accedan a información previa de mantenimientos.</td>
            <td>
                <p><strong>Scenario 1 — Historial adjuntado exitosamente:</strong><br>
                    • Given que el cuerpo tiene documentos válidos<br>
                    • When se envía la solicitud<br>
                    • Then se responde con 201 Created y se vincula al vehículo.
                </p>
                <p><strong>Scenario 2 — Consulta de historial existente:</strong><br>
                    • Given que el vehículo tiene historial<br>
                    • When se consulta el endpoint<br>
                    • Then se responde con 200 OK y la lista de mantenimientos.
                </p>
                <p><strong>Scenario 3 — Vehículo sin historial:</strong><br>
                    • Given que no hay registros previos<br>
                    • When se consulta el historial<br>
                    • Then se responde con 204 No Content.
                </p>
                <p><strong>Scenario 4 — Vehículo no encontrado:</strong><br>
                    • Given que el ID no existe<br>
                    • When se consulta el historial<br>
                    • Then se responde con 404 Not Found.
                </p>
            </td>
            <td>EP08</td>
        </tr>
        <tr>
            <td>TS03</td>
            <td>Implementar endpoint para catálogo de servicios de taller (POST, PUT, DELETE, GET /services)</td>
            <td>Como developer, quiero exponer endpoints para publicar, actualizar, eliminar y listar servicios de los talleres, para que los propietarios puedan explorarlos.</td>
            <td>
                <p><strong>Scenario 1 — Publicación válida:</strong><br>
                    • Given que los datos requeridos son completos<br>
                    • When se publica el servicio<br>
                    • Then se responde con 201 Created.
                </p>
                <p><strong>Scenario 2 — Campos incompletos:</strong><br>
                    • Given que faltan datos obligatorios<br>
                    • When se envía la solicitud<br>
                    • Then se responde con 400 Bad Request.
                </p>
                <p><strong>Scenario 3 — Actualización exitosa:</strong><br>
                    • Given que el servicio existe<br>
                    • When se actualiza con datos válidos<br>
                    • Then se responde con 200 OK.
                </p>
                <p><strong>Scenario 4 — Eliminación exitosa:</strong><br>
                    • Given que el servicio existe<br>
                    • When se solicita eliminar<br>
                    • Then se responde con 204 No Content.
                </p>
                <p><strong>Scenario 5 — ID no encontrado:</strong><br>
                    • Given que el servicio no existe<br>
                    • When se intenta actualizar o eliminar<br>
                    • Then se responde con 404 Not Found.
                </p>
            </td>
            <td>EP08</td>
        </tr>
        <tr>
            <td>TS04</td>
            <td>Implementar endpoint para gestión de reservas de mantenimiento (POST, PUT, DELETE, GET /reservations)</td>
            <td>Como developer, quiero exponer endpoints para crear, actualizar, cancelar y consultar reservas, para que talleres y propietarios puedan coordinar mantenimientos.</td>
            <td>
                <p><strong>Scenario 1 — Reserva creada exitosamente:</strong><br>
                    • Given que los datos son válidos<br>
                    • When se crea una reserva<br>
                    • Then se responde con 201 Created.
                </p>
                <p><strong>Scenario 2 — Cancelación dentro de ventana permitida:</strong><br>
                    • Given que la cancelación cumple las reglas<br>
                    • When se solicita cancelar la reserva<br>
                    • Then se responde con 200 OK y estado “cancelada”.
                </p>
                <p><strong>Scenario 3 — Cancelación fuera de ventana:</strong><br>
                    • Given que la cancelación no cumple la política<br>
                    • When se solicita cancelar<br>
                    • Then se responde con 409 Conflict o la política definida.
                </p>
                <p><strong>Scenario 4 — Reserva no encontrada:</strong><br>
                    • Given que el ID no existe<br>
                    • When se consulta o cancela la reserva<br>
                    • Then se responde con 404 Not Found.
                </p>
            </td>
            <td>EP08</td>
        </tr>
        <tr>
            <td>TS05</td>
            <td>Implementar endpoint para sistema de mensajería (POST, GET /messages)</td>
            <td>Como developer, quiero exponer endpoints para enviar y consultar mensajes, para que propietarios y talleres puedan coordinarse vía chat.</td>
            <td>
                <p><strong>Scenario 1 — Envío exitoso:</strong><br>
                    • Given que el cuerpo es válido<br>
                    • When se envía un mensaje<br>
                    • Then se responde con 201 Created y se almacena la conversación.
                </p>
                <p><strong>Scenario 2 — Adjuntar imágenes:</strong><br>
                    • Given que se adjuntan imágenes dentro de límites permitidos<br>
                    • When se envía el mensaje<br>
                    • Then se responde con 201 Created y archivos asociados.
                </p>
                <p><strong>Scenario 3 — Consulta de mensajes:</strong><br>
                    • Given que existen mensajes previos<br>
                    • When se consulta la conversación<br>
                    • Then se responde con 200 OK y la lista.
                </p>
                <p><strong>Scenario 4 — Conversación inexistente:</strong><br>
                    • Given que no hay mensajes<br>
                    • When se consulta la conversación<br>
                    • Then se responde con 204 No Content.
                </p>
            </td>
            <td>EP08</td>
        </tr>
        <tr>
            <td>TS06</td>
            <td>Implementar endpoint para calificaciones y reputación (POST, GET /ratings)</td>
            <td>Como developer, quiero exponer endpoints para registrar calificaciones y consultar reputaciones de talleres/propietarios, para fomentar confianza en el sistema.</td>
            <td>
                <p><strong>Scenario 1 — Calificación registrada exitosamente:</strong><br>
                    • Given que los datos son válidos<br>
                    • When se registra la reseña<br>
                    • Then se responde con 201 Created.
                </p>
                <p><strong>Scenario 2 — Calificación duplicada:</strong><br>
                    • Given que ya existe una reseña para el mismo servicio<br>
                    • When se intenta registrar otra<br>
                    • Then se responde con 409 Conflict.
                </p>
                <p><strong>Scenario 3 — Consulta de reputación existente:</strong><br>
                    • Given que el taller o propietario tiene reseñas<br>
                    • When se consulta la reputación<br>
                    • Then se responde con 200 OK con estadísticas.
                </p>
                <p><strong>Scenario 4 — Sin calificaciones previas:</strong><br>
                    • Given que no existen reseñas<br>
                    • When se consulta la reputación<br>
                    • Then se responde con 204 No Content.
                </p>
            </td>
            <td>EP08</td>
        </tr>
        <tr>
            <td>TS07</td>
            <td>Implementar endpoint para exploración y búsqueda de servicios (GET /services?filters=)</td>
            <td>Como developer, quiero exponer un endpoint que permita buscar y filtrar servicios por palabras clave, categorías, compatibilidad y orden, para que los propietarios encuentren opciones fácilmente.</td>
            <td>
                <p><strong>Scenario 1 — Búsqueda con resultados:</strong><br>
                    • Given que existen servicios que coinciden con los filtros<br>
                    • When se consulta el endpoint<br>
                    • Then se responde con 200 OK con arreglo de servicios.
                </p>
                <p><strong>Scenario 2 — Sin resultados:</strong><br>
                    • Given que no existen coincidencias<br>
                    • When se consulta el endpoint<br>
                    • Then se responde con 200 OK con un arreglo vacío y sugerencias.
                </p>
                <p><strong>Scenario 3 — Vista detalle de servicio:</strong><br>
                    • Given que se solicita ver un servicio específico<br>
                    • When se consulta el detalle<br>
                    • Then se responde con 200 OK con la información completa.
                </p>
            </td>
            <td>EP08</td>
        </tr>
            <tr>
      <td>TS08</td>
      <td>Implementar endpoint para filtros y geolocalización de talleres (GET /workshops?location=)</td>
      <td>Como developer, quiero exponer un endpoint para filtrar talleres por servicio, ubicación (GPS/código postal) y compatibilidad, para que los propietarios tengan resultados relevantes.</td>
      <td>
        <p><strong>Scenario 1 — Talleres dentro del rango:</strong><br>
            • Given que existen talleres en el rango definido<br>
            • When se consulta el endpoint<br>
            • Then se responde con 200 OK con lista ordenada por distancia.
        </p>
        <p><strong>Scenario 2 — GPS no disponible:</strong><br>
            • Given que no se puede usar la ubicación por GPS<br>
            • When se consulta con código postal<br>
            • Then se responde con 200 OK con talleres en esa zona.
        </p>
        <p><strong>Scenario 3 — Sin talleres:</strong><br>
            • Given que no hay talleres disponibles<br>
            • When se realiza la búsqueda<br>
            • Then se responde con 200 OK con un arreglo vacío y sugerencia de ampliar rango.
        </p>
      </td>
      <td>EP08</td>
    </tr>
    <tr>
      <td>TS09</td>
      <td>Implementar endpoint para gestión de favoritos (POST, DELETE, GET /favorites)</td>
      <td>Como developer, quiero exponer endpoints para agregar, eliminar y listar talleres favoritos, para que los propietarios puedan priorizarlos.</td>
      <td>
        <p><strong>Scenario 1 — Agregar taller a favoritos:</strong><br>
            • Given que el taller existe<br>
            • When se envía la solicitud de agregar<br>
            • Then se responde con 201 Created.
        </p>
        <p><strong>Scenario 2 — Quitar de favoritos:</strong><br>
            • Given que el taller está en la lista de favoritos<br>
            • When se envía la solicitud de eliminar<br>
            • Then se responde con 204 No Content.
        </p>
        <p><strong>Scenario 3 — Listar favoritos:</strong><br>
            • Given que el usuario tiene talleres favoritos<br>
            • When se consulta el endpoint<br>
            • Then se responde con 200 OK con la lista.
        </p>
        <p><strong>Scenario 4 — Taller no encontrado:</strong><br>
            • Given que el taller no existe<br>
            • When se consulta o elimina<br>
            • Then se responde con 404 Not Found.
        </p>
      </td>
      <td>EP08</td>
    </tr>
    <tr>
      <td>TS10</td>
      <td>Implementar endpoint para promociones de talleres (GET /promotions)</td>
      <td>Como developer, quiero exponer un endpoint para listar promociones de talleres, con especial énfasis en los favoritos del propietario.</td>
      <td>
        <p><strong>Scenario 1 — Promociones disponibles:</strong><br>
            • Given que existen promociones activas<br>
            • When se consulta el endpoint<br>
            • Then se responde con 200 OK con condiciones.
        </p>
        <p><strong>Scenario 2 — Sin promociones activas:</strong><br>
            • Given que no existen promociones<br>
            • When se consulta el endpoint<br>
            • Then se responde con 204 No Content.
        </p>
      </td>
      <td>EP08</td>
    </tr>
    <tr>
      <td>TS11</td>
      <td>Implementar endpoint para coordinación de citas (POST, PUT /appointments)</td>
      <td>Como developer, quiero exponer endpoints para proponer, aceptar y reprogramar citas de mantenimiento, para sincronizar agendas.</td>
      <td>
        <p><strong>Scenario 1 — Cita propuesta y aceptada:</strong><br>
            • Given que el taller propone una cita y el propietario la acepta<br>
            • When se confirma la solicitud<br>
            • Then se responde con 201 Created.
        </p>
        <p><strong>Scenario 2 — Reprogramación exitosa:</strong><br>
            • Given que existe una cita programada<br>
            • When se solicita reprogramar con un nuevo slot válido<br>
            • Then se responde con 200 OK.
        </p>
        <p><strong>Scenario 3 — Conflicto de agenda:</strong><br>
            • Given que el slot ya está ocupado<br>
            • When se intenta confirmar<br>
            • Then se responde con 409 Conflict.
        </p>
      </td>
      <td>EP08</td>
    </tr>
    <tr>
      <td>TS12</td>
      <td>Implementar endpoint para notificaciones push (POST /notifications)</td>
      <td>Como developer, quiero exponer un endpoint que dispare notificaciones push al móvil/web, para informar sobre mensajes, reservas y mantenimientos.</td>
      <td>
        <p><strong>Scenario 1 — Mensaje nuevo:</strong><br>
            • Given que un usuario recibe un mensaje<br>
            • When el sistema lo registra<br>
            • Then se envía una notificación push.
        </p>
        <p><strong>Scenario 2 — Reserva confirmada:</strong><br>
            • Given que se confirma una reserva<br>
            • When el sistema guarda la confirmación<br>
            • Then se envía una notificación push a ambas partes.
        </p>
        <p><strong>Scenario 3 — Avance checklist:</strong><br>
            • Given que el taller actualiza un hito de la checklist<br>
            • When el cambio se guarda<br>
            • Then se envía una notificación push al propietario.
        </p>
      </td>
      <td>EP08</td>
    </tr>
    <tr>
      <td>TS13</td>
      <td>Implementar endpoint para gestión de mantenimientos (POST, PUT, GET, DELETE /maintenances)</td>
      <td>Como developer, quiero exponer endpoints para crear, listar, actualizar (checklist, estado) y finalizar mantenimientos, para garantizar trazabilidad.</td>
      <td>
        <p><strong>Scenario 1 — Creación desde reserva:</strong><br>
            • Given que existe una reserva aceptada<br>
            • When el taller confirma el inicio<br>
            • Then se responde con 201 Created.
        </p>
        <p><strong>Scenario 2 — Actualización de checklist:</strong><br>
            • Given que existe un mantenimiento activo<br>
            • When se marcan tareas como realizadas<br>
            • Then se responde con 200 OK.
        </p>
        <p><strong>Scenario 3 — Visualizar mantenimientos pendientes:</strong><br>
            • Given que existen mantenimientos activos<br>
            • When se consulta la lista<br>
            • Then se responde con 200 OK.
        </p>
        <p><strong>Scenario 4 — Finalización:</strong><br>
            • Given que todas las tareas están completadas<br>
            • When se marca como finalizado<br>
            • Then se responde con 200 OK con registro completo.
        </p>
        <p><strong>Scenario 5 — ID no encontrado:</strong><br>
            • Given que el mantenimiento no existe<br>
            • When se consulta o actualiza<br>
            • Then se responde con 404 Not Found.
        </p>
      </td>
      <td>EP08</td>
    </tr>
    <tr>
      <td>TS14</td>
      <td>Implementar endpoint para landing page y registro de usuarios (POST, GET /users)</td>
      <td>Como developer, quiero exponer endpoints para registrar propietarios/talleres desde la landing y obtener datos de usuarios, para iniciar la experiencia digital.</td>
      <td>
        <p><strong>Scenario 1 — Registro exitoso:</strong><br>
            • Given que el visitante proporciona datos válidos<br>
            • When se envía la solicitud<br>
            • Then se responde con 201 Created con rol asignado.
        </p>
        <p><strong>Scenario 2 — Email duplicado:</strong><br>
            • Given que el email ya está registrado<br>
            • When se intenta registrar<br>
            • Then se responde con 409 Conflict.
        </p>
        <p><strong>Scenario 3 — Consulta de usuario existente:</strong><br>
            • Given que el usuario existe<br>
            • When se consulta su información<br>
            • Then se responde con 200 OK.
        </p>
        <p><strong>Scenario 4 — Usuario no encontrado:</strong><br>
            • Given que el usuario no existe<br>
            • When se consulta el endpoint<br>
            • Then se responde con 404 Not Found.
        </p>
      </td>
      <td>EP08</td>
    </tr>
    <tr>
  <td>TS15</td>
  <td>Implementar endpoint para soporte, FAQ y contacto (GET /faq, POST /support, POST /contact)</td>
  <td>Como developer, quiero exponer endpoints que devuelvan FAQ, gestionen tickets de soporte y permitan contacto, para resolver dudas de visitantes.</td>
  <td>
    <p><strong>Scenario 1 — FAQ con registros:</strong><br>
        • Given que existen entradas en la FAQ<br>
        • When se consulta el endpoint<br>
        • Then se responde con 200 OK con la lista.
    </p>
    <p><strong>Scenario 2 — FAQ vacío:</strong><br>
        • Given que no hay registros en FAQ<br>
        • When se consulta el endpoint<br>
        • Then se responde con 204 No Content.
    </p>
    <p><strong>Scenario 3 — Ticket de soporte creado:</strong><br>
        • Given que un visitante envía un ticket válido<br>
        • When se procesa la solicitud<br>
        • Then se responde con 201 Created.
    </p>
    <p><strong>Scenario 4 — Contacto enviado:</strong><br>
        • Given que un visitante completa el formulario de contacto<br>
        • When se envía la solicitud<br>
        • Then se responde con 201 Created.
    </p>
  </td>
  <td>EP08</td>
</tr>
  </tbody>
</table>






  </tbody>
</table>






<h2>Spike 1: Investigación de la Integración de Stripe para el Procesamiento de Pagos</h2>

<table border="1">
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>SP-01</td>
    <td>Developer</td>
    <td>Alta</td>
    <td>Autenticación</td>
  </tr>
</table>

<h3>Title: Investigación de la Integración de Stripe para el Procesamiento de Pagos</h3>

<h4>Description:</h4>
<p>Como equipo de desarrollo, queremos investigar cómo integrar Stripe para el procesamiento de pagos en la plataforma Autonexo, para asegurarnos de que sea una solución adecuada para manejar pagos de manera segura y eficiente.</p>

<h4>Acceptance Criteria:</h4>
<ul>
  <li><strong>Given</strong> acceso a la documentación de la API de Stripe, <strong>When</strong> se revisan las opciones disponibles para el procesamiento de pagos (como Payments, Checkout, Mobile SDKs, Stripe.js), <strong>Then</strong> se debe definir si Stripe es adecuado para la integración en Autonexo.</li>
  <li><strong>Given</strong> las tarifas de Stripe, <strong>When</strong> se comparan los costos con otros sistemas de pagos en el mercado, <strong>Then</strong> se debe decidir si Stripe es la opción más económica para Autonexo.</li>
  <li><strong>Given</strong> las opciones de suscripción de Stripe, <strong>When</strong> se determina si la plataforma de Autonexo requiere un modelo de suscripción mensual, <strong>Then</strong> se debe confirmar que Stripe es compatible con este modelo y con las necesidades de Autonexo.</li>
  <li><strong>Given</strong> las capacidades de integración de Stripe con plataformas móviles (iOS/Android), <strong>When</strong> se verifica la documentación de integración con plataformas móviles a través de los Mobile SDKs de Stripe, <strong>Then</strong> se debe confirmar que Stripe es fácil de integrar con las aplicaciones móviles de Autonexo.</li>
  <li><strong>Given</strong> que la integración de Stripe se prueba en un entorno de pruebas, <strong>When</strong> se realiza una transacción de pago utilizando un flujo de pago de prueba, <strong>Then</strong> se debe verificar que el pago se procese correctamente y que la información de pago se guarde de manera segura.</li>
  <li><strong>Given</strong> que el procesamiento de pagos debe ser seguro, <strong>When</strong> se revisa el cumplimiento de las normativas de seguridad de Stripe (como PCI-DSS y tokenización), <strong>Then</strong> se debe garantizar que Stripe cumpla con los estándares de seguridad necesarios.</li>
  <li><strong>Given</strong> que la integración de Stripe afecta tanto al frontend como al backend, <strong>When</strong> se verifica la compatibilidad de Stripe con el backend (Spring Boot), <strong>Then</strong> se debe asegurar que los endpoints RESTful y los webhooks de Stripe funcionen correctamente con el sistema backend de Autonexo.</li>
  <li><strong>Given</strong> que la plataforma Autonexo podría tener un alto volumen de transacciones, <strong>When</strong> se realizan pruebas de carga en la integración de Stripe, <strong>Then</strong> se debe asegurar que Stripe pueda manejar un gran volumen de pagos sin afectar el rendimiento.</li>
  <li><strong>Given</strong> que el procesamiento de pagos debe ser rápido, <strong>When</strong> se miden los tiempos de latencia al realizar pagos con Stripe, <strong>Then</strong> los tiempos de procesamiento de pagos no deben exceder los 3 segundos.</li>
  <li><strong>Given</strong> que la integración de Stripe requiere documentación clara, <strong>When</strong> se documentan los pasos de integración, <strong>Then</strong> se debe crear un informe detallado que describa cómo integrar Stripe en Autonexo, incluyendo cualquier problema encontrado y las soluciones propuestas.</li>
  <li><strong>Given</strong> que el flujo de pago debe ser fácil de usar para los clientes de Autonexo, <strong>When</strong> se prueba el flujo de pago en un entorno de pruebas con usuarios simulados, <strong>Then</strong> se debe asegurar que la experiencia del usuario sea intuitiva, rápida y sin errores.</li>
</ul>




<h2>Spike 2: Investigación de Google Maps para la Localización de Mecánicos</h2>

<table border="1">
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>SP-02</td>
    <td>Developer</td>
    <td>Alta</td>
    <td>Localización</td>
  </tr>
</table>

<h3>Title: Investigación de Google Maps para la Localización de Mecánicos</h3>

<h4>Description:</h4>
<p>Como equipo de desarrollo, quiero investigar la integración de Google Maps para la localización de mecánicos, para ofrecer a los conductores la capacidad de encontrar mecánicos cercanos de manera rápida y eficiente.</p>

<h4>Acceptance Criteria:</h4>
<ul>
  <li><strong>Given</strong> que el equipo tiene acceso a la documentación de la API de Google Maps, <strong>When</strong> el equipo investigue las opciones para implementar mapas interactivos y localización, <strong>Then</strong> deberán determinar si la Google Maps API es adecuada para la integración en Autonexo.</li>
  <li><strong>Given</strong> que el equipo ha analizado los costos asociados a Google Maps API, <strong>When</strong> comparen los costos con los beneficios que aportará la integración de la localización, <strong>Then</strong> deberán decidir si Google Maps es económicamente viable para la plataforma.</li>
  <li><strong>Given</strong> que el equipo ha implementado la API de Google Maps para la localización, <strong>When</strong> realicen pruebas con la función de búsqueda de mecánicos, <strong>Then</strong> deberán asegurarse de que los resultados sean rápidos y precisos.</li>
  <li><strong>Given</strong> que se ha integrado la Google Maps API, <strong>When</strong> realicen pruebas de rendimiento en la carga del mapa y los resultados de búsqueda, <strong>Then</strong> deberán garantizar que el sistema cargue los resultados en menos de 3 segundos.</li>
  <li><strong>Given</strong> que la API de Google Maps está implementada, <strong>When</strong> un usuario busque mecánicos cercanos, <strong>Then</strong> deberán asegurarse de que la ubicación del mecánico sea precisa en el mapa.</li>
  <li><strong>Given</strong> que Autonexo debe ser compatible con dispositivos móviles, <strong>When</strong> el equipo prueba la integración en dispositivos móviles (iOS/Android), <strong>Then</strong> deberán garantizar que la localización funcione correctamente en ambas plataformas.</li>
  <li><strong>Given</strong> que la experiencia del usuario es crucial, <strong>When</strong> implementen la funcionalidad de localización en las aplicaciones móviles y web, <strong>Then</strong> deberán asegurarse de que la interfaz de usuario sea fácil de usar y eficiente.</li>
  <li><strong>Given</strong> que la integración de Google Maps debe trabajar con el backend, <strong>When</strong> el equipo verifique la comunicación entre la API de Google Maps y el backend de Autonexo, <strong>Then</strong> deberán asegurarse de que los datos de ubicación se sincronicen correctamente en tiempo real.</li>
</ul>






<h2>Spike 3: Evaluación de Sistemas de Notificaciones Push</h2>

<table border="1">
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>SP-03</td>
    <td>Developer</td>
    <td>Alta</td>
    <td>Notificaciones</td>
  </tr>
</table>

<h3>Title: Evaluación de Sistemas de Notificaciones Push</h3>

<h4>Description:</h4>
<p>Como equipo de desarrollo, quiero investigar los sistemas de notificaciones push para enviar alertas de mantenimientos próximos a los usuarios, para mejorar la experiencia del usuario y asegurarnos de que nunca se olviden de los mantenimientos.</p>

<h4>Acceptance Criteria:</h4>
<ul>
  <li><strong>Given</strong> que el equipo ha identificado varias opciones de sistemas de notificaciones push como Firebase y OneSignal, <strong>When</strong> investiguen las características y capacidades de cada uno, <strong>Then</strong> deberán decidir cuál es el más adecuado para la plataforma Autonexo.</li>
  <li><strong>Given</strong> que el equipo ha probado la implementación de Firebase Cloud Messaging, <strong>When</strong> envíen una notificación push de prueba, <strong>Then</strong> deberán confirmar que la notificación se recibe correctamente en dispositivos iOS y Android.</li>
  <li><strong>Given</strong> que el equipo ha implementado Firebase Cloud Messaging, <strong>When</strong> evalúen la facilidad de integración en el frontend y backend, <strong>Then</strong> deberán determinar si la integración es sencilla y eficiente para la plataforma.</li>
  <li><strong>Given</strong> que el equipo ha implementado la función de notificaciones push, <strong>When</strong> un usuario reciba una notificación sobre un mantenimiento próximo, <strong>Then</strong> deberán asegurarse de que la notificación sea clara, visible y llegue sin demoras.</li>
  <li><strong>Given</strong> que el equipo ha implementado la funcionalidad de notificaciones programadas, <strong>When</strong> se configure una notificación para ser enviada 24 horas antes de un mantenimiento, <strong>Then</strong> se deberá verificar que la notificación se envíe correctamente en el momento programado.</li>
  <li><strong>Given</strong> que se han considerado otras opciones de notificaciones push como OneSignal, <strong>When</strong> se investigan sus características y ventajas comparativas, <strong>Then</strong> deberán decidir si OneSignal es una alternativa viable a Firebase para la plataforma.</li>
  <li><strong>Given</strong> que el equipo ha implementado la función de notificaciones push, <strong>When</strong> se personaliza el contenido de las notificaciones (como texto, imágenes, botones), <strong>Then</strong> deberán asegurar que las notificaciones sean personalizables según las necesidades del usuario.</li>
  <li><strong>Given</strong> que la plataforma Autonexo puede crecer en número de usuarios, <strong>When</strong> se evalúa la capacidad de Firebase y otras opciones para manejar un gran volumen de notificaciones, <strong>Then</strong> deberán determinar si el sistema puede escalar eficientemente sin afectar el rendimiento.</li>
  <li><strong>Given</strong> que la seguridad de las notificaciones es crucial, <strong>When</strong> se revisa la seguridad en el envío de las notificaciones (como autenticación, encriptación), <strong>Then</strong> deberán garantizar que el sistema de notificaciones cumpla con los estándares de seguridad necesarios.</li>
</ul>


<h2>Spike 4: Investigación de Herramientas de Reportes de Mantenimiento</h2>

<table border="1">
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>SP-04</td>
    <td>Developer</td>
    <td>Alta</td>
    <td>Reportes de Mantenimiento</td>
  </tr>
</table>

<h3>Title: Investigación de Herramientas de Reportes de Mantenimiento</h3>

<h4>Description:</h4>
<p>Como equipo de desarrollo, quiero investigar herramientas como Power BI o Tableau para generar informes detallados sobre el mantenimiento de los vehículos, para mejorar la toma de decisiones y dar a los usuarios acceso a datos importantes.</p>

<h4>Acceptance Criteria:</h4>
<ul>
  <li><strong>Given</strong> que el equipo ha identificado herramientas como Power BI y Tableau, <strong>When</strong> investiguen las características y capacidades de cada herramienta, <strong>Then</strong> deberán seleccionar la herramienta que mejor se adapte a las necesidades de informes de mantenimiento de Autonexo.</li>
  <li><strong>Given</strong> que el equipo ha probado Power BI con datos de prueba, <strong>When</strong> creen un reporte básico, <strong>Then</strong> deberán evaluar si la herramienta proporciona visualizaciones claras y útiles para los usuarios.</li>
  <li><strong>Given</strong> que el equipo ha probado Tableau para la creación de reportes, <strong>When</strong> realicen un análisis de desempeño, <strong>Then</strong> deberán asegurar que Tableau sea capaz de manejar grandes volúmenes de datos de manera eficiente.</li>
  <li><strong>Given</strong> que Power BI y Tableau tienen interfaces diferentes, <strong>When</strong> se comparan la facilidad de uso de ambas herramientas, <strong>Then</strong> deberán elegir la herramienta más fácil de usar para el equipo de desarrollo y los usuarios finales.</li>
  <li><strong>Given</strong> que ambas herramientas tienen modelos de precios distintos, <strong>When</strong> se comparan los costos de uso de Power BI y Tableau, <strong>Then</strong> deberán decidir cuál herramienta ofrece la mejor relación calidad-precio para Autonexo.</li>
  <li><strong>Given</strong> que los informes deben adaptarse a diferentes necesidades, <strong>When</strong> el equipo personaliza los informes en Power BI y Tableau, <strong>Then</strong> deberán garantizar que las herramientas permitan una amplia personalización de los informes, incluyendo gráficos, tablas y filtros.</li>
  <li><strong>Given</strong> que se requiere una visualización clara de los datos de mantenimiento, <strong>When</strong> se comparan las capacidades de visualización de Power BI y Tableau, <strong>Then</strong> deberán decidir cuál herramienta ofrece las mejores opciones de visualización para facilitar la toma de decisiones.</li>
  <li><strong>Given</strong> que los datos de mantenimiento de Autonexo están almacenados en una base de datos, <strong>When</strong> el equipo integra Power BI y Tableau con los datos de mantenimiento, <strong>Then</strong> deberán asegurar que ambas herramientas puedan acceder a los datos de manera eficiente y sin errores.</li>
  <li><strong>Given</strong> que la plataforma Autonexo puede crecer en volumen de datos, <strong>When</strong> el equipo evalúa la escalabilidad de Power BI y Tableau, <strong>Then</strong> deberán determinar si ambas herramientas pueden manejar el crecimiento futuro de los datos sin afectar el rendimiento.</li>
</ul>

<h2>Spike 5: Investigación de Integración de API de Pagos con MercadoPago</h2>

<table border="1">
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>SP-05</td>
    <td>Developer</td>
    <td>Alta</td>
    <td>Integración de Pagos</td>
  </tr>
</table>

<h3>Title: Investigación de Integración de API de Pagos con MercadoPago</h3>

<h4>Description:</h4>
<p>Como equipo de desarrollo, quiero investigar cómo integrar la API de MercadoPago para procesar pagos, para ofrecer una solución de pagos alternativa para los usuarios en la plataforma.</p>

<h4>Acceptance Criteria:</h4>
<ul>
  <li><strong>Given</strong> que el equipo tiene acceso a la documentación de la API de MercadoPago, <strong>When</strong> el equipo investiga las opciones para integrar métodos de pago como tarjetas de crédito y débito, <strong>Then</strong> deberá definir si MercadoPago es adecuado para la integración en Autonexo.</li>
  <li><strong>Given</strong> que el equipo ha realizado una prueba de pago con MercadoPago, <strong>When</strong> el equipo verifique que el proceso de pago se complete correctamente, <strong>Then</strong> deberá confirmar si MercadoPago es viable como solución de pagos para la plataforma.</li>
  <li><strong>Given</strong> que MercadoPago ofrece tarifas para diferentes tipos de transacciones, <strong>When</strong> el equipo compare los costos de MercadoPago con otras soluciones de pagos, <strong>Then</strong> deberá decidir si MercadoPago es económicamente viable para Autonexo.</li>
  <li><strong>Given</strong> que la integración de MercadoPago afecta el backend de Autonexo, <strong>When</strong> el equipo evalúe la compatibilidad de MercadoPago con el backend (Spring Boot), <strong>Then</strong> deberá garantizar que la API de MercadoPago se pueda integrar sin problemas con los servicios RESTful del backend.</li>
  <li><strong>Given</strong> que el equipo requiere personalización en el flujo de pagos, <strong>When</strong> el equipo explore las opciones de personalización de pagos de MercadoPago (páginas de pago, métodos de pago), <strong>Then</strong> deberá determinar si MercadoPago ofrece suficientes opciones de personalización para satisfacer las necesidades de Autonexo.</li>
  <li><strong>Given</strong> que MercadoPago ofrece diferentes métodos de pago, <strong>When</strong> el equipo realice pruebas de pago con diferentes métodos (tarjetas, débito, transferencias), <strong>Then</strong> deberá asegurarse de que todos los métodos de pago funcionen correctamente en la plataforma.</li>
  <li><strong>Given</strong> que la seguridad es fundamental en el procesamiento de pagos, <strong>When</strong> el equipo revise las medidas de seguridad que ofrece MercadoPago (encriptación, cumplimiento con PCI-DSS), <strong>Then</strong> deberá confirmar que MercadoPago cumple con los estándares de seguridad necesarios.</li>
  <li><strong>Given</strong> que MercadoPago utiliza webhooks para notificar cambios de estado en pagos, <strong>When</strong> el equipo implemente y pruebe los webhooks de MercadoPago, <strong>Then</strong> deberá asegurarse de que los webhooks funcionen correctamente y sin errores.</li>
</ul>



<h2>Spike 6: Investigación de Técnicas de Caching para Mejorar el Rendimiento</h2>

<table border="1">
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>SP-06</td>
    <td>Developer</td>
    <td>Alta</td>
    <td>Rendimiento</td>
  </tr>
</table>

<h3>Title: Investigación de Técnicas de Caching para Mejorar el Rendimiento</h3>

<h4>Description:</h4>
<p>Como equipo de desarrollo, quiero investigar técnicas de caching como Redis o Memcached, para mejorar el rendimiento de la plataforma y reducir los tiempos de carga.</p>

<h4>Acceptance Criteria:</h4>
<ul>
  <li><strong>Given</strong> que el equipo ha considerado opciones como Redis y Memcached, <strong>When</strong> investiguen las características y ventajas de cada uno, <strong>Then</strong> deberán seleccionar la opción que mejor se adapte a las necesidades de Autonexo.</li>
  <li><strong>Given</strong> que el equipo ha implementado una solución de caching en Redis, <strong>When</strong> realicen pruebas de rendimiento en una función crítica, <strong>Then</strong> deberán verificar si el tiempo de respuesta mejora significativamente.</li>
  <li><strong>Given</strong> que el equipo ha probado el caching de Memcached, <strong>When</strong> comparen los tiempos de respuesta en diferentes pruebas de carga, <strong>Then</strong> deberán decidir si Memcached es adecuado para el uso en Autonexo.</li>
  <li><strong>Given</strong> que Redis y Memcached tienen implementaciones y configuraciones distintas, <strong>When</strong> el equipo evalúa la facilidad de integración de cada sistema en la arquitectura de Autonexo, <strong>Then</strong> deberán determinar cuál es más sencillo de implementar y mantener.</li>
  <li><strong>Given</strong> que Autonexo puede crecer en volumen de usuarios y datos, <strong>When</strong> se evalúa la escalabilidad de Redis y Memcached, <strong>Then</strong> deberán garantizar que la opción seleccionada pueda manejar un crecimiento significativo sin afectar el rendimiento.</li>
  <li><strong>Given</strong> que la seguridad es un factor crítico en la integración de caching, <strong>When</strong> se revisan las medidas de seguridad de Redis y Memcached (como la encriptación de datos), <strong>Then</strong> deberán confirmar que la solución de caching cumple con los requisitos de seguridad necesarios.</li>
  <li><strong>Given</strong> que las soluciones de caching deben ser eficientes en el uso de recursos, <strong>When</strong> se mide el consumo de CPU y memoria al implementar Redis o Memcached, <strong>Then</strong> deberán asegurar que la solución elegida no afecte negativamente los recursos de Autonexo.</li>
  <li><strong>Given</strong> que la alta disponibilidad es crucial para el sistema de caching, <strong>When</strong> se simulan fallos en Redis o Memcached, <strong>Then</strong> deberán verificar que la solución seleccionada pueda recuperarse correctamente sin perder datos importantes.</li>
</ul>
<h2>Spike 7: Evaluación de Herramientas de Seguridad para la Plataforma</h2>

<table border="1">
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>SP-07</td>
    <td>Security Team</td>
    <td>Alta</td>
    <td>Seguridad</td>
  </tr>
</table>

<h4>Descripción:</h4>
<p>Como equipo de seguridad, quiero investigar herramientas de seguridad como OWASP ZAP o Burp Suite para realizar pruebas de penetración y asegurarnos de que la plataforma esté segura.</p>

<h4>Criterios de Aceptación:</h4>
<ul>
  <li><strong>Given</strong> que el equipo ha considerado herramientas como OWASP ZAP y Burp Suite, <strong>When</strong> investiguen las características de cada una, <strong>Then</strong> deberán decidir cuál es la mejor herramienta para realizar pruebas de seguridad en Autonexo.</li>
  <li><strong>Given</strong> que el equipo ha implementado una prueba de seguridad con OWASP ZAP, <strong>When</strong> realicen un escaneo de vulnerabilidades, <strong>Then</strong> deberán identificar todas las posibles brechas de seguridad en el sistema.</li>
  <li><strong>Given</strong> que el equipo ha implementado Burp Suite para pruebas de seguridad, <strong>When</strong> realicen pruebas de penetración, <strong>Then</strong> deberán asegurarse de que la plataforma esté segura contra ataques comunes.</li>
  <li><strong>Given</strong> que OWASP ZAP y Burp Suite tienen interfaces y configuraciones distintas, <strong>When</strong> el equipo evalúa la facilidad de uso de ambas herramientas, <strong>Then</strong> deberán decidir cuál herramienta es más fácil de integrar y utilizar en el flujo de trabajo de Autonexo.</li>
  <li><strong>Given</strong> que el objetivo es detectar vulnerabilidades críticas en la plataforma, <strong>When</strong> el equipo prueba las capacidades de detección de vulnerabilidades de OWASP ZAP y Burp Suite, <strong>Then</strong> deberán asegurarse de que ambas herramientas detecten las vulnerabilidades clave en Autonexo.</li>
  <li><strong>Given</strong> que las configuraciones de seguridad son esenciales en las pruebas de penetración, <strong>When</strong> el equipo evalúa las configuraciones de seguridad de OWASP ZAP y Burp Suite, <strong>Then</strong> deberán determinar si las herramientas permiten una configuración detallada y personalizada según las necesidades de Autonexo.</li>
  <li><strong>Given</strong> que las pruebas de seguridad deben integrarse con el flujo de desarrollo de Autonexo, <strong>When</strong> el equipo evalúa cómo OWASP ZAP y Burp Suite se integran con las herramientas y procesos de desarrollo existentes, <strong>Then</strong> deberán garantizar que las herramientas se integren sin interrumpir el flujo de trabajo de desarrollo.</li>
  <li><strong>Given</strong> que los informes de seguridad son cruciales para la corrección de vulnerabilidades, <strong>When</strong> el equipo revisa los informes generados por OWASP ZAP y Burp Suite, <strong>Then</strong> deberán asegurarse de que los informes sean claros, detallados y proporcionen las recomendaciones necesarias para corregir las vulnerabilidades encontradas.</li>
</ul>

<h2>Spike 8: Investigación de Plataforma para Gestión de Suscripciones</h2>

<table border="1">
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>SP-08</td>
    <td>Developer</td>
    <td>Alta</td>
    <td>Suscripciones</td>
  </tr>
</table>

<h4>Descripción:</h4>
<p>Como equipo de desarrollo, quiero investigar plataformas como Recurly o Stripe Billing para gestionar suscripciones y automatizar el proceso de pagos recurrentes en la plataforma.</p>

<h4>Criterios de Aceptación:</h4>
<ul>
  <li><strong>Given</strong> que el equipo ha considerado plataformas como Recurly y Stripe Billing, <strong>When</strong> investiguen las funcionalidades y capacidades de cada plataforma, <strong>Then</strong> deberán seleccionar la plataforma más adecuada para gestionar las suscripciones de Autonexo.</li>
  <li><strong>Given</strong> que el equipo ha probado la implementación de Recurly con datos de prueba, <strong>When</strong> creen un ciclo de suscripción y realicen un pago de prueba, <strong>Then</strong> deberán verificar que la plataforma maneje correctamente los pagos recurrentes.</li>
  <li><strong>Given</strong> que el equipo ha probado Stripe Billing para gestionar suscripciones, <strong>When</strong> realicen una prueba de suscripción con Stripe Billing, <strong>Then</strong> deberán asegurarse de que la plataforma maneje correctamente los pagos recurrentes.</li>
  <li><strong>Given</strong> que ambas plataformas tienen estructuras de precios diferentes, <strong>When</strong> se comparen los costos de Recurly y Stripe Billing, <strong>Then</strong> deberán decidir cuál plataforma ofrece la mejor relación calidad-precio para Autonexo.</li>
  <li><strong>Given</strong> que la plataforma de suscripciones debe integrarse con el backend de Autonexo, <strong>When</strong> el equipo evalúa la facilidad de integración de Recurly y Stripe Billing con el backend (Spring Boot), <strong>Then</strong> deberán garantizar que ambas plataformas se integren de manera sencilla y eficiente.</li>
  <li><strong>Given</strong> que la seguridad es fundamental en los pagos recurrentes, <strong>When</strong> el equipo revise las medidas de seguridad de Recurly y Stripe Billing, <strong>Then</strong> deberán garantizar que ambas plataformas cumplan con los estándares de seguridad necesarios, como PCI-DSS.</li>
  <li><strong>Given</strong> que es necesario gestionar los datos de clientes y suscripciones, <strong>When</strong> se utilicen las herramientas de reportes de Recurly y Stripe Billing, <strong>Then</strong> deberán asegurarse de que las plataformas generen informes detallados y fáciles de usar sobre las suscripciones.</li>
</ul>
<h2>Spike 9: Investigación de API de Localización para Mejorar la Búsqueda de Mecánicos</h2>

<table border="1">
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>SP-09</td>
    <td>Developer</td>
    <td>Alta</td>
    <td>Localización</td>
  </tr>
</table>

<h4>Descripción:</h4>
<p>Como equipo de desarrollo, quiero investigar APIs de localización como Google Maps, Mapbox o Here para mejorar la búsqueda de mecánicos cercanos, ofreciendo una experiencia más eficiente y precisa a los conductores.</p>

<h4>Criterios de Aceptación:</h4>
<ul>
  <li><strong>Given</strong> que el equipo ha considerado APIs como Google Maps, Mapbox o Here, <strong>When</strong> investiguen las características y opciones de integración de cada API, <strong>Then</strong> deberán seleccionar la mejor API para la localización en Autonexo.</li>
  <li><strong>Given</strong> que el equipo ha implementado la API de Google Maps para la localización, <strong>When</strong> realicen pruebas de búsqueda de mecánicos cercanos, <strong>Then</strong> deberán asegurarse de que la función de localización sea precisa y eficiente.</li>
  <li><strong>Given</strong> que el equipo ha implementado la API de Mapbox para la localización, <strong>When</strong> realicen pruebas de búsqueda de mecánicos cercanos, <strong>Then</strong> deberán asegurarse de que la función de localización sea precisa y eficiente.</li>
  <li><strong>Given</strong> que el equipo ha implementado la API de Here para la localización, <strong>When</strong> realicen pruebas de búsqueda de mecánicos cercanos, <strong>Then</strong> deberán asegurarse de que la función de localización sea precisa y eficiente.</li>
  <li><strong>Given</strong> que cada API tiene diferentes modelos de precios, <strong>When</strong> comparen los costos de Google Maps, Mapbox y Here, <strong>Then</strong> deberán decidir cuál API ofrece la mejor relación calidad-precio para la plataforma.</li>
  <li><strong>Given</strong> que Google Maps, Mapbox y Here tienen implementaciones y configuraciones distintas, <strong>When</strong> el equipo evalúe la facilidad de integración de cada API con la plataforma Autonexo, <strong>Then</strong> deberán determinar cuál API es más sencilla de implementar y mantener.</li>
  <li><strong>Given</strong> que la plataforma Autonexo puede crecer en volumen de usuarios y mecánicos, <strong>When</strong> el equipo evalúe la escalabilidad de Google Maps, Mapbox y Here, <strong>Then</strong> deberán asegurarse de que todas las APIs puedan manejar un gran volumen de solicitudes sin afectar el rendimiento.</li>
  <li><strong>Given</strong> que la precisión es clave en la búsqueda de mecánicos cercanos, <strong>When</strong> el equipo pruebe las APIs de Google Maps, Mapbox y Here en diferentes ubicaciones, <strong>Then</strong> deberán asegurarse de que todas las APIs proporcionen ubicaciones precisas y fiables.</li>
  <li><strong>Given</strong> que las aplicaciones de Autonexo están disponibles en dispositivos móviles, <strong>When</strong> el equipo evalúe la compatibilidad de Google Maps, Mapbox y Here con dispositivos móviles (iOS/Android), <strong>Then</strong> deberán asegurarse de que todas las APIs funcionen correctamente en plataformas móviles.</li>
  <li><strong>Given</strong> que tanto Google Maps, Mapbox y Here ofrecen características adicionales (como rutas optimizadas, tráfico en tiempo real, etc.), <strong>When</strong> el equipo explore estas características, <strong>Then</strong> deberán decidir si alguna de estas funcionalidades adicionales es relevante y útil para la plataforma Autonexo.</li>
</ul>



### 2.4.2. Impact Mapping

<br>

<img alt="Journey-Map-José-Quispe" src="assets\chapter-II-assets\impact-mapping.png" />

[Ver mapa completo hecho en UxPressia guardado en Drive](https://drive.google.com/file/d/1v3L6OcPESk6r_FUhPRhijSQP3rokYtJJ/view?usp=sharing)

<br>

### 2.4.3. Product Backlog

<table border="1">
  <thead>
    <tr>
      <th>Orden</th>
      <th>User Story ID</th>
      <th>Título</th>
      <th>Story Points</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>US24</td>
      <td>Visualizar información y beneficios (Landing Page)</td>
      <td>2</td>
    </tr>
    <tr>
      <td>2</td>
      <td>US05</td>
      <td>Catálogo de servicios de taller</td>
      <td>5</td>
    </tr>
    <tr>
      <td>3</td>
      <td>US06</td>
      <td>Explorar catálogo y búsqueda</td>
      <td>5</td>
    </tr>
    <tr>
      <td>4</td>
      <td>US08</td>
      <td>Filtrar por servicio</td>
      <td>3</td>
    </tr>
    <tr>
      <td>5</td>
      <td>US09</td>
      <td>Recomendación por geolocalización</td>
      <td>5</td>
    </tr>
    <tr>
      <td>6</td>
      <td>US01</td>
      <td>Registro de vehículo</td>
      <td>3</td>
    </tr>
    <tr>
      <td>7</td>
      <td>US02</td>
      <td>Adjuntar historial inicial</td>
      <td>2</td>
    </tr>
    <tr>
      <td>8</td>
      <td>US03</td>
      <td>Visualizar historial de vehículo</td>
      <td>3</td>
    </tr>
    <tr>
      <td>9</td>
      <td>US12</td>
      <td>Sistema de mensajería</td>
      <td>5</td>
    </tr>
    <tr>
      <td>10</td>
      <td>US13</td>
      <td>Coordinación de citas de mantenimiento</td>
      <td>5</td>
    </tr>
    <tr>
      <td>11</td>
      <td>US14</td>
      <td>Notificaciones push</td>
      <td>3</td>
    </tr>
    <tr>
      <td>12</td>
      <td>US15</td>
      <td>Actualización de checklist en mantenimiento</td>
      <td>3</td>
    </tr>
    <tr>
      <td>13</td>
      <td>US16</td>
      <td>Creación de mantenimiento confirmado</td>
      <td>3</td>
    </tr>
    <tr>
      <td>14</td>
      <td>US17</td>
      <td>Visualización de mantenimientos pendientes</td>
      <td>3</td>
    </tr>
    <tr>
      <td>15</td>
      <td>US18</td>
      <td>Visualización de checklist en mantenimiento</td>
      <td>2</td>
    </tr>
    <tr>
      <td>16</td>
      <td>US19</td>
      <td>Finalización de mantenimiento</td>
      <td>3</td>
    </tr>
    <tr>
      <td>17</td>
      <td>US10</td>
      <td>Taller favorito</td>
      <td>2</td>
    </tr>
    <tr>
      <td>18</td>
      <td>US11</td>
      <td>Promociones de taller de confianza</td>
      <td>3</td>
    </tr>
    <tr>
      <td>19</td>
      <td>US07</td>
      <td>Cancelar reserva de mantenimiento</td>
      <td>3</td>
    </tr>
    <tr>
      <td>20</td>
      <td>US04</td>
      <td>Actualización automática del historial</td>
      <td>3</td>
    </tr>
    <tr>
      <td>21</td>
      <td>US25</td>
      <td>Registro de usuario (propietario o taller)</td>
      <td>3</td>
    </tr>
    <tr>
      <td>22</td>
      <td>US26</td>
      <td>Preguntas frecuentes y soporte</td>
      <td>2</td>
    </tr>
    <tr>
      <td>23</td>
      <td>US27</td>
      <td>Contacto y descarga de la app</td>
      <td>2</td>
    </tr>
    <tr>
      <td>24</td>
      <td>US20</td>
      <td>Calificación de taller</td>
      <td>2</td>
    </tr>
    <tr>
      <td>25</td>
      <td>US21</td>
      <td>Calificación de propietario</td>
      <td>2</td>
    </tr>
    <tr>
      <td>26</td>
      <td>US22</td>
      <td>Consulta de reputación de taller</td>
      <td>2</td>
    </tr>
    <tr>
      <td>27</td>
      <td>US23</td>
      <td>Consulta de reputación de propietario</td>
      <td>2</td>
    </tr>
    <tr>
      <td>28</td>
      <td>TS01</td>
      <td>Implementar endpoint para registrar y gestionar vehículos (/vehicles)</td>
      <td>5</td>
    </tr>
    <tr>
      <td>29</td>
      <td>TS02</td>
      <td>Implementar endpoint para adjuntar y consultar historial (/vehicles/{id}/history)</td>
      <td>5</td>
    </tr>
    <tr>
      <td>30</td>
      <td>TS03</td>
      <td>Implementar endpoint para catálogo de servicios de taller (/services)</td>
      <td>5</td>
    </tr>
    <tr>
      <td>31</td>
      <td>TS04</td>
      <td>Implementar endpoint para gestión de reservas de mantenimiento (/reservations)</td>
      <td>5</td>
    </tr>
    <tr>
      <td>32</td>
      <td>TS05</td>
      <td>Implementar endpoint para sistema de mensajería (/messages)</td>
      <td>5</td>
    </tr>
    <tr>
      <td>33</td>
      <td>TS06</td>
      <td>Implementar endpoint para calificaciones y reputación (/ratings)</td>
      <td>3</td>
    </tr>
    <tr>
      <td>34</td>
      <td>TS07</td>
      <td>Implementar endpoint para exploración y búsqueda de servicios (/services?filters=)</td>
      <td>5</td>
    </tr>
    <tr>
      <td>35</td>
      <td>TS08</td>
      <td>Implementar endpoint para filtros y geolocalización de talleres (/workshops?location=)</td>
      <td>5</td>
    </tr>
    <tr>
      <td>36</td>
      <td>TS09</td>
      <td>Implementar endpoint para gestión de favoritos (/favorites)</td>
      <td>3</td>
    </tr>
    <tr>
      <td>37</td>
      <td>TS10</td>
      <td>Implementar endpoint para promociones de talleres (/promotions)</td>
      <td>2</td>
    </tr>
    <tr>
      <td>38</td>
      <td>TS11</td>
      <td>Implementar endpoint para coordinación de citas (/appointments)</td>
      <td>5</td>
    </tr>
    <tr>
      <td>39</td>
      <td>TS12</td>
      <td>Implementar endpoint para notificaciones push (/notifications)</td>
      <td>3</td>
    </tr>
    <tr>
      <td>40</td>
      <td>TS13</td>
      <td>Implementar endpoint para gestión de mantenimientos (/maintenances)</td>
      <td>5</td>
    </tr>
    <tr>
      <td>41</td>
      <td>TS14</td>
      <td>Implementar endpoint para landing page y registro de usuarios (/users)</td>
      <td>3</td>
    </tr>
    <tr>
      <td>42</td>
      <td>TS15</td>
      <td>Implementar endpoint para soporte, FAQ y contacto (/faq, /support, /contact)</td>
      <td>2</td>
    </tr>
  </tbody>
</table>

## 2.5. Strategic-Level Domain-Driven Design
<br>

### 2.5.1. EventStorming
El objetivo de la sesión de EventStorming fue realizar una exploración amplia y colaborativa del dominio del problema de Autonexo. Mediante esta técnica buscamos representar de manera visual y comprensible los distintos eventos que ocurren dentro del flujo de interacción entre usuarios (propietarios de vehículos) y mecánicos, con el fin de identificar oportunidades de mejora, puntos críticos y posibles cambios de estado en el sistema.
<br>
- Step 1 – Unstructured Exploration: El equipo colocó en Miro todos los eventos relevantes sin ningún orden, con el fin de vaciar conocimiento y asegurar que ninguna parte del dominio quedara fuera.

<img alt="step1_UnstructuredExploration src="assets\chapter-II-assets\step1_UnsExp.png" />
<br>

- Step 2 – Timelines: Los eventos fueron organizados en una línea de tiempo, lo que permitió identificar la secuencia lógica de las acciones

<img alt="step2_Timelines" src="assets\chapter-II-assets\step2_Timelines.png" />
<br>


- Step 3 – Pain Points: Se marcaron las dificultades que enfrentan los usuarios, como la demora en la asignación de mecánicos o la falta de transparencia en los precios.

<img alt="step3_PaintPoints" src="assets\chapter-II-assets\step3_PaintPoints.png" />
<br>

- Step 4 – Pivotal Points: Finalmente, se destacaron los eventos clave que generan cambios de estado.
<br>

<img alt="step4_PivotalPoints" src="assets\chapter-II-assets\step4_PivotalPoints.png" />
<br>
<br>

Esta dinámica permitió al equipo obtener una visión compartida del proceso, detectar problemas reales y reconocer eventos centrales que posteriormente servirían para delimitar los bounded contexts.
<br>

#### 2.5.1.1 Candidate Context Discovery
El objetivo de la sesión de Candidate Context Discovery fue identificar y delimitar los bounded contexts del dominio a partir del EventStorming, con el fin de proponer una primera aproximación modular al sistema. Esto asegura que cada parte del dominio tenga responsabilidades claras, evitando la complejidad innecesaria y permitiendo un diseño más mantenible y escalable.
<br>

Se partió del resultado del EventStorming y se aplicó la técnica Look-for-pivotal-events, donde se tomaron como referencia los eventos clave mediante lineas secantes en los post-its (“Service request submitted”, “Offer accepted”, “Service completed”, etc) para determinar los límites naturales entre contextos.

<img alt="step4_PivotalPoints" src="assets\chapter-II-assets\step4_PivotalPoints.png" />

<br>

A partir de esto, se definieron los bounded contexts:
- IAM Context: Abarca la lógica de registro/autenticación de usuario
- Subscription context: Hace referencia al sistmea de suscripción para acceder a las funcionalidades, mediante el cual la aplicación generará ingresos.
- Workshop Context: Engloba la lógica de los mécnicos dentro de las talleres.
- Trust&Reputation: Hace referncia al sistmea de calificación a los usuarios.
- Vehicle&Maintenance: Engloba la lógica acerca de los vehículos y sus mantenimientos.
- Matching&Booking Context: Engloba el proceso de búsqueda, booking y ejecución del servicio.
- Notifications: Hace referencia a las notificaciones del sistema.

#### 2.5.1.2 Domain Message Flows Modeling
<br>

#### 2.5.1.3 Bounded Context Canvases
<br>

### 2.5.2. Context Mapping
<br>

El Context Mapping en Domain-Driven Design (DDD) representa explícitamente cómo interactúan los bounded contexts entre sí, definiendo contratos, direcciones de influencia (upstream/downstream) y patrones de integración. Este mapeo permite identificar qué contextos requieren estandarización, cuáles deben protegerse mediante traducción (Anti-Corruption Layer), y dónde preservar independencia para asegurar que cada contexto pueda evolucionar de forma predecible y segura.

En Autonexo, los contexts se organizaron considerando los siguientes patrones:

**Context Map Patterns**

**1. Open Host Service (OHS)**
Un contexto upstream expone servicios mediante contratos estables (APIs, endpoints o eventos), de forma que múltiples consumidores downstream pueden integrarse sin conocer su modelo interno.

Uso en Autonexo:
El IAM Context actúa como OHS, proveyendo autenticación, autorización y gestión de roles. Todos los contexts (Matching & Booking, Vehicle & Maintenance, Workshop, Subscription, Trust & Reputation, Notification) consumen estos servicios para validar identidad y permisos.

<img alt="OHS" src="assets\chapter-II-assets\ctxMapPatt_OHS.png" />

**2. Customer/Supplier (C/S)**
Relación proveedor–cliente entre contextos. El Supplier prioriza parte de su backlog en función de las necesidades del Customer, adaptando sus capacidades para habilitar los objetivos del cliente.

Uso en Autonexo:
Matching & Booking (Customer) – Workshop (Supplier): el Workshop Context provee disponibilidad de agenda y catálogo de servicios, mientras el Booking Context depende de esos datos para confirmar reservas de manera confiable.

Subscription (Customer) – Workshop (Supplier): las suscripciones otorgan beneficios como prioridad de agenda o descuentos, los cuales dependen de la configuración y condiciones publicadas por los talleres en el Workshop Context.

<img alt="Customer/Supplier" src="assets\chapter-II-assets\ctxMapPatt_CS.png" />

**3. Shared Kernel (SK)**
Dos contexts comparten un submodelo común, usualmente entidades o identificadores críticos, que deben mantenerse consistentes para evitar duplicación y divergencia.

Uso en Autonexo:
El Matching & Booking Context y el Vehicle & Maintenance Context comparten identificadores de vehículos y mantenimientos confirmados, de modo que ambos contexts operan sobre la misma referencia, garantizando consistencia y evitando duplicación de datos.

<img alt="ctxMapPatt_SharedKernel" src="assets\chapter-II-assets\ctxMapPatt_SK.png" />

**4. Conformist (CF)**
El downstream adopta el modelo del upstream sin traducción, lo que facilita una integración rápida, pero sacrifica independencia, ya que hereda sus decisiones de diseño.

Uso en Autonexo:
El Subscription Context se adapta directamente al modelo de Matching and Booking Context (ejemplo: estados de reserva como activa, cancelada, finalizada) sin redefinirlos ni transformarlos. Esto agiliza la integración, pero obliga a Subscription a depender de los cambios en Booking.

<img alt="ctxMapPatt_Conformist" src="assets\chapter-II-assets\ctxMapPatt_CF.png" />

**5. Publisher/Subscriber (Event-Driven)**
Un contexto upstream publica eventos que otros contextos downstream consumen de manera asíncrona, desacoplando la integración. Esto permite que el publisher no dependa de los consumidores y que múltiples contexts reaccionen a un mismo evento.

Uso en Autonexo:
El Notification Context actúa como subscriber de eventos generados por otros contexts:
-Matching and Booking Context → publica el evento Reserva Creada.
-Vehicle and Maintenance Context → publica el evento Mantenimiento Finalizado.
-Trust and Reputation Context → publica el evento Calificación Registrada.

El Notification Context escucha estos eventos y envía notificaciones push a los usuarios afectados.

<img alt="ctxMapPatt_Publisher/Subscriber" src="assets\chapter-II-assets\ctxMapPatt_PS.png" />


### 2.5.3. Software Architecture
En esta sección se expone la arquitectura de software de la solución Red Carga, aplicando el enfoque del Modelo C4. Se incluyen los diagramas de Contexto, Contenedores y Despliegue, los cuales permiten comprender el sistema desde una visión general hasta su implementación en un entorno productivo. Cada nivel representa a los actores involucrados, las tecnologías clave y las interacciones con los servicios externos que forman parte del alcance del proyecto.
<br>

#### 2.5.3.1 Software Architecture Context Level Diagrams
El siguiente diagrama muestra de manera general Autonexo conectado con los sistemas externos y los usuarios que intervienen
<br>
<img alt="Context-Diagram" src="assets\chapter-II-assets\structurizr-101398-SystemContext-001.png" />

#### 2.5.3.2 Software Architecture Container Level Diagrams
El diagrama C2 profundiza en el sistema y representa la arquitectura general del software, destacando las principales tecnologías empleadas y la manera en que estas se interconectan.
<br>
<img alt="Container-Diagram" src="assets\chapter-II-assets\c4\structurizr-101398-Container-001.png" />

#### 2.5.3.3 Software Architecture Deployment Diagrams
El siguiente diagrama muestra los contenedores del sistema Autonexo desplegados en el entorno de desarrollo y producción. Además, se muestran los servicios externos, la base de datos y el storage.
<br>
- Sistema en entorno de desarrollo:
<br>
<img alt="Deployment-Diagram-1" src="assets\chapter-II-assets\c4\structurizr-101398-SystemContext-001.png" />

<br>

- Sistema en entorno de producción:
<br>
<img alt="Deployment-Diagram-2" src="assets\chapter-II-assets\c4\structurizr-101398-Deployment-002.png" />

## 2.6 Tactical-Level Domain-Driven Design
<br>

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

#### 2.6.1.5 Bounded Context Software Architecture Component Level Diagrams
<br>

<img alt="Component-IAM" src="assets\chapter-II-assets\components\structurizr-101398-Component-001.png" />

#### 2.6.1.6 Bounded Context Software Architecture Code Level Diagrams
<br>

##### 2.6.1.6.1 Bounded Context Domain Layer Class Diagrams
<br>
<img alt="Class-IAM" src="assets\chapter-II-assets\bc\class-vehicle.png" />

##### 2.6.1.6.2 Bounded Context Database Design Diagram
<br>
<img alt="Database-IAM" src="assets\chapter-II-assets\bc\db-vehicle.png" />

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

#### 2.6.2.5 Bounded Context Software Architecture Component Level Diagrams
<br>

<img alt="Component-Workshops" src="assets\chapter-II-assets\components\structurizr-101398-Component-002.png" />

#### 2.6.2.6 Bounded Context Software Architecture Code Level Diagrams
<br>

##### 2.6.2.6.1 Bounded Context Domain Layer Class Diagrams
<br>
<img alt="Class-Workshop" src="assets\chapter-II-assets\bc\class-trusting.png" />

##### 2.6.2.6.2 Bounded Context Database Design Diagram
<br>
<img alt="Database-Workshop" src="assets\chapter-II-assets\bc\db-trusting.png" />

### **2.6.3. Bounded Context: Matching&Booking**

#### **2.6.3.1. Domain Layer**

Este bounded context cubre desde la solicitud de servicio hasta la creación/confirmación del booking, la gestión de ofertas y reprogramaciones, y la apertura de la service order para el handover hacia Vehicle&Maintenance.  
---

### **Aggregates**

- **ServiceRequest**  
  **Propósito:** Intención del propietario de recibir un servicio (tipo, ventana deseada, ubicación).  
  **Atributos:**  
  - serviceRequestId: UUID  
  - ownerId: UUID  
  - vehicleId: UUID  
  - serviceType: ServiceType  
  - preferredWindow: TimeRange  
  - location: GeoLocation  
  - status: ServiceRequestStatus (Open, Matching, Offered, Archived, Cancelled)  
  **Métodos:**  
  - startMatching()  
  - archive(reason: string)  
  - cancel(reason: string)  
  **Relaciones:**  
  - 1 ⟶ * con Offer  
  - 1 ⟶ 0..1 con Booking

- **Offer**  
  **Propósito:** Propuesta desde un workshop (referencia externa por workshopId) para atender el ServiceRequest.  
  **Atributos:**  
  - offerId: UUID  
  - serviceRequestId: UUID  
  - workshopId: UUID  
  - proposedSlot: TimeRange  
  - price: Money  
  - terms: Terms  
  - status: OfferStatus (Submitted, Withdrawn, Accepted, Rejected, Expired)  
  **Métodos:**  
  - withdraw(reason: string)  
  - accept()  
  - reject()  
  **Relaciones:**  
  - * ⟶ 1 con ServiceRequest  
  - 0..1 ⟶ 1 con Booking

- **Booking**  
  **Propósito:** Reserva formal entre owner y workshop basada en una Offer aceptada.  
  **Atributos:**  
  - bookingId: UUID  
  - serviceRequestId: UUID  
  - offerId: UUID  
  - workshopId: UUID  
  - vehicleId: UUID  
  - slot: TimeRange  
  - status: BookingStatus (Created, Confirmed, RescheduleRequested, Rescheduled, Cancelled)  
  - cancellationPolicy: CancellationPolicy  
  - createdAt: DateTime  
  **Métodos:**  
  - confirm()  
  - requestReschedule(newSlot: TimeRange, reason: string)  
  - reschedule(approvedSlot: TimeRange)  
  - cancel(reason: string)  
  **Relaciones:**  
  - 1 ⟶ 1 con Offer  
  - 1 ⟶ 1 con ServiceRequest  
  - 1 ⟶ 0..1 con ServiceOrder

- **ServiceOrder**  
  **Propósito:** Orden operativa creada al confirmar un Booking; artefacto de handover hacia Vehicle&Maintenance.  
  **Atributos:**  
  - serviceOrderId: UUID  
  - bookingId: UUID  
  - workshopId: UUID  
  - vehicleId: UUID  
  - scheduledSlot: TimeRange  
  - status: ServiceOrderStatus (Opened, Closed, Cancelled)  
  - openedAt: DateTime  
  **Métodos:**  
  - open()  
  - close()  
  - cancel(reason: string)  
  **Relaciones:**  
  - 1 ⟶ 1 con Booking

---

### **Entities**

- **RescheduleRequest**  
  **Propósito:** Solicitud de reprogramación sobre un Booking existente.  
  **Atributos:**  
  - rescheduleRequestId: UUID  
  - bookingId: UUID  
  - requestedSlot: TimeRange  
  - reason: string  
  - status: RescheduleStatus (Requested, Approved, Declined)  
  **Métodos:**  
  - approve(approvedSlot: TimeRange)  
  - decline(reason: string)  
  **Relaciones:**  
  - * ⟶ 1 con Booking

---

### **Value Objects**

- **TimeRange:** start: DateTime, end: DateTime  
- **Money:** amount: decimal, currency: string  
- **GeoLocation:** lat: decimal, lon: decimal  
- **Terms:** summary: string, detailsUrl: string?  
- **CancellationPolicy:** freeUntilHours: int, penaltyAfter: Money  
- **ServiceType:** enum (Inspection, OilChange, Tires, Brakes, Bodywork, Other)

---

### **Events (Domain Events)**

- ServiceRequestSubmittedEvent(serviceRequestId, ownerId, vehicleId, serviceType, occurredAt)  
- MatchingProcessStartedEvent(serviceRequestId, occurredAt)  
- WorkshopRecommendationsGeneratedEvent(serviceRequestId, workshopIds, occurredAt)  
- OfferSubmittedEvent(offerId, serviceRequestId, workshopId, occurredAt)  
- OfferWithdrawnEvent(offerId, occurredAt)  
- OfferAcceptedEvent(offerId, serviceRequestId, occurredAt)  
- BookingCreatedEvent(bookingId, serviceRequestId, offerId, occurredAt)  
- BookingConfirmedEvent(bookingId, occurredAt)  
- BookingRescheduleRequestedEvent(bookingId, rescheduleRequestId, requestedSlot, occurredAt)  
- BookingRescheduledEvent(bookingId, newSlot, occurredAt)  
- BookingCancelledEvent(bookingId, reason, occurredAt)  
- ServiceOrderOpenedEvent(serviceOrderId, bookingId, occurredAt)  
- ServiceOrderClosedEvent(serviceOrderId, bookingId, occurredAt)  
- ServiceRequestArchivedEvent(serviceRequestId, occurredAt)

---

### **Services (Domain Interfaces)**

**Nota:** Aquí solo se definen interfaces. **Sus implementaciones que interactúan con otros BCs se ubican en Application Layer** mediante ACL/adapters.

- **MatchingEngine**  
  Métodos:  
  - findCandidates(serviceRequest: ServiceRequest) → List<UUID>  (workshopId)

- **AvailabilityService**  
  Métodos:  
  - isAvailable(workshopId: UUID, slot: TimeRange) → bool  
  - suggestSlots(workshopId: UUID, constraints: TimeRange) → List<TimeRange>

- **PricingService**  
  Métodos:  
  - quote(serviceType: ServiceType, workshopId: UUID) → Money

- **OfferPolicy**  
  Métodos:  
  - canSubmit(workshopId: UUID, serviceRequestId: UUID) → bool  
  - canAccept(offerId: UUID) → bool

- **BookingPolicy**  
  Métodos:  
  - canConfirm(bookingId: UUID) → bool  
  - canCancel(bookingId: UUID, when: DateTime) → bool

- **ScheduleAllocator**  
  Métodos:  
  - reserve(workshopId: UUID, slot: TimeRange) → bool  
  - release(workshopId: UUID, slot: TimeRange)

---

#### **2.6.3.2. Interface Layer**

- **Controllers:** ServiceRequestController, MatchingController, OfferController, BookingController, ServiceOrderController, RescheduleController  
- **Resources:**  
  - SubmitServiceRequestResource { ownerId, vehicleId, serviceType, preferredWindow, location }  
  - OfferResource { offerId, serviceRequestId, workshopId, proposedSlot, price, status }  
  - BookingResource { bookingId, serviceRequestId, offerId, workshopId, vehicleId, slot, status, createdAt }  
  - RescheduleRequestResource { rescheduleRequestId, bookingId, requestedSlot, reason, status }  
  - ServiceOrderResource { serviceOrderId, bookingId, workshopId, vehicleId, scheduledSlot, status, openedAt }  
- **Assemblers:** ServiceRequestAssembler, OfferAssembler, BookingAssembler, ServiceOrderAssembler, RescheduleAssembler

---

#### **2.6.3.3. Application Layer**

**Aquí se implementan las integraciones con otros bounded contexts (ACL) y los servicios concretos.**

- **Command Services:**  
  - ServiceRequestCommandService  
  - OfferCommandService  
  - BookingCommandService  
  - RescheduleCommandService  
  - ServiceOrderCommandService

- **Query Services:**  
  - ServiceRequestQueryService  
  - OfferQueryService  
  - BookingQueryService  
  - ServiceOrderQueryService

- **Event Handlers:**  
  - OnOfferAccepted → crea Booking y emite BookingCreatedEvent  
  - OnBookingConfirmed → usa ScheduleAllocator (ACL) para reservar slot y emite ServiceOrderOpenedEvent  
  - OnBookingCancelled → usa ScheduleAllocator (ACL) para liberar slot; puede emitir ServiceOrderClosedEvent  
  - OnWorkshopProjectionUpdated (evento externo proyectado) → ajusta sugerencias de Matching

- **ACL Implementations (implementaciones concretas de las interfaces del Domain Layer):**  
  - WorkshopCalendarAclAvailabilityService (implementa AvailabilityService)  
  - WorkshopCalendarAclScheduleAllocator (implementa ScheduleAllocator)  
  - WorkshopPricingAcl (implementa PricingService)  
  - PaymentsAcl (si BookingPolicy depende de pago)  
  - IdentityAcl, NotificationsAcl  
  - TrustingReputationAcl (dispara invitación a calificar tras cierre)

- **Outbound Services:**  
  - DomainEventPublisher  
  - BookingNotificationSender

---

#### **2.6.3.4. Infrastructure Layer**

- **Repositories (implementaciones):**  
  - ServiceRequestRepository : IServiceRequestRepository  
  - OfferRepository : IOfferRepository  
  - BookingRepository : IBookingRepository  
  - ServiceOrderRepository : IServiceOrderRepository

- **External Services Adapters (utilizados por la Application Layer/ACL):**  
  - WorkshopCalendarAdapter (conecta con Workshop BC)  
  - PaymentGatewayAdapter  
  - MessageBrokerPublisher  
  - NotificationAdapter

---

#### 2.6.3.5 Bounded Context Software Architecture Component Level Diagrams
<br>
<img alt="Component-Vehicle-Maintenance" src="assets\chapter-II-assets\components\structurizr-101398-Component-003.png"/>

#### 2.6.3.6 Bounded Context Software Architecture Code Level Diagrams
<br>

##### 2.6.3.6.1 Bounded Context Domain Layer Class Diagrams
<br>
<img alt="Class-Vehicle" src="assets\chapter-II-assets\bc/class-matching.png" />

##### 2.6.3.6.2 Bounded Context Database Design Diagram
<br>
<img alt="Database-Vehicle" src="assets\chapter-II-assets\bc\db-matching.png" />

### **2.6.4. Bounded Context: Workshop**

#### **2.6.4.1. Domain Layer**

Este bounded context cubre la **gestión integral de los talleres (workshops)**: identidad, catálogo de servicios, disponibilidad operativa y personal técnico.  
Su rol es mantener la información canónica del taller y exponerla a otros bounded contexts como Matching&Booking (para reservas) y Trusting&Reputation (para proyecciones de reputación).  
No ejecuta procesos de matching, booking ni reputación, pero **publica eventos** que permiten integraciones.

---

### **Aggregates**

- **Workshop**  
  **Propósito:** Entidad raíz que representa un taller registrado en la plataforma.  
  **Atributos:**  
  - workshopId: UUID  
  - legalName: string  
  - tradeName: string  
  - taxId: string  
  - status: WorkshopStatus (Active, Suspended, Deactivated)  
  - contacts: List<Contact>  
  - addresses: List<Address>  
  - certifications: List<Certification>  
  - operatingPolicy: OperatingPolicy  
  - capabilities: Capabilities  
  - services: List<WorkshopService>  
  **Métodos:**  
  - amendInformation(delta: WorkshopDelta)  
  - addService(service: WorkshopService)  
  - removeService(serviceId: UUID)  
  - setCapabilities(c: Capabilities)  
  - activate() / suspend(reason) / deactivate(reason)  
  **Relaciones:**  
  - 1 ⟶ * con WorkshopService  
  - 1 ⟶ 1 con WorkshopSchedule

- **WorkshopSchedule**  
  **Propósito:** Calendario operativo del taller, con reglas de disponibilidad y excepciones.  
  **Atributos:**  
  - workshopId: UUID  
  - businessHours: List<BusinessWindow>  
  - exceptions: List<ExceptionWindow>  
  - timezone: string  
  **Métodos:**  
  - updateBusinessHours(windows: List<BusinessWindow>)  
  - addException(window: ExceptionWindow)  
  - proposeSlots(constraints: SlotConstraints) → List<AvailabilitySlot>  
  **Relaciones:**  
  - 1 ⟶ * con AvailabilitySlot

---

##### **Entities**

- **Mechanic**  
  **Propósito:** Representa un técnico/mecánico asociado al taller.  
  **Atributos:**  
  - mechanicId: UUID  
  - fullName: string  
  - skills: List<Skill>  
  - certifications: List<Certification>  
  - active: bool  
  **Métodos:**  
  - assignSkill(skill: Skill)  
  - revokeSkill(skill: Skill)

- **WorkshopService**  
  **Propósito:** Define un servicio que el taller ofrece a los clientes.  
  **Atributos:**  
  - serviceId: UUID  
  - serviceType: ServiceType  
  - stdDuration: Duration  
  - basePrice: Money  
  - requirements: List<Requirement>  
  - active: bool  
  **Métodos:**  
  - changePrice(newPrice: Money)  
  - activate() / deactivate()

---

##### **Value Objects**

- **Contact** – tipo (Phone, Email, WhatsApp) y valor.  
- **Address** – line1, city, region, postalCode, country.  
- **GeoPoint** – latitud, longitud.  
- **Certification** – código, entidad emisora, vigencia.  
- **OperatingPolicy** – políticas de operación (cancelación, leadTime, etc.).  
- **Capabilities** – marcas, tipos de vehículo, equipamiento, capacidad máxima concurrente.  
- **Equipment** – nombre del equipo, servicios para los que aplica.  
- **AvailabilitySlot** – slotId, start, end, state (Free, Blocked, Unavailable), reason.  
- **BusinessWindow** – dayOfWeek, openTime, closeTime.  
- **ExceptionWindow** – start, end, reason.  

---

##### **Events (Domain Events)**

- WorkshopRegisteredEvent(workshopId, occurredAt)  
  **Propósito:** Se registró un nuevo taller en la plataforma.  
- WorkshopInformationAmendedEvent(workshopId, delta, occurredAt)  
  **Propósito:** Se modificó la información del taller.  
- WorkshopScheduleUpdatedEvent(workshopId, occurredAt)  
  **Propósito:** Se actualizó el calendario operativo.  
- WorkshopAvailabilityBlockedEvent(workshopId, slotId, occurredAt)  
  **Propósito:** Un slot quedó bloqueado (ej. por booking confirmado).  
- WorkshopAvailabilityReleasedEvent(workshopId, slotId, occurredAt)  
  **Propósito:** Un slot bloqueado fue liberado.  
- MechanicAssignedEvent(workshopId, mechanicId, occurredAt)  
  **Propósito:** Se asignó un mecánico al taller.  
- MechanicUnassignedEvent(workshopId, mechanicId, occurredAt)  
  **Propósito:** Se desasignó un mecánico.  
- WorkshopDeactivatedEvent(workshopId, occurredAt)  
  **Propósito:** El taller quedó inactivo.  

---

##### **Services (Domain Interfaces)**

- **ScheduleService**  
  Métodos:  
  - isAvailable(workshopId: UUID, slot: TimeRange) → bool  
  - reserveSlot(workshopId: UUID, slot: TimeRange)  
  - releaseSlot(workshopId: UUID, slot: TimeRange)  
  **Propósito:** Gestionar disponibilidad del calendario de talleres.  

- **WorkshopPolicy**  
  Métodos:  
  - canActivate(workshopId: UUID) → bool  
  - canAssignMechanic(workshopId: UUID, mechanicId: UUID) → bool  
  **Propósito:** Validar reglas de negocio específicas de talleres.  

---

#### **2.6.4.2. Interface Layer**

Capa de exposición de APIs y DTOs para integración con otros contexts.  

- **Controllers**: WorkshopController, ScheduleController, MechanicController.  
- **Resources**:  
  - WorkshopResource { workshopId, legalName, status, services, capabilities }  
  - WorkshopScheduleResource { workshopId, businessHours, exceptions }  
  - MechanicResource { mechanicId, fullName, skills, active }  
  - WorkshopServiceResource { serviceId, serviceType, stdDuration, basePrice, active }  
- **Assemblers**: WorkshopAssembler, ScheduleAssembler, MechanicAssembler, ServiceAssembler.  

---

#### **2.6.4.3. Application Layer**

Implementa los casos de uso del negocio y la orquestación con otros contexts.  

- **Command Services**: WorkshopCommandService, ScheduleCommandService, MechanicCommandService.  
- **Query Services**: WorkshopQueryService, ScheduleQueryService.  
- **Event Handlers**:  
  - OnBookingConfirmed → bloquea slot (ScheduleService).  
  - OnBookingCancelled → libera slot.  
  - OnServiceOrderClosed → libera slot.  
  - OnReviewSubmitted (Trusting&Reputation) → actualiza proyección de reputación.  
- **ACLs / Adaptadores**:  
  - MatchingAcl (exposición de servicios y disponibilidad hacia Matching&Booking).  
  - TrustingReputationAcl (publica información de talleres hacia Trusting&Reputation).  

---

#### **2.6.4.4. Infrastructure Layer**

Implementaciones de persistencia y adaptadores externos.  

- **Repositories**:  
  - WorkshopRepository : IWorkshopRepository  
  - ScheduleRepository : IScheduleRepository  
  - MechanicRepository : IMechanicRepository  
- **External Adapters**:  
  - ExternalCertificationAdapter (validación de certificaciones)  
  - MessageBrokerPublisher (publicación de eventos a otros BCs)  

---

#### 2.6.4.5 Bounded Context Software Architecture Component Level Diagrams
<br>

<img alt="Component-Matching-Booking" src="assets\chapter-II-assets\components\structurizr-101398-Component-004.png" />

#### 2.6.4.6 Bounded Context Software Architecture Code Level Diagrams
<br>

##### 2.6.4.6.1 Bounded Context Domain Layer Class Diagrams
<br>
<img alt="Class-Matching" src="assets\chapter-II-assets\bc\class-workshop.png" />

##### 2.6.4.6.2 Bounded Context Database Design Diagram
<br>
<img alt="Database-Matching" src="assets\chapter-II-assets\bc\db-workshop.png" />

### **2.6.5. Bounded Context: Payment**

#### **2.6.5.1. Domain Layer**

Este bounded context cubre la **gestión de suscripciones a la plataforma**, incluyendo la activación, renovación, cancelación y facturación asociada.  
No gestiona pagos directos entre propietarios y talleres. Su alcance se limita a planes de suscripción de los distintos actores (owners, workshops, administradores).

---

### **Aggregates**

- **Subscription**  
  **Propósito:** Representa una suscripción activa en la plataforma.  
  **Atributos:**  
  - subscriptionId: UUID  
  - subscriberId: UUID (puede ser ownerId o workshopId)  
  - planId: UUID  
  - status: SubscriptionStatus (Active, Suspended, Cancelled, Expired)  
  - startDate: DateTime  
  - endDate: DateTime  
  - renewalDate: DateTime  
  - paymentMethod: PaymentMethod  
  **Métodos:**  
  - activate(planId, paymentMethod)  
  - renew()  
  - cancel(reason: string)  
  - suspend(reason: string)  
  - expire()  
  **Relaciones:**  
  - 1 ⟶ 1 con Plan

- **Invoice**  
  **Propósito:** Documento de facturación generado en cada ciclo de suscripción.  
  **Atributos:**  
  - invoiceId: UUID  
  - subscriptionId: UUID  
  - amount: Money  
  - periodStart: DateTime  
  - periodEnd: DateTime  
  - issuedAt: DateTime  
  - status: InvoiceStatus (Issued, Paid, Failed)  
  **Métodos:**  
  - markPaid()  
  - markFailed(reason: string)  

---

##### **Entities**

- **Plan**  
  **Propósito:** Define las características de un plan de suscripción.  
  **Atributos:**  
  - planId: UUID  
  - name: string  
  - description: string  
  - price: Money  
  - duration: Duration (ej. mensual, anual)  
  - features: List<Feature>  
  **Métodos:**  
  - updateDetails(name, description, price, duration, features)  

---

##### **Value Objects**

- **Money** – amount, currency.  
- **PaymentMethod** – tipo (Card, PayPal, Transfer), tokenizado.  
- **Feature** – nombre, descripción.  

---

##### **Events (Domain Events)**

- SubscriptionActivatedEvent(subscriptionId, subscriberId, planId, occurredAt)  
  **Propósito:** Se activó una nueva suscripción.  
- SubscriptionRenewedEvent(subscriptionId, planId, renewalDate, occurredAt)  
  **Propósito:** Se renovó una suscripción existente.  
- SubscriptionCancelledEvent(subscriptionId, reason, occurredAt)  
  **Propósito:** Una suscripción fue cancelada.  
- SubscriptionSuspendedEvent(subscriptionId, reason, occurredAt)  
  **Propósito:** La suscripción fue suspendida por incumplimiento o fallo de pago.  
- SubscriptionExpiredEvent(subscriptionId, occurredAt)  
  **Propósito:** La suscripción llegó a su fin y no fue renovada.  
- InvoiceIssuedEvent(invoiceId, subscriptionId, amount, occurredAt)  
  **Propósito:** Se generó una factura.  
- InvoicePaidEvent(invoiceId, occurredAt)  
  **Propósito:** Una factura fue pagada correctamente.  
- InvoiceFailedEvent(invoiceId, reason, occurredAt)  
  **Propósito:** Falló el cobro de la factura.  

---

##### **Services (Domain Interfaces)**

- **BillingService**  
  Métodos:  
  - generateInvoice(subscriptionId: UUID) → Invoice  
  - charge(invoiceId: UUID, paymentMethod: PaymentMethod) → bool  
  **Propósito:** Gestiona la facturación y cobro de suscripciones.  

- **SubscriptionPolicy**  
  Métodos:  
  - canRenew(subscriptionId: UUID) → bool  
  - canCancel(subscriptionId: UUID) → bool  
  **Propósito:** Define reglas de negocio sobre renovación y cancelación.  

---

#### **2.6.5.2. Interface Layer**

Expone endpoints REST/GraphQL para gestión de suscripciones.  

- **Controllers:** SubscriptionController, BillingController  
- **Resources:**  
  - SubscriptionResource { subscriptionId, subscriberId, planId, status, startDate, endDate, renewalDate }  
  - InvoiceResource { invoiceId, subscriptionId, amount, periodStart, periodEnd, status }  
  - PlanResource { planId, name, description, price, duration, features }  
- **Assemblers:** SubscriptionAssembler, InvoiceAssembler, PlanAssembler  

---

#### **2.6.5.3. Application Layer**

- **Command Services:**  
  - SubscriptionCommandService  
  - BillingCommandService  

- **Query Services:**  
  - SubscriptionQueryService  
  - InvoiceQueryService  
  - PlanQueryService  

- **Event Handlers:**  
  - OnInvoicePaid → renueva suscripción si aplica.  
  - OnInvoiceFailed → suspende suscripción.  
  - OnSubscriptionExpired → genera evento para notificar al usuario.  

- **ACLs:**  
  - ExternalPaymentGatewayAcl (integra con proveedor de pagos externo).  

---

#### **2.6.5.4. Infrastructure Layer**

Implementaciones de repositorios y adaptadores externos.  

- **Repositories:**  
  - SubscriptionRepository : ISubscriptionRepository  
  - InvoiceRepository : IInvoiceRepository  
  - PlanRepository : IPlanRepository  

- **External Adapters:**  
  - PaymentGatewayAdapter (Stripe/PayPal/etc.)  
  - MessageBrokerPublisher (publicación de eventos a otros BCs)  

---

#### 2.6.5.5 Bounded Context Software Architecture Component Level Diagrams
<br>

<img alt="Component-Trust" src="assets\chapter-II-assets\components\structurizr-101398-Component-005.png" />

#### 2.6.5.6 Bounded Context Software Architecture Code Level Diagrams
<br>

##### 2.6.5.6.1 Bounded Context Domain Layer Class Diagrams
<br>
<img alt="Class-trusting" src="assets\chapter-II-assets\bc\class-payment.png" />

##### 2.6.5.6.2 Bounded Context Database Design Diagram
<br>
<img alt="Database-trusting" src="assets\chapter-II-assets\bc\db-payment.png" />

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

#### 2.6.6.5 Bounded Context Software Architecture Component Level Diagrams
<br>

<img alt="Component-Suscription" src="assets\chapter-II-assets\components\structurizr-101398-Component-006.png" />

#### 2.6.6.6 Bounded Context Software Architecture Code Level Diagrams
<br>

##### 2.6.6.6.1 Bounded Context Domain Layer Class Diagrams
<br>
<img alt="Class-payment" src="assets\chapter-II-assets\bc\class-iam.png" />

##### 2.6.6.6.2 Bounded Context Database Design Diagram
<br>
<img alt="Database-trusting" src="assets\chapter-II-assets\bc\db-iam.png" />

### **2.6.7. Bounded Context: Notifications**

#### **2.6.7.1. Domain Layer**

Este bounded context gestiona la orquestación y entrega de notificaciones en tres canales: **Push, Email y SMS**.  
Soporta mensajes transaccionales  y mensajes programados
No incorpora lógica de negocio de otros BCs; consume sus eventos y aplica plantillas, preferencias y políticas de envío.
---

### **Aggregates**

- **Notification**  
  **Propósito:** Representa una notificación a uno o más destinatarios, con plantillas y rutas por canal.  
  **Atributos:**  
  - notificationId: UUID  
  - correlationId: string  
  - type: NotificationType (Transactional, Security, Reminder)  
  - recipients: List<UserId>  
  - templateId: UUID  
  - locale: string  
  - payload: Map<string,string>  
  - channelPlan: List<ChannelRoute>  
  - scheduledAt: DateTime?  
  - priority: Priority (High, Normal, Low)  
  - status: NotificationStatus (Pending, Scheduled, Sending, Sent, Failed, Cancelled)  
  **Métodos:**  
  - schedule(at: DateTime)  
  - send()  
  - cancel(reason: string)  
  - recordAttempt(result: DeliveryResult)

- **Template**  
  **Propósito:** Contenido parametrizable por **canal** e **idioma**.  
  **Atributos:**  
  - templateId: UUID  
  - key: string (ej. booking.confirmed)  
  - version: int  
  - channels: Map<Channel, ChannelTemplate>  
  - variables: List<VariableSpec>  
  - defaultLocale: string  
  **Métodos:**  
  - render(channel: Channel, locale: string, payload: Map) → RenderedMessage  
  - newVersion(changes)

---

### **Entities**

- **DeliveryAttempt**  
  **Propósito:** Trazabilidad por canal/proveedor.  
  **Atributos:**  
  - attemptId: UUID  
  - notificationId: UUID  
  - channel: Channel (Email, Push, SMS)  
  - provider: string  
  - requestedAt: DateTime  
  - status: AttemptStatus (Queued, Sent, Delivered, Opened, Clicked, Bounced, Failed)  
  - error?: string  
  **Métodos:**  
  - markDelivered()/markOpened()/markClicked(url)  
  - markBounced(reason)/markFailed(reason)

- **Preference**  
  **Propósito:** Preferencias por usuario y por tipo/canal.  
  **Atributos:**  
  - preferenceId: UUID  
  - userId: UUID  
  - locale: string  
  - channelOptIn: Map<Channel,bool>  
  - typeOptIn: Map<NotificationType,bool>  
  - quietHours?: TimeRange  
  **Métodos:**  
  - setOptIn(scope, enabled: bool)  
  - setQuietHours(range: TimeRange)

---

### **Value Objects**

- **ChannelRoute** – channel, primaryProvider, fallbackProviders[], retries, timeoutMs  
- **RenderedMessage** – subject?, body, richBody?, data?  
- **VariableSpec** – name, required, description  
- **DeliveryResult** – status, providerMessageId?, error?  
- **TimeRange** – startTime, endTime

---

### **Events (Domain Events)**

- NotificationRequestedEvent(notificationId, type, occurredAt)  
  **Propósito:** Se solicitó una notificación (por evento externo o API).
- NotificationScheduledEvent(notificationId, scheduledAt, occurredAt)  
  **Propósito:** Quedó programada para envío futuro.
- NotificationSentEvent(notificationId, occurredAt)  
  **Propósito:** Todos los intentos fueron despachados.
- DeliveryStatusUpdatedEvent(notificationId, attemptId, channel, status, occurredAt)  
  **Propósito:** Actualización de estado por canal/proveedor.
- NotificationFailedEvent(notificationId, reason, occurredAt)  
  **Propósito:** Falló definitivamente tras reintentos.
- PreferenceChangedEvent(userId, occurredAt)  
  **Propósito:** Cambiaron las preferencias y afectan el enrutamiento.

---

### **Services (Domain Interfaces)**

- **TemplateRenderer**  
  - render(templateId, channel, locale, payload) → RenderedMessage  
  **Propósito:** Resuelve versión/idioma y genera el contenido final.

- **ChannelRouter**  
  - route(notification: Notification) → List<ChannelRoute>  
  - dispatch(route, message) → DeliveryResult  
  **Propósito:** Selección de canal/proveedor, reintentos y failover.

- **PreferenceService**  
  - check(userId, type, channel, at: DateTime) → bool  
  **Propósito:** Respeta opt-in/out y quiet hours.

- **SchedulerService**  
  - enqueue(notificationId, at: DateTime)  
  **Propósito:** Programa recordatorios y ventanas de envío.

---

#### **2.6.7.2. Interface Layer**

- **Controllers:** NotificationController, TemplateController, PreferenceController  
- **Resources:**  
  - NotificationResource { notificationId, type, recipients, templateId, scheduledAt, status }  
  - TemplateResource { templateId, key, version, channels, variables }  
  - PreferenceResource { userId, channelOptIn, typeOptIn, quietHours }  
- **Assemblers:** NotificationAssembler, TemplateAssembler, PreferenceAssembler

---

#### **2.6.7.3. Application Layer**

- **Command Services:** NotificationCommandService, TemplateCommandService, PreferenceCommandService  
- **Query Services:** NotificationQueryService, TemplateQueryService  
- **Event Handlers (ejemplos):**  
  - OnBookingConfirmed (Matching&Booking) → NotificationRequestedEvent (Transactional)  
  - OnInvoiceIssued (Payment) → NotificationRequestedEvent (Transactional)  
  - ScheduledReminderTick → envía recordatorios de mantenimiento (Reminder)  
- **ACLs:**  
  - EmailProviderAcl, PushProviderAcl, SmsProviderAcl  
  - IAMAcl (para obtener correos/tokens push verificados)

---

#### **2.6.7.4. Infrastructure Layer**

- **Repositories:** NotificationRepository, TemplateRepository, PreferenceRepository, DeliveryAttemptRepository  
- **External Adapters:** EmailAdapter, PushAdapter, SmsAdapter, MessageBrokerPublisher, SchedulerAdapter

---

#### 2.6.7.5 Bounded Context Software Architecture Component Level Diagrams
<br>

<img alt="Component-Notifications" src="assets\chapter-II-assets\components\structurizr-101398-Component-007.png" />

#### 2.6.7.6 Bounded Context Software Architecture Code Level Diagrams
<br>

##### 2.6.7.6.1 Bounded Context Domain Layer Class Diagrams
<br>
<img alt="Class-trusting" src="assets\chapter-II-assets\bc/class-notification.png" />

##### 2.6.7.6.2 Bounded Context Database Design Diagram
<br>
<img alt="Database-trusting" src="assets\chapter-II-assets\bc/db-notifications.png" />

---


---



<div style="page-break-after: always;"></div>

# **Capítulo III: Solution UI/UX Design**

## **3.1. Product design**

### **3.1.1. Style Guidelines**

#### **3.1.1.1. General Style Guidelines**

Un “style guideline” o guía de estilo es un conjunto de reglas y pautas que establecen la forma en que se deben diseñar, redactar y presentar los elementos visuales y funcionales de un proyecto digital. Estas guías garantizan consistencia, coherencia y una identidad sólida a lo largo de todas las interfaces y materiales del producto.

A continuación, se detallan los parámetros implementados en la estructura visual y conceptual del proyecto AutoNexo, una aplicación móvil desarrollada por el equipo ATG, como parte de una iniciativa tecnológica orientada a optimizar la gestión y conexión entre talleres mecánicos y propietarios de vehículos.

**Branding**

Brand Overview

AutoNexo es una aplicación móvil desarrollada por el equipo ATG, enfocada en conectar talleres mecánicos, técnicos independientes y propietarios de vehículos dentro de un ecosistema digital integral. Su propósito principal es optimizar la gestión, comunicación y trazabilidad de los servicios automotrices, ofreciendo una experiencia más eficiente tanto para los clientes como para los talleres.

La aplicación permite administrar servicios, citas, historial de mantenimiento, inventario y facturación, todo desde una misma plataforma. A través de sus módulos, los talleres pueden organizar el flujo de trabajo, comunicarse directamente con los propietarios y analizar su rendimiento operativo mediante reportes visuales.

Una de las principales fortalezas de AutoNexo es su capacidad de adaptación a distintos tipos de talleres y mecánicos, integrando tecnologías móviles y notificaciones inteligentes para mejorar la atención al cliente. Además, su diseño modular facilita la expansión a nuevas funciones como recordatorios automáticos, integración con seguros y análisis de desempeño.

**Misión**

Digitalizar y optimizar la gestión de servicios automotrices mediante una plataforma móvil inteligente que conecte talleres, técnicos y propietarios, garantizando eficiencia, transparencia y satisfacción del cliente.

**Visión**

Convertirse en la aplicación líder en gestión automotriz en Latinoamérica, ofreciendo soluciones tecnológicas que impulsen la productividad de los talleres y fortalezcan la confianza entre clientes y mecánicos.

**Logo de ATG**

El logotipo de ATG representa innovación, colaboración y tecnología aplicada al sector automotriz. Sus elementos visuales refuerzan la idea de conexión y dinamismo, pilares fundamentales de la identidad de AutoNexo.

<p align="center">
  <img src="assets/chapter-III-assets/Logo de ATG.png" alt="Logo de ATG" width="250px" />
</p>

 **Brand Name**

El nombre AutoNexo combina los términos “Auto” (vehículo) y “Nexo” (conexión, enlace), simbolizando su función principal como punto de unión digital entre los actores del ecosistema automotriz. Representa agilidad, confianza y control sobre los procesos de mantenimiento y servicio.

El nombre refleja también su visión de comunidad, en la que cada interacción entre taller, técnico y cliente contribuye a un sistema más inteligente, ordenado y conectado.

<p align="center">
  <img src="assets/chapter-II-assets/logo-1.png.jpg" alt="Logo de ATG" width="250px" />
</p>

**Colores**

La identidad visual de AutoNexo se fundamenta en una paleta cromática que transmite confianza, tecnología y conexión. Cada color ha sido seleccionado para reflejar la esencia de la marca: profesionalismo, precisión y cercanía con el usuario.

El azul primario (#202D36) simboliza solidez y tecnología, siendo el color principal de la interfaz y de los elementos de navegación. Este tono refuerza la percepción de confianza y modernidad que caracteriza a la aplicación.

El blanco primario (#FFFFFF) proporciona equilibrio y claridad visual, garantizando una lectura limpia y una experiencia de usuario fluida.

Los colores secundarios complementan la identidad principal con acentos de energía y contraste. El crimson (#800C1F) y el dark red (#3C0007) representan fuerza, determinación y energía mecánica, ideales para destacar alertas o secciones relacionadas con acciones importantes.

Por su parte, los tonos metálicos como el steel blue y el light blue-gray aportan una sensación de modernidad industrial, evocando el entorno técnico de los talleres y la conexión digital entre sistemas. (Nota: falta definir sus códigos HEX exactos.)

En los prototipos y wireframes, se emplean tonos neutros que garantizan jerarquía visual sin distraer al usuario: gris claro (#D9D9D9) para contenedores, gris medio (#8E8E8E) para texto auxiliar, y negro (#282828) para íconos y tipografía principal sobre fondos claros.

Los colores de texto mantienen un alto contraste para asegurar legibilidad: negro (#000000) sobre fondos claros y blanco grisáceo (#D9D9D9) sobre fondos oscuros.

En conjunto, esta paleta cromática refuerza la identidad moderna, confiable y funcional de AutoNexo, creando una experiencia visual coherente con su propósito tecnológico y su enfoque en la eficiencia del servicio automotriz.

<p align="center">
  <img src="assets/chapter-III-assets/Paleta de colores.png" alt="Paleta de colores ATG" width="600px" />
</p>

<section id="typography">
  <h2>Tipografía</h2>
  <p>
    La tipografía seleccionada para <strong>AutoNexo</strong> es <strong>Inter</strong>, en sus variantes <em>Medium</em> y <em>Bold</em>. 
    Esta fuente <em>sans-serif</em> fue elegida por su modernidad, claridad visual y excelente legibilidad en pantallas móviles, 
    características esenciales para una experiencia de usuario fluida y profesional.
  </p>
  <p>
    Su estructura geométrica y balanceada refuerza la identidad tecnológica y confiable de la aplicación, 
    manteniendo coherencia en todos los componentes de la interfaz.
  </p>

  <p>Se aplica de forma jerarquizada en los siguientes niveles:</p>

  <table border="1" cellspacing="0" cellpadding="8">
    <thead>
      <tr>
        <th>Nivel</th>
        <th>Uso principal</th>
        <th>Estilo</th>
        <th>Tamaño</th>
        <th>Line Height</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Heading 01</td>
        <td>Títulos principales, encabezados generales</td>
        <td>Inter Medium</td>
        <td>70 px</td>
        <td>84 px</td>
      </tr>
      <tr>
        <td>Heading 02</td>
        <td>Secciones destacadas y subtítulos</td>
        <td>Inter Medium</td>
        <td>40 px</td>
        <td>52 px</td>
      </tr>
      <tr>
        <td>Heading 03</td>
        <td>Bloques de contenido intermedio</td>
        <td>Inter Medium</td>
        <td>25 px</td>
        <td>34 px</td>
      </tr>
      <tr>
        <td>Large Text Bold</td>
        <td>Textos de énfasis o botones principales</td>
        <td>Inter Bold</td>
        <td>25 px</td>
        <td>34 px</td>
      </tr>
      <tr>
        <td>Medium Text Bold</td>
        <td>Subtítulos o texto destacado secundario</td>
        <td>Inter Bold</td>
        <td>18 px</td>
        <td>30 px</td>
      </tr>
      <tr>
        <td>Normal Text Bold</td>
        <td>Texto informativo o párrafos breves</td>
        <td>Inter Bold</td>
        <td>16 px</td>
        <td>24 px</td>
      </tr>
      <tr>
        <td>Small Text Bold</td>
        <td>Etiquetas, menús o elementos de interfaz compactos</td>
        <td>Inter Bold</td>
        <td>14 px</td>
        <td>21 px</td>
      </tr>
    </tbody>
  </table>

<p align="center">
  <img src="assets/chapter-III-assets/Typography.png" alt="Tipografía SwiftPort" width="600px" />
</p>

  <p>
    La jerarquía tipográfica de <strong>AutoNexo</strong> busca mantener consistencia visual y equilibrio, 
    permitiendo una lectura fluida y una clara diferenciación entre niveles de información.
  </p>
  <p>
    De este modo, la aplicación proyecta una imagen moderna, estructurada y profesional, 
    coherente con su enfoque tecnológico y su propósito de conectar digitalmente a talleres y propietarios de vehículos.
  </p>
</section>

### **3.1.2. Information Architecture**

#### **3.1.2.1. Organization Systems**

El sistema de navegación de AutoNexo está diseñado para ofrecer una experiencia intuitiva, fluida y centrada en la usabilidad móvil, asegurando que tanto mecánicos como propietarios puedan acceder fácilmente a las funciones principales sin perder el contexto de su actividad.

**Estructura de Navegación Principal**

En la pantalla Home, la navegación parte de una estructura principal de barra inferior (bottom navigation bar) que contiene los accesos directos a las secciones más utilizadas:

- **Home**: Vista principal con el estado actual de citas y agenda, proporcionando una visión general del día y las actividades pendientes.

- **Request**: Permite gestionar solicitudes de servicio de los clientes, facilitando la comunicación bidireccional entre taller y propietarios.

- **Offer**: Muestra promociones o servicios destacados del taller, permitiendo a los mecánicos promocionar sus especialidades.

- **Workshop**: Acceso directo al perfil del taller y a las funciones administrativas, incluyendo gestión de inventario y configuración.

- **Service**: Historial y seguimiento de servicios realizados, proporcionando trazabilidad completa de las intervenciones.

Cada icono cuenta con una etiqueta breve y un color activo que destaca la sección seleccionada, reforzando la claridad del recorrido visual y manteniendo al usuario orientado en todo momento.

**Navegación Superior y Menú Lateral**

En la parte superior de la interfaz se ubica una barra de encabezado (App Bar) con el nombre del usuario, ícono de notificaciones y un menú lateral desplegable (hamburger menu). Este último ofrece accesos secundarios organizados en categorías lógicas:

**Gestión de Perfil:**
- Profile
- Support and Assistance

**Configuración y Legal:**
- Terms of Use
- Privacy Policy
- Logout

**Personalización:**
- Cambio de idioma (Español / English)
- Modo de tema (oscuro o claro)

Esta estructura brinda al usuario flexibilidad y control sobre su experiencia de uso, manteniendo las opciones de configuración accesibles pero no intrusivas.

**Navegación Contextual en Pantallas de Detalle**

En las pantallas de detalle, como la vista de Workshop, la navegación mantiene la misma coherencia visual y funcional. El encabezado superior permite regresar a la vista anterior mediante una flecha de retroceso (Back Arrow), mientras que los botones inferiores ("Generate Code", "Edit Workshop") proporcionan acceso directo a las acciones específicas de gestión.

**Principios de Usabilidad**

Cada transición entre pantallas es suave y contextual, evitando recargar al usuario con demasiada información. Se prioriza la simplicidad y la eficiencia: los usuarios pueden moverse entre módulos con un número mínimo de toques, manteniendo siempre visibles los elementos de navegación principales.

**Consistencia y Accesibilidad**

En conjunto, este sistema de navegación garantiza que AutoNexo mantenga una experiencia uniforme, clara y accesible, adaptada tanto a la operatividad técnica del mecánico como a la practicidad del usuario final. La organización de la información sigue principios de jerarquía visual, agrupación lógica y feedback inmediato, asegurando que cada usuario pueda encontrar rápidamente lo que necesita.

#### **3.1.2.2. Labelling Systems**

El sistema de etiquetado de AutoNexo está diseñado para proporcionar claridad, consistencia y comprensión inmediata de las funciones y contenidos de la aplicación. Cada etiqueta ha sido cuidadosamente seleccionada para reflejar la terminología del sector automotriz mientras mantiene accesibilidad para usuarios de diferentes niveles técnicos.

**Principios de Etiquetado**

**Claridad y Precisión:**
- Cada etiqueta comunica exactamente su función sin ambigüedad
- Se evita jerga técnica innecesaria que pueda confundir a usuarios no especializados
- Se utilizan términos familiares del contexto automotriz cuando es apropiado

**Consistencia Terminológica:**
- Mismo término para la misma función en toda la aplicación
- Vocabulario unificado entre mecánicos y propietarios de vehículos
- Mantenimiento de convenciones establecidas en la industria

**Jerarquía Visual:**
- Etiquetas principales en tipografía más prominente
- Etiquetas secundarias con menor peso visual
- Uso de colores y tamaños para establecer prioridad informativa

**Estructura de Etiquetado por Módulos**

**Navegación Principal:**
- **Home**: Término universalmente reconocido para la pantalla principal
- **Request**: Indica claramente la gestión de solicitudes de servicio
- **Offer**: Comunica promociones y ofertas especiales
- **Workshop**: Identifica el perfil y gestión del taller
- **Service**: Refiere al historial y seguimiento de servicios

**Gestión de Servicios:**
- **Schedule Appointment**: Programar cita de manera clara y directa
- **Service History**: Historial de servicios con terminología estándar
- **Maintenance Reminder**: Recordatorio de mantenimiento
- **Quote Request**: Solicitud de cotización
- **Service Status**: Estado del servicio en tiempo real

**Perfil y Configuración:**
- **Profile Settings**: Configuración de perfil
- **Workshop Information**: Información del taller
- **Notification Preferences**: Preferencias de notificaciones
- **Language Settings**: Configuración de idioma
- **Theme Selection**: Selección de tema visual

**Comunicación y Soporte:**
- **Contact Support**: Contactar soporte
- **Help Center**: Centro de ayuda
- **FAQ**: Preguntas frecuentes
- **Report Issue**: Reportar problema
- **Feedback**: Retroalimentación

**Estados y Acciones:**
- **Pending**: Pendiente
- **In Progress**: En progreso
- **Completed**: Completado
- **Cancelled**: Cancelado
- **Rescheduled**: Reprogramado

**Etiquetado de Formularios**

**Campos de Entrada:**
- **Vehicle Make**: Marca del vehículo
- **Vehicle Model**: Modelo del vehículo
- **Year**: Año
- **License Plate**: Placa de matrícula
- **VIN Number**: Número de VIN
- **Service Type**: Tipo de servicio
- **Estimated Duration**: Duración estimada
- **Service Description**: Descripción del servicio

**Botones de Acción:**
- **Save**: Guardar
- **Cancel**: Cancelar
- **Submit**: Enviar
- **Edit**: Editar
- **Delete**: Eliminar
- **Confirm**: Confirmar
- **Back**: Atrás
- **Next**: Siguiente

**Mensajes y Alertas:**
- **Success**: Éxito
- **Warning**: Advertencia
- **Error**: Error
- **Information**: Información
- **Confirmation Required**: Confirmación requerida

**Localización y Accesibilidad**

**Soporte Multilingüe:**
- Etiquetas disponibles en español e inglés
- Adaptación cultural de términos técnicos
- Mantenimiento de consistencia entre idiomas

**Accesibilidad:**
- Etiquetas descriptivas para lectores de pantalla
- Texto alternativo para iconos y elementos gráficos
- Contraste adecuado para legibilidad
- Tamaños de fuente accesibles

**Convenciones de Nomenclatura**

**CamelCase para IDs técnicos:**
- `serviceHistory`
- `workshopProfile`
- `maintenanceReminder`

**kebab-case para URLs:**
- `/service-history`
- `/workshop-profile`
- `/maintenance-reminder`

**PascalCase para componentes:**
- `ServiceCard`
- `WorkshopProfile`
- `MaintenanceReminder`

Este sistema de etiquetado asegura que AutoNexo mantenga una comunicación clara y efectiva con sus usuarios, facilitando la adopción de la aplicación y reduciendo la curva de aprendizaje tanto para mecánicos como para propietarios de vehículos.

#### **3.1.2.3. SEO Tags and Meta Tags**

La estrategia de SEO y Meta Tags para AutoNexo está diseñada para optimizar la visibilidad en motores de búsqueda y mejorar la experiencia del usuario tanto en la Landing Page como en la Web Application. Además, se incluyen elementos de ASO (App Store Optimization) para maximizar la descarga y adopción de la aplicación móvil.

**Landing Page - SEO Tags y Meta Tags**

**Página Principal:**
```html
<title>AutoNexo - Servicio Rápido de Mecánicos Especializados | Reserva Instantánea</title>
<meta name="description" content="Conectamos mecánicos certificados con propietarios de vehículos de manera rápida y confiable. Reserva tu servicio de mantenimiento o reparación en minutos. Servicio automotriz completo con reserva instantánea.">
<meta name="keywords" content="servicio rápido, mecánicos certificados, reserva instantánea, mantenimiento vehicular, reparación automotriz, AutoNexo, servicio automotriz completo, mecánicos especializados, citas automotrices">
<meta name="author" content="ATG - AutoNexo Team">
<meta name="robots" content="index, follow">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta property="og:title" content="AutoNexo - Servicio Rápido de Mecánicos Especializados">
<meta property="og:description" content="Conectamos mecánicos certificados con propietarios de vehículos. Reserva tu servicio de mantenimiento o reparación en minutos con nuestro sistema de reserva instantánea.">
<meta property="og:type" content="website">
<meta property="og:url" content="https://autonexo.com">
<meta property="og:image" content="https://autonexo.com/assets/og-image.jpg">
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="AutoNexo - Servicio Rápido de Mecánicos">
<meta name="twitter:description" content="Reserva instantánea de servicios automotrices con mecánicos certificados. Servicio rápido y confiable.">
```

**Página de Características:**
```html
<title>Características - AutoNexo | Todo para Servicio Automotriz Completo</title>
<meta name="description" content="Descubre todas las características de AutoNexo. Reserva instantánea, servicio automotriz completo, conexión con mecánicos certificados y más funcionalidades.">
<meta name="keywords" content="características AutoNexo, reserva instantánea, servicio automotriz completo, funcionalidades, mecánicos certificados, sistema automático">
<meta name="author" content="ATG - AutoNexo Team">
```

**Página de Precios:**
```html
<title>Precios - AutoNexo | Planes Básico y Pro para Mecánicos</title>
<meta name="description" content="Elige tu plan en AutoNexo. Plan Básico $10/mes para comenzar o Plan Pro $30/mes para profesionales. Actualiza cuando tus necesidades crezcan.">
<meta name="keywords" content="precios AutoNexo, plan básico, plan pro, planes mensuales, profesionales mecánicos, actualización planes">
<meta name="author" content="ATG - AutoNexo Team">
```

**Página de Testimonios:**
```html
<title>Testimonios - AutoNexo | Lo que Dicen Nuestros Usuarios</title>
<meta name="description" content="Lee testimonios reales de usuarios de AutoNexo. Descubre cómo nuestra app se ha convertido en herramienta esencial para usuarios alrededor del mundo.">
<meta name="keywords" content="testimonios AutoNexo, opiniones usuarios, reseñas, experiencia usuarios, herramienta esencial, usuarios mundo">
<meta name="author" content="ATG - AutoNexo Team">
```

**Página de Equipo:**
```html
<title>Equipo - AutoNexo | Conoce a los Creadores del Proyecto</title>
<meta name="description" content="Conoce al equipo ATG creador de AutoNexo. Profesionales dedicados y adaptables que aportan dedicación y actitud positiva al proyecto.">
<meta name="keywords" content="equipo AutoNexo, creadores proyecto, equipo ATG, profesionales dedicados, actitud positiva, desarrolladores">
<meta name="author" content="ATG - AutoNexo Team">
```

**Página de Contacto:**
```html
<title>Contacto - AutoNexo | ¿Necesitas Ayuda? Estamos Aquí</title>
<meta name="description" content="¿Necesitas ayuda? Contacta con AutoNexo. Estamos aquí para ayudarte con cualquier pregunta o problema. Teléfono, email y dirección disponibles.">
<meta name="keywords" content="contacto AutoNexo, ayuda, soporte, preguntas, problemas, teléfono, email, dirección, atención al cliente">
<meta name="author" content="ATG - AutoNexo Team">
```

**Web Application - SEO Tags y Meta Tags**

**Dashboard Principal:**
```html
<title>Dashboard - AutoNexo | Panel de Control</title>
<meta name="description" content="Panel de control de AutoNexo. Gestiona tus citas, servicios y comunicación con mecánicos especializados.">
<meta name="keywords" content="dashboard AutoNexo, panel de control, gestión automotriz, citas programadas">
<meta name="author" content="ATG - AutoNexo Team">
<meta name="robots" content="noindex, nofollow">
```

**Perfil de Usuario:**
```html
<title>Mi Perfil - AutoNexo | Configuración de Cuenta</title>
<meta name="description" content="Gestiona tu perfil en AutoNexo. Configura tus datos, preferencias y configuración de cuenta.">
<meta name="keywords" content="perfil usuario, configuración cuenta, AutoNexo, datos personales">
<meta name="author" content="ATG - AutoNexo Team">
<meta name="robots" content="noindex, nofollow">
```

**Historial de Servicios:**
```html
<title>Historial de Servicios - AutoNexo | Registro de Mantenimiento</title>
<meta name="description" content="Consulta tu historial completo de servicios automotrices en AutoNexo. Mantén un registro detallado de todos los mantenimientos realizados.">
<meta name="keywords" content="historial servicios, registro mantenimiento, AutoNexo, servicios automotrices">
<meta name="author" content="ATG - AutoNexo Team">
<meta name="robots" content="noindex, nofollow">
```

**App Store Optimization (ASO) - Elementos para Aplicación Móvil**

**Google Play Store:**

**App Title:**
```
AutoNexo - Mecánicos y Talleres
```

**App Subtitle:**
```
Conecta con mecánicos especializados y gestiona el mantenimiento de tu vehículo
```

**App Description:**
```
AutoNexo es la aplicación móvil que revoluciona la gestión automotriz, conectando propietarios de vehículos con mecánicos especializados y talleres certificados.

 FUNCIONALIDADES PRINCIPALES:
• Conecta con mecánicos especializados en tu zona
• Programa citas de mantenimiento de forma fácil
• Gestiona el historial completo de tu vehículo
• Recibe recordatorios de mantenimiento automático
• Comunícate directamente con tu taller
• Accede a promociones y ofertas especiales
• Sistema de calificaciones y reseñas

 PARA MECÁNICOS Y TALLERES:
• Gestiona tu agenda de citas
• Administra tu perfil y servicios
• Comunícate con clientes
• Genera reportes de servicios
• Accede a herramientas de gestión

 BENEFICIOS:
• Ahorro de tiempo en la gestión de citas
• Transparencia en precios y servicios
• Historial completo de mantenimiento
• Acceso a mecánicos certificados
• Comunicación directa y eficiente

Descarga AutoNexo y transforma tu experiencia automotriz. Disponible para propietarios de vehículos y profesionales del sector automotriz.

Desarrollado por el equipo ATG.
```

**App Keywords:**
```
mecánico, taller automotriz, mantenimiento vehicular, citas automotrices, servicios automotrices, reparación automotriz, gestión de vehículos, AutoNexo, taller mecánico, mantenimiento preventivo, diagnóstico automotriz, mecánicos especializados, talleres cerca, servicios de reparación, gestión automotriz, app automotriz, citas programadas, historial vehicular, recordatorios mantenimiento, comunicación taller
```

**Apple App Store:**

**App Title:**
```
AutoNexo - Mecánicos y Talleres
```

**App Subtitle:**
```
Conecta con mecánicos especializados
```

**App Description:**
```
AutoNexo conecta propietarios de vehículos con mecánicos especializados, ofreciendo una plataforma integral para la gestión automotriz.

CARACTERÍSTICAS:
• Conexión directa con mecánicos certificados
• Programación de citas simplificada
• Historial completo de mantenimiento
• Recordatorios automáticos de servicio
• Comunicación en tiempo real
• Sistema de calificaciones
• Promociones y ofertas especiales

PARA MECÁNICOS:
• Gestión de agenda y citas
• Administración de perfil
• Comunicación con clientes
• Herramientas de gestión

Transforma tu experiencia automotriz con AutoNexo.

Desarrollado por ATG.
```

**App Keywords:**
```
mecánico, taller, automotriz, mantenimiento, citas, servicios, reparación, vehículo, AutoNexo, diagnóstico, especializado, gestión, app, móvil
```

**Estrategia de Keywords y Posicionamiento**

**Keywords Primarias:**
- AutoNexo
- servicio rápido mecánicos
- reserva instantánea
- mecánicos certificados
- servicio automotriz completo

**Keywords Secundarias:**
- mantenimiento vehicular
- planes básico pro
- testimonios usuarios
- equipo ATG

**Keywords de Cola Larga:**
- "reserva instantánea servicios automotrices"
- "servicio rápido mecánicos certificados"
- "planes básico pro AutoNexo"
- "testimonios usuarios AutoNexo"
- "equipo creadores proyecto AutoNexo"
- "características servicio automotriz completo"
- "conecta mecánicos propietarios vehículos"

Esta estrategia de SEO y ASO asegura que AutoNexo sea fácilmente encontrable tanto en motores de búsqueda como en las tiendas de aplicaciones, maximizando la visibilidad y adopción de la plataforma.

#### **3.1.2.4. Searching Systems**

El sistema de búsqueda de AutoNexo está diseñado para proporcionar a los usuarios herramientas eficientes y precisas para encontrar mecánicos, talleres y servicios específicos, evitando que se sientan perdidos entre el volumen de información disponible. El sistema combina búsqueda textual, filtros avanzados y navegación por tags para optimizar la experiencia de descubrimiento.

**Opciones de Búsqueda Disponibles**

**Búsqueda por Texto Libre:**
- **Campo de búsqueda principal:** Permite a los usuarios escribir términos relacionados con servicios, ubicaciones o nombres de talleres
- **Búsqueda inteligente:** Sistema que sugiere autocompletado basado en servicios populares, ubicaciones y talleres registrados
- **Búsqueda por voz:** Opción de dictado para facilitar la búsqueda en dispositivos móviles

**Búsqueda por Ubicación:**
- **Búsqueda geográfica:** Filtro por ciudad, distrito o proximidad (radio en kilómetros)
- **Detección automática:** Utiliza GPS para sugerir talleres cercanos automáticamente
- **Mapa interactivo:** Visualización de talleres disponibles en un mapa con marcadores

**Búsqueda por Servicios Específicos:**
- **Tags de servicios:** Sistema de etiquetas como "Tire change", "Oil change", "Gas System", "Car wash"
- **Categorías principales:** Mantenimiento preventivo, reparaciones, diagnósticos, servicios especializados
- **Búsqueda por marca/modelo:** Filtros específicos para vehículos (Ford, Toyota, etc.)

**Filtros Avanzados Disponibles**

**Filtros por Calificación y Reputación:**
- **Rating mínimo:** Filtro por calificación de talleres (ej: 4.0 ★ o superior)
- **Número de reseñas:** Filtrar por talleres con mínimo de reseñas para mayor confiabilidad
- **Certificaciones:** Mostrar solo talleres con certificaciones específicas

**Filtros por Disponibilidad:**
- **Horarios de atención:** Filtrar por talleres abiertos en horario específico
- **Disponibilidad inmediata:** Mostrar talleres con disponibilidad para el mismo día
- **Citas programadas:** Filtro por fechas específicas disponibles

**Filtros por Precio y Servicios:**
- **Rango de precios:** Filtro por presupuesto estimado
- **Servicios incluidos:** Selección múltiple de servicios requeridos
- **Tipo de servicio:** Urgente, programado, mantenimiento preventivo

**Filtros por Características del Taller:**
- **Tamaño del taller:** Individual, pequeño, mediano, grande
- **Especialización:** General, especializado en marca específica, servicios premium
- **Facilidades:** Estacionamiento, sala de espera, Wi-Fi, café

**Sistema de Tags y Etiquetado**

**Tags de Servicios (Filtros Rápidos):**
- **Mantenimiento Básico:** "Oil change", "Filter change", "Brake check"
- **Reparaciones:** "Engine repair", "Transmission", "Electrical system"
- **Servicios Especializados:** "Tire change", "Gas System", "Car wash", "Diagnostics"
- **Emergencias:** "24/7 service", "Roadside assistance", "Emergency repair"

**Tags de Ubicación:**
- **Distritos:** "Surco", "Miraflores", "San Isidro", "La Molina"
- **Ciudades:** "Lima", "Arequipa", "Cusco", "Trujillo"
- **Zonas comerciales:** "Centro", "Zona residencial", "Zona industrial"

**Tags de Características:**
- **Horarios:** "24/7", "Fines de semana", "Solo citas"
- **Certificaciones:** "Certificado", "Especializado", "Premium"
- **Facilidades:** "Estacionamiento", "Sala de espera", "Wi-Fi"

**Presentación de Resultados de Búsqueda**

**Vista de Lista (Resultados Principales):**
- **Tarjeta de taller:** Nombre del taller, calificación (4.0 ★), ubicación (Surco, Lima)
- **Servicios destacados:** Tags de servicios más relevantes para la búsqueda
- **Información clave:** Dirección, horarios, disponibilidad inmediata
- **Acciones rápidas:** "Ver perfil", "Contactar", "Agendar cita"

**Vista de Mapa:**
- **Marcadores interactivos:** Ubicación exacta de cada taller
- **Clusters:** Agrupación de talleres cercanos para mejor visualización
- **Información emergente:** Vista previa al hacer clic en marcador

**Vista de Detalle del Taller:**
- **Información completa:** Nombre, calificación, dirección específica (Av. Arequipa 1234)
- **Galería de imágenes:** Fotos del taller, equipos y vehículos en servicio
- **Servicios disponibles:** Lista completa con tags clickeables
- **Personal del taller:** Mecánicos disponibles con roles (Workshop owner, Workshop member)
- **Reseñas y testimonios:** Opiniones de clientes anteriores

**Funcionalidades de Búsqueda Avanzada**

**Búsqueda Combinada:**
- **Múltiples filtros simultáneos:** Combinar ubicación + servicios + precio + disponibilidad
- **Búsqueda guardada:** Permitir guardar combinaciones de filtros frecuentes
- **Historial de búsquedas:** Recordar búsquedas anteriores para facilitar repetición

**Resultados Inteligentes:**
- **Relevancia personalizada:** Priorizar resultados basados en historial del usuario
- **Sugerencias contextuales:** Recomendar servicios complementarios
- **Alertas de disponibilidad:** Notificar cuando talleres favoritos tengan disponibilidad

**Herramientas de Comparación:**
- **Comparar talleres:** Selección múltiple para comparar precios, servicios y calificaciones
- **Tabla comparativa:** Vista lado a lado de características principales
- **Recomendación inteligente:** Sugerir el mejor taller basado en criterios del usuario

Este sistema de búsqueda integral asegura que los usuarios de AutoNexo puedan encontrar rápidamente el taller y los servicios que necesitan, proporcionando múltiples vías de descubrimiento y filtrado para optimizar su experiencia de búsqueda.

#### **3.1.2.5. Navigation Systems**

El sistema de navegación de AutoNexo está diseñado para guiar eficientemente a los usuarios a través de la Landing Page y las aplicaciones móviles, permitiéndoles cumplir sus objetivos de manera intuitiva y satisfactoria. La navegación se estructura en múltiples niveles para adaptarse a diferentes contextos de uso y necesidades del usuario.

**Navegación de Landing Page**

**Header Navigation (Navegación Superior):**
- **Logo AutoNexo:** Elemento principal que lleva siempre al inicio de la página
- **Menú de navegación horizontal:** "Valores", "Características", "Precios", "Testimonios", "Preguntas", "Equipo"
- **Botones de acción:** "REGISTRARSE" (destacado en rojo) y selector de idioma "ES"
- **Comportamiento:** Menú fijo que permanece visible durante el scroll para acceso constante

**Navegación por Secciones:**
- **Scroll suave:** Transiciones fluidas entre secciones sin recargas de página
- **Enlaces de ancla:** Cada elemento del menú superior lleva directamente a la sección correspondiente
- **Indicadores visuales:** Resaltado del elemento activo en el menú según la sección visible

**Navegación de Contenido:**
- **Hero Section:** Botón "Comenzar" que lleva a registro o descarga de app
- **Sección Valores:** Navegación por cards con información de confiabilidad
- **Sección Características:** Cards interactivos que expanden información al hover
- **Sección Precios:** Botones de selección de planes que llevan a proceso de registro
- **Sección Testimonios:** Carrusel de testimonios con navegación por puntos
- **Sección Equipo:** Tarjetas de perfil con información expandible
- **Sección Contacto:** Formulario directo con validación en tiempo real

**Navegación de Aplicación Móvil**

**Bottom Navigation Bar (Navegación Inferior):**
- **Home:** Vista principal con dashboard de citas y agenda del día
- **Request:** Gestión de solicitudes de servicio y comunicación con clientes
- **Offer:** Promociones, ofertas especiales y servicios destacados
- **Workshop:** Perfil del taller, configuración y herramientas administrativas
- **Service:** Historial completo de servicios y seguimiento de intervenciones

**Top Navigation (App Bar):**
- **Flecha de retroceso:** Navegación hacia atrás contextual
- **Título de sección:** Indica ubicación actual en la aplicación
- **Icono de notificaciones:** Acceso directo a alertas y mensajes
- **Menú hamburguesa:** Acceso a funciones secundarias y configuración

**Menú Lateral (Drawer Navigation):**
- **Perfil de usuario:** Acceso a configuración personal y datos del taller
- **Soporte y asistencia:** Centro de ayuda y contacto técnico
- **Términos de uso:** Información legal y políticas
- **Política de privacidad:** Documentación de protección de datos
- **Configuración de idioma:** Cambio entre español e inglés
- **Selección de tema:** Modo claro u oscuro
- **Cerrar sesión:** Logout seguro de la aplicación

**Navegación Contextual**

**Navegación por Breadcrumbs:**
- **Ruta de navegación:** Indica la ubicación actual dentro de la jerarquía
- **Navegación rápida:** Permite regresar a niveles superiores con un toque
- **Ejemplo:** Home > Workshop > Adonz Automotive > Mechanics

**Navegación por Gestos:**
- **Swipe horizontal:** Navegación entre pestañas en la misma pantalla
- **Swipe vertical:** Scroll en listas y contenido extenso
- **Pinch to zoom:** Ampliación de imágenes en galerías de talleres
- **Pull to refresh:** Actualización de contenido en listas y feeds

**Navegación por Acciones:**

**Botones de Acción Primaria:**
- **"Comenzar":** Inicio del proceso de registro o descarga
- **"Registrarse":** Acceso directo al formulario de creación de cuenta
- **"Generate Code":** Generación de código para compartir taller
- **"Edit Workshop":** Edición de información del taller

**Botones de Acción Secundaria:**
- **"Ver perfil":** Acceso al detalle completo del taller
- **"Contactar":** Inicio de comunicación directa
- **"Agendar cita":** Programación de servicios
- **"Copy to Clipboard":** Copia de información para compartir

**Flujos de Navegación Principales**

**Flujo de Registro:**
1. Landing Page → Botón "Comenzar"
2. Formulario de registro → Validación
3. Verificación de email → Confirmación
4. Onboarding → Configuración inicial
5. Dashboard principal → Primera experiencia

**Flujo de Búsqueda de Taller:**
1. Home → Búsqueda o filtros
2. Lista de resultados → Vista previa
3. Detalle del taller → Información completa
4. Contacto o agendado → Acción final

**Flujo de Gestión de Taller:**
1. Workshop → Perfil del taller
2. Edición → Modificación de datos
3. Servicios → Gestión de ofertas
4. Mecánicos → Administración de personal
5. Guardar cambios → Confirmación

**Principios de Navegación**

**Consistencia:**
- Mismos patrones de navegación en toda la aplicación
- Iconografía uniforme y reconocible
- Colores y tipografías consistentes

**Accesibilidad:**
- Navegación por teclado en web
- Lectores de pantalla compatibles
- Contraste adecuado para visibilidad
- Tamaños de toque apropiados (mínimo 44px)

**Feedback Visual:**
- Estados hover y active claramente definidos
- Animaciones suaves en transiciones
- Indicadores de carga durante procesos
- Confirmaciones visuales de acciones

**Eficiencia:**
- Acceso directo a funciones principales
- Número mínimo de toques para tareas comunes
- Navegación contextual basada en el flujo de trabajo
- Búsqueda rápida y filtros accesibles

**Recuperación de Errores:**
- Botones de retroceso siempre disponibles
- Mensajes de error claros y accionables
- Opciones de cancelación en procesos largos
- Historial de navegación para regresar fácilmente

Este sistema de navegación integral asegura que los usuarios puedan moverse de manera intuitiva y eficiente a través de AutoNexo, cumpliendo sus objetivos sin fricción y manteniendo una experiencia satisfactoria tanto en la Landing Page como en las aplicaciones móviles.

### **3.1.3. Landing Page UI Design**

#### **3.1.3.1. Landing Page Wireframe**

<section id="wireframes-landing-autonexo">
  <h2>Wireframes del Landing Page (Desktop & Mobile) – AutoNexo</h2>
  <p>
    Esta sección presenta y explica los <strong>wireframes</strong> del Landing Page para
    <em>Desktop Web Browser</em> y <em>Mobile Web Browser</em>, evidenciando la aplicación de
    <strong>principios de diseño</strong>, <strong>elementos de diseño</strong>, 
    <strong>diseño inclusivo</strong> y <strong>arquitectura de información</strong>.
  </p>

  <!-- Resumen estructural -->
  <h3>Resumen estructural</h3>
  <ul>
    <li><strong>Header fijo:</strong> logo, menú (Inicio, Características, Beneficios, Equipo, Testimonios, Contacto), selector ES/EN y CTA “Solicitar Demo”.</li>
    <li><strong>Hero:</strong> eslogan + párrafo de valor + botón primario (CTA) y visual del producto.</li>
    <li><strong>Características:</strong> 3–6 tarjetas con icono, título y texto breve.</li>
    <li><strong>Beneficios:</strong> grid de tarjetas con evidencia/valor.</li>
    <li><strong>Equipo (ATG):</strong> fotos/íconos, rol y breve bio.</li>
    <li><strong>Testimonios/Partners:</strong> carrusel o grid de logos/opiniones.</li>
    <li><strong>Formulario de contacto/solicitud de demo:</strong> campos básicos y confirmación.</li>
    <li><strong>Footer:</strong> Términos, Privacidad, Soporte y redes.</li>
  </ul>

  <!-- Diferencias Desktop vs Mobile -->
  <h3>Wireframes · Desktop vs Mobile</h3>
  <ul>
    <li><strong>Desktop:</strong> secciones en <em>grid</em> (2–3 columnas); texto e imagen en paralelo; navegación superior visible siempre.</li>
    <li><strong>Mobile:</strong> disposición <em>vertical</em> y apilada; bloques con mayor separación; CTAs centrados; navegación accesible desde el menú.</li>
  </ul>

  <!-- Principios de diseño -->
  <h3>Principios de diseño aplicados</h3>
  <ul>
    <li><strong>Jerarquía visual:</strong> títulos Inter/Medium (H1&gt;H2&gt;H3), CTA destacado, uso consistente de tamaños (70/40/25 px).</li>
    <li><strong>Contraste y énfasis:</strong> primario #202D36 vs fondos #FFFFFF; CTAs con acento (crimson #800C1F).</li>
    <li><strong>Alineación y ritmo:</strong> rejilla base de 8 px; alineación izquierda para texto, centrado para CTAs.</li>
    <li><strong>Proximidad y repetición:</strong> tarjetas con patrón consistente (icono &gt; título &gt; texto &gt; CTA).</li>
    <li><strong>Equilibrio:</strong> distribución homogénea de texto/imagen para evitar sobrecarga cognitiva.</li>
  </ul>

  <!-- Elementos de diseño -->
  <h3>Elementos de diseño evidenciados</h3>
  <ul>
    <li><strong>Tipografía:</strong> Inter (Medium/Bold) por legibilidad y coherencia móvil.</li>
    <li><strong>Color:</strong> primario #202D36, fondo #FFFFFF, grises #D9D9D9/#8E8E8E; acentos #800C1F/#3C0007.</li>
    <li><strong>Espacio:</strong> márgenes/padding 16–24 px; white space para escaneabilidad.</li>
    <li><strong>Iconografía:</strong> pictogramas simples y consistentes para features/beneficios.</li>
    <li><strong>Tamaño/Disposición:</strong> tarjetas modulares; imágenes responsivas (max-width:100%).</li>
  </ul>

  <!-- Diseño inclusivo / Accesibilidad -->
  <h3>Diseño inclusivo y accesibilidad</h3>
  <ul>
    <li><strong>Contraste:</strong> texto oscuro sobre claro y viceversa; metas AA para cuerpo (≥4.5:1) y títulos grandes (≥3:1).</li>
    <li><strong>Legibilidad:</strong> tamaños base 16–18 px; line-height 1.5–1.6; párrafos breves.</li>
    <li><strong>Interacción:</strong> blancos táctiles ≥44×44 px; estados de foco/hover/active visibles.</li>
    <li><strong>Lenguaje claro:</strong> microcopys directos en CTAs (“Solicitar Demo”, “Ver más”).</li>
    <li><strong>Internacionalización:</strong> selector ES/EN desde el header; textos preparados para longitud variable.</li>
    <li><strong>Responsive first:</strong> breakpoints típicos (≤480, ≤768, ≤1024, &gt;=1280); contenido refluye sin pérdida.</li>
  </ul>

  <!-- Arquitectura de información -->
  <h3>Arquitectura de información</h3>
  <ul>
    <li><strong>Organización:</strong> estructura jerárquica por secciones (hero → features → benefits → trust → form → footer).</li>
    <li><strong>Navegación:</strong> menú superior con anclas; CTA persistente en hero; breadcrumb implícito por orden lineal.</li>
    <li><strong>Etiquetado:</strong> nombres claros y consistentes (“Características”, “Beneficios”, “Equipo”, “Contacto”).</li>
    <li><strong>Flujo:</strong> descubrimiento (hero) → valor (features/benefits) → prueba social (testimonios/partners) → conversión (formulario).</li>
  </ul>

  <!-- Criterios de aceptación (concreto) -->
  <h3>Criterios de aceptación (cumplimiento)</h3>
  <ol>
    <li>El header muestra logo, menú y selector ES/EN en Desktop; en Mobile, menú accesible y CTA visible en el primer pantallazo.</li>
    <li>Todos los CTAs tienen tamaño mínimo táctil, contraste suficiente y texto accionable.</li>
    <li>La misma jerarquía se conserva en Mobile con bloques apilados y espaciado adecuado.</li>
    <li>Tarjetas de características y beneficios mantienen patrón visual y lectura en Z/F.</li>
    <li>El formulario captura nombre, correo, mensaje y confirma envío; campos con etiquetas visibles y validación básica.</li>
    <li>Footer incluye Términos, Privacidad, Soporte y redes; accesible en ambas vistas.</li>
  </ol>

  <!-- Nota final -->
  <p><em>
    Con lo anterior, los wireframes del Landing Page demuestran aplicación de principios visuales, elementos de diseño,
    criterios de inclusión/accesibilidad y una arquitectura de información clara que guía hacia la conversión (“Solicitar Demo”).
  </em></p>
</section>

<div>
  <p align="center"><img src="assets/chapter-III-assets/Landing page wariframes.png" alt="open-landing-wireframe.png" width="700px" /></p>
</div>

#### **3.1.3.2. Landing Page Mock-up**

<section id="landing-mockups-autonexo">
  <h2>Landing Page Mock-up (Desktop & Mobile) – AutoNexo</h2>
  <p>
    Esta sección presenta los <strong>mock-ups</strong> finales del Landing Page para
    <em>Desktop Web Browser</em> y <em>Mobile Web Browser</em>. La propuesta evidencia la aplicación de
    <strong>principios y elementos de diseño</strong>, <strong>diseño inclusivo</strong>,
    <strong>arquitectura de información</strong> y la alineación con el <strong>Design System</strong> de AutoNexo.
  </p>

  <!-- Resumen visual -->
  <h3>Resumen visual</h3>
  <ul>
    <li><strong>Hero</strong> con eslogan, párrafo de valor y CTA primario “Solicitar demo”.</li>
    <li><strong>Valores</strong> y <strong>Características</strong> en tarjetas con icono + título + texto.</li>
    <li><strong>Precios/Planes</strong> con comparación Básico vs. Pro.</li>
    <li><strong>Testimonios</strong> en tarjetas compactas de una sola línea.</li>
    <li><strong>FAQs</strong> con acordeones (+) expandibles.</li>
    <li><strong>Equipo (ATG)</strong> con fichas de miembros.</li>
    <li><strong>Contacto</strong> con formulario y datos directos.</li>
    <li><strong>Footer</strong> con Términos, Privacidad, Soporte y redes sociales.</li>
  </ul>

  <!-- Desktop vs Mobile -->
  <h3>Distribución · Desktop vs Mobile</h3>
  <ul>
    <li><strong>Desktop:</strong> secciones en grid (2–3 columnas), pares texto/imagen en paralelo, navegación fija en header.</li>
    <li><strong>Mobile:</strong> flujo vertical apilado; CTAs centrados; tarjetas a 1 columna; acordeones ocupan ancho completo.</li>
  </ul>

  <!-- Principios y elementos -->
  <h3>Principios y elementos de diseño aplicados</h3>
  <ul>
    <li><strong>Jerarquía visual:</strong> Inter Medium para H1/H2/H3 (70/40/25 px); contraste de CTAs para énfasis.</li>
    <li><strong>Contraste:</strong> primario <code>#202D36</code> sobre fondos claros <code>#FFFFFF</code>; acentos <code>#800C1F</code>/<code>#3C0007</code>.</li>
    <li><strong>Alineación y ritmo:</strong> rejilla base de 8 px; alineación izquierda para texto, centrado para acciones.</li>
    <li><strong>Proximidad/repetición:</strong> patrón consistente de tarjeta (icono &gt; título &gt; texto &gt; acción).</li>
    <li><strong>Espacio en blanco:</strong> márgenes/padding 16–24 px para escaneabilidad sin sobrecarga.</li>
  </ul>

  <!-- Inclusión / Accesibilidad -->
  <h3>Diseño inclusivo y accesibilidad</h3>
  <ul>
    <li><strong>Contraste AA:</strong> texto normal ≥ 4.5:1; títulos grandes ≥ 3:1.</li>
    <li><strong>Tipografía legible:</strong> base 16–18 px, line-height 1.5–1.6.</li>
    <li><strong>Targets táctiles:</strong> mínimos de 44×44 px; estados <em>hover/focus/active</em> visibles.</li>
    <li><strong>Lenguaje claro:</strong> microcopys directos (p. ej., “Solicitar demo”, “Ver detalles”).</li>
    <li><strong>Internacionalización:</strong> selector ES/EN en header; textos preparados para distinta longitud.</li>
    <li><strong>Responsive first:</strong> breakpoints ≤480, ≤768, ≤1024, ≥1280; imágenes fluidas (max-width:100%).</li>
  </ul>

  <!-- Arquitectura de Información -->
  <h3>Arquitectura de información (mapeo de secciones)</h3>
  <ol>
    <li><strong>Hero</strong> → Descubrimiento y CTA principal.</li>
    <li><strong>Valores</strong> → Principios de marca que guían el servicio.</li>
    <li><strong>Características</strong> → Qué hace el producto (evidencia funcional).</li>
    <li><strong>Precios/Planes</strong> → Decisión informada (Básico vs Pro).</li>
    <li><strong>Testimonios</strong> → Prueba social y confianza.</li>
    <li><strong>FAQs</strong> → Objeciones comunes y soporte inmediato.</li>
    <li><strong>Equipo</strong> → Credibilidad del grupo ATG.</li>
    <li><strong>Contacto</strong> → Conversión secundaria (formulario y datos directos).</li>
    <li><strong>Footer</strong> → Enlaces legales y canales de soporte.</li>
  </ol>

  <!-- Design System -->
  <h3>Alineación con el Design System de AutoNexo</h3>
  <ul>
    <li><strong>Colores:</strong> Primary Blue <code>#202D36</code>, Primary White <code>#FFFFFF</code>, Grays <code>#D9D9D9</code>/<code>#8E8E8E</code>, Acentos <code>#800C1F</code>/<code>#3C0007</code>.</li>
    <li><strong>Tipografía:</strong> Inter (Medium/Bold) con escalas 70/40/25 y 16–18 px para cuerpo.</li>
    <li><strong>Componentes:</strong> botones primarios/secundarios, tarjetas, acordeones, chips, formularios, navbar y footer.</li>
    <li><strong>Tokens:</strong> espaciado 8 px, radios 10–12 px, sombras sutiles para elevación de tarjetas.</li>
  </ul>

  <!-- Criterios de aceptación -->
  <h3>Criterios de aceptación</h3>
  <ol>
    <li>Header con logo, navegación y selector ES/EN en Desktop; menú accesible en Mobile.</li>
    <li>CTA “Solicitar demo” visible en el primer pantallazo (ambas vistas) y con contraste AA.</li>
    <li>Tarjetas de características/beneficios mantienen patrón y ritmo vertical/columnas según viewport.</li>
    <li>Sección de planes presenta comparación clara (precio, beneficios, acción).</li>
    <li>FAQs con acordeones expandibles; foco/teclado navegable.</li>
    <li>Formulario con validación básica y confirmación de envío; campos etiquetados.</li>
    <li>Footer con Términos, Privacidad, Soporte y redes sociales.</li>
  </ol>

  <p><em>
    Los mock-ups consolidan la propuesta visual y funcional del Landing Page de AutoNexo, demostrando consistencia con el Design System,
    cumplimiento de accesibilidad y una arquitectura de información orientada a la conversión.
  </em></p>
</section>


<div>
  <p align="center"><img src="assets/chapter-III-assets/Landing page Mockup.png" alt="open-landing-wireframe.png" width="700px" /></p>
</div>

### **3.1.4. Mobile Applications UX/UI Design**

#### **3.1.4.1. Mobile Applications Wireframes**

#### **3.1.4.2. Mobile Applications Wireflow Diagrams**

#### **3.1.4.3. Mobile Applications Mock-ups**

__Register Mechanic__

<div>
  <p align="center"><img src="assets/chapter-III-assets/Register Mechanic.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

__Recover password__

<div>
  <p align="center"><img src="assets/chapter-III-assets/Recover password.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

__Register Workshop__

<div>
  <p align="center"><img src="assets/chapter-III-assets/Register Workshop.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

__Home Mechanic__

<div>
  <p align="center"><img src="assets/chapter-III-assets/Home Mechanic.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

__Workshop Detail Mechanic__

<div>
  <p align="center"><img src="assets/chapter-III-assets/Home Mechanic.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

__Profile Mechanic and Edit__

<div>
  <p align="center"><img src="assets/chapter-III-assets/Profile Mechanic and Edit.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>  

__Support and Assitance__

<div>
  <p align="center"><img src="assets/chapter-III-assets/Support and Assitance.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>  

__Request Mechanic__

<div>
  <p align="center"><img src="assets/chapter-III-assets/Support and Assitance.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>  

__Offer Mechanic__

<div>
  <p align="center"><img src="assets/chapter-III-assets/Offer Mechanic.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>  

__Service Mechanic__

<div>
  <p align="center"><img src="assets/chapter-III-assets/Service Mechanic.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>  

__Payment__

<div>
  <p align="center"><img src="assets/chapter-III-assets/Payment.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>  

__Subscription payment__

<div>
  <p align="center"><img src="assets/chapter-III-assets/Subscription payment.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>  

__Register Owner__

<div>
  <p align="center"><img src="assets/chapter-III-assets/Register Owner.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>  

__Recover Passaword__

<div>
  <p align="center"><img src="assets/chapter-III-assets/Recover Passaword.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>  

__Profile and Edit__

<div>
  <p align="center"><img src="assets/chapter-III-assets/Profile and Edit.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>  

__Support and Assistance__

<div>
  <p align="center"><img src="assets/chapter-III-assets/Support and Assitance.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>  

__Vehicles__

<div>
  <p align="center"><img src="assets/chapter-III-assets/Vehicles.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>  

__Register Vehicle__

<div>
  <p align="center"><img src="assets/chapter-III-assets/Register Vehicle.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>  

__Edit Vehicle__

<div>
  <p align="center"><img src="assets/chapter-III-assets/Edit Vehicle.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>  

__Maintenance Log__

<div>
  <p align="center"><img src="assets/chapter-III-assets/Maintenance Log.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>  

__Add Maintenance__

<div>
  <p align="center"><img src="assets/chapter-III-assets/Add Maintenance.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>  

__Edit Maintenance__

<div>
  <p align="center"><img src="assets/chapter-III-assets/Edit Maintenance.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>  

__Workshop Details__

<div>
  <p align="center"><img src="assets/chapter-III-assets/Workshop Details.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>  


#### **3.1.4.4. Mobile Applications User Flow Diagrams**

User goal: Registrarse como nuevo usuario

User persona: Mecánico o jefe de taller

Al ingresar a la aplicación móvil, los usuarios pueden acceder con su correo y contraseña desde la pantalla Login. Si no tienen una cuenta, pueden seleccionar “Register”, pasando a la pantalla de Registro, donde deberán ingresar su nombre, correo, número de teléfono y contraseña.

De manera opcional, pueden incluir un Workshop Code para asociarse a un taller existente. Si no saben qué es, pueden consultar la opción “What’s this?”, que muestra una breve explicación visual.

Antes de finalizar, los usuarios deben aceptar los Términos y Condiciones y luego presionar “Register” para completar su registro. Una vez creado el usuario, la aplicación los redirige a su pantalla principal Home.

<p align="center">
  <img src="assets/chapter-III-assets/Flujo 1.jpg" alt="Registro del mecanico" width="720px" />
</p>


User goal: Recuperar contraseña

User persona: Mecánico o jefe de taller

Al ingresar a la aplicación, el usuario puede seleccionar la opción “Forgot Password?” desde la pantalla de Login. Luego, se le solicita ingresar su número de teléfono registrado para recibir un código de verificación (OTP).

En la pantalla de OTP Verification, el usuario ingresa el código recibido por mensaje y selecciona “Verify & Proceed”. Una vez validado, pasa a la pantalla donde podrá establecer una nueva contraseña, confirmarla y presionar “Submit” para completar el proceso.

Finalmente, el sistema confirma el cambio y redirige al usuario nuevamente a la pantalla de Login para acceder con sus nuevas credenciales.

<p align="center">
  <img src="assets/chapter-III-assets/Flujo 2.jpg" alt="Recuperar Contraseña" width="720px" />
</p>

User goal: Iniciar sesión y acceder al panel principal

User persona: Mecánico o Jefe de taller

Al ingresar a la aplicación, el usuario visualiza la pantalla de Login, donde puede acceder ingresando su correo y contraseña. Una vez autenticado, la aplicación lo redirige a la pantalla principal Home, donde se muestra su nombre, próximas citas y el calendario de trabajo con las solicitudes programadas.

Desde el ícono de menú, el usuario puede abrir el panel lateral y acceder a diferentes secciones como Profile, Payment, Support and Assistance, Terms of use, Privacy Policy o Logout, además de cambiar el idioma y el tema de la aplicación.

<p align="center">
  <img src="assets/chapter-III-assets/Flujo 3.jpg" alt="Ingresar a la aplicación" width="720px" />
</p>

User goal: Registrar y configurar un taller

User persona: Mecánico o Jefe de taller

Al ingresar a la sección Workshop, el usuario puede registrar la información de su taller completando los campos de nombre comercial, RUC, distrito, ciudad y dirección. También puede añadir el logo, una imagen representativa y los servicios disponibles.

En la siguiente pantalla, el usuario define los horarios de atención para cada día de la semana y, si lo desea, marca los días libres o la opción de atención las 24 horas.

Finalmente, al presionar “Save”, la aplicación guarda la información y registra el taller correctamente dentro del sistema, quedando listo para ser visualizado o editado posteriormente.

<p align="center">
  <img src="assets/chapter-III-assets/Flujo 4.jpg" alt="Registrar taller" width="720px" />
</p>

User goal: Visualizar y compartir el código del taller

User persona: Propietario o jefe de taller

Desde la pantalla principal Home, el usuario puede acceder a la sección Workshop, donde visualiza la información completa de su taller, incluyendo nombre, ubicación, servicios y miembros del equipo.

En esta vista, el usuario puede seleccionar la opción “Generate Code” para crear un Workshop Code, el cual se muestra en una ventana emergente con la opción de copiarlo para compartirlo con nuevos mecánicos que deseen unirse al taller.

Una vez generado, el código puede ser utilizado por un solo usuario y posteriormente caduca. El propietario también puede editar los datos del taller seleccionando “Edit Workshop”.

<p align="center">
  <img src="assets/chapter-III-assets/Flujo 5.jpg" alt="Registrar taller" width="720px" />
</p>

User goal: Visualizar y editar perfil de usuario

User persona: Propietario o jefe de taller

Desde el menú lateral, el usuario puede acceder a la sección Profile, donde visualiza su información personal, como nombre, correo, número de teléfono y taller actual. También puede gestionar las notificaciones de mensajes y ofertas.

Al seleccionar el ícono de edición, el usuario ingresa a la pantalla Edit Profile, donde puede actualizar sus datos personales o modificar su contraseña seleccionando la opción “Change Password”.

En la pantalla New Password, debe ingresar y confirmar la nueva contraseña. Finalmente, al presionar “Save”, los cambios se guardan y el usuario regresa a su perfil actualizado.

<p align="center">
  <img src="assets/chapter-III-assets/Flujo 6.jpg" alt="Editar Perfil" width="720px" />
</p>

User goal: Contactar con soporte técnico

User persona:  Propietario o jefe de taller

Desde el menú lateral, el usuario puede acceder a la sección Support and Assistance, donde se presentan distintas opciones de ayuda como Call Us, Mail Us, Frequently Asked Questions, Terms and Conditions y un tutorial en video.

Al seleccionar Mail Us, se abre la pantalla Contact us via Gmail, donde el usuario puede escribir el asunto y el mensaje dirigido al equipo de soporte de Autonexo.

Finalmente, al presionar “Send Email”, aparece una ventana de confirmación con el mensaje “Success!”, indicando que el correo fue enviado correctamente.

<p align="center">
  <img src="assets/chapter-III-assets/Flujo 7.jpg" alt="Asistencia y Soporte" width="720px" />
</p>

User goal: Enviar una oferta al propietario del vehículo

User persona:  Propietario o jefe de taller

Desde la pantalla principal Home, el usuario puede ingresar a la sección Request, donde se muestran las solicitudes de mantenimiento enviadas por los propietarios de vehículos.

Al seleccionar Offer en una solicitud, el mecánico puede revisar los detalles del vehículo y completar el formulario Make an Offer, indicando el precio estimado, fecha y hora de cita, además de observaciones adicionales sobre el servicio.

Finalmente, al presionar “Send Offer”, aparece una ventana emergente con el mensaje “Success!”, confirmando que la oferta fue enviada exitosamente al cliente.

<p align="center">
  <img src="assets/chapter-III-assets/Flujo 8.jpg" alt="Oferta" width="720px" />
</p>

User goal: Visualizar ofertas pendientes y realizadas

User persona: Mecánico o jefe de taller

Desde la pantalla principal Home, el usuario puede acceder a la sección Offer, donde se muestran las ofertas enviadas a los propietarios de vehículos.

En esta pantalla, las ofertas se organizan en dos categorías: Pending, que agrupa las propuestas aún no respondidas, y Realized, que muestra las ofertas aceptadas o completadas.

De esta forma, el usuario puede realizar un seguimiento de sus propuestas y gestionar de manera eficiente sus servicios dentro de la plataforma.

<p align="center">
  <img src="assets/chapter-III-assets/Flujo 9.jpg" alt="Visualizar ofertas" width="720px" />
</p>

User goal: Registrar y gestionar órdenes de servicio

User persona: Mecánico o jefe de taller

Desde la pantalla principal Home, el usuario puede ingresar a la sección Service, donde se muestran las órdenes de servicio clasificadas como In progress, Done o Canceled.

Al seleccionar Register Service Order, el mecánico puede crear una nueva orden, eligiendo la oferta asociada, la fecha y hora de entrega, y agregando las tareas específicas del mantenimiento.

Finalmente, al presionar “Register”, la orden se guarda en el sistema y queda disponible para seguimiento dentro del listado de servicios activos.

<p align="center">
  <img src="assets/chapter-III-assets/Flujo 10.jpg" alt="Registrar y gestionar servicios" width="720px" />
</p>

User goal: Suscribirse a un plan de pago

User persona: Mecánico o jefe de taller

Desde el menú lateral, el usuario puede acceder a la sección Payment, donde visualiza los planes disponibles (Monthly y Annual) con sus respectivos precios y beneficios.

Tras seleccionar el plan deseado, se muestra la pantalla Billing address, donde el usuario completa los datos de facturación. Luego, pasa a la pantalla Add Payment, en la que debe ingresar la información de su tarjeta o método de pago preferido.

Finalmente, al presionar “Pay”, aparece una ventana de confirmación con el mensaje “Success!”, indicando que la suscripción se realizó correctamente.

<p align="center">
  <img src="assets/chapter-III-assets/Flujo 11.jpg" alt="Suscribirse a un plan" width="720px" />
</p>


User goal: Registrarse como propietario de vehículo

User persona: Propietario de vehículo

Al ingresar a la aplicación, el usuario propietario accede a la pantalla Login, donde puede iniciar sesión con su correo y contraseña. Si no tiene una cuenta, puede seleccionar la opción “Register” para continuar con el proceso de registro.

En la pantalla Registration, el usuario debe completar los campos con su nombre, correo electrónico, número de teléfono y contraseña, la cual debe ser confirmada. Antes de finalizar, debe aceptar los Términos y Condiciones mostrados en una ventana emergente.

Finalmente, al presionar “Register”, su cuenta se crea exitosamente, quedando listo para acceder a las funciones principales de la aplicación.

<p align="center">
  <img src="assets/chapter-III-assets/Flujo 1 Owner.jpg" alt="Registrarse como propietario de vehículo" width="720px" />
</p>

User goal: Recuperar contraseña

User persona: Propietario de vehículo

Desde la pantalla Login, el usuario selecciona la opción “Forgot Password?”, lo que lo dirige a una pantalla donde debe ingresar su número de teléfono registrado.

A continuación, recibe un código de verificación (OTP) que debe ingresar en la pantalla OTP Verification para validar su identidad. Una vez verificado, se habilita la pantalla para establecer una nueva contraseña, la cual debe ser confirmada antes de presionar “Submit”.

Finalmente, el sistema confirma la actualización de la contraseña, permitiendo al usuario volver al inicio de sesión con sus nuevas credenciales.

<p align="center">
  <img src="assets/chapter-III-assets/Flujo 2 Owner.jpg" alt="Recuperar contraseña" width="720px" />
</p>

User goal: Iniciar sesión y acceder al panel principal

User persona: Propietario de vehículo

Al ingresar a la aplicación, el usuario visualiza la pantalla Login, donde puede acceder ingresando su correo electrónico y contraseña. Una vez autenticado, es redirigido al Home, donde se muestra la información de su cita actual, el taller asignado y el mecánico encargado.

Desde el menú lateral, el usuario puede acceder a secciones como Profile, Payment, Support and Assistance, Terms of use, Privacy Policy y Logout, además de cambiar el idioma y el tema de la aplicación.


<p align="center">
  <img src="assets/chapter-III-assets/Flujo 3 Owner.jpg" alt="Iniciar sesión y acceder al panel principal" width="720px" />
</p>

User goal: Visualizar y editar perfil de usuario

User persona: Propietario de vehículo

Desde el menú lateral, el usuario accede a la sección Profile, donde puede visualizar su información personal, como nombre, correo electrónico, número de teléfono, talleres favoritos y configuración de notificaciones.

Al presionar el ícono de edición, se abre la pantalla Edit Profile, que permite modificar los datos personales o cambiar la contraseña seleccionando “Change Password”.

En la pantalla New Password, el usuario ingresa y confirma su nueva contraseña. Finalmente, al presionar “Save”, los cambios se guardan correctamente, actualizando su perfil.

<p align="center">
  <img src="assets/chapter-III-assets/Flujo 4 Owner.jpg" alt="Visualizar y editar perfil de usuario" width="720px" />
</p>

User goal: Contactar con soporte técnico

User persona: Propietario de vehículo

Desde el menú lateral, el usuario puede acceder a la sección Support and Assistance, donde se muestran opciones de ayuda como Call Us, Mail Us, Frequently Asked Questions, Terms and Conditions y un tutorial en video.

Al seleccionar Mail Us, se abre la pantalla Contact us via Gmail, donde el usuario puede escribir el asunto y el mensaje para comunicarse con el equipo de soporte.

Finalmente, al presionar “Send Email”, aparece una ventana de confirmación con el mensaje “Success!”, indicando que el correo fue enviado correctamente.

<p align="center">
  <img src="assets/chapter-III-assets/Flujo 5 Owner.jpg" alt="Contactar con soporte técnico" width="720px" />
</p>

User goal: Eliminar un vehículo registrado

User persona: Propietario de vehículo

Desde el Home, el usuario selecciona la pestaña Vehicles, donde puede visualizar todos los vehículos registrados en su cuenta. Cada vehículo muestra las opciones Edit y Delete.

Al presionar Delete, se muestra un mensaje de confirmación indicando “Success! Vehicle deleted successfully”, confirmando que la eliminación del vehículo se realizó correctamente.

Este flujo permite mantener actualizada la información de los vehículos asociados a la cuenta del usuario, brindando un control fácil y rápido desde la aplicación.

<p align="center">
  <img src="assets/chapter-III-assets/Flujo 6 Owner.jpg" alt="Eliminar un vehículo registrado" width="720px" />
</p>

User goal: Registrar un nuevo vehículo

User persona: Propietario de vehículo

Desde la sección Vehicles, el usuario selecciona la opción Add New Vehicle para registrar un nuevo automóvil.
En la pantalla Register Vehicle, ingresa la información del vehículo, incluyendo marca, modelo, año, placa, fotografía, y una breve descripción del estado o características del vehículo.

Tras completar los campos requeridos, el usuario presiona Register, y el sistema confirma la operación con el mensaje:
“Success! Vehicle registered successfully”, indicando que el vehículo se añadió correctamente a su cuenta.

<p align="center">
  <img src="assets/chapter-III-assets/Flujo 7 Owner.jpg" alt="Registrar un nuevo vehículo" width="720px" />
</p>

User goal: Editar la información de un vehículo registrado

User persona: Propietario de vehículo

Desde la sección Vehicles, el usuario selecciona la opción Edit en el vehículo que desea actualizar.
En la pantalla Edit Vehicle, puede modificar los campos disponibles como marca, modelo, año, fotografía, placa y descripción.

Una vez realizados los cambios, el usuario presiona Save, y el sistema muestra el mensaje de confirmación:
“Success! Vehicle edited successfully”, indicando que la información fue actualizada correctamente.

<p align="center">
  <img src="assets/chapter-III-assets/Flujo 8 Owner.jpg" alt="Editar la información de un vehículo registrado" width="720px" />
</p>

User goal: Registrar o editar un mantenimiento del vehículo

User persona: Propietario de vehículo

Desde la pantalla Maintenance Log, el usuario puede visualizar el historial de mantenimientos realizados a su vehículo, con información como fecha y tipo de servicio.

Al seleccionar Add Maintenance, se abre la pantalla Maintenance, donde el usuario puede ingresar o actualizar los datos del mantenimiento: nombre del servicio, fecha, costo, mecánico responsable y una breve descripción.

Tras guardar los cambios con el botón Add Maintenance, el sistema muestra el mensaje de confirmación:
“Success! Maintenance edited successfully”, indicando que el registro fue actualizado correctamente.

<p align="center">
  <img src="assets/chapter-III-assets/Flujo 9 Owner.jpg" alt="Registrar o editar un mantenimiento del vehículo" width="720px" />
</p>

User goal: Buscar y visualizar información de talleres

User persona: Propietario de vehículo

Desde la pantalla principal, el usuario selecciona la opción Workshop en la barra de navegación inferior.
En la pantalla Workshop, puede aplicar filtros por departamento, provincia y distrito para visualizar los talleres disponibles cercanos a su ubicación.

Al seleccionar un taller, se muestra la pantalla con su información detallada: nombre, dirección, teléfono, servicios ofrecidos, calificación promedio y la lista de mecánicos asociados.

De esta manera, el usuario puede elegir el taller más conveniente antes de realizar una solicitud de servicio.

<p align="center">
  <img src="assets/chapter-III-assets/Flujo 10 Owner.jpg" alt="Buscar y visualizar información de talleres" width="720px" />
</p>

#### **3.1.4.5. Mobile Applications Prototyping**


---



<div style="page-break-after: always;"></div>

# <font color="skyblue"> **Capítulo IV: Product Implementation & Validation** </font>

## **4. Product Implementation & Validation**

### **4.1. Software Configuration Management**

#### **4.1.1. Software Development Environment Configuration**

#### **4.1.2. Source Code Management**

#### **4.1.3. Source Code Style Guide & Conventions**

#### **4.1.4. Software Deployment Configuration**

### **4.2. Landing Page & Mobile Application Implementation**

#### **4.2.1. Sprint n**

##### **4.2.1.1. Sprint Planning n**

##### **4.2.1.2. Sprint Backlog n**

##### **4.2.1.3. Development Evidence for Sprint Review**

##### **4.2.1.4. Testing Suite Evidence for Sprint Review**

##### **4.2.1.5. Execution Evidence for Sprint Review**

##### **4.2.1.6. Services Documentation Evidence for Sprint Review**

##### **4.2.1.7. Software Deployment Evidence for Sprint Review**

##### **4.2.1.8. Team Collaboration Insights during Sprint**

### **4.3. Validation Interviews**

#### **4.3.1. Diseño de Entrevistas**

#### **4.3.2. Registro de Entrevistas**

#### **4.3.3. Evaluaciones según heurísticas**


---



<div style="page-break-after: always;"></div>

## Conclusiones

**Integración de metodologías**: La combinación de Lean UX, User Stories y Domain-Driven Design (DDD) proporciona un marco sólido para diseñar soluciones centradas en el usuario y alineadas con los objetivos del negocio.

**Importancia del lenguaje común**: El uso de Ubiquitous Language asegura que tanto el equipo técnico como los usuarios comprendan los conceptos clave sin ambigüedades, reduciendo errores en el desarrollo.

**Validación constante**: Las entrevistas y herramientas como Empathy Mapping o User Personas permiten identificar necesidades reales y garantizar que la solución propuesta responda a problemas concretos.

**Trazabilidad y claridad**: El uso de User Stories, Impact Mapping y Product Backlog aporta organización y priorización en los requerimientos, facilitando la gestión ágil del proyecto.

**Escalabilidad del diseño**: EventStorming y los diagramas de arquitectura de software permiten visualizar la complejidad del sistema, anticipar dependencias y construir una solución escalable y mantenible.

---



<div style="page-break-after: always;"></div>

## Bibliografía

Fowler, M. (2004). Ubiquitous Language. Recuperado de: https://martinfowler.com/bliki/UbiquitousLanguage.html

Gothelf, J. (2016). Lean UX – Chapter 3. Scribd. Recuperado de: https://www.scribd.com/document/655516553/Leanux-Sampler

Cohn, M. (s. f.). User Stories Articles. Mountain Goat Software. Recuperado de: https://www.mountaingoatsoftware.com/blog/tag/user-stories

UXPressia. (2022). How to create an Impact Map in 4 easy steps? Recuperado de: https://uxpressia.com/blog/build-impact-map-4-easy-steps

Nielsen Norman Group. (2019). Empathy Mapping: The First Step in Design Thinking. Recuperado de: https://www.nngroup.com/articles/empathy-mapping/

DDD by Examples. (s. f.). Big Picture EventStorming. Recuperado de: https://github.com/ddd-by-examples/library/blob/master/docs/bigpicture.md

Tune, N. (2019). Domain-Driven Architecture Diagrams. Medium. Recuperado de: https://medium.com/nick-tune-tech-strategy-blog/domain-drivenarchitecture-diagrams-139a75acb578

Channel News Perú. (2021, 22 de noviembre). Sólo 23.5% de talleres mecánicos de América Latina utiliza software especializado para gestionar sus operaciones. Channel News Perú. Recuperado de: https://channelnewsperu.com/solo-23-5-de-talleres-mecanicos-de-america-latina-utiliza-software-especializado-para-gestionar-sus-operaciones/

UpKeep. (2023). Maintenance cost statistics: Everything you need to know. UpKeep. Recuperado de:  Recuperado de:zhttps://upkeep.com/maintenance-management/maintenance-cost-statistics

Infraspeak. (2024). Maintenance costs: A complete guide. Infraspeak. Recuperado de: https://www.infraspeak.com/blog/maintenance-costs

---



<div style="page-break-after: always;"></div>



---

