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

| Repository                    | Branch                    | Commit Id | Commit Message                          | Commit Message Body                                                                                                     | Committed on (Date) |
| ----------------------------- | ------------------------- | --------- | --------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- | ------------------- |
| ATG-UPC/AutoNexo-Landing-Page | feature/landing-content   | 3fa219b   | feat: add main benefits section         | Se añadió la sección principal con texto descriptivo, beneficios clave y botones de llamada a la acción (CTA). *(US01)* | 2025-10-01          |
| ATG-UPC/AutoNexo-Landing-Page | feature/register-form     | 7c4f2d9   | feat: implement user registration form  | Se creó el formulario de registro con validación básica y estructura responsiva. *(US21)*                               | 2025-10-02          |
| ATG-UPC/AutoNexo-Landing-Page | feature/faq-support       | 61e3a20   | feat: add FAQ component                 | Se implementó el componente de preguntas frecuentes con diseño colapsable. *(US22)*                                     | 2025-10-03          |
| ATG-UPC/AutoNexo-Landing-Page | feature/contact-section   | b48df23   | feat: add contact form and store links  | Se añadieron el formulario de contacto y los botones con enlaces de descarga. *(US23)*                                  | 2025-10-04          |
| ATG-UPC/AutoNexo-Landing-Page | feature/plans-section     | d279b7a   | feat: add pricing plans section         | Se desarrolló la sección de planes de pago para talleres con maquetado responsivo. *(US28)*                             | 2025-10-05          |
| ATG-UPC/AutoNexo-Landing-Page | feature/mechanic-selector | 94fca31   | feat: add mechanic type selector        | Se implementó el componente que permite seleccionar el tipo de mecánico al registrarse. *(US29)*                        | 2025-10-06          |
| ATG-UPC/AutoNexo-Landing-Page | feature/workshop-code     | a12b57d   | feat: generate and share workshop code  | Se implementó la funcionalidad para generar y compartir el código de taller. *(US30)*                                   | 2025-10-07          |
| ATG-UPC/AutoNexo-Landing-Page | feature/navbar            | f57ce4a   | feat: add navigation bar and menu links | Se diseñó y programó la barra de navegación principal, mejorando la accesibilidad entre secciones. *(US32)*             | 2025-10-08          |



##### **4.2.1.4. Testing Suite Evidence for Sprint Review**

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

| **Endpoint**                                | **HTTP Method** | **Descripción**                                                     |
| ------------------------------------------- | --------------- | ------------------------------------------------------------------- |
| `/api/v1/workshops`                         | `POST`          | Crea un nuevo taller a partir de los datos del usuario propietario. |
| `/api/v1/workshops/my-workshop`             | `GET`           | Recupera la información del taller asociado al usuario autenticado. |
| `/api/v1/workshops/{workshopId}`            | `GET`           | Obtiene la información pública de un taller por su ID.              |
| `/api/v1/workshops/by-owner/{ownerUserId}`  | `GET`           | Recupera el taller perteneciente a un propietario específico.       |
| `/api/v1/workshops`                         | `GET`           | Lista todos los talleres activos.                                   |
| `/api/v1/workshops/by-tag`                  | `GET`           | Filtra los talleres según una etiqueta de capacidad.                |
| `/api/v1/workshops`                         | `PUT`           | Actualiza la información básica del taller.                         |
| `/api/v1/workshops/locations`               | `POST`          | Agrega una nueva ubicación al taller.                               |
| `/api/v1/workshops/service-templates`       | `POST`          | Registra una plantilla de servicio en el taller.                    |
| `/api/v1/workshops/tags`                    | `POST`          | Añade una etiqueta de capacidad (capability tag) al taller.         |
| `/api/v1/workshops/tags`                    | `PUT`           | Actualiza el conjunto completo de etiquetas de capacidad.           |
| `/api/v1/workshops/logo`                    | `POST`          | Carga y actualiza el logotipo del taller (usa Cloudinary).          |
| `/api/v1/workshops/photos`                  | `POST`          | Agrega una foto al carrusel de imágenes del taller.                 |
| `/api/v1/workshops/photos/{photoIndex}`     | `DELETE`        | Elimina una foto del carrusel de imágenes del taller.               |
| `/api/v1/workshops/catalog/categories`      | `GET`           | Obtiene las categorías de servicios disponibles en el catálogo.     |
| `/api/v1/workshops/catalog/services`        | `GET`           | Obtiene los servicios disponibles del catálogo general.             |
| `/api/v1/workshops/catalog/capability-tags` | `GET`           | Lista las etiquetas de capacidad disponibles.                       |

**B. InvitationController**

Este controlador administra las invitaciones que permiten a los talleres agregar nuevos miembros de personal (staff members) mediante códigos únicos.

Principales endpoints:

| **Endpoint**                                 | **HTTP Method** | **Descripción**                                                                |
| -------------------------------------------- | --------------- | ------------------------------------------------------------------------------ |
| `/api/v1/invitations/workshops/{workshopId}` | `POST`          | Crea una invitación asociada a un taller específico.                           |
| `/api/v1/invitations/accept`                 | `POST`          | Permite aceptar una invitación y registrar al usuario como miembro del taller. |
| `/api/v1/invitations/{code}`                 | `GET`           | Consulta la información de una invitación mediante su código único.            |
| `/api/v1/invitations/workshops/{workshopId}` | `GET`           | Lista todas las invitaciones emitidas por un taller determinado.               |


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

| **Nombre**                           | **Actividad**                                                                                                                                                                     |
| ------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Cruz Ibarra, Victor Andrés**       | Redacción del contenido principal de la landing page, incluyendo secciones de información general y llamados a la acción (CTAs). Apoyo en la estructura visual de los beneficios. |
| **Iglesias Pérez, Sergio Sebastián** | Implementación del formulario de registro de usuario (propietario o taller) y validaciones de entrada. Participación en la integración de enlaces entre secciones.                |
| **Roman Esteban, Henry Kalet**       | Desarrollo de la sección de **Preguntas Frecuentes (FAQ)**, maquetado de los elementos expandibles y redacción de las preguntas base.                                             |
| **Solano Armas, Angelo Hector**      | Configuración de la **sección de contacto y descarga de la aplicación**, asegurando la funcionalidad de los formularios y enlaces hacia las tiendas móviles.                      |
| **Vivanco Salazar, Rafael Andrés**   | Diseño e implementación de la **sección de planes de pago para talleres**, mostrando los distintos niveles de suscripción y sus beneficios comparativos.                          |

##### Evidencia de colaboración en GitHub

A continuación, se presenta la evidencia de participación de los miembros del equipo, extraída del repositorio oficial del proyecto. Se puede observar el trabajo colaborativo y los aportes de cada integrante en las distintas ramas del desarrollo.

<img alt="participation" src="assets\chapter-IV-assets\sprint1_evidence_participation.png" />


##### Repositorio de trabajo:

- [Repositorio de la Landing Page en GitHub](https://github.com/ATG-UPC/AutoNexo-Landing-Page)

### **4.3. Validation Interviews**

#### **4.3.1. Diseño de Entrevistas**

#### **4.3.2. Registro de Entrevistas**

#### **4.3.3. Evaluaciones según heurísticas**