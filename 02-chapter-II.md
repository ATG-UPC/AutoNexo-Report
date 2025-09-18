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
      <th>Fleetio <img src="assets\chapter-II\competidor_1.png" alt="Drivvo Logo" height="70" width="120"></th>
      <th>Drivvo <img src="assets\chapter-II\competidor_2.png" alt="Drivvo Logo" height="70" width="120"></th>
      <th>Whip Around <img src="assets\chapter-II\competidor_3.png" alt="Whip Around Logo" height="70" width="120"></th>
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

#### 2.5.1.2. Domain Message Flows Modeling

### **Descripción**

Esta sección describe los flujos de mensajes que se generan entre los Bounded Contexts, mostrando cómo los diferentes dominios del sistema colaboran a través de eventos y comandos. Cada flujo refleja un escenario de negocio completo que integra múltiples contextos en sus interacciones.

### **Escenarios de Integración**

#### **1. Solicitud y Reserva de Mantenimiento**

<img alt="scn_Solicitud y Reserva de Mantenimiento" src="assets\chapter-II-assets\scn_Soli.png" />

**Flujo de Integración:**
- El propietario solicita crear una reserva en **Matching & Booking(Command → CreateReservation)**
- **Matching & Booking** valida la información del vehículo consultando a **Vehicle & Maintenance (Query → CheckVehicleData).**
- **Matching & Booking** envía una consulta de disponibilidad a **Workshop (Query → CheckAvailability).**
- Si hay disponibilidad,**Workshop** responde con horarios válidos (Event → AvailabilityConfirmed).
- **Matching & Booking** confirma la reserva y emite ReservationConfirmed.
- **Notification** escucha el evento y envía una notificación push al propietario y al taller.


**Bounded Contexts Involucrados:**
- Matching & Booking → Vehicle & Maintenance → Workshop → Notification


#### **2. Creación de Mantenimiento Confirmado**

<img alt="scn_Creación de Mantenimiento Confirmado" src="assets\chapter-II-assets\scn_Crea.png">

**Flujo de Integración:**
- Una reserva aceptada en **Matching & Booking (Event → ReservationAccepted)** dispara la orden a **Vehicle & Maintenance (Command → CreateMaintenance).**
- **Vehicle & Maintenance** genera la checklist inicial y marca el mantenimiento con estado pendiente.
- **Vehicle & Maintenance** publica el evento (Event → MaintenanceCreated).
- **Notification** escucha el evento y envía un aviso al propietario.

**Bounded Contexts Involucrados:**
- Matching & Booking → Vehicle & Maintenance → Notification


#### **3. Avance de Mantenimiento y Checklist**

<img alt="scn_Avance de Mantenimiento y Checklist" src="assets\chapter-II-assets\scn_Ava.png">

**Flujo de Integración:**
- El taller actualiza tareas en la checklist desde **Workshop (Command → UpdateChecklist).**
- **Vehicle & Maintenance** procesa la actualización (Event → ChecklistUpdated).
- **Vehicle & Maintenance** publica el avance (Event → MaintenanceProgressed).
- **Notification** escucha el evento y envía una notificación al propietario sobre los avances.

**Bounded Contexts Involucrados:**
- Workshop → Vehicle & Maintenance → Notification


#### **4. Finalización de Mantenimiento y Actualización de Historial**

<img alt="scn_Finalización de Mantenimiento y Actualización de Historial" src="assets\chapter-II-assets\scn_Fin.png">

**Flujo de Integración:**
- El mecánico marca la finalización en **Workshop (Command → FinalizeMaintenance).**
- **Vehicle & Maintenance** registra el evento (Event → MaintenanceFinalized), genera el informe y actualiza el historial del vehículo.
- **Vehicle & Maintenance** publica el evento (Event → MaintenanceClosed) hacia **Trust & Reputation.**
- **Notification** escucha el evento y envía un aviso al propietario indicando el cierre del servicio.

**Bounded Contexts Involucrados:**
- Workshop → Vehicle & Maintenance → Trust & Reputation → Notification


#### **5. Calificación y Actualización de Reputación**

<img alt="scn_Calificación y Actualización de Reputación" src="assets\chapter-II-assets\scn_Cal.png">

**Flujo de Integración:**
- Tras un mantenimiento, el propietario envía una calificación en **Trust & Reputation (Command → RateMechanic).**
- **Trust & Reputation** actualiza el score y publica (Event → RatingRegistered).
- **Notification** consume el evento y envía un aviso al taller.
- De manera análoga, el taller también puede calificar al propietario.

**Bounded Contexts Involucrados:**
- Trust & Reputation → Notification

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

### 2.6.1 Bounded Context: IAM Context
<br>

#### 2.6.1.1 Domain Layer
<br>

#### 2.6.1.2 Interface Layer
<br>

#### 2.6.1.3 Application Layer
<br>

#### 2.6.1.4 Infrastructure Layer
<br>

#### 2.6.1.5 Bounded Context Software Architecture Component Level Diagrams
<br>

<img alt="Component-IAM" src="assets\chapter-II-assets\components\structurizr-101398-Component-006.png" />

#### 2.6.1.6 Bounded Context Software Architecture Code Level Diagrams
<br>

##### 2.6.1.6.1 Bounded Context Domain Layer Class Diagrams
<br>
<img alt="Class-IAM" src="assets\chapter-II-assets\bc\class-iam.png" />

##### 2.6.1.6.2 Bounded Context Database Design Diagram
<br>
<img alt="Database-IAM" src="assets\chapter-II-assets\bc\db-iam.png" />

### 2.6.2 Bounded Context: Workshop Context
<br>

#### 2.6.2.1 Domain Layer
<br>

#### 2.6.2.2 Interface Layer
<br>

#### 2.6.2.3 Application Layer
<br>

#### 2.6.2.4 Infrastructure Layer
<br>

#### 2.6.2.5 Bounded Context Software Architecture Component Level Diagrams
<br>

<img alt="Component-Workshops" src="assets\chapter-II-assets\components\structurizr-101398-Component-004.png" />

#### 2.6.2.6 Bounded Context Software Architecture Code Level Diagrams
<br>

##### 2.6.2.6.1 Bounded Context Domain Layer Class Diagrams
<br>
<img alt="Class-Workshop" src="assets\chapter-II-assets\bc\class-workshop.png" />

##### 2.6.2.6.2 Bounded Context Database Design Diagram
<br>
<img alt="Database-Workshop" src="assets\chapter-II-assets\bc\db-workshop.png" />

### 2.6.3 Bounded Context: Vehicle&Maintenance
<br>

#### 2.6.3.1 Domain Layer
<br>

#### 2.6.3.2 Interface Layer
<br>

#### 2.6.3.3 Application Layer
<br>

#### 2.6.3.4 Infrastructure Layer
<br>

#### 2.6.3.5 Bounded Context Software Architecture Component Level Diagrams
<br>
<img alt="Component-Vehicle-Maintenance" src="assets\chapter-II-assets\components\structurizr-101398-Component-001.png"/>

#### 2.6.3.6 Bounded Context Software Architecture Code Level Diagrams
<br>

##### 2.6.3.6.1 Bounded Context Domain Layer Class Diagrams
<br>
<img alt="Class-Vehicle" src="assets\chapter-II-assets\bc\class-vehicle.png" />

##### 2.6.3.6.2 Bounded Context Database Design Diagram
<br>
<img alt="Database-Vehicle" src="assets\chapter-II-assets\bc\db-vehicle.png" />

### 2.6.4 Bounded Context: Matching&Booking Context
<br>

#### 2.6.4.1 Domain Layer
<br>

#### 2.6.4.2 Interface Layer
<br>

#### 2.6.4.3 Application Layer
<br>

#### 2.6.4.4 Infrastructure Layer
<br>

#### 2.6.4.5 Bounded Context Software Architecture Component Level Diagrams
<br>

<img alt="Component-Matching-Booking" src="assets\chapter-II-assets\components\structurizr-101398-Component-003.png" />

#### 2.6.4.6 Bounded Context Software Architecture Code Level Diagrams
<br>

##### 2.6.4.6.1 Bounded Context Domain Layer Class Diagrams
<br>
<img alt="Class-Matching" src="assets\chapter-II-assets\bc\class-matching.png" />

##### 2.6.4.6.2 Bounded Context Database Design Diagram
<br>
<img alt="Database-Matching" src="assets\chapter-II-assets\bc\db-matching.png" />

### 2.6.5 Bounded Context: Trust&Reputation
<br>

#### 2.6.5.1 Domain Layer
<br>

#### 2.6.5.2 Interface Layer
<br>

#### 2.6.5.3 Application Layer
<br>

#### 2.6.5.4 Infrastructure Layer
<br>

#### 2.6.5.5 Bounded Context Software Architecture Component Level Diagrams
<br>

<img alt="Component-Trust" src="assets\chapter-II-assets\components\structurizr-101398-Component-002.png" />

#### 2.6.5.6 Bounded Context Software Architecture Code Level Diagrams
<br>

##### 2.6.5.6.1 Bounded Context Domain Layer Class Diagrams
<br>
<img alt="Class-trusting" src="assets\chapter-II-assets\bc\class-trusting.png" />

##### 2.6.5.6.2 Bounded Context Database Design Diagram
<br>
<img alt="Database-trusting" src="assets\chapter-II-assets\bc\db-trusting.png" />

### 2.6.6 Bounded Context: Subscription context
<br>

#### 2.6.6.1 Domain Layer
<br>

#### 2.6.6.2 Interface Layer
<br>

#### 2.6.6.3 Application Layer
<br>

#### 2.6.6.4 Infrastructure Layer
<br>

#### 2.6.6.5 Bounded Context Software Architecture Component Level Diagrams
<br>

<img alt="Component-Suscription" src="assets\chapter-II-assets\components\structurizr-101398-Component-005.png" />

#### 2.6.6.6 Bounded Context Software Architecture Code Level Diagrams
<br>

##### 2.6.6.6.1 Bounded Context Domain Layer Class Diagrams
<br>
<img alt="Class-payment" src="assets\chapter-II-assets\bc\class-payment.png" />

##### 2.6.6.6.2 Bounded Context Database Design Diagram
<br>
<img alt="Database-trusting" src="assets\chapter-II-assets\bc\db-payment.png" />

### 2.6.7 Bounded Context: Notifications context
<br>

#### 2.6.7.1 Domain Layer
<br>

#### 2.6.7.2 Interface Layer
<br>

#### 2.6.7.3 Application Layer
<br>

#### 2.6.7.4 Infrastructure Layer
<br>

#### 2.6.7.5 Bounded Context Software Architecture Component Level Diagrams
<br>

<img alt="Component-Notifications" src="assets\chapter-II-assets\components\structurizr-101398-Component-007.png" />

#### 2.6.7.6 Bounded Context Software Architecture Code Level Diagrams
<br>

##### 2.6.7.6.1 Bounded Context Domain Layer Class Diagrams
<br>
<img alt="Class-trusting" src="assets\chapter-II-assets\bc\class-payment.png" />

##### 2.6.7.6.2 Bounded Context Database Design Diagram
<br>
<img alt="Database-trusting" src="assets\chapter-II-assets\bc\db-payment.png" />