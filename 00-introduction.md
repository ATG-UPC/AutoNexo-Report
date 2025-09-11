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

| Versión | Fecha      | Autor                          | Descripción de modificación      |
|---------|------------|--------------------------------|----------------------------------|
| TB1     | 07/09/2025 | Todos los integrantes del grupo aportaron  | Reporte, capítulos 1, 2, 3 y 4|

# <font color="skyblue">**Project Report Collaboration Insights**</font>

Enlace de la organización del proyecto: https://github.com/ATG-UPC

**TB1**

Para el desarrollo del informe correspondiente a la entrega TB1, se repartieron las tareas de la siguiente manera para cada integrante del equipo:

|Integrante|Tareas Asignadas|
|-|-|
|Victor Andres Cruz Ibarra| |
|Rafael Andres Vivanco Salazar| |
|Sergio Sebastián Iglesias Pérez | |
|Henry Kalet Esteban Roman | |
|Angelo Hector Solano Armas| |

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
<td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal">Andres Cruz: <br> TB1: <br> <br>Angelo Solano: <br> TB1: <br> <br>Henry Esteban: <br> TB1: <br> <br>Rafael Vivanco: <br> TB1: <br> <br>Sergio Iglesias  <br> TB1: <br> </td>
<td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal">TB1: </td>
</tr>
<tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal">Reconoce la necesidad del
aprendizaje permanente para el
desempeño profesional y el desarrollo
de proyectos en soluciones de
tecnologías de ingeniería de software.</td>
<td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal">Andres Cruz: <br> TB1: <br> <br>Angelo Solano: <br> TB1: <br> <br>Henry Esteban: <br> TB1: <br> <br>Rafael Vivanco: <br> TB1: <br> <br>Sergio Iglesias  <br> TB1: <br> </td>
<td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal">TB1: </td>
</tr>
</tbody></table>
</br></br>
