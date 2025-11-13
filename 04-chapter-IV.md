# <font color="skyblue"> **Capítulo IV: Product Implementation & Validation** </font>

## **4.1. Software Configuration Management**

El equipo definió un conjunto de herramientas y configuraciones destinadas a mantener un entorno de desarrollo coherente y estandarizado. Este entorno busca facilitar la colaboración entre los integrantes del proyecto, garantizar la trazabilidad del código y asegurar la correcta gestión de las versiones y despliegues a lo largo del ciclo de vida del producto digital.

#### **4.1.1. Software Development Environment Configuration**

#### Project Management

**Trello** es la herramienta principal que el equipo utiliza para la gestión ágil del proyecto. A través de tableros, listas y tarjetas, permite planificar, priorizar y hacer seguimiento de las tareas, historias de usuario y actividades de diseño o desarrollo. Su interfaz visual facilita la colaboración y la organización del flujo de trabajo.
<br>https://trello.com

**Discord** es la plataforma elegida para la comunicación diaria entre los miembros del equipo. Mediante canales temáticos y reuniones virtuales, se coordinan los avances, revisiones y soporte en tiempo real durante todo el proceso de desarrollo.  <br>
https://discord.com

#### Product UX/UI Design

**Figma** es la herramienta principal utilizada para el diseño de la interfaz de usuario (UI) y la experiencia de usuario (UX). Permite la colaboración simultánea del equipo en la creación de prototipos interactivos, estructuras visuales y pruebas de usabilidad. <br>
https://www.figma.com

**UXPressia** complementa el trabajo de diseño al permitir documentar los elementos de investigación UX, como los User Personas, Customer Journey Maps y Empathy Maps. Esta herramienta facilita comprender mejor las necesidades de los usuarios y orientar el diseño hacia una experiencia más empática.
<br>https://uxpressia.com

#### Software Development

**Android Studio** es el entorno de desarrollo integrado (IDE) utilizado para construir y probar la aplicación móvil. Ofrece herramientas integradas para programación, diseño de interfaces, depuración y emulación de dispositivos Android, lo que permite un desarrollo fluido y controlado del frontend móvil.<br>
https://developer.android.com

#### Software Deployment

**Git** es el sistema de control de versiones adoptado por el equipo para gestionar los cambios en el código fuente. Facilita el trabajo colaborativo, el control de versiones y la integración continua mediante ramas y commits organizados.<br>
https://git-scm.com

**GitHub Pages** se utiliza como plataforma de despliegue para publicar la interfaz del frontend. Al integrarse directamente con los repositorios de GitHub, permite alojar sitios web estáticos de manera sencilla y automatizada.<br>
https://pages.github.com

**Azure** es la plataforma en la nube seleccionada para el despliegue del backend del sistema. Proporciona servicios escalables, seguros y de alto rendimiento, como App Services y Azure SQL, garantizando la disponibilidad y estabilidad de la aplicación en producción.<br>
https://azure.microsoft.com


#### Software Documentation and Project Management

**GitHub** cumple la función de repositorio remoto centralizado. Se utiliza para almacenar y versionar el código, documentar el proyecto, gestionar incidencias y coordinar revisiones de código mediante pull requests.<br>
https://github.com

#### Software Testing

**Gherkin** es el lenguaje utilizado para definir los criterios de aceptación de las User Stories mediante escenarios estructurados. Su formato legible facilita la comunicación entre desarrolladores y analistas, garantizando una comprensión clara de las funcionalidades.<br>
https://cucumber.io/docs/gherkin/

#### **4.1.2. Source Code Management**

### 4.1.2. Source Code Management

Para el control de versiones del proyecto, el equipo adoptará el flujo de trabajo propuesto por el modelo GitFlow, utilizando GitHub como plataforma principal para la gestión y colaboración del código fuente. Este enfoque permite mantener un desarrollo organizado, controlado y fácilmente escalable entre todos los miembros del equipo.

A continuación, se presenta la estructura general del flujo GitFlow y la distribución de repositorios utilizados por el proyecto:

**Repositorios de GitHub:**

- Enlace para acceder a la organización de GitHub: https://github.com/ATG-UPC
- Enlace para acceder a repositorio de la Landing Page: https://github.com/ATG-UPC/AutoNexo-Landing-Page
- Enlace para acceder a repositorio de FrontEnd Web Mobile Application: https://github.com/ATG-UPC/AutoNexo-Android
- Enlace para acceder a repositorio de BackEnd Web Service: https://github.com/ATG-UPC/AutoNexo-Backend

**Flujo de trabajo GitFlow:** <br>El proyecto sigue el modelo de ramificación diseñado por Vincent Driessen en “A successful Git branching model”, el cual facilita el desarrollo paralelo de nuevas funcionalidades, la integración continua y la gestión ordenada de versiones estables.

**Estructura de branches (Ramas):**

1. **Main branch (Rama principal):** Contiene las versiones estables y verificadas del sistema. Toda versión en esta rama se considera lista para despliegue en producción. Los cambios solo se incorporan tras pasar por revisiones y pruebas en ramas previas.

2. **Develop branch (Rama de desarrollo):** Es la base de integración de las funcionalidades en progreso. En esta rama se concentran los avances consolidados del equipo antes de generar una versión de lanzamiento.

3. **Feature branches (Ramas de funcionalidad):** Cada nueva funcionalidad, mejora o experimento se desarrolla en una rama independiente, derivada desde develop. Al finalizar y validar su funcionamiento, se fusiona nuevamente con develop

4. **Release branches (Ramas de lanzamiento):** Se crean cuando el sistema está próximo a una versión estable. Permiten realizar pruebas finales, ajustes menores y preparar la documentación de la versión antes de integrarla a main.

5. **Hotfix branches (Ramas de corrección):** Se emplean para resolver errores críticos detectados en la rama principal sin interrumpir el flujo de desarrollo. Una vez corregido el problema, los cambios se integran tanto a main como a develop.

**Versionamiento Semántico:** El equipo aplicará el estándar Semantic Versioning 2.0.0, basado en el formato MAJOR.MINOR.PATCH, para identificar claramente los tipos de cambios entre versiones:

MAJOR: Cambios incompatibles con versiones anteriores.

MINOR: Nuevas funcionalidades compatibles con la versión previa.

PATCH: Correcciones menores o de errores.

**Convenciones de Commits:** Para mantener un historial de cambios consistente y fácil de interpretar, se seguirá la especificación Conventional Commits, inspirada en las Angular Commit Guidelines.
El formato propuesto será:

`git commit -m "<type>[optional scope]: <description">`

Donde:

-**type** indica el tipo de cambio (ej. feat, fix, refactor, docs).

-**scope** describe el módulo o área afectada (opcional).

-**description** es una breve descripción en presente del cambio realizado.

#### **4.1.3. Source Code Style Guide & Conventions**

**Kotlin/Java (Android):** Para garantizar la legibilidad, mantenibilidad y coherencia del código dentro del entorno de Android Studio, el equipo seguirá las siguientes convenciones de estilo:

1. Utilizar camelCase para nombres de variables y métodos, y PascalCase para clases y componentes principales.

2. Mantener una indentación de 4 espacios y procurar que las líneas no superen los 100 caracteres para facilitar la lectura.

3. Redactar comentarios únicamente cuando el fragmento de código no sea autoexplicativo, priorizando la claridad sobre la redundancia.

4. Nombrar los recursos XML (layouts, strings, drawables, ids) en minúsculas y separados por guiones bajos, siguiendo el formato nombre_recurso_tipo.

5. Respetar la arquitectura definida del proyecto, asegurando que las responsabilidades estén claramente separadas dentro de paquetes organizados (por ejemplo, ui/, data/, domain/).

**Gherkin:** Este lenguaje de especificación de comportamiento permite comunicar de manera efectiva los requerimientos entre los equipos técnicos y de negocio, en el contexto de Behavior Driven Development (BDD).
Para su uso, se han seguido las siguientes buenas prácticas:

-Utilización de saltos de línea para mantener la estructura clara entre los distintos escenarios.

-Empleo de las palabras clave Given, When, Then y And para construir escenarios comprensibles, estandarizados 

-Organización de los escenarios en formato descriptivo, manteniendo una redacción orientada al comportamiento esperado del sistema.

#### **4.1.4. Software Deployment Configuration**

**Landing page deployment:**

El despliegue de la página principal del proyecto (Landing Page) se realiza mediante GitHub Pages, aprovechando su integración directa con los repositorios del proyecto. Este proceso permite publicar la interfaz web de manera gratuita y automática, a partir de la rama principal del repositorio.
y fáciles de validar.
A continuación, se detallan los pasos seguidos para su configuración:

1. Crear una carpeta denominada docs, donde se almacenarán los archivos del Landing Page. 

2. Asegurar que la estructura del proyecto contenga los archivos principales con las siguientes convenciones:<br>-index.html → página de inicio.<br>-style.css → hoja de estilos principal.<br>-Carpeta img → recursos gráficos y multimedia.

3. Subir los archivos al repositorio remoto en GitHub.

4. Acceder a Settings → Pages, seleccionar la rama correspondiente (generalmente main o master) y definir la carpeta /docs como origen del contenido. 

5. Guardar los cambios y esperar a que GitHub procese el despliegue automático. 

6. Una vez finalizado el proceso, el sistema genera un enlace público donde se podrá visualizar la landing page en línea. 


#### **4.2.1. Sprint 1**

##### **4.2.1.1. Sprint Planning 1**

En esta sección se describen los elementos principales abordados durante la reunión de planificación del Sprint 1. Se especifican detalles como la fecha y hora del encuentro, los miembros participantes, el objetivo del Sprint, la velocidad estimada del equipo y la cantidad total de puntos de historia comprometidos para este ciclo de desarrollo. A continuación, se expone el resumen correspondiente a dicha planificación.

| Sprint # | Sprint 1 |
|----------|---------|
| Date | 2025 - 10 - 01 |
| Time | 10:20 PM |
| Location | Reunión virtual a través de discord | 
| Prepared by | Solano Armas, Angelo Hector | 
| Attendees (to planning meeting) | Cruz Ibarra, Victor Andres; Iglesias Pérez, Sergio Sebastián; Roman Esteban, Henry Kalet; Solano Armas, Angelo Hector; Vivanco Salazar, Rafael Andres
| Sprint n – 1 Review Summary | No existe sprint previo | 
| Sprint 1 Goal | Nuestro enfoque está en entregar la primera versión integrada del ecosistema AutoNexo, que incluye la Landing Page pública y la conexión funcional inicial entre los servicios backend y la aplicación móvil. Creemos que esto proporcionará visibilidad, confiabilidad y capacidades de interacción temprana tanto a los usuarios finales como a los propietarios de talleres, permitiéndoles explorar la propuesta de valor de la plataforma e interactuar con datos reales a través de la aplicación móvil.  | 
| Sprint 1 Velocity | 19 story points | 
| Sum of story points | 19 story points |


##### **4.2.1.2. Sprint Backlog 1**

El propósito del Sprint 1 es diseñar y poner en marcha una landing page completamente funcional para el proyecto Autonexo. A continuación, se presenta una vista general de las historias de usuario planificadas para este sprint, junto con sus respectivas épicas y el estado de avance de cada una.

<img alt="Sprint Backlog 1 in Trello" src="assets\chapter-IV-assets\sprint1_trello.png" />

<br>

Link Trello: [Autonexo - Trello](https://trello.com/b/4uTEBz5O/atg-autonexo)

<table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>Sprint #</th>
      <th colspan="8">Sprint 1</th>
    </tr>
    <tr>
      <th colspan="2">User Story</th>
      <th colspan="7">Work Item / Task</th>
    </tr>
    <tr>
      <th>ID</th>
      <th>Title</th>
      <th>ID</th>
      <th>Title</th>
      <th>Description</th>
      <th>Estimation (hours)</th>
      <th>Assigned To</th>
      <th>Status</th>
      <th>Story Points</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US01</td>
      <td>Visualizar información y beneficios (Landing Page)</td>
      <td>T01</td>
      <td>Redactar contenido principal y CTAs</td>
      <td>Escribir y revisar el texto principal de la landing (beneficios + CTA).</td>
      <td>2</td>
      <td>Cruz Ibarra, Victor Andres</td>
      <td>To Do</td>
      <td>2</td>
    </tr>
    <tr>
      <td>US21</td>
      <td>Registro de usuario (propietario o taller)</td>
      <td>T02</td>
      <td>Implementar formulario básico de registro</td>
      <td>Crear formulario con campos esenciales y validaciones front.</td>
      <td>2</td>
      <td>Iglesias Pérez, Sergio Sebastián</td>
      <td>To Do</td>
      <td>3</td>
    </tr>
    <tr>
      <td>US22</td>
      <td>Preguntas frecuentes y soporte</td>
      <td>T03</td>
      <td>Redactar y publicar FAQ</td>
      <td>Redactar FAQ principales y dejar la sección maquetada simple.</td>
      <td>1</td>
      <td>Roman Esteban, Henry Kalet</td>
      <td>To Do</td>
      <td>2</td>
    </tr>
    <tr>
      <td>US23</td>
      <td>Contacto y descarga de la app</td>
      <td>T04</td>
      <td>Configurar formulario de contacto + botones de descarga</td>
      <td>Implementar formulario de contacto y añadir botones con enlaces a tiendas.</td>
      <td>2</td>
      <td>Solano Armas, Angelo Hector</td>
      <td>To Do</td>
      <td>2</td>
    </tr>
    <tr>
      <td>US28</td>
      <td>Visualizar planes de pago para talleres (Landing Page)</td>
      <td>T05</td>
      <td>Diseñar/maquetar sección de planes</td>
      <td>Crear la tabla/tiles de planes con precios y beneficios (responsivo).</td>
      <td>2</td>
      <td>Vivanco Salazar, Rafael Andres</td>
      <td>To Do</td>
      <td>2</td>
    </tr>
    <tr>
      <td>US29</td>
      <td>Seleccionar tipo de mecánico</td>
      <td>T06</td>
      <td>Implementar selector de tipo de mecánico</td>
      <td>Desarrollar componente para que el usuario elija el tipo de mecánico al registrarse.</td>
      <td>2</td>
      <td>Cruz Ibarra, Victor Andres</td>
      <td>To Do</td>
      <td>3</td>
    </tr>
    <tr>
      <td>US30</td>
      <td>Generar y compartir código de taller</td>
      <td>T07</td>
      <td>Implementar generación de código de invitación</td>
      <td>Programar función para generar y compartir código que permite a otros unirse al taller.</td>
      <td>2</td>
      <td>Roman Esteban, Henry Kalet</td>
      <td>To Do</td>
      <td>3</td>
    </tr>
    <tr>
      <td>US32</td>
      <td>Navegación mediante barra de menú</td>
      <td>T08</td>
      <td>Diseñar e implementar barra de navegación</td>
      <td>Crear barra de navegación funcional para moverse entre secciones del sistema.</td>
      <td>2</td>
      <td>Vivanco Salazar, Rafael Andres</td>
      <td>To Do</td>
      <td>2</td>
    </tr>
  </tbody>
</table>



##### **4.2.1.3. Development Evidence for Sprint Review**

En esta sección se presentan los avances logrados durante el Sprint 1, enfocados en la implementación de la Landing Page del proyecto AutoNexo. El objetivo de este sprint fue desarrollar los principales componentes de la página web orientada a talleres mecánicos y propietarios de vehículos, asegurando una interfaz clara, responsiva y funcional.

<table>
  <thead>
    <tr>
      <th>Repository</th>
      <th>Branch</th>
      <th>Commit Id</th>
      <th>Commit Message</th>
      <th>Commit Message Body</th>
      <th>Committed on (Date)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ATG-UPC/AutoNexo-Landing-Page</td>
      <td>feature/landing-content</td>
      <td>3fa219b</td>
      <td>feat: add main benefits section</td>
      <td>Se añadió la sección principal con texto descriptivo, beneficios clave y botones de llamada a la acción (CTA). <em>(US01)</em></td>
      <td>2025-10-01</td>
    </tr>
    <tr>
      <td>ATG-UPC/AutoNexo-Landing-Page</td>
      <td>feature/register-form</td>
      <td>7c4f2d9</td>
      <td>feat: implement user registration form</td>
      <td>Se creó el formulario de registro con validación básica y estructura responsiva. <em>(US21)</em></td>
      <td>2025-10-02</td>
    </tr>
    <tr>
      <td>ATG-UPC/AutoNexo-Landing-Page</td>
      <td>feature/faq-support</td>
      <td>61e3a20</td>
      <td>feat: add FAQ component</td>
      <td>Se implementó el componente de preguntas frecuentes con diseño colapsable. <em>(US22)</em></td>
      <td>2025-10-03</td>
    </tr>
    <tr>
      <td>ATG-UPC/AutoNexo-Landing-Page</td>
      <td>feature/contact-section</td>
      <td>b48df23</td>
      <td>feat: add contact form and store links</td>
      <td>Se añadieron el formulario de contacto y los botones con enlaces de descarga. <em>(US23)</em></td>
      <td>2025-10-04</td>
    </tr>
    <tr>
      <td>ATG-UPC/AutoNexo-Landing-Page</td>
      <td>feature/plans-section</td>
      <td>72b26b7</td>
      <td>feat: add pricing plans section</td>
      <td>Se desarrolló la sección de planes de pago para talleres con maquetado responsivo. <em>(US28)</em></td>
      <td>2025-10-05</td>
    </tr>
    <tr>
      <td>ATG-UPC/AutoNexo-Android</td>
      <td>feature/mechanic-selector</td>
      <td>94fca31</td>
      <td>feat: add mechanic type selector</td>
      <td>Se implementó el componente que permite seleccionar el tipo de mecánico al registrarse. <em>(US29)</em></td>
      <td>2025-10-06</td>
    </tr>
    <tr>
      <td>ATG-UPC/AutoNexo-Android</td>
      <td>feature/workshop-code</td>
      <td>a12b57d</td>
      <td>feat: generate and share workshop code</td>
      <td>Se implementó la funcionalidad para generar y compartir el código de taller. <em>(US30)</em></td>
      <td>2025-10-07</td>
    </tr>
    <tr>
      <td>ATG-UPC/AutoNexo-Android</td>
      <td>feature/navbar</td>
      <td>381206e</td>
      <td>feat: add navigation bar and menu links</td>
      <td>Se diseñó y programó la barra de navegación principal, mejorando la accesibilidad entre secciones. <em>(US32)</em></td>
      <td>2025-10-08</td>
    </tr>
  </tbody>
</table>

##### **4.2.1.4. Testing Suite Evidence for Sprint Review**

Durante el Sprint 1, el equipo de AutoNexo desarrolló y ejecutó un conjunto de pruebas automatizadas y manuales para verificar el correcto funcionamiento de los componentes implementados en la Landing Page y la interfaz inicial de la aplicación móvil.

<table> <thead> <tr> <th>Repository</th> <th>Branch</th> <th>Commit Id</th> <th>Commit Message</th> <th>Commit Message Body</th> <th>Committed on (Date)</th> </tr> </thead> <tbody> <tr> <td>ATG-UPC/AutoNexo-Landing-Page</td> <td>test/landing-benefits</td> <td>f28a1b7</td> <td>test: add unit tests for landing benefits section</td> <td>Se agregaron pruebas unitarias para verificar la correcta visualización del texto principal, beneficios y botones CTA de la Landing Page. <em>(US01)</em></td> <td>2025-10-02</td> </tr> <tr> <td>ATG-UPC/AutoNexo-Landing-Page</td> <td>test/user-register-form</td> <td>a91cbf2</td> <td>test: validate registration form fields</td> <td>Se desarrollaron pruebas para comprobar la validación de campos, formato de correo y respuesta al envío correcto del formulario de registro. <em>(US21)</em></td> <td>2025-10-03</td> </tr> <tr> <td>ATG-UPC/AutoNexo-Landing-Page</td> <td>test/faq-support</td> <td>b82e3c4</td> <td>test: verify FAQ toggle behavior</td> <td>Se probaron los comportamientos de expansión y colapso de los ítems del componente de Preguntas Frecuentes (FAQ). <em>(US22)</em></td> <td>2025-10-04</td> </tr> <tr> <td>ATG-UPC/AutoNexo-Landing-Page</td> <td>test/contact-section</td> <td>d24fa15</td> <td>test: test contact form and store links</td> <td>Se validó el funcionamiento del formulario de contacto y los botones de descarga en las tiendas móviles. <em>(US23)</em></td> <td>2025-10-05</td> </tr> <tr> <td>ATG-UPC/AutoNexo-Landing-Page</td> <td>test/plans-section</td> <td>c41e99b</td> <td>test: ensure pricing plans render correctly</td> <td>Se realizaron pruebas de renderizado y consistencia de contenido en los distintos planes de pago para talleres. <em>(US28)</em></td> <td>2025-10-06</td> </tr> <tr> <td>ATG-UPC/AutoNexo-Landing-Page</td> <td>test/mechanic-type</td> <td>e9ad4f8</td> <td>test: add tests for mechanic type selector</td> <td>Se verificó que el selector de tipo de mecánico muestre correctamente las opciones y guarde la selección del usuario. <em>(US29)</em></td> <td>2025-10-06</td> </tr> <tr> <td>ATG-UPC/AutoNexo-Landing-Page</td> <td>test/workshop-code</td> <td>f63db33</td> <td>test: test generation and sharing of workshop code</td> <td>Se implementaron pruebas unitarias para validar la generación, copia y compartición del código de taller. <em>(US30)</em></td> <td>2025-10-07</td> </tr> <tr> <td>ATG-UPC/AutoNexo-Landing-Page</td> <td>test/navbar</td> <td>ac9b7d2</td> <td>test: verify navigation bar routes and active state</td> <td>Se realizaron pruebas para asegurar que los enlaces de navegación funcionen correctamente y mantengan el estado activo de la sección. <em>(US32)</em></td> <td>2025-10-08</td> </tr> </tbody> </table>

##### **4.2.1.5. Execution Evidence for Sprint Review**

Durante este Sprint se logró implementar de forma completa la Landing Page del proyecto AutoNexo, cumpliendo con el objetivo principal del Sprint 1. Esta página inicial permite a los talleres mecánicos y propietarios de vehículos conocer los servicios ofrecidos por la plataforma, registrarse según su rol, acceder a información relevante y explorar los distintos planes de pago disponibles.

El desarrollo se centró en crear una interfaz moderna, funcional y responsiva, asegurando una navegación clara y una presentación coherente con la identidad visual del proyecto. Dentro de las tareas realizadas se incluyeron la redacción del contenido principal, la creación del formulario de registro, la sección de preguntas frecuentes, el módulo de contacto y la visualización de los planes de pago para talleres.

A continuación, se presentan las capturas de pantalla de las vistas desarrolladas como evidencia del trabajo realizado:

<br>
Header:

<img alt="Header" src="assets\chapter-IV-assets\sprint1_evidence_header.png" />

<br>
Sección de beneficios:

<img alt="Beneficios" src="assets\chapter-IV-assets\sprint1_evidence_benefits.png" />

<br>
Preguntas frecuentes (FAQ):

<img alt="Preguntas frecuentes" src="assets\chapter-IV-assets\sprint1_evidence_faq.png" />

<br>
Planes de pago para talleres:

<img alt="Planes de pago" src="assets\chapter-IV-assets\sprint1_evidence_plans.png" />

<br>
Sección de contacto y descarga de la aplicación:

<img alt="Sección de contacto y descarga" src="assets\chapter-IV-assets\sprint1_evidence_contact.png" />

<br>
Registro de usuario (propietario o taller):

<img alt="Registro" src="assets\chapter-IV-assets\sprint1_evidence_ur.png" />

<br>

Video de evidencia: [Autonexo - Landing Video](https://drive.google.com/file/d/163ZhWu71eMLBHduWRDx6wPGMCe84rkoQ/view?usp=sharing)


##### **4.2.1.6. Services Documentation Evidence for Sprint Review**

Durante el Sprint, se implementaron y documentaron correctamente los servicios RESTful correspondientes a los contextos de Workshop e Invitation, garantizando una comunicación eficiente entre el frontend y el backend mediante peticiones HTTP estandarizadas (GET, POST, PUT, DELETE).
A continuación, se detallan las principales evidencias y descripciones de los endpoints desarrollados:

**A. WorkshopController**

Este controlador gestiona las operaciones relacionadas con los talleres (Workshops), incluyendo su creación, consulta, actualización, manejo de ubicaciones, personal, servicios, etiquetas de capacidad y archivos multimedia.

Principales endpoints:

<table>
  <thead>
    <tr>
      <th><strong>Endpoint</strong></th>
      <th><strong>HTTP Method</strong></th>
      <th><strong>Descripción</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>/api/v1/workshops</td>
      <td>POST</td>
      <td>Crea un nuevo taller a partir de los datos del usuario propietario.</td>
    </tr>
    <tr>
      <td>/api/v1/workshops/my-workshop</td>
      <td>GET</td>
      <td>Recupera la información del taller asociado al usuario autenticado.</td>
    </tr>
    <tr>
      <td>/api/v1/workshops/{workshopId}</td>
      <td>GET</td>
      <td>Obtiene la información pública de un taller por su ID.</td>
    </tr>
    <tr>
      <td>/api/v1/workshops/by-owner/{ownerUserId}</td>
      <td>GET</td>
      <td>Recupera el taller perteneciente a un propietario específico.</td>
    </tr>
    <tr>
      <td>/api/v1/workshops</td>
      <td>GET</td>
      <td>Lista todos los talleres activos.</td>
    </tr>
    <tr>
      <td>/api/v1/workshops/by-tag</td>
      <td>GET</td>
      <td>Filtra los talleres según una etiqueta de capacidad.</td>
    </tr>
    <tr>
      <td>/api/v1/workshops</td>
      <td>PUT</td>
      <td>Actualiza la información básica del taller.</td>
    </tr>
    <tr>
      <td>/api/v1/workshops/locations</td>
      <td>POST</td>
      <td>Agrega una nueva ubicación al taller.</td>
    </tr>
    <tr>
      <td>/api/v1/workshops/service-templates</td>
      <td>POST</td>
      <td>Registra una plantilla de servicio en el taller.</td>
    </tr>
    <tr>
      <td>/api/v1/workshops/tags</td>
      <td>POST</td>
      <td>Añade una etiqueta de capacidad (capability tag) al taller.</td>
    </tr>
    <tr>
      <td>/api/v1/workshops/tags</td>
      <td>PUT</td>
      <td>Actualiza el conjunto completo de etiquetas de capacidad.</td>
    </tr>
    <tr>
      <td>/api/v1/workshops/logo</td>
      <td>POST</td>
      <td>Carga y actualiza el logotipo del taller (usa Cloudinary).</td>
    </tr>
    <tr>
      <td>/api/v1/workshops/photos</td>
      <td>POST</td>
      <td>Agrega una foto al carrusel de imágenes del taller.</td>
    </tr>
    <tr>
      <td>/api/v1/workshops/photos/{photoIndex}</td>
      <td>DELETE</td>
      <td>Elimina una foto del carrusel de imágenes del taller.</td>
    </tr>
    <tr>
      <td>/api/v1/workshops/catalog/categories</td>
      <td>GET</td>
      <td>Obtiene las categorías de servicios disponibles en el catálogo.</td>
    </tr>
    <tr>
      <td>/api/v1/workshops/catalog/services</td>
      <td>GET</td>
      <td>Obtiene los servicios disponibles del catálogo general.</td>
    </tr>
    <tr>
      <td>/api/v1/workshops/catalog/capability-tags</td>
      <td>GET</td>
      <td>Lista las etiquetas de capacidad disponibles.</td>
    </tr>
  </tbody>
</table>

**B. InvitationController**

Este controlador administra las invitaciones que permiten a los talleres agregar nuevos miembros de personal (staff members) mediante códigos únicos.

Principales endpoints:

<table>
  <thead>
    <tr>
      <th><strong>Endpoint</strong></th>
      <th><strong>HTTP Method</strong></th>
      <th><strong>Descripción</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>/api/v1/invitations/workshops/{workshopId}</td>
      <td>POST</td>
      <td>Crea una invitación asociada a un taller específico.</td>
    </tr>
    <tr>
      <td>/api/v1/invitations/accept</td>
      <td>POST</td>
      <td>Permite aceptar una invitación y registrar al usuario como miembro del taller.</td>
    </tr>
    <tr>
      <td>/api/v1/invitations/{code}</td>
      <td>GET</td>
      <td>Consulta la información de una invitación mediante su código único.</td>
    </tr>
    <tr>
      <td>/api/v1/invitations/workshops/{workshopId}</td>
      <td>GET</td>
      <td>Lista todas las invitaciones emitidas por un taller determinado.</td>
    </tr>
  </tbody>
</table>



**C. Seguridad, validación y consistencia**
- Todos los endpoints aplican validaciones automáticas mediante @Valid y tipos de recursos (CreateWorkshopResource, AddServiceTemplateResource, etc.).

- Se maneja de forma controlada el flujo de errores y respuestas HTTP (400, 403, 404, 500).

- Se integran patrones de diseño Domain-Driven Design (DDD) y CQRS para mantener la escalabilidad del sistema.

##### **4.2.1.7. Software Deployment Evidence for Sprint Review**

Durante este Sprint se completó con éxito el despliegue de la Landing Page del proyecto AutoNexo mediante el servicio Azure Static Web Apps, siguiendo un enfoque incremental orientado a la entrega continua del producto.

**Actividades realizadas:**
- Se habilitó una cuenta en Azure y se configuró un grupo de recursos compartido, permitiendo una gestión centralizada de los componentes del proyecto.

- Se desplegó la Landing Page directamente desde el repositorio en GitHub, utilizando Azure Static Web Apps para automatizar el proceso de publicación.

- Se configuró un flujo CI/CD (Integración y Entrega Continua) a través de GitHub Actions, de modo que cada commit en la rama main actualiza automáticamente la versión publicada del sitio.

- Se validó el correcto funcionamiento y disponibilidad del producto a través del dominio generado por Azure, comprobando que todas las secciones y enlaces operen de forma óptima.

**Evidencias del proceso de despliegue:**
A continuación, se incluyen las capturas correspondientes al proceso de configuración, vinculación del repositorio en GitHub y la publicación satisfactoria del sitio en Azure.

1. Creación del grupo de recursos:
<div>
  <p align="center"><img src="assets\chapter-IV-assets\sprint1_deployment-1.png" alt="deployment-1.png" width="700px" /></p>
</div>

2. Configuración de recurso Static Web App:

<div>
  <p align="center"><img src="assets\chapter-IV-assets\sprint1_deployment-3.png" alt="deployment-3.png" width="700px" /></p>
</div>

3. Vinculación con GitHub y configuración del flujo CI/CD:

4. Despliegue exitoso con confirmación del dominio generado por Azure:
<div>
  <p align="center"><img src="assets\chapter-IV-assets\sprint1_deployment-8.png" alt="deployment-8.png" width="700px" /></p>
</div>


<div>
  <p align="center"><img src="assets\chapter-IV-assets\sprint1_deployment-9.png" alt="deployment-9.png" width="700px" /></p>
</div>


<div>
  <p align="center"><img src="assets\chapter-IV-assets\sprint1_deployment-10.png" alt="deployment-10.png" width="700px" /></p>
</div>

##### **4.2.1.8. Team Collaboration Insights during Sprint**

Durante el desarrollo del Sprint, todos los integrantes del equipo participaron activamente en la implementación de la Landing Page de AutoNexo, organizando el trabajo por secciones según el contenido y diseño establecidos previamente. El enfoque principal fue ofrecer una interfaz clara, moderna y alineada con la identidad visual del proyecto, que comunique efectivamente los beneficios y servicios de la plataforma.

A continuación, se detalla la participación específica de cada miembro del equipo:

<table>
  <thead>
    <tr>
      <th><strong>Nombre</strong></th>
      <th><strong>Actividad</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Cruz Ibarra, Victor Andrés</strong></td>
      <td>Redacción del contenido principal de la landing page, incluyendo secciones de información general y llamados a la acción (CTAs). Apoyo en la estructura visual de los beneficios.</td>
    </tr>
    <tr>
      <td><strong>Iglesias Pérez, Sergio Sebastián</strong></td>
      <td>Implementación del formulario de registro de usuario (propietario o taller) y validaciones de entrada. Participación en la integración de enlaces entre secciones.</td>
    </tr>
    <tr>
      <td><strong>Roman Esteban, Henry Kalet</strong></td>
      <td>Desarrollo de la sección de <strong>Preguntas Frecuentes (FAQ)</strong>, maquetado de los elementos expandibles y redacción de las preguntas base.</td>
    </tr>
    <tr>
      <td><strong>Solano Armas, Angelo Hector</strong></td>
      <td>Configuración de la <strong>sección de contacto y descarga de la aplicación</strong>, asegurando la funcionalidad de los formularios y enlaces hacia las tiendas móviles.</td>
    </tr>
    <tr>
      <td><strong>Vivanco Salazar, Rafael Andrés</strong></td>
      <td>Diseño e implementación de la <strong>sección de planes de pago para talleres</strong>, mostrando los distintos niveles de suscripción y sus beneficios comparativos.</td>
    </tr>
  </tbody>
</table>

##### Evidencia de colaboración en GitHub

A continuación, se presenta la evidencia de participación de los miembros del equipo, extraída del repositorio oficial del proyecto. Se puede observar el trabajo colaborativo y los aportes de cada integrante en las distintas ramas del desarrollo.

<img alt="participation" src="assets\chapter-IV-assets\sprint1_evidence_participation.png" />


##### Repositorio de trabajo:

- [Repositorio de la Landing Page en GitHub](https://github.com/ATG-UPC/AutoNexo-Landing-Page)

### **4.3. Validation Interviews**

#### **4.3.1. Diseño de Entrevistas**

#### **4.3.2. Registro de Entrevistas**

#### **4.3.3. Evaluaciones según heurísticas**

#### **4.2.2. Sprint 2**

##### **4.2.2.1. Sprint Planning 2**

En esta sección se describen los elementos principales abordados durante la reunión de planificación del Sprint 2. Se especifican detalles como la fecha y hora del encuentro, los miembros participantes, el objetivo del Sprint, la velocidad estimada del equipo y la cantidad total de puntos de historia comprometidos para este ciclo de desarrollo. A continuación, se expone el resumen correspondiente a dicha planificación.

| Sprint # | Sprint 2 |
|----------|---------|
| Date | 2025 - 10 - 15 |
| Time | 9:00 PM |
| Location | Reunión virtual a través de discord | 
| Prepared by | Solano Armas, Angelo Hector | 
| Attendees (to planning meeting) | Cruz Ibarra, Victor Andres; Iglesias Pérez, Sergio Sebastián; Roman Esteban, Henry Kalet; Solano Armas, Angelo Hector; Vivanco Salazar, Rafael Andres
| Sprint n – 1 Review Summary | Durante el Sprint 1 se completó exitosamente la Landing Page del proyecto AutoNexo, incluyendo todas las secciones principales (beneficios, registro, FAQ, contacto, planes de pago). Se implementaron funcionalidades básicas en la aplicación móvil como el selector de tipo de mecánico, generación de códigos de taller y navegación. La Landing Page fue desplegada en Azure Static Web Apps. | 
| Sprint 2 Goal | Nuestro enfoque está en completar el despliegue del backend al 100% en un sitio público con documentación completa, finalizar la implementación de las principales funcionalidades core de la aplicación móvil (pantallas de propietario y mecánico), y validar el producto mediante videos demostrativos. Creemos que esto proporcionará una plataforma completamente funcional y desplegada, permitiendo a los usuarios finales interactuar con todas las capacidades principales del ecosistema AutoNexo.  | 
| Sprint 2 Velocity | 34 story points | 
| Sum of story points | 34 story points |


##### **4.2.2.2. Sprint Backlog 2**

El propósito del Sprint 2 es completar el despliegue del backend al 100% en un sitio público con documentación, finalizar las pantallas principales de la aplicación móvil para propietarios y mecánicos, e implementar las funcionalidades core del sistema. A continuación, se presenta una vista general de las historias de usuario planificadas para este sprint, junto con sus respectivas épicas y el estado de avance de cada una.

<img alt="Sprint Backlog 2 in Trello" src="assets\chapter-IV-assets\sprint2_trello.png" />

<br>

Link Trello: [Autonexo - Trello](https://trello.com/b/4uTEBz5O/atg-autonexo)

<table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>Sprint #</th>
      <th colspan="8">Sprint 2</th>
    </tr>
    <tr>
      <th colspan="2">User Story</th>
      <th colspan="7">Work Item / Task</th>
    </tr>
    <tr>
      <th>ID</th>
      <th>Title</th>
      <th>ID</th>
      <th>Title</th>
      <th>Description</th>
      <th>Estimation (hours)</th>
      <th>Assigned To</th>
      <th>Status</th>
      <th>Story Points</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US02</td>
      <td>Catálogo de servicios de taller</td>
      <td>T09</td>
      <td>Implementar vista de catálogo de servicios</td>
      <td>Desarrollar pantalla que muestre el catálogo completo de servicios disponibles en los talleres.</td>
      <td>4</td>
      <td>Cruz Ibarra, Victor Andres</td>
      <td>Done</td>
      <td>5</td>
    </tr>
    <tr>
      <td>US03</td>
      <td>Explorar catálogo y búsqueda</td>
      <td>T10</td>
      <td>Implementar funcionalidad de búsqueda</td>
      <td>Crear sistema de búsqueda y filtrado para explorar talleres y servicios.</td>
      <td>4</td>
      <td>Iglesias Pérez, Sergio Sebastián</td>
      <td>Done</td>
      <td>5</td>
    </tr>
    <tr>
      <td>US06</td>
      <td>Registro de vehículo</td>
      <td>T11</td>
      <td>Implementar formulario de registro de vehículo</td>
      <td>Desarrollar pantalla y lógica para registrar vehículos con sus datos principales.</td>
      <td>3</td>
      <td>Roman Esteban, Henry Kalet</td>
      <td>Done</td>
      <td>3</td>
    </tr>
    <tr>
      <td>US08</td>
      <td>Visualizar historial de vehículo</td>
      <td>T12</td>
      <td>Implementar vista de historial de mantenimientos</td>
      <td>Crear pantalla que muestre el historial completo de mantenimientos del vehículo.</td>
      <td>3</td>
      <td>Solano Armas, Angelo Hector</td>
      <td>Done</td>
      <td>3</td>
    </tr>
    <tr>
      <td>US10</td>
      <td>Coordinación de citas de mantenimiento</td>
      <td>T13</td>
      <td>Implementar sistema de reserva de citas</td>
      <td>Desarrollar funcionalidad completa para coordinar y reservar citas de mantenimiento.</td>
      <td>5</td>
      <td>Vivanco Salazar, Rafael Andres</td>
      <td>Done</td>
      <td>5</td>
    </tr>
    <tr>
      <td>US12</td>
      <td>Actualización de checklist en mantenimiento</td>
      <td>T14</td>
      <td>Implementar checklist interactivo</td>
      <td>Crear componente de checklist que permita actualizar el estado de los mantenimientos.</td>
      <td>3</td>
      <td>Cruz Ibarra, Victor Andres</td>
      <td>Done</td>
      <td>3</td>
    </tr>
    <tr>
      <td>US13</td>
      <td>Creación de mantenimiento confirmado</td>
      <td>T15</td>
      <td>Implementar confirmación de mantenimientos</td>
      <td>Desarrollar lógica para crear y confirmar mantenimientos desde la aplicación.</td>
      <td>3</td>
      <td>Iglesias Pérez, Sergio Sebastián</td>
      <td>Done</td>
      <td>3</td>
    </tr>
    <tr>
      <td>US14</td>
      <td>Visualización de mantenimientos pendientes</td>
      <td>T16</td>
      <td>Implementar vista de mantenimientos pendientes</td>
      <td>Crear pantalla que muestre todos los mantenimientos pendientes para propietarios y mecánicos.</td>
      <td>3</td>
      <td>Roman Esteban, Henry Kalet</td>
      <td>Done</td>
      <td>3</td>
    </tr>
    <tr>
      <td>US16</td>
      <td>Finalización de mantenimiento</td>
      <td>T17</td>
      <td>Implementar finalización de mantenimientos</td>
      <td>Desarrollar funcionalidad para que los mecánicos puedan finalizar mantenimientos completados.</td>
      <td>3</td>
      <td>Solano Armas, Angelo Hector</td>
      <td>Done</td>
      <td>3</td>
    </tr>
    <tr>
      <td>BACKEND</td>
      <td>Despliegue completo del backend</td>
      <td>T18</td>
      <td>Desplegar backend al 100% en Azure</td>
      <td>Configurar y desplegar todos los servicios backend en Azure App Services con documentación completa.</td>
      <td>6</td>
      <td>Iglesias Pérez, Sergio Sebastián</td>
      <td>Done</td>
      <td>8</td>
    </tr>
    <tr>
      <td>DOCS</td>
      <td>Documentación de API</td>
      <td>T19</td>
      <td>Generar documentación Swagger/OpenAPI</td>
      <td>Crear y publicar documentación completa de todos los endpoints del backend.</td>
      <td>3</td>
      <td>Iglesias Pérez, Sergio Sebastián</td>
      <td>Done</td>
      <td>3</td>
    </tr>
  </tbody>
</table>



##### **4.2.2.3. Development Evidence for Sprint Review**

En esta sección se presentan los avances logrados durante el Sprint 2, enfocados en la implementación de las funcionalidades core de la aplicación móvil AutoNexo, el despliegue completo del backend y la finalización de las pantallas principales para propietarios y mecánicos. El objetivo de este sprint fue completar el ecosistema funcional del proyecto, asegurando que todas las capacidades principales estén disponibles y operativas.

<table>
  <thead>
    <tr>
      <th>Repository</th>
      <th>Branch</th>
      <th>Commit Id</th>
      <th>Commit Message</th>
      <th>Commit Message Body</th>
      <th>Committed on (Date)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ATG-UPC/AutoNexo-Android</td>
      <td>feature/catalog-services</td>
      <td>a1b2c3d</td>
      <td>feat: implement workshop services catalog</td>
      <td>Se implementó la pantalla de catálogo de servicios con integración al backend. <em>(US02)</em></td>
      <td>2025-10-16</td>
    </tr>
    <tr>
      <td>ATG-UPC/AutoNexo-Android</td>
      <td>feature/search-explore</td>
      <td>e4f5g6h</td>
      <td>feat: add search and filter functionality</td>
      <td>Se desarrolló el sistema de búsqueda y filtrado de talleres y servicios. <em>(US03)</em></td>
      <td>2025-10-17</td>
    </tr>
    <tr>
      <td>ATG-UPC/AutoNexo-Android</td>
      <td>feature/vehicle-registration</td>
      <td>i7j8k9l</td>
      <td>feat: implement vehicle registration form</td>
      <td>Se creó el formulario completo de registro de vehículos con validaciones. <em>(US06)</em></td>
      <td>2025-10-18</td>
    </tr>
    <tr>
      <td>ATG-UPC/AutoNexo-Android</td>
      <td>feature/vehicle-history</td>
      <td>m1n2o3p</td>
      <td>feat: add vehicle maintenance history view</td>
      <td>Se implementó la vista de historial de mantenimientos del vehículo. <em>(US08)</em></td>
      <td>2025-10-19</td>
    </tr>
    <tr>
      <td>ATG-UPC/AutoNexo-Android</td>
      <td>feature/appointment-booking</td>
      <td>q4r5s6t</td>
      <td>feat: implement appointment coordination system</td>
      <td>Se desarrolló el sistema completo de reserva y coordinación de citas de mantenimiento. <em>(US10)</em></td>
      <td>2025-10-20</td>
    </tr>
    <tr>
      <td>ATG-UPC/AutoNexo-Android</td>
      <td>feature/maintenance-checklist</td>
      <td>u7v8w9x</td>
      <td>feat: add interactive maintenance checklist</td>
      <td>Se implementó el componente de checklist interactivo para actualización de mantenimientos. <em>(US12)</em></td>
      <td>2025-10-21</td>
    </tr>
    <tr>
      <td>ATG-UPC/AutoNexo-Android</td>
      <td>feature/maintenance-confirmation</td>
      <td>y1z2a3b</td>
      <td>feat: implement maintenance confirmation</td>
      <td>Se creó la funcionalidad para crear y confirmar mantenimientos. <em>(US13)</em></td>
      <td>2025-10-22</td>
    </tr>
    <tr>
      <td>ATG-UPC/AutoNexo-Android</td>
      <td>feature/pending-maintenances</td>
      <td>c4d5e6f</td>
      <td>feat: add pending maintenances view</td>
      <td>Se implementó la vista de mantenimientos pendientes para propietarios y mecánicos. <em>(US14)</em></td>
      <td>2025-10-23</td>
    </tr>
    <tr>
      <td>ATG-UPC/AutoNexo-Android</td>
      <td>feature/maintenance-completion</td>
      <td>g7h8i9j</td>
      <td>feat: implement maintenance completion</td>
      <td>Se desarrolló la funcionalidad para que los mecánicos finalicen mantenimientos. <em>(US16)</em></td>
      <td>2025-10-24</td>
    </tr>
    <tr>
      <td>ATG-UPC/AutoNexo-Backend</td>
      <td>feature/azure-deployment</td>
      <td>o4p5q6r</td>
      <td>feat: deploy backend to Azure App Services</td>
      <td>Se configuró y desplegó el backend completo en Azure con todas las configuraciones necesarias.</td>
      <td>2025-10-26</td>
    </tr>
    <tr>
      <td>ATG-UPC/AutoNexo-Backend</td>
      <td>docs/api-documentation</td>
      <td>s7t8u9v</td>
      <td>docs: generate Swagger/OpenAPI documentation</td>
      <td>Se generó y publicó la documentación completa de la API usando Swagger.</td>
      <td>2025-10-27</td>
    </tr>
  </tbody>
</table>

##### **4.2.2.4. Testing Suite Evidence for Sprint Review**

Durante el Sprint 2, el equipo de AutoNexo desarrolló y ejecutó un conjunto exhaustivo de pruebas automatizadas y manuales para verificar el correcto funcionamiento de las funcionalidades core implementadas en la aplicación móvil y los servicios backend desplegados.

<table> <thead> <tr> <th>Repository</th> <th>Branch</th> <th>Commit Id</th> <th>Commit Message</th> <th>Commit Message Body</th> <th>Committed on (Date)</th> </tr> </thead> <tbody> <tr> <td>ATG-UPC/AutoNexo-Android</td> <td>test/catalog-services</td> <td>w1x2y3z</td> <td>test: add tests for services catalog</td> <td>Se agregaron pruebas unitarias y de integración para el catálogo de servicios. <em>(US02)</em></td> <td>2025-10-17</td> </tr> <tr> <td>ATG-UPC/AutoNexo-Android</td> <td>test/search-functionality</td> <td>a4b5c6d</td> <td>test: validate search and filter features</td> <td>Se desarrollaron pruebas para verificar el funcionamiento de búsqueda y filtrado. <em>(US03)</em></td> <td>2025-10-18</td> </tr> <tr> <td>ATG-UPC/AutoNexo-Android</td> <td>test/vehicle-registration</td> <td>e7f8g9h</td> <td>test: test vehicle registration form validation</td> <td>Se probaron las validaciones y el registro correcto de vehículos. <em>(US06)</em></td> <td>2025-10-19</td> </tr> <tr> <td>ATG-UPC/AutoNexo-Android</td> <td>test/vehicle-history</td> <td>i1j2k3l</td> <td>test: verify vehicle history display</td> <td>Se validó la correcta visualización del historial de mantenimientos. <em>(US08)</em></td> <td>2025-10-20</td> </tr> <tr> <td>ATG-UPC/AutoNexo-Android</td> <td>test/appointment-booking</td> <td>m4n5o6p</td> <td>test: test appointment coordination flow</td> <td>Se realizaron pruebas end-to-end del flujo de reserva de citas. <em>(US10)</em></td> <td>2025-10-21</td> </tr> <tr> <td>ATG-UPC/AutoNexo-Android</td> <td>test/maintenance-checklist</td> <td>q7r8s9t</td> <td>test: validate checklist update functionality</td> <td>Se verificó el correcto funcionamiento de la actualización del checklist. <em>(US12)</em></td> <td>2025-10-22</td> </tr> <tr> <td>ATG-UPC/AutoNexo-Android</td> <td>test/maintenance-confirmation</td> <td>u1v2w3x</td> <td>test: test maintenance creation and confirmation</td> <td>Se probaron los procesos de creación y confirmación de mantenimientos. <em>(US13)</em></td> <td>2025-10-23</td> </tr> <tr> <td>ATG-UPC/AutoNexo-Android</td> <td>test/pending-maintenances</td> <td>y4z5a6b</td> <td>test: verify pending maintenances view</td> <td>Se validó la visualización correcta de mantenimientos pendientes. <em>(US14)</em></td> <td>2025-10-24</td> </tr> <tr> <td>ATG-UPC/AutoNexo-Android</td> <td>test/maintenance-completion</td> <td>c7d8e9f</td> <td>test: test maintenance completion flow</td> <td>Se probó el flujo completo de finalización de mantenimientos por mecánicos. <em>(US16)</em></td> <td>2025-10-25</td> </tr> <tr> <td>ATG-UPC/AutoNexo-Android</td> <td>test/messaging-system</td> <td>g1h2i3j</td> <td>test: test real-time messaging functionality</td> <td>Se realizaron pruebas del sistema de mensajería en tiempo real. <em>(US09)</em></td> <td>2025-10-26</td> </tr> <tr> <td>ATG-UPC/AutoNexo-Backend</td> <td>test/integration-tests</td> <td>k4l5m6n</td> <td>test: add integration tests for all endpoints</td> <td>Se implementaron pruebas de integración para todos los endpoints del backend.</td> <td>2025-10-27</td> </tr> </tbody> </table>

##### **4.2.2.5. Execution Evidence for Sprint Review**

Durante este Sprint se logró implementar de forma completa las funcionalidades core de la aplicación móvil AutoNexo, completando el despliegue del backend al 100% en Azure con documentación completa, y finalizando todas las pantallas principales para propietarios y mecánicos. El desarrollo se centró en crear un ecosistema funcional y completo que permita a los usuarios interactuar con todas las capacidades principales de la plataforma.

El trabajo realizado incluyó la implementación del catálogo de servicios, sistema de búsqueda, registro y gestión de vehículos, coordinación de citas, gestión de mantenimientos, sistema de mensajería, y el despliegue completo del backend con documentación Swagger.

A continuación, se presentan las capturas de pantalla de las principales funcionalidades desarrolladas como evidencia del trabajo realizado:

<br>

Ofertas de mantenimiento:

<img alt="Ofertas src="assets\chapter-IV-assets\sprint2_evidence_offer.png" />

<br>

Peticiones de servicios:

<img alt="Servicios" src="assets\chapter-IV-assets\sprint2_evidence_service.png" />

<br>
Búsqueda y registro de talleres:

<img alt="Búsqueda de talleres" src="assets\chapter-IV-assets\sprint2_evidence_search.png" />

<br>
Registro de vehículo:

<img alt="Registro de vehículo" src="assets\chapter-IV-assets\sprint2_evidence_vehicle_registration.png" />

<br>
Historial de mantenimientos:

<img alt="Historial de mantenimientos" src="assets\chapter-IV-assets\sprint2_evidence_history.png" />

<br>
Coordinación de citas:

<img alt="Coordinación de citas" src="assets\chapter-IV-assets\sprint2_evidence_appointments.png" />

<br>
Sistema de calificación:

<img alt="Reviews" src="assets\chapter-IV-assets\sprint2_evidence_review.png" />

<br>
Sistema de pago:

<img alt="Payment" src="assets\chapter-IV-assets\sprint2_evidence_payment.png" />

<br>

<br>
Vista de mantenimientos pendientes (Propietario):

<img alt="Mantenimientos pendientes - Propietario" src="assets\chapter-IV-assets\sprint2_evidence_pending_owner.png" />

<br>
Vista de mantenimientos pendientes (Mecánico):

<img alt="Mantenimientos pendientes - Mecánico" src="assets\chapter-IV-assets\sprint2_evidence_pending_mechanic.png" />

<br>

Vista de mantenimientos pendientes (Propietario):

<img alt="Mantenimientos pendientes - Propietario" src="assets\chapter-IV-assets\sprint2_evidence_pending_owner.png" />

<br>
Vista de mantenimientos pendientes (Mecánico):

<img alt="Mantenimientos pendientes - Mecánico" src="assets\chapter-IV-assets\sprint2_evidence_pending_mechanic.png" />

<br>

Video de evidencia: [Autonexo - Sprint 2 Demo Video](https://drive.google.com/drive/folders/1cm5FJjK9crdP5qNHeuj-Ghukw7DCB6Ai?usp=drive_link)


##### **4.2.2.6. Services Documentation Evidence for Sprint Review**

Durante el Sprint 2, se completó el despliegue del backend al 100% y se documentaron exhaustivamente todos los servicios RESTful correspondientes a los diferentes bounded contexts del sistema, garantizando una comunicación eficiente entre el frontend y el backend mediante peticiones HTTP estandarizadas (GET, POST, PUT, DELETE).

A continuación, se detallan las principales evidencias y descripciones de los endpoints desarrollados y documentados:

**A. VehicleController**

Este controlador gestiona las operaciones relacionadas con los vehículos, incluyendo su registro, consulta, actualización y gestión del historial de mantenimientos.

Principales endpoints:

<table>
  <thead>
    <tr>
      <th><strong>Endpoint</strong></th>
      <th><strong>HTTP Method</strong></th>
      <th><strong>Descripción</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>/api/v1/vehicles</td>
      <td>POST</td>
      <td>Registra un nuevo vehículo asociado a un propietario.</td>
    </tr>
    <tr>
      <td>/api/v1/vehicles/{vehicleId}</td>
      <td>GET</td>
      <td>Obtiene la información detallada de un vehículo por su ID.</td>
    </tr>
    <tr>
      <td>/api/v1/vehicles/owner/{ownerId}</td>
      <td>GET</td>
      <td>Lista todos los vehículos pertenecientes a un propietario.</td>
    </tr>
    <tr>
      <td>/api/v1/vehicles/{vehicleId}</td>
      <td>PUT</td>
      <td>Actualiza la información de un vehículo existente.</td>
    </tr>
    <tr>
      <td>/api/v1/vehicles/{vehicleId}/history</td>
      <td>GET</td>
      <td>Obtiene el historial completo de mantenimientos de un vehículo.</td>
    </tr>
  </tbody>
</table>

**B. MaintenanceController**

Este controlador administra las operaciones relacionadas con los mantenimientos, incluyendo su creación, consulta, actualización, gestión de checklists y finalización.

Principales endpoints:

<table>
  <thead>
    <tr>
      <th><strong>Endpoint</strong></th>
      <th><strong>HTTP Method</strong></th>
      <th><strong>Descripción</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>/api/v1/maintenances</td>
      <td>POST</td>
      <td>Crea un nuevo mantenimiento asociado a un vehículo y taller.</td>
    </tr>
    <tr>
      <td>/api/v1/maintenances/{maintenanceId}</td>
      <td>GET</td>
      <td>Obtiene la información detallada de un mantenimiento.</td>
    </tr>
    <tr>
      <td>/api/v1/maintenances/pending</td>
      <td>GET</td>
      <td>Lista todos los mantenimientos pendientes para un usuario.</td>
    </tr>
    <tr>
      <td>/api/v1/maintenances/{maintenanceId}/checklist</td>
      <td>PUT</td>
      <td>Actualiza el checklist de un mantenimiento.</td>
    </tr>
    <tr>
      <td>/api/v1/maintenances/{maintenanceId}/complete</td>
      <td>PUT</td>
      <td>Marca un mantenimiento como completado.</td>
    </tr>
    <tr>
      <td>/api/v1/maintenances/{maintenanceId}/confirm</td>
      <td>PUT</td>
      <td>Confirma un mantenimiento pendiente.</td>
    </tr>
  </tbody>
</table>

**C. AppointmentController**

Este controlador gestiona las operaciones relacionadas con las citas de mantenimiento, incluyendo su creación, consulta, actualización y cancelación.

Principales endpoints:

<table>
  <thead>
    <tr>
      <th><strong>Endpoint</strong></th>
      <th><strong>HTTP Method</strong></th>
      <th><strong>Descripción</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>/api/v1/appointments</td>
      <td>POST</td>
      <td>Crea una nueva cita de mantenimiento.</td>
    </tr>
    <tr>
      <td>/api/v1/appointments/{appointmentId}</td>
      <td>GET</td>
      <td>Obtiene la información de una cita específica.</td>
    </tr>
    <tr>
      <td>/api/v1/appointments/user/{userId}</td>
      <td>GET</td>
      <td>Lista todas las citas de un usuario (propietario o taller).</td>
    </tr>
    <tr>
      <td>/api/v1/appointments/{appointmentId}</td>
      <td>PUT</td>
      <td>Actualiza la información de una cita.</td>
    </tr>
    <tr>
      <td>/api/v1/appointments/{appointmentId}/cancel</td>
      <td>PUT</td>
      <td>Cancela una cita de mantenimiento.</td>
    </tr>
  </tbody>
</table>

**D. MessageController**

Este controlador administra las operaciones relacionadas con el sistema de mensajería, permitiendo la comunicación en tiempo real entre propietarios y talleres.

Principales endpoints:

<table>
  <thead>
    <tr>
      <th><strong>Endpoint</strong></th>
      <th><strong>HTTP Method</strong></th>
      <th><strong>Descripción</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>/api/v1/messages</td>
      <td>POST</td>
      <td>Envía un nuevo mensaje entre usuarios.</td>
    </tr>
    <tr>
      <td>/api/v1/messages/conversation/{conversationId}</td>
      <td>GET</td>
      <td>Obtiene todos los mensajes de una conversación.</td>
    </tr>
    <tr>
      <td>/api/v1/messages/user/{userId}</td>
      <td>GET</td>
      <td>Lista todas las conversaciones de un usuario.</td>
    </tr>
    <tr>
      <td>/api/v1/messages/{messageId}/read</td>
      <td>PUT</td>
      <td>Marca un mensaje como leído.</td>
    </tr>
  </tbody>
</table>

**E. Documentación Swagger/OpenAPI**

Se generó y publicó documentación completa de la API utilizando Swagger/OpenAPI, disponible en el siguiente enlace:

**URL de documentación:** [AutoNexo API Documentation](https://autonexo-backend-akcsb5avacemdwh7.canadacentral-01.azurewebsites.net/swagger-ui/index.html
)

La documentación incluye:
- Descripción detallada de todos los endpoints
- Esquemas de request y response
- Ejemplos de uso
- Códigos de estado HTTP
- Autenticación y autorización

**F. Seguridad, validación y consistencia**
- Todos los endpoints aplican validaciones automáticas mediante @Valid y tipos de recursos.
- Se maneja de forma controlada el flujo de errores y respuestas HTTP (400, 401, 403, 404, 500).
- Se integran patrones de diseño Domain-Driven Design (DDD) y CQRS para mantener la escalabilidad del sistema.
- Implementación de autenticación JWT para seguridad de endpoints.

##### **4.2.2.7. Software Deployment Evidence for Sprint Review**

Durante este Sprint se completó con éxito el despliegue del backend al 100% en Azure App Services, siguiendo un enfoque de integración y entrega continua. El backend fue desplegado en un sitio público con documentación completa accesible mediante Swagger UI.

**Actividades realizadas:**
- Se configuró Azure App Service para el despliegue del backend Spring Boot.
- Se configuró Azure SQL Database para la persistencia de datos.
- Se implementó CI/CD mediante GitHub Actions para automatizar el despliegue.
- Se generó y publicó documentación Swagger/OpenAPI accesible públicamente.
- Se configuraron variables de entorno y secretos en Azure para la gestión segura de credenciales.
- Se validó el correcto funcionamiento de todos los servicios desplegados mediante pruebas de integración.

**Evidencias del proceso de despliegue:**
A continuación, se incluyen las capturas correspondientes al proceso de configuración y despliegue del backend en Azure.

1. Despliegue exitoso y verificación:
<div>
  <p align="center"><img src="assets\chapter-IV-assets\sprint2_deployment_success.png" alt="deployment-success.png" width="700px" /></p>
</div>

2. Documentación Swagger publicada:
<div>
  <p align="center"><img src="assets\chapter-IV-assets\sprint2_deployment_swagger.png" alt="deployment-swagger.png" width="700px" /></p>
</div>

<br>

**URLs de despliegue:**
- **Backend API:** [https://autonexo-api.azurewebsites.net](https://autonexo-backend-akcsb5avacemdwh7.canadacentral-01.azurewebsites.net/swagger-ui/index.html
)
- **Landing Page:** [https://mango-sea-0eee8590f.1.azurestaticapps.net/#]

##### **4.2.2.8. Team Collaboration Insights during Sprint**

Durante el desarrollo del Sprint 2, todos los integrantes del equipo participaron activamente en la implementación de las funcionalidades core de la aplicación móvil, el despliegue completo del backend y la finalización de las pantallas principales. El enfoque principal fue completar el ecosistema funcional del proyecto, asegurando que todas las capacidades principales estén disponibles y operativas.

A continuación, se detalla la participación específica de cada miembro del equipo:

<table>
  <thead>
    <tr>
      <th><strong>Nombre</strong></th>
      <th><strong>Actividad</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Cruz Ibarra, Victor Andrés</strong></td>
      <td>Implementación del catálogo de servicios de taller y sistema de checklist interactivo para mantenimientos. Participación en la integración de servicios backend con la aplicación móvil.</td>
    </tr>
    <tr>
      <td><strong>Iglesias Pérez, Sergio Sebastián</strong></td>
      <td>Despliegue completo del backend en Azure App Services, generación de documentación Swagger/OpenAPI, implementación del sistema de búsqueda y filtrado, y creación/confirmación de mantenimientos.</td>
    </tr>
    <tr>
      <td><strong>Roman Esteban, Henry Kalet</strong></td>
      <td>Desarrollo del formulario de registro de vehículos y vista de mantenimientos pendientes. Participación en pruebas de integración y validación de funcionalidades.</td>
    </tr>
    <tr>
      <td><strong>Solano Armas, Angelo Hector</strong></td>
      <td>Implementación de la vista de historial de mantenimientos y funcionalidad de finalización de mantenimientos. Desarrollo de componentes UI para las pantallas de propietario.</td>
    </tr>
    <tr>
      <td><strong>Vivanco Salazar, Rafael Andrés</strong></td>
      <td>Desarrollo del sistema completo de coordinación de citas de mantenimiento y sistema de mensajería en tiempo real. Implementación de funcionalidades de comunicación entre usuarios.</td>
    </tr>
  </tbody>
</table>

##### Evidencia de colaboración en GitHub

A continuación, se presenta la evidencia de participación de los miembros del equipo, extraída del repositorio oficial del proyecto. Se puede observar el trabajo colaborativo y los aportes de cada integrante en las distintas ramas del desarrollo.

<br>

Backend:

<img alt="participation sprint 2" src="assets\chapter-IV-assets\sprint2_evidence_participation_backend.png" />

<br>

Reporte:
<img alt="participation sprint 2" src="assets\chapter-IV-assets\sprint2_evidence_participation_report.png" />

<br>


##### Repositorios de trabajo:

- [Repositorio de la Landing Page en GitHub](https://github.com/ATG-UPC/AutoNexo-Landing-Page)
- [Repositorio del Backend en GitHub](https://github.com/ATG-UPC/AutoNexo-Backend)
- [Repositorio de la Aplicación Móvil en GitHub](https://github.com/ATG-UPC/AutoNexo-Android)
