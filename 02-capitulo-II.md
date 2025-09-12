# Capítulo II: Requirements Development and Software Solution Design

## 2.1. Competidores
### 2.1.1. Análisis competitivo
# Competitive Analysis Landscape

## ¿Por qué llevar a cabo este análisis?

El objetivo es definir el posicionamiento de Autonexo frente a soluciones de gestión de flotas y mantenimiento vehicular, identificando diferenciadores de valor y riesgos competitivos para el mercado local.

| | | AutoNexo | Fleetio | Drivvo | Whip Around |
|---|---|---|---|---|---|
| **Perfil** | Overview | Software especializado para gestión integral del mantenimiento vehicular que conecta conductores y mecánicos, centralizando historial, presupuestos y coordinación de servicios. | Plataforma robusta de gestión y mantenimiento de flotas (vehículos, conductores, combustible, inspecciones) con móvil y web, orientada a optimizar operaciones con datos. | App de gestión de vehículo/flota ligera para uso personal o pequeños negocios: control de combustible, gastos y mantenimientos; versión gratuita y planes Pro. | Plataforma para inspecciones digitales (DVIR), cumplimiento y mantenimiento para flotas comerciales, con foco en reducir downtime y riesgos. |
| | Ventaja competitiva – ¿Qué valor ofrece al cliente? | Digitaliza y automatiza el proceso de mantenimiento; conecta demanda (conductores) con oferta (mecánicos) y da trazabilidad del historial. | Gestión centralizada y basada en datos para reducir costos (mantenimiento, combustible) y mejorar decisiones; módulos de inspección, órdenes de trabajo y fuel tracking. | Accesibilidad y simplicidad móvil para controlar gastos y recordatorios de servicio; apta para usuarios individuales. | Cumplimiento y seguridad: inspecciones digitalizadas y flujos mecánico–conductor para atender defectos rápido y cumplir normas (CSA/DOT). |
| **Perfil de marketing** | Mercado objetivo | Dueños de flotas o conductores individuales y mecánicos/talleres. | Gestores de flota en transporte, construcción, servicios y sector público. | Conductores y pequeños negocios que desean controlar gastos/consumo del vehículo. | Gerentes de flota, supervisores de operaciones y conductores en flotas comerciales. |
| | Estrategias de marketing | Performance en redes, programa de referidos y alianzas con talleres. | Contenido y recursos para fleet managers (guías, plantillas, blog), demos y pruebas gratuitas. | Web/app store pages + educación ligera (contenido de uso, ventajas). | Campañas orientadas a cumplimiento y reducción de riesgos; trial/demo. |
| **Perfil de producto** | Productos & servicios | Registro de vehículos/usuarios, planificación y seguimiento de mantenimientos, control de repuestos, búsqueda de mecánico, mensajería y presupuestos. | Gestión de activos, mantenimiento preventivo/WO, inspecciones, combustible, partes/inventario, reportes y mobile app Fleetio Go. | Registro de gastos, combustible, recordatorios de servicio, reportes; opciones de Fleet para múltiples vehículos. | Inspecciones DVIR personalizables, mantenimiento, órdenes de reparación y reporting para compliance. |
| | Precios & costos | Suscripción por plan (accesible) para talleres y mecánicos; conductor gratuito o incluido (definición interna). | Suscripción mensual por plan (Essential/Professional) con usuarios ilimitados; add-ons por herramienta/activo; precios varían por tamaño. | Gratis (básico) + in-app purchases para Pro; en App Store figuran opciones mensuales/anuales y tiers de flota. | Suscripción por plan; mínimo mensual publicado: USD $120 (Standard) y $220 (Pro) en mes a mes; opciones "FixedUnlimited" para activos ilimitados. |
| | Canales de distribución | Web y app móvil. | Web + app móvil; usuarios ilimitados incluidos. | App móvil (iOS/Android); web principalmente informativa. | Web y app móvil. |
| **Análisis SWOT** | Fortalezas | Enfoque local, matching conductor–mecánico, trazabilidad del historial. | Cobertura funcional amplia y ecosistema maduro; fuerte orientación a datos. | Barrera de entrada baja y usabilidad móvil para usuario individual. | Especialista en inspecciones y cumplimiento; valor claro para safety/compliance. |
| | Debilidades | Requiere onboarding/educación para talleres no digitalizados. | Coste total puede crecer con activos/add-ons en flotas grandes. | Menor cobertura "enterprise"; dependiente del móvil. | Menor foco en gestión integral de costos/combustible vs. suites completas. |
| | Oportunidades | Digitalización del sector y integraciones (facturación, repuestos, GPS). | Creciente adopción SaaS en LATAM/SMBs. | Extender funciones de flota ligera/pequeñas empresas. | Integrarse con plataformas de gestión de flotas y TMS. |
| | Amenazas | UX inicial: si es compleja, podría afectar adopción temprana. | Competidores de menor costo o suites verticales. | Usuarios migran a soluciones más completas a medida que crecen. | Cambios normativos que reduzcan inspecciones obligatorias. |

## 2.1.2. Estrategias y tácticas frente a competidores

Para competir eficazmente frente a suites de gestión de flotas, apps personales de control vehicular y plataformas de inspecciones, Autonexo aplicará las siguientes estrategias y tácticas preliminares, considerando nuestras fortalezas (gestión integral del mantenimiento y conexión conductor–mecánico) y la oportunidad de mercado (demanda creciente de transparencia, trazabilidad y control).

### Diferenciación por enfoque especializado en mantenimiento 

**Estrategia:** Posicionar a Autonexo como la plataforma especializada en mantenimiento vehicular que conecta a conductores/flotas con mecánicos locales, y que centraliza historial, presupuestos y comunicación.

**Tácticas:**
- Desarrollar el buscador de mecánico con filtros por especialidad, SLA y calificación.
- Ofrecer historial técnico unificado (diagnóstico, repuestos, OT, evidencias) compartible entre taller y conductor.
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
- Modo offline (cache móvil) para registrar trabajos sin conexión y sincronizar luego.

### Seguridad, confianza y cumplimiento

**Estrategia:** Reducir la percepción de riesgo y aumentar la confianza desde etapas tempranas.

**Tácticas:**
- Cifrado en tránsito y en reposo, backups automáticos, control de accesos por roles.
- Auditoría básica externa y pruebas de penetración anuales.
- Bitácora de cambios en historiales y descarga de datos (portabilidad) para transparencia.

### Ecosistema e integraciones 

**Estrategia:** Construir un ecosistema digital que conecte mantenimiento, repuestos y operaciones para optimizar decisiones con datos.

**Tácticas:**
- APIs RESTful para módulos internos; conectores con facturación, pasarelas de pago, GPS/telemática, catálogos de repuestos y WhatsApp Business.
- Alertas inteligentes (kilometraje/horas, tiempo, códigos OBD, garantías de repuesto).
- Dashboard de salud de flota y forecasts de mantenimiento.

### Alianzas estratégicas

**Estrategia:** Acelerar adquisición con presencia local y pruebas guiadas.

**Tácticas:**
- Alianzas con cadenas de talleres, distribuidores de repuestos, aseguradoras/SOAT y escuelas de mecánica.
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

#### Segmento 1: Mecánicos

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

#### Segmento 2: Conductores

**Preguntas sobre la problemática**

1. ¿Cuáles son tus principales problemas al buscar o gestionar mantenimientos de tu vehículo?
2. ¿Cómo sueles pedir actualmente un mantenimiento y en qué parte del proceso se complica más?

**Preguntas sobre la solución**

1. ¿Cómo te gustaría crear la solicitud de mantenimiento en la app (voz, formulario, chat, llamada)?
2. ¿Qué información mínima debería incluir tu solicitud (placa, síntomas, fotos/video, ubicación, presupuesto)?
3. ¿Cómo preferirías ver y comparar mecánicos (lista, mapa, filtros) y qué criterios decidirían tu elección?
4. ¿Qué datos o preferencias te gustaría poder personalizar (mecánico favorito, horarios, precio máximo, marcas de repuestos)?
5. ¿Qué formato de interfaz te resultaría más claro para revisar el estado del trabajo (checklist, porcentaje, fotos)?
6. ¿Qué información debería guardarse en el historial de tu vehículo y cómo te gustaría consultarla?
7. ¿Cómo prefieres realizar el pago de los servicios (Yape/Plin, tarjeta, efectivo) y en qué momento del proceso?
8. ¿Qué criterios usarías para calificar al mecánico después de un servicio (puntualidad, precio, confianza, claridad)?
9. Al abrir la app, ¿qué información te gustaría ver primero (urgencias, citas del día, presupuestos pendientes)?


### 2.2.2. Registro de entrevistas

**Segmento 1: Bodegas especializadas por rubro**

<table border="1">
  <tr>
    <th>Entrevista</th>
    <td>1</td>
    <th>Nombre</th>
    <td>Milagros Almerco</td>
  </tr>
  <tr>
    <th>Edad</th>
    <td>28</td>
    <th>Distrito</th>
    <td>San Martín de Porres</td>
  </tr>
  <tr>
    <th>Captura de la entrevista: <img src="assets/Chapter-2/Segmento 1 - Milagros Almerco.png" alt="Captura de la entrevista" width="200"></th>
    <td colspan="3">
        En la entrevista, la estudiante Milagros Almerco comenta que lleva el control de su bodega en un cuaderno, anotando manualmente las ventas y compras. Reconoce que su sistema es básico y que a veces se olvida de registrar productos, lo que dificulta llevar un control claro del inventario. Además, le resulta complicado encontrar información específica entre tantas hojas. Señala como uno de sus principales problemas la falta de control sobre las fechas de vencimiento, lo que ha ocasionado pérdidas por productos que no logró vender a tiempo. También menciona que no siempre actualiza los cambios de precio. Para prevenir esto, trata de revisar los estantes y adelantar los productos por vencer. Respecto a herramientas digitales, indica que usa el celular y la calculadora por practicidad. Pero le gustaría contar con un sistema que le avise qué productos están por vencer, cuáles debe reponer y cómo están cambiando los precios. Además, considera importante poder visualizar su inventario en tiempo real. Le gustaría recibir alertas y reportes que le ayuden a organizar mejor su negocio.
    </td>
  </tr>
  <tr>
    <th>URL de la grabación</th>
    <td colspan="3">
      <a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310210_upc_edu_pe/EcdO_7IMHslJvnfLQriZz-ABm7y1EeoaVKtpaloN3Upm4A?e=2MviFe&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D">
        Ver grabación
      </a>
    </td>
  </tr>
  <tr>
   <th>Timing</th>
    <td colspan="3">
        05:24 -11:12
    </td>
  </tr>
</table>
<br>

<table border="1">
  <tr>
    <th>Entrevista</th>
    <td>2</td>
    <th>Nombre</th>
    <td>Elvis Aranga Mesa</td>
  </tr>
  <tr>
    <th>Edad</th>
    <td>31</td>
    <th>Distrito</th>
    <td>Santiago de Surco</td>
  </tr>
  <tr>
    <th>Captura de la entrevista: <img src="assets/Chapter-2/seg1-Elvis.png" alt="Captura de la entrevista" width="200"></th>
    <td colspan="3">
        Elis Aranga Meza, de 31 años y encargado de la administración en su bodega en Santiago de Surco, gestiona el inventario de forma manual, sin un sistema digital, basándose en el control visual y el registro de ventas totales. Reconoce que esta falta de control sistematizado dificulta hacer proyecciones, identificar los productos con mayor rotación o margen de ganancia, y manejar adecuadamente las mermas, especialmente en productos perecibles como frutas y abarrotes. Ha enfrentado pérdidas por productos vencidos y robos, y señala la necesidad de implementar un sistema digital para actualizar precios en tiempo real, controlar vencimientos y facilitar la gestión por parte del personal. Considera que una plataforma digital mejoraría la eficiencia, permitiría delegar tareas y evitar errores en la rotación y precios, aportando mayor libertad y control en la operación diaria.
    </td>
  </tr>
  <tr>
    <th>URL de la grabación</th>
    <td colspan="3">
      <a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310210_upc_edu_pe/EcdO_7IMHslJvnfLQriZz-ABm7y1EeoaVKtpaloN3Upm4A?e=2MviFe&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D">
        Ver grabación
      </a>
    </td>
  </tr>
  <tr>
   <th>Timing</th>
    <td colspan="3">
        11:12 - 17:11
    </td>
  </tr>
</table>
<br>
<table border="1">
  <tr>
    <th>Entrevista</th>
    <td>3</td>
    <th>Nombre</th>
    <td>Kerry Baquerrizo</td>
  </tr>
  <tr>
    <th>Edad</th>
    <td>21</td>
    <th>Distrito</th>
    <td>San Luis</td>
  </tr>
  <tr>
    <th>Captura de la entrevista: <img src="assets/Chapter-2/Seg1-Kerry.png" alt="Captura de la entrevista" width="200"></th>
    <td colspan="3">
        Kerry Baquerrizo tiene 21 años y trabaja en la bodega de sus padres. A lo largo de la entrevista menciona la falta de un sistema para poder organizar mejor su inventario y manejo de stock, teniendo como un ejemplo las frutas, siendo agotador para ella estar yendo al mercado para abastacer las frutas ya que se malogran muy rápido por la temporada o los clientes simplemente  no compran la cantidad suficiente que los vendedores esperan que compren, por lo que se deteriora y pierden ganancias. También menciona la importancia de poder adquirir una herramienta que pueda gestionar, alertar y registrar sus productos, pues considera que podrían mejorar enormemente su manera de organizar sus productos en su tienda.
    </td>
  </tr>
  <tr>
    <th>URL de la grabación</th>
    <td colspan="3">
      <a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310210_upc_edu_pe/EcdO_7IMHslJvnfLQriZz-ABm7y1EeoaVKtpaloN3Upm4A?e=2MviFe&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D">
        Ver grabación
      </a>
    </td>
  </tr>
  <tr>
   <th>Timing</th>
    <td colspan="3">
        00:00 - 5:24
    </td>
  </tr>
</table>
<br>

**Segmento 2: Startups y emprendedores en expansión con necesidades logísticas**

<table border="1">
  <tr>
    <th>Entrevista</th>
    <td>4</td>
    <th>Nombre</th>
    <td>Alexander Miranda</td>
  </tr>
  <tr>
    <th>Edad</th>
    <td>25</td>
    <th>Distrito</th>
    <td>Villa el Salvador</td>
  </tr>
  <tr>
    <th>Captura de la entrevista: <img src="assets/Chapter-2/segmento2 - Alexander Miranda.png" alt="Captura de la entrevista" width="200"></th>
    <td colspan="3">
        En la entrevista, Alexander Miranda comentó que se dedica a la venta texti. Explicó que hace sus registros de manera manual lo que es agotador para él y que siente que pierde mucho tiempo ya que le puede tomar horas. Mediante excel controla sus ingresos y luego revisa las boletas para actualziar el inventario y llevar un conteo general. Nos dice que le gustaría automatizar sus procesos y ha considerado emplear tecnologías que le apoyen a modernizar su negocio para la gestión de inventarios. 
    </td>
  </tr>
  <tr>
    <th>URL de la grabación</th>
    <td colspan="3">
      <a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310210_upc_edu_pe/EcdO_7IMHslJvnfLQriZz-ABm7y1EeoaVKtpaloN3Upm4A?e=2MviFe&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D">
        Ver grabación
      </a>
    </td>
  </tr>
  <tr>
   <th>Timing</th>
    <td colspan="3">
        20:45 - 23:50
    </td>
  </tr>
</table>

<table border="1">
  <tr>
    <th>Entrevista</th>
    <td>5</td>
    <th>Nombre</th>
    <td>Juan Carlos Ramírez</td>
  </tr>
  <tr>
    <th>Edad</th>
    <td>49</td>
    <th>Distrito</th>
    <td>Suquillo</td>
  </tr>
  <tr>
    <th>Captura de la entrevista: <img src="assets/Chapter-2/seg2-carlitos.png" alt="Captura de la entrevista" width="200"></th>
    <td colspan="3">
        Juan Carlos Ramírez, emprendedor de 49 años, gestiona su inventario principalmente de forma manual, registrando entradas y salidas mediante boletas y facturas sin un control digital completo. Actualmente está en proceso de digitalizar su sistema con un programa y una máquina POS que escanea códigos de barra, aunque aún no emite boletas ni facturas electrónicas. La revisión del stock se realiza visualmente y las ventas se gestionan principalmente por WhatsApp con entrega a domicilio. Busca mejorar la eficiencia y liberar tiempo mediante la implementación de herramientas digitales más integradas.
    </td>
  </tr>
  <tr>
    <th>URL de la grabación</th>
    <td colspan="3">
      <a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310210_upc_edu_pe/EcdO_7IMHslJvnfLQriZz-ABm7y1EeoaVKtpaloN3Upm4A?e=2MviFe&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D">
        Ver grabación
      </a>
    </td>
  </tr>
  <tr>
   <th>Timing</th>
    <td colspan="3">
        17:11 - 20:45
    </td>
  </tr>
</table>

<table border="1">
  <tr>
    <th>Entrevista</th>
    <td>6</td>
    <th>Nombre</th>
    <td>Octavio</td>
  </tr>
  <tr>
    <th>Edad</th>
    <td>23</td>
    <th>Distrito</th>
    <td>Jesus Maria</td>
  </tr>
  <tr>
    <th>Captura de la entrevista: <img src="assets/Chapter-2/seg2-octavio.png" alt="Captura de la entrevista" width="200"></th>
    <td colspan="3">
        En la entrevista, Octavio comentó que se dedica a vender productos ecologicos para el hogar, nos cuentas que para gestionar su inventario lo hace de forma manual a través de un excel en google sheets pero ya se queda corto pq no se sincroniza con sus canales de venta y que ha estado investigando sobre buscar una plataforma para gestionar su inventario pero estas lo detiene por su cruva de aprendizaje, cuenta que si va a pagar por una plataforma quiere que sea intuitiva y facil de utilizar para que valga la pena la inversión que esta haciendo</td>
  </tr>
  <tr>
    <th>URL de la grabación</th>
    <td colspan="3">
      <a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310210_upc_edu_pe/EcdO_7IMHslJvnfLQriZz-ABm7y1EeoaVKtpaloN3Upm4A?e=2MviFe&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D">
        Ver grabación
      </a>
    </td>
  </tr>
  <tr>
   <th>Timing</th>
    <td colspan="3">
        23:50 - 27:02
    </td>
  </tr>
</table>
