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

- AuEntoncestication (Autenticación): Proceso de verificar la identidad de un usuario mediante credenciales.

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
      <td>US01</td>
      <td>Visualizar información y beneficios (Landing Page)</td>
      <td>Como visitante, quiero visualizar la información general de la aplicación y sus beneficios, para entender qué ofrece antes de registrarme.</td>
      <td>
        <p><strong>Scenario 1 — Landing informativa:</strong><br>
          • Dado que un visitante accede a la landing page<br>
          • Cuando navega por la sección de información<br>
          • Entonces el sistema (o la página) presenta claramente los beneficios, secciones y llamados a la acción con información completa sobre el servicio.
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
          • Dado que el taller proporciona título, descripción, precio, duración, categorías y compatibilidades mínimas<br>
          • Cuando solicita publicar la oferta<br>
          • Entonces el sistema guarda la oferta con estado publicada, registra timestamps y la hace visible en el catálogo.
        </p>
        <p><strong>Scenario 2 — Campos obligatorios incompletos:</strong><br>
          • Dado que el taller omite campos obligatorios (ej. precio o categoría)<br>
          • Cuando intenta publicar la oferta<br>
          • Entonces el sistema rechaza la publicación y devuelve la lista de campos obligatorios faltantes.
        </p>
        <p><strong>Scenario 3 — Imágenes/validación:</strong><br>
          • Dado que el taller adjunta imágenes que exceden límites permitidos<br>
          • Cuando intenta subir las imágenes<br>
          • Entonces el sistema rechaza las imágenes que exceden el tamaño y acepta las válidas.
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
          • Dado que existen ofertas que coinciden con término o categoría<br>
          • Cuando el propietario busca por palabra clave, categoría o filtro<br>
          • Entonces el sistema devuelve una lista de ofertas coincidentes paginada y ordenable por distancia, precio, rating o relevancia.
        </p>
        <p><strong>Scenario 2 — Sin resultados:</strong><br>
          • Dado que no hay ofertas que coincidan con los criterios de búsqueda<br>
          • Cuando el propietario realiza la búsqueda<br>
          • Entonces el sistema devuelve una lista vacía y sugiere alternativas (otras categorías o ampliar rango).
        </p>
        <p><strong>Scenario 3 — Vista detalle:</strong><br>
          • Dado que el propietario solicita info de una oferta<br>
          • Cuando solicita ver el detalle de la oferta<br>
          • Entonces el sistema entrega la información completa de la oferta y los datos del taller (rating, ubicación, términos).
        </p>
      </td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US04</td>
      <td>Filtrar por servicio</td>
      <td>Como usuario, quiero filtrar por categorías de servicio (ej. cambio de aceite, frenos, afinamiento), para ver solo ofertas relevantes.</td>
      <td>
        <p><strong>Scenario 1 — Filtros básicos:</strong><br>
          • Dado que existen ofertas con distintas categorías<br>
          • Cuando el usuario aplica filtros por categoría o subcategoría<br>
          • Entonces el sistema devuelve únicamente las ofertas que cumplen los criterios seleccionados.
        </p>
        <p><strong>Scenario 2 — Filtros avanzados:</strong><br>
          • Dado que el usuario aplica filtros por compatibilidad (marca/motor/combustible)<br>
          • Cuando aplica dichos filtros<br>
          • Entonces el sistema muestra las ofertas compatibles y oculta las no compatibles.
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
          • Dado que existen talleres disponibles dentro del rango definido por el propietario<br>
          • Cuando solicita ver talleres cercanos<br>
          • Entonces el sistema lista los talleres ordenados por distancia.
        </p>
        <p><strong>Scenario 2 — Fallback por código postal:</strong><br>
          • Dado que el propietario no permite ubicación por GPS o GPS falla<br>
          • Cuando el propietario suministra código postal o ciudad<br>
          • Entonces el sistema busca talleres dentro del área indicada y devuelve resultados.
        </p>
        <p><strong>Scenario 3 — Sin talleres en rango:</strong><br>
          • Dado que no hay talleres en el rango definido<br>
          • Cuando solicita buscar<br>
          • Entonces el sistema muestra un mensaje indicando ausencia de talleres en ese rango y sugiere ampliar búsqueda.
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
          • Dado que el propietario proporciona todos los datos requeridos del vehículo (marca, modelo, año, placa, etc.)<br>
          • Cuando solicita guardar el registro<br>
          • Entonces el sistema asocia y almacena el vehículo en el perfil del propietario.
        </p>
        <p><strong>Scenario 2 — Registro incompleto:</strong><br>
          • Dado que el propietario omite uno o más campos obligatorios<br>
          • Cuando intenta guardar el registro<br>
          • Entonces el sistema devuelve un error indicando los campos faltantes y no crea el registro.
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
          • Dado que el propietario dispone de documentos o datos de mantenimientos previos<br>
          • Cuando incorpora la información o adjunta los documentos y confirma el registro del vehículo<br>
          • Entonces el sistema guarda el historial asociado al vehículo y lo marca como disponible para talleres autorizados.
        </p>
        <p><strong>Scenario 2 — Sin historial:</strong><br>
          • Dado que el propietario no tiene historial disponible<br>
          • Cuando finaliza el registro del vehículo<br>
          • Entonces el sistema crea el registro del vehículo sin historial asociado y lo deja marcado como “sin historial”.
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
          • Dado que el vehículo tiene registros previos de mantenimiento<br>
          • Cuando el taller solicita consultar el historial del vehículo<br>
          • Entonces el sistema entrega la lista de registros previos (fechas, tipo de servicio, taller, notas) de forma completa y ordenada.
        </p>
        <p><strong>Scenario 2 — Vehículo sin historial:</strong><br>
          • Dado que el vehículo no tiene registros previos<br>
          • Cuando el taller solicita el historial<br>
          • Entonces el sistema indica que no existen registros previos para ese vehículo.
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
          • Dado que dos usuarios (propietario y taller) desean comunicarse<br>
          • Cuando uno envía un mensaje<br>
          • Entonces el sistema entrega el mensaje al destinatario y registra la conversación.
        </p>
        <p><strong>Scenario 2 — Adjuntar fotos:</strong><br>
          • Dado que el remitente adjunta imágenes del vehículo<br>
          • Cuando envía el mensaje con adjuntos<br>
          • Entonces el sistema acepta imágenes dentro de los límites establecidos y las asocia a la conversación.
        </p>
        <p><strong>Scenario 3 — Notificación de nuevo mensaje:</strong><br>
          • Dado que llega un nuevo mensaje<br>
          • Cuando el destinatario está offline o en otra sección<br>
          • Entonces el sistema genera una notificación que informa la llegada del nuevo mensaje.
        </p>
        <p><strong>Scenario 4 — Reporte de abuso:</strong><br>
          • Dado que un usuario recibe mensajes inapropiados<br>
          • Cuando reporta la conversación por abuso<br>
          • Entonces el sistema registra la denuncia y marca la conversación para revisión.
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
          • Dado que el taller dispone de slots y el propietario solicita servicio<br>
          • Cuando el taller propone una fecha/hora y el propietario la acepta<br>
          • Entonces el sistema registra la cita en ambas agendas y la confirma a ambas partes.
        </p>
        <p><strong>Scenario 2 — Reprogramación:</strong><br>
          • Dado que existe una cita programada<br>
          • Cuando una de las partes solicita reprogramar y la otra acepta un nuevo slot disponible<br>
          • Entonces el sistema actualiza la cita y notifica los cambios.
        </p>
        <p><strong>Scenario 3 — Conflicto de agenda:</strong><br>
          • Dado que el slot propuesto ya está ocupado en la agenda del taller<br>
          • Cuando se intenta confirmar una cita que choca con otra<br>
          • Entonces el sistema rechaza la confirmación y solicita seleccionar otro slot.
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
          • Dado que llega un mensaje nuevo al usuario<br>
          • Cuando el mensaje es enviado por el remitente<br>
          • Entonces el sistema notifica al destinatario mediante notificación push.
        </p>
        <p><strong>Scenario 2 — Reserva confirmada:</strong><br>
          • Dado que una reserva o cita es confirmada<br>
          • Cuando la confirmación queda registrada<br>
          • Entonces el sistema notifica push a ambas partes.
        </p>
        <p><strong>Scenario 3 — Avance del mantenimiento:</strong><br>
          • Dado que el taller actualiza la checklist con un hito relevante<br>
          • Cuando el hito se marca como completado<br>
          • Entonces el sistema notifica al propietario el avance del servicio.
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
          • Dado que el taller está realizando un mantenimiento y existe una checklist asociada<br>
          • Cuando el taller marca una o varias tareas como realizadas<br>
          • Entonces el sistema actualiza el estado del mantenimiento y registra la marcación en la trazabilidad del servicio, además notifica el cambio al propietario.
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
          • Dado que el propietario ha aceptado una propuesta o reserva<br>
          • Cuando el taller confirma el inicio del servicio<br>
          • Entonces el sistema crea el registro de mantenimiento pendiente, genera la checklist inicial y asocia la reserva al mantenimiento.
        </p>
        <p><strong>Scenario 2 — Validación de datos antes de crear:</strong><br>
          • Dado que el taller intenta crear un mantenimiento desde una reserva<br>
          • Cuando el sistema valida que la reserva esté en estado "aceptada" y que todos los datos requeridos estén completos<br>
          • Entonces el sistema verifica la validez de la reserva antes de proceder con la creación del mantenimiento.
        </p>
        <p><strong>Scenario 3 — Generación automática de checklist:</strong><br>
          • Dado que se está creando un mantenimiento confirmado<br>
          • Cuando el sistema genera la checklist inicial basada en el tipo de servicio solicitado<br>
          • Entonces el sistema crea automáticamente las tareas estándar para ese tipo de mantenimiento y las marca como pendientes.
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
          • Dado que el taller tiene mantenimientos asignados<br>
          • Cuando consulta su listado de trabajos<br>
          • Entonces el sistema muestra la lista de servicios pendientes con su estado y prioridades.
        </p>
        <p><strong>Scenario 2 — Propietario: detalle de su mantenimiento:</strong><br>
          • Dado que el vehículo del propietario está en mantenimiento<br>
          • Cuando el propietario consulta el detalle del servicio en curso<br>
          • Entonces el sistema muestra el estado actual y la checklist asociada en tiempo real.
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
          • Dado que el vehículo está en mantenimiento y la checklist está completa<br>
          • Cuando el propietario solicita el detalle del servicio<br>
          • Entonces el sistema muestra todas las tareas completadas y las pendientes, con marcas temporales de cada avance, y resalta las tareas que han sido completadas.
        </p>
        <p><strong>Scenario 2 — Checklist en Progreso:</strong><br>
          • Dado que el vehículo está en mantenimiento y la checklist tiene tareas en progreso<br>
          • Cuando el propietario solicita el detalle del servicio<br>
          • Entonces el sistema muestra las tareas pendientes y las que están en progreso, con un indicador visual de progreso (por ejemplo, barra de progreso o porcentaje completado).
        </p>
        <p><strong>Scenario 3 — Actualización en Tiempo Real:</strong><br>
          • Dado que el vehículo está siendo atendido y las tareas de la checklist están siendo actualizadas<br>
          • Cuando el propietario visualiza la checklist<br>
          • Entonces el sistema actualiza la información en tiempo real, reflejando cualquier cambio en el estado de las tareas sin necesidad de recargar la página.
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
          • Dado que el taller ha completado todas las tareas de la checklist<br>
          • Cuando el taller marca el mantenimiento como finalizado<br>
          • Entonces el sistema solicita una confirmación de la finalización antes de cerrar el servicio, asegurando que no falten tareas.
        </p>
        <p><strong>Scenario 2 — Generación de Informe de Mantenimiento:</strong><br>
          • Dado que el mantenimiento ha sido finalizado y los resultados registrados<br>
          • Cuando el taller finaliza el servicio<br>
          • Entonces el sistema genera un informe final que incluye todos los detalles del mantenimiento (trabajos realizados, repuestos, observaciones, fechas) y lo guarda para su futura consulta en el historial del vehículo.
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
          • Dado que el propietario identifica un taller que desea priorizar<br>
          • Cuando añade el taller a su lista de favoritos<br>
          • Entonces el sistema almacena el taller en la lista de favoritos del propietario.
        </p>
        <p><strong>Scenario 2 — Quitar de favoritos:</strong><br>
          • Dado que el taller está en la lista de favoritos<br>
          • Cuando el propietario lo elimina<br>
          • Entonces el sistema lo retira de la lista de favoritos.
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
          • Dado que existen promociones activas de los talleres favoritos del propietario<br>
          • Cuando el propietario consulta el feed de promociones<br>
          • Entonces el sistema destaca las promociones de favoritos con datos de vigencia, cupos y precio promocional.
        </p>
        <p><strong>Scenario 2 — Mostrar condiciones de promo:</strong><br>
          • Dado que una promoción tiene condiciones (cupos limitados, vigencia)<br>
          • Cuando el propietario revisa la promo<br>
          • Entonces el sistema muestra las condiciones completas y la disponibilidad actual.
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
          • Dado que la cancelación se realiza dentro de la ventana configurable (ej. >3h antes de la cita)<br>
          • Cuando el propietario solicita cancelar la reserva<br>
          • Entonces el sistema cambia el estado a cancelada, notifica al taller y aplica la política sin penalidad.
        </p>
        <p><strong>Scenario 2 — Cancelación fuera de ventana:</strong><br>
          • Dado que la cancelación se realiza fuera de la ventana permitida (ej. <3h antes)<br>
          • Cuando el propietario solicita cancelar<br>
          • Entonces el sistema rechaza o aplica la política de penalidad según reglas y notifica al taller.
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
          • Dado que el taller marca un mantenimiento como finalizado y registra los resultados (servicios realizados, repuestos, observaciones)<br>
          • Cuando el registro de cierre queda confirmado<br>
          • Entonces el sistema añade automáticamente ese mantenimiento al historial del vehículo y lo hace visible en el historial.
        </p>
        <p><strong>Scenario 2 — Mantenimiento cancelado:</strong><br>
          • Cuando que un mantenimiento es cancelado antes de su finalización<br>
          • Cuando el taller registra la cancelación con motivo<br>
          • Entonces el sistema no añade el mantenimiento al historial y marca el evento como cancelado (sin entrada en historial de servicios realizados).
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
          • Dado que el visitante proporciona los datos necesarios y usa un email único<br>
          • Cuando confirma el registro<br>
          • Entonces el sistema crea la cuenta, la asocia al rol elegido y envía confirmación por correo.
        </p>
        <p><strong>Scenario 2 — Email duplicado:</strong><br>
          • Dado que el email ya está registrado en el sistema<br>
          • Cuando el visitante intenta registrarse con ese email<br>
          • Entonces el sistema impide la duplicación y sugiere recuperar la cuenta o usar otro email.
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
          • Dado que el visitante necesita información o tiene una duda común<br>
          • Cuando accede a la sección de FAQ o al enlace de soporte<br>
          • Entonces el sistema presenta respuestas categorizadas y ofrece un medio de contacto para soporte en caso de requerir atención personalizada.
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
          • Dado que el visitante busca contactar al equipo o descargar la app<br>
          • Cuando consulta la sección de contacto y descarga<br>
          • Entonces el sistema (la landing) muestra un formulario de contacto funcional y enlaces claros para descargar la app en tiendas compatibles.
        </p>
        <p><strong>Scenario 2 — Envío de formulario de contacto:</strong><br>
          • Dado que el visitante completa el formulario de contacto con datos válidos<br>
          • Cuando envía el formulario<br>
          • Entonces el sistema procesa el mensaje, envía confirmación al visitante y notifica al equipo de soporte sobre la nueva consulta.
        </p>
        <p><strong>Scenario 3 — Descarga según dispositivo:</strong><br>
          • Dado que el visitante accede desde diferentes dispositivos (iOS, Android, desktop)<br>
          • Cuando hace clic en el enlace de descarga<br>
          • Entonces el sistema redirige automáticamente a la tienda de aplicaciones correspondiente (App Store, Google Play) o muestra opciones para ambos sistemas.
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
          • Dado que el mantenimiento está finalizado y el servicio está asociado al propietario<br>
          • Cuando el propietario registra una calificación (1–5) y un comentario para ese servicio<br>
          • Entonces el sistema guarda la reseña, la asocia al servicio y actualiza la calificación promedio del taller.
        </p>
        <p><strong>Scenario 2 — Restricción de una reseña por servicio:</strong><br>
          • Dado que el propietario ya calificó ese servicio<br>
          • Cuando intenta agregar una segunda reseña para el mismo servicio<br>
          • Entonces el sistema impide la duplicación y sugiere editar la reseña existente.
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
          • Dado que el mantenimiento fue finalizado y corresponde al taller que presta el servicio<br>
          • Cuando el taller registra una calificación y comentario sobre el propietario para ese servicio<br>
          • Entonces el sistema guarda la evaluación y la asocia al perfil del propietario, contribuyendo a su reputación.
        </p>
        <p><strong>Scenario 2 — Restricción de calificación duplicada:</strong><br>
          • Dado que el taller ya calificó al propietario para un servicio específico<br>
          • Cuando intenta calificar nuevamente al mismo propietario para el mismo servicio<br>
          • Entonces el sistema impide la calificación duplicada y sugiere editar la calificación existente.
        </p>
        <p><strong>Scenario 3 — Calificación con comentario opcional:</strong><br>
          • Dado que el taller desea calificar al propietario<br>
          • Cuando proporciona una calificación numérica (1-5) y opcionalmente un comentario<br>
          • Entonces el sistema acepta la calificación con o sin comentario y actualiza la reputación promedio del propietario.
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
          • Dado que el taller tiene reseñas y calificaciones previas<br>
          • Cuando el propietario solicita la reputación del taller<br>
          • Entonces el sistema muestra calificación promedio, número de reseñas, comentarios recientes y total de servicios realizados, con opciones de ordenar/comparar.
        </p>
        <p><strong>Scenario 2 — Filtro por Rango de Calificación:</strong><br>
          • Dado que el propietario desea consultar talleres con cierta calificación<br>
          • Cuando el propietario aplica un filtro de calificación<br>
          • Entonces el sistema muestra únicamente los talleres que cumplen con el rango de calificación seleccionado (por ejemplo, calificación de 4 estrellas o más).
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
          • Dado que el propietario tiene calificaciones previas de otros talleres<br>
          • Cuando el taller solicita la reputación del propietario asociada a la reserva<br>
          • Entonces el sistema muestra la calificación promedio, comentarios y número de mantenimientos previos.
        </p>
        <p><strong>Scenario 2 — Propietario sin historial:</strong><br>
          • Dado que el propietario no tiene calificaciones previas en el sistema<br>
          • Cuando el taller consulta la reputación del propietario<br>
          • Entonces el sistema indica que es un usuario nuevo sin historial de calificaciones y muestra información básica del perfil.
        </p>
        <p><strong>Scenario 3 — Filtrado por tipo de servicio:</strong><br>
          • Dado que el propietario tiene calificaciones de diferentes tipos de servicios<br>
          • Cuando el taller consulta la reputación específica para el tipo de servicio solicitado<br>
          • Entonces el sistema muestra calificaciones relevantes al tipo de servicio y un promedio específico para esa categoría.
        </p>
      </td>
      <td>EP06</td>
    </tr>
    <tr>
      <td>US28</td>
      <td>Visualizar planes de pago para talleres (Landing Page)</td>
      <td>Como visitante interesado en registrar mi taller,
      quiero visualizar los planes de pago y beneficios disponibles en la landing page,
      para evaluar cuál se adapta mejor a las necesidades de mi negocio antes de registrarme.</td>
      <td>
        <p><strong>Scenario 1 — Visualización de planes disponibles:</strong><br>
          • Dado que un visitante accede a la landing page<br>
          • Cuando navega a la sección de “Planes”<br>
          • Entonces el sistema muestra una lista clara de planes (pro y premium) con precios, duración y beneficios detallados.
        </p>
        <p><strong>Scenario 2 — Acceso al registro desde un plan:</strong><br>
          • Dado que el visitante revisa un plan y desea contratarlo<br>
          • Cuando hace clic en el botón “Registrarme” o “Elegir este plan”<br>
          • Entonces el sistema redirige al formulario de registro preseleccionando el plan elegido.
        </p>
      </td>
      <td>EP07</td>
    </tr>
    <tr>
  <td>US29</td>
  <td>Seleccionar tipo de mecánico</td>
  <td>Como mecánico, quiero seleccionar si soy un mecánico independiente o un mecánico con taller, para configurar correctamente mi perfil dentro de la aplicación.</td>
  <td>
    <p><strong>Scenario 1 — Selección inicial:</strong><br>
      • Dado que el usuario ha iniciado sesión como mecánico por primera vez<br>
      • Cuando el sistema le solicita definir su tipo de cuenta<br>
      • Entonces el sistema muestra dos opciones: “Mecánico con taller” y “Mecánico que pertenece a un taller”.</p>
    <p><strong>Scenario 2 — Confirmación de selección:</strong><br>
      • Dado que el mecánico selecciona un tipo de cuenta<br>
      • Cuando confirma la selección<br>
      • Entonces el sistema guarda el tipo de perfil y redirige a la configuración correspondiente.</p>
  </td>
  <td>EP01</td>
</tr>
<tr>
  <td>US30</td>
  <td>Generar y compartir código de taller</td>
  <td>Como mecánico con taller, quiero generar un código único de invitación, para compartirlo con otros mecánicos y que puedan unirse a mi taller en la aplicación.</td>
  <td>
    <p><strong>Scenario 1 — Generación de código único:</strong><br>
      • Dado que el mecánico tiene un perfil de tipo “con taller”<br>
      • Cuando accede a la sección de administración del taller<br>
      • Entonces el sistema genera un código alfanumérico único que identifica su taller.</p>
    <p><strong>Scenario 2 — Compartir código:</strong><br>
      • Dado que el código fue generado exitosamente<br>
      • Cuando el mecánico selecciona la opción “Compartir código”<br>
      • Entonces el sistema permite copiar el código o enviarlo mediante enlace directo (por mensaje o correo).</p>
  </td>
  <td>EP01</td>
</tr>
<tr>
  <td>US31</td>
  <td>Unirse a un taller mediante código</td>
  <td>Como mecánico que pertenece a un taller, quiero ingresar el código único del taller, para vincular mi cuenta correctamente al grupo de trabajo.</td>
  <td>
    <p><strong>Scenario 1 — Código válido:</strong><br>
      • Dado que el mecánico tiene el código proporcionado por un taller<br>
      • Cuando ingresa el código en la aplicación y confirma<br>
      • Entonces el sistema valida el código y asocia el perfil del mecánico al taller correspondiente.</p>
    <p><strong>Scenario 2 — Código inválido o expirado:</strong><br>
      • Dado que el código ingresado no existe o ha expirado<br>
      • Cuando el mecánico intenta unirse<br>
      • Entonces el sistema muestra un mensaje de error indicando que el código no es válido y ofrece reintentar o solicitar un nuevo código.</p>
  </td>
  <td>EP01</td>
</tr>
<tr>
  <td>US32</td>
  <td>Navegación mediante barra de menú</td>
  <td>Como usuario, quiero navegar fácilmente entre las secciones principales de la aplicación mediante una barra de menú, para acceder rápidamente a las funciones que necesito.</td>
  <td>
    <p><strong>Scenario 1 — Acceso desde barra principal:</strong><br>
      • Dado que el usuario se encuentra dentro de la aplicación<br>
      • Cuando utiliza la barra de navegación inferior o lateral<br>
      • Entonces el sistema redirige correctamente a las secciones seleccionadas (Inicio, Taller, Mantenimientos, Perfil, etc.).</p>
    <p><strong>Scenario 2 — Indicador visual de sección activa:</strong><br>
      • Dado que el usuario cambia entre secciones<br>
      • Cuando selecciona una nueva opción en la barra<br>
      • Entonces el sistema actualiza el icono o color de la sección activa para indicar visualmente dónde se encuentra el usuario.</p>
  </td>
  <td>EP03</td>
</tr>
    <tr>
            <td>TS01</td>
            <td>Implementar endpoint para registrar y gestionar vehículos (POST, PUT, DELETE /vehicles)</td>
            <td>Como developer, quiero exponer endpoints para registrar, actualizar y eliminar vehículos, para que los propietarios puedan gestionar sus datos básicos.</td>
            <td>
                <p><strong>Scenario 1 — Registro exitoso:</strong><br>
                    • Dado que el cuerpo contiene datos válidos<br>
                    • Cuando se envía la solicitud<br>
                    • Entonces se responde con 201 Created y el vehículo queda vinculado al propietario.
                </p>
                <p><strong>Scenario 2 — Registro incompleto:</strong><br>
                    • Dado que faltan campos obligatorios<br>
                    • Cuando se envía la solicitud<br>
                    • Entonces se responde con 400 Bad Request indicando los campos faltantes.
                </p>
                <p><strong>Scenario 3 — Actualización exitosa:</strong><br>
                    • Dado que el ID del vehículo existe<br>
                    • Cuando se actualiza con datos válidos<br>
                    • Entonces se responde con 200 OK y los datos se reflejan.
                </p>
                <p><strong>Scenario 4 — Eliminación exitosa:</strong><br>
                    • Dado que el ID existe<br>
                    • Cuando se solicita eliminar<br>
                    • Entonces se responde con 204 No Content.
                </p>
                <p><strong>Scenario 5 — ID no encontrado:</strong><br>
                    • Dado que el vehículo no existe<br>
                    • Cuando se intenta actualizar o eliminar<br>
                    • Entonces se responde con 404 Not Found.
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
                    • Dado que el cuerpo tiene documentos válidos<br>
                    • Cuando se envía la solicitud<br>
                    • Entonces se responde con 201 Created y se vincula al vehículo.
                </p>
                <p><strong>Scenario 2 — Consulta de historial existente:</strong><br>
                    • Dado que el vehículo tiene historial<br>
                    • Cuando se consulta el endpoint<br>
                    • Entonces se responde con 200 OK y la lista de mantenimientos.
                </p>
                <p><strong>Scenario 3 — Vehículo sin historial:</strong><br>
                    • Dado que no hay registros previos<br>
                    • Cuando se consulta el historial<br>
                    • Entonces se responde con 204 No Content.
                </p>
                <p><strong>Scenario 4 — Vehículo no encontrado:</strong><br>
                    • Dado que el ID no existe<br>
                    • Cuando se consulta el historial<br>
                    • Entonces se responde con 404 Not Found.
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
                    • Dado que los datos requeridos son completos<br>
                    • Cuando se publica el servicio<br>
                    • Entonces se responde con 201 Created.
                </p>
                <p><strong>Scenario 2 — Campos incompletos:</strong><br>
                    • Dado que faltan datos obligatorios<br>
                    • Cuando se envía la solicitud<br>
                    • Entonces se responde con 400 Bad Request.
                </p>
                <p><strong>Scenario 3 — Actualización exitosa:</strong><br>
                    • Dado que el servicio existe<br>
                    • Cuando se actualiza con datos válidos<br>
                    • Entonces se responde con 200 OK.
                </p>
                <p><strong>Scenario 4 — Eliminación exitosa:</strong><br>
                    • Dado que el servicio existe<br>
                    • Cuando se solicita eliminar<br>
                    • Entonces se responde con 204 No Content.
                </p>
                <p><strong>Scenario 5 — ID no encontrado:</strong><br>
                    • Dado que el servicio no existe<br>
                    • Cuando se intenta actualizar o eliminar<br>
                    • Entonces se responde con 404 Not Found.
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
                    • Dado que los datos son válidos<br>
                    • Cuando se crea una reserva<br>
                    • Entonces se responde con 201 Created.
                </p>
                <p><strong>Scenario 2 — Cancelación dentro de ventana permitida:</strong><br>
                    • Dado que la cancelación cumple las reglas<br>
                    • Cuando se solicita cancelar la reserva<br>
                    • Entonces se responde con 200 OK y estado “cancelada”.
                </p>
                <p><strong>Scenario 3 — Cancelación fuera de ventana:</strong><br>
                    • Dado que la cancelación no cumple la política<br>
                    • Cuando se solicita cancelar<br>
                    • Entonces se responde con 409 Conflict o la política definida.
                </p>
                <p><strong>Scenario 4 — Reserva no encontrada:</strong><br>
                    • Dado que el ID no existe<br>
                    • Cuando se consulta o cancela la reserva<br>
                    • Entonces se responde con 404 Not Found.
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
                    • Dado que el cuerpo es válido<br>
                    • Cuando se envía un mensaje<br>
                    • Entonces se responde con 201 Created y se almacena la conversación.
                </p>
                <p><strong>Scenario 2 — Adjuntar imágenes:</strong><br>
                    • Dado que se adjuntan imágenes dentro de límites permitidos<br>
                    • Cuando se envía el mensaje<br>
                    • Entonces se responde con 201 Created y archivos asociados.
                </p>
                <p><strong>Scenario 3 — Consulta de mensajes:</strong><br>
                    • Dado que existen mensajes previos<br>
                    • Cuando se consulta la conversación<br>
                    • Entonces se responde con 200 OK y la lista.
                </p>
                <p><strong>Scenario 4 — Conversación inexistente:</strong><br>
                    • Dado que no hay mensajes<br>
                    • Cuando se consulta la conversación<br>
                    • Entonces se responde con 204 No Content.
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
                    • Dado que los datos son válidos<br>
                    • Cuando se registra la reseña<br>
                    • Entonces se responde con 201 Created.
                </p>
                <p><strong>Scenario 2 — Calificación duplicada:</strong><br>
                    • Dado que ya existe una reseña para el mismo servicio<br>
                    • Cuando se intenta registrar otra<br>
                    • Entonces se responde con 409 Conflict.
                </p>
                <p><strong>Scenario 3 — Consulta de reputación existente:</strong><br>
                    • Dado que el taller o propietario tiene reseñas<br>
                    • Cuando se consulta la reputación<br>
                    • Entonces se responde con 200 OK con estadísticas.
                </p>
                <p><strong>Scenario 4 — Sin calificaciones previas:</strong><br>
                    • Dado que no existen reseñas<br>
                    • Cuando se consulta la reputación<br>
                    • Entonces se responde con 204 No Content.
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
                    • Dado que existen servicios que coinciden con los filtros<br>
                    • Cuando se consulta el endpoint<br>
                    • Entonces se responde con 200 OK con arreglo de servicios.
                </p>
                <p><strong>Scenario 2 — Sin resultados:</strong><br>
                    • Dado que no existen coincidencias<br>
                    • Cuando se consulta el endpoint<br>
                    • Entonces se responde con 200 OK con un arreglo vacío y sugerencias.
                </p>
                <p><strong>Scenario 3 — Vista detalle de servicio:</strong><br>
                    • Dado que se solicita ver un servicio específico<br>
                    • Cuando se consulta el detalle<br>
                    • Entonces se responde con 200 OK con la información completa.
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
            • Dado que existen talleres en el rango definido<br>
            • Cuando se consulta el endpoint<br>
            • Entonces se responde con 200 OK con lista ordenada por distancia.
        </p>
        <p><strong>Scenario 2 — GPS no disponible:</strong><br>
            • Dado que no se puede usar la ubicación por GPS<br>
            • Cuando se consulta con código postal<br>
            • Entonces se responde con 200 OK con talleres en esa zona.
        </p>
        <p><strong>Scenario 3 — Sin talleres:</strong><br>
            • Dado que no hay talleres disponibles<br>
            • Cuando se realiza la búsqueda<br>
            • Entonces se responde con 200 OK con un arreglo vacío y sugerencia de ampliar rango.
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
            • Dado que el taller existe<br>
            • Cuando se envía la solicitud de agregar<br>
            • Entonces se responde con 201 Created.
        </p>
        <p><strong>Scenario 2 — Quitar de favoritos:</strong><br>
            • Dado que el taller está en la lista de favoritos<br>
            • Cuando se envía la solicitud de eliminar<br>
            • Entonces se responde con 204 No Content.
        </p>
        <p><strong>Scenario 3 — Listar favoritos:</strong><br>
            • Dado que el usuario tiene talleres favoritos<br>
            • Cuando se consulta el endpoint<br>
            • Entonces se responde con 200 OK con la lista.
        </p>
        <p><strong>Scenario 4 — Taller no encontrado:</strong><br>
            • Dado que el taller no existe<br>
            • Cuando se consulta o elimina<br>
            • Entonces se responde con 404 Not Found.
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
            • Dado que existen promociones activas<br>
            • Cuando se consulta el endpoint<br>
            • Entonces se responde con 200 OK con condiciones.
        </p>
        <p><strong>Scenario 2 — Sin promociones activas:</strong><br>
            • Dado que no existen promociones<br>
            • Cuando se consulta el endpoint<br>
            • Entonces se responde con 204 No Content.
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
            • Dado que el taller propone una cita y el propietario la acepta<br>
            • Cuando se confirma la solicitud<br>
            • Entonces se responde con 201 Created.
        </p>
        <p><strong>Scenario 2 — Reprogramación exitosa:</strong><br>
            • Dado que existe una cita programada<br>
            • Cuando se solicita reprogramar con un nuevo slot válido<br>
            • Entonces se responde con 200 OK.
        </p>
        <p><strong>Scenario 3 — Conflicto de agenda:</strong><br>
            • Dado que el slot ya está ocupado<br>
            • Cuando se intenta confirmar<br>
            • Entonces se responde con 409 Conflict.
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
            • Dado que un usuario recibe un mensaje<br>
            • Cuando el sistema lo registra<br>
            • Entonces se envía una notificación push.
        </p>
        <p><strong>Scenario 2 — Reserva confirmada:</strong><br>
            • Dado que se confirma una reserva<br>
            • Cuando el sistema guarda la confirmación<br>
            • Entonces se envía una notificación push a ambas partes.
        </p>
        <p><strong>Scenario 3 — Avance checklist:</strong><br>
            • Dado que el taller actualiza un hito de la checklist<br>
            • Cuando el cambio se guarda<br>
            • Entonces se envía una notificación push al propietario.
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
            • Dado que existe una reserva aceptada<br>
            • Cuando el taller confirma el inicio<br>
            • Entonces se responde con 201 Created.
        </p>
        <p><strong>Scenario 2 — Actualización de checklist:</strong><br>
            • Dado que existe un mantenimiento activo<br>
            • Cuando se marcan tareas como realizadas<br>
            • Entonces se responde con 200 OK.
        </p>
        <p><strong>Scenario 3 — Visualizar mantenimientos pendientes:</strong><br>
            • Dado que existen mantenimientos activos<br>
            • Cuando se consulta la lista<br>
            • Entonces se responde con 200 OK.
        </p>
        <p><strong>Scenario 4 — Finalización:</strong><br>
            • Dado que todas las tareas están completadas<br>
            • Cuando se marca como finalizado<br>
            • Entonces se responde con 200 OK con registro completo.
        </p>
        <p><strong>Scenario 5 — ID no encontrado:</strong><br>
            • Dado que el mantenimiento no existe<br>
            • Cuando se consulta o actualiza<br>
            • Entonces se responde con 404 Not Found.
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
            • Dado que el visitante proporciona datos válidos<br>
            • Cuando se envía la solicitud<br>
            • Entonces se responde con 201 Created con rol asignado.
        </p>
        <p><strong>Scenario 2 — Email duplicado:</strong><br>
            • Dado que el email ya está registrado<br>
            • Cuando se intenta registrar<br>
            • Entonces se responde con 409 Conflict.
        </p>
        <p><strong>Scenario 3 — Consulta de usuario existente:</strong><br>
            • Dado que el usuario existe<br>
            • Cuando se consulta su información<br>
            • Entonces se responde con 200 OK.
        </p>
        <p><strong>Scenario 4 — Usuario no encontrado:</strong><br>
            • Dado que el usuario no existe<br>
            • Cuando se consulta el endpoint<br>
            • Entonces se responde con 404 Not Found.
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
        • Dado que existen entradas en la FAQ<br>
        • Cuando se consulta el endpoint<br>
        • Entonces se responde con 200 OK con la lista.
    </p>
    <p><strong>Scenario 2 — FAQ vacío:</strong><br>
        • Dado que no hay registros en FAQ<br>
        • Cuando se consulta el endpoint<br>
        • Entonces se responde con 204 No Content.
    </p>
    <p><strong>Scenario 3 — Ticket de soporte creado:</strong><br>
        • Dado que un visitante envía un ticket válido<br>
        • Cuando se procesa la solicitud<br>
        • Entonces se responde con 201 Created.
    </p>
    <p><strong>Scenario 4 — Contacto enviado:</strong><br>
        • Dado que un visitante completa el formulario de contacto<br>
        • Cuando se envía la solicitud<br>
        • Entonces se responde con 201 Created.
    </p>
  </td>
  <td>EP08</td>
</tr>
  <tr>
  <td>SP-01</td>
  <td>Investigación de la Integración de Stripe para el Procesamiento de Pagos</td>
  <td>Como equipo de desarrollo, queremos investigar cómo integrar Stripe para el procesamiento de pagos en la plataforma Autonexo, para asegurarnos de que sea una solución adecuada para manejar pagos de manera segura y eficiente.</td>
  <td>
    <p><strong>Scenario 1 — Revisión de documentación Stripe:</strong><br>• Dado acceso a la documentación de la API de Stripe<br>• Cuando se revisan las opciones disponibles para el procesamiento de pagos (Payments, Checkout, Mobile SDKs, Stripe.js)<br>• Entonces se debe definir si Stripe es adecuado para la integración en Autonexo.</p>
    <p><strong>Scenario 2 — Comparación de tarifas:</strong><br>• Dado las tarifas de Stripe<br>• Cuando se comparan los costos con otros sistemas de pagos en el mercado<br>• Entonces se debe decidir si Stripe es la opción más económica para Autonexo.</p>
    <p><strong>Scenario 3 — Validación de suscripciones:</strong><br>• Dado las opciones de suscripción de Stripe<br>• Cuando se determina si la plataforma de Autonexo requiere un modelo de suscripción mensual<br>• Entonces se debe confirmar que Stripe es compatible con este modelo.</p>
    <p><strong>Scenario 4 — Integración móvil:</strong><br>• Dado las capacidades de integración de Stripe con plataformas móviles (iOS/Android)<br>• Cuando se verifica la documentación de integración con Mobile SDKs<br>• Entonces se debe confirmar que Stripe es fácil de integrar con las aplicaciones móviles de Autonexo.</p>
    <p><strong>Scenario 5 — Prueba de pago en entorno sandbox:</strong><br>• Dado que la integración de Stripe se prueba en un entorno de pruebas<br>• Cuando se realiza una transacción de pago utilizando un flujo de pago de prueba<br>• Entonces se debe verificar que el pago se procese correctamente y que la información de pago se guarde de manera segura.</p>
    <p><strong>Scenario 6 — Cumplimiento de normativas:</strong><br>• Dado que el procesamiento de pagos debe ser seguro<br>• Cuando se revisa el cumplimiento de normativas (PCI-DSS, tokenización)<br>• Entonces se debe garantizar que Stripe cumpla con los estándares de seguridad necesarios.</p>
    <p><strong>Scenario 7 — Compatibilidad con backend:</strong><br>• Dado que la integración afecta frontend y backend<br>• Cuando se verifica la compatibilidad de Stripe con el backend (Spring Boot)<br>• Entonces se debe asegurar que endpoints RESTful y webhooks funcionen correctamente.</p>
    <p><strong>Scenario 8 — Prueba de carga:</strong><br>• Dado que Autonexo podría tener alto volumen de transacciones<br>• Cuando se realizan pruebas de carga<br>• Entonces se debe asegurar que Stripe maneje gran volumen de pagos sin afectar rendimiento.</p>
    <p><strong>Scenario 9 — Tiempo de procesamiento:</strong><br>• Dado que el procesamiento debe ser rápido<br>• Cuando se miden los tiempos de latencia<br>• Entonces los pagos no deben exceder los 3 segundos.</p>
    <p><strong>Scenario 10 — Documentación de integración:</strong><br>• Dado que la integración requiere documentación<br>• Cuando se documentan los pasos de integración<br>• Entonces se debe crear un informe detallado con problemas y soluciones.</p>
    <p><strong>Scenario 11 — Usabilidad del flujo de pago:</strong><br>• Dado que el flujo de pago debe ser fácil de usar<br>• Cuando se prueba con usuarios simulados en entorno de pruebas<br>• Entonces se debe asegurar que la experiencia sea intuitiva, rápida y sin errores.</p>
  </td>
  <td>No corresponde</td>
</tr>
<tr>
  <td>SP-02</td>
  <td>Investigación de Google Maps para la Localización de Mecánicos</td>
  <td>Como equipo de desarrollo, quiero investigar la integración de Google Maps para la localización de mecánicos, para ofrecer a los conductores la capacidad de encontrar mecánicos cercanos de manera rápida y eficiente.</td>
  <td>
    <p><strong>Scenario 1 — Revisión de documentación:</strong><br>• Dado que el equipo tiene acceso a la documentación de la API de Google Maps<br>• Cuando el equipo investigue las opciones para implementar mapas interactivos y localización<br>• Entonces deberán determinar si la Google Maps API es adecuada para la integración en Autonexo.</p>
    <p><strong>Scenario 2 — Análisis de costos:</strong><br>• Dado que el equipo ha analizado los costos asociados a Google Maps API<br>• Cuando comparen los costos con los beneficios que aportará la integración de la localización<br>• Entonces deberán decidir si Google Maps es económicamente viable para la plataforma.</p>
    <p><strong>Scenario 3 — Pruebas de localización:</strong><br>• Dado que el equipo ha implementado la API de Google Maps para la localización<br>• Cuando realicen pruebas con la función de búsqueda de mecánicos<br>• Entonces deberán asegurarse de que los resultados sean rápidos y precisos.</p>
    <p><strong>Scenario 4 — Pruebas de rendimiento:</strong><br>• Dado que se ha integrado la Google Maps API<br>• Cuando realicen pruebas de rendimiento en la carga del mapa y los resultados de búsqueda<br>• Entonces deberán garantizar que el sistema cargue los resultados en menos de 3 segundos.</p>
    <p><strong>Scenario 5 — Precisión en la ubicación:</strong><br>• Dado que la API de Google Maps está implementada<br>• Cuando un usuario busque mecánicos cercanos<br>• Entonces deberán asegurarse de que la ubicación del mecánico sea precisa en el mapa.</p>
    <p><strong>Scenario 6 — Compatibilidad móvil:</strong><br>• Dado que Autonexo debe ser compatible con dispositivos móviles<br>• Cuando el equipo prueba la integración en dispositivos móviles (iOS/Android)<br>• Entonces deberán garantizar que la localización funcione correctamente en ambas plataformas.</p>
    <p><strong>Scenario 7 — Usabilidad de la interfaz:</strong><br>• Dado que la experiencia del usuario es crucial<br>• Cuando implementen la funcionalidad de localización en las aplicaciones móviles y web<br>• Entonces deberán asegurarse de que la interfaz de usuario sea fácil de usar y eficiente.</p>
    <p><strong>Scenario 8 — Integración backend:</strong><br>• Dado que la integración de Google Maps debe trabajar con el backend<br>• Cuando el equipo verifique la comunicación entre la API de Google Maps y el backend de Autonexo<br>• Entonces deberán asegurarse de que los datos de ubicación se sincronicen correctamente en tiempo real.</p>
  </td>
  <td>No corresponde</td>
</tr>
<tr>
  <td>SP-03</td>
  <td>Evaluación de Sistemas de Notificaciones Push</td>
  <td>Como equipo de desarrollo, quiero investigar los sistemas de notificaciones push para enviar alertas de mantenimientos próximos a los usuarios, para mejorar la experiencia del usuario y asegurarnos de que nunca se olviden de los mantenimientos.</td>
  <td>
    <p><strong>Scenario 1 — Comparación de opciones:</strong><br>• Dado que el equipo ha identificado varias opciones de sistemas de notificaciones push como Firebase y OneSignal<br>• Cuando investiguen las características y capacidades de cada uno<br>• Entonces deberán decidir cuál es el más adecuado para la plataforma Autonexo.</p>
    <p><strong>Scenario 2 — Prueba con Firebase:</strong><br>• Dado que el equipo ha probado la implementación de Firebase Cloud Messaging<br>• Cuando envíen una notificación push de prueba<br>• Entonces deberán confirmar que la notificación se recibe correctamente en dispositivos iOS y Android.</p>
    <p><strong>Scenario 3 — Facilidad de integración:</strong><br>• Dado que el equipo ha implementado Firebase Cloud Messaging<br>• Cuando evalúen la facilidad de integración en el frontend y backend<br>• Entonces deberán determinar si la integración es sencilla y eficiente para la plataforma.</p>
    <p><strong>Scenario 4 — Calidad de la notificación:</strong><br>• Dado que el equipo ha implementado la función de notificaciones push<br>• Cuando un usuario reciba una notificación sobre un mantenimiento próximo<br>• Entonces deberán asegurarse de que la notificación sea clara, visible y llegue sin demoras.</p>
    <p><strong>Scenario 5 — Notificaciones programadas:</strong><br>• Dado que el equipo ha implementado la funcionalidad de notificaciones programadas<br>• Cuando se configure una notificación para ser enviada 24 horas antes de un mantenimiento<br>• Entonces se deberá verificar que la notificación se envíe correctamente en el momento programado.</p>
    <p><strong>Scenario 6 — Evaluación de OneSignal:</strong><br>• Dado que se han considerado otras opciones de notificaciones push como OneSignal<br>• Cuando se investiguen sus características y ventajas comparativas<br>• Entonces deberán decidir si OneSignal es una alternativa viable a Firebase para la plataforma.</p>
    <p><strong>Scenario 7 — Personalización:</strong><br>• Dado que el equipo ha implementado la función de notificaciones push<br>• Cuando se personaliza el contenido de las notificaciones (como texto, imágenes, botones)<br>• Entonces deberán asegurar que las notificaciones sean personalizables según las necesidades del usuario.</p>
    <p><strong>Scenario 8 — Escalabilidad:</strong><br>• Dado que la plataforma Autonexo puede crecer en número de usuarios<br>• Cuando se evalúe la capacidad de Firebase y otras opciones para manejar un gran volumen de notificaciones<br>• Entonces deberán determinar si el sistema puede escalar eficientemente sin afectar el rendimiento.</p>
    <p><strong>Scenario 9 — Seguridad:</strong><br>• Dado que la seguridad de las notificaciones es crucial<br>• Cuando se revisa la seguridad en el envío de las notificaciones (como autenticación, encriptación)<br>• Entonces deberán garantizar que el sistema de notificaciones cumpla con los estándares de seguridad necesarios.</p>
  </td>
  <td>No corresponde</td>
</tr>
<tr>
  <td>SP-04</td>
  <td>Investigación de Herramientas de Reportes de Mantenimiento</td>
  <td>Como equipo de desarrollo, quiero investigar herramientas como Power BI o Tableau para generar informes detallados sobre el mantenimiento de los vehículos, para mejorar la toma de decisiones y dar a los usuarios acceso a datos importantes.</td>
  <td>
    <p><strong>Scenario 1 — Comparación de herramientas:</strong><br>• Dado que el equipo ha identificado herramientas como Power BI y Tableau<br>• Cuando investiguen las características y capacidades de cada herramienta<br>• Entonces deberán seleccionar la herramienta que mejor se adapte a las necesidades de informes de mantenimiento de Autonexo.</p>
    <p><strong>Scenario 2 — Prueba con Power BI:</strong><br>• Dado que el equipo ha probado Power BI con datos de prueba<br>• Cuando creen un reporte básico<br>• Entonces deberán evaluar si la herramienta proporciona visualizaciones claras y útiles para los usuarios.</p>
    <p><strong>Scenario 3 — Prueba con Tableau:</strong><br>• Dado que el equipo ha probado Tableau para la creación de reportes<br>• Cuando realicen un análisis de desempeño<br>• Entonces deberán asegurar que Tableau sea capaz de manejar grandes volúmenes de datos de manera eficiente.</p>
    <p><strong>Scenario 4 — Facilidad de uso:</strong><br>• Dado que Power BI y Tableau tienen interfaces diferentes<br>• Cuando se comparen la facilidad de uso de ambas herramientas<br>• Entonces deberán elegir la herramienta más fácil de usar para el equipo de desarrollo y los usuarios finales.</p>
    <p><strong>Scenario 5 — Costos:</strong><br>• Dado que ambas herramientas tienen modelos de precios distintos<br>• Cuando se comparen los costos de uso de Power BI y Tableau<br>• Entonces deberán decidir cuál herramienta ofrece la mejor relación calidad-precio para Autonexo.</p>
    <p><strong>Scenario 6 — Personalización:</strong><br>• Dado que los informes deben adaptarse a diferentes necesidades<br>• Cuando el equipo personalice los informes en Power BI y Tableau<br>• Entonces deberán garantizar que las herramientas permitan una amplia personalización de los informes, incluyendo gráficos, tablas y filtros.</p>
    <p><strong>Scenario 7 — Visualización:</strong><br>• Dado que se requiere una visualización clara de los datos de mantenimiento<br>• Cuando se comparen las capacidades de visualización de Power BI y Tableau<br>• Entonces deberán decidir cuál herramienta ofrece las mejores opciones de visualización para facilitar la toma de decisiones.</p>
    <p><strong>Scenario 8 — Integración con base de datos:</strong><br>• Dado que los datos de mantenimiento de Autonexo están almacenados en una base de datos<br>• Cuando el equipo integre Power BI y Tableau con los datos<br>• Entonces deberán asegurar que ambas herramientas puedan acceder a los datos de manera eficiente y sin errores.</p>
    <p><strong>Scenario 9 — Escalabilidad:</strong><br>• Dado que la plataforma Autonexo puede crecer en volumen de datos<br>• Cuando el equipo evalúe la escalabilidad de Power BI y Tableau<br>• Entonces deberán determinar si ambas herramientas pueden manejar el crecimiento futuro de los datos sin afectar el rendimiento.</p>
  </td>
  <td>No corresponde</td>
</tr>
<tr>
  <td>SP-05</td>
  <td>Investigación de Técnicas de Caching para Mejorar el Rendimiento</td>
  <td>Como equipo de desarrollo, quiero investigar técnicas de caching como Redis o Memcached, para mejorar el rendimiento de la plataforma y reducir los tiempos de carga.</td>
  <td>
    <p><strong>Scenario 1 — Comparación de opciones:</strong><br>• Dado que el equipo ha considerado opciones como Redis y Memcached<br>• Cuando investiguen las características y ventajas de cada uno<br>• Entonces deberán seleccionar la opción que mejor se adapte a las necesidades de Autonexo.</p>
    <p><strong>Scenario 2 — Prueba con Redis:</strong><br>• Dado que el equipo ha implementado una solución de caching en Redis<br>• Cuando realicen pruebas de rendimiento en una función crítica<br>• Entonces deberán verificar si el tiempo de respuesta mejora significativamente.</p>
    <p><strong>Scenario 3 — Prueba con Memcached:</strong><br>• Dado que el equipo ha probado el caching de Memcached<br>• Cuando comparen los tiempos de respuesta en diferentes pruebas de carga<br>• Entonces deberán decidir si Memcached es adecuado para el uso en Autonexo.</p>
    <p><strong>Scenario 4 — Facilidad de integración:</strong><br>• Dado que Redis y Memcached tienen implementaciones y configuraciones distintas<br>• Cuando el equipo evalúe la facilidad de integración de cada sistema en la arquitectura de Autonexo<br>• Entonces deberán determinar cuál es más sencillo de implementar y mantener.</p>
    <p><strong>Scenario 5 — Escalabilidad:</strong><br>• Dado que Autonexo puede crecer en volumen de usuarios y datos<br>• Cuando se evalúe la escalabilidad de Redis y Memcached<br>• Entonces deberán garantizar que la opción seleccionada pueda manejar un crecimiento significativo sin afectar el rendimiento.</p>
    <p><strong>Scenario 6 — Seguridad:</strong><br>• Dado que la seguridad es un factor crítico en la integración de caching<br>• Cuando se revisen las medidas de seguridad de Redis y Memcached (como la encriptación de datos)<br>• Entonces deberán confirmar que la solución de caching cumple con los requisitos de seguridad necesarios.</p>
    <p><strong>Scenario 7 — Consumo de recursos:</strong><br>• Dado que las soluciones de caching deben ser eficientes en el uso de recursos<br>• Cuando se mida el consumo de CPU y memoria al implementar Redis o Memcached<br>• Entonces deberán asegurar que la solución elegida no afecte negativamente los recursos de Autonexo.</p>
    <p><strong>Scenario 8 — Alta disponibilidad:</strong><br>• Dado que la alta disponibilidad es crucial para el sistema de caching<br>• Cuando se simulen fallos en Redis o Memcached<br>• Entonces deberán verificar que la solución seleccionada pueda recuperarse correctamente sin perder datos importantes.</p>
  </td>
  <td>No corresponde</td>
</tr>
<tr>
  <td>SP-06</td>
  <td>Evaluación de Herramientas de Seguridad para la Plataforma</td>
  <td>Como equipo de seguridad, quiero investigar herramientas de seguridad como OWASP ZAP o Burp Suite para realizar pruebas de penetración y asegurarnos de que la plataforma esté segura.</td>
  <td>
    <p><strong>Scenario 1 — Comparación de herramientas:</strong><br>• Dado que el equipo ha considerado herramientas como OWASP ZAP y Burp Suite<br>• Cuando investiguen las características de cada una<br>• Entonces deberán decidir cuál es la mejor herramienta para realizar pruebas de seguridad en Autonexo.</p>
    <p><strong>Scenario 2 — Escaneo de vulnerabilidades con OWASP ZAP:</strong><br>• Dado que el equipo ha implementado una prueba de seguridad con OWASP ZAP<br>• Cuando realicen un escaneo de vulnerabilidades<br>• Entonces deberán identificar todas las posibles brechas de seguridad en el sistema.</p>
    <p><strong>Scenario 3 — Prueba de penetración con Burp Suite:</strong><br>• Dado que el equipo ha implementado Burp Suite para pruebas de seguridad<br>• Cuando realicen pruebas de penetración<br>• Entonces deberán asegurarse de que la plataforma esté segura contra ataques comunes.</p>
    <p><strong>Scenario 4 — Facilidad de uso:</strong><br>• Dado que OWASP ZAP y Burp Suite tienen interfaces y configuraciones distintas<br>• Cuando el equipo evalúe la facilidad de uso de ambas herramientas<br>• Entonces deberán decidir cuál herramienta es más fácil de integrar y utilizar en el flujo de trabajo de Autonexo.</p>
    <p><strong>Scenario 5 — Detección de vulnerabilidades críticas:</strong><br>• Dado que el objetivo es detectar vulnerabilidades críticas en la plataforma<br>• Cuando el equipo pruebe las capacidades de detección de vulnerabilidades de OWASP ZAP y Burp Suite<br>• Entonces deberán asegurarse de que ambas herramientas detecten las vulnerabilidades clave en Autonexo.</p>
    <p><strong>Scenario 6 — Configuraciones de seguridad:</strong><br>• Dado que las configuraciones de seguridad son esenciales en las pruebas de penetración<br>• Cuando el equipo evalúe las configuraciones de seguridad de OWASP ZAP y Burp Suite<br>• Entonces deberán determinar si las herramientas permiten una configuración detallada y personalizada según las necesidades de Autonexo.</p>
    <p><strong>Scenario 7 — Integración en el flujo de desarrollo:</strong><br>• Dado que las pruebas de seguridad deben integrarse con el flujo de desarrollo de Autonexo<br>• Cuando el equipo evalúe cómo OWASP ZAP y Burp Suite se integran con las herramientas y procesos de desarrollo existentes<br>• Entonces deberán garantizar que las herramientas se integren sin interrumpir el flujo de trabajo de desarrollo.</p>
    <p><strong>Scenario 8 — Informes de seguridad:</strong><br>• Dado que los informes de seguridad son cruciales para la corrección de vulnerabilidades<br>• Cuando el equipo revise los informes generados por OWASP ZAP y Burp Suite<br>• Entonces deberán asegurarse de que los informes sean claros, detallados y proporcionen las recomendaciones necesarias para corregir las vulnerabilidades encontradas.</p>
  </td>
  <td>No corresponde</td>
</tr>
<tr>
  <td>SP-07</td>
  <td>Investigación de Plataforma para Gestión de Suscripciones</td>
  <td>Como equipo de desarrollo, quiero investigar plataformas como Recurly o Stripe Billing para gestionar suscripciones y automatizar el proceso de pagos recurrentes en la plataforma.</td>
  <td>
    <p><strong>Scenario 1 — Comparación de plataformas:</strong><br>• Dado que el equipo ha considerado plataformas como Recurly y Stripe Billing<br>• Cuando investiguen las funcionalidades y capacidades de cada plataforma<br>• Entonces deberán seleccionar la plataforma más adecuada para gestionar las suscripciones de Autonexo.</p>
    <p><strong>Scenario 2 — Prueba con Recurly:</strong><br>• Dado que el equipo ha probado la implementación de Recurly con datos de prueba<br>• Cuando creen un ciclo de suscripción y realicen un pago de prueba<br>• Entonces deberán verificar que la plataforma maneje correctamente los pagos recurrentes.</p>
    <p><strong>Scenario 3 — Prueba con Stripe Billing:</strong><br>• Dado que el equipo ha probado Stripe Billing para gestionar suscripciones<br>• Cuando realicen una prueba de suscripción con Stripe Billing<br>• Entonces deberán asegurarse de que la plataforma maneje correctamente los pagos recurrentes.</p>
    <p><strong>Scenario 4 — Comparación de costos:</strong><br>• Dado que ambas plataformas tienen estructuras de precios diferentes<br>• Cuando se comparen los costos de Recurly y Stripe Billing<br>• Entonces deberán decidir cuál plataforma ofrece la mejor relación calidad-precio para Autonexo.</p>
    <p><strong>Scenario 5 — Integración con backend:</strong><br>• Dado que la plataforma de suscripciones debe integrarse con el backend de Autonexo<br>• Cuando el equipo evalúe la facilidad de integración de Recurly y Stripe Billing con el backend (Spring Boot)<br>• Entonces deberán garantizar que ambas plataformas se integren de manera sencilla y eficiente.</p>
    <p><strong>Scenario 6 — Seguridad en pagos:</strong><br>• Dado que la seguridad es fundamental en los pagos recurrentes<br>• Cuando el equipo revise las medidas de seguridad de Recurly y Stripe Billing<br>• Entonces deberán garantizar que ambas plataformas cumplan con los estándares de seguridad necesarios, como PCI-DSS.</p>
    <p><strong>Scenario 7 — Reportes de suscripciones:</strong><br>• Dado que es necesario gestionar los datos de clientes y suscripciones<br>• Cuando se utilicen las herramientas de reportes de Recurly y Stripe Billing<br>• Entonces deberán asegurarse de que las plataformas generen informes detallados y fáciles de usar sobre las suscripciones.</p>
  </td>
  <td>No corresponde</td>
</tr>
<tr>
  <td>SP-08</td>
  <td>Investigación de API de Localización para Mejorar la Búsqueda de Mecánicos</td>
  <td>Como equipo de desarrollo, quiero investigar APIs de localización como Google Maps, Mapbox o Here para mejorar la búsqueda de mecánicos cercanos, ofreciendo una experiencia más eficiente y precisa a los conductores.</td>
  <td>
    <p><strong>Scenario 1 — Comparación de APIs:</strong><br>• Dado que el equipo ha considerado APIs como Google Maps, Mapbox o Here<br>• Cuando investiguen las características y opciones de integración de cada API<br>• Entonces deberán seleccionar la mejor API para la localización en Autonexo.</p>
    <p><strong>Scenario 2 — Prueba con Google Maps:</strong><br>• Dado que el equipo ha implementado la API de Google Maps para la localización<br>• Cuando realicen pruebas de búsqueda de mecánicos cercanos<br>• Entonces deberán asegurarse de que la función de localización sea precisa y eficiente.</p>
    <p><strong>Scenario 3 — Prueba con Mapbox:</strong><br>• Dado que el equipo ha implementado la API de Mapbox para la localización<br>• Cuando realicen pruebas de búsqueda de mecánicos cercanos<br>• Entonces deberán asegurarse de que la función de localización sea precisa y eficiente.</p>
    <p><strong>Scenario 4 — Prueba con Here:</strong><br>• Dado que el equipo ha implementado la API de Here para la localización<br>• Cuando realicen pruebas de búsqueda de mecánicos cercanos<br>• Entonces deberán asegurarse de que la función de localización sea precisa y eficiente.</p>
    <p><strong>Scenario 5 — Comparación de costos:</strong><br>• Dado que cada API tiene diferentes modelos de precios<br>• Cuando comparen los costos de Google Maps, Mapbox y Here<br>• Entonces deberán decidir cuál API ofrece la mejor relación calidad-precio para la plataforma.</p>
    <p><strong>Scenario 6 — Facilidad de integración:</strong><br>• Dado que Google Maps, Mapbox y Here tienen implementaciones y configuraciones distintas<br>• Cuando el equipo evalúe la facilidad de integración de cada API con la plataforma Autonexo<br>• Entonces deberán determinar cuál API es más sencilla de implementar y mantener.</p>
    <p><strong>Scenario 7 — Escalabilidad:</strong><br>• Dado que la plataforma Autonexo puede crecer en volumen de usuarios y mecánicos<br>• Cuando el equipo evalúe la escalabilidad de Google Maps, Mapbox y Here<br>• Entonces deberán asegurarse de que todas las APIs puedan manejar un gran volumen de solicitudes sin afectar el rendimiento.</p>
    <p><strong>Scenario 8 — Precisión en ubicaciones:</strong><br>• Dado que la precisión es clave en la búsqueda de mecánicos cercanos<br>• Cuando el equipo pruebe las APIs de Google Maps, Mapbox y Here en diferentes ubicaciones<br>• Entonces deberán asegurarse de que todas las APIs proporcionen ubicaciones precisas y fiables.</p>
    <p><strong>Scenario 9 — Compatibilidad móvil:</strong><br>• Dado que las aplicaciones de Autonexo están disponibles en dispositivos móviles<br>• Cuando el equipo evalúe la compatibilidad de Google Maps, Mapbox y Here con dispositivos móviles (iOS/Android)<br>• Entonces deberán asegurarse de que todas las APIs funcionen correctamente en plataformas móviles.</p>
    <p><strong>Scenario 10 — Funcionalidades adicionales:</strong><br>• Dado que tanto Google Maps, Mapbox y Here ofrecen características adicionales (como rutas optimizadas, tráfico en tiempo real, etc.)<br>• Cuando el equipo explore estas características<br>• Entonces deberán decidir si alguna de estas funcionalidades adicionales es relevante y útil para la plataforma Autonexo.</p>
  </td>
  <td>No corresponde</td>
</tr>
  </tbody>
</table>
  </tbody>
</table>


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
            <td>US06, US07, US08, US20, US29, US30, US31</td>
        </tr>
        <tr>
            <td>EP02</td>
            <td>Gestión de servicios y reservas</td>
            <td>Como taller y propietario, quiero gestionar ofertas de mantenimiento y reservas, para asegurar que las tareas se coordinen en tiempo y forma.</td>
            <td>No corresponde</td>
            <td>US02, US19</td>
        </tr>
        <tr>
            <td>EP03</td>
            <td>Descubrimiento y personalización</td>
            <td>Como propietario, quiero encontrar talleres y servicios mediante filtros, ubicación y promociones, para elegir la mejor opción.</td>
            <td>No corresponde</td>
            <td>US03, US04, US05, US17, US18, US32</td>
        </tr>
        <tr>
            <td>EP04</td>
            <td>Comunicación y coordinación</td>
            <td>Como usuario, quiero comunicarme y coordinar con el taller en tiempo real, para asegurar un servicio claro y sin errores.</td>
            <td>No corresponde</td>
            <td>US09, US10, US11</td>
        </tr>
        <tr>
            <td>EP05</td>
            <td>Gestión de mantenimientos</td>
            <td>Como usuario, quiero gestionar los mantenimientos desde la creación hasta la finalización, para asegurar el control y trazabilidad de cada servicio.</td>
            <td>No corresponde</td>
            <td>US12, US13, US14, US15, US16</td>
        </tr>
        <tr>
            <td>EP06</td>
            <td>Calificaciones y reputación</td>
            <td>Como usuarios (propietario y taller), queremos calificarnos mutuamente y consultar reputaciones, para fomentar confianza y calidad en el servicio.</td>
            <td>No corresponde</td>
            <td>US24, US25, US26, US27</td>
        </tr>
        <tr>
            <td>EP07</td>
            <td>Landing Page (visitantes)</td>
            <td>Como visitante, quiero acceder a información, registro y soporte desde la landing page, para conocer y empezar a usar la aplicación.</td>
            <td>No corresponde</td>
            <td>US01, US21, US22, US23, US28</td>
        </tr>
           <tr>
            <td>EP08</td>
            <td>Servicios técnicos y APIs REST</td>
            <td>Como equipo de desarrollo, quiero exponer endpoints REST bien documentados y seguros, para facilitar la integración, el mantenimiento y la escalabilidad del sistema.</td>
            <td>No corresponde</td>
            <td>TS01, TS02, TS03, TS04, TS05, TS06, TS07, TS08, TS09, TS10, TS11, TS12, TS13, TS14, TS15</td>
        </tr>
  </tbody>
</table>
  </tbody>
</table>

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
    <tr><td>1</td><td>US01</td><td>Visualizar información y beneficios (Landing Page)</td><td>2</td></tr>
    <tr><td>2</td><td>US02</td><td>Catálogo de servicios de taller</td><td>5</td></tr>
    <tr><td>3</td><td>US03</td><td>Explorar catálogo y búsqueda</td><td>5</td></tr>
    <tr><td>4</td><td>US04</td><td>Filtrar por servicio</td><td>3</td></tr>
    <tr><td>5</td><td>US05</td><td>Recomendación por geolocalización</td><td>5</td></tr>
    <tr><td>6</td><td>US06</td><td>Registro de vehículo</td><td>3</td></tr>
    <tr><td>7</td><td>US07</td><td>Adjuntar historial inicial</td><td>2</td></tr>
    <tr><td>8</td><td>US08</td><td>Visualizar historial de vehículo</td><td>3</td></tr>
    <tr><td>9</td><td>US09</td><td>Sistema de mensajería</td><td>5</td></tr>
    <tr><td>10</td><td>US10</td><td>Coordinación de citas de mantenimiento</td><td>5</td></tr>
    <tr><td>11</td><td>US11</td><td>Notificaciones push</td><td>3</td></tr>
    <tr><td>12</td><td>US12</td><td>Actualización de checklist en mantenimiento</td><td>3</td></tr>
    <tr><td>13</td><td>US13</td><td>Creación de mantenimiento confirmado</td><td>3</td></tr>
    <tr><td>14</td><td>US14</td><td>Visualización de mantenimientos pendientes</td><td>3</td></tr>
    <tr><td>15</td><td>US15</td><td>Visualización de checklist en mantenimiento</td><td>2</td></tr>
    <tr><td>16</td><td>US16</td><td>Finalización de mantenimiento</td><td>3</td></tr>
    <tr><td>17</td><td>US17</td><td>Taller favorito</td><td>2</td></tr>
    <tr><td>18</td><td>US18</td><td>Promociones de taller de confianza</td><td>3</td></tr>
    <tr><td>19</td><td>US19</td><td>Cancelar reserva de mantenimiento</td><td>3</td></tr>
    <tr><td>20</td><td>US20</td><td>Actualización automática del historial</td><td>3</td></tr>
    <tr><td>21</td><td>US21</td><td>Registro de usuario (propietario o taller)</td><td>3</td></tr>
    <tr><td>22</td><td>US22</td><td>Preguntas frecuentes y soporte</td><td>2</td></tr>
    <tr><td>23</td><td>US23</td><td>Contacto y descarga de la app</td><td>2</td></tr>
    <tr><td>24</td><td>US24</td><td>Calificación de taller</td><td>2</td></tr>
    <tr><td>25</td><td>US25</td><td>Calificación de propietario</td><td>2</td></tr>
    <tr><td>26</td><td>US26</td><td>Consulta de reputación de taller</td><td>2</td></tr>
    <tr><td>27</td><td>US27</td><td>Consulta de reputación de propietario</td><td>2</td></tr>
    <tr><td>28</td><td>US28</td><td>Visualizar planes de pago para talleres (Landing Page)</td><td>2</td></tr>
    <tr><td>29</td><td>US29</td><td>Seleccionar tipo de mecánico</td><td>3</td></tr>
    <tr><td>30</td><td>US30</td><td>Generar y compartir código de taller</td><td>3</td></tr>
    <tr><td>31</td><td>US31</td><td>Unirse a un taller mediante código</td><td>3</td></tr>
    <tr><td>32</td><td>US32</td><td>Navegación mediante barra de menú</td><td>2</td></tr>
    <tr><td>33</td><td>TS01</td><td>Implementar endpoint para registrar y gestionar vehículos (/vehicles)</td><td>5</td></tr>
    <tr><td>34</td><td>TS02</td><td>Implementar endpoint para adjuntar y consultar historial (/vehicles/{id}/history)</td><td>5</td></tr>
    <tr><td>35</td><td>TS03</td><td>Implementar endpoint para catálogo de servicios de taller (/services)</td><td>5</td></tr>
    <tr><td>36</td><td>TS04</td><td>Implementar endpoint para gestión de reservas de mantenimiento (/reservations)</td><td>5</td></tr>
    <tr><td>37</td><td>TS05</td><td>Implementar endpoint para sistema de mensajería (/messages)</td><td>5</td></tr>
    <tr><td>38</td><td>TS06</td><td>Implementar endpoint para calificaciones y reputación (/ratings)</td><td>3</td></tr>
    <tr><td>39</td><td>TS07</td><td>Implementar endpoint para exploración y búsqueda de servicios (/services?filters=)</td><td>5</td></tr>
    <tr><td>40</td><td>TS08</td><td>Implementar endpoint para filtros y geolocalización de talleres (/workshops?location=)</td><td>5</td></tr>
    <tr><td>41</td><td>TS09</td><td>Implementar endpoint para gestión de favoritos (/favorites)</td><td>3</td></tr>
    <tr><td>42</td><td>TS10</td><td>Implementar endpoint para promociones de talleres (/promotions)</td><td>2</td></tr>
    <tr><td>43</td><td>TS11</td><td>Implementar endpoint para coordinación de citas (/appointments)</td><td>5</td></tr>
    <tr><td>44</td><td>TS12</td><td>Implementar endpoint para notificaciones push (/notifications)</td><td>3</td></tr>
    <tr><td>45</td><td>TS13</td><td>Implementar endpoint para gestión de mantenimientos (/maintenances)</td><td>5</td></tr>
    <tr><td>46</td><td>TS14</td><td>Implementar endpoint para landing page y registro de usuarios (/users)</td><td>3</td></tr>
    <tr><td>47</td><td>TS15</td><td>Implementar endpoint para soporte, FAQ y contacto (/faq, /support, /contact)</td><td>2</td></tr>
    <tr><td>48</td><td>SP-01</td><td>Investigación de la Integración de Stripe para el Procesamiento de Pagos</td><td>3</td></tr>
    <tr><td>49</td><td>SP-02</td><td>Investigación de Google Maps para la Localización de Mecánicos</td><td>3</td></tr>
    <tr><td>50</td><td>SP-03</td><td>Evaluación de Sistemas de Notificaciones Push</td><td>3</td></tr>
    <tr><td>51</td><td>SP-04</td><td>Investigación de Herramientas de Reportes de Mantenimiento</td><td>3</td></tr>
    <tr><td>52</td><td>SP-06</td><td>Investigación de Técnicas de Caching para Mejorar el Rendimiento</td><td>3</td></tr>
    <tr><td>53</td><td>SP-07</td><td>Evaluación de Herramientas de Seguridad para la Plataforma</td><td>3</td></tr>
    <tr><td>54</td><td>SP-08</td><td>Investigación de Plataforma para Gestión de Suscripciones</td><td>3</td></tr>
    <tr><td>55</td><td>SP-09</td><td>Investigación de API de Localización para Mejorar la Búsqueda de Mecánicos</td><td>3</td></tr>
  </tbody>
</table>


## 2.5. Strategic-Level Domain-Driven Design
<br>

### 2.5.1. EventStorming
El objetivo de la sesión de EventStorming fue realizar una exploración amplia y colaborativa del dominio del problema de Autonexo. Mediante esta técnica buscamos representar de manera visual y comprensible los distintos eventos que ocurren dentro del flujo de interacción entre usuarios (propietarios de vehículos) y mecánicos, con el fin de identificar oportunidades de mejora, puntos críticos y posibles cambios de estado en el sistema.
<br>
- Step 1 – Unstructured Exploration: El equipo colocó en Miro todos los eventos relevantes sin ningún orden, con el fin de vaciar conocimiento y asegurar que ninguna parte del dominio quedara fuera.

<img alt="step1_UnstructuredExploration" src="assets\chapter-II-assets\step1_UnsExp.png" />
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

**Scenario 1**
<img alt="scenario-1" src="assets\chapter-II-assets\scenario-1.png" />
<br> <br>

**Scenario 2**
<img alt="scenario-2" src="assets\chapter-II-assets\scenario-2.png" />
<br> <br>

**Scenario 3**
<img alt="scenario-3" src="assets\chapter-II-assets\scenario-3.png" />
<br> <br>

**Scenario 4**
<img alt="scenario-4" src="assets\chapter-II-assets\scenario-4.png" />
<br> <br>

#### 2.5.1.3 Bounded Context Canvases

**IAM bounded context canvas**

<img alt="IAM" src="assets\chapter-II-assets\bounded-context-canvases\canvases-IAM.png" />
<br> <br>

**Matching&Booking bounded context canvas**

<img alt="Matching" src="assets\chapter-II-assets\bounded-context-canvases\canvases-matching.png" />
<br> <br>
 
**Notifications bounded context canvas**

<img alt="Notification" src="assets\chapter-II-assets\bounded-context-canvases\canvases-notification.png" />
<br> <br>

**Payment bounded context canvas**

<img alt="Payment" src="assets\chapter-II-assets\bounded-context-canvases\canvases-payment.png" />
<br> <br>

**Trust&Reputation bounded context canvas**

<img alt="Trust" src="assets\chapter-II-assets\bounded-context-canvases\canvases-trust.png" />
<br> <br>

**Vehicle&Maintenance bounded context canvas**

<img alt="Vehicle" src="assets\chapter-II-assets\bounded-context-canvases\canvases-vehicle.png" />
<br> <br>

**Workshop bounded context canvas**

<img alt="Workshop" src="assets\chapter-II-assets\bounded-context-canvases\canvases-workshop.png" />
<br> <br>

### 2.5.2. Context Mapping

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
<img alt="Context-Diagram" src="assets\chapter-II-assets\c4\structurizr-101398-SystemContext-001.png" />

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

##### 2.6.2.6.1 Bounded Context Domain Layer Class Diagrams

<img alt="Class-Workshop" src="assets\chapter-II-assets\bc\class-trusting.png" />

##### 2.6.2.6.2 Bounded Context Database Design Diagram

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
  - canCancel(bookingId: UUID, Cuando: DateTime) → bool

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
  - auEntoncesticate(candidateHash: PasswordHash)  
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
- UserAuEntoncesticatedEvent(userId, sessionId, occurredAt)  
  **Propósito:** Inicio de sesión exitoso.
- UserAuEntoncesticationFailedEvent(email, reason, occurredAt)  
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

- **AuEntoncesticationService**  
  **Métodos:** auEntoncesticate(email, password) → Token; refreshToken(token) → Token; revokeToken(token).  
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
- AuEntoncesticateUser(email: string, password: string)  
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
  - OnAuEntoncesticationFailedThresholdReached → bloquea cuenta y emite UserLockedEvent.

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
