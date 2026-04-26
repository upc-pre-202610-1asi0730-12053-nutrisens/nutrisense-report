# CAPÍTULO II: REQUIREMENTS ELICITATION & ANALYSIS

## 2.1. Competidores

El mercado de plataformas digitales de nutrición y bienestar personal presenta una oferta consolidada tanto a nivel global como regional, con actores que abordan el seguimiento nutricional desde distintos ángulos: cobertura de base de datos, integración con wearables o detalle micronutricional. Sin embargo, ninguno de los productos existentes combina recomendaciones contextuales en tiempo real con análisis visual personalizado de alimentos, que es precisamente el espacio que NutriSense busca ocupar. Tras un proceso de investigación del landscape competitivo, se identificaron tres competidores directos cuyas propuestas de valor se solapan parcial o totalmente con la de nuestra aplicación.

Fitia es una aplicación SaaS de nutrición de origen peruano con fuerte penetración en Latinoamérica. Su propuesta central es una base de datos de alimentos con amplia cobertura de productos y preparaciones locales (peruanas y latinoamericanas), lo que la posiciona favorablemente en la región. Ofrece registro calórico, seguimiento de macros y planes de alimentación básicos.

MyFitnessPal es la plataforma de seguimiento nutricional más usada a nivel mundial. Cuenta con una base de datos de más de 14 millones de alimentos, integración con wearables y aplicaciones de fitness, registro de ejercicios, y una comunidad activa. Su modelo freemium ofrece funciones básicas gratuitas y un plan premium de pago mensual y anual.

Cronometer es una plataforma SaaS orientada a usuarios con interés en la salud profunda y el detalle micronutricional. Su diferencial es el tracking exhaustivo de vitaminas, minerales y otros micronutrientes. Es favorecida por deportistas, personas con condiciones médicas específicas y usuarios que requieren control nutricional preciso.

### 2.1.1. Análisis competitivo

<table>
  <colgroup>
    <col width="10%"> <col width="10%"> <col width="20%"> <col width="20%"> <col width="20%"> <col width="20%"> </colgroup>
  
  <thead>
    <tr>
      <th colspan="6" style="text-align: left;"><b>Competitive Analysis Landscape</b></th>
    </tr>
    <tr>
      <th colspan="2">¿Por qué llevar a cabo este análisis?</th>
      <td colspan="4">
        ¿Qué ofrecen los principales competidores del mercado de nutrición digital y en qué aspectos NutriSense puede diferenciarse para capturar usuarios en el mercado latinoamericano?
        <br><br>
      </td>
    </tr>
    <tr>
      <th colspan="2"><i>Nombre y logo</i></th>
      <th style="text-align: center; vertical-align: top;">
        <img src="../assets/img/nutrisense-logo.png" width="120" alt="Logo Startup"><br><b>NutriSense</b>
      </th>
      <th style="text-align: center; vertical-align: top;">
        <img src="../assets/img/competitors/fitia.png" width="120" alt="Logo Fitia"><br><b>Fitia</b>
      </th>
      <th style="text-align: center; vertical-align: top;">
        <img src="../assets/img/competitors/myfitness.png" width="120" alt="Logo MyFitnessPal"><br><b>MyFitnessPal</b>
      </th>
      <th style="text-align: center; vertical-align: top;">
        <img src="../assets/img/competitors/cronometer.png" width="120" alt="Logo Cronometer"><br><b>Cronometer</b>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="2" style="vertical-align: middle; text-align: center;"><b>Perfil</b></td>
      <td>Overview</td>
      <td>Plataforma web SaaS de nutrición inteligente contextual. Combina seguimiento nutricional con recomendaciones personalizadas en tiempo real basadas en clima, ubicación geográfica y disponibilidad de ingredientes.</td>
      <td>Aplicación SaaS de nutrición de origen peruano con amplia base de datos de alimentos latinoamericanos. Fuerte presencia en Perú y países hispanohablantes. Enfocada en registro calórico y planes básicos de alimentación.</td>
      <td>Plataforma SaaS de seguimiento nutricional líder a nivel mundial. Cuenta con más de 14 millones de alimentos en su base de datos, integración con wearables y una comunidad global activa.</td>
      <td>Plataforma SaaS especializada en el tracking exhaustivo de micronutrientes (vitaminas, minerales, aminoácidos). Orientada a usuarios con necesidades nutricionales específicas y control de salud profundo.</td>
    </tr>
    <tr>
      <td>Ventaja competitiva / Valor</td>
      <td>Única plataforma que adapta las recomendaciones según el clima actual, la ubicación geográfica (Modo Viaje) y los ingredientes disponibles en casa. Análisis de menús de restaurante personalizado al perfil del usuario.</td>
      <td>Base de datos nutricional con fuerte cobertura de alimentos peruanos y latinoamericanos. Interfaz en español optimizada para el mercado local. Reconocimiento de marca consolidado en Perú.</td>
      <td>Base de datos masiva (más de 14 millones de alimentos), integración con más de 50 aplicaciones y wearables, y comunidad activa de usuarios. Posicionamiento global como estándar del sector.</td>
      <td>Tracking exhaustivo de más de 80 micronutrientes. Herramienta de referencia para deportistas, personas con condiciones médicas y profesionales de la salud que requieren precisión nutricional.</td>
    </tr>
    <tr>
      <td rowspan="2" style="vertical-align: middle; text-align: center;"><b>Perfil de Marketing</b></td>
      <td>Mercado objetivo</td>
      <td>Adultos de 18 a 60 años en Perú y Latinoamérica con metas físicas definidas (pérdida de peso o ganancia de masa muscular), que comen frecuentemente fuera de casa o viajan con regularidad y buscan recomendaciones nutricionales contextuales.</td>
      <td>Adultos hispanohablantes, principalmente peruanos y latinoamericanos, interesados en controlar su alimentación diaria. Perfil mayoritariamente femenino, rango de 20 a 45 años, con acceso a smartphone.</td>
      <td>Usuarios globales de 18 a 45 años interesados en perder peso, ganar músculo o mantener un estilo de vida saludable. Fuerte presencia en mercados anglófonos (EE.UU., Reino Unido, Australia) con crecimiento en Latinoamérica.</td>
      <td>Usuarios con necesidades nutricionales avanzadas: deportistas de alto rendimiento, personas con condiciones médicas (diabetes, enfermedad celíaca, insuficiencia renal) y profesionales de la salud. Rango de 25 a 50 años.</td>
    </tr>
    <tr>
      <td>Estrategias de marketing</td>
      <td>Marketing de contenido en redes sociales (Instagram, TikTok) dirigido a comunidades fitness y de alimentación saludable en Latinoamérica. Estrategia de referidos entre usuarios. Alianzas con nutricionistas y entrenadores personales como canales de distribución.</td>
      <td>Redes sociales con contenido en español orientado a hábitos saludables. Publicidad digital segmentada en Perú y Latinoamérica. Presencia en tiendas de aplicaciones (App Store y Google Play) como canal principal de adquisición.</td>
      <td>Campañas de publicidad digital masiva a nivel global. Partnerships con marcas de fitness y wearables (Fitbit, Garmin, Apple Health). Programa de referidos y comunidad de usuarios activa. Presencia en medios especializados en salud y bienestar.</td>
      <td>Marketing educativo orientado a comunidades de salud y bienestar avanzado. Presencia en foros especializados (Reddit, comunidades de deportistas). Recomendaciones de profesionales de la salud como canal orgánico principal.</td>
    </tr>
    <tr>
      <td rowspan="3" style="vertical-align: middle; text-align: center;"><b>Perfil de Producto</b></td>
      <td>Productos y servicios</td>
      <td>Plataforma web SaaS con registro nutricional, Smart Scan (análisis de fotos de platos y menús), motor de recomendaciones contextuales por clima y ubicación, Modo Viaje, módulo de despensa, sincronización con Google Fit, dashboard de progreso y exportación de reportes PDF.</td>
      <td>Aplicación móvil y web con registro de alimentos, base de datos nutricional latinoamericana, planes de alimentación básicos, seguimiento de macros y calorías, y versión premium con funciones adicionales.</td>
      <td>Aplicación móvil y web con registro de alimentos, escáner de código de barras, registro de ejercicio, integración con más de 50 aplicaciones y wearables, análisis de macros, recetas y comunidad de usuarios.</td>
      <td>Aplicación móvil y web con tracking exhaustivo de micronutrientes, registro de alimentos, análisis de composición corporal, diarios de salud y reportes detallados para profesionales.</td>
    </tr>
    <tr>
      <td>Precios y costos</td>
      <td>Tres planes de suscripción mensual sin modelo freemium: Basic ($7.99 — registro manual y dashboard), Pro ($14.99/mes — Smart Scan, clima, viaje, wearable, despensa), Premium ($ 19.90/mes — análisis de menú, PDF, historial ilimitado).</td>
      <td>Modelo freemium con plan gratuito limitado y plan premium de aproximadamente S/ 25–30/mes (varía por región). Las funciones avanzadas de planes y seguimiento detallado requieren suscripción paga.</td>
      <td>Modelo freemium con plan gratuito funcional y plan Premium de aproximadamente USD 19.99/mes o USD 79.99/año. El plan gratuito incluye el registro básico y la base de datos completa.</td>
      <td>Modelo freemium con plan gratuito completo en funciones básicas y plan Gold de USD 9.99/mes o USD 49.99/año. El plan gratuito ya incluye el tracking de micronutrientes, lo que reduce la fricción de conversión.</td>
    </tr>
    <tr>
      <td>Canales de distribución</td>
      <td>Plataforma web accesible desde cualquier navegador (desktop y móvil). Sin aplicación nativa en el alcance inicial. Distribución directa vía web y marketing digital.</td>
      <td>Aplicación móvil (iOS y Android) como canal principal. Versión web disponible pero con funcionalidad reducida respecto a la app móvil.</td>
      <td>Aplicación móvil (iOS y Android) y plataforma web completa. Integración como canal de distribución secundario a través de partnerships con wearables y otras aplicaciones de salud.</td>
      <td>Aplicación móvil (iOS y Android) y plataforma web. Distribución orgánica a través de recomendaciones de profesionales de la salud y comunidades especializadas.</td>
    </tr>
    <tr>
      <td rowspan="4" style="vertical-align: middle; text-align: center;"><b>Análisis SWOT</b></td>
      <td>Fortalezas</td>
      <td>Recomendaciones contextuales únicas (clima, ubicación, despensa). Diferenciación clara frente a competidores existentes. Plataforma web sin necesidad de instalación.</td>
      <td>Base de datos con amplia cobertura de alimentos peruanos y latinoamericanos. Marca reconocida en el mercado local. Interfaz completamente en español adaptada al contexto cultural latinoamericano.</td>
      <td>Base de datos más grande del sector (más de 14 millones de alimentos). Reconocimiento de marca global. Integraciones con prácticamente todos los wearables y aplicaciones de fitness del mercado.</td>
      <td>Tracking de micronutrientes más exhaustivo del mercado. Base de usuarios fiel y altamente comprometida. Precio competitivo con plan gratuito robusto que no limita las funciones core.</td>
    </tr>
    <tr>
      <td>Debilidades</td>
      <td>Marca nueva sin reconocimiento en el mercado. Dependencia de APIs de terceros para funciones core (Google Cloud Vision, OpenWeatherMap). Base de datos de alimentos inicial limitada comparada con competidores establecidos. Sin aplicación móvil nativa en el alcance inicial.</td>
      <td>Sin recomendaciones contextuales basadas en clima o ubicación. Sin análisis de fotos de platos o menús. Funcionalidades de wearable limitadas. Cobertura reducida fuera de Latinoamérica.</td>
      <td>Interfaz percibida como sobrecargada por muchos usuarios. Historial de problemas de privacidad y seguridad de datos (brecha de seguridad en 2018). Plan gratuito con publicidad intrusiva. Precio del plan premium elevado para el mercado latinoamericano.</td>
      <td>Curva de aprendizaje alta para usuarios sin conocimientos nutricionales avanzados. Interfaz menos intuitiva para el usuario casual. Sin recomendaciones contextuales ni análisis de imágenes. Comunidad significativamente más pequeña que MyFitnessPal.</td>
    </tr>
    <tr>
      <td>Oportunidades</td>
      <td>Creciente adopción de tecnología de salud en Latinoamérica. Demanda insatisfecha de herramientas nutricionales contextuales. Tendencia creciente de turismo interno en Perú (Modo Viaje). Alianzas potenciales con nutricionistas, gimnasios y cadenas de restaurantes.</td>
      <td>Expansión a otros mercados latinoamericanos con bases de datos locales. Incorporación de funciones de IA para personalización. Alianzas con supermercados y servicios de delivery locales.</td>
      <td>Expansión en mercados emergentes de Asia y Latinoamérica. Incorporación de funciones de IA generativa para recomendaciones. Alianzas con aseguradoras de salud como canal B2B.</td>
      <td>Crecimiento del segmento de salud preventiva y nutrición de precisión. Alianzas con clínicas, hospitales y profesionales de la salud. Expansión de funciones hacia gestión de enfermedades crónicas.</td>
    </tr>
    <tr>
      <td>Amenazas</td>
      <td>Competidores establecidos con mayor presupuesto que podrían replicar las funciones contextuales. Cambios en las políticas de uso o precios de las APIs de terceros. Baja disposición a pagar por aplicaciones de nutrición en el mercado peruano. Dependencia de la confianza del usuario para compartir datos de salud.</td>
      <td>Posible entrada de competidores globales con localización para el mercado latinoamericano. Usuarios que migran a plataformas con mayor integración tecnológica. Dificultad para competir en funciones avanzadas frente a plataformas con mayor inversión en I+D.</td>
      <td>Saturación del mercado de aplicaciones de nutrición. Regulaciones de privacidad más estrictas (GDPR, leyes locales de protección de datos). Nuevos entrantes con propuestas más innovadoras y precios más competitivos.</td>
      <td>Público objetivo de nicho con bajo potencial de crecimiento masivo. Competencia de plataformas médicas especializadas con mayor respaldo clínico. Dificultad para atraer usuarios casuales que representan el mayor volumen del mercado.</td>
    </tr>
  </tbody>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores

### 2.1.2. Estrategias y tácticas frente a competidores

El análisis competitivo revela que los actores establecidos tienen ventajas claras en escala de base de datos, reconocimiento de marca y presupuesto de marketing. Sin embargo, ninguno ha desarrollado recomendaciones contextuales en tiempo real basadas en clima, ubicación geográfica y disponibilidad de ingredientes, que constituye el espacio diferencial que la plataforma busca ocupar.

**Frente a Fitia: aprovechar su debilidad tecnológica**

La principal brecha de Fitia es la ausencia total de análisis visual y recomendaciones contextuales. El posicionamiento apunta a ser su evolución natural: pasar del simple registro calórico a la orientación activa en el momento exacto de la decisión alimentaria. Como táctica concreta, se desarrollará contenido en redes sociales que ilustre escenarios donde la plataforma resuelve problemas que Fitia no puede abordar, como elegir qué pedir en un restaurante desconocido estando de viaje. Paralelamente, se priorizará desde el inicio una cobertura sólida de alimentos peruanos y latinoamericanos para no ceder ese terreno regional.

**Frente a MyFitnessPal: competir en experiencia**

Igualar los 14 millones de alimentos o el reconocimiento global de MyFitnessPal no es viable ni estratégicamente necesario. La apuesta es ofrecer una experiencia más inteligente y menos sobrecargada. En términos tácticos, se enfatizará la sencillez del flujo de registro mediante Smart Scan frente al proceso de búsqueda manual, y se resaltará la política de privacidad transparente frente a los antecedentes públicos de esa plataforma en el tema. En lo económico, el diferencial es significativo para el mercado latinoamericano: el plan Pro cuesta USD 14.99/mes frente a los aproximadamente USD 19.99/mes del Premium de MyFitnessPal, con una propuesta de valor más contextualizada y un plan de entrada (Basic a USD 7.99/mes) que reduce la barrera de conversión inicial.

**Frente a Cronometer: ampliar el segmento objetivo**

Cronometer domina un nicho bien definido pero de volumen reducido. La estrategia no pasa por competir en tracking exhaustivo de micronutrientes, sino por capturar a usuarios que buscan resultados concretos con el menor esfuerzo posible, en contraposición al perfil de usuario de Cronometer, que disfruta del análisis nutricional detallado como fin en sí mismo. La accesibilidad de precios refuerza este posicionamiento: el plan Premium a USD 19.99/mes es comparable al Gold de Cronometer, pero incluye funciones contextuales que esa plataforma no ofrece. En el largo plazo, se evaluará incorporar seguimiento de micronutrientes seleccionados como función Premium para capturar también ese segmento sin comprometer la propuesta central.

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

Las entrevistas fueron diseñadas con preguntas diferenciadas según cada segmento objetivo, organizadas en bloques temáticos que permiten recopilar información sobre el perfil del usuario, sus hábitos actuales y la validación de las funcionalidades propuestas.

##### Segmento 1 — Pérdida de Peso (Adultos de 25 a 60 años)

**Bloque 1: Perfil y biografía**

1. ¿Cuál es su nombre, edad y a qué se dedica?
2. ¿Cómo describiría su rutina diaria en cuanto a movimiento físico? ¿Diría que es una persona que pasa mucho tiempo sentada, o que se mueve bastante durante el día?

**Bloque 2: Control calórico y conocimiento nutricional**

3. ¿Tiene alguna meta física actualmente, como bajar de peso o mejorar su alimentación? ¿Qué es lo que más le cuesta lograr?
4. Cuando come fuera de casa, en un restaurante, en la calle o en el trabajo, ¿sabe con certeza cuánto está comiendo en términos de calorías, o simplemente calcula una cifra aproximada?

**Bloque 3: Validación de funciones**

5. Si una aplicación pudiera analizar la foto de su plato o del menú de un restaurante y decirle automáticamente qué tan saludable es esa comida para usted, ¿la usaría? ¿Por qué?
6. ¿Le parecería útil que la aplicación le sugiera qué comer según el clima del día, por ejemplo, algo más ligero cuando hace mucho calor, o algo más sustancioso cuando hace frío?

##### Segmento 2 — Ganancia de Masa Muscular (Jóvenes de 18 a 32 años)

**Bloque 1: Perfil y biografía**

1. ¿Cuál es tu nombre, edad y a qué te dedicas?
2. ¿Con qué frecuencia entrenas a la semana y hace cuánto tiempo llevas haciéndolo?
3. ¿Qué dispositivos usas normalmente? ¿Tienes smartwatch, reloj deportivo o algún accesorio que te mida los pasos o el ejercicio?

**Bloque 2: Macros, adaptabilidad y contexto**

4. ¿Llevas algún control de lo que comes, especialmente de cuánta proteína consumes al día? ¿Qué es lo que más te incomoda de las aplicaciones que has probado para registrar tu comida?
5. Cuando viajas o tu rutina cambia por algún motivo, trabajo, viaje, eventos, ¿cómo afecta eso tu alimentación y tu entrenamiento?

**Bloque 3: Validación de funciones**

6. Si estuvieras de viaje en una ciudad que no conoces y una aplicación te sugiriera automáticamente platos típicos de esa zona que encajan con tu dieta, ¿lo usarías? ¿Qué te parecería eso?
7. Si tu reloj o tu celular midiera automáticamente cuánto te moviste en el día y la aplicación ajustara sola cuánto deberías comer ese día según eso, ¿qué valor le darías a esa función?

### 2.2.2. Registro de entrevistas

| Segmento: Pérdida de peso | Entrevista #1 |
| --- | --- |
| Nombres y Apellidos |Evelyn Diaz|
| Edad |54|
| Distrito |Loreto - Iquitos|
| Ocupación |Docente universitaria de idiomas|
| Timming inicio |0:06 - 3:46|
| Duración |3:41 minutos|
| URL | [Video entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202411669_upc_edu_pe/IQCphaql_3BGSYUeamvL9k2rAe99Zhj1kZ-homZdjyFdwFc?e=0yLaa4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifSwicGxheWJhY2tPcHRpb25zIjp7InN0YXJ0VGltZUluU2Vjb25kcyI6MS4yNX19)|
| Screenshot |![Entrevista 1 Seg1](../assets/img/interviews/Entrevista1-seg1.png)|
| Resumen |Evelyn describe su rutina diaria como permanentemente activa debido a su labor docente, la cual le exige estar en constante movimiento entre clases y actividades con sus alumnos. Su motivación para buscar un mejor control alimenticio nace de preocupaciones de salud, específicamente por el aumento de peso relacionado con la edad y niveles elevados de azúcar, por lo cual cuenta actualmente con asesoría de un nutricionista. Al comer fuera de casa, no conoce el valor calórico exacto, pero aplica una estrategia de control basada en evitar la repetición de carbohidratos y equilibrar las proteínas y verduras. Ella califica como una "idea magnífica" la posibilidad de usar una aplicación que analice sus platos mediante fotografías, ya que le permitiría contar con una herramienta de apoyo precisa para el control riguroso de su ingesta diaria. Asimismo, aprueba totalmente la función de sugerencias según el clima como un complemento útil para su alimentación.|

<div style="page-break-after: always"></div>

| Segmento: Pérdida de peso | Entrevista #2 |
| --- | --- |
| Nombres y Apellidos |Jorge Del Aguila|
| Edad |49|
| Distrito |Loreto - Iquitos|
| Ocupación |Administrador de empresas y jefe de garantías y taller|
| Timming inicio |3:47 - 8:04|
| Duración |4:18 minutos |
| URL |[Video entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202411669_upc_edu_pe/IQCphaql_3BGSYUeamvL9k2rAe99Zhj1kZ-homZdjyFdwFc?e=J5a59A&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifSwicGxheWJhY2tPcHRpb25zIjp7InN0YXJ0VGltZUluU2Vjb25kcyI6MjI3LjMyfX0%3D)|
| Screenshot |![Entrevista 2 Seg1](../assets/img/interviews/Entrevista2-seg1.png)|
| Resumen |Jorge es un profesional cuya jornada laboral transcurre mayoritariamente en una oficina, permaneciendo sentado aproximadamente el 90% de su tiempo, mientras que el resto lo dedica a la coordinación en taller. A pesar de este sedentarismo laboral, mantiene una rutina de ejercicio nocturno de lunes a viernes con el objetivo de combatir su sobrepeso actual mediante un déficit calórico. En cuanto a su alimentación, suele consumir menús diarios calculando las porciones de manera visual o "al ojo", sin tener certeza sobre el valor calórico real de sus platos. Se muestra muy interesado en utilizar una herramienta tecnológica que analice su metabolismo y las fotos de su comida, asegurando que, de ser efectiva, la recomendaría a su círculo cercano. Respecto a las sugerencias por clima, aunque vive en una zona predominantemente cálida, considera que podrían ser útiles en momentos específicos de lluvia para elegir alimentos como café o sándwiches.|

<div style="page-break-after: always"></div>

| Segmento: Pérdida de peso | Entrevista #3 |
| --- | --- |
| Nombres y Apellidos |Larisa Ramírez|
| Edad |25|
| Distrito |San Miguel |
| Ocupación |Estudiante de Administración y Marketing|
| Timming inicio |8:05 - 11:59|
| Duración |3:53 minutos|
| URL |[Video entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202411669_upc_edu_pe/IQCphaql_3BGSYUeamvL9k2rAe99Zhj1kZ-homZdjyFdwFc?e=azeyo7&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifSwicGxheWJhY2tPcHRpb25zIjp7InN0YXJ0VGltZUluU2Vjb25kcyI6NDg2LjI1fX0%3D)|
| Screenshot |![Entrevista 3 Seg1](../assets/img/interviews/Entrevista3-seg1.png)|
| Resumen |Larisa mantiene una rutina mayoritariamente sedentaria debido a sus estudios universitarios, aunque intenta realizar pausas activas y camina diariamente hacia el transporte público. Su principal desafío para perder peso y mejorar su alimentación es un diagnóstico médico de Síndrome de Ovario Poliquístico (SOP), lo cual dificulta la pérdida de peso y le genera constantes antojos de alimentos poco saludables. Al igual que los otros entrevistados, suele medir sus porciones de forma estimada cuando come en restaurantes, pero carece de información calórica real. Ella utilizaría la aplicación propuesta para mantener la disciplina en su alimentación, especialmente cuando sale a comer fuera. Además, destaca que la función de sugerencias por clima sería muy innovadora, mencionando que durante el invierno suele sentir más hambre y deseos de consumir dulces, por lo que una guía adecuada le ayudaría a evitar alimentos que no son saludables.|

<div style="page-break-after: always"></div>

| Segmento: Ganancia de Masa Muscular | Entrevista #1 |
| --- | --- |
| Nombres y Apellidos |David Miguel Ramos Parihuamán|
| Edad |19|
| Distrito |Surco|
| Ocupación |Estudiante universitario|
| Timming inicio |12:13 - 16:00|
| Duración |3:47 minutos|
| URL |[Video entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202411669_upc_edu_pe/IQCphaql_3BGSYUeamvL9k2rAe99Zhj1kZ-homZdjyFdwFc?e=uQgfK8&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifSwicGxheWJhY2tPcHRpb25zIjp7InN0YXJ0VGltZUluU2Vjb25kcyI6NzIwLjEyfX0%3D)|
| Screenshot |![Entrevista 1 Seg2](../assets/img/interviews/2_1.png)|
| Resumen |David es un estudiante universitario que entrena en el gimnasio de dos a tres veces por semana con el objetivo de aumentar su masa muscular, proceso que inició hace aproximadamente dos meses. Su mayor dificultad para mantener la constancia radica en los viajes y en las alteraciones de su rutina debidas a responsabilidades académicas y laborales, lo que le complica identificar alimentos locales adecuados y mantener su ritmo de entrenamiento fuera de su entorno habitual. Actualmente monitorea sus pasos con un smartwatch y sigue una dieta basada en las recomendaciones de sus instructores para controlar calorías y proteínas. David ve en la aplicación propuesta una solución para reducir la carga mental durante sus viajes, valorando especialmente las sugerencias de platos típicos adaptados a su dieta y el ajuste automático de porciones según su actividad física, lo cual le permitiría regular su alimentación con precisión incluso cuando sus estudios le impiden asistir al gimnasio.|

<div style="page-break-after: always"></div>

| Segmento: Ganancia de Masa Muscular | Entrevista #2 |
| --- | --- |
| Nombres y Apellidos |Rando López|
| Edad |22|
| Distrito |San Borja|
| Ocupación |Estudiante universitario|
| Timming inicio |16:01 - 19:06|
| Duración |3:05 minutos|
| URL |[Video entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202411669_upc_edu_pe/IQCphaql_3BGSYUeamvL9k2rAe99Zhj1kZ-homZdjyFdwFc?e=t4cPdX&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifSwicGxheWJhY2tPcHRpb25zIjp7InN0YXJ0VGltZUluU2Vjb25kcyI6OTYyLjExfX0%3D)|
| Screenshot |![Entrevista 2 Seg2](../assets/img/interviews/2_2.png)|
| Resumen |Rando es un joven universitario que entrena cuatro veces por semana con el enfoque de ganar masa muscular. Su principal desafío es la gestión del tiempo, ya que sus deberes académicos suelen interferir con su capacidad para asistir al gimnasio y ajustar su ingesta calórica diaria. Aunque ya utiliza tecnología como un smartwatch para medir pasos y pulsaciones, y lleva un control manual de sus proteínas, manifiesta que las aplicaciones de nutrición convencionales le resultan confusas o poco atractivas. Considera que la aplicación propuesta sería de gran valor para mantener su disciplina, destacando la importancia de contar con sugerencias de gastronomía local que encajen con su dieta al viajar. Asimismo, resalta como una herramienta fundamental la automatización en el ajuste de porciones basada en la actividad física registrada por sus dispositivos, lo que facilitaría significativamente el seguimiento de su régimen alimenticio.|

<div style="page-break-after: always"></div>

| Segmento: Ganancia de Masa Muscular | Entrevista #3 |
| --- | --- |
| Nombres y Apellidos | Daphne Faustor |
| Edad | 25 |
| Distrito | Callao |
| Ocupación | Marketing y publicidad |
| Timming inicio |19:07 - 22:58|
| Duración | 3:52 minutos |
| URL |[Video entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202411669_upc_edu_pe/IQCphaql_3BGSYUeamvL9k2rAe99Zhj1kZ-homZdjyFdwFc?e=Vamnsc&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifSwicGxheWJhY2tPcHRpb25zIjp7InN0YXJ0VGltZUluU2Vjb25kcyI6MTE0My41Mn19)|
| Screenshot | ![Entrevista3 Seg2](../assets/img/interviews/Entrevista1-seg2.png) |
| Resumen | Daphne Faustor, profesional de 25 años en el área de Marketing y Publicidad, nos comenta que mantiene un estilo de vida activo entrenando fuerza y cardio de 5 a 6 veces por semana para aumentar su masa muscular. Usa su Apple Watch todo el día para monitorear sus pasos y entrenamientos de cardio. Aunque antes seguía dietas estrictas, hoy rechaza el pesaje manual de alimentos porque le resulta estresante y le quita tiempo en su rutina de estudio y trabajo. Prefiere guiarse por referencias visuales, como "puñados". Cuando viaja le encanta probar la comida local, pero siente la frustración de que las opciones baratas suelan ser comida chatarra. Por esta razón, le entusiasma la idea de una plataforma automatizada que use los datos de su smartwatch para sugerirle platos locales que encajen con su dieta, permitiéndole disfrutar de sus viajes y cuidar su nutrición sin complicaciones. |

<div style="page-break-after: always"></div>

### 2.2.3. Análisis de entrevistas

#### Segmento 1: Personas que buscan perder peso

**Características objetivas**

Los tres entrevistados de este segmento (100%) comparten una situación de base: quieren perder peso o mejorar su salud, pero desconocen los valores nutricionales reales de los platos que consumen fuera de casa. En cuanto a diversidad geográfica, el 67% (2/3) reside en Loreto - Iquitos (Evelyn, 54 años; Jorge, 49 años) y el 33% (1/3) en Lima - San Miguel (Larisa, 25 años). Respecto a la ocupación, el 67% (2/3) desempeña actividades de tipo sedentario o semisedentario: Jorge permanece sentado aproximadamente el 90% de su jornada laboral en oficina, y Larisa desarrolla la mayor parte de su día en modalidad de estudio universitario. El 33% restante (1/3), Evelyn, desempeña una labor docente que implica movimiento constante entre clases y actividades.

Respecto a condiciones de salud, el 100% presenta alguna condición médica o física que motiva su búsqueda de un control alimenticio más riguroso. Las razones varían según la edad: el 67% (2/3) corresponde a personas mayores de 40 años que enfrentan problemas como niveles elevados de azúcar y aumento de peso relacionado con la edad (Evelyn) o sobrepeso derivado del sedentarismo laboral (Jorge). El 33% (1/3) restante pertenece al grupo joven adulto: Larisa, de 25 años, tiene diagnóstico de Síndrome de Ovario Poliquístico — SOP, condición que dificulta la pérdida de peso y le genera constantes antojos de alimentos poco saludables.

**Características subjetivas**

En cuanto al control alimenticio fuera de casa, el 100% (3/3) reconoce no contar con información calórica real sobre los platos que consume en restaurantes o en el trabajo. El 67% (2/3) aplica estrategias de estimación visual para compensar esta falta de información: Evelyn evita la repetición de carbohidratos y equilibra proteínas y verduras, mientras que Jorge calcula porciones "al ojo". El 33% (1/3) restante, Larisa, no aplica ninguna estrategia activa de control fuera de casa, lo que agrava su situación dado su diagnóstico.

Respecto a la disposición tecnológica, el 100% (3/3) mostró una muy buena aceptación hacia el uso de la cámara del celular para analizar sus platos fotográficamente, sin necesidad de escribir listas ni buscar alimentos manualmente. Evelyn calificó la idea como "magnífica" y destacó que le permitiría un control riguroso de su ingesta diaria; Jorge afirmó que, de ser efectiva, la recomendaría a su círculo cercano; y Larisa indicó que la usaría principalmente para mantener la disciplina cuando sale a comer fuera. Esto deja claro que la facilidad de uso es uno de los factores más importantes para que una herramienta así sea adoptada en la vida real.

En cuanto a la función de sugerencias por clima, el 100% (3/3) valoró positivamente esta característica, reconociendo que las condiciones ambientales influyen directamente en sus decisiones alimentarias. Larisa la considera "muy innovadora" y menciona que en invierno siente más hambre y deseos de consumir dulces; Jorge, que vive en una zona predominantemente cálida, la considera útil en momentos de lluvia para elegir opciones como café o sándwiches; y Evelyn la aprueba como complemento útil para su alimentación diaria.

En términos de motivación y acompañamiento, el 67% (2/3) ya cuenta con alguna forma de apoyo externo: Evelyn tiene asesoría de un nutricionista, y Larisa sigue recomendaciones médicas derivadas de su diagnóstico de SOP. El 33% (1/3), Jorge, actúa de forma autónoma complementando su jornada laboral sedentaria con una rutina de ejercicio nocturno de lunes a viernes.

**Conclusión**

En conclusión, este grupo no busca simplemente contar calorías, sino una solución integral que se adapte a sus distintos estilos de vida, ya sea una rutina de oficina, trabajo docente u horarios irregulares. Quieren entender mejor lo que comen, recibir orientación sobre la composición de sus platos y sentir un acompañamiento constante que los motive sin complicarles el día a día. Su disposición a adoptar la herramienta es alta, especialmente cuando perciben que esta fue diseñada pensando en sus condiciones reales y no en un usuario ideal.

#### Segmento 2: Personas que quieren ganar masa muscular

**Características objetivas**

Los tres entrevistados de este segmento (100%) residen en Lima: David (19 años, Surco), Rando (22 años, San Borja) y Daphne (25 años, Callao). A diferencia del primer grupo, estas personas no buscan adelgazar sino optimizar su alimentación para rendir mejor físicamente y ganar músculo. En cuanto a ocupación, el 67% (2/3) son estudiantes universitarios (David y Rando), mientras que el 33% (1/3) es profesional activo en Marketing y Publicidad (Daphne). Respecto a la frecuencia de entrenamiento, el 33% (1/3) entrena de 2 a 3 veces por semana (David), el 33% (1/3) entrena 4 veces por semana (Rando), y el 33% (1/3) entrena de 5 a 6 veces por semana (Daphne).

El 100% (3/3) ya utiliza dispositivos wearable para registrar su actividad física: David y Rando usan smartwatch para monitorear pasos y pulsaciones, y Daphne usa su Apple Watch de forma continua durante el día, lo que indica que están familiarizados con la tecnología aplicada a la salud y tienen altas expectativas sobre lo que una aplicación puede hacer por ellos.

**Características subjetivas**

Respecto al principal obstáculo para mantener su régimen, el 100% (3/3) coincide en que el tiempo es su mayor limitante, aunque con orígenes distintos: el 67% (2/3) identifica las responsabilidades académicas como el factor principal que interrumpe constantemente su planificación alimentaria y sus rutinas de entrenamiento (David y Rando), mientras que el 33% (1/3) señala la carga combinada de trabajo y estudio como la causa de esta dificultad (Daphne). Su principal obstáculo no es la falta de motivación, sino la imposibilidad de mantener la consistencia que sus metas exigen.

En cuanto a la percepción de las aplicaciones de nutrición existentes, el 67% (2/3) las describe como confusas o poco prácticas porque obligan a registrar todo manualmente, generando más estrés del que resuelven (Rando y Daphne). En particular, Daphne rechaza activamente el pesaje de alimentos por considerarlo estresante y que le resta tiempo, optando actualmente por referencias visuales como "puñados". David no reporta uso previo de aplicaciones de nutrición, pero sigue las recomendaciones de sus instructores de gimnasio para controlar calorías y proteínas.

Respecto a la automatización de porciones y macronutrientes según actividad física, el 100% (3/3) valoró esta función como la más importante de la propuesta. David la identifica como la solución para regular su alimentación cuando sus estudios le impiden asistir al gimnasio; Rando la destaca como herramienta clave para mantener la disciplina sin carga mental adicional; y Daphne la considera muy útil para agilizar su seguimiento nutricional entre estudios y trabajo. Lo que realmente valoran es la automatización: quieren que la app detecte cuánto se movieron durante el día y ajuste sola las porciones necesarias, sin que tengan que estar pendientes de cada detalle.

Finalmente, el 100% (3/3) mencionó de forma espontánea que los viajes representan una interrupción significativa en su progreso físico, ya que al salir de su entorno habitual no conocen la gastronomía local ni saben si los platos disponibles son compatibles con sus objetivos. David señala que los viajes le dificultan identificar alimentos locales adecuados; Rando destaca la importancia de contar con sugerencias de gastronomía local compatibles con su dieta; y Daphne expresa frustración porque al viajar, las opciones económicas suelen ser comida chatarra. Por eso, los tres valoran especialmente una función que sugiera platos típicos del lugar donde se encuentran, adaptados a sus metas nutricionales.

**Conclusión**

En conclusión, este grupo no busca simplemente registrar lo que come, sino una solución inteligente que se adapte a sus distintos ritmos de vida. Quieren optimizar su alimentación sin que eso represente una carga adicional, recibir ajustes automáticos según su actividad física y contar con orientación nutricional incluso cuando están fuera de su entorno habitual. Su disposición a adoptar la herramienta es alta, especialmente cuando perciben que esta se integra con la tecnología que ya usan y fue pensada para acompañarlos tanto en su gimnasio como en cualquier lugar del mundo.

## 2.3. Needfinding

### 2.3.1. User Personas

### 2.3.2. User Task Matrix

### 2.3.3. User Journey Mapping

### 2.3.4. Empathy Mapping

## 2.4. Big Picture EventStorming

## 2.5. Ubiquitous Language