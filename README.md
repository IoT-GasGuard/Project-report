# Project-report
<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Ingeniería de Software</strong><br>
    <strong>Desarrollo de Soluciones IOT - 2968</strong><br>
    <strong>Profesor: Marco Antonio Leon Baca</strong><br>
    <br>INFORME
</p>
<p align="center">
    <strong>Startup:  GasGuard</strong><br>
    <strong>Producto:  GasGuard</strong>
</p>
    <h3 align="center">Team Members:</h3>
    </div>
<div>
     <table align="center">
        <tr>
            <th style="text-align:center;">Member</th>
            <th style="text-align:center;">Code</th>
        </tr>
        <tr>
            <td>Alvarez Araguache, Samira Jetzabel</td>
            <td>U20211A046</td>
        </tr>
	<tr>
            <td>Llacchua Peralta, Joseph Ulysses</td>
            <td>u202317002</td>
        </tr>
        <tr>
            <td>Quilla Luyo, Jorge Gerardo</td>
            <td> u20211b197</td>
        </tr>
        <tr>
            <td>Ramirez Contreras, Zaid Valentino</td>
            <td>U202218472</td>
        </tr>
         <tr>
            <td>Ticona Luque, Rony Piero</td>
            <td>u201420422</td>
        </tr>
    </table>
</div>

<p align="center">
    <strong>2025</strong>
</p>

<br>

# Registro de Versiones del Informe
<table>
        <tr>
            <th style="text-align:center;">Versión</th>
            <th style="text-align:center;">Fecha</th>
            <th style="text-align:center;">Autor</th>
            <th style="text-align:center;">Descripción de la modificación</th>
        </tr>
        <tr>
            <td align = "center">TB1</td>
            <td>18/04/2025</td>
            <td> Grupo 2
            <td>Se agregó el contenido del capítulo 1, apartados 1.1, 1.2 y 1.3; el contenido del capítulo 2, apartados 2.1, 2.2, 2.3, 2.4; el contenido del capítulo 3, apartados 3.1, 3.2, 3.3 y 3.4; el contenido del capítulo 4, apartados 4.1 y 4.2</td>
        </tr>
</table>
<br>

# Tabla de Contenidos

- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)
- [Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
  - [4.1. Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
    - [4.1.1. EventStorming](#411-eventstorming)
      - [4.1.1.1. Candidate Context Discovery](#4111-candidate-context-discovery)
      - [4.1.1.2. Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
      - [4.1.1.3. Bounded Context Canvases](#4113-bounded-context-canvases)
    - [4.1.2. Context Mapping](#412-context-mapping)
    - [4.1.3. Software Architecture](#413-software-architecture)
      - [4.1.3.1. System Landscape Diagram](#4131-software-architecture-system-landscape-diagram)
      - [4.1.3.2. Context Level Diagrams](#4132-software-architecture-context-level-diagrams)
      - [4.1.3.3. Container Level Diagrams](#4133-software-architecture-container-level-diagrams)
      - [4.1.3.4. Deployment Diagrams](#4134-software-architecture-deployment-diagrams)
  - [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
    - [4.2.X. Bounded Context](#42x-bounded-context-bounded-context-name)
      - [4.2.X.1. Domain Layer](#42x1-domain-layer)
      - [4.2.X.2. Interface Layer](#42x2-interface-layer)
      - [4.2.X.3. Application Layer](#42x3-application-layer)
      - [4.2.X.4. Infrastructure Layer](#42x4-infrastructure-layer)
      - [4.2.X.5. Component Level Diagrams](#42x5-component-level-diagrams)
      - [4.2.X.6. Code Level Diagrams](#42x6-code-level-diagrams)
        - [4.2.X.6.1. Domain Layer Class Diagrams](#42x61-domain-layer-class-diagrams)
        - [4.2.X.6.2. Database Design Diagram](#42x62-database-design-diagram)
- [Capítulo V: Solution UI/UX Design](#capítulo-v-solution-uiux-design)
  - [5.1. Style Guidelines](#51-style-guidelines)
    - [5.1.1. General Style Guidelines](#511-general-style-guidelines)
    - [5.1.2. Web, Mobile and IoT Style Guidelines](#512-web-mobile-and-iot-style-guidelines)
  - [5.2. Information Architecture](#52-information-architecture)
    - [5.2.1. Organization Systems](#521-organization-systems)
    - [5.2.2. Labeling Systems](#522-labeling-systems)
    - [5.2.3. SEO Tags and Meta Tags](#523-seo-tags-and-meta-tags)
    - [5.2.4. Searching Systems](#524-searching-systems)
    - [5.2.5. Navigation Systems](#525-navigation-systems)
  - [5.3. Landing Page UI Design](#53-landing-page-ui-design)
    - [5.3.1. Wireframe](#531-wireframe)
    - [5.3.2. Mock-up](#532-mock-up)
  - [5.4. Applications UX/UI Design](#54-applications-uxui-design)
    - [5.4.1. Wireframes](#541-wireframes)
    - [5.4.2. Wireflow Diagrams](#542-wireflow-diagrams)
    - [5.4.3. Mock-ups](#543-mock-ups)
    - [5.4.4. User Flow Diagrams](#544-user-flow-diagrams)
  - [5.5. Applications Prototyping](#55-applications-prototyping)
- [Capítulo VI: Product Implementation, Validation & Deployment](#capítulo-vi-product-implementation-validation--deployment)
  - [6.1. Software Configuration Management](#61-software-configuration-management)
    - [6.1.1. Development Environment Configuration](#611-development-environment-configuration)
    - [6.1.2. Source Code Management](#612-source-code-management)
    - [6.1.3. Style Guide & Conventions](#613-style-guide--conventions)
    - [6.1.4. Deployment Configuration](#614-deployment-configuration)
  - [6.2. Implementation](#62-implementation)
    - [6.2.X. Sprint n](#62x-sprint-n)
      - [6.2.X.1. Sprint Planning](#62x1-sprint-planning)
      - [6.2.X.2. Aspect Leaders and Collaborators](#62x2-aspect-leaders-and-collaborators)
      - [6.2.X.3. Sprint Backlog](#62x3-sprint-backlog)
      - [6.2.X.4-8. Sprint Review Evidences](#62x4-8-sprint-review-evidences)
      - [6.2.X.9. Team Collaboration Insights](#62x9-team-collaboration-insights)
  - [6.3. Validation Interviews](#63-validation-interviews)
    - [6.3.1. Diseño](#631-diseño)
    - [6.3.2. Registro](#632-registro)
    - [6.3.3. Evaluaciones](#633-evaluaciones)
  - [6.4. Video About-the-Product](#64-video-about-the-product)
- [Conclusiones y Recomendaciones](#conclusiones-y-recomendaciones)
- [Video About-the-Team](#video-about-the-team)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

---

# Student Outcome

# Student Outcome
<table >
        <tr>
            <th style="text-align:center;">Criterio específico</th>
            <th style="text-align:center;">Acciones realizadas</th>
            <th style="text-align:center;">Conclusiones</th>
        </tr>
        <tr>
            <td align = "center">Trabaja en equipo para
proporcionar liderazgo en
forma conjunta</td>
            <td> 

Alvarez Araguache, Samira Jetzabel <br>
**TB1** <br>
Para esta entrega, el trabajo se llevó a cabo de manera cooperativa, involucrando a todos los integrantes en el desarrollo de las tareas del proyecto. Para la realización de las entrevistas fue parte fundamental la participación de cada miembro en la recolección de información clave para definir las funcionalidades de nuestra solución. Asímismo, el uso de Gitflow facilitó un flujo de trabajo eficiente, permitiendo a cada miembro contribuir al desarrollo de la documentación de manera coordinada y fluida. 

Ramirez Contreras, Zaid Valentino <br>
**TB1** <br>
En esta etapa, el trabajo se hizo en conjunto donde cada integrante aportó su conocimiento y habilidad para el diseño del proyecto. Se usaron, además, herramientas para la creación de las user personas que nos ayudaran a entender correctamente y en su totalidad las necesidades de nuestro segmento objetivo e idear un plan de acción para abarcarlas.

Quilla Luyo, Jorge Gerardo <br>
**TB1** <br>
En esta entrega, se usaron herramientas visuales para la elaboración de escenarios donde nuestra propuesta resuelve la problemática planteada. Además, se usó un formato estándar y entendible para redactar los requerimientos de nuestros segmentos objetivos. La información recolectada por cada integrante del equipo fue necesario para la correcta elaboración de cada punto en esta entrega y así estar todos coordinados.

Ticona Luque, Rony Piero <br>
**TB1** <br>
En esta entrega, se utilizó una herramienta de modelado C4 en Structurizr para el desarrollo de los diagramas de contexto, contenedores y componentes que serán implementados en el proyecto. Además, se emplearon herramientas como Lucidchart y Vertabelo para crear los diagramas de las bases de datos. También se realizaron entrevistas para identificar y comprender mejor las necesidades del segmento de público objetivo, lo cual fue fundamental para definir las funcionalidades clave del proyecto.
 
Llacchua Peralta, Joseph Ulysses <br>
**TB1** <br>
En esta entrega, trabajamos en la definición de metas claras, distribuyendo responsabilidades según las habilidades individuales mientras manteníamos un propósito colectivo. Mediante una planificación colaborativa, establecimos hitos y mecanismos de seguimiento que permitieron ajustar estrategias de manera ágil. Este proceso no solo optimizó la eficiencia, sino que también reforzó la confianza y el compromiso mutuo.


</td>
         <td> TB1: Conclusiones <br>
		 El trabajo en equipo durante esta entrega demostró un liderazgo colaborativo, donde cada integrante aportó sus habilidades para alcanzar los objetivos comunes. Mediante herramientas como Gitflow, Structurizr, Lucidchart y entrevistas, logramos una coordinación eficiente, una comprensión profunda de las necesidades del usuario y una documentación bien estructurada. Este enfoque no solo optimizó el flujo de trabajo, sino que también fortaleció la cohesión del grupo, asegurando un avance sólido y alineado hacia el éxito del proyecto.
</td>         

  <tr>
            <td align = "center">Crea un entorno colaborativo e
inclusivo, establece metas,
planifica tareas y cumple
objetivos</td>
            <td>

Alvarez Araguache, Samira Jetzabel  <br>
**TB1** <br>
En esta etapa del proyecto, se logró determinar el estado actual del mercado relacionado con soluciones tecnológicas orientadas a la seguridad del hogar, en particular aquellas vinculadas a IoT y detección de fugas de gas. Este análisis permitió identificar fortalezas y debilidades de productos similares, así como plantear estrategias para diferenciar a GasGuard, posicionándolo como una solución accesible, confiable y centrada en el usuario. Además, se profundizó en el comportamiento, necesidades y motivaciones de los potenciales usuarios mediante entrevistas y ejercicios de empatía, lo que permitió establecer los objetivos principales del proyecto a largo plazo.

Ramirez Contreras, Zaid Valentino <br>
**TB1** <br>
Para esta entrega se identificaron los usuarios objetivos del proyecto, por lo que se analizaron sus habilidades, necesidades y frustraciones para diseñar el producto de manera que pueda cumplir de manera eficiente todas estas cosas. Además se identificaron los competidores para conocer las distintas tacticas y funciones que ofrecen para poder mejorar y apuntar a objetivos mas especifico y asi diferenciarnos de la competencia. Todo este estudio se llevo a cabo para ofrecer la mejor version de la solucion IoT y asi atacar eficientemente al problema al que se dirige nuestro proyecto.

Quilla Luyo, Jorge Gerardo <br>
**TB1** <br>
En esta entrega, se logró redactar las historias de usuario, tomando en cuenta los posibles módulos de nuestra solución propuesta. También se priorizaron estos requerimientos para agilizar el desarrollo de las principales necesidades identificadas. Además, se realizó escenarios donde nuestra solución lograr satisfacer necesidades, resolver problemas y marcar una diferencia frente a la competencia.

Ticona Luque Rony Piero <br>
**TB1** <br>
En esta entrega del proyecto, se avanzó en la definición y diseño de la solución tecnológica. Se desarrollaron diagramas de contexto, contenedores y componentes utilizando herramientas de modelado C4 en Structurizr, estableciendo una base sólida para la arquitectura del sistema. Adicionalmente, se emplearon Lucidchart y Vertabelo para crear diagramas detallados de las bases de datos. Adicional de realizaron entrevistas del segmento objetivo para profundizar en la comprensión de sus necesidades, expectativas y problemas clave.

Llacchua Peralta, Joseph Ulysses <br>
**TB1** <br>
Durante esta fase, prioricé la creación de un espacio de trabajo en equipo, integrando diversas perspectivas y fortaleciendo la comunicación. Realizamos una revisión conjunta de la literatura existente, analizamos los segmentos objetivos de manera participativa y exploramos metodologías de resolución de problemas en conjunto. Este enfoque inclusivo permitió enriquecer el proyecto con aportes diversos y fomentar un sentido de pertenencia en el equipo.

</td>
            <td>TB1: Conclusiones<br>
            n esta etapa del proyecto, el equipo logró consolidar los fundamentos estratégicos, técnicos y centrados en el usuario para el desarrollo de GasGuard. A través de un análisis exhaustivo del mercado y la competencia, se identificaron oportunidades clave para posicionar nuestra solución IoT como una alternativa accesible y diferenciada en seguridad del hogar.

La investigación con usuarios permitió definir requerimientos prioritarios y diseñar historias de usuario alineadas a sus necesidades reales, mientras que el modelado arquitectónico (diagramas C4, bases de datos) sentó las bases técnicas para el desarrollo. El trabajo colaborativo, apoyado en metodologías ágiles y herramientas como Structurizr y Lucidchart, facilitó la integración de perspectivas diversas y aseguró una planificación eficiente.

</td>
       <tr>
</table>

<br>

---

# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
GasGuard nace como respuesta a la falta de soluciones autónomas frente a las fugas de gas licuado en hogares, donde es necesaria la intervención humana para mitigar estas emergencias. 

Esta propuesta busca implementar tecnología del internet de las cosas (IoT) que, al detectar una fuga de gas, sea capaz de aplicar de manera innmediatas medidas de seguridad que reduzcan el riesgo de explosiones e incendios.


### Misión
Proteger a las personas y sus hogares con una solución simple, eficaz y segura ante situaciones de riesgo.

### Visión
Ser una empresa referente en el ámbito de la seguridad con tecnología IoT, centrados en innovar y transformar los hogares inteligentes.

### 1.1.2. Perfiles de integrantes del equipo
<table border="1" width="70%" style="text-align:center;">
    <tr align="center">
        <td rowspan="3">
            <img src="./assets/team_img/gerardo.jpeg" alt="Gerardo Quilla"  style="margin-bottom: 5px;" width="600"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>
            Jorge Gerardo Quilla Luyo
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ingeniería de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
        Estudiante de la carrera de ingeniería de software, tengo experiencia en los lenguajes de programación de java, python y c#, me considero una persona puntual y comprometida con los trabajos en grupo. Me esfuerzo en comunicar los resultados e investigar temas nuevos por cuenta propia.
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
            <img src="./assets/team_img/piero.jpeg" alt="Piero Ticona"  style="margin-bottom: 5px;" width="600"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>
            Rony Piero Ticona Luque            
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ingeniería de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
        Estudiante de la carrera de Ingeniería de Software con experiencia en lenguajes de programación como Java, Python y Flutter. Además, poseo conocimientos en el uso de Power BI para el análisis y visualización de datos. Me considero una persona responsable, dedicada y conprometida con los proyectos de la universidad.
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
            <img src="https://media.licdn.com/dms/image/v2/D4E03AQESEoiwSF0wVg/profile-displayphoto-shrink_200_200/profile-displayphoto-shrink_200_200/0/1711066191126?e=1750291200&v=beta&t=MjZOYpRFS9wjwe28DYvAkiGW4LOsiI8pupY9ohTLhbM" alt="Joseph" style="margin-bottom: 5px;" width="150"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>
            Joseph Ulysses Llacchua Peralta 
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ingeniería de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
        Soy un estudiante de la carrera de Ingeniería de Software, con experiencia en lenguajes de programación como Java, TypeScript y C#. Soy una persona comprometida con lo que me propongo, puntual, responsable y con habilidades para trabajar en equipo.
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
            <img src="./assets/team_img/zaid.png" alt="Zaid Ramirez"  style="margin-bottom: 5px;" width="600"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>
            Zaid Valentino Ramirez Contreras 
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ingeniería de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
        Soy estudiante de la carrera de Ingeniería de Software, con conocimientos en Java, C++, python, javascript, entre otros. Soy alguien que le gusta aprender constantemente, además soy comunicativo y responsable. Espero seguir aprendiendo acerca de herramientas y habilidades que me puedan ser de utilidad en el futuro.
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
        <img src="https://raw.githubusercontent.com/Open-Source-SW54-Group-3-ArtCollab/Report/develop/assets/images/Samira-Alvarez-photo.jpg" alt="Samira Alvarez Araguache"  style="margin-bottom: 5px;" width="600"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Samira Jetzabel Alvarez Araguache
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ingeniería de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
        Soy una estudiante de ingeniería de software con experiencia en los lenguajes de programación C++, C# y JavaScript. Soy una persona comunicativa, capaz de trabajar eficazmente con mi equipo y con habilidades para liderar y gestionar proyectos.
        </td>
    </tr>
</table>

## 1.2. Solution Profile
Esta parte del contendo se encuentra dividida en dos partes:
- Antecedentes y Problemática: En este apartado se identifica la problemática que el proyecto busca a resolver. Se incluye el plantamento del problema, los aspectos más relevantes que la solución debe considerar y los objetivos y limitaciones que se esperan del proyecto. 
- Lean UX Process: En esta sección se implementa el enfoque Lean UX. Se describe de manera detallada la manera en la que se abordará la problemática según el modelo de negocio del proyecto. 
 
### 1.2.1. Antecedentes y problemática
### Antecedentes:

En la actualidad, el avance en la tecnología ha transformado nuestra interacción con nuestro entorno. Dichos avances han ganado fuerza en el ámbito doméstico, donde la integración con distintas tecnologías ha llevado a la creación del concepto de "hogares inteligentes". El internet de las cosas (IoT) ha formado una parte crucial de este proceso, aportando bienestar y comodidad facilitando tareas y optimizando el consumo de recursos. Sin embargo, la mayoría de estas soluciones se enfocan más en la comodidad, y no en la seguridad de los habitantes antes situaciones de riesgo.

En el caso de Perú, las fugas de gas licuado son la cuarta emergencia más recurrente. Solo en el año 2024 se registró un total de 5787 casos, mientras que en el primer trimestre del año 2025, ya se han contabilizado 1096, sin tomar en cuenta aquellos que escalaron a incendios (Cuerpo general de bomberos voluntario del Perú, 2025). Muchos de estos casos involucran el uso de gas domestico (Pereyra, 2020). 

Pese a existir sistemas de detección ante estas situaciones, la mayoría se limitan a emitir señales visuales o auditivas, por lo que todavía se requiere intervención humana para mitigar y comunicar este tipo de emergencias. Esta limitación deja expuestos tanto a los vecinos como a los residentes de la vivienda ante a estas amenazas.

Frente a este contexto, surge GasGuard como un sistema inteligente ante fugas de gas. Con el uso de tecnología IoT, se ejecutan medidas automáticas antes este tipo de emergencia, con protocolos de seguridad como la apertura de puertas, ventanas y corte de sistemas eléctricos, activación de señales visuales, así como notificaciones a los miembros del hogar y los servicios de emergencia. Mientras tanto, en condiciones normales, GasGuard se integra como un gestor inteligente de iluminación, controlando la intensidad de las luces del innmueble según la luz ambiental. 

### Problemática (5Ws y 2Hs)
### What/Qué
#### ¿Cuál es el problema?
Los hogares inteligentes muchas veces optan por la comodidad y conveniencia, descuidando situaciones de riesgo. La gran parte de sensores de detección requieren intervención humana inmediata para tomar acciones contra una fuga de gas. Estos se limitan a emitir señales visuales o sonoras, por lo que se tiene una respuesta más pasiva sobre estos incidentes.

### Where / Dónde
#### ¿Dónde está el usuario cuando usa el producto?
El usuario puede encontrarse en cualquier lugar, siempre y cuando tenga conexión a internet. Gracias a la naturaleza de los dispositivos IoT, es posible interactuar con GasGuard de manera remota, ya sea desde un teléfono inteligente o una computadora, siendo más accesible que los sistemas tradicionales de alarma.

#### ¿Dónde surge el problema?
El problema surge dentro del hogar, específicamente en zonas con instalaciones de gas o donde el uso de GLP es recurrente como en cocinas y lavanderías.

### Why / Por Qué
#### ¿Cuál es la causa del problema?
La causa del problema incluye factores como la necesidad de los sistemas tradicionales de alarma de requerir intervención humana, así como la falta de integración con otros sistemas del hogar para una reacción inmediata. Estas circunstancias aumentan la vunerabilidad de las familias en el hogar ante una fuga de gas.

### When / Cuándo
#### ¿Cuándo sucede el problema?
El problema puede suceder en cualquier momento, especialmente cuando no se han tomado medidas preventivas para reducir las posibilidades de una fuga de gas. Esto empeora cuando no hay personas en casa que puedan actuar rápida.   

### Who / Quién
#### ¿Quiénes están involucrados?
Los involucrados son principalmente las personas residentes de hogares que utilizan gas licuado. 

#### ¿A quién le sucede el problema?
El problema perjudica a cualquier persona que cuente con una instalación de gas licuado. Esto incluye a personas que viven solas, familias y condominios donde una fuga de gas puede tener consecuencias de mayor alcance.

#### ¿Quién lo utilizará?
Lo utilizaría cualquier persona que quiera mejorar la seguridad de su casa usando tecnología IoT. Esto incluye a familias que buscan hacer su hogar un espacio más seguro, así como adultos mayores o personas con problemas de movilidad que puedan tener dificultades a la hora de actuar en caso de una emergencia.

### How / Cómo
#### ¿En qué condiciones los usuarios usan nuestro producto?
Los usuarios utilizarían el sistema como parte de su hogar inteligente, siendo un complemento junto con otros dispositivos IoT en este tipo de viviendas. De manera predeterminada, GasGuard cumple con la función de regular la iluminación según el ambiente cuando la persona se encuentre en casa. Por otra parte, sus protocolos de seguridad se activan en caso de emergencia, ya sea que el usuario esté en su vivienda o fuera de ella.

#### ¿Cómo nos conocieron los usuarios?
Los usuarios pueden conocer el sistema a través de:
- Publicaciones o anuncios en plataformas de redes sociales como Instagram, Twitter, Facebook, TikTok, etc.
- Campañas de publicidad en línea mediante SEO en nuestra página web y artículos en periódicos o blogs.
- Eventos y exposiciones de tecnología IoT centrados en la domótica.
- Recomendaciones de usuarios actuales a amigos o familiares interesados en iniciar o complementar su hogar inteligente implementando un sistema de seguridad.

#### ¿Cómo prefieren los usuarios acceder a nuestro servicio?
Los usuarios prefieren acceder desde cualquier lugar de manera sencilla y conveniente. Por ello, pueden gestionar el sistema por medio de una aplicación web accesible desde computadoras de escritorio. Sin embargo, la mayoría de usuarios valoran la disponibilidad de una aplicación móvil, donde pueden recibir notificaciones a tiempo real sobre el estado de su hogar, así como controlar de manera remota los dispositivos del sistema.

### How much / Cuánto
El impacto del problema es considerable, especialmente teniendo en cuenta la cantidad de incidentes reportados anualmente relacionados a fugas de gas licuado. Las consecuencias de este tipo de emergencias implican un grave riesgo la integridad de las personas, así como perdidas materiales significativas. Por ello, es invaluable un sistema que pueda anticiparse ante este tipo de situaciones, que permita un accionar rápido que proteja no solo a una familia y sus bienes, sino también a los vecinos y a edificaciones de su entorno.

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem statements

En Perú,el gas licuado es uno de los principales combustibles de energía domestica en cocinas, termas, calefacción, etc. Esto implica un mayor riesgo de sufrir alguna fuga de gas. Pese a esta amenaza, muchos hogares no cuentan con un sistema de seguridad que sea capaz de detectar y actuar frente a este tipo de emergencias. 

Hemos observado que, pese a que en el mercado existen detectores de gas, estos se limitan a mostrar alarmas visuales o sonoras, sin tomar medidas para mitigar la fuga. Así mismo, muchas personas no saben como reaccionar ante estas situaciones, ya sea por desconocimiento o temor. 

¿Cómo podríamos crear una solución accesible, confiable y automatizada que detecte de una fuga de gas, tome medidas de seguridad de manera innmediata para proteger a los habitantes de una vivienda y pueda integrarse en un hogar inteligente?

#### 1.2.2.2. Lean UX Assumptions
#### Features

- Detección a tiempo real de fuga de gas licuado: Sensores de gas para detectar altas concentraciones de GLP.
- Activación automática de protocolos de seguridad: Alerta visual, corte del suministro eléctrico y apertura de ventanas y puertas ante una fuga de gas.
- Notificaciones inteligentes: Envío de mensajes de texto a contactos seleccionados en la app y alertas a servicios de emergencia.
- Modo en reposo: Control inteligente de la iluminación en condiciones normales.
- Estado e historial: Aplicación para la consulta del estado actual del sistema y el historial de alertas.


#### Business Outcomes
- Aumento de usuarios: Mayor demanda de integración de sistemas automatizados de seguridad.
- Reducción de accidentes por fuga de gas: Reducir incidentes generadas como consecuencias de una fuga de gas doméstica.
- Reconocimiento de marca: Establecer GasGuard como lider en soluciones de seguridad para hogares inteligentes.
- Ingresos sostenibles: Ejecutar un modelo de ingreso en base a la venta e instalación de dispositivos, así como suscripciones en la aplicación para producir beneficios.

#### Users
Los usuarios serán principalmente aquellas personas que viven en hogares que emplean uso de GLP y busquen un sistema de seguridad ante fugas de gas que sea autónomo.

#### User Outcomes & Benefits
- Mayor seguridad en casos de fugas de gas: Disminuición del estrés por quedar en riesgo de sufrir accidentes debido a una fuga de GLP.
- Respuesta inmediata: Ejecución de sistemas de seguridad automáticas antes la detección de una fuga de gas.
- Integración como gestor de iluminación: Controlador inteligente de luces en el inmueble según la luz ambiental o intervención del usuario.
- Prevención de fugas: Informes, estadísticas y estadísticas acerca de los niveles de gas licuado en el inmueble.

#### User assumptions
#### ¿Quién es el usuario?
El usuario es cualquier persona que desee mejorar la seguridad en su hogar ante la amenzada de una fuga de gas.
#### ¿Dónde encaja nuestro producto en sus trabajos o vidas?
Nuestro producto se integra en la vida diaria de nuestros usuarios como un sistema de seguridad instalado en su hogar para actuar en situaciones de emergencia, donde podrá monitorearlo desde una aplicación web y móvil.
#### ¿Qué problema resuelve nuestro producto?
Nuestro producto reduce los incidentes producidos por fugas de gas licuado, ya sea por ausencia de personas en la vivienda, la presencia de personas que no puedan reaccionar de manera rápida o el desconocimiento de los protocolos a seguir en caso de este tipo de emergencias.
El sistema ofrece una respuesta automática ante la detección de una fuga de gas, alertando a las personas dentro o fuera de la vivienda, así como ejecutando protocolos de seguridad físicos sin necesitar intervención humana.
#### ¿Cuándo y cómo es usado nuestro producto?
- Funciona 24/7 desde que el sistema en instalado en el hogar del usuario.
- Cuando los niveles de gas son normales, controla de manera automática los niveles de luz en el inmueble. El usuario también puede gestionar la iluminación mediante la aplicación móvil.
- Cuando se detecta niveles altos de gas, se ejecutan medidas de seguridad para disminuir el riesgo ante fugas de gas. El usuario puede revisar el nivel de gas desde sus dispositivos.
#### ¿Qué características son importantes?
- Sistema de alerta: El sistema debe detectar y notificar de manera rápida los niveles anormales de gas licuado en el aire.
- Respuesta automática: Se ejecutan protocolos de seguridad de manera autónoma sin necesitar intervención humana.
- Control remoto: El usuario puede controlar el nivel de luminosidad en el hogar, así como abrir/cerrar ventanas o puertas de su vivienda desde cualquier dispositivo.
- Reportes: Reportes e historial acerca de los niveles de gas en el inmueble y el estado de los dispositivos asociados al sistema.

#### ¿Cómo debería verse y comportarse nuestro producto?
- Interacción simple: Un rápido flujo de interacción para cada acción que pueda realizar el usuario.
- Comportamiento predecible: Funcionamiento fluido, sin comportamientos inesperados o errores de conexión con los dispositivos asociados al sistema.
- Comunicación clara: Informar de manera simple el estado actual del sistema y las acciones disponibles.

#### Business Assumptions
1. **Creemos que nuestros clientes necesitan** una solución tecnológica confiable que actúe y detecte de manera innmediata una fuga de gas en sus hogares, así como ayude en la gestión inteligente en el hogar. 
2. **Estas necesidades se pueden resolver con un** un sistema IoT con sensores de gas que automatice la respuesta ante una fuga de gas (apertura de ventanas o puertas, corte de electricidad, notificaciones, etc) y pueda ser controlado de manera remota.
3. **El valor #1 que mi cliente quiere de mi servicio** es un sistema íntegro, que le permita sentirse seguro ante este tipo de emergencias, incluso estando fuera de casa.
4. **El cliente también puede obtener beneficios adicionales como** 
- Control de iluminación según la luz ambiental.
- Reportes acerca de los niveles de gas en el hogar e historial de alertas.
- Gestión remota del sistema mediante plataformas web y móvil.
5. **Voy a adquirir la mayoría de mis clientes** mediante marketing digital en redes sociales, asociaciones con inmobiliarias o empresas de gas y ferias o eventos de tecnología y seguridad.
6. **Haré dinero a través de** la venta directa e instalación del sistema, así como un modelo freemium de suscripción para brindar funcionalidades avanzadas.
7. **Mi competencia principal en el mercado** serán detectores de gas, otras soluciones IoT con acción limitada y alarmas tradicionales sin respuesta autónoma.
8. **Los venceremos debido a** nuestro elemento diferenciador: acción inmediata ante un accidente. De igual manera, ofreceremos un modo reposo, que se integrará junto a otros dispositivos smart-home para la gestión inteligente de iluminación.
9. **El mayor riesgo es que** no cumplamos con las expectativas de seguridad de nuestros usuarios y la desconfianza hacia los sistemas automatizados en el hogar.
10. **Resolveremos esto a través de** pruebas pilotos, demostraciones en vivo y testimonios de clientes, así como la mejora continua de nuestro sistema ante el feedback de nuestros usuarios.

#### 1.2.2.3. Lean UX Hypothesis Statements
### Hipótesis 1:
**Creemos que** cuando los protocolos de seguridad sean ejecutados de manera autónoma en caso de una fuga de gas, los usuarios se sentirán más protegidos por el sistema.
**Sabremos que** hemos tenido éxito **cuando** al menos el 70% de usuarios consultados en los primeros 6 meses de uso manifiesten sentirse más seguros gracias a la respuesta automática de la solución.

### Hipótesis 2:
**Creemos que** al integrar un sistema de control de iluminación inteligente aumentará el valor percibido por el cliente de la solución.
**Sabremos que** hemos tenido éxito **cuando** al menos el 60% de usuarios utilicen de manera diaria esta función después del primer mes de instalación.

### Hipótesis 3:
**Creemos que** al ejecutar cortes automáticos del suministro de seguridad, así como la apertura de ventanas/puertas al detectar niveles anormales de gas cuando se detecte una fuga de gas, se disminuirá el riesgo de incendios, explosiones e intoxicaciones en las viviendas.
**Sabremos que** hemos tenido éxito **cuando** no se reporten accidentes graves como consecuencias de una fuga de gas en los hogares con el sistema activado durante los primeros 12 meses.

### Hipótesis 4:
**Creemos que** implementar un modelo de suscripción freemium ofreciendo funciones adicionales avanzadas, incrementaremos la monetización del sistema.
**Sabremos que** hemos tenido éxito **cuando** observemos que al menos el 20% de nuestros clientes adquieran una suscripción premium durante el primer año.


#### 1.2.2.4. Lean UX Canvas
<TABLE BORDER>
	<TR>
		<TD ROWSPAN=2>

**Lean UX Canvas**
</TD>
	    	<TD ROWSPAN=2></TD> <TD>

**Fecha:** 10/04/2025

</TD> 
	</TR>
	<TR>
		<TD>

**Iteración 1**
</TD> 
	</TR>
    <TR>
		<TD ROWSPAN>
        
**1. Problema de negocios:**
        
En Perú,el gas licuado es uno de los principales combustibles de energía domestica en cocinas, termas, calefacción, etc. Esto implica un mayor riesgo de sufrir alguna fuga de gas. Pese a esta amenaza, muchos hogares no cuentan con un sistema de seguridad que sea capaz de detectar y actuar frente a este tipo de emergencias. 

Hemos observado que, pese a que en el mercado existen detectores de gas, estos se limitan a mostrar alarmas visuales o sonoras, sin tomar medidas para mitigar la fuga. Así mismo, muchas personas no saben como reaccionar ante estas situaciones, ya sea por desconocimiento o temor. 

¿Cómo podríamos crear una solución accesible, confiable y automatizada que detecte de una fuga de gas, tome medidas de seguridad de manera innmediata para proteger a los habitantes de una vivienda y pueda integrarse en un hogar inteligente?

</TD>
	    	<TD ROWSPAN=2>

**5. Ideas de solución:**
- Detección de fugas de gas inmediata mediante sensores IoT.
- Acciones automáticas de seguridad ante fugas de gas como: corte del servicio eléctrico, apertura de ventanas/puertas, alertas visuales y sonoras, etc.
- Notificaciones de alerta a contactos seleccionados y a servicios de emergencia mediante la app móvil o sms.
- Historial de eventos y monitereo remoto desde una aplicación web/móvil.
- Gestor de iluminación inteligente en condiciones normales.
</TD> <TD ROWSPAN=2>

**2. Resultados comerciales:**
- Tasa de conversión del 15% de usuarios gratuitos a suscriptores premium para acceder a funciones avanzadas.
- Retención del 80% de clientes durante el primer año del sistema.
- Integración en al menos el 5% de casas con servicios de gas licuado o con hogares inteligentes.
- Reducción en un 85% de accidentes graves generados por fugas de gas en viviendas.
</TD> 
	</TR>
	<TR>
		<TD >
        
**3. Usuarios y Clientes:**
Principalmente familias, adultos mayores, personas con movilidad reducida y cualquier usuario que utilice gas licuado en su hogar.
</TD> 
	</TR>
    <TR>
		<TD ROWSPAN=2>

**6. Hipótesis**
        
**Creemos que** cuando los protocolos de seguridad sean ejecutados de manera autónoma en caso de una fuga de gas, los usuarios se sentirán más protegidos por el sistema.
**Sabremos que** hemos tenido éxito **cuando** al menos el 70% de usuarios consultados en los primeros 6 meses de uso manifiesten sentirse más seguros gracias a la respuesta automática de la solución.

**Creemos que** al integrar un sistema de control de iluminación inteligente aumentará el valor percibido por el cliente de la solución.
**Sabremos que** hemos tenido éxito **cuando** al menos el 60% de usuarios utilicen de manera diaria esta función después del primer mes de instalación.

**Creemos que** al ejecutar cortes automáticos del suministro de seguridad, así como la apertura de ventanas/puertas al detectar niveles anormales de gas cuando se detecte una fuga de gas, se disminuirá el riesgo de incendios, explosiones e intoxicaciones en las viviendas.
**Sabremos que** hemos tenido éxito **cuando** no se reporten accidentes graves como consecuencias de una fuga de gas en los hogares con el sistema activado durante los primeros 12 meses.

**Creemos que** implementar un modelo de suscripción freemium ofreciendo funciones adicionales avanzadas, incrementaremos la monetización del sistema.
**Sabremos que** hemos tenido éxito **cuando** observemos que al menos el 20% de nuestros clientes adquieran una suscripción premium durante el primer año.</TD>

<TD ROWSPAN=2>

**7. ¿Qué es lo más importante que debemos aprender primero?**
- El tiempo mínimo de reacción del sistema ante una fuga de gas para que esta sea efectiva para el usuario y pueda tomar medidas.
- El nivel de confianza de los usuarios en las respuestas de sistemas automatizados de seguridad.
- Que tan efectivas pueden ser las medidas que toma el sistema para evitar accidentes mayores.
- Que tan dispuestos están los usuarios para adquirir una suscripcion premium.
</TD> 

<TD>

**4. Beneficios del usuario:**
- Mayor seguridad y protección ante una fuga de gas.
- Posibilidad de actuar de manera remota sin encontrarse en el inmueble en caso de una emergencia.
- Gestión automática de iluminación según la luz ambiental.
- Reducción de accidentes graves como consecuencia de una fuga de gas.

</TD> 
	</TR>
	<TR>
		<TD>
        
**8. ¿Cuál es la menor cantidad de trabajo que necesitamos para resolver las dudas y para hacer lo siguiente más importante?**
- Crear un prototipo funcional integrado a una aplicación web/móvil.
- Realizar simulacros y pruebas con usuarios reales.
- Validar la percepción el usuario con el sistema antes y después de su uso.
- Desarrollar un análisis de mercado para detectar puntos de mejora o nuevas necesidades del segmento objetivo. 
- Plantear estrategias de marketing para promocionar el sistema y su aplicación.
</TD> 
	</TR>
</TABLE>

## 1.3. Segmentos Objetivo
<TABLE BORDER>
	<TR>
		<TD>

**Tipo de usuario**</TD> <TD>

**Geográfico** </TD> <TD>

**Psicográfico**</TD> <TD>

**Demográfico**</TD>
</TR>
	<TR>
		<TD>Personas con vivienda propia o alquilada</TD> <TD> Zonas urbanas en distritos residenciales y ciudades en crecimiento.</TD> 
        <TD>

Preocupado por la seguridad de su vivienda o las personas que viven en ella. Interesado en la integración de soluciones tecnológicas en el hogar. Priorizan la automatización de procesos.

</TD> 
<TD>

- Edad: Desde jóvenes adultos hasta personas mayores.
- Educación: Educación básica hasta educación superior.

</TABLE>


---

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

### 2.1.1. Análisis competitivo
| **Categoría**               | **Honeywell** <br><img src="./assets/competitors/honeywell.png" alt="img" style="margin-bottom: 5px;" width="100"/>                                                                 | **Siemens** <br><img src="./assets/competitors/siemens.png" alt="img" style="margin-bottom: 5px;" width="100"/>                                                                | **Johnson Controls** <br> <img src="./assets/competitors/johnson_ctrl.png" alt="img" style="margin-bottom: 5px;" width="100"/>                                                         |
|----------------------------|-------------------------------------------------------------------------------|---------------------------------------------------------------------------|------------------------------------------------------------------------------|
| **Perfil**                 |                                                                               |                                                                           |                                                                              |
| Overview                | Empresa líder en soluciones de detección y control de gases, con amplio respaldo internacional. | Multinacional especializada en automatización e integración IoT para seguridad. | Líder global en la gestión integral de edificios y sistemas de seguridad.   |
| Ventaja competitiva     | Alta fiabilidad, robusta red técnica y variedad de soluciones.                | Alta integración con sistemas BMS existentes, escalabilidad.              | Fuerte presencia global y experiencia en múltiples sectores.                |
| **Perfil de marketing**    |                                                                               |                                                                           |                                                                              |
| Mercado objetivo        | Hogares, empresas e industrias.                                               | Edificios inteligentes y corporativos.                                    | Infraestructura, sector salud, retail.                                      |
| Estrategias de marketing| Campañas digitales, distribuidores y ferias tecnológicas.                    | Marketing B2B, eventos y alianzas corporativas.                           | Consultoría técnica, contenido técnico y enfoque en seguridad.             |
| **Perfil de producto**     |                                                                               |                                                                           |                                                                              |
| Productos y Servicios   | Detectores de gas, alarmas y plataformas conectadas.                          | Sensores de gas, monitoreo IoT y automatización.                          | Sistemas de gestión de edificios, IoT y detección ambiental.                |
| Precios y Costos        | Segmento medio-alto con énfasis en fiabilidad.                               | Soluciones premium a medida.                                              | Altamente variable según proyecto.                                          |
| Canales de distribución | Web, App móvil y red de distribuidores.                                       | Red de partners, app móvil y web.                                         | Venta directa y vía distribuidores.                                         |
| Fortalezas              | Innovación constante, soporte técnico robusto.                                | Soluciones modulares y amplia escalabilidad.                              | Integración completa, experiencia técnica.                                  |
| Debilidades             | Costos elevados para pequeños proyectos.                                      | Complejidad en integración.                                               | Alto costo inicial.                                                         |
| Oportunidades           | Expansión en LATAM y nuevos hogares smart.                                    | Integración con IA y cloud.                                               | Creciente demanda en automatización.                                        |
| Amenazas                | Nuevos competidores low-cost.                                                 | Competencia asiática y precios bajos.                                     | Nuevas startups con soluciones ágiles.                                      |

### 2.1.2. Estrategias y tácticas frente a competidores
| Competidores | ¿Que se puede hacer para ganarle a la competencia?|
|--------------|---------------------------------------------------|
| Honeywell    |Ofrecer una solución más accesible y especializada para hogares, con menor costo y mayor automatización inmediata (sin depender de instalaciones complejas).|
|Siemens|Presentar un producto más simple y enfocado en seguridad doméstica, evitando la complejidad y el enfoque corporativo de Siemens.|
|Johnson Controls|Aprovechar la agilidad de una startup para innovar más rápido y con una solución más adaptable y fácil de instalar en viviendas comunes, no solo en grandes infraestructuras.|

## 2.2. Entrevistas


### 2.2.1. Diseño de entrevistas

**Uso actual y percepcion de seguridad**
1. ¿Actualmente usas algún sistema para detectar fugas de gas en tu hogar?

2. ¿Cómo actuarías ante una fuga de gas? ¿Tienes un plan o herramienta que te ayude?

3. ¿Qué tan seguro/a te sientes en tu hogar respecto al uso de gas?

**Expectativas sobre una app de seguridad doméstica**

4. Si existiera una app que te avisara automáticamente sobre una fuga de gas y tomara acciones de seguridad por ti, ¿qué funcionalidades te parecerían imprescindibles?

5. ¿Te gustaría que la app se conecte con otros dispositivos del hogar (ventanas, luces, puertas, etc.)? ¿Con cuáles específicamente?

6. ¿Qué tipo de notificaciones preferirías recibir (sonido, vibración, mensaje, llamada, etc.)?

**Preferencias de diseño y experiencia de usuario**

7. ¿Cómo debería ser la interfaz de una app así para que te resulte fácil de usar?

8. ¿Qué tan cómodo/a te sientes usando apps relacionadas con seguridad del hogar?

9. ¿Te gustaría tener un panel con el estado en tiempo real de los sensores o solo alertas cuando haya problemas?

**Oportunidades de mejora / feedback**

10. Si ya usaste alguna app de seguridad o domótica, ¿qué aspectos te gustaron y cuáles no?

11. ¿Qué crees que podría mejorar una app de seguridad como esta para que realmente confíes en ella?

12. ¿Estarías dispuesto/a a pagar por una app que proteja tu hogar de forma automática? ¿Qué precio te parecería justo?

### 2.2.2. Registro de entrevistas

<strong>Entrevista 1</strong>

Entrevistador: Jorge Gerardo Quilla Luyo

Entrevistado: Jorge Carlos Quilla Luyo

Edad: 18 años

Residencia: Lima - La Victoria

<a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u20211b197_upc_edu_pe/ERD-BT5hLC5EpKAYPNymmsUB043RTDuk0x3Hc6QE13G2pA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=1CcGsV">Link a la entrevista</a>

<img src="./assets/interviews/entrevista_jorge_quilla.png" alt="Entrevista Jorge Quilla">

**Resumen:**

Se entrevistó a Jorge Carlos, joven de 18 años estudiante de la carrera de Derecho. Actualmente no cuenta con un dispositivo inteligente que sea capaz de detectar fugas de gas en ambientes de su hogar. Ante una fuga de gas, él y su familia conocen que medidas tomar, tales como abrir puertas y ventanas, y no encender las luces, además, en caso sea posible, usan una medida de contención, la cual consiste en poner un trapo mojado en la boca del balón de gas, así para  reducir la salida de gas momentáneamente y tener tiempo para llamar a servicios de emergencia.

Jorge Carlos piensa que contar con una aplicación que te permita visualizar en tiempo real los niveles de gas en el ambiente serían de mucha ayuda, siempre y cuando tengan baja incertidumbre y tenga la mejor precisión en cuanto a los datos. También cree que las notificaciones a servicios de emergencia son muy importantes en caso la situación de fuga de gas se agrave. Menciona que recibir un mensaje y la inclusión de un sonido como tipo de notificación son necesarios para que una persona pueda darse cuenta de la fuga de gas detectada y así pueda tomar acciones.

<strong>Entrevista 2</strong>

Entrevistador: Diego Nicolas Ramirez Rodriguez

Entrevistado: Diego Nicolas Ramirez Rodriguez

Edad: 20 años

Residencia: Lima - San Felipe

<a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202218472_upc_edu_pe/EY2xMPNuv5ZFhTiGBvLWvTcBq1WC5vwQnOJlPXIKIMxn_Q?e=rskZbD&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D" >Link a la entrevista</a>

<img src="./assets/interviews/entrevista_diego_ramirez.png" alt="Entrevista Diego Ramirez">

**Resumen:**
Se entrevisto a Diego Nicolas, joven de 20 años estudiante de la carrera de Ingeniería de Sistemas. Actualmente no tiene algun dispositivo capaz de detectar algun tipo de fuga o reaccionar al respecto.

Él menciona que el considera que sería una buena opcion con contar con un dispositivo inteligente que le pueda notificar en caso haya una fuga de gas, a pesar de estar lejos del punto de fuga. Además de contar con una funcion para reaccionar ante la fuga de gas, como por ejemplo abrir ventanas o puertas. Tambien le gustaria tener un panel de control donde pueda ver el estado de los sensores y el historial de eventos. En cuanto a las notificaciones, menciona que le gustaria recibir una alarma que se pueda configurar, ya que no siempre tiene el celular a la mano. Finalemnte menciona que en otra aplicacion que ha usado, le gustaria que la interfaz sea sencilla y amigable, ya que pueden tener mucho texto y funciones que interrumpen la experiencia de usuario.



<strong>Entrevista 3</strong>

Entrevistador: Rony Piero Ticona Luque

Entrevistado: Alexandra Mariella Cabezas

Edad: 29 años

Residencia: Lima - Breña

<a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u201420422_upc_edu_pe/ER6IMmm720xKssiJipPkNDgBu0oYowaPz2dTQ_KsdV0Vlw?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=KqPf7q">Link a la entrevista</a>

<img src="./assets/interviews/entrevista_piero_ticona.png" alt="Entrevista Piero Ticona">

Resumen:

Se entrevistó a Alexandra Cabezas, licenciada en Derecho y Ciencias Políticas de 29 años. Actualmente no cuenta con un sistema para detectar fugas de gas en su hogar. Ante una fuga, indica que sus acciones serían cerrar las llaves de paso y abrir ventanas para ventilar el ambiente. Expresa preocupación por el uso de gas, especialmente porque en su hogar hay personas mayores de más de 80 años que en ocasiones han dejado la llave de gas abierta accidentalmente.

Considera que una aplicación que detecte fugas y tome acciones automáticas sería muy útil, sobre todo si puede alertar mediante notificaciones sonoras y vibración, similares a las alertas de sismos. También ve valioso que la app ventile el ambiente, informe a familiares y pueda cortar el circuito eléctrico en caso necesario. Mencionó la posibilidad de vincular la app con puertas y luces de emergencia.

Para ella, es importante que la interfaz sea dinámica y clara, con acceso al estado del ambiente en tiempo real. Aunque no ha usado apps similares, le interesa una que permita conexión desde cualquier dispositivo mediante cuenta y contraseña. Confía en aplicaciones que tengan actualizaciones constantes y buen rendimiento. Finalmente, estaría dispuesta a pagar hasta S/ 70 mensuales por este servicio.

### 2.2.3. Análisis de entrevistas

Las entrevistas realizadas muestran una clara preocupación por la seguridad frente a fugas de gas en el hogar, especialmente por la ausencia actual de sistemas inteligentes que permitan detectar y actuar ante estos eventos. Todos los entrevistados valoran la posibilidad de implementar una solución basada en IoT que permita monitorear en tiempo real los niveles de gas en el ambiente, con datos precisos y de baja incertidumbre. Además, consideran fundamental que esta solución no solo alerte mediante notificaciones eficaces (mensajes, sonidos, alarmas configurables o vibración), sino que también sea capaz de ejecutar acciones automáticas como abrir ventanas, cortar la energía eléctrica o cerrar válvulas de gas. Un punto recurrente es la importancia de contar con una interfaz intuitiva, dinámica y amigable, que brinde acceso inmediato al estado del sistema, al historial de eventos y que funcione desde cualquier dispositivo mediante autenticación segura. También se resalta la utilidad de permitir la conexión con servicios de emergencia o familiares, sobre todo en hogares donde hay personas mayores, como en el caso de Alexandra. Por otro lado, se observa una disposición positiva hacia el uso de tecnología si esta es confiable, tiene buen rendimiento y se mantiene actualizada, llegando incluso a considerar un pago mensual por el servicio. En resumen, los entrevistados expresan una necesidad latente por soluciones IoT domésticas centradas en seguridad, automatización, conectividad remota y facilidad de uso, lo que valida la viabilidad y el valor de una propuesta tecnológica en este ámbito.

## 2.3. Needfinding

### 2.3.1. User Personas

<img src="./assets/user_personas/persona1.png" alt="img" style="margin-bottom: 5px;" width="500"/><br>   
<img src="./assets/user_personas/persona2.png" alt="img" style="margin-bottom: 5px;" width="500"/><br>
<img src="./assets/user_personas/persona3.png" alt="img" style="margin-bottom: 5px;" width="500"/><br>  

### 2.3.2. User Task Matrix
| Tarea                            | Carolina (Madre de familia) | Jorge (Adulto mayor) | Claudia (Usuario tecnologico) |
|----------------------------------|-----------------------------|-------------------------|------------------------------|
| Instalar el dispositivo          | Medio                       | Bajo                    | Alto                         |
| Configurar desde la app         | Medio                       | Bajo                    | Alto                         |
| Recibir alertas de fuga         | Alto                        | Medio                   | Alto                         |
| Ver historial de eventos        | Medio                       | Bajo                    | Alto                         |
| Controlar iluminación           | Medio                       | Bajo                    | Alto                         |
| Usar botón físico de emergencia | Bajo                        | Alto                    | Alto                         |
| Contactar soporte técnico       | Medio                       | Medio                   | Alto                         |
| Recomendar a otros              | Alto                        | Bajo                    | Alto                         |

### 2.3.3. User Journey Mapping
<img src="./assets/journey_map.png" alt="img" style="margin-bottom: 5px;" width="500"/>

### 2.3.4. Empathy Mapping

<img src="./assets/empathy_maps/Empathy_map1.png" alt="img" style="margin-bottom: 5px;" width="500"/><br>
<img src="./assets/empathy_maps/Empathy_map2.png" alt="img" style="margin-bottom: 5px;" width="500"/><br>
<img src="./assets/empathy_maps/Empathy_map3.png" alt="img" style="margin-bottom: 5px;" width="500"/><br>

### 2.3.5. As-is Scenario Mapping

<img src="./assets/scenario-mapping/as-is.png" alt="as-is scenario mapping">

Link al Miro: <a href="https://miro.com/app/board/uXjVIDkps3Q=/?moveToWidget=3458764624540110425&cot=14">As-Is Scenario Mapping - GasGuard</a>

## 2.4. Ubiquitous Language

<strong>Dispositivo IoT:</strong> Integra el sensor de gas, el microcontrolador y los actuadores. Se encarga de detectar niveles de gas, procesar la información y ejecutar acciones automáticas en caso de emergencia.
<br><br>
<strong>Sensor de gas:</strong> Sensor de gas MQ-135, es un componente que mide la concentración de gases en el ambiente. Su lectura constante permite detectar posibles fugas de gas en zonas como la cocina, lavandería, etc.
<br><br>
<strong>Actuadores:</strong> Son dispositivos controlados electrónicamente que ejecutan respuestas físicas, como cortar la energía eléctrica, abrir ventanas o activar luces de emergencia cuando se detecta un nivel peligroso de gas.
<br><br>
<strong>Aplicación móvil:</strong> Interfaz desde la cual los usuarios monitorean el estado de su hogar, visualizan niveles de gas en tiempo real, reciben notificaciones y controlan funciones del sistema GasGuard, incluso de manera remota.
<br><br>
<strong>Gráfica en tiempo real:</strong> Representación visual dinámica que muestra la evolución del nivel de gas detectado por el sensor. Facilita al usuario la comprensión de la situación y la detección de patrones o irregularidades.
<br><br>
<strong>Notificación SMS:</strong> Alerta enviada automáticamente por mensaje de texto a los usuarios registrados o a los servicios de emergencia cuando se detecta una fuga crítica.
<br><br>
<strong>Protocolos de emergencia:</strong> Conjunto de acciones automáticas que se activan cuando se detecta una fuga peligrosa de gas. Incluyen la activación de alarmas, notificaciones, cortes eléctricos y apertura de ventilación.
<br><br>
<strong>Servicios de emergencia:</strong> Entidades externas como bomberos o compañías de gas que pueden ser notificadas automáticamente por el sistema ante una emergencia. Su inclusión busca acelerar la respuesta y mitigar el riesgo.
<br><br>
<strong>Iluminación inteligente:</strong> Función del sistema que regula la intensidad de las luces del hogar en base a la luz ambiental. También puede adaptarse a situaciones de emergencia, activando señales visuales para alertar a los ocupantes.


---

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

<img src="./assets/scenario-mapping/to-be.png" alt="to-be scenario">

Link al Miro: <a href="https://miro.com/app/board/uXjVIDkps3Q=/?moveToWidget=3458764624540224366&cot=14">To-Be Scenario Mapping - GasGuard</a>

## 3.2. User Stories

<table>
  <thead>
    <tr>
      <th>Epic ID</th>
      <th>Título</th>
      <th>Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>E1</td>
      <td>Monitoreo y respuesta del sensor</td>
      <td>
        Como usuario
        <br>
        Quiero que el sensor detecte gases peligrosos
        <br>
        Para tomar medidas necesarias
      </td>
    </tr>
    <tr>
      <td>E2</td>
      <td>Visualización de datos</td>
      <td>
        Como usuario
        <br>
        Quiero visualizar las lecturas del sensor en tiempo real
        <br>
        Para conocer el estado de la calidad del aire
      </td>
    </tr>
    <tr>
      <td>E3</td>
      <td>Notificaciones y alertas</td>
      <td>
        Como usuario
        <br>
        Quiero enviar notificaciones y alertas a miembros de mi familia o conocidos, y a servicios de emergencia
        <br>
        Para que tomen las acciones necesarias
      </td>
    </tr>
    <tr>
      <td>E4</td>
      <td>Gestión de usuarios</td>
      <td>
        Como usuario
        <br>
        Quiero acceder a la aplicación móvil
        <br>
        Para gestionar mi cuenta      
      </td>
    </tr>
    <tr>
      <td>E5</td>
      <td>Desarrollo del backend</td>
      <td>
        Como desarrollador
        <br>
        Quiero construir una api rest, integrar servicios y distribuir los datos del sensor
        <br>
        Para que la información sea recibida por la aplicación móvil, otros actuadores, y se ejecuten las acciones necesarias      
      </td>
    </tr>
    <tr>
      <td>E6</td>
      <td>Diseño de Landing Page</td>
      <td>
        Como visitante del sitio
        <br>
        Quiero visualizar una página antarctica y clara
        <br>
        Para conocer características y propósito de la aplicación      
      </td>
    </tr>
  </tbody>
</table>

<br>

<table>
  <thead>
    <tr>
      <th>Epic/<br>Story ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Criterio de aceptación</th>
      <th>Epic ID</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US01</td>
      <td>Detectar fuga de gas</td>
      <td>
        <strong>Como </strong>usuario
        <br>
        <strong>Quiero </strong>que el sensor detecte niveles de gas en el ambiente
        <br>
        <strong>Para </strong>que pueda identificar si son peligrosos
      </td>
      <td>
        <strong>Escenario 1: Detección de gas por encima del límite</strong>
        <br>
        <strong>Dado que </strong>el sensor está monitoreando el nivel de gas en el ambiente
        <br>
        <strong>Cuando </strong>detecte una concentración de gas mayor al límite permitido
        <br>
        <strong>Entonces </strong>se activa una alerta de fuga de gas
        <br><br>
        <strong>Escenario 2: Detección de gas dentro del límite establecido</strong>
        <br>
        <strong>Dado que </strong>el sensor está monitoreando el nivel de gas en el ambiente
        <br>
        <strong>Cuando </strong>detecte una concentración de gas dentro del límite permitido
        <br>
        <strong>Entonces </strong>el sensor continúa monitoreando el nivel de gas en el ambiente
      </td>
      <td>E1</td>
    </tr>
    <tr>
      <td>US02</td>
      <td>Ejecutar protocolos de seguridad</td>
      <td>
        <strong>Como </strong>usuario
        <br>
        <strong>Quiero </strong>que el sensor ejecute protocolos de seguridad cuando detecte niveles de gas peligrosos
        <br>
        <strong>Para </strong>reducir riesgos durante una fuga
      </td>
      <td>
        <strong>Escenario 1: Ejecución de protocolos</strong>
        <br>
        <strong>Dado que </strong>el sensor se encuentra monitoreando el nivel de gas en el ambiente
        <br>
        <strong>Cuando </strong>detecte que el nivel de gas sobrepasa el límite
        <br>
        <strong>Entonces </strong>abrirá puertas y ventanas
        <br>
        <strong>Y </strong>cortará sistemas eléctricos
        <br>
        <strong>Y </strong>activará señales visuales
        <br><br>
        <strong>Escenario 2: Protocolos en espera</strong>
        <br>
        <strong>Dado que </strong>el sensor se encuentra monitoreando el nivel de gas en el ambiente
        <br>
        <strong>Cuando </strong>detecte que el nivel de gas se encuentra dentro del límite
        <br>
        <strong>Entonces </strong>los protocolos de seguridad permanecerán a la espera
      </td>
      <td>E1</td>
    </tr>
    <tr>
      <td>US03</td>
      <td>Ajustar automáticamente la iluminación</td>
      <td>
        <strong>Como </strong>usuario
        <br>
        <strong>Quiero </strong>que las luces del ambiente se ajusten automáticamente a un nivel adecuado
        <br>
        <strong>Para </strong>tener suficiente iluminación durante la fuga de gas
      </td>
      <td>
        <strong>Escenario 1: Ajustar intensidad de la luz</strong>
        <br>
        <strong>Dado que </strong>el sensor se encuentra monitoreando el nivel de gas en el ambiente
        <br>
        <strong>Cuando </strong>detecte que el nivel de gas sobrepasa el límite
        <br>
        <strong>Entonces </strong>se ajustará automaticamente la intensidad de las luces en el ambiente
        <br><br>
        <strong>Escenario 2: Luces en intensidad normal</strong>
        <br>
        <strong>Dado que </strong>el sensor se encuentra monitoreando el nivel de gas en el ambiente
        <br>
        <strong>Cuando </strong>el nivel de gas se encuentra dentro del límite
        <br>
        <strong>Entonces </strong>la intensidad de las luces permanecen normales
      </td>
      <td>E1</td>
    </tr>
    <tr>
      <td>US04</td>
      <td>Visualizar lecturas del sensor</td>
      <td>
        <strong>Como </strong>usuario
        <br>
        <strong>Quiero </strong>ver en tiempo real las lecturas del sensor
        <br>
        <strong>Para </strong>estar informado de los niveles de gas en el ambiente
      </td>
      <td>
        <strong>Escenario 1: Visualización de datos en una gráfica</strong>
        <br>
        <strong>Dado que </strong>el sensor se encuentra monitoreando el nivel de gas en el ambiente
        <br>
        <strong>Cuando </strong>envíe datos en tiempo real a la aplicación móvil
        <br>
        <strong>Entonces </strong>se mostrarán los datos en una gráfica intuitiva
        <br><br>
        <strong>Escenario 2: Fallo en recepción de datos</strong>
        <br>
        <strong>Dado que </strong>el sensor se encuentra monitoreando el nivel de gas en el ambiente
        <br>
        <strong>Cuando </strong>la aplicación no reciba lecturas
        <br>
        <strong>Entonces </strong>se mostrará un mensaje indicando error al capturar datos
      </td>
      <td>E2</td>
    </tr>
    <tr>
      <td>US05</td>
      <td>Generar reporte</td>
      <td>
        <strong>Como </strong>usuario
        <br>
        <strong>Quiero </strong>que se genere un reporte sobre los niveles de gas que se detectaron
        <br>
        <strong>Para </strong>tomar precauciones necesarias
      </td>
      <td>
        <strong>Escenario 1: Generar reporte de última fuga de gas</strong>
        <br>
        <strong>Dado que </strong>el sensor detectó una fuga de gas
        <br>
        <strong>Y </strong>ya se tomaron acciones necesarias
        <br>
        <strong>Cuando </strong>ingreso a la aplicación de GasGuard
        <br>
        <strong>Entonces </strong>tengo la opción de generar un reporte sobre el último incidente
        <br>
        <strong>Y </strong>puedo tomar las respectivas precauciones para evitar más problemas en un futuro
        <br><br>
        <strong>Escenario 2: Reporte con niveles bajos de gas</strong>
        <br>
        <strong>Dado que </strong>el sensor se encuentra monitoreando el nivel de gas en el ambiente
        <br>
        <strong>Cuando </strong>ingreso a la aplicación de GasGuard
        <br>
        <strong>Y </strong>tengo la opción de generar un reporte sobre el último incidente
        <br>
        <strong>Entonces </strong>visualizo datos de niveles de gas normales sin lecturas peligrosas
      </td>
      <td>E2</td>
    </tr>
    <tr>
      <td>US06</td>
      <td>Notificar a miembros del hogar</td>
      <td>
        <strong>Como </strong>usuario
        <br>
        <strong>Quiero </strong>que la aplicación notifique a los miembros registrados
        <br>
        <strong>Para </strong>que tomen sus medidas necesarias
      </td>
      <td>
        <strong>Escenario 1: Notificar alerta a miembros registrados en la aplicación</strong>
        <br>
        <strong>Dado que </strong>tengo a otros usuarios registrados en la aplicación
        <br>
        <strong>Cuando </strong>se detecte niveles peligrosos de gas en el ambiente
        <br>
        <strong>Entonces </strong>se notificará a esos usuarios
        <br><br>
        <strong>Escenario 2: Notificaciones de calma a miembros registrados en la aplicación</strong>
        <br>
        <strong>Dado que </strong>tengo a otros usuarios registrados en la aplicación
        <br>
        <strong>Cuando </strong>se detecte niveles de gas dentro del límite
        <br>
        <strong>Entonces </strong>se notificarán a otros usuarios con mensajes de calma
      </td>
      <td>E3</td>
    </tr>
    <tr>
      <td>US07</td>
      <td>Alertar a servicios de emergencia</td>
      <td>
        <strong>Como </strong>usuario
        <br>
        <strong>Quiero </strong>que la aplicación notifique a servicios de emergencia cuando se detecte una fuga de gas
        <br>
        <strong>Para </strong>que actúen rapidamente
      </td>
      <td>
        <strong>Escenario 1: Alertar a servicios de emergencia</strong>
        <strong>Dado que </strong>el sensor está monitoreando los niveles de gas del ambiente
        <br>
        <strong>Y </strong>está enviando datos en tiempo real a la aplicación
        <br>
        <strong>Cuando </strong>la gráfica muestre niveles de gas peligrosos
        <br>
        <strong>Entonces </strong>se enviará una alerta a los servicios de emergencia
        <br><br>
        <strong>Escenario 2: Sin alteraciones en la gráfica</strong>
        <br>
        <strong>Dado que </strong>el sensor está monitoreando los niveles de gas del ambiente
        <br>
        <strong>Y </strong>está enviando datos en tiempo real a la aplicación
        <br>
        <strong>Cuando </strong>detecte niveles de gas por debajo del límite
        <br>
        <strong>Entonces </strong>no se enviarán alertas a los servicios de emergencia
      </td>
      <td>E3</td>
    </tr>
    <tr>
      <td>US08</td>
      <td>Visualizar historial de alertas</td>
      <td>
        <strong>Como </strong>usuario
        <br>
        <strong>Quiero </strong>visualizar el historial de alertas
        <br>
        <strong>Para </strong>estar informado de las notificaciones y alertas que se enviaron
      </td>
      <td>
        <strong>Escenario 1: Visualizar historial de notificaciones y alertas</strong>
        <br>
        <strong>Dado que </strong>el sensor está enviando datos en tiempo real a la aplicación
        <br>
        <strong>Y </strong>se detectaron niveles de gas peligrosos
        <br>
        <strong>Cuando </strong>se envíen notificaciones o alertas
        <br>
        <strong>Entonces </strong>puedo ver un historial
        <br>
        <strong>Y </strong>ver detalles de cada notificación o alerta enviada
        <br><br>
        <strong>Escenario 2: Historial de alertas vacío</strong>
        <br>
        <strong>Dado que </strong>el sensor está enviando datos en tiempo real a la aplicación
        <br>
        <strong>Cuando </strong>no se detecten niveles de gas peligrosos
        <br>
        <strong>Entonces </strong>el historial estará vacío
      </td>
      <td>E3</td>
    </tr>    
    <tr>
      <td>US09</td>
      <td>Registrar usuario</td>
      <td>
        <strong>Como </strong>usuario
        <br>
        <strong>Quiero </strong>crear una cuenta
        <br>
        <strong>Para </strong>acceder a la aplicación y sus funciones
      </td>
      <td>
        <strong>Escenario 1: Registro exitoso</strong>
        <br>
        <strong>Dado que</strong> el usuario ingresa por primera vez a la aplicación
        <br>
        <strong>Cuando</strong> llene el formulario
        <br>
        <strong>Y</strong> presione Registrar cuenta
        <br>
        <strong>Entonces</strong> la aplicación muestra un mensajje que confirma la creación de su cuenta
        <br><br>
        <strong>Escenario 2: Registro fallido</strong>
        <br>
        <strong>Dado que</strong> el usuario ingresa por primera vez a la aplicación
        <br>
        <strong>Cuando</strong> llene solo algunos campos del formulario
        <br>
        <strong>Y</strong> presione Registrar cuenta
        <br>
        <strong>Entonces</strong> la aplicación muestra un mensajje que indica que hubo un error al crear la cuenta
      </td>
      <td>E4</td>
    </tr>
    <tr>
      <td>US10</td>
      <td>Iniciar sesión</td>
      <td>
        <strong>Como </strong>usuario 
        <br>
        <strong>Quiero </strong>iniciar sesión
        <br>
        <strong>Para </strong>acceder a la aplicación y sus funciones
      </td>
      <td>
        <strong>Escenario 1: Inicio de sesión exitoso</strong>
        <br>
        <strong>Dado que</strong> el usuario está en la aplicación
        <br>
        <strong>Y</strong> selecciona iniciar sesión
        <br>
        <strong>Cuando</strong> llene el formulario con sus credenciales
        <br>
        <strong>Y</strong> la aplicación valida sus datos
        <br>
        <strong>Entonces</strong> el usuario ingresa al contenido de la aplicación
        <br><br>
        <strong>Escenario 2: Inicio de sesión fallido</strong>
        <br>
        <strong>Dado que</strong> el usuario está en la aplicación
        <br>
        <strong>Y</strong> selecciona iniciar sesión
        <br>
        <strong>Cuando</strong> llene el formulario con sus credenciales
        <br>
        <strong>Y</strong> la aplicación detecta que sus credenciales no son correctas
        <br>
        <strong>Entonces</strong> la aplicación muestra un mensaje indicando que sus datos son incorrectos
      </td>
      <td>E4</td>
    </tr>
    <tr>
      <td>US11</td>
      <td>Recuperar contraseña</td>
      <td>
        <strong>Como </strong>usuario 
        <br>
        <strong>Quiero </strong> recibir un correo
        <br>
        <strong>Para </strong>reestablecer mi contraseña
      </td>
      <td>
        <strong>Escenario 1: Recuperación de contraseña exitosa</strong>
        <br>
        <strong>Dado que</strong> el usuario ingresa a la aplicación
        <br>
        <strong>Y</strong> selecciona Olvidé mi contraseña
        <br>
        <strong>Cuando</strong> llene el formulario con su correo electrónico
        <br>
        <strong>Y</strong> la aplicación valida que el correo existe
        <br>
        <strong>Entonces</strong> se envía un enlace a su correo para que el usuario ingrese una nueva contraseña
        <br><br>
        <strong>Escenario 2: Recuperación de contraseña fallido</strong>
        <br>
        <strong>Dado que</strong> el usuario ingresa a la aplicación
        <br>
        <strong>Y</strong> selecciona Olvidé mi contraseña
        <br>
        <strong>Cuando</strong> llene el formulario con su correo electrónico
        <br>
        <strong>Y</strong> la aplicación no logra encontrar el correo ingresado
        <br>
        <strong>Entonces</strong> la aplicación muestra un mensaje de error
      </td>
      <td>E4</td>
    </tr>
    <tr>
      <td>US12</td>
      <td>Implementar comunicación por WebSocket</td>
      <td>
        <strong>Como </strong>desarrollador
        <br>
        <strong>Quiero </strong>implementar un canal WebSocket en el backend
        <br>
        <strong>Para </strong>recibir los datos en tiempo real desde el Edge Gateway
      </td>
      <td>
        <strong>Escenario 1: Recepción exitosa de datos</strong>
        <br>
        <strong>Dado que </strong>soy desarrollador
        <br>
        <strong>Y </strong>he implementado websockets para recepción de datos en tiempo real
        <br>
        <strong>Cuando </strong>el sensor de gas envíe datos al Edge Gateway
        <br>
        <strong>Entonces </strong>se establece conexión con el backend por un canal WebSocket
        <br>
        <strong>Y </strong>se reciben los datos en tiempo real para ser mostrados en la aplicación
        <br><br>
        <strong>Escenario 2: Fallo al recepcionar datos del sensor</strong>
        <br>
        <strong>Dado que </strong>soy desarrollador
        <br>
        <strong>Y </strong>he implementado websockets para recepción de datos en tiempo real
        <br>
        <strong>Cuando </strong>el sensor de gas envíe datos al Edge Gateway
        <br>
        <strong>Y </strong>no se pueda establecer conexión WebSocket
        <br>
        <strong>Entonces </strong>se mostrarán LOGS para realizar las respectivas correcciones
      </td>
      <td>E5</td>
    </tr>
    <tr>
      <td>US13</td>
      <td>Implementar servicio de notificación por SMS</td>
      <td>
        <strong>Como </strong>desarrollador
        <br>
        <strong>Quiero </strong>integrar un servicio de notificaciones por SMS
        <br>
        <strong>Para </strong>notificar a los respectivos usuarios sobre una fuga de gas
      </td>
      <td>
        <strong>Escenario 1: Notificación enviada exitosamente</strong>
        <br>
        <strong>Dado que </strong>soy desarrollador
        <br>
        <strong>Y </strong>he implementado el servicio de notificación SMS
        <br>
        <strong>Cuando </strong>se haga una petición POST al endpoint correspondiente
        <br>
        <strong>Entonces </strong>se enviará mensajes a los respectivos números de telefono de los usuarios
        <br><br>
        <strong>Escenario 2: Fallo al enviar notificación SMS</strong>
        <br>
        <strong>Dado que </strong>soy desarrollador
        <br>
        <strong>Y </strong>he implementado el servicio de notificación SMS
        <br>
        <strong>Cuando </strong>se haga una petición POST al endpoint correspondiente
        <br>
        <strong>Y </strong>ocurra algun error
        <br>
        <strong>Entonces </strong>se manejarán las excepciones
        <br>
        <strong>Y </strong>se mostrarán LOGS para realizar las respectivas correcciones
      </td>
      <td>E5</td>
    </tr>
    <tr>
      <td>US14</td>
      <td>Visualizar características del sistema GasGuard</td>
      <td>
        <strong>Como </strong>visitante del sitio web
        <br>
        <strong>Quiero </strong>ver las características principales de GasGuard en el landing page
        <br>
        <strong>Para </strong>entender como funciona y cómo puede garantiza seguridad
      </td>
      <td>
        <strong>Escenario 1: Visualización detallada del contenido</strong>
        <br>
        <strong>Dado que </strong>soy visitante del sitio web
        <br>
        <strong>Y </strong>me encuentro en la landing page
        <br>
        <strong>Cuando </strong>seleccione Acerca del producto de GasGuard
        <br>
        <strong>Entonces </strong>se muestran puntos clave y detallados del funcionamiento del producto
        <br><br>
        <strong>Escenario 2: Poco detalle acerca del producto</strong>
        <br>
        <strong>Dado que </strong>soy visitante del sitio web
        <br>
        <strong>Y </strong>me encuentro en la landing page
        <br>
        <strong>Cuando </strong>seleccione Acerca del producto de GasGuard
        <br>
        <strong>Entonces </strong>se muestra información escasa o irrelevante
      </td>
      <td>E6</td>
    </tr>
    <tr>
      <td>US15</td>
      <td>Visualizar planes</td>
      <td>
        <strong>Como </strong>visitante del sitio web
        <br>
        <strong>Quiero </strong>ver comparar los planes que ofrece GasGuard
        <br>
        <strong>Para </strong>elegir el que se adapte a mis necesidades
      </td>
      <td>
        <strong>Escenario 1: Comparar planes</strong>
        <br>
        <strong>Dado que </strong>soy visitante del sitio web
        <br>
        <strong>Cuando </strong>me encuentre en la tabla de comparación de planes
        <br>
        <strong>Entonces </strong>visualizo los beneficios que ofrece cada uno
        <br><br>
        <strong>Escenario 2: Poco detalle de beneficios de planes</strong>
        <br>
        <strong>Dado que </strong>soy visitante del sitio web
        <br>
        <strong>Cuando </strong>me encuentre en la tabla de comparación de planes
        <br>
        <strong>Y </strong>no hay detalle de los beneficios de cada plan
        <br>
        <strong>Entonces </strong>no puedo tomar una decisión sobre que plan elegir
      </td>
      <td>E6</td>
    </tr>
    <tr>
      <td>US16</td>
      <td>Visualizar sitio web desde dispositivo de preferencia</td>
      <td>
        <strong>Como </strong>visitante del sitio web
        <br>
        <strong>Quiero </strong>que la landing page sea accesible desde mi computadora, tablet o móvil
        <br>
        <strong>Para </strong>tener una buena experiencia desde cualquier dispositivo 
      </td>
      <td>
        <strong>Escenario 1: Navegación desde dispositivo de preferencia</strong>
        <br>
        <strong>Dado que </strong>soy visitante del sitio web
        <br>
        <strong>Cuando </strong>ingrese al landing page
        <br>
        <strong>Entonces </strong>la página se adapta a la resolución de mi dispositivo
        <br><br>
        <strong>Escenario 2: Elementos desordenados en pantalla</strong>
        <br>
        <strong>Dado que </strong>soy visitante del sitio web
        <br>
        <strong>Cuando </strong>cuando ingrese al landing page
        <br>
        <strong>Y </strong>se muestre contenido desbordado y desordenado
        <br>
        <strong>Entonces </strong>entiendo que la landing page no es adaptable a distintas resoluciones
      </td>
      <td>E6</td>
    </tr>
  </tbody>
</table>

## 3.3. Impact Mapping

<img src="./assets/scenario-mapping/impact-mapping.png" alt="impact-mapping">

## 3.4. Product Backlog
![imagen](https://github.com/user-attachments/assets/1c9a1693-26db-49aa-a697-65e5bf5cb365)
Link al tablero de Trello: https://trello.com/b/RRNb2Jdg/gasguard-2968 

<table>
  <thead>
    <tr>
      <th># Orden</th>
      <th>User Story Id</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Story Points<br>(1/2/3/5/8)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>E6-US14</td>
      <td>Visualizar características del sistema GasGuard</td>
      <td>
        Como visitante del sitio web
        <br>
        Quiero ver las características principales de GasGuard en el landing page
        <br>
        Para entender como funciona y cómo puede garantiza seguridad
      </td>
      <td>1</td>
    </tr>
    <tr>
      <td>2</td>
      <td>E6-US15</td>
      <td>Visualizar planes</td>
      <td>
        Como visitante del sitio web
        <br>
        Quiero ver comparar los planes que ofrece GasGuard
        <br>
        Para elegir el que se adapte a mis necesidades      
      </td>
      <td>1</td>
    </tr>
    <tr>
      <td>3</td>
      <td>E6-US16</td>
      <td>Visualizar sitio web desde dispositivo de preferencia</td>
      <td>
        Como visitante del sitio web
        <br>
        Quiero que la landing page sea accesible desde mi computadora, tablet o móvil
        <br>
        Para tener una buena experiencia desde cualquier dispositivo
      </td>
      <td>2</td>
    </tr>
    <tr>
      <td>4</td>
      <td>E1-US01</td>
      <td>Detectar fuga de gas</td>
      <td>
        Como usuario
        <br>
        Quiero que el sensor detecte niveles de gas en el ambiente
        <br>
        Para que pueda identificar si son peligrosos      
      </td>
      <td>3</td>
    </tr>
    <tr>
      <td>5</td>
      <td>E1-US02</td>
      <td>Ejecutar protocolos de seguridad</td>
      <td>
        Como usuario
        <br>
        Quiero que el sensor ejecute protocolos de seguridad cuando detecte niveles de gas peligrosos
        <br>
        Para reducir riesgos durante una fuga      
      </td>
      <td>5</td>
    </tr>
    <tr>
      <td>6</td>
      <td>E1-US03</td>
      <td>Ajustar automáticamente la iluminación</td>
      <td>
        Como usuario
        <br>
        Quiero que las luces del ambiente se ajusten automáticamente a un nivel adecuado
        <br>
        Para tener suficiente iluminación durante la fuga de gas      
      </td>
      <td>5</td>
    </tr>
    <tr>
      <td>7</td>
      <td>E2-US04</td>
      <td>Visualizar lecturas del sensor</td>
      <td>
        Como usuario
        <br>
        Quiero ver en tiempo real las lecturas del sensor
        <br>
        Para estar informado de los niveles de gas en el ambiente      
      </td>
      <td>5</td>
    </tr>
    <tr>
      <td>8</td>
      <td>E3-US06</td>
      <td>Notificar a miembros del hogar</td>
      <td>
        Como usuario
        <br>
        Quiero que la aplicación notifique a los miembros registrados
        <br>
        Para que tomen sus medidas necesarias      
      </td>
      <td>3</td>
    </tr>
    <tr>
      <td>9</td>
      <td>E3-US07</td>
      <td>Alertar a servicios de emergencia</td>
      <td>
        Como usuario
        <br>
        Quiero que la aplicación notifique a servicios de emergencia cuando se detecte una fuga de gas
        <br>
        Para que actúen rapidamente      
      </td>
      <td>3</td>
    </tr>
    <tr>
      <td>10</td>
      <td>E2-US05</td>
      <td>Generar reporte</td>
      <td>
        Como usuario
        <br>
        Quiero que se genere un reporte sobre los niveles de gas que se detectaron
        <br>
        Para tomar precauciones necesarias
      </td>
      <td>3</td>
    </tr>
    <tr>
      <td>11</td>
      <td>E3-US08</td>
      <td>Visualizar historial de alertas</td>
      <td>
        Como usuario
        <br>
        Quiero visualizar el historial de alertas
        <br>
        Para estar informado de las notificaciones y alertas que se enviaron
      </td>
      <td>3</td>
    </tr>
    <tr>
      <td>12</td>
      <td>E5-US12</td>
      <td>Implementar comunicación por WebSocket</td>
      <td>
        Como desarrollador
        <br>
        Quiero implementar un canal WebSocket en el backend
        <br>
        Para recibir los datos en tiempo real desde el Edge Gateway
      </td>
      <td>5</td>
    </tr>
    <tr>
      <td>13</td>
      <td>E5-US13</td>
      <td>Implementar servicio de notificación por SMS</td>
      <td>
        Como desarrollador
        <br>
        Quiero integrar un servicio de notificaciones por SMS
        <br>
        Para notificar a los respectivos usuarios sobre una fuga de gas      
      </td>
      <td>3</td>
    </tr>
    <tr>
      <td>14</td>
      <td>E4-US09</td>
      <td>Registrar usuario</td>
      <td>
        Como usuario
        <br>
        Quiero crear una cuenta
        <br>
        Para acceder a la aplicación y sus funciones      
      </td>
      <td>3</td>
    </tr>
    <tr>
      <td>15</td>
      <td>E4-US10</td>
      <td>Iniciar sesión</td>
      <td>
        Como usuario
        <br>
        Quiero iniciar sesión
        <br>
        Para acceder a la aplicación y sus funciones      
      </td>
      <td>3</td>
    </tr>
    <tr>
      <td>16</td>
      <td>E4-US11</td>
      <td>Recuperar contraseña</td>
      <td>
        Como usuario
        <br>
        Quiero recibir un correo
        <br>
        Para reestablecer mi contraseña      
      </td>
      <td>3</td>
    </tr>
  </tbody>
</table>

---

# Capítulo IV: Solution Software Design
## 4.1. Strategic-Level Domain-Driven Design

En esta sección se detalla el enfoque de Diseño Dirigido por el Dominio a nivel estratégico para el proyecto GasGuard. Este enfoque es fundamental para establecer una base sólida que permita definir y modelar los dominios complejos de nuestro sistema de detección y mitigación de fugas de gas. A través de técnicas como Event Storming, Context Mapping y la definición de la Arquitectura de Software, se ha logrado obtener una comprensión profunda de los elementos esenciales necesarios para crear un sistema efectivo y bien estructurado.

### 4.1.1. EventStorming

El EventStorming es un enfoque colaborativo y visual que permitió modelar el contexto del dominio de GasGuard. Esta técnica nos ayudó a identificar los eventos clave, comandos, políticas y otros elementos que conforman el flujo del sistema.

#### 4.1.1.1. Candidate Context Discovery

Empleando la metodología de EventStorming con enfoque en la técnica "start-with-simple", realizamos una sesión colaborativa donde identificamos los siguientes contextos candidatos para nuestro sistema GasGuard:

**Proceso de identificación:**

 **Identificación de Valores del Negocio:**  
   Analizamos los valores clave que nuestro sistema debe proporcionar:
   - Seguridad preventiva ante situaciones de riesgo
   - Automatización efectiva de respuestas ante emergencias
   - Tranquilidad para los usuarios al saber que su hogar está protegido
   - Reducción significativa de daños materiales y riesgos para la vida

**Identificación de Funcionalidades Clave:**  
   Determinamos las capacidades esenciales que el sistema debe ofrecer:
   - Detección precisa de concentraciones de gas
   - Ejecución automática de protocolos de emergencia
   - Sistema de notificaciones a usuarios y servicios de emergencia
   - Control adaptativo de iluminación y sistemas conectados

1. **Gas Detection & Sensor Management**  
   <img src="./assets/images/cap_4/iot_device_management.png" alt="Gas Detection & Sensor Management">  
   Este contexto es responsable de la adquisición y procesamiento de datos desde los sensores de gas, incluyendo la calibración de dispositivos, monitoreo continuo de niveles de concentración y generación de alertas cuando se detectan niveles anormales.

2. **Safety Protocol Automation**  
   <img src="./assets/images/cap_4/security_protocol_management.png" alt="Safety Protocol Automation">  
   
   Gestiona los protocolos automáticos que se activan cuando se detecta una fuga, controlando actuadores para ventilación, apertura de puertas/ventanas, corte de suministro eléctrico, y activación de señales visuales de emergencia.

3. **Resident Profile & Access Management**  
   <img src="./assets/images/cap_4/user_profile_management.png" alt="Resident Profile & Access Management">  

   Maneja la información de los residentes, sus preferencias de notificación, roles dentro del sistema, y permisos para controlar diferentes aspectos del sistema GasGuard, así como la configuración específica de cada hogar.

4. **Emergency Alert & Notification**  
   <img src="./assets/images/cap_4/notification_management.png" alt="Emergency Alert & Notification">  

   Coordina todas las comunicaciones de emergencia, distribuyendo alertas a diferentes canales (app móvil, SMS, llamadas) según la gravedad de la situación, y manteniendo un registro auditable de todas las notificaciones enviadas.

5. **Environment Analytics**  
   <img src="./assets/images/cap_4/data_analytics.png" alt="Environment Analytics">  

   Procesa los datos históricos recolectados por los sensores para proporcionar insights sobre patrones de calidad del aire, eficacia de los protocolos implementados, y generación de reportes preventivos para los usuarios.

Estos contextos delimitados forman la base para nuestro diseño modular del sistema, permitiendo que cada área evolucione de manera independiente mientras mantiene interfaces claras para la comunicación entre ellas, asegurando así la escalabilidad y mantenibilidad de GasGuard.
Empleando la metodología de EventStorming con enfoque en la técnica "start-with-simple", identificamos los siguientes contextos candidatos para nuestro sistema GasGuard:

#### 4.1.1.2. Domain Message Flows Modeling

En esta sección presentamos los flujos de mensajes entre los diferentes contextos delimitados de GasGuard, modelando las interacciones clave que ocurren durante escenarios críticos del sistema.

**Escenario 1: Registro en la Aplicación**

<img src="./assets/images/cap_4/user_registration_flow.png" alt="User Registration Flow">

Este flujo modela el proceso de registro de un nuevo usuario en el sistema GasGuard. Comienza con la solicitud de creación de cuenta desde la app móvil, donde los datos son validados por el contexto **Resident Profile & Access Management**. Una vez verificada la información, se crea el perfil con preferencias de notificación y se establecen los permisos correspondientes. El proceso finaliza con la confirmación del registro que permite al usuario comenzar a configurar los dispositivos de su hogar.

**Escenario 2: Detección de Fuga de Gas**

<img src="./assets/images/cap_4/gas_leak_detection.png" alt="Gas Leak Detection Flow">

Este flujo representa el proceso desde que el sensor detecta concentraciones elevadas de gas hasta la generación de alertas. El contexto de **Gas Detection & Sensor Management** captura las lecturas y, al identificar niveles superiores al umbral establecido, genera el evento "GasLevelExceededThreshold" que es consumido por otros contextos para iniciar sus respectivas acciones.

**Escenario 3: Ejecución de Protocolo de Seguridad**

<img src="./assets/images/cap_4/security_protocol_execution.png" alt="Security Protocol Execution">

Una vez detectada la fuga, este flujo muestra cómo el contexto **Safety Protocol Automation** orquesta la secuencia de respuestas automáticas. Se activan los actuadores que abren ventanas, cortan suministro eléctrico y activan señales visuales, generando eventos de confirmación que permiten el seguimiento del proceso de mitigación.

**Escenario 4: Notificación a Usuarios y Servicios de Emergencia**

<img src="./assets/images/cap_4/notifications_flow.png" alt="Notifications Flow">

Este diagrama ilustra cómo el contexto **Emergency Alert & Notification** distribuye alertas a diferentes canales según la severidad de la fuga. Se consultan preferencias del usuario desde **Resident Profile & Access Management** y se priorizan notificaciones a residentes y servicios de emergencia, manteniendo un registro de todas las comunicaciones enviadas.


#### 4.1.1.3. Bounded Context Canvases

Para completar nuestro análisis de EventStorming, desarrollamos los Bounded Context Canvases para cada uno de los contextos delimitados de GasGuard, definiendo sus responsabilidades específicas y relaciones con otros componentes del sistema.

1. Resident Profile & Access Management

<img src="./assets/images/cap_4/boundedcontext_resident_profile.png" alt="Resident Profile Canvas">

2. Gas Detection & Sensor Management

<img src="./assets/images/cap_4/boundedcontext_gas_detection.png" alt="Gas Detection & Sensor Management Canvas">

3. Safety Protocol Automation

<img src="./assets/images/cap_4/boundedcontext_safety_protocol.png" alt="Safety Protocol Automation Canvas">

4. Emergency Alert & Notification

<img src="./assets/images/cap_4/boundedcontext_emergency_alert.png" alt="Emergency Alert Canvas">

5. Environment Analytics

<img src="./assets/images/cap_4/boundedcontext_environment_analytics.png" alt="Environment Analytics Canvas">


### 4.1.2. Context Mapping

El Context Mapping representa cómo los diferentes módulos interactúan dentro del sistema GasGuard. En el centro se encuentra el Sistema de Gestión de Protocolos de Seguridad, que actúa como núcleo coordinando la interacción con otros componentes. La Gestión de Dispositivos IoT proporciona los datos de sensores y controla los actuadores, conformándose a los requisitos del sistema central. La Gestión de Perfiles de Usuario maneja las configuraciones personalizadas y se apoya en Gestión de Identidad y Accesos para controlar la autenticación y autorización.

El sistema también interactúa con el módulo de Gestión de Notificaciones que maneja las alertas generadas por el sistema, mientras que el módulo de Análisis de Datos procesa la información para proporcionar insights sobre la calidad del aire, patrones de fugas y eficacia de los protocolos de seguridad.

### 4.1.3. Software Architecture

Este diagrama muestra el panorama general del sistema GasGuard, destacando las principales entidades involucradas: Usuarios Residenciales, Servicios de Emergencia y Administradores del Sistema. También representa las interacciones con componentes externos como la API de Notificaciones SMS y el Sistema de Autenticación. Cada actor interactúa con el sistema GasGuard de forma diferente según su rol, accediendo a funcionalidades específicas como monitoreo, configuración o respuesta a emergencias.

#### 4.1.3.1. Software Architecture System Landscape Diagram

El diagrama a continuación muestra el panorama general del sistema GasGuard, destacando las principales entidades involucradas: Usuarios Residenciales, Servicios de Emergencia y Administradores del Sistema. También representa las interacciones con componentes externos como la API de Notificaciones SMS y el Sistema de Autenticación. Cada actor interactúa con el sistema GasGuard de forma diferente según su rol, accediendo a funcionalidades específicas como monitoreo, configuración o respuesta a emergencias.

<img src="./assets/images/cap_4/system_landscape_diagram.png" alt="System Landscape Diagram">

#### 4.1.3.2. Software Architecture Context Level Diagrams

El System Context Diagram ofrece una vista general del sistema GasGuard, destacando cómo interactúa con actores externos como usuarios finales y operadores de dispositivos IoT, así como con sistemas externos como servicios de pago y envío de SMS. Este diagrama identifica los límites del sistema y resalta las interacciones clave, proporcionando un marco claro para entender cómo el sistema se integra en su entorno. Es una herramienta esencial para visualizar las relaciones principales entre el sistema y los actores o servicios externos.

<img src="./assets/diagrams_C4/Context.png" alt="Context"/>

#### 4.1.3.3. Software Architecture Container Level Diagrams

El Container Diagram desglosa el sistema GasGuard en contenedores principales como la aplicación móvil, la aplicación web, las APIs REST y los servicios de backend (por ejemplo, IAM, Perfiles, Pago, y Reporte). Este diagrama ilustra cómo estos contenedores interactúan entre sí y con actores externos, detallando las tecnologías empleadas y las interfaces que conectan estos elementos. Proporciona un entendimiento claro de la arquitectura lógica del sistema y cómo los módulos principales colaboran para cumplir sus funciones.

<img src="./assets/diagrams_C4/Container.png" alt="Container"/>

#### 4.1.3.4. Software Architecture Deployment Diagrams

El Deployment Diagram describe cómo los diferentes contenedores de GasGuard se implementan en infraestructura física o en la nube. Detalla dónde se ejecutan las aplicaciones móviles y web, y cómo se despliegan servicios clave como Web API, Edge API e IoT App en diferentes nodos. Este diagrama también incluye las conexiones de red necesarias para la comunicación entre dispositivos IoT y la infraestructura central, garantizando la disponibilidad, la escalabilidad y la seguridad del sistema en entornos de despliegue en tiempo real.

<img src="./assets/diagrams_C4/Deployment.png" alt="Deployment"/>

## 4.2. Tactical-Level Domain-Driven Design

### 4.2.1. Bounded Context: Perfiles

#### 4.2.1.1. Domain Layer

Clases a tomar en cuenta para este bounded context:

* Entities:

  * Usuario: Representa a un usuario registrado en el sistema. Atributos:

    * id: UUID
    * email: string
    * password: string

  * Perfil: Representa el perfil asociado a un usuario. Atributos:

    * userId: UUID
    * id: String
    * name: string

* ValueObjects:

  * Ninguno explícito en el modelo actual.

* Servicios de Dominio:

  * IAMService: Gestiona operaciones relacionadas con credenciales de usuarios:

    * validarCredenciales()
    * hashPassword()


#### 4.2.1.2. Interface Layer

Controllers a incluir en este contexto:

* UserController:

  * Gestiona las solicitudes de autenticación y registro de usuarios.

  * Métodos:

    * iniciarSesion()
    * registrarUsuario()

* ProfileController:

  * Gestiona las solicitudes relacionadas con perfiles de usuario.

  * Métodos:

    * actualizarPerfil()
    * consultarPerfil()

#### 4.2.1.3. Application Layer

Manejadores de eventos y comandos para este contexto:

* CommandHandler:

  * UserCommandHandler:

    * RegisterUserCommand
    * AuthenticateUserCommand

  * ProfileCommandHandler:

    * UpdateProfileCommand

* EventHandler:

  * UserEventHandler:

    * UserRegisteredEvent
    * UserAuthenticatedEvent

  * ProfileEventHandler:

    * ProfileUpdatedEvent

#### 4.2.1.4. Infrastructure Layer

Repositorios necesarios para gestionar la persistencia de datos:

* UsuarioRepository: Gestiona la persistencia de los datos de usuarios.
* PerfilRepository: Gestiona la persistencia de los perfiles asociados a los usuarios.

#### 4.2.1.5. Component Level Diagrams

El módulo IAM y Perfiles gestiona la autenticación, autorización y configuración de usuarios. IAMController y ProfileController manejan registro, inicio de sesión y gestión de perfiles, delegando la lógica a IAMService y ProfileService. Los repositorios asociados garantizan el acceso seguro y estructurado a la base de datos. Este módulo asegura una experiencia personalizada y segura para cada usuario.

<img src="./assets/diagrams_C4/IAM_Component.png" alt="Component"/>
<img src="./assets/diagrams_C4/Perfiles_Component.png" alt="Component"/>

#### 4.2.1.6. Code Level Diagrams

##### 4.2.1.6.1. Domain Layer Class Diagrams

<img src="./assets/diagrams_C4/Diagrama_Bounded_Context_Acceso_Perfiles.png" alt="Diagraman"/>

##### 4.2.1.6.2. Database Design Diagram

<img src="./assets/diagrams_C4/Database_Perfiles.png" alt="Database"/>


### 4.2.2. Bounded Context: Protocolo de Seguridad

#### 4.2.2.1. Domain Layer

Clases a tomar en cuenta para este bounded context:

* Entities:

  * IoTDevice: Representa el dispositivo IoT responsable de ejecutar los protocolos de seguridad.

  * SensorGas: Clase encargada de medir los niveles de gas y determinar si existe un peligro.

* ValueObjects:

  * GasLevelStatus: Enum que define los estados del nivel de gas: BIEN, MODERADO, PELIGROSO.

* Interfaces:

  * ProtocolosDeSeguridad: Define los métodos necesarios para activar medidas de seguridad:

    * abrirPuertas()
    * abrirVentanas()
    * ajustarIluminacion()
    * deteccionGasPeligroso()

#### 4.2.2.2. Interface Layer

Controllers a incluir en este contexto:

* ProtocolosDeSeguridadController:

  * Gestiona las peticiones HTTPS para activar y supervisar los protocolos de seguridad.

  * Métodos:

    * activarProtocoloDeSeguridad()
    * supervisarEstadoProtocolo()

#### 4.2.2.3. Application Layer

Manejadores de eventos y comandos para este contexto:

* CommandHandler:

  * SecurityProtocolCommandHandler:

    * ActivateSecurityProtocolCommand
    * AdjustIlluminationCommand
    * OpenDoorsCommand
    * OpenWindowsCommand

* EventHandler:

  * SecurityProtocolEventHandler:

    * SecurityProtocolActivatedEvent
    * GasDangerDetectedEvent

#### 4.2.2.4. Infrastructure Layer

Repositorios necesarios para gestionar la persistencia de datos:

* IoTDeviceRepository: Gestiona la persistencia de los dispositivos IoT y su estado actual.
* SensorGasRepository: Permite almacenar y recuperar datos sobre lecturas del sensor de gas y niveles de peligro detectados.

#### 4.2.2.5. Component Level Diagrams

El ActuatorController toma decisiones basadas en los datos de los sensores y ejecuta comandos para controlar los actuadores, como cerrar válvulas en caso de fuga de gas. Paralelamente, el SensorMonitor realiza una supervisión constante de los sensores, reportando anomalías y asegurando la integridad de los datos capturados. Juntos, estos componentes conforman el núcleo de la funcionalidad IoT del sistema.

<img src="./assets/diagrams_C4/IOTAPP_Component.png" alt="Component"/>

#### 4.2.2.6. Code Level Diagrams

##### 4.2.2.6.1. Domain Layer Class Diagrams

<img src="./assets/diagrams_C4/Diagrama_Bounded_Context_Security_Protocol.png" alt="Diagraman"/>

##### 4.2.2.6.2. Database Design Diagram

<img src="./assets/diagrams_C4/Database_Protocolo_Seguridad.png" alt="Database"/>



### 4.2.3. Bounded Context: Detector de Gas

#### 4.2.3.1. Domain Layer

Clases a tomar en cuenta para este bounded context:

* Entities:

  * IoTDevice: Clase que representa el dispositivo IoT encargado de procesar las lecturas de gas.

  * SensorGas: Clase que representa el sensor que mide los niveles de gas.

  * EdgeGateway: Clase que actúa como punto de conexión entre los dispositivos IoT y la red central.

* ValueObjects:

  * GasLevelStatus: Enum que define los estados del nivel de gas: BIEN, MODERADO, PELIGROSO.

* Interfaces:

  * ProtocolosDeSeguridad: Define los protocolos de seguridad que incluyen:

    * abrirPuertas()
    * abrirVentanas()
    * ajustarIluminacion()
    * deteccionGasPeligroso()

#### 4.2.3.2. Interface Layer

Controllers a incluir en este contexto:

* GasLevelReadingsController: Controlador para gestionar las peticiones relacionadas con las lecturas del nivel de gas.

* ReportsService: Servicio para generar y mostrar reportes sobre los niveles de gas.

Componentes de comunicación:

* WebSocket: Maneja la recepción de datos desde el dispositivo IoT.

#### 4.2.3.3. Application Layer

Manejadores de eventos y comandos para este contexto:

* CommandHandler:

  * GasDetectionCommandHandler:

    * RegisterIoTDeviceCommand
    * UpdateGasLevelStatusCommand
    * ActivateSafetyProtocolsCommand

* EventHandler:

  * GasDetectionEventHandler:

    * GasLevelUpdatedEvent
    * SafetyProtocolsActivatedEvent

#### 4.2.3.4. Infrastructure Layer

Repositorios necesarios para gestionar la persistencia de datos:

* IoTDeviceRepository: Maneja la persistencia de los dispositivos IoT.

* SensorGasRepository: Almacena y recupera datos relacionados con los sensores de gas.

* EdgeGatewayRepository: Gestiona los datos de los gateways de red.

#### 4.2.3.5. Component Level Diagrams

El Edge API sirve para la detección de gas. El IoTController recibe lecturas de los sensores de gas de los dispositivos IoT. El EventHandler analiza estos datos para detectar fugas o niveles peligrosos. Cuando se detecta una anomalía, el WebSocket envía alertas en tiempo real a las aplicaciones cliente.

<img src="./assets/diagrams_C4/EdgeAPI_Component.png" alt="Component"/>

#### 4.2.3.6. Code Level Diagrams

##### 4.2.3.6.1. Domain Layer Class Diagrams

<img src="./assets/diagrams_C4/Diagrama_Bounded_Context_Gas_Detection.png" alt="Diagraman"/>

##### 4.2.3.6.2. Database Design Diagram

<img src="./assets/diagrams_C4/Database_Detector_Gas.png" alt="Database"/>



### 4.2.4. Bounded Context: Notificacion

#### 4.2.4.1. Domain Layer

Clases a tomar en cuenta para este bounded context:

* Entities:

  * Notification: Representa una notificación enviada a un perfil.

    * id: String
    * date: DateTime
    * message: String

* ValueObjects:

  * Ninguno explícito en el modelo actual.

* Servicios de Dominio:

  * NotificationService: Gestiona el envío de notificaciones y alertas a los usuarios.

    * Métodos:

      * enviarNotificacionSMS(): void
      * alertarServiciosDeEmergencia(): void

#### 4.2.4.2. Interface Layer

Controllers a incluir en este contexto:

* NotificationController:

  * Gestiona las solicitudes relacionadas con el envío y visualización de notificaciones.

  * Métodos:

    * enviarNotificacion()
    * consultarNotificaciones()

* EventController (Opcional):

  * Gestiona eventos provenientes del sistema IoT o sensores.

#### 4.2.4.3. Application Layer

Manejadores de eventos y comandos para este contexto:

* CommandHandler:

  * NotificationCommandHandler:

    * EnviarNotificacionCommand
    * AlertarServiciosCommand

* EventHandler:

  * GasLevelEventHandler: Responde a eventos de niveles peligrosos de gas:
    * GasLevelDetectedEvent

#### 4.2.4.4. Infrastructure Layer

Repositorios necesarios para gestionar la persistencia de datos:

* NotificationRepository: Gestiona la persistencia de las notificaciones enviadas y recibidas.

* Integration Components:

  * Edge Gateway: Interactúa con dispositivos IoT para recibir datos sobre el nivel de gas.

  * WebSocket: Facilita la comunicación en tiempo real con los usuarios para notificaciones inmediatas.



#### 4.2.4.5. Component Level Diagrams

El Edge API gestiona las notificaciones en tiempo real. El IoTController recibe datos de los dispositivos, y el WebSocket envía estas notificaciones a los clientes suscritos. El EventHandler procesa los eventos de los sensores para determinar cuándo y qué notificaciones enviar a través del WebSocket.

<img src="./assets/diagrams_C4/EdgeAPI_Component.png" alt="Component"/>

#### 4.2.4.6. Code Level Diagrams

##### 4.2.4.6.1. Domain Layer Class Diagrams

<img src="./assets/diagrams_C4/Diagrama_Bounded_Context_Notificaciones.png" alt="Diagraman"/>

##### 4.2.4.6.2. Database Design Diagram

<img src="./assets/diagrams_C4/Database_Notificacion.png" alt="Database"/>



### 4.2.5. Bounded Context: Reporte

#### 4.2.5.1. Domain Layer

Clases a tomar en cuenta para este bounded context:

* Entities:

  * GasLevelReport: Representa un informe detallado del nivel de gas detectado.

    * Atributos:

      * status: ENUM (BIEN, MODERADO, PELIGROSO)
      * valor: Float
      * unidad: String
      * incidentDate: datetime

    * Métodos:

      * esPeligroso(): Boolean

* ValueObjects:

  * GasLevelStatus (ENUM): Define los posibles estados de los niveles de gas (BIEN, MODERADO, PELIGROSO).

* Servicios de Dominio:

  * CalcularRiesgoServicio:

    * Lógica para determinar el nivel de riesgo en función del reporte.

    * Métodos:

      * determinarRiesgo(valor: Float, unidad: String): GasLevelStatus
      * Valores numéricos de gas a un estado ENUM (BIEN, MODERADO, PELIGROSO)

#### 4.2.5.2. Interface Layer

Controllers y Endpoints a incluir:

* GasLevelReadingsController:

  * Responsable de exponer los datos sobre los niveles de gas detectados.

  * Métodos:

    * showGasLevelReadings(): void

* WebSocket:

  * Proporciona una interfaz de comunicación en tiempo real para la transmisión de los reportes.

#### 4.2.5.3. Application Layer

* ReportsService:

  * Gestiona la generación y visualización de reportes relacionados con los niveles de gas.

  * Atributos:

    * content: GasLevelReport

  * Métodos:

    * showReport(): void

* Command/Event Handlers:

  * Comandos para manejar solicitudes de reportes en tiempo real o programados:

    * GenerateGasReportCommand

  * Eventos para notificar cambios en los niveles de gas detectados.

#### 4.2.5.4. Infrastructure Layer

Componentes técnicos necesarios:

* Data Adapters:

  * Edge Gateway: Recibe y transmite datos desde los dispositivos IoT hacia el sistema de reportes.

  * IoTDevice: Recopila información en tiempo real del estado del gas y su nivel.

* Base de datos para reportes:

  * Sistema de almacenamiento para mantener un historial de reportes generados.

* Integración en tiempo real:

  * WebSocket: Canal para notificaciones inmediatas relacionadas con los reportes.

#### 4.2.5.5. Component Level Diagrams

El ReportController permite a los usuarios visualizar y consultar reportes generados a partir de los datos del sistema IoT, como métricas de rendimiento y eventos de emergencia. Este controlador se apoya en el ReportService, que procesa y formatea los datos para generar reportes comprensibles y útiles. Finalmente, el ReportRepository interactúa con la base de datos para obtener la información necesaria y almacenarla para futuras consultas.

<img src="./assets/diagrams_C4/Reporte_Component.png" alt="Component"/>

#### 4.2.5.6. Code Level Diagrams

##### 4.2.5.6.1. Domain Layer Class Diagrams

<img src="./assets/diagrams_C4/Diagrama_Bounded_Context_Reporte.png" alt="Diagraman"/>

##### 4.2.5.6.2. Database Design Diagram

<img src="./assets/diagrams_C4/Database_Reporte.png" alt="Database"/>


---

# Capítulo V: Solution UI/UX Design

## 5.1. Style Guidelines

### 5.1.1. General Style Guidelines

### 5.1.2. Web, Mobile and IoT Style Guidelines

## 5.2. Information Architecture

### 5.2.1. Organization Systems

### 5.2.2. Labeling Systems

### 5.2.3. SEO Tags and Meta Tags

### 5.2.4. Searching Systems

### 5.2.5. Navigation Systems

## 5.3. Landing Page UI Design

### 5.3.1. Wireframe

### 5.3.2. Mock-up

## 5.4. Applications UX/UI Design

### 5.4.1. Wireframes

### 5.4.2. Wireflow Diagrams

### 5.4.3. Mock-ups

### 5.4.4. User Flow Diagrams

## 5.5. Applications Prototyping

---

# Capítulo VI: Product Implementation, Validation & Deployment

## 6.1. Software Configuration Management

### 6.1.1. Development Environment Configuration

### 6.1.2. Source Code Management

### 6.1.3. Style Guide & Conventions

### 6.1.4. Deployment Configuration

## 6.2. Implementation

### 6.2.X. Sprint n

#### 6.2.X.1. Sprint Planning

#### 6.2.X.2. Aspect Leaders and Collaborators

#### 6.2.X.3. Sprint Backlog

#### 6.2.X.4-8. Sprint Review Evidences

#### 6.2.X.9. Team Collaboration Insights

## 6.3. Validation Interviews

### 6.3.1. Diseño

### 6.3.2. Registro

### 6.3.3. Evaluaciones

## 6.4. Video About-the-Product

---

# Conclusiones y Recomendaciones
En conclusión, el proyecto GasGuard se es sustendado baso un análisis riguroso de las necesidades reales de los usuarios, apoyado por entrevistas, investigación de mercado y herramientas de diseño centradas en las personas. A lo largo del proceso, se identificaron problemáticas críticas relacionadas con la seguridad doméstica frente a fugas de gas, así como oportunidades para ofrecer una solución tecnológica accesible, preventiva y automatizada.

Hemos planteado hipótesis claras que orientan el desarrollo del sistema, priorizando funcionalidades clave como la detección temprana, la respuesta automática ante emergencias, la gestión inteligente del hogar y la notificación inmediata a los usuarios. A ello se suma una propuesta de valor que abarca tanto el diseño intuitivo de la interfaz, como el desarrollo de hardware confiable, estrategias de sensibilización, y un modelo de negocio sostenible. Todo esto con el fin de mejorar la seguridad de los hogares y generar confianza en el uso de tecnología IoT para proteger vidas.

# Video About-the-Team

# Bibliografía

Cuerpo General de Bomberos Voluntarios del Perú. (2024). *Estadísticas de emergencias - 2024*. https://www.bomberosperu.gob.pe/diprein/Estadisticas/po_muestra_esta.asp?a%F1o=2024&cboTipo=TipoEmer&cboNivel=Nac

Cuerpo General de Bomberos Voluntarios del Perú. (2025). *Estadísticas de emergencias - 2025*. https://www.bomberosperu.gob.pe/diprein/Estadisticas/po_muestra_esta.asp?a%F1o=2025&cboTipo=TipoEmer&cboNivel=Nac

Kumar, M., Naidu, V., Mohit, S., Avyakth, P., y Acharyulu, B. (2021). Design and implementation of IOT based Gas detection & fire extinguishing System. *International Journal* , 9(7), 944 - 949. https://www.warse.org/IJETER/static/pdf/file/ijeter18972021.pdf 

Pereyra, G.(28 de enero de 2020). Bombas de tiempo: todos los días hay al menos 18 fugas de gas en el país. *El Comercio*. https://elcomercio.pe/lima/sucesos/villa-el-salvador-bombas-de-tiempo-todos-los-dias-hay-al-menos-18-fugas-de-gas-en-el-pais-glp-balon-de-gas-bomberos-noticia/ 

# Anexos
Link de la exposición de la TB1: https://youtu.be/2CsRgKz3QEI 

Link de la organización en GitHub: https://github.com/IoT-GasGuard

Repositorio del informe: https://github.com/IoT-GasGuard/Project-report 
