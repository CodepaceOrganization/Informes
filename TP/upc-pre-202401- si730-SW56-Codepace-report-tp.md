<div align="center">

# Universidad Peruana de Ciencias Aplicadas
### INFORME DEL TRABAJO 1 (TB1)
![image](https://github.com/TripTeamOrganization/Informes/assets/134337719/c8a24a74-515a-436b-b7b9-ea1b2e418e60)

**Curso:** Aplicaciones Web

**Sección:** SW56

**Profesor:** Efraín Ricardo Bautista Ubillús

**Carrera:** Ingeniería de Software

**Ciclo:** 2024-01

**Startup:** CodePace

**Producto:** GetWork

### Integrantes:

| Nombre                            | Código       |
|-----------------------------------|--------------|
| Adriano Sebastian Cruz Palomino| u202210697   |
| Sebastian Nicolas Cachis Gonzales | u202210846 |
| Jeremy Joel Quispe Andia         | u202216279   |
| Andrea Milagros Cabanillas Gora    | u202211711   |
| Elias Yauri Paucar     | u202211817   |
| Alexander Jair Castillo Castillo     | u202211390   |



### Marzo del 2024
</div>

<div align="justify">

### Registro de versiones del informe

| Versión   | Fecha       | Autor      | Descripción                                                                                      | 
|-----------|-------------|------------|--------------------------------------------------------------------------------------------------|
| 1.0       |  2024/03/22| Quispe Andia, Jeremy Joel | Creación del documento de trabajo en formato markdown. |
| 1.1       |  2024/03/22    | Quispe Andia, Jeremy Joel  |Redacción del startup profile y solution profile, delimitación de segmentos objetivo, redacción de preguntas para el diseño de entrevistas |
| 1.2       |  2024/03/22    | Cabanillas Gora, Andrea Milagros |Elaboración y registro de entrevistas a segmentos objetivo, análisis de entrevistas    |
| 1.3       |  2024/03/22    | Cabanillas Gora, Andrea Milagros|Elaboración de user personas, impact mapping, as-is y to-be |
| 1.4       |  2024/03/22    | Castillo Castillo, Alexander Jair |Elaboración de user stories, product backlog |
| 1.5       |  2024/03/22    | Quispe Andia, Jeremy Joel |Elaboración de prototipos de wireframes y mockups  |
| 1.6       |  2024/03/22    | Yauri Paucar, Elias|Redacción de style guidelines e information architecture|
| 1.7       |  2024/03/22    | Cruz Palomino, Adriano Sebastian|Elaboración de diagrama de base de datos,diagrama de clases, diccionario de clases|
| 1.7       |  2024/03/22    |Quispe Andia, Jeremy Joel|Elaboración de diagramas de contenedores, diagramas de contexto, diagramas de componentes |
| 1.8       |  2024/03/22    | Quispe Andia, Jeremy Joel |Registro de evidencias del Sprint 1 |
| 1.9       |  2024/03/22    | Yauri Paucar, Elias |Rediseño de mockups. Elaboración de wireflows y user-flows|
| 2.0       |  2024/03/22    | Quispe Andia, Jeremy Joel| Redacción de conclusiones, biblografía y anexos|
| 2.1       |  2024/03/22    | Cachis Gonzales, Sebastian Nicolas | Redacción de Collaboration Insights|

### Project Report Collaboration Insights

**TB1**
Para el desarrollo del informe perteneciente a la entrega TB1, se dividió la implementación de secciones de la siguiente forma
para cada integrante del equipo:

| Integrante                            | Tareas Designadas       |
|-----------------------------------|--------------|
| Adriano Sebastian Cruz Palomino| Creación de la base de la Landing, Capítulo V, Modelado de Base de Datos   |
| Sebastian Nicolas Cachis Gonzales | Capitulo V, Diagrama Clases, Landing Page|
| Jeremy Joel Quispe Andia         | Capitulo I, Implementar Form De Registro, Crear la plantilla en markdown, elaborar conclusiones y anexos, corregir CAPITULO II, III, IV y V |
| Andrea Milagros Cabanillas Gora    | Capitulo II, Creaación del canva, implementar los planes en la Landing Page   |
| Elias Yauri Paucar     | Capitulo IV, implementar form registro  |
| Alexander Jair Castillo Castillo     | Capítulo III, implementar form contacto |

Evidencias del Insights Contributos de los commits del informe:

![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/f9afac6a-1133-4364-af91-3df3351cf313)

### Tabla de contenidos
- [Capítulo I: Introducción](#cap%C3%ADtulo-i-introducci%C3%B3n)
  
  - 1.1. Startup Profile
  
  - 1.1.1. Descripción de la Startup
  
  - 1.1.2. Perfiles de integrantes del equipo
  
  - 1.2. Solution Profile
  
  - 1.2.1 Antecedentes y problemática
  
  - 1.2.2 Lean UX Process.
  
  - 1.2.2.1. Lean UX Problem Statements.
  
  - 1.2.2.2. Lean UX Assumptions.
  
  - 1.2.2.3. Lean UX Hypothesis Statements.
  
  - 1.2.2.4. Lean UX Canvas.
  
  - 1.3. Segmentos objetivo.

- [Capítulo II: Requirements Elicitation & Analysis](#cap%C3%ADtulo-ii-requirements-elicitation--analysis)

  - 2.1. Competidores.
  
  - 2.1.1. Análisis competitivo.
  
  - 2.1.2. Estrategias y tácticas frente a competidores.
  
  - 2.2. Entrevistas.
  
  - 2.2.1. Diseño de entrevistas.
  
  - 2.2.2. Registro de entrevistas.
  
  - 2.2.3. Análisis de entrevistas.
  
  - 2.3. Needfinding.
  
  - 2.3.1. User Personas.
  
  - 2.3.2. User Task Matrix.
  
  - 2.3.3. User Journey Mapping.
  
  - 2.3.4. Empathy Mapping.
  
  - 2.3.5. As-is Scenario Mapping.
  
  - 2.4. Ubiquitous Language.
  
- [Capítulo III: Requirements Specification](#cap%C3%ADtulo-iii-requirements-specification)

  - 3.1. To-Be Scenario Mapping.
  
  - 3.2. User Stories.
  
  - 3.3. Impact Mapping.
  
  - 3.4. Product Backlog.
  
- [Capítulo IV: Product Design](#cap%C3%ADtulo-iv-product-design)

  - 4.1. Style Guidelines.
  
  - 4.1.1. General Style Guidelines.
  
  - 4.1.2. Web Style Guidelines.
  
  - 4.2. Information Architecture.
  
  - 4.2.1. Organization Systems.
  
  - 4.2.2. Labeling Systems.
  
  - 4.2.3. SEO Tags and Meta Tags.
  
  - 4.2.4. Searching Systems.
  
  - 4.2.5. Navigation Systems.
  
  - 4.3. Landing Page UI Design.
  
  - 4.3.1. Landing Page Wireframe.
  
  - 4.3.2. Landing Page Mock-up.
  
  - 4.4. Web Applications UX/UI Design.
  
  - 4.4.1. Web Applications Wireframes.
  
  - 4.4.2. Web Applications Wireflow Diagrams.
  
  - 4.4.2. Web Applications Mock-ups.
  
  - 4.4.3. Web Applications User Flow Diagrams.
  
  - 4.5. Web Applications Prototyping.
  
  - 4.6. Domain-Driven Software Architecture.
  
  - 4.6.1. Software Architecture Context Diagram.
  
  - 4.6.2. Software Architecture Container Diagrams.
  
  - 4.6.3. Software Architecture Components Diagrams.
  
  - 4.7. Software Object-Oriented Design.
  
  - 4.7.1. Class Diagrams.
  
  - 4.7.2. Class Dictionary.
  
  - 4.8. Database Design.
  
  - 4.8.1. Database Diagram.
  
- [Capítulo V: Product Implementation, Validation & Deployment](#cap%C3%ADtulo-v-product-implementation-validation--deployment)

  - 5.1. Software Configuration Management.
  
  - 5.1.1. Software Development Environment Configuration.
  
  - 5.1.2. Source Code Management.
  
  - 5.1.3. Source Code Style Guide & Conventions.
  
  - 5.1.4. Software Deployment Configuration.
  
  - 5.2. Landing Page, Services & Applications Implementation.
  
  - 5.2.1. Sprint 1
  
  - 5.2.1.1. Sprint Planning 1.
  
  - 5.2.1.2. Sprint Backlog 1.
  
  - 5.2.1.3. Development Evidence for Sprint Review.
  
  - 5.2.1.4. Testing Suite Evidence for Sprint Review.
  
  - 5.2.1.5. Execution Evidence for Sprint Review.
  
  - 5.2.1.6. Services Documentation Evidence for Sprint Review.
  
  - 5.2.1.7. Software Deployment Evidence for Sprint Review.
  
  - 5.2.1.8. Team Collaboration Insights during Sprint.
  
  - 5.2.2. Sprint 2
  - 5.2.2.1.Sprint Planning 2.
  - 5.2.2.2.Sprint Backlog 2.
  - 5.2.2.3.Development Evidence for Sprint Review.
  - 5.2.2.4.Testing Suite Evidence for Sprint Review.
  - 5.2.2.5.Execution Evidence for Sprint Review.
  - 5.2.2.6.Services Documentation Evidence for Sprint Review.
  - 5.2.2.7.Software Deployment Evidence for Sprint Review.
  - 5.2.2.8.Team Collaboration Insights during Sprint.    
  - Avance de Conclusiones, Bibliografía y Anexos.

### Studen Outcome

| Criterio específico | Acciones Realizadas | Conclusiones |
|---------------------|----------------------|--------------|
|Participa en equipos multidisciplinarios con eficacia, eficiencia y objetividad, en el marco de un proyecto en soluciones de ingeniería de software.|<br><br>Sebastian Nicolas Cachis Gonzales<br><b>TB1</b><br>Me mantuve activo en la participación y comunicación oral en las llamadas grupales, dando ideas de mejora y ayuda tanto para el informe como para la Landing Page.<br><br>Jeremy Joel Quispe Andia<br><b>TB1</b><br>Participe en las llamadas grupales de cada semana pidiendo opiniones y nuevas ideas de implementación para la Landing Page. Además, realicé entrevistas a los usuarios para conocer sus opiniones y recomendaciones acerca del proyecto.<br><br>Alexander Jair Castillo Castillo<br><b>TB1</b><br>Estuve presente en las llamadas grupales y comunicaba mis dudas e ideas al grupo sobre los puntos que me tocaba realizar, como las entrevistas, donde me encargue de resumir las respuestas de los usuarios entrevistados.<br><br>Elias Yauri Paucar<br><b>TB1</b><br>Comuniqué mi idea de proyecto mediante la primera llamada grupal, la cual quedó como finalista y me encargue de especificar cada punto de la idea a todos los integrantes.<br><br>Ancrea Cabanillas<br><b>TB1</b><br>Me encargue de hacer todo las entrevistas  , seleccionar los segmentos y analizar la respuesta de nuestros entrevistados, luego hice los user persona, el impact map basados en personajes ficticios que podrían usar la app, por último hice el as_is con las diferentes posibles fases.|<b>TB1</b><br> Como conclusión para esta primera entrega del proyecto, hemos confirmado que la comunicación oral grupal desde el inicio del proyecto es fundamental para un buen inicio de trabajo. No solo nos ha permitido conocernos entre nosotros, sino que también ha servido como plataforma para expresar nuestras ideas, dudas y consultas de manera efectiva, lo cual ha contribuido significativamente a la organización y la claridad en el desarrollo del proyecto. Al participar activamente en las llamadas grupales, hemos establecido una base sólida de comprensión mutua y confianza, lo que facilita la asignación de tareas y la colaboración en equipo. Además, estas interacciones nos han permitido identificar áreas clave que requieren atención y enfoque, asegurando que abordemos los desafíos de manera proactiva y eficiente. En resumen, la comunicación oral grupal no solo es esencial para compartir información, sino que también es fundamental para construir relaciones sólidas y establecer una estructura organizativa efectiva que guiará nuestro progreso en las siguientes etapas del proyecto.|
|Conoce al menos un sector empresarial o dominio de aplicación de soluciones de software.|Adriano Sebastian Cruz Palomino<br><b>TB1</b><br>Me sumerjo en la investigación del sector tecnológico, explorando las demandas y expectativas de las empresas de tecnología en cuanto a habilidades y conocimientos técnicos, para asegurarme de que nuestra plataforma responda de manera efectiva a estas necesidades.<br><br>Sebastian Nicolas Cachis Gonzales<br><b>TB1</b><br>e involucro en conversaciones y colaboraciones con empresas de tecnología para comprender de primera mano lo que están buscando en los candidatos durante las entrevistas técnicas, utilizando esta información para dar forma al contenido y las características de nuestra plataforma.<br><br>Jeremy Joel Quispe Andia<br><b>TB1</b><br>Me enfoqué en crear contenido altamente relevante y práctico para las entrevistas técnicas en el sector tecnológico, ofreciendo preguntas frecuentes, ejercicios de codificación y tutoriales específicamente diseñados para este dominio.<br><br>Elias Yauri Paucar<br><b>TB1</b><br> Implementamos simulacros de entrevistas en vivo con expertos en tecnología, diseñados para reflejar fielmente las situaciones y desafíos que los candidatos enfrentarán en las entrevistas técnicas del mundo real.<br><br>Alexander Jair Castillo Castillo<br><b>TB1</b><br>Consideramos cuidadosamente las opciones de monetización, como membresías premium con acceso a contenido adicional y sesiones de tutoría personalizada, para garantizar un flujo de ingresos sostenible mientras proporcionamos un valor significativo a nuestros usuarios.<br><br>Andrea Cabanillas<br><b>TB1</b><br>Nos comprometemos a mantenernos al tanto de las últimas tendencias y cambios en la industria tecnológica, actualizando y mejorando constantemente nuestra plataforma para garantizar su relevancia y efectividad a largo plazo en la preparación de los candidatos para las entrevistas técnicas.|<b>TB1</b><br>Como equipo, nuestra iniciativa de crear una plataforma de preparación para entrevistas técnicas en el sector tecnológico representa un compromiso sólido con la excelencia y la innovación. A lo largo de este proyecto, hemos demostrado una capacidad excepcional para investigar, colaborar y desarrollar contenido altamente relevante y práctico para nuestros usuarios. Nuestra colaboración estratégica con empresas de tecnología nos ha permitido comprender a fondo las demandas y expectativas del sector, asegurando que nuestra plataforma esté perfectamente alineada con las necesidades del mercado laboral actual. Al mismo tiempo, hemos mantenido un enfoque constante en la mejora continua, utilizando retroalimentación de usuarios y seguimiento de tendencias para actualizar y mejorar constantemente nuestra oferta. En conclusión, como equipo, estamos orgullosos del impacto positivo que nuestra plataforma está teniendo en la preparación de los candidatos para las entrevistas técnicas. Seguiremos trabajando arduamente para mantenernos a la vanguardia de la industria, proporcionando a nuestros usuarios las herramientas y el apoyo que necesitan para alcanzar sus metas profesionales en el mundo tecnológico en constante evolución.|

### Capítulo I: Introducción
**1.1. Startup Profile**
  - 1.1.1. Descripción de la Startup
 
    *CodePace* es una plataforma especializada en la preparación de programadores para entrevistas técnicas en empresas de tecnología. Nos dedicamos a ofrecer una variedad de recursos y entrenamiento diseñados para ayudar a los usuarios a mejorar sus habilidades de                 codificación, prepararse para entrevistas y asegurar trabajos en la industria tecnológica.

    Con un enfoque centrado en el usuario, nuestra plataforma proporciona una experiencia integral que abarca desde preguntas frecuentes de entrevistas hasta ejercicios de codificación práctica y simulacros de entrevistas en vivo con expertos. Además, colaboramos                  estrechamente con empresas de tecnología para ofrecer contenido exclusivo y oportunidades de reclutamiento para nuestros usuarios.

    **Misión:**
    Nuestra misión en CodePace es brindar a los programadores las herramientas y el conocimiento necesarios para tener éxito en sus entrevistas técnicas y carreras profesionales en la industria tecnológica. Nos esforzamos por ser el compañero de confianza de cada usuario en       su viaje hacia el éxito laboral en tecnología.

    **Visión:**
    En *CodePace*, visualizamos un futuro donde cada programador tenga acceso a recursos de calidad y entrenamiento efectivo para prepararse para entrevistas técnicas y avanzar en sus carreras en la industria tecnológica. Nos dedicamos a ser líderes en la preparación para         entrevistas técnicas, impulsando el crecimiento y la excelencia en la comunidad de desarrolladores a nivel mundial.


  - 1.1.2. Perfiles de integrantes del equipo

| Integrantes                        | Descripción del perfil |
|-----------------------------------|--------------|
|Elias Yauri Paucar (u202211817)<br><img src="https://github.com/CodepaceOrganization/Informes/assets/134337719/7cc1bfac-2b67-43eb-bb3a-140739bb4b8c" alt="Elias Yauri" style="width: 200px;">|Mi nombre es Elias Yauri Paucar, tengo 18 años, soy estudiante de Ing. De software en la UPC y actualmente estoy en 5 ciclo de mi carrera. Me considero una persona muy versátil a cualquier circunstancia o problema que se me presente, me logro acoplar y congeniar fácilmente con un equipo. Me comprometo a dar mi mayor esfuerzo en realizar todos los puntos y actividades con respecto a este proyecto.|
| Jair Castillo (u202211390)<br><img src="https://github.com/CodepaceOrganization/Informes/assets/134337719/f96f45ff-da0d-4adf-b7a8-92382705d282" alt="Jair Castillo" style="width: 200px;">|Mi nombre es Jair Castillo, estoy cursando el 5to ciclo de la carrera de Ingeniería de Software en la UPC.Poseo habilidades intermedias en el lenguaje de programación C++. Soy una persona atenta y responsable, con capacidad para adaptarme de manera efectiva a diversos escenarios y desafíos que puedan surgir.|
| Jeremy Joel Quispe Andia (u202216279) <br><img src="https://github.com/CodepaceOrganization/Informes/assets/134337719/8640c1f6-2922-480b-88d3-be4f0a8ec94f" alt="Jeremy Quispe" style="width: 200px;"> |Mi nombre es Jeremy Quispe, estoy cursando el 5to ciclo de la carrera de Ingeniería de Software en la UPC. Decidí estudiar esta carrera debido a que me agrada mucho poder crear soluciones tecnológicas y cómo estás podrían contribuir de manera positiva a la sociedad. Por ello, agradezco a la universidad por brindarme los recursos para poder superarme cada día y adquiriendo grandes conocimientos.|
| Andrea Milagros Cabanillas Gora (u202211711) <br><img src="https://github.com/CodepaceOrganization/Informes/assets/134337719/f800cd02-e527-4056-9807-e61dbacd264b" alt="Andrea Cabanillas" style="width: 200px;">| Soy Andrea, actualmente soy una estudiante de Ingeniería de software, me gusta diseñar paginas web, dibujar y bailar marinera.   |
| Sebastian Nicolas Cachis Gonzales (u202210846) <br><img src="https://github.com/CodepaceOrganization/Informes/assets/134337719/552d3d92-0a4d-41d8-b90e-3ec504d56c55" alt="Sebastian Cachis" style="width: 200px;">| Tengo 19 años, soy alumno de Ingeniería de Software en la UPC en mi quinto ciclo. Me considero una persona proactiva, organizada, meticulosa y muy enfocada en mis estudios, tanto grupales como individuales. Tengo facilidad para entender y ejemplificar los distintos temas que vemos, teniendo soltura para explicar.  |
| Adriano Sebastian Cruz Palomino (u202211711) <br><img src="https://github.com/CodepaceOrganization/Informes/assets/134337719/4ea280b1-1aa7-485f-ab81-05404307bf22" alt="Adriano Cruz" style="width: 200px;">|Mi nombre es Adriano Sebastian Cruz Palomino, tengo 19 años, soy alumno de Ingeniería de Software en la UPC, actualmente estoy cursando el 5to ciclo. Soy una persona curiosa, responsable, y comprometida con mis estudios, siempre busco aprender más y mejorar mis habilidades.  |

**1.2. Solution Profile**
  - 1.2.1. Antecedentes y problemática
  
    Para comprender las necesidades de nuestros usuarios universitarios en el proyecto GetWork, hemos realizado un estudio utilizando la técnica 5W's & 2H's. Esta metodología, ampliamente utilizada en la gestión empresarial, nos ha permitido identificar los siguientes             aspectos cruciales:

    **¿Cuáles son las 5W?**
    What (Qué)

    El problema que abordamos es la falta de preparación adecuada de los estudiantes universitarios para enfrentarse a entrevistas técnicas y el mercado laboral en el ámbito de la tecnología. Muchos graduados carecen de las habilidades técnicas, de resolución de problemas y       de comunicación necesarias para destacar en este competitivo campo. La insuficiente preparación limita sus oportunidades laborales y puede afectar negativamente su progreso profesional.

    **Who (Quién)**

    Este problema afecta a estudiantes universitarios de diversas disciplinas y niveles académicos que aspiran a ingresar al mercado laboral tecnológico. Tanto profesores como estudiantes se ven directamente afectados por la falta de preparación para enfrentar las exigencias      específicas de la industria.

    **When (Cuándo)**

    El problema se manifiesta en el momento en que los estudiantes universitarios están buscando oportunidades laborales y se enfrentan a entrevistas técnicas. La falta de preparación adecuada puede hacer que pierdan oportunidades valiosas de empleo y retrasar su inserción en     el mercado laboral.

    **Where (Dónde)**

    El problema está presente en todo el proceso de búsqueda de empleo, desde la elaboración de currículums hasta la participación en entrevistas, tanto en entornos físicos como virtuales. La falta de habilidades técnicas y de preparación puede obstaculizar la capacidad de        los estudiantes para destacar en cualquier contexto laboral.

    **Why (Por qué)**

    La causa fundamental del problema radica en la falta de acceso a recursos y entrenamiento especializado que prepare a los estudiantes universitarios para las demandas específicas del mercado laboral tecnológico. Aunque las instituciones educativas pueden brindar una base      sólida en conceptos teóricos, muchas veces no ofrecen una preparación práctica y específica para las habilidades y competencias necesarias en la industria.

    **¿Cuáles son las 2H?**
    **How (Cómo)**

    Nuestros usuarios recurren a GetWork cuando desean mejorar sus habilidades técnicas, prepararse para entrevistas técnicas y asegurar empleos en la industria tecnológica. Descubren nuestra plataforma a través de campañas de promoción en línea, recomendaciones de amigos, y      referencias de instituciones educativas y empresas asociadas. GetWork ofrece una amplia gama de recursos y herramientas, incluyendo preguntas frecuentes de entrevistas, ejercicios de codificación práctica, simulacros de entrevistas en vivo con expertos, tutoriales sobre       temas comunes de entrevistas y contenido exclusivo proporcionado por empresas de tecnología.

    **How much (Cuánto)**

    En la actualidad, el mercado laboral tecnológico experimenta un crecimiento constante y una demanda creciente de profesionales con habilidades técnicas sólidas. Se espera que esta tendencia continúe en los próximos años, lo que respalda la importancia y la viabilidad de       plataformas como GetWork. El volumen de datos almacenados en la nube sigue aumentando exponencialmente, reflejando la necesidad continua de soluciones seguras y confiables para la preparación laboral en tecnología. Este crecimiento y demanda ofrecen un amplio campo de          oportunidades para la expansión y el desarrollo futuro de GetWork.

    - 1.2.2. Lean UX Process

    El proceso Lean UX Process es una estrategia diseñada para optimizar el desarrollo de nuestro producto, centrándose en principios esenciales como la validación, el pensamiento y la acción. Siguiendo esta filosofía, hemos creado nuestro propio proceso Lean UX, que se           fundamenta en cuatro elementos clave: declaraciones de problemas, suposiciones, enunciados de hipótesis y lienzo.
    - 1.2.2.1. Lean UX Problem Statements

    Con la plataforma de preparación para entrevistas técnicas, nos enfrentamos a un desafío crítico en la seguridad de los datos y la confidencialidad de la información personal y profesional de nuestros usuarios. Es fundamental abordar esta preocupación para garantizar la       confianza de los programadores que utilizan nuestra plataforma.

    Para enfrentar esta incertidumbre y ofrecer una solución confiable, hemos desarrollado un proceso basado en la metodología Lean UX, adaptado específicamente a las necesidades de nuestro proyecto.

    En primer lugar, identificamos claramente el problema principal que enfrentan nuestros usuarios: la preocupación por la seguridad y la privacidad de sus datos mientras utilizan nuestra plataforma para prepararse para entrevistas técnicas. Esta preocupación se convierte en     nuestra declaración de problema, lo que nos permite comprender a fondo las necesidades y preocupaciones de nuestros usuarios.

    A continuación, formulamos suposiciones sobre cómo podríamos abordar este problema y mejorar la seguridad de los datos para nuestros usuarios. Estas suposiciones nos ayudan a generar hipótesis sobre las posibles soluciones que podríamos implementar para garantizar la          confidencialidad de la información personal y profesional de nuestros usuarios.

    Una vez que tenemos nuestras hipótesis, las sometemos a pruebas y validación utilizando diversas técnicas, como pruebas de penetración, auditorías de seguridad y evaluaciones de riesgos. Esto nos permite recopilar datos reales y retroalimentación de nuestros usuarios para     evaluar la efectividad de nuestras soluciones propuestas en términos de seguridad de datos.

    Finalmente, basándonos en los resultados de nuestras pruebas y validación, iteramos en nuestro diseño y ejecución para mejorar continuamente la seguridad y la confidencialidad de la información de nuestros usuarios. Esto nos permite desarrollar una plataforma de               preparación para entrevistas técnicas que nuestros usuarios puedan utilizar con total confianza en la protección de sus datos personales y profesionales.

  - 1.2.2.2. Lean UX Assumptions

  **Business Assumptions**
  
  Creemos que existe una necesidad en el mercado de una plataforma que ayude a los programadores a prepararse de manera efectiva para las entrevistas técnicas en empresas de tecnología.
  
  Esta necesidad puede ser abordada mediante el desarrollo de una plataforma que ofrezca recursos de calidad, como preguntas frecuentes de entrevistas, ejercicios de codificación práctica y simulacros de entrevistas en vivo con expertos.
  
  Nuestros clientes iniciales serán programadores y desarrolladores de software que estén buscando activamente oportunidades laborales en empresas de tecnología.
  
  El valor principal que nuestros clientes desean de nuestro servicio es poder prepararse de manera adecuada y eficiente para las entrevistas técnicas, aumentando así sus posibilidades de éxito en el proceso de contratación.
  
  Los clientes también obtendrán beneficios adicionales, como acceso a contenido exclusivo de empresas de tecnología y oportunidades de reclutamiento a través de la plataforma.
  
  Planeamos adquirir la mayoría de nuestros clientes mediante estrategias de marketing digital dirigidas a programadores y desarrolladores interesados en mejorar sus habilidades y oportunidades laborales.
  
  Generaremos ingresos a través de membresías premium que brinden acceso a contenido adicional, sesiones de tutoría personalizada y garantías de devolución de dinero para aquellos que no logren resultados satisfactorios en sus entrevistas, además de comisiones por oportunidades de reclutamiento.
  
  Nuestra competencia principal serán otras plataformas de preparación para entrevistas técnicas, así como recursos en línea disponibles gratuitamente.
  
  Nos diferenciaremos de la competencia al ofrecer contenido exclusivo de empresas de tecnología y oportunidades de reclutamiento integradas en la plataforma.
  
  El mayor riesgo para nuestro servicio es que el segmento objetivo no perciba el valor agregado de nuestra plataforma o no esté dispuesto a invertir en su preparación para entrevistas técnicas.
  
  Resolveremos este riesgo mediante una estrategia de marketing efectiva que resalte los beneficios y ventajas de nuestra plataforma, así como mediante una continua mejora y actualización de nuestro contenido y servicios.

  **User Assumptions**
  
  ¿Quién es el usuario?
  Los usuarios principales son programadores y desarrolladores de software que buscan activamente oportunidades laborales en empresas de tecnología.
  
  ¿Qué problemas enfrenta nuestro producto y cómo los resolveremos?
  Uno de los problemas actuales del producto es la posible falta de acceso a recursos de calidad para prepararse adecuadamente para las entrevistas técnicas. Esto se resolverá mediante la incorporación de contenido exclusivo de empresas de tecnología y sesiones de tutoría personalizada.
  
  ¿Qué características son importantes?
  Las características clave incluyen preguntas frecuentes de entrevistas, ejercicios de codificación práctica, simulacros de entrevistas en vivo con expertos, así como acceso a contenido exclusivo de empresas de tecnología y oportunidades de reclutamiento integradas en la plataforma.
  
  ¿Dónde encaja nuestro producto en la vida laboral del usuario?
  Nuestro producto encaja en la preparación y mejora de las habilidades de los usuarios para entrevistas técnicas, lo que aumenta sus oportunidades de obtener empleo en empresas de tecnología.
  
  ¿Cuándo y cómo se usa nuestro producto?
  El producto será utilizado cuando los usuarios estén preparándose para entrevistas técnicas en empresas de tecnología. Se accederá a la plataforma para practicar ejercicios de codificación, revisar preguntas frecuentes y participar en simulacros de entrevistas en vivo.
  
  ¿Cómo debe verse y comportarse nuestro producto?
  El producto debe tener una interfaz intuitiva y fácil de usar, con acceso rápido y sencillo a todos los recursos de preparación. Además, debe garantizar la privacidad y seguridad de los datos de los usuarios, así como ofrecer una experiencia personalizada y motivadora para el aprendizaje.

  Asimismo, podemos ver una gráfica de los roles más requeridos en el campo y tomamos esto como referencia para capacitar de la mejor manera a nuestros usuarios:

  ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/293834dd-6d81-4f64-8d26-e241b4ab767b)

  Referencia: [Genbeta](https://www.genbeta.com/desarrollo/lenguajes-programacion-puestos-trabajo-para-desarrolladores-demanda-que-mejor-pagan)
  
  - 1.2.2.3. Lean UX Hypothesis Statements

  **Hypothesis Statement 01:**
  **Creemos**  que los programadores y desarrolladores estarán dispuestos a adoptar nuestra plataforma de preparación para entrevistas técnicas para mejorar sus habilidades y aumentar sus posibilidades de éxito en las entrevistas de trabajo en empresas de tecnología.
  **Sabremos** que hemos tenido éxito.
  **Cuando** la tasa de adopción de la plataforma entre los usuarios objetivo alcance al menos el 80% dentro de los primeros tres meses posteriores al lanzamiento.
  
  **Hypothesis Statement 02:**
  **Creemos** que nuestra plataforma facilitará una mejor preparación para las entrevistas técnicas al proporcionar recursos de calidad y simulacros de entrevistas en vivo.
  **Sabremos** que hemos tenido éxito.
  **Cuando** se observe un aumento del 30% en la tasa de éxito de los usuarios en las entrevistas técnicas después de utilizar nuestra plataforma durante al menos un mes.
  
  **Hypothesis Statement 03:**
  **Creemos** que al ofrecer contenido exclusivo de empresas de tecnología y oportunidades de reclutamiento, nuestra plataforma aumentará la satisfacción y la confianza de los usuarios en su preparación para entrevistas técnicas.
  **Sabremos** que hemos tenido éxito.
  **Cuando** al menos el 70% de los usuarios que hayan utilizado las oportunidades de reclutamiento a través de nuestra plataforma informen haber tenido una experiencia positiva y útil.
  
  **Hypothesis Statement 04:**
  **Creemos** que al proporcionar sesiones de tutoría personalizada y garantías de devolución de dinero para aquellos que no logren resultados satisfactorios en sus entrevistas, aumentaremos la retención de usuarios y la satisfacción del cliente.
  **Sabremos** que hemos tenido éxito.
  **Cuando** la tasa de retención de usuarios de la membresía premium supere el 60% en los primeros seis meses de su lanzamiento.

  - 1.2.2.4. Lean UX Canvas

![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/8624af12-9d1f-4638-84cf-f773edc14884)

**1.3. Segmentos objetivo**

  Para el desarrollo de este punto hemos recolectado información del cuadro estadístico de Kinst, donde se muestra la edad de los developer que buscan entrevistas técnicas.

  ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/fd0d1d47-9496-4ba8-8422-edf13993ab08)

  Referencia: [Kinsta](https://kinsta.com/es/estadisticas-ingenieria-software/)
  
  **Segmento objetivo #1: Desarrolladores en búsqueda de empleo**
  
  Descripción: Este segmento objetivo está compuesto por programadores y desarrolladores de software que están activamente buscando oportunidades laborales en empresas de tecnología.
  
  Aspectos demográficos:
  Sexo: Masculino y Femenino
  Edades: Mayoritariamente entre 18 y 35 años.
  Nivel socioeconómico: Clases A, B, C (Alta, Media-alta y Media)
  
  Aspectos geográficos:
  Nacionalidad: Peruana
  Zona geográfica en la que vive: Urbana
  Departamento: Lima y Callao
  Aspectos psicográficos:
  
  Buscan mejorar sus habilidades técnicas para destacar en el mercado laboral.
  Desean acceder a recursos de preparación para entrevistas de manera conveniente y eficaz.
  Valorizan la seguridad y la privacidad en el almacenamiento de datos.
  Necesidades: Buscan mejorar sus habilidades de codificación, prepararse para entrevistas técnicas y obtener un empleo en el campo tecnológico.
  
  Requisitos: Desean una plataforma que les brinde recursos de calidad, como preguntas frecuentes de entrevistas, ejercicios de codificación práctica y simulacros de entrevistas en vivo.
  
  Objetivo: Aumentar sus posibilidades de éxito en el proceso de contratación.
  
  **Segmento objetivo #2: Estudiantes de informática y carreras relacionadas**
  
  Descripción: Este segmento objetivo incluye a estudiantes universitarios y recién graduados de carreras de informática, ingeniería de software y disciplinas afines.
  
  Aspectos demográficos:
  Sexo: Masculino y Femenino
  Edades: Mayoritariamente entre 18 y 25 años.
  Nivel socioeconómico: Clases A, B, C (Alta, Media-alta y Media)
  Aspectos geográficos:
  
  Nacionalidad: Peruana
  Zona geográfica en la que vive: Urbana
  Departamento: Lima y Callao
  
  Aspectos psicográficos:
  Buscan mejorar sus habilidades técnicas y prepararse para su futura inserción laboral.
  Valorizan la facilidad de acceso y la seguridad en el almacenamiento de archivos.
  Prefieren soluciones intuitivas y fáciles de usar para gestionar sus documentos.
  Necesidades: Están interesados en mejorar sus habilidades técnicas y prepararse para futuras entrevistas de trabajo en la industria tecnológica.
  
  Requisitos: Buscan una plataforma que les proporcione tutoriales sobre temas comunes de entrevistas, contenido exclusivo de empresas de tecnología y oportunidades de reclutamiento.
  
  Objetivo: Facilitar su transición al mercado laboral y obtener empleo en empresas líderes del sector tecnológico.

### Capítulo II: Requirements Elicitation & Analysis

  - 2.1.1. Análisis competitivo

    LeetCode: Es una plataforma en línea para que los programadores practiquen sus habilidades de codificación a través de una amplia gama de preguntas de entrevistas técnicas.
    Ofrece una variedad de preguntas clasificadas por dificultad y tema, así como discusiones comunitarias y soluciones para cada pregunta y proporciona una amplia gama de recursos gratuitos y opciones de suscripción premium para acceder a contenido adicional y características avanzadas.

    HackerRank: Es una plataforma para que los programadores mejoren sus habilidades de codificación y se preparen para entrevistas técnicas.
    Ofrece desafíos de codificación en línea, tutoriales y entrevistas prácticas, así como una comunidad activa de desarrolladores, por otro lado colabora con empresas de tecnología para ofrecer oportunidades de reclutamiento a través de la plataforma, conectando a los usuarios con empleadores potenciales.

    InterviewBit Es una plataforma diseñada para ayudar a los programadores a prepararse para entrevistas técnicas en empresas de tecnología.
    Ofrece una combinación de preguntas de entrevistas prácticas, tutoriales y sesiones de práctica en vivo con expertos y colabora con empresas de tecnología para ofrecer contenido exclusivo y oportunidades de reclutamiento para los usuarios de la plataforma.

        
  - 2.1.2. Estrategias y tácticas frente a competidores

<table><tr><th colspan="2" valign="top">Nombre</th><th valign="top"><b>GetWork</b></th><th valign="top">LeetCode</th><th valign="top">HackerRank</th><th valign="top">InterviewBit</th></tr>
<tr><td rowspan="2" valign="top">Perfil</td><td valign="top">Overview</td><td valign="top">Es una plataforma que ofrece recursos y entrenamiento para ayudar a los programadores a prepararse para entrevistas técnicas. </td><td valign="top">Es una plataforma en línea para codificar la preparación de entrevistas. El servicio proporciona problemas algorítmicos y de codificación destinados a que los usuarios practiquen la codificación.</td><td valign="top">HackerRank es una empresa de tecnología que se enfoca en desafíos de programación competitivos tanto para consumidores como para empresas. Los desarrolladores compiten escribiendo programas de acuerdo con las especificaciones proporcionadas</td><td valign="top">Es una plataforma para aprender las habilidades que necesita para trabajos tecnológicos. Le ayudamos a pulir sus habilidades y prepararse para el trabajo, ya sea un recién graduado universitario o un profesional en activo</td></tr>
<tr><td valign="top">Ventaja competitiva ¿Que valor ofrecemos a los clientes?</td><td valign="top"><p>La plataforma podría incluir preguntas frecuentes de entrevistas, ejercicios de codificación práctica, simulacros de entrevistas en vivo con expertos y tutoriales sobre temas comunes de entrevistas. Además, tendriamos empresas de tecnología para ofrecer contenido exclusivo y oportunidades de reclutamiento para los usuarios de la plataforma. Ofrecemos membresías premium que brindan acceso a contenido adicional, sesiones de tutoría personalizada y garantías de devolución de dinero para aquellos que no logren resultados satisfactorios en sus entrevistas.</p><p></p></td><td valign="top">ofrece una plataforma integral que combina preguntas de codificación práctica, discusiones comunitarias, entrenamiento para entrevistas técnicas y características avanzadas para ayudar a los desarrolladores a mejorar sus habilidades de codificación y prepararse para entrevistas en empresas de tecnología</td><td valign="top">ofrece una plataforma integral que combina desafíos de codificación, entrenamiento para entrevistas técnicas, eventos de programación, certificaciones de habilidades técnicas y herramientas de análisis para ayudar a los desarrolladores a mejorar sus habilidades y avanzar en sus carreras en tecnología.</td><td valign="top">InterviewBit ofrece a sus clientes una plataforma integral para prepararse para entrevistas técnicas, mejorar sus habilidades de programación, recibir orientación profesional y acceder a oportunidades laborales en la industria tecnológica.</td></tr>
<tr><td valign="top">Plan de marketing</td><td valign="top">Mercado objetivo</td><td valign="top">El mercado objetivo serían programadores y profesionales de tecnología que estén buscando empleo en empresas del sector tecnológico. Este mercado incluiría a estudiantes universitarios de carreras relacionadas con la informática, ingeniería informática o campos afines, así como a profesionales con experiencia que estén buscando cambiar de trabajo o avanzar en sus carreras dentro de la industria tecnológica.</td><td valign="top"><p>Candidatos en búsqueda de empleo</p><p>Empresas que buscan contratar empleados</p></td><td valign="top"><p>Desarrolladores, entusiastas de la programación</p><p>Reclutadores  empresas en busca de talento tecnológico</p><p>interesados en mejorar sus habilidades de programación, prepararse para entrevistas técnicas y encontrar oportunidades laborales en el campo de la tecnología.</p></td><td valign="top"><p>estudiantes y profesionales de tecnología que buscan mejorar sus habilidades de codificación y prepararse para entrevistas técnicas </p><p></p><p></p><p></p><p></p><p></p></td></tr>
<tr><td valign="top"> </td><td valign="top">Estrategias de Marketing</td><td valign="top">se utilizarían tácticas de publicidad en línea, marketing de influencia y asociaciones estratégicas con instituciones educativas y empresas de tecnología. El email marketing y la construcción de una comunidad en torno a la plataforma también serían componentes importantes para mantener a los usuarios comprometidos y fomentar la participación. </td><td valign="top">LeetCode utiliza diversas estrategias de marketing y publicidad en línea para promocionar su plataforma y llegar a nuevos usuarios. Esto puede incluir anuncios pagados en motores de búsqueda, redes sociales, sitios web relacionados con la tecnología y otras plataformas en línea.</td><td valign="top">El plan de marketing para HackerRank se enfoca en comprender a su audiencia objetivo, destacar sus propuestas únicas de venta y utilizar diversas estrategias de marketing para alcanzar los objetivos establecidos. Esto incluye la creación de contenido relevante, el uso de redes sociales, SEO, email marketing, alianzas estratégicas, publicidad pagada y participación en eventos. Se asigna un presupuesto y recursos para cada estrategia, seguido de una implementación cuidadosa, monitoreo constante de resultados y ajustes según sea necesario. El plan se centra en la mejora continua y la innovación para mantener a HackerRank competitivo y atraer a más usuarios y clientes.</td><td valign="top">Las estrategias de marketing para InterviewBit se centran en la creación de contenido educativo de alta calidad, publicidad digital dirigida en plataformas relevantes, optimización para motores de búsqueda (SEO), campañas de email marketing, alianzas estratégicas con instituciones educativas y empresas de tecnología, marketing de influencers, eventos y webinars, y programas de referidos. Estas estrategias tienen como objetivo aumentar la visibilidad de InterviewBit, atraer nuevos usuarios y construir una comunidad comprometida de aprendices de tecnología.</td></tr>
<tr><td rowspan="3" valign="top">Perfil del producto</td><td valign="top">Productos y Servicios</td><td valign="top"><p>Recursos educativos</p><p>Simulacros de entrevistas en vivo</p><p>contenido exclusivo y oportunidades de reclutamiento</p><p>Membresías premium</p></td><td valign="top"><p>Plataforma de práctica de codificación</p><p>Banco de preguntas de entrevista</p><p>Contenido educativo</p><p>Premium Membership</p></td><td valign="top"><p>Plataforma de Desafíos de Codificación</p><p>Herramientas de Entrevistas Técnicas</p><p>Plataforma de Contratación Técnica:</p><p>Desafíos de Codificación en el Mundo Real</p></td><td valign="top"><p>Plataforma de Aprendizaje</p><p>Preparación para Entrevistas Técnicas</p><p>Evaluación de Habilidades Técnicas</p><p>Recursos Educativos</p></td></tr>
<tr><td valign="top">Precios y Costos</td><td valign="top">Membresías premium:  $9.99</td><td valign="top"><p>Membresía premium cuesta:</p><p>Plan mensual: Aproximadamente $35 USD por mes.</p><p>Plan anual: Aproximadamente $159 USD por año.</p></td><td valign="top"><p></p><p>Starter : 1 user $100</p><p>Pro : 5 user $450</p><p></p></td><td valign="top">El precio depende del plan que quieras dependiendo de que a empresas quieres postular y cuanto tiempo dura la preparación.</td></tr>
<tr><td valign="top">Canales de distribución</td><td valign="top">Sus canales de distribución serian  la propia plataforma en línea, redes sociales, publicidad en línea, marketing de contenidos, marketing de afiliados, email marketing, asociaciones estratégicas y participación en eventos. Estos canales se utilizan para aumentar la visibilidad, llegar a una amplia audiencia y atraer a usuarios interesados en mejorar sus habilidades técnicas para entrevistas en la industria tecnológica.</td><td valign="top"><p>Los canales de distribución de LeetCode se centran principalmente en su plataforma en línea, a través de la cual los usuarios pueden acceder a sus productos y servcios.</p><p>El canal principal de distribución de LeetCode es su plataforma en línea, que está accesible a través de su sitio web oficial</p><p>LeetCode ofrece aplicaciones móviles disponibles para dispositivos iOS y Android.</p><p></p><p></p></td><td valign="top">HackerRank utiliza una combinación de canales en línea, estrategias de marketing digital, alianzas estratégicas y ventas directas para distribuir sus servicios a usuarios individuales y empresas en el campo de la tecnología y la contratación técnica</td><td valign="top"><p>Los canales de distribución de InterviewBit se centran en la distribución de sus servicios a través de una plataforma en línea, su sitio web oficial y diversas estrategias de marketing digital, incluyendo SEO, marketing de contenidos y redes sociales. Además, la empresa puede aprovechar alianzas estratégicas con instituciones educativas y empresas de tecnología, así como implementar programas de afiliados para ampliar su alcance. Estos canales de distribución permiten a InterviewBit llegar a su audiencia objetivo y promocionar sus servicios de manera efectiva en el mercado.</p><p></p><p></p><p></p><p></p><p></p><p></p></td></tr>
<tr><td rowspan="4" valign="top">Análisis SWOT</td><td valign="top">Fortalezas</td><td valign="top"><p>Contenido diverso y útil: La plataforma ofrece una amplia gama de recursos educativos, simulacros de entrevistas en vivo y contenido exclusivo, lo que la hace atractiva para los usuarios que buscan prepararse para entrevistas técnicas en empresas de tecnología.</p><p></p><p>Colaboraciones estratégicas: Las asociaciones con empresas de tecnología y otras organizaciones relevantes proporcionan acceso a contenido exclusivo y oportunidades de reclutamiento, lo que añade valor a la plataforma y la diferencia de la competencia.</p><p></p><p>Variedad de canales de distribución: Utiliza una combinación efectiva de canales de distribución en línea y fuera de línea, lo que permite llegar a una amplia audiencia de manera eficiente y efectiva.</p></td><td valign="top">Las fortalezas de LeetCode incluyen su amplia colección de problemas, plataforma fácil de usar, contenido educativo complementario, enfoque en la preparación para entrevistas técnicas, comunidad activa y opciones de membresía premium. Estas características hacen que LeetCode sea una herramienta valiosa para programadores de todos los niveles que buscan mejorar sus habilidades de codificación y prepararse para desafíos profesionales en el campo de la tecnología.</td><td valign="top"><p>HackerRank destaca por su amplia oferta de desafíos de codificación, herramientas de preparación para entrevistas técnicas, soluciones de contratación técnica para empresas, enfoque en proyectos del mundo real y recursos educativos, lo que lo convierte en una plataforma integral para desarrolladores y empresas en el campo de la tecnología.</p><p></p><p></p><p></p><p></p><p></p><p></p></td><td valign="top"><p>Plataforma educativa integral con recursos de calidad para mejorar las habilidades de programación.</p><p>Enfoque en la preparación para entrevistas técnicas, una necesidad creciente en el mercado laboral de tecnología.</p><p>Capacidad para adaptarse a las tendencias tecnológicas y ofrecer contenido actualizado y relevante.</p><p>Amplia gama de recursos educativos disponibles para usuarios de diversos niveles de habilidad</p></td></tr>
<tr><td valign="top">Oportunidades</td><td valign="top"><p>Crecimiento del mercado de tecnología: Con el continuo crecimiento del sector tecnológico, hay una creciente demanda de herramientas y recursos para ayudar a los profesionales a prepararse para entrevistas técnicas, lo que representa una oportunidad de crecimiento para la plataforma.</p><p></p><p>Expansión internacional: Existe la posibilidad de expandir la plataforma a mercados internacionales, aprovechando la demanda global de preparación para entrevistas técnicas en empresas de tecnología.</p></td><td valign="top">Las oportunidades para LeetCode son amplias y pueden incluir la expansión de la plataforma, el desarrollo de contenido educativo, el enfoque en la educación académica, la personalización de la experiencia del usuario, la internacionalización y las colaboraciones estratégicas. Al aprovechar estas oportunidades, LeetCode puede continuar creciendo y mejorando su oferta para satisfacer las necesidades cambiantes de los usuarios en el campo de la programación y la tecnología.</td><td valign="top">HackerRank tiene la oportunidad de capitalizar el crecimiento del mercado de tecnología, la educación en línea, la digitalización de procesos de contratación, la expansión internacional y las alianzas estratégicas para seguir creciendo y consolidándose como una plataforma líder en el campo de la tecnología y la contratación técnic</td><td valign="top"><p>Crecimiento continuo del mercado de tecnología y demanda de habilidades técnicas.</p><p>Aumento de la educación en línea y la preparación para entrevistas técnicas.</p><p>Posibilidad de expandirse a nuevos mercados internacionales y colaborar con instituciones educativas.</p><p>Potencial para establecer alianzas estratégicas y programas de afiliados para ampliar el alcance y la visibilidad.</p></td></tr>
<tr><td valign="top">Debilidades</td><td valign="top"><p>Competencia intensa: El mercado de preparación para entrevistas técnicas está saturado, con múltiples competidores ofreciendo servicios similares, lo que puede dificultar la diferenciación y la captación de usuarios.</p><p></p><p></p><p>Dependencia de asociaciones: La plataforma puede depender en gran medida de asociaciones estratégicas con empresas de tecnología, lo que podría limitar su crecimiento si estas asociaciones se ven afectadas.</p></td><td valign="top"><p></p><p>Las debilidades que tiene son : </p><p>Curva de aprendizaje pronunciada, lo que puede resultar intimidante para principiantes.</p><p>Retroalimentación limitada sobre soluciones propuestas por usuarios.</p><p>Falta de diversidad en el contenido, especialmente en áreas especializadas.</p><p>Costo elevado de la membresía premium, lo que limita el acceso a características clave.</p><p>Dependencia excesiva en la resolución de problemas específicos, limitando la comprensión más amplia de conceptos.</p><p>Limitaciones en la colaboración y la interacción entre usuarios.</p></td><td valign="top"><p>HackerRank puede enfrentar desafíos en términos de competencia en el mercado, percepción de complejidad de la plataforma, limitaciones de personalización y dependencia de habilidades técnicas, lo que podría afectar su capacidad para mantener y expandir su base de usuarios.</p><p></p><p></p><p></p><p></p><p></p><p></p></td><td valign="top"><p>Competencia en el mercado de plataformas educativas y de preparación para entrevistas técnicas.</p><p>Posible complejidad percibida de la plataforma para algunos usuarios.</p><p>Limitaciones en la personalización de la experiencia del usuario.</p><p>Dependencia de habilidades técnicas y entrevistas técnicas puede limitar el atractivo para audiencias no técnicas.</p></td></tr>
<tr><td valign="top">Amenazas</td><td valign="top">Cambios en las tendencias tecnológicas: Los cambios rápidos en la tecnología pueden hacer que ciertos recursos y habilidades se vuelvan obsoletos, lo que podría afectar la relevancia de la plataforma si no se adapta rápidamente.</td><td valign="top">LeetCode enfrenta varias amenazas en su posición en el mercado de aprendizaje de programación, que incluyen la competencia creciente, cambios en la demanda del mercado, problemas de calidad del contenido, preocupaciones de ciberseguridad y privacidad.</td><td valign="top">HackerRank enfrenta amenazas potenciales como la competencia en el mercado, los cambios tecnológicos, las regulaciones de protección de datos, las amenazas de seguridad cibernética y las condiciones económicas adversas, que podrían impactar su capacidad para mantener y expandir su base de usuarios.</td><td valign="top"><p>Competencia continua y evolución del mercado de tecnología y educación en línea. Cambios en las tecnologías y programación pueden requerir actualizaciones frecuentes de contenido.Posibles cambios en las regulaciones de privacidad de datos pueden afectar la recopilación y el uso de información de los usuarios.</p><p></p></td></tr>
</table>


  **2.2. Entrevistas**
  
  Las entrevistas van dirigidas a desarrolladores, estudiantes y programadores ya que son el público objetivo principal de la plataforma, entrevistarlos permitirá comprender sus necesidades específicas en términos de preparación para entrevistas técnicas, qué recursos encuentran más útiles, qué áreas considera más desafiantes y qué características valorarán en la plataforma.

  - 2.2.1. Diseño de entrevistas


Preguntas para el Segmento Objetivo #1: Desarrolladores en búsqueda de empleo

1. ¿Qué tipo de recursos o herramientas utilizas actualmente para prepararte para entrevistas técnicas?
2. ¿Cuáles son los principales desafíos que enfrentas al prepararte para entrevistas de trabajo en empresas de tecnología?
3. ¿Qué valoras más al buscar recursos de preparación para entrevistas técnicas?
4. ¿Qué características consideras esenciales en una plataforma de preparación para entrevistas técnicas?
5. ¿Cómo te sentirías al tener acceso a preguntas frecuentes de entrevistas, ejercicios de codificación práctica y simulacros de entrevistas en vivo en una plataforma?
6. ¿Cuál es tu opinión sobre la idea de tener contenido exclusivo de empresas de tecnología en una plataforma de preparación para entrevistas?
7. ¿Qué tipo de recursos o funcionalidades crees que serían más útiles para mejorar tus habilidades técnicas y prepararte para entrevistas?
8. ¿Qué importancia le das a la seguridad y privacidad de tus datos al utilizar una plataforma de preparación para entrevistas técnicas?
9. ¿Consideras que una membresía premium que brinde acceso a contenido adicional y sesiones de tutoría personalizada sería útil para ti?
10. ¿Cómo crees que una plataforma de preparación para entrevistas técnicas podría aumentar tus posibilidades de éxito en el proceso de contratación?


Preguntas para el Segmento Objetivo #2: Estudiantes de informática y carreras relacionadas

1. ¿Qué estrategias utilizas actualmente para mejorar tus habilidades técnicas y prepararte para tu futura inserción laboral?
2. ¿Cuáles son tus mayores preocupaciones al enfrentarte al proceso de búsqueda de empleo en la industria tecnológica?
3. ¿Qué características buscas en una plataforma de preparación para entrevistas técnicas?
4. ¿Te resultaría útil tener acceso a tutoriales sobre temas comunes de entrevistas en una plataforma de preparación para entrevistas técnicas?
5. ¿Qué te parecería tener la oportunidad de acceder a contenido exclusivo de empresas de tecnología en una plataforma de preparación para entrevistas?
6. ¿Qué tipo de recursos o funcionalidades consideras más importantes para mejorar tus habilidades técnicas y prepararte para entrevistas?
7. ¿Valoras la facilidad de acceso y la usabilidad de una plataforma de preparación para entrevistas técnicas?
8. ¿Qué opinas sobre la posibilidad de tener sesiones de tutoría personalizada como parte de una membresía premium en una plataforma de preparación para entrevistas?
9. ¿Cuál es tu opinión sobre la seguridad y privacidad de tus datos al utilizar una plataforma de preparación para entrevistas técnicas?
10. ¿Cómo crees que una plataforma de preparación para entrevistas técnicas podría facilitar tu transición al mercado laboral y ayudarte a obtener empleo en empresas de tecnología líderes?

- 2.2.2. Registro de entrevistas

Segmento Objetivo #1: Desarrolladores

| Entrevistado N°1: Hernan Morales |<img src="https://github.com/CodepaceOrganization/Informes/assets/134337719/ec3abe0c-f9e2-49dd-849b-d3d52ae2d921" alt="Hernan Morales" style="width: 200px;">|
|--------------------------------|------------------------------------------------------------|
| **Nombre:**                    | Hernan Morales                                           |
| **Edad:**                      | 28                                                         |
| **Sexo:**                      | Masculino                                                  |
| **Ocupación:**                 | Desarrollador Web                                     |
| **Entrevista:**                | [Link]([https://youtu.be/c6rtyvA7e8s](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202216279_upc_edu_pe/EaamMTLNLXFIkqSN91zWbcoB50FCtcaRcFfin2Tb9V2gkA?e=eoOsSh&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D))       |
| **Momento de inicio:**         | 0:01                                                       |
| **Duración:**                  | 3:36                                                      |


| Entrevistado N°2: Andrés Valle |<img src="https://github.com/CodepaceOrganization/Informes/assets/134337719/85909d81-3243-4d99-8a8f-f023bba83fc6" alt="Andrés Valle" style="width: 220px;">|
|--------------------------------|------------------------------------------------------------|
| **Nombre:**                    | Andrés Valle                                               |
| **Edad:**                      | 28                                                         |
| **Sexo:**                      | Masculino                                                  |
| **Ocupación:**                 | Desarrollador Web                                     |
| **Entrevista:**                | [Link]([https://youtu.be/c6rtyvA7e8s](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202216279_upc_edu_pe/EaamMTLNLXFIkqSN91zWbcoB50FCtcaRcFfin2Tb9V2gkA?e=eoOsSh&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D))       |
| **Momento de inicio:**         | 3:37                                                       |
| **Duración:**                  | 7:40                                                      |


| Entrevistado N°3: Bárbara Quezada | <img src="https://github.com/CodepaceOrganization/Informes/assets/134337719/74231784-ca8b-4bd6-b71b-1b668a84927f" alt="Barbara" width="190"> |
|--------------------------------|------------------------------------------------------------|
| **Nombre:**                    | Barbara Quezada                                             |
| **Edad:**                      | 24                                                        |
| **Sexo:**                      | Femenino                                                  |
| **Ocupación:**                 | Desarrolladora Web                                     |
| **Entrevista:**                | [Link]([https://youtu.be/c6rtyvA7e8s](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202216279_upc_edu_pe/EaamMTLNLXFIkqSN91zWbcoB50FCtcaRcFfin2Tb9V2gkA?e=eoOsSh&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)) |
| **Momento de inicio:**         | 7:41                                                       |
| **Duración:**                  | 12:36                                                       |


Segmento objetivo #2: Estudiantes de informática y carreras relacionadas

| Entrevistado N°4: Marcelo Poggi | <img src="https://github.com/CodepaceOrganization/Informes/assets/134337719/e9564a4e-34c4-47d8-b3af-3dc9c2a913ba" alt="Poggi" width="200"> |
|--------------------------------|------------------------------------------------------------|
| **Nombre:**                    | Marcelo Poggi                                             |
| **Edad:**                      | 20                                                        |
| **Sexo:**                      | Masculino                                                  |
| **Ocupación:**                 | Estudiante de <br>ciencias de la computación                                     |
| **Entrevista:**                | [Link]([https://youtu.be/c6rtyvA7e8s](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202216279_upc_edu_pe/EaamMTLNLXFIkqSN91zWbcoB50FCtcaRcFfin2Tb9V2gkA?e=eoOsSh&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)) |
| **Momento de inicio:**         | 12:37                                                       |
| **Duración:**                  | 16:19                                                       |



| Entrevistado N°5: Alex Avila | <img src="https://github.com/CodepaceOrganization/Informes/assets/134337719/df319732-3e30-4916-b740-59f4bcf9d440" alt="alex" width="230"> |
|--------------------------------|------------------------------------------------------------|
| **Nombre:**                    | Alex Avila                                             |
| **Edad:**                      | 19                                                       |
| **Sexo:**                      | Masculino                                                  |
| **Ocupación:**                 | Estudiante de <br>ingieniria de software                                 |
| **Entrevista:**                | [Link]([https://youtu.be/c6rtyvA7e8s](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202216279_upc_edu_pe/EaamMTLNLXFIkqSN91zWbcoB50FCtcaRcFfin2Tb9V2gkA?e=eoOsSh&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)) |
| **Momento de inicio:**         | 16:20                                                       |
| **Duración:**                  | 21:44                                                      |


| Entrevistado N°6: Diego Salinas | <img src="https://github.com/CodepaceOrganization/Informes/assets/134337719/2ca79dc6-d0d4-479c-b399-2b83dbf9b2b4" alt="Diego" width="200"> |
|--------------------------------|------------------------------------------------------------|
| **Nombre:**                    | Diego Salinas                                             |
| **Edad:**                      | 19                                                       |
| **Sexo:**                      | Masculino                                                  |
| **Ocupación:**                 | Estudiante de ingenieria<br> de software                                 |
| **Entrevista:**                | [Link]([https://youtu.be/c6rtyvA7e8s](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202216279_upc_edu_pe/EaamMTLNLXFIkqSN91zWbcoB50FCtcaRcFfin2Tb9V2gkA?e=eoOsSh&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D))    |
| **Momento de inicio:**         | 21:45                                                       |
| **Duración:**                  | 26:45                                                      |


- 2.2.3. Análisis de entrevistas
  
| Entrevistado | Necesidades                                                                             | Pago Premium |
|--------------|-----------------------------------------------------------------------------------------|--------------|
| Marcelo Poggi      | - App fácil de usar <br> - Material actualizado <br> - Atención personalizada          | Sí           |
| Alex Ávila        | - Plataforma para codear en tiempo real <br> - Preparación para entrevistas reales <br> - Atención personalizada | Sí |
| Hernán Morales       | - Acceso a problemas desafiantes <br> - Recursos para mejorar habilidades blandas <br> - Contenido exclusivo de empresas | Sí |
| Andrés Valle      | - Acceso a preguntas frecuentes de entrevistas <br> - Contenido exclusivo de empresas <br> - Sesiones de práctica de entrevistas en vivo | Sí |
| Diego Salinas       | - Acceso a preguntas frecuentes de entrevistas <br> - Contenido exclusivo de empresas <br> - Sesiones de práctica de entrevistas en vivo | Sí |
| Bárbara Quezada     | - Acceso a preguntas frecuentes de entrevistas <br> - Recursos para mejorar habilidades blandas <br> - Atención personalizada | Sí |


Aspectos Valorados:
- Calidad y variedad de problemas de codificación
- Acceso a contenido exclusivo de empresas de tecnología
- Tutoriales claros
- Medidas sólidas de seguridad de datos
- Sesiones de práctica de entrevistas en vivo
- Contenido adicional y asesoramiento personalizado

Conclusiones del Análisis:
Los entrevistados, Marcelo, Alex, Hernán, Andrés, Diego y Bárbara, demandan una plataforma de preparación para entrevistas técnicas que cumpla con criterios específicos. Marcelo prioriza una atención personalizada y la actualización constante del material, demostrando disposición a pagar por una membresía premium que ofrezca estos servicios. Por otro lado, Alex busca una experiencia interactiva de codificación en tiempo real para simular entrevistas reales, también dispuesto a invertir en una atención personalizada y acceso a contenido exclusivo. Hernán valora el acceso a problemas desafiantes, recursos para mejorar habilidades blandas y contenido exclusivo de empresas. Andrés y Diego buscan acceso a preguntas frecuentes de entrevistas, contenido exclusivo de empresas y sesiones prácticas en vivo. Bárbara busca una plataforma que ofrezca preguntas frecuentes de entrevistas, recursos para mejorar habilidades blandas y una atención personalizada. En resumen, la plataforma ideal debe ofrecer una combinación de desafíos técnicos, recursos de aprendizaje claros y una atención adaptada a las necesidades individuales de los usuarios.

- 2.3. Needfinding

**2.3.1. User Personas**
  
  Segmento objetivo 1: Leticia Cassanova
  
  ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/c6d2950b-7f93-4562-8f4a-7a9f089c93a9)
  
  Segmento objetivo 2: Maria Sanchez
  
  ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/3ff745a7-66bd-4319-9ff1-60104ad00ae7)

  
**2.3.2. User Task Matrix**
  
Segmento objetivo 1: Leticia Cassanova

| Actividades                                                                                               | Frecuencia     | Importancia |
|-----------------------------------------------------------------------------------------------------------|----------------|-------------|
| Acceder a recursos de preparación para entrevistas técnicas en línea.                                     | Con Frecuencia | Alta        |
| Participar en simulacros de entrevistas técnicas en vivo.                                                  | Con Frecuencia | Alta        |
| Realizar ejercicios de codificación práctica para mejorar habilidades técnicas.                            | Con Frecuencia | Alta        |
| Almacenar y organizar documentos relacionados con oportunidades laborales y proyectos en la nube.         | A veces        | Media       |
| Acceder a material de estudio y tutoriales para mejorar habilidades de codificación.                        | Con Frecuencia | Alta        |
| Valorar la privacidad y seguridad en el acceso y almacenamiento de datos personales y laborales.          | Siempre         | Muy Alta    |
| Utilizar herramientas colaborativas en línea para proyectos grupales o trabajo remoto.                     | Con Frecuencia | Alta        |
| Participar en comunidades en línea para obtener retroalimentación y consejos sobre búsqueda de empleo.    | A veces        | Media       |
| Actualizarse sobre tendencias y noticias del mercado laboral y tecnológico.                                | Con Frecuencia | Alta        |

Segmento objetivo 2: Maria Sanchez

| Actividades                                                                                               | Frecuencia       | Importancia |
|-----------------------------------------------------------------------------------------------------------|------------------|-------------|
| Acceder a recursos de preparación para entrevistas técnicas en línea.                                     | Con Frecuencia   | Alta        |
| Participar en simulacros de entrevistas técnicas en vivo.                                                  | Con Frecuencia   | Alta        |
| Realizar ejercicios de codificación práctica para mejorar habilidades técnicas.                            | Con Frecuencia   | Alta        |
| Almacenar y organizar documentos relacionados con oportunidades laborales y proyectos en la nube.         | A veces          | Media       |
| Acceder a material de estudio y tutoriales para mejorar habilidades de codificación.                       | Con Frecuencia   | Alta        |
| Valorar la privacidad y seguridad en el acceso y almacenamiento de datos personales y laborales.          | Siempre          | Muy Alta    |
| Utilizar herramientas colaborativas en línea para proyectos grupales o trabajo remoto.                     | Con Frecuencia   | Alta        |
| Participar en comunidades en línea para obtener retroalimentación y consejos sobre búsqueda de empleo.    | A veces          | Media       |
| Actualizarse sobre tendencias y noticias del mercado laboral y tecnológico.                                | Con Frecuencia   | Alta        |


**2.3.3. User Journey Mapping**

  Segmento objetivo 1: Leticia Cassanova

  ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/d99113c8-1dc3-4129-aafd-38589607439b)

  Segmento objetivo 2: Maria Sanchez

  ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/a8e6f328-6069-4355-8be1-1fe952fe34b5)


**2.3.4. Empathy Mapping**

  Segmento objetivo 1: Leticia Cassanova

  ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/2078dd41-9aef-4083-9147-0baebb34f5df)

  Segmento objetivo 2: Maria Sanchez
  
  ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/a0b23c5e-93ad-4829-9b14-9602232c4641)

**2.3.5. As-is Scenario Mapping**

  Segmento objetivo 1: Leticia Cassanova

  ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/ae9248cc-8f2d-474c-bc9c-f1dc040d12e2)


  Segmento objetivo 2: Maria Sanchez

  ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/1d14233e-a3c4-4110-bc97-43d20c1e5e66)

**2.4. Ubiquitous Language**
  
  **Entrevistas Técnicas:** Procesos de evaluación utilizados por las empresas de tecnología para evaluar las habilidades técnicas y la idoneidad de los candidatos para un puesto.
  
- **Recursos de Preparación:** Materiales educativos y herramientas utilizadas para mejorar las habilidades técnicas y prepararse para entrevistas técnicas, incluyendo preguntas frecuentes de entrevistas, ejercicios de codificación práctica y simulacros de entrevistas en vivo.

- **Plataforma de Preparación para Entrevistas Técnicas:** Sistema en línea diseñado para ayudar a los programadores y desarrolladores a mejorar sus habilidades técnicas y prepararse para entrevistas técnicas, proporcionando una amplia gama de recursos de preparación y oportunidades de práctica.

- **Usuarios Objetivo:** Grupos específicos de personas a quienes está dirigido el producto, incluyendo desarrolladores en búsqueda de empleo y estudiantes de informática y carreras relacionadas.

- **Valor Agregado:** Beneficios adicionales proporcionados por la plataforma de preparación para entrevistas técnicas, como acceso a contenido exclusivo de empresas de tecnología, oportunidades de reclutamiento integradas y sesiones de tutoría personalizada.

- **Lean UX Process:** Método de desarrollo centrado en la optimización del producto mediante la validación, el pensamiento y la acción, incluyendo la identificación de problemas, suposiciones, hipótesis y el uso de lienzos para organizar ideas y estrategias.

- **Problem Statements:** Declaraciones que identifican los problemas principales que enfrentan los usuarios y guían el proceso de diseño y desarrollo del producto.

- **Hypothesis Statements:** Declaraciones que expresan creencias sobre cómo resolver los problemas identificados y establecen criterios para evaluar el éxito del producto.

- **Lean UX Canvas:** Herramienta visual utilizada para definir y organizar los elementos clave del proceso de diseño y desarrollo del producto, incluyendo problemas, soluciones, suposiciones y métricas de éxito.


### Capítulo III: Requirements Specification
**3.1. To-Be Scenario Mapping**

Segmento objetivo #1: Desarrolladores en búsqueda de empleo

![image](https://github.com/CodepaceOrganization/Informes/assets/142842509/5e44de7a-22cb-49ad-b6e6-d233dbf293dc)

Segmento objetivo #2: Estudiantes de informática y carreras relacionadas

![image](https://github.com/CodepaceOrganization/Informes/assets/142842509/4b0ac504-971a-4802-b447-785534a8ec82)


**3.2. User Stories**

|**Epic ID**|**Título**|**Descripción**|**Relacionado con (User Story ID)**|
| :- | :- | :- | :- |
|EP01|Gestión de Usuario|<p>**Como** usuario</p><p>**Quiero** gestionar mi perfil</p><p>**Para** acceder a la aplicación de GetWork</p>|<p>- US13 - Registrarse en la landing page</p><p>- US23 - Registrarse para obtener acceso exclusivo</p><p>- US30 - Evaluación de habilidades antes de la preparación</p><p></p>|
|EP02|Seguridad y Privacidad|<p>**Como** usuario</p><p>**Quiero** resguardar mis datos y privacidad</p><p>**Para** poder sentirme seguro al navegar en la aplicación de GetWork</p>|<p>- US02 - Seguridad de cuenta</p><p></p><p></p>|
|EP03|Reserva de Entrevistas|<p>**Como** usuario</p><p>**Quiero** poder reservar entrevistas</p><p>**Para** tener un mejor performance al momento de que se dé realmente.</p>|- US03 - Realizar reserva|
|EP04|Métodos de Pago|<p>**Como** usuario de GetWork</p><p>**Quiero** realizar mis pagos dentro de la aplicación de GetWork</p><p>**Para** poder adquirir los servicios premium con más confianza.</p>|<p>- US04 - Métodos de Pago</p><p></p><p></p>|
|EP05|Interfaz de Usuario|<p>**Como** usuario</p><p>**Quiero** tener una interfaz intuitiva</p><p>**Para** navegar con comodidad dentro de la aplicación de GetWork</p>|<p>- US07 - Interfaz sencilla</p><p>- US05 - Visualización de calendario de entrevistas y anotaciones</p><p>- US17 - Visualización de datos de usuario</p><p>- US21 - Ver testimonios de clientes en la landing page</p><p>- US01– Variedad de idioamas</p><p>- US09 - Visualizar la landing page de la empresa</p><p>&emsp;</p><p></p><p></p>|
|EP06|Participación y Competencia|<p>**Como** usuario</p><p>**Quiero** poder acceder a distintas competencias</p><p>**Para** poder estar preparado para cada situación que se pueda dar en la entrevista técnica.</p>|<p>- US08 - Participación en GetWork Contest</p><p>- US18 - Simulacros de entrevistas en grupo</p><p>- US24 - Simulacros de entrevistas técnicas en diferentes formatos</p><p>- US26 - Entrevistas técnicas en vivo con expertos</p><p>- US28 - Ver testimonios de clientes en la landing page</p><p></p>|
|EP07|Comunicación y Notificaciones|<p>**Como** usuario </p><p>**Quiero** poder comunicarme y recibir notificaciones</p><p>**Para** poder estar enterado de las últimas noticias</p>|<p>- US06 - Medio de comunicación</p><p></p><p></p>|
|EP08|Feedback y Mejora Continua|<p>**Como** usuario</p><p>**Quiero** recibir un feedback</p><p>**Para** poder estar al tanto de mi desempeño y cómo podría mejorar.</p>|<p>- US10 - Agregar sugerencias y/o comentarios</p><p></p><p></p>|
|EP09|Recursos de Aprendizaje|<p>**Como** usuario</p><p>**Quiero** acceder a los recursos de aprendizaje</p><p>**Para** poder prepararse con mayor eficacia y con una metodología buena de enseñanza.</p>|<p>- US11 - Entrenamiento especializado en desarrollo de algoritmos</p><p>- US12 - Práctica de simulacros de entrevistas técnicas</p><p>- US14 - Entrenamiento en resolución de problemas de lógica</p><p>- US15 - Acceso a tutores especializados</p><p>- US16 - Planificación de estudio personalizado</p><p>- US19 - Enviar consulta a través del formulario de contacto</p><p>- US20 - Asesoramiento profesional y de carrera</p><p>- US25 - Plataforma de práctica de diseño de sistemas</p><p>- US29 - Preparación para entrevistas técnicas de desarrollo web</p><p>- US27 - Preparación para entrevistas técnicas específicas de la industria</p><p>- US22 - Entrenamiento en resolución de problemas de codificación en tiempo real</p><p></p><p></p><p></p>|



|**Epic / User Story ID**|**Título**|**Descripción** |**Criterios de aceptación**|**Relacionado con (Epic ID)**|
| :- | :- | :- | :- | :- |
|**US01**|**Variedad de idioamas**|**Como** usuario **quiero** que la aplicación esté disponible al menos en idioma inglés o español **para** que alguien que solo sepa inglés y no sólo español.|<p>**Escenario 1** El usuario quiere que haya 2 idiomas en la aplicación</p><p>**Dado que** el usuario puede ser de otra nacionalidad y al acceder al programa puede que al inicio no entienda a la aplicación, pero tendrá un opción de cambiar el idioma.  </p><p>**Cuando** desee cambiar el idioma, tendrá 2 opciones.</p><p>**Entonces** seleccione su idioma con el que se sienta seguro de sí mismo y pueda continuar con sus reservas de entrevistas.</p><p></p><p>**Escenario 2:**<br><br>**Dado que** el usuario desea cambiar el idioma de la aplicación para adaptarse a sus preferencias lingüísticas.</p><p>**Cuando** accede a la configuración o ajustes de la aplicación.</p><p>**Entonces**, encontrará una opción para seleccionar el idioma deseado entre las dos opciones disponibles: inglés o español.</p><p></p>|**EP05**||
|**US02**|**Seguridad de cuenta**|<p>**Como** usuario **quiero** vincular un número de celular adicional **para** que en caso pierda la cuenta principal pueda recuperarlo con este.</p><p></p>|<p>**Escenario 1**: El usuario vincula un número de celular a la aplicación</p><p>**Dado que** el usuario se encuentra dentro de la aplicación, le sale un aviso de asegurar su cuenta  “SI” o “NO” en caso de pérdida o robo del dispositivo.</p><p>**Cuando** el usuario presione el botón en “SI“ le dará la opción de “Agregar un número de celular”.</p><p>**Entonces** el usuario tiene que llenar en esa opción.</p><p>**Y** rápidamente llegará un mensaje de aviso “Usted ha vinculado su numero de celular a nuestra aplicación” .</p><p></p><p>**Escenario 2:**</p><p>**Dado que** el usuario ya tiene un número de celular vinculado a la aplicación y desea agregar un número adicional como medida de seguridad.</p><p>**Cuando** el usuario seleccione la opción de seguridad de cuenta dentro de la configuración de la aplicación.</p><p>**Entonces**, se le presentará la opción de "Agregar un número de celular adicional".</p><p>El usuario procede a ingresar el nuevo número de celular y confirma su elección.</p><p>Inmediatamente después de confirmar, recibirá un mensaje de confirmación que dice: "Se ha vinculado exitosamente un número de celular adicional a su cuenta para mayor seguridad"</p><p>** </p>|**EP02**||
|**US03**|**Realizar reserva**|<p>**Como** usuario **quiero** reservar una entrevista en Lima.</p><p></p>|<p>**Escenario 1** El usuario reserva una entrevista con el horario que eligió</p><p>**Dado que** el usuario se encuentra en la aplicación, le sale una opción “Reservar entrevista“</p><p>**Cuando** el usuario presione el botón en “Reservar Entrevista“ le dará las opciones de elegir  el horario que quiere partir y las características de la Entrevista.</p><p>**Entonces** el usuario tendrá que seleccionar las que él requiera.</p><p></p><p>**Y** luego tendrá que pagar de manera electrónica la reserva.</p><p></p><p>**Y** rápidamente llegará un mensaje “Usted ha reservado una entrevista con el  siguiente horario”.</p><p></p>|**EP03**||
|**US04**|**Métodos de Pago**|**Como** usuario **quiero** realizar las transferencias con diferentes medios de pagos **para** poder reservar la entrevista en la aplicación.|<p>**Escenario 1.** El usuario quiere realizar pagos electrónicos.</p><p>**Dado que** el usuario quiere realizar los pagos por medio de tarjeta o algún otro medio.</p><p>**Cuando** ya terminó de seleccionar, le saldrá unas opciones para pagar con tarjeta de crédito u otro medio de pago.</p><p>**Entonces** el usuario tiene que llenar los datos si paga con tarjeta o si paga por otro medio</p><p></p><p>**Escenario 2:**</p><p>**Dado que** el usuario desea realizar el pago con tarjeta de crédito.</p><p>**Cuando** haya seleccionado la opción de pagar con tarjeta dentro de las opciones de pago disponibles.</p><p>**Entonces**, se le solicitará al usuario que llene los datos de su tarjeta, incluyendo el número de tarjeta, la fecha de vencimiento y el código de seguridad.</p><p>Una vez que el usuario haya ingresado los detalles de su tarjeta, deberá confirmar la transacción.</p><p>Después de confirmar, la aplicación procesará el pago y mostrará un mensaje de confirmación que indique que la transacción se ha completado con éxito.</p><p></p>|**EP04**||
|**US05**|**Visualización de calendario de entrevistas y anotaciones**|**Como** usuario de GetWork **Quiero** poder acceder a un calendario con mis entrevistas programadas y la capacidad de hacer anotaciones **Para** tener una visión clara de mis compromisos y preparación para entrevistas|<p>**Escenario 1:**<br>` `El usuario accede a su perfil en GetWork .<br>**Dado que** tengo entrevistas programadas **Cuando** navego a la sección de calendario **Entonces** veo un calendario con las fechas y horas de mis entrevistas junto con la capacidad de hacer anotaciones</p><p>**Escenario 2:** <br>El usuario desea agregar una nueva entrevista al calendario. <br>**Dado que** tengo una nueva entrevista programada **Cuando** selecciono la opción para agregar una nueva entrada al calendario **Entonces** puedo ingresar la fecha, hora y detalles de la entrevista y guardarla correctamente.</p><p></p><p></p><p></p>|**EP05**||
|**US06**|**Medio de comunicación**|**Como** usuario **quiero** visualizar en la aplicación **para** mantenerte al tanto de nuevas actualizaciones o alertas de cambios.|<p>**Escenario 1** El usuario es notificado sobre alguna actualización o advertencias.</p><p>**Dado que** se notifica al usuario sobre alguna actualización o advertencia sobre los cambios.</p><p>**Cuando** él está navegando en la aplicación o no.</p><p>**Entonces** podrá tomar medidas al respecto con anticipación.</p><p></p>|**EP07**||
|**US07**|**Interfaz sencilla**|**Como** usuario **quiero** una interfaz sencilla **para** poder reservar con facilidad la entrevista.|<p>**Escenario 1** El usuario quiere un interfaz muy sencilla en toda la aplicación </p><p>**Dado que** el usuario podrá visualizar y sea de su mayor agrado</p><p>**Cuando** se encuentre reservando la entrevista.</p><p>**Entonces** no tendrá problemas por la interfaz y seguirá con su reserva sin ningún inconveniente.</p>|**EP05**||
|**US08**|**Participación en GetWork Contest**|**Como** usuario de GetWork **quiero** poder participar en GetWork Contest y ver mi posición en el ranking **para** competir con otros usuarios y mejorar mis habilidades.|<p>**Escenario 1:** <br>El usuario accede a la sección GetWork Contest. <br>**Dado que** quiero participar en el concurso semanal **Cuando** selecciono la opción para unirse al concurso, entonces** puedo resolver los desafíos y mi puntuación se refleja en el ranking.</p><p>**Escenario 2:** <br>El usuario desea ver su posición en el ranking actual.<br>` `**Dado que** quiero conocer mi posición en el ranking **Cuando** accedo a la sección de ranking **Entonces** puedo ver mi posición actual junto con otros usuarios y sus puntuaciones.</p><p></p><p></p>|**EP06**||
|**US09**|**Visualizar la landing page de la empresa**|<p>**Como** usuario interesado en los productos/servicios de la empresa,</p><p></p><p>**Quiero** poder ver la landing page para obtener información relevante y</p><p><br>**Para que**</p><p>decidir si quiero registrarme o contactar a la empresa.</p>|<p>**Escenario 1:** Visualización exitosa de la landing page</p><p></p><p>**Dado que** soy un usuario interesado en los productos/servicios de la empresa.</p><p></p><p>**Cuando** ingreso a la landing page desde cualquier dispositivo.</p><p></p><p>**Entonces** veo claramente la estructura de la página con una barra de navegación y secciones principales.</p><p></p><p>**Escenario 2**: Error en la visualización de la landing page</p><p></p><p>**Dado que** soy un usuario interesado en los productos/servicios de la empresa.</p><p></p><p>**Cuando** intento acceder a la landing page desde un dispositivo y encuentro problemas de visualización.</p><p></p><p>**Entonces** informo el problema al equipo de soporte técnico para su pronta solución.</p><p></p><p></p>|**EP05**||
|**US10**|**Agregar sugerencias y/o comentarios**|**Como** usuario **quiero** realizar sugerencias/comentarios sobre la experiencia de la reserva **para** un mejor desarrollo de la aplicación y comentar algún inconveniente que tuve.|<p>**Escenario 1** El usuario manifiesta sus sugerencias en la sección de comentarios.</p><p>**Dado que** el usuario notará algún defecto en nuestra aplicación o una experiencia no agradable</p><p>**Cuando** haya experimentado la entrevista.</p><p>**Entonces** dejará en la sección de comentarios, sus sugerencias acerca de las mejoras que se podrían implementar o algún inconveniente que tuvo al momento de la entrevista.</p><p></p><p>**Escenario 2:** </p><p>**Dado que** el usuario ha completado una reserva y desea proporcionar comentarios o sugerencias para mejorar la experiencia de reserva en la aplicación.</p><p>**Cuando** haya finalizado la entrevista o la experiencia relacionada con la reserva.</p><p>**Entonces**, el usuario accederá a la sección de comentarios o sugerencias dentro de la aplicación.</p><p>Una vez allí, escribirá sus comentarios detallando cualquier defecto experimentado o cualquier </p><p></p><p></p>|**EP08**||
|**US11**|**Entrenamiento especializado en desarrollo de algoritmos**|**Como** usuario **quiero** acceder a cursos y ejercicios especializados en desarrollo de algoritmos **para** mejorar mi capacidad de resolver problemas complejos durante las entrevistas técnicas.|<p>**Escenario 1:**</p><p>**Dado** que un usuario ha intentado registrarse varias veces sin éxito debido a un problema técnico en la aplicación,</p><p>**Cuando** el usuario intenta registrarse nuevamente utilizando un correo electrónico diferente,</p><p>**Entonces** la aplicación debe reconocer el intento anterior y proporcionar una opción para verificar el correo electrónico anterior o continuar con el nuevo.</p><p></p><p>**Escenario 2:**</p><p>**Dado que** un usuario ha completado exitosamente un curso sobre algoritmos de búsqueda en la plataforma,</p><p>**Cuando** el usuario intenta aplicar los conceptos aprendidos en un ejercicio práctico proporcionado por la plataforma,</p><p>**Entonces** la aplicación evalúa la solución propuesta por el usuario y proporciona retroalimentación específica sobre la eficiencia y la lógica del algoritmo implementado.</p><p></p><p></p><p></p>|**EP09**||
|**US12**|**Práctica de simulacros de entrevistas técnicas**|**Como** usuario de GetWork **quiero** tener acceso a simulacros de entrevistas técnicas **para** poder practicar y mejorar mis habilidades de entrevista.|<p>**Escenario 1:** <br>El usuario accede a la sección de simulacros de entrevistas. <br>**Dado que** quiero practicar una entrevista técnica simulada **Cuando** seleccione una categoría de entrevista (por ejemplo, desarrollo web, algoritmos) **Entonces** se me presenta un conjunto de preguntas y problemas para resolver</p><p>Escenario 2: <br>El usuario desea recibir retroalimentación después de completar un simulacro de entrevista. <br>**Dado que** he completado un simulacro de entrevista técnica **Cuando** finalizó la sesión **Entonces** recibo retroalimentación sobre mi desempeño y áreas de mejora.</p><p></p><p></p><p></p>|**EP09**||
|**US13**|**Registrarse en la landing page**|<p>**Como** usuario interesado en los productos/servicios de la empresa,</p><p></p><p>**Quiero** poder registrarme en la landing page utilizando mi correo electrónico<br><br>**Para** acceder a funciones adicionales o recibir información relevante.</p>|<p>**Escenario 1**: Registro exitoso</p><p></p><p>**Dado que** soy un usuario interesado en los productos/servicios de la empresa y deseo registrarme en la landing page.</p><p></p><p>**Cuando** encuentro claramente la opción de registrarme y proporciono mi correo electrónico y otros datos necesarios.</p><p></p><p>**Entonces** recibo un mensaje de confirmación indicando que mi registro ha sido exitoso.</p><p></p><p>**Escenario 2:** Error en el registro</p><p></p><p>**Dado que** soy un usuario interesado en los productos/servicios de la empresa y deseo registrarme en la landing page.</p><p></p><p>**Cuando** intento registrarme pero encuentro un problema, como datos incorrectos o falta de conexión.</p><p></p><p>**Entonces** recibo un mensaje de error indicando el problema y me dan instrucciones sobre cómo solucionarlo.</p><p></p><p></p>|**EP01**||
|**US14**|**Entrenamiento en resolución de problemas de lógica**|<p>**Como** usuario **quiero** acceder a recursos y ejercicios de entrenamiento centrados en la resolución de problemas de lógica **para** mejorar mis habilidades de pensamiento crítico durante las entrevistas técnicas.</p><p></p>|<p>**Escenario 1:<br>Dado que** un usuario está realizando un pago utilizando una tarjeta de crédito, pero la transacción falla debido a problemas de conectividad o del servidor,</p><p>**Cuando** el usuario intenta realizar el pago nuevamente después de la falla,</p><p>**Entonces** la aplicación debe proporcionar una opción para reintentar el pago o seleccionar un método de pago alternativo para completar la reserva con éxito.</p><p></p><p>**Escenario 2:**</p><p>**Dado que** un usuario se encuentra trabajando en un acertijo de lógica proporcionado por la plataforma,</p><p>**Cuando** el usuario se queda atascado en una parte específica del problema,</p><p>**Entonces** la aplicación ofrece pistas adicionales para ayudar al usuario a avanzar en la resolución del acertijo sin revelar completamente la solución.</p><p></p>|**EP09**||
|**US15**|**Acceso a tutores especializados**|**Como** usuario de GetWork **quiero** tener acceso a tutores especializados con sus descripciones **para** recibir orientación personalizada y ayuda en mi preparación para entrevistas técnicas.|<p>**Escenario 1:** <br>El usuario accede a la sección de tutores en GetWork. <br>**Dado que** necesito ayuda con una pregunta específica o concepto técnico **Cuando** navego por la lista de tutores disponibles **Entonces** puedo ver información detallada sobre cada tutor, incluyendo su experiencia y áreas de especialización.</p><p>Escenario 2: <br>El usuario desea programar una sesión de tutoría con un tutor específico. <br>**Dado que** quiero recibir orientación personalizada en mi preparación para una entrevista técnica **Cuando** selecciono un tutor y veo su disponibilidad **Entonces** puedo programar una sesión de tutoría con el tutor deseado en un horario conveniente.</p><p></p>|**EP09**||
|**US16**|**Planificación de estudio personalizado**|**Como** usuario **quiero** tener acceso a una función de planificación de estudio personalizado que me permita establecer metas de aprendizaje, seguir mi progreso y recibir recomendaciones específicas de recursos basadas en mis necesidades individuales.|<p>**Escenario 1:**</p><p>**Dado que** un usuario ha establecido una meta específica de aprendizaje en la plataforma,</p><p>**Cuando** el usuario ingresa su disponibilidad de tiempo de estudio y áreas de enfoque preferidas,</p><p>**Entonces** la aplicación genera un plan de estudio personalizado que incluye recomendaciones de cursos, ejercicios y actividades que se ajustan a las necesidades y objetivos del usuario.</p><p>**Escenario 2:**</p><p>**Dado que** un usuario ha estado siguiendo su plan de estudio personalizado durante varias semanas,</p><p>**Cuando** el usuario realiza un seguimiento de su progreso y se da cuenta de que está luchando con un concepto particular,</p><p>**Entonces** la aplicación ajusta automáticamente el plan de estudio del usuario, proporcionando más recursos y ejercicios relacionados con el área problemática para reforzar su comprensión.</p><p></p><p></p>|**EP09**||
|**US17**|**Visualización de datos de usuario**|**Como** usuario de GetWork **quiero** poder ver y actualizar mis datos de perfil **para** mantener mi información actualizada y relevante en la plataforma.|<p>**Escenario 1:**<br>` `El usuario accede a la configuración de su perfil en GetWork <br>**Dado que** deseo actualizar mi información personal (nombre, correo electrónico, contraseña, etc.) **Cuando** accedo a la sección de configuración de perfil **Entonces** puedo ver mis datos actuales y realizar cambios según sea necesario.</p><p>**Escenario 2:** <br>El usuario desea ver un resumen de su actividad en la plataforma.<br>**Dado que** quiero tener una visión general de mi progreso y participación en GetWork **Cuando** accedo a la sección de estadísticas o resumen de actividad **Entonces** puedo ver datos como el número de simulacros de entrevistas realizados, desafíos completados, etc.</p><p></p><p></p><p></p>|**EP05**||
|**US18**|**Simulacros de entrevistas en grupo**|**Como** usuario **quiero** tener la oportunidad de participar en simulacros de entrevistas grupales donde pueda practicar habilidades de comunicación, trabajo en equipo y resolución de problemas en un entorno simulado similar a una entrevista técnica real.|<p>**Escenario 1:**</p><p>**Dado que** un grupo de usuarios se ha unido a un simulacro de entrevista en grupo organizado por la plataforma,</p><p>**Cuando** los participantes se dividen en equipos y reciben un caso de estudio para resolver en un tiempo determinado,</p><p>**Entonces** los usuarios practican la comunicación efectiva, la colaboración y la toma de decisiones bajo presión, recibiendo retroalimentación de los moderadores del evento al finalizar la simulación.</p><p>**Escenario 2:**</p><p>**Dado que** un usuario ha completado varios simulacros de entrevistas en grupo y ha demostrado un rendimiento excepcional,</p><p>**Cuando** el usuario es seleccionado para participar como moderador en futuros eventos de simulacro de entrevistas,</p><p>**Entonces** el usuario asume un papel de liderazgo, facilitando las discusiones del grupo y proporcionando retroalimentación constructiva a los participantes para mejorar su desempeño.</p><p></p><p></p>|**EP06**||
|**US19**|**Enviar consulta a través del formulario de contacto**|<p>**Como** usuario interesado en obtener más información sobre los productos/servicios de la empresa, </p><p></p><p>**Quiero** poder enviar una consulta a través del formulario de contacto en la landing page.</p><p></p><p>**Para** poder contactarme con la empresa cuando lo requira.</p>|<p>**Escenario 1:** Envío de consulta exitoso</p><p></p><p>**Dado** que soy un usuario interesado en los productos/servicios de la empresa y deseo enviar una consulta.</p><p></p><p>**Cuando** encuentro claramente la opción de contacto, ingreso mi nombre, correo electrónico, asunto y mensaje en el formulario.</p><p></p><p>**Entonces** envio el formulario y recibo una confirmación de que mi consulta había sido enviada con éxito.</p><p></p><p>**Escenario 2:** Error en el envío de consulta</p><p></p><p>**Dado que** soy un usuario interesado en los productos/servicios de la empresa y deseo enviar una consulta.</p><p></p><p>**Cuando** intento enviar la consulta pero encuentro un problema, como campos obligatorios incompletos o conexión a internet interrumpida.</p><p></p><p>**Entonces** recibo un mensaje de error indicando el problema y me dan instrucciones sobre cómo solucionarlo.</p><p></p>|**EP09**||
|**US20**|**Asesoramiento profesional y de carrera**|**Como** usuario **quiero** tener acceso a recursos y servicios de asesoramiento profesional y de carrera **para** que me ayuden a planificar mi trayectoria profesional, prepararse para entrevistas y tomar decisiones informadas sobre mi desarrollo profesional.|<p>**Escenario 1:**</p><p>**Dado que** un usuario ha completado una serie de cursos de preparación para entrevistas técnicas en la plataforma,</p><p>**Cuando** el usuario solicita una consulta de asesoramiento de carrera con un experto en desarrollo profesional,</p><p>**Entonces** el experto revisa el perfil del usuario, brinda orientación sobre las oportunidades laborales disponibles y sugiere estrategias para maximizar el potencial de empleabilidad del usuario en la industria tecnológica.</p><p>**Escenario 2:**</p><p>**Dado que** un usuario ha seguido las recomendaciones de desarrollo profesional proporcionadas por un asesor de carrera en la plataforma,</p><p>**Cuando** el usuario aplica con éxito a una oportunidad laboral y obtiene una oferta de trabajo deseada,</p><p>**Entonces** el usuario comparte su éxito en la comunidad, inspirando a otros a seguir el mismo camino y utilizar los recursos disponibles en la plataforma para avanzar en sus carreras profesionales.</p><p></p>|**EP09**||
|**US21**|**Ver testimonios de clientes en la landing page**|<p>**Como** usuario interesado en los productos/servicios de la empresa, </p><p></p><p>**quiero** poder ver testimonios de clientes satisfechos en la landing page</p><p></p><p>**para** obtener una mejor comprensión de la experiencia de otros usuarios con la empresa.</p>|<p>**Escenario 1:** Ver testimonios exitosamente</p><p></p><p>**Dado que** estoy en la landing page de la empresa y quiero ver los testimonios de clientes satisfechos.</p><p></p><p>**Cuando** accedo a la sección de testimonios.</p><p></p><p>**Entonces** veo una lista de testimonios con los nombres y experiencias de los clientes.</p><p></p><p>**Escenario 2:** Error al cargar testimonios</p><p></p><p>**Dado que** estoy en la landing page de la empresa y quiero ver los testimonios de clientes satisfechos.</p><p></p><p>**Cuando** accedo a la sección de testimonios.</p><p></p><p>**Pero** hay un problema técnico que impide la carga de los testimonios.</p><p></p><p>**Entonces** veo un mensaje de error indicando que no se pueden cargar los testimonios en este momento.</p><p></p><p></p>|**EP05**||
|**US22**|**Entrenamiento en resolución de problemas de codificación en tiempo real**|**Como** usuario **quiero** practicar la resolución de problemas de codificación en tiempo real con un temporizador **para** simular condiciones de entrevistas técnicas reales.|<p>**Escenario 1:**</p><p>**Dado que** un usuario inicia una sesión de entrenamiento en resolución de problemas de codificación en tiempo real en la plataforma,</p><p>**Cuando** comienza a resolver un problema específico,</p><p>**Entonces** la aplicación activa un temporizador para limitar el tiempo disponible para completar el problema y simular la presión de una entrevista técnica real.</p><p>**Escenario 2:**</p><p>**Dado que** un usuario está practicando la resolución de problemas de codificación en tiempo real en la plataforma y se enfrenta a dificultades para completar un problema dentro del límite de tiempo establecido,</p><p>**Cuando** el temporizador llega a cero antes de que el usuario termine de resolver el problema,</p><p>**Entonces** la aplicación ofrece una revisión detallada del problema junto con sugerencias para mejorar la eficiencia en la resolución de problemas bajo presión temporal.</p><p></p><p></p>|||
|**US23**|**Registrarse para obtener acceso exclusivo**|<p>**Como** usuario interesado en los productos/servicios de la empresa, </p><p></p><p>**Quiero** poder registrarme en la landing page utilizando un formulario de registro</p><p></p><p>**Para** acceder a funciones exclusivas o recibir beneficios adicionales.</p>|<p>**Escenario 1:** Registro exitoso</p><p></p><p>**Dado que** estoy en la landing page de la empresa y quiero registrarme para obtener acceso exclusivo.</p><p></p><p>**Cuando** ingreso mi correo electrónico y otros datos necesarios en el formulario de registro.</p><p></p><p>**Y** envío el formulario.</p><p></p><p>**Entonces** recibo una confirmación de que mi cuenta ha sido creada exitosamente.</p><p></p><p>**Escenario 2:** Error al registrar</p><p></p><p>**Dado que** estoy en la landing page de la empresa y quiero registrarme para obtener acceso exclusivo.</p><p></p><p>**Cuando** intento enviar el formulario de registro con información incorrecta o incompleta.</p><p></p><p>**Entonces** el sistema muestra un mensaje de error indicando que algunos campos están incorrectos o faltantes.</p><p></p><p></p>|**EP01**||
|**US24**|**Simulacros de entrevistas técnicas en diferentes formatos**|<p>**Como** usuario **quiero** participar en simulacros de entrevistas técnicas en diferentes formatos, como entrevistas telefónicas, entrevistas de codificación en vivo y entrevistas técnicas basadas en casos, **para** prepararse para una variedad de situaciones de entrevistas.</p><p></p>|<p>**Escenario 1:**</p><p>**Dado que** un usuario se une a un simulacro de entrevista técnica en formato de entrevista telefónica en la plataforma,</p><p>**Cuando** se le presenta un escenario técnico y se le pide que resuelva un problema de codificación verbalmente,</p><p>**Entonces** practica la comunicación efectiva de sus ideas y soluciones sin el soporte visual de un editor de código.</p><p></p><p>**Escenario 2:**</p><p>**Dado que** un usuario se une a un simulacro de entrevista técnica en formato de entrevista de codificación en vivo en la plataforma y experimenta problemas de conexión durante la sesión,</p><p>**Cuando** la conexión se restablece,</p><p>**Entonces** la aplicación ofrece la opción de reanudar la sesión desde el punto en que se interrumpió o comenzar nuevamente desde el principio, según la preferencia del usuario.</p><p></p>|**EP06**||
|<p>**US25**</p><p></p><p></p>|**Plataforma de práctica de diseño de sistemas**|<p>**Como** usuario **quiero** acceder a una plataforma donde pueda practicar el diseño de sistemas mediante la resolución de problemas de arquitectura, escalabilidad y manejo de datos.</p><p></p>|<p>**Escenario 1:**</p><p>**Dado que** un usuario accede a la sección de práctica de diseño de sistemas en la plataforma,</p><p>**Cuando** selecciona un problema de diseño específico, como la construcción de un sistema de gestión de pedidos en línea,</p><p>**Entonces** la aplicación proporciona una descripción del problema y herramientas para diagramar la arquitectura del sistema y proponer soluciones.</p><p></p><p>**Escenario 2:**</p><p>**Dado que** un usuario está trabajando en un problema de diseño de sistemas en la plataforma y tiene dificultades para visualizar la arquitectura propuesta,</p><p>**Cuando** solicita ayuda adicional,</p><p>**Entonces** la aplicación ofrece la opción de programar una sesión de tutoría en vivo con un experto en diseño de sistemas para obtener orientación personalizada sobre cómo abordar el problema específico.</p><p></p>|**EP09**||
|**US26**|**Entrevistas técnicas en vivo con expertos**|**Como** usuario **quiero** participar en entrevistas técnicas en vivo con expertos de la industria **para** recibir retroalimentación directa y consejos sobre mi desempeño.|<p>**Escenario 1:**</p><p>**Dado que** un usuario se une a una sesión de entrevista técnica en vivo con un experto en la plataforma,</p><p>**Cuando** responde a preguntas técnicas y resuelve problemas de codificación en tiempo real,</p><p>**Entonces** el experto proporciona retroalimentación inmediata sobre el enfoque del usuario, la eficiencia del código y las áreas de mejora.</p><p></p><p>**Escenario 2:**</p><p>**Dado que** un usuario se une a una sesión de entrevista técnica en vivo con un experto en la plataforma y experimenta una discrepancia en las expectativas sobre el problema técnico presentado,</p><p>**Cuando** el usuario solicita aclaraciones sobre los requisitos del problema,</p><p>**Entonces** el experto aclara las expectativas y proporciona orientación adicional para ayudar al usuario a abordar el problema de manera más efectiva.</p><p></p>|**EP06**||
|**US27**|**Preparación para entrevistas técnicas específicas de la industria**|**Como** usuario **quiero** acceder a recursos y entrenamiento específicos para prepararse para** entrevistas técnicas en áreas de la industria específicas, como inteligencia artificial, desarrollo móvil o ciberseguridad.|<p>**Escenario 1:**</p><p>**Dado que** un usuario está interesado en prepararse para una entrevista técnica en el campo de la inteligencia artificial,</p><p>**Cuando** accede a la sección de recursos específicos de la industria en la plataforma,</p><p>**Entonces** encuentra una colección de materiales de estudio, cursos y ejercicios centrados en temas relevantes para la inteligencia artificial, como aprendizaje automático y procesamiento de lenguaje natural.</p><p>**Escenario 2:**</p><p>**Dado que** un usuario se une a una sesión de entrevista técnica en vivo con un experto en la plataforma y experimenta una discrepancia en las expectativas sobre el problema técnico presentado,</p><p>**Cuando** el usuario solicita aclaraciones sobre los requisitos del problema,</p><p>**Entonces** el experto aclara las expectativas y proporciona orientación adicional para ayudar al usuario a abordar el problema de manera más efectiva.</p><p></p>|**EP09**||
|**US28**|**Ver testimonios de clientes en la landing page**|<p>**Como** usuario interesado en los productos/servicios de la empresa, </p><p></p><p>**Quiero** poder ver testimonios de clientes satisfechos en la landing page </p><p></p><p>**Para** obtener una mejor comprensión de la experiencia de otros usuarios con la empresa.</p><p></p>|<p>**Escenario 1:** Visualización de testimonios exitosa</p><p></p><p>**Dado que** soy un usuario interesado en los productos/servicios de la empresa y deseo ver testimonios de clientes.</p><p></p><p>**Cuando** accedo a la landing page y busco la sección de testimonios.</p><p></p><p>**Entonces** encuentro claramente la sección de testimonios y puedo ver los testimonios presentados de forma clara y ordenada, mostrando el nombre y la experiencia del cliente.</p><p></p><p>**Escenario 2:** Error al cargar testimonios</p><p></p><p>**Dado que** soy un usuario interesado en los productos/servicios de la empresa y deseo ver testimonios de clientes.</p><p></p><p>**Cuando** accedo a la landing page y busco la sección de testimonios.</p><p></p><p>**Pero** hay un problema técnico que impide la carga de los testimonios.</p><p></p><p>**Entonces** no puedo ver los testimonios y se muestra un mensaje de error indicando que no se pueden cargar los testimonios en este momento.</p><p></p>|**EP06**||
|**US29**|**Preparación para entrevistas técnicas de desarrollo web**|**Como** usuario **quiero** acceder a recursos y entrenamiento específicos para prepararse **para** entrevistas técnicas en desarrollo web, incluyendo tecnologías como HTML, CSS, JavaScript y frameworks populares como React y Angular.|<p>**Escenario 1:**</p><p>**Dado que** un usuario está buscando mejorar sus habilidades en el desarrollo web para entrevistas técnicas,</p><p>**Cuando** accede a la sección de preparación para entrevistas técnicas de desarrollo web en la plataforma,</p><p>**Entonces** encuentra una serie de cursos, ejercicios y proyectos prácticos que cubren los fundamentos y las tecnologías avanzadas del desarrollo web.</p><p></p><p>**Escenario 2:**</p><p>**Dado que** un usuario desea familiarizarse con proyectos prácticos relevantes para entrevistas técnicas de desarrollo web,</p><p>**Cuando** accede a la sección de proyectos prácticos en la plataforma,</p><p>**Entonces** encuentra una variedad de proyectos simulados que simulan situaciones reales de desarrollo web, como la creación de una aplicación de comercio electrónico o una aplicación de redes sociales, con guías paso a paso para completar cada proyecto.</p><p></p>|**EP09**||
|**US30**|**Evaluación de habilidades antes de la preparación**|**Como** usuario **quiero** realizar una evaluación inicial de mis habilidades técnicas para identificar las áreas de fortaleza y debilidad antes de comenzar mi preparación **para** entrevistas técnicas.|<p>**Escenario 1:**</p><p>**Dado que** un usuario está interesado en conocer su nivel de competencia técnica antes de comenzar su preparación,</p><p>**Cuando** accede a la sección de evaluación de habilidades en la plataforma,</p><p>**Entonces** completa una serie de pruebas que cubren diversos temas como algoritmos, estructuras de datos y desarrollo web, y recibe un informe detallado que destaca sus fortalezas y áreas de mejora.</p><p></p><p>**Escenario 2:**</p><p>**Dado que** un usuario ha completado una evaluación inicial de habilidades,</p><p>**Cuando** revisa el informe de resultados proporcionado por la plataforma,</p><p>**Entonces** la aplicación sugiere un plan de estudio personalizado basado en las áreas identificadas como áreas de mejora, proporcionando recomendaciones específicas de recursos y cursos para abordar esas áreas débiles.</p><p></p>|**EP01**||


**Technical User Stories**

|**Technical story ID**|**Título**|**Descripción**|**Escenario**|
| :- | :- | :- | :- |
|TS01|Registrar Usuario|**Como** desarrollador que trabaja en la aplicación de CodePace **Quiero** poder registrar a un nuevo usuario mediante una API <br>**Para** permitir que los usuarios se inscriban en nuestra plataforma y accedan a nuestros recursos de preparación para entrevistas técnicas.|**Dado que** el usuario proporciona información válida de registro **Cuando** se envía una solicitud POST a /api/users con los detalles del usuario **Entonces** la API responde con un código de estado 201 (Created) Y el cuerpo de la respuesta contiene los detalles del usuario recién registrado|
|TS02|Iniciar Sesión de Usuario|**Como** desarrollador que trabaja en la aplicación de CodePace **Quiero** proporcionar una API para que los usuarios inicien sesión en sus cuentas **Para** permitirles acceder a su contenido personalizado y continuar con sus actividades de preparación para entrevistas técnicas|**Dado que** el usuario proporciona credenciales de inicio de sesión válidas **Cuando** se envía una solicitud POST a /api/login con las credenciales del usuario **Entonces** la API responde con un código de estado 200 (OK) Y el cuerpo de la respuesta contiene un token de autenticación válido para el usuario|
|TS03|Obtener Detalles del Usuario|**Como** desarrollador que trabaja en la aplicación de CodePace <br>**Quiero** proporcionar una API<br>` `**para** que los usuarios recuperen sus detalles de perfil Para que puedan ver y actualizar su información personal cuando sea necesario|**Dado que** el usuario proporciona un token de autenticación válido **Cuando** se envía una solicitud GET a /api/profile con el token de autenticación **Entonces** la API responde con un código de estado 200 (OK) Y el cuerpo de la respuesta contiene los detalles del perfil del usuario|
|TS04|Actualizar Detalles del Usuario|**Como** desarrollador que trabaja en la aplicación de CodePace <br>**Quiero** proporcionar una API<br>` `**para** que los usuarios actualicen su información de perfil Para que puedan mantener sus datos personales actualizados en nuestra plataforma|**Dado que** el usuario proporciona un token de autenticación válido y los nuevos detalles del perfil **Cuando** se envía una solicitud PUT a /api/profile con el token de autenticación y los nuevos detalles **Entonces** la API responde con un código de estado 200 (OK) Y el cuerpo de la respuesta contiene los detalles actualizados del perfil del usuario|
|TS05|Cerrar Sesión de Usuario|**Como** desarrollador que trabaja en la aplicación de CodePace <br>**Quiero** proporcionar una API para que los usuarios cierren sesión en sus cuentas<br>` `**Para** garantizar la seguridad y la privacidad de sus datos cuando finalicen su sesión en la plataforma|**Dado que** el usuario proporciona un token de autenticación válido **Cuando** se envía una solicitud DELETE a /api/logout con el token de autenticación **Entonces** la API responde con un código de estado 204 (No Content) Y el usuario es desconectado exitosamente de su sesión en la plataforma|
|<p>TS06</p><p></p>|Recuperar Contraseña Olvidada|**Como** desarrollador que trabaja en la aplicación de CodePace <br>**Quiero** proporcionar una API<br>` `**para** que los usuarios puedan restablecer su contraseña en caso de olvidarla Para permitir que los usuarios recuperen el acceso a sus cuentas en caso de olvidar su contraseña|**Dado que** el usuario proporciona su correo electrónico registrado **Cuando** se envía una solicitud POST a /api/reset-password con el correo electrónico del usuario **Entonces** la API responde con un código de estado 200 (OK) Y se envía un correo electrónico al usuario con un enlace para restablecer su contraseña|
|TS07|Verificar Correo Electrónico|**Como** desarrollador que trabaja en la aplicación de CodePace <br>**Quiero** proporcionar una API<br>` `**para** que los usuarios puedan verificar su dirección de correo electrónico después del registro Para garantizar la autenticidad de las cuentas de usuario en nuestra plataforma|**Dado que** el usuario proporciona un token de verificación válido **Cuando** se envía una solicitud POST a /api/verify-email con el token de verificación del usuario **Entonces** la API responde con un código de estado 200 (OK) Y la cuenta de usuario se marca como verificada en nuestra base de datos|
|TS08|Recuperar Preguntas de Entrevista|**Como** desarrollador que trabaja en la aplicación de CodePace <br>**Quiero** proporcionar una API <br>**para** que los usuarios puedan recuperar preguntas de entrevista técnicas Para ayudar a los usuarios en su preparación para entrevistas técnicas|**Dado que** el usuario proporciona un token de autenticación válido **Cuando** se envía una solicitud GET a /api/interview-questions con el token de autenticación del usuario **Entonces** la API responde con un código de estado 200 (OK) Y el cuerpo de la respuesta contiene una lista de preguntas de entrevista técnica|
|TS09|Registrar Actividad de Usuario|**Como** desarrollador que trabaja en la aplicación de CodePace **Quiero** proporcionar una API **para** que podamos registrar la actividad de los usuarios en la plataforma Para analizar el compromiso de los usuarios y mejorar la experiencia del usuario|**Dado que** se realiza una acción por parte del usuario en la plataforma **Cuando** se envía una solicitud POST a /api/activity-log con los detalles de la acción y el token de autenticación del usuario **Entonces** la API responde con un código de estado 201 (Created) Y la actividad del usuario se registra correctamente en nuestra base de datos|
|TS10|Eliminar Cuenta de Usuario|**Como** desarrollador que trabaja en la aplicación de CodePace <br>**Quiero** proporcionar una API<br>` `**para** que los usuarios puedan eliminar permanentemente sus cuentas Para permitir a los usuarios retirarse completamente de nuestra plataforma si así lo desean|**Dado que** el usuario confirma su intención de eliminar su cuenta **Cuando** se envía una solicitud DELETE a /api/delete-account con el token de autenticación del usuario y la confirmación de eliminación **Entonces** la API responde con un código de estado 204 (No Content) Y la cuenta de usuario se elimina permanentemente de nuestra base de datos|



**3.3. Impact Mapping**

Segmento objetivo #1: Desarrolladores en búsqueda de empleo

![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/45040204-0233-4b19-ab5f-a447ac95f3a2)


Segmento objetivo #2: Estudiantes de informática y carreras relacionadas

![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/73a4794a-efe6-4ace-a82f-8e4a0327eded)


**3.4. Product Backlog**

|**# Orden**|**User Story Id**|**Título**|**Descripción** |**Story Point ( 1 / 2 / 3 / 5 / 8)** |
| :- | :- | :- | :- | :- |
|**1**|**US01**|**Variedad de idioamas**|**Como** usuario **quiero** que la aplicación esté disponible al menos en idioma inglés o español **para** que alguien que solo sepa inglés y no sólo español.|**2**|
|**2**|**US12**|**Práctica de simulacros de entrevistas técnicas**|**Como** usuario de GetWork **quiero** tener acceso a simulacros de entrevistas técnicas **para** poder practicar y mejorar mis habilidades de entrevista.|**2**|
|**3**|**US17**|**Visualización de datos de usuario**|**Como** usuario de GetWork **quiero** poder ver y actualizar mis datos de perfil **para** mantener mi información actualizada y relevante en la plataforma.|**2**|
|**4**|**US21**|**Ver testimonios de clientes en la landing page**|<p>**Como** usuario interesado en los productos/servicios de la empresa, </p><p></p><p>**quiero** poder ver testimonios de clientes satisfechos en la landing page</p><p></p><p>**para** obtener una mejor comprensión de la experiencia de otros usuarios con la empresa.</p>|**2**|
|**5**|**US11**|**Entrenamiento especializado en desarrollo de algoritmos**|**Como** usuario **quiero** acceder a cursos y ejercicios especializados en desarrollo de algoritmos **para** mejorar mi capacidad de resolver problemas complejos durante las entrevistas técnicas.|**2**|
|**6**|**US24**|**Simulacros de entrevistas técnicas en diferentes formatos**|<p>**Como** usuario **quiero** participar en simulacros de entrevistas técnicas en diferentes formatos, como entrevistas telefónicas, entrevistas de codificación en vivo y entrevistas técnicas basadas en casos, **para** prepararse para una variedad de situaciones de entrevistas.</p><p></p>|**2**|
|**7**|**US30**|**Evaluación de habilidades antes de la preparación**|**Como** usuario **quiero** realizar una evaluación inicial de mis habilidades técnicas para identificar las áreas de fortaleza y debilidad antes de comenzar mi preparación **para** entrevistas técnicas.|**2**|
|**8**|**US05**|**Visualización de calendario de entrevistas y anotaciones**|**Como** usuario de GetWork **Quiero** poder acceder a un calendario con mis entrevistas programadas y la capacidad de hacer anotaciones **Para** tener una visión clara de mis compromisos y preparación para entrevistas|**3**|
|**9**|**US07**|**Interfaz sencilla**|**Como** usuario **quiero** una interfaz sencilla **para** poder reservar con facilidad la entrevista.|**3**|
|**10**|**US08**|**Participación en GetWork Contest**|**Como** usuario de GetWork **quiero** poder participar en GetWork Contest y ver mi posición en el ranking **para** competir con otros usuarios y mejorar mis habilidades.|**3**|
|**11**|**US19**|**Enviar consulta a través del formulario de contacto**|<p>**Como** usuario interesado en obtener más información sobre los productos/servicios de la empresa, </p><p></p><p>**Quiero** poder enviar una consulta a través del formulario de contacto en la landing page.</p><p></p><p>**Para** poder contactarme con la empresa cuando lo requira.</p>|**3**|
|<p>**12**</p><p></p>|**US26**|**Entrevistas técnicas en vivo con expertos**|**Como** usuario **quiero** participar en entrevistas técnicas en vivo con expertos de la industria **para** recibir retroalimentación directa y consejos sobre mi desempeño.|**3**|
|**13**|**US28**|**Ver testimonios de clientes en la landing page**|<p>**Como** usuario interesado en los productos/servicios de la empresa, </p><p></p><p>**Quiero** poder ver testimonios de clientes satisfechos en la landing page </p><p></p><p>**Para** obtener una mejor comprensión de la experiencia de otros usuarios con la empresa.</p><p></p>|**3**|
|**14**|**US02**|**Seguridad de cuenta**|<p>**Como** usuario **quiero** vincular un número de celular adicional **para** que en caso pierda la cuenta principal pueda recuperarlo con este.</p><p></p>|**5**|
|**15**|**US04**|**Métodos de Pago**|**Como** usuario **quiero** realizar las transferencias con diferentes medios de pagos **para** poder reservar la entrevista en la aplicación.|**5**|
|**16**|**US06**|**Medio de comunicación**|**Como** usuario **quiero** visualizar en la aplicación **para** mantenerte al tanto de nuevas actualizaciones o alertas de cambios.|**5**|
|**17**|**US09**|**Visualizar la landing page de la empresa**|<p>**Como** usuario interesado en los productos/servicios de la empresa,</p><p></p><p>**Quiero** poder ver la landing page para obtener información relevante y</p><p><br>**Para que**</p><p>decidir si quiero registrarme o contactar a la empresa.</p>|**5**|
|**18**|**US13**|**Registrarse en la landing page**|<p>**Como** usuario interesado en los productos/servicios de la empresa,</p><p></p><p>**Quiero** poder registrarme en la landing page utilizando mi correo electrónico<br><br>**Para** acceder a funciones adicionales o recibir información relevante.</p>|**5**|
|**19**|**US14**|**Entrenamiento en resolución de problemas de lógica**|<p>**Como** usuario **quiero** acceder a recursos y ejercicios de entrenamiento centrados en la resolución de problemas de lógica **para** mejorar mis habilidades de pensamiento crítico durante las entrevistas técnicas.</p><p></p>|**5**|
|**20**|**US23**|**Registrarse para obtener acceso exclusivo**|<p>**Como** usuario interesado en los productos/servicios de la empresa, </p><p></p><p>**Quiero** poder registrarme en la landing page utilizando un formulario de registro</p><p></p><p>**Para** acceder a funciones exclusivas o recibir beneficios adicionales.</p>|**5**|
|**21**|**US03**|**Realizar reserva**|<p>**Como** usuario **quiero** reservar una entrevista en Lima.</p><p></p>|**5**|
|**22**|**US10**|**Agregar sugerencias y/o comentarios**|**Como** usuario **quiero** realizar sugerencias/comentarios sobre la experiencia de la reserva **para** un mejor desarrollo de la aplicación y comentar algún inconveniente que tuve.|**5**|
|**23**|**US18**|**Simulacros de entrevistas en grupo**|**Como** usuario **quiero** tener la oportunidad de participar en simulacros de entrevistas grupales donde pueda practicar habilidades de comunicación, trabajo en equipo y resolución de problemas en un entorno simulado similar a una entrevista técnica real.|**5**|
|**24**|**US29**|**Preparación para entrevistas técnicas de desarrollo web**|**Como** usuario **quiero** acceder a recursos y entrenamiento específicos para prepararse **para** entrevistas técnicas en desarrollo web, incluyendo tecnologías como HTML, CSS, JavaScript y frameworks populares como React y Angular.|**5**|
|**25**|**US15**|**Acceso a tutores especializados**|**Como** usuario de GetWork **quiero** tener acceso a tutores especializados con sus descripciones **para** recibir orientación personalizada y ayuda en mi preparación para entrevistas técnicas.|**5**|
|**26**|**US22**|**Entrenamiento en resolución de problemas de codificación en tiempo real**|**Como** usuario **quiero** practicar la resolución de problemas de codificación en tiempo real con un temporizador **para** simular condiciones de entrevistas técnicas reales.|**5**|
|**27**|**US25**|**Plataforma de práctica de diseño de sistemas**|<p>**Como** usuario **quiero** acceder a una plataforma donde pueda practicar el diseño de sistemas mediante la resolución de problemas de arquitectura, escalabilidad y manejo de datos.</p><p></p>|**5**|
|**28**|**US16**|**Planificación de estudio personalizado**|**Como** usuario **quiero** tener acceso a una función de planificación de estudio personalizado que me permita establecer metas de aprendizaje, seguir mi progreso y recibir recomendaciones específicas de recursos basadas en mis necesidades individuales.|**5**|
|**29**|**US20**|**Asesoramiento profesional y de carrera**|**Como** usuario **quiero** tener acceso a recursos y servicios de asesoramiento profesional y de carrera **para** que me ayuden a planificar mi trayectoria profesional, prepararse para entrevistas y tomar decisiones informadas sobre mi desarrollo profesional.|**8**|
|**30**|**US27**|**Preparación para entrevistas técnicas específicas de la industria**|**Como** usuario **quiero** acceder a recursos y entrenamiento específicos para prepararse para** entrevistas técnicas en áreas de la industria específicas, como inteligencia artificial, desarrollo móvil o ciberseguridad.|**8**|

Link en Pivotal Tracker: [Ver enlace]("https://www.pivotaltracker.com/n/projects/2700961")

### Capítulo IV: Product Design
**4.1. Style Guidelines**
  - 4.1.1. General Style Guidelines
    
    **Paleta de colores:** Nuestra aplicación web y landing page, al estar dirigida a desarrolladores y estudiantes, cuenta con colores que denoten confianza, sean sobrios y formales,        por lo     que los colores principales que usaremos para GetWorkserán el blanco, Rojo, el negro y el gris. El blanco en representación del orden y limpieza, el azul la tranquilidad y     relajación      y el gris para la seriedad y modestia. El color principal de las letras será el negro para la formalidad pero también usaremos letras en color blano para un buen          contraste con el          fondo en donde se encuentra.

    ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/bd62e087-a892-49b5-adb1-1bcffdb070ad)
    
    **Tipografía:** La tipografía de nuestra aplicación será fácilmente legible y estética, por lo que se hará uso de la fuente Roboto para botones y títulos y Asap para textos, con          interlineado 1.15 con tamaño base 18px para desktop y para móvil tamaño 16px, no obstante, decidimos hacer uso de la unidad de medida “em” para que las letras sean escalables y           responsivas a la variedad de tamaños de pantalla. Los tamaños variarán según si son títulos principales, subtítulos o textos.

    - Base: 18px
    
    - Fuente principal: "Roboto", que es una fuente sans-serif.
    
    - Se establecen varios tamaños de texto para diferentes elementos:
    
    - Tamaño de encabezado 1: 2.5 rem.
    
    - Tamaño de encabezado 2: 2 rem.
    
    - Tamaño de encabezado 3: 1.5 rem.
    
    - Tamaño de encabezado 4: 1.125 rem.
    
    - Tamaño de párrafo: 1 rem.
    
    - Tamaño de texto pequeño: 0.875 rem.
    
    Estos ajustes de tamaño de texto proporcionan coherencia en el diseño y la presentación de la página web. La fuente "Roboto" es ampliamente utilizada por su      legibilidad y versatilidad, lo que la hace adecuada para una variedad de contextos en el diseño web.

    ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/52cdc829-e776-497a-b2c5-06ddda625f2f)

    **Misión:**
    Revolucionar la preparación para entrevistas técnicas ofreciendo una plataforma integral que equipa a los programadores con las herramientas, conocimientos y     confianza necesarios para lograr el éxito.
    
    **Visión:**
    En el lapso de los próximos tres años, Getwork aspira a consolidarse como la plataforma líder y de referencia en el mercado para la preparación de                entrevistas técnicas, siendo reconocida por su enfoque innovador, sostenibilidad y compromiso con la calidad y el éxito de sus usuarios.
    
    **Brand Name:**
    El nombre "Getwork" se deriva de la idea de obtener (get) trabajo (work), enfocándose en el objetivo final de los usuarios: asegurar una posición en el campo     de la tecnología. Este nombre refleja directamente la misión y los valores de la plataforma, haciendo énfasis en la acción y los resultados concretos.

    ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/c1be0b9b-36e2-40d8-83ae-8f0dc9a30717)


**4.1.2. Web Style Guidelines**


  La plataforma Getwork ofrecería recursos y entrenamiento crucial para
programadores y desarrolladores que buscan prepararse para entrevistas
técnicas en el sector tecnológico. Su diseño web debe reflejar la
claridad, accesibilidad y la relevancia del contenido para los usuarios
aspirantes a roles técnicos.

**Tarjetas de Servicios**

Preguntas Frecuentes de Entrevistas: Tarjetas que enumeran preguntas
comunes en entrevistas técnicas, con respuestas detalladas y consejos
para responder adecuadamente.

Ejercicios de Codificación Práctica: Presentación de desafíos de
codificación para practicar, con niveles de dificultad variados y
soluciones disponibles para miembros premium.

Simulacros de Entrevistas en Vivo: Información sobre cómo participar en
simulacros de entrevistas con expertos, incluyendo detalles sobre la
reserva de sesiones y temas cubiertos.

Tutoriales sobre Temas Comunes de Entrevistas: Acceso a tutoriales que
cubren áreas clave frecuentes en entrevistas técnicas, desde estructuras
de datos hasta algoritmos complejos.

![image79](https://github.com/CodepaceOrganization/Informes/assets/133830443/2b90a28b-5e45-4550-8187-a46d4b81db7f)
  
![image48](https://github.com/CodepaceOrganization/Informes/assets/133830443/0c3ff570-f5e2-4006-85f5-35a56498600a)

![image41](https://github.com/CodepaceOrganization/Informes/assets/133830443/862e6b68-4c9a-460a-bd09-3058b551a28f)

**Imágenes**

Imágenes descriptivas y motivacionales: Utilizar imágenes que reflejen
el ambiente de una entrevista de trabajo técnica, así como la
satisfacción de superar desafíos de codificación.

Representación Visual de Servicios: Imágenes que simbolizan cada uno de
los servicios principales, ayudando a la identificación rápida por parte
del usuario.  
  
![image61](https://github.com/CodepaceOrganization/Informes/assets/133830443/e2b89f50-cbc8-4c75-9a18-2c6562ff87f2)
![image30](https://github.com/CodepaceOrganization/Informes/assets/133830443/560792d4-43b1-488e-8d50-04e088c54b4e)
![image58](https://github.com/CodepaceOrganization/Informes/assets/133830443/e3d860c7-0f2a-4945-aa4a-4be6c1d18e37)

**Botones**

Acciones decisivas: Botones situados estratégicamente para fomentar la
inscripción a la plataforma, participación en ejercicios y simulacros, y
acceso a contenido premium.

Estilo y color distintivo: Los botones diseñados para resaltar y
provocar acciones positivas (ej., verde para continuar o confirmar) y
precaución (ej., rojo para cancelaciones o advertencias).

![image43](https://github.com/CodepaceOrganization/Informes/assets/133830443/5724ccf1-98b3-4abe-8412-0cf99e3abfea)

![image46](https://github.com/CodepaceOrganization/Informes/assets/133830443/4c2ab3cd-4f26-4bad-9d6f-2594ac9146be)

**Formularios**

**Organización de Contenido:** Uso de formularios para estructurar
listas de recursos disponibles, ejercicios por dificultad, y horarios
para simulacros de entrevistas, facilitando la visualización y selección
por parte de los usuarios.

![image57](https://github.com/CodepaceOrganization/Informes/assets/133830443/af434b00-d053-4b24-80dd-6352eb625b23)

![image4](https://github.com/CodepaceOrganization/Informes/assets/133830443/df5aa401-d1e7-45e7-a729-f91f6acd85f2)

**4.2. Information Architecture**

**Página de inicio:**

- Contenido Especializado: Encuentra artículos y guías sobre preparación para entrevistas técnicas en GetWork. Obtén consejos sobre cómo abordar preguntas comunes, mejorar tus habilidades de codificación y navegar por el proceso de entrevista técnica.

- Registro/Inicio de Sesión: Regístrate ahora o inicia sesión para comenzar a explorar la plataforma de GetWork y acceder a todas las funciones disponibles. Únete a nuestra comunidad comprometida con la preparación para entrevistas técnicas y el crecimiento profesional.

**Recursos y Entrenamiento:**

- Una sección donde los usuarios pueden acceder a una variedad de recursos diseñados para ayudarlos a prepararse para entrevistas técnicas. Esto incluirá preguntas frecuentes de entrevistas, ejercicios de codificación práctica, simulacros de entrevistas en vivo con expertos y tutoriales sobre temas comunes de entrevistas en empresas de tecnología.

**Blog:** 

- Un espacio donde los usuarios pueden encontrar artículos informativos y útiles relacionados con la preparación para entrevistas técnicas. Nuestro blog incluirá publicaciones sobre consejos de entrevistas, tendencias en la industria tecnológica, perfiles de empresas de tecnología y entrevistas con profesionales del sector.

**Preguntas Frecuentes:** 

- Una sección dedicada a proporcionar respuestas claras y completas a preguntas comunes sobre GetWork y el proceso de preparación para entrevistas técnicas. Aquí, los usuarios encontrarán información sobre cómo funciona la plataforma, cómo acceder a los recursos disponibles y cómo aprovechar al máximo su experiencia de preparación para entrevistas técnicas con GetWork.

**Cuenta de usuario:**

- Recursos Complejos: Desde preguntas frecuentes de entrevistas hasta ejercicios de codificación práctica, ofrecemos una amplia gama de recursos para que los usuarios se preparen adecuadamente.

- Simulacros de Entrevistas en Vivo: Nada supera la práctica real. Ofrecemos simulacros de entrevistas en vivo con expertos para que los usuarios se familiaricen con el ambiente de una entrevista técnica real.

- Colaboración con Empresas de Tecnología: Trabajamos en estrecha colaboración con empresas de tecnología para ofrecer contenido exclusivo y oportunidades de reclutamiento para los usuarios de nuestra plataforma.

- Membresías Premium: Para aquellos que buscan un nivel adicional de preparación, ofrecemos membresías premium que brindan acceso a contenido exclusivo, sesiones de tutoría personalizada y garantías de devolución de dinero para aquellos que no logren resultados satisfactorios en sus entrevistas.

**Declaración de misión:**

- Getwork se dedica a revolucionar el espacio de preparación laboral al
proporcionar una plataforma integral que ayuda a los programadores a
tener éxito en sus entrevistas técnicas y conseguir los trabajos de sus
sueños.

**Declaración de visión:**

- Nuestra visión es convertirnos en la plataforma de referencia para
programadores y empresas de tecnología de todo el mundo, proporcionando
un proceso ágil y eficaz para la preparación y contratación de puestos
de trabajo.

**Valores fundamentales:**

- Empatía: Priorizar las necesidades e inquietudes de los usuarios y
clientes.

- Innovación: Buscar continuamente nuevas y mejores formas de resolver
problemas y mejorar la plataforma.

- Integridad: Actuar siempre con honestidad, transparencia y
comportamiento ético en todas nuestras interacciones.

- Experiencia de usuario: céntrese en brindar una experiencia de usuario
excepcional que supere las expectativas.

**Indicadores clave de rendimiento:**

- Crecimiento de usuarios: usuarios activos mensuales y tasa de
adquisición de nuevos usuarios.

- Satisfacción del cliente: comentarios de los usuarios y calificaciones
de satisfacción.

- Crecimiento de ingresos: Crecimiento de ingresos mensuales y anuales.

**Gestión de Proyectos:**

- Planificación de proyectos: Definir el alcance, los objetivos, los
cronogramas y las tareas del proyecto.

- Asignación de tareas: Asignar las tareas específicas a los miembros del
equipo en función de sus fortalezas y experiencia.

- Seguimiento del proyecto: Supervisar el progreso y ajuste las tareas
según sea necesario.

Informes del proyecto: Proporcionar actualizaciones periódicas a las
partes interesadas sobre el estado, el progreso y los resultados del
proyecto.

- 4.2.2. Labeling Systems

En GetWork, hemos implementado sistemas de etiquetado para mejorar la experiencia del usuario y facilitar la navegación dentro de la plataforma. Estas etiquetas están presentes en diferentes partes de la aplicación, proporcionando una descripción clara y concisa del contenido de cada sección.

Panel de Control: Cada sección del panel de control está asociada con etiquetas que resumen el contenido disponible. Esto ayuda a los usuarios a comprender rápidamente qué pueden encontrar en cada área y facilita la navegación hacia la información relevante.

Tarjetas y Navegación: Además, todas las tarjetas presentadas en la plataforma incluyen títulos descriptivos para que los usuarios puedan identificar fácilmente el contenido que están visualizando. En la barra de navegación, las etiquetas proporcionan una breve explicación del contenido de cada sección, como "Empleos: Encuentra y solicita ofertas de trabajo", "Candidatos: Administra tu proceso de búsqueda y solicitud de empleo", "Empleadores: Publica ofertas de trabajo y gestiona tu proceso de contratación".

- 4.2.3. SEO Tags and Meta Tags
  
Metadatos o meta tags en HTML son etiquetas invisiblemente introducidas
en un documento HTML para proporcionar información relevante a los
navegadores y motores de búsqueda sobre la contenida y el estructura de
una página web. Estas etiquetas no están visibles para los usuarios pero
sirven para mejorar la comprensión y el análisis de los archivos HTML,
facilitando la gestión del contenido de una página web.

Las meta etiquetas que usaremos:

**Title**

Técnicamente hablando, <span class="mark">este</span> no es una
metaetiqueta, sino una etiqueta HTML que sirve como elemento obligatorio
en el encabezado de un documento HTML. Sin embargo, debido a su función
de interacción con los agentes de usuario, a menudo se menciona como
parte de los metadatos. Como elemento de encabezado, generalmente
aparece encima de todas las demás etiquetas del documento.

\<title\>Welcome to Getwork\</title\>

**Codificación de caracteres**

Si la codificación de caracteres no está definida en el encabezado HTTP,
es necesario definirla en el propio documento HTML utilizando la
etiqueta \<meta\>. Esto se hace para garantizar que los caracteres
especiales como la tilde (~) o el acento grave (é) se muestren
correctamente. La etiqueta \<meta\> que usaremos es la siguiente:

\<meta http-equiv="Content-Type" content="text/html; charset=UTF-8" /\>

**Description**  
La metaetiqueta description proporciona un breve resumen del contenido
de una página web, que se muestra como un fragmento en motores de
búsqueda como Google o Bing. Esta información es crucial ya que influye
en la decisión del usuario de elegir el mejor resultado de búsqueda que
coincida con su consulta. Dado que desempeña un papel central en la
optimización de la clasificación de los motores de búsqueda, esta
metaetiqueta se considera una de las más importantes para mejorar la
visibilidad y relevancia de una página web en los resultados de
búsqueda.

\<meta name="description" content="Getwork is a platform that offers
resources and training to help programmers prepare for technical
interviews at technology companies."/\>

**Keywords**

Con esta metaetiqueta, los administradores pueden definir palabras clave
para el motor de búsqueda. Las palabras clave son los criterios que
utiliza un motor de búsqueda para ofrecer al usuario páginas HTML como
respuesta, donde dichas palabras clave forman parte de las
metaetiquetas.

\<meta name="keywords" content="process, management, application,
records"/\>

**Autor y copyright**

Estas dos metaetiquetas, que son opcionales desde un punto de vista
legal, permiten hacer referencia al diseñador de un sitio web y al
propietario de los derechos del código fuente de una página HTML.

\<meta name="author" content="Codepace" /\>

\<meta name="copyright" content="Copyright Codepace team" /\>

- 4.2.4. Searching Systems

Filtro de fecha: los usuarios pueden buscar registros según la fecha en
que se registraron.

Filtro de fase: los usuarios pueden buscar registros según la fase en la
que se encuentran.

Filtro de autor: los usuarios pueden buscar registros según el autor del
registro.

Filtro de historial general: los usuarios pueden buscar registros según
varios criterios, como fecha, fase y autor.

Búsqueda de empleados: El sistema de búsqueda también estará presente en
la visualización de empleados.

Al implementar estos sistemas de búsqueda, los usuarios podrán encontrar
fácil y rápidamente la información que necesitan dentro de la aplicación
"Getwork". Esto les ayudará a gestionar y realizar un seguimiento eficaz
de sus contrataciones y a tomar decisiones informadas basadas en los
datos proporcionados.

- 4.2.5. Navigation Systems

Los principales sistemas de navegación en Getwork son los menús superior
e inferior. Estas etiquetas ayudan a los usuarios a navegar por las
secciones que desean ver dentro de la página. Si no se utilizan enlaces,
el usuario verá la página en orden descendente. En la aplicación, los
usuarios navegan por los recursos y la formación que ofrece Getwork para
prepararse para entrevistas técnicas en empresas de tecnología. Los
botones también representan la apertura, confirmación o finalización de
un registro y permiten a los usuarios seguir el proceso en una nueva
pantalla.

- 4.3. Landing Page UI Design
  - 4.3.1. Landing Page Wireframe
  **Landing Page para Desktop Web Browser**

![image40](https://github.com/CodepaceOrganization/Informes/assets/133830443/d06c68be-d5cf-4109-b4d6-4f14f91e25ea)

![image65](https://github.com/CodepaceOrganization/Informes/assets/133830443/0ecc5f77-f69b-4674-935f-53515a607720)

**Landing Page para Mobile Web Browser**

![image67](https://github.com/CodepaceOrganization/Informes/assets/133830443/e63ea6ad-0dcb-49aa-aee7-239e0537adf8)
![image32](https://github.com/CodepaceOrganization/Informes/assets/133830443/cb12a0ce-0e03-42b8-a66e-9de4438ceb33)
![image2](https://github.com/CodepaceOrganization/Informes/assets/133830443/931c1d4b-1e05-4986-b857-424521fc38f4)

![image56](https://github.com/CodepaceOrganization/Informes/assets/133830443/9c2cdc10-7100-4276-8ed6-dd72f87476e3)
![image59](https://github.com/CodepaceOrganization/Informes/assets/133830443/197dded9-4b8e-4fe8-8d15-78b1f0c4f2ca)
![image56](https://github.com/CodepaceOrganization/Informes/assets/133830443/9c2cdc10-7100-4276-8ed6-dd72f87476e3)

![image47](https://github.com/CodepaceOrganization/Informes/assets/133830443/12674a09-a40d-426c-b632-23476ba9226e)
![image49](https://github.com/CodepaceOrganization/Informes/assets/133830443/68a6c50f-ec8f-4b7c-85f2-8fb11d32f7af)
![image34](https://github.com/CodepaceOrganization/Informes/assets/133830443/3d803b81-3f06-4ffc-a7e9-7e973b6c04d5)
  - 4.3.2. Landing Page Mock-up

  ![image36](https://github.com/CodepaceOrganization/Informes/assets/133830443/dfa391b0-52a6-443e-9aa5-798a4c026cfa)

**Landing Page para Mobile Mock-up**

![image11](https://github.com/CodepaceOrganization/Informes/assets/133830443/5d564cef-30df-46e2-ad91-52003ad81140)
![image16](https://github.com/CodepaceOrganization/Informes/assets/133830443/f01902b9-98f9-451d-906c-b3999d1e99ef)![image63](https://github.com/CodepaceOrganization/Informes/assets/133830443/db1ad815-61d8-4838-b353-2357cc6cbc09)


![image63](https://github.com/CodepaceOrganization/Informes/assets/133830443/db1ad815-61d8-4838-b353-2357cc6cbc09)
![image53](https://github.com/CodepaceOrganization/Informes/assets/133830443/e99a2e99-ec26-4222-ab93-90053a46efa2)
![image3](https://github.com/CodepaceOrganization/Informes/assets/133830443/092ab1e7-a8e2-445f-8e38-3c5b8bf2d683)

![image7](https://github.com/CodepaceOrganization/Informes/assets/133830443/f441b0ec-dc09-4b77-8283-36fc8f604e41)
![image52](https://github.com/CodepaceOrganization/Informes/assets/133830443/73d029e1-163e-4a05-bd4c-03ca919130da)
![image14](https://github.com/CodepaceOrganization/Informes/assets/133830443/947603de-6d0e-4039-83ef-f01cdfe8c071)

![image17](https://github.com/CodepaceOrganization/Informes/assets/133830443/fff427fb-0f2c-44a6-af9c-013a2b7c1f82)
- 4.4. Web Applications UX/UI Design
  - 4.4.1. Web Applications Wireframes
  **Enlace para acceder al**
[**<u>Figma</u>**](https://www.figma.com/file/IBYRstHzBvbdgKjdJMCOF7/LandingPage-GetWork?type=design&node-id=1%3A2&mode=design&t=bo7HJOLiUkXbaOlr-1)

**Iniciar sesión**

![image25](https://github.com/CodepaceOrganization/Informes/assets/133830443/cde87525-2ee7-40d0-9db1-5fd3e905593e)

**Crear cuenta**

![image1](https://github.com/CodepaceOrganization/Informes/assets/133830443/abd4ea98-fd21-4ea6-a286-c76f38a33b24)

**Elegir plan de pago**

![image10](https://github.com/CodepaceOrganization/Informes/assets/133830443/712c36cb-c012-4fca-b417-8eae845c6f64)

**Sección de prácticas**

![image20](https://github.com/CodepaceOrganization/Informes/assets/133830443/206d7de3-a355-4da8-9ce0-283233f37730)

![image69](https://github.com/CodepaceOrganization/Informes/assets/133830443/14f6610b-d71e-4302-b4e1-f7b23798325a)

**Sección de contenido**

![image51](https://github.com/CodepaceOrganization/Informes/assets/133830443/6b70a250-b528-4496-8b8a-eabc6037b9b5)

![image12](https://github.com/CodepaceOrganization/Informes/assets/133830443/d9f7e1f1-6d62-4b98-ba18-ac24fc0b1a4e)

**Sección de tutores**

![image31](https://github.com/CodepaceOrganization/Informes/assets/133830443/f35c1a1a-71d8-497d-a1b1-1032f2f7bec0)

**Sección de Simulacro**

![image71](https://github.com/CodepaceOrganization/Informes/assets/133830443/143a22b2-47a7-4372-adbb-0955d1ec6ec5)

**Sección de perfil**

![image80](https://github.com/CodepaceOrganization/Informes/assets/133830443/160b2a0a-6d5b-4c45-bf65-f4ef2cd4e9fe)

**Web Application para Mobile Web Browser**

![image35](https://github.com/CodepaceOrganization/Informes/assets/133830443/1479d76e-37d6-4bc2-8755-bfeab352778d)
![image50](https://github.com/CodepaceOrganization/Informes/assets/133830443/048bdb72-e411-49e4-bd2a-3108887e243d)

![image39](https://github.com/CodepaceOrganization/Informes/assets/133830443/c5c690a4-ec09-46cc-ae07-21f75ea64e1d)
![image9](https://github.com/CodepaceOrganization/Informes/assets/133830443/6b668000-7dbc-4465-93fc-cd34bafacb0f)
![image15](https://github.com/CodepaceOrganization/Informes/assets/133830443/45cf8f26-31ba-4e24-9373-2a16c00d7ed8)
![image26](https://github.com/CodepaceOrganization/Informes/assets/133830443/6bbb140a-9d75-4c30-bfe6-6e30fdc8c442)
![image5](https://github.com/CodepaceOrganization/Informes/assets/133830443/f66dd8dc-698c-48e3-9620-2d5f9b195016)
![image18](https://github.com/CodepaceOrganization/Informes/assets/133830443/4c8b8240-5eb7-465c-871d-886124d6f902)

![image27](https://github.com/CodepaceOrganization/Informes/assets/133830443/4b91dc61-3d86-4a60-9ce1-087438e2b344)
  - 4.4.2. Web Applications Wireflow Diagrams
  **Enlace para acceder al**
[**<u>Lucidchart</u>**](https://lucid.app/lucidchart/80cf9743-81db-40e0-84e8-50e9ca926967/edit?viewport_loc=-9706%2C-2705%2C18465%2C9375%2C0_0&invitationId=inv_8255df90-1551-4474-bb4a-348c48e2e553)

**User Goal: Registrar Usuario**

![image60](https://github.com/CodepaceOrganization/Informes/assets/133830443/8ae6dc65-b962-42e2-9cbe-25ec6d3c1796)

**User Goal: Interfaz de practica**

![image66](https://github.com/CodepaceOrganization/Informes/assets/133830443/eaf76378-211e-4ddb-8b4b-c9a38414519e)

**User Goal: Interfaz de contenido**

![image33](https://github.com/CodepaceOrganization/Informes/assets/133830443/effc2165-e386-47ca-b49e-989c6b051269)

**User Goal: Interfaz de tutores**

![image81](https://github.com/CodepaceOrganization/Informes/assets/133830443/56c44e85-6870-40ff-a106-8c8637be6356)

**User Goal: Simulacro de entrevista**

![image74](https://github.com/CodepaceOrganization/Informes/assets/133830443/36d38b49-f1f3-4c38-9948-61114845f84a)
  - 4.4.3. Web Applications Mock-ups
  **Iniciar sesión**

![image68](https://github.com/CodepaceOrganization/Informes/assets/133830443/43a001a2-5936-4c2a-b14d-a94100c49101)

**Crear cuenta**

![image13](https://github.com/CodepaceOrganization/Informes/assets/133830443/5f876002-8d3e-454c-b03c-68506bc88e79)

**Elegir plan de pago**

![image73](https://github.com/CodepaceOrganization/Informes/assets/133830443/3867d6ca-38c2-44b8-9cb6-818f4c5a79ad)

**Sección de prácticas**

![image64](https://github.com/CodepaceOrganization/Informes/assets/133830443/9953ba87-6d5f-40f8-9e00-99a1af2f75bb)

![image42](https://github.com/CodepaceOrganization/Informes/assets/133830443/e0b0fb52-0e49-4994-981d-b1b271a4565d)

**Sección de contenido**

![image28](https://github.com/CodepaceOrganization/Informes/assets/133830443/facf99ce-eb6b-474c-80fb-0e987d35cc46)

![image44](https://github.com/CodepaceOrganization/Informes/assets/133830443/3827927f-f4f0-4b14-856d-5a0d7aa39e2e)

**Sección de tutores**

![image55](https://github.com/CodepaceOrganization/Informes/assets/133830443/074a2284-0a49-4a03-bda0-25526d84242b)

**Sección de Simulacro**

![image45](https://github.com/CodepaceOrganization/Informes/assets/133830443/7e62c29a-0898-4cac-ae0f-9142ac88bdad)

**Sección de perfil**

![image37](https://github.com/CodepaceOrganization/Informes/assets/133830443/f4903f7a-711d-41c8-b90d-0736d7e2f229)

**Web Application para Mobile Web Browser**

![image75](https://github.com/CodepaceOrganization/Informes/assets/133830443/1bc6b30d-e12d-46c1-9f7f-94cb551c9847)
![image62](https://github.com/CodepaceOrganization/Informes/assets/133830443/4153ef8d-0faa-4f92-9fce-7650acce1f02)

![image29](https://github.com/CodepaceOrganization/Informes/assets/133830443/1a2b1310-f8e2-486d-8fb8-70f675392502)
![image6](https://github.com/CodepaceOrganization/Informes/assets/133830443/ba936e42-a01e-4fdf-afb6-2ee386dd9481)
![image21](https://github.com/CodepaceOrganization/Informes/assets/133830443/dcae70b0-c4c4-4c30-96c0-40cc6b91900c)
![image19](https://github.com/CodepaceOrganization/Informes/assets/133830443/82fd0e83-6204-4a25-a8d0-4a6753979748)

![image72](https://github.com/CodepaceOrganization/Informes/assets/133830443/3821cbfc-cdbc-4fe8-9e57-a9116b54087d)
![image8](https://github.com/CodepaceOrganization/Informes/assets/133830443/d5d6ce07-2e38-4123-982f-e6c339e3e5cc)
  - 4.4.4. Web Applications User Flow Diagrams

  **Enlace para acceder al**
[**<u>Lucidchart</u>**](https://lucid.app/lucidchart/80cf9743-81db-40e0-84e8-50e9ca926967/edit?viewport_loc=-9706%2C-2705%2C18465%2C9375%2C0_0&invitationId=inv_8255df90-1551-4474-bb4a-348c48e2e553)

**User Goal: Registrar Usuario**

![image23](https://github.com/CodepaceOrganization/Informes/assets/133830443/0b9e3ccd-75bc-473b-acb4-02f7d79e5e92)

**User Goal: Interfaz de practica**

![image78](https://github.com/CodepaceOrganization/Informes/assets/133830443/0a439f1d-225b-4265-abee-24a911d7c01a)

**User Goal: Interfaz de contenido**

![image70](https://github.com/CodepaceOrganization/Informes/assets/133830443/0498fd55-196a-4c42-a57d-5b766923c587)

**User Goal: Interfaz de tutores**

![image38](https://github.com/CodepaceOrganization/Informes/assets/133830443/428d4221-02e4-4c57-816b-d4bc059987a6)

**User Goal: Simulacro de entrevista**

![image76](https://github.com/CodepaceOrganization/Informes/assets/133830443/3e24f045-9c84-4a20-aec1-ebdab9642619)

- 4.5. Web Applications Prototyping
  
Al diseñar los prototipos de interfaz de usuario para Desktop y Mobile
Web Browser, se ha seguido una serie de criterios fundamentales para
garantizar una experiencia de usuario efectiva y satisfactoria:

Claridad y Facilidad:

- Se ha priorizado la claridad y la facilidad de uso para hacer que la
  navegación en la aplicación sea intuitiva y comprensible.

- El objetivo es que los usuarios puedan entender completamente las
  funciones de la aplicación, como el registro de procesos y la
  visualización de reportes estadísticos.

Diseño Responsive:

- Se ha considerado la importancia del diseño "responsive" para asegurar
  que la aplicación web sea compatible con una variedad de tamaños de
  pantalla.

- Esto garantiza que los usuarios no se vean limitados por el
  dispositivo que estén utilizando, obteniendo una experiencia
  consistente en distintos dispositivos.

Priorización de Información Relevante:

- El diseño de la aplicación se ha enfocado en mostrar solo la
  información más relevante para los usuarios pertenecientes al segmento
  objetivo.

- Se evita la sobrecarga de información y se destaca lo esencial para
  mejorar la eficiencia y la usabilidad de la interfaz.

![image22](https://github.com/CodepaceOrganization/Informes/assets/133830443/9889696a-d077-43ed-b985-e44df89e6851)

Enlace para acceder al video de explicación del [<u>Web Applications
Prototyping</u>](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202211817_upc_edu_pe/EZp3Qo0XnLdCoBRmMhmBUfIB7_6CEbss59x39MwdOPCSnw?e=NWa7dV)

Enlace para acceder al
[<u>Flujo</u>](https://www.figma.com/proto/IBYRstHzBvbdgKjdJMCOF7/LandingPage-GetWork?type=design&node-id=137-4273&t=XccoLGwDpLxRJeyh-1&scaling=min-zoom&page-id=1%3A2&mode=design)
- 4.6. Domain-Driven Software Architecture
  - 4.6.1. Software Architecture Context Diagram

    ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/0c6edff0-e4e4-4d85-8f21-9ae36604785d)
    
    Enlace para acceder al Diagram [Ver enlace](https://structurizr.com/dsl)

  - 4.6.2. Software Architecture Container Diagrams
    
   **Para usuarios de GetWork:**

   ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/62c40ce8-eae4-48c1-9977-9c06250bb9b0)
  Enlace para acceder al Diagram [Ver enlace](https://structurizr.com/dsl)


  **Para empresas tecnológicas de GetWork:**

   ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/461e8b1e-76ac-4234-81bb-bd34c60083d9)
  Enlace para acceder al Diagram [Ver enlace](https://structurizr.com/dsl)

  - 4.6.3. Software Architecture Components Diagrams

  ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/6a1e7aab-5339-4f7e-938c-db8fd13faa7d)
  Enlace para acceder al Diagram [Ver enlace](https://structurizr.com/dsl)

  
- 4.7. Software Object-Oriented Design
  - 4.7.1. Class Diagrams

  ![image](https://github.com/CodepaceOrganization/Informes/assets/130580982/e4c0be0b-e400-46cd-a807-f632fed90743)

  - 4.7.2. Class Dictionary

  **User**


|**Atribute**|**Type**|**Description**|
| :- | :- | :- |
|id|int|The unique identifier for the user|
|name|string|The user's first name|
|lastName|string|The user's last name|
|email|string|The user's email address|
|password|string|The user's password|

**Interviewer**


|**Atribute**|**Type**|**Description**|
| :- | :- | :- |
|interviewerId|int|The unique identifier for the interviewer|
|department|string|The department to which the interviewer belongs|
|bio|string|The biography or description of the interviewer|
|expertiseAreas|string[]|An array of expertise areas of the interviewer|

**Student**


|**Atribute**|**Type**|**Description**|
| :- | :- | :- |
|studentId|int|Identifier for the student.|
|career|string|Field of study or career path of the student.|
|year|int|Current academic year of the student.|
|gpa|float|Grade Point Average (GPA) of the student.|
|skills|string[]|Array of skills possessed by the student.|
|experience|string|Previous experience or work history of the student.|
|projects|string[]|Array of projects undertaken by the student.|

**CurrentSubscription**


|**Atribute**|**Type**|**Description**|
| :- | :- | :- |
|id|int|Unique identifier for the current subscription|
|subscription|int|Identifier indicating the type of subscription|

**SubcriptionExpire**


|**Atribute**|**Type**|**Description**|
| :- | :- | :- |
|expire\_date|Date|Date indicating the expiration of the subscription.|

**PaymentMethod**


|**Atribute**|**Type**|**Description**|
| :- | :- | :- |
|id|int|Identifier for the payment method.|
|price|float|Price associated with the payment method.|

**PriceSubscription**


|**Atribute**|**Type**|**Description**|
| :- | :- | :- |
|id|int|Unique identifier for the price subscription|
|price|float|Price of the subscription|
|subscription|CurrentSubscription|Reference to the current subscription associated with this price subscription|

**FeaturesSubscription**


|**Atribute**|**Type**|**Description**|
| :- | :- | :- |
|id|int|Identifier for the features subscription.|
|features|string|Description of the features included in the subscription.|
|subscription|current\_subscription|Current subscription associated with the features.|

**MockInterview**


|**Atribute**|**Type**|**Description**|
| :- | :- | :- |
|interviewer|User|The interviewer participating in the interview|
|student|User|The student being interviewed|
|questions|List<String>|List of questions asked during the interview|
|answers|List<String> |List of answers provided by the student|
|success|boolean|Indicates whether the interview was successful|
|strategy|InterviewStrategy|The strategy used during the interview|

**MemberList**


|**Atribute**|**Type**|**Description**|
| :- | :- | :- |
|userList|List<User>|List of users who are members.|
|resourceList|List<Resource>|List of resources associated with members.|

**Resource**


|**Atribute**|**Type**|**Description**|
| :- | :- | :- |
|type|ResourceType|Type of the resource.|
|content|String|Content of the resource.|


- 4.8. Database Design

  En nuestro proyecto, hemos optado por utilizar SQL (Structured Query Language) como el lenguaje principal para interactuar con la base de datos. SQL es un lenguaje estándar ampliamente reconocido y utilizado en la gestión de bases de datos relacionales.
  Para la gestión de nuestras bases de datos, hemos elegido Microsoft SQL Server como nuestro sistema de gestión de bases de datos (DBMS). Microsoft SQL Server es una opción confiable y robusta que ofrece una amplia gama de características y herramientas para el diseño, desarrollo y administración de bases de datos.
  Al utilizar Microsoft SQL Server, podemos aprovechar su capacidad para manejar grandes volúmenes de datos de manera eficiente y segura. Además, nos brinda herramientas para la administración de usuarios, la configuración de permisos de acceso y la implementación de medidas de seguridad avanzadas para proteger la integridad y confidencialidad de nuestros datos.


  - 4.8.1. Database Diagram

![image](https://github.com/CodepaceOrganization/Informes/assets/130580982/3cb9ee4b-ba67-433d-9e12-90a25b7aa150)

### Capítulo V: Product Implementation, Validation & Deployment
**5.1. Software Configuration Management**
  - 5.1.1. Software Development Environment Configuration
    En nuestro proceso de gestión de requisitos, nos apoyamos en una variedad de herramientas que aseguran una organización efectiva y transparente. Empleamos Trello para supervisar el flujo de trabajo, lo que nos permite visualizar y mantener actualizado el estado de las tareas y las historias de usuario en los sprints en desarrollo. Para el diseño de la experiencia de usuario (UX), confiamos en Figma, una plataforma versátil que nos permite crear y revisar los diseños de la aplicación en sus diferentes versiones, desde escritorio hasta dispositivos móviles. Complementamos este proceso de diseño con el uso de Lucidchart, que nos ayuda a diagramar flujos y estructuras clave, proporcionando una comprensión clara de la arquitectura del proyecto.

    En el ámbito del testing de software, utilizamos Gherkin como nuestro sistema de etiquetado para describir los criterios de aceptación de las historias de usuario. Este enfoque nos permite realizar una verificación estructurada y exhaustiva de cada funcionalidad desarrollada, garantizando la calidad del producto final.
    
    ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/a860532b-0aa0-4127-8af0-105f7f81d225)

    Para el desarrollo de software, confiamos en Rider como nuestro entorno de desarrollo integrado (IDE) preferido. Rider ofrece un conjunto de herramientas robusto y eficaz que nos permite elaborar y compilar el código con eficiencia, con soporte completo para una amplia gama de lenguajes de programación, incluido C#. Durante el desarrollo, utilizamos HTML5 y CSS para la presentación y el diseño de la aplicación web, mientras que C# se emplea para desarrollar la interfaz de usuario, aprovechando su orientación a objetos y su integración perfecta con Rider.

    ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/67d3ae81-7d85-4fb3-9241-a41297bbfb73)

    Para el control de versiones y el despliegue del software, hacemos uso de Git y GitHub. Git nos permite gestionar los repositorios del proyecto, mientras que GitHub nos proporciona una plataforma basada en la nube que facilita la colaboración en tiempo real y la revisión de contribuciones entre los miembros del equipo. Esto asegura un desarrollo y despliegue eficientes del proyecto en su totalidad.
    
    Git:

    ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/c42fc202-e798-4b91-9b44-bd0d0251b22d)

    Github:

    ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/52f0687d-5f2d-40bd-ac0d-78f37cc35370)


  - **5.1.2. Source Code Management**
    
    En nuestro proyecto, hemos adoptado una estrategia que utiliza GitFlow para la gestión altamente eficiente del código fuente, junto con GitHub para el registro de versiones. A continuación, se detalla cómo hemos implementado GitFlow en nuestro flujo de trabajo:

    Implementación de GitFlow:
    
    ![image](https://github.com/CodepaceOrganization/Informes/assets/130623774/f2be5d26-18f7-4c6f-a51e-2a06e7579726)
    Ramas Principales:

    **Main:** Esta rama contiene la versión más estable y lista para producción de nuestro proyecto.
    Develop: En esta rama se integran todas las características finalizadas, representando así la versión en desarrollo del proyecto.
    Ramas de Funcionalidades (Feature Branches):

    Cada nueva característica o cambio importante se desarrolla en su propia rama de funcionalidades, creada a partir de develop.

    Una vez completada y probada la funcionalidad, se fusiona nuevamente en develop.

    **Ramas de Publicación (Release Branches):**

    Cuando se alcanza un conjunto de características suficientemente estable en develop, se crea una rama de publicación.

    En esta rama, se realizan las últimas pruebas y ajustes antes de lanzar una nueva versión.

    Posteriormente, la rama de publicación se fusiona en master y develop, etiquetándola con el número de versión correspondiente.

    **Ramas de Corrección de Errores (Hotfix Branches):**

    Si surge un problema crítico en la versión en producción, se crea una rama de corrección de errores desde master.

    La solución se implementa en esta rama y luego se fusiona en master y develop.

    **Repositorio en GitHub:**

    Estos enlaces proporcionan acceso directo a nuestros repositorios:

    Enlace de Organización: [Ver enlace](https://github.com/CodepaceOrganization)

    Enlace de Landing Page: [Ver enlace](https://github.com/CodepaceOrganization/GetWork-LandingPage)

    **Commits:**
    
    Para los commits que realicemos en nuestro proyecto utilizaremos Conventional Commits. Esta convención nos permite estructurar mejor los mensajes de commits de manera clara y consistente, lo que facilita la comprensión en los cambios realizados en el repositorio


  - **5.1.3. Source Code Style Guide & Conventions**

    **Convenciones de Nomenclatura:**

    - HTML, CSS, JavaScript:
      - Utilizar camelCase para nombres de variables y funciones.
      - Emplear nombres descriptivos que reflejen el propósito o contenido del elemento.
      - Evitar abreviaturas a menos que estén ampliamente aceptadas o estandarizadas.
      - Utilizar letras minúsculas para nombres de archivos y carpetas.

    **Convenciones de Codificación:**

    - Guía de Estilo y Convenciones de Codificación HTML:
      - Seguir las mejores prácticas para la estructura HTML, incluyendo la indentación y comentarios.
      - Utilizar elementos HTML semánticos cuando sea apropiado.

    - Guía de Estilo de Google para HTML/CSS:
      - Mantener un formato y una indentación consistentes.
      - Utilizar preprocesadores CSS como Sass para organizar y modularizar el código.
    - Guía de Estilo de Google para JavaScript, Directrices de JavaScript de MDN, Guía de Estilo de JavaScript de la W3C:
      - Seguir los estándares ES6 para la sintaxis de JavaScript.
      - Emplear nombres de variables significativos y evitar variables globales cuando sea posible.
      - Utilizar funciones de flecha, literales de plantilla y desestructuración cuando sea apropiado.
    - Guía de Estilo de Vue:
      - Seguir las pautas específicas de Vue.js para la estructura y convenciones de nombres de componentes.
      - Utilizar eficazmente el sistema de reactividad de Vue para un renderizado eficiente.
    - Convenciones de Codificación de C#, Directrices de Codificación de ASP.NET Core de Microsoft:
      - Seguir las convenciones de codificación de C# de Microsoft para garantizar consistencia y legibilidad.
      - Utilizar PascalCase para nombres de clases y métodos, camelCase para variables locales y parámetros.
      - Implementar un manejo adecuado de errores y el uso de excepciones.

  - 5.1.4. Software Deployment Configuration

    **Pasos de Implementación:**

    - Página de Aterrizaje:
      - Asegurar que todos los archivos HTML, CSS y JavaScript estén minimizados para una carga eficiente.
      - Utilizar un servidor web como Apache o Nginx para servir archivos estáticos.
      - Considerar la implementación a través de plataformas como Netlify o Vercel para una configuración fácil y despliegue continuo.
    - Servicios Web:
      - Contenerizar los servicios web utilizando Docker para consistencia entre entornos.
      - Utilizar pipelines de integración y despliegue continuo (CI/CD) con herramientas como Jenkins o GitLab CI.
      - Desplegar en plataformas en la nube como AWS, Azure o Google Cloud para escalabilidad y confiabilidad.
    - Aplicaciones Web Frontend:
      - Agrupar los activos frontend utilizando webpack o Parcel para optimización.
      - Utilizar CDNs para servir bibliotecas y frameworks y mejorar los tiempos de carga.
      - Implementar estrategias de almacenamiento en caché para activos estáticos para reducir la carga del servidor.

  **5.2. Landing Page, Services & Applications Implementation**
  - 5.2.1. Sprint 1
    - 5.2.1.1. Sprint Planning 1
      
      Un sprint representa un periodo corto y fijo de tiempo durante el cual se desarrolla un conjunto de tareas o actividades específicas en un proyecto, asociado con metodologías             ágiles como Scrum. El           Sprint #1          tiene como fecha de inicio el 25/03/2024 y plantea elaborar una landing page atractiva para TripMate que capte la atención de los usuarios                 visitantes y comunique los principales                beneficios de nuestro        producto.

      | **Sprint #** | **Sprint 1** |
      | :- | :- |
      | **Sprint Planning Background** | |
      | Date | 25/03/2024 |
      | Time | 8:00 PM - 11:00 PM |
      | Location | Google Meet |
      | **Prepared By** | Quispe Andia, Jeremy Joel|
      | Attendees | - Cachis Gonzales, Sebastian Nicolas (u202210846)<br>- Cruz Palomino, Adriano Sebastian (u202210697)<br>- Castillo Castillo, Alexander Jair (u202211390)<br>- Quispe Andia, Jeremy Joel (u202216279)<br>- Cabanillas Gora, Andrea Milagros (u202211711)<br>- Yauri Paucar, Elias (u202211817) |
      | **Sprint 0 Review Summary** | Diseño y desarrollo del Landing Page |
      | **Sprint 0 Retrospective Summary** | Completar los diseños y estandarizar el lenguaje usado en el desarrollo y presentación del landing page |
      | **Sprint Goal & User Stories** | |
      | **Sprint 1 Goal** | Elaborar, diseñar y desplegar una Landing Page atractiva e informativa para la aplicación GetWork |
      | **Sprint 1 Velocity** | 15 |
      | **Sum of Story Points** | 15 |


  - 5.2.1.2. Sprint Backlog 1
  
|**Sprint 1**|**Sprint 1**|||||||
| :- | :- | :- | :- | :- | :- | :- | :- |
|**User Story**|**Work-Item / Task**|||||||
|<p>** </p><p>**Id**</p>|<p>** </p><p>**Title**</p>|<p>** </p><p>**Id**</p>|<p>** </p><p>**Title**</p>|<p>** </p><p>**Description**</p>|**Estimation (Hours)**|<p>** </p><p>**Assigned To**</p>|**Status(To do/In process/To review/Done)**|
|US09|Visualizar la landing page de la empresa|W01|Implementar los archivos y la base de la landingpage|Desarrollar en VS la base de la landing page|1|<p>Adriano</p><p>Cruz</p>|Done|
|US02|Seguridad de cuenta|W02|Configurar sistema de autenticación|Configurar sistema de autenticación de dos factores para la seguridad de la cuenta.|2|Sebastian Cachis|To review|
|US13|<p>Registrarse en la landing page</p><p></p><p></p>|W03|Implementar pantalla de registro|Implementar pantalla de registro con campos de nombre, correo electrónico y contraseña.|1|<p>Jeremy</p><p>Quispe</p>|Done|
|US19|<p>Enviar consulta a través del formulario de contacto</p><p></p><p></p>|W04|Crear formulario contacto|Implementar formulario contacto con sus atributos requeridos.|3|<p>Alexander</p><p>Castillo</p>|Done|
|US21|Ver testimonios de clientes en la landing page|W05|Crear la seccion testimonios|Implementar sección de testimonios|2|<p>Andrea</p><p>Cabanillas</p>|Done|
|US07|<p>Interfaz </p><p>sencilla</p>|W06|Implementar una interfaz sencilla|Implementar un sistema de mensajería interna para permitir la comunicación entre usuarios.|3|Elias<br>Yauri|Done|

Sprint en trello: [Ver enlace](https://trello.com/invite/b/LttsMJKr/ATTIcf77758198087805f0691dd9c443d0bc2AD611CA/sprint-1)


  - 5.2.1.3. Development Evidence for Sprint Review

    |Repository|Branch|Commit ID|Commit Message|Commit Message Body|Commited On<br>(Date)|  
    |----------|------|---------|--------------|-------------------|------------------|
    |AdrianoSCruzP/<br>CodepaceOrganization<br>/GetWork-LandingPage|Main|bd35415|feat: add initial version of landing page|-|26/03/2024| 
    |AdrianoSCruzP/<br>CodepaceOrganization<br>/GetWork-LandingPage|Main|0a66582|refactor: Replace <div> with <header> for navbar|-|27/03/2024|
    |AdrianoSCruzP/<br>CodepaceOrganization<br>/GetWork-LandingPage|Main|21c0f18|styles: add styles for navbar|-|27/03/2024| 
    |Dark7YT/<br>CodepaceOrganization<br>/GetWork-LandingPage|Main|d6d55fc|feat: add in the index the services section and the images|-|27/03/2024| 
    |Dark7YT/<br>CodepaceOrganization<br>/GetWork-LandingPage|Main|16d3c8f|refactor: names of the images of services|-|28/03/2024| 
    |Dark7YT/<br>CodepaceOrganization<br>/GetWork-LandingPage|Main|0452280|style: implement the style to the index and the images for the service section|-|28/03/2024| 
    |Dark7YT/<br>CodepaceOrganization<br>/GetWork-LandingPage|Main|b8bd137|refactor: variable names instead of color code in the CSS|-|29/03/2024| 
    |Dark7YT/<br>CodepaceOrganization<br>/GetWork-LandingPage|Main|716c4ec|feat: add in the index the about section and the style|-|29/03/2024|
    |Jemisas/<br>CodepaceOrganization<br>/GetWork-LandingPage|Main|988016c|feat: Add Login.html Login.css Login.js|-|29/03/2024| 
    |Dark7YT/<br>CodepaceOrganization<br>/GetWork-LandingPage|Main|f2dd6d8|fix: the back-button class in login.html|-|23/03/2024| 
    |Jemisas/<br>CodepaceOrganization<br>/GetWork-LandingPage|Main|1069955|fix: Add link to registration page from login form|-|30/03/2024| 
    |AdrianoSCruzP/<br>CodepaceOrganization<br>/GetWork-LandingPage|Main|ec9602b|fix: folder structure arrangement|-|30/03/2024|
    |U202211390/<br>CodepaceOrganization<br>/GetWork-LandingPage|Main|f3dfcc5|feat: add contact in the code and their styles|-|30/03/2024| 
    |U202211390/<br>CodepaceOrganization<br>/GetWork-LandingPage|Main|f386290|fix: ref css login transition|-|30/03/2024| 
    |EliasYP/<br>CodepaceOrganization<br>/GetWork-LandingPage|Main|f2dd6d8|feat: added the register interface and made some changes to the login|-|30/03/2024| 
    |U202211390/<br>CodepaceOrganization<br>/GetWork-LandingPage|Main|bd2d6af|fix: section plans|-|30/03/2024|  
    |Jemisas/<br>CodepaceOrganization<br>/GetWork-LandingPage|Main|bd2d6af|feat: add section plans and images|-|30/03/2024|  
    |U202211390/<br>CodepaceOrganization<br>/GetWork-LandingPage|Main|e46b5a0|feat: add contact in the code and their styles|-|02/04/2024| 
    |Jemisas/<br>CodepaceOrganization<br>/GetWork-LandingPage|Main|268ec8c|Fix: navbar and plans responsive|-|02/04/2024|
    |Jemisas/<br>CodepaceOrganization<br>/GetWork-LandingPage|Main|32a7bbd|Feat: add section inicio and ajust navbar responsive|-|04/04/2024|
    |Jemisas/<br>CodepaceOrganization<br>/GetWork-LandingPage|Main|5c5c700|Feat: Add footer and styles|-|04/04/2024|
    |AdrianoSCruzP/<br>CodepaceOrganization<br>/GetWork-LandingPage|Main|ae238f8|feat: update HTML code with structural changes and fixed links|-|07/04/2024|
    |AdrianoSCruzP/<br>CodepaceOrganization<br>/GetWork-LandingPage|Main|bedba2e|feat: Add styles and functionality to the navbar|-|07/04/2024|
    |AdrianoSCruzP/<br>CodepaceOrganization<br>/GetWork-LandingPage|Main|e8214c5|fix: Fix responsive layout on mobile devices and navbar functionality|-|07/04/2024|
    |Jemisas/<br>CodepaceOrganization<br>/GetWork-LandingPage|Main|c1b2f40|fix: the folders|-|09/04/2024|
    |Jemisas/<br>CodepaceOrganization<br>/GetWork-LandingPage|Main|e1c853c|feat: add readme of the landingpage|-|09/04/2024|
    |Jemisas/<br>CodepaceOrganization<br>/GetWork-LandingPage|Main|1d0488b|fix: route the images|-|09/04/2024|

  - 5.2.1.4. Testing Suite Evidence for Sprint Review
    
    |Repository|Branch|Commit ID|Commit Message|Commit Message Body|Commited On<br>(Date)|  
    |----------|------|---------|--------------|-------------------|------------------|
    |Jemisas/<br>CodepaceOrganization<br>/Acceptance-Test|Main|f10284|feat: added files .feature|-|12/04/2024| 
    |Jemisas/<br>CodepaceOrganization<br>/Acceptance-Test|Main|47a6e36|feat: added US02 "Vinculación de número de celular a la aplicación"|-|12/04/2024|
    |Jemisas/<br>CodepaceOrganization<br>/Acceptance-Test|Main|3632856|feat: added US07: "Interfaz sencilla"|-|12/04/2024| 
    |Jemisas/<br>CodepaceOrganization<br>/Acceptance-Test|Main|631167d|feat: Added US09 "Visualizar la landing page de la empresa"|-|12/04/2024| 
    |Jemisas/<br>CodepaceOrganization<br>/Acceptance-Test|Main|bd6751|feat: added US13 "Registrarse en la landing page"|-|12/04/2024| 
    |Jemisas/<br>CodepaceOrganization<br>/Acceptance-Test|Main|e526d|sfeat: added US21: "Ver testimonios de clientes en la landing page"|-|12/04/2024|

    Link para visualizar los acceptance test elaborados en gherkin: [Ver enlace](https://github.com/CodepaceOrganization/Acceptance-Test)
    
  - 5.2.1.5. Execution Evidence for Sprint Review
  
    Durante el Sprint 1, se realizaron las siguientes implementaciones en la página de inicio:

    **1. Creación de la base de la Landing Page:**
    
    -Se desarrolla la estructura inicial de la página de destino, estableciendo los elementos fundamentales para su funcionamiento y diseño.
    
    ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/5fb4496e-9171-4bde-8f8e-909e235aef35)

    **2. Implementar sistema de autenticación:**
  
    -Se integra un sistema que permite a los usuarios registrarse e iniciar sesión de manera segura, garantizando la privacidad y la protección de datos.
      
    ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/bcc08a18-de71-4fec-abd2-ffbecedc0b89)

   **3. Implementar pantalla de registro:**
   
   -Se crea una interfaz para que los usuarios puedan registrarse en la plataforma, proporcionando la información necesaria y cumpliendo con los requisitos de seguridad.
      
   ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/bf76235e-f4e0-4968-8122-ed7af61a84cb)

   **4. Implementar Formulario Contacto:**
   
   -Se añade un formulario que permite a los visitantes de la página ponerse en contacto con el equipo a través de mensajes, consultas o comentarios.
      
   ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/64929c86-c633-4db4-825e-9a1887c03662)


   **5. Implementar testimonios:**
   
   -Se implementa card en las cuales reflejan la experiencia que tendras los usuarios en nuestra aplicación web.  
      
   ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/6d8620d4-cab2-47e7-8020-d892e90449ca)

   **6. Implementar una interfaz sencilla:**
   
  -Se diseña una interfaz fácil de usar y entender, priorizando la accesibilidad y la experiencia del usuario para garantizar una navegación fluida y agradable.
      
   ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/b96d5875-f55e-48ce-ab3a-a2f0850fe809)

  - 5.2.1.6. Services Documentation Evidence for Sprint Review

  Para esta entrega no fue contemplada la evidencia de documentación de los servicios

  - 5.2.1.7. Software Deployment Evidence for Sprint Review

    Durante este sprint, se ha realizado una serie de actividades relacionadas con el despliegue de nuestros productos, incluyendo la creación de cuentas, configuración de recursos en        proveedores de servicios en la nube y la implementación de proyectos de desarrollo para integrar y automatizar el proceso de despliegue. Como parte de estas actividades, hemos creado     un repositorio en GitHub para gestionar el código fuente de nuestros productos. Este repositorio nos proporciona un entorno colaborativo donde los miembros del equipo pueden trabajar     en conjunto y realizar un seguimiento de las versiones del código.
    
    Además, hemos desarrollado una Landing Page como parte de nuestra estrategia de despliegue. La Landing Page es una interfaz inicial que proporciona información relevante sobre            nuestros productos y servicios. Para su implementación, hemos utilizado tecnologías web modernas y hemos seguido prácticas de diseño centradas en el usuario para garantizar una           experiencia atractiva y funcional para nuestros visitantes. La creación de la Landing Page ha sido un paso crucial en nuestra estrategia de despliegue, ya que sirve como punto de         entrada para los usuarios interesados en nuestros productos y servicios.

![image](https://github.com/CodepaceOrganization/Informes/assets/130580982/4d85bf19-b26f-4f95-9b0e-6f8b4e5fed46)

![image](https://github.com/CodepaceOrganization/Informes/assets/130580982/dcfe81d3-c078-48ed-be78-b9c6c6d5685c)

![image](https://github.com/CodepaceOrganization/Informes/assets/130580982/5cb5af11-b798-476b-a860-b5fd6b00fdbe)

![image](https://github.com/CodepaceOrganization/Informes/assets/130580982/1d7dbcd2-0dbf-44c1-95cc-ef76fa6d2ab8)

  - 5.2.1.8. Team Collaboration Insights during Sprint

    | Alumno                              | Actividad                                                  |
      |-------------------------------------|------------------------------------------------------------|
      | Cruz Palomino, Adriano Sebastian   | Implementación de la base y los archivos de la landing page     |
      | Cachis Gonzales, Sebastian Nicolas| Implementación de la sección de Feautures de la empresa   |
      | Quispe Andia, Jeremy Joel      | Implementación del responsive, form registro y footer     |
      | Cabanillas Gora, Andrea Milagros 	| Implementación de la sección testimonos           |
      | Yauri Paucar, Elias| Implementación Form Registro       |
      | Castillo Castillo, Alexander Jair| Implementación Form Contact |

 
      Hemos desarrollado en conjunto un total de 38 commits para el desarrollo de nuestra landing page, tanto en creación de secciones, corrección de bugs, entre otras cosas.
 
      Tabla para poder identificarnos:

      |Username (Github)                    | Nombre                                                  |
      |-------------------------------------|------------------------------------------------------------|
      | FlowerPowerA  | Cabanillas Gora, Andrea Milagros      |
      | AdrianoSCruzP       | Cruz Palomino, Adriano Sebastian   |
      | Jemisas      | Quispe Andia, Jeremy Joel      |
      | Dark7YT 	| Cachis Gonzales, Sebastian Nicolas           |
      | U202211390 | Castillo Castillo, Alexander Jair    |
      | EliasYP  | Yauri Paucar, Elias |

      ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/713c0172-ed8c-4a00-85b3-5a28ce2b0106)
      ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/b06f9713-607c-4f7b-b801-78f06ab88b04)

**5.2.2. Sprint 2**

**5.2.2.1.Sprint Planning 2.**

**5.2.2.2.Sprint Backlog 2.**

**5.2.2.3.Development Evidence for Sprint Review.**

**5.2.2.4.Testing Suite Evidence for Sprint Review.**

**5.2.2.5.Execution Evidence for Sprint Review.**

En el sprint 2 se alcanzó a implementra el desarrollo completo del despliegue de nuestra app web. La cual muestra al usuario una interfaz llamativa donde puede vizualizar nuestras diferentes secciones donde podra realizar practicas de codificación, simulacro de entrevistas, etc.

Sección Technical Tests:

![image](https://github.com/CodepaceOrganization/Informes/assets/133830443/cc06cbd0-ee61-4286-9b91-618fb63e3444)

![image](https://github.com/CodepaceOrganization/Informes/assets/133830443/63335c9a-9619-4fa3-9da7-30ad9adad485)

Sección Contest:

![image](https://github.com/CodepaceOrganization/Informes/assets/133830443/143aaee5-0a61-4fd1-9cad-429851091ad0)

Sección Simulacrum:

![image](https://github.com/CodepaceOrganization/Informes/assets/133830443/62800727-4d37-4884-9a6c-e4cfce0e85c1)

Sección Tutors:

![image](https://github.com/CodepaceOrganization/Informes/assets/133830443/9a29ae85-ddbb-4fab-9268-0d7c4e4678b9)

Sección User:

![image](https://github.com/CodepaceOrganization/Informes/assets/133830443/247b1980-c753-4021-bad6-be5175977fa9)

Sección Premium:

![image](https://github.com/CodepaceOrganization/Informes/assets/133830443/ac5d3c5b-82f6-426d-a4cb-56a32d6d1e21)

Responsive: 

![image](https://github.com/CodepaceOrganization/Informes/assets/133830443/ae16f66d-a3b5-473a-ba60-a3fc7bc7f55f)


**5.2.2.6.Services Documentation Evidence for Sprint Review.**

**5.2.2.7.Software Deployment Evidence for Sprint Review.**

**5.2.2.8.Team Collaboration Insights during Sprint.**
| Alumno                             | Actividad                                                             |
|------------------------------------|-----------------------------------------------------------------------|
| Cruz Palomino, Adriano Sebastian   | Implementación de la sección Planes y Gestión de perfil de la web app |
| Cachis Gonzales, Sebastian Nicolas | Implementación de la sección de Problems y derivados de la web app    |
| Quispe Andia, Jeremy Joel          | Implementación de la sección simulacrum y tutors de la web app        |
| Cabanillas Gora, Andrea Milagros   | Implementación de sección de Problems y derivados de la web app       |
| Yauri Paucar, Elias                | Implementación de la sección Contest y derivados de la web app        |
| Castillo Castillo, Alexander Jair  | Implementación de la sección Contest y derivados de la web app        |

Repositorio Web App:

![image](https://github.com/CodepaceOrganization/Informes/assets/133830443/aeeb9d0b-9bd4-427a-9de1-172181125ff9)
![image](https://github.com/CodepaceOrganization/Informes/assets/133830443/73f85868-3e30-4938-8099-4c630903fb3f)

      
**Conclusiones**

**TB1:**

El proyecto "GetWork" de la startup CodePace se presenta como una solución innovadora y necesaria para abordar un desafío comúnmente enfrentado por los estudiantes universitarios: la falta de preparación adecuada para enfrentar entrevistas técnicas y el mercado laboral en el campo de la tecnología. Mediante una cuidadosa investigación y análisis de las necesidades de los estudiantes y las demandas de la industria, CodePace ha desarrollado una plataforma integral que tiene como objetivo cerrar la brecha entre la educación académica y las expectativas del mundo laboral. Esta iniciativa demuestra un profundo compromiso de la startup con el éxito y el crecimiento profesional de los estudiantes, así como con la creación de una fuerza laboral altamente calificada en el campo de la tecnología.

Una de las fortalezas clave del proyecto "GetWork" radica en su enfoque centrado en el usuario. CodePace ha comprendido la importancia de brindar una experiencia integral y personalizada a sus usuarios. La plataforma ofrece una amplia gama de recursos y herramientas, que van desde preguntas frecuentes de entrevistas hasta ejercicios de codificación práctica y simulacros de entrevistas en vivo con expertos. Además, la colaboración estrecha con empresas de tecnología permite a CodePace ofrecer contenido exclusivo y oportunidades de reclutamiento para sus usuarios. Este enfoque centrado en el usuario garantiza que los estudiantes tengan acceso a recursos relevantes y actualizados, lo que mejora significativamente sus posibilidades de éxito en el proceso de búsqueda de empleo y los coloca en una posición ventajosa en un mercado altamente competitivo.

Además de su enfoque en el desarrollo de habilidades técnicas, el proyecto "GetWork" hace hincapié en la importancia de las competencias interpersonales y las habilidades de trabajo en equipo. CodePace reconoce que el éxito en la industria de la tecnología no se limita únicamente a la excelencia técnica, sino que también requiere la capacidad de colaborar eficazmente en equipos multidisciplinarios. Por lo tanto, el proyecto busca fomentar la participación efectiva y objetiva de los estudiantes en proyectos reales, brindándoles la oportunidad de aplicar sus conocimientos y habilidades en un entorno de trabajo colaborativo. Además, al proporcionar a los estudiantes la oportunidad de conocer y comprender al menos un sector empresarial o dominio de aplicación de soluciones de software, se promueve una visión más amplia y contextualizada de las habilidades necesarias en el campo. Esta combinación única de habilidades técnicas y competencias interpersonales fortalece el perfil de los estudiantes, los prepara adecuadamente para los desafíos del mundo laboral y los diferencia como profesionales altamente capacitados y versátiles.

En conlusión, el proyecto "GetWork" de CodePace representa una solución innovadora y necesaria para abordar la brecha entre la educación académica y las demandas del mercado laboral en el campo de la tecnología. Su enfoque centrado en el usuario, la oferta integral de recursos y herramientas, así como la promoción de competencias interpersonales y habilidades de trabajo en equipo, demuestran el compromiso de la startup con el éxito y el crecimiento profesional de los estudiantes. Este proyecto no solo prepara a los estudiantes para enfrentar entrevistas técnicas, sino que también los equipa con las habilidades necesarias para sobresalir en la industria tecnológica y contribuir al desarrollo de soluciones innovadoras.

**TP:**


**Bibliografía**

  - Apliint. (2024). 10 principales tecnologías frontend para usar en 2022. Recuperado de: [Apliint](https://apliint.com/2022/03/15/10-principales-tecnologias-frontend-para-usar-en-2022/)
  
  - HackerRank. (2024). Skills speak louder than words. Recuperado de: [HackerRank](https://www.hackerrank.com/)
  
  - LeetCode. (2024). A New Way to Learn. Recuperado de: [LeetCode](https://leetcode.com/)
  
  - Indeed. (2023). Las 10 mejores aplicaciones para buscar trabajo por internet. Recuperado de: [Indeed](https://www.indeed.com/orientacion-profesional/como-encontrar-empleo/mejores-aplicaciones-buscar-trabajo-internet)
  
  - Interviewbit. (2024). Everything you need to crack your Next Tech Interview. Recuperado de: [Interviewbit](https://www.interviewbit.com/)
    
  - The Markdown Guide. (s.f.). Recuperado de: [Markdown Guide](https://www.markdownguide.org/)

  - Mendel, J. (s.f.). Seriously, what’s your (startup’s) problem? Recuperado de: [Medium](https://medium.com/@jakemendel/seriously-whats-your-startup-s-problemb3a884c54ab4)

  - Progressa Lean. (s.f.). 5W+2H - Técnica de análisis de problemas. Recuperado de: [ProgessaLean](https://www.progressalean.com/5w2h-tecnica-de-analisis-de-problemas/)

  - Fowler, M. (s.f.). Ubiquitous Language. Recuperado de: [MartinFowler](https://martinfowler.com/bliki/UbiquitousLanguage.html)

**Anexos**
- Enlace para acceder a la landing page: [Ver enlace](https://getwork.netlify.app/)
- Enlace para acceder la aplicación web: [NO aplica este entregable]()
- Video de todas las entrevistas subido a stream: [Ver enlace](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202216279_upc_edu_pe/EaamMTLNLXFIkqSN91zWbcoB50FCtcaRcFfin2Tb9V2gkA?e=eoOsSh&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)
- Video exposición TB1: [Ver enlace](https://upcedupe-my.sharepoint.com/personal/u202210846_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu202210846%5Fupc%5Fedu%5Fpe%2FDocuments%2Fupc%2Dpre%2D202401%2D%20si730%2DSW56%2DGetWork%2Dexpo%2Dtb1%2Emp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0=&ga=1)
- Repositorio GitHub LandingPage: [Ver enlace](https://github.com/CodepaceOrganization/GetWork-LandingPage/tree/develop)
- Repositorio GitHub Informes: [Ver enlace](https://github.com/CodepaceOrganization/Informes)
- Repositorio GitHub Acceptance-Test: [Ver enlace](https://github.com/CodepaceOrganization/Acceptance-Test)
- Enlace para acceder al figma LandingPage: [Ver enlace](https://www.figma.com/file/IBYRstHzBvbdgKjdJMCOF7/LandingPage-GetWork?type=design&node-id=0%3A3&mode=design&t=Lv20k0Frf2z0vmA0-1)
- Enlace para acceder al figma Aplicación Web: [Ver enlace](https://www.figma.com/file/fBSQdNJJcBVnOnb3b6qj0t/Web-Application-GetWork?type=design&node-id=0%3A1&mode=design&t=ZWpSGbkUwjfRnrYe-1)
- Enlace para acceder al video de explicación del [<u>Web ApplicationsPrototyping</u>](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202211817_upc_edu_pe/EZp3Qo0XnLdCoBRmMhmBUfIB7_6CEbss59x39MwdOPCSnw?e=NWa7dV)

</div>
