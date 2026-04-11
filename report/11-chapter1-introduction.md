# CAPÍTULO I: INTRODUCCIÓN

## 1.1. Startup Profile

### 1.1.1. Descripción del Startup

NutriSense es una startup tecnológica enfocada en transformar la manera en que las personas gestionan su alimentación y alcanzan sus metas físicas. Nacimos para resolver uno de los retos más comunes en la vida cotidiana, tales como la dificultad de mantener una alimentación saludable y coherente con los objetivos personales en un entorno dinámico, donde los hábitos cambian según el clima, la ubicación y la disponibilidad de alimentos. Competimos en un mercado donde las soluciones existentes ofrecen un seguimiento genérico sin considerar el contexto real del usuario, y nos diferenciamos al integrar recomendaciones verdaderamente personalizadas basadas en datos ambientales, geográficos y del perfil individual de cada persona.
<br>Nuestra misión es empoderar a las personas para que tomen decisiones alimentarias más inteligentes mediante una plataforma web que combina el seguimiento nutricional, el análisis visual de alimentos y recomendaciones contextuales adaptadas al clima, la ubicación y los hábitos de cada usuario, contribuyendo así a una vida más saludable y sostenible.
<br>Nuestra visión es convertirnos en la plataforma de nutrición inteligente de referencia en América Latina, reconocida por ofrecer la experiencia más personalizada y contextual del mercado, capaz de acompañar a cada persona en su camino hacia sus metas físicas sin importar dónde se encuentre ni las circunstancias de su entorno.

### 1.1.2. Perfiles de integrantes del equipo

## 1.1. Solution Profile

| Integrantes | Descripción |
| :--- | :--- |
| | |
| | |
| | |
| ![Rose](../assets/img/chapter1/vergaray.png) | **Nombres y Apellidos:** Rose Almendra Vergaray Calderon<br> **Código:** U20241D159<br> **Carrera:** Ingeniería de Software<br> Soy una persona responsable, creativa y detallista, cualidades que me impulsan a dar lo mejor de mí en cada proyecto. Cuento con conocimientos en Python, HTML, Java y un nivel intermedio en C++, además de experiencia en el diseño y programación de páginas web y en el manejo de bases de datos relacionales y no relacionales. Me motiva el aprendizaje constante, la exploración de nuevas herramientas y el desarrollo de soluciones innovadoras. Además, considero que el trabajo en equipo y la comunicación son esenciales para alcanzar metas y crecer tanto en lo personal como en lo profesional. |
| ![Angel](../assets/img/chapter1/villarreal.png) |**Nombres y Apellidos:** Angel Martin Villarreal Bazan<br> **Código:** U202417857<br> **Carrera:** Ingeniería de Software<br>Soy una persona proactiva y dedicada, enfocada en la mejora continua y el cumplimiento de objetivos. Cuento con sólidos conocimientos en C++ y Java, además de una fuerte base en lógica de programación para resolver problemas complejos. Me motiva el aprendizaje constante de nuevas tecnologías y el desafío de proyectos innovadores. Gracias a mi capacidad de organización y liderazgo, logro optimizar procesos y fomentar un entorno de trabajo colaborativo y eficiente.|

### 1.2.1. Antecedentes y problemática
Aplicamos 5Ws y 2Hs, utilizado para examinar los antecedentes y la problemática que aborda nuestro proyecto.

| 5W / 2H | Pregunta | Descripcion|
| :--- | :--- | :--- |
|Who?|¿Quién es afectado?|Los principales afectados son dos grupos bien definidos. El primero son adultos que buscan perder peso sin seguir dietas rígidas, que comen frecuentemente fuera de casa y no tienen claridad sobre el valor nutricional real de lo que consumen. El segundo son jóvenes que practican ejercicio con regularidad y necesitan un control preciso de sus macronutrientes, especialmente proteínas, pero que ven interrumpida su disciplina nutricional cuando viajan o cuando su rutina cambia. De forma indirecta, también se ven involucrados profesionales de la salud que podrían recomendar la plataforma a sus pacientes.|
|What?|¿Cuál es el problema?|El problema central es la dificultad que enfrentan las personas para mantener un control nutricional efectivo y personalizado en su vida diaria. Las aplicaciones de nutrición actuales ofrecen un registro genérico de calorías y macros, pero no consideran el contexto real del usuario: el clima del día, el país o ciudad donde se encuentra, los ingredientes que tiene disponibles en casa, ni las restricciones médicas o alimentarias específicas de cada persona. Esto genera que el usuario registre lo que come, pero no reciba orientación útil sobre qué debería comer según su situación particular. Nuestra solución busca cerrar esa brecha ofreciendo recomendaciones verdaderamente contextuales y personalizadas para quienes quieren perder peso o ganar masa muscular.|
|When?|¿Cuándo sucede el problema?|Esto ocurre de forma cotidiana, especialmente en los momentos de decisión alimentaria: al elegir qué comer en un restaurante, al planificar las comidas del día, al viajar a una ciudad desconocida o al notar que el clima ha cambiado los hábitos de alimentación. El usuario recurre a la aplicación antes y durante las comidas, así como al final del día para revisar su progreso y planificar el día siguiente.|
|Where?|¿Dónde sucede el problema?|Surge en cualquier entorno donde el usuario deba tomar una decisión alimentaria sin información adecuada: en restaurantes, en la calle, en el trabajo, en casa o de viaje. La solución se accede desde cualquier dispositivo con navegador web, lo que permite acompañar al usuario en todos estos contextos sin necesidad de instalar nada adicional.|
|Why?|¿Cuál es la causa del problema?|La causa raíz del problema es la ausencia de herramientas que integren el contexto del usuario en las recomendaciones nutricionales. Las aplicaciones existentes como Fitia, MyFitnessPal o Cronometer permiten registrar alimentos, pero sus sugerencias no cambian según el clima, la ubicación geográfica ni los ingredientes disponibles en el hogar del usuario. Esto hace que la experiencia sea útil para el registro, pero limitada para la orientación real.|
|How?|¿Qué llevó a la persona a esta situación?|La implementación de NutriSense responde a la necesidad de simplificar la gestión nutricional mediante una plataforma SaaS que automatiza la toma de decisiones del usuario. El sistema procesa variables contextuales como el clima, la ubicación y la disponibilidad de ingredientes en el hogar, además de integrar el módulo Smart Scan para el reconocimiento de alimentos mediante visión artificial. Este modelo funcional se basa en la premisa de que la personalización extrema y la reducción del esfuerzo manual en el registro de datos son los factores determinantes para el éxito y la costumbre a largo plazo en programas de salud digital (Carmina et al., 2019).|
|How much?|¿Cuál es la cantidad, duración o intensidad del evento?|La magnitud del problema sanitario en el entorno local es crítica, ya que el sobrepeso y la obesidad alcanzan al 60.9% de los adultos en el Perú (Alsahli et al., 2023). Esta condición no es un evento aislado, sino una situación persistente que incrementa exponencialmente la probabilidad de padecer enfermedades crónicas no transmisibles, como la hipertensión y la diabetes tipo 2. La intensidad de esta problemática evidencia que la mayor parte de la población urbana enfrenta barreras estructurales para mantener hábitos saludables, lo que genera una carga epidemiológica que requiere soluciones tecnológicas de intervención inmediata (Lopez & Serrano, 2023). Por otro lado, la intensidad de la demanda en el sector digital refleja una oportunidad de mercado sólida y en crecimiento constante. Existe una disposición real por parte de los usuarios peruanos para adoptar y pagar por aplicaciones de salud que ofrezcan propuestas de valor diferenciadas y personalizadas. Este interés del consumidor post-pandemia indica que el mercado no solo busca herramientas de monitoreo, sino soluciones integrales bajo modelos de suscripción que garanticen una mejora tangible en la gestión de su bienestar personal (Alsahli et al., 2023).|

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

**Problem Statement 1**

NutriSense offers a web platform that helps people achieve their physical goals through personalized nutritional tracking and smart food recommendations adapted to their profile, dietary restrictions, and daily context.

We have observed that adults between 25 and 60 years old who want to lose weight struggle to maintain consistent caloric control, especially when eating outside the home. Existing apps provide generic calorie counters but fail to account for real-life variables such as the weather, the city they are in, or the specific dishes available at a restaurant, leaving users without actionable guidance at the moment they need it most.

How might we help users make informed food decisions in any context — whether at a restaurant, traveling, or at home — without requiring significant effort or nutritional expertise from them?

**Problem Statement 2**

NutriSense offers a smart food scanning module that analyzes photos of dishes and restaurant menus to provide instant nutritional estimates and personalized recommendations aligned with the user's active goal and dietary restrictions.

We have observed that users frequently eat outside the home or order from restaurants, and estimating the caloric content of those meals is either impossible or inaccurate using current manual search methods. This causes the nutritional log to be incomplete or unreliable, reducing the user's ability to track progress effectively.

How might we allow users to instantly capture and log the nutritional value of any meal they encounter — in any restaurant or food context — with minimal manual effort and high contextual relevance?

**Problem Statement 3**

NutriSense offers a recommendations engine that adapts food suggestions based on the user's current location, the local weather, and the ingredients available in their pantry at home.

We have observed that young adults between 18 and 32 years old who train regularly find it difficult to maintain their nutritional discipline when they travel to unfamiliar cities or when climate changes affect their eating habits. Generic apps do not adjust recommendations to these contextual variables, leading to poor macro tracking and inconsistent progress toward muscle gain goals.

How might we provide users with relevant and locally-adapted food suggestions that keep them on track with their nutritional goals regardless of where they are or what environmental conditions they face?

**Problem Statement 4**

NutriSense offers a subscription-based model with three differentiated tiers designed to serve users at different levels of commitment and nutritional sophistication.

We have observed that the majority of nutrition apps in the Latin American market rely on freemium models that limit engagement and reduce the perceived value of their premium features, resulting in low conversion rates and high churn. Users are willing to pay for features that demonstrably improve their outcomes, but only when those features solve specific, recurring problems they experience in their daily lives.

How might we design a subscription structure that clearly communicates the value of each tier and converts Basic users into Pro and Premium subscribers by delivering features that solve real contextual problems they encounter every day?


#### 1.2.2.2. Lean UX Assumptions

**Who is the user?**

Our primary users are two clearly defined segments. The first segment consists of adults between 25 and 60 years old who want to lose weight without following rigid diets. They eat frequently outside the home, have a sedentary or moderately active lifestyle, and feel frustrated by their inability to know exactly what they are consuming in terms of calories and macros. The second segment consists of young adults between 18 and 32 years old who exercise regularly and need precise macro tracking to support muscle gain goals. They are disciplined in their training but lose nutritional consistency when they travel or when their routine changes.

**Where does our product fit in their work or life?**

For the first segment, NutriSense fits into the daily moments of food decision-making: choosing what to eat at a restaurant, planning meals at home, or evaluating whether a dish aligns with their weekly goals. For the second segment, the product fits into their pre- and post-workout nutrition planning, macro tracking throughout the day, and adaptation of their diet when traveling or facing changes in their usual environment.

**What problems does our product have and how can they be resolved?**

We have identified several potential limitations. The accuracy of the Smart Scan module depends on the quality of the photo provided and the precision of cloud vision, which may produce imprecise estimates for mixed or visually complex dishes. This can be mitigated by allowing users to confirm or adjust the result before saving it to their log. Another limitation is user trust in AI-generated recommendations, which may be low initially. This can be addressed by displaying the reasoning behind each recommendation clearly and allowing users to override suggestions easily. Additionally, the weather-based and travel-based recommendations rely on third-party APIs, which introduces a dependency on external service availability.

**When and how is our product used?**

The product is used multiple times throughout the day: before meals to plan food choices, during meals to scan dishes or consult recommendations, and at the end of the day to review progress on the dashboard. It is accessed through a web browser on any device without requiring app installation. The experience is designed to be fast and low-friction, requiring minimal input from the user once the initial profile is configured.

**What features are important?**

The most important features are the Smart Scan module for photo-based food analysis, the contextual recommendations engine that adapts suggestions based on weather and location, the pantry module that generates recipe suggestions based on ingredients available at home, the body tracking module with automatic IMC, TMB, and TDEE calculation, and the wearable sync integration that adjusts daily caloric goals based on actual physical activity.

**How should our product look and behave?**

NutriSense should have a clean, modern interface built on Material Design principles, with clear visual hierarchy that makes nutritional data easy to read at a glance. It should behave responsively across all screen sizes, load quickly, and minimize the number of steps required to complete any core action such as logging a meal or accessing a recommendation. The tone of communication should be supportive and motivating, not clinical or technical, so that users of all backgrounds feel comfortable using it.

**Assumptions list:**

a) We believe our users need a way to make smart food decisions in real-time, especially when eating outside the home, without requiring nutritional expertise.<br><br>b) These needs can be solved with NutriSense's contextual recommendation engine and Smart Scan module, which remove the need for manual calorie estimation.<br><br>c) Our initial customers are adults between 18 and 60 years old living in urban areas of Peru who have an active interest in improving their physical condition.<br><br>d) The greatest value a customer wants from our service is to receive food recommendations that are actually relevant to their current situation — their location, the weather, and what they have available.<br><br>e) Customers can also obtain additional benefits such as consistent macro tracking, better body composition progress visibility, and reduced effort in daily nutritional planning.<br><br>f) We will acquire most of our customers through social media content (Instagram, TikTok) targeting fitness and healthy lifestyle communities, and through word-of-mouth from early users who achieve visible results.<br><br>g) We will generate revenue through a three-tier subscription model: Basic, Pro, and Premium, with no permanent free tier.<br><br>h) Our primary competition in the market will be Fitia, MyFitnessPal, and Cronometer, all of which offer nutritional tracking without contextual recommendations.<br><br>i) We will outperform them because none of our competitors combine weather-based recommendations, travel mode, restaurant menu analysis, and pantry-based recipe suggestions in a single web platform.<br><br>j) Our greatest product risks are low initial user trust in AI-generated food recommendations, dependency on third-party API availability, and the challenge of building a sufficiently large and locally relevant food database for the Latin American market.<br><br>k) We will resolve these risks through transparent recommendation explanations, fallback manual entry options for all automated features, and prioritized integration with Open Food Facts, which already contains a large catalog of Latin American food products.

**Business Outcomes:**

- We will know our solution is working when at least 40% of registered users log at least one meal per day for three consecutive weeks.
- We will know our solution is working when the Smart Scan module is used in at least 30% of all meal log entries among Pro and Premium subscribers.
- We will know our solution is working when the monthly conversion rate from Basic to Pro reaches at least 15% within the first six months after launch.
- We will know our solution is working when user-reported satisfaction with the relevance of food recommendations averages 4 out of 5 or higher in post-session surveys.
- We will know our solution is working when at least 60% of active users enable the travel mode or weather-based recommendations during their first month of use.

**User Outcomes & Benefits:**

Adults seeking weight loss want to feel in control of their food choices without the stress of counting every calorie manually. What motivates them to seek our solution is the desire to make smarter decisions at restaurants and in their daily routine without needing to become nutrition experts. They will know they have achieved their goal when they can confidently choose what to eat in any context and see consistent progress on their body metrics over time.<br>Young adults seeking muscle gain want to maintain their macro discipline even when their routine changes due to travel, social events, or weather. What motivates them is the frustration of losing progress during periods when their usual food environment is not available. They will know they have achieved their goal when they can stay on track with their protein and caloric targets regardless of where they are or what is available to eat.

**Features:**

- **Smart Scan:** photo analysis of dishes and restaurant menus using Google Cloud Vision API to provide instant nutritional estimates and personalized recommendations.
- **Contextual Recommendations Engine:** food suggestions adapted in real time to the user's current weather (OpenWeatherMap API), geographic location, and active dietary restrictions.
- **Travel Mode:** detection of the user's current city or country to suggest healthy local dishes compatible with their nutritional profile.
- **Pantry Module:** ingredient registration at home with recipe and meal combination suggestions based on the user's daily macro deficit.
- **Body Tracking:** periodic weight and height logging with automatic calculation of BMI, BMR, and TDEE, and a dynamically adjusted daily caloric goal.
- **Wearable Sync:** integration with Google Fit to import daily steps and active calories burned, automatically adjusting the day's caloric balance.
- **Dashboard & Analytics:** weekly progress view with weight trend charts, daily calorie bar graphs, macro donut chart, and consecutive-day streak tracking.
- **Three-tier Subscription:** Basic (manual tracking and dashboard), Pro (Smart Scan, Travel Mode, weather recommendations, Wearable Sync, Pantry), Premium (restaurant menu analysis, unlimited history, PDF report export).

#### 1.2.2.3. Lean UX Hypothesis Statements

**Hypothesis Statement 1**

We believe that daily nutritional consistency among adults seeking weight loss will increase if they use NutriSense's contextual recommendation engine, which adapts food suggestions to their current weather and location.<br>We will know our solution is working when at least 50% of users in this segment log all three main meals on at least 5 out of 7 days during their second month of use.

**Hypothesis Statement 2**

We believe that the accuracy and completeness of nutritional logs will improve significantly if users adopt the Smart Scan module to register meals eaten outside the home instead of relying on manual food search.<br>We will know our solution is working when the average number of logged meals per day among Pro and Premium users increases by at least 35% compared to their first week of use, within the first 30 days after activating the feature.

**Hypothesis Statement 3**

We believe that young adults seeking muscle gain will maintain their macro tracking discipline during travel periods if they use the Travel Mode feature, which suggests healthy local dishes compatible with their active nutritional profile. <br>We will know our solution is working when the drop in daily log completion rate during trips reported by this segment decreases by at least 40% compared to their pre-NutriSense baseline, as reported in validation interviews.

**Hypothesis Statement 4**

We believe that the conversion rate from Basic to Pro subscriptions will increase if users clearly experience the value of at least one Pro feature during their first two weeks on the platform. <br>We will know our solution is working when the Basic-to-Pro monthly conversion rate reaches 15% or higher within the first six months after public launch.



#### 1.2.2.4. Lean UX Canvas

| # | Section | Content |
|---|---------|-----------|
| 1 | **Business Problem** | Nutrition apps available in the Latin American market offer generic caloric and macro tracking without adapting recommendations to the user's real-life context. Users who want to lose weight or gain muscle mass struggle to maintain consistent nutritional habits when eating outside the home, traveling, or facing changes in their routine. NutriSense needs to differentiate itself in a competitive market by solving this contextual gap and building a subscription model that sustains long-term growth. |
| 2 | **Business Outcomes** | • 40% of registered users log at least one meal per day for three consecutive weeks. <br> • Smart Scan is used in at least 30% of all meal log entries among Pro and Premium users. <br> • Basic-to-Pro monthly conversion rate reaches 15% within the first six months. <br> • Average recommendation satisfaction score of 4/5 or higher. <br> • 60% of active users enable Travel Mode or weather-based recommendations in their first month. |
| 3 | **Users** | **Segment 1:** Adults 25–60 years old, sedentary or moderately active, seeking weight loss without rigid diets. Eat frequently outside the home. Frustrated by the inability to estimate real caloric intake. <br> **Segment 2:** Young adults 18–32 years old, train regularly, seeking muscle gain. Need precise macro tracking. Lose nutritional discipline when traveling or when routine changes. |
| 4 | **User Outcomes & Benefits** | **Segment 1:** Feel in control of food choices in any context without needing nutritional expertise. See consistent body metric progress over time. <br> **Segment 2:** Maintain macro discipline during travel or routine disruptions. Stay on track with protein and caloric targets regardless of food environment. |
| 5 | **Solutions** | Smart Scan module, Contextual Recommendations Engine, Travel Mode, Pantry Module, Wearable Sync, Three-tier subscription (Basic, Pro, Premium). |
| 6 | **Hypotheses** | • Nutritional consistency will increase if weight-loss users receive weather and location-adapted recommendations.<br> • Log completeness will improve if users adopt Smart Scan for out-of-home meals. <br>• Muscle-gain users will maintain macro tracking during travel if Travel Mode provides locally-adapted suggestions. <br>• Basic-to-Pro conversion will increase if users experience at least one Pro feature value within their first two weeks. |
| 7 | **Most Important Thing to Learn** | Whether users actually trust and act on AI-generated food recommendations at the moment of decision, specifically when eating at a restaurant. If users do not find the Smart Scan and menu recommendations accurate or useful enough to influence their food choices, the core value proposition of NutriSense collapses. |
| 8 | **Least Amount of Work to Learn** | Conduct moderated usability sessions with 5 users per segment using a clickable prototype of the Smart Scan flow and the restaurant menu recommendation screen with sample photos. Measure whether they would act on the recommendation, rate perceived accuracy and usefulness on a 1–5 scale, and collect qualitative feedback on what would need to change for them to trust the feature consistently. |

## 1.3. Segmentos Objetivo

### Segmento Objetivo 1: Personas que buscan perder peso

Nuestro primer segmento objetivo son adultos que tienen como meta la pérdida de peso y la mejora de sus hábitos alimentarios. Se trata de personas que buscan controlar su ingesta calórica de manera progresiva y sostenible, sin seguir planes dietéticos rígidos, y que necesitan orientación práctica en su vida cotidiana, especialmente cuando comen fuera de casa o se encuentran en entornos alimentarios poco familiares.

**Aspectos demográficos:**
- Sexo: Masculino y femenino
- Edades: 25 – 60 años
- Nivel socioeconómico: B y C (medio y medio-alto)

**Aspectos geográficos:**
- Nacionalidad: Peruana
  - Zona geográfica: Urbana
- Departamentos: Lima

**Aspectos psicográficos:**
- Valores: bienestar personal, salud preventiva, equilibrio entre vida social y hábitos saludables
- Estilos de vida: personas con rutinas laborales exigentes, que comen con frecuencia fuera de casa y disponen de tiempo limitado para planificar sus comidas
- Intereses: salud, bienestar, alimentación consciente, seguimiento de progreso físico
- Personalidad: motivados pero con dificultad para mantener la constancia; buscan soluciones prácticas que se adapten a su ritmo de vida sin requerir conocimientos nutricionales avanzados
- Frustraciones: no saber cuántas calorías consumen realmente al comer fuera, no recibir orientación relevante según su contexto, y sentir que las apps actuales son útiles para registrar pero no para decidir

### Segmento Objetivo 2: Personas que buscan ganar masa muscular

Nuestro segundo segmento objetivo son jóvenes adultos que practican ejercicio de forma regular y tienen como meta la ganancia de masa muscular. Su principal necesidad es el control preciso de macronutrientes, especialmente proteínas, y mantener su disciplina nutricional incluso cuando su entorno cambia por viajes, eventos sociales o variaciones climáticas.

**Aspectos demográficos:**
- Sexo: Masculino y femenino
- Edades: 18 – 32 años
- Nivel socioeconómico: B y C (medio y medio-alto)

**Aspectos geográficos:**
- Nacionalidad: Peruana
- Zona geográfica: Urbana
- Departamentos: Lima

**Aspectos psicográficos:**
- Valores: disciplina, rendimiento físico, constancia, superación personal
- Estilos de vida: activos, con rutinas de entrenamiento establecidas de 3 a 6 días por semana; usan habitualmente dispositivos tecnológicos como smartphones y smartwatches
- Intereses: fitness, nutrición deportiva, seguimiento de métricas corporales, tecnología aplicada al rendimiento
- Personalidad: metódicos y orientados a resultados; frustrados cuando su progreso se ve interrumpido por factores externos que no pueden controlar
- Frustraciones: perder el control de sus macros cuando viajan o cuando su rutina cambia, la dificultad de registrar comidas complejas en apps actuales, y la falta de sugerencias adaptadas a su contexto geográfico o climático