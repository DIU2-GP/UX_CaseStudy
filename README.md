# DIU25

Prácticas Diseño Interfaces de Usuario (Tema: Gastronomía, Ocio y Degustación)

[Guiones de prácticas](GuionesPracticas/)

Grupo: DIU2_GP.  Curso: 2024/25

Actualizado: 07/03/2025

Proyecto:

Página Web Taberna de Kafka

Descripción:

Desarrollo de una página web que permita al negocio La Taberna de Kafka para mejorar la experiencia de usuario, que actualmente se limita a la consulta de información, y ofrecer servicios actualizados como la reserva a través de internet, la consulta de información en tiempo real, o la subscripción a información, para permitir a la taberna modernizarse y adaptarse a las necesidades digitales de sus clientes.

Logotipo:

El logotipo es un rediseño del cartel actual del local. Para simplificarlo y hacer que funcione como logotipo nos decidimos por escoger la parte más importante del mismo, la K, y para darle un toque que recuerde al vino, más allá de la figura de copa introducida en la sombra de la letra, decidimos utilizar el color principal de la página web para hacer un degradado de color.

<img src="./P3/logotipo.png" alt="Logotipo" width="200" height="200"/>

Miembros:

* :bust_in_silhouette:  Germán Vega Avila     :octocat:    <https://github.com/germanvegaa>
* :bust_in_silhouette:  Pablo Del Río López     :octocat:    <https://github.com/pdrl02>

# Proceso de Diseño

<br>

## Paso 1. UX User & Desk Research & Analisis

### 1.a User Reseach Plan

#### 1 Introducción

Granada es un referente en cultura y ocio, y la gastronomía juega un papel clave. Dentro de este mercado las nuevas tecnologías pueden ser muy útiles para muchos negocios. Así, la interacción entre las personas y los servicios de información que estas empresas ponen a disposición de los mismos es muy importante. Durante esta práctica nos centraremos en analizar este sector y en estudiar diferentes métodos para estudiar la usabilidad.

#### 2 Objetivos Principales

Existirían dos objetivos principales, el estudio del sector de la gastronomía como una forma de ocio, y el análisis de diferentes métodos y tecnología para estudiar la usabilidad de los diferentes diseños de las interfaces de usuario.

#### 3 Estrategia

Utilizaremos diferentes técnicas.  
Para estudiar el sector del ocio de desgustación, nos centraremos en:  

* Investigar el mercado: Principalmente a través de la visita a diferentes establecimientos y las entrevistas a trabajadores y propietarios de los negocios para conocer su visión.
* Realizar observaciones de los eventos, promociones, festivales... para prestar especial atención a las opiniones de los clientes y obtener un perfil de los mismos.  

Para conocer diferentes herramientas para analizar la usabilidad consultaremos:  

* Artículos de investigación, en páginas como Google Scholar o ResearchGate, acerca de la evaluación de la experiencia de usuario.  
* Libros, manuales y páginas de referencia, como "Dont Make Me Think".  

#### 4 Conocimiento previo

Partimos de unos conocimientos limitados sobre las dos área clave, pues no frecuentamos este tipo de establecimientos, aunque sí es cierto que hemos implementado algunas interfaces de usuario básicas en otros proyectos y tenemos unos conocimientos básicos en esta área.  

-----

### 1.b Competitive Analysis

Empezando por las características comunes de los sitios Web que debemos estudiar, debemos destacar que varios de los negocios propuestos no cuentan con página web propia, sino que para conectar con el público realizan publicaciones en diferentes redes sociales. Estas publicaciones están sobretodo enfocadas a difundir las diferentes actividades y experencias culinarias que proponen. Aquellos negocios que si cuentan con páginas propias, las utilizan de forma similar, aunque ofrecen más servicios como sistemas de reserva.  

En nuestro caso hemos seleccionado "La Taberna De Kafka", un negocio que no cuenta con página propia pero que cuida en cierta medida su imagen en las redes sociales. Creemos que es una buena opción ya que nos permitirá definir hasta que punto es negativo no contar con una web propia, además de comparar los diferentes estilos de comunicación a través de las redes sociales. Para la comparación, utilizaremos una tabla que muestre aspectos acerca de el modelo de negocio, problemas tecnológicos, funcionalidad, usabilidad y fortalezas y debilidades de los mismos.  

![Competitive_Analysis](./P1/competitor_analysis.png)

Como conclusión, podemos afirmar que contar con una página web bien actualizada y funcional es de gran ayuda. Así, creemos que la Taberna De Kafka no está desarrollando esta faceta correctamente, pues muchos de sus competidores cuentan con webs con muchas funcionalidades como la reserva, consulta de precios, consulta de cartas... Por otro lado, debemos darle el punto de las redes sociales a la taberna, pues de las consultadas es la única que mantiene actualizadas sus redes sociales.

-----

### 1.c Personas

Por un lado, tenemos a Natalia, una chica joven, interesada en la cultura, que vive en Granada, y frecuenta asiduamente estos locales en busca de experiencias enriquecedoras que sean una inspiración para su trabajo de guionista. Aunque es sociable, no muchas de sus amistades aprecian ese lado creativo, por lo que estos lugares le ayudan a conectar con personas que también les interesa el arte y la cultura.  

![Persona_1](./P1/Persona_1.png)  

Por otro lado tenemos a Emily, una mujer de 34 años inglesa, que viene a Granada de turista en busca de experiencias gastronómicas y culturalesauténticas. Ha visitado España varias veces y está enamorada de la comida mediterránea. Ahora ha decidido explorar Granada para descubrir su historia, sus tapas y sus vinos.

![Persona_2](./P1/persona2.png)  

-----

### 1.d User Journey Map

Para el primer jouney map hemos seleccionado una experiencia de usuario en la que Natalia, una chica de la zona, decide acudir para desconectar de su trabajo y conocer gente nueva. Lo hemos seleccionado porque representa a la clienta local que busca una experiencia gastronómica y cultural única. Así, podemos observar los intereses del cliente habitual que valora la oferta cultural y gastronómica y la opción de socializar.  

![JouneyMapPersona1](./P1/User_Journey_Map_1.png)  

Para el segundo jounery map hemos descrito una experiencia de usuario de Emily, una turista británica. Emily decide acudir a la taberna para descubrir la gastronomía local y vivir una experiencia auténtica. Representa a la clienta extranjera que busca una inmersión cultural a través de la comida. Así, podemos observar los intereses del turista gastronómico que valora la autenticidad, la historia detrás de los platos y la posibilidad de compartir su experiencia en redes sociales y blogs de viajes.

![JouneyMapPersona2](./P1//User_Journey_Map_2.png)  

-----

### 1.e Usability Review

Tras realizar la revisión de usabilidad podemos concluir que las páginas son correctas en la parte de navegabilidad, funcionanmiento, errores y control, pero estas partes de cierta forma son las correspondientes al marco básico que ofrecen las redes sociales. Por otro lado, flaquea en la búsqueda, la existencia de formularios y procesos y funcionalidades adicionales, para realizar por ejemplo reservas. Creemos que deben centrarse en mejorar estos aspectos y formalizar y mejorar el diseño de las publicaciones para crear una estética acorde a la oferta en sus perfiles.

Enlace al documento: [PDF](./P1/usability_review.pdf) / [Excel](./P1/Usability-review.xlsx)
URL de los lugares seleccionados:  

* <https://www.instagram.com/latabernadekafka/>  
* <https://www.facebook.com/laTabernadeKafka/?locale=es_ES>  

Valoración numérica obtenida: 49 Moderate  

-----

### 1.f Briefing

Tras realizar este estudio y revisión de la usabilidad, hemos llegado a las siguientes conclusiones:

* **Presencia digital limitada**: La Taberna de Kafka es un referente gastronómico en Granada, pero actualmente **no cuenta con una página web**, lo que restringe su capacidad para atraer clientes potenciales, especialmente turistas que buscan información en línea antes de decidir dónde comer.

* **Competencia con funcionalidades avanzadas**: Algunos de sus competidores ofrecen sitios web con **reservas online, consulta de cartas y precios**, lo que facilita la experiencia del usuario y optimiza el proceso de toma de decisiones.

* **Fortaleza en redes sociales**: A diferencia de sus competidores, la taberna mantiene **redes sociales actualizadas**, lo que le permite conectar con su comunidad y compartir novedades. Sin embargo, esto no sustituye la necesidad de una web bien estructurada.

Contar con una **página web funcional y actualizada** permitiría a la Taberna de Kafka **mejorar su accesibilidad, diferenciarse de la competencia y optimizar la experiencia del cliente** desde el primer punto de contacto.

-----

<br>

## Paso 2. UX Design  

### 2.a IDEACION: Feedback Capture Grid

A partir de la práctica anterior, en la que analizamos la experiencia de usuario, hemos identificado tanto aspectos positivos como negativos en la accesibilidad e información que muestra el local en internet. Entre los positivos, podemos destacar que utilizan las redes sociales a menudo, es fácil encontrarlos y contactar, sim embargo, no cuentan con opciones de reserva online ni ofrecen más información como podría ser la carta del local. Para tratar estos problemas proponemos el desarrollo de una página web propia que permita ofrecer todo este tipo de servicios y mejorar así la experiencia del usuario.  

Para organizar todos estos aspectos hemos creado una malla receptora con todas estas ideas.  
![MallaReceptora](./P2/malla_receptora.png)  

Podemos por tanto concluir que el principal problema en la experiencia de usuario es que se limita únicamente a la consulta de información, que en ocasiones puede estar desactualizada, y ni siquiera se ofrecen filtros para la búsqueda.  
Nuestra propuesta de valor consiste por tanto en crear una página web propia que permita:  

* Reservar a través de la web  
* Acceder a información acerca del local en tiempo real (espacio disponible, aviso de productos agotados, tiempo de espera para entrar, nivel de ruido...)
* Implementar un servicio exclusivo basado en invitaciones, parecido a BestSecret o Veepee.
* Mostrar menús y precios así como recomendaciones y enlaces a otros sitios de interés relacionados.  

### 2.b ScopeCanvas

![ScopeCanvar](./P2/scope%20canvas.png)

### 2.b User Flow (task) analysis

#### User Task Matrix

Un "User Task Matrix" es una herramienta que nos servirá para organizar y  visualizar las tareas que podrán realizar los usuarios en nuestra página web. La utilizaremos para mostrar cuales serían las tareas que se podrían realizar y los usuarios que tendrían acceso a las mismas.  

Los usuarios tendríamos dos tipos, el básico y el premium. El segundo serían aquellos que pertenecen al grupo de clientes que se han registrado en la página a través de un código de invitación, para crear ese servicio de venta privada, o acceso privado, que se plantea en la malla receptora.

| Tareas       | Usuario Básico | Usuario  Premium |
|--------------|----------------|------------------|
| Consultar información | :heavy_check_mark: | :heavy_check_mark: |
| Consultar publicaciones | :heavy_check_mark: | :heavy_check_mark: |
| Registrarse (Con un código) | :heavy_check_mark: | :x: |
| Iniciar Sesión | :x: | :heavy_check_mark: |
| Subscribirse a la Newsletter | :heavy_check_mark: | :heavy_check_mark: |
| Consultar la galería de fotos | :heavy_check_mark: | :heavy_check_mark: |
| Reservar una mesa | :heavy_check_mark: | :heavy_check_mark: |
| Reservar plaza en una cata de vino o evento | :x: | :heavy_check_mark: |
| Cancelar reserva | :heavy_check_mark: | :heavy_check_mark: |

#### Task Flow  

A continuación se mostrarán los Task Flow de algunas de las tareas que aparecen en la tabla anterior.  

El primer Task Flow abarca la operación de Reservar plaza en una cata de vino o evento. Podemos ver como para realizar tal acción, el usuario debe iniciar sesión obligatoriamente y una vez hecho esto, se le mostrarán los eventos y podrá inscribirse o reservar para alguno si es de su interés.  

![TaskFlowReservarEvent](P2/reserva_de_evento.png)  

En el segundo Task Flow se muestra como el usuario puede navergar por las publicaciones de la página principal y que ocurre al interaccionar con ellas. Estas publicaciones pueden dividirse en dos grupos, publicación normal, que serían aquellas en las que por ejemplo se comenta la existencia de nuevos vinos en la carta, se promociona una nueva tapa o se comparte una actualización en general del negocio. Las otras publicaciones son las de evento, que sirven para promocionar estos y ofrecer más información acerca de los mismos, como por ejemplo personas invitadas que acudirán o detalles sobre la fecha y la hora. Para facilitar la reserva de mesas o asistencias a eventos existirán enlaces directos desde las publicaciones para estas cuestiones, aunque si no está interesado el usuario siempre puede volver atrás.

![TaskFlowNavegacionEventos](P2/navegar_por_publicaciones.png)

### 2.c IA: Sitemap + Labelling

Diagrama tipo Sitemap de la página y tabla de Labelling asociada al mismo:

![SiteMap](./P2/sitemap.png)

![Labelling](./P2/labelling.png)  

### 2.d Wireframes

Para la elaboración de los bocetos hemos utilizado Figma, lo que nos permite simular la distribución y organización del layout para una página web en un ordenador. Los wireframes realizados son:

#### Página Inicio

Esta sería la página principal que se mostraría al entrar a la web.

![PaginaInicio](./P2/PaginaInicio.png)

#### Página Eventos

Esta sería la página de eventos, la cual muestra todos los eventos ordenados por fecha en una lista desplazable.

![PaginaEventos](./P2/Eventos.png)

#### Página Evento

Se muestra la página de un evento concreto, en la cual se ofrece más informacióna acerca del mismo.

![PaginaEvento](./P2/Evento.png)

#### Página de Reserva

Se muestra a continuación el formulario que el usuario debería rellenar para reservar una mesa o un evento.  
En la parte derecha, se mostraría el horario del local o del evento, y una recomendación de a que hora/día reservar
en función de las necesidades del local y la disponibilidad.

![FormularioReserva](./P2/FormularioReservarMesaEvento.png)

#### Área Cliente - Acceso

Aquí se muestra la página de registro/acceso junto con la newsletter.
El apartado de newsletter permanecerá fijo mientras que el de registro dependerá de si el usuario está o no logueado.

![AreaClienteInvitado](./P2/AREA_CLIENTE_invitado.png)


#### Área Cliente - Mis datos

Aquí encontramos el apartado donde un usuario logueado puede ver y modificar sus datos.

![AreaClienteDatos](./P2/AREA_CLIENTE_misdatos.png)


#### Área Cliente - Mis Código de invitación

Subpágina del área cliente donde se puede visualizar el código de invitación del usuario junto con los usos disponibles.
Además, aquí se explica el funcionamiento del sistema de invitación en el que cada usuario puede invitar a determinado número de nuevos usuarios.

![AreaClienteInvitacion](./P2/AREA_CLIENTE_invitacion.png)


-----
<br>

## Paso 3. Mi UX-Case Study (diseño)

### 3.a Moodboard

A través de este moodboard intentamos definir una guía de estilo visual para nuestra propuesta, una página web que permita realizar reservas, obtener información y en definitiva mejorar la experiencia al visitar la Taberna de Kafka.

Para diseñar el moodboard utilizamos Figma para hacer el diseño del mismo, y otras herramientas como Paletton para escoger la paleta de colores de forma correcta y Fonts de google para establecer las fuentes.

Para diseñar el logotipo utilizamos Figma y Photoshop. El logotipo es un rediseño del cartel actual del local. Para simplificarlo y hacer que funcione como logotipo nos decidimos por escoger la parte más importante del mismo, la K, y para darle un toque que recuerde al vino, más allá de la figura de copa introducida en la sombra de la letra, decidimos utilizar el color principal de la página web para hacer un degradado de color.  

En este moodboard que mostramos a continuación se incluye:

* Un pequeño resumen de nuestro objetivo
* Logotipo
* Fuentes
* Paleta de colores
* Iconos y símbolos a utilizar
* Varias imágenes inspiradoras para nuestro diseño  

![Moodboard](./P3/moodboard.png)

### 3.b Landing Page

Nuestra landing page nace con el objetivo de atraer a aquellas personas interesadas en experiencias gastronómicas únicas, relacionadas principalmente con el vino. Para ello, esta página cuenta con una imagen que se encarga de definir correctamente la temática principal del local, el vino y las catas, y además cuenta con una frase inspirado que muestra la atmósfera que encontrará el cliente en el local. Por otro lado, se describen varios puntos interesantes acerca de la actividad desarrollada y ofrece, en el footer, información adicional como el horario o la ubicación del establecimiento. Antes de este último elemento, encontramos el CTA de la página, un botón de reserva que nos llevará a la página que nos permita reserva una mesa en el local.

Esto permitirá a la taberna atraer a gente con una experiencia visual organizada, limpia, sencilla y directa.

![LandingPage](./P3/landingpage.png)

### 3.c Guidelines

![Método UX](img/guidelines.png)
----

En esta sección explicamos los patrones de diseño utilizados en la versión móvil de nuestro prototipo. Se emplearán componentes reutilizables de direferente librerías además de otros que nosotros mismo diseñaremos. Esto facilitará la coherencia en el diseño, la accesibilidad y la claridad visual tan determinantes en el diseño para dispositivos móviles.

Principalmente utilizaremos los diseños de diferentes librerrías de componentes de figma:

* iOS 18 and iPadOS 18 UI Kit
* Material 3 Design Kit
* Simple Design System

A partir de estos componentes, nosotros hemos utilizado algunos directamente, y reutilizados otros para crear los nuestros propios.
A continuación se presentan en formato imagen los diferentes patrones utilizados entre los que podemos ver:

* Barra de navegación
* Menu 
* Cabecera
* Pie de página
* Botones
* Formulario
* Lista deslizable
* Formularios

![GuideLines](./P3/guidelines.png)

### 3.d Mockup

Para ver el Mockup de nuestra aplicación puedes clickar en el siguiente enlace: [Mockup](https://www.figma.com/proto/H6MAbSNR6fP3zFImcuXvOs/Pagina-Inicio-Mockup?page-id=0%3A1&node-id=1-2&viewport=402%2C181%2C0.2&t=MRlfMIh0oxqF1L89-1&scaling=scale-down&content-scaling=fixed&starting-point-node-id=1%3A2)

### 3.e ¿My UX-Case Study?

Este readme es un resumen del case study realizado.

<br>

## Paso 4. Pruebas de Evaluación

### 4.a Reclutamiento de usuarios

El caso que se nos ha asignado para llevar a cabo el método A/B Testing corresponde al grupo DIU1.AmbosMarcan.  
Podemos encontrar su repositorio de GitHub [aquí](https://github.com/RodriDelo/UX_CaseStudy).

En este caso, se han seleccionado 4 participantes para realizar las pruebas de la aplicación. Esperamos que esta muestra sea representativa de las personas que utilizarán la aplicación, aunque al ser tan pocas personas es probable que esté sesgada de alguna forma.  

|   |   |   |   |   |   |   |   |
|---|---|---|---|---|---|---|---|
|#id. usuario|Sexo/edad|Ocupación|Experiencia internet|Plataforma|Perfil cubierto|TEST|SUS score|
| 1          | 21 Mujer  | Estudiante de Ingeniería Informática | Avanzado | Móvil | A | Todos | 82.5 |
| 2          | 22 Mujer | Estudiante de Ingeniería Informática | Avanzado | Móvil | B | Todos | 42.5 |
| 3          | 59 Mujer  | Ama de casa | Bajo | Móvl | A | Todos | 82.5 |
| 4          | 25 Hombre  | Asesor inmobiliaria | Avanzado | Móvil | B | Todos | 60 |


### 4.b Diseño de las pruebas

Vamos a utilizar la herramienta maze para diseñar y llevar a cabo las pruebas remotas de los usuarios seleccionados. Crearemos dos proyectos, uno para nuestro proyecto (A) y otro para el que debemos evaluar (B).  

En ellos, se realizarán unas cuantas preguntas de control a los usuarios, para obtener un perfil del mismo. A continuación, se realizará una prueba de navegación libre por la página web del proyecto, o se le encomendará una tarea al usuario. Una vez finalizada, la persona deberá contestar nuevamente unas preguntas que hemos considerado interesantes para la evaluación de la web. Finalmente, se le pasará el test SUS para completar la evaluación.

Además de maze, utilizaremos GazeRecorder para realizar una prueba de Eye Tracking sobre los usuarios y obtener mapas de calor de las páginas principales de la web para conocer donde se fijan más nuestros usuarios.

Por tanto, utilizaremos un modelo A/B Testing con las siguientes pruebas:  

* Preguntas de control para conocer el perfil del usuario
* Navegación libre o realización de una tarea en la página web
* Preguntas de evaluación de la web de elaboración propia
* Cuestionario SUS
* Eye Tracking de la web

Finalmente, toda esta información la resumiremos en el Usability Report que realizaremos.  

### 4.c Cuestionario SUS

El cuestionario SUS es una batería de preguntas que se responden según una escalar Likert que sirve para evaluar la usabilidad percibida de un producto o aplicación digital. En este caso, evaluamos la usabilidad de nuestro proyecto y del proyecto B.

En este caso, la puntuación de los cuestionarios para la aplicación A es de 82.5 en ambos casos. Esta aplicación entraría por tanto en la calificación Aceptable. Esto nos muestra que a la gente le ha gustado nuestra aplicación y la recomendaría a sus amigos. Por tanto, podemos decir que la aplicación es intuitiva, fácil de entender y aprender y satisfactoria de usar, que en la mayoría de ocasiones, es lo más importante.

Por otro lado, las puntuaciones del proyecto B son de 60 y 42.5. Podemos afirmar que el diseño de la aplicación no es aceptable, entraría dentro de la calificación de Marginal, muy cerca de lo Inaceptable, pues se encuentra por debajo del umbral mínimo (68). Esto nos indica que la página es complicada de utilizar o no se entiende correctamente por los usuarios. Probablemente sea compleja en términos de navegación y no tenga todas las funcionalidades que se esperaba en un sitio de este tipo.  

A continuación se muestran los test realizados a los usuarios:

[CuestionariosSUS](./P4/cuestionarios_sus.pdf)  

### 4.d A/B Testing

##### Objetivo

Evaluar cuál de las dos aplicaciones web proporciona una mejor experiencia de usuario en términos de navegación, confianza visual, claridad funcional y facilidad de uso.

##### Proceso de Testing

###### 1. **Pregunta de filtrado**

Antes de iniciar la prueba, se realizó una pregunta de filtrado para un posterior estudio de los usuarios testados:

> "¿Usas internet normalmente para comprar o reservar?"


###### 2. **Exploración libre del prototipo**

Utilizando el módulo **Prototype Test** de Maze, se presentó a los usuarios el prototipo navegable de la web. Se les indicó lo siguiente:

> "Navega libremente por toda la aplicación y experimenta todas las funcionalidades que te parezcan relevantes."

###### 3. **Tarea específica por versión**

Además de la navegación libre, se solicitó a los usuarios que completaran una **tarea clave** en función de la versión del prototipo:

* **Versión A:** Reservar una cata de vinos.
* **Versión B:** Añadir un elemento a la cesta.

Esta fase buscó evaluar la claridad y accesibilidad de las funciones principales.

###### 4. **Cuestionario posterior**

Una vez finalizada la navegación y la tarea principal, se les presentó a los usuarios el siguiente cuestionario:

* **¿Te ha parecido sencilla la navegación?**
* **¿El diseño te inspira confianza para comprar o visitar el lugar?**
* **¿Cuánto tiempo le ha llevado la navegación y uso de la Web?**
* **¿El estilo visual refleja adecuadamente el tipo de negocio?**
* **¿Encontraste todas las funcionalidades que esperabas encontrar?**
* **¿Tuviste que hacer muchos clics para encontrar lo que buscabas?**

##### Resultados

Tras realizar las pruebas y analizar los resultados, podemos concluir que la aplicación A es más usable que la aplicación B ya que obtiene mejor puntuación tanto en el cuestionario SUS como en las respuestas a las cuestiones propias planteadas. Además los mapas de calor del eye tracking, que se explican a continuación, son más coherentes en A.  

### 4.e Aplicación del método Eye Tracking

Para realizar la prueba de Eye Tracking hemos utilizado la herramienta GazeRecorder. Esto nos ha permitido obtener mapas de calor acerca de donde centran los usuarios la atención. Se realizaron varias pruebas, una a cada usuario, que nos permitió obtener un par de muestras para cada proyecto.  

Se dió un tiempo de 6 segundos para cada imagen.

Entre los puntos de interés que podemos encontrar en los bocetos del proyecto A encontramos:

* Página de Inicio: Información en tiempo real del local y botón de reserva para el evento de la semana.
* Página de Eventos: Fecha, títulos y bótones de saber más y reservar.
* Página de un Evento Específico: Título e información importante.  
* Página de Reserva de Mesa: Fecha y Hora.

Entre los pintos de interés que podemos encontrar de los bocetos del proyecto B encontramos:  

* Landing page: Botón de inicio.
* Página de Registro: Campos a rellenar y el botón de registro.
* Página de Inicio: Recomendados y los 3 botones centrales.
* Página de Compra Habitual: Botones de la parte inferior. 

A continuación se encuentran dos pdfs con los resultados:

[ResultadosA](./P4/EyeTrackingA.pdf)
[ResultadosB](./P4/EyeTrackingB.pdf)

En ambos casos, se muestra como la mayoría de las areas de interés definidas son donde se centra la atención de los usuarios.

### 4.f Usability Report de B

![Método UX](img/usability-report.png)
-----

>>> Añadir report de usabilidad para práctica B (la de los compañeros) aportando resultados y valoración de cada debilidad de usabilidad.
>>> Enlazar aqui con el archivo subido a P4/ que indica qué equipo evalua a qué otro equipo.

>>> Complementad el Case Study en su Paso 4 con una Valoración personal del equipo sobre esta tarea

<br>

## Paso 5. Exportación y Documentación

### 5.a Exportación a HTML/React

![Método UX](img/usabilityReview.png)
----

>>> Breve descripción de esta tarea. Las evidencias de este paso quedan subidas a P5/

### 5.b Documentación con Storybook

![Método UX](img/usabilityReview.png)
----

>>> Breve descripción de esta tarea. Las evidencias de este paso quedan subidas a P5/

<br>

## Conclusiones finales & Valoración de las prácticas

>>> Opinión FINAL del proceso de desarrollo de diseño siguiendo metodología UX y valoración (positiva /negativa) de los resultados obtenidos. ¿Qué se puede mejorar? Recuerda que este tipo de texto se debe eliminar del template que se os proporciona
