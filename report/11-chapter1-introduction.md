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

#### 1.2.2.2. Lean UX Assumptions

#### 1.2.2.3. Lean UX Hypothesis Statements

#### 1.2.2.4. Lean UX Canvas

## 1.3. Segmentos Objetivo