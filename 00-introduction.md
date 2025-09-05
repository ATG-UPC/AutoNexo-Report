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
            <td>Sergio Sebastián Iglesias Pérez</td>
            <td>u202316118</td>
        </tr>
        <tr>
            <td>Henry Kalet Esteban Roman</td>
            <td>U202310210</td>
        </tr>
        <tr>
            <td>Victor Andres Cruz Ibarra</td>
            <td>u202311053</td>
        </tr>
        <tr>
            <td>Angelo Hector Solano Armas</td>
            <td>u20231B775</td>
        </tr>
        <tr>
            <td>Rafael Andres Vivanco Salazar</td>
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
| TB1     | 07/09/2025 | Todos los integrantes del grupo aportaron  | Reporte, capítulos 1, 2, 3, 4 y 5|

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
- [ **Capítulo I: Introducción** ](#-capítulo-i-introducción-)
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
- [ **Capítulo II: Requirements Elicitation \& Analysis** ](#-capítulo-ii-requirements-elicitation--analysis-)
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
    - [**2.3.5. As-is Scenario Mapping**](#235-as-is-scenario-mapping)
  - [**2.4. Ubiquitous Language**](#24-ubiquitous-language)
- [ **Capítulo III: Requirements Specification** ](#-capítulo-iii-requirements-specification-)
  - [**3.1. To-Be Scenario Mapping**](#31-to-be-scenario-mapping)
  - [**3.2. User Stories**](#32-user-stories)
  - [**3.3. Impact Mapping**](#33-impact-mapping)
  - [**3.4. Product Backlog**](#34-product-backlog)
- [ **Capítulo IV: Solution Software Design** ](#-capítulo-iv-solution-software-design)
  - [**4.1. Strategic-Level Domain-Driven Design**](#41-strategic-level-domain-driven-design)
    - [**4.1.1. EventStorming**](#411-eventstorming)
        - [**4.1.1.1 Candidate Context Discovery**](#4111-candidate-context-discovery)
        - [**4.1.1.2 Domain Message Flows Modeling**](#4112-domain-message-flows-modeling)
        - [**4.1.1.3 Bounded Context Canvases**](#4113-bounded-context-canvases)
    - [**4.1.2. Context Mapping**](#412-context-mapping)
    - [**4.1.3. Software Architecture**](#413-software-architecture)
        - [**4.1.3.1 Software Architecture Context Level Diagrams**](#4131-software-architecture-context-level-diagrams)
        - [**4.1.3.2 Software Architecture Container Level Diagrams**](#4131-software-architecture-container-level-diagrams)
        - [**4.1.3.3 Software Architecture Deployment Diagrams**](#4131-software-architecture-deployment-diagrams)
  - [**4.2 Tactical-Level Domain-Driven Design**](#42-tactical-level-domain-driven-design)
    - [**4.2.1 Bounded Context: Bounded Context Name**](#42-bounded-context:-bounded-context-name)
        - [**4.2.1.1 Domain Layer**](#4211-domain-laye>)
        - [**4.2.1.2 Interface Layer**](#4212-interface-layer)
        - [**4.2.1.3 Application Layer**](#4213-application-layer)
        - [**4.2.1.4 Infrastructure Layer**](#4214-infrastructure-layer)
        - [**4.2.1.5 Bounded Context Software Architecture Component Level Diagrams**](#4215-bounded-context-software-architecture-component-level-diagrams)
        - [**4.2.1.6 Bounded Context Software Architecture Code Level Diagrams**](#4216-bounded-context-software-architecture-code-level-diagrams)
             - [**4.2.1.6.1 Bounded Context Domain Layer Class Diagrams**](#42161-bounded-context-domain-layer-class-diagrams)
             - [**4.2.1.6.2 Bounded Context Database Design Diagram**](#42162-bounded-context-database-design-diagram)
- [ **Capítulo V: Solution UI/UX Design** ](#-capítulo-v-product-design-)
  - [**5.1. Product design**](#51-product-design)
  - [**5.1.1. Style Guidelines**](#511-style-guidelines)
    - [**5.1.1.1 General Style Guidelines**](#5111-general-style-guidelines)
  - [**5.1.2. Information Architecture**](#512-information-architecture)
    - [**5.1.2.1 Organization Systems**](#5121-organization-systems)
    - [**5.1.2.2 Labeling Systems**](#5122-labeling-systems)
    - [**5.1.2.3 SEO Tags and Meta Tags**](#5123-seo-tags-and-meta-tags)
     - [**5.1-2.4. Searching Systems**](#5124-searching-systems)
    - [**5.1.2.5. Navigation Systems**](#5125-navigation-systems)
  - [**5.1.3. Landing Page UI Design**](#513-landing-page-ui-design)
      - [**5.1.3.1. Landing Page Wireframe**](#5131-landing-page-wireframe)
      - [**5.1.3.2. Landing Page Mock-up**](#5132-landing-page-mock-up)
  - [**5.1.4. Mobile Applications UX/UI Design**](#514-mobile-application-ux/ui-design)
    - [**5.1.4.1. Mobile Applications Wireframes**](#5141-mobile-applications-wireframes)
    - [**5.1.4.2. Mobile Applications Wireflow Diagrams**](#5142-mobile-applications-wireflow-diagrams)
    - [**5.1.4.3. Mobile Applications Mock-ups**](#5143-mobile-applications-mock-ups)
    - [**5.1.4.4. Mobile Applications User Flow Diagram**](#5144-mobile-applications-user-flow-diagram)
    - [**5.1.4.5. Mobile Applications Prototyping**](#5145-mobile-applications-prototyping)
  
- [ **Capítulo VI: Product Implementation, Validation \& Deployment** ](#-capítulo-vi-product-implementation-validation--deployment-)
  - [**6.1. Software Configuration Management**](#61-software-configuration-management)
    - [**6.1.1. Software Development Environment Configuration**](#611-software-development-environment-configuration)
    - [**6.1.2. Source Code Management**](#612-source-code-management)
    - [**6.1.3. Source Code Style Guide \& Conventions**](#613-source-code-style-guide--conventions)
    - [**6.1.4. Software Deployment Configuration**](#614-software-deployment-configuration)
  - [**6.2. Landing Page, Services \& Applications Implementation**](#62-landing-page-services--applications-implementation)
    - [**6.2.1. Sprint 1**](#621-sprint-1)
      - [**6.2.1.1. Sprint Planning 1**](#6211-sprint-planning-1)
      - [**6.2.1.2. Sprint Backlog 1**](#6212-sprint-backlog)
      - [**6.2.1.3. Development Evidence for Sprint Review**](#6213-development-evidence-for-sprint-review)
      - [**6.2.1.4. Testing Suite Evidence for Sprint Review**](#6214-testing-suite-evidence-for-sprint-review)
      - [**6.2.1.5. Execution Evidence for Sprint Review**](#6215-execution-evidence-for-sprint-review)
      - [**6.2.1.6. Services Documentation Evidence for Sprint Review**](#6216-services-documentation-evidence-for-sprint-review)
      - [**6.2.1.7. Software Deployment Evidence for Sprint Review**](#6217-software-deployment-evidence-for-sprint-review)
      - [**6.2.1.8. Team Collaboration Insights during Sprint**](#6218-team-collaboration-insights-during-sprint)
  - [**6.3. Validation Interviews**](#63-validation-interviews)
    - [**6.3.1. Diseño de Entrevistas**](#631-diseño-de-entrevistas)
    - [**6.3.2. Registro de Entrevistas.**](#632-registro-de-entrevistas)
    - [**6.3.3. Evaluaciones según heurísticas**](#633-evaluaciones-según-heurísticas)
  - [**6.4. Video About-the-Product**](#64-video-about-the-product)
- [**Conclusiones**](#conclusiones)
  - [**Conclusiones y recomendaciones**](#conclusiones-y-recomendaciones)
  - [**Video About-the-Team**](#video-about-the-team)

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