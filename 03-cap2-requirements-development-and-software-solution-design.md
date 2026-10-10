# Capítulo II: Requirements Development and Software Solution Design
## 2.1. Competidores
### 2.1.1. Análisis competitivo
<table style="width:100%; border-collapse:collapse; table-layout:fixed;" border="1" align="center">
  <!-- Título principal -->
  <tr>
    <th colspan="6" align="center">Competitive Analysis Landscape</th>
  </tr>
  <!-- Justificación -->
  <tr>
    <td rowspan="2" align="center"><b>¿Por qué llevar a cabo este análisis?</b></td>
    <td colspan="5" align="center">
      Identificar fortalezas, debilidades y estrategias de los principales competidores en logística de última milla (SimpliRoute, Beetrack, FarEye) para posicionar nuestra aplicación web.
    </td>
  </tr>
  <tr>
    <td colspan="5">
      <b>Objetivo:</b> Determinar cómo diferenciar nuestro producto frente a competidores consolidados en LATAM y globales. <br> 
    </td>
  </tr>
  <!-- Encabezados con logos -->
  <tr>
    <th colspan="2" style="width:20%">(En la cabecera colocar por cada competidor nombre y logo)</th>
    <th style="width:20%">
      <img src="assets/images/cap2/Logo_rutana.png" alt="Rutana" width="100" height="100">
    </th>
    <th style="width:20%">
      <img src="assets/images/cap2/Logo_simpliroute.png" alt="SimpliRoute" width="100" height="100">
    </th>
    <th style="width:20%">
      <img src="assets/images/cap2/Logo_beetrack.png" alt="Beetrack" width="100" height="100">
    </th>   
    <th style="width:20%">
      <img src="assets/images/cap2/Logo_fareye.png" alt="FarEye" width="100" height="100">
    </th>
  </tr>
  <!-- PERFIL -->
  <tr>
    <td rowspan="2" align="center"><b>Perfil</b></td>
    <td><b>Overview</b></td>
    <td> Solución tecnológica desarrollada para el mercado peruano que fusiona IoT y GPS para garantizar el seguimiento en vivo, la mejora de rutas y la supervisión de mercancías en tránsito. Está diseñada específicamente para mitigar los retos locales de transporte, tales como la congestión vehicular, los cierres de vías y las variaciones climatológicas. </td>
    <td> Plataforma chilena con fuerte presencia en LATAM; optimización de rutas y seguimiento en tiempo real. </td>
    <td> Fundada en Chile, adquirida por DispatchTrack; fuerte en trazabilidad de última milla. </td>
    <td> Empresa multinacional de origen indio especializada en orquestación de entregas, visibilidad de envíos y gestión inteligente de devoluciones. </td>
  </tr>
  <tr>
    <td><b>Ventaja competitiva:<br>¿Qué valor ofrece a los clientes?</b></td>
    <td> Ofrece en una sola solución: seguimiento en vivo, validación automatizada de pedidos y alertas inteligentes. Está pensada para pymes peruanas, ayudándolas a reducir errores de entrega, evitar pérdidas y mejorar la puntualidad. </td>
    <td> Reducción de costos logísticos hasta 30% con algoritmos de optimización. </td>
    <td> Experiencia de usuario robusta y alta penetración en empresas medianas/grandes de LATAM. </td>
    <td> Escalabilidad global y capacidad de integración con grandes retailers y 3PL. </td>
  </tr>
  <!-- PERFIL DE MARKETING -->
  <tr>
    <td rowspan="2" align="center"><b>Perfil de Marketing</b></td>
    <td><b>Mercado objetivo</b></td>
    <td> Pequeñas y medianas empresas de transporte y distribución en Perú, con foco inicial en Lima y ciudades con alta informalidad logística como las empresas de provincia también.</td>
    <td> Pymes y grandes empresas de distribución en LATAM. </td>
    <td> Retail, consumo masivo y distribución en varios países de LATAM. </td>
    <td> Retailers, e-commerce y logística global (Asia, Europa, LATAM). </td>
  </tr>
  <tr>
    <td><b>Estrategias de marketing</b></td>
    <td> Evidenciar beneficios cuantitativos (menos errores, más puntualidad) mediante pilotos locales, campañas digitales y casos de éxito adaptados a la realidad peruana.</td>
    <td> Casos de éxito locales, métricas de reducción de costos y demos personalizadas. </td>
    <td> Branding fuerte en trazabilidad y seguridad de entregas; foco en confiabilidad. </td>
    <td> Posicionamiento como solución integral global; alianzas con grandes corporativos. </td>
  </tr>
  <!-- PERFIL DE PRODUCTO -->
  <tr>
    <td rowspan="3" align="center"><b>Perfil de Producto</b></td>
    <td><b>Productos & Servicios</b></td>
    <td> Incluye monitoreo IoT en tiempo real, registro automático de pedidos, panel de control para administradores y alertas de desvíos o incidencias.</td>
    <td> Optimización de rutas, seguimiento en vivo, gestión de flota y analítica. </td>
    <td> PlannerPro (rutas), LastMile (seguimiento), notificaciones y prueba de entrega. </td>
    <td> Administración total de la cadena de distribución, control de logística inversa y trazabilidad instantánea de los envíos. </td>
  </tr>
  <tr>
    <td><b>Precios & Costos</b></td>
    <td> Planes de suscripción flexible y escalonada (básico, estándar y corporativo) adaptados al ecosistema peruano. Permiten iniciar operaciones con un presupuesto reducido y expandir las capacidades conforme la empresa crece. </td> 
    <td> Modelo SaaS flexible según volumen de entregas. </td>
    <td> Suscripción mensual adaptada al tamaño de la operación. </td>
    <td> Tarifas empresariales escalables para operaciones globales. </td>
  </tr>
  <tr>
    <td><b>Canales de distribución<br>(Web y/o Móvil)</b></td>
    <td> El sistema será accesible a través de plataforma web para administradores y conductores, garantizando sincronización en tiempo real entre ambos segmentos. </td>
    <td> Web y app móvil para conductores y administradores. </td>
    <td> Web, app móvil y APIs de integración. </td>
    <td> Plataforma web, apps móviles, integraciones con ERP/CRM. </td>
  </tr>
  <!-- SWOT -->
  <tr>
    <td rowspan="4" align="center"><b>Análisis SWOT</b></td>
    <td><b>Fortalezas</b></td>
    <td> Integración de IoT y validaciones automatizadas que ofrecen una trazabilidad superior a competidores regionales. </td>
    <td> Alta adopción en LATAM; soporte local. </td>
    <td> Reconocimiento de marca y respaldo de DispatchTrack. </td>
    <td> Cobertura global, escalabilidad y capacidad de integración. </td>
  </tr>
  <tr>
    <td><b>Debilidades</b></td>
    <td> Al ser una solución nueva, carece todavía de base de clientes consolidados y casos de éxito reales. </td>
    <td> Menos reconocimiento fuera de LATAM. </td>
    <td> Dependencia de adaptación tras adquisición. </td>
    <td> Puede resultar costosa y compleja para pymes locales. </td>
  </tr>
  <tr>
    <td><b>Oportunidades</b></td>
    <td> Aprovechar el crecimiento acelerado del e-commerce y la digitalización logística en LATAM para posicionarse como alternativa innovadora. </td>
    <td> Crecimiento del e-commerce en LATAM. </td>
    <td> Sinergias con la expansión global de DispatchTrack. </td>
    <td> Expansión en mercados emergentes con alto crecimiento digital. </td>
  </tr>
  <tr>
    <td><b>Amenazas</b></td>
    <td> Competidores consolidados como Beetrack y SimpliRoute ya cuentan con reconocimiento de marca y clientes en el mercado. </td>
    <td> Aparición de nuevos SaaS locales más económicos. </td>
    <td> Competencia fuerte de soluciones globales más completas. </td>
    <td> Regulaciones locales y adaptación cultural en LATAM. </td>
  </tr>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores

Nuestra estrategia frente a competidores como SimpliRoute, Beetrack y FarEye será iniciar con pymes de transporte y distribución en el mercado peruano, ofreciendo una solución accesible y adaptable. A diferencia de los competidores consolidados, priorizaremos la simplicidad de uso, el soporte local y la personalización de funciones según la realidad de cada empresa.

Implementaremos un modelo SaaS modular y escalonado que facilite a las pequeñas empresas una adopción de bajo costo, permitiéndoles expandir capacidades a la par de sus operaciones. Para consolidar la confianza en el mercado nacional, impulsaremos estrategias basadas en pruebas piloto sin costo, validación con casos de éxito locales y un soporte técnico directo y cercano.

Nuestra propuesta de valor destaca por fusionar monitoreo IoT en tiempo real, automatización en la validación de pedidos y un sistema de alertas inteligentes dentro de una plataforma ágil y ligera. Esto se traduce en una reducción drástica de costos operativos, mayor cumplimiento en los tiempos de entrega y una seguridad reforzada frente a los desafíos logísticos del contexto peruano.

### 2.2. Entrevistas.

### 2.2.1. Diseño de entrevistas.

**Preguntas Generales**

**Objetivo:** obtener información personal y de contexto laboral del entrevistado.  
**Presentación con:** Nombres, apellidos, edad.

- **Principal:** ¿Cuál es tu rol dentro de la empresa de transporte?
- **Principal:** ¿Qué responsabilidades tienes en tu área?
- **Complementaria:** ¿Qué herramientas digitales/apps usas ahora para tu trabajo y qué te frustra de ellas?

**Primer Segmento Objetivo: Transportistas**

**Objetivo:** identificar cómo reciben, procesan y ejecutan la información de entregas, así como dificultades comunes en ruta.

- **Principal:** Actualmente, ¿cómo te pasan las ubicaciones de entrega (canal, formato y con cuánta anticipación) y quiénes son los que deciden?
- **Principal:** Si no conoces el lugar, ¿qué haces para encontrar el punto de entrega?
- **Principal:** ¿Qué información mínima necesitas por entrega?
- **Principal:** ¿Cómo confirmas una entrega realizada (firma, foto) y qué te complica de ese proceso?
- **Principal:** ¿Qué factores te retrasan con mayor frecuencia (tráfico, direcciones erróneas, esperas, documentación) y cómo los resuelves hoy?
- **Complementaria:** ¿Cómo reportas incidencias durante el reparto y qué tipos de incidencias son las más comunes?

**Segundo Segmento Objetivo: Administradores**

**Objetivo:** conocer procesos actuales de planificación y monitoreo, así como problemas y oportunidades de mejora.

- **Principal:** ¿Cómo registran actualmente qué productos se cargan en cada camión?
- **Complementaria:** ¿Han tenido incidentes de pérdida, daño o confusión en las cargas? ¿Cómo los resolvieron?
- **Principal:** ¿Qué problemas suelen enfrentar con la planificación de rutas?
- **Principal:** ¿Cómo registran la finalización de una ruta o la entrega al cliente?
- **Principal:** ¿Cómo monitorean hoy en día si un camión está siguiendo la ruta prevista?
- **Complementaria:** ¿Qué hacen cuando un camión se retrasa o cambia de ruta?

### 2.2.2. Registro de entrevistas.

***1. Primer Segmento Objetivo:***

**Primer Segmento Objetivo: Transportistas**

<table style="width: 100%" align='center'>
<tr>
<th>Entrevistado 1</th>
<th>Entrevistado 2</th>
<th>Entrevistado 3</th>
</tr>
<tr>
<td align='center'>
<a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202213185_upc_edu_pe/ET1TzP6JedZArvWvap237PcBMwKH12NdqIgFlqqtIGRJIA?e=r2iFfE&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D" target= 'blank'>
<img src="assets/images/cap2/jhon huaman.png" alt="Primera entrevista del primer segmento"
 width="150">
</a>
</td>
<td align='center'>
<a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202213185_upc_edu_pe/EXnpE4mhsDFMmHRdgpIgWdkBw5qgJK4qoQR-ptPTdy-Lbg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=23t4N5" target= 'blank'>
<img src="assets/images/cap2/Carlos Maque.png" alt="Segunda entrevista del primer segmento"  width="150">
</a>
</td>
<td align='center'>
<a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202213185_upc_edu_pe/EeUGT35ds8JEgUb9SddYv_MB7fjld1Jtl7ajbjpe9i-S3w?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=Ny0ro0" target= 'blank'>
<img src="assets/images/cap2/Danny Riverra.png" alt="Tercera entrevista del primer segmento" width="150" >
</a>
</td>
   <tr>
   <td>
    <b>Entrevistador:</b> Christofer William Costa Morales <br>
    <b>Entrevistado:</b> Jhon Willy Huaman Huaman <br>
    <b>Edad:</b> 34 años <br>
    <b>Distrito:</b> San Sebastian - Cusco <br>
    <b>Inicio de la entrevista:</b>  0:20 <br><br>
    <b> Resumen: </b>John Willy es un chofer y encargado de una empresa de transporte, que esta encargado de hacer las rutas y la liquidación de los pedidos de transporte. Este utiliza la <b>dirección en las boletas</b> que emite para calcular su ruta, además, con la información que el cliente le proporcione sobre la ruta (accidentes, desfiles, etc). Sin embargo, todos estos procesos pueden conllevan a muchos inconvenientes, cómo la confirmación de la ruta y de la dirección final, la recepción por parte del cliente, la zona en donde se despacha el pedido, la actitud de los clientes y el tiempo de espera. Adicionalmente, nos comento no usar su aplicación laboral, ya que, gracias a su experiencia puede manejar mejor algún problema y lo considera algo innecesario y tedioso de utilizar al poseer características muy intrusivas para su flujo laboral.<br><br>
    <b>Perfil del entrevistado:</b> El entrevistado demuestra una actitud práctica y autosuficiente, confiando en su experiencia más que en las herramientas tecnológicas. Prefiere mantener el control directo de su trabajo y se muestra escéptico ante sistemas digitales que percibe como poco adaptados a la realidad del campo. Su enfoque pragmático y su resistencia al cambio tecnológico reflejan la brecha existente entre las soluciones digitales actuales y las necesidades reales del personal operativo.<br>
    <p>
    </p>
   </td>
   <td>
    <b>Entrevistador:</b> Guillermo Arturo Howard Robles <br>
    <b>Entrevistado:</b> Carlos Maque Huachaca <br>
    <b>Edad:</b> 30 años <br>
    <b>Distrito:</b> Santiago - Cusco <br>
    <b>Inicio de la entrevista:</b> 0:33 <br><br>
    <b> Resumen:</b> Carlos Maque es un conductor y encargado, su rol es de transportista de producto de la marca Gloria. Este utiliza una aplicación llamada <b>BeeTrack</b>, la cual le otorga la geolocalización del cliente en un mapa, previamente proporcionado por la empresa. Además, la aplicación le proporciona un número de contacto de los clientes, en caso se pierda o la dirección sea incorrecta, y le otorga opciones para confirmar, rechazar o justificar la entrega o devolución de los pedidos. Por otro lado, <b>se guia con las boletas para obtener la información necesaria del pedido</b>. Adicionalmente, los retrasos en los pedidos más importantes, según el entrevistado, son: las tiendas cerradas, clientes sin dinero y mala geoposición. Por lo anterior, el reporta los inconvenientes por <b>WhatsApp</b> y <b>BeeTrack</b>. Sin embargo, este ultimo no funciona correctamente en las zonas con poca señal, por ello, se puede retrasar las confirmaciones de la entrega del pedidos y necesitan dirigirse a una zona con mejor señal para que cargue las confirmaciones.<br><br>
    <b>Perfil del entrevistado:</b> El entrevistado muestra una actitud responsable y abierta al uso de herramientas tecnológicas, aunque reconoce las limitaciones prácticas que enfrenta en campo. Es consciente de la importancia de la trazabilidad digital, pero se frustra ante la falta de conectividad y la dependencia del sistema para completar sus tareas. Refleja el perfil de un trabajador que valora la eficiencia tecnológica, siempre que esta se adapte a las condiciones reales del entorno operativo.<br>
  <p> </p>
   </td>
      <td>
    <b>Entrevistador:</b> Kenyi Efrain Ramirez Cabrera <br>
    <b>Entrevistado:</b> Danny Riverra Ticona<br>
    <b>Edad:</b> 24 años <br>
    <b>Distrito:</b> San Jeronimo - Cusco <br>
    <b>Inicio de la entrevista:</b> 0:25<br><br>
     <b>Resumen:</b> Danny Riverra, encargado y chofer en una empresa de transporte, utiliza el <b>teléfono móvil</b> y la aplicación <b>BeeTrack</b> para gestionar entregas, junto con documentos de oficina. Usa <b>BeeTrack y Google Maps</b> para localizar direcciones y referencias de clientes, necesitando solo la dirección exacta y calles cercanas. Registra las entregas con la firma del cliente y valida en <b>BeeTrack</b>, aunque las fallas de internet complican el proceso. Los retrasos principales son por tráfico, demoras en alistar mercadería y clientes sin pedidos, lo que requiere contactar al vendedor y reportar en <b>WhatsApp</b>. Los incidentes más comunes son locales cerrados o clientes sin dinero.<br><br>
    <b>Perfil del entrevistado:</b> El entrevistado muestra una actitud práctica y confianza en herramientas digitales, pero se frustra por factores externos como el tráfico, la falta de preparación de clientes y la dependencia de internet.<br>
      <p> 
     </p>
   </td>
   </tr>
</table>

Link de entrevistas: <a href="https://upcedupe-my.sharepoint.com/:f:/g/personal/u202315968_upc_edu_pe/IgCKXbh_32uXS69-VBq-wMImAdmonj2-7iZ4ZVsiDWAKElE?e=ffpJYm">Segmento 01- Transportistas</a>

**Segundo Segmento Objetivo: Administradores**

<table style="width: 100%" align='center'>
<tr>
<th>Entrevistado 1</th>
<th>Entrevistado 2</th>
<th>Entrevistado 3</th>
</tr>
<tr>
<td align='center'>
<a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202213185_upc_edu_pe/EVTQKC-v_1lEhE1mJT9JnmsB9xNmx4hF5Exa5TUm8AYjtg?e=tQDRf8&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D" target= 'blank'>
<img src="assets/images/cap2/Miguel Fernandez.png" alt="Primera entrevista del segundo segmento"
 width="150">
</a>
</td>
<td align='center'>
<a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202213185_upc_edu_pe/EZLL3X652L5KoLk1RWZn0zoBWGmWOQ80ZYl12yLueoednQ?e=vXoTwInav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D" target= 'blank'>
<img src="assets/images/cap2/Eliana Paullo.png" alt="Segunda entrevista del segundo segmento"
 width="150">
</a>
</td>
<td align='center'>
<a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202213185_upc_edu_pe/EcOPh-bhFsNCjQaceAJEYO8BwE3BUIW-e4wFdvoBHN-O2w?e=NPvjhC&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D" target= 'blank'>
<img src="assets/images/cap2/Adriana Merma.png" alt="Tercera entrevista del segundo segmento"  width="150">
</a>
</td>
   <tr>
   <td>
    <b>Entrevistador:</b> Christofer William Costa Morales <br>
    <b>Entrevistado:</b> Miguel Alcelmo Fernandez <br>
    <b>Edad:</b> 27 años <br>
    <b>Distrito:</b> Cusco <br>
    <b>Inicio de la entrevista:</b>  0:55 <br>
    <b> Resumen:</b> es un radiotransportista en la empresa de MR emprendimientos, esta encargado del monitoreo y coordinación de los pedidos. Luego, nos menciona que su empresa utiliza la aplicación <b>BeeTrack</b> que le permite mantener un monitoreo constante del estado de los pedidos. Sin embargo, este aplicación posee <em>inconvenientes con la geolocalización</em>, no identifica la ubicación exacta del cliente y eso confunde y frustra a los transportistas encargados. Siguiendo con la entrevista, nos menciona que la manera que registran los productos que ingresan a los camiones es con dos personas que van a la localidad y se encarga de verificar si esta todo en orden. Además, la manera en la que subsanan alguna perdida de producto, es por medio de los transportistas que se hacen responsables. En el caso de la planificación de las rutas, nos da su opinión de cómo los planificadores que trabajan en Lima, desconocen lo complicado que puede ser las rutas en Cusco y por ello, extienden las horas laborales de los transportistas. Finalmente, nos comenta cómo arreglan los problemas de retraso o incumplimiento de entregas y esto lo realizan llamando al encargado del camión, luego lo redirigen al área de ventas y este comunica al cliente mismo. <br><br>  
    <b>Perfil del entrevistado:</b> El entrevistado demuestra una actitud analítica y orientada al trabajo en equipo. Aunque confía en las herramientas digitales, reconoce las limitaciones del software actual y la falta de adaptación a contextos locales. Su visión combina la experiencia operativa con una comprensión clara de los procesos logísticos, lo que lo convierte en un perfil que valora la precisión, la comunicación y la eficiencia, pero que también exige soluciones tecnológicas más contextualizadas y realistas.
 <br>
    <p>
   </td>
   <td>
    <b>Entrevistador: </b> Rodrigo Jesus Miraval Pomalaya <br>
    <b>Entrevistado:</b>Eliana Paullo Palma<br>
    <b>Inicio de la entrevista:</b> 
    <b>Edad:</b> 49 años <br>
    <b>Distrito:</b> Cusco <br>
    <b>Inicio de la entrevista:</b>  0:17 <br><br>
    <b> Resumen:</b> Eliana Paullo es una administradora de la empresa MR emprendimientos, mayormente usa herramientas como celular y computadora, esta encargada de la planificación de los camiones, el monitoreo de personal y transportes, evaluar y ayudar al personal. Después, nos menciona que todo el personal de la empresa, por camión, usa la aplicación <b>"Beetrack"</b>, el cual le ayuda a monitorear el porcentaje de avance que posee cada camión y los clientes y productos asignados a cada camión<b>esto mediante el celular que la empresa proporciona</b>. Además, utilizan <b>GPS</b> para mantener un control de las rutas de los camiones y del uso de sensores, ya que los productos deben mantenerse refrigerados y este le alerta si esta o no activado el refrigerante. Los principales incidentes que sufrieron son: Confunción en el cargamento del camión, a causa de la forma en cómo estan divididos los camiones, y el daño de los productos y la compensación económica por los mismos. Luego, nos comenta cómo realizan la planificación de las rutas y cómo lidian con problemas que pueden ocurrir el mismo dia de entrega. Esto lo realizan de manera manual, <b>con llamadas y mensajes a los clientes para informarle de los retrasos</b>. Adicionalmente, nos comenta que se utiliza bastante <b>Whatsapp</b> para la coordinación de pedidos para los diferentes conductores. Finalmente, nos comento su sugerencia para mejorar las herramientas que usan, este seria la Opción para identificar a clientes complicados y deribarlos a un plan de pago adelantado para evitar problemas al momento de realizar las entregas. <br><br> 
    <b>Perfil del entrevistado:</b>La entrevistada refleja un perfil estratégico, organizado y con una clara comprensión del funcionamiento integral de la empresa. Valora la tecnología como herramienta de control y prevención, aunque reconoce la necesidad de optimizar la comunicación y automatizar procesos repetitivos. Su enfoque busca equilibrar la supervisión operativa con la eficiencia administrativa, mostrando apertura hacia soluciones que mejoren la trazabilidad, la gestión de incidencias y la relación con los clientes.
 <br>
   <p>
   </p>
   </td>
      <td>
    <b>Entrevistador:</b> Bruno Aldair Huaman Gallardo  <br>
    <b>Entrevistado: </b>Adriana Merma Noblega<br>
    <b>Inicio de la entrevista:</b> 
    <b>Edad:</b> 50 años <br>
    <b>Distrito:</b> Lima <br>
    <b>Inicio de la entrevista:</b>  0:08 <br><br>
    <b> Resumen:</b> Adriana Merma es una gerente de una empresa de transporte que se encarga de la gestión de las diferentes áreas y del personal. El entrevistado dice que poseen varios aplicaciones empresariales con diferentes usos. Por ejemplo, uno de ellos le da actualizaciones del avance del trabajo en las diferente áreas mediante su <b>celular</b>, otro mantenimiento de sus vehiculos, qué se debe transportar en cada pedido y de informar de algún error o daños en los productos, y otro más para poder registrar la finalización del trabajo y poder registrarlo. Además, comenta que no hay muchos errores en las planificación de rutas, en caso los haya, se utilizarían las aplicaciones como <b>BeeTrack</b> y documentos de registros o control mediante tablas de <b>excel en computadora o laptop</b>. Al final, el entrevistado nos comenta que todo lo que realizan, siempre usan varios aplicaciones durante todo el proceso. <br><br> 
    <b>Perfil del entrevistado:</b> La entrevistada presenta una mentalidad gerencial orientada a la digitalización y la eficiencia. Su confianza en los sistemas tecnológicos refleja un alto nivel de adaptación a la transformación digital empresarial. Sin embargo, también deja entrever una dependencia de múltiples plataformas que podrían beneficiarse de una integración más fluida. Representa un perfil directivo que prioriza la automatización, la trazabilidad y el control centralizado, con interés en soluciones que unifiquen y optimicen las herramientas actuales.
 <br>
     <p>
     </p>
   </td>
   </tr>
</table>

Link de entrevistas: <a href="https://upcedupe-my.sharepoint.com/:f:/g/personal/u202315968_upc_edu_pe/IgB2L_q6O4iORK8XUs_QuMvKAeFxtTwxrbqLVKTeMAafTVA?e=ydA6C3">Segmento 02- Administración</a>

Más informacion en Anexo A.

### 2.2.3. Análisis de entrevistas.

***Segmento 1: Transportistas***

Se realizo el analisis de 3 entrevistas a los transportistas con experiencia en el sector. Con la información obtenida se puede identificar las características claves para el perfil de nuestros segmento objetivo de transportistas.

****Caracteristicas****

<table>
<tr>
<th>Características</th>
<th>Mención</th>
<th>Porcentaje</th>
<th>Evidencia</th>
</tr>
<tr>
<td>Uso de aplicaciones de gestión de entregas</td>
<td>2/3</td>
<td>66.7%</td>
<td><b>Entrevistado 2:</b> Utiliza "Beetrack" para geolocalización, contacto de clientes y confirmar/rechazar pedidos. <br>
<b>Entrevistado 3:</b> Usa "Beetrack" para localizar direcciones y validar entregas con la firma del cliente.</td>
</tr>
<tr>
<td>Dependencia de documentos físicos (boletas) </td>
<td>2/3</td>
<td>66.7%</td>
<td><b>Entrevistado 1:</b> Utiliza la dirección en las boletas para calcular su ruta.<br>
<b>Entrevistado 2:</b> Se guía con las boletas para obtener la información del pedido.</td>
</tr>
<tr>
<td>Problemas de conectividad (Señal/Internet)</td>
<td>2/3</td>
<td>66.7%</td>
<td><b>Entrevistado 2:</b> La app no funciona en zonas con poca señal, retrasando confirmaciones. <br>
<b>Entrevistado 3: </b>Las fallas de internet complican el proceso de validación.</td>
</tr>
<tr>
<td>Problemas con clientes (Local cerrado/Sin dinero)</td>
<td>3/3</td>
<td>100%</td>
<td><b>Entrevistado 1:</b> Menciona "la recepción por parte del cliente" como inconveniente.<br>
<b>Entrevistado 2: </b>"Tiendas cerradas, clientes sin dinero".<br>
<b>Entrevistado 3:</b> "Locales cerrados o clientes sin dinero".
</td>
</tr>
<tr>
<td>Problemas de logística externa (Tráfico/Mala geolocalización)</td>
<td>3/3</td>
<td>100%</td>
<td><b>Entrevistado 1:</b> Considera información sobre "accidentes, desfiles" para su ruta. <br>
<b>Entrevistado 2:</b> "Mala geoposición" como causa de retraso. <br>
<b>Entrevistado 3:</b> "Tráfico" como retraso principal. </td>
</tr>
<tr>
<td>Uso de canales informales de comunicación (WhatsApp)</td>
<td>2/3</td>
<td>66.7%</td>
<td><b>Entrevistado 2:</b> Reporta inconvenientes por WhatsApp.<br>
<b>Entrevistado 3:</b> Notifica incidentes y contacta al vendedor por WhatsApp</td>
</tr>
<tr>
<td>Rol multifuncional (Conductor y encargado)</td>
<td>3/3</td>
<td>100%</td>
<td><b>Todos los entrevistados </b>son descritos como "chofer y encargado", lo que implica responsabilidades beyond solo manejar, como la liquidación de pedidos (Entrevistado 1) y la gestión de incidencias.</td>
</tr>
<tr>
<td>Frustración con factores externos incontrolables</td>
<td>2/3</td>
<td>66.7%</td>
<td>Entrevistado 3: Muestra "frustración por factores externos como el tráfico y la falta de preparación de clientes". <br>
Entrevistado 2: Los retrasos e incidencias son causados por factores que escapan a su control.</td>
</tr>
</table>

***Insights***

<b>1. Brecha Digital Operativa:</b> Existe una brecha entre la tecnología implementada y la realidad operativa. Las apps son útiles pero fallan en el momento crítico (falta de conectividad), lo que fuerza a los transportistas a crear soluciones híbridas (apps + WhatsApp + documentos físicos) para cumplir con su trabajo, duplicando esfuerzos en algunos casos. Una solución ideal debería integrar un sistema de mensajería robusto que funcione offline o con mala señal, eliminando la necesidad de cambiar de aplicación.

<b>2. Respeto por la experiencia: </b>Para transportistas experimentados, la autonomía y el criterio propio son más valiosos que la supervisión estricta. Una aplicación que priorice el control sobre la utilidad práctica es percibida como un obstáculo, no como una ayuda. La utilidad de una herramienta digital está sujeta a que respete y le apoye en situaciones extraordinarias.

<b>3. Problemas con los retrasos:</b>La principal causa de retrasos e ineficiencias no son fallas técnicas o de planificación de rutas, sino imprevistos originados en el punto de entrega (cliente ausente, sin dinero, local cerrado). Esto sugiere que cualquier solución tecnológica debe incluir mecanismos para mejorar la comunicación y preparación previa del cliente.

***Segmento 2: Administradores***

Se realizo el analisis de 3 entrevistas a los administradores con experiencia en el sector. Con la información obtenida se puede identificar las características claves para el perfil de nuestros segmento objetivo de transportistas.

****Caracteristicas****

<table>
<tr>
<th>Características</th>
<th>Mención</th>
<th>Porcentaje</th>
<th>Evidencia</th>
</tr>
<tr>
<td>Uso de multiples aplicaciones empresariales</td>
<td>3/3</td>
<td>100%</td>
<td><b>Entrevistado 1: </b>Utilizan "Beetrack" para monitoreo y GPS. <br>
<b>Entrevistado 2: </b> Usan "Beetrack", GPS y sensores de refrigeración.  <br>
<b>Entrevistado 3: </b>Poseen "varios aplicativos empresariales con diferentes usos" (avance, inventario, registro).</td>
</tr>
<tr>
<td>Problemas de coordinación y comunicación</td>
<td>2/3</td>
<td>66.7%</td>
<td><b>Entrevistado 1: </b> Planificadores en Lima desconocen las rutas de Cusco. Problemas se resuelven con llamadas al camión y luego a ventas.<br>
<b>Entrevistado 2: </b> La planificación de rutas y solución de problemas del día se hace de manera manual con llamadas y mensajes.</td>
</tr>
<tr>
<td>Dependencia de canales informales (WhatsApp/Llamadas)</td>
<td>2/3</td>
<td>66.7%</td>
<td><b>Entrevistado 1: </b>Arreglan problemas llamando al encargado del camión. <br>
<b>Entrevistado 2: </b> "Se utiliza bastante Whatsapp para la coordinación".</td>
</tr>
<tr>
<td>Problemas con la integridad de la carga (daños, pérdidas, confusión)</td>
<td>2/3</td>
<td>66.7%</td>
<td><b>Entrevistado 1: </b>Verificación manual de la carga. Los transportistas se hacen responsables de las pérdidas.<br>
<b>Entrevistado 2: </b>Incidentes por "confusión en el cargamento" y "daño de los productos" que generan compensaciones económicas.</td>
</tr>
<tr>
<td>Monitoreo en tiempo real del estado de la flota</td>
<td>2/3</td>
<td>66.7%</td>
<td><b>Entrevistado 1:</b> Monitoreo constante con Beetrack.
<b>Entrevistado 2: </b>Monitorean porcentaje de avance, usan GPS para control de rutas y sensores para estado de refrigeración.</td>
</tr>
<tr>
<td>Procesos manuales de verificación y registro</td>
<td>2/3</td>
<td>66.7%</td>
<td><b>Entrevistado 1:</b> Verificación física de la carga por dos personas. <br>
<b>Entrevistado 3:</b> Uso de "documentos de registros o control" además de los aplicativos.</td>
</tr>
</table>

***Insights***

<b>1. Valor a la visibilidad y precisión:</b> Los administradores valoran profundamente la visibilidad en tiempo real de su operación (avance, ubicación, estado de refrigeración). Sin embargo, esta visibilidad se ve empañada cuando los datos de base (como la geolocalización) son inexactos. Un sistema que asegure la calidad y precisión de los datos sería igual de importante como la capacidad de monitoreo.

<b>2. Fragmentación Operativa:</b> Los administradores operan en un ecosistema de herramientas fragmentado. Utilizan múltiples aplicativos especializados (monitoreo, inventario, registro) junto con métodos manuales y canales informales como WhatsApp. Esto sugiere una falta de una plataforma unificada que centralice todas las funciones críticas, lo que puede generar ineficiencia y riesgo de error

<b>3. La desinformación de las rutas</b> Existe una desconexión crítica entre la planificación centralizada y la ejecución operativa en terreno. Los planificadores toman decisiones sin conocimiento contextual real (ej: complejidad de rutas en Cusco vs. Lima), lo que impacta directamente en la eficiencia y el bienestar de los transportistas. Un sistema de planificación necesitaría ser más colaborativa y basada en datos reales de campo.

<b>4. Problemas con la comunicación durante incidentes:</b> Los protocolos para manejar imprevistos (retrasos, incumplimiento) son más reactivos y dependen de la comunicación interpersonal (llamadas, WhatsApp) en lugar de flujos automatizados dentro de una plataforma. Esto hace que la resolución de problemas sea lenta, poco escalable y difícil de trackea.


## 2.3. Needfinding
### 2.3.1. User Personas
En esta sección se presentan dos User Personas que representan los segmentos del proyecto: los Administradores y los Transportistas. Estos perfiles permiten comprender en profundidad las necesidades, motivaciones, frustraciones y comportamientos de los usuarios potenciales del sistema, el cual busca mejorar el seguimiento de rutas, la gestión de pedidos y el control de las operaciones de transporte.

El User Persona Jorge Caceres representa a los administradores de distribución. Jorge Caceres trabaja coordinando diariamente las rutas de camiones y supervisando la correcta entrega de cientos de pedidos. A pesar de su experiencia en el sector, suele enfrentarse a problemas de visibilidad: no siempre sabe en qué punto exacto se encuentran los transportistas ni si los pedidos han sido entregados en orden y a tiempo. Ha intentado usar otras plataformas de gestión, pero se queja de que son demasiado complejas o poco adaptables a la realidad de su empresa. Su motivación principal es tener un control en tiempo real y sin errores, que le permita optimizar rutas, reducir costos y asegurar la satisfacción de los clientes. Jorge busca una herramienta práctica, intuitiva y confiable que le dé autonomía y reduzca su dependencia de reportes manuales.

<img src="assets/images/cap2/Jorge Caceress-user-persona.png" alt="Jorge Caceres">

El User Persona Luis Gutiérrez representa a los transportistas que realizan las entregas en ruta. Luis tiene tiempo trabajando en transporte de mercancías y conoce de primera mano las dificultades de su labor diaria: rutas mal planificadas, entregas duplicadas o mal registradas y la falta de comunicación clara con los administradores. Actualmente utiliza aplicaciones que le resultan confusas y que generan frustración porque no consolidan pedidos de un mismo cliente, obligándolo a hacer viajes innecesarios y perder tiempo valioso. Su principal motivación es contar con una app sencilla y ágil en su teléfono que le muestre claramente su ruta, los pedidos cargados y entregados. Luis quiere reducir la carga administrativa de su trabajo y enfocarse en lo que mejor sabe hacer: transportar y entregar productos de manera segura y puntual.

<img src="assets/images/cap2/Luis Gutierrezz-user-persona.png" alt="Luis Gutierrez">

### 2.3.2. User Task Matrix

La User Task Matrix nos permite descomponer las actividades y tareas que nuestros usuarios realizan al utilizar la solución propuesta. Estas tareas, al clasificarse por su frecuencia e importancia, nos ayudan a priorizar qué funcionalidades de la aplicación deben ser desarrolladas con mayor énfasis para optimizar la experiencia.

Los segmentos considerados para este análisis son:

- **Administrador (Jorge Cáceres)**
- **Transportista (Luis Gutiérrez)**

---

### Task Matrix

| **Tarea**                                                  | **Jorge Cáceres (Administrador)** |        | **Luis Gutiérrez (Transportista)** |        |
| ---------------------------------------------------------- | --------------------------------- | ------ | ---------------------------------- | ------ |
| Supervisar y controlar inventario de productos             | Often                             | High   | Sometimes                          | Medium |
| Coordinar pedidos y entregas                               | Always                            | High   | Often                              | High   |
| Revisar ingresos, costos y márgenes de venta               | Often                             | High   | Rarely                             | Low    |
| Comunicarse con clientes y proveedores                     | Often                             | High   | Sometimes                          | Medium |
| Gestionar incidencias en pedidos (faltantes, devoluciones) | Sometimes                         | High   | Sometimes                          | Medium |
| Optimizar rutas de distribución                            | Rarely                            | Medium | Always                             | High   |
| Confirmar entregas en destino                              | Sometimes                         | Medium | Always                             | High   |
| Cargar y despachar productos al camión                     | Sometimes                         | Low    | Often                              | High   |
| Buscar herramientas para mejorar la gestión logística      | Sometimes                         | Medium | Rarely                             | Low    |

---

***Análisis***

El **administrador** se enfoca en el control y la eficiencia del negocio: supervisa, gestiona pedidos, revisa márgenes de venta y mantiene comunicación constante con los proveedores y demás áreas. Su prioridad está en asegurar que los productos estén disponibles y que las entregas se realicen sin contratiempos, lo cual impacta directamente en la rentabilidad.

El **transportista**, concentra sus esfuerzos en la ejecución operativa de las entregas: optimiza rutas, confirma entregas en destino y monitorea el estado del camión. Su rol está directamente ligado a la puntualidad y la confiabilidad de la distribución, lo que lo convierte en un eslabón esencial.

Ambos perfiles coinciden en la importancia de **gestionar incidencias** y **mantener una comunicación fluida**, ya que cualquier error o retraso impacta tanto en la operación del administrador como en la del transportista.

### 2.3.3. User Journey Mapping

**Jorge Caceres**

<img src="assets/images/cap2/UJM-Administración.png" alt="User Journey Mapping de Transportistas">

**Luis Gutierrez**

<img src="assets/images/cap2/UJM-Transportista.png" alt="User Journey Mapping de Transportistas">

### 2.3.4. Empathy Mapping

**Jorge Caceres**

![Jorge Caceres empathy mapping.png](assets/images/cap2/Jorge%20Caceres%20empathy%20mapping.png)

**Luis Gutiérrez**

![Luis Gutiérrez empathy mapping.png](assets/images/cap2/Luis%20Guti%C3%A9rrez%20empathy%20mapping.png)


### 2.3.5. Big Picture EventStorming

1. Delivery Execution
<p align="center">
  <img src="assets/images/cap2/Big-Picture-EventStorming/Storming AppsWeb - Delivery Execution.jpg" 
       alt="SuscripcionesyPagos" 
       width="250">
</p>

2. Route Management
<p align="center">
  <img src="assets/images/cap2/Big-Picture-EventStorming/Storming AppsWeb - Route Management.jpg" 
       alt="IdentidadyAcceso" 
       width="250">
</p>

3. Operations Monitoring
<p align="center">
  <img src="assets/images/cap2/Big-Picture-EventStorming/Storming AppsWeb - Operations Monitoring.jpg" 
       alt="Recursos" 
       width="250">
</p>

4. Document Management
<p align="center">
  <img src="assets/images/cap2/Big-Picture-EventStorming/Storming AppsWeb - Document Management.jpg" 
       alt="Ejecucion" 
       width="250">
</p>

5. Incident Management
<p align="center">
  <img src="assets/images/cap2/Big-Picture-EventStorming/Storming AppsWeb - Incident Management.jpg" 
       alt="Incidencias" 
       width="250">
</p>


### 2.3.6. Ubiquitous Language
| Term (EN)                                         | Definición (ES)                                                                                                                                                           |
| ------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Worker (Trabajador / “Administrador” en interfaz) | Persona responsable de gestionar operaciones en la plataforma. No es un administrador del sistema, sino un trabajador operativo que organiza rutas, despachos y entregas. |
| Route (Ruta)                                      | Zona de entregas asignada a un vehículo o trabajador. Define un conjunto de destinos a cubrir en un recorrido.                                                            |
| Traveler (Viajero)                                | Representa una zona de entrega lejana, normalmente asociada a mayor tiempo o distancia de recorrido.                                                                      |
| Local (Local)                                     | Representa una zona de entrega cercana, asociada a distancias cortas o repartos inmediatos.                                                                               |
| Dispatch (Despacho)                               | Despacho de salida, embarque, carga de flota.                                                          |
| Client (Cliente)                                  | Bodega o punto de venta al cual se deben entregar los productos. Cada cliente pertenece a una zona de entrega.                                                            |
| Supplier (Proveedor)                              | Empresa abastecedora de los productos a distribuir. En este caso, corresponde a **Gloria**.                                                                               |
| Delivery zone (Zona de entrega)                   | Sector de reparto, zona operativa, clúster de entrega.                                                                        |

## 2.4. Requirements specification
### 2.4.1. User Stories

<table border="1" style="border-collapse:collapse; width:100%; table-layout:fixed;">
  <tr><th style="width:15%;">Epic /<br> Story/<br>ID</th>    <th style="width:15%;">Título</th><th style="width:35%;">Descripción</th>
  <tr>
    <td>EP01</td>
    <td>Registro y autenticación</td>
    <td>
      <b>Como usuario</b>, quiero poder registrar, iniciar sesión, recuperar mi contraseña y cambiarla,
      <p>para poder acceder a la plataforma y mantener mi cuenta segura.</p>
    </td>
  </tr>
  <tr>
    <td>EP02</td>
    <td>Roles y permisos</td>
    <td>
      <b>Como administrador</b>, quiero administrar los diferentes perfiles bajo mi cuenta y otorgarles los permisos pertinentes,
      <p>para que realicen sus trabajos sin que personal no autorizado acceda a información reservada.</p>
    </td>
  </tr>
  <tr>
    <td>EP03</td>
    <td>Suscripciones y organización</td>
    <td>
      <b>Como usuario</b>, quiero manejar y monitorear mis suscripciones,
      <p>para poder crear y gestionar una mayor cantidad de organizaciones y asignarles su respectivo personal.</p>
    </td>
  </tr>
  <tr>
    <td>EP04</td>
    <td>Gestión de clientes</td>
    <td>
      <b>Como administrador</b>, quiero controlar la información, estado y puntos de entrega de clientes frecuentes,
      <p>para agilizar la asignación de zonas de despacho a transportistas.</p>
    </td>
  </tr>
  <tr>
    <td>EP05</td>
    <td>Ubicaciones</td>
    <td>
      <b>Como administrador</b>, quiero registrar, organizar y gestionar ubicaciones relacionadas con las operaciones de transporte,
      <p>para optimizar la planificación de rutas y la logística de entregas.</p>
    </td>
  </tr>
  <tr>
    <td>EP06</td>
    <td>Flota y Recursos</td>
    <td>
      <b>Como administrador</b>, quiero gestionar el estado de los vehículos y los recursos de la flota,
      <p>para garantizar que las unidades estén disponibles, en buen estado y listas para operar.</p>
    </td>
  </tr>
  <tr>
    <td>EP07</td>
    <td>Monitoreo y control de ruta</td>
    <td>
      <b>Como transportista</b>, quiero actualizar los estados de cada pedido a lo largo de la ruta de distribución,
      <p>para proporcionar visibilidad sobre mi progreso y garantizar que administración reciba información actualizada.</p>
    </td>
  </tr>
  <tr>
    <td>EP08</td>
    <td>Incidencias</td>
    <td>
      <b>Como transportista</b>, quiero reportar eventos inesperados que afecten la operación de transporte (retrasos, problemas mecánicos, clientes ausentes),
      <p>para que los administradores reciban notificaciones y puedan resolver o mitigar los problemas oportunamente.</p>
    </td>
  </tr>
  <tr>
    <td>EP09</td>
    <td>Reportes y análisis</td>
    <td>
      <b>Como administrador</b>, quiero generar reportes y análisis detallados sobre el rendimiento de mis vehículos,
      <p>para optimizar la eficiencia, mejorar las rutas y aumentar la satisfacción del cliente.</p>
    </td>
  </tr>
  <tr>
    <td>EP10</td>
    <td>Landing Page e internacionalización</td>
    <td>
      <b>Como visitante</b>, quiero acceder a un sitio web estático bien diseñado, segmentado y disponible en múltiples idiomas,
      <p>para informarme sobre la plataforma y facilitar mi decisión de registrarme.</p>
    </td>
  </tr>
  </table>
  <table border="1" style="border-collapse:collapse; width:100%; table-layout:fixed;">
  <tr>
    <th style="width:15%;">Epic /<br> Story/<br>ID</th>
    <th style="width:15%;">Título</th>
    <th style="width:35%;">Descripción</th>
    <th style="width:25%;">Criterios de Aceptación</th>
    <th style="width:10%;">Relacionado con<br>(Epic ID)</th>
  </tr>
  <tr>
    <td>US01</td>
    <td>Crear cuenta</td>
    <td>
      <b>Como usuario</b>, quiero crear una nueva cuenta,
      <p>para estar registrado en la plataforma.</p>
    </td>
    <td>
      <b>Escenario 1: Creación de usuario</b><br>
      Dado que el usuario selecciona la opción de registro de cuenta,<br>
      Cuando ingresa los datos correspondientes,<br>
      Entonces se le informa que su cuenta se creó con éxito.<br><br>
      <b>Escenario 2: Usuario ya registrado</b><br>
      Dado que el usuario selecciona la opción de registro de cuenta,<br>
      Cuando ingresa los datos correspondientes,<br>
      Entonces la aplicación le avisa que ya existe una cuenta con ese nombre o correo.
    </td>
    <td>EP01</td>
  </tr>
<tr>
<td>US02</td>
<td>Ingreso a la plataforma</td>
<td>
<b>Como usuario</b>, quiero poder ingresar con mi cuenta,
<p>para acceder a la plataforma.</p>
</td>
<td>
<b>Escenario 1: Inicio de sesión</b><br>
Dado que el usuario selecciona la opción iniciar sesión,<br>
Cuando ingresa su cuenta y contraseña correcta,<br>
Entonces la plataforma le permite el acceso.<br><br>
<b>Escenario 2: Error en iniciar sesión</b><br>
Dado que el usuario selecciona la opción iniciar sesión,<br>
Cuando no ingresa la contraseña o nombre correctos,<br>
Entonces aparece un mensaje que le dice que el usuario o contraseña no son correctos.
</td>
<td>EP01</td>
</tr>
<tr>
<td>US03</td>
<td>Creación de rol de equipo de transporte</td>
<td>
  <b>Como administrador</b>, quiero crear roles de equipo de transporte,
  <p>para organizar a los equipos.</p>
</td>
<td>
<b>Escenario 1: Creación exitosa</b><br>
Dado que el administrador entra a la opción de gestión de roles,<br>
Cuando ingresa un nombre y descripción válidos para un nuevo rol,<br>
Entonces el sistema registra el rol y confirma su creación.<br><br>
<b>Escenario 2: Falta de información</b><br>
Dado que el administrador entra a la opción de gestión de roles,<br>
Cuando intenta guardar un rol sin nombre o datos obligatorios,<br>
Entonces el sistema muestra un mensaje de error indicando la falta de información.
</td>
<td>EP02</td>
</tr>
<tr>
<td>US04</td>
<td>Gestión de permisos</td>
<td>
<b>Como administrador con suscripción</b>, quiero dar permisos necesarios a los miembros de los equipos,
<p>para que tengan acceso solo a la información o acciones pertinentes a su rol laboral.</p>
</td>
<td>
<b>Escenario 1: Permiso asignado</b><br>
Dado que el administrador selecciona a un miembro del equipo,<br>
Cuando le asigna un permiso específico relacionado a su rol,<br>
Entonces el sistema registra la asignación y confirma que el permiso fue otorgado.<br><br>
<b>Escenario 2: Permiso denegado</b><br>
Dado que el administrador selecciona a un miembro del equipo,<br>
Cuando intenta asignar un permiso no permitido por la suscripción,<br>
Entonces el sistema muestra un mensaje informando que no es posible otorgar ese permiso.
</td>
<td>EP02</td>
</tr>
<tr>
<td>US05</td>
<td>Gestión de roles del equipo de transporte</td>
<td>
<b>Como administrador</b>, quiero actualizar o modificar los diferentes roles del equipo de transporte,<br>
<p>para renombrar, deshabilitar o habilitar los roles pertinentes a cada equipo de trabajo.</p>
</td>
<td>
<b>Escenario 1: Rol renombrado</b><br>
Dado que el administrador selecciona un rol existente,<br>
Cuando edita su nombre y guarda los cambios,<br>
Entonces el sistema actualiza el rol y confirma la modificación.<br><br>
<b>Escenario 2: Rol habilitado</b><br>
Dado que un rol estaba deshabilitado,<br>
Cuando el administrador lo habilita nuevamente,<br>
Entonces el sistema cambia su estado a activo y lo deja disponible para asignación.<br><br>
<b>Escenario 3: Rol deshabilitado</b><br>
Dado que un rol está en uso o activo,<br>
Cuando el administrador lo deshabilita,<br>
Entonces el sistema cambia su estado a inactivo y lo bloquea para nuevas asignaciones.
</td>
<td>EP02</td>
</tr>
<tr>
<td>US06</td>
<td>Suscripción a planes</td>
<td>
<b>Como usuario</b>, quiero suscribirme a un plan de suscripción,<br>
<p>para poder acceder a los beneficios que este ofrece (ej. más cuentas, plan mensual).</p>
</td>
<td>
<b>Escenario 1: Suscripción exitosa</b><br>
Dado que el usuario selecciona un tipo de plan,<br>
Cuando ingresa la información de pago y confirma la suscripción,<br>
Entonces el sistema activa el plan y habilita los beneficios asociados.<br><br>
<b>Escenario 2: Falta de información</b><br>
Dado que el usuario intenta suscribirse,<br>
Cuando omite información obligatoria de pago o selección de plan,<br>
Entonces el sistema muestra un mensaje de error indicando la falta de datos.
</td>
<td>EP03</td>
</tr>
<tr>
<td>US07</td>
<td>Gestión de perfil de la empresa</td>
<td>
<b>Como usuario con suscripción</b>, quiero crear y modificar el perfil de la empresa,<br>
<p>para personalizar la aplicación en base a la información de esta.</p>
</td>
<td>
<b>Escenario 1: Empresa creada</b><br>
Dado que el usuario accede a la opción de perfil de empresa,<br>
Cuando completa la información requerida y guarda,<br>
Entonces el sistema registra el perfil de la empresa.<br><br>
<b>Escenario 2: Empresa modificada</b><br>
Dado que el usuario ya tiene un perfil registrado,<br>
Cuando actualiza la información de la empresa y guarda,<br>
Entonces el sistema confirma la actualización exitosa.<br><br>
<b>Escenario 3: Falta de información</b><br>
Dado que el usuario intenta registrar o modificar un perfil,<br>
Cuando omite datos obligatorios,<br>
Entonces el sistema muestra un mensaje indicando qué información falta.
</td>
<td>EP03</td>
</tr>
<tr>
<td>US08</td>
<td>Asignación del personal</td>
<td>
<b>Como usuario</b>, quiero agregar al personal al perfil de la empresa,<br>
<p>para hacer un seguimiento de sus actividades.</p>
</td>
<td>
<b>Escenario 1: Asignación exitosa</b><br>
Dado que el usuario accede a la opción de gestión de personal,<br>
Cuando ingresa los datos de un miembro válido,<br>
Entonces el sistema lo asocia correctamente al perfil de la empresa.<br><br>
<b>Escenario 2: Asignación denegada</b><br>
Dado que el usuario intenta asignar a una persona,<br>
Cuando el sistema no encuentra la cuenta ingresada,<br>
Entonces el sistema muestra un mensaje de error indicando que el personal no existe.
</td>
<td>EP03</td>
</tr>
<tr>
<td>US09</td>
<td>Registro de clientes</td>
<td>
<b>Como administrador</b>, quiero registrar clientes frecuentes con su punto de entrega y forma de contacto,<br>
<p>para mantener una lista organizada.</p>
</td>
<td>
<b>Escenario 1: Registro exitoso</b><br>
Dado que el administrador accede a la opción de registro de clientes,<br>
Cuando ingresa la información completa y válida,<br>
Entonces el sistema guarda al cliente y confirma el registro.<br><br>
<b>Escenario 2: Información insuficiente</b><br>
Dado que el administrador intenta registrar un cliente,<br>
Cuando no ingresa todos los campos requeridos,<br>
Entonces el sistema muestra un mensaje indicando qué información falta.
</td>
<td>EP04</td>
</tr>
 <tr> <td>US10</td> <td>Gestión de clientes</td> <td> <b>Como administrador</b>, quiero manejar el estado de los clientes,<br> <p>para poder determinar si están o no disponibles.</p> </td> <td> <b>Escenario 1: Cliente habilitado</b><br> Dado que el cliente estaba inhabilitado,<br> Cuando el administrador lo habilita,<br> Entonces el sistema cambia su estado a activo y disponible.<br><br>
  <b>Escenario 2: Cliente deshabilitado</b><br>
  Dado que el cliente está activo,<br>
  Cuando el administrador lo deshabilita,<br>
  Entonces el sistema cambia su estado a inactivo y restringe su uso en procesos.
</td>
<td>EP04</td>
</tr> <tr> <td>US11</td> <td>Actualizar información de contacto</td> <td> <b>Como administrador</b>, quiero actualizar la información de contacto del cliente,<br> <p>para poder comunicarme con este en caso de algún incidente.</p> </td> <td> <b>Escenario 1: Información modificada</b><br> Dado que el administrador selecciona un cliente registrado,<br> Cuando actualiza la información de contacto y guarda,<br> Entonces el sistema confirma la actualización exitosa.<br><br>
  <b>Escenario 2: Falta de información</b><br>
  Dado que el administrador intenta actualizar un contacto,<br>
  Cuando omite datos obligatorios como teléfono o correo,<br>
  Entonces el sistema muestra un mensaje indicando la falta de información.
</td>
<td>EP04</td>
</tr>
<tr>
<td>US12</td>
<td>Crear ubicación y asignarla a un cliente</td>
<td>
<b>Como administrador</b>, quiero crear una ubicación en el mapa y asignarla a un cliente,<br>
<p>para usarla luego en las rutas.</p>
</td>
<td>
  <b>Escenario 1: Guardar dirección al crear la ubicación</b><br>
  Dado que soy Administrador y seleccioné el cliente "ACME",<br>
  Cuando escojo la ubicación en el mapa en una posición válida,<br>
  Entonces se crea la ubicación con latitud y longitud,<br>
  Y el sistema obtiene la dirección por reverse geocoding,<br>
  Y guarda la dirección formateada y el placeId junto con la ubicación.<br><br>
  <b>Escenario 2: Bloqueo si no hay cliente seleccionado</b><br>
  Dado que soy Administrador en la pantalla de Ubicaciones,<br>
  Y no he seleccionado un cliente,<br>
  Cuando intento guardar la nueva ubicación creada,<br>
  Entonces veo el mensaje "Seleccione un cliente",<br>
  Y la ubicación no se guarda.<br><br>
  <b>Escenario 3: Falla de geocoding con fallback</b><br>
  Dado que soy Administrador y seleccioné el cliente "ACME",<br>
  Y el servicio de geocoding no responde,<br>
  Cuando creo un punto en el mapa en una posición válida,<br>
  Entonces se muestra "Dirección no disponible" con opción de reintentar o editar manualmente.
</td>
<td>EP05</td>
</tr>
<tr>
<td>US13</td>
<td>Reubicar una ubicación existente</td>
<td>
  <b>Como administrador</b>, quiero mover el marcador de una ubicación,<br>
  <p>para corregir su posición sin perder la relación con el cliente.</p>
</td>
<td>
  <b>Escenario 1: Reubicar arrastrando el marcador</b><br>
  Dado una ubicación existente asociada al cliente "ACME",<br>
  Cuando arrastro el marcador a una nueva posición,<br>
  Entonces la latitud y longitud de la ubicación se actualizan,<br>
  Y el sistema guarda el cambio correctamente.<br><br>
  <b>Escenario 2: Validar coordenadas obligatorias</b><br>
  Dado una ubicación existente sin latitud o longitud válidas,<br>
  Cuando intento utilizarla en la planificación de una ruta,<br>
  Entonces el sistema impide seleccionarla,<br>
  Y veo el mensaje "La ubicación requiere coordenadas válidas".
</td>
<td>EP05</td>
</tr>
<tr>
<td>US14</td>
<td>Inhabilitar ubicación</td>
<td>
  <b>Como administrador</b>, quiero marcar una ubicación como cerrada,<br>
  <p>para que no pueda usarse en nuevas rutas.</p>
</td>
<td>
  <b>Escenario 1: Marcar ubicación como cerrada</b><br>
  Dado una ubicación activa asociada al cliente "ACME",<br>
  Cuando la marco como "Cerrada",<br>
  Entonces su estado pasa a "Inhabilitada",<br>
  Y deja de aparecer en los listados por defecto,<br>
  Y no puede seleccionarse en formularios de planificación.
</td>
<td>EP05</td>
</tr>
<tr>
<td>US15</td>
<td>Filtrar puntos por cliente en el mapa</td>
<td>
  <b>Como administrador</b>, quiero buscar un cliente por nombre y ver solo sus puntos en el pa,<br>
  <p>para seleccionar rápidamente los puntos correctos.</p>
</td>
<td>
  <b>Escenario 1: Filtrar puntos por nombre de cliente</b><br>
  Dado que estoy en la pantalla de planificación con el mapa visible,<br>
  Y escribo "ACME" en el buscador de clientes,<br>
  Cuando selecciono el cliente "ACME",<br>
  Entonces el mapa muestra solo los puntos de "ACME",<br>
  Y los demás puntos se atenúan o se ocultan.<br><br>
  <b>Escenario 2: Limpiar filtro</b><br>
  Dado que tengo aplicado el filtro del cliente "ACME",<br>
  Cuando presiono "Limpiar filtro",<br>
  Entonces el mapa vuelve a mostrar todos los puntos disponibles.
</td>
<td>EP05</td>
</tr>
<tr>
<td>US16</td>
<td>Agregar/Quitar puntos en una ruta</td>
<td>
  <b>Como administrador</b>, quiero asignar o quitar puntos en la ruta del día,<br>
  <p>para crear entregas rápidamente.</p>
</td>
<td>
  <b>Escenario 1: Asignar punto disponible a la ruta en borrador</b><br>
  Dado una ruta en estado "borrador" para la fecha 2025-09-17,<br>
  Y un punto "P-001" disponible para esa fecha,<br>
  Cuando selecciono el punto "P-001",<br>
  Entonces se muestra la información del punto,<br>
  Y al presionar “Agregar a la ruta” el punto queda reservado para la fecha 2025-09-17.r><br>
  <b>Escenario 2: Impedir duplicado el mismo día</b><br>
  Dado que el punto "P-001" ya está reservado en otra ruta para 2025-09-17,<br>
  Cuando intento seleccionarlo,<br>
  Entonces veo el mensaje "Este punto ya está asignado a otra ruta hoy",<br>
  Y el punto no se agrega a la ruta activa.<br><br>
  <b>Escenario 3: Quitar punto de la ruta</b><br>
  Dado que el punto "P-002" está asignado a la ruta en borrador,<br>
  Cuando selecciono nuevamente "P-002",<br>
  Entonces se muestra la información del punto,<br>
  Y aparece el botón “Quitar de la ruta”.
</td>
<td>EP05</td>
</tr>
<tr>
<td>US17</td>
<td>Registrar vehículo</td>
<td>
<b>Como administrador</b>, quiero registrar un vehículo con placa y capacidad,<br>
<p>para poder asignarlo a una ruta.</p>
</td>
<td>
<b>Escenario 1: Registro exitoso</b><br>
Dado que soy Administrador en la pantalla de Vehículos,<br>
Cuando registro un vehículo con placa "ABC-123" y capacidad 1500 kg,<br>
Entonces el vehículo queda creado en estado "habilitado".<br><br>
<b>Escenario 2: Placa duplicada</b><br>
Dado que existe un vehículo con placa "ABC-123",<br>
Cuando intento registrar otro vehículo con la misma placa,<br>
Entonces veo el mensaje "La placa ya está registrada",<br>
Y el vehículo no se crea.
</td>
<td>EP06</td>
</tr>
<tr>
<td>US18</td>
<td>Inhabilitar vehículo</td>
<td>
<b>Como administrador</b>, quiero inhabilitar un vehículo,<br>
<p>para evitar que se use en nuevas rutas.</p>
</td>
<td>
<b>Escenario 1: Inhabilitar evita nuevas asignaciones</b><br>
Dado un vehículo "ABC-123" en estado "habilitado",<br>
Cuando lo cambio a estado "inhabilitado",<br>
Entonces el sistema impide asignarlo a rutas nuevas,<br>
Y al intentar publicar una ruta que lo incluye,<br>
Entonces veo el mensaje "El vehículo está inhabilitado" y la publicación se bloquea.
</td>
<td>EP06</td>
</tr>
<tr>
<td>US19</td>
<td>Publicar ruta bloquea edición</td>
<td>
<b>Como administrador</b>, quiero bloquear cambios al publicar,<br>
<p>para evitar modificaciones después de la planificación.</p>
</td>
<td>
<b>Escenario 1: Bloquear edición tras publicar</b><br>
Dado una ruta en estado "borrador" con entregas asignadas,<br>
Cuando publico la ruta,<br>
Entonces el estado cambia a "publicada",<br>
Y ya no puedo añadir ni quitar puntos.<br><br>
<b>Escenario 2: Impedir agregar punto en ruta publicada</b><br>
Dado una ruta en estado "publicada",<br>
Cuando intento asignar un nuevo punto desde el mapa,<br>
Entonces veo "La ruta está publicada y no admite cambios",<br>
Y el punto no se agrega.<br><br>
<b>Escenario 3: Publicación incompleta</b><br>
Dado que he creado una ruta sin vehículo o sin entregas,<br>
Cuando intento publicarla,<br>
Entonces veo el mensaje "Asigne un vehículo y al menos una entrega para publicar",<br>
Y la ruta permanece en estado "borrador".
</td>
<td>EP06</td>
</tr>
<tr>
<td>US20</td>
<td>Crear una ruta en borrador</td>
<td>
<b>Como administrador</b>, quiero crear una ruta del día y guardarla como borrador,<br>
<p>para que los transportistas aún no vean la ruta antes de publicarla.</p>
</td>
<td>
<b>Escenario 1: Crear ruta en borrador</b><br>
Dado que soy Administrador en la pantalla de Rutas,<br>
Cuando ingreso la fecha "2025-09-18" y un nombre de ruta válido,<br>
Entonces se crea la ruta con estado "borrador",<br>
Y queda disponible para asignar vehículo y puntos.<br><br>
<b>Escenario 2: Validar fecha obligatoria</b><br>
Dado que no ingreso una fecha al crear la ruta,<br>
Cuando intento guardar,<br>
Entonces veo el mensaje "Debe ingresar una fecha válida",<br>
Y la ruta no se crea.
</td>
<td>EP07</td>
</tr>
<tr>
<td>US21</td>
<td>Transportista actualiza estado de entrega</td>
<td>
<b>Como transportista</b>, quiero marcar una entrega como entregada o rechazada con motivo,br>
<p>para dejar constancia del resultado.</p>
</td>
<td>
<b>Escenario 1: Marcar entrega como finalizada</b><br>
Dado una ruta publicada que ha sido iniciada,<br>
Y una entrega en estado "pendiente",<br>
Cuando marco la entrega como "entregada",<br>
Entonces la entrega cambia a estado "entregada",<br>
Y se registra la hora de confirmación y se actualiza su progreso de entrega.<br><br>
<b>Escenario 2: Marcar entrega como rechazada con motivo</b><br>
Dado una ruta publicada que ha sido iniciada,<br>
Y una entrega en estado "pendiente",<br>
Cuando marco la entrega como "rechazada" e ingreso el motivo "Destinatario ausente",<br>
Entonces la entrega cambia a estado "rechazada",<br>
Y el motivo queda guardado y se actualiza el progreso de entregas con rechazo.
</td>
<td>EP07</td>
</tr>
<tr>
<td>US22</td>
<td>Cierre de ruta con y sin pendientes</td>
<td>
<b>Como transportista</b>, quiero cerrar la ruta al finalizar y reprogramar pendientes,<br>
<p>para visualizar deudas y continuar al día siguiente.</p>
</td>
<td>
<b>Escenario 1: Cierre normal sin pendientes</b><br>
Dado una ruta iniciada cuyas entregas están todas en estado terminal,<br>
Cuando cierro la ruta,<br>
Entonces el estado de la ruta cambia a "completada".<br><br>
<b>Escenario 2: Cierre forzado con pendientes y reprogramación</b><br>
Dado una ruta iniciada con entregas en estado "pendiente",<br>
Cuando cierro la ruta en modo "forzado",<br>
Entonces el estado de la ruta cambia a "cerrada con pendientes",<br>
Y las entregas pendientes se listarán en la ruta como entregas pendientes.
</td>
<td>EP07</td>
</tr>
<tr>
<td>US23</td>
<td>Vista previa de la ruta</td>
<td>
<b>Como administrador</b>, quiero una vista previa que resalte solo los puntos asignados,br>
<p>para validar la selección antes de publicar.</p>
</td>
<td>
<b>Escenario 1: Mostrar solo los puntos asignados</b><br>
Dado una ruta en borrador con puntos asignados,<br>
Cuando activo la "Vista previa",<br>
Entonces el mapa centra y resalta únicamente los puntos de la ruta,<br>
Y se muestra una lista lateral con los puntos seleccionados.
</td>
<td>EP07</td>
</tr>
<tr>
<td>US24</td>
<td>Visualización de progreso</td>
<td>
<b>Como administrador</b>, quiero ver el progreso de las entregas en tiempo real,<br>
<p>para saber exactamente cuánto falta por completar y tomar decisiones oportunas.</p>
</td>
<td>
<b>Escenario 1: Estado actualizado</b><br>
Dado que un pedido está en tránsito,<br>
Cuando el transportista avanza en la ruta,<br>
Entonces el administrador puede ver los avances en el panel de monitoreo mediante líneas de progreso.<br><br>
<b>Escenario 2: Notificación automática</b><br>
Dado que el pedido cambia de estado,<br>
Cuando pasa a "Rechazo",<br>
Entonces el administrador recibe una alerta en el sistema de gestión para registrar el  y tomar acción si es necesario.
</td>
<td>EP07</td>
</tr>
<tr>
<td>US25</td>
<td>Visualizar rutas asignadas</td>
<td>
<b>Como transportista</b>, quiero quiero ver las rutas que me han sido asignadas para el día,<br>
<p>para conocer mis entregas pendientes y planificar mi recorrido.</p>
</td>
<td>
<b>Escenario 1: Ver ruta del día</b><br>
Dado que he iniciado sesión en la aplicación,<br>
Cuando ingreso a la sección “Mis rutas”,<br>
Entonces veo una lista con las rutas asignadas del día y su estado (en progreso, completadas o rechazadas).
<br><br>
<b>Escenario 2: Detalle de ruta seleccionada</b><br>
Dado que selecciono una ruta,<br>
Cuando entro al detalle,<br>
Entonces se muestra el mapa con los puntos de entrega, el progreso (X/Y completadas) y el listado de clientes con dirección.
</td>
<td>EP07</td>
</tr>
<tr>
<td>US26</td>
<td>Filtrar entregas por estado</td>
<td>
<b>Como transportista</b>, quiero filtrar mis entregas según su estado (in progress, completed, rejected),<br>
<p>para organizar mejor mi jornada.</p>
</td>
<td>
<b>Escenario 1: Filtro aplicado</b><br>
Dado que estoy en la vista de mis entregas,<br>
Cuando selecciono un filtro de estado,<br>
Entonces se muestran únicamente las entregas correspondientes a ese estado.<br><br>
<b>Escenario 2: Filtro limpio</b><br>
Dado que tengo un filtro activo,<br>
Cuando presiono “Todos”,<br>
Entonces vuelvo a ver la lista completa de entregas.
</td>
<td>EP07</td>
</tr>
<tr>
<td>US27</td>
<td>Marcar entrega como completada</td>
<td>
<b>Como transportista</b>, quiero marcar una entrega como completada,<br>
<p>para registrar su cumplimiento y actualizar el progreso total de la ruta.
</p>
</td>
<td>
<b>Escenario 1:  Entrega completada exitosamente</b><br>
Dado que tengo una entrega en estado “in progress”,<br>
Cuando presiono el botón “Complete”,<br>
Entonces la entrega cambia a estado “Completed” y se actualiza la barra de progreso.<br><br>
<b>Escenario 2: Actualización del progreso total</b><br>
Dado que completo una entrega,<br>
Cuando el sistema recalcula el total,<br>
Entonces el progreso se muestra actualizado (por ejemplo, “3/8 completadas – 37%”).
</td>
<td>EP07</td>
</tr>
<tr>
<td>US28</td>
<td>Rechazar entrega y registrar motivo</td>
<td>
<b>Como transportista</b>, quiero poder rechazar una entrega e indicar el motivo del rechazo,<br>
<p>para que el administrador conozca la causa.
</p>
</td>
<td>
<b>Escenario 1: Selección de motivo predefinido</b><br>
Dado que selecciono “Reject”,<br>
Cuando se abre el modal de rechazo,<br>
Entonces puedo elegir entre los motivos predefinidos (cliente ausente, dirección incorrecta, cliente rechazó entrega, otro motivo).
<br><br>
<b>Escenario 2: Ingreso de detalle adicional</b><br>
Dado que selecciono “Otro motivo”,<br>
Cuando escribo una descripción,<br>
Entonces el sistema guarda el texto junto al registro del rechazo.
<br><br>
<b>Escenario 3: Estado actualizado</b><br>
Dado que confirmo el rechazo,<br>
Cuando cierro el modal,<br>
Entonces la entrega cambia a estado “Rejected” y el progreso se actualiza automáticamente.
</td>
<td>EP07</td>
</tr>
<tr>
<td>US29</td>
<td>Asignación de flota a la ruta</td>
<td>
<b>Como administrador</b>, quiero asignar vehículos y transportistas disponibles a una ruta planificada,<br>
<p>para asegurar que cada vehiculo tenga un equipo asignado y las entregas puedan ejecutarse sin retrasos.</p>
</td>
<td>
<b>Escenario 1: Selección de ruta para asignar flota</b><br>
Dado que el administrador se encuentra en la vista Routes List,<br>
Cuando selecciona una ruta con estado “Pending assignment” y presiona el botón “Assign”,<br>
Entonces el sistema abre el módulo Locations mostrando los puntos de entrega asociados a esa ruta.<br><br>
<b>Escenario 2: Asignación de equipo de transporte</b><br>
Dado que el administrador ha visualizado las ubicaciones y detalles de la ruta,<br>
Cuando accede a la sección Teams y selecciona un transportista y vehículo disponibles,<br>
Entonces el sistema asigna automáticamente esa flota a la ruta seleccionada, mostrando su estado como “Assigned”.
</td>
<td>EP07</td>
</tr>
<tr>
<td>US30</td>
<td>Adjuntar evidencia</td>
<td>
<b>Como transportista</b>, quiero adjuntar fotos al registrar una incidencia,<br>
<p>para que Administración tenga pruebas claras de la situación.</p>
</td>
<td>
<b>Escenario 1: Foto como evidencia</b><br>
Dado que el transportista reporta "Cliente ausente",<br>
Cuando adjunta una foto de la ubicación y la tienda cerrada,<br>
Entonces la evidencia queda registrada junto a la incidencia.
</td>
<td>EP08</td>
</tr>
<tr>
<td>US31</td>
<td>Etiquetado de incidencias por prioridad</td>
<td>
<b>Como administrador</b>, quiero que las incidencias reportadas por los transportistas se etiqueten según su nivel de prioridad,<br>
<p>para identificar rápidamente cuáles requieren atención inmediata y gestionarlas de manera eficiente.</p>
</td>
<td>
<b>Escenario 1: Priorización de incidencia etiquetada como urgente</b><br>
Dado que hay múltiples incidencias registradas en el sistema,<br>
Cuando un transportista reporta una incidencia y la etiqueta como "Urgente" (ej. avería grave del vehículo),<br>
Entonces el sistema destaca la incidencia en la interfaz del administrador (ej. con alerta visual o en la parte superior de la lista),<br>
Y se envía al apartado de incidencias.<br><br>
<b>Escenario 2: Rechazo de entrega por mercadería dañada</b><br>
Dado que un transportista reporta una incidencia de "Cliente no acepta el pedido" por mercadería dañada,<br>
Cuando el transportista etiqueta la incidencia como "Media" y adjunta evidencia (ej. foto del daño),<br>
Entonces el sistema registra la incidencia con la etiqueta "Media" y la evidencia,<br>
Y se adjunta en el apartado de incidencias para coordinar la reposición o reprogramación de la entrega.
</td>
<td>EP08</td>
</tr>
<tr>
<td>US32</td>
<td>Generación de reportes operativos</td>
<td>
<b>Como administrador</b>, quiero generar reportes de entregas completadas, fallidas y pendientes,<br>
<p>para evaluar el desempeño logístico y tomar decisiones de mejora.</p>
</td>
<td>
<b>Escenario 1: Reporte diario</b><br>
Dado que finaliza la jornada de entregas,<br>
Cuando el administrador genera el reporte,<br>
Entonces se visualizan métricas de pedidos entregados, fallidos y pendientes.<br><br>
<b>Escenario 2: Exportación de reporte</b><br>
Dado que el administrador consulta un reporte en el sistema,<br>
Cuando selecciona la opción "Exportar",<br>
Entonces se descarga el archivo en formato Excel.
</td>
<td>EP09</td>
</tr>
  <tr>
    <td>US33</td>
    <td>Diseño responsivo y navegación</td>
    <td>
      <b>Como visitante</b>, quiero que la landing page se adapte a cualquier dispositivo y tenga navegación clara,
      <p>para explorar fácilmente la información sin importar si uso móvil, tablet o escritorio.</p>
    </td>
    <td>
      <b>Escenario 1: Vista en dispositivos móviles</b><br>
      Dado que el visitante abre la landing page en un celular,<br>
      Cuando navega entre secciones,<br>
      Entonces el contenido se adapta sin perder legibilidad ni usabilidad.<br><br>
      <b>Escenario 2: Navegación intuitiva</b><br>
      Dado que el visitante ingresa al sitio,<br>
      Cuando usa el menú principal,<br>
      Entonces puede acceder rápidamente a las secciones principales sin confusión.
    </td>
    <td>EP10</td>
  </tr>
  <tr>
    <td>US34</td>
    <td>Secciones segmentadas</td>
    <td>
      <b>Como visitante del segmento empresa de transporte</b>, quiero ver una sección dedicada con beneficios y planes,
      <p>para evaluar si la plataforma se ajusta a las necesidades de mi negocio.</p>
    </td>
    <td>
      <b>Escenario 1: Visualización de planes</b><br>
      Dado que el visitante navega a la sección de empresas de transporte,<br>
      Cuando revisa el contenido,<br>
      Entonces visualiza información sobre los planes premium y sus beneficios.<br><br>
      <b>Escenario 2: Segmento correcto</b><br>
      Dado que existen diferentes tipos de visitantes,<br>
      Cuando un visitante del segmento "transportista independiente" ingresa,<br>
      Entonces ve una sección adaptada a sus necesidades específicas.
    </td>
    <td>EP10</td>
  </tr>
  <tr>
    <td>US35</td>
    <td>Internacionalización (i18n)</td>
    <td>
      <b>Como visitante internacional</b>, quiero poder seleccionar el idioma de la landing page (ej. español o inglés),
      <p>para comprender claramente la propuesta de valor sin barreras idiomáticas.</p>
    </td>
    <td>
      <b>Escenario 1: Selección de idioma</b><br>
      Dado que el visitante está en la landing page,<br>
      Cuando selecciona "Inglés" en el selector de idioma,<br>
      Entonces todo el contenido se muestra en inglés.<br><br>
      <b>Escenario 2: Idioma por defecto</b><br>
      Dado que un visitante abre la página sin seleccionar idioma,<br>
      Cuando el sistema detecta la configuración de su navegador,<br>
      Entonces la landing page se muestra en el idioma más adecuado automáticamente.
    </td>
    <td>EP10</td>
  </tr>
</table>

### 2.4.2. Impact Mapping

A continuación se presenta el Impact Map de Rutana, el cual permite visualizar de manera clara
cómo las funcionalidades clave de la aplicación se alinean con los objetivos de negocio, considerando
a los actores involucrados y los impactos esperados en su comportamiento.
<p align="center">
  <img src="assets/images/cap2/impact mapping.png" 
       alt="impact mapping" 
       width="550">
</p>

### 2.4.3. Product Backlog

<table border="1" style="border-collapse:collapse; width:100%; table-layout:fixed;">
  <tr>
    <th style="width:4%; word-wrap:break-word; white-space:normal;"># Orden</th>
    <th style="width:10%; word-wrap:break-word; white-space:normal;">User Story Id</th>
    <th style="width:24%; word-wrap:break-word; white-space:normal;">Título</th>
    <th style="width:42%; word-wrap:break-word; white-space:normal;">Descripción</th>
    <th style="width:20%; word-wrap:break-word; white-space:normal;">Story Points <br> (1 / 2 / 3 / 5 / 8)</th>
  </tr>
  <tr>
    <td>1</td>
    <td>US34</td>
    <td>Secciones segmentadas</td>
    <td><b>Como empresa de transporte</b>, quiero una sección dedicada con beneficios y planes,<br><p>para evaluar si se ajusta a mi negocio.</p>
        <b>Escenario 1:</b> Visualización de planes. <br>
        <b>Escenario 2:</b> Segmento correcto por tipo de visitante.</td>
    <td>1</td>
  </tr>
  <tr>
    <td>2</td>
    <td>US33</td>
    <td>Diseño responsivo y navegación</td>
    <td><b>Como visitante</b>, quiero que la landing se adapte y sea clara,<br><p>para explorar en móvil/tablet/desktop.</p>
        <b>Escenario 1:</b> Vista móvil usable. <br>
        <b>Escenario 2:</b> Navegación intuitiva.</td>
    <td>1</td>

  </tr>
  <tr>
    <td>3</td>
    <td>US35</td>
    <td>Internacionalización (i18n)</td>
    <td><b>Como visitante internacional</b>, quiero seleccionar idioma (ES/EN),<br><p>para entender la propuesta sin barreras.</p>
        <b>Escenario 1:</b> Selector de idioma. <br>
        <b>Escenario 2:</b> Idioma por defecto según navegador.</td>
    <td>2</td>
  </tr>
  <tr>
    <td>4</td>
    <td>US01</td>
    <td>Crear cuenta</td>
    <td><b>Como usuario</b>, quiero crear una nueva cuenta,<br><p>para estar registrado en la plataforma.</p>
        <b>Escenario 1:</b> Creación de usuario. <br>
        <b>Escenario 2:</b> Usuario ya registrado.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>5</td>
    <td>US02</td>
    <td>Ingreso a la plataforma</td>
    <td><b>Como usuario</b>, quiero poder ingresar con mi cuenta,<br><p>para acceder a la plataforma.</p>
        <b>Escenario 1:</b> Inicio de sesión. <br>
        <b>Escenario 2:</b> Error en iniciar sesión.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>6</td>
    <td>US03</td>
    <td>Creación de rol de equipo de transporte</td>
    <td><b>Como administrador</b>, quiero crear roles de equipo de transporte,<br><p>para organizar a los equipos.</p>
        <b>Escenario 1:</b> Creación exitosa. <br>
        <b>Escenario 2:</b> Falta de información.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>7</td>
    <td>US04</td>
    <td>Gestión de permisos</td>
    <td><b>Como administrador con suscripción</b>, quiero dar permisos a los miembros,<br><p>para limitar el acceso según su rol.</p>
        <b>Escenario 1:</b> Permiso asignado. <br>
        <b>Escenario 2:</b> Permiso denegado por plan.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>8</td>
    <td>US05</td>
    <td>Gestión de roles del equipo de transporte</td>
    <td><b>Como administrador</b>, quiero actualizar/renombrar/deshabilitar roles,<br><p>para mantenerlos vigentes por equipo.</p>
        <b>Escenario 1:</b> Rol renombrado. <br>
        <b>Escenario 2:</b> Rol habilitado. <br>
        <b>Escenario 3:</b> Rol deshabilitado.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>9</td>
    <td>US06</td>
    <td>Suscripción a planes</td>
    <td><b>Como usuario</b>, quiero suscribirme a un plan,<br><p>para acceder a beneficios (más cuentas, plan mensual).</p>
        <b>Escenario 1:</b> Suscripción exitosa. <br>
        <b>Escenario 2:</b> Falta de información.</td>
    <td>5</td>
  </tr>
  <tr>
    <td>10</td>
    <td>US07</td>
    <td>Gestión de perfil de la empresa</td>
    <td><b>Como usuario con suscripción</b>, quiero crear/modificar el perfil de empresa,<br><p>para personalizar la aplicación.</p>
        <b>Escenario 1:</b> Empresa creada. <br>
        <b>Escenario 2:</b> Empresa modificada. <br>
        <b>Escenario 3:</b> Falta de información.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>11</td>
    <td>US08</td>
    <td>Asignación del personal</td>
    <td><b>Como usuario</b>, quiero agregar personal al perfil de empresa,<br><p>para dar seguimiento a sus actividades.</p>
        <b>Escenario 1:</b> Asignación exitosa. <br>
        <b>Escenario 2:</b> Asignación denegada (usuario no existe).</td>
    <td>3</td>
  </tr>
  <tr>
    <td>12</td>
    <td>US09</td>
    <td>Registro de clientes</td>
    <td><b>Como administrador</b>, quiero registrar clientes frecuentes,<br><p>para mantener una lista organizada.</p>
        <b>Escenario 1:</b> Registro exitoso. <br>
        <b>Escenario 2:</b> Información insuficiente.</td>
    <td>2</td>
  </tr>
  <tr>
    <td>13</td>
    <td>US10</td>
    <td>Gestión de clientes</td>
    <td><b>Como administrador</b>, quiero habilitar/inhabilitar clientes,<br><p>para controlar su disponibilidad.</p>
        <b>Escenario 1:</b> Cliente habilitado. <br>
        <b>Escenario 2:</b> Cliente deshabilitado.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>14</td>
    <td>US11</td>
    <td>Actualizar información de contacto</td>
    <td><b>Como administrador</b>, quiero actualizar contactos del cliente,<br><p>para comunicar incidentes.</p>
        <b>Escenario 1:</b> Información modificada. <br>
        <b>Escenario 2:</b> Falta de información.</td>
    <td>2</td>
  </tr>
  <tr>
    <td>15</td>
    <td>US12</td>
    <td>Crear ubicación y asignarla a un cliente</td>
    <td><b>Como administrador</b>, quiero crear una ubicación en el mapa,<br><p>para usarla luego en rutas.</p>
        <b>Escenario 1:</b> Guardar dirección (reverse geocoding). <br>
        <b>Escenario 2:</b> Bloqueo sin cliente seleccionado. <br>
        <b>Escenario 3:</b> Falla de geocoding con fallback.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>16</td>
    <td>US13</td>
    <td>Reubicar una ubicación existente</td>
    <td><b>Como administrador</b>, quiero mover el marcador de una ubicación,<br><p>para corregir su posición.</p>
        <b>Escenario 1:</b> Reubicar arrastrando. <br>
        <b>Escenario 2:</b> Validar coordenadas obligatorias.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>17</td>
    <td>US14</td>
    <td>Inhabilitar ubicación</td>
    <td><b>Como administrador</b>, quiero marcar una ubicación como cerrada,<br><p>para no usarla en nuevas rutas.</p>
        <b>Escenario 1:</b> Marcar como cerrada e impedir selección.</td>
    <td>2</td>
  </tr>
  <tr>
    <td>18</td>
    <td>US15</td>
    <td>Filtrar puntos por cliente en el mapa</td>
    <td><b>Como administrador</b>, quiero ver solo los puntos de un cliente,<br><p>para seleccionar rápidamente.</p>
        <b>Escenario 1:</b> Filtrar por nombre. <br>
        <b>Escenario 2:</b> Limpiar filtro.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>19</td>
    <td>US16</td>
    <td>Agregar/Quitar puntos en una ruta</td>
    <td><b>Como administrador</b>, quiero asignar o quitar puntos en la ruta del día,<br><p>para crear entregas rápidamente.</p>
        <b>Escenario 1:</b> Asignar y reservar punto. <br>
        <b>Escenario 2:</b> Impedir duplicado el mismo día. <br>
        <b>Escenario 3:</b> Quitar punto.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>20</td>
    <td>US17</td>
    <td>Registrar vehículo</td>
    <td><b>Como administrador</b>, quiero registrar un vehículo con placa y capacidad,<br><p>para asignarlo a una ruta.</p>
        <b>Escenario 1:</b> Registro exitoso. <br>
        <b>Escenario 2:</b> Placa duplicada.</td>
    <td>2</td>
  </tr>
  <tr>
    <td>21</td>
    <td>US18</td>
    <td>Inhabilitar vehículo</td>
    <td><b>Como administrador</b>, quiero inhabilitar un vehículo,<br><p>para evitar su uso en nuevas rutas.</p>
        <b>Escenario 1:</b> Bloquea nuevas asignaciones/publicación.</td>
    <td>2</td>
  </tr>
  <tr>
    <td>22</td>
    <td>US19</td>
    <td>Publicar ruta bloquea edición</td>
    <td><b>Como administrador</b>, quiero bloquear cambios al publicar,<br><p>para evitar modificaciones posteriores.</p>
        <b>Escenario 1:</b> Bloquear edición tras publicar. <br>
        <b>Escenario 2:</b> Impedir agregar punto en publicada. <br>
        <b>Escenario 3:</b> Validar requisitos mínimos.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>23</td>
    <td>US20</td>
    <td>Crear una ruta en borrador</td>
    <td><b>Como administrador</b>, quiero crear una ruta del día en borrador,<br><p>para ocultarla hasta publicar.</p>
        <b>Escenario 1:</b> Crear borrador. <br>
        <b>Escenario 2:</b> Validar fecha obligatoria.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>24</td>
    <td>US21</td>
    <td>Transportista actualiza estado de entrega</td>
    <td><b>Como transportista</b>, quiero marcar entregada o rechazada con motivo,<br><p>para dejar constancia.</p>
        <b>Escenario 1:</b> Entrega finalizada. <br>
        <b>Escenario 2:</b> Rechazada con motivo.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>25</td>
    <td>US22</td>
    <td>Cierre de ruta con y sin pendientes</td>
    <td><b>Como transportista</b>, quiero cerrar la ruta y reprogramar pendientes,<br><p>para continuar al día siguiente.</p>
        <b>Escenario 1:</b> Cierre normal. <br>
        <b>Escenario 2:</b> Cierre forzado con pendientes.</td>
    <td>2</td>
  </tr>
  <tr>
    <td>26</td>
    <td>US23</td>
    <td>Vista previa de la ruta</td>
    <td><b>Como administrador</b>, quiero una vista previa con solo puntos asignados,<br><p>para validar antes de publicar.</p>
        <b>Escenario 1:</b> Mostrar y resaltar puntos asignados.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>27</td>
    <td>US24</td>
    <td>Visualización de progreso</td>
    <td><b>Como administrador</b>, quiero ver progreso en tiempo real y alertas,<br><p>para tomar decisiones oportunas.</p>
        <b>Escenario 1:</b> Estado actualizado en panel. <br>
        <b>Escenario 2:</b> Notificación automática.</td>
    <td>3</td>
  </tr>
<tr>
 <td>28</td>
<td>US25</td>
<td>Visualizar rutas asignadas</td>
<td>
<b>Como transportista</b>, quiero quiero ver las rutas que me han sido asignadas para el día,<br>
<p>para conocer mis entregas pendientes y planificar mi recorrido.</p>
<b>Escenario 1: Ver ruta del día</b><br>
<b>Escenario 2: Detalle de ruta seleccionada</b><br>
</td>
<td>5</td>
</tr>
<tr>
 <td>29</td>
<td>US26</td>
<td>Filtrar entregas por estado</td>
<td>
<b>Como transportista</b>, quiero filtrar mis entregas según su estado (in progress, completed, rejected),<br>
<p>para organizar mejor mi jornada.</p>
<b>Escenario 1: Filtro aplicado</b><br>
<b>Escenario 2: Filtro limpio</b><br>
</td>
<td>3</td>
</tr>
<tr>
 <td>30</td>
<td>US27</td>
<td>Marcar entrega como completada</td>
<td>
<b>Como transportista</b>, quiero marcar una entrega como completada,<br>
<p>para registrar su cumplimiento y actualizar el progreso total de la ruta.
</p>
<b>Escenario 1:  Entrega completada exitosamente</b><br>
zación del progreso total</b><br>
</td>
<td>3</td>
</tr>
<tr>
 <td>31</td>
<td>US28</td>
<td>Rechazar entrega y registrar motivo</td>
<td>
<b>Como transportista</b>, quiero poder rechazar una entrega e indicar el motivo del rechazo,<br>
<p>para que el administrador conozca la causa.
</p>
<b>Escenario 1: Selección de motivo predefinido</b><br>
<b>Escenario 2: Ingreso de detalle adicional</b><br>
<b>Escenario 3: Estado actualizado</b><br>
</td>
<td>3</td>
</tr>
<tr>
 <td>32</td>
<td>US29</td>
<td>Asignación de flota a la ruta</td>
<td>
<b>Como administrador</b>, quiero asignar vehículos y transportistas disponibles a una ruta planificada,<br>
<p>para asegurar que cada vehiculo tenga un equipo asignado y las entregas puedan ejecutarse sin retrasos.</p>
<b>Escenario 1: Selección de ruta para asignar flota</b><br>
<b>Escenario 2: Asignación de equipo de transporte</b><br>
</td>
<td>3</td>
</tr>
  <tr>
    <td>33</td>
    <td>US30</td>
    <td>Adjuntar evidencia</td>
    <td><b>Como transportista</b>, quiero adjuntar fotos en incidencias,<br><p>para brindar pruebas claras.</p>
        <b>Escenario 1:</b> Foto como evidencia.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>34</td>
    <td>US32</td>
    <td>Etiquetado de incidencias por prioridad</td>
    <td><b>Como administrador</b>, quiero etiquetar incidencias por prioridad,<br><p>para gestionar lo urgente primero.</p>
        <b>Escenario 1:</b> Incidencia urgente destacada. <br>
        <b>Escenario 2:</b> Rechazo por mercadería dañada con evidencia.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>35</td>
    <td>US32</td>
    <td>Generación de reportes operativos</td>
    <td><b>Como administrador</b>, quiero reportes de entregas y exportación a Excel,<br><p>para evaluar desempeño.</p>
        <b>Escenario 1:</b> Reporte diario. <br>
        <b>Escenario 2:</b> Exportación a Excel.</td>
    <td>5</td>
  </tr>
  <tr>
    <td>36</td>
    <td>TS-IAM-001</td>
    <td>Register User</td>
    <td><b>Como usuario</b>, quiero registrarme en la plataforma,<br><p>para poder acceder a las funcionalidades de mi organización.</p>
        <b>Escenario 1:</b> Successful create - POST /api/v1/users valida email, password y crea usuario con 201 Created.<br>
        <b>Escenario 2:</b> Email already registered - responde 409 Conflict.<br>
        <b>Escenario 3:</b> Validation error - responde 400 Bad Request.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>37</td>
    <td>TS-IAM-002</td>
    <td>Sign In User</td>
    <td><b>Como usuario</b>, quiero iniciar sesión,<br><p>para obtener un token de acceso.</p>
        <b>Escenario 1:</b> Successful sign in - POST /api/v1/auth/sign-in responde 200 OK con tokens.<br>
        <b>Escenario 2:</b> Invalid credentials - responde 401 Unauthorized.</td>
    <td>2</td>
  </tr>
  <tr>
    <td>38</td>
    <td>TS-IAM-003</td>
    <td>Invite & Accept Organization Member</td>
    <td><b>Como owner</b>, quiero invitar usuarios a mi organización,<br><p>para que ellos puedan aceptar la invitación.</p>
        <b>Escenario 1:</b> Create invitation - POST crea invitation Pending con 201 Created.<br>
        <b>Escenario 2:</b> Accept invitation - POST acepta y crea membresía con 200 OK.<br>
        <b>Escenario 3:</b> Cancel invitation - POST cancela invitation con 200 OK.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>39</td>
    <td>TS-SUB-001</td>
    <td>Create Organization</td>
    <td><b>Como owner</b>, quiero registrar la organización,<br><p>para poder gestionar flota, clientes y rutas.</p>
        <b>Escenario 1:</b> Successful create - POST /api/v1/organizations crea organización con 201 Created.<br>
        <b>Escenario 2:</b> Duplicate RUC - responde 409 Conflict.<br>
        <b>Escenario 3:</b> Validation error - responde 400 Bad Request.</td>
    <td>2</td>
  </tr>
  <tr>
    <td>40</td>
    <td>TS-SUB-002</td>
    <td>Get Organization By Id</td>
    <td><b>Como usuario</b>, quiero obtener los datos de mi organización,<br><p>para mostrarlos en el panel de configuración.</p>
        <b>Escenario 1:</b> Organization found - GET responde 200 OK con OrganizationResource.<br>
        <b>Escenario 2:</b> Organization not found - responde 404 Not Found o 403 Forbidden.</td>
    <td>1</td>
  </tr>
  <tr>
    <td>41</td>
    <td>TS-FLE-001</td>
    <td>Register Vehicle</td>
    <td><b>Como owner/dispatcher</b>, quiero registrar vehículos,<br><p>para asociarlos a mi organización.</p>
        <b>Escenario 1:</b> Successful vehicle registration - POST crea Vehicle Disabled con 201 Created.<br>
        <b>Escenario 2:</b> Duplicate license plate - responde 409 Conflict.<br>
        <b>Escenario 3:</b> Validation error - responde 400 Bad Request.</td>
    <td>2</td>
  </tr>
  <tr>
    <td>42</td>
    <td>TS-FLE-002</td>
    <td>Update Vehicle Profile & Enable/Disable</td>
    <td><b>Como dispatcher</b>, quiero editar datos del vehículo,<br><p>para habilitarlo o deshabilitarlo.</p>
        <b>Escenario 1:</b> Update vehicle profile - PUT actualiza con 200 OK.<br>
        <b>Escenario 2:</b> Enable vehicle - POST /enable cambia estado a Enabled.<br>
        <b>Escenario 3:</b> Disable vehicle - POST /disable cambia estado a Disabled.</td>
    <td>2</td>
  </tr>
  <tr>
    <td>43</td>
    <td>TS-FLE-003</td>
    <td>Get Vehicles By Organization</td>
    <td><b>Como dispatcher</b>, quiero listar los vehículos de mi organización,<br><p>para filtrar por estado.</p>
        <b>Escenario 1:</b> Get all vehicles - GET responde 200 OK con collection.<br>
        <b>Escenario 2:</b> Get only enabled vehicles - GET con ?state=enabled filtra vehículos.<br>
        <b>Escenario 3:</b> Get vehicle by id - GET responde 200 OK o 404 Not Found.</td>
    <td>2</td>
  </tr>
  <tr>
    <td>44</td>
    <td>TS-CRM-001</td>
    <td>Register & Toggle Client</td>
    <td><b>Como dispatcher</b>, quiero registrar clientes (tiendas),<br><p>para poder habilitarlos o deshabilitarlos.</p>
        <b>Escenario 1:</b> Register client - POST crea Client isEnabled=true con 201 Created.<br>
        <b>Escenario 2:</b> Disable client - POST /disable cambia isEnabled a false.<br>
        <b>Escenario 3:</b> Enable client - POST /enable cambia isEnabled a true.</td>
    <td>2</td>
  </tr>
  <tr>
    <td>45</td>
    <td>TS-CRM-002</td>
    <td>Register & Toggle Location</td>
    <td><b>Como dispatcher</b>, quiero registrar puntos de entrega (locations),<br><p>para asociarlos a un cliente y poder habilitarlos o deshabilitarlos.</p>
        <b>Escenario 1:</b> Register location - POST crea Location isEnabled=true con 201 Created.<br>
        <b>Escenario 2:</b> Disable location - POST /disable cambia isEnabled a false.<br>
        <b>Escenario 3:</b> Enable location - POST /enable cambia isEnabled a true.</td>
    <td>2</td>
  </tr>
  <tr>
    <td>46</td>
    <td>TS-CRM-003</td>
    <td>Query Clients and Locations</td>
    <td><b>Como dispatcher</b>, quiero ver todos los clientes de mi organización,<br><p>para consultar sus locations.</p>
        <b>Escenario 1:</b> Get clients by organization - GET responde 200 OK con ClientResource collection.<br>
        <b>Escenario 2:</b> Get locations by client - GET responde 200 OK con LocationResource[].<br>
        <b>Escenario 3:</b> Get single location - GET responde 200 OK o 404 Not Found.</td>
    <td>2</td>
  </tr>
  <tr>
    <td>47</td>
    <td>TS-PLA-001</td>
    <td>Create Route Draft</td>
    <td><b>Como planner</b>, quiero crear un borrador de ruta para una fecha,<br><p>para utilizar un color de identificación.</p>
        <b>Escenario 1:</b> Successful draft creation - POST crea RouteDraft con 201 Created.<br>
        <b>Escenario 2:</b> Validation error - responde 400 Bad Request.</td>
    <td>2</td>
  </tr>
  <tr>
    <td>48</td>
    <td>TS-PLA-002</td>
    <td>Edit Route Draft (Locations, Vehicle, Team)</td>
    <td><b>Como planner</b>, quiero armar el borrador de ruta,<br><p>para añadir locations, vehículo y equipo.</p>
        <b>Escenario 1:</b> Add location - POST crea Delivery Pending con 200 OK.<br>
        <b>Escenario 2:</b> Assign vehicle - POST almacena vehicleId con 200 OK.<br>
        <b>Escenario 3:</b> Assign members - POST almacena team members con 200 OK.<br>
        <b>Escenario 4:</b> Save changes - persiste y GET refleja nuevo estado.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>49</td>
    <td>TS-PLA-003</td>
    <td>Publish Route</td>
    <td><b>Como planner</b>, quiero publicar un borrador de ruta,<br><p>para que pase a ejecución generando una snapshot estable.</p>
        <b>Escenario 1:</b> Successful publish - POST crea Route con snapshot y responde 201 Created.<br>
        <b>Escenario 2:</b> Publish with missing data - responde 400 Bad Request con validation errors.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>50</td>
    <td>TS-PLA-004</td>
    <td>Query Routes</td>
    <td><b>Como dispatcher/planner</b>, quiero consultar las rutas publicadas,<br><p>para ver su información completa.</p>
        <b>Escenario 1:</b> Get route by id - GET responde 200 OK con RouteResource completo.<br>
        <b>Escenario 2:</b> Get routes by organization and date - GET responde 200 OK con collection filtrada.</td>
    <td>2</td>
  </tr>
</table>

## 2.5. Strategic-Level Domain-Driven Design

### 2.5.1. EventStorming

<img src="assets/images/cap2/eventstorming-cap2.jpeg" alt="EventStorming">

#### 2.5.1.1. Candidate Context Discovery

Se aplicaron las tres estrategias indicadas en el enunciado para identificar los bounded contexts a partir del EventStorm de Rutana.

***Estrategia: Start-with-Value***

Se identificaron las partes del dominio con mayor valor para el negocio (core). El sistema tiene como propósito principal la planificación y ejecución de rutas de distribución, gestionando flota, clientes y ubicaciones asociadas.

| Módulo | Valor de Negocio | Tipo de Dominio |
|:----|:----|:----|
| Planning | Creación, publicación y ejecución de rutas — núcleo del sistema | Core Domain |
| Fleet | Registro y disponibilidad de vehículos para las rutas | Core Domain |
| CRM | Gestión de clientes y ubicaciones de entrega | Core Domain |
| Suscriptions | Habilita el acceso a la plataforma según plan contratado | Supporting Domain |
| IAM | Autenticación, organizaciones y gestión de sesiones | Generic Domain |



***Estrategia: Start-with-Simple***

Se descompuso el timeline del EventStorm en steps secuenciales para identificar modelos simples con propósito claro. Cada módulo tiene actores y flujos definidos, lo que permite establecer límites claros entre contextos.

| Contexto | Actores Involucrados | Flujo Principal |
|:----|:----|:----|
| IAM | Usuario, Administrador | Registrar cuenta → Iniciar sesión → Crear organización → Invitar usuario |
| Suscriptions | Administrador | Crear organización → Crear suscripción → Realizar pago → Suscripción activada |
| Fleet | Administrador, Despachador | Registrar vehículo → Habilitar vehículo → Actualizar estado operacional |
| CRM | Administrador, Despachador | Registrar cliente → Registrar ubicación → Actualizar posición de ubicación |
| Planning | Despachador | Crear borrador de ruta → Agregar ubicaciones → Asignar vehículo → Publicar ruta → Iniciar ruta → Completar ruta |


***3.3 Estrategia: Look-for-Pivotal-Events***

Se identificaron los eventos clave del negocio que indican cruces entre diferentes partes del proceso. Estos eventos actúan como fronteras naturales entre bounded contexts.

| Pivotal Event | Contexto Origen | Contexto Destino |
|:----|:----|:----|
| Organization Created | IAM | Suscriptions (creación de suscripción) |
| Subscription Activated | Suscriptions | CRM, Fleet, Planning (habilita uso de la plataforma) |
| Vehicle Registered | Fleet | Planning (Vehicle Assigned to Route) |
| Client Registered | CRM | Planning (asociación de ubicaciones a rutas) |
| Location Created | CRM | Planning (Location Added to Route) |
| Route Published | Planning | Fleet (Dispatcher/Vehicle Assigned) |
| Route Started | Planning | CRM (Location Completed en tiempo real) |


Con estas estrategias pudimos identificar los bounded contexts que obtuvimos en el Event Storming: **IAM**, **Suscriptions**, **Fleet**, **CRM** y **Planning**.

#### 2.5.1.2. Domain Message Flows Modeling

Para el desarrollo del Message Flow Modeling utilizamos la técnica de **Domain Storytelling**, un modelado colaborativo en el que los expertos de dominio narran su trabajo. El modelador escucha y registra estas historias usando un lenguaje pictográfico que combina: **Actores** (personas o sistemas de software) • **Objetos de trabajo** (documentos, datos, mensajes) • **Actividades** (flechas numeradas que indican el flujo secuencial) • **Anotaciones** (escenarios alternativos o condiciones de error).

Para cada flujo se identificaron: el actor iniciador, los bounded contexts involucrados, la secuencia de mensajes intercambiados y los escenarios alternativos.

<br>

***DS-01: Administrador registra su organización y activa una suscripción***

**Historia:** El administrador se registra en el sistema, crea una organización y contrata una suscripción. El sistema procesa el pago y activa el acceso a la plataforma.

**DS-01: Administrador registra su organización y activa una suscripción**
*Bounded Contexts: IAM · Suscriptions*

![DS-01 - Registro de organización y activación de suscripción](assets/images/readme/ds-01-registro-organizacion-suscripcion.png)

**Bounded Contexts Involucrados:**
1. IAM — registra al usuario y crea la organización
2. Suscriptions — gestiona el plan, el pago y la activación del acceso

**Flujo Principal:**

|#|Actor|Mensaje / Acción|Destino|Resultado|
|:--:|:----|:----|:----|:----|
|1|Administrador|Se registra en el sistema|IAM|Usuario registrado|
|2|Administrador|Crea una organización|IAM|Organización creada|
|3|IAM|Notifica creación al módulo de suscripciones|Suscriptions|Organización disponible para suscripción|
|4|Administrador|Crea una suscripción y realiza el pago|Suscriptions|Suscripción creada|
|5|Suscriptions|Procesa el pago mediante pasarela de pago|Suscriptions|Pago exitoso|
|6|Suscriptions|Activa la suscripción|Suscriptions|Suscripción activada|

**Escenarios Alternativos:**

|Escenario Alternativo|Respuesta del Sistema|
|:----|:----|
|Registro de usuario fallido|IAM rechaza el registro → Muestra error de validación|
|Pago rechazado|Suscriptions no activa la suscripción → Notifica error de pago|
|Suscripción vencida|Suscriptions marca la suscripción como expirada → Restringe acceso a módulos|

<br>

***DS-02: Despachador registra un cliente y su ubicación de entrega***

**Historia:** El despachador registra un nuevo cliente en el sistema y, a continuación, registra la ubicación asociada a ese cliente para futuras entregas.

**DS-02: Despachador registra un cliente y su ubicación**
*Bounded Contexts: CRM*

![DS-02 - Registro de cliente y ubicación](assets/images/readme/ds-02-registro-cliente-ubicacion.png)

**Bounded Contexts Involucrados:**
1. IAM — autentica al despachador
2. CRM — gestiona el registro del cliente y sus ubicaciones

**Flujo Principal:**

|#|Actor|Mensaje / Acción|Destino|Resultado|
|:--:|:----|:----|:----|:----|
|1|Despachador|Inicia sesión en el sistema|IAM|Sesión iniciada|
|2|Despachador|Registra un nuevo cliente|CRM|Cliente registrado|
|3|Despachador|Registra la ubicación del cliente|CRM|Ubicación creada|
|4|CRM|Consulta coordenadas mediante Google Maps API|Google Maps API|Ubicación geolocalizada|
|5|CRM|Habilita la ubicación para su uso en rutas|CRM|Ubicación habilitada|

**Escenarios Alternativos:**

|Escenario Alternativo|Respuesta del Sistema|
|:----|:----|
|Datos de cliente incompletos|CRM rechaza el registro → Muestra error de validación|
|Dirección no encontrada en Google Maps|CRM marca la creación de ubicación como fallida → Solicita corrección manual|
|Cliente desactivado previamente|CRM impide registrar nuevas ubicaciones para ese cliente|

<br>

***DS-03: Despachador planifica y publica una ruta con vehículo asignado***

**Historia:** El despachador crea un borrador de ruta, agrega las ubicaciones que debe visitar, asigna un vehículo disponible y publica la ruta para su ejecución.

**DS-03: Despachador planifica y publica una ruta**
*Bounded Contexts: Planning · Fleet · CRM*

![DS-03 - Planificación y publicación de ruta](assets/images/readme/ds-03-planificacion-publicacion-ruta.png)

**Bounded Contexts Involucrados:**
1. Planning — gestiona el borrador, las ubicaciones y la publicación de la ruta
2. CRM — provee las ubicaciones disponibles del cliente
3. Fleet — provee los vehículos disponibles para la asignación

**Flujo Principal:**

|#|Actor|Mensaje / Acción|Destino|Resultado|
|:--:|:----|:----|:----|:----|
|1|Despachador|Crea un borrador de ruta|Planning|Borrador de ruta creado|
|2|Despachador|Consulta ubicaciones registradas del cliente|CRM|Ubicaciones obtenidas|
|3|Despachador|Agrega ubicaciones al borrador de ruta|Planning|Ubicación agregada a la ruta|
|4|Despachador|Consulta vehículos disponibles|Fleet|Vehículos obtenidos|
|5|Despachador|Asigna un vehículo a la ruta|Planning|Vehículo asignado a la ruta|
|6|Despachador|Publica la ruta|Planning|Ruta publicada|

**Escenarios Alternativos:**

|Escenario Alternativo|Respuesta del Sistema|
|:----|:----|
|Vehículo no disponible|Planning notifica asignación fallida → Solicita elegir otro vehículo|
|Ubicación eliminada del borrador|Planning remueve la ubicación de la ruta y recalcula el recorrido|
|Publicación fallida por datos incompletos|Planning rechaza la publicación → Indica campos pendientes|

<br>

***DS-04: Conductor ejecuta la ruta y completa las entregas***

**Historia:** El despachador inicia la ejecución de la ruta publicada y el sistema va marcando cada ubicación como completada conforme se realizan las entregas, hasta finalizar la ruta.

**DS-04: Ejecución de ruta y completado de entregas**
*Bounded Contexts: Planning · CRM*

![DS-04 - Ejecución de ruta y completado de entregas](assets/images/readme/ds-04-ejecucion-ruta-entregas.png)

**Bounded Contexts Involucrados:**
1. Planning — gestiona el inicio, avance y finalización de la ruta
2. CRM — refleja el estado de las ubicaciones visitadas

**Flujo Principal:**

|#|Actor|Mensaje / Acción|Destino|Resultado|
|:--:|:----|:----|:----|:----|
|1|Despachador|Inicia la ruta publicada|Planning|Ruta iniciada|
|2|Planning|Marca la primera ubicación en tránsito|Planning|Ubicación en curso|
|3|Despachador|Confirma la entrega en la ubicación|Planning|Ubicación completada|
|4|Planning|Actualiza el estado de la ubicación en CRM|CRM|Estado de ubicación sincronizado|
|5|Planning|Repite el ciclo para cada ubicación de la ruta|Planning|Todas las ubicaciones procesadas|
|6|Planning|Finaliza la ruta|Planning|Ruta completada|

**Escenarios Alternativos:**

|Escenario Alternativo|Respuesta del Sistema|
|:----|:----|
|Cliente rechaza la entrega|Planning marca la ubicación como rechazada → Registra el motivo|
|Pérdida de conexión durante la ruta|Planning almacena los cambios localmente → Sincroniza al recuperar señal|
|Cancelación de ruta en curso|Planning marca la ruta como cancelada → Libera el vehículo asignado|

<br>

Con estas historias de dominio se evidencia cómo colaboran los bounded contexts **IAM**, **Suscriptions**, **CRM**, **Fleet** y **Planning** para resolver los principales casos de uso del negocio en Rutana.

#### 2.5.1.3. Bounded Context Canvases
### 2.5.2. Context Mapping
### 2.5.3. Software Architecture
#### 2.5.3.1. Software Architecture Context Level Diagrams
#### 2.5.3.2. Software Architecture Container Level Diagrams
#### 2.5.3.3. Software Architecture Deployment Diagrams

En esta sección se presenta el Deployment Diagram elaborado bajo el estándar C4. Este diagrama describe la distribución física del sistema y la topología de infraestructura sobre la cual se ejecutan los componentes de software.

![SA-Deployment-diagram.png](assets/images/cap2/SA-Deployment-diagram.png)


## 2.6. Tactical-Level Domain-Driven Design
### 2.6.1. Bounded Context: IAM

El bounded context **IAM (Identity & Access Management)** corresponde a un *Generic Domain* dentro de Rutana, encargado de la autenticación, la gestión de identidad de los usuarios y la administración de invitaciones a organizaciones. A continuación se detallan los términos clave de su lenguaje ubicuo:

| Término | Definición |
|:----|:----|
| **User** | Representa la identidad de un usuario dentro del sistema, incluyendo sus credenciales y su rol. |
| **Profile** | Contiene los datos personales asociados a un usuario (nombre, teléfono, avatar). |
| **Invitation** | Representa la invitación enviada a un correo electrónico para unirse a una organización con un rol asignado. |
| **Role** | Define el conjunto de permisos que posee un usuario dentro de una organización. |

<br>

#### 2.6.1.1. Domain Layer

En esta capa se modelan las clases de categoría como **Entities**, **Value Objects**, **Aggregates**, **Factories** y **Domain Services**, o abstracciones representadas por interfaces como en el caso de los **Repositories**.

- **Aggregate Root:** `User` — encapsula la identidad, credenciales y estado del usuario, y actúa como raíz de consistencia junto con `Profile`.
- **Entities:** `Profile`, `Invitation`.
- **Value Objects:** `Email`, `Role`.
- **Domain Services:** `AuthenticationService` — valida credenciales y aplica las políticas de autorización.
- **Factories:** `UserFactory` — encapsula la creación de un `User` válido a partir de datos de registro.
- **Repositories (interfaces):** `UserRepository`, `InvitationRepository`.

<br>

#### 2.6.1.2. Interface Layer

En esta sección se introduce y presenta las clases que forman parte de la Interface/Presentation Layer, como clases del tipo **Controllers** o **Consumers**.

- **Controllers:**
  - `AuthController` — expone los endpoints de inicio de sesión y registro.
  - `UserController` — expone las operaciones sobre el perfil del usuario.
  - `InvitationController` — expone las operaciones de invitación a una organización (crear, aceptar, cancelar).

<br>

#### 2.6.1.3. Application Layer

En esta sección se explica a través de qué clases se manejan los flujos de procesos del negocio. Debe evidenciarse las capabilities de la aplicación en relación al bounded context. Aquí deben considerarse clases del tipo **Command Handlers** e **Event Handlers**.

- **Command Handlers:**
  - `UserCommandService` — procesa el registro de usuarios y el cambio de rol.
  - `InvitationCommandService` — procesa la creación, aceptación y cancelación de invitaciones.
- **Query Handlers:**
  - `UserQueryService` — resuelve las consultas sobre usuarios.
  - `InvitationQueryService` — resuelve las consultas sobre invitaciones.
- **Event Handlers:**
  - `UserEventHandler` — reacciona a eventos de dominio (`UserRegistered`, `InvitationAccepted`) y coordina efectos secundarios hacia otros bounded contexts.

<br>

#### 2.6.1.4. Infrastructure Layer

En esta capa se presentan aquellas clases que acceden a servicios externos como *databases*, *messaging systems* o *email services*. Es en esta capa se ubica la implementación de los **Repositories** para las interfaces definidas en Domain Layer.

- `UserRepositoryImpl` — implementa `UserRepository` mediante JPA/Spring Data.
- `InvitationRepositoryImpl` — implementa `InvitationRepository` mediante JPA/Spring Data.
- `TokenProvider` — genera y valida los tokens JWT de sesión.
- `DomainEventPublisher` — publica los eventos de dominio hacia el message broker para que otros bounded contexts (como Suscriptions) puedan reaccionar a ellos.

<br>

#### 2.6.1.5. Bounded Context Software Architecture Component Level Diagrams

En esta sección se presenta el **Component Diagram** de C4 Model correspondiente al bounded context de IAM, reflejando la descomposición del Container en sus principales bloques estructurales (Interface, Application, Domain e Infrastructure Layer) y sus interacciones.

![Component_Diagram](assets/images/cap2/iam-component-diagram.png)

<br>


#### 2.6.1.6. Bounded Context Software Architecture Code Level Diagrams

En esta sección se presentan los diagramas que muestran un mayor detalle sobre la implementación de componentes en el bounded context de IAM, incluyendo el diagrama de clases del Domain Layer y el diagrama de base de datos.

<br>

##### 2.6.1.6.1. Bounded Context Domain Layer Class Diagrams

Se presenta el **Class Diagram** en UML de las clases del Domain Layer del bounded context de IAM, incluyendo atributos, métodos, su visibilidad (cuando corresponda) y la multiplicidad de las relaciones entre ellas.

![Class Diagram](assets/images/cap2/iam-domain-class-diagram.png)

<br>

##### 2.6.1.6.2. Bounded Context Database Design Diagram

Se presenta y explica el **Database Diagram** que incluye los objetos de base de datos del bounded context de IAM: tablas, columnas, constraints (primary key, foreign key) y las relaciones entre tablas.

![Database Diagram](assets/images/cap2/iam-database-diagram.png)


### 2.6.2. Bounded Context: Fleet

El bounded context **Fleet** corresponde a un *Core Domain* dentro de Rutana, encargado de la gestión integral de la flota de vehículos de las organizaciones de transporte, controlando su registro, disponibilidad, capacidad de carga y estado dentro del sistema. A continuación se detallan los términos clave de su lenguaje ubicuo:

| Término | Definición |
|:----|:----|
| **Vehicle** | Unidad de transporte registrada en la plataforma perteneciente a una organización específica. |
| **License Plate** | Identificador único alfanumérico legal de un vehículo. |
| **Vehicle Capacity** | Capacidad máxima de carga expresada en kilogramos (kg) que un vehículo puede transportar. |
| **Vehicle State** | Estado operativo del vehículo dentro de la flota (ej. Enabled, Disabled). |
| **Fleet Context Facade** | Capa Anti-Corrupción (ACL) que expone capacidades del contexto de flota a otros Bounded Contexts. |

<br>

#### 2.6.2.1. Domain Layer

En esta capa se modelan las clases de categoría como **Entities**, **Value Objects**, **Aggregates**, **Factories** y **Domain Services**, o abstracciones representadas por interfaces como en el caso de los **Repositories**.

- **Aggregate Root:** `Vehicle` — encapsula la identidad, placa, capacidad, estado operativo y pertenencia a una organización.
- **Entities:** (No aplica entidades secundarias adicionales dentro del agregado `Vehicle`).
- **Value Objects:** `LicensePlate`, `VehicleCapacity`, `VehicleState`.
- **Domain Services:** `VehicleService` — valida la disponibilidad del vehículo y aplica las reglas de negocio de la flota.
- **Factories:** `VehicleFactory` — encapsula la creación de una entidad `Vehicle` con su estado e identificadores iniciales válidos.
- **Repositories (interfaces):** `VehicleRepository`.

<br>

#### 2.6.2.2. Interface Layer

En esta sección se introduce y presenta las clases que forman parte de la Interface/Presentation Layer, como clases del tipo **Controllers** o **Consumers**.

- **Controllers:**
  - `VehicleController` — expone los endpoints de registro, consulta, actualización de perfil y modificación del estado del vehículo.

<br>

#### 2.6.2.3. Application Layer

En esta sección se explica a través de qué clases se manejan los flujos de procesos del negocio. Debe evidenciarse las capabilities de la aplicación en relación al bounded context. Aquí deben considerarse clases del tipo **Command Handlers** e **Event Handlers**.

- **Command Handlers:**
  - `VehicleCommandService` — procesa la creación, actualización de perfil y cambio de estado de los vehículos.
- **Query Handlers:**
  - `VehicleQueryService` — resuelve las consultas sobre vehículos por ID, por organización o por estado.
- **Event Handlers:**
  - `VehicleEventHandler` — reacciona a eventos de dominio (`VehicleRegistered`, `VehicleStateChanged`) y coordina efectos secundarios hacia otros bounded contexts (como Planning).

<br>

#### 2.6.2.4. Infrastructure Layer

En esta capa se presentan aquellas clases que acceden a servicios externos como *databases*, *messaging systems* o *email services*. Es en esta capa se ubica la implementación de los **Repositories** para las interfaces definidas en Domain Layer.

- `VehicleRepositoryImpl` — implementa `VehicleRepository` mediante la tecnología de persistencia de la aplicación.
- `FleetContextFacadeImpl` — implementa la fachada para exponer consultas e integraciones con otros bounded contexts.
- `DomainEventPublisher` — publica eventos de dominio relacionados con la flota hacia el message broker.

<br>


#### 2.6.2.5. Bounded Context Software Architecture Component Level Diagrams

En esta sección se presenta el **Component Diagram** de C4 Model correspondiente al bounded context de Fleet, reflejando la descomposición del Container en sus principales bloques estructurales (Interface, Application, Domain e Infrastructure Layer) y sus interacciones.

![Component_Diagram](assets/images/cap2/fleet-component-diagram.png)

<br>


#### 2.6.2.6. Bounded Context Software Architecture Code Level Diagrams

En esta sección se presentan los diagramas que muestran un mayor detalle sobre la implementación de componentes en el bounded context de Fleet, incluyendo el diagrama de clases del Domain Layer y el diagrama de base de datos.

<br>

##### 2.6.2.6.1. Bounded Context Domain Layer Class Diagrams

Se presenta el **Class Diagram** en UML de las clases del Domain Layer del bounded context de Fleet, incluyendo atributos, métodos, su visibilidad (cuando corresponda) y la multiplicidad de las relaciones entre ellas.

![Class Diagram](assets/images/cap2/fleet-domain-class-diagram.png)

<br>

##### 2.6.2.6.2. Bounded Context Database Design Diagram

Se presenta y explica el **Database Diagram** que incluye los objetos de base de datos del bounded context de Fleet: tablas, columnas, constraints (primary key, foreign key) y las relaciones entre tablas.

![Database Diagram](assets/images/cap2/fleet-database-diagram.png)

<br>

