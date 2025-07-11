<hr>

# <center>Informe del Trabajo Final</center>

<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Ingeniería de Software</strong><br>
    <strong>Diseño de Experimentos de Ingeniería de Software - 4433</strong><br>
    <strong>Profesor: Juan Carlos Tinoco Licas </strong><br>
    <br>INFORME
</p>

<center>

#### Startup: **RoomWise**

#### Product: **Sweet Manager**

</center>

## Team  Members:

<div align="center">

|               Member                   |    Code    |
| :---------------------------------:    | :--------: |
| Escobar Palomino ,Sebastian Matias     | u202125968 |
| Morales Montalvo,Omar Andrew           | u202212383 |
| Gutierrez Tume , Stanley Jeremy        | u202118152 |
| Salgado Luna, Fernando Brian           | u202212023 |
| Antonio Loayza, Luiggi Jeremy          | u202011431 |
| Arana Ramos, Jack                      | u202121875 |
</div>

# Registro de Versiones del Informe

| Versión | Fecha | Autor                                | Descripción de modificación                                                                 |
|---------|-------|--------------------------------------|--------------------------------------------------------------------------------------------|
| TB1     |27/4/25       | Escobar Palomino, Sebastian Matias   | - 1.1.1. Descripción de la Startup<br>- 1.2.1. Antecedentes y problemática                 |
| TB1     |27/4/25       | Morales Montalvo, Omar Andrew        | - 1.2.2. Lean UX Process (todos los subpuntos)<br>- 1.3. Segmentos objetivo<br>- 4.9. Software Object-Oriented Design<br>- 4.10. Database Design                 |
| TB1     |27/4/25       | Gutierrez Tume, Stanley Jeremy       | - 2.1. Competidores (todos los subpuntos)<br>- 2.2. Entrevistas (todos los subpuntos)<br>- 3.1. To-Be Scenario Mapping<br>- 3.2. User Stories<br>- 3.3. Product Backlog<br>- 3.4. Impact Mapping<br>- 5.1. Software Configuration Management (todos los subpuntos)         |
| TB1     |27/4/25       | Salgado Luna, Fernando Brian         | - 2.3. Needfinding (todos los subpuntos)<br>- 2.4. Ubiquitous Language<br>- 4.1. Style Guidelines (todos los subpuntos)<br>- 4.2. Information Architecture (todos los subpuntos)                     |
| TB1     |27/4/25       | Antonio Loayza, Luiggi Jeremy        | - 4.7. Web Applications Prototyping<br>- 4.8. Domain-Driven Software Architecture<br>- 4.5. Mobile Applications Prototyping<br>- 4.6. Web Applications UX/UI Design<br>- 4.3. Landing Page UI Design<br>- 4.4. Mobile Applications UX/UI Design   |
| TP1     |17/5/25       | Escobar Palomino, Sebastian Matias   | - 6.1.3. Core Behavior-Driven Development                |
| TP1     |17/5/25       | Morales Montalvo, Omar Andrew        | - 6.1.1. Core Entities Unit Tests            |
| TP1     |17/5/25       | Gutierrez Tume, Stanley Jeremy       | - 6.1.4. Core System Tests |
| TP1     |17/5/25       | Salgado Luna, Fernando Brian         | - 6.1.2. Core Integration Tests                  |
| TP1     |17/5/25       | Antonio Loayza, Luiggi Jeremy        | - 7.3. Continuous Deployment  |
| TB2     |21/6/25       | Arana Ramos, Jack                    | - 7.4. Continuous Monitoring<br>- 7.4.1. Tools and Practices<br>- 7.4.2. Monitoring Pipeline Components<br>- 7.4.3. Alerting Pipeline Components<br>- 7.4.4. Notification Pipeline Components  |
| TB2     |21/6/25       | Gutierrez Tume, Stanley Jeremy       | - 8.2.6. Data Analytics: Goals, KPIs and Metrics Selection<br>- 8.2.7. Web and Mobile Tracking Plan<br>- 8.3. Experimentation |
| TB2     |21/6/25       | Escobar Palomino, Sebastian Matias   | - 8.3.1. To-Be User Stories<br>- 8.3.2. To-Be Product Backlog<br>- Avance de Conclusiones, Bibliografía y Anexos<br>- Outcomes |
| TB2     |21/6/25       | Morales Montalvo, Omar Andrew        | - 6.3.3. Evaluaciones según heurísticas<br>- 6.4. Auditoría de Experiencias de Usuario<br>- 6.4.1. Auditoría realizada<br>- 6.4.1.1. Información del grupo auditado<br>- 6.4.1.2. Cronograma de auditoría realizada<br>- 6.4.1.3. Contenido de auditoría realizada<br>- 6.4.2. Auditoría recibida<br>- 6.4.2.1. Información del grupo auditor<br>- 6.4.2.2. Cronograma de auditoría recibida<br>- 6.4.2.3. Contenido de auditoría recibida<br>- 6.4.2.4. Resumen de modificaciones para subsanar hallazgos<br>- 8.1.5. Experiment Cards<br>- 8.2. Experiment Design<br>- 8.2.1. Hypotheses<br>- 8.2.2. Measures |
| TB2     |21/6/25       | Antonio Loayza, Luiggi Jeremy        | - 8.1.1. As-Is Summary<br>- 8.1.2. Raw Material: Assumptions, Knowledge Gaps, Ideas, Claims<br>- 8.1.3. Experiment-Ready Questions<br>- 8.1.4. Question Backlog |
| TB2     |21/6/25       | Salgado Luna, Fernando Brian         | - 8.2.3. Conditions<br>- 8.2.4. Scale Calculations and Decisions<br>- 8.2.5. Methods Selection |
| TF      |       | Arana Ramos, Jack                    | - 8.3.3. Pipeline-supported, Experiment-Driven To-Be Software Platform Lifecycle<br>- 8.3.3.1. To-Be Sprint Backlogs<br>- Conclusiones<br>- Conclusiones y recomendaciones<br>- Bibliografía<br>- Anexos |
| TF      |11/7/25       | Gutierrez Tume, Stanley Jeremy       | - 8.3.3.2. Implemented To-Be Landing Page Evidence<br>- 8.3.3.5. Implemented To-Be RESTful API and/or Serverless Backend Evidence |
| TF      |11/7/25       | Morales Montalvo, Omar Andrew        | - 8.3.3.3. Implemented To-Be Frontend-Web Application Evidence<br>- 8.3.3.4. Implemented To-Be Native-Mobile Application Evidence |
| TF      |11/7/25       | Salgado Luna, Fernando Brian         | - 8.3.3.6. Team Collaboration Insights<br>- 8.3.4. To-Be Validation Interviews<br>- 8.3.4.1. Diseño de Entrevistas |
| TF      |11/7/25       | Escobar Palomino, Sebastian Matias   | - 8.3.4.2. Registro de Entrevistas<br>- 8.4. Experiment Aftermath & Analysis<br>- 8.4.1. Analysis and Interpretation of Results<br>- 8.4.2. Re-scored and Re-prioritized Question Backlog |
| TF      |11/7/25       | Antonio Loayza, Luiggi Jeremy        | - 8.5. Continuous Learning<br>- 8.5.1. Shareback Session Artifacts: Learning Workflow<br>- 8.6. To-Be Software Platform Pre-launch<br>- 8.6.1. About-the-Product Intro Video |
| TF      |11/7/25       | Todos los participantes              | - Video About-The-Team |

---
# Project Report Collaboration Insights
TB1
La entrega TB1 se completó exitosamente y quedó documentada en el repositorio de GitHub de la organización del equipo: <https://github.com/1ASI0732-2510-4433-G1-ROOMWISE/final-project-report> Durante la elaboración del informe, se consideraron los siguientes aspectos:

- Cada miembro redactó y estructuró sus secciones asignadas en formato Markdown.

- Se realizaron commits periódicos para registrar los avances en el repositorio.

- Se finalizaron los Capítulos I al IV, junto con las conclusiones y el video de exposición, trabajando en colaboración.

- Se organizaron reuniones semanales para revisar el progreso del equipo y ajustar los contenidos.

TP
En esta entrega del trabajo parcial se completó de manera exitosa. Durante la elaboración del informe, se consideraron los siguientes aspectos:

- Se realizaron commits periódicos para registrar los avances en el repositorio.

- Se realizaron los Capítulos VI & VII.

- Se organizaron reuniones semanales para revisar el progreso del equipo y ajustar los contenidos.

- Se realizaron las pruebas unitarias e integrales.


<div style="text-align: center;">
  <img src="https://i.imgur.com/DpVf4gs.png" alt="" width="70%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/LMiaTpP.png" alt="" width="70%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/y3xZP2R.png" alt="" width="70%" />
</div>

## Tabla de Contenidos Interactiva

### Capítulo I: Introducción
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

### Capítulo II: Requirements Elicitation & Analysis
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

### Capítulo III: Requirements Specification
- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Product Backlog](#33-product-backlog)
- [3.4. Impact Mapping](#34-impact-mapping)

### Capítulo IV: Product Design
- [4.1. Style Guidelines](#41-style-guidelines)
  - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
  - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
  - [4.1.3. Mobile Style Guidelines](#413-mobile-style-guidelines)
    - [4.1.3.1. iOS Mobile Style Guidelines](#4131-ios-mobile-style-guidelines)
    - [4.1.3.2. Android Mobile Style Guidelines](#4132-android-mobile-style-guidelines)
- [4.2. Information Architecture](#42-information-architecture)
  - [4.2.1. Organization Systems](#421-organization-systems)
  - [4.2.2. Labeling Systems](#422-labeling-systems)
  - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
  - [4.2.4. Searching Systems](#424-searching-systems)
  - [4.2.5. Navigation Systems](#425-navigation-systems)
- [4.3. Landing Page UI Design](#43-landing-page-ui-design)
  - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
  - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
- [4.4. Mobile Applications UX/UI Design](#44-mobile-applications-uxui-design)
  - [4.4.1. Mobile Applications Wireframes](#441-mobile-applications-wireframes)
  - [4.4.2. Mobile Applications Wireflow Diagrams](#442-mobile-applications-wireflow-diagrams)
  - [4.4.3. Mobile Applications Mock-ups](#443-mobile-applications-mock-ups)
  - [4.4.4. Mobile Applications User Flow Diagrams](#444-mobile-applications-user-flow-diagrams)
- [4.5. Mobile Applications Prototyping](#45-mobile-applications-prototyping)
  - [4.5.1. Android Mobile Applications Prototyping](#451-android-mobile-applications-prototyping)
  - [4.5.2. iOS Mobile Applications Prototyping](#452-ios-mobile-applications-prototyping)
- [4.6. Web Applications UX/UI Design](#46-web-applications-uxui-design)
  - [4.6.1. Web Applications Wireframes](#461-web-applications-wireframes)
  - [4.6.2. Web Applications Wireflow Diagrams](#462-web-applications-wireflow-diagrams)
  - [4.6.3. Web Applications Mock-ups](#463-web-applications-mock-ups)
  - [4.6.4. Web Applications User Flow Diagrams](#464-web-applications-user-flow-diagrams)
- [4.7. Web Applications Prototyping](#47-web-applications-prototyping)
- [4.8. Domain-Driven Software Architecture](#48-domain-driven-software-architecture)
  - [4.8.1. Software Architecture Context Diagram](#481-software-architecture-context-diagram)
  - [4.8.2. Software Architecture Container Diagrams](#482-software-architecture-container-diagrams)
  - [4.8.3. Software Architecture Components Diagrams](#483-software-architecture-components-diagrams)
- [4.9. Software Object-Oriented Design](#49-software-object-oriented-design)
  - [4.9.1. Class Diagrams](#491-class-diagrams)
  - [4.9.2. Class Dictionary](#492-class-dictionary)
- [4.10. Database Design](#410-database-design)
  - [4.10.1. Relational/Non-Relational Database Diagram](#4101-relationalnon-relational-database-diagram)

### Capítulo V: Product Implementation
- [5.1. Software Configuration Management](#51-software-configuration-management)
  - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
  - [5.1.2. Source Code Management](#512-source-code-management)
  - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
  - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
- [5.2. Product Implementation & Deployment](#52-product-implementation--deployment)
  - [5.2.1. Sprint Backlogs](#521-sprint-backlogs)
  - [5.2.2. Implemented Landing Page Evidence](#522-implemented-landing-page-evidence)
  - [5.2.3. Implemented Frontend-Web Application Evidence](#523-implemented-frontend-web-application-evidence)
  - [5.2.4. Acuerdo de Servicio - SaaS](#524-acuerdo-de-servicio---saas)
  - [5.2.5. Implemented Native-Mobile Application Evidence](#525-implemented-native-mobile-application-evidence)
  - [5.2.6. Implemented RESTful API and/or Serverless Backend Evidence](#526-implemented-restful-api-andor-serverless-backend-evidence)
  - [5.2.7. RESTful API Documentation](#527-restful-api-documentation)
  - [5.2.8. Team Collaboration Insights](#528-team-collaboration-insights)
- [5.3. Video About-the-Product](#53-video-about-the-product)

### Capítulo VI: Product Verification & Validation
- [6.1. Testing Suites & Validation](#61-testing-suites--validation)
  - [6.1.1. Core Entities Unit Tests](#611-core-entities-unit-tests)
  - [6.1.2. Core Integration Tests](#612-core-integration-tests)
  - [6.1.3. Core Behavior-Driven Development](#613-core-behavior-driven-development)
  - [6.1.4. Core System Tests](#614-core-system-tests)
- [6.2. Static testing & Verification](#62-static-testing--verification)
  - [6.2.1. Static Code Analysis](#621-static-code-analysis)
    - [6.2.1.1. Coding standard & Code conventions](#6211-coding-standard--code-conventions)
    - [6.2.1.2. Code Quality & Code Security](#6212-code-quality--code-security)
  - [6.2.2. Reviews](#622-reviews)
- [6.3. Validation Interviews](#63-validation-interviews)
  - [6.3.1. Diseño de Entrevistas](#631-diseño-de-entrevistas)
  - [6.3.2. Registro de Entrevistas](#632-registro-de-entrevistas)
  - [6.3.3. Evaluaciones según heurísticas](#633-evaluaciones-según-heurísticas)
- [6.4. Auditoría de Experiencias de Usuario](#64-auditoría-de-experiencias-de-usuario)
  - [6.4.1. Auditoría realizada](#641-auditoría-realizada)
    - [6.4.1.1. Información del grupo auditado](#6411-información-del-grupo-auditado)
    - [6.4.1.2. Cronograma de auditoría realizada](#6412-cronograma-de-auditoría-realizada)
    - [6.4.1.3. Contenido de auditoría realizada](#6413-contenido-de-auditoría-realizada)
  - [6.4.2. Auditoría recibida](#642-auditoría-recibida)
    - [6.4.2.1. Información del grupo auditor](#6421-información-del-grupo-auditor)
    - [6.4.2.2. Cronograma de auditoría recibida](#6422-cronograma-de-auditoría-recibida)
    - [6.4.2.3. Contenido de auditoría recibida](#6423-contenido-de-auditoría-recibida)
    - [6.4.2.4. Resumen de modificaciones para subsanar hallazgos](#6424-resumen-de-modificaciones-para-subsanar-hallazgos)

### Capítulo VII: DevOps Practices
- [7.1. Continuous Integration](#71-continuous-integration)
  - [7.1.1. Tools and Practices](#711-tools-and-practices)
  - [7.1.2. Build & Test Suite Pipeline Components](#712-build--test-suite-pipeline-components)
- [7.2. Continuous Delivery](#72-continuous-delivery)
  - [7.2.1. Tools and Practices](#721-tools-and-practices)
  - [7.2.2. Stages Deployment Pipeline Components](#722-stages-deployment-pipeline-components)
- [7.3. Continuous Deployment](#73-continuous-deployment)
  - [7.3.1. Tools and Practices](#731-tools-and-practices)
  - [7.3.2. Production Deployment Pipeline Components](#732-production-deployment-pipeline-components)
- [7.4. Continuous Monitoring](#74-continuous-monitoring)
  - [7.4.1. Tools and Practices](#741-tools-and-practices)
  - [7.4.2. Monitoring Pipeline Components](#742-monitoring-pipeline-components)
  - [7.4.3. Alerting Pipeline Components](#743-alerting-pipeline-components)
  - [7.4.4. Notification Pipeline Components](#744-notification-pipeline-components)

### Capítulo VIII: Experiment-Driven Development
- [8.1. Experiment Planning](#81-experiment-planning)
  - [8.1.1. As-Is Summary](#811-as-is-summary)
  - [8.1.2. Raw Material: Assumptions, Knowledge Gaps, Ideas, Claims](#812-raw-material-assumptions-knowledge-gaps-ideas-claims)
  - [8.1.3. Experiment-Ready Questions](#813-experiment-ready-questions)
  - [8.1.4. Question Backlog](#814-question-backlog)
  - [8.1.5. Experiment Cards](#815-experiment-cards)
- [8.2. Experiment Design](#82-experiment-design)
  - [8.2.1. Hypotheses](#821-hypotheses)
  - [8.2.2. Measures](#822-measures)
  - [8.2.3. Conditions](#823-conditions)
  - [8.2.4. Scale Calculations and Decisions](#824-scale-calculations-and-decisions)
  - [8.2.5. Methods Selection](#825-methods-selection)
  - [8.2.6. Data Analytics: Goals, KPIs and Metrics Selection](#826-data-analytics-goals-kpis-and-metrics-selection)
  - [8.2.7. Web and Mobile Tracking Plan](#827-web-and-mobile-tracking-plan)
- [8.3. Experimentation](#83-experimentation)
  - [8.3.1. To-Be User Stories](#831-to-be-user-stories)
  - [8.3.2. To-Be Product Backlog](#832-to-be-product-backlog)
  - [8.3.3. Pipeline-supported, Experiment-Driven To-Be Software Platform Lifecycle](#833-pipeline-supported-experiment-driven-to-be-software-platform-lifecycle)
    - [8.3.3.1. To-Be Sprint Backlogs](#8331-to-be-sprint-backlogs)
    - [8.3.3.2. Implemented To-Be Landing Page Evidence](#8332-implemented-to-be-landing-page-evidence)
    - [8.3.3.3. Implemented To-Be Frontend-Web Application Evidence](#8333-implemented-to-be-frontend-web-application-evidence)
    - [8.3.3.4. Implemented To-Be Native-Mobile Application Evidence](#8334-implemented-to-be-native-mobile-application-evidence)
    - [8.3.3.5. Implemented To-Be RESTful API and/or Serverless Backend Evidence](#8335-implemented-to-be-restful-api-andor-serverless-backend-evidence)
    - [8.3.3.6. Team Collaboration Insights](#8336-team-collaboration-insights)
  - [8.3.4. To-Be Validation Interviews](#834-to-be-validation-interviews)
    - [8.3.4.1. Diseño de Entrevistas](#8341-diseño-de-entrevistas)
    - [8.3.4.2. Registro de Entrevistas](#8342-registro-de-entrevistas)
- [8.4. Experiment Aftermath & Analysis](#84-experiment-aftermath--analysis)
  - [8.4.1. Analysis and Interpretation of Results](#841-analysis-and-interpretation-of-results)
  - [8.4.2. Re-scored and Re-prioritized Question Backlog](#842-re-scored-and-re-prioritized-question-backlog)
- [8.5. Continuous Learning](#85-continuous-learning)
  - [8.5.1. Shareback Session Artifacts: Learning Workflow](#851-shareback-session-artifacts-learning-workflow)
- [8.6. To-Be Software Platform Pre-launch](#86-to-be-software-platform-pre-launch)
  - [8.6.1. About-the-Product Intro Video](#861-about-the-product-intro-video)

### [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
### [Video About-the-Team](#video-about-the-team)
### [Bibliografía](#bibliografía)
### [Anexos](#anexos)


# Student Outcome 4

**Criterio:** La capacidad de reconocer responsabilidades éticas y profesionales en situaciones de ingeniería y hacer juicios informados, que deben considerar el impacto de las soluciones de ingeniería en contextos globales, económicos, ambientales y sociales.

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 4.

| Criterio Específico | Acciones Realizadas (TB1-TP-TB2-TF) | Conclusiones |
|---------------------|---------------------------|-------------|
| **Reconoce las responsabilidades éticas y profesionales en situaciones de ingeniería** | **TB1:** <br><br>**Escobar Palomino, Sebastian Matias (u202125968):** Durante el desarrollo del TB1, identifiqué y documenté los principios éticos fundamentales que debían guiar nuestro proyecto, incluyendo la privacidad de datos, la transparencia en algoritmos y la accesibilidad universal. Implementé un marco de evaluación ética que consideraba el impacto potencial de cada funcionalidad en diferentes grupos de usuarios, especialmente aquellos en situación de vulnerabilidad. Además, establecí protocolos para el manejo responsable de información sensible y promovimos el uso de tecnologías abiertas cuando era posible.<br><br>**Morales Montalvo, Omar Andrew (u202212383):** Mi contribución se enfocó en el análisis de las implicaciones éticas del manejo de datos personales en el sistema. Desarrollé políticas de privacidad claras y comprensibles, implementé medidas de seguridad robustas para proteger la información de los usuarios, y aseguré el cumplimiento de regulaciones como GDPR y LOPD. También promovimos la transparencia en el procesamiento de datos, permitiendo a los usuarios conocer y controlar el uso de su información.<br><br>**Gutierrez Tume, Stanley Jeremy (u202118152):** Durante esta fase, me dediqué a evaluar el impacto social de nuestras decisiones de diseño, considerando cómo diferentes grupos demográficos podrían verse afectados por la implementación del sistema. Realicé análisis de accesibilidad para usuarios con discapacidades, propuse interfaces inclusivas y documenté consideraciones éticas relacionadas con la equidad en el acceso a la tecnología. También participé en discusiones sobre el uso responsable de la inteligencia artificial en nuestras funcionalidades.<br><br>**Salgado Luna, Fernando Brian (u202212023):** Mi enfoque se centró en identificar dilemas éticos relacionados con la automatización y su impacto en el empleo. Analicé cómo nuestro sistema podría afectar los roles laborales existentes y propuse estrategias para minimizar disrupciones negativas. Además, establecí criterios éticos para la toma de decisiones automatizadas, asegurando que el sistema mantuviera la dignidad humana y evitara sesgos discriminatorios en sus procesos.<br><br>**Antonio Loayza, Luiggi Jeremy (u202011431):** Durante el TB1, me responsabilicé de evaluar las implicaciones ambientales de nuestras decisiones tecnológicas, promoviendo el uso de arquitecturas eficientes energéticamente y servicios en la nube con políticas de sostenibilidad. También analicé el ciclo de vida del software, considerando el impacto ambiental desde el desarrollo hasta el despliegue y mantenimiento del sistema.<br><br>**Arana Ramos, Jack (u202121875):** En el TB1, me especialicé en el análisis de dilemas éticos relacionados con la inteligencia artificial y machine learning implementados en el sistema. Desarrollé lineamientos para el uso ético de algoritmos de aprendizaje automático, estableciendo protocolos para la detección y mitigación de sesgos algorítmicos. También me enfoqué en garantizar la explicabilidad de los modelos de IA, asegurando que las decisiones automatizadas fueran transparentes y auditables. Además, establecí marcos de evaluación continua para monitorear el comportamiento ético de los algoritmos en diferentes contextos culturales y demográficos.<br><br>**TP:** <br><br>**Escobar Palomino, Sebastian Matias (u202125968):** En esta entrega, profundicé en la implementación de pruebas éticas para validar que nuestro sistema cumpliera con los estándares profesionales establecidos. Desarrollé casos de prueba específicos para evaluar la equidad, transparencia y responsabilidad de nuestras funcionalidades, asegurando que los resultados fueran auditables y justificables desde una perspectiva ética.<br><br>**Morales Montalvo, Omar Andrew (u202212383):** Mi contribución se centró en la documentación ética del sistema, creando manuales que explicaran claramente las decisiones éticas tomadas durante el desarrollo. Implementé mecanismos de monitoreo continuo para detectar posibles sesgos o problemas éticos en el funcionamiento del sistema, y establecí procedimientos para la corrección rápida de estos problemas.<br><br>**Gutierrez Tume, Stanley Jeremy (u202118152):** Durante el TP, me enfoqué en validar que las pruebas automatizadas incluyeran verificaciones éticas, asegurando que el sistema no solo funcionara correctamente desde un punto de vista técnico, sino que también cumpliera con nuestros estándares éticos y profesionales. Desarrollé métricas para medir el impacto social positivo de nuestras funcionalidades.<br><br>**Salgado Luna, Fernando Brian (u202212023):** En esta fase, elaboré documentación detallada sobre las consideraciones éticas en el desarrollo de pruebas unitarias, asegurando que cada componente del sistema fuera evaluado no solo por su funcionalidad técnica, sino también por su impacto ético. Implementé protocolos de revisión ética que se integraron en nuestro proceso de desarrollo continuo.<br><br>**Antonio Loayza, Luiggi Jeremy (u202011431):** Mi trabajo se centró en establecer procesos de despliegue continuo que incorporaran verificaciones éticas automáticas. Desarrollé pipelines que no solo validaran la funcionalidad técnica, sino que también evaluaran el cumplimiento de nuestros estándares éticos antes de cada despliegue en producción.<br><br>**Arana Ramos, Jack (u202121875):** Durante el TP, implementé sistemas de testing ético específicos para validar el comportamiento de los algoritmos de machine learning en condiciones diversas. Desarrollé suites de pruebas que evaluaban la fairness algorítmica, la robustez ante datos sesgados y la consistencia de decisiones en diferentes grupos demográficos. También establecí procesos de validación cruzada ética que aseguraban que los modelos de IA mantuvieran comportamientos éticos consistentes durante las actualizaciones y reentrenamientos del sistema.<br><br>**TB2:** <br><br>**Escobar Palomino, Sebastian Matias (u202125968):** En la fase final, lideré la implementación de un sistema de auditoría ética continua que monitoreaba el comportamiento del sistema en producción. Establecí métricas de impacto social y ambiental, y desarrollé informes regulares para evaluar el cumplimiento de nuestros compromisos éticos. También implementé mecanismos de retroalimentación de usuarios para identificar problemas éticos no previstos.<br><br>**Morales Montalvo, Omar Andrew (u202212383):** Durante el TB2, consolidé toda la documentación ética del proyecto, creando un marco completo que detallaba nuestras políticas, procedimientos y compromisos éticos. Desarrollé un sistema de certificación interna que garantizaba que cada nueva funcionalidad cumpliera con nuestros estándares éticos antes de su liberación.<br><br>**Gutierrez Tume, Stanley Jeremy (u202118152):** Mi contribución final se centró en validar que todas las funcionalidades del sistema cumplieran con principios éticos de transparencia, equidad y responsabilidad. Desarrollé un conjunto completo de pruebas éticas automatizadas que se ejecutaban como parte de nuestro pipeline de integración continua, asegurando que ningún cambio comprometiera nuestros estándares éticos.<br><br>**Salgado Luna, Fernando Brian (u202212023):** En esta etapa final, me enfoqué en evaluar el impacto real de nuestro sistema en los usuarios finales, desarrollando métricas de bienestar y satisfacción que iban más allá de la funcionalidad técnica. Implementé sistemas de feedback ético que permitían a los usuarios reportar preocupaciones éticas y sugerir mejoras en la responsabilidad social del sistema.<br><br>**Antonio Loayza, Luiggi Jeremy (u202011431):** Durante el TB2, establecí procesos de monitoreo post-despliegue que evaluaban continuamente el impacto ético y social de nuestro sistema. Desarrollé alertas automáticas para identificar patrones de uso que pudieran indicar problemas éticos, y establecí procedimientos de respuesta rápida para abordar cualquier problema identificado.<br><br>**Arana Ramos, Jack (u202121875):** En la fase final del TB2, implementé un sistema completo de gobernanza de IA que aseguraba el cumplimiento ético continuo de todos los componentes de machine learning del sistema. Desarrollé dashboards de transparencia algorítmica que permitían a los stakeholders monitorear el comportamiento ético de los modelos en tiempo real. También establecí protocolos de intervención humana para casos donde los algoritmos pudieran tomar decisiones éticamente cuestionables, garantizando que siempre existiera supervisión humana en decisiones críticas que afectaran a los usuarios finales.<br><br>**TF:** <br><br>**Escobar Palomino, Sebastian Matias (u202125968):** En el trabajo final, consolidé la evaluación integral del impacto ético del proyecto completo, desarrollando un informe exhaustivo que documentaba todas las decisiones éticas tomadas durante el ciclo de vida del proyecto. Implementé un framework de lecciones aprendidas que servirá como guía para futuros proyectos, estableciendo mejores prácticas para la integración de consideraciones éticas en proyectos de ingeniería de software. También desarrollé métricas de éxito ético que permitieron cuantificar el impacto positivo del sistema en términos de responsabilidad social y profesional.<br><br>**Morales Montalvo, Omar Andrew (u202212383):** Durante el TF, creé un manual completo de ética en ingeniería que compilaba todas las políticas, procedimientos y herramientas desarrolladas durante el proyecto. Este manual incluye templates reutilizables para evaluaciones éticas, checklists de verificación y marcos de toma de decisiones éticas que pueden ser aplicados en futuros proyectos. También desarrollé un sistema de certificación ética que garantiza que los ingenieros del equipo mantengan competencias actualizadas en ética profesional.<br><br>**Gutierrez Tume, Stanley Jeremy (u202118152):** Mi contribución al TF se centró en la validación final de que el sistema cumpliera con todos los estándares éticos y profesionales establecidos desde el inicio del proyecto. Desarrollé un conjunto completo de métricas de impacto social que demuestran cómo el sistema contribuye positivamente al bienestar de diferentes grupos de usuarios. También implementé un sistema de monitoreo a largo plazo que continuará evaluando el impacto ético del sistema post-implementación.<br><br>**Salgado Luna, Fernando Brian (u202212023):** En la fase final, desarrollé un análisis retrospectivo completo que evaluaba la efectividad de nuestras decisiones éticas y su impacto real en los usuarios finales. Implementé un sistema de mejora continua que utilizaba feedback de usuarios para refinar continuamente nuestros estándares éticos. También creé un programa de capacitación en ética profesional que asegura que futuros miembros del equipo comprendan y apliquen nuestros principios éticos establecidos.<br><br>**Antonio Loayza, Luiggi Jeremy (u202011431):** Durante el TF, establecí un framework completo de sostenibilidad ética que asegura que el sistema mantenga altos estándares éticos a lo largo de su ciclo de vida operativo. Desarrollé procesos de auditoría ética regular y sistemas de alerta temprana que identifican potenciales problemas éticos antes de que se materialicen. También implementé un plan de evolución ética que permite que el sistema se adapte a nuevos estándares y expectativas éticas emergentes.<br><br>**Arana Ramos, Jack (u202121875):** En el trabajo final, desarrollé un marco completo de ética en inteligencia artificial que establece estándares de la industria para el desarrollo y despliegue responsable de sistemas de IA. Este framework incluye protocolos específicos para la evaluación continua de sesgos algorítmicos, procedimientos de transparencia algorítmica y sistemas de accountability que aseguran la responsabilidad humana en todas las decisiones automatizadas. También implementé un sistema de monitoreo de impacto ético de largo plazo que evalúa continuamente cómo los algoritmos de IA afectan a diferentes comunidades y grupos demográficos, asegurando que el sistema evolucione para maximizar el beneficio social mientras minimiza potenciales daños. | La integración de consideraciones éticas desde el inicio del proyecto (TB1) demostró ser fundamental para el desarrollo responsable de soluciones de ingeniería. El equipo logró establecer un marco ético sólido que guió todas las decisiones técnicas, desde la arquitectura del sistema hasta la implementación de funcionalidades específicas. La identificación temprana de dilemas éticos relacionados con privacidad, accesibilidad, impacto social, sostenibilidad ambiental y ética en inteligencia artificial permitió tomar decisiones informadas que balancearon efectividad técnica con responsabilidad social.<br><br>Durante el desarrollo del trabajo parcial (TP), el equipo fortaleció su capacidad para integrar consideraciones éticas en procesos técnicos como testing y despliegue continuo. La implementación de pruebas éticas automatizadas, incluyendo validaciones específicas para algoritmos de IA, demostró que es posible mantener altos estándares éticos sin comprometer la eficiencia del desarrollo.<br><br>La finalización del TB2 consolidó nuestro enfoque hacia la ingeniería ética y socialmente responsable. La implementación de sistemas de monitoreo ético continuo, incluyendo gobernanza especializada para componentes de IA, demostró que los ingenieros tienen la responsabilidad de asegurar que sus soluciones contribuyan positivamente a la sociedad.<br><br>El trabajo final (TF) estableció un legado duradero al crear frameworks, manuales y sistemas de mejora continua que aseguran la sostenibilidad ética a largo plazo. La experiencia completa del proyecto reforzó que la excelencia en ingeniería incluye necesariamente la responsabilidad ética y el compromiso con el bienestar global, estableciendo precedentes valiosos para futuros proyectos de ingeniería responsable. |
| **Evalúa las soluciones de ingeniería considerando el impacto global, económico, ambiental y social** | **TB1:** <br><br>**Escobar Palomino, Sebastian Matias (u202125968):** Desarrollé un marco de evaluación multidimensional que analizaba cada decisión técnica desde perspectivas globales, económicas, ambientales y sociales. Implementé matrices de impacto que consideraban efectos a corto y largo plazo, evaluando cómo nuestras soluciones podrían afectar diferentes regiones geográficas y grupos socioeconómicos. También establecí indicadores cuantitativos para medir el impacto positivo de nuestras decisiones en cada dimensión.<br><br>**Morales Montalvo, Omar Andrew (u202212383):** Me enfoqué en evaluar el impacto económico de nuestras decisiones tecnológicas, analizando el costo-beneficio no solo para nuestro proyecto, sino para los stakeholders y la sociedad en general. Desarrollé modelos de análisis que consideraban la democratización del acceso a la tecnología, la creación de valor social y la sostenibilidad económica a largo plazo de nuestras soluciones.<br><br>**Gutierrez Tume, Stanley Jeremy (u202118152):** Durante el TB1, me dediqué a evaluar el impacto social de nuestras decisiones de diseño, considerando factores como inclusión digital, accesibilidad para diferentes grupos demográficos y potencial para reducir brechas tecnológicas. Desarrollé criterios de evaluación que priorizaban soluciones que beneficiaran a comunidades marginadas y promovieran la equidad social.<br><br>**Salgado Luna, Fernando Brian (u202212023):** Mi contribución se centró en el análisis del impacto ambiental de nuestras decisiones tecnológicas, evaluando la huella de carbono, el consumo energético y la sostenibilidad de los recursos utilizados. Implementé métricas de eficiencia ambiental y propuse alternativas más sostenibles cuando era posible, considerando el ciclo de vida completo de nuestras soluciones.<br><br>**Antonio Loayza, Luiggi Jeremy (u202011431):** Durante esta fase, desarrollé análisis de impacto global que consideraban cómo nuestras soluciones podrían escalar y adaptarse a diferentes contextos culturales y regulatorios. Evalué la interoperabilidad con sistemas existentes en diferentes países y regiones, y consideré implicaciones geopolíticas de nuestras decisiones tecnológicas.<br><br>**Arana Ramos, Jack (u202121875):** En el TB1, me enfoqué en evaluar el impacto socioeconómico de la implementación de algoritmos de inteligencia artificial en diferentes contextos globales. Analicé cómo los modelos de machine learning podrían afectar la distribución de oportunidades económicas, considerando factores como el acceso desigual a la tecnología y las diferencias en infraestructura digital entre países desarrollados y en desarrollo. También evalué el impacto potencial en mercados laborales específicos, desarrollando estrategias para maximizar los beneficios sociales mientras se minimizan las disrupciones negativas.<br><br>**TP:** <br><br>**Escobar Palomino, Sebastian Matias (u202125968):** En el trabajo parcial, refiné nuestros métodos de evaluación de impacto, incorporando feedback de la primera fase para desarrollar métricas más precisas. Implementé sistemas de monitoreo que rastreaban el impacto real de nuestras decisiones en las cuatro dimensiones, permitiendo ajustes basados en datos reales en lugar de proyecciones teóricas.<br><br>**Morales Montalvo, Omar Andrew (u202212383):** Mi trabajo se centró en documentar detalladamente las evaluaciones de impacto realizadas, creando un marco replicable para futuros proyectos. Desarrollé plantillas de análisis que facilitaran la evaluación sistemática de impacto en proyectos similares, contribuyendo al desarrollo de mejores prácticas en ingeniería responsable.<br><br>**Gutierrez Tume, Stanley Jeremy (u202118152):** Durante el TP, implementé pruebas específicas que validaran que nuestro sistema cumpliera con los criterios de impacto social positivo establecidos en la primera fase. Desarrollé casos de prueba que evaluaban no solo la funcionalidad técnica, sino también la contribución social de cada característica del sistema.<br><br>**Salgado Luna, Fernando Brian (u202212023):** En esta fase, consolidé las evaluaciones de impacto ambiental, desarrollando un sistema de métricas que permitía el monitoreo continuo de nuestra huella ecológica. Implementé alertas automáticas para identificar cuando el sistema excedía umbrales ambientales predefinidos, permitiendo acciones correctivas inmediatas.<br><br>**Antonio Loayza, Luiggi Jeremy (u202011431):** Mi contribución se enfocó en validar que nuestros procesos de despliegue continuo consideraran evaluaciones de impacto en cada liberación. Desarrollé pipelines que incluían verificaciones automáticas de impacto global, económico, ambiental y social antes de cada despliegue en producción.<br><br>**Arana Ramos, Jack (u202121875):** Durante el TP, desarrollé métricas específicas para evaluar el impacto de los algoritmos de IA en la equidad económica y social. Implementé sistemas de monitoreo que rastreaban cómo las decisiones algorítmicas afectaban diferentes grupos demográficos y socioeconómicos, asegurando que el sistema promoviera la inclusión en lugar de perpetuar desigualdades existentes.<br><br>**TB2:** <br><br>**Escobar Palomino, Sebastian Matias (u202125968):** En la fase final, implementé un sistema completo de evaluación de impacto que operaba en tiempo real, proporcionando retroalimentación continua sobre el desempeño de nuestro sistema en las cuatro dimensiones. Desarrollé dashboards que permitían a los stakeholders monitorear el impacto positivo del sistema y identificar áreas de mejora.<br><br>**Morales Montalvo, Omar Andrew (u202212383):** Durante el TB2, consolidé toda la documentación de impacto del proyecto, creando un informe completo que detallaba cómo cada decisión técnica había sido evaluada y validada desde perspectivas múltiples. Este documento sirvió como modelo para futuros proyectos y como evidencia del compromiso del equipo con la ingeniería responsable.<br><br>**Gutierrez Tume, Stanley Jeremy (u202118152):** Mi trabajo final se centró en validar que el sistema cumpliera con todos los criterios de impacto positivo establecidos durante el proyecto. Desarrollé un conjunto completo de pruebas de impacto que evaluaban el desempeño del sistema en condiciones reales, confirmando que nuestras proyecciones teóricas se materializaran en beneficios concretos.<br><br>**Salgado Luna, Fernando Brian (u202212023):** En esta etapa final, establecí sistemas de monitoreo post-implementación que continuarían evaluando el impacto ambiental del sistema después de su despliegue. Desarrollé protocolos de optimización continua que aseguraran que el sistema mantuviera y mejorara su desempeño ambiental a lo largo del tiempo.<br><br>**Antonio Loayza, Luiggi Jeremy (u202011431):** Durante el TB2, implementé procesos de evaluación de impacto post-despliegue que proporcionaban feedback continuo sobre el desempeño real del sistema en contextos globales diversos. Establecí métricas de éxito que iban más allá de indicadores técnicos tradicionales, incluyendo medidas de impacto social, económico y ambiental positivo.<br><br>**Arana Ramos, Jack (u202121875):** En la fase final del TB2, implementé un sistema completo de evaluación de impacto algorítmico que monitoreaba continuamente cómo los componentes de IA del sistema afectaban las cuatro dimensiones de impacto. Desarrollé indicadores específicos para medir la contribución de los algoritmos al desarrollo económico inclusivo, la reducción de brechas digitales y la promoción de oportunidades equitativas a nivel global.<br><br>**TF:** <br><br>**Escobar Palomino, Sebastian Matias (u202125968):** En el trabajo final, desarrollé un análisis integral del impacto acumulativo del proyecto en las cuatro dimensiones evaluadas. Creé un modelo predictivo que estima el impacto a largo plazo de nuestras decisiones tecnológicas, permitiendo una evaluación más precisa del retorno social de la inversión en ingeniería responsable. También establecí un framework de evaluación continua que permitirá monitorear y optimizar el impacto del sistema durante toda su vida útil operativa.<br><br>**Morales Montalvo, Omar Andrew (u202212383):** Durante el TF, consolidé un reporte completo de impacto que cuantifica los beneficios económicos, sociales, ambientales y globales generados por el proyecto. Desarrollé métricas de valor social creado que demuestran cómo la inversión en consideraciones éticas genera retornos positivos tanto para los stakeholders como para la sociedad. También creé un modelo de escalabilidad que evalúa cómo estos impactos positivos pueden replicarse y amplificarse en futuros proyectos.<br><br>**Gutierrez Tume, Stanley Jeremy (u202118152):** Mi contribución al TF se centró en validar el impacto social real del sistema mediante estudios de caso con usuarios finales. Desarrollé un conjunto de métricas de impacto social que demuestran cómo el sistema ha mejorado la calidad de vida y las oportunidades de diferentes grupos de usuarios. También implementé un sistema de seguimiento longitudinal que continuará evaluando el impacto social del sistema a largo plazo.<br><br>**Salgado Luna, Fernando Brian (u202212023):** En la fase final, desarrollé un análisis completo del impacto ambiental del ciclo de vida del proyecto, cuantificando tanto los beneficios ambientales generados como la huella ecológica del sistema. Implementé un programa de compensación ambiental que asegura que el proyecto sea carbono-neutral y contribuya positivamente a objetivos de sostenibilidad ambiental. También establecí métricas de eficiencia ambiental que guiarán futuras optimizaciones del sistema.<br><br>**Antonio Loayza, Luiggi Jeremy (u202011431):** Durante el TF, creé un análisis completo del impacto global del proyecto, evaluando cómo nuestras decisiones tecnológicas han contribuido a objetivos de desarrollo sostenible global. Desarrollé un modelo de escalabilidad internacional que evalúa el potencial del sistema para generar impacto positivo en diferentes contextos culturales y socioeconómicos. También implementé un framework de adaptación cultural que permitirá que el sistema mantenga su efectividad e impacto positivo cuando se despliegue en diferentes regiones del mundo.<br><br>**Arana Ramos, Jack (u202121875):** En el trabajo final, desarrollé un análisis comprehensivo del impacto de los algoritmos de IA en las cuatro dimensiones evaluadas, creando el primer framework de evaluación de impacto algorítmico multidimensional del equipo. Este análisis incluyó métricas específicas para evaluar cómo los algoritmos de machine learning contribuyen a la equidad económica, la inclusión social, la sostenibilidad ambiental y el desarrollo global responsable. También implementé un sistema de optimización algorítmica continua que ajusta automáticamente los modelos de IA para maximizar el impacto positivo mientras mantiene la efectividad técnica, estableciendo un nuevo estándar para el desarrollo de IA socialmente responsable. | El desarrollo del TB1 estableció un precedente importante al demostrar que la evaluación multidimensional de impacto es esencial para el desarrollo de soluciones de ingeniería responsables. La implementación de marcos de evaluación que consideraron simultáneamente impactos globales, económicos, ambientales y sociales, incluyendo consideraciones específicas para el impacto de la inteligencia artificial, permitió tomar decisiones más informadas y desarrollar soluciones más robustas y sostenibles.<br><br>La experiencia del trabajo parcial (TP) demostró que es posible integrar evaluaciones de impacto en procesos de desarrollo ágil sin comprometer la eficiencia. La implementación de métricas automáticas de impacto y la integración de evaluaciones en pipelines de desarrollo continuo estableció un modelo escalable para ingeniería responsable.<br><br>La finalización del TB2 consolidó nuestro enfoque hacia la ingeniería con impacto positivo, demostrando que es posible crear soluciones técnicamente excelentes que también generen valor social, económico y ambiental significativo. La implementación de sistemas de monitoreo continuo de impacto confirmó que nuestro enfoque multidimensional había sido efectivo.<br><br>El trabajo final (TF) estableció un modelo completo y replicable para la evaluación e optimización continua del impacto multidimensional en proyectos de ingeniería. La cuantificación del impacto acumulativo y el desarrollo de frameworks de escalabilidad demuestran que la consideración sistemática de impactos diversos no es una limitación sino una oportunidad para crear soluciones más innovadoras y valiosas. El proyecto estableció precedentes importantes para futuros proyectos que busquen maximizar su contribución positiva a la sociedad mientras mantienen excelencia técnica. |




# Capítulo I: Introducción

## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
Una administración eficaz de un hotel es clave para asegurar que los huéspedes disfruten de una experiencia única y, al mismo tiempo, maximizar las ganancias. Con ese objetivo, presentamos “Sweet Manager”, una aplicación diseñada para optimizar todos los procesos operativos de la gestión hotelera, garantizando estancias cómodas y de calidad para los visitantes.

Sweet Manager es una herramienta completa que cubre desde el monitoreo de ingresos y gastos hasta la supervisión de proveedores, inventarios y recursos humanos. Con su interfaz amigable y sencilla de usar, permite a los gerentes y propietarios de hoteles controlar todos los aspectos de su negocio de manera remota y en cualquier momento.

Entre sus principales características se incluyen:

- Seguimiento de Ingresos y Egresos: Sweet Manager proporciona un monitoreo detallado de los ingresos y egresos del hotel, ofreciendo informes actualizados para tomar decisiones más acertadas.

- Gestión de Inventarios: Nuestra aplicación facilita la administración de inventarios de alimentos, bebidas, productos de tocador y otros, evitando tanto escasez como desperdicios.

- Gestión de Proveedores: Simplificamos la interacción con proveedores, permitiendo realizar pedidos de forma ágil y eficiente.

- Gestión de Clientes: Optimiza la organización y control de los huéspedes mediante el uso de calendarios y agendas para una gestión más eficiente de las reservas.


### Misión:
 Nuestro objetivo es ser la principal opción en gestión hotelera a nivel global, proporcionando a hoteles de cualquier tamaño soluciones tecnológicas avanzadas que facilitan y mejoran cada aspecto de su operación, lo que les permite a nuestros clientes concentrarse en brindar experiencias excepcionales a sus visitantes.
### Visión:
Ofrecer a los responsables de la administración hotelera una solución completa y accesible que cubra aspectos clave como la administración de ingresos y egresos, la supervisión de inventarios, y la gestión de relaciones con proveedores y clientes. Buscamos simplificar el manejo del negocio, permitiendo su monitoreo remoto y en tiempo real, apoyando a nuestros usuarios en la toma de decisiones acertadas, optimizando los procesos operativos y maximizando la rentabilidad de sus negocios.

### 1.1.2. Perfiles de integrantes del equipo

| Miembros del equipo              | Código Estudiante | Carrera                | Conocimientos / Habilidades | Foto |
|----------------------------------|-------------------|------------------------|------------------------------|------|
| Escobar Palomino, Sebastian Matias | u202125968       | Ingeniería de Software | **Lenguajes:** Java, JavaScript<br>**Frameworks:** Spring Boot<br>**Bases de datos:** MySQL | <img src="https://i.imgur.com/tDWIiqt.png" width="80"> |
| Morales Montalvo, Omar Andrew    | u202212383       | Ingeniería de Software | **Lenguajes:** C#, JavaScript<br>**Frameworks:** .NET Core, Angular<br>**Gestión:** Jira, Trello | <img src="https://i.imgur.com/rV6QLMK.png" width="80"> |
| Gutierrez Tume, Stanley Jeremy   | u202118152       | Ingeniería de Software | **Lenguajes:** Java, Kotlin, Swift<br>**Mobile:** Android Studio, Xcode | <img src="https://i.imgur.com/wH0dfWs.png" width="80"> |
| Salgado Luna, Fernando Brian     | u202212023       | Ingeniería de Software | **Lenguajes:** Python, JavaScript<br>**Documentación:** Swagger | <img src="https://i.imgur.com/bNNGLG6.png" width="80"> |
| Antonio Loayza, Luiggi Jeremy    | u202011431       | Ingeniería de Software | **Lenguajes:** JavaScript<br>**Frameworks:** Node.js<br>**UI/UX:** Figma, Sketch | <img src="https://i.imgur.com/rPKbaMd.png" width="80"> |
| Arana Ramos, Jack                | u202124503       | Ingeniería de Software | **Lenguajes:** Java, TypeScript<br>**Frameworks:** Vue.js, Spring Boot<br>**DevOps:** Docker, Azure, CI/CD | <img src="https://lh3.googleusercontent.com/a/ACg8ocL39ewBX3TSajOL3ouvj0OuljxzjQBhNbXw3D0nZ5DQog6GfHw=s288-c-no" width="80"> |



## 1.2. Solution Profile
### 1.2.1. Antecedentes y problemática
#### Uso de la técnica The 5'W's w Y 2'H's

| LAS 5W y 2H | Pregunta                                                | Descripción                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| ----------- | ------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| What?        | ¿Cuál es el problema?                                     | Nos enfocamos en los retos asociados con la administración de hoteles, tales como dificultades en el control de ingresos, manejo de inventarios, organización del personal, gestión de habitaciones, elaboración de informes, distribución de tareas al equipo, entre otros. Estos problemas afectan las operaciones, la eficacia del hotel, la obtención de ingresos y la experiencia del cliente.                                                                                                          |
| When?       | ¿Cuándo sucede el problema?                                   |  El problema puede presentarse en cualquier instante, ya sea de forma cotidiana en la supervisión del equipo o el manejo de existencias, o de manera inesperada con carencias de recursos fundamentales como alimentos, agua o electricidad. |
| Where?       | ¿Dónde sucede el problema?                             | Las dificultades surgen en la administración de las actividades cotidianas, como el control de los ingresos, la gestión del inventario y la organización del equipo de trabajo.                                                                                                                                           |
| Why?      | ¿Por qué sucede el problema?                               | El problema se origina por una administración deficiente, lo que puede acarrear pérdidas económicas, falta de stock, desorganización en el trabajo del personal y, en consecuencia, una experiencia negativa para los clientes. Esto tiene un impacto directo en la imagen y los ingresos del establecimiento hotelero.                                                                                                                                                                                        |
| Who?        | ¿Quiénes son los afectados?                    |Los inconvenientes impactan a dueños, administradores de hoteles y al personal laboral en los centros de hospedaje.       |
| How?        | ¿Como se distingue el problema del estado ideal?            |   El estado ideal se define por una gestión hotelera eficiente, sin contratiempos y con una buena coordinación entre áreas. En cambio, el problema rompe con esa fluidez, generando interrupciones que afectan negativamente tanto la eficiencia operativa como la experiencia del cliente. La aparición de este problema puede deberse a patrones predecibles, como la ausencia de automatización, o presentarse de forma aleatoria por falta de planificación.                                                                                                                                                                   |
| How Much?   | ¿Con qué frecuencia o en qué cantidad se utilizará nuestro producto? | Sweet Manager será utilizado diariamente por el personal administrativo del hotel, especialmente por gerentes, supervisores y encargados de áreas como contabilidad, recepción y almacén. Su uso será constante, ya que centraliza funciones esenciales como el control de ingresos y egresos, la gestión de inventarios y proveedores, y la administración de reservas. Dado que las operaciones hoteleras son continuas, la aplicación será una herramienta de uso frecuente y sostenido durante toda la jornada laboral.                                                                                         |
### 1.2.2. Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements
La administración hotelera enfrenta retos operativos que impactan la rentabilidad y la calidad del servicio. Entre ellos destacan la gestión ineficiente de ingresos, inventarios, proveedores y personal, agravada por la falta de herramientas integradas. Esto genera pérdidas económicas, sobrecarga de trabajo y una experiencia deficiente para los huéspedes.

Gerentes y propietarios tienen dificultades para alcanzar sus metas debido al escaso control financiero, la mala administración de insumos y la complejidad de gestionar al personal. Estas fallas reducen la competitividad y eficiencia del hotel.

Por ello, se requiere una solución integral que centralice y simplifique la gestión financiera, operativa y de recursos humanos, mejorando la productividad y la experiencia tanto del equipo como de los huéspedes.



#### 1.2.2.2. Lean UX Assumptions


---

**Features**

Estas son las herramientas clave que integrará nuestra solución:

- **Seguimiento Financiero en Tiempo Real:** Permite registrar y analizar ingresos y gastos al instante para tener una visión clara de la situación económica del hotel.  
- **Gestión de Inventario y Proveedores:** Control preciso de suministros y pedidos, con comunicación eficiente con proveedores.  
- **Módulos de Recursos Humanos:** Gestión de horarios, nóminas y evaluaciones del personal para optimizar el área de RRHH.  
- **Interfaz Intuitiva y Personalizable:** Fácil de usar y adaptable a cada hotel para una experiencia personalizada.  
- **Integración con Sistemas Existentes:** Compatible con plataformas hoteleras actuales para una transición fluida y una gestión completa.

---

**Assumptions Worksheets**

1. **Necesidad del Cliente:** Soluciones tecnológicas que aumenten la eficiencia y rentabilidad.  
2. **Cómo lo resolvemos:** Con Sweet Manager, una plataforma integral y fácil de usar.  
3. **Clientes iniciales:** Propietarios y gerentes que buscan simplificar la gestión diaria.  
4. **Valor principal:** Simplificar la gestión y mejorar la experiencia del cliente.  
5. **Beneficios adicionales:**
   - Mejora operativa
   - Decisiones basadas en datos
   - Menor carga laboral
   - Mejor comunicación interna
   - Mayor transparencia
6. **Adquisición de clientes:** Marketing dirigido y alianzas con la industria hotelera.  
7. **Modelo de ingresos:** Suscripción, servicios premium e integraciones.  
8. **Competencia:** Otras soluciones de gestión hotelera.  
9. **Ventaja competitiva:** Facilidad de uso, servicio de calidad y personalización.  
10. **Mayor riesgo:** No cumplir expectativas en funcionalidad, rendimiento o soporte.  
11. **Mitigación del riesgo:** Enfoque centrado en el cliente, soporte constante y actualizaciones.  
12. **Otras suposiciones críticas:**
    - **Adopción tecnológica:** Si los usuarios se resisten, puede afectar el crecimiento.  
    - **Demanda del mercado:** Si disminuye, compromete la viabilidad.  
    - **Escalabilidad:** Si no escala bien, limita el mercado y requiere cambios técnicos o estratégicos.

---

**¿Quién es el usuario?**

- **Propietarios y Gerentes:** Responsables de decisiones estratégicas, buscan eficiencia y rentabilidad.  
- **Personal de Trabajo:** Contabilidad, compras y RRHH. Buscan herramientas que faciliten sus tareas diarias.

---

**¿Dónde encaja el producto?**

- **Gerentes/Propietarios:** Plataforma centralizada para gestionar todo el hotel y tomar decisiones informadas.  
- **Personal:** Herramientas especializadas para automatizar tareas y mejorar la productividad.

---

**¿Qué problema resuelve?**

- **Gerentes/Propietarios:** Dispersión de datos y herramientas. Centraliza la gestión en un solo lugar con datos en tiempo real.  
- **Personal:** Tareas manuales y complejas. Automatiza procesos para reducir carga laboral y estrés.

---

**¿Cómo y cuándo se usa?**

- **Gerentes/Propietarios:** A diario para tomar decisiones y supervisar la operación del hotel.  
- **Personal:** Durante la jornada laboral para gestionar tareas específicas de su área.

---

**Características clave**

**Gerentes/Propietarios:**  
- Datos en tiempo real  
- Interfaz personalizable  
- Gestión centralizada  
- Análisis y reportes

**Personal:**  
- Automatización de tareas  
- Integración con otros sistemas  
- Herramientas específicas  
- Comunicación eficiente

---

**¿Cómo debe verse y funcionar?**

**Gerentes/Propietarios:**  
- Interfaz limpia, personalizable y funcional. Acceso rápido a datos.

**Personal:**  
- Navegación sencilla, funcionamiento estable, procesos automatizados.

---

**Business Outcomes**

- **Referente del mercado:** Ser reconocidos como solución líder en gestión hotelera.  
- **Eficiencia operativa:** Reducir en un 30% el tiempo en tareas administrativas.  
- **Mejor rentabilidad:** Aumentar en 15% el margen neto en seis meses.  
- **Satisfacción del cliente:** Incremento de 0.5 puntos en reseñas.  
- **Fidelización:** Aumentar 20% las reservas repetidas en un año.  
- **Reducción de costos:** Disminución del 25% en gastos operativos.

---

**User Outcomes**

**¿Qué buscan los usuarios?**  
- **Gerentes/Propietarios:** Mejorar rentabilidad y eficiencia.  
- **Personal:** Simplificar sus responsabilidades con herramientas efectivas.

**¿Cómo se quieren sentir?**  
- **Gerentes/Propietarios:** En control y seguros con datos confiables.  
- **Personal:** Menos estresados, más eficientes.

**¿Cómo ayuda el producto?**  
- **Gerentes/Propietarios:** Plataforma integral con información en tiempo real.  
- **Personal:** Automatización de tareas que reduce la carga diaria.

**¿Qué beneficios obtienen?**  
- **Gerentes/Propietarios:** Gestión eficiente, operaciones fluidas.  
- **Personal:** Procesos simplificados, mejor comunicación y productividad.

**¿Qué cambios veremos si logramos el objetivo?**  
- **Gerentes/Propietarios:** Mayor uso de datos en decisiones y aumento de rentabilidad.  
- **Personal:** Tiempos más cortos de ejecución, menos estrés y mayor satisfacción.

#### 1.2.2.3. Lean UX Hypothesis Statements
 **Hipótesis**

- **Hipótesis 1:**  
  Creemos que una interfaz intuitiva y adaptable para gerentes y propietarios mejorará la eficiencia operativa.  
  Sabremos que esto es cierto si al menos el 80% de los usuarios reportan una experiencia positiva.

- **Hipótesis 2:**  
  Creemos que mostrar datos financieros en tiempo real ayudará a tomar decisiones más rápidas e informadas.  
  Sabremos que esto es cierto si el tiempo de decisión se reduce en un 30% y la precisión de los reportes mejora en un 15%.

- **Hipótesis 3:**  
  Creemos que mejorar la gestión de inventario disminuirá los costos operativos.  
  Sabremos que estamos bien si los costos bajan un 20% y el exceso de stock cae un 15% en seis meses.

- **Hipótesis 4:**  
  Creemos que un módulo eficiente de gestión de personal aumentará la productividad.  
  Sabremos que esto es cierto si la satisfacción del equipo sube un 25% y las evaluaciones mejoran en un 10%.

- **Hipótesis 5:**  
  Creemos que centralizar la plataforma reducirá cancelaciones.  
  Sabremos que esto es cierto si la retención de usuarios crece un 15% y las cancelaciones bajan un 10% en el primer año.

#### 1.2.2.4. Lean UX Canvas
<div style="text-align: center;">
  <img src="https://i.imgur.com/LiHSxX2.png" alt="Lean Ux Canva" width="100%" />
</div>

## 1.3. Segmentos objetivo

**Usuarios:**  
**Propietarios y Gerentes de Hoteles:**

- **Ubicación:** Principalmente en ciudades y destinos turísticos a nivel global.

- **Perfil:** Enfocados en la eficiencia, rentabilidad y control total de su negocio. Buscan herramientas para mejorar continuamente la experiencia del cliente y el éxito del hotel.

- **Demografía:** Adultos de 30 a 60 años, con formación empresarial o experiencia directa en hotelería. Pueden ser expertos en gestión o nuevos propietarios optimizando su operación.

**Personal de Trabajo**

- **Ubicación:** También en zonas urbanas y turísticas alrededor del mundo.

- **Perfil:** Comprometidos con la atención al cliente y adaptables a entornos dinámicos. Valoran la colaboración y comunicación efectiva dentro del equipo.

- **Demografía:** Adultos jóvenes a de mediana edad, con experiencia laboral diversa y educación desde nivel secundario hasta formación técnica en hospitalidad.


**Stakeholders (Externos e Internos )**

- **Equipo de Desarrollo de Producto:** Diseña y mejora la plataforma Sweet Manager, adaptándola a las necesidades de los usuarios.

- **Equipo de Marketing:** Desarrolla estrategias para captar a propietarios y gerentes de hoteles.

- **Soporte Técnico:** Ofrece asistencia constante para resolver problemas técnicos y asegurar la satisfacción del cliente.

- **Clientes Finales:** Propietarios, gerentes y personal de hoteles que utilizan directamente la plataforma.

- **Asociaciones de la Industria Hotelera:** Potenciales aliados estratégicos que pueden impulsar la visibilidad y adopción de Sweet Manager.

- **Proveedores de Sistemas Integrados:** Empresas con soluciones complementarias que se integran con la plataforma para ofrecer un sistema más completo.



# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores
El análisis competitivo es clave para tomar decisiones estratégicas, identificar oportunidades y amenazas, y generar ventajas sostenibles. Permite a las empresas adaptarse y actuar con información en un entorno cambiante. A continuación, se presenta su aplicación en el proyecto y el análisis de competidores.
### 2.1.1. Análisis competitivo

<table border="1" style="border-collapse: collapse; width: 100%;">
    <thead>
        <tr>
            <th colspan="7" style="text-align: center;">Competitive Analysis Landscape</th>
        </tr>
        <tr>
            <td colspan="2">¿Por qué llevar a cabo este análisis?</td>
            <td colspan="5">Porque de esta forma, es posible identificar a los posibles competidores en el mercado, analizar sus propuestas y detectar debilidades que podamos aprovechar para diferenciarnos y destacar frente a ellos.</td>
        </tr>
    </thead>
    <tbody>
        <tr style="text-align: center;">
            <td colspan="2">Empresas</td>
            <td><strong>SweetManager</strong><br></td>
            <td><strong>Sistema hotelero Xafiro</strong><div style="text-align: center;">
            <img src="https://i.imgur.com/4g6o3D5.jpeg"  width="70%" />
            </div>
            <td><strong>Samin PMS</strong><br><div style="text-align: center;">
            <img src="https://i.imgur.com/Sbq8QNG.png"  width="70%" />
            <td><strong>Binz360</strong><br><div style="text-align: center;">
            <img src="https://i.imgur.com/kis4Kz4.jpeg["  width="70%" />
            </div></td>
        </tr>
        <tr>
            <td rowspan="2" style="writing-mode: vertical-lr; text-align: center;">Perfil</td>
            <td>Overview</td>
            <td>Plataforma tecnológica peruana especializada en la gestión hotelera eficiente, orientada a facilitar las labores operativas y administrativas, además de modernizar los procedimientos mediante enfoques que mejoran la comodidad, seguridad y eficiencia energética de las instalaciones.</td>
            <td>Solución desarrollada en Perú que permite gestionar operaciones administrativas y funcionales de hoteles, operable desde cualquier dispositivo gracias a su enfoque multiplataforma. Agiliza tareas manuales repetitivas y ofrece facturación electrónica homologada por SUNAT.</td>
            <td>Plataforma nacional que brinda una solución integral para administrar hoteles, incorporando herramientas para reservas, facturación SUNAT, limpieza, entre otros, con el fin de optimizar procesos y elevar la experiencia del cliente.</td>
            <td>Software peruano orientado a la administración de hoteles que centraliza funciones como reservas, manejo de huéspedes, caja y almacén. Incorpora facturación electrónica y automatización de tareas con reportes interactivos mediante dashboards.</td>
            </tr>
            <tr>
            <td>¿Qué valor ofrece a los clientes?</td>
            <td>SweetManager integra un sistema hotelero fácil de usar, permitiendo gestionar trámites administrativos en tiempo real con una configuración adaptable y orientada al cliente.</td>
            <td>Xafiro digitaliza la operación hotelera desde la planificación hasta la facturación, ofreciendo acceso multiplataforma y una interfaz intuitiva para reservas. Se comercializa bajo un modelo de suscripción mensual.</td>
            <td>Samin PMS proporciona un sistema completo que abarca todo el ciclo operativo del hotel, incluyendo facturación, reservas, recepción, limpieza, caja y almacén, complementado con dashboards que permiten analizar el rendimiento.</td>
            <td>Binz360 propone una herramienta automatizada que reemplaza procesos manuales con un sistema integral para la gestión de áreas clave del hotel como caja, facturación y almacén, evitando el uso de Excel u otros métodos tradicionales.</td>
            </tr>
            <tr>
            <td rowspan="2" style="writing-mode: vertical-lr; text-align: center;">Perfil de Marketing</td>
            <td>Mercado objetivo</td>
            <td><strong>Demográfico</strong><br>Dirigido a hoteles medianos y grandes con más de 20 habitaciones, con personal administrativo de entre 30 y 55 años interesado en transformación digital.<br><strong>Geográfico</strong><br>Enfocado en Perú con miras a expandirse por Latinoamérica, comenzando en ciudades turísticas como Lima, Cusco, Arequipa y Trujillo.<br><strong>Psicológico</strong><br>Profesionales enfocados en eficiencia energética y sostenibilidad que buscan automatizar procesos.<br><strong>Comportamiento</strong><br>Empresas que utilizan soluciones básicas pero desean evolucionar a sistemas más avanzados e innovadores.</td>
            <td><strong>Demográfico</strong><br>Hoteles pequeños y medianos con hasta 50 habitaciones, dirigidos por empresarios jóvenes (25-45 años) en emprendimientos familiares.<br><strong>Geográfico</strong><br>Opera principalmente en Perú, especialmente en ciudades turísticas y rurales emergentes como Cusco, Iquitos y Trujillo.<br><strong>Psicológico</strong><br>Usuarios con mentalidad de expansión que aún dependen de métodos manuales.<br><strong>Comportamiento</strong><br>Propietarios que prefieren pagar mensualmente en lugar de realizar una inversión inicial alta.</td>
            <td><strong>Demográfico</strong><br>Diseñado para hoteles de cualquier tamaño, incluyendo cadenas hoteleras. Enfocado en gerentes y administradores con experiencia y equipos de más de 10 personas.<br><strong>Geográfico</strong><br>Presencia en todo Perú, con foco en zonas urbanas y turísticas. Planes de expansión hacia otros países de Latinoamérica.<br><strong>Psicológico</strong><br>Negocios con mentalidad analítica que buscan reportes para optimizar decisiones.<br><strong>Comportamiento</strong><br>Empresas que requieren herramientas robustas como facturación electrónica y automatización total.</td>
            <td><strong>Demográfico</strong><br>Dirigido a hoteles medianos con necesidad de modernización gradual. Gerentes entre 28 y 50 años interesados en digitalización.<br><strong>Geográfico</strong><br>Enfocado en regiones de Perú con menor adopción tecnológica y alto potencial turístico.<br><strong>Psicológico</strong><br>Dueños que buscan avanzar tecnológicamente sin modificar drásticamente sus métodos tradicionales.<br><strong>Comportamiento</strong><br>Usuarios que buscan soluciones simples para automatizar tareas sin cambiar todo su sistema operativo.</td>
            </tr>
            <tr>
            <td>Estrategias de marketing</td>
            <td>SweetManager presenta una propuesta diferenciada, permitiendo a los huéspedes personalizar su entorno desde una app. Se combina con funciones tradicionales como facturación, automatización y monitoreo, además de marketing digital en redes sociales. Incluye una página de preguntas frecuentes para atención personalizada y claridad informativa.</td>
            <td>Su estrategia se basa en un motor de reservas directo para aumentar ingresos sin comisiones. Destacan la integración con SUNAT y el ahorro significativo de tiempo en operaciones, beneficiando al equipo del hotel.</td>
            <td>Samin PMS agrega valor con herramientas como Housekeeping Smart y Restaurante Smart. Ofrece apoyo en marketing digital, publicidad y demostraciones gratuitas como medio para atraer y convencer a potenciales clientes.</td>
            <td>Binz360 ofrece una prueba gratuita de 14 días y planes desde S/7.50 por habitación. Su estrategia se centra en la automatización, reemplazando tareas manuales para optimizar la operación hotelera.</td>
            </tr>
        <tr>
            <td rowspan="3" style="writing-mode: vertical-lr; text-align: center;">Perfil de Producto</td>
            <td>Productos & Servicios</td>
            <td>
            SweetManager ofrece una plataforma integral de gestión hotelera la cual para permite a los huéspedes controlar su entorno y acceder a opciones de entretenimiento. Además, optimiza el consumo energético con sensores inteligentes y facilita la administración del hotel con herramientas como reservas, check-in/check-out, facturación electrónica y reportes en tiempo real.
            </td>
            <td>
            Xafiro es un software orientado a la digitalización completa de la gestión hotelera, con integración de facturación electrónica y un motor de reservas directo para mejorar los ingresos del hotel. Ofrece informes detallados sobre la ocupación y el rendimiento, permitiendo una visión en tiempo real de la operación del hotel.
            </td>
            <td>
            Samin PMS proporciona una solución de gestión hotelera integral que cubre reservas, check-in/check-out, tarifas y facturación electrónica. Incorpora módulos avanzados como Restaurante Smart y Housekeeping Smart, además de ofrecer reportes detallados para mejorar la toma de decisiones estratégicas.
            </td>
            <td>
            Binz360 es una plataforma centrada en la automatización de procesos operativos y administrativos de los hoteles. Incluye un panel de control centralizado, gestión de habitaciones, reportes financieros, administración de tarifas y facturación electrónica, con el objetivo de reducir la carga de trabajo manual y mejorar la eficiencia operativa.
            </td>
            </tr>
            <tr>
            <td>Precios & Costos</td>
            <td>
            SweetManager ofrece planes de suscripción mensual ajustados a las necesidades del hotel, con costos adicionales. Su modelo flexible permite adaptar los servicios a medida que el hotel crece.
            </td>
            <td>
            Xafiro tiene planes mensuales en función del número de habitaciones y las funcionalidades seleccionadas. Ofrece paquetes básicos y avanzados, con un costo adicional si se requiere la integración de la facturación electrónica.
            </td>
            <td>
            Samin PMS ofrece planes modulares que permiten elegir los servicios y funciones que mejor se adapten al hotel. El costo de la facturación electrónica y otros módulos adicionales varía según las necesidades específicas de cada cliente.
            </td>
            <td>
            Binz360 tiene una suscripción mensual basada en el número de habitaciones y los servicios contratados. Sus precios varían según el tamaño del hotel y las opciones de personalización requeridas, con soporte técnico adicional para personalizaciones.
            </td>
            </tr>
            <tr>
            <td>Canales de distribución (Web y/o Móvil)</td>
            <td>
            SweetManager está disponible tanto en versión web como móvil, permitiendo la gestión del hotel desde cualquier dispositivo conectado. 
            </td>
            <td>
            Xafiro es una plataforma accesible desde cualquier navegador web, con una versión responsiva que se adapta a dispositivos móviles, aunque no cuenta con una aplicación móvil dedicada para la gestión.
            </td>
            <td>
            Samin PMS ofrece una plataforma web que también tiene versiones adaptadas a dispositivos móviles. Algunos módulos específicos están disponibles como aplicaciones móviles para una gestión más especializada del hotel.
            </td>
            <td>
            Binz360 ofrece una plataforma web optimizada para diferentes dispositivos, con una versión móvil que permite gestionar algunas funciones básicas. Sin embargo, la experiencia completa está diseñada para el uso en escritorio.
            </td>
            </tr>
            <tr>
            <td rowspan="4" style="writing-mode: vertical-lr; text-align: center;">Análisis SWOT</td>
            <td>Fortalezas</td>
            <td>
            Integración de tecnología , entretenimiento y automatización de procesos.<br>
            Aplicación móvil intuitiva que permite gestionar el hotel desde cualquier lugar.<br>
            Facturación electrónica completamente integrada con SUNAT.<br>
            Enfoque sostenible y eficiente en el consumo energético.
            </td>
            <td>
            Plataforma estable con vasta experiencia en el mercado.<br>
            Compatibilidad con diversos dispositivos.<br>
            Integración fluida con sistemas contables y de reservas.
            </td>
            <td>
            Sistema de gestión hotelera completo con aplicaciones móviles para tareas específicas.<br>
            Automatización de procesos administrativos que facilita la operación del hotel.
            </td>
            <td>
            Enfoque en la digitalización de hoteles medianos y grandes.<br>
            Plataforma intuitiva con opciones de personalización.<br>
            Adaptabilidad a diferentes tipos de establecimientos hoteleros.
            </td>
            </tr>
            <tr>
            <td>Debilidades</td>
            <td>
            Ser una opción nueva en el mercado, con menor reconocimiento frente a competidores establecidos.<br>
            Dependencia de infraestructura tecnológica avanzada para su funcionamiento.
            </td>
            <td>
            Falta de una aplicación móvil robusta.<br>
            El sistema es menos flexible para empresas de menor tamaño.<br>
            Dependencia de integraciones externas para funciones avanzadas.
            </td>
            <td>
            Curva de aprendizaje moderada para nuevos usuarios.<br>
            Algunas funcionalidades requieren pagos adicionales.<br>
            No posee una estrategia de expansión clara fuera de Perú.
            </td>
            <td>
            Dependencia de la automatización sin una fuerte diferenciación tecnológica.<br>
            Poca personalización disponible para los usuarios.<br>
            </td>
            </tr>
            <tr>
            <td>Oportunidades</td>
            <td>
            Expansión en mercados latinoamericanos con una creciente demanda turística.<br>
            Alianzas estratégicas con cadenas hoteleras para implementaciones exclusivas.
            </td>
            <td>
            Mejorar la plataforma móvil para atraer a más usuarios.<br>
            Desarrollo de nuevos módulos para segmentos de hotelería de lujo.<br>
            Expansión a mercados con menos competencia digital.
            </td>
            <td>
            Desarrollo de nuevas integraciones con plataformas de pago y reservas online.<br>
            Crecimiento del turismo y de la digitalización en el sector hotelero.<br>
            Fortalecer la automatización para diferenciarse en el mercado.
            </td>
            <td>
            Fortalecer la experiencia móvil y en la nube.<br>
            Adopción de nuevas tecnologías que optimicen los procesos operativos.<br>
            Expansión en mercados de hoteles boutique y pequeñas cadenas.
            </td>
            </tr>
            <tr>
            <td>Amenazas</td>
            <td>
            Competencia con marcas consolidadas que ya dominan el mercado.<br>
            Posibles dificultades para la adopción de nuevas tecnologías por parte de hoteles tradicionales.<br>
            </td>
            <td>
            Avance de competidores con mejor integración móvil.<br>
            Posibles cambios regulatorios en la facturación electrónica que afecten la operación.<br>
            Aparición de soluciones más económicas y accesibles.
            </td>
            <td>
            Aparición de nuevas startups con tecnología más avanzada.<br>
            Resistencia de algunos hoteles a adaptarse a nuevas tendencias tecnológicas.<br>
            Posible saturación del mercado con soluciones similares.
            </td>
            <td>
            La llegada de nuevas soluciones con mayor escalabilidad.<br>
            Cambios en las preferencias de los hoteles por sistemas más flexibles.<br>
            Reducción de inversión tecnológica en hoteles más pequeños.
            </td>
            </tr>

</table>


### 2.1.2. Estrategias y tácticas frente a competidores
**Estrategias para afrontar las fortalezas de la competencia**

- **Enfoque en la experiencia del usuario:**  
A diferencia de los competidores centrados en lo administrativo, **Sweet Manager** priorizará una interfaz moderna, intuitiva y adaptable.

---

**Estrategias ante las debilidades de la competencia**

- **Planes escalables y flexibles:**  
Frente a los precios fijos poco accesibles, **Sweet Manager** ofrecerá suscripciones modulares ajustadas al tamaño y necesidades del hotel.

- **Compatibilidad multiplataforma:** 
Mientras otros tienen interfaces limitadas, **Sweet Manager** optimizará su app web y móvil para una experiencia fluida en cualquier dispositivo.

---

**Estrategias frente a las oportunidades de la competencia**

- **Alianzas con proveedores :**    
**Sweet Manager** se asociará con fabricantes de dispositivos inteligentes para reducir costos, mejorar la integración y asegurar compatibilidad.

- **Eficiencia energética:**   
La conexión del sistema  con el consumo eléctrico permitirá controlar y reducir gastos operativos.

---

**Estrategias frente a las amenazas**

- **Seguridad y privacidad:**   
Se aplicará cifrado avanzado y estándares de protección de datos para evitar vulnerabilidades y generar confianza.

- **Marketing estratégico:**    
Se impulsará la marca mediante publicidad digital y alianzas con influencers del sector hotelero, anticipándose a la competencia.


## 2.2. Entrevistas

Las entrevistas representan una herramienta clave para identificar las necesidades, deseos y problemas de los usuarios, además de permitir la validación de hipótesis y suposiciones del negocio. Mediante estas conversaciones, es posible recopilar información valiosa sobre las expectativas de los clientes, sus experiencias actuales y sus preferencias respecto a productos y servicios. En el contexto de Sweet Manager, entrevistar a propietarios, administradores y trabajadores será esencial para desarrollar una solución alineada con las demandas del mercado y que aporte un valor real a sus usuarios.

### 2.2.1. Diseño de entrevistas

En esta sección se documentarán las preguntas que se utilizaron en nuestras entrevistas, conteniendo las preguntas generales que se comparten entre los segmentos objetivos, y las preguntas que fueron creadas específicamente para cada una.

**Preguntas complementarias generales**

- ¿Qué navegador usas con más frecuencia?

- ¿Qué dispositivo tecnológico usas con más frecuencia?

- ¿Cómo describes tu personalidad?

- ¿Presentas alguna frustración en el trabajo?

- ¿Cuáles son los canales de interacción que usas?

- ¿Qué tipo de ambiente de trabajo te resulta más motivador y productivo?

- ¿Cómo se llama el distrito o lugar de tu residencia?

- ¿Qué objetivos tienes tanto laboralmente como personalmente?

**Preguntas Segmento 1: Gerentes**

- ¿Qué caracteristicas o funcionalidades consideraría más utiles para mejorar la eficiencia de su hotel?

- ¿Cómo gestiona actualmente las reservas de habitaciones y el seguimiento de ingresos y gastos en su hotel?

- ¿Qué aspectos valoran más al evaluar nuevas soluciones de software para su hotel?

- ¿Cómo crees que podríamos mejorar la comunicación y la colaboración del equipo?

- ¿Qué desafíos enfrentan al gestionar proveedores y controlar los inventarios en su hotel?

- ¿Cómo ve conveniente un sistema hotelero dedicado a la gestión de recursos, comunicación con proveedores, seguimiento de ganancias, etc?

**Preguntas Segmento 2: Administradores**

- ¿Qué herramientas o sistemas utilizan actualmente para realizar su trabajo y qué aspectos les resultan más difíciles o menos eficientes?

- ¿Qué características adicionales le gustaría ver en un sistema de gestión hotelera para facilitar su trabajo diario?

- ¿Cómo se sienten acerca de la adopción de nuevas tecnologías en el lugar de trabajo y cómo creen que podría mejorar su experiencia laboral?

- ¿Qué desafíos enfrenta al gestionar las solicitudes de los huéspedes y asegurarse de que se cumplan sus expectativas durante su estancia?

- ¿Cómo creen que podríamos simplificar los procesos de registro de huéspedes y check-in/check-out en su hotel?

- ¿Qué herramientas o recursos adicionales les ayudarán a ofrecer un mejor servicio a los huéspedes y mejorar su experiencia general en el hotel?

**Preguntas Segmento 3: Trabajadores**

- ¿Cuáles son las tareas o procesos diarios que considera más tediosos o que consumen más tiempo en su trabajo?

- ¿Qué herramientas o sistemas utilizan actualmente para realizar su trabajo y qué aspectos les resultan más difíciles o menos eficientes?

- ¿Cómo describiría la interacción y la comunicación entre los diferentes departamentos y miembros del personal del hotel?

- ¿Qué características adicionales le gustaría ver en un sistema de gestión hotelera para facilitar su trabajo diario?

- ¿Cómo se sienten acerca de la adopción de nuevas tecnologías en el lugar de trabajo y cómo creen que podría mejorar su experiencia laboral?

- ¿Qué desafíos enfrenta al gestionar las solicitudes de los huéspedes y asegurarse de que se cumplan sus expectativas durante su estancia?

### 2.2.2. Registro de entrevistas

A continuación, se registraron todas las entrevistas realizadas para nuestra solución, categorizadas según su segmento objetivo, y con un resumen que destaca las características y críticas realizadas sobre nuestro proyecto.

**Entrevista 01 (Gerentes)**
<br>
Nombre: Cesar Augusto Rodriguez <br>
Edad: 44 <br>
Sexo: Masculino <br>
Lugar donde vive:Surco - Lima, Perú <br>
Duración de la entrevista: 06:00 - 12:50 <br>
Ocupación: Owner de hotel <br>
Personalidad: Práctico y poco perfeccionista  <br>
URL VIDEO: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u202212383_upc_edu_pe/EQhyagVIyztBjx-XqvwF4OIB-jQ172VjzyCBXXasMZIIjg?e=ycIgsi&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D>

<div style="text-align: center;">
   <img src="https://imgur.com/J1LJUd1.png" alt="Manuel Chávez Interview"/>
</div><br>

Cesar Augusto es un owner de un hotel , reside en surco , se describe como una persona práctica y algo perfeccionista , les frustra que el personal no siga las indicaciones o las reglas del trabajo.
Suele usar su celular para responder a los terabajadores , le gusta un ambiente comprometido y que haya comunicación.

Le gustaría que el hotel funcione igual o mejor que cuando el no esté que no necesariamente esté presente para que las cosas funcionen , para que el personal siga las reglas , sean amables y educados.
El mayor reto que tiene es que no todas las solicitudes llegan a la persona correcta. A veces el cliente pide algo en recepción, pero no se lo comunican a limpieza o mantenimiento
Usa un sistema de gestión básico, más algunas hojas de Excel. El problema es que no todo está conectado. Por ejemplo, si alguien reserva en Booking, tenemos que actualizar manualmente en el sistema interno, y a veces eso causa sobreventas.



**Entrevista 02 (Gerentes)**
<br>
Nombre: Diego Bastidas<br>
Edad: 28<br>
Sexo: Masculino<br>
Lugar donde vive: San Miguel, Lima, Perú<br>
Ocupación: Gerente de hotel<br>
Duración de la entrevista: 00:00 - 06:00 <br>
Personalidad: Innovador<br>
Minuto de la entrevista: <br>
URL VIDEO: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u202212383_upc_edu_pe/EQhyagVIyztBjx-XqvwF4OIB-jQ172VjzyCBXXasMZIIjg?e=ycIgsi&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D> 

<div style="text-align: center;">
   <img src="https://i.imgur.com/4qIERTB.png" alt="Diego Bastidas Interview" width="80%" />
 </div><br>

Diego Bastidas dueño de un hotel que recibe tanto turistas locales como internacionales. Día a día enfrenta los retos de gestionar manualmente las reservas, pagos y preferencias de los huéspedes, lo que implica una alta carga operativa y riesgo de errores. Con una fuerte dedicación al servicio y buscando siempre mejorar la experiencia de sus clientes, está en busca de una solución tecnológica que optimice la administración del hotel. Su meta es centralizar la gestión de reservas, personalizar la atención a los huéspedes y modernizar los procesos internos, impulsando así la eficiencia y la competitividad del establecimiento.


**Entrevista 03 (Gerentes)**
<br>
Nombre: Sebastian Silva<br>
Edad: 23<br>
Sexo: Masculino<br>
Lugar donde vive: Cercado de Lima, Lima, Perú<br>
Ocupación: Dueño de hotel<br>
Personalidad: Proactivo y receptivo a nuevas tecnologías<br>
Duración de la entrevista: 28:23 - 37:00 <br>
URL VIDEO: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u202212383_upc_edu_pe/EQhyagVIyztBjx-XqvwF4OIB-jQ172VjzyCBXXasMZIIjg?e=ycIgsi&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D> 

<div style="text-align: center;">
   <img src="https://i.imgur.com/mmqqRu3.png" alt="Sebastian Silva Interview" width="80%" />
 </div><br>

Sebastian Silva dueño de un hotel y está acostumbrado a manejar personalmente las reservas, pagos y solicitudes de los huéspedes, lo que genera una alta carga de trabajo y posibles errores en la operación diaria. Comprometido con brindar un servicio de calidad y mejorar la experiencia de quienes se hospedan, busca una solución digital que le permita automatizar la gestión, registrar preferencias de los clientes y facilitar las tareas administrativas. Su objetivo es modernizar los procesos internos, optimizar el tiempo de trabajo y ofrecer una atención más personalizada y eficiente.

**Entrevista 01 (Administradores)**
<br>
Nombre: Sergio Renard <br>
Edad: 21 <br>
Sexo: Masculino <br>
Lugar donde vive: La Plata - Argentina <br>
Ocupación: Administrador de hotel <br>
Duración de la entrevista: 48:20 - 52:39 <br>
Personalidad: Alegre <br>
URL VIDEO: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u202212383_upc_edu_pe/EQhyagVIyztBjx-XqvwF4OIB-jQ172VjzyCBXXasMZIIjg?e=ycIgsi&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D>

<div style="text-align: center;">
   <img src="https://i.imgur.com/sKGvt61.png" alt="Sergio Renard Interview" width="80%" />
 </div><br>

Sergio Renard es un administrador hotelero que reside en La Plata, Argentina, y dirige un hospedaje familiar enfocado en el turismo tanto local como internacional. Comparte su experiencia enfrentando los desafíos diarios de la gestión hotelera, especialmente en lo referente al manejo de reservas y a las preferencias de los huéspedes. A diferencia de los grandes hoteles, actualmente no dispone de un sistema automatizado, por lo que realiza el control de reservas, pagos y asignaciones de manera manual, lo que representa una alta carga operativa y un margen considerable para errores humanos.

Sergio se describe como una persona práctica, dedicada y muy atenta a las necesidades de sus clientes. Por eso, está en busca de una solución tecnológica que le permita modernizar su modelo de gestión. Su meta principal es ofrecer mayor comodidad a los huéspedes mediante una plataforma digital que les permita registrar sus preferencias de estadía, lo cual facilitaría brindar una experiencia más personalizada en futuras visitas.

Además, considera esencial que esta herramienta no solo optimice el proceso de reservas, sino que también incorpore funcionalidades administrativas, seguimiento de recursos y comunicación interna, todo dentro de un mismo sistema. Sergio está convencido de que una gestión digital eficiente no solo mejora el trabajo del administrador, sino que también eleva la calidad del servicio al cliente y refuerza la competitividad del establecimiento.


**Entrevista 02 (Administradores)**
<br>
Nombre: Manuel Chávez <br>
Edad: 23 <br>
Sexo: Masculino <br>
Lugar donde vive: San Borja - Lima, Perú <br>
Ocupación: Administrador de hotel <br>
Duración de la entrevista: 20:36 - 28:23 <br>
Personalidad: Práctico, organizado y resolutivo <br>
URL VIDEO: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u202212383_upc_edu_pe/EQhyagVIyztBjx-XqvwF4OIB-jQ172VjzyCBXXasMZIIjg?e=ycIgsi&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D>

<div style="text-align: center;">
   <img src="https://i.imgur.com/L3xAeOf.png" alt="Manuel Chávez Interview"/>
</div><br>

Manuel Chávez es un administrador hotelero con base en San Borja, Lima, que gestiona un hotel urbano de nivel medio. Actualmente, su trabajo se ve afectado por la falta de integración entre herramientas como hojas de cálculo, software contable básico y un sistema de reservas obsoleto. Esto provoca duplicación de tareas, pérdida de tiempo y problemas de coordinación interna.

Se describe como una persona práctica, organizada y enfocada en la resolución de problemas. Aunque enfrenta frustraciones relacionadas con la falta de alineación entre herramientas y fallos de comunicación interna, mantiene una actitud proactiva hacia la adopción tecnológica, siempre que esta venga acompañada de capacitación adecuada.

Manuel busca una plataforma de gestión hotelera "todo en uno" que incluya una interfaz moderna, automatización de reportes, coordinación de tareas, y acceso móvil para facilitar su trabajo en diferentes áreas del hotel. También considera vital la existencia de una app interna que notifique en tiempo real sobre solicitudes, cambios y llegadas, así como herramientas para evaluar el rendimiento del personal y recopilar opiniones de los huéspedes a través de encuestas rápidas.

Está convencido de que una transformación digital efectiva puede mejorar significativamente la experiencia del cliente y hacer que la gestión hotelera sea más eficiente, profesional y competitiva.

**Entrevista 03 (Administradores)**
<br>
Nombre: CAMILA BUSTAMANTE <br>
Edad: 25 <br>
Sexo: FEMENINO <br>
Lugar donde vive: Miraflores - Perú <br>
Ocupación: Administradora de hotel <br>
Duración de la entrevista: 37:00 - 43:04 <br>
Personalidad: Proactiva <br>
URL VIDEO: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u202212383_upc_edu_pe/EQhyagVIyztBjx-XqvwF4OIB-jQ172VjzyCBXXasMZIIjg?e=ycIgsi&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D>

<div style="text-align: center;">
   <img src="https://imgur.com/8y2Uu33.png" alt="Camila Bustamante Interview" width="80%" />
 </div><br>

Camila Bustamante es una administrado de un hotel , reside en Miraflores. En esta entrevista comparte algunos detalles de su trabajo como administradora, se describe como una persona proactiva y empática , suele usar 
su laptop mayormente usando el navegador de chrome.Laboralmente quiere seguir creciendo y mejorar el funcionamiento del hotel.Le motiva trabajar con personas comprometidas y tambien el trabajo en equipo.Se frustra cuando el sistema se cae ya que generan muchos problemas y perdida de tiempo.

 Usan un sistema para reservas , factuarición y check-in, le gustaría un interfaz mas agradable y una app que permita gestionar puntos claves. Piensa que las tecnologías bien implementadas reducen el tiempo y errores.
El principal reto es la coordinación rápida entre el hotel y los huéspedes. Implementando check-in online reduciría el tiempo de espera haciendo colas.

**Entrevista 01 (Trabajadores)**
<br>
Nombre: Joseph Cubas <br>
Edad: 21 <br>
Sexo: Masculino <br>
Lugar donde vive: Pueblo Libre, Lima, Perú <br>
Ocupación: Trabajador del sector hotelero <br>
Duración de la entrevista: 43:05 - 48:20 <br>
Personalidad: Comprometido y receptivo al cambio <br>
URL VIDEO: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u202212383_upc_edu_pe/EQhyagVIyztBjx-XqvwF4OIB-jQ172VjzyCBXXasMZIIjg?e=ycIgsi&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D>

<div style="text-align: center;">
   <img src="https://i.imgur.com/Km9qFjd.png" alt="Joseph Cubas Interview"/>
</div><br>

Joseph Cubas forma parte del personal operativo de un hotel, desempeñando un rol clave en la atención diaria de las necesidades tanto del establecimiento como de los huéspedes. Durante la entrevista, compartió con franqueza los principales desafíos que enfrenta en su trabajo, entre ellos la falta de coordinación entre áreas, la dependencia de herramientas informales como radios y WhatsApp, y el uso persistente del papel para registrar tareas y reportes.

Para Joseph, estos métodos generan demoras, confusiones y duplicación de esfuerzos. Destaca que una de sus mayores frustraciones es enterarse tarde de las solicitudes de los huéspedes o no saber si una tarea ya fue realizada por otro compañero. A pesar de las limitaciones actuales, valora la buena disposición del equipo, aunque reconoce que la ausencia de un sistema centralizado de información afecta negativamente la eficiencia.

Joseph imagina un sistema ideal donde las tareas se asignen en tiempo real, puedan actualizarse fácilmente, incluyan evidencia fotográfica y estén visibles para todo el personal. A su juicio, esto permitiría mayor control, mejor comunicación interdepartamental y una experiencia más satisfactoria tanto para el huésped como para el trabajador.

Finalmente, se muestra abierto al uso de nuevas tecnologías, siempre que vengan acompañadas de una adecuada capacitación. Considera que la digitalización no solo mejoraría el flujo de trabajo, sino que también elevaría la calidad del servicio ofrecido, beneficiando a todos los actores del entorno hotelero.

**Entrevista 02 (Trabajadores)**
<br>
Nombre: Marcela <br>
Edad: 26 <br>
Sexo: Femenino <br>
Lugar donde vive: Jesús María, Lima, Perú <br>
Ocupación: Jefa de cocina en hotel <br>
Duración de la entrevista: 17:26 - 20:36 <br>
Personalidad: Dinámica y enfocada en la organización <br> 
Minuto de la entrevista: <br>
URL VIDEO: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u202212383_upc_edu_pe/EQhyagVIyztBjx-XqvwF4OIB-jQ172VjzyCBXXasMZIIjg?e=ycIgsi&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D>


<div style="text-align: center;">
   <img src="https://i.imgur.com/yQoqea1.png" alt="Joseph Cubas Interview"/>
</div><br>

Marcela lidera el área de cocina en un hotel ubicado en Jesús María, desempeñándose como jefa de cocina y supervisando tanto al personal fijo como a los practicantes en formación. Durante la entrevista, resaltó que una de las actividades más demandantes en su día a día es la capacitación de los nuevos practicantes, ya que su falta de experiencia genera confusión y requiere un acompañamiento constante.

Actualmente, utiliza una ticketera  para gestionar los pedidos de los huéspedes. Sin embargo, Marcela señaló que durante las horas pico, como a las seis o siete de la tarde, el volumen de pedidos puede resultar abrumador, sobre todo para los practicantes, lo que ralentiza la operación.

Respecto a la comunicación interna, mencionó que existe un flujo dinámico y constante de información entre las áreas, aunque reconoció que en ocasiones la organización de los comunicados podría mejorar para evitar confusiones. A Marcela le gustaría un sistema más robusto que incluya un chat interno para todos los colaboradores y un módulo de control de inventario para su área, cree que esto mejoraría la comunicación y le permitiría una gestión más eficiente de los insumos.

Finalmente, indicó que uno de los principales desafíos es atender adecuadamente los pedidos especiales de los huéspedes, como aquellos relacionados con alergias alimentarias ya que requieren una comunicación precisa a todo el equipo para evitar errores que comprometan la seguridad de los clientes.

**Entrevista 03 (Trabajadores)**
<br>
Nombre: Jesús Pérez
Edad: 23 <br>
Sexo: Masculino <br>
Lugar donde vive: Cercado de Lima, Lima, Perú <br>
Ocupación: Recepcionista de hotel <br>
Duración de la entrevista: 12:50 - 17:26 <br>
Personalidad: Proactivo y receptivo a nuevas tecnologías <br>
Minuto de la entrevista:<br> 
URL VIDEO: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u202212383_upc_edu_pe/EQhyagVIyztBjx-XqvwF4OIB-jQ172VjzyCBXXasMZIIjg?e=ycIgsi&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D> 

<div style="text-align: center;">
   <img src="https://i.imgur.com/hecaQOP.png" alt="Joseph Cubas Interview"/>
</div><br>

Jesús Pérez es recepcionista en un hotel de Cercado de Lima. Identifica como tareas más tediosas la actualización manual del inventario de habitaciones y la coordinación con limpieza, especialmente en eventos grandes.

Aunque utilizan un sistema de gestión hotelera, Jesús señala que es poco eficiente para cambios rápidos de reserva y generación de reportes. La comunicación interna es dinámica, pero presenta fallas de coordinación entre recepción, limpieza y alimentos.

Sugiere incorporar una gestión de inventario en tiempo real con alertas automáticas para optimizar el flujo de trabajo. Se muestra a favor de la implementación de tecnologías como la inteligencia artificial para automatizar areas repetitivas. Entre sus principales desafíos destaca gestionar las solicitudes urgentes de huéspedes en situaciones de alta ocupación.

### 2.2.3. Análisis de entrevistas

<div style="text-align: center;">
   <img src="https://i.imgur.com/tNa6xYM.png" alt=""/>
</div><br>
<div style="text-align: center;">
   <img src="https://i.imgur.com/0bEaJdt.png" alt=""/>
</div><br>
<div style="text-align: center;">
   <img src="https://i.imgur.com/Gjv7vD8.png" alt=""/>
</div><br>
<div style="text-align: center;">
   <img src="https://i.imgur.com/ObXTOpk.png" alt=""/>
</div><br>

# Hallazgos Clave de las Entrevistas

## Necesidades de los Trabajadores del Hotel
- **Factores valorados**: Ubicación, precio, comodidades y servicios del hotel.
- **Comparación y filtrado**: Desean poder comparar opciones fácilmente y filtrar según sus necesidades.
- **Tecnología utilizada**: Todos usan Google como principal buscador y dispositivos móviles (celular y laptop).
- **Recepción a la aplicación**: Muy receptivos ante la idea de una aplicación para:
  - Registrar reservas.
  - Cancelar reservas.
  - Administrar preferencias.
  - Comunicarse con el personal del hotel.

## Necesidades del Staff del Hotel
- **Herramientas actuales**: 
  - Uso de herramientas manuales como Excel.
  - Software limitado que no cubre toda la operación.
- **Objetivos del staff**: Buscan soluciones que:
  - Reduzcan la carga operativa.
  - Eviten errores humanos.
  - Permitan una gestión integral de:
    - Reservas.
    - Housekeeping.
    - Inventario.
    - Comunicación interna.
    - Reportes.

## Conclusión
Los tres segmentos objetivo coinciden en la necesidad de una **plataforma centralizada, intuitiva y automatizada** que:
- Mejore la gestión hotelera.
- Mejore la experiencia del trabajador.

**Staff del hotel**:  
La comunicación interna y la gestión de recursos son aspectos clave para el éxito de la operación hotelera.

**Trabajadores**:  
Buscan una experiencia personalizada y fluida al interactuar con el hotel, desde la reserva hasta el check-out.

## 2.3. Needfinding
Para comprender mejor cómo será la experiencia del usuario con nuestro producto, emplearemos herramientas como User Persona, User Task Matrix, User Journey Mapping, Empathy Mapping y As-is Scenario Mapping. 
### 2.3.1. User Personas

**User Persona Owner**

<div style="text-align: center;">
  <img src="https://i.imgur.com/PiF2qgU.png"  width="100%" />
</div>

**User Persona Admin**

<div style="text-align: center;">
  <img src="https://i.imgur.com/zfG6bqy.png"  width="100%" />
</div>

**User Persona Worker**

<div style="text-align: center;">
  <img src="https://i.imgur.com/zumaQ9w.png" width="100%" />
</div>

### 2.3.2. User Task Matrix
**Descripción**

Esta sección introduce la User Task Matrix, una herramienta esencial para identificar las tareas más importantes y frecuentes que realizan los User Personas en su ambiente laboral. Esta matriz permite observar y comparar las actividades de los huéspedes, administradores y dueños, destacando tanto sus diferencias como sus similitudes respecto a la frecuencia y la importancia de dichas tareas.

El análisis obtenido facilita una comprensión más profunda de las necesidades y desafíos de cada tipo de usuario, lo que permite enfocar el diseño del producto en aquellas funciones que realmente impactan en su trabajo diario.

---

**Tabla de Actividades por Usuario**

| **Tarea** | **Trabajador (Frecuencia/Importancia)** | **Administrador (Frecuencia/Importancia)** | **Dueño (Frecuencia/Importancia)** |
|----------|----------------------------------------|---------------------------------------------|--------------------------------------|
| Reserva de habitaciones | Alta/Alta | Baja/Baja | Baja/Baja |
| Gestión de reservas | Alta/Alta | Alta/Alta | Media/Media |
| Solicitud de servicio a las habitaciones | Alta/Alta | Baja/Baja | Baja/Baja |
| Programación de limpieza de habitaciones | Baja/Baja | Alta/Alta | Baja/Media |
| Registro de preferencias de temperatura e iluminación | Alta/Alta | Baja/Baja | Baja/Baja |
| Negociación con proveedores | Baja/Baja | Media/Media | Alta/Alta |
| Gestión de las habitaciones | Baja/Baja | Alta/Alta | Alta/Alta |
| Gestión de las finanzas | Baja/Baja | Media/Media | Alta/Alta |
| Administración de recursos | Baja/Baja | Alta/Alta | Alta/Alta |
| Comunicación y organización constante | Baja/Baja | Alta/Alta | Alta/Alta |
| Solicitud de abastecimiento | Baja/Baja | Media/Alta | Alta/Alta |
| Control de entradas y salidas | Baja/Baja | Alta/Alta | Media/Alta |


### 2.3.3. User Journey Mapping

En esta sección se presentarán los User Journey Mapping para cada user persona, detallando las etapas clave de interacción con RoomWise, sus puntos de contacto, y las experiencias y emociones asociadas en cada paso. El objetivo es identificar oportunidades de mejora y optimizar la experiencia del usuario. A continuación se describen los User Journey Maps para cada perfil de usuario:

 ADMINISTRADOR:

<div style="text-align: center;">
  <img src="https://imgur.com/e39q0mz.png" width="100%" />
</div>

TRABAJADOR:

<div style="text-align: center;">
  <img src="https://imgur.com/Fsa9KUm.png" width="100%" />
</div>

GERENTE:

<div style="text-align: center;">
  <img src="https://imgur.com/YNTuzXu.png" width="100%" />
</div>




### 2.3.4. Empathy Mapping

Administrador:

<div style="text-align: center;">
  <img src="https://imgur.com/dZbf6ah.png" width="100%" />
</div>

Gerente:

<div style="text-align: center;">
  <img src="https://imgur.com/6BpZa1F.png" width="100%" />
</div>

Trabajador:

<div style="text-align: center;">
  <img src="https://imgur.com/XEIK6Tv.png" width="100%" />
</div>

### 2.3.5. As-is Scenario Mapping
Esta sección expone los mapeos de escenarios para los segmentos objetivo: Huésped, Administrador y Dueño, los cuales ilustran cómo son actualmente sus experiencias y rutinas diarias como usuarios potenciales.

**As-is Scenario Mapping Trabajador:**
<div style="text-align: center;">
  <img src="https://i.imgur.com/IWYO0Cp.png" width="100%" />
</div>

**As-is Scenario Mapping Administrador:**
<div style="text-align: center;">
  <img src="https://i.imgur.com/dmDgckf.png" width="100%" />
</div>

**As-is Scenario Mapping Dueño:**
<div style="text-align: center;">
  <img src="https://i.imgur.com/PQLe7XV.png" width="100%" />
</div>

**A continuación, se comparte el enlace de LucidChart donde fueron elaborados: https://lucid.app/lucidspark/06682147-9f10-470a-8e7c-5a780fb41668/edit?viewport_loc=8240%2C-1378%2C2989%2C1484%2C0_0&invitationId=inv_8659ae05-40f9-4205-88ad-a899659127c8**

## 2.4. Ubiquitous Language
Esta sección presenta un glosario de términos y conceptos clave, con el fin de mantener una comunicación clara y uniforme entre el equipo de trabajo y los stakeholders. Esta práctica sigue el enfoque propuesto por Eric Evans en su libro Domain-Driven Design: Tackling Complexity in the Heart of Software.

| Término (Inglés)         | Término (Español)             | Definición                                                                 |
|--------------------------|-------------------------------|---------------------------------------------------------------------------|
| **Check-In**             | (Registro de entrada)         | Procedimiento mediante el cual el huésped se registra al llegar y recibe su habitación. |
| **Check-Out**            | (Salida del huésped)          | Proceso en el que el huésped concluye su estadía, liquida su cuenta y entrega la llave o tarjeta. |
| **Reservation**          | (Reserva)                     | Acción de apartar una habitación para fechas específicas.                |
| **Reservation Status**   | (Estado de la reserva)        | Estado actual de una reserva: confirmada, pendiente, cancelada o completada. |
| **Reservation Type**     | (Tipo de reserva)             | Clasificación de la reserva según su origen o condiciones, como directa, en línea, grupal o por agencia. |
| **Availability**         | (Disponibilidad)              | Número de habitaciones disponibles para reservar en un periodo específico. |
| **No-show**              | (No presentación)             | Situación en la que un huésped con reserva confirmada no se presenta en el hotel. |
| **House Rules**          | (Reglamento del hotel)        | Conjunto de normas internas que deben seguir los huéspedes durante su estadía. |
| **Housekeeping**         | (Limpieza)                    | Departamento encargado del aseo, mantenimiento y organización diaria de las habitaciones. |
| **Inventory Management** | (Gestión de inventario)       | Supervisión de los productos y materiales necesarios para el funcionamiento del hotel. |


# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

En esta sección se presentan los diagramas de los escenarios futuros (To-Be Scenario Mapping) para los perfiles de gerentes y empleados, los cuales detallan las interacciones y tareas que los usuarios llevarán a cabo con el sistema de gestión hotelera una vez implementado. Estos diagramas proporcionan una visión general de las funciones y características esperadas del producto final, sirviendo como guía para su diseño y desarrollo.

SEGMENTO TRABAJADOR:

<div style="text-align: center;">
  <img src="https://i.imgur.com/wThvLlw.png" alt="to be scenario maping trabajador" width="70%" />
</div>

SEGMENTO ADMINISTRADOR:

<div style="text-align: center;">
  <img src="https://imgur.com/KaOigqr.png" alt="to be scenario maping administrador" width="70%" />
</div>

SEGMENTO GERENTE:

<div style="text-align: center;">
  <img src="https://imgur.com/XPxZMX7.png" alt="to be scenario maping gerente" width="70%" />
</div>


## 3.2. User Stories

| EPIC ID | TÍTULO                        | Descripción                                                                 |
|---------|-------------------------------|-----------------------------------------------------------------------------|
| EP01    | Información del Producto       | Como visitante, quiero ver información clara del producto, para comprender sus beneficios. |
| EP02    | Gestión de Usuarios y Autenticación | Como usuario del sistema, deseo gestionar cuentas y acceder de manera segura a Sweet Manager. |
| EP03    | Gestión Operativa del Hotel    | Como administrador, deseo gestionar habitaciones, trabajadores, proveedores e inventario para optimizar la operación hotelera. |
| EP04    | Gestión de Reservas y Comunicación | Como administrador, deseo gestionar reservas y notificaciones para mantener una comunicación eficiente. |
| EP05    | Análisis y Reportes            | Como gerente, deseo visualizar dashboards, reportes y analíticos para tomar decisiones informadas. |

| US ID | TÍTULO | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
|-------|--------|-------------|--------------------------|--------------------------|
| US01 | Acceder a información de la empresa | Como visitante del sitio web, deseo conocer más acerca de la empresa responsable del producto. | DADO QUE el visitante navega en la sección "Nosotros", CUANDO revisa la información relevante sobre la compañía, ENTONCES se genera un mayor interés por el producto Y opta por registrarse como usuario. | EP01 |
| US02 | Conocer los beneficios del producto | Como visitante del sitio web, deseo conocer las ventajas que ofrece el producto. | DADO QUE el visitante está en la sección de beneficios, CUANDO revisa las ventajas asociadas al uso de nuestra solución, ENTONCES aumenta su interés por el producto Y decide registrarse como usuario. | EP01 |
| US03 | Consultar planes de precios | Como visitante del sitio web, deseo conocer las distintas opciones de precios disponibles para el producto. | DADO QUE el visitante se encuentra en la sección de planes de precios, CUANDO examina las diferentes alternativas ofrecidas, ENTONCES puede comprender mejor las opciones disponibles Y optar por registrarse como usuario. | EP01 |
| US04 | Establecer contacto con la empresa | Como visitante del sitio web, deseo poder comunicarme fácilmente con la empresa. | DADO QUE el visitante se encuentra en la página principal, CUANDO busca una opción de contacto accesible, ENTONCES puede establecer comunicación de forma rápida Y sencilla con la empresa. | EP01 |
| US05 | Iniciar sesión en el sistema | Como usuario, quiero poder acceder a Sweet Manager utilizando mi cuenta personal. | DADO QUE el usuario se encuentra en la pantalla de inicio de sesión, CUANDO introduce sus credenciales correctamente, ENTONCES puede iniciar sesión de manera exitosa Y será dirigido a su dashboard. | EP02 |
| US06 | Registro de cuenta | Como gerente, deseo crear mi cuenta para poder administrar el hotel. | DADO QUE el usuario completa el formulario de registro, CUANDO ingresa los datos del hotel y su información personal, ENTONCES se crea la cuenta correctamente Y accede al panel principal. | EP02 |
| US07 | Gestión de perfil de usuario | Como usuario, deseo actualizar mi información personal en el sistema. | DADO QUE el usuario accede a su perfil, CUANDO modifica sus datos personales Y guarda los cambios, ENTONCES la información se actualiza correctamente. | EP02 |
| US08 | Gestión de trabajadores | Como administrador, deseo agregar y visualizar trabajadores del hotel. | DADO QUE el usuario tiene permisos administrativos, CUANDO accede a la sección de trabajadores, ENTONCES puede agregar nuevos trabajadores Y visualizar la lista completa del personal. | EP03 |
| US09 | Gestión de habitaciones | Como administrador, deseo agregar habitaciones y tipos de habitaciones. | DADO QUE el usuario gestiona habitaciones, CUANDO crea nuevas habitaciones o tipos, ENTONCES se registran correctamente Y aparecen en la lista de habitaciones. | EP03 |
| US10 | Gestión de proveedores | Como administrador, deseo agregar y visualizar proveedores del hotel. | DADO QUE el usuario gestiona proveedores, CUANDO agrega un nuevo proveedor, ENTONCES se registra correctamente Y aparece en la lista de proveedores. | EP03 |
| US11 | Gestión de inventario | Como administrador, deseo agregar suministros y crear solicitudes de inventario. | DADO QUE el usuario gestiona inventario, CUANDO agrega suministros o crea solicitudes, ENTONCES se registran correctamente en el sistema de inventario. | EP03 |
| US12 | Gestión de administradores | Como gerente, deseo agregar y visualizar administradores del hotel. | DADO QUE el usuario tiene permisos de gerente, CUANDO accede a la sección de administradores, ENTONCES puede agregar nuevos administradores Y visualizar la lista completa. | EP03 |
| US13 | Gestión de información del hotel | Como gerente, deseo crear y visualizar la información del hotel. | DADO QUE el usuario registra información del hotel, CUANDO completa los datos, ENTONCES la información se guarda correctamente Y puede ser consultada posteriormente. | EP03 |
| US14 | Gestión de reservas | Como administrador, deseo crear reservas y visualizar la tabla de reservas. | DADO QUE el usuario gestiona reservas, CUANDO crea una nueva reserva, ENTONCES se registra correctamente Y aparece en la tabla de reservas. | EP04 |
| US15 | Sistema de notificaciones | Como administrador, deseo crear alertas y enviar mensajes a los usuarios. | DADO QUE el usuario gestiona notificaciones, CUANDO crea alertas o mensajes, ENTONCES se envían correctamente Y los usuarios pueden visualizar sus notificaciones. | EP04 |
| US16 | Visualizar notificaciones | Como usuario, deseo ver todas las notificaciones que he recibido. | DADO QUE el usuario accede a la sección de notificaciones, CUANDO la página se carga, ENTONCES se muestra una lista de todas las notificaciones recibidas. | EP04 |
| US17 | Dashboard personalizado | Como usuario, deseo visualizar un dashboard con resumen del sistema según mi rol. | DADO QUE el usuario accede al dashboard, CUANDO la página se carga, ENTONCES se muestra un resumen personalizado con estadísticas relevantes para su rol (admin, worker). | EP05 |
| US18 | Reportes estadísticos | Como administrador, deseo visualizar reportes estadísticos y analíticos del hotel. | DADO QUE el usuario accede a reportes, CUANDO selecciona el tipo de reporte, ENTONCES se generan gráficos y estadísticas detalladas del rendimiento del hotel. | EP05 |


## 3.3. Product Backlog

| #ORDEN | USER STORY ID | TÍTULO                                  | DESCRIPCIÓN | STORY POINTS(1/2/3/5/8/13) |
|--------|--------------|----------------------------------------|-------------|---------------------------|
| 1      | US01 - EP01  | Acceder a información de la empresa | Como visitante del sitio web, deseo conocer más acerca de la empresa responsable del producto. | 3 |
| 2      | US02 - EP01  | Conocer los beneficios del producto | Como visitante del sitio web, deseo conocer las ventajas que ofrece el producto. | 3 |
| 3      | US03 - EP01  | Consultar planes de precios | Como visitante del sitio web, deseo conocer las distintas opciones de precios disponibles para el producto. | 3 |
| 4      | US04 - EP01  | Establecer contacto con la empresa | Como visitante del sitio web, deseo poder comunicarme fácilmente con la empresa. | 2 |
| 5      | US05 - EP02  | Iniciar sesión en el sistema | Como usuario, quiero poder acceder a Sweet Manager utilizando mi cuenta personal. | 3 |
| 6      | US06 - EP02  | Registro de cuenta | Como gerente, deseo crear mi cuenta para poder administrar el hotel. | 5 |
| 7      | US07 - EP02  | Gestión de perfil de usuario | Como usuario, deseo actualizar mi información personal en el sistema. | 3 |
| 8      | US08 - EP03  | Gestión de trabajadores | Como administrador, deseo agregar y visualizar trabajadores del hotel. | 5 |
| 9      | US09 - EP03  | Gestión de habitaciones | Como administrador, deseo agregar habitaciones y tipos de habitaciones. | 5 |
| 10     | US10 - EP03  | Gestión de proveedores | Como administrador, deseo agregar y visualizar proveedores del hotel. | 5 |
| 11     | US11 - EP03  | Gestión de inventario | Como administrador, deseo agregar suministros y crear solicitudes de inventario. | 5 |
| 12     | US12 - EP03  | Gestión de administradores | Como gerente, deseo agregar y visualizar administradores del hotel. | 5 |
| 13     | US13 - EP03  | Gestión de información del hotel | Como gerente, deseo crear y visualizar la información del hotel. | 3 |
| 14     | US14 - EP04  | Gestión de reservas | Como administrador, deseo crear reservas y visualizar la tabla de reservas. | 8 |
| 15     | US15 - EP04  | Sistema de notificaciones | Como administrador, deseo crear alertas y enviar mensajes a los usuarios. | 5 |
| 16     | US16 - EP04  | Visualizar notificaciones | Como usuario, deseo ver todas las notificaciones que he recibido. | 3 |
| 17     | US17 - EP05  | Dashboard personalizado | Como usuario, deseo visualizar un dashboard con resumen del sistema según mi rol. | 8 |
| 18     | US18 - EP05  | Reportes estadísticos | Como administrador, deseo visualizar reportes estadísticos y analíticos del hotel. | 8 |



## 3.4. Impact Mapping

En esta sección se describen y muestran los Impact Mappings, los cuales fueron desarrollados a partir de los User Personas. Estos mapas incluyen los objetivos de negocio de cada uno y permiten identificar las funcionalidades necesarias para generar los entregables definidos.

<div style="text-align: center;">
  <img src="https://imgur.com/2lY2qvQ.png" alt="impact map gerente" width="70%" />
</div>

<div style="text-align: center;">
  <img src="https://imgur.com/OTJCXhk.png" alt="impact map administrador" width="70%" />
</div>

<div style="text-align: center;">
  <img src="https://imgur.com/uHk2kQo.png" alt="impact map empleado" width="70%" />
</div>

# Capítulo IV: Product Design

## 4.1. Style Guidelines
# Capítulo IV: Product Design

## 4.1. Style Guidelines

| Aspecto             | Directrices                                                                                                                                                                                                 |
|---------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Nombre de la aplicación | Sweet Manager                                                                                                                                                                                              |
| Identidad Visual    | Se utilizarán colores tenues que inspiran seguridad y profesionalismo en la herramienta.                                                                                                                   |
| Diseño de la Interfaz | El diseño estará enfocado en facilitar la navegación a todo tipo de usuarios, independientemente de su edad o experiencia con la tecnología. Se empleará una disposición lógica en los menús, agrupando funciones similares para optimizar la experiencia del usuario. |
| Diseño de Usuario   | - Se da prioridad a una navegación intuitiva.<br>- La estructura del menú será ordenada y directa.                                                                                                         |
| Contenido           | - Se mostrará información verificada y actualizada.<br>- Control detallado de los recursos e insumos empleados en el establecimiento hotelero.                                                             |
| Funcionalidad       | - Registro de ingresos.<br>- Gestión precisa y actualizada de materiales y recursos, con el fin de minimizar errores y reducir pérdidas.                                                                   |
| Comunicación        | - Funciones de chat y correo electrónico.<br>- Formulario de contacto para comentarios.                                                                                                                    |
| Diseño Responsivo   | - Compatibilidad con dispositivos móviles.                                                                                                                                                                 |
| Seguridad y Privacidad | - Protección de datos sensibles.<br>- Cumplimiento de regulaciones de privacidad.                                                                                                                          |
| Actualizaciones y Mantenimiento | - Actualizaciones regulares de las bases de datos principales.<br>- Respuestas oportunas a problemas informados.                                                                                           |
| Promoción           | - Estrategias de marketing digital (publicidades en redes sociales).<br>- Colaboraciones con organizaciones hoteleras.                                                                                     |
### 4.1.1. General Style Guidelines
| **Aspecto**         | **Directrices** |
|----------------------|----------------|
| **Tipografía**       | Se optará por fuentes profesionales y de fácil lectura, priorizando la claridad del texto sobre su aspecto visual. Se recomienda el uso de tipografías Sans Serif. |
| **Colores**          | Se preferirán tonalidades suaves y tranquilas. |
| **Espaciado y diseño** | Se mantendrá un diseño despejado y estéticamente equilibrado. Se usarán márgenes amplios para evitar que el contenido luzca saturado. El espaciado ideal será entre 1.5 a 2 veces el tamaño de fuente utilizado. |
### 4.1.2. Web Style Guidelines
| **Aspecto**          | **Directrices** |
|----------------------|----------------|
| **Paleta de colores** | <div style="text-align: center;"><img src="https://i.imgur.com/T7mEAgd.png" alt="Paleta de colores"/></div>Estos colores fueron elegidos en base a principios de confianza, habilidad y limpieza. |
| **Menú de navegación** | El menú será adaptable a cualquier tamaño de pantalla, aprovechando el espacio disponible para mejorar la visibilidad del contenido. |
| **Interacción del Ratón** | Se diseñarán los elementos interactivos como botones, menús desplegables y animaciones pensando en la usabilidad con el ratón, brindando una experiencia fluida y atractiva. |
| **Uso de imágenes** | Se utilizarán imágenes de alta calidad y adecuadas para diferentes resoluciones sin comprometer el rendimiento de carga de la web. |
| **Cumplimiento de WCAG** | Se cumplirán los estándares de accesibilidad del contenido web, asegurando que cualquier persona pueda acceder y comprender el sitio sin barreras. |
| **Tipo de letra** | Se usará la fuente "Nunito" en sus estilos Medium y Normal, favoreciendo la claridad y el confort visual. |
### 4.1.3. Mobile Style Guidelines
| **Aspecto**          | **Directrices** |
|----------------------|----------------|
| **Paleta de colores** | <div style="text-align: center;"><img src="https://i.imgur.com/yk5loNt.png" alt="Paleta de colores móvil"/></div> Se emplearán colores suaves que refuercen la percepción de limpieza, profesionalismo y confianza en la interfaz móvil. |
| **Menú de navegación** | El menú inferior será claro, accesible y adaptable a diferentes tamaños de pantalla. Se utilizarán iconos intuitivos con colores suaves. |
| **Interacción táctil** | Los botones responderán con microanimaciones y cambios de color al tocarse, generando una experiencia amigable y reactiva para el usuario. |
| **Uso de imágenes** | Se usarán imágenes optimizadas para dispositivos móviles, asegurando tiempos de carga rápidos sin sacrificar la calidad visual. |
| **Accesibilidad** | Se mantendrá el contraste suficiente entre los colores, respetando los lineamientos de accesibilidad móvil (Android/iOS), como etiquetas de voz. |
| **Tipografía** | Se utilizará "Nunito" en dispositivos Android y "San Francisco" en iOS, ambas Sans Serif, para asegurar legibilidad y estética limpia en móviles. |
#### 4.1.3.1. iOS Mobile Style Guidelines
| **Aspecto**             | **Directrices** |
|-------------------------|----------------|
| **Diseño Visual**       | Se prioriza un diseño minimalista con una estructura limpia, donde los colores suaves transmiten profesionalismo y confianza. Se respetan las proporciones estándar del sistema iOS para una integración nativa. |
| **Navegación**          | Se implementa una barra de navegación inferior (tab bar) con íconos intuitivos, permitiendo al usuario acceder fácilmente a secciones clave como mensajes, alertas y ajustes. Se emplean transiciones suaves entre pantallas para una experiencia fluida. |
| **Tipografía**          | Se utiliza una tipografía Sans Serif moderna y legible, como "San Francisco", adaptándose al estilo nativo del sistema operativo iOS. |
| **Interacciones táctiles** | Los botones responden con animaciones suaves al tacto, utilizando gestos comunes como deslizamiento y tap para una navegación cómoda. |
| **Íconos e imágenes**   | Se utilizan iconos en formato vectorial de alta calidad compatibles con Retina Display. Las imágenes mantienen una resolución óptima sin sacrificar el rendimiento. |
| **Seguridad y privacidad** | Se integra Face ID y Touch ID como métodos de autenticación rápida, cumpliendo con los lineamientos de privacidad de Apple. |
| **Compatibilidad**      | La interfaz está optimizada para adaptarse a diferentes resoluciones de pantalla de iPhone, desde versiones SE hasta Pro Max. |
| **Accesibilidad**       | Se cumple con las recomendaciones de accesibilidad de Apple, como texto dinámico, etiquetas de voz y contraste suficiente para usuarios con discapacidades visuales. |
#### 4.1.3.2. Android Mobile Style Guidelines
| **Aspecto**             | **Directrices** |
|-------------------------|----------------|
| **Diseño Visual**       | Se sigue el sistema de diseño Material You, adaptando los colores suaves de la identidad visual a la personalización del usuario. El diseño es simple, limpio y estructurado para garantizar claridad. |
| **Navegación**          | Se utiliza una barra inferior de navegación (bottom navigation) con iconos representativos. El menú hamburguesa se usa para funciones secundarias. |
| **Tipografía**          | Se emplea la fuente "Roboto", optimizada para legibilidad en Android. Se asegura consistencia con los tamaños recomendados por Material Design. |
| **Interacciones táctiles** | Los botones y tarjetas responden con sombras y microanimaciones al ser presionados, siguiendo las directrices de interacción de Android. |
| **Íconos e imágenes**   | Se usan iconos adaptativos y vectores compatibles con múltiples densidades de pantalla (mdpi, hdpi, xhdpi, etc.). Las imágenes se adaptan automáticamente sin pérdida de calidad. |
| **Seguridad y privacidad** | Se incluye autenticación mediante PIN o huella dactilar. La aplicación sigue los lineamientos de Google para el manejo de datos sensibles. |
| **Compatibilidad**      | Se garantiza el correcto funcionamiento en una amplia gama de dispositivos con diferentes resoluciones, desde Android 8 (Oreo) en adelante. |
| **Accesibilidad**       | Se respetan las pautas de accesibilidad de Android, incluyendo compatibilidad con TalkBack, tamaños de texto escalables y colores con contraste adecuado. |
## 4.2. Information Architecture
La arquitectura de información de **Sweet Manager** ha sido diseñada para garantizar una navegación fluida, comprensible y accesible para todos los usuarios del sector hotelero. Cada módulo ha sido estructurado jerárquicamente según tareas, con etiquetas claras, organización visual efectiva y mecanismos de búsqueda potentes. La organización interna de los datos y su presentación facilitan la toma de decisiones y mejoran la experiencia de usuario en todo momento.
### 4.2.1. Organization Systems
La organización de contenidos en **Sweet Manager** responde a una estructura jerárquica basada en módulos funcionales que permiten la segmentación lógica de las tareas principales de gestión hotelera. Esta jerarquía garantiza que los usuarios puedan acceder a la información de forma rápida y ordenada, optimizando el tiempo de operación y reduciendo la carga cognitiva.

La información se presenta en secciones como:

- **Inicio**: Vista general con resumen de ingresos, tareas y notificaciones urgentes.
- **Inventario**: Módulo para el control de insumos y recursos, con indicadores visuales de stock y alertas de reabastecimiento.
- **Proveedores**: Listado de proveedores ordenado alfabéticamente con filtros por categoría, historial de pedidos y contacto directo.
- **Habitaciones**: Gestión del estado de las habitaciones (disponible, ocupada, mantenimiento), asignación de huéspedes y programación de limpieza.
- **Perfil**: Información del usuario y del establecimiento, con funciones para editar datos y gestionar accesos.

Estos módulos han sido organizados para facilitar la operación diaria, agrupando funciones similares y priorizando la información más consultada.

### 4.2.2. Labeling Systems
El sistema de etiquetado de **Sweet Manager** está diseñado para ser directo, comprensible y coherente a lo largo de toda la aplicación. Se busca minimizar la carga cognitiva del usuario mediante el uso de términos sencillos y familiares, principalmente sustantivos y verbos que describan acciones claras.

#### Criterios aplicados:

- **Claridad**: Las etiquetas como "Agregar proveedor", "Ver inventario" o "Editar habitación" describen exactamente la acción a realizar.

- **Consistencia**: Se utiliza el mismo término en todo el sistema para referirse a una función (por ejemplo, siempre se usa "habitaciones", no "cuartos" o "dormitorios").

- **Brevedad**: Las etiquetas son cortas y precisas, evitando frases largas que dificulten la lectura rápida.

- **Apoyo visual**: Se acompañan de iconos o colores que refuerzan el significado. Por ejemplo, el icono de caja se usa para inventario, el de gráfico para ingresos.

Este sistema mejora la velocidad de navegación, reduce errores y permite que incluso usuarios con baja alfabetización digital puedan utilizar la herramienta con facilidad.
### 4.2.3. SEO Tags and Meta Tags
Aunque **Sweet Manager** es una plataforma de acceso restringido, se aplican buenas prácticas de SEO y metadatos en las páginas públicas, como la **landing page** y documentación de soporte, lo cual permite mejorar su visibilidad en motores de búsqueda y garantizar una buena accesibilidad.

**Principales metaetiquetas implementadas:**

- **Título** : Describe brevemente el contenido de cada vista. Ejemplo: "Sweet Manager - Panel Principal", "Sweet Manager - Proveedores".

- **Meta descripción**: Resume en una o dos frases el propósito de la página. Ejemplo: "Gestiona de manera eficiente tus insumos, proveedores y habitaciones desde una sola plataforma."

- **Meta autor y copyright**: Atribuye el contenido a la empresa o equipo desarrollador, asegurando propiedad intelectual.

- **Codificación**: Asegura que todos los caracteres especiales, acentos y símbolos se visualicen correctamente.

- **Meta viewport**: Permite la correcta adaptación del diseño en dispositivos móviles.
### 4.2.4. Searching Systems
El sistema de búsqueda de Sweet Manager ha sido implementado para agilizar la localización de información dentro de los módulos principales, especialmente en áreas como proveedores, inventario y registros financieros.

**Características del sistema de búsqueda:**

- **Filtros personalizables**: Se pueden aplicar filtros por nombre, categoría, estado (activo/inactivo), fecha o tipo de transacción.

- **Autocompletado**: Sugiere resultados a medida que se escribe, utilizando el historial reciente y registros frecuentes.

- **Búsqueda global vs. contextual**:  
  - Global: Disponible desde la barra superior para buscar en toda la aplicación.  
  - Contextual: Integrada en cada módulo para buscar dentro de ese contexto específico (por ejemplo, solo en "Insumos").

- **Resultados ordenados por relevancia**: Los resultados más relacionados con la búsqueda aparecen primero.

Este sistema permite ahorrar tiempo y facilita el acceso a datos en tiempo real, algo esencial en entornos hoteleros donde la eficiencia es clave.
### 4.2.5. Navigation Systems
La navegación de **Sweet Manager** ha sido desarrollada siguiendo un enfoque centrado en el usuario, permitiéndole desplazarse de forma rápida, lógica y coherente entre los distintos módulos y funciones.

**Elementos clave del sistema de navegación:**

- **Menú inferior (mobile):** Contiene accesos rápidos a las secciones principales (Inicio, Inventario, Proveedores, Perfil).

- **Menú lateral (web):** Desplegable, contiene acceso a configuraciones, reportes y funciones avanzadas.

- **Breadcrumbs o migas de pan:** Indican al usuario en qué sección se encuentra, permitiendo regresar fácilmente al paso anterior.

- **Botones de acción flotantes:** Para realizar tareas comunes como añadir, editar o eliminar elementos, visibles en todas las vistas operativas.

Además, la navegación es completamente **responsive**, adaptándose a cualquier tamaño de pantalla y manteniendo la coherencia visual y funcional en todos los dispositivos.

## 4.3. Landing Page UI Design

La landing page de **Sweet Manager** es la primera vista que tiene un usuario cuando llega al producto, por lo que se pensó para ser clara, llamativa y fácil de entender. La idea es que el usuario sepa de inmediato de qué trata la plataforma y por qué le conviene usarla. Todo el diseño sigue una lógica centrada en el usuario, buscando una experiencia fluida tanto en computadora como en celular.

### 4.3.1. Landing Page Wireframe

Se usó un patrón visual en forma de “Z” porque es el que mejor guía la vista del usuario. La estructura tiene secciones clave como:

* Un encabezado con el logo y menú.
* Un bloque principal con mensaje central y botón para empezar.
* Una sección donde se explican las principales funciones.
* Una parte final con contacto, redes y enlaces importantes.

**Wireframe Landing Page - Desktop**

<div style="text-align: center;">
  <img src="https://i.imgur.com/vg3Ursw.jpg" alt="Landing Page Wireframe" width="70%" />
</div>

**Wireframe Landing Page - Mobile**

<div style="text-align: center;">
  <img src="https://i.imgur.com/FbzK3HV.png" alt="Landing Page Wireframe" width="70%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/hnCTEWz.png" alt="Landing Page Wireframe" width="70%" />
</div>

### 4.3.2. Landing Page Mock-up

El mock-up muestra cómo se verá realmente la landing, ya con los colores, tipografías, íconos, imágenes. Se diseñó pensando tanto en desktop como en móvil, y se hizo usando  **Figma** , respetando el sistema visual del proyecto.

**Mockup Landing Page - Español Web**

<div style="text-align: center;">
  <img src="https://i.imgur.com/4ZjeJNy.png" alt="Landing Page Wireframe" width="70%" />
</div>

**Mockup Landing Page - Español Mobile**

<div style="text-align: center;">
  <img src="https://i.imgur.com/3CdDW9N.png" alt="Landing Page Wireframe" width="70%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/w36fmPq.png" alt="Landing Page Wireframe" width="70%" />
</div>

**Mockup Landing Page - Inglés Web**

<div style="text-align: center;">
  <img src="https://i.imgur.com/a7NFJRU.png" alt="Landing Page Wireframe" width="70%" />
</div>

**Mockup Landing Page - Inglés Mobile**

<div style="text-align: center;">
  <img src="https://i.imgur.com/7OQRdzy.png" alt="Landing Page Wireframe" width="70%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/mX279QV.png" alt="Landing Page Wireframe" width="70%" />
</div>

## 4.4. Mobile Applications UX/UI Design

### 4.4.1. Mobile Applications Wireframes

Son los primeros bocetos de las pantallas de la app. Nos ayudan a definir la estructura de cada vista sin meternos aún con los colores o estilos. Es una guía visual para ver cómo se distribuye todo.

<div style="text-align: center;">
  <img src="https://i.imgur.com/e4GOmc0.png" alt="Landing Page Wireframe" width="70%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/c5P0wpj.png" alt="Landing Page Wireframe" width="70%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/sKfwEkA.png" alt="Landing Page Wireframe" width="70%" />
</div>

### 4.4.2. Mobile Applications Wireflow Diagrams

Aquí mostramos cómo se conectan entre sí las pantallas de la app. Sirve para entender el recorrido que hace el usuario desde que entra hasta que realiza una acción específica.

**Creación de usuario y compra de membresía**

<div style="text-align: center;">
  <img src="https://i.imgur.com/ZvQllH2.png" alt="Landing Page Wireframe" width="70%" />
</div>

**Pantallas Principales**

<div style="text-align: center;">
  <img src="https://i.imgur.com/9q1Uec6.png" alt="Landing Page Wireframe" width="70%" />
</div>

**Creación de trabajador**

<div style="text-align: center;">
  <img src="https://i.imgur.com/zH2UCtE.png" alt="Landing Page Wireframe" width="70%" />
</div>

### 4.4.3. Mobile Applications Mock-ups

Estos son los diseños ya con colores, íconos, tipografías y estilos aplicados. Representan cómo se verá la app en su versión final, tanto en Android como en iOS.

**Creación de trabajador y compra membresía**

<div style="text-align: center;">
  <img src="https://i.imgur.com/dnAQFIn.png" alt="Landing Page Wireframe" width="70%" />
</div>

**Pantallas principales**

<div style="text-align: center;">
  <img src="https://i.imgur.com/7YSvo13.png" alt="Landing Page Wireframe" width="70%" />
</div>

**Vistas Mobile - iOS**

<div style="text-align: center;">
  <img src="https://i.imgur.com/I9YRNQi.png" alt="Landing Page Wireframe" width="70%" />
</div>

**Vistas Mobile - Android**

<div style="text-align: center;">
  <img src="https://i.imgur.com/LqYPKni.png" alt="Landing Page Wireframe" width="70%" />
</div>

### 4.4.4. Mobile Applications User Flow Diagrams

Mostramos los pasos que sigue el usuario para completar tareas dentro de la app. Esto nos permite validar si la experiencia es clara o si hay puntos que podrían confundir.

**Flujo creación de trabajador**

<div style="text-align: center;">
  <img src="https://i.imgur.com/t4FuCze.png" alt="Landing Page Wireframe" width="70%" />
</div>

**Compra de membresía**

<div style="text-align: center;">
  <img src="https://i.imgur.com/nXgA78C.png" alt="Landing Page Wireframe" width="70%" />
</div>

## 4.5. Mobile Applications Prototyping

### 4.5.1. Android Mobile Applications Prototyping

Link: https://www.figma.com/proto/dgI7kPPYrsUiQ0wPGJ2Aqg/RoomWise?page-id=0%3A1&node-id=2-12476&viewport=99%2C230%2C0.08&t=N0loGqeQmIjNZuxK-1&scaling=min-zoom&content-scaling=fixed&starting-point-node-id=2%3A12476&show-proto-sidebar=1

<div style="text-align: center;">
  <img src="https://i.imgur.com/GCsihGx.png" alt="Landing Page Wireframe" width="70%" />
</div>

### 4.5.2. iOS Mobile Applications Prototyping

Link: https://www.figma.com/proto/dgI7kPPYrsUiQ0wPGJ2Aqg/RoomWise?page-id=0%3A1&node-id=3-25830&viewport=99%2C230%2C0.08&t=N0loGqeQmIjNZuxK-1&scaling=min-zoom&content-scaling=fixed&starting-point-node-id=3%3A25830&show-proto-sidebar=1

<div style="text-align: center;">
  <img src="https://i.imgur.com/ZPvFbBa.png" alt="Landing Page Wireframe" width="70%" />
</div>

## 4.6. Web Applications UX/UI Design

### 4.6.1. Web Applications Wireframes

Diseñamos la estructura de las páginas web sin detalles visuales. Es útil para tener clara la organización de la información y los elementos.

<div style="text-align: center;">
  <img src="https://i.imgur.com/n4vSjLJ.png" alt="Landing Page Wireframe" width="70%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/CcjdMif.png" alt="Landing Page Wireframe" width="70%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/YAmHbfl.png" alt="Landing Page Wireframe" width="70%" />
</div>

### 4.6.2. Web Applications Wireflow Diagrams

Representan cómo se conecta cada vista del sistema web. Ayuda a identificar posibles caminos del usuario y cómo se mueve dentro de la plataforma.

**Creación de cliente:**

<div style="text-align: center;">
  <img src="https://i.imgur.com/ujb0ynL.png" alt="Landing Page Wireframe" width="70%" />
</div>

**Creación de usuario:**

<div style="text-align: center;">
  <img src="https://i.imgur.com/WfTNwWF.png" alt="Landing Page Wireframe" width="70%" />
</div>

### 4.6.3. Web Applications Mock-ups

Se aplica el diseño visual completo de la versión web.

**Componentes Trabajadores e Inventario**

<div style="text-align: center;">
  <img src="https://i.imgur.com/ZGFalim.png" alt="Landing Page Wireframe" width="70%" />
</div>

**Componentes Proveedores y Clientes**

<div style="text-align: center;">
  <img src="https://i.imgur.com/mYZmZvS.png" alt="Landing Page Wireframe" width="70%" />
</div>

Componentes Login/Register/Planes/Pasarela de Pago

<div style="text-align: center;">
  <img src="https://i.imgur.com/MXxYNn4.png" alt="Landing Page Wireframe" width="70%" />
</div>

**Componentes Design System**

<div style="text-align: center;">
  <img src="https://i.imgur.com/vNqjFyp.png" alt="Landing Page Wireframe" width="70%" />
</div>

### 4.6.4. Web Applications User Flow Diagrams

Muestra el recorrido que sigue el usuario desde que entra al sistema web hasta que realiza acciones.

**Añadir a un nuevo cliente:**

<div style="text-align: center;">
  <img src="https://i.imgur.com/5nccaSk.png" alt="Landing Page Wireframe" width="70%" />
</div>

**Creación de cuenta y compra de membresía:**

<div style="text-align: center;">
  <img src="https://i.imgur.com/O5yCAHx.png" alt="Landing Page Wireframe" width="70%" />
</div>

## 4.7. Web Applications Prototyping

Creamos un prototipo navegable de la versión web, con interacciones simuladas. Esto nos sirve para probar la experiencia completa antes de pasar al desarrollo real.
Link del prototipo: https://www.figma.com/proto/dgI7kPPYrsUiQ0wPGJ2Aqg/RoomWise?page-id=10%3A27888&node-id=111-5594&viewport=655%2C-536%2C0.07&t=Tx3sXW59IhsNi3BM-1&scaling=min-zoom&content-scaling=fixed&starting-point-node-id=111%3A5594

<div style="text-align: center;">
  <img src="https://i.imgur.com/BWarI1n.png" alt="Landing Page Wireframe" width="70%" />
</div>

## 4.8. Domain-Driven Software Architecture
A continuación, se mostrarán los diagramas C4
### 4.8.1. Software Architecture Context Diagram
Se puede visualizar el diagrama de contexto que representa un panorama general de la comunicación entre nuestros segmento objetivo y la aplicacion
<div style="text-align: center;">
  <img src="https://i.imgur.com/GL3GbgB.png" alt="Imagen del context diagram" width="90%" />
</div>

### 4.8.2. Software Architecture Container Diagrams
En el siguiente diagrama se puede apreciar el funcionamiento que la aplicación trendrá y las relaciones con los correspondientes sistemas, lo que se busca es lograr una organización de forma que no generen dependencias fuertes que perjudiquen migraciones a futuro, asi mcomo también esquematizar como funcionara la interaccion entre los diferentes sistemas
<div style="text-align: center;">
  <img src="https://i.imgur.com/BigfPO9.png" alt="Imagen del container diagram" width="90%" />
</div>

### 4.8.3. Software Architecture Components Diagrams
A contuniación, se muestra las relaciones entre los bounded context que trabajan en el servicio de Sweet Manager
<div style="text-align: center;">
  <img src="https://i.imgur.com/5gOn3Bk.png" alt="Imagen del container diagram" width="50%" />
</div>

## **Commerce Context**
<div style="text-align: center;">
  <img src="https://i.imgur.com/V51iHjq.png" alt="Imagen del container diagram" width="90%" />
</div>

## **Resource Management Context**
<div style="text-align: center;">
  <img src="https://i.imgur.com/Fm1raQs.png" alt="Imagen del container diagram" width="90%" />
</div>

## **Supply Management Context**
<div style="text-align: center;">
  <img src="https://i.imgur.com/c7wVVE4.png" alt="Imagen del container diagram" width="90%" />
</div>

## **Profile Context**
<div style="text-align: center;">
  <img src="https://i.imgur.com/dzpzORr.png" alt="Imagen del container diagram" width="90%" />
</div>

## **Monitoring Context**
<div style="text-align: center;">
  <img src="https://i.imgur.com/E1mg7F4.png" alt="Imagen del container diagram" width="90%" />
</div>

## **Communication Context**
<div style="text-align: center;">
  <img src="https://i.imgur.com/Q3HWIkh.png" alt="Imagen del container diagram" width="90%" />
</div>

## 4.9. Software Object-Oriented Design
### 4.9.1. Class Diagrams

## Communication 
<div style="text-align: center;">
  <img src="https://i.imgur.com/657Jcan.jpeg" alt="Imagen del db diagram" width="90%" />
</div>

## Commerce 
<div style="text-align: center;">
  <img src="https://i.imgur.com/Hjbopta.png" alt="Imagen del db diagram" width="90%" />
</div>

## Profile
<div style="text-align: center;">
  <img src="https://i.imgur.com/mTtALSQ.png" alt="Imagen del db diagram" width="90%" />
</div>

## Reservation
<div style="text-align: center;">
  <img src="https://i.imgur.com/XDh2sCt.png" alt="Imagen del db diagram" width="90%" />
</div>

## IAM
<div style="text-align: center;">
  <img src="https://i.imgur.com/6OAktK0.png" alt="Imagen del db diagram" width="90%" />
</div>

## Supply
<div style="text-align: center;">
  <img src="https://i.imgur.com/qFkckna.png" alt="Imagen del db diagram" width="90%" />
</div>


### 4.9.2. Class Dictionary
| Clase                   | Descripción                                                                 |
|-------------------------|----------------------------------------------------------------------------|
| `assignments_workers`   | Asignaciones de trabajadores a áreas con fechas y estado.                  |
| `types_reports`         | Tipos de reportes disponibles en el sistema.                               |
| `workers_areas`         | Áreas de trabajo donde se asignan los trabajadores.                        |
| `reports`               | Reportes generados por trabajadores o administradores.                    |
| `workers_`              | Información de los trabajadores (usuarios con rol de operación).           |
| `owners_credentials`    | Credenciales de acceso para propietarios.                                  |
| `subscriptions`         | Planes de suscripción disponibles para propietarios.                       |
| `contracts_owners`      | Contratos activos de propietarios con suscripciones.                       |
| `supplies`              | Insumos o materiales gestionados en el sistema.                            |
| `providers`             | Proveedores de insumos/materiales.                                         |
| `notifications`         | Notificaciones enviadas a usuarios (propietarios, admins o trabajadores). |
| `notes`                 | Notas asociadas a propietarios (datos adicionales).                       |
| `payments_owners`       | Pagos realizados por propietarios.                                         |
| `customers`             | Clientes del sistema (usuarios que realizan reservas).                     |
| `supplies_requests`     | Solicitudes de insumos vinculadas a pagos.                                 |
| `admins_credentials`    | Credenciales de acceso para administradores.                               |
| `admins`                | Usuarios con rol administrativo.                                           |
| `types_notifications`   | Tipos de notificaciones disponibles.                                       |
| `types_rooms`           | Tipos de habitaciones y sus características.                               |
| `bookings`              | Reservas realizadas por clientes.                                          |
| `payments_customers`    | Pagos realizados por clientes.                                             |


## 4.10. Database Design
Para Sweet Manager, se ha implementado una base de datos relacional que garantiza la integridad y consistencia de los datos mediante relaciones bien definidas entre entidades como habitaciones, clientes, reservas y pagos, permitiendo consultas complejas con alto rendimiento para gestionar disponibilidad, historiales y transacciones, mientras que su estructura normalizada elimina redundancias y facilita la escalabilidad para incorporar futuras funcionalidades sin comprometer la organización existente, todo ello asegurando la coherencia de las operaciones mediante claves primarias y foráneas.
### 4.10.1. Relational/Non-Relational Database Diagram
<div style="text-align: center;">
  <img src="https://i.imgur.com/QPeNpMH.png" alt="Imagen del db diagram" width="90%" />
</div>

# Capítulo V: Product Implementation
## 5.1. Software Configuration Management
### 5.1.1. Software Development Environment Configuration

-Project Management:

*Producto: Jira
*Propósito: Ayudar a los equipos a planificar, rastrear y gestionar el trabajo en proyectos de desarrollo de software y otras iniciativas.

*Enlace: https://jeremyantonio.atlassian.net/jira/software/projects/EDS/boards/34/backlog?atlOrigin=eyJpIjoiZDdlM2UxYzEwMDFhNDQ2Zjk2YmExZWViMmZhZTM4ZmUiLCJwIjoiaiJ9

-Product UX/UI Design:

*Producto: Figma

*Propósito:  Proporcionar una plataforma de diseño colaborativo en línea para equipos de diseño de interfaces de usuario (UI) y experiencia de usuario (UX), permitiendo crear, compartir y colaborar en tiempo real en proyectos de diseño visual, prototipos y maquetas de productos digitales.

 *Enlace: https://www.figma.com/design/dgI7kPPYrsUiQ0wPGJ2Aqg/RoomWise?node-id=10-27888&t=qPAbglcZ1AvZZ9FW-1

### 5.1.2. Source Code Management
A continuación, se describe cómo se gestionará el código fuente en este proyecto, lo cual permitirá monitorear y controlar los cambios realizados por cualquier integrante del equipo durante el proceso de desarrollo. Además, se utilizará un repositorio en GitHub para administrar las distintas versiones del código a lo largo del proyecto.

*REPOSITORIO DE GITHUB: <https://github.com/1ASI0732-2510-4433-G1-ROOMWISE>

*LANDING PAGE:

Desarrollo de GitFlow: Para llevar a cabo este proyecto, se emplea GitFlow como modelo de control de versiones. Este enfoque facilitará la organización mediante la creación de ramas principales y ramas de apoyo, permitiendo una gestión estructurada del desarrollo.

 Ramas de apoyo:

-Rama Release:
Se genera a partir de la rama Develop y se utiliza para preparar una nueva versión del proyecto. En esta etapa se llevan a cabo tareas como la identificación y corrección de errores. No obstante, no se permite la incorporación de nuevas funcionalidades. Una vez finalizado este proceso, la rama Release debe fusionarse tanto con main como con develop.

-Rama Hotfix:
Se crea desde la rama Main con el objetivo de solucionar errores detectados durante la fase de depuración del código en producción. Tras resolver dichos problemas, esta rama debe integrarse nuevamente en main y develop para mantener la coherencia del proyecto.

### 5.1.3. Source Code Style Guide & Conventions

Para la implementación en HTML y CSS, se adoptarán las convenciones establecidas por la Google HTML/CSS Style Guide, la cual proporciona lineamientos claros sobre cómo estructurar y escribir código utilizando estas tecnologías. Entre las principales prácticas que aplicaremos se encuentran:

-Utilizar siempre letras minúsculas para nombrar los elementos HTML.

-Asegurarse de cerrar correctamente todos los elementos HTML.

-Incluir siempre comillas alrededor de los atributos de los elementos HTML.

-Evitar líneas de código excesivamente largas para mejorar la legibilidad.

-Incluir la etiqueta meta (MetaTags) al inicio del documento para definir la codificación y otros metadatos relevantes.

### 5.1.4. Software Deployment Configuration

Para implementar la Landing Page del proyecto, se empleará GitHub Pages, un servicio proporcionado por GitHub que permite la publicación sencilla de sitios web estáticos directamente desde un repositorio. Por ello, se ha creado un repositorio inicial donde se documentan las distintas versiones generadas durante el desarrollo.
Durante la construcción de la Landing Page, se utilizarán las siguientes herramientas:

HTML: Este lenguaje  se usará para estructurar y organizar el contenido del landing page.

CSS: Se aplicará este lenguaje de estilos para definir la presentación visual del sitio, mejorando su apariencia y experiencia de usuario. Para agilizar este proceso, se aprovecharán clases previamente definidas mediante el framework Tailwind CSS.


## 5.2. Product Implementation & Deployment

### 5.2.1. Sprint Backlogs
Esta sección presenta las tareas completadas en cada sprint correspondiente, junto con una captura de Jira que muestra el progreso alcanzado hasta ese punto y el enlace al tablero

<https://jeremyantonio.atlassian.net/jira/software/projects/EDS/boards/34?atlOrigin=eyJpIjoiMzBhYWNkZWVjZGIxNDczNjlmNGZiMzlmNjgzMzEzMzgiLCJwIjoiaiJ9>


__Sprint 01__

__Evidencia del Jira__


<div style="text-align: center;">
   <img src="https://i.imgur.com/BT7BE15.png" alt="Jira tasks"/>
</div><br>

# Sprint Backlog 02 (Completed)

| Module                | Sprint # | User Story ID | User Story Description                      | Work-item Task                         | Estimation (hours) | Assigned To | Status |
|-----------------------|----------|---------------|--------------------------------------------|----------------------------------------|--------------------|-------------|--------|
| Landing Page          | Sprint 1 | US03 - EP01   | Consultar planes de precios                | Mostrar planes de precios en landing page | 2                | Omar        | Done   |
|                       | Sprint 1 | US04 - EP01   | Establecer contacto con la empresa         | Implementar formulario de contacto        | 2                | Jeremy A         | Done   |
| Autenticación         | Sprint 1 | US05 - EP02   | Iniciar sesión en el sistema               | Implementar login con JWT                | 4                | Jeremy G        | Done   |
|                       | Sprint 1 | US06 - EP02   | Registro de cuenta                         | Formulario registro gerentes             | 4                | Jeremy A        | Done   |
| Gestión Operativa     | Sprint 1 | US08 - EP03   | Gestión de trabajadores                    | CRUD básico de trabajadores              | 5                | Fernando        | Done   |
|                       | Sprint 1 | US09 - EP03   | Gestión de habitaciones                    | CRUD habitaciones y tipos                | 5                | Jack        | Done   |
|                       | Sprint 1 | US10 - EP03   | Gestión de proveedores                     | CRUD básico de proveedores               | 4                | Sebastian        | Done   |
|                       | Sprint 1 | US11 - EP03   | Gestión de inventario                      | Agregar suministros y solicitudes       | 5                | Omar        | Done   |
|                       | Sprint 1 | US12 - EP03   | Gestión de administradores                 | CRUD básico de administradores           | 4                | Sebastian        | Done   |
|                       | Sprint 1 | US13 - EP03   | Gestión de información del hotel           | Formulario información del hotel         | 3                | Jack        | Done   |
| Gestión Reservas      | Sprint 1 | US14 - EP04   | Gestión de reservas                        | CRUD básico de reservas                  | 6                | Fernando        | Done   |
| Comunicación          | Sprint 1 | US15 - EP04   | Sistema de notificaciones                  | Crear alertas y mensajes                 | 4                | Omar        | Done   |
|                       | Sprint 1 | US16 - EP04   | Visualizar notificaciones                  | Lista de notificaciones recibidas       | 3                | Jack        | Done   |

### 5.2.2. Implemented Landing Page Evidence

<p>Evidencias del avance de la implemmentación de la Landing Page</p>

<div style="text-align: center;">
   <img src="https://i.imgur.com/gL6uj1N.png" alt="Landing evidence"/>
</div><br>


<div style="text-align: center;">
   <img src="https://i.imgur.com/6TA4DdJ.png" alt="Landing evidence"/>
</div><br>

<div style="text-align: center;">
   <img src="https://i.imgur.com/393hd8t.png" alt="Landing evidence"/>
</div><br>


### 5.2.3. Implemented Frontend-Web Application Evidence

<div style="text-align: center;">
   <img src="https://i.imgur.com/GQSSFZw.png" alt="Landing evidence"/>
</div><br>

<div style="text-align: center;">
   <img src="https://i.imgur.com/umWVqae.png" alt="Landing evidence"/>
</div><br>

<div style="text-align: center;">
   <img src="https://i.imgur.com/SVMqRYp.png" alt="Landing evidence"/>
</div><br>

<div style="text-align: center;">
   <img src="https://i.imgur.com/4tKsDgy.png" alt="Landing evidence"/>
</div><br>

### 5.2.4. Acuerdo de Servicio - SaaS

Al utilizar la aplicación web *Sweet Manager* (en adelante, "la Aplicación"), el usuario acepta los términos del presente Acuerdo de Servicio bajo el modelo *Software as a Service* (SaaS). Este acuerdo establece las condiciones bajo las cuales *SweetSolutions* (en adelante, "la Empresa") proporciona el acceso y uso de la Aplicación a través de internet.

#### Alcance del Servicio
La Aplicación permite la gestión integral de hoteles, incluyendo el registro de clientes, administración de habitaciones, gestión de incidencias, notificaciones, administración de suministros y proveedores, entre otras funcionalidades orientadas a la mejora operativa del negocio hotelero.

#### Registro y Cuenta de Usuario
Para acceder a todas las funcionalidades de la Aplicación, el usuario deberá registrarse proporcionando información personal válida, como nombre completo, correo electrónico y número de celular. La Empresa garantiza que esta información será utilizada exclusivamente con fines operativos y de prestación del servicio.

#### Protección de Datos y Seguridad
La Empresa se compromete a proteger los datos personales de los usuarios mediante medidas de seguridad técnicas y organizativas. Se emplean prácticas como el uso de tokens de autenticación en el backend para prevenir accesos no autorizados.

#### Modelos de Suscripción
El uso de la Aplicación está sujeto a la adquisición de un plan de suscripción. El pago se realiza exclusivamente mediante tarjeta de crédito o débito. Los planes, junto con sus precios y características, estarán claramente descritos en la plataforma.

#### Derechos de Propiedad Intelectual
Todos los derechos sobre la Aplicación, incluyendo el software, diseño, funcionalidades y contenido, son propiedad exclusiva de *SweetSolutions*. El usuario no adquiere ningún derecho de propiedad intelectual por el uso de la Aplicación.

#### Legislación Aplicable
Este Acuerdo de Servicio se rige por las leyes de la República del Perú. En caso de controversia, ambas partes acuerdan someterse a la jurisdicción exclusiva de los tribunales peruanos.

#### Contacto
Para consultas, quejas o solicitudes relacionadas con el presente acuerdo, el usuario puede comunicarse al correo electrónico: roomwise@gmail.com.

### 5.2.5. Implemented Native-Mobile Application Evidence

<div style="text-align: center;">
   <img src="https://i.imgur.com/UHoWDTK.jpeg" alt="Landing evidence" width = "40%"/>
</div><br>

<div style="text-align: center;">
   <img src="https://i.imgur.com/U4oQl6F.jpeg" alt="Landing evidence" width = "40%"/>
</div><br>

<div style="text-align: center;">
   <img src="https://i.imgur.com/rY2SvVt.jpeg" alt="Landing evidence" width = "40%" />
</div><br>

<div style="text-align: center;">
   <img src="https://i.imgur.com/Qm0qIGt.jpeg" alt="Landing evidence" width = "40%"/>
</div><br>

### 5.2.6. Implemented RESTful API and/or Serverless Backend Evidence

<div style="text-align: center;">
   <img src="https://i.imgur.com/hYcn7q9.png" alt="Landing evidence" width = "90%"/>
</div><br>

<div style="text-align: center;">
   <img src="https://i.imgur.com/R463vJ9.png" alt="Landing evidence" width = "90%"/>
</div><br>

<div style="text-align: center;">
   <img src="https://i.imgur.com/aKSW4y8.png" alt="Landing evidence" width = "90%"/>
</div><br>

<div style="text-align: center;">
   <img src="https://i.imgur.com/ker53Nl.png" alt="Landing evidence" width = "90%"/>
</div><br>

<div style="text-align: center;">
   <img src="https://i.imgur.com/gnA9D8y.png" alt="Landing evidence" width = "90%"/>
</div><br>


### 5.2.7. RESTful API documentation


A continuación, se presenta una descripción detallada de la documentación de la RESTful API desarrollada para este sistema. Esta interfaz de programación de aplicaciones permite la comunicación entre clientes (tanto web como móviles) y el servidor backend, utilizando el paradigma REST (Representational State Transfer), ampliamente adoptado por su simplicidad, escalabilidad y separación de responsabilidades.

## Principios RESTful

Una API RESTful se basa en los siguientes principios fundamentales:

- **Recursos como entidades centrales**: Cada recurso (por ejemplo, usuarios, espacios, reservas) se representa mediante una URI única.

- **Operaciones a través de verbos HTTP**: Las operaciones sobre los recursos se realizan mediante los verbos HTTP estándar:
  - `GET`: Recuperar información.
  - `POST`: Crear un nuevo recurso.
  - `PUT`: Actualizar un recurso existente.
  - `DELETE`: Eliminar un recurso.

- **Sin estado (stateless)**: Cada solicitud debe contener toda la información necesaria para ser procesada. El servidor no almacena estado entre peticiones.

- **Uso de hipermedios (opcional - HATEOAS)**: Aunque no se implementa siempre, REST permite que las respuestas incluyan enlaces para navegar entre recursos relacionados.

## Autenticación

- **Método utilizado**: JWT (JSON Web Token), una forma segura y compacta de transmitir información entre partes.

- **Formato del encabezado requerido**: 
Los tokens JWT permiten autenticar y autorizar a los usuarios sin necesidad de mantener sesiones en el servidor, lo cual es coherente con el principio stateless.

## Convenciones y Buenas Prácticas

- **Nombres de recursos en plural**: Para mantener la coherencia y claridad, los endpoints usan sustantivos en plural (e.g., `/users`, `/spaces`, `/reservations`).

- **Versionamiento de la API**: Aunque no siempre es necesario, es recomendable incluir una versión en la URI (e.g., `/api/v1/users`) para facilitar futuras actualizaciones sin romper la compatibilidad.

- **Códigos de estado HTTP**: La API utiliza códigos de estado HTTP estándar para indicar el resultado de cada operación:
- `200 OK`: Solicitud exitosa.
- `201 Created`: Recurso creado correctamente.
- `400 Bad Request`: Error en los datos enviados.
- `401 Unauthorized`: Falta de autenticación o token inválido.
- `404 Not Found`: Recurso no encontrado.
- `500 Internal Server Error`: Error inesperado en el servidor.


## Documentación Interactiva

Se recomienda el uso de herramientas como Swagger (OpenAPI) o Postman para documentar y probar la API de manera interactiva. Esto mejora la experiencia de los desarrolladores y facilita la integración con otras aplicaciones.

### 5.2.8. Team Collaboration Insights

#### Document Report 
<div style="text-align: center;">
   <img src="https://i.imgur.com/EYzqJ9h.png" alt="document report insights" width = "95%"/>
</div><br>

#### Web Service 
<div style="text-align: center;">
   <img src="https://i.imgur.com/uoyxkMa.png" alt="web service insights" width = "95%"/>
</div><br>

#### Frontend 
<div style="text-align: center;">
   <img src="https://i.imgur.com/gLQqAnm.png" alt="frontend insights" width = "95%"/>
</div><br>

#### Mobile Aplication 
<div style="text-align: center;">
   <img src="https://i.imgur.com/ke2RqBc.png" alt="mobile application insights" width = "95%"/>
</div><br>

## 5.3. Video About-the-Product

<div style="text-align: center;">
   <img src="https://i.imgur.com/FUZX03I.png" alt="Landing evidence"/>
</div><br>

Enlace del video: <https://youtu.be/T92OwQTaaeg>

# Capítulo VI:  Product Verification & Validation


## 6.1. Testing Suites & Validation

### 6.1.1. Core Entities Unit Tests.

Las pruebas unitarias de las entidades principales (Core Entities) son fundamentales en el desarrollo de software, ya que aseguran la calidad y el funcionamiento adecuado de los componentes clave, ayudando a prevenir errores y a mantener el código de forma más sencilla.

__Bookign Tests__
<div style="text-align: center;">
   <img src="https://i.imgur.com/M6GLbTV.png" alt="Landing evidence"/>
</div><br>

__Notification Tests__
<div style="text-align: center;">
   <img src="https://i.imgur.com/mRXZWyp.png" alt="Landing evidence"/>
</div><br>


__Report Tests__
<div style="text-align: center;">
   <img src="https://i.imgur.com/RswEY24.png" alt="Landing evidence"/>
</div><br>

__Room Tests__
<div style="text-align: center;">
   <img src="https://i.imgur.com/2szS89u.png" alt="Landing evidence"/>
</div><br>

__Supply Request Tests__
<div style="text-align: center;">
   <img src="https://i.imgur.com/NmbWc2j.png" alt="Landing evidence"/>
</div><br>

__Supply Tests__
<div style="text-align: center;">
   <img src="https://i.imgur.com/dBVEtum.png" alt="Landing evidence"/>
</div><br>

### 6.1.2. Core Integration Tests

Las pruebas de integración son esenciales para verificar que los controladores funcionen correctamente al interactuar con otros módulos del sistema, como servicios y bases de datos. Estas pruebas aseguran que la aplicación gestione adecuadamente casos excepcionales, devolviendo los códigos de estado HTTP correspondientes. Esto no solo optimiza la experiencia del usuario, sino que también simplifica el diagnóstico de fallos y ayuda a construir un software robusto y confiable.

__Contracts Controller Tests__
<div style="text-align: center;">
   <img src="https://i.imgur.com/G543PD9.png" alt="Contracts Controller Tests"/>
</div><br>

__Payment Controller Tests__
<div style="text-align: center;">
   <img src="https://i.imgur.com/ENKFwzh.png" alt="Payment Controller Tests"/>
</div><br>

__Subscription Controller Tests__
<div style="text-align: center;">
   <img src="https://i.imgur.com/cow0Q04.png" alt="Subscription Controller Tests"/>
</div><br>

__Notifications Controller Tests__
<div style="text-align: center;">
   <img src="https://i.imgur.com/S9zHYtb.png" alt="Notifications Controller Tests"/>
</div><br>

__Types Notifications Controller Tests__
<div style="text-align: center;">
   <img src="https://i.imgur.com/iCqzW94.png" alt="Types Notifications Controller Tests"/>
</div><br>

__Assignment Worker Controller Tests__
<div style="text-align: center;">
   <img src="https://i.imgur.com/A8orZJe.png" alt="Assignment Worker Controller Tests"/>
</div><br>

__Authentication Controller Tests__
<div style="text-align: center;">
   <img src="https://i.imgur.com/VqbsEbB.png" alt="Authentication Controller Tests"/>
</div><br>

__User Controller Tests__
<div style="text-align: center;">
   <img src="https://i.imgur.com/dwBBBiA.png" alt="UserController Tests"/>
</div><br>

__Worker Area Controller Tests__
<div style="text-align: center;">
   <img src="https://i.imgur.com/MnxbbGq.png" alt="WorkerAreaController Tests"/>
</div><br>

__Bookings Controller Tests__
<div style="text-align: center;">
   <img src="https://i.imgur.com/pW4IcHW.png" alt="BookingsController Tests"/>
</div><br>

__Rooms Controller Tests__
<div style="text-align: center;">
   <img src="https://i.imgur.com/FXBzFMC.png" alt="Rooms Controller Tests"/>
</div><br>

__Types Rooms Controller Tests__
<div style="text-align: center;">
   <img src="https://i.imgur.com/5lpV5p8.png" alt="TypesRoomsController Tests"/>
</div><br>

__Customer Controller Tests__
<div style="text-align: center;">
   <img src="https://i.imgur.com/C9k9OGr.png" alt="Customer Controller Tests"/>
</div><br>

__Hotel Controller Tests__
<div style="text-align: center;">
   <img src="https://i.imgur.com/55OaMJl.png" alt="Hotel Controller Tests"/>
</div><br>

__Provider Controller Tests__
<div style="text-align: center;">
   <img src="https://i.imgur.com/lmzF6Mg.png" alt="Provider Controller Tests"/>
</div><br>

__Reports Controller Tests__
<div style="text-align: center;">
   <img src="https://i.imgur.com/WIRLVNM.png" alt="Reports Controller Tests"/>
</div><br>

__Types Reports Controller Tests__
<div style="text-align: center;">
   <img src="https://i.imgur.com/wOqOYVx.png" alt="Types Reports Controller Tests"/>
</div><br>

__Supplies Request Controller Tests__
<div style="text-align: center;">
   <img src="https://i.imgur.com/cCt1CfX.png" alt="Supplies Request Controller Tests"/>
</div><br>

__Supply Controller Tests__
<div style="text-align: center;">
   <img src="https://i.imgur.com/nzErJn7.png" alt="Supply Controller Tests"/>
</div><br>

### 6.1.3. Core Behavior-Driven Development

<div style="text-align: center;">
  <img src="https://i.imgur.com/luXLX7w.png"  width="70%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/3FiYhVk.png"  width="70%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/CeEZogh.png"  width="70%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/rRpQgeC.png"  width="70%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/Ps9ylm0.png"  width="70%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/wXbtZYl.png"  width="70%" />
</div>




### 6.1.4. Core System Tests

| ID   | TÍTULO                               | DESCRIPCIÓN                                                                                          |
|------|--------------------------------------|------------------------------------------------------------------------------------------------------|
| HU01 | Acceder a la información de la empresa | Como visitante del sitio web, deseo conocer más acerca de la empresa responsable del producto.       |
                                         
<div style="text-align: center;">
  <img src="https://imgur.com/eMNQtaE.png[/img]"  width="70%" />
</div>

| ID   | TÍTULO                             | DESCRIPCIÓN                                                                                      |
|------|------------------------------------|--------------------------------------------------------------------------------------------------|
| HU02 | Conocer los beneficios del producto | Como visitante del sitio web, deseo conocer las ventajas que ofrece el producto.                |
<div style="text-align: center;">
  <img src="https://imgur.com/zfpXGB4.png[/img]"  width="70%" />
</div>

| ID   | TÍTULO                                 | DESCRIPCIÓN                                                                                                      |
|------|----------------------------------------|------------------------------------------------------------------------------------------------------------------|
| HU03 | Consultar los planes de precios del producto | Como visitante del sitio web, deseo conocer las distintas opciones de precios disponibles para el producto.     |

<div style="text-align: center;">
  <img src="https://imgur.com/XvuhBsR.png[/img]"  width="70%" />
</div>

| ID   | TÍTULO                             | DESCRIPCIÓN                                                                                                              |
|------|------------------------------------|--------------------------------------------------------------------------------------------------------------------------|
| HU04 | Establecer contacto con la empresa | Como visitante del sitio web, deseo poder comunicarme fácilmente con la empresa directamente desde la página de inicio. |
<div style="text-align: center;">
  <img src="https://imgur.com/UjUchIX.png[/img]"  width="70%" />
</div>

| US05 | Activación de cuenta de empleado | Como empleado, deseo verificar mi cuenta para poder acceder al sistema de gestión |
| ---- | --------------------------------- | ---------------------------------------------------------------------------------- |

<div style="text-align: center;">
   <img src="https://i.imgur.com/8NvVsuw.png" alt="Landing evidence"/>
</div><br>


| US06 | Registro de cuenta para gerente | Como gerente, deseo crear mi cuenta para poder administrar al personal a mi cargo |
| ---- | ------------------------------- | --------------------------------------------------------------------------------- |

<div style="text-align: center;">
   <img src="https://i.imgur.com/iE7IrC2.png" alt="Landing evidence"/>
</div><br>


| US09 | Agregar nuevas habitaciones al sistema | Como gerente, deseo crear nuevas habitaciones en el sistema de gestión |
| ---- | -------------------------------------- | ----------------------------------------------------------------------- |

<div style="text-align: center;">
   <img src="https://i.imgur.com/bb8wsWN.png" alt="Landing evidence"/>
</div><br>


| US10 | Agregar un nuevo item al inventario | Como gestor, deseo agregar un nuevo ítem al inventario del hotel |
| ---- | ----------------------------------- | ----------------------------------------------------------------- |

<div style="text-align: center;">
   <img src="https://i.imgur.com/cfMoXhy.png" alt="Landing evidence"/>
</div><br>


| US11 | Registro de cuenta para administrador | Como administrador, quiero asegurarme de que los clientes hospedados estén registrados en el sistema para tener un control sobre las reservas. |
| ----- | ------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |

<div style="text-align: center;">
   <img src="https://i.imgur.com/0m0VoIX.png" alt="Landing evidence"/>
</div><br>

## 6.2. Static testing & Verification

La verificación estática del software permite identificar errores, malas prácticas y posibles vulnerabilidades sin necesidad de ejecutar el código. Esta etapa se centra en revisar el cumplimiento de estándares de codificación, calidad estructural y seguridad del código fuente, apoyándose en herramientas automatizadas.

### 6.2.1. Static Code Analysis

Se utilizó análisis estático de código para detectar errores comunes, duplicaciones, violaciones a las convenciones de estilo, posibles vulnerabilidades de seguridad y otros problemas que pueden afectar la mantenibilidad del proyecto.

#### 6.2.1.1. Coding standard & Code conventions.

El equipo adoptó convenciones de codificación específicas para cada tecnología usada:

- Frontend (Vue.js / JavaScript):
Se siguieron las reglas de estilo recomendadas por ESLint con el preset de AirBnB, asegurando legibilidad, consistencia y buenas prácticas.

- Backend (.NET / C#):
Se aplicaron convenciones como PascalCase para clases y métodos, camelCase para variables locales, comentarios XML para métodos públicos y separación lógica por capas.

- Mobile (Kotlin):
Se utilizaron lineamientos oficiales de Android Developers, enfocados en claridad y arquitectura limpia (MVVM).

- El análisis estático incluyó reglas personalizadas para validar la indentación, nombres de variables, complejidad ciclomática y funciones con demasiadas líneas.

#### 6.2.1.2. Code Quality & Code Security.

Para asegurar la calidad y seguridad del código se aplicaron las siguientes herramientas:

| Herramienta    | Lenguaje | Propósito principal                                                   |
| -------------- | -------- | --------------------------------------------------------------------- |
| **SonarQube**  | JS, C#   | Detección de bugs, code smells, vulnerabilidades y cobertura de tests |
| **ESLint**     | JS       | Estilo de código y errores comunes en JavaScript                      |
| **Detekt**     | Kotlin   | Análisis de calidad en código Android                                 |
| **Dependabot** | GitHub   | Verificación de dependencias inseguras                                |

**Los resultados del análisis ayudaron a identificar:**

- Duplicación de funciones en componentes frontend.

- Posibles excepciones no controladas en controladores del backend.

- Variables no utilizadas.

- Advertencias por complejidad alta en funciones específicas.

### 6.2.2. Reviews

Durante el desarrollo de Sweet Manager se llevaron a cabo revisiones periódicas entre los miembros del equipo para asegurar la calidad y coherencia del producto. Estas revisiones se centraron en:

- Revisión de código: Los Pull Requests en GitHub fueron evaluados por al menos un miembro del equipo antes de ser integrados a la rama develop. Se revisaron aspectos como estructura del código, reutilización, cumplimiento de convenciones y claridad en los comentarios.

- Revisión de diseño de interfaces: Se realizaron sesiones en Figma donde se validaron los flujos de usuario, consistencia visual y accesibilidad. Estas sesiones sirvieron para detectar botones redundantes o secciones poco intuitivas.

- Revisión de requisitos: El equipo revisó los criterios de aceptación de cada historia de usuario antes de iniciar el desarrollo, asegurando el alineamiento con los objetivos del cliente.

- Las revisiones permitieron detectar errores antes de pasar a pruebas funcionales y mejorar la colaboración entre frontend, backend y diseño.

## 6.3. Validation Interviews.

Con el objetivo de validar la experiencia del usuario y la propuesta de valor de Sweet Manager, se llevaron a cabo entrevistas de validación mostrando el Landing Page y una versión funcional de la aplicación móvil.

Estas entrevistas permitieron obtener retroalimentación directa de usuarios representativos de los tres segmentos clave, evaluar la claridad del mensaje, la facilidad de uso de la app y detectar oportunidades de mejora en la propuesta de producto.

**Segmentos entrevistados**

- Gerentes de hotel: Interesados en paneles de control, reportes financieros y toma de decisiones.

- Administradores operativos: Encargados de inventario, reservas y recursos humanos.

- Trabajadores l del hotel: Usuarios de la app móvil para registro de tareas, check-in, limpieza, etc.

**Metodología aplicada** 

- Se mostró el Landing Page desde un navegador (web) y la app desde un dispositivo móvil.

**Se realizaron preguntas de validación centradas en:**

- Claridad del mensaje del Landing Page

- Expectativas funcionales

- Facilidad de navegación

- Valor percibido del producto

- Preferencias de uso entre web y móvil

- Se registraron observaciones, reacciones y sugerencias de mejora.

### 6.3.1. Diseño de Entrevistas.

En esta sección se documentarán las preguntas que se utilizaron en nuestras entrevistas, conteniendo las preguntas generales que se comparten entre los segmentos objetivos, y las preguntas que fueron creadas específicamente para cada una.

**Preguntas generales**

- ¿Qué crees que hace esta plataforma con solo ver esta página?

- ¿Te resulta claro el propósito del producto?

- ¿Qué parte de la página te llamó más la atención?

- ¿Cambiarías algo del diseño o del contenido?

- ¿Te sentirías motivado/a a registrarte o saber más?

**Segmentos: Gerentes**

- ¿Sientes que esta plataforma te ayudaría a tener mayor control sobre las operaciones del hotel?

- ¿Qué opinas del enfoque que se le da a los reportes y panel de control?

- ¿Confías en esta solución con base solo en lo que ves?

- ¿Qué información esperas ver destacada como gerente en el Landing Page?

- ¿Te genera suficiente credibilidad para probarla o compartirla con tu equipo?

**Segmento: Administradores**

- ¿Logras identificar que la plataforma te ayudaría con la gestión diaria del hotel?

- ¿Qué parte del Landing Page te parece más útil o relevante para ti?

- ¿Crees que el diseño facilita entender lo que podrías hacer dentro del sistema?

- ¿Hay funciones que esperas ver mencionadas pero no aparecen?

- ¿La página transmite eficiencia o te deja dudas?

**Segmento: Trabajadores**

- ¿Te parece amigable la plataforma para alguien sin experiencia técnica?

- ¿Crees que podrías usar esta app en tu día a día solo viendo esta página?

- ¿Sientes que está pensada para ayudarte o más para los jefes?

 - ¿Qué dudas te surgen al ver esta página?

- ¿Qué sección te gustaría que se explique mejor?



### 6.3.2. Registro de Entrevistas.

A continuación, se registraron todas las entrevistas realizadas para nuestra solución, categorizadas según su segmento objetivo, y con un resumen que destaca las características y críticas realizadas sobre nuestro proyecto.

**Entrevista 01 (Owners)**
<br>
Nombre: CAMILA BUSTAMANTE
Edad: 25
Sexo: FEMENINO
Lugar donde vive: Miraflores - Perú
Duración de la entrevista: 00:00 - 06:00 
Ocupación: Dueña de hotel

<div style="text-align: center;">
   <img src="https://imgur.com/8y2Uu33.png" alt="Camila Bustamante Interview" width="80%" />
 </div><br>

URL VIDEO: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u202212383_upc_edu_pe/ES-LwF5Abv5JnminNe-j8z8BQG_C22-NOPPYz_W2hVsS3w?e=02ITEa&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D>

RESUMEN: Camila se mostró comprometida con la mejora constante de su hotel. Destacó la importancia de contar con herramientas digitales que le permitan gestionar reservas, habitaciones y personal de manera más eficiente. Apreció la posibilidad de automatizar procesos que normalmente le demandan mucho tiempo, lo que le permitiría enfocarse más en la experiencia del cliente.


**Entrevista 02 (Owners)**

<br>
Nombre: Sergio Renard <br>
Edad: 21 <br>
Sexo: Masculino <br>
Lugar donde vive: La Plata - Argentina <br>
Ocupación: Dueño de hotel <br>
Duración de la entrevista: 06:00 - 12:00 <br>
Personalidad: Alegre <br>

<div style="text-align: center;">
   <img src="https://i.imgur.com/SPB9KYm.png" alt="Sergio Renard  Interview" width="80%" />
 </div><br>

URL VIDEO: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u202212383_upc_edu_pe/ES-LwF5Abv5JnminNe-j8z8BQG_C22-NOPPYz_W2hVsS3w?e=02ITEa&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D>

RESUMEN: Sergio se mostró entusiasta respecto al uso de tecnologías en la administración hotelera. Valora soluciones simples pero funcionales que ayuden a mantener el orden y mejorar la comunicación con los clientes. Mencionó estar abierto a herramientas que optimicen su operación diaria y contribuyan al crecimiento de su negocio.


**Entrevista 03 (Owners)**
<br>
Nombre:  <br>
Edad:  <br>
Sexo:  <br>
Lugar donde vive:     <br>
Ocupación: Dueño de hotel <br>
Duración de la entrevista: 00:00 - 00:00 <br>
Personalidad: <br>

<div style="text-align: center;">
   <img src="" alt="  Interview" width="80%" />
 </div><br>

 URL VIDEO: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u202212383_upc_edu_pe/ES-LwF5Abv5JnminNe-j8z8BQG_C22-NOPPYz_W2hVsS3w?e=02ITEa&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D>


**Entrevista 01 (Admins)**
<br>
Nombre: Juan Reyes  <br>
Edad:  21 <br>
Sexo:  Masculino <br>
Lugar donde vive:    Lima <br>
Ocupación:    Administrador de Hotel<br>
Duración de la entrevista: 12:00 - 16:30 <br>
Personalidad: <br>

<div style="text-align: center;">
   <img src="https://i.imgur.com/deel97A.png" alt="Juan Reyes Interview" width="80%" />
 </div><br>

 URL VIDEO: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u202212383_upc_edu_pe/ES-LwF5Abv5JnminNe-j8z8BQG_C22-NOPPYz_W2hVsS3w?e=02ITEa&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D>

RESUMEN: Juan resaltó la necesidad de una plataforma centralizada para manejar tanto la información de los huéspedes como la asignación de habitaciones. Mostró una actitud receptiva hacia soluciones tecnológicas que le faciliten la coordinación con otros miembros del equipo y reduzcan los errores en los registros.


**Entrevista 02 (Admins)**

<br>
Nombre: Manuel Chavez  <br>
Edad: 21 <br>
Sexo: Masculino <br>
Lugar donde vive:  Lima   <br>
Ocupación:    Administrador de Hotel<br>
Duración de la entrevista: 16:30 - 31:35 <br>
Personalidad: <br>

<div style="text-align: center;">
   <img src="https://i.imgur.com/VALCtTP.png" alt="Manuel Chavez Interview" width="80%" />
 </div><br>

URL VIDEO: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u202212383_upc_edu_pe/ES-LwF5Abv5JnminNe-j8z8BQG_C22-NOPPYz_W2hVsS3w?e=02ITEa&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D>

RESUMEN: Manuel expresó interés en contar con una interfaz clara y funcional para el control de las operaciones diarias del hotel. Subrayó la importancia de que el sistema sea intuitivo, especialmente para el nuevo personal. Su enfoque estuvo en la eficiencia y en el seguimiento de las tareas administrativas y de mantenimiento.



**Entrevista 03 (Admins)**

<br>
Nombre: Sebastian Silva  <br>
Edad: 25   <br>
Sexo: masculino  <br>
Lugar donde vive: San Luis     <br>
Ocupación: Administrador de Hotel<br>
Duración de la entrevista: 00:00 - 07:08 <br>
Personalidad: <br>

<div style="text-align: center;">
   <img src="https://i.imgur.com/wfr536z.png" alt="  Interview" width="80%" />
 </div><br>

URL VIDEO: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u202125968_upc_edu_pe/EcMhtW1zJ7FLhwn8Ll8bpdIB1ERaDVo7NOitzRnK9Mz3LQ?e=Bcau9L&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D>

RESUMEN: Sebastian Silva, administrador de hotele, ofrece su opinión sobre la Landing Page y la aplicación móvil RoomWise. Menciona que la Landing Page proporciona una descripción clara del producto, beneficios, misión, visión y planes de suscripción, y que la sección de empresas registradas y contacto son útiles.

En relación con la app RoomWise, destaca que permite a los administradores gestionar clientes, proveedores, inventarios y cuartos, y valora la funcionalidad de mensajería interna y reportes. Según su opinión, la plataforma facilita la gestión diaria del hotel, especialmente al proporcionar información en tiempo real sobre clientes e inventarios.

Sin embargo, sugiere mejorar el botón de activar/desactivar inventarios y propone la incorporación de una función de mensajería más ágil para la comunicación entre los trabajadores. En general, considera que el diseño es intuitivo y fácil de usar.

**Entrevista 04 (Trabajadores)**
<br>
Nombre: Jesús Pérez
Edad: 23 <br>
Sexo: Masculino <br>
Lugar donde vive: Cercado de Lima, Lima, Perú <br>
Ocupación: Recepcionista de hotel <br>
Duración de la entrevista: 05:27 minutos <br>
Personalidad: Proactivo y receptivo a nuevas tecnologías <br>
Minuto de la entrevista:<br>
URL VIDEO: 

<div style="text-align: center;">
   <img src="https://i.imgur.com/cGcK4GJ.png" alt="Jesus Pérez Interview"/>
</div><br>

Jesús Pérez es recepcionista en un hotel de Cercado de Lima. Identifica como tareas más tediosas la actualización manual del inventario de habitaciones y la coordinación con limpieza, especialmente en eventos grandes. Jesús se mostró proactivo durante toda la entrevista, nos comenta que le gustó la plataforma, le pareción interactiva y muy cómoda a nivel visual, le gusta que se puedan gestionar los proveedores, trabajadores, notificaciones e inventario. Se muestra contento al visualizar las recomendaciones que en su momento propuso en la primera entrevista: gestión en base a tableros y control de inventarios.

### 6.3.3. Evaluaciones según heurísticas

A continuación se presentan las evaluaciones aplicadas a partir de los problemas encontrados en el sistema de gestión de proyectos ágiles.

#### 1. Heurística: Prevención de errores

* **Descripción de la heurística:** Diseñar de modo que evite situaciones propensas a errores o proporcione información clara para su resolución.
* **Observaciones:** 
  * Los usuarios experimentan confusión al acceder a rutas inexistentes sin retroalimentación del sistema.
  * El sistema no maneja adecuadamente las páginas no encontradas, generando una experiencia poco profesional.
* **Evidencia:**
  * Los usuarios pueden encontrar pantallas en blanco o errores del navegador al acceder a URLs incorrectas.
  * La ausencia de manejo de errores 404 genera sensación de fallo del sistema.
* **Nivel de severidad:** 4 (Crítico)
* **Recomendaciones:**
  * Implementar una ruta catch-all (*) que redirija a una página de error 404 informativa.
  * Incluir mensaje claro con botón de navegación para volver al inicio o dashboard.

#### 2. Heurística: Control y libertad del usuario

* **Descripción de la heurística:** Los usuarios necesitan sentir que controlan el sistema y pueden navegar libremente.
* **Observaciones:**
  * El logo de la plataforma no funciona como elemento de navegación.
  * Los usuarios esperan poder regresar al inicio haciendo clic en el logo según convenciones web.
* **Evidencia:**
  * Los usuarios intentan hacer clic en el logo esperando regresar a la página principal.
  * La falta de esta funcionalidad reduce la eficiencia de navegación.
* **Nivel de severidad:** 3 (Alto)
* **Recomendaciones:**
  * Habilitar el logo como enlace interactivo que redirija a la página principal.
  * Añadir cursor pointer y efecto hover para indicar interactividad.

#### 3. Heurística: Diagnóstico y recuperación de errores

* **Descripción de la heurística:** Los mensajes de error deben expresarse en lenguaje sencillo, indicar el problema y sugerir soluciones.
* **Observaciones:**
  * Al agregar nuevos miembros, el sistema no proporciona retroalimentación específica sobre errores.
  * Los usuarios no pueden identificar qué información es incorrecta o faltante.
* **Evidencia:**
  * Los usuarios reportan frustración al no saber por qué falla el proceso de agregar miembros.
  * La ausencia de mensajes específicos impide la corrección efectiva de errores.
* **Nivel de severidad:** 4 (Crítico)
* **Recomendaciones:**
  * Implementar validaciones en tiempo real con mensajes específicos de error.
  * Mostrar mensajes como "El correo ya está registrado" o "Complete todos los campos obligatorios".

#### 4. Heurística: Flexibilidad y eficiencia de uso

* **Descripción de la heurística:** El sistema debe permitir adaptar flujos a las necesidades del usuario y acelerar tareas frecuentes.
* **Observaciones:**
  * Una vez creado un sprint, no existe opción para modificar su información.
  * Los usuarios deben eliminar y recrear sprints para hacer cambios, reduciendo la eficiencia.
* **Evidencia:**
  * Los usuarios expresan la necesidad de editar sprints existentes para ajustar fechas o información.
  * La falta de flexibilidad no se adapta a las necesidades de entornos ágiles donde los cambios son frecuentes.
* **Nivel de severidad:** 3 (Alto)
* **Recomendaciones:**
  * Añadir funcionalidad de edición accesible desde la vista de sprint.
  * Permitir modificación de campos relevantes manteniendo la integridad de datos.

#### 5. Heurística: Consistencia y estándares

* **Descripción de la heurística:** La interfaz debe seguir patrones reconocibles y uniformes en todos sus elementos.
* **Observaciones:**
  * Algunos elementos de la interfaz no siguen las convenciones web establecidas.
  * La falta de consistencia en comportamientos esperados puede confundir a los usuarios.
* **Evidencia:**
  * El logo no cumple con el estándar de ser un elemento de navegación.
  * Los formularios no proporcionan feedback consistente en caso de errores.
* **Nivel de severidad:** 2 (Moderado)
* **Recomendaciones:**
  * Establecer un sistema de diseño que defina comportamientos estándar.
  * Documentar y aplicar consistentemente patrones de interacción en toda la aplicación.

## 6.4. Auditoría de Experiencias de Usuario.

### 6.4.1. Auditoría realizada.

#### 6.4.1.1. Información del grupo auditado.

| Member | Roles |
|--------|--------|
| Joaquín Alonso Carbajal Pozzo | Developer |
| Joaquin David Rivadeneyra Ramos | Developer |
| Nelson Elías Serrano Ircañaupa | Scrum Master |
| Sergio André Gómez Vallejos | Developer |
| Diego Miguel Ramirez Ortega | Product Owner |
| Josue Omar Hidalgo Bustamante | Developer |

#### 6.4.1.2. Cronograma de auditoría realizada.

| Fase | Actividades | Fecha Inicio | Fecha Fin | Responsable |
|------|-------------|--------------|-----------|-------------|
| Recepción | • Solicitud formal de auditoría<br>• Recopilación de documentación<br>• Acceso a sistemas/producto | 16/05/2025 | 20/05/2025 | Omar Morales |
| Planificación | • Revisión de requisitos<br>• Definición de heurísticas<br>• Elaboración de checklist | 23/05/2025 | 27/05/2025 | Omar Morales |
| Ejecución | • Evaluación heurística<br>• Pruebas de usabilidad<br>• Análisis de accesibilidad<br>• Registro de os | 01/06/2025 | 03/06/2025 | Omar Morales |
| Reporte | • Redacción de informe<br>• Diseño de recomendaciones<br>• Revisión final | 04/06/2025 | 10/06/2025 | Omar Morales |

#### 6.4.1.3. Contenido de auditoría realizada.

TAREAS A EVALUAR

El alcance de esta evaluación incluye la revisión de la usabilidad de las siguientes tareas:

- Registro de un usuario nuevo
- Edición de perfil
- Navegación en la interfaz
- Visualización de proyectos
- Creación de proyectos
- Validación de formularios
- Interacción con botones
- Responsive design

__Escala de severidad__

| Nivel | Descripción |
|-------|-------------|
| 1 | Problema superficial: puede ser fácilmente superado por el usuario o ocurre con muy poca frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo. |
| 2 | Problema menor: ocurre con mayor frecuencia o es un poco más difícil de superar para el usuario. Prioridad baja para su corrección. |
| 3 | Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlo. Prioridad alta para su corrección. |
| 4 | Problema muy grave: error de gran impacto que impide al usuario continuar. Debe ser corregido antes del lanzamiento. |

__Tabla resumen__


| # | Problema | Escala de severidad | Heurística/Principio violado |
|---|----------|-------------------|---------------------------|
| 1 | No hay una ruta base para manejar páginas no encontradas | 4 | Usability: Prevención de errores |
| 2 | El logo no redirige a la página principal | 3 | Usability: Control y libertad del usuario |
| 3 | No se muestra el motivo del fallo al agregar un nuevo miembro | 4 | Usability: Diagnóstico y recuperación de errores |
| 4 | No existe una opción para editar un sprint existente | 3 | Usability: Flexibilidad y eficiencia de uso |

__Descripción de problemas__

No hay una ruta base para manejar páginas no encontradas. (nivel – 4)
Heurística violada: Prevención de errores y ayuda al usuario.
Actualmente, cuando los usuarios acceden a una ruta incorrecta o inexistente, el sistema no redirige a una página de error personalizada. Esto puede causar confusión, sensación de fallo y una experiencia poco profesional.
Recomendación: Implementar una ruta base de tipo catch-all (*) que redirija a una página de error 404 informativa. Esta debe incluir un mensaje claro, un botón para volver al inicio y mantener el diseño visual de la plataforma.

<div style="text-align: center;">
   <img src="https://i.imgur.com/9xtxmOD.png" alt="Landing evidence"  width="80%" />
</div><br>


El logo no redirige a la página principal. (nivel – 3)
Heurística violada: Control y libertad del usuario.
Actualmente, al hacer clic en el logo de la plataforma, no se realiza ninguna acción o no se redirige al usuario a la página principal. Esto va en contra del comportamiento esperado por los estándares de usabilidad web, donde el logo funciona como un acceso rápido a la pantalla de inicio.
Recomendación: Habilitar el logo como un enlace interactivo que redirija automáticamente al usuario a la página principal del sistema o al dashboard correspondiente según su rol.

<div style="text-align: center;">
   <img src="https://i.imgur.com/wXaB3fQ.png" alt="Landing evidence"  width="80%" />
</div><br>

No se muestra el motivo del fallo al agregar un nuevo miembro. (nivel – 4)
Heurística violada: Diagnóstico y recuperación de errores.
Actualmente, al intentar agregar un nuevo miembro, el sistema no indica la causa del error. Esto incluye situaciones como campos inválidos, usuario ya existente o fallos de red. La falta de retroalimentación clara impide que el usuario entienda qué debe corregir y dificulta completar la acción.
Recomendación: Implementar validaciones visibles tanto en el frontend como en el backend. Mostrar mensajes de error específicos como “El correo ya está registrado” o “Debe completar todos los campos obligatorios” para guiar al usuario de forma efectiva durante el proceso.

<div style="text-align: center;">
   <img src="https://i.imgur.com/YntXaid.png" alt="Landing evidence"  width="80%" />
</div><br>

No existe una opción para editar un sprint existente. (nivel – 3)
Heurística violada: Flexibilidad y eficiencia de uso.
Actualmente, una vez creado un sprint, no se ofrece ninguna opción en la interfaz para modificar su información (como nombre, fechas o tareas asociadas). Esto limita la capacidad del usuario para corregir errores o ajustar la planificación, lo cual es común en entornos ágiles.
Recomendación: Añadir una funcionalidad que permita editar los detalles del sprint. Esta opción debe ser fácilmente accesible desde la vista de resumen del sprint o en su detalle, permitiendo actualizar campos relevantes sin necesidad de eliminar y volver a crear el sprint

<div style="text-align: center;">
   <img src="https://i.imgur.com/6hvbMs5.png" alt="Landing evidence"  width="80%" />
</div><br>


### 6.4.2. Auditoría recibida.

#### 6.4.2.1. Información del grupo auditor.

| Member | Roles |
|--------|--------|
| Joaquín Alonso Carbajal Pozzo | Developer |
| Joaquin David Rivadeneyra Ramos | Developer |
| Nelson Elías Serrano Ircañaupa | Scrum Master |
| Sergio André Gómez Vallejos | Developer |
| Diego Miguel Ramirez Ortega | Product Owner |
| Josue Omar Hidalgo Bustamante | Developer |

#### 6.4.2.2. Cronograma de auditoría recibida.

| Fase | Actividades | Fecha Inicio | Fecha Fin | Responsable |
|------|-------------|--------------|-----------|-------------|
| Recepción | • Solicitud formal de auditoría<br>• Recopilación de documentación<br>• Acceso a sistemas/producto | 16/05/2025 | 20/05/2025 | Diego Ramirez |
| Planificación | • Revisión de requisitos<br>• Definición de heurísticas<br>• Elaboración de checklist | 23/05/2025 | 27/05/2025 | Diego Ramirez |
| Ejecución | • Evaluación heurística<br>• Pruebas de usabilidad<br>• Análisis de accesibilidad<br>• Registro de os | 01/06/2025 | 03/06/2025 | Diego Ramirez |
| Reporte | • Redacción de informe<br>• Diseño de recomendaciones<br>• Revisión final | 04/06/2025 | 10/06/2025 | Diego Ramirez |

#### 6.4.2.3. Contenido de auditoría recibida.

TAREAS A EVALUAR

El alcance de esta evaluación incluye la revisión de la usabilidad de las siguientes tareas:

- Registro de un usuario nuevo
- Edición de perfil
- Navegación en la interfaz
- Visualización de proyectos
- Creación de proyectos
- Validación de formularios
- Interacción con botones
- Responsive design

__Escala de severidad__

| Nivel | Descripción |
|-------|-------------|
| 1 | Problema superficial: puede ser fácilmente superado por el usuario o ocurre con muy poca frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo. |
| 2 | Problema menor: ocurre con mayor frecuencia o es un poco más difícil de superar para el usuario. Prioridad baja para su corrección. |
| 3 | Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlo. Prioridad alta para su corrección. |
| 4 | Problema muy grave: error de gran impacto que impide al usuario continuar. Debe ser corregido antes del lanzamiento. |

__Tabla resumen__


# TABLA RESUMEN

| # | Problema | Escala de severidad | Heurística/Principio violado |
|---|----------|-------------------|---------------------------|
| 1 | El aforo de las habitaciones no tiene un campo dedicado y se oculta en la descripción | 4 | Usability: Consistencia y estándares |
| 2 | Falta un botón específico para regresar a la vista anterior en "Agregar" | 4 | Usability: Control y libertad del usuario |
| 3 | Mensaje de error confuso al crear un trabajador | 5 | Usability: Diagnóstico y recuperación de errores |

__Descripción de problemas__

El aforo de las habitaciones no tiene un campo dedicado y se oculta en la descripción. (nivel – 4)
Heuristica violada: Consistencia y estándares.
Actualmente, los owners deben escribir el aforo manualmente en la descripción, lo que genera inconsistencia en el formato. Dificulta la validación automática y rompe con los estándares de plataformas similares
Recomendación: Añadir un campo numérico obligatorio etiquetado como "Aforo máximo"

<div style="text-align: center;">
   <img src="https://i.imgur.com/ItS4TZe.png" alt="Landing evidence"  width="80%" />
</div><br>

Falta un botón específico para regresar a la vista anterior en "Agregar” (4)
Heurística violada: Control y libertad del usuario
Descripción del problema: Solo existe un botón que regresa a la pantalla principal, lo que obliga al usuario a perder el contexto de su flujo de trabajo (ej: si estaba editando múltiples habitaciones) y navegar manualmente desde el inicio para continuar tareas relacionadas, aumentando la fricción.
Recomendación: Incluir un botón para regresar a la pantalla anterior a “Agregar”  

<div style="text-align: center;">
   <img src="https://i.imgur.com/V25qh3p.png" alt="Landing evidence"  width="80%" />
</div><br>

Mensaje de error confuso al crear un trabajador. 5
Heurística violada: Ayuda al usuario a reconocer, diagnosticar y recuperarse de errores (Heurística #9 de Nielsen)
Descripción del problema:
El mensaje de error muestra códigos técnicos irrelevantes para el usuario final. Además, no indica claramente qué campo falló ni cómo corregirlo.
Recomendación: Mostrar un mensaje simple y entendible para el usuario

<div style="text-align: center;">
   <img src="https://i.imgur.com/5VdyqrE.png" alt="Landing evidence"  width="80%" />
</div><br>

##### 6.4.2.4. Resumen de Modificaciones para Subsanar Hallazgos

###### Resumen de Modificaciones Prioritarias

###### Problemas Críticos (Severidad 5)

| # | Problema | Solución Propuesta | Heurística Afectada |
|---|----------|-------------------|-------------------|
| 1 | Mensaje de error confuso al crear un trabajador | Mostrar mensajes simples y entendibles para el usuario | Diagnóstico de errores |

###### Problemas Críticos (Severidad 4)

| # | Problema | Solución Propuesta | Heurística Afectada |
|---|----------|-------------------|-------------------|
| 1 | El aforo de las habitaciones no tiene un campo dedicado | Añadir un campo numérico obligatorio etiquetado como "Aforo máximo" | Consistencia y estándares |
| 2 | Falta un botón específico para regresar a la vista anterior en "Agregar" | Incluir un botón para regresar a la pantalla anterior a "Agregar" | Control y libertad
# Capítulo VII:  DevOps Practices

## 7.1 Continous Integration

### 7.1.1. Tools and Practices

En el ámbito del desarrollo y pruebas de software, es esencial contar con herramientas y métodos que aseguren tanto la calidad del código como la productividad del equipo. En nuestro proceso de trabajo, empleamos una variedad de herramientas que optimizan tanto la creación como la validación de la funcionalidad y el comportamiento previsto de la aplicación. Estas herramientas abarcan distintas fases del ciclo de vida del software, desde la escritura del código hasta la ejecución de pruebas y la automatización de tareas.

Seguimos las metodologías de **Desarrollo Orientado por Comportamiento (BDD)** y **Desarrollo Orientado por Pruebas (TDD)** para asegurar que nuestras soluciones no solo cumplan con los requerimientos del cliente, sino que también mantengan altos niveles de calidad técnica. Algunas de las herramientas principales que utilizamos son:

| Herramienta | Tipo                         | Descripción                                                                                         | Propósito                                                                                   |
|-------------|------------------------------|-----------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------|
| **NUnit**   | Herramienta para pruebas (TDD) | Es un framework para pruebas en .NET que permite probar unidades individuales del código.           | Facilita la creación y ejecución de pruebas automatizadas para validar el comportamiento del código. |
| **Moq**     | Herramienta de simulaciones (TDD) | Permite crear objetos simulados (mocks) de dependencias para pruebas unitarias en .NET.             | Simula el comportamiento de objetos externos para facilitar pruebas aisladas.              |
| **Cucumber**| Herramienta de BDD             | Ayuda a desarrollar programas centrándose en el comportamiento, usando un lenguaje simple (Gherkin). | Permite definir y verificar escenarios de uso reales, alineando el desarrollo con los requerimientos del negocio. |

### 7.1.2. Build & Test Suite Pipeline Components

<div style="text-align: center;">
   <img src="https://i.imgur.com/2VIntro.png" alt="Landing evidence"  width="80%" />
</div><br>

## 7.2 Continous Delivery

Su propósito es automatizar tanto la integración como las pruebas del código, garantizando que todo esté preparado para su implementación en cualquier momento.

### 7.2.1. Tools and Practices

__Tools:__

- Utilizamos **GitHub** como repositorio principal para gestionar el código fuente y coordinar el flujo de deployment.
- Usamos **Selenium** para ejecutar pruebas automatizadas end-to-end en cada stage antes del deployment, validando funcionalidades críticas como autenticación, gestión de habitaciones e inventario. Esto nos permite mantener un control estricto sobre la calidad del código que se despliega.
- Integramos **Jira** para gestionar las tareas de desarrollo y el proceso de aprobación del despliegue. Después de validar el pipeline, un administrador o gerente de proyecto puede revisar y aprobar manualmente el paso a producción, asegurando una supervisión clara del proceso.

__Practices:__

- **Despliegue automático a staging y producción:**  
  Cada vez que se realiza un cambio en la rama `main` y supera todas las pruebas con éxito, Render se encarga de desplegar automáticamente la aplicación. Esto garantiza que la versión más reciente esté siempre activa y disponible. Render monitorea continuamente el repositorio y lanza el despliegue en cuanto detecta nuevas actualizaciones.

- **Control de calidad antes del despliegue:**  
  Aunque el despliegue está automatizado, este no se ejecuta si alguna prueba falla. De esta manera, se asegura que solo el código que ha sido validado correctamente llegue al entorno de producción, preservando la estabilidad y confiabilidad del sistema.


<div style="text-align: center;">
   <img src="https://i.imgur.com/IyxGRVq.png" alt="Landing evidence"  width="80%" />
</div><br>


### 7.2.2. Stages Deployment Pipeline Components

- **Integración Continua (CI):**  
  Cada vez que se realiza un commit en una rama de desarrollo, el pipeline inicia automáticamente una serie de pruebas para verificar que la aplicación esté en condiciones óptimas para ser desplegada. Esto asegura que el código se mantenga en un estado funcional y listo para producción.

- **Validación en entorno de Staging:**  
  Antes de avanzar al entorno productivo, el código se valida en un entorno de *staging*, donde se recrean condiciones similares a las de producción. En esta etapa se pueden ejecutar pruebas adicionales como pruebas manuales, de carga o de seguridad, con el fin de detectar posibles problemas antes del despliegue definitivo.

- **Despliegue con aprobación manual:**  
  Aunque el pipeline puede preparar automáticamente el código para su despliegue, el paso final hacia producción requiere la autorización de un responsable. Esta validación manual permite mayor control y evita que cambios no verificados lleguen a los usuarios finales.

- **Monitoreo y retroalimentación:**  
  El pipeline incorpora herramientas de monitoreo y análisis para observar el impacto del nuevo código en el rendimiento del sistema. Esto permite detectar posibles problemas de manera temprana y realizar ajustes antes del despliegue total.

- **Confirmación del despliegue:**  
  En este punto del pipeline, el proceso queda pausado a la espera de que un desarrollador, administrador o miembro del equipo de operaciones apruebe el despliegue a producción. Esta etapa es crucial para validar que todos los criterios han sido cumplidos antes de liberar la versión final.

## 7.3 Continous Deployment

El propósito del Continuous Deployment (CD) es asegurar que los cambios en el código que hayan sido validados se desplieguen automáticamente desde el entorno de desarrollo hasta producción. Esto permite que cada nueva versión se libere sin necesidad de intervención humana, siempre que supere todas las pruebas establecidas en el pipeline.


### 7.3.1. Tools and Practices
El proceso de despliegue continuo en **Sweet Manager** se sustenta en una serie de herramientas modernas que permiten automatizar y simplificar el flujo de trabajo del sistema. Cada una de estas herramientas está integrada dentro del pipeline CI/CD y cumple un rol definido para asegurar un despliegue eficiente y confiable.

### `Vercel` (Frontend - Vue.js)

- **Función:**  
  Vercel es la plataforma encargada del despliegue automático del frontend de Sweet Manager, desarrollado en Vue.js. Cada vez que se realiza un commit en la rama `main` o se fusiona un *pull request* exitoso, Vercel reconstruye y publica la aplicación.

- **Automatización:**  
  Vercel gestiona el proceso completo de construcción del frontend. Una vez subido el nuevo código, la aplicación se actualiza automáticamente en producción, sin requerir pasos manuales por parte del equipo de desarrollo.

### `Render` (Backend - `ASP.NET Core`)

- **Función:**  
  Render gestiona el despliegue del backend de Sweet Manager, desarrollado en `ASP.NET Core`. Esta plataforma garantiza que los servicios del backend estén siempre disponibles y actualizados en el entorno de producción.

- **Automatización:**  
  Render está configurado para detectar cambios en el repositorio del backend y realizar un despliegue automático. El proceso incluye la construcción del servicio y su despliegue directo al entorno productivo.

### `Railway` (Base de Datos - MySQL)

- **Función:**  
  Railway administra la base de datos MySQL que da soporte a la aplicación. Asegura que los datos estén siempre alineados con las versiones actuales del sistema.

- **Automatización:**  
  Railway se integra con el entorno backend y permite que cualquier cambio en la estructura de la base de datos se aplique automáticamente durante el despliegue. Esto garantiza que el esquema de datos esté sincronizado en todo momento con la lógica de la aplicación.

### 7.3.2. Production Deployment Pipeline Components


El pipeline de despliegue continuo de **Sweet Manager** se compone de distintas etapas clave, cada una respaldada por herramientas especializadas que automatizan y controlan el flujo de entrega en producción.

### Despliegue del Frontend con Vercel

- **Herramienta:** `Vercel`
- **Funcionamiento:**  
  Cada vez que se detecta una modificación en la rama `main` del repositorio frontend, Vercel ejecuta automáticamente el proceso de construcción del proyecto y despliega la versión actualizada en producción.
- **Características:**  
  Vercel facilita la entrega continua del frontend al encargarse del proceso de *build*, gestión de caché, distribución mediante CDN y protección del entorno mediante HTTPS.

  <div style="text-align: center;">
  <img src="https://i.imgur.com/WqHxiID.png"  width="70%" />
  </div>


### Despliegue del Backend con Render

- **Herramienta:** `Render`
- **Funcionamiento:**  
  Cuando se realiza un *push* a la rama `main` del repositorio backend, Render inicia la construcción del proyecto `ASP.NET Core` y, una vez finalizada, despliega la nueva versión directamente en el entorno productivo.
- **Características:**  
  Render automatiza el despliegue del backend, proporciona monitoreo de servicios, escalabilidad y asegura que la API de Sweet Manager esté disponible de forma constante.
 
<div style="text-align: center;">
  <img src="https://i.imgur.com/PF02C6H.jpeg[/img]"  width="70%" />
</div>

### Gestión de la Base de Datos con Railway

- **Herramienta:** `Railway`
- **Funcionamiento:**  
  Railway se integra al pipeline para administrar la base de datos MySQL que respalda a Sweet Manager. En cada despliegue del backend, Railway garantiza que los cambios en la estructura de datos (como migraciones o ajustes de esquema) se apliquen correctamente y estén sincronizados.
- **Características:**  
  Railway permite una gestión ágil y automatizada de la base de datos, asegurando disponibilidad, compatibilidad y facilidad para escalar o ajustar la infraestructura de datos cuando sea necesario.

<div style="text-align: center;">
  <img src="https://i.imgur.com/bZD5MKW.png"  width="70%" />
</div>
  
## 7.4. Continuous Monitoring

### 7.4.1 Tools and Practices

Para implementar un sistema de monitoreo continuo eficiente en nuestra solución, se proponen las siguientes herramientas y prácticas adaptadas al stack tecnológico del proyecto (C# .NET y Vue.js):

- **App Metrics (.NET)**: Biblioteca para exponer métricas de rendimiento y uso desde el backend desarrollado en .NET. Permite registrar datos como latencia de endpoints, uso de CPU y memoria, cantidad de solicitudes, entre otros.
- **Prometheus**: Sistema de recopilación de métricas que consume los datos expuestos por el backend (por ejemplo, en `/metrics`) y los almacena para posterior análisis.
- **Grafana**: Herramienta de visualización que se integra con Prometheus para generar dashboards en tiempo real con métricas relevantes del backend.
- **Google Analytics**: Utilizado para monitorear la interacción del usuario con el frontend en Vue.js, brindando información sobre navegación, tiempos de carga, tasa de rebote y comportamiento general de los usuarios.
- **Pruebas de carga (k6)**: Herramienta para simular múltiples usuarios concurrentes y analizar el rendimiento del sistema ante alta demanda.
- **Auditorías de calidad web (Lighthouse)**: Evaluación del rendimiento, accesibilidad, SEO y buenas prácticas en el frontend. Permite asegurar una experiencia de usuario óptima.

---

### 7.4.2 Monitoring Pipeline Components

El pipeline de monitoreo propuesto sigue una estructura de etapas que permiten capturar, procesar y visualizar información crítica para asegurar la salud del sistema:

1. **Recolección de métricas**: A través de App Metrics en el backend y Google Analytics en el frontend.
2. **Exposición de métricas**: El backend expone los datos en un endpoint `/metrics` compatible con Prometheus.
3. **Scraping y almacenamiento**: Prometheus consulta periódicamente el endpoint y guarda las métricas recolectadas.
4. **Visualización**: Grafana presenta las métricas en dashboards personalizables, permitiendo detectar patrones anómalos y realizar seguimiento a KPIs.
5. **Evaluación de experiencia de usuario**: Lighthouse y Google Analytics se usan para auditar la calidad de la interfaz, tiempos de carga y navegación del usuario.

<div style="display: flex; flex-wrap: wrap;">
    <img src="https://i.imgur.com/DpkmcHv.png" alt="Image" width="50%" />
    <img src="https://i.imgur.com/lUXDqIa.png" alt="Image" width="50%" />
</div>

---

### 7.4.3 Alerting Pipeline Components

La detección oportuna de fallos o comportamientos anómalos es clave. Para ello, se plantea un sistema de alertas basado en:

- **Prometheus + Alertmanager**: Se definen reglas de alerta (por ejemplo, alta latencia, aumento de errores 5xx o caída del servicio). Cuando se incumple una condición, Prometheus genera una alerta que es gestionada por Alertmanager.
- **Alertmanager**: Permite configurar rutas de notificación según tipo de alerta (crítica, advertencia, info), destinatarios y canales de comunicación.
- **Grafana Alerts**: Configuración de alertas visuales directamente desde los dashboards para facilitar la detección temprana de eventos fuera de lo normal.

Las alertas pueden incluir escalamiento automático, silenciamiento durante mantenimiento programado o reintentos automáticos.

<div style="display: flex; flex-wrap: wrap;">
    <img src="https://i.imgur.com/xgDGti7.jpeg" alt="Image" width="50%" />
    <img src="https://i.imgur.com/ztyi3U5.png" alt="Image" width="50%" />
</div>

---

### 7.4.4 Notification Pipeline Components

Para asegurar la comunicación inmediata ante cualquier problema en el sistema, el pipeline de notificaciones incluye:

- **Canales de comunicación**: Las alertas generadas por Alertmanager pueden enviarse a correo electrónico, Slack, Microsoft Teams u otras plataformas de mensajería.
- **Integración con CI/CD (GitHub Actions o Azure DevOps)**: En cada ejecución del pipeline de despliegue, se pueden configurar notificaciones automáticas al completar las etapas, indicando éxito, fallo, o problemas en pruebas.
- **Reportes automatizados**: Se pueden generar resúmenes periódicos del estado del sistema, uptime, métricas críticas y resultados de auditorías.

Este esquema garantiza que el equipo esté informado en tiempo real sobre cualquier incidente o evento relevante, lo cual permite una rápida respuesta y reduce el impacto sobre los usuarios.

<div style="display: flex; flex-wrap: wrap;">
    <img src="https://i.imgur.com/DY2eSP3.png" alt="Image" width="50%" />
    <img src="https://i.imgur.com/x5GQPfZ.jpeg" alt="Image" width="50%" />
</div>


# Capítulo VIII: Experiment-Driven Development

## 8.1. Experiment Planning
### 8.1.1. As-Is Summary.

La plataforma Sweet Manager se encuentra actualmente en una etapa de desarrollo intermedia con módulos core implementados para la gestión integral de establecimientos hoteleros. El sistema permite la supervisión de habitaciones, control de inventarios, administración del personal y coordinación con proveedores mediante interfaces web y móviles. Sin embargo, el desempeño muestra variaciones significativas, con tiempos de respuesta que frecuentemente exceden los 3.5 segundos, impactando la fluidez operativa y la experiencia del usuario final.

**Desafíos identificados:**

* **Desempeño del sistema** : La plataforma presenta ralentizaciones durante períodos de alta demanda operativa, especialmente en funciones críticas como check-in/check-out simultáneos y actualización masiva de estados de habitaciones.
* **Usabilidad** : La interfaz actual carece de personalización avanzada, y algunos usuarios reportan dificultades para adaptar el sistema a sus flujos de trabajo específicos.
* **Coherencia multiplataforma** : La aplicación no está completamente optimizada para diferentes dispositivos y roles de usuario, resultando en una experiencia inconsistente entre gerentes, administradores y trabajadores.
* **Capacidades avanzadas** : El sistema carece de características avanzadas como análisis predictivo, integración con sistemas de terceros y automatización inteligente de tareas.

**Metas de mejora:**

Para transformar Sweet Manager en una solución líder del mercado hotelero, se han definido los siguientes objetivos estratégicos:

* **Optimización técnica** : Alcanzar tiempos de respuesta inferiores a 1.5 segundos mediante refactorización de la arquitectura backend y implementación de técnicas de caching inteligente.
* **Personalización avanzada** : Desarrollar interfaces adaptativas que permitan configuraciones granulares según el tipo de establecimiento, tamaño y preferencias operativas específicas.
* **Ampliación funcional** : Incorporar módulos de inteligencia artificial, conectores con ecosistemas hoteleros populares y herramientas de automatización que reduzcan la intervención manual.
* **Arquitectura escalable** : Rediseñar la infraestructura para soportar desde boutique hotels hasta cadenas internacionales con miles de habitaciones distribuidas globalmente.

### 8.1.2. Raw Material: Assumptions, Knowledge Gaps, Ideas, Claims. 

**Assumptions:**

* **Personalización de interfaces** : Se asume que los usuarios valoran la capacidad de personalizar sus dashboards y workflows según sus roles específicos, lo que podría incrementar la satisfacción y eficiencia operativa.
* **Integración con sistemas existentes** : Se asume que la mayoría de hoteles medianos y grandes ya utilizan algún tipo de sistema PMS o contable, por lo que la capacidad de integración sería altamente valorada.
* **Automatización inteligente** : Se asume que los gerentes y administradores buscan reducir tareas manuales repetitivas mediante automatización, especialmente en áreas como asignación de habitaciones y gestión de inventario.
* **Analytics y reportes** : Se asume que los propietarios y gerentes necesitan insights más profundos sobre el rendimiento operativo para tomar decisiones estratégicas informadas.
* **Notificaciones inteligentes** : Se asume que un sistema de alertas proactivas puede prevenir problemas operativos y mejorar la respuesta ante situaciones críticas.

**Knowledge Gaps:**

* **Preferencias de integración** : Falta información específica sobre qué sistemas de terceros son más utilizados por nuestros usuarios objetivo y qué tipo de integraciones priorizan.
* **Patrones de uso** : Se requiere más datos sobre cómo los diferentes roles utilizan la aplicación durante diferentes períodos del día y temporadas del año.
* **Tolerancia al cambio** : Necesitamos entender mejor la disposición de los usuarios a adoptar nuevas funcionalidades y procesos automatizados.
* **Métricas de éxito** : Falta claridad sobre qué indicadores de rendimiento son más importantes para diferentes tipos de establecimientos hoteleros.
* **Competencia directa** : Se carece de un análisis exhaustivo sobre cómo los competidores directos están abordando problemas similares.

**Ideas:**

* **Dashboard adaptativo** : Crear dashboards que se ajusten automáticamente según el rol del usuario y las métricas más relevantes para su función.
* **Asistente virtual** : Implementar un chatbot inteligente que pueda responder preguntas comunes y guiar a los usuarios a través de procesos complejos.
* **Análisis predictivo** : Desarrollar algoritmos que puedan predecir demanda de habitaciones, necesidades de inventario y patrones de mantenimiento.
* **Modo offline** : Implementar funcionalidades básicas que funcionen sin conexión a internet para situaciones de emergencia.

**Claims:**

* **Mejora de eficiencia** : Se postula que la implementación de dashboards personalizables puede incrementar la eficiencia operativa en un 25% al reducir el tiempo necesario para acceder a información crítica.
* **Reducción de errores** : Se afirma que la automatización inteligente de tareas rutinarias puede disminuir errores operativos en un 40%, especialmente en áreas como asignación de habitaciones y control de inventario.
* **Incremento de satisfacción** : Se sostiene que las mejoras en la experiencia del usuario pueden resultar en un incremento del 30% en la satisfacción general, medida a través de encuestas de usabilidad.
* **ROI mejorado** : Se afirma que las nuevas funcionalidades pueden generar un retorno de inversión del 150% en el primer año a través de eficiencias operativas y reducción de costos.

### 8.1.3. Experiment-Ready Questions.

| Question | Confidence | Risk | Impact | Interest | Puntaje |
|----------|------------|------|---------|----------|---------|
| ¿Aumentará la productividad operativa la implementación de interfaces completamente personalizables por rol y establecimiento? | 7 - Evidencia sólida del valor de personalización en software empresarial. | 3 - Riesgo moderado por complejidad de desarrollo y testing. | 8 - Alto potencial de transformación en eficiencia diaria. | 8 - Fuerte demanda expresada por usuarios actuales. | Puntaje: 26 |
| ¿Incrementará la retención de clientes la integración nativa con ecosistemas hoteleros populares (PMS, Channel Managers, etc.)? | 8 - Demanda validada en investigación de mercado y feedback directo. | 5 - Riesgo alto debido a complejidad técnica y dependencias externas. | 9 - Impacto crítico en adopción empresarial y expansión de mercado. | 9 - Interés máximo de segmentos enterprise y mid-market. | Puntaje: 31 |
| ¿Disminuirá significativamente la incidencia de errores críticos la implementación de automatización basada en AI? | 8 - Casos de éxito documentados en industrias similares. | 4 - Riesgo medio-alto por complejidad de algoritmos y datos de entrenamiento. | 9 - Impacto transformacional en calidad operativa y costos. | 7 - Interés considerable, especialmente de gerentes operativos. | Puntaje: 28 |
| ¿Mejorará la toma de decisiones estratégicas la incorporación de analytics predictivos y dashboards ejecutivos? | 6 - Potencial comprobado pero dependiente de calidad y volumen de datos. | 6 - Riesgo elevado por complejidad algorítmica y expectativas de precisión. | 8 - Impacto sustancial en planificación y revenue optimization. | 8 - Alto interés de propietarios y directores generales. | Puntaje: 28 |
| ¿Optimizará la respuesta ante situaciones críticas un sistema de alertas predictivas y notificaciones contextuales? | 7 - Tecnologías probadas en otros sectores con resultados positivos. | 2 - Riesgo bajo, tecnología madura y bien establecida. | 7 - Impacto notable en prevención de problemas y tiempo de respuesta. | 6 - Interés moderado-alto, valorado por personal operativo. | Puntaje: 22 |

### 8.1.4. Question Backlog.

| Prioridad (1,2,3,5,8) | Pregunta |
|----------------------|----------|
| 8 | ¿Incrementará la retención de clientes la integración nativa con ecosistemas hoteleros populares (PMS, Channel Managers, etc.)? |
| 8 | ¿Disminuirá significativamente la incidencia de errores críticos la implementación de automatización basada en AI? |
| 8 | ¿Mejorará la toma de decisiones estratégicas la incorporación de analytics predictivos y dashboards ejecutivos? |
| 5 | ¿Aumentará la productividad operativa la implementación de interfaces completamente personalizables por rol y establecimiento? |
| 3 | ¿Optimizará la respuesta ante situaciones críticas un sistema de alertas predictivas y notificaciones contextuales? |ReintentarClaude puede cometer errores. Verifique las respuestas.

### 8.1.5. Experiment Cards

| **Question** | ¿Mejorará la eficiencia del housekeeping implementando un sistema digital de gestión de estados de habitaciones? |
|--------------|------------------------------------------------------------------------------------------------------------------------|
| **Why** | Actualmente los gerentes y empleados de housekeeping dependen de métodos manuales o sistemas desactualizados para consultar y modificar el estado de las habitaciones. Un sistema digital centralizado permitirá una comunicación más eficiente entre el personal y una mejor coordinación de las tareas de limpieza y mantenimiento. |
| **What** | Desarrollar una interfaz donde gerentes puedan modificar estados de habitaciones mediante botones de edición y ventanas emergentes, mientras que empleados puedan actualizar el estado de habitaciones asignadas al completar sus tareas de limpieza o mantenimiento. |
| **Hypothesis** | Se espera que, con la implementación del sistema digital de habitaciones, el tiempo de comunicación entre housekeeping se reduzca en un 40% y la precisión en el seguimiento de estados aumente en un 35%. |

| **Question** | ¿Reducirá el desabastecimiento implementando un sistema digital de gestión de inventario con alertas automáticas? |
|--------------|-------------------------------------------------------------------------------------------------------------------|
| **Why** | Los hoteles frecuentemente enfrentan problemas de desabastecimiento de suministros esenciales debido a la falta de un sistema centralizado que permita agregar, actualizar y monitorear ítems del inventario. Un sistema digital evitará la escasez de productos y optimizará la gestión de suministros. |
| **What** | Implementar un módulo que permita a los gestores agregar nuevos ítems al inventario con detalles como nombre y cantidad, actualizar información existente y recibir alertas cuando los suministros estén por agotarse. |
| **Hypothesis** | Se espera que, tras la implementación del sistema de inventario digital, los casos de desabastecimiento se reduzcan en un 50% y el tiempo dedicado a gestión manual de inventario disminuya en un 30%. |

| **Question** | ¿Aumentará la productividad del personal implementando un sistema centralizado de asignación y seguimiento de tareas? |
|--------------|------------------------------------------------------------------------------------------------------------------------|
| **Why** | La coordinación manual de tareas entre gerentes y empleados genera confusión, duplicación de esfuerzos y pérdida de tiempo. Un sistema centralizado donde se puedan crear, asignar, editar y eliminar tareas mejorará la organización del trabajo y la claridad en las responsabilidades. |
| **What** | Crear un módulo que permita a los gerentes crear nuevas tareas definiendo descripción, empleado asignado y fecha límite, editar tareas existentes, eliminar tareas no necesarias y asignar tareas a empleados específicos mediante diálogos intuitivos. |
| **Hypothesis** | Se espera que, con la implementación del sistema de gestión de tareas, la productividad del personal aumente en un 25% y el tiempo que gerentes dedican a coordinación se reduzca en un 40%. |

| **Question** | ¿Mejorará la adopción del sistema implementando interfaces diferenciadas por rol (gerente vs. empleado)? |
|--------------|----------------------------------------------------------------------------------------------------------|
| **Why** | Diferentes roles requieren acceso a funcionalidades específicas. Los gerentes necesitan capacidades completas de gestión mientras que los empleados solo requieren acceso a sus tareas asignadas. Interfaces diferenciadas por rol reducirán la complejidad y mejorarán la experiencia de usuario. |
| **What** | Desarrollar perfiles de acceso donde gerentes tengan acceso completo a gestión de habitaciones, inventario y tareas, mientras que empleados accedan únicamente a actualización de estados de habitaciones asignadas y visualización de sus tareas específicas. |
| **Hypothesis** | Se espera que, con las interfaces diferenciadas por rol, el tiempo de capacitación se reduzca en un 45% y la tasa de adopción del sistema alcance el 95% del personal en el primer mes. |

| **Question** | ¿Aumentará la conversión implementando un landing page informativo con proceso de registro simplificado? |
|--------------|----------------------------------------------------------------------------------------------------------|
| **Why** | Los visitantes necesitan comprender claramente los beneficios del producto, conocer los planes de precios y tener un proceso de registro sencillo. Un landing page bien estructurado con información clara sobre la empresa, beneficios y contacto aumentará la conversión de visitantes a usuarios registrados. |
| **What** | Desarrollar secciones de "Nosotros", beneficios del producto, planes de precios y contacto fácil desde la página principal, junto con un proceso simplificado de registro para gerentes que incluya activación automática de cuentas de empleados. |
| **Hypothesis** | Se espera que, con el landing page optimizado y proceso de registro simplificado, la tasa de conversión de visitantes a usuarios registrados aumente en un 35% y el tiempo de setup inicial se reduzca en un 50%. |

---

## 8.2. Experiment Design

### 8.2.1. Hypotheses

### Hipótesis 1: Gestión Digital de Estados de Habitaciones

| Aspecto | Descripción |
|---------|-------------|
| **Pregunta** | ¿Mejorará la eficiencia del housekeeping implementando un sistema digital de gestión de estados de habitaciones? |
| **Creencia** | Los hoteles que utilizan métodos manuales para gestionar estados de habitaciones experimentan retrasos en comunicación y errores en coordinación. Un sistema digital donde gerentes y empleados puedan consultar y modificar estados en tiempo real mejorará significativamente la eficiencia operativa del área de housekeeping. |
| **Hipótesis** | La implementación del sistema digital de gestión de habitaciones reducirá el tiempo de comunicación entre personal de housekeeping en un 40% y aumentará la precisión en el seguimiento de estados en un 35%. |
| **Hipótesis Nula** | La implementación del sistema digital de gestión de habitaciones no tendrá un impacto significativo en el tiempo de comunicación ni en la precisión del seguimiento de estados. |

### Hipótesis 2: Gestión Digital de Inventario

| Aspecto | Descripción |
|---------|-------------|
| **Pregunta** | ¿Reducirá el desabastecimiento implementando un sistema digital de gestión de inventario con capacidades de agregar y actualizar ítems? |
| **Creencia** | Los hoteles enfrentan problemas recurrentes de desabastecimiento debido a la falta de sistemas centralizados para gestionar inventario. Un sistema que permita agregar nuevos ítems con detalles específicos y actualizar información existente proporcionará mejor control sobre los suministros disponibles. |
| **Hipótesis** | La implementación del sistema digital de inventario reducirá los casos de desabastecimiento en un 50% y disminuirá el tiempo dedicado a gestión manual de inventario en un 30%. |
| **Hipótesis Nula** | La implementación del sistema digital de inventario no tendrá un efecto significativo en la reducción del desabastecimiento ni en el tiempo de gestión manual. |

### Hipótesis 3: Gestión Centralizada de Tareas

| Aspecto | Descripción |
|---------|-------------|
| **Pregunta** | ¿Aumentará la productividad implementando un sistema centralizado donde gerentes puedan crear, asignar, editar y eliminar tareas? |
| **Creencia** | La gestión manual de tareas genera confusión sobre responsabilidades y duplicación de esfuerzos. Un sistema centralizado que permita a gerentes gestionar completamente el ciclo de vida de las tareas (crear, asignar, editar, eliminar) mejorará la organización del trabajo y clarificará las responsabilidades del personal. |
| **Hipótesis** | La implementación del sistema centralizado de gestión de tareas aumentará la productividad del personal en un 25% y reducirá el tiempo de coordinación gerencial en un 40%. |
| **Hipótesis Nula** | La implementación del sistema centralizado de gestión de tareas no tendrá un impacto significativo en la productividad del personal ni en el tiempo de coordinación gerencial. |

### Hipótesis 4: Controles de Acceso por Rol

| Aspecto | Descripción |
|---------|-------------|
| **Pregunta** | ¿Mejorará la adopción del sistema implementando controles de acceso diferenciados por rol específico? |
| **Creencia** | Proporcionar acceso completo a gerentes (gestión de habitaciones, inventario y tareas) mientras se limita el acceso de empleados a sus funciones específicas (actualizar estados de habitaciones asignadas) reducirá la complejidad percibida y mejorará la experiencia de usuario para cada rol. |
| **Hipótesis** | La implementación de controles de acceso diferenciados por rol reducirá el tiempo de capacitación en un 45% y logrará una tasa de adopción del 95% del personal en el primer mes. |
| **Hipótesis Nula** | Los controles de acceso diferenciados por rol no tendrán un efecto significativo en el tiempo de capacitación ni en la tasa de adopción del sistema. |

### Hipótesis 5: Landing Page y Proceso de Registro

| Aspecto | Descripción |
|---------|-------------|
| **Pregunta** | ¿Aumentará la conversión de visitantes implementando un landing page con información clara y proceso de registro simplificado? |
| **Creencia** | Los visitantes necesitan comprender los beneficios del producto y tener un proceso de registro sin fricciones. Un landing page con secciones claras sobre la empresa, beneficios, precios y contacto, combinado con un proceso simplificado de registro para gerentes y activación automática para empleados, aumentará la conversión. |
| **Hipótesis** | La implementación del landing page optimizado y proceso de registro simplificado aumentará la tasa de conversión de visitantes a usuarios registrados en un 35% y reducirá el tiempo de setup inicial en un 50%. |
| **Hipótesis Nula** | El landing page optimizado y proceso de registro simplificado no tendrán un impacto significativo en la tasa de conversión ni en el tiempo de setup inicial. |

### 8.2.2. Measures

| **Question** | ¿Mejorará la eficiencia del housekeeping implementando un sistema digital de gestión de estados de habitaciones? |
|--------------|------------------------------------------------------------------------------------------------------------------------|
| **Measure** | Medir el tiempo promedio que toma comunicar cambios de estado entre personal de housekeeping antes y después de la implementación. Analizar la frecuencia de errores en coordinación de limpieza y mantenimiento. Evaluar el tiempo que gerentes y empleados dedican a consultar y actualizar estados de habitaciones mediante cronometraje de tareas específicas. |

| **Question** | ¿Reducirá el desabastecimiento implementando un sistema digital de gestión de inventario? |
|--------------|-------------------------------------------------------------------------------------------|
| **Measure** | Contar los casos de desabastecimiento de suministros críticos mensualmente antes y después de la implementación. Medir el tiempo que gestores dedican a tareas manuales de inventario como conteo físico y actualización de registros. Analizar la precisión en el control de stock comparando registros del sistema con inventario físico real. |

| **Question** | ¿Aumentará la productividad implementando un sistema centralizado de gestión de tareas? |
|--------------|-----------------------------------------------------------------------------------------|
| **Measure** | Evaluar métricas de productividad como número de tareas completadas por empleado por día y tiempo promedio para completar tareas específicas. Medir el tiempo que gerentes dedican semanalmente a coordinación de tareas (reuniones, llamadas, seguimiento). Analizar la claridad en asignación de responsabilidades mediante encuestas al personal sobre comprensión de sus tareas asignadas. |

| **Question** | ¿Mejorará la adopción del sistema implementando controles de acceso diferenciados por rol? |
|--------------|--------------------------------------------------------------------------------------------|
| **Measure** | Medir el tiempo requerido para capacitar a gerentes y empleados en el uso del sistema mediante cronometraje de sesiones de entrenamiento. Evaluar la tasa de adopción mediante el porcentaje de personal que utiliza activamente el sistema después de períodos específicos (1 semana, 1 mes). Analizar la frecuencia de errores en el uso del sistema por tipo de usuario. |

| **Question** | ¿Aumentará la conversión implementando un landing page con información clara y proceso de registro simplificado? |
|--------------|------------------------------------------------------------------------------------------------------------------|
| **Measure** | Calcular la tasa de conversión midiendo el porcentaje de visitantes únicos que completan el proceso de registro como gerentes. Medir el tiempo promedio que toman los gerentes en completar el proceso de registro desde el inicio hasta acceder al panel principal. Analizar el engagement en el landing page mediante métricas como tiempo en página, páginas vistas por sesión y tasa de rebote en las secciones de información. |

### 8.2.3. Conditions

| Question | ¿Mejorará la eficiencia del housekeeping implementando un sistema digital de gestión de estados de habitaciones? |
|----------|----------------------------------------------------------------------------------------------------------------|
| **Condición Experimental** | La eficiencia del housekeeping aumentará en un 40% en tiempo de comunicación y 35% en precisión de seguimiento después de implementar el sistema digital de gestión de habitaciones, medido a través del cronometraje de tareas y análisis de errores de coordinación. |
| **Condición de Control** | No habrá un aumento significativo en la eficiencia del housekeeping tras la implementación del sistema digital de gestión de habitaciones. |

| Question | ¿Reducirá el desabastecimiento implementando un sistema digital de gestión de inventario? |
|----------|-------------------------------------------------------------------------------------------|
| **Condición Experimental** | Se espera una reducción del 50% en casos de desabastecimiento y 30% en tiempo de gestión manual después de implementar el sistema digital de inventario, medido mediante conteo de casos mensuales y cronometraje de tareas. |
| **Condición de Control** | No habrá una reducción significativa en casos de desabastecimiento ni en tiempo de gestión manual tras la implementación del sistema digital de inventario. |

| Question | ¿Aumentará la productividad implementando un sistema centralizado de gestión de tareas? |
|----------|-----------------------------------------------------------------------------------------|
| **Condición Experimental** | La productividad del personal aumentará en un 25% y el tiempo de coordinación gerencial se reducirá en un 40% después de implementar el sistema centralizado de tareas, medido por número de tareas completadas y tiempo de coordinación semanal. |
| **Condición de Control** | No habrá un aumento significativo en la productividad del personal ni reducción en tiempo de coordinación gerencial tras la implementación del sistema centralizado. |

| Question | ¿Mejorará la adopción del sistema implementando controles de acceso diferenciados por rol? |
|----------|----------------------------------------------------------------------------------------------|
| **Condición Experimental** | El tiempo de capacitación se reducirá en un 45% y se alcanzará una tasa de adopción del 95% del personal en el primer mes después de implementar controles de acceso diferenciados por rol. |
| **Condición de Control** | No habrá una reducción significativa en tiempo de capacitación ni mejora en tasa de adopción tras implementar controles de acceso diferenciados. |

| Question | ¿Aumentará la conversión implementando un landing page con información clara y proceso de registro simplificado? |
|----------|-------------------------------------------------------------------------------------------------------------------|
| **Condición Experimental** | Se espera un aumento del 35% en la tasa de conversión de visitantes a usuarios registrados y una reducción del 50% en tiempo de setup inicial después de implementar el landing page optimizado. |
| **Condición de Control** | No habrá un aumento significativo en la tasa de conversión ni reducción en tiempo de setup inicial tras la implementación del landing page optimizado. |

### 8.2.4. Scale Calculations and Decisions

Este enfoque utiliza métricas para evaluar el cumplimiento de las hipótesis en Sweet Manager. Cada hipótesis se asocia con un indicador de éxito: se considera ideal cuando la métrica alcanza plenamente el objetivo, aceptable cuando está entre el mínimo y el ideal, y desfavorable si queda por debajo del mínimo, requiriendo así una revisión. Un nivel excelente se define como cuando el valor supera el ideal en un 25% o más, indicando un éxito significativo. Este enfoque permite tomar decisiones fundamentadas en métricas para validar o ajustar las hipótesis del proyecto.

| Scale Calculation | Decision Factor | Desfavorable | Aceptable | Ideal | Excelente |
|-------------------|-----------------|--------------|-----------|--------|-----------|
| Creemos que al implementar un sistema digital de gestión de habitaciones, mejoraremos la eficiencia del housekeeping reduciendo el tiempo de comunicación en un 40% y aumentando la precisión en un 35%. Sabremos que esto es cierto cuando observemos estas mejoras en las métricas de comunicación y precisión. | Implementar un sistema digital donde gerentes puedan modificar estados mediante botones de edición y empleados puedan actualizar estados de habitaciones asignadas al completar tareas. | | | X | |
| Creemos que al implementar un sistema digital de inventario, reduciremos el desabastecimiento en un 50% y el tiempo de gestión manual en un 30%. Sabremos que esto es cierto cuando observemos una reducción significativa en casos de desabastecimiento y tiempo dedicado a gestión manual. | Implementar un módulo que permita agregar nuevos ítems con detalles específicos, actualizar información existente y recibir alertas automáticas de stock bajo. | | | | X |
| Creemos que al implementar un sistema centralizado de gestión de tareas, aumentaremos la productividad del personal en un 25% y reduciremos el tiempo de coordinación gerencial en un 40%. Sabremos que esto es cierto cuando observemos mejoras en estas métricas operativas. | Crear un módulo donde gerentes puedan crear, asignar, editar y eliminar tareas con descripción, empleado asignado y fecha límite mediante diálogos intuitivos. | | X | | |
| Creemos que al implementar controles de acceso diferenciados por rol, reduciremos el tiempo de capacitación en un 45% y alcanzaremos una tasa de adopción del 95% en el primer mes. Sabremos que esto es cierto cuando observemos estas mejoras en capacitación y adopción. | Desarrollar perfiles donde gerentes tengan acceso completo a gestión mientras empleados accedan solo a funciones específicas de sus roles asignados. | | | X | |
| Creemos que al implementar un landing page optimizado con proceso de registro simplificado, aumentaremos la conversión en un 35% y reduciremos el tiempo de setup en un 50%. Sabremos que esto es cierto cuando observemos mejoras en conversión y tiempo de configuración. | Desarrollar secciones informativas claras sobre empresa, beneficios y precios, junto con proceso simplificado de registro para gerentes y activación automática para empleados. | | X | | |

### 8.2.5. Methods Selection

| Herramienta | Google Analytics | Hotjar | Mixpanel | Firebase Analytics |
|-------------|------------------|---------|-----------|-------------------|
| **Precio** | Plan gratuito/premium disponible | Basado en suscripción con plan gratuito limitado | Freemium con limitaciones en eventos | Plan gratuito con límites generosos |
| **Capacidad de Análisis** | Análisis exhaustivo de tráfico web, conversiones y comportamiento de usuarios en landing page | Análisis de comportamiento de usuario con heatmaps, grabaciones de sesión y encuestas de feedback | Análisis avanzado de eventos en aplicación, funnels de conversión y retención de usuarios | Análisis de eventos de aplicación móvil y web, audiencias y rendimiento en tiempo real |
| **Sencillez** | Curva de aprendizaje moderada, interfaz familiar para marketing digital | Muy intuitivo con visualizaciones claras de comportamiento de usuario | Interfaz potente pero requiere configuración técnica de eventos | Integración sencilla con productos Google, interfaz simplificada |
| **Ventajas** | Excelente para análisis de conversión en landing page, integración con Google Ads y Search Console | Ideal para entender experiencia de usuario real mediante heatmaps y grabaciones de sesión | Perfecto para tracking de acciones específicas en aplicación como gestión de habitaciones y tareas | Análisis en tiempo real, integración nativa con plataformas de desarrollo, segmentación avanzada de usuarios |

### 8.2.6. Data Analytics: Goals, KPIs and Metrics Selection

En esta sección, se establecen los objetivos de análisis de datos y se seleccionan los indicadores clave de desempeño (KPIs) y métricas relevantes para medir el rendimiento de la plataforma Sweet Manager.Estos indicadores permiten validar el impacto del producto en el proceso de gestión 

hotelera y respaldar decisiones basadas en datos.

## Objetivos de Analítica de Datos

- Mejorar la eficiencia operativa del hotel.

- Optimizar la gestión de inventario y proveedores.

- Incrementar la satisfacción de los huéspedes.

- Aumentar la rentabilidad del negocio.

- Monitorear el comportamiento del usuario en la plataforma.

**KPIs y Métricas Seleccionadas**

| Objetivo Estratégico               | KPI                                        | Métricas Específicas                                                                     |
| :--------------------------------- | :----------------------------------------- | :--------------------------------------------------------------------------------------- |
| **Eficiencia operativa** | Tasa de uso de módulos administrativos     | % de accesos al módulo financiero, inventario y RRHH                                     |
| **Gestión de inventario y proveedores** | Tiempo medio de reposición de stock        | Días promedio entre solicitud y entrega de productos                                     |
| **Satisfacción de los huéspedes** | NPS (Net Promoter Score)                   | Valoración promedio de encuestas de satisfacción (>7: promotores)                        |
| **Rentabilidad del negocio** | Margen de ganancia mensual                 | (Ingresos - Gastos) / Ingresos * 100                                                     |
| **Uso de la plataforma** | Retención mensual de usuarios              | % de usuarios activos mensuales en comparación con el mes anterior                        |
| **Comportamiento de usuarios** | Interacciones por sesión                   | Número promedio de clics por sesión (navegación web/móvil)                               |
| **Toma de decisiones basada en datos** | Reportes generados por usuario             | Nº promedio de reportes descargados por mes por usuario                                  |

---
### 8.2.7. Web and Mobile Tracking Plan

El siguiente plan de seguimiento define los eventos clave que serán monitoreados tanto en la versión web como móvil de la plataforma Sweet Manager. El objetivo es entender mejor la interacción de los usuarios, identificar puntos de fricción y tomar decisiones basadas en evidencia para 
mejorar la experiencia del usuario.

## Herramientas de Tracking Utilizadas

- Google Analytics 4 (GA4): Para seguimiento de eventos y análisis de comportamiento.

- Firebase Analytics: Para análisis de la app móvil Android/iOS.

- Hotjar: Para mapas de calor y grabaciones de sesiones en la versión web.

- Tag Manager: Para gestión de etiquetas sin necesidad de desplegar nuevo código.


## Propuestas de Eventos y Propiedades para Captura de Datos


| Plataforma   | Evento                     | Propiedades a Capturar                       | Objetivo                                                |
| :----------- | :------------------------- | :------------------------------------------- | :------------------------------------------------------ |
| **Web** | `login_success`            | `user_id`, `role`, `device`                  | Medir el acceso exitoso y distribución de roles         |
| **Web/Mobile** | `module_opened`            | `module_name`, `timestamp`                   | Identificar los módulos más utilizados                  |
| **Web** | `inventory_update`         | `item_id`, `change_type`, `quantity`         | Analizar cambios en inventario                          |
| **Mobile** | `check_in_guest`           | `guest_id`, `room_id`, `timestamp`           | Medir eficiencia del personal en registros de entrada   |
| **Web/Mobile** | `report_generated`         | `report_type`, `user_id`, `download`         | Cuantificar el uso de reportes para toma de decisiones  |
| **Web** | `form_error`               | `form_id`, `error_type`                      | Identificar errores que impiden acciones clave          |
| **Mobile** | `push_notification_opened` | `campaign_id`, `user_id`, `open_time`        | Evaluar efectividad de comunicaciones internas          |
| **Web/Mobile** | `logout`                   | `user_id`, `session_duration`                | Medir duración media de sesiones                        |


## Conversion Funnels a Analizar

- Reserva → Confirmación → Check-in digital

- Inicio de sesión → Navegación por módulo → Generación de reporte

- Notificación → Acción en app → Satisfacción reportada (NPS)


## 8.3. Experimentation

La experimentación es una etapa fundamental para validar hipótesis de producto mediante pruebas controladas con usuarios reales.En esta fase se busca medir el impacto de funcionalidades clave, recolectar evidencia sobre su utilidad y orientar futuras mejoras con base en datos.En esta 
versión del proyecto, aún no se han desarrollado experimentos formales, pero se proyecta su ejecución en la siguiente iteración del producto para validar módulos como gestión de reservas, reportes financieros y tareas del personal.

### 8.3.1. To-Be User Stories

# User Stories (To-Be)

| **User Story ID** | **Título** | **Descripción** | **Criterios de Aceptación** | **Relacionado con (Epic ID)** |
|-------------------|------------|-----------------|----------------------------|-------------------------------|
| **US05** | Iniciar sesión en el sistema | Como usuario, quiero poder acceder a Sweet Manager utilizando mi cuenta personal. | **Given** que el usuario se encuentra en la pantalla de inicio de sesión, **When** introduce sus credenciales correctamente, **Then** puede iniciar sesión de manera exitosa Y será dirigido a su dashboard. | EP02 |
| **US06** | Registro de cuenta | Como gerente, deseo crear mi cuenta para poder administrar el hotel. | **Given** que el usuario completa el formulario de registro, **When** ingresa los datos del hotel y su información personal, **Then** se crea la cuenta correctamente Y accede al panel principal. | EP02 |
| **US08** | Gestión de trabajadores | Como administrador, deseo agregar y visualizar trabajadores del hotel. | **Given** que el usuario tiene permisos administrativos, **When** accede a la sección de trabajadores, **Then** puede agregar nuevos trabajadores Y visualizar la lista completa del personal. | EP03 |
| **US09** | Gestión de habitaciones | Como administrador, deseo agregar habitaciones y tipos de habitaciones. | **Given** que el usuario gestiona habitaciones, **When** crea nuevas habitaciones o tipos, **Then** se registran correctamente Y aparecen en la lista de habitaciones. | EP03 |
| **US11** | Gestión de inventario | Como administrador, deseo agregar suministros y crear solicitudes de inventario. | **Given** que el usuario gestiona inventario, **When** agrega suministros o crea solicitudes, **Then** se registran correctamente en el sistema de inventario. | EP03 |
| **US14** | Gestión de reservas | Como administrador, deseo crear reservas y visualizar la tabla de reservas. | **Given** que el usuario gestiona reservas, **When** crea una nueva reserva, **Then** se registra correctamente Y aparece en la tabla de reservas. | EP04 |
| **US15** | Sistema de notificaciones | Como administrador, deseo crear alertas y enviar mensajes a los usuarios. | **Given** que el usuario gestiona notificaciones, **When** crea alertas o mensajes, **Then** se envían correctamente Y los usuarios pueden visualizar sus notificaciones. | EP04 |
| **US17** | Dashboard personalizado | Como usuario, deseo visualizar un dashboard con resumen del sistema según mi rol. | **Given** que el usuario accede al dashboard, **When** la página se carga, **Then** se muestra un resumen personalizado con estadísticas relevantes para su rol (admin, worker). | EP05 |

### 8.3.2. To-Be Product Backlog

| **#ORDEN** | **USER STORY ID** | **TÍTULO** | **DESCRIPCIÓN** | **SUBTAREAS** | **STORY POINTS (1/2/3/5/8/13)** |
|------------|-------------------|------------|-----------------|---------------|--------------------------------|
| **1** | **US05** | Iniciar sesión en el sistema | Como usuario, quiero poder acceder a Sweet Manager utilizando mi cuenta personal. | **ST01:** Diseñar interfaz de login<br>**ST02:** Implementar validación de credenciales<br>**ST03:** Crear redirección a dashboard<br>**ST04:** Manejar errores de autenticación | 5 |
| **2** | **US06** | Registro de cuenta | Como gerente, deseo crear mi cuenta para poder administrar el hotel. | **ST01:** Diseñar formulario de registro<br>**ST02:** Implementar validación de datos<br>**ST03:** Crear proceso de verificación<br>**ST04:** Configurar cuenta inicial | 8 |
| **3** | **US17** | Dashboard personalizado | Como usuario, deseo visualizar un dashboard con resumen del sistema según mi rol. | **ST01:** Diseñar layout del dashboard<br>**ST02:** Implementar widgets por rol<br>**ST03:** Crear métricas en tiempo real<br>**ST04:** Optimizar rendimiento | 8 |
| **4** | **US08** | Gestión de trabajadores | Como administrador, deseo agregar y visualizar trabajadores del hotel. | **ST01:** Crear lista de trabajadores<br>**ST02:** Implementar formulario de registro<br>**ST03:** Asignar roles y permisos<br>**ST04:** Gestionar estados de empleados | 5 |
| **5** | **US09** | Gestión de habitaciones | Como administrador, deseo agregar habitaciones y tipos de habitaciones. | **ST01:** Crear catálogo de habitaciones<br>**ST02:** Implementar tipos de habitación<br>**ST03:** Gestionar estados<br>**ST04:** Configurar características | 5 |
| **6** | **US11** | Gestión de inventario | Como administrador, deseo agregar suministros y crear solicitudes de inventario. | **ST01:** Crear catálogo de suministros<br>**ST02:** Implementar solicitudes<br>**ST03:** Gestionar stock<br>**ST04:** Generar alertas de inventario | 8 |
| **7** | **US14** | Gestión de reservas | Como administrador, deseo crear reservas y visualizar la tabla de reservas. | **ST01:** Crear sistema de reservas<br>**ST02:** Implementar calendario<br>**ST03:** Gestionar disponibilidad<br>**ST04:** Procesar pagos | 8 |
| **8** | **US15** | Sistema de notificaciones | Como administrador, deseo crear alertas y enviar mensajes a los usuarios. | **ST01:** Crear sistema de alertas<br>**ST02:** Implementar envío de mensajes<br>**ST03:** Configurar tipos de notificación<br>**ST04:** Gestionar preferencias | 5 |

---

### 8.3.3. Pipeline-supported, Experiment-Driven To-Be Software Platform Lifecycle

En esta sección se presenta el ciclo de vida propuesto para el desarrollo de la plataforma digital *SweetManager*, orientado a una estrategia basada en experimentación continua y respaldada por un pipeline de integración. Este enfoque busca validar de manera iterativa las funcionalidades del producto, permitiendo mejorar su calidad, reducir el riesgo de fallos y alinear constantemente el desarrollo con las necesidades reales del usuario.

El ciclo incluye desde la planificación de los Sprint Backlogs y la implementación técnica de los distintos componentes (landing page, aplicación web, aplicación móvil y backend RESTful), hasta la validación mediante entrevistas con usuarios reales. Asimismo, se documentan los aprendizajes, resultados obtenidos, prioridades ajustadas y las actividades clave realizadas antes del lanzamiento.

Este enfoque integral no solo garantiza la entrega de un MVP funcional, sino que además proporciona evidencias claras del trabajo colaborativo, de la validación empírica de hipótesis y del aprendizaje continuo durante el proceso.

#### 8.3.3.1. To-Be Sprint Backlog

| **Sprint #** | **Sprint 3** | | | | | | |
|--------------|--------------|--|--|--|--|--|--|
| **User Story** | | **WorkItem/Task** | | | | | |
| **Id** | **Title** | **Id** | **Title** | **Description** | **Estimation (Story Points)** | **Assigned To** | **Status** |
| US01 - EP01 | Acceder a información de la empresa | T1 | Diseñar sección "Nosotros" | Crear wireframe y diseño visual de la sección de información de la empresa | 2 | Omar | To-Do |
| | | T2 | Implementar página "Nosotros" | Desarrollar la página web con información detallada de la empresa | 3 | Omar | To-Do |
| US02 - EP01 | Conocer los beneficios del producto | T3 | Diseñar sección de beneficios | Crear wireframe y diseño visual de la sección de beneficios del producto | 2 | Stanley | To-Do |
| | | T4 | Implementar página de beneficios | Desarrollar la página web con información detallada de las ventajas del producto | 3 | Stanley | To-Do |
| US03 - EP01 | Consultar planes de precios | T5 | Diseñar tabla de precios | Crear diseño visual de la tabla comparativa de planes de precios | 2 | Fernando | To-Do |
| | | T6 | Implementar página de precios | Desarrollar la página con información detallada de los diferentes planes | 3 | Fernando | To-Do |
| US04 - EP01 | Establecer contacto con la empresa | T7 | Crear formulario de contacto | Diseñar e implementar formulario de contacto con validaciones | 2 | Luiggi | To-Do |
| | | T8 | Implementar envío de mensajes | Programar funcionalidad para envío de mensajes desde el formulario | 2 | Luiggi | To-Do |
| US05 - EP02 | Iniciar sesión en el sistema | T9 | Crear interfaz de login | Diseñar e implementar pantalla de inicio de sesión | 2 | Sebastian | To-Do |
| | | T10 | Implementar autenticación | Programar validación de credenciales y redirección al dashboard | 3 | Sebastian | To-Do |
| US06 - EP02 | Registro de cuenta | T11 | Crear formulario de registro | Diseñar e implementar formulario de registro para gerentes | 3 | Jack | To-Do |
| | | T12 | Implementar creación de cuenta | Programar lógica de creación de cuenta y datos del hotel | 2 | Jack | To-Do |
| US07 - EP02 | Gestión de perfil de usuario | T13 | Crear página de perfil | Diseñar e implementar página de perfil de usuario | 2 | Omar | To-Do |
| | | T14 | Implementar actualización de datos | Programar funcionalidad para modificar información personal | 2 | Omar | To-Do |
| US08 - EP03 | Gestión de trabajadores | T15 | Crear formulario de trabajador | Diseñar e implementar formulario para agregar trabajadores | 2 | Stanley | To-Do |
| | | T16 | Implementar lista de trabajadores | Programar visualización y gestión de trabajadores del hotel | 3 | Stanley | To-Do |
| US09 - EP03 | Gestión de habitaciones | T17 | Crear formulario de habitación | Diseñar e implementar formulario para agregar habitaciones | 2 | Fernando | To-Do |
| | | T18 | Implementar gestión de habitaciones | Programar creación de habitaciones y tipos de habitaciones | 3 | Fernando | To-Do |
| US10 - EP03 | Gestión de proveedores | T19 | Crear formulario de proveedor | Diseñar e implementar formulario para registrar proveedores | 2 | Luiggi | To-Do |
| | | T20 | Implementar lista de proveedores | Programar visualización y gestión de proveedores | 2 | Luiggi | To-Do |
| US11 - EP03 | Gestión de inventario | T21 | Crear formulario de inventario | Diseñar e implementar formulario para agregar suministros | 2 | Sebastian | To-Do |
| | | T22 | Implementar solicitudes de inventario | Programar creación y gestión de solicitudes de inventario | 3 | Sebastian | To-Do |
| US12 - EP03 | Gestión de administradores | T23 | Crear formulario de administrador | Diseñar e implementar formulario para agregar administradores | 2 | Jack | To-Do |
| | | T24 | Implementar lista de administradores | Programar visualización y gestión de administradores | 2 | Jack | To-Do |
| US13 - EP03 | Gestión de información del hotel | T25 | Crear formulario de información del hotel | Diseñar e implementar formulario para datos del hotel | 2 | Omar | To-Do |
| | | T26 | Implementar visualización de información | Programar consulta y visualización de información del hotel | 2 | Omar | To-Do |
| US14 - EP04 | Gestión de reservas | T27 | Crear formulario de reserva | Diseñar e implementar formulario para crear reservas | 3 | Stanley | To-Do |
| | | T28 | Implementar tabla de reservas | Programar visualización y gestión de reservas | 2 | Stanley | To-Do |
| US15 - EP04 | Sistema de notificaciones | T29 | Crear sistema de alertas | Implementar funcionalidad para crear y enviar alertas | 3 | Fernando | To-Do |
| | | T30 | Implementar envío de mensajes | Programar funcionalidad para enviar mensajes a usuarios | 2 | Fernando | To-Do |
| US16 - EP04 | Visualizar notificaciones | T31 | Crear panel de notificaciones | Diseñar e implementar panel para visualizar notificaciones | 2 | Luiggi | To-Do |
| | | T32 | Implementar lista de notificaciones | Programar carga y visualización de notificaciones recibidas | 2 | Luiggi | To-Do |
| US17 - EP05 | Dashboard personalizado | T33 | Crear dashboard base | Diseñar e implementar estructura base del dashboard | 3 | Sebastian | To-Do |
| | | T34 | Implementar personalización por rol | Programar contenido personalizado según rol del usuario | 2 | Sebastian | To-Do |
| US18 - EP05 | Reportes estadísticos | T35 | Crear interfaz de reportes | Diseñar e implementar interfaz para visualizar reportes | 3 | Jack | To-Do |
| | | T36 | Implementar gráficos estadísticos | Programar generación de gráficos y estadísticas del hotel | 4 | Jack | To-Do |

---

#### 8.3.3.2. Implemented To-Be Landing Page Evidence

En esta parte se expone la evidencia de la implementación de la Landing Page según el modelo To-Be planteado. En esta etapa, se llevaron a cabo mejoras sustanciales en elementos esenciales como la optimización para buscadores (SEO), la velocidad de carga, la estructura semántica del contenido y la adaptabilidad a diversos dispositivos (diseño responsivo). Estos avances no solo refuerzan la presencia digital del producto, sino que también mejoran la experiencia del usuario y aumentan su visibilidad en los motores de búsqueda.

<div style="text-align: center;">
  <img src="https://i.imgur.com/Wuw4e7H.png" alt="" width="70%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/nkY4YFz.png" alt="" width="70%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/5HLiUK4.png" alt="" width="70%" />
</div>

Enlace: <https://1asi0732-2510-4433-g1-roomwise.github.io/landing-page/>

#### 8.3.3.3. Implemented To-Be Frontend-Web Application Evidence

<div style="text-align: center;">
  <img src="https://i.imgur.com/UpZNLw6.png" alt="" width="70%" />
</div>
<div style="text-align: center;">
  <img src="https://i.imgur.com/4HWK3r7.png" alt="" width="70%" />
</div>
<div style="text-align: center;">
  <img src="https://i.imgur.com/VHtiL5y.png" alt="" width="70%" />
</div>
<div style="text-align: center;">
  <img src="https://i.imgur.com/ZJYUrZY.png" alt="" width="70%" />
</div>
<div style="text-align: center;">
  <img src="https://i.imgur.com/ufKjcKU.png" alt="" width="70%" />
</div>
<div style="text-align: center;">
  <img src="https://i.imgur.com/HTH8OkQ.png" alt="" width="70%" />
</div>

#### 8.3.3.4. Implemented To-Be Native-Mobile Application Evidence
<div style="text-align: center;">
  <img src="https://i.imgur.com/PhqAq4k.png" alt="" width="40%" />
</div>
<br>
<div style="text-align: center;">
  <img src="https://i.imgur.com/ZGKWw5W.png" alt="" width="40%" />
</div>
<br>
<div style="text-align: center;">
  <img src="https://i.imgur.com/viIrOpx.png" alt="" width="40%" />
</div>


#### 8.3.3.5. Implemented To-Be RESTful API and/or Serverless Backend Evidence

<div style="text-align: center;">
  <img src="https://i.imgur.com/mbkSzQv.png" alt="" width="70%" />
</div>
<br>
<div style="text-align: center;">
  <img src="https://i.imgur.com/jjTXIEC.png" alt="" width="70%" />
</div>

#### 8.3.3.6. Team Collaboration Insights

Durante el desarrollo de los nuevos puntos a trabajar, el equipo adoptó un enfoque colaborativo y enfocado en la especialización de tareas, logrando una implementación eficiente y organizada de la plataforma.

### Flujo de trabajo

- Uso de **GitHub** con ramas por feature siguiendo el modelo **GitFlow**.
- Gestión de tareas mediante **GitHub Projects** con tableros tipo **Kanban/Scrum**.
- Validaciones y revisiones constantes a través de **Pull Requests**.

###  Comunicación

- Reuniones de sincronización por **Google meet**.
- Coordinación ágil para resolver bloqueos y alinear criterios de implementación.

### Validación y evidencias

- Cada entregable fue documentado con capturas, pruebas funcionales y evidencia en los issues de GitHub.
- Se utilizó Swagger para documentar la API y facilitar su consumo por parte del frontend y mobile.

### Contribución de los miembros del equipo en el repositorio final-project-report

<div style="text-align: center;">
  <img src="https://i.imgur.com/uoMk2F9.png" alt="" width="70%" />
</div>

### Contribución de los miembros del equipo en el repositorio web-services

<div style="text-align: center;">
  <img src="https://i.imgur.com/uAp08rZ.png" alt="" width="70%" />
</div>

### Contribución de los miembros del equipo en el repositorio landing-page

<div style="text-align: center;">
  <img src="https://i.imgur.com/ul6PbQ6.png" alt="" width="70%" />
</div>

### Contribución de los miembros del equipo en el repositorio mobile-app

<div style="text-align: center;">
  <img src="https://i.imgur.com/XHZ1bs2.png" alt="" width="70%" />
</div>

### Contribución de los miembros del equipo en el repositorio frontend

<div style="text-align: center;">
  <img src="https://i.imgur.com/O2Bwyvc.png" alt="" width="70%" />
</div>


### 8.3.4. To-Be Validation Interviews

#### 8.3.4.1. Diseño de Entrevistas.   

## Segmento 1: Gerentes (Owners)

### Landing Page

- ¿La información en la landing page fue suficiente para entender los beneficios del sistema?
- ¿Te resultó confiable el diseño y contenido del sitio para decidir registrarte?
- ¿Qué tanto influyó la presentación de funcionalidades en tu interés por probar la plataforma?
- ¿Faltó alguna información clave que te hubiera gustado ver antes de registrarte?

### Aplicación Móvil

- ¿Te resultó cómoda la experiencia de usar la app desde tu celular?
- ¿Te sentiste en control al modificar precios o disponibilidad de habitaciones desde la app?
- ¿Qué tan útil te pareció gestionar reservas y ver alertas desde tu celular?
- ¿Cambiarías algo de la app para que se adapte mejor a tus decisiones diarias?

## Segmento 2: Administradores (Admins)

### Landing Page

- ¿La landing page te ayudó a comprender cómo esta plataforma te facilitaría el trabajo diario?
- ¿Te sentiste identificado/a con los problemas que la plataforma promete solucionar?
- ¿Te habría gustado una demo interactiva o más casos de uso concretos?
- ¿La información fue clara para entender cómo aplicarías esta herramienta en tu rutina diaria?

### Aplicación Móvil
- ¿Fue fácil acceder a tus tareas desde la app móvil?
- ¿Te ayudó a resolver incidencias o necesidades urgentes desde tu celular?
- ¿Cómo calificarías la facilidad para actualizar tareas o estados de habitación desde la app?
- ¿La aplicación móvil ayudó a reducir tu carga operativa o la mantuvo igual?

## Segmento 3: Trabajadores (Staff Operativo)

### Landing Page

- ¿La información en la landing page te ayudó a entender cómo la plataforma puede ayudarte en tu trabajo diario?
- ¿Te identificaste con las situaciones que se muestran en la página como problemas comunes?
- ¿Te pareció fácil entender qué funciones específicas podrías usar tú como trabajador?
- ¿Agregarías algún ejemplo o información para que se entienda mejor tu rol en la plataforma?

### Aplicación Móvil
- ¿Fue fácil para ti usar la aplicación desde tu celular?
- ¿Pudiste cambiar el estado de las habitaciones o tareas sin dificultad?
- ¿Te ayudó la app a organizar mejor tus tareas durante el día?
- ¿Te sentiste más conectado o comunicado con tu equipo gracias a la aplicación?

#### 8.3.4.2. Registro de Entrevistas. 

## 8.4. Experiment Aftermath & Analysis

### 8.4.1. Analysis and Interpretation of Results
### 8.4.2. Re-scored and Re-prioritized Question Backlog

## 8.5. Continuous Learning
### 8.5.1. Shareback Session Artifacts: Learning Workflow

El prototipo interactivo creado en Figma representa las interfaces y soluciones definidas, elaboradas a partir de los requerimientos y preferencias identificadas en los usuarios. Este recurso evidencia cómo el equipo fue refinando tanto los aspectos visuales como funcionales a lo largo del proceso de diseño. 

<div style="text-align: center;">
  <img src="https://i.imgur.com/uU4KZRK.png" alt="" width="70%" />
</div>

Link del prototipo: <https://www.figma.com/proto/dgI7kPPYrsUiQ0wPGJ2Aqg/RoomWise?page-id=10%3A27888&node-id=111-5594&viewport=885%2C-684%2C0.08&t=unY9joNBXN7cw8kD-1&scaling=min-zoom&content-scaling=fixed&starting-point-node-id=111%3A5594>

Encuesta de Google Forms para RoomWise: Se creó una encuesta específica en Google Forms para recopilar feedback de usuarios hoteleros y validar las hipótesis de diseño de RoomWise. Esta herramienta evaluó la usabilidad de las funcionalidades de gestión hotelera y proporcionó datos que respaldaron las mejoras implementadas en la plataforma.

<div style="text-align: center;">
  <img src="https://i.imgur.com/6slSQTC.png" alt="" width="70%" />
</div>

Link de la encuesta: https://forms.gle/5ENXDJsXHHU7B5m49

## 8.6. To-Be Software Platform Pre-launch
### 8.6.1. About-the-Product Intro Video
El siguiente video tiene como objetivo presentar SweetManager, una plataforma digital diseñada para facilitar la gestión integral de hoteles, pensada especialmente para propietarios que buscan optimizar la administración de sus establecimientos de forma eficiente y centralizada.
A través de una interfaz moderna, intuitiva y potenciada por tecnología inteligente, SweetManager permite controlar reservas, gestionar habitaciones, monitorear ingresos y coordinar al personal en tiempo real.

Este contenido destaca cómo la plataforma transforma la experiencia de gestión hotelera al reducir tareas manuales, automatizar procesos clave y ofrecer información valiosa para la toma de decisiones. Con SweetManager, los propietarios pueden enfocarse en brindar una mejor experiencia a sus huéspedes, mientras aprovechan el poder de la digitalización para hacer crecer su negocio en el competitivo sector turístico y urbano.

Link del video: <https://www.youtube.com/watch?v=T92OwQTaaeg>

<div style="text-align: center;">
  <img src="https://i.imgur.com/NKa8wbB.png" alt="" width="70%" />
</div>

# Conclusiones

## Conclusiones y Recomendaciones

El desarrollo del proyecto **SweetManager** ha representado una experiencia de aprendizaje integral para el equipo, permitiéndonos aplicar metodologías ágiles, herramientas de diseño centradas en el usuario y principios de desarrollo de software de calidad. Desde la etapa de exploración hasta las pruebas técnicas, cada fase ha estado guiada por la necesidad de resolver problemas reales en la gestión operativa de hoteles.

Partimos de una serie de **Problem Statements** que evidenciaban una gestión fragmentada en aspectos críticos como ingresos y egresos, inventario, tareas operativas y comunicación con proveedores. Para resolver estos desafíos, formulamos **assumptions** clave sobre el comportamiento de nuestros segmentos, como la preferencia por sistemas centralizados, automatizados y accesibles en tiempo real.

Con base en ello, elaboramos **Hypothesis Statements** que vinculaban nuestras funcionalidades con criterios de éxito medibles. Por ejemplo:

- Si digitalizamos la gestión de habitaciones, tareas e inventario, entonces se reducirá el tiempo de coordinación entre personal en un 25–40%.
- Si se implementa un sistema de inventario con alertas, entonces se reducirán los casos de desabastecimiento en al menos un 50%.
- Si optimizamos la experiencia inicial con un landing page clara y roles diferenciados, entonces se logrará una adopción del sistema de hasta un 95% en el primer mes.

Estas hipótesis fueron validadas parcialmente a través de prototipos de media y alta fidelidad, feedback de usuarios y pruebas internas. Los resultados obtenidos nos permiten afirmar que el enfoque funcional propuesto es viable y responde adecuadamente a las necesidades del usuario final.

Además, se implementaron **pruebas unitarias** e **integración de módulos** para asegurar la robustez del sistema, así como prácticas de **Behavior-Driven Development (BDD)** para alinear flujos técnicos con los escenarios reales de uso. Todo esto se complementó con la aplicación de **Integración Continua (CI)** y **Despliegue Continuo (CD)**, lo cual optimizó el ciclo de desarrollo y garantizó un flujo más confiable hasta producción.

**Recomendaciones y próximos pasos**

- Validar funcionalidades clave con usuarios finales mediante prototipos de alta fidelidad e iteraciones centradas en Lean UX.
- Incluir en el roadmap funcionalidades complementarias como el módulo de reservas, historial de tareas, y visualización de métricas personalizadas por rol.
- Fortalecer el componente analítico del sistema, permitiendo reportes automatizados de desempeño operativo.
- Continuar implementando pruebas automatizadas y mantener la cultura DevOps para asegurar calidad y escalabilidad en futuras versiones.
- Enfocar esfuerzos en la experiencia del usuario (UX), asegurando que tanto gerentes como empleados comprendan y adopten la herramienta de forma efectiva.

En conclusión, **SweetManager** es una solución digital con alto potencial de impacto en el sector hotelero. Su diseño responde directamente a los pain points detectados, y su desarrollo refleja buenas prácticas técnicas y estratégicas. Recomendamos continuar con su evolución hacia un producto mínimo viable (MVP) completo, listo para ser probado en entornos reales.


## Bibliografía

- de Javier, V. M. C. (s. f.). *DDD y arquitectura Onion, todo lo que necesitas saber*. Paradigma Digital. Recuperado el 29 de abril de 2024, de https://www.paradigmadigital.com/techbiz/domain-driven-design-y-arquitectura-onion/

- Eseme, S. (2021, agosto 12). *10 cosas que debes saber sobre Vue.js Frontend Framework*. Kinsta. https://kinsta.com/es/blog/vue-js/

- Gothelf, J., & Seiden, J. (2021). *Lean UX* (3.ª ed.). O’Reilly Media. https://www.oreilly.com/library/view/lean-ux-3rd/9781098116293/

- Gothelf, J. (2024). *LeanUX Sampler*. Scribd. https://es.scribd.com/document/655516553/Leanux-Sampler

- Ostelea. (2021, febrero 10). *¿Qué es la gestión hotelera y cuál es su importancia en el sector hotelero?* https://www.ostelea.com/actualidad/blog-turismo/direccion-hotelera/que-es-la-gestion-hotelera-y-cual-es-su-importancia-en-el-sector-hotelero

- Progressa Lean. (2014). *5W+2H Técnica de análisis de problemas*. https://www.progressalean.com/5w2h-tecnica-de-analisis-de-problemas/

- Solucionex. (s. f.). *Buenas prácticas para el desarrollo de grandes proyectos con Vue.js*. Recuperado el 29 de abril de 2024, de https://www.solucionex.com/blog/buenas-practicas-para-el-desarrollo-de-grandes-proyectos-con-vuejs

- Tapia, S. (2021, junio 21). *Arquitectura DDD (Domain Driven Design)*. https://sergiotapia.net/arquitectura-ddddomain-driven-design/

- UX Planet. (2017). *Information architecture: Basics for designers*. Medium. https://uxplanet.org/information-architecture-basics-for-designers-b5d43df62e20


## Anexos

### Anexo A. Videos de exposición y validaciones

- **Entrevistas a usuarios (Video):**  
  <https://upcedupe-my.sharepoint.com/:v:/g/personal/u202212383_upc_edu_pe/EQhyagVIyztBjx-XqvwF4OIB-jQ172VjzyCBXXasMZIIjg?e=lE8RTc>

- **Exposición TP1 (Video):**  
  <https://upcedupe-my.sharepoint.com/:v:/g/personal/u202212383_upc_edu_pe/EaY-6yBQ9phPrMgOXhjPG0IB5ddE7CzGnNGbG-alzz7BKg?e=3bvM0p>

- **Exposición TB2 (Video):**  
  <https://upcedupe-my.sharepoint.com/:v:/g/personal/u202212383_upc_edu_pe/EXFDnB3n-OdEoK-Zr1gtahsBk5lVK3dmkrzBKiK_Bgf9oA?e=tHa6KX>

---

### Anexo B. Repositorios de la solución digital

- **Repositorio general (Organización GitHub):**  
  <https://github.com/1ASI0732-2510-4433-G1-ROOMWISE>

- **Repositorio del informe final:**  
  <https://github.com/1ASI0732-2510-4433-G1-ROOMWISE/final-project-report>

- **Repositorio del backend (web services):**  
  <https://github.com/1ASI0732-2510-4433-G1-ROOMWISE/web-services>

- **Repositorio de la aplicación web:**  
  <https://github.com/1ASI0732-2510-4433-G1-ROOMWISE/frontend>

- **Repositorio de la aplicación móvil:**  
  <https://github.com/1ASI0732-2510-4433-G1-ROOMWISE/mobile-app>

- **Repositorio de la landing page:**  
  <https://github.com/1ASI0732-2510-4433-G1-ROOMWISE/landing-page>
