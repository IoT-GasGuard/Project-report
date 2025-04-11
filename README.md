# Project-report

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

| Student Name | Contribution Summary |
|--------------|----------------------|
|              |                      |

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
            <img src="https://raw.githubusercontent.com/upc-pre-202401-si729-wx56-g3/Project-Report/main/assets/members-profile/Gerardo.png" alt="Jorge Quilla" style="margin-bottom: 5px;" width="150"/>
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
            <img src="" alt="" style="margin-bottom: 5px;" width="150"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
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
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
            <img src="" alt="" style="margin-bottom: 5px;" width="150"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>
            Joseph Llacchua Peralta 
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
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
            <img src="" alt=""  style="margin-bottom: 5px;" width="600"/>
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

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

#### 1.2.2.2. Lean UX Assumptions

#### 1.2.2.3. Lean UX Hypothesis Statements

#### 1.2.2.4. Lean UX Canvas

## 1.3. Segmentos objetivo

---

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

### 2.1.1. Análisis competitivo

### 2.1.2. Estrategias y tácticas frente a competidores

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

### 2.2.2. Registro de entrevistas

### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding

### 2.3.1. User Personas

### 2.3.2. User Task Matrix

### 2.3.3. User Journey Mapping

### 2.3.4. Empathy Mapping

### 2.3.5. As-is Scenario Mapping

## 2.4. Ubiquitous Language

---

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

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
        Quiero que el sensor detecte gases peligrosos
        Para tomar medidas necesarias
      </td>
    </tr>
    <tr>
      <td>E2</td>
      <td>Visualización de datos en la aplicación móvil</td>
      <td>
        Como usuario
        Quiero visualizar en mi celular la lecturas del sensor en tiempo real
        Para conocer el estado de la calidad del aire
      </td>
    </tr>
    <tr>
      <td>E3</td>
      <td>Gestión de usuarios</td>
      <td>
        Como usuario
        Quiero acceder a la aplicación móvil
        Para gestionar mi cuenta      
      </td>
    </tr>
    <tr>
      <td>E4</td>
      <td>Desarrollo del backend</td>
      <td>
        Como desarrollador
        Quiero construir una api rest, integrar servicios y distribuir los datos del sensor
        Para que la información sea recibida por la aplicación móvil, otros actuadores, y se ejecuten las acciones necesarias      
      </td>
    </tr>
    <tr>
      <td>E5</td>
      <td>Diseño de Landing Page</td>
      <td>
        Como visitante del sitio
        Quiero visualizar una página antarctica y clara
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
        <strong>Quiero </strong>que el sensor detecte niveles de gas en el ambiente
        <strong>Para </strong>que pueda identificar si son peligrosos
      </td>
      <td></td>
      <td>E1</td>
    </tr>
    <tr>
      <td>US02</td>
      <td>Ejecutar protocolos de seguridad</td>
      <td>
        <strong>Como </strong>usuario
        <strong>Quiero </strong>que el sensor ejecute protocolos de seguridad cuando detecte niveles de gas peligrosos
        <br>
        <strong>Para </strong>reducir riesgos durante una fuga
      </td>
      <td></td>
      <td>E1</td>
    </tr>
    <tr>
      <td>US03</td>
      <td>Ajustar automaticamente la iluminación</td>
      <td>
        <strong>Como </strong>usuario
        <strong>Quiero </strong>que las luces del ambiente se ajusten automaticamente a un nivel adecuado
        <br>
        <strong>Para </strong>tener suficiente iluminación durante la fuga de gas
      </td>
      <td></td>
      <td>E1</td>
    </tr>
    <tr>
      <td>US04</td>
      <td>Visualizar lecturas del sensor</td>
      <td>
        <strong>Como </strong>usuario
        <strong>Quiero </strong>ver en tiempo real las lecturas del sensor
        <br>
        <strong>Para </strong>estar informado de los niveles de gas en el ambiente
      </td>
      <td></td>
      <td>E2</td>
    </tr>
    <tr>
      <td>US05</td>
      <td>Notificar a miembros del hogar</td>
      <td>
        <strong>Como </strong>usuario
        <strong>Quiero </strong>que la aplicación notifique a los miembros registrados
        <br>
        <strong>Para </strong>que tomen sus medidas necesarias
      </td>
      <td></td>
      <td>E2</td>
    </tr>
    <tr>
      <td>US06</td>
      <td>Notificar a servicios de emergencia</td>
      <td>
        <strong>Como </strong>usuaqrio
        <strong>Quiero </strong>que la aplicación notifique a servicios de emrgencia cuando se detecte una fuga de gas
        <br>
        <strong>Para </strong>que actúen rapidamente
      </td>
      <td></td>
      <td>E2</td>
    </tr>
    <tr>
      <td>US07</td>
      <td>Registrar usuario</td>
      <td>
        <strong>Como </strong>usuario 
        <strong>Quiero </strong>crear una cuenta
        <br>
        <strong>Para </strong>acceder a la aplicación y sus funciones
      </td>
      <td>
        <strong>Escenario 1: Registro exitoso</strong>
        <br>
        <strong>Dado que</strong> el usuario ingresa por primera vez a la aplicación
        <strong>Cuando</strong> llene el formulario
        <strong>Y</strong> presione Registrar cuenta
        <strong>Entonces</strong> la aplicación muestra un mensajje que confirma la creación de su cuenta
        <br><br>
        <strong>Escenario 2: Registro fallido</strong>
        <br>
        <strong>Dado que</strong> el usuario ingresa por primera vez a la aplicación
        <strong>Cuando</strong> llene solo algunos campos del formulario
        <strong>Y</strong> presione Registrar cuenta
        <strong>Entonces</strong> la aplicación muestra un mensajje que indica que hubo un error al crear la cuenta
      </td>
      <td>E3</td>
    </tr>
    <tr>
      <td>US08</td>
      <td>Iniciar sesión</td>
      <td>
        <strong>Como </strong>usuario 
        <strong>Quiero </strong>iniciar sesión
        <strong>Para </strong>acceder a la aplicación y sus funciones
      </td>
      <td>
        <strong>Escenario 1: Inicio de sesión exitoso</strong>
        <br>
        <strong>Dado que</strong> el usuario está en la aplicación
        <strong>Y</strong> selecciona iniciar sesión
        <strong>Cuando</strong> llene el formulario con sus credenciales
        <strong>Y</strong> la aplicación valida sus datos
        <strong>Entonces</strong> el usuario ingresa al contenido de la aplicación
        <br><br>
        <strong>Escenario 2: Inicio de sesión fallido</strong>
        <br>
        <strong>Dado que</strong> el usuario está en la aplicación
        <strong>Y</strong> selecciona iniciar sesión
        <strong>Cuando</strong> llene el formulario con sus credenciales
        <strong>Y</strong> la aplicación detecta que sus credenciales no son correctas
        <strong>Entonces</strong> la aplicación muestra un mensaje indicando que sus datos son incorrectos
      </td>
      <td>E3</td>
    </tr>
    <tr>
      <td>US09</td>
      <td>Recuperar contraseña</td>
      <td>
        <strong>Como </strong>usuario 
        <strong>Quiero </strong> recibir un correo
        <br>
        <strong>Para </strong>reestablecer mi contraseña
      </td>
      <td>
        <strong>Escenario 1: Recuperación de contraseña exitosa</strong>
        <br>
        <strong>Dado que</strong> el usuario ingresa a la aplicación
        <strong>Y</strong> selecciona Olvidé mi contraseña
        <strong>Cuando</strong> llene el formulario con su correo electrónico
        <strong>Y</strong> la aplicación valida que el correo existe
        <strong>Entonces</strong> se envía un enlace a su correo para que el usuario ingrese una nueva contraseña
        <br><br>
        <strong>Escenario 2: Recuperación de contraseña fallido</strong>
        <br>
        <strong>Dado que</strong> el usuario ingresa a la aplicación
        <strong>Y</strong> selecciona Olvidé mi contraseña
        <strong>Cuando</strong> llene el formulario con su correo electrónico
        <strong>Y</strong> la aplicación no logra encontrar el correo ingresado
        <strong>Entonces</strong> la aplicación muestra un mensaje de error
      </td>
      <td>E3</td>
    </tr>
    <tr>
      <td>US10</td>
      <td>Desarrollar API REST para comunicación de sistemas</td>
      <td>
        <strong>Como </strong>desarrollador
        <strong>Quiero </strong>construir una API REST que permita la comunicación entre dispositivos IoT y la aplicación móvil
        <br>
        <strong>Para </strong>que los datos sean distribuidos entre los sistemas
      </td>
      <td></td>
      <td>E4</td>
    </tr>
    <tr>
      <td>US11</td>
      <td>Implementar servicio de notificación por SMS</td>
      <td>
        <strong>Como </strong>desarrollador
        <strong>Quiero </strong>integrar un servicio de notificaciones por SMS
        <br>
        <strong>Para </strong>notificar a los respectivos usuarios sobre una fuga de gas
      </td>
      <td></td>
      <td>E4</td>
    </tr>
    <tr>
      <td>US12</td>
      <td>Visualizar características del sistema GasGuard</td>
      <td>
        <strong>Como </strong>visitante del sitio web
        <br>
        <strong>Quiero </strong>ver las características principales de GasGuard en el landing page
        <br>
        <strong>Para </strong>entender como funciona y cómo puede garantiza seguridad
      </td>
      <td></td>
      <td>E5</td>
    </tr>
    <tr>
      <td>US13</td>
      <td>Visualizar sitio web desde dispositivo de preferencia</td>
      <td>
        <strong>Como </strong>visitante del sitio web
        <br>
        <strong>Quiero </strong>que la landing page sea accesible desde mi computadora, tablet o móvil
        <br>
        <strong>Para </strong>tener una buena experiencia desde cualquier dispositivo 
      </td>
      <td></td>
      <td>E5</td>
    </tr>
  </tbody>
</table>

## 3.3. Impact Mapping

## 3.4. Product Backlog

---

# Capítulo IV: Solution Software Design

## 4.1. Strategic-Level Domain-Driven Design

### 4.1.1. EventStorming

#### 4.1.1.1. Candidate Context Discovery

#### 4.1.1.2. Domain Message Flows Modeling

#### 4.1.1.3. Bounded Context Canvases

### 4.1.2. Context Mapping

### 4.1.3. Software Architecture

#### 4.1.3.1. Software Architecture System Landscape Diagram

#### 4.1.3.2. Software Architecture Context Level Diagrams

#### 4.1.3.3. Software Architecture Container Level Diagrams

#### 4.1.3.4. Software Architecture Deployment Diagrams

## 4.2. Tactical-Level Domain-Driven Design

### 4.2.X. Bounded Context: <Bounded Context Name>

#### 4.2.X.1. Domain Layer

#### 4.2.X.2. Interface Layer

#### 4.2.X.3. Application Layer

#### 4.2.X.4. Infrastructure Layer

#### 4.2.X.5. Component Level Diagrams

#### 4.2.X.6. Code Level Diagrams

##### 4.2.X.6.1. Domain Layer Class Diagrams

##### 4.2.X.6.2. Database Design Diagram

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

# Video About-the-Team

# Bibliografía

# Anexos
