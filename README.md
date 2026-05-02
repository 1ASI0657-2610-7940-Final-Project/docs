<div style="margin-top: 140px;"></div>

<div align="center">
  <img src="./imgs/upc-logo.png" alt="Logo de UPC" width="120" />
</div>

## <p align="center">Universidad Peruana de Ciencias Aplicadas</p>

<p align="center">Ingeniería de Software</p>
<p align="center">Periodo 2610</p>
<p align="center">1ASI0657 | Fundamentos de Arquitectura de Software - Virtual</p>
<p align="center"><strong>Sección:</strong> 7940</p>
<p align="center"><strong>Docente:</strong> Daniel Enrique Mori Yzaguirre</p>

# <p align="center">Informe del Trabajo Final</p>

<p align="center"><strong>Startup:</strong> GigU</p>
<p align="center"><strong>Producto:</strong> GigU</p>

### Integrantes

| Código     | Nombres y Apellidos            |
| ---------- | ------------------------------ |
| U202310222 | Oblitas Davila, Mariano Moises |
| U20201B298 | Ybañez Esquerre, Miguel Angel  |
| U202218531 | Mio Mejia, Andy Alejandro      |

<p align="center"><strong>Abril 2026</strong></p>

<div style="page-break-before: always;"></div>

# Registro de versiones del informe

| Versión | Fecha      | Autores                                        | Descripción                                                                                                                                                                                                     |
| :------ | :--------- | :--------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| TB1     | 17/04/2026 | Mariano Oblitas, Miguel Ybañez, Andy Mio Mejia | Carátula, registro de versiones, tabla de contenidos actualizada, Student Outcome reiniciado, Capítulo I completo y estructura base de los capítulos II, III, IV, V, conclusiones, referencias, anexos y links. |

<div style="page-break-before: always;"></div>

# Tabla de Contenidos

* [Student Outcome](#student-outcome)

* [Capítulo I: Introducción](#capítulo-i-introducción)

  * [1.1. Startup Profile](#11-startup-profile)

    * [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    * [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)

  * [1.2. Solution Profile](#12-solution-profile)

    * [1.2.1. Nombre del producto](#121-nombre-del-producto)
    * [1.2.2. Antecedentes y problemática](#122-antecedentes-y-problemática)
    * [1.2.3. Lean UX Process](#123-lean-ux-process)

      * [1.2.3.1. Lean UX Problem Statement](#1231-lean-ux-problem-statement)
      * [1.2.3.2. Lean UX Assumptions](#1232-lean-ux-assumptions)
      * [1.2.3.3. Lean UX Hypothesis Statements](#1233-lean-ux-hypothesis-statements)
      * [1.2.3.4. Lean UX Canvas](#1234-lean-ux-canvas)

  * [1.3. Segmentos objetivo](#13-segmentos-objetivo)

* [Capítulo II: Requirements & Analysis](#capítulo-ii-requirements--analysis)

  * [2.1. Competidores](#21-competidores)

    * [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    * [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)

  * [2.2. Entrevistas](#22-entrevistas)

    * [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    * [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    * [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)

  * [2.3. Needfinding](#23-needfinding)

    * [2.3.1. User Personas](#231-user-personas)
    * [2.3.2. User Task Matrix](#232-user-task-matrix)
    * [2.3.3. Empathy Maps](#233-empathy-maps)
    * [2.3.4. As-Is Scenario Mapping](#234-as-is-scenario-mapping)

* [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)

  * [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  * [3.2. User Stories](#32-user-stories)
  * [3.3. Impact Map](#33-impact-map)
  * [3.4. Product Backlog](#34-product-backlog)

* [Capítulo IV: Product Architecture Design](#capítulo-iv-product-architecture-design)

  * [4.1. Design Concepts, ViewPoints & ER Diagrams](#41-design-concepts-viewpoints--er-diagrams)

    * [4.1.1. Principles Statements](#411-principles-statements)
    * [4.1.2. Approaches Statements: Architectural Styles & Patterns](#412-approaches-statements-architectural-styles--patterns)
    * [4.1.3. Context Diagram](#413-context-diagram)
    * [4.1.4. Approach-driven ViewPoints Diagrams](#414-approach-driven-viewpoints-diagrams)
    * [4.1.5. Relational/Non-Relational Database Diagram](#415-relationalnon-relational-database-diagram)
    * [4.1.6. Design Patterns](#416-design-patterns)
    * [4.1.7. Tactics](#417-tactics)

  * [4.2. Architectural Drivers](#42-architectural-drivers)

    * [4.2.1. Design Purpose](#421-design-purpose)
    * [4.2.2. Primary Functionality: Primary User Stories](#422-primary-functionality-primary-user-stories)
    * [4.2.3. Quality Attribute Scenarios](#423-quality-attribute-scenarios)
    * [4.2.4. Constraints](#424-constraints)
    * [4.2.5. Architectural Concerns](#425-architectural-concerns)

  * [4.3. ADD Iterations](#43-add-iterations)

    * [4.3.1. Iteration 1: Core Marketplace & Engagement Flow](#431-iteration-1-core-marketplace--engagement-flow)

      * [4.3.1.1. Architectural Design Backlog 1](#4311-architectural-design-backlog-1)
      * [4.3.1.2. Establish Iteration Goal by Selecting Drivers](#4312-establish-iteration-goal-by-selecting-drivers)
      * [4.3.1.3. Choose One or More Elements of the System to Refine](#4313-choose-one-or-more-elements-of-the-system-to-refine)
      * [4.3.1.4. Choose One or More Design Concepts That Satisfy the Selected Drivers](#4314-choose-one-or-more-design-concepts-that-satisfy-the-selected-drivers)
      * [4.3.1.5. Instantiate Architectural Elements, Allocate Responsibilities, and Define Interfaces](#4315-instantiate-architectural-elements-allocate-responsibilities-and-define-interfaces)
      * [4.3.1.6. Sketch Views: C4 & UML, and Record Design Decisions](#4316-sketch-views-c4--uml-and-record-design-decisions)
      * [4.3.1.7. Analysis of Current Design and Review Iteration Goal: Kanban Board](#4317-analysis-of-current-design-and-review-iteration-goal-kanban-board)

    * [4.3.2. Iteration 2: Communication, Security & Deployment Readiness](#432-iteration-2-communication-security--deployment-readiness)

      * [4.3.2.1. Architectural Design Backlog 2](#4321-architectural-design-backlog-2)
      * [4.3.2.2. Establish Iteration Goal by Selecting Drivers](#4322-establish-iteration-goal-by-selecting-drivers)
      * [4.3.2.3. Choose One or More Elements of the System to Refine](#4323-choose-one-or-more-elements-of-the-system-to-refine)
      * [4.3.2.4. Choose One or More Design Concepts That Satisfy the Selected Drivers](#4324-choose-one-or-more-design-concepts-that-satisfy-the-selected-drivers)
      * [4.3.2.5. Instantiate Architectural Elements, Allocate Responsibilities, and Define Interfaces](#4325-instantiate-architectural-elements-allocate-responsibilities-and-define-interfaces)
      * [4.3.2.6. Sketch Views: C4 & UML, and Record Design Decisions](#4326-sketch-views-c4--uml-and-record-design-decisions)
      * [4.3.2.7. Analysis of Current Design and Review Iteration Goal: Kanban Board](#4327-analysis-of-current-design-and-review-iteration-goal-kanban-board)

* [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)

  * [5.1. Testing Suites & General Patterns](#51-testing-suites--general-patterns)

    * [5.1.1. Backend Application Core Testing Suite](#511-backend-application-core-testing-suite)
    * [5.1.2. Pattern Based Backend Application(s)](#512-pattern-based-backend-applications)
    * [5.1.3. Pattern Based Custom Software Library](#513-pattern-based-custom-software-library)
    * [5.1.4. Framework Pattern Driven Refactoring Report](#514-framework-pattern-driven-refactoring-report)

  * [5.2. Software Configuration Management](#52-software-configuration-management)

    * [5.2.1. Software Development Environment Configuration](#521-software-development-environment-configuration)
    * [5.2.2. Source Code Management](#522-source-code-management)
    * [5.2.3. Source Code Style Guide & Conventions](#523-source-code-style-guide--conventions)
    * [5.2.4. Software Deployment Configuration](#524-software-deployment-configuration)

  * [5.3. Microservices Implementation](#53-microservices-implementation)

    * [5.3.1. Sprint 1](#531-sprint-1)

      * [5.3.1.1. Sprint Backlog 1](#5311-sprint-backlog-1)
      * [5.3.1.2. Development Evidence for Sprint Review](#5312-development-evidence-for-sprint-review)
      * [5.3.1.3. Testing Suite Evidence for Sprint Review](#5313-testing-suite-evidence-for-sprint-review)
      * [5.3.1.4. Execution Evidence for Sprint Review](#5314-execution-evidence-for-sprint-review)
      * [5.3.1.5. Microservices Documentation Evidence for Sprint Review](#5315-microservices-documentation-evidence-for-sprint-review)
      * [5.3.1.6. Software Deployment Evidence for Sprint Review](#5316-software-deployment-evidence-for-sprint-review)
      * [5.3.1.7. Team Collaboration Insights during Sprint](#5317-team-collaboration-insights-during-sprint)
      * [5.3.1.8. Kanban Board](#5318-kanban-board)

    * [5.3.2. Sprint 2](#532-sprint-2)

      * [5.3.2.1. Sprint Backlog 2](#5321-sprint-backlog-2)
      * [5.3.2.2. Development Evidence for Sprint Review](#5322-development-evidence-for-sprint-review)
      * [5.3.2.3. Testing Suite Evidence for Sprint Review](#5323-testing-suite-evidence-for-sprint-review)
      * [5.3.2.4. Execution Evidence for Sprint Review](#5324-execution-evidence-for-sprint-review)
      * [5.3.2.5. Microservices Documentation Evidence for Sprint Review](#5325-microservices-documentation-evidence-for-sprint-review)
      * [5.3.2.6. Software Deployment Evidence for Sprint Review](#5326-software-deployment-evidence-for-sprint-review)
      * [5.3.2.7. Team Collaboration Insights during Sprint](#5327-team-collaboration-insights-during-sprint)
      * [5.3.2.8. Kanban Board](#5328-kanban-board)

    * [5.3.3. Sprint 3](#533-sprint-3)

      * [5.3.3.1. Sprint Backlog 3](#5331-sprint-backlog-3)
      * [5.3.3.2. Development Evidence for Sprint Review](#5332-development-evidence-for-sprint-review)
      * [5.3.3.3. Testing Suite Evidence for Sprint Review](#5333-testing-suite-evidence-for-sprint-review)
      * [5.3.3.4. Execution Evidence for Sprint Review](#5334-execution-evidence-for-sprint-review)
      * [5.3.3.5. Microservices Documentation Evidence for Sprint Review](#5335-microservices-documentation-evidence-for-sprint-review)
      * [5.3.3.6. Software Deployment Evidence for Sprint Review](#5336-software-deployment-evidence-for-sprint-review)
      * [5.3.3.7. Team Collaboration Insights during Sprint](#5337-team-collaboration-insights-during-sprint)
      * [5.3.3.8. Kanban Board](#5338-kanban-board)

    * [5.3.4. Sprint 4](#534-sprint-4)

      * [5.3.4.1. Sprint Backlog 4](#5341-sprint-backlog-4)
      * [5.3.4.2. Development Evidence for Sprint Review](#5342-development-evidence-for-sprint-review)
      * [5.3.4.3. Testing Suite Evidence for Sprint Review](#5343-testing-suite-evidence-for-sprint-review)
      * [5.3.4.4. Execution Evidence for Sprint Review](#5344-execution-evidence-for-sprint-review)
      * [5.3.4.5. Microservices Documentation Evidence for Sprint Review](#5345-microservices-documentation-evidence-for-sprint-review)
      * [5.3.4.6. Software Deployment Evidence for Sprint Review](#5346-software-deployment-evidence-for-sprint-review)
      * [5.3.4.7. Team Collaboration Insights during Sprint](#5347-team-collaboration-insights-during-sprint)
      * [5.3.4.8. Kanban Board](#5348-kanban-board)

  * [5.4. Microservices Deployment](#54-microservices-deployment)

    * [5.4.1. Cloud Architecture Diagram](#541-cloud-architecture-diagram)
    * [5.4.2. Cloud Architecture Deployment](#542-cloud-architecture-deployment)

* [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)

* [Video About-The-Team](#video-about-the-team)

* [Referencias bibliográficas](#referencias-bibliográficas)

* [Anexos](#anexos)

* [Links](#links)

# Student Outcome

ABET – EAC - Student Outcome 7: Aprendizaje Continuo y Autónomo.

**Criterio:** La capacidad de adquirir y aplicar nuevos conocimientos según sea necesario, utilizando estrategias de aprendizaje apropiadas.

| Criterio específico                                                                                                                         | Acciones realizadas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | Conclusiones                                                                                                                                                                                                                                                                                                                                           |
| ------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software.** | **Oblitas Davila, Mariano Moises** **TB1:** Elaboré la carátula del informe y desarrollé el Capítulo I, adaptando la estructura previa del proyecto GigU al nuevo curso de Fundamentos de Arquitectura de Software y reorganizando la información inicial de la startup, la solución y los segmentos objetivo.<br><br>**Ybañez Esquerre, Miguel Angel** **TB1:** Desarrollé la estructura base del Capítulo II, alineando los apartados de Competidores, Entrevistas y Needfinding con la guía del nuevo curso para preparar la siguiente fase de análisis del producto.<br><br>**Mio Mejia, Andy Alejandro** **TB1:** Desarrollé la estructura base del Capítulo III, organizando las secciones de To-Be Scenario Mapping, User Stories, Impact Map y Product Backlog conforme a los requerimientos del curso.                    | En esta primera entrega, el equipo actualizó la estructura del proyecto para alinearlo con el enfoque de arquitectura de software del nuevo curso. Se reorganizó el informe según la guía oficial y se establecieron bases claras para continuar el desarrollo de los capítulos de análisis, especificación y arquitectura en las siguientes entregas. |
| **Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software.**  | **Oblitas Davila, Mariano Moises** **TB1:** Reconocí la necesidad de revisar y adaptar el trabajo previo a una nueva estructura académica orientada a arquitectura, lo que implicó reforzar conceptos de formulación del problema, Lean UX y organización formal de entregables.<br><br>**Ybañez Esquerre, Miguel Angel** **TB1:** Identifiqué la importancia de seguir aprendiendo sobre técnicas de análisis de competidores, entrevistas y needfinding para sustentar correctamente la fase de levantamiento y análisis de requisitos del proyecto.<br><br>**Mio Mejia, Andy Alejandro** **TB1:** Reconocí la necesidad de profundizar en la especificación de requisitos, especialmente en la construcción de artefactos como User Stories, Impact Map y Product Backlog, para adaptar el proyecto a las exigencias del curso. | El equipo evidenció desde la primera entrega que continuar el mismo producto en un nuevo curso exige aprendizaje permanente, reorganización técnica y comprensión de nuevos enfoques de arquitectura. Esta adaptación permitió establecer una base más sólida para el desarrollo progresivo del trabajo final.                                         |

<div style="page-break-before: always;"></div>

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

Somos GigU, un equipo de estudiantes de la Universidad Peruana de Ciencias Aplicadas comprometidos con la innovación tecnológica y la creación de oportunidades para nuestra comunidad universitaria.

Nuestra misión es ofrecer una plataforma que permita a los estudiantes universitarios ofrecer sus habilidades y conocimientos a través de servicios freelance, generando ingresos adicionales mientras desarrollan experiencia profesional en su campo.

Nuestra visión es convertirnos en la principal plataforma de trabajo freelance para estudiantes en Perú y Latinoamérica, facilitando la conexión entre talento joven y clientes que buscan soluciones creativas y eficientes en múltiples áreas como desarrollo de software, diseño, tutorías, gestión empresarial, entre otros.

Nuestro producto principal es GigU, una plataforma que conecta a estudiantes con clientes interesados en servicios freelance. Los freelancers pueden publicar sus servicios, definir tarifas y cotizar precios de manera inteligente con base en factores como el tiempo estimado de trabajo, la complejidad del servicio y las tarifas del mercado. La plataforma también proporciona comunicación con clientes y procesamiento seguro de pagos.

GigU no solo ayuda a los estudiantes a generar ingresos mientras estudian, sino que también les permite desarrollar habilidades clave como la gestión del tiempo, la negociación, la resolución de problemas y el trato con clientes reales, preparándose así para la vida profesional.

Además, con GigU, los estudiantes tienen una forma flexible, accesible y efectiva de adquirir experiencia laboral y construir una red de clientes y contactos profesionales desde el inicio de su carrera.


### 1.1.2. Perfiles de integrantes del equipo

| Nombre                             | Detalle                                                                                                                                                                                                                                                                                                                                                       |
| Nombre: Ybañez Esquerre, Miguel Angel | <img src="imgs/team/miguel.jpg" alt="Miguel" title="Foto de Miguel" width="520"/> |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------- |
| **Código:** U20201B298|                               |
| **Carrera:** Ingeniería de Software    |                               |
| **Habilidades:** Miguel Ángel Ybañez Esquerre – Estudiante de 23 años de Ingeniería de Software en la UPC. Me caracterizo por mi creatividad, capacidad analítica y enfoque práctico para resolver problemas. Apasionado por el desarrollo web y los agentes de inteligencia artificial, con experiencia en desarrollo de videojuegos en Unity y realidad virtual con Meta Quest. Siempre en búsqueda de explorar nuevas tecnologías y llevar las ideas a soluciones reales. |                               |

| Nombre: Oblitas Davila, Mariano Moises | <img src="imgs/team/mariano.png" alt="Mariano" title="Foto de Mariano" width="320"/> |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------- |
| **Código:** U202310222  |                               |
| **Carrera:** Ingeniería de Software |                               |
| **Habilidades:** Estudiante de 20 años de Ingeniería de Software en la UPC. Me caracterizo por mi creatividad, eficacia y capacidad para resolver problemas de manera racional. Apasionado por la programación y el desarrollo de software, busco constantemente innovar y aprender nuevas tecnologías. |          |

| Nombre: Mio Mejia, Andy Alejandro | <img src="imgs/team/andy.jpg" alt="Andy" title="Foto de Andy" width="320"/> |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------- |
| **Código:** U202218531  |                               |
| **Carrera:** Ingeniería de Software |                               |
| **Habilidades:** Soy estudiante de 7mo ciclo de Ingeniería de Software con sólidos fundamentos en programación, desarrollo web y análisis de datos. Apasionado por la Inteligencia Artificial, desarrollo Web Robusto, sistemas inteligentes y soluciones tecnológicas escalables. Poseo capacidad para aprender rápidamente y trabajar en entornos ágiles (Scrum). Me gustaría aplicar mis conocimientos técnicos en Python (avanzado), C++ y frameworks modernos para contribuir al desarrollo de software robusto y de alta usabilidad. |          |

## 1.2. Solution Profile

### 1.2.1. Nombre del producto
GigU

### 1.2.2. Antecedentes y problemática

##### **¿Cuál es el problema?**

Muchos estudiantes universitarios enfrentan serias dificultades para generar ingresos y adquirir experiencia profesional mientras cursan sus estudios. Esta carencia de oportunidades laborales adecuadas no solo limita su independencia económica, sino también el desarrollo temprano de habilidades prácticas y su inserción competitiva en el mercado laboral. Según datos del Ministerio de Educación del Perú, una parte importante de los estudiantes universitarios combina estudios y trabajo de manera simultánea, reflejando que la necesidad de generar ingresos aparece incluso antes del egreso. Sin embargo, a pesar de contar con talentos y conocimientos valiosos, la mayoría no dispone de una plataforma accesible, segura y adaptada que les permita ofrecer sus servicios de forma organizada y profesional, especialmente bajo la modalidad freelance.

Como antecedente, el Ministerio de Educación aplicó la Encuesta Nacional de Estudiantes de Educación Superior Universitaria 2019 a 63,412 estudiantes de 18 universidades públicas. En dicha encuesta, el 28.5% de los estudiantes que interrumpieron sus estudios señaló como razón principal la falta de recursos económicos, lo que evidencia que la presión financiera puede afectar directamente la continuidad académica (Ministerio de Educación del Perú, 2021).

Además, el sistema universitario peruano concentra una población joven altamente expuesta a esta problemática. El Ministerio de Educación reporta que el 65% de los estudiantes universitarios tiene entre 18 y 25 años, y que el 24% pertenece a hogares en situación de pobreza o pobreza extrema. Por ello, la necesidad de generar ingresos durante la etapa universitaria no es un caso aislado, sino una condición relevante para una parte importante de la población estudiantil (Ministerio de Educación del Perú, 2023).

##### **¿Cuándo ocurre el problema?**

El problema se presenta a lo largo de toda la etapa universitaria, con mayor énfasis a partir del 2.º o 3.º año de carrera, cuando los estudiantes ya han adquirido capacidades técnicas, académicas o creativas que podrían ser aplicadas en el ámbito laboral. La necesidad de generar ingresos se intensifica en periodos críticos como matrículas, proyectos finales o gastos personales, momentos en los que la presión financiera se convierte en un factor determinante para su permanencia y rendimiento académico.

Este problema también se vuelve más evidente en la transición entre la formación académica y la empleabilidad temprana. La universidad peruana exige progresivamente que los estudiantes desarrollen competencias profesionales, portafolios, prácticas y experiencia demostrable; sin embargo, el acceso a oportunidades compatibles con horarios académicos sigue siendo limitado. Aunque la Ley Universitaria reconoce mecanismos orientados a mejorar la formación y empleabilidad, como bolsas de trabajo y promoción de iniciativas estudiantiles, estos mecanismos suelen estar más orientados al egreso, las prácticas o la empleabilidad institucional, no necesariamente a servicios freelance flexibles durante la etapa formativa (Ministerio de Educación del Perú, 2024).

##### **¿Dónde ocurre el problema?**

Esta problemática es evidente en el contexto universitario peruano y latinoamericano, especialmente en instituciones donde las políticas de empleabilidad son limitadas o inexistentes, y donde los programas de prácticas preprofesionales o los vínculos con el mercado freelance son insuficientes o inaccesibles. Asimismo, en el entorno digital persiste la falta de una plataforma centralizada y especializada que facilite a los estudiantes la oferta de servicios freelance de manera organizada, validada y segura.

En América Latina y el Caribe, la Organización Internacional del Trabajo advierte que las personas jóvenes enfrentan tasas de desocupación 3 veces superiores a las de los adultos, y que la informalidad afecta al 60% de los jóvenes que trabajan. Este contexto regional refuerza la necesidad de soluciones que no solo conecten oferta y demanda, sino que también reduzcan la informalidad, aumenten la confianza entre estudiantes y clientes, y permitan que el trabajo independiente se realice bajo condiciones más transparentes (Organización Internacional del Trabajo, 2025).

##### **¿A quién afecta el problema?**

El problema impacta directamente a estudiantes universitarios que buscan generar ingresos, adquirir experiencia laboral temprana y construir un portafolio real antes de egresar. Esta situación también afecta a microempresas, emprendedores y particulares que requieren servicios profesionales accesibles, confiables y de calidad, y que a menudo no logran encontrar talento joven disponible y verificado en su entorno inmediato.

El impacto sobre los estudiantes es especialmente relevante porque se trata de una población que combina necesidades económicas, restricciones de horario y baja experiencia laboral acumulada. Al mismo tiempo, las microempresas y emprendimientos suelen requerir servicios puntuales de diseño, desarrollo web, edición, marketing, traducción, soporte tecnológico, asistencia académica o producción de contenido, pero no siempre cuentan con presupuesto para contratar agencias o personal permanente. El Banco Mundial señala que las plataformas de trabajo digital pueden facilitar la conexión entre trabajadores independientes y empresas que requieren servicios específicos, aunque también advierte que estos mercados necesitan mecanismos de confianza, acceso y protección para ser sostenibles (Banco Mundial, 2023).

##### **¿Por qué sucede el problema?**

El problema radica en la falta de plataformas diseñadas específicamente para conectar estudiantes con clientes potenciales, considerando sus limitaciones de tiempo, experiencia y recursos. Las plataformas freelance tradicionales imponen barreras de entrada significativas, como comisiones elevadas, competencia global desproporcionada y escasa validación académica de perfiles, lo que desalienta la participación de estudiantes y perpetúa su informalidad laboral.

Las plataformas globales de trabajo independiente permiten acceder a mercados amplios, pero no siempre son adecuadas para estudiantes que recién comienzan. El Banco Mundial identifica que las plataformas locales o regionales pueden reducir barreras para jóvenes y trabajadores primerizos, debido a una menor competencia global, mayor cercanía con clientes locales y menor dependencia de idiomas extranjeros. También advierte que las plataformas globales pueden generar barreras de entrada más altas para nuevos trabajadores. Por ello, una solución especializada para universitarios puede aportar valor si incorpora validación académica, reputación inicial, categorías alineadas a carreras, pagos seguros y reglas claras de contratación (Banco Mundial, 2024).

##### **¿Cómo sucede el problema?**

En ausencia de alternativas formales y especializadas, los estudiantes optan por ofrecer sus servicios a través de redes sociales, contactos personales o plataformas genéricas que no garantizan seguridad, visibilidad ni condiciones laborales justas. Esta informalidad expone a los estudiantes a malas prácticas, incumplimientos de pago, sobreexplotación de tiempo y escaso reconocimiento de sus capacidades, lo que frecuentemente deriva en frustración, desmotivación y experiencias laborales negativas.

Este proceso ocurre porque el estudiante suele iniciar su búsqueda laboral desde redes informales, sin mecanismos claros de verificación, contratos simples, protección frente a incumplimientos, gestión de entregables o calificación del cliente. La Organización Internacional del Trabajo señala que el trabajo mediante plataformas digitales puede ampliar oportunidades, pero también plantea riesgos vinculados a condiciones de trabajo, ingresos variables y ausencia de protección suficiente si no existen reglas claras. En el mismo sentido, el Banco Mundial advierte que el trabajo digital puede ofrecer flexibilidad, pero también generar tareas esporádicas, dificultad para progresar profesionalmente y altos tiempos de búsqueda de encargos (Organización Internacional del Trabajo, 2021; Banco Mundial, 2023).

##### **¿Cuán grande es el impacto de este problema?**

El impacto es considerable tanto en el plano individual como en el social. En el Perú, una alta proporción de jóvenes trabaja en condiciones de informalidad, lo que evidencia una fuerte precarización del empleo juvenil y una limitada protección social. Además, la tasa de desempleo juvenil supera al promedio nacional, posicionando a este grupo como uno de los más vulnerables del mercado laboral. Esta realidad afecta directamente su desarrollo personal y profesional, retrasa su independencia económica y limita su proyección laboral futura.

Los indicadores laborales recientes refuerzan esta situación. Según el Instituto Nacional de Estadística e Informática, en el 1.er trimestre de 2025 la tasa de desempleo nacional fue de 5.5%, mientras que en jóvenes de 14 a 24 años alcanzó 11.3%. En el mismo periodo, el desempleo afectó al 8.0% de la población con educación superior universitaria, y el subempleo afectó al 58.2% de la población económicamente activa ocupada joven (Instituto Nacional de Estadística e Informática, 2025a).

En el 2.º trimestre de 2025, el INEI reportó que la tasa de desempleo nacional fue de 5.9%, mientras que en jóvenes de 14 a 24 años alcanzó 13.0%. Además, la tasa de desempleo entre personas con educación superior universitaria fue de 7.0%. Estos datos no corresponden exclusivamente a estudiantes universitarios, pero sí describen el entorno laboral del grupo etario y educativo al que pertenece gran parte de ellos (Instituto Nacional de Estadística e Informática, 2025b).

### 1.2.3. Lean UX Process


#### 1.2.3.1. Lean UX Problem Statement

En el contexto universitario peruano, los estudiantes enfrentan grandes desafíos para insertarse en el mercado laboral mientras cursan sus estudios. Esta situación se relaciona con factores económicos, académicos y laborales: el 65% de los estudiantes universitarios tiene entre 18 y 25 años, el 24% pertenece a hogares en situación de pobreza o pobreza extrema, y la falta de recursos económicos aparece como una causa relevante de interrupción de estudios universitarios (Ministerio de Educación del Perú, 2023).

Hemos observado que no existen plataformas efectivas y especializadas que conecten directamente a estudiantes universitarios con oportunidades laborales formales, flexibles y alineadas a sus carreras, lo cual perpetúa la falta de experiencia profesional al egresar. Aunque existen plataformas freelance globales, estas no resuelven completamente el problema para estudiantes que recién comienzan, debido a barreras como alta competencia, dificultad para construir reputación inicial, posibles comisiones, baja validación académica y menor adaptación al mercado local (Banco Mundial, 2024).

Este problema afecta principalmente a estudiantes universitarios que necesitan generar ingresos, adquirir experiencia práctica y construir un portafolio profesional antes de egresar. También afecta a emprendedores, microempresas y particulares que requieren servicios accesibles y confiables, pero no cuentan con un canal especializado para encontrar talento universitario verificado.

¿Cómo podemos ayudar a los estudiantes universitarios en el Perú a insertarse en el mercado laboral de forma formal, flexible y segura durante su etapa académica, permitiéndoles desarrollar habilidades prácticas, generar ingresos y mejorar su empleabilidad desde los primeros ciclos?

#### 1.2.3.2. Lean UX Assumptions

**¿Quién es el usuario?**
Estudiantes universitarios peruanos, principalmente entre los 17 y 24 años, que buscan generar ingresos y experiencia profesional compatible con sus horarios académicos.

**¿Dónde encaja nuestro producto en su vida?**
GigU se integra como una herramienta esencial para complementar su formación académica con experiencia laboral real, generar ingresos y conectarse con profesionales, clientes o mentores, sin sacrificar su rendimiento académico.

**¿Qué problemas tiene nuestro producto y cómo se pueden resolver?**

* Posible desconfianza hacia la formalidad de las oportunidades.
  Solución: verificación de empleadores o clientes y contratos inteligentes.

* Dificultad para encontrar tareas relacionadas a su carrera.
  Solución: sistema de categorización inteligente por carreras y habilidades.

* Baja retención o uso esporádico.
  Solución: gamificación, badges y recompensas por participación activa.

**¿Cómo y cuándo es usado nuestro producto?**
El producto es usado principalmente durante los tiempos libres o entre clases. Los estudiantes lo utilizan para buscar encargos, postular a proyectos freelance, recibir feedback y conectarse con mentores o empresas pequeñas que necesitan apoyo técnico o creativo.

**¿Qué características son importantes?**

* Perfiles profesionales con historial académico y de proyectos.
* Oportunidades freelance o part time verificadas.
* Inteligencia artificial para emparejar tareas con habilidades.
* Retroalimentación entre estudiantes y clientes.
* Panel de seguimiento de experiencia acumulada.
* Integración con LinkedIn y portafolios.
* Sistema de reputación y badges.
* Chat seguro entre clientes y postulantes.
* Acceso a microcursos gratuitos recomendados según proyectos.

**¿Cómo debe verse nuestro producto y cómo comportarse?**
Debe tener un diseño moderno, amigable y responsivo. Su comportamiento debe ser fluido, con tiempos de carga bajos y navegación clara. La experiencia de usuario debe motivar la interacción constante, con notificaciones relevantes y recomendaciones que generen valor real para el usuario.

#### 1.2.3.3. Lean UX Hypothesis Statements

* Creemos que al conectar estudiantes universitarios con oportunidades laborales compatibles con sus carreras y horarios, lograremos que desarrollen experiencia profesional antes de egresar.
  Sabremos que hemos tenido éxito cuando más del 50% de los usuarios activos complete al menos una tarea remunerada en su primer mes.

* Creemos que implementar un sistema de reputación y gamificación aumentará la participación y compromiso con la plataforma.
  Sabremos que hemos tenido éxito cuando el tiempo promedio de uso semanal supere los 45 minutos por usuario activo.

* Creemos que ofrecer oportunidades relacionadas a sus habilidades y carrera aumentará su satisfacción y fidelización.
  Sabremos que hemos tenido éxito cuando al menos el 70% de los usuarios califique la relevancia de las recomendaciones como alta o muy alta.

#### 1.2.3.4. Lean UX Canvas

<img src="imgs/LeanUX_Canvas.png" alt="LeanUXCanvas" title="LeanUXCanvas"/>

## 1.3. Segmentos objetivo

#### **Estudiantes Universitarios Freelancers**

Estudiantes de cualquier ciclo universitario que buscan ofrecer sus servicios de manera independiente para adquirir experiencia laboral, generar ingresos y construir una red de clientes. Estos estudiantes pueden pertenecer a diversas especialidades como diseño gráfico, programación, marketing digital, redacción, tutorías académicas, entre otros.

**Características:**

* Buscan oportunidades de trabajo flexible que les permitan combinar sus estudios con el trabajo freelance.
* Necesitan herramientas que los ayuden a promocionar sus habilidades y construir una cartera de clientes.
* Valoran la facilidad de pago y la seguridad en la gestión de contratos.

#### **Personas y Emprendimientos que buscan contratar servicios freelance**

Individuos o empresas que requieren servicios especializados sin la necesidad de contratar empleados a tiempo completo. Esto incluye emprendedores, startups, pequeñas empresas y particulares que buscan soluciones rápidas y accesibles para sus proyectos.

**Características:**

* Buscan talento accesible y de calidad para tareas específicas.
* Prefieren plataformas que garanticen la seguridad en la contratación y el cumplimiento del trabajo.
* Valoran las recomendaciones y validaciones de otros clientes para elegir freelancers confiables.

<div style="page-break-before: always;"></div>

# Capítulo II: Requirements & Analysis

## 2.1. Competidores

En el mercado freelance existen múltiples plataformas consolidadas, pero ninguna está 100% orientada al talento universitario. Por ello, los competidores identificados para GigU son plataformas freelance generalistas que, aunque comparten funcionalidades similares, no cubren a profundidad las necesidades específicas de los estudiantes universitarios que buscan dar sus primeros pasos profesionales.

### 2.1.1. Análisis competitivo

A continuación se presenta el análisis competitivo comparando a GigU con las principales alternativas del mercado freelance. Se evalúan dimensiones como perfil estratégico, segmento objetivo, propuesta de valor, canales, relaciones con el cliente y ventajas competitivas.

<img src="imgs/Competidores1.png" alt="Competidores1" title="Competidores1"/>
<img src="imgs/Competidores2.png" alt="Competidores2" title="Competidores2"/>
<img src="imgs/Competidores3.png" alt="Competidores3" title="Competidores3"/>
<img src="imgs/Competidores4.png" alt="Competidores4" title="Competidores4"/>
<img src="imgs/Competidores5.png" alt="Competidores5" title="Competidores5"/>
<img src="imgs/Competidores6.png" alt="Competidores6" title="Competidores6"/>

### 2.1.2. Estrategias y tácticas frente a competidores

GigU adopta una estrategia de **diferenciación centrada en el talento universitario**, apoyándose en un enfoque educativo, precios accesibles y alianzas con instituciones académicas. A diferencia de los grandes actores del mercado freelance global, nuestra plataforma se posiciona como una alternativa confiable y de propósito social que conecta clientes con estudiantes verificados académicamente.

Las tácticas principales son:

* **Verificación académica:** Validar que los freelancers sean estudiantes activos para transmitir confianza al cliente.
* **Soporte regional y en español:** Aprovechar la debilidad de plataformas globales con soporte limitado o genérico.
* **Personalización:** Recomendaciones de proyectos basadas en carrera, habilidades y disponibilidad del estudiante.
* **Garantías y filtros de calidad:** Mitigar la percepción de “poca experiencia” con reseñas reales, portafolios y calificaciones.
* **Pagos seguros y automatizados:** Reducir la fricción e inseguridad de métodos informales (Yape, transferencias directas).

En conjunto, la estrategia busca capitalizar las debilidades de los competidores (poca personalización, fuerte competencia global, comisiones elevadas) y convertirlas en ventajas competitivas para GigU.

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

Para el proceso de *needfinding* se diseñaron dos guías de entrevista, una por cada segmento objetivo. El objetivo fue identificar motivaciones, dificultades actuales, comportamientos de búsqueda de trabajo/contratación y requisitos ideales de una plataforma freelance universitaria.

**Segmento objetivo 1: Estudiantes Universitarios Freelancers**

* ¿Cuál es tu nombre completo?
* ¿Cuál es tu edad?
* ¿Dónde vives?
* ¿Has ofrecido tus servicios como freelancer alguna vez? ¿En qué área?
* ¿Qué te motivó a ofrecer tus servicios de manera independiente?
* ¿Dónde sueles buscar oportunidades freelance (redes, plataformas, conocidos, etc.)?
* ¿Qué dificultades has encontrado al intentar conseguir clientes como estudiante?
* ¿Qué características debería tener una plataforma ideal para ayudarte a encontrar clientes?
* ¿Qué métodos usas actualmente para cobrar tus servicios? ¿Has tenido problemas con eso?
* ¿Cuánto tiempo a la semana podrías dedicarle a trabajos freelance?
* ¿Crees que sería útil tener una app que te sugiera proyectos freelance según tu perfil y habilidades?
* ¿Qué tan importante es para ti tener una forma segura y automática de cobrar por tu trabajo freelance?

**Segmento objetivo 2: Personas y Emprendimientos que buscan contratar servicios freelance**

* ¿Cuál es tu nombre completo?
* ¿Cuál es tu edad?
* ¿Dónde vives?
* ¿Alguna vez has contratado a un freelancer para un proyecto? ¿Cómo fue tu experiencia?
* ¿Qué tipo de tareas sueles tercerizar o te gustaría tercerizar?
* ¿Qué canales usas actualmente para encontrar freelancers (plataformas, conocidos, redes)?
* ¿Qué te haría confiar en un estudiante universitario como freelancer?
* ¿Qué tan importante es para ti poder ver recomendaciones o validaciones de otros clientes?
* ¿Te gustaría una plataforma que se encargue de gestionar los pagos y acuerdos con el freelancer, o prefieres hacerlo tú directamente con la persona?
* ¿Qué haría que descartes a un freelancer incluso si su precio es atractivo?
* ¿Qué funcionalidades te gustaría ver en una plataforma para contratar freelancers?
* ¿Qué tan importante es para ti poder negociar el precio antes de contratar un servicio freelance? ¿Preferirías un precio fijo o la opción de llegar a un acuerdo con el freelancer?
* ¿Qué factores tomas en cuenta al elegir a un freelancer: precio, portafolio, tiempo de entrega, reputación, otro? ¿Cuál de ellos pesa más para ti al decidir?

### 2.2.2. Registro de entrevistas

**Segmento objetivo #1: Estudiantes Universitarios Freelancers**

**Entrevistado N°1: Bruno Sebastián Gamarra Torres**

* Sexo: Masculino
* Edad: 23
* Ubicación: Surco
* Instante de inicio: 0:03 min · Duración: 3:44

**Resumen:** Bruno ofrece servicios de diseño gráfico y edición de video desde hace algunos meses, motivado por la necesidad económica y por ganar experiencia. Consigue clientes sobre todo vía Instagram y TikTok, pero lidia con la desconfianza hacia estudiantes. Cobra por Yape, Plin y transferencias, y a veces sufre retrasos. Una plataforma ideal, según él, debería permitir reseñas reales, chat integrado y contratos.

![imgs](imgs/Seg1EntrevistaWener.png)

**Entrevistado N°2: Werner Lang**

* Sexo: Masculino
* Edad: 20
* Ubicación: San Isidro
* Instante de inicio: 3:45 min · Duración: 9:57 min

**Resumen:** Werner trabaja en diseño gráfico y desarrollo web como freelancer para aplicar lo aprendido y ganar experiencia antes de egresar. Consigue clientes por conocidos, redes sociales y Workana, pero siente que no lo toman en serio por ser estudiante; además carece de un portafolio sólido. Cobra por Yape o transferencia, con demoras ocasionales. Dedica 8–12 horas semanales. Considera que una plataforma ideal debe facilitar mostrar habilidades, cotizar, asegurar pagos y permitir comunicación fluida, además de sugerirle proyectos alineados a su perfil.

![imgs](imgs/Seg1Entrevista2.png)

**Entrevistado N°3: Mario André Cacho Seminario**

* Sexo: Masculino
* Edad: 21
* Ubicación: Surco
* Link: [YouTube](https://youtu.be/hSg2bZ3Jgbc) · Instante de inicio: 0:10 · Duración: 3:26

**Resumen:** Mario crea videos de marketing para pequeñas empresas. Le motiva ampliar su perspectiva profesional, pero le resulta difícil conseguir clientes porque priorizan la experiencia. Consigue oportunidades por redes sociales y contactos cercanos, y cobra por transferencia bancaria. Dedica 6–8 horas semanales. Valora que una plataforma muestre a perfiles de todos los niveles, sugiera proyectos por habilidades, exhiba un historial de trabajos y cuente con un sistema de cobros seguro.

![imgs](imgs/Seg1Entrevista1.png)

**Segmento objetivo #2: Personas y Emprendimientos que buscan contratar servicios freelance**

**Entrevistada N°1: Yulia Estephania Martinez Martinez**

* Sexo: Femenino
* Edad: 19
* Ubicación: Surco
* Link: [YouTube](https://youtu.be/MFs44DHr8_Q) · Instante de inicio: 0:01 · Duración: 5:46

![imgs](imgs/Seg2Entrevista1a.png)

![imgs](imgs/Seg2Entrevista1b.png)

**Resumen:** Yulia tiene un emprendimiento de cuadros personalizados (*Quack_cuadros*). Aún no ha contratado freelancers pero está interesada en tercerizar marketing digital (reels) y diseño web. Actualmente busca talento por Instagram y contactos, lo cual considera poco confiable.

* **Criterios para confiar:** portafolio visual para trabajos creativos; CV para otros; valora recomendaciones y validaciones.
* **Pagos:** prefiere que la plataforma gestione pagos y acuerdos.
* **Motivos de descarte:** mala calidad, falta de responsabilidad, poca puntualidad.
* **Funciones deseadas:** perfiles detallados, herramientas de negociación, reuniones dentro de la plataforma, chats y acuerdos formales.
* **Factores de decisión:** el portafolio es lo más determinante, seguido del precio; un trabajo que impacte positivamente la vuelve flexible en el pago.

**Entrevistado N°2: Fabrizio Morales**

* Sexo: Masculino
* Edad: 22
* Ubicación: La Molina
* Instante de inicio: 25:32 min · Duración: 31:17 min

![imgs](imgs/Seg2EntrevistaFabrizio.png)

**Resumen:** Fabrizio dirige un negocio de venta de vapes y contrata freelancers para marketing y ventas, principalmente por Facebook y LinkedIn, apoyándose también en recomendaciones cercanas.

* **Criterios para confiar:** portafolio visual o ejemplos previos para trabajos creativos; CV para otros; testimonios de antiguos clientes.
* **Pagos:** prefiere que la plataforma gestione acuerdos y pagos para evitar negociaciones directas.
* **Motivos de descarte:** trabajo deficiente, falta de responsabilidad, retrasos en entregas.
* **Funciones deseadas:** perfiles completos, herramientas de negociación, reuniones dentro de la plataforma, chats formales con acuerdos visibles.
* **Factores de decisión:** el portafolio visual es lo más determinante; si un resultado impacta positivamente, acepta pagar más de lo previsto.

Link de entrevista: [SharePoint UPC](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202213241_upc_edu_pe/ERWRYYotMDNKrb9UZXiaV90BczcuHnygJ1UOZNQE1nmmxQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=v3wSIJ)

### 2.2.3. Análisis de entrevistas

**Segmento 1 — Estudiantes Universitarios Freelancers.** Los tres entrevistados (Bruno, Werner y Mario) coinciden en que la principal motivación es generar ingresos mientras ganan experiencia profesional, y que la mayor barrera es la **desconfianza del cliente hacia los estudiantes**. El insight central es que, más que su nivel de experiencia, el obstáculo real es la percepción del mercado; esto evidencia la necesidad de **mecanismos de validación**: reseñas, calificaciones y contratos formales dentro de la plataforma.

Usan redes sociales y plataformas como Workana, pero obtienen poca visibilidad. Surge así un segundo insight: los freelancers quieren ser emparejados por **habilidades**, no únicamente por historial previo, lo que abre espacio a un sistema de recomendaciones por competencias. En cuanto a pagos, todos usan Yape y transferencias y han sufrido retrasos, lo que refuerza la necesidad de un **sistema de cobros seguro y automatizado**. Además del ingreso, valoran construir reputación profesional y recibir retroalimentación, señal de que la plataforma también debe actuar como un espacio de **desarrollo de carrera**.

**Segmento 2 — Personas y Emprendimientos que buscan freelancers.** Yulia y Fabrizio priorizan **calidad y responsabilidad** por encima del precio. El insight clave es que el **portafolio visual pesa más que el costo**: si un trabajo impacta positivamente, están dispuestos a pagar más. Ambos muestran desconfianza hacia perfiles sin referencias, por lo que las **recomendaciones, testimonios y perfiles detallados** son elementos indispensables.

En la gestión de acuerdos y pagos ambos prefieren no tratar directamente con el freelancer, lo que revela una necesidad de **automatizar negociación, acuerdos y pagos dentro de la plataforma**. Finalmente, el impacto emocional del resultado influye en la disposición a pagar más, lo que asigna un rol estratégico a la **presentación del trabajo** (antes y después de la entrega).

**Conclusión transversal.** Ambos segmentos convergen en la necesidad de una plataforma que ofrezca: (i) perfiles verificados y portafolios, (ii) emparejamiento inteligente por habilidades, (iii) acuerdos y pagos seguros gestionados por la plataforma, (iv) reseñas y reputación, y (v) comunicación fluida dentro del entorno. Estos hallazgos alimentan directamente los *User Personas*, la *User Task Matrix* y los *Empathy Maps* del siguiente apartado.

## 2.3. Needfinding

En esta sección se presentan los artefactos derivados del análisis de la información recolectada en las entrevistas, sintetizando motivaciones, problemas y requisitos para cada segmento objetivo.

**Segmento objetivo #1: Estudiantes Universitarios Freelancers**

* **Motivaciones principales:**
  * Desarrollo profesional y aplicación de lo aprendido en la universidad.
  * Ganar experiencia real antes de egresar.
  * Explorar distintas áreas del mercado y ampliar su perspectiva profesional.
* **Problemas identificados:**
  * Dificultad para conseguir clientes por el prejuicio hacia su condición de estudiante.
  * Poca visibilidad en plataformas tradicionales y baja confianza hacia perfiles jóvenes.
  * Problemas con los pagos: demoras, renegociaciones y falta de sistemas seguros.
* **Requisitos para una plataforma ideal:**
  * Permitir mostrar habilidades y portafolio aun con experiencia limitada.
  * Sugerencias de proyectos basadas en habilidades y perfil.
  * Herramientas de cotización automática y segura.
  * Historial de trabajos realizados.
  * Cobros seguros y automatizados.
  * Comunicación fluida dentro de la plataforma.

**Segmento objetivo #2: Personas y Emprendimientos que buscan contratar servicios freelance**

* **Motivaciones principales:**
  * Externalizar tareas específicas (diseño, marketing, desarrollo web).
  * Falta de tiempo o conocimiento técnico para tareas clave del negocio.
  * Necesidad de soluciones rápidas y flexibles sin contratar personal fijo.
* **Problemas identificados:**
  * Desconfianza al contratar freelancers sin referencias.
  * Miedo a mala calidad, incumplimiento o falta de responsabilidad.
  * Inseguridad para negociar precios o gestionar pagos.
* **Requisitos para una plataforma ideal:**
  * Perfiles detallados con muestras de trabajo previas.
  * Sistema de calificaciones y opiniones verificadas.
  * Gestión clara de pagos y acuerdos dentro de la plataforma.
  * Chat interno, reuniones virtuales y acuerdos escritos.
  * Negociación dentro de rangos sugeridos.
  * Visualización clara del costo total del proyecto.

### 2.3.1. User Personas

A partir del análisis anterior se construyeron dos *User Personas* que representan arquetípicamente a cada segmento. Estos perfiles orientarán las decisiones de diseño y priorización del Product Backlog.

User Persona del Usuario Estudiante Freelancer:
<img src="imgs/UserPersona1.png" alt="UserPersona1" title="UserPersona1"/>

User Persona del Usuario Persona o Emprendimiento:
<img src="imgs/UserPersona2.png" alt="UserPersona2" title="UserPersona2"/>

### 2.3.2. User Task Matrix

La *User Task Matrix* cruza las tareas clave identificadas con la frecuencia e importancia que cada *User Persona* les asigna. Este artefacto nos permite priorizar funcionalidades en las fases de arquitectura e implementación.

| USER TASK                                         | Julio Bernal (Freelancer) |            | Luisa Fuentes (Cliente) |            |
| :------------------------------------------------ | :-----------------------: | :--------: | :---------------------: | :--------: |
|                                                   |         Frequency         | Importance |        Frequency        | Importance |
| Publicar servicios y mostrar habilidades          |           Often           |    High    |        Sometimes        |    High    |
| Cotizar precios fácilmente según tipo de trabajo  |         Sometimes         |    High    |          Often          |    High    |
| Encontrar oportunidades mediante una app central  |         Sometimes         |    High    |          Often          |   Medium   |
| Procesar pagos seguros a través de la plataforma  |           Always          |    High    |          Always         |    High    |
| Mostrar historial de trabajos realizados          |         Sometimes         |   Medium   |          Often          |   Medium   |
| Negociar precios dentro de un rango flexible      |         Sometimes         |   Medium   |          Always         |    High    |
| Establecer acuerdos y comunicación en la plataforma |         Often           |    High    |          Always         |    High    |

### 2.3.3. Empathy Maps

Los *Empathy Maps* permiten construir una comprensión profunda de la perspectiva y experiencia de cada *User Persona*. Para cada perfil se describe lo que el usuario **ve, escucha, dice, hace y siente**, así como sus *pains* y *gains*, lo que habilita decisiones de diseño centradas en el usuario.

Empathy Map del Estudiante Freelancer:
<img src="imgs/Empathymap1.png" alt="Empathymap1" title="Empathymap1"/>

Empathy Map de Persona o Empresa:
<img src="imgs/Empathymap2.png" alt="Empathymap2" title="Empathymap2"/>

### 2.3.4. As-Is Scenario Mapping

El *As-Is Scenario Mapping* refleja el estado actual de la experiencia de cada segmento **antes** de utilizar GigU. Recorre las fases típicas —desde la búsqueda de oportunidades o de talento, pasando por la contratación, ejecución y cobro— e identifica emociones, acciones y puntos de dolor en cada paso. Este artefacto es la línea base sobre la que, en el Capítulo III, se diseñará el *To-Be Scenario*.

As-Is del Estudiante Freelancer (búsqueda de clientes, negociación informal y cobro mediante Yape/transferencias):
<img src="imgs/AS-IS1.png" alt="AS-IS1" title="AS-IS1"/>

As-Is de Persona o Emprendimiento (búsqueda de freelancers vía redes, contratación sin contratos formales y coordinación manual de pagos):
<img src="imgs/AS-IS2.png" alt="AS-IS2" title="AS-IS2"/>

<div style="page-break-before: always;"></div>

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

Se realizaron los siguientes cuadros en la herramienta Miro, el link original puede ser observado aquí: 

[LINK TO-BE](https://miro.com/app/board/uXjVIFvzuZo=/?share_link_id=785027992176)

* To-Be Scenario Mapping para Estudiantes Universitarios Freelancers
<img src="imgs/TO-BE1.png" alt="To-Be" title="To-BeScenarioMapping"/>

* To-Be Scenario Mapping para Personas y Emprendimientos que buscan contratar servicios Freelance

<img src="imgs/TO-BE2.png" alt="To-Be" title="To-BeScenarioMapping"/>

## 3.2. User Stories

* EPICS
Las epics definidas para el proyecto GigU están orientadas a cubrir las necesidades principales tanto de los estudiantes de la UPC como de los usuarios que buscan contratar servicios freelance. Estas epics abordan funcionalidades esenciales para el funcionamiento de la plataforma, asegurando una experiencia fluida y efectiva desde la publicación de habilidades por parte de los estudiantes hasta la contratación por parte de clientes o emprendimientos. Desde la interfaz de la landing page, donde los usuarios conocen la propuesta de valor de GigU, hasta la gestión técnica del backend, frontend y servicios web, las epics actúan como una guía estructurada que facilita el desarrollo progresivo y coherente del sistema, alineándose con los objetivos académicos y de empleabilidad del proyecto.

| Epic / Story ID | Título | Descripción |
| :---: | ----- | ----- |
| EP01 | Navegación en Landing Page | Como visitante de GigU, deseo poder navegar de forma intuitiva por la landing page para conocer los beneficios de contratar o publicar servicios. |
| EP02 | Autenticación y Registro de Usuarios | Como usuario nuevo, deseo registrarme e iniciar sesión utilizando correo o redes sociales para acceder a mi cuenta de manera rápida y segura. |
| EP03 | Recuperación de Contraseña | Como usuario registrado, deseo recuperar mi contraseña fácilmente para poder acceder nuevamente en caso de olvidarla. |
| EP04 | Visualización de Servicios y Beneficios | Como visitante, deseo conocer los tipos de servicios disponibles y cómo funciona GigU para saber cómo puede ayudarme a contratar o ser contratado. |
| EP05 | Soporte y FAQ | Como visitante, deseo acceder a una sección de preguntas frecuentes y soporte para resolver mis dudas de forma autónoma y rápida. |
| EP06 | Gestión de Perfil Freelance | Como estudiante, deseo crear y editar mi perfil público con información, habilidades y precios para que posibles clientes conozcan mis servicios. |
| EP07 | Publicación y Edición de Servicios | Como estudiante, deseo publicar servicios personalizados con precios, plazos y descripciones claras para atraer clientes interesados. |
| EP08 | Búsqueda y Filtro de Freelancers | Como cliente, deseo buscar freelancers y filtrar por habilidades, precio o disponibilidad para encontrar al más adecuado para mi proyecto. |
| EP09 | Sistema de Contratación Directa | Como cliente, deseo contratar directamente a un freelancer desde su perfil para simplificar el proceso de contratación. |
| EP10 | Gestión de Proyectos y Solicitudes | Como freelancer, deseo gestionar las solicitudes recibidas y proyectos activos para poder organizar mejor mi trabajo y tiempos. |
| EP11 | Calificaciones y Opiniones | Como usuario, deseo dejar y ver calificaciones y comentarios sobre los freelancers para tomar decisiones más informadas. |
| EP12 | Sistema de Mensajería Interna | Como usuario, deseo comunicarme directamente dentro de la plataforma con el otro usuario para coordinar detalles antes o durante un proyecto. |
| EP13 | Cálculo Inteligente de Precio del Servicio | Como usuario, deseo que la plataforma sugiera un precio justo basado en la propuesta del freelancer, la oferta del cliente, el tipo y tamaño del servicio, y la experiencia del freelancer, para facilitar acuerdos equilibrados entre ambas partes. |

* User Stories


| Story ID                | User                                                                                                                                                                                                                                                                                                                  | Priority | Epic |
| :---------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US01                    | Visitante de GigU                                                                                                                                                                                                                                                                                                     | Alta     | EP01 |
| **Title**               | Navegar de forma intuitiva en la landing page                                                                                                                                                                                                                                                                         |          |      |
| **Description**         | Como visitante de GigU, deseo que la landing page tenga una barra de navegación clara y accesible para encontrar fácilmente las secciones importantes.                                                                                                                                                                |          |      |
|                         |                                                                                                                                                                                                                                                                                                                       |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que un visitante está en la landing page, cuando consulta el menú de navegación, entonces el sistema muestra las secciones principales del sitio.<br><br>**Escenario 02:** Dado que un visitante navega por la página, cuando cambia de sección, entonces el sistema indica la sección activa. |          |      |




| Story ID                | User                                                                                                                                                                                                                                                                                                                                                                  | Priority | Epic |
| :---------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US02                    | Visitante                                                                                                                                                                                                                                                                                                                                                             | Alta     | EP01 |
| **Title**               | Acceder rápidamente a funcionalidades clave                                                                                                                                                                                                                                                                                                                           |          |      |
| **Description**         | Como visitante, deseo acceder desde la landing page a secciones clave como publicar proyecto o registrarme para actuar rápidamente.                                                                                                                                                                                                                                   |          |      |
|                         |                                                                                                                                                                                                                                                                                                                                                                       |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que un visitante está en la landing page, cuando busca acciones principales, entonces el sistema muestra accesos visibles a funcionalidades clave.<br><br>**Escenario 02:** Dado que un visitante selecciona una acción principal, cuando solicita registrarse o publicar un proyecto, entonces el sistema lo dirige al flujo correspondiente. |          |      |




| Story ID                | User                                                                                                                                                                                                                                                                                                                                               | Priority | Epic |
| :---------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US03                    | Visitante de GigU                                                                                                                                                                                                                                                                                                                                  | Alta     | EP01 |
| **Title**               | Navegar por la landing page con menú claro                                                                                                                                                                                                                                                                                                         |          |      |
| **Description**         | Como visitante de GigU, deseo que la landing page tenga una barra de navegación clara para encontrar fácilmente las secciones importantes.                                                                                                                                                                                                         |          |      |
|                         |                                                                                                                                                                                                                                                                                                                                                    |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que un visitante accede a la landing page, cuando consulta el menú, entonces el sistema presenta las secciones relevantes de forma estructurada.<br><br>**Escenario 02:** Dado que un visitante navega entre secciones, cuando usa el menú, entonces el sistema mantiene coherencia en el orden y nombres de las secciones. |          |      |




| Story ID                | User                                                                                                                                                                                                                                                                                                                              | Priority | Epic |
| :---------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US04                    | Usuario registrado                                                                                                                                                                                                                                                                                                                | Alta     | EP02 |
| **Title**               | Iniciar sesión como freelancer o cliente                                                                                                                                                                                                                                                                                          |          |      |
| **Description**         | Como usuario registrado, deseo poder iniciar sesión para acceder a mi cuenta y funcionalidades específicas según mi rol.                                                                                                                                                                                                          |          |      |
|                         |                                                                                                                                                                                                                                                                                                                                   |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que un usuario proporciona credenciales válidas, cuando el sistema procesa el inicio de sesión, entonces habilita las funcionalidades según su rol.<br><br>**Escenario 02:** Dado que un usuario proporciona credenciales incorrectas, cuando intenta autenticarse, entonces el sistema rechaza el acceso. |          |      |




| Story ID                | User                                                                                                                                                                                                                                                                                                                                     | Priority | Epic |
| :---------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US05                    | Visitante                                                                                                                                                                                                                                                                                                                                | Alta     | EP02 |
| **Title**               | Registrarse con cuenta de Google                                                                                                                                                                                                                                                                                                         |          |      |
| **Description**         | Como visitante, deseo registrarme con Google para agilizar el proceso de creación de cuenta.                                                                                                                                                                                                                                             |          |      |
|                         |                                                                                                                                                                                                                                                                                                                                          |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que un visitante elige registrarse con Google, cuando autoriza el uso de sus datos básicos, entonces el sistema crea su cuenta.<br><br>**Escenario 02:** Dado que una cuenta de Google ya está registrada, cuando intenta registrarse nuevamente, entonces el sistema notifica que ya existe una cuenta asociada. |          |      |




| Story ID                | User                                                                                                                                                                                                                                                                                                                              | Priority | Epic |
| :---------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US06                    | Usuario                                                                                                                                                                                                                                                                                                                           | Alta     | EP03 |
| **Title**               | Solicitar recuperación de contraseña                                                                                                                                                                                                                                                                                              |          |      |
| **Description**         | Como usuario, deseo solicitar la recuperación de mi contraseña para volver a acceder si la olvido.                                                                                                                                                                                                                                |          |      |
|                         |                                                                                                                                                                                                                                                                                                                                   |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que un usuario olvidó su contraseña, cuando proporciona un correo registrado, entonces el sistema genera un mecanismo seguro de recuperación.<br><br>**Escenario 02:** Dado que ingresa un correo no registrado, cuando solicita recuperar, entonces el sistema informa que no existe una cuenta asociada. |          |      |




| Story ID                | User                                                                                                                                                                                                                                                                    | Priority | Epic |
| :---------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US07                    | Usuario                                                                                                                                                                                                                                                                 | Alta     | EP03 |
| **Title**               | Restablecer contraseña mediante enlace seguro                                                                                                                                                                                                                           |          |      |
| **Description**         | Como usuario, deseo restablecer mi contraseña usando un enlace enviado a mi correo.                                                                                                                                                                                     |          |      |
|                         |                                                                                                                                                                                                                                                                         |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que un usuario recibe un enlace válido, cuando accede a él, entonces puede crear una nueva contraseña.<br><br>**Escenario 02:** Dado que ingresa una contraseña inválida, cuando intenta registrarla, entonces el sistema notifica la invalidez. |          |      |




| Story ID                | User                                                                                                                                                                                                                                                                                                                      | Priority | Epic |
| :---------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :------- | :--- |
| US08                    | Visitante                                                                                                                                                                                                                                                                                                                 | Media    | EP04 |
| **Title**               | Conocer los beneficios de GigU                                                                                                                                                                                                                                                                                            |          |      |
| **Description**         | Como visitante, deseo conocer los beneficios de usar GigU para entender por qué debería utilizar la plataforma.                                                                                                                                                                                                           |          |      |
|                         |                                                                                                                                                                                                                                                                                                                           |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que un visitante accede a la sección de información, cuando consulta los beneficios, entonces el sistema presenta los principales beneficios de la plataforma.<br><br>**Escenario 02:** Dado que selecciona un beneficio, cuando solicita ampliación, entonces recibe más información explicativa. |          |      |




| Story ID                | User                                                                                                                                                                                                                                                                                                                           | Priority | Epic |
| :---------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US09                    | Visitante                                                                                                                                                                                                                                                                                                                      | Media    | EP04 |
| **Title**               | Conocer diferencias entre roles                                                                                                                                                                                                                                                                                                |          |      |
| **Description**         | Como visitante, deseo saber las diferencias entre registrarme como freelancer o cliente para elegir el rol adecuado.                                                                                                                                                                                                           |          |      |
|                         |                                                                                                                                                                                                                                                                                                                                |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que un visitante revisa la sección de roles, cuando consulta la información, entonces el sistema muestra comparaciones claras.<br><br>**Escenario 02:** Dado que el visitante selecciona un rol, cuando consulta más detalles, entonces el sistema muestra información específica del flujo de ese rol. |          |      |




| Story ID                | User                                                                                                                                                                                                                                                                                                                 | Priority | Epic |
| :---------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US10                    | Visitante                                                                                                                                                                                                                                                                                                            | Media    | EP04 |
| **Title**               | Ver experiencias de otros usuarios                                                                                                                                                                                                                                                                                   |          |      |
| **Description**         | Como visitante, deseo ver testimonios de usuarios anteriores para confiar en la plataforma.                                                                                                                                                                                                                          |          |      |
|                         |                                                                                                                                                                                                                                                                                                                      |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que un visitante accede a la sección de experiencias, cuando visualiza testimonios, entonces el sistema muestra nombre, rol y comentario.<br><br>**Escenario 02:** Dado que solicita ver más testimonios, cuando el sistema detecta la acción, entonces muestra más experiencias registradas. |          |      |




| Story ID                | User                                                                                                                                                                                                                                                                                                | Priority | Epic |
| :---------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US11                    | Visitante                                                                                                                                                                                                                                                                                           | Media    | EP04 |
| **Title**               | Conocer tipos de servicios disponibles                                                                                                                                                                                                                                                              |          |      |
| **Description**         | Como visitante, deseo conocer los tipos de servicios que puedo contratar o brindar en GigU.                                                                                                                                                                                                         |          |      |
|                         |                                                                                                                                                                                                                                                                                                     |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que un visitante consulta la sección de tipos de servicios, cuando selecciona uno, entonces el sistema muestra su descripción.<br><br>**Escenario 02:** Dado que desea más información, cuando selecciona detalles, entonces el sistema presenta casos prácticos y ejemplos. |          |      |




| Story ID                | User                                                                                                                                                                                                                                                                                                                  | Priority | Epic |
| :---------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US12                    | Visitante                                                                                                                                                                                                                                                                                                             | Media    | EP05 |
| **Title**               | Acceder a preguntas frecuentes                                                                                                                                                                                                                                                                                        |          |      |
| **Description**         | Como visitante, deseo ver una sección de preguntas frecuentes para resolver dudas comunes sin ayuda externa.                                                                                                                                                                                                          |          |      |
|                         |                                                                                                                                                                                                                                                                                                                       |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que un visitante accede a FAQ, cuando consulta las preguntas, entonces el sistema muestra un listado con respuestas.<br><br>**Escenario 02:** Dado que selecciona una pregunta, cuando visualiza o cierra la respuesta, entonces el sistema muestra u oculta la información según corresponda. |          |      |




| Story ID                | User                                                                                                                                                                                                                                                                                                              | Priority | Epic |
| :---------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US13                    | Usuario                                                                                                                                                                                                                                                                                                           | Media    | EP05 |
| **Title**               | Buscar información dentro de preguntas frecuentes                                                                                                                                                                                                                                                                 |          |      |
| **Description**         | Como usuario, deseo buscar palabras clave en la sección de FAQ para encontrar respuestas más rápido.                                                                                                                                                                                                              |          |      |
|                         |                                                                                                                                                                                                                                                                                                                   |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que un usuario busca información, cuando ingresa una palabra clave, entonces el sistema muestra las preguntas relacionadas.<br><br>**Escenario 02:** Dado que la búsqueda no tiene coincidencias, cuando el sistema procesa el término, entonces informa que no se encontraron resultados. |          |      |




| Story ID                | User                                                                                                                                                                                                                                                                                                                      | Priority | Epic |
| :---------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :------- | :--- |
| US14                    | Usuario                                                                                                                                                                                                                                                                                                                   | Media    | EP05 |
| **Title**               | Enviar un ticket de soporte                                                                                                                                                                                                                                                                                               |          |      |
| **Description**         | Como usuario, deseo enviar un mensaje de soporte si no encuentro mi duda en la FAQ para recibir asistencia personalizada.                                                                                                                                                                                                 |          |      |
|                         |                                                                                                                                                                                                                                                                                                                           |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que un usuario no encuentra solución, cuando proporciona la información necesaria, entonces el sistema registra el ticket.<br><br>**Escenario 02:** Dado que los datos están incompletos, cuando intenta registrar el ticket, entonces el sistema rechaza el envío e informa los campos faltantes. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                                                                                                                | Priority | Epic |
| :---------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :------- | :--- |
| US15                    | Estudiante                                                                                                                                                                                                                                                                                                                                                          | Alta     | EP06 |
| **Title**               | Crear perfil freelance                                                                                                                                                                                                                                                                                                                                              |          |      |
| **Description**         | Como estudiante, deseo crear mi perfil freelance con mi nombre, carrera y universidad para que los clientes conozcan mi identidad profesional.                                                                                                                                                                                                                      |          |      |
|                         |                                                                                                                                                                                                                                                                                                                                                                     |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que un estudiante accede a la creación de perfil, cuando proporciona información válida como nombre, carrera y universidad, entonces el sistema registra el perfil y lo deja disponible.<br><br>**Escenario 02:** Dado que el estudiante completa el registro, cuando el sistema valida los datos, entonces confirma la creación del perfil. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                                                                        | Priority | Epic |
| :---------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US16                    | Freelancer                                                                                                                                                                                                                                                                                                                  | Alta     | EP06 |
| **Title**               | Añadir habilidades y descripción personal                                                                                                                                                                                                                                                                                   |          |      |
| **Description**         | Como freelancer, deseo añadir habilidades y una descripción personal para destacar mis fortalezas.                                                                                                                                                                                                                          |          |      |
|                         |                                                                                                                                                                                                                                                                                                                             |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que un freelancer edita su perfil, cuando añade habilidades y descripción válida, entonces el sistema almacena la información.<br><br>**Escenario 02:** Dado que el freelancer actualiza sus habilidades, cuando consulta su perfil público, entonces el sistema muestra la información actualizada. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                                                                                        | Priority | Epic |
| :---------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :------- | :--- |
| US17                    | Freelancer                                                                                                                                                                                                                                                                                                                                  | Alta     | EP06 |
| **Title**               | Establecer tarifas por servicio                                                                                                                                                                                                                                                                                                             |          |      |
| **Description**         | Como freelancer, deseo establecer mis tarifas por tipo de servicio para que los clientes conozcan mis precios.                                                                                                                                                                                                                              |          |      |
|                         |                                                                                                                                                                                                                                                                                                                                             |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que un freelancer asigna una tarifa válida, cuando el sistema valida el valor ingresado, entonces registra el precio y lo muestra públicamente.<br><br>**Escenario 02:** Dado que el freelancer ingresa un valor fuera de rango, cuando intenta guardarlo, entonces el sistema rechaza la tarifa e informa el error. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                                                                          | Priority | Epic |
| :---------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US18                    | Freelancer                                                                                                                                                                                                                                                                                                                    | Media    | EP06 |
| **Title**               | Subir portafolio de proyectos                                                                                                                                                                                                                                                                                                 |          |      |
| **Description**         | Como freelancer, deseo subir muestras de trabajos anteriores para demostrar mi experiencia a los clientes.                                                                                                                                                                                                                    |          |      |
|                         |                                                                                                                                                                                                                                                                                                                               |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que un freelancer proporciona archivos o enlaces válidos, cuando el sistema valida el contenido, entonces lo almacena y muestra en su perfil.<br><br>**Escenario 02:** Dado que intenta subir un archivo no permitido, cuando el sistema valida el tipo, entonces rechaza la carga e informa el error. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                                                    | Priority | Epic |
| :---------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :------- | :--- |
| US19                    | Freelancer                                                                                                                                                                                                                                                                                              | Alta     | EP06 |
| **Title**               | Actualizar perfil freelance                                                                                                                                                                                                                                                                             |          |      |
| **Description**         | Como freelancer, deseo poder actualizar mi perfil cuando quiera para mantener mi información al día.                                                                                                                                                                                                    |          |      |
|                         |                                                                                                                                                                                                                                                                                                         |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que un freelancer modifica datos válidos, cuando el sistema los valida, entonces actualiza la información públicamente.<br><br>**Escenario 02:** Dado que el perfil es actualizado, cuando consulta su vista pública, entonces los cambios se muestran sin procesos adicionales. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                                | Priority | Epic |
| :---------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US20                    | Freelancer                                                                                                                                                                                                                                                                          | Alta     | EP07 |
| **Title**               | Publicar un servicio personalizado                                                                                                                                                                                                                                                  |          |      |
| **Description**         | Como freelancer, deseo publicar un servicio con título, descripción y precio para ofrecerlo a potenciales clientes.                                                                                                                                                                 |          |      |
|                         |                                                                                                                                                                                                                                                                                     |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que un freelancer completa los datos del servicio, cuando el sistema los valida, entonces registra la publicación.<br><br>**Escenario 02:** Dado que falta un campo obligatorio, cuando intenta guardar, entonces el sistema indica la información faltante. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                       | Priority | Epic |
| :---------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US21                    | Freelancer                                                                                                                                                                                                                                                                 | Media    | EP07 |
| **Title**               | Establecer plazos de entrega                                                                                                                                                                                                                                               |          |      |
| **Description**         | Como freelancer, deseo definir el tiempo de entrega estimado para que el cliente tenga expectativas claras.                                                                                                                                                                |          |      |
|                         |                                                                                                                                                                                                                                                                            |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que un freelancer define un plazo, cuando el sistema valida el valor, entonces lo registra y muestra públicamente.<br><br>**Escenario 02:** Dado que el plazo está registrado, cuando el servicio se consulta, entonces incluye los días estimados. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                                 | Priority | Epic |
| :---------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US22                    | Freelancer                                                                                                                                                                                                                                                                           | Media    | EP07 |
| **Title**               | Editar servicios publicados                                                                                                                                                                                                                                                          |          |      |
| **Description**         | Como freelancer, deseo editar mis servicios publicados para corregir errores o actualizar precios.                                                                                                                                                                                   |          |      |
|                         |                                                                                                                                                                                                                                                                                      |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que un freelancer modifica la información de un servicio, cuando el sistema la valida, entonces actualiza la publicación.<br><br>**Escenario 02:** Dado que el servicio es editado, cuando un usuario lo consulta, entonces visualiza la versión actualizada. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                                                                      | Priority | Epic |
| :---------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :------- | :--- |
| US23                    | Freelancer                                                                                                                                                                                                                                                                                                                | Media    | EP07 |
| **Title**               | Pausar o eliminar servicios publicados                                                                                                                                                                                                                                                                                    |          |      |
| **Description**         | Como freelancer, deseo pausar o eliminar mis servicios cuando ya no desee ofrecerlos.                                                                                                                                                                                                                                     |          |      |
|                         |                                                                                                                                                                                                                                                                                                                           |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que un freelancer decide pausar o eliminar un servicio, cuando el sistema procesa la acción, entonces lo retira de la vista pública.<br><br>**Escenario 02:** Dado que el servicio está pausado o eliminado, cuando el freelancer revisa su listado, entonces el sistema muestra su estado actual. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                                                       | Priority | Epic |
| :---------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US24                    | Freelancer                                                                                                                                                                                                                                                                                                 | Media    | EP07 |
| **Title**               | Añadir imágenes o archivos al servicio                                                                                                                                                                                                                                                                     |          |      |
| **Description**         | Como freelancer, deseo subir imágenes o archivos a mis servicios para facilitar la comprensión del cliente.                                                                                                                                                                                                |          |      |
|                         |                                                                                                                                                                                                                                                                                                            |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que un freelancer sube archivos permitidos, cuando el sistema valida el contenido, entonces los muestra asociados al servicio.<br><br>**Escenario 02:** Dado que sube múltiples imágenes, cuando el servicio se visualiza, entonces el sistema permite recorrerlas secuencialmente. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                                                 | Priority | Epic |
| :---------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US25                    | Cliente                                                                                                                                                                                                                                                                                              | Alta     | EP08 |
| **Title**               | Buscar freelancers por palabra clave                                                                                                                                                                                                                                                                 |          |      |
| **Description**         | Como cliente, deseo buscar freelancers usando palabras clave para encontrar rápidamente lo que necesito.                                                                                                                                                                                             |          |      |
|                         |                                                                                                                                                                                                                                                                                                      |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que un cliente ingresa una palabra clave, cuando el sistema procesa la búsqueda, entonces muestra freelancers relacionados.<br><br>**Escenario 02:** Dado que ingresa múltiples palabras, cuando el sistema filtra, entonces muestra coincidencias con al menos una de ellas. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                                                                 | Priority | Epic |
| :---------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US26                    | Cliente                                                                                                                                                                                                                                                                                                              | Alta     | EP08 |
| **Title**               | Filtrar freelancers por habilidad                                                                                                                                                                                                                                                                                    |          |      |
| **Description**         | Como cliente, deseo filtrar freelancers según sus habilidades para encontrar al más apto para mi proyecto.                                                                                                                                                                                                           |          |      |
|                         |                                                                                                                                                                                                                                                                                                                      |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que el cliente selecciona una habilidad, cuando el sistema filtra, entonces muestra solo freelancers que la tengan registrada.<br><br>**Escenario 02:** Dado que selecciona varias habilidades, cuando el sistema filtra, entonces muestra freelancers que cumplan con al menos una de ellas. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                              | Priority | Epic |
| :---------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US27                    | Cliente                                                                                                                                                                                                                                                                           | Media    | EP08 |
| **Title**               | Filtrar por rango de precios                                                                                                                                                                                                                                                      |          |      |
| **Description**         | Como cliente, deseo establecer un rango de precios para ver freelancers dentro de mi presupuesto.                                                                                                                                                                                 |          |      |
|                         |                                                                                                                                                                                                                                                                                   |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que el cliente define un rango, cuando el sistema filtra, entonces muestra freelancers dentro del presupuesto.<br><br>**Escenario 02:** Dado que no existen coincidencias, cuando el sistema completa el filtrado, entonces informa que no hay resultados. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                                                                    | Priority | Epic |
| :---------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US28                    | Cliente                                                                                                                                                                                                                                                                                                                 | Media    | EP08 |
| **Title**               | Filtrar freelancers por experiencia                                                                                                                                                                                                                                                                                     |          |      |
| **Description**         | Como cliente, deseo filtrar freelancers según su nivel de experiencia para elegir al adecuado.                                                                                                                                                                                                                          |          |      |
|                         |                                                                                                                                                                                                                                                                                                                         |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que un cliente selecciona un nivel, cuando el sistema procesa el filtro, entonces muestra freelancers con dicho nivel.<br><br>**Escenario 02:** Dado que el freelancer tiene nivel registrado, cuando aparece en los resultados, entonces el sistema muestra su nivel en la tarjeta informativa. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                                     | Priority | Epic |
| :---------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US29                    | Cliente                                                                                                                                                                                                                                                                                  | Media    | EP08 |
| **Title**               | Ordenar resultados de búsqueda                                                                                                                                                                                                                                                           |          |      |
| **Description**         | Como cliente, deseo ordenar resultados por relevancia o calificación para comparar perfiles.                                                                                                                                                                                             |          |      |
|                         |                                                                                                                                                                                                                                                                                          |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que un cliente elige un criterio de ordenamiento, cuando el sistema procesa la solicitud, entonces reordena los resultados.<br><br>**Escenario 02:** Dado que cambia el criterio, cuando se muestran los resultados, entonces se mantienen los filtros aplicados. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                                                            | Priority | Epic |
| :---------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US30                    | Cliente                                                                                                                                                                                                                                                                                                         | Alta     | EP09 |
| **Title**               | Contratar desde el perfil del freelancer                                                                                                                                                                                                                                                                        |          |      |
| **Description**         | Como cliente, deseo contratar a un freelancer directamente desde su perfil para ahorrar tiempo al iniciar una negociación.                                                                                                                                                                                      |          |      |
|                         |                                                                                                                                                                                                                                                                                                                 |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que un cliente consulta el perfil del freelancer, cuando envía una solicitud de contratación, entonces el sistema registra la solicitud.<br><br>**Escenario 02:** Dado que la contratación fue iniciada, cuando el sistema la procesa, entonces se registra en el historial del cliente. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                                                           | Priority | Epic |
| :---------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US31                    | Cliente                                                                                                                                                                                                                                                                                                        | Media    | EP09 |
| **Title**               | Confirmación de contratación exitosa                                                                                                                                                                                                                                                                           |          |      |
| **Description**         | Como cliente, deseo recibir confirmación del sistema y por correo al contratar a un freelancer.                                                                                                                                                                                                                |          |      |
|                         |                                                                                                                                                                                                                                                                                                                |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que la contratación es procesada, cuando el sistema finaliza el registro, entonces muestra una confirmación en pantalla.<br><br>**Escenario 02:** Dado que la contratación fue exitosa, cuando el sistema envía la notificación, entonces el cliente recibe un correo con los detalles. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                                 | Priority | Epic |
| :---------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US32                    | Freelancer                                                                                                                                                                                                                                                                           | Media    | EP09 |
| **Title**               | Aceptar o rechazar solicitud de contrato                                                                                                                                                                                                                                             |          |      |
| **Description**         | Como freelancer, deseo aceptar o rechazar solicitudes de contratación para gestionar mi disponibilidad.                                                                                                                                                                              |          |      |
|                         |                                                                                                                                                                                                                                                                                      |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que un freelancer recibe una solicitud, cuando consulta los detalles, entonces puede aceptarla o rechazarla.<br><br>**Escenario 02:** Dado que rechaza una solicitud, cuando registra la acción, entonces el sistema almacena el motivo si fue proporcionado. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                                                | Priority | Epic |
| :---------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US33                    | Cliente                                                                                                                                                                                                                                                                                             | Media    | EP09 |
| **Title**               | Ver historial de contrataciones                                                                                                                                                                                                                                                                     |          |      |
| **Description**         | Como cliente, deseo ver un historial de mis contrataciones para tener un registro de mis actividades.                                                                                                                                                                                               |          |      |
|                         |                                                                                                                                                                                                                                                                                                     |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que el cliente ha realizado contrataciones, cuando accede al historial, entonces el sistema muestra la lista con fechas y estados.<br><br>**Escenario 02:** Dado que selecciona una contratación, cuando solicita más información, entonces el sistema muestra los detalles. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                                                                                           | Priority | Epic |
| :---------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US34                    | Freelancer                                                                                                                                                                                                                                                                                                                                     | Alta     | EP10 |
| **Title**               | Visualizar proyectos activos                                                                                                                                                                                                                                                                                                                   |          |      |
| **Description**         | Como freelancer, deseo ver una lista de mis proyectos activos para organizar mi trabajo.                                                                                                                                                                                                                                                       |          |      |
|                         |                                                                                                                                                                                                                                                                                                                                                |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que existen proyectos activos, cuando el freelancer accede al listado, entonces el sistema muestra los proyectos con su información relevante.<br><br>**Escenario 02:** Dado que existen múltiples proyectos, cuando el freelancer solicita ordenarlos, entonces el sistema permite ordenarlos por criterios definidos. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                                            | Priority | Epic |
| :---------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US35                    | Freelancer                                                                                                                                                                                                                                                                                      | Alta     | EP10 |
| **Title**               | Gestionar solicitudes recibidas                                                                                                                                                                                                                                                                 |          |      |
| **Description**         | Como freelancer, deseo revisar y gestionar solicitudes de nuevos proyectos para aceptar las que se ajusten a mi disponibilidad.                                                                                                                                                                 |          |      |
|                         |                                                                                                                                                                                                                                                                                                 |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que el freelancer tiene solicitudes pendientes, cuando accede al panel, entonces el sistema muestra los detalles de cada solicitud.<br><br>**Escenario 02:** Dado que acepta o rechaza una solicitud, cuando el sistema procesa la acción, entonces actualiza su estado. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                             | Priority | Epic |
| :---------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US36                    | Freelancer                                                                                                                                                                                                                                                                       | Media    | EP10 |
| **Title**               | Marcar proyecto como finalizado                                                                                                                                                                                                                                                  |          |      |
| **Description**         | Como freelancer, deseo marcar un proyecto como finalizado para indicar que mi trabajo fue completado.                                                                                                                                                                            |          |      |
|                         |                                                                                                                                                                                                                                                                                  |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que un freelancer concluye un proyecto, cuando lo marca como finalizado, entonces el sistema actualiza su estado.<br><br>**Escenario 02:** Dado que un proyecto está finalizado, cuando el cliente lo consulta, entonces visualiza su estado actualizado. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                                                | Priority | Epic |
| :---------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US37                    | Cliente                                                                                                                                                                                                                                                                                             | Media    | EP10 |
| **Title**               | Ver estado del proyecto                                                                                                                                                                                                                                                                             |          |      |
| **Description**         | Como cliente, deseo ver el estado de mis proyectos en curso para saber si están en espera, en proceso o finalizados.                                                                                                                                                                                |          |      |
|                         |                                                                                                                                                                                                                                                                                                     |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que el cliente consulta sus proyectos, cuando accede al listado, entonces el sistema muestra su estado actual.<br><br>**Escenario 02:** Dado que un proyecto cambia de estado, cuando el cliente consulta su historial, entonces el sistema muestra los cambios registrados. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                          | Priority | Epic |
| :---------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US38                    | Cliente                                                                                                                                                                                                                                                                       | Media    | EP11 |
| **Title**               | Calificar al freelancer                                                                                                                                                                                                                                                       |          |      |
| **Description**         | Como cliente, deseo calificar al freelancer al finalizar un proyecto para compartir mi experiencia.                                                                                                                                                                           |          |      |
|                         |                                                                                                                                                                                                                                                                               |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que un proyecto finalizó, cuando el cliente registra una calificación con comentario, entonces el sistema guarda la reseña.<br><br>**Escenario 02:** Dado que ya calificó, cuando consulta el proyecto, entonces visualiza la calificación registrada. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                                                                             | Priority | Epic |
| :---------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US39                    | Cliente                                                                                                                                                                                                                                                                                                                          | Media    | EP11 |
| **Title**               | Ver calificaciones del freelancer                                                                                                                                                                                                                                                                                                |          |      |
| **Description**         | Como cliente, deseo ver las calificaciones que otros usuarios han dejado a un freelancer antes de contratarlo.                                                                                                                                                                                                                   |          |      |
|                         |                                                                                                                                                                                                                                                                                                                                  |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que un cliente visita un perfil, cuando consulta la sección de calificaciones, entonces visualiza el promedio y comentarios existentes.<br><br>**Escenario 02:** Dado que un comentario tiene más contenido, cuando el cliente solicita verlo completo, entonces el sistema muestra la versión extendida. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                                                               | Priority | Epic |
| :---------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US40                    | Cliente                                                                                                                                                                                                                                                                                                            | Baja     | EP11 |
| **Title**               | Editar calificación después de un proyecto                                                                                                                                                                                                                                                                         |          |      |
| **Description**         | Como cliente, deseo editar una calificación si cometí un error o si el freelancer mejoró tras retroalimentación.                                                                                                                                                                                                   |          |      |
|                         |                                                                                                                                                                                                                                                                                                                    |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que el cliente escribió una reseña, cuando solicita editarla, entonces el sistema permite cambiar puntuación y comentario.<br><br>**Escenario 02:** Dado que la reseña es modificada, cuando otros usuarios la visualizan, entonces el sistema muestra que fue editada y registra la fecha. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                                                            | Priority | Epic |
| :---------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US41                    | Freelancer                                                                                                                                                                                                                                                                                                      | Media    | EP11 |
| **Title**               | Calificar al cliente                                                                                                                                                                                                                                                                                            |          |      |
| **Description**         | Como freelancer, deseo calificar al cliente luego de terminar un proyecto para informar a otros freelancers sobre su comportamiento.                                                                                                                                                                            |          |      |
|                         |                                                                                                                                                                                                                                                                                                                 |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que un proyecto terminó, cuando el freelancer registra una calificación y comentario, entonces el sistema guarda la reseña.<br><br>**Escenario 02:** Dado que la calificación fue registrada, cuando el freelancer revisa su historial, entonces visualiza que ya calificó ese proyecto. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                                       | Priority | Epic |
| :---------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US42                    | Usuario                                                                                                                                                                                                                                                                                    | Alta     | EP12 |
| **Title**               | Enviar mensaje a usuario desde perfil                                                                                                                                                                                                                                                      |          |      |
| **Description**         | Como usuario, deseo enviar un mensaje a otro usuario desde su perfil para coordinar detalles.                                                                                                                                                                                              |          |      |
|                         |                                                                                                                                                                                                                                                                                            |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que un usuario accede al perfil de otro, cuando inicia una conversación, entonces el sistema crea el canal de mensajería.<br><br>**Escenario 02:** Dado que se recibe un mensaje, cuando el sistema registra la llegada, entonces notifica dentro de la plataforma. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                                                        | Priority | Epic |
| :---------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US43                    | Usuario                                                                                                                                                                                                                                                                                                     | Media    | EP12 |
| **Title**               | Ver historial de conversaciones                                                                                                                                                                                                                                                                             |          |      |
| **Description**         | Como usuario, deseo ver mi historial de conversaciones previas para recordar acuerdos importantes.                                                                                                                                                                                                          |          |      |
|                         |                                                                                                                                                                                                                                                                                                             |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que el usuario tiene conversaciones previas, cuando accede a la sección de mensajes, entonces el sistema muestra la lista de chats recientes.<br><br>**Escenario 02:** Dado que revisa un chat antiguo, cuando navega hacia arriba, entonces el sistema carga el historial completo. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                          | Priority | Epic |
| :---------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US44                    | Usuario                                                                                                                                                                                                                                                                       | Media    | EP12 |
| **Title**               | Recibir notificación de nuevo mensaje                                                                                                                                                                                                                                         |          |      |
| **Description**         | Como usuario, deseo recibir una notificación cuando me envíen un nuevo mensaje para no perder comunicación importante.                                                                                                                                                        |          |      |
|                         |                                                                                                                                                                                                                                                                               |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que se recibe un mensaje, cuando el sistema lo registra, entonces genera una notificación visible.<br><br>**Escenario 02:** Dado que el usuario está dentro del chat, cuando se envía un mensaje nuevo, entonces aparece automáticamente sin recargar. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                        | Priority | Epic |
| :---------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US45                    | Usuario                                                                                                                                                                                                                                                                     | Media    | EP12 |
| **Title**               | Bloquear o reportar usuario desde el chat                                                                                                                                                                                                                                   |          |      |
| **Description**         | Como usuario, deseo bloquear o reportar a otra persona si recibo mensajes inapropiados o spam.                                                                                                                                                                              |          |      |
|                         |                                                                                                                                                                                                                                                                             |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que un usuario reporta a otro, cuando especifica un motivo válido, entonces el sistema registra el reporte.<br><br>**Escenario 02:** Dado que un usuario bloquea a otro, cuando el sistema procesa la acción, entonces impide futuras interacciones. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                                                     | Priority | Epic |
| :---------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US46                    | Usuario                                                                                                                                                                                                                                                                                                  | Alta     | EP13 |
| **Title**               | Recibir sugerencia automática de precio                                                                                                                                                                                                                                                                  |          |      |
| **Description**         | Como usuario, deseo recibir una sugerencia automática de precio basada en variables del servicio.                                                                                                                                                                                                        |          |      |
|                         |                                                                                                                                                                                                                                                                                                          |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que el usuario especifica tipo de servicio y nivel de experiencia, cuando el sistema procesa los datos, entonces genera una sugerencia automática.<br><br>**Escenario 02:** Dado que el usuario cambia parámetros, cuando el sistema recalcula, entonces actualiza la sugerencia. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                                                                      | Priority | Epic |
| :---------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :------- | :--- |
| US47                    | Usuario                                                                                                                                                                                                                                                                                                                   | Media    | EP13 |
| **Title**               | Ajustar manualmente el precio sugerido                                                                                                                                                                                                                                                                                    |          |      |
| **Description**         | Como usuario, deseo modificar manualmente el precio sugerido para adaptarlo a mis condiciones.                                                                                                                                                                                                                            |          |      |
|                         |                                                                                                                                                                                                                                                                                                                           |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que existe una sugerencia, cuando el usuario ingresa un nuevo valor, entonces el sistema lo registra sin afectar la lógica base.<br><br>**Escenario 02:** Dado que el usuario ya modificó el precio, cuando consulta nuevamente la sección, entonces el sistema muestra el valor manual ingresado. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                                                  | Priority | Epic |
| :---------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US48                    | Usuario                                                                                                                                                                                                                                                                                               | Baja     | EP13 |
| **Title**               | Ver detalle del cálculo del precio                                                                                                                                                                                                                                                                    |          |      |
| **Description**         | Como usuario, deseo ver una explicación breve de cómo se calculó el precio sugerido.                                                                                                                                                                                                                  |          |      |
|                         |                                                                                                                                                                                                                                                                                                       |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que existe una sugerencia, cuando el usuario solicita ver detalles, entonces el sistema muestra los factores utilizados.<br><br>**Escenario 02:** Dado que se muestran factores, cuando el usuario solicita más información de uno, entonces el sistema explica su influencia. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                                                                | Priority | Epic |
| :---------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :------- | :--- |
| US49                    | Usuario                                                                                                                                                                                                                                                                                                             | Media    | EP13 |
| **Title**               | Comparar propuesta y oferta                                                                                                                                                                                                                                                                                         |          |      |
| **Description**         | Como usuario, deseo comparar mi propuesta y la oferta de la otra parte para facilitar un acuerdo.                                                                                                                                                                                                                   |          |      |
|                         |                                                                                                                                                                                                                                                                                                                     |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que ambas partes ingresan valores, cuando el usuario solicita compararlos, entonces el sistema muestra una tabla comparativa.<br><br>**Escenario 02:** Dado que hay diferencia significativa, cuando el sistema analiza los datos, entonces sugiere continuar negociación o ajustar valores. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                                                                  | Priority | Epic |
| :---------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| US50                    | Usuario                                                                                                                                                                                                                                                                                                               | Baja     | EP13 |
| **Title**               | Consultar historial de precios similares                                                                                                                                                                                                                                                                              |          |      |
| **Description**         | Como usuario, deseo ver precios históricos de servicios similares para tomar decisiones informadas.                                                                                                                                                                                                                   |          |      |
|                         |                                                                                                                                                                                                                                                                                                                       |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que existen datos históricos, cuando el usuario solicita verlos, entonces el sistema muestra un listado o gráfico.<br><br>**Escenario 02:** Dado que el usuario cambia de categoría, cuando el sistema actualiza los datos, entonces muestra información correspondiente a la nueva categoría. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                                      | Priority | Epic |
| :---------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| SP01                    | Equipo de desarrollo                                                                                                                                                                                                                                                                      | Media    | EP02 |
| **Title**               | Investigación de autenticación con Google                                                                                                                                                                                                                                                 |          |      |
| **Description**         | Como equipo de desarrollo, deseo investigar cómo integrar Google OAuth 2.0 para permitir registro e inicio de sesión seguro.                                                                                                                                                              |          |      |
|                         |                                                                                                                                                                                                                                                                                           |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que se revisa la documentación, cuando se analizan los requisitos, entonces se documentan los pasos de integración.<br><br>**Escenario 02:** Dado que se desarrolla un prototipo, cuando se completa el flujo, entonces se valida que el token generado es seguro. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                                                 | Priority | Epic |
| :---------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| SP02                    | Equipo de desarrollo                                                                                                                                                                                                                                                                                 | Media    | EP03 |
| **Title**               | Recuperación segura de contraseña                                                                                                                                                                                                                                                                    |          |      |
| **Description**         | Como equipo de desarrollo, deseo investigar mecanismos seguros de recuperación de contraseña mediante enlaces temporales.                                                                                                                                                                            |          |      |
|                         |                                                                                                                                                                                                                                                                                                      |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que se revisan buenas prácticas, cuando se analiza la documentación, entonces se define la estrategia recomendada.<br><br>**Escenario 02:** Dado que se genera un prototipo de envío de correo, cuando el usuario recibe el enlace, entonces este expira según configuración. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                            | Priority | Epic |
| :---------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :------- | :--- |
| SP03                    | Equipo de desarrollo                                                                                                                                                                                                                                                            | Media    | EP08 |
| **Title**               | Investigación de motores de búsqueda y filtros                                                                                                                                                                                                                                  |          |      |
| **Description**         | Como equipo de desarrollo, deseo investigar motores de búsqueda eficientes para mejorar la experiencia de encontrar freelancers.                                                                                                                                                |          |      |
|                         |                                                                                                                                                                                                                                                                                 |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que se revisan alternativas, cuando se documentan pros y contras, entonces se incluye una recomendación técnica.<br><br>**Escenario 02:** Dado que se desarrolla un prototipo, cuando se ejecuta en un dataset, entonces se mide el tiempo de respuesta. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                             | Priority | Epic |
| :---------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| SP04                    | Equipo de desarrollo                                                                                                                                                                                                                                                             | Media    | EP12 |
| **Title**               | Investigación de mensajería en tiempo real                                                                                                                                                                                                                                       |          |      |
| **Description**         | Como equipo de desarrollo, deseo investigar opciones para implementar mensajería en tiempo real.                                                                                                                                                                                 |          |      |
|                         |                                                                                                                                                                                                                                                                                  |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que se revisan tecnologías, cuando se comparan, entonces el informe incluye la mejor opción.<br><br>**Escenario 02:** Dado que se crea un prototipo básico, cuando dos usuarios intercambian mensajes, entonces estos se reciben sin refrescar la página. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                               | Priority | Epic |
| :---------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| SP05                    | Equipo de desarrollo                                                                                                                                                                                                                                                               | Media    | EP13 |
| **Title**               | Investigación para cálculo inteligente de precios                                                                                                                                                                                                                                  |          |      |
| **Description**         | Como equipo de desarrollo, deseo investigar modelos para sugerir precios justos evaluando variables y reglas.                                                                                                                                                                      |          |      |
|                         |                                                                                                                                                                                                                                                                                    |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que se analizan variables, cuando se desarrolla un prototipo, entonces devuelve un precio sugerido.<br><br>**Escenario 02:** Dado que se documenta la investigación, cuando se presentan resultados, entonces se incluye complejidad y enfoque recomendado. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                                             | Priority | Epic |
| :---------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| SP06                    | Equipo de desarrollo                                                                                                                                                                                                                                                                             | Media    | EP06 |
| **Title**               | Gestión de archivos y portafolio                                                                                                                                                                                                                                                                 |          |      |
| **Description**         | Como equipo de desarrollo, deseo investigar almacenamiento seguro de imágenes y archivos para portafolios multimedia.                                                                                                                                                                            |          |      |
|                         |                                                                                                                                                                                                                                                                                                  |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que se evalúan proveedores de nube, cuando se documentan costos y seguridad, entonces se elige la opción más viable.<br><br>**Escenario 02:** Dado que se construye un prototipo, cuando un usuario carga una imagen, entonces esta es accesible mediante una URL segura. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                  | Priority | Epic |
| :---------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| SP07                    | Equipo de desarrollo                                                                                                                                                                                                                                                  | Alta     | EP09 |
| **Title**               | Contratación directa y pagos                                                                                                                                                                                                                                          |          |      |
| **Description**         | Como equipo de desarrollo, deseo investigar opciones de integración de pagos para habilitar contrataciones directas.                                                                                                                                                  |          |      |
|                         |                                                                                                                                                                                                                                                                       |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que se revisan APIs de pago, cuando se comparan, entonces se documentan dependencias y requisitos legales.<br><br>**Escenario 02:** Dado que se desarrolla un prototipo, cuando el cliente confirma, entonces se genera un registro de prueba. |          |      |



| Story ID                | User                                                                                                                                                                                                                                                                                             | Priority | Epic |
| :---------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :--- |
| SP08                    | Equipo de desarrollo                                                                                                                                                                                                                                                                             | Media    | EP11 |
| **Title**               | Sistema de calificaciones y opiniones                                                                                                                                                                                                                                                            |          |      |
| **Description**         | Como equipo de desarrollo, deseo investigar formas seguras y eficientes de almacenar calificaciones evitando fraudes.                                                                                                                                                                            |          |      |
|                         |                                                                                                                                                                                                                                                                                                  |          |      |
| **Acceptance Criteria** | **Escenario 01:** Dado que se diseña un esquema de BD, cuando se prueba, entonces soporta calificaciones con comentarios vinculados a proyectos finalizados.<br><br>**Escenario 02:** Dado que se documentan riesgos, cuando se presenta el informe, entonces se incluyen medidas de mitigación. |          |      |



## 3.3. Impact Map

Se realizaron los siguientes cuadros en la herramienta Miro, el link original puede ser observado aquí: [LINK Impact Mapping](https://miro.com/app/board/uXjVIE5Pk5Q=/?share_link_id=296495865120)

**Impact Map Segmento 1:** Estudiantes Universitarios Freelancers  
El impact map de GigU para los estudiantes universitarios freelancers busca proporcionar un sistema robusto con alta posibilidad de personalización para la expresión creativa y profesional de los freelancers con la posibilidad de subir portafolios completos, publicar diversos tipos de servicios y editar o personalizar los perfiles junto a los servicios del freelancer.  
<img src="imgs/ImpactMap1.png" alt="ImpactMapping" title="ImpactMapping"/>

**Impact Map Segmento 2:** Personas y Emprendimientos que buscan contratar servicios freelance  
El impact map de GigU para las personas y emprendimientos que buscan contratar servicios freelance busca optimizar el proceso del contratado de freelancers por medio de un sistema de búsqueda completo que permite encontrar al freelancer indicado teniendo en cuenta sus servicios disponibles, la media de costos que propone y su nivel de experiencia.  
<img src="imgs/ImpactMap2.png" alt="ImpactMapping" title="ImpactMapping"/>


## 3.4. Product Backlog
Se utilizó la escala Fibonacci para la estimación de los Story Points. En total se tuvieron **197** Story Points.

| # Orden | User Story ID | Título                                                      | Story Points |
| :-----: | :-----------: | ----------------------------------------------------------- | :----------: |
|  **1**  |    **US01**   | Navegación intuitiva en la landing page                     |       3      |
|  **2**  |    **US02**   | Acceso rápido a funcionalidades clave                       |       3      |
|  **3**  |    **US03**   | Registro con correo y contraseña                            |       3      |
|  **4**  |    **US04**   | Iniciar sesión como freelancer o cliente                    |       5      |
|  **5**  |    **US05**   | Registro con Google                                         |       2      |
|  **6**  |    **US06**   | Solicitar recuperación de contraseña                        |       2      |
|  **7**  |    **US07**   | Restablecer contraseña vía correo                           |       2      |
|  **8**  |    **US12**   | Acceso a preguntas frecuentes (FAQ)                         |       3      |
|  **9**  |    **US13**   | Búsqueda dentro de preguntas frecuentes                     |       3      |
|  **10** |    **US14**   | Envío de ticket de soporte                                  |       3      |
|  **11** |    **US08**   | Conocer los beneficios de GigU                              |       1      |
|  **12** |    **US11**   | Detalles sobre tipos de servicios                           |       5      |
|  **13** |    **US10**   | Experiencias de otros usuarios                              |       5      |
|  **14** |    **US09**   | Diferencias entre roles (Freelancer / Cliente)              |       8      |
|  **15** |    **US25**   | Buscar freelancers por palabra clave                        |       3      |
|  **16** |    **US26**   | Filtrar freelancers por habilidad                           |       3      |
|  **17** |    **US29**   | Ordenar resultados por relevancia o calificación            |       3      |
|  **18** |    **US27**   | Filtrar por rango de precios                                |       5      |
|  **19** |    **US28**   | Filtrar por nivel de experiencia                            |       5      |
|  **20** |    **US30**   | Contratar desde el perfil del freelancer                    |       5      |
|  **21** |    **US31**   | Confirmación de contratación exitosa                        |       3      |
|  **22** |    **US24**   | Añadir imágenes o archivos al servicio (previo a contratar) |       3      |
|  **23** |    **US33**   | Historial de contrataciones realizadas                      |       2      |
|  **24** |    **US34**   | Visualizar proyectos activos                                |       5      |
|  **25** |    **US37**   | Seguimiento del estado del proyecto                         |       5      |
|  **26** |    **US32**   | Aceptar o rechazar una solicitud de contrato                |       3      |
|  **27** |    **US35**   | Gestionar solicitudes recibidas                             |       3      |
|  **28** |    **US36**   | Marcar proyecto como finalizado                             |       3      |
|  **29** |    **US38**   | Calificar al freelancer al finalizar el proyecto            |       3      |
|  **30** |    **US39**   | Ver calificaciones en perfil de freelancer                  |       5      |
|  **31** |    **US41**   | Calificar al cliente                                        |       5      |
|  **32** |    **US40**   | Editar calificación después del proyecto                    |       5      |
|  **33** |    **US42**   | Enviar mensaje a usuario desde perfil                       |       3      |
|  **34** |    **US43**   | Ver historial de conversaciones                             |       2      |
|  **35** |    **US44**   | Notificaciones de nuevos mensajes                           |       1      |
|  **36** |    **US45**   | Bloquear o reportar usuario desde chat                      |       2      |
|  **37** |    **US15**   | Creación de perfil freelance                                |       5      |
|  **38** |    **US16**   | Añadir habilidades y descripción personal                   |       8      |
|  **39** |    **US17**   | Establecer tarifas por servicio                             |       8      |
|  **40** |    **US18**   | Subir portafolio de proyectos                               |       5      |
|  **41** |    **US19**   | Editar y actualizar perfil en cualquier momento             |       3      |
|  **42** |    **US20**   | Publicar un servicio personalizado                          |       5      |
|  **43** |    **US21**   | Establecer plazos de entrega                                |       5      |
|  **44** |    **US22**   | Editar servicios publicados                                 |       5      |
|  **45** |    **US23**   | Pausar o eliminar servicios publicados                      |       5      |
|  **46** |    **US46**   | Sugerencia de precio inteligente                            |       8      |
|  **47** |    **US47**   | Ajuste manual sobre precio sugerido                         |       5      |
|  **48** |    **US48**   | Detalle del cálculo del precio sugerido                     |       5      |
|  **49** |    **US49**   | Comparación entre propuesta y oferta                        |       3      |
|  **50** |    **US50**   | Historial de precios de servicios similares                 |       2      |


<div style="page-break-before: always;"></div>

# Capítulo IV: Product Architecture Design

## 4.1. Design Concepts, ViewPoints & ER Diagrams

Esta sección presenta los conceptos de diseño, principios, estilos arquitectónicos, patrones, vistas y tácticas que guían la arquitectura de GigU. La propuesta se alinea con el objetivo del curso de construir una arquitectura empresarial basada en microservicios, Domain-Driven Design y arquitectura cloud native, aplicando decisiones de diseño justificables mediante ADD v3.

GigU es una plataforma que conecta estudiantes universitarios freelancers con clientes o emprendimientos que requieren contratar servicios. La solución permite publicar servicios, definir tarifas, gestionar solicitudes de contratación, coordinar proyectos, comunicarse dentro de la plataforma y consultar calificaciones para aumentar la confianza entre las partes (GigU, 2026).

### 4.1.1. Principles Statements

#### Domain-Driven Design como principio rector

La arquitectura de GigU se organizará alrededor de las capacidades centrales del dominio freelance universitario. Cada microservicio representará un límite funcional coherente del negocio, evitando dividir el sistema por capas técnicas aisladas. Esta decisión permite que el modelo de software refleje conceptos propios del dominio, tales como perfil freelance, servicio publicado, solicitud de contratación, proyecto, conversación, calificación y sugerencia de precio.

| Principio                   | Aplicación en GigU                                                                                                                                                |
| --------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Lenguaje ubicuo             | El equipo utilizará términos consistentes como freelancer, cliente, servicio, solicitud, acuerdo, proyecto, tarifa, reseña, conversación y portafolio.            |
| Bounded contexts            | El sistema se dividirá en contextos delimitados: acceso/perfiles, marketplace, contratación/proyectos y chat/notificaciones.                                      |
| Modelo de dominio explícito | Las reglas principales no estarán dispersas en controladores o consultas SQL, sino encapsuladas en entidades, value objects, servicios de dominio y casos de uso. |
| Alta cohesión               | Cada microservicio concentrará reglas relacionadas con una capacidad de negocio específica.                                                                       |

#### Clean Architecture por microservicio

Cada microservicio de GigU aplicará Clean Architecture para separar reglas de negocio, casos de uso, adaptadores de entrada/salida e infraestructura. El objetivo es que el dominio no dependa del framework, de la base de datos, del gateway, del broker de mensajería ni de servicios externos.

| Capa                 | Responsabilidad                                                                                          |
| -------------------- | -------------------------------------------------------------------------------------------------------- |
| Domain Layer         | Define entidades, value objects, reglas de negocio, invariantes y eventos de dominio.                    |
| Application Layer    | Orquesta casos de uso, comandos, consultas y puertos.                                                    |
| Interface Layer      | Expone controladores REST, DTOs de entrada/salida y validaciones de contrato.                            |
| Infrastructure Layer | Implementa persistencia, integración con Supabase, RabbitMQ, Caddy, almacenamiento y servicios externos. |

#### API First y contratos explícitos

Las APIs REST de GigU se diseñarán con contratos claros, versionados y documentados. Cada microservicio expondrá endpoints bajo `/api/v1`, utilizando DTOs específicos para evitar exponer directamente entidades del dominio. OpenAPI se utilizará para documentar formalmente la superficie de las APIs HTTP, facilitando comprensión, pruebas y consumo por parte del frontend (OpenAPI Initiative, s. f.).

| Principio             | Aplicación en GigU                                                                        |
| --------------------- | ----------------------------------------------------------------------------------------- |
| Contratos versionados | Los endpoints públicos se publicarán bajo `/api/v1`.                                      |
| DTOs explícitos       | Los modelos internos no serán expuestos directamente en la API.                           |
| Documentación viva    | Cada microservicio tendrá documentación OpenAPI/Swagger.                                  |
| Compatibilidad        | Los cambios incompatibles deberán manejarse mediante nuevos DTOs o versiones de endpoint. |

#### Autonomía de servicios y ownership de datos

Cada microservicio será responsable de sus propios datos y reglas. Aunque Supabase PostgreSQL será la base de datos administrada utilizada por el proyecto, la propiedad lógica de los datos se mantendrá separada por esquemas y por límites de microservicio. El enfoque de microservicios propone servicios pequeños, ejecutados en procesos independientes, organizados alrededor de capacidades de negocio y comunicados mediante mecanismos ligeros, usualmente APIs HTTP (Lewis & Fowler, 2014).

| Microservicio           | Ownership principal                                                                       |
| ----------------------- | ----------------------------------------------------------------------------------------- |
| AccessProfileService    | Usuarios, roles, perfiles, habilidades, portafolio y verificación académica.              |
| GigMarketplaceService   | Servicios publicados, categorías, filtros, tarifas base y archivos asociados al servicio. |
| PullEngagementService   | Solicitudes, acuerdos, proyectos, estados, reseñas y sugerencias de precio.               |
| ChatNotificationService | Conversaciones, mensajes, notificaciones, reportes y tickets.                             |

#### Seguridad por diseño

GigU gestionará información de usuarios, perfiles públicos, conversaciones, solicitudes y acuerdos. Por ello, la seguridad se incorporará desde la arquitectura y no como una extensión posterior. Spring Security se utilizará para autenticación, autorización y protección de endpoints en los microservicios Spring Boot (Spring, s. f.-a).

| Principio     | Aplicación en GigU                                                                    |
| ------------- | ------------------------------------------------------------------------------------- |
| Autenticación | Inicio de sesión con JWT emitido por el backend.                                      |
| Autorización  | Control de acceso por roles: visitante, freelancer, cliente y administrador.          |
| Ownership     | Un usuario solo podrá modificar recursos de su propiedad.                             |
| Auditoría     | Los cambios relevantes de contratación, proyecto, reseña y bloqueo serán registrados. |
| Validación    | Las entradas serán validadas en API y en casos de uso.                                |

#### Comunicación asíncrona para eventos secundarios

Las operaciones críticas se resolverán mediante REST cuando el usuario requiera respuesta inmediata. Las operaciones secundarias, como notificaciones internas, eventos de cambio de estado o avisos de nuevos mensajes, se manejarán mediante RabbitMQ. RabbitMQ es un broker de mensajería open source orientado a comunicación eficiente y confiable entre aplicaciones distribuidas (RabbitMQ, s. f.).

| Evento                     | Publicador              | Consumidor              |
| -------------------------- | ----------------------- | ----------------------- |
| `UserRegistered`           | AccessProfileService    | ChatNotificationService |
| `FreelancerProfileUpdated` | AccessProfileService    | GigMarketplaceService   |
| `ServicePublished`         | GigMarketplaceService   | ChatNotificationService |
| `ProjectRequestCreated`    | PullEngagementService   | ChatNotificationService |
| `ProjectStatusChanged`     | PullEngagementService   | ChatNotificationService |
| `MessageSent`              | ChatNotificationService | ChatNotificationService |
| `ReviewCreated`            | PullEngagementService   | GigMarketplaceService   |

#### Despliegue reproducible

Los servicios backend se desplegarán mediante contenedores administrados con Docker Compose en Oracle Cloud Always Free. Docker Compose permite definir y ejecutar aplicaciones multi-contenedor mediante un archivo YAML, lo que permite levantar microservicios, gateway y broker de forma reproducible (Docker, s. f.).

### 4.1.2. Approaches Statements: Architectural Styles & Patterns

#### Approaches Statements

| Enfoque                  | Aplicación en GigU                                                                                                                                                                                                                                                                                    |
| ------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Domain-Driven Design     | Se utilizará para definir bounded contexts alineados con capacidades de negocio.                                                                                                                                                                                                                      |
| Clean Architecture       | Se aplicará dentro de cada microservicio para separar dominio, casos de uso, interfaces e infraestructura.                                                                                                                                                                                            |
| API First                | Se diseñarán contratos REST claros y versionados antes de acoplar el frontend al backend.                                                                                                                                                                                                             |
| Event-Driven Integration | Se utilizarán eventos asíncronos para notificaciones, cambios de estado y actualización de vistas derivadas.                                                                                                                                                                                          |
| Cloud Native Deployment  | El frontend se alojará en Vercel, mientras que los microservicios backend se desplegarán en Oracle Cloud Always Free mediante contenedores. Oracle Cloud Always Free incluye recursos Ampere A1 equivalentes a 4 OCPU y 24 GB de memoria dentro de sus límites gratuitos (Oracle, s. f.). |

#### Architectural Styles

| Estilo arquitectónico        | Aplicación en GigU                                                                                              | Justificación                                                                |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| Microservices Architecture   | El backend se divide en servicios independientes por capacidad de negocio.                                      | Permite modularidad, despliegue separado, testabilidad y alineación con DDD. |
| Client-Server                | El frontend Vue consume APIs REST expuestas por el backend.                                                     | Separa experiencia de usuario de lógica de negocio.                          |
| Layered / Clean Architecture | Cada microservicio se organiza en capas internas con dependencias hacia el dominio.                             | Reduce acoplamiento y facilita pruebas.                                      |
| Event-Driven Architecture    | RabbitMQ soporta eventos secundarios entre microservicios.                                                      | Reduce dependencia temporal entre servicios.                                 |
| Cloud Native Deployment      | La solución se despliega con frontend, backend, almacenamiento y base de datos distribuidos en servicios cloud. | Permite acceso público, evidencias de despliegue y validación incremental.   |

#### Architectural Patterns

| Patrón arquitectónico        | Aplicación en GigU                                                                                                                                                                                                                                                   |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Lightweight API Gateway      | Caddy actuará como reverse proxy y gateway liviano, enrutando `/api/access`, `/api/marketplace`, `/api/engagement` y `/api/chat` hacia los microservicios correspondientes. Caddy soporta HTTPS automático y renovación de certificados TLS (Caddy, s. f.). |
| Database per Service lógico  | Supabase PostgreSQL contendrá esquemas separados por microservicio.                                                                                                                                                                                                  |
| Message Broker               | RabbitMQ desacoplará eventos de dominio y notificaciones.                                                                                                                                                                                                            |
| Containerized Deployment     | Docker Compose ejecutará Caddy, microservicios y RabbitMQ en la VM de Oracle Cloud.                                                                                                                                                                                  |
| Backend for Frontend parcial | El gateway expondrá rutas estables para el frontend sin exponer la topología interna.                                                                                                                                                                                |
| RESTful API                  | Los microservicios expondrán recursos mediante APIs HTTP documentadas con OpenAPI.                                                                                                                                                                                   |
| Domain Events                | Cambios relevantes del negocio serán publicados como eventos internos.                                                                                                                                                                                               |

#### Bounded Contexts y microservicios

| Bounded Context     | Microservicio           | Responsabilidades principales                                                                           |
| ------------------- | ----------------------- | ------------------------------------------------------------------------------------------------------- |
| Access & Profile    | AccessProfileService    | Registro, autenticación, roles, perfiles freelance, habilidades, portafolio y verificación académica.   |
| Gig Marketplace     | GigMarketplaceService   | Publicación de servicios, edición, búsqueda, filtros, categorías, tarifas base y archivos de servicios. |
| Pull & Engagement   | PullEngagementService   | Solicitudes de contratación, acuerdos, proyectos, estados, entrega, reseñas y sugerencias de precio.    |
| Chat & Notification | ChatNotificationService | Conversaciones, mensajes, notificaciones internas, reportes, bloqueos y tickets de soporte.             |

#### Servicios externos de soporte

| Servicio externo         | Uso arquitectónico                                                                                                                    |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------- |
| Vercel                   | Alojamiento del frontend Vue + Vite. El plan Hobby está orientado a proyectos personales y aplicaciones pequeñas (Vercel, s. f.).     |
| Oracle Cloud Always Free | Alojamiento de backend, Caddy, microservicios y RabbitMQ.                                                                             |
| Supabase PostgreSQL      | Base de datos relacional administrada. Supabase se define como una plataforma de desarrollo basada en PostgreSQL (Supabase, s. f.-a). |
| Supabase Storage         | Almacenamiento de archivos de portafolio, imágenes y adjuntos.                                                                        |
| GitHub Actions           | Automatización de build, pruebas y evidencias de integración continua.                                                                |
| Resend                   | Servicio opcional para correos de recuperación y notificaciones.                                                                      |

### 4.1.3. Context Diagram

El diagrama de contexto representa a GigU como sistema de software y muestra su relación con los usuarios principales y servicios externos. El proyecto identifica como actores principales al estudiante universitario freelancer, al cliente o emprendimiento que contrata servicios y al administrador de plataforma. Las funcionalidades principales incluyen creación de perfil, publicación de servicios, búsqueda, contratación, gestión de proyectos, calificaciones, mensajería y sugerencia de precios (GigU, 2026).

![4.1.3.ContextDiagram](imgs/add/4.1.3.ContextDiagram.png)

### 4.1.4. Approach-driven ViewPoints Diagrams

Para comunicar la arquitectura de GigU se utilizarán vistas C4 y UML. El C4 Model permite representar el sistema en distintos niveles de abstracción: contexto, contenedores, componentes y código. Para este punto se incluyen vistas de contexto, contenedores, componentes, actividad, estado y clases, coherentes con la estructura solicitada para el capítulo.

#### Viewpoint 01: Container View

La vista de contenedores muestra los elementos ejecutables principales de GigU: frontend, gateway, microservicios backend, broker de eventos, base de datos y almacenamiento. Esta vista permite observar la distribución de responsabilidades en tiempo de ejecución.

![4.1.4 ApproachdrivenViewPointsDiagrams1](<imgs/add/4.1.4 ApproachdrivenViewPointsDiagrams1.png>)

#### Viewpoint 02: Component View - PullEngagementService

El PullEngagementService concentra las reglas transaccionales más relevantes de GigU: solicitudes de contratación, acuerdos, proyectos, cambios de estado, reseñas y sugerencias de precio. Este servicio refleja historias críticas del producto, como contratar desde el perfil del freelancer, aceptar o rechazar solicitudes, visualizar proyectos activos, marcar proyectos como finalizados y registrar calificaciones (GigU, 2026).

![4.1.4 ApproachdrivenViewPointsDiagrams2](<imgs/add/4.1.4 ApproachdrivenViewPointsDiagrams2.png>)

#### Viewpoint 03: Activity Diagram - contratación de servicio

![4.1.4 ApproachdrivenViewPointsDiagrams3](<imgs/add/4.1.4 ApproachdrivenViewPointsDiagrams3.png>)

#### Viewpoint 04: State Diagram - ciclo de vida de proyecto

![4.1.4 ApproachdrivenViewPointsDiagrams4](<imgs/add/4.1.4 ApproachdrivenViewPointsDiagrams4.png>)

#### Viewpoint 05: Domain Class Diagram

![4.1.4 ApproachdrivenViewPointsDiagrams5](<imgs/add/4.1.4 ApproachdrivenViewPointsDiagrams5.png>)

### 4.1.5. Relational/Non-Relational Database Diagram

GigU utilizará una base de datos relacional administrada con PostgreSQL en Supabase. La separación lógica se realizará mediante esquemas por microservicio para preservar ownership de datos y evitar acoplamiento directo entre contextos. Las relaciones internas de cada esquema se podrán implementar con claves foráneas, mientras que las referencias hacia datos de otros microservicios se representarán mediante identificadores externos controlados por contrato.

| Esquema                    | Microservicio propietario | Tablas principales                                                                                           |
| -------------------------- | ------------------------- | ------------------------------------------------------------------------------------------------------------ |
| `access_profile_schema`    | AccessProfileService      | `users`, `roles`, `user_roles`, `freelancer_profiles`, `skills`, `freelancer_skills`, `portfolio_items`      |
| `marketplace_schema`       | GigMarketplaceService     | `service_categories`, `service_offerings`, `service_media`                                                   |
| `engagement_schema`        | PullEngagementService     | `project_requests`, `agreements`, `projects`, `project_status_history`, `reviews`, `price_suggestions`       |
| `chat_notification_schema` | ChatNotificationService   | `conversations`, `conversation_participants`, `messages`, `notifications`, `user_reports`, `support_tickets` |

![4.1.5.RelationalNonRelationalDatabaseDiagram](imgs/add/4.1.5.RelationalNonRelationalDatabaseDiagram.png)

### 4.1.6. Design Patterns

| Design Pattern        | Aplicación en GigU                                                                                                                                  | Beneficio arquitectónico                                                     |
| --------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| Repository Pattern    | Cada microservicio tendrá repositorios para abstraer acceso a PostgreSQL.                                                                           | Reduce acoplamiento con persistencia y facilita pruebas.                     |
| DTO Pattern           | Los controllers recibirán y devolverán DTOs, no entidades de dominio.                                                                               | Protege el modelo interno y estabiliza contratos.                            |
| Mapper Pattern        | Se convertirán DTOs, comandos, entidades y respuestas mediante mappers.                                                                             | Evita lógica de transformación dispersa.                                     |
| Factory Method        | Se crearán objetos complejos como `ProjectRequest`, `Agreement`, `Project` y `ServiceOffering` mediante fábricas o métodos de creación controlados. | Centraliza invariantes de construcción.                                      |
| Strategy Pattern      | La sugerencia de precios podrá usar estrategias por tipo de servicio, complejidad, urgencia o experiencia.                                          | Permite extender reglas de pricing sin modificar el caso de uso principal.   |
| Specification Pattern | Los filtros de búsqueda podrán componerse por habilidad, categoría, precio, disponibilidad y reputación.                                            | Evita consultas rígidas y mejora mantenibilidad.                             |
| Domain Events         | Eventos como `ProjectRequestCreated`, `ProjectStatusChanged`, `ReviewCreated` y `MessageSent` representarán cambios relevantes del dominio.         | Desacopla microservicios y facilita reacciones asíncronas.                   |
| Outbox Pattern        | Los eventos críticos podrán registrarse junto con la transacción local antes de publicarse en RabbitMQ.                                             | Reduce riesgo de pérdida de eventos.                                         |
| Adapter Pattern       | Integraciones con Supabase Storage, RabbitMQ, Resend y persistencia se encapsularán como adaptadores.                                               | Mantiene el dominio independiente de proveedores externos.                   |
| Dependency Injection  | Los casos de uso dependerán de interfaces y no de implementaciones concretas.                                                                       | Facilita pruebas unitarias y sustitución de infraestructura.                 |
| API Gateway Pattern   | Caddy centralizará el ingreso HTTP y enrutará hacia microservicios.                                                                                 | Oculta la topología interna y simplifica el consumo del frontend.            |
| CQRS Lite             | Se separarán comandos y queries en casos de uso relevantes, como búsqueda, contratación y mensajería.                                               | Mejora claridad de responsabilidades sin introducir complejidad innecesaria. |

### 4.1.7. Tactics

Las tácticas seleccionadas responden a los atributos de calidad más relevantes para GigU: seguridad, modificabilidad, interoperabilidad, disponibilidad, performance y capacidad de prueba. El material del curso clasifica tácticas para disponibilidad, interoperabilidad, modificabilidad, performance, seguridad, capacidad de prueba y usabilidad; por ello, la selección se mantiene enfocada en los atributos que más influyen en la arquitectura del sistema.

| Atributo de calidad | Táctica                         | Aplicación en GigU                                                                                                                                                                                                             |
| ------------------- | ------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Seguridad           | Authenticate Actors             | Los usuarios se autentican mediante Spring Security y JWT.                                                                                                                                                                     |
| Seguridad           | Authorize Actors                | Los endpoints validan roles y ownership antes de permitir operaciones sobre perfiles, servicios, solicitudes, proyectos, reseñas o conversaciones.                                                                             |
| Seguridad           | Maintain Audit Trail            | Se registran acciones relevantes: creación de solicitud, aceptación/rechazo, cambio de estado de proyecto, calificación, bloqueo y reporte.                                                                                    |
| Seguridad           | Validate Inputs                 | Los DTOs y casos de uso validan entradas antes de ejecutar reglas de negocio.                                                                                                                                                  |
| Modificabilidad     | Increase Semantic Coherence     | Cada microservicio agrupa responsabilidades de un bounded context específico.                                                                                                                                                  |
| Modificabilidad     | Encapsulate                     | Reglas de perfil, marketplace, contratación y chat se encapsulan en sus respectivos servicios.                                                                                                                                 |
| Modificabilidad     | Restrict Dependencies           | Los microservicios no consultan directamente tablas de otros contextos; usan IDs externos, APIs o eventos.                                                                                                                     |
| Modificabilidad     | Use an Intermediary             | RabbitMQ desacopla eventos secundarios entre microservicios.                                                                                                                                                                   |
| Interoperabilidad   | Tailor Interface                | Cada microservicio expone contratos REST específicos para su contexto.                                                                                                                                                         |
| Interoperabilidad   | Orchestrate                     | PullEngagementService coordina el flujo de solicitud, acuerdo, proyecto, entrega y reseña.                                                                                                                                     |
| Interoperabilidad   | Maintain Contract Documentation | OpenAPI documenta endpoints, requests, responses y errores esperados.                                                                                                                                                          |
| Disponibilidad      | Ping/Echo                       | Cada microservicio expondrá endpoint de health check para validar disponibilidad.                                                                                                                                              |
| Disponibilidad      | Exception Handling              | Fallas de notificación, correo o evento no deben interrumpir la operación principal de contratación.                                                                                                                           |
| Disponibilidad      | Retry                           | Publicación de eventos y envío de notificaciones podrán reintentarse de forma controlada.                                                                                                                                      |
| Disponibilidad      | Graceful Degradation            | Si falla la notificación externa, el proyecto y la contratación seguirán funcionando y se mantendrá notificación interna.                                                                                                      |
| Performance         | Manage Resources                | Las búsquedas usarán paginación, filtros e índices en campos como habilidad, categoría, estado, precio y fecha.                                                                                                                |
| Performance         | Reduce Overhead                 | El frontend consumirá DTOs ligeros en listados de servicios, perfiles y conversaciones.                                                                                                                                        |
| Performance         | Asynchronous Processing         | Notificaciones y eventos secundarios se procesarán fuera del flujo principal.                                                                                                                                                  |
| Capacidad de prueba | Specialized Interfaces          | Los casos de uso dependerán de interfaces, permitiendo mocks en pruebas unitarias.                                                                                                                                             |
| Capacidad de prueba | Record/Playback                 | Los eventos y respuestas externas podrán simularse en pruebas automatizadas.                                                                                                                                                   |
| Capacidad de prueba | Test with Real Dependencies     | Testcontainers permitirá ejecutar pruebas de integración con servicios reales en contenedores. Spring Boot documenta Testcontainers como mecanismo para levantar servicios reales durante pruebas de integración (Spring, s. f.-b). |
| Usabilidad          | Feedback                        | El sistema mostrará confirmaciones para registro, publicación, contratación, envío de mensaje, cambio de estado y calificación.                                                                                                |
| Usabilidad          | Maintain Task Model             | Los flujos del sistema seguirán las tareas reales identificadas: publicar servicios, cotizar precios, negociar, establecer acuerdos y comunicarse dentro de la plataforma (GigU, 2026).                                       |

## 4.2. Architectural Drivers

La arquitectura de GigU se diseña siguiendo el método Attribute-Driven Design, debido a que el Product Architecture Design del proyecto exige aplicar ADD v3 para relacionar el propósito de diseño, la funcionalidad principal, los atributos de calidad, las restricciones y las preocupaciones arquitectónicas con decisiones concretas de arquitectura. El project statement establece que la solución debe evidenciar una arquitectura empresarial basada en microservicios, Domain-Driven Design y cloud native architecture, además de un RESTful API accesible desde internet.

ADD considera como entradas principales del diseño el design purpose, primary functionality, quality attributes, architectural concerns y constraints. A partir de estas entradas, el diseño se ejecuta mediante iteraciones donde se seleccionan drivers, se refinan elementos del sistema, se eligen conceptos de diseño, se asignan responsabilidades, se definen interfaces y se registran decisiones arquitectónicas.

| Driver            | Prioridad  | Justificación                                                                                                                                               |
| ----------------- | ---------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Modificabilidad   | Alta       | GigU debe poder evolucionar por nuevas categorías de servicios, reglas de contratación, flujos de proyectos, reputación, pricing y funcionalidades de chat. |
| Seguridad         | Alta       | La plataforma gestiona cuentas, perfiles, portafolios, conversaciones, solicitudes, acuerdos, reseñas y reportes.                                           |
| Testabilidad      | Alta       | El curso exige evidencias de testing, implementación de microservicios y validación técnica por sprint.                                                     |
| Interoperabilidad | Media-Alta | El sistema integra frontend, gateway, microservicios, base de datos administrada, storage y mensajería asíncrona.                                           |
| Disponibilidad    | Media      | La plataforma debe estar accesible durante la validación académica, considerando las limitaciones de servicios gratuitos.                                   |
| Performance       | Media      | La búsqueda de servicios, perfiles, mensajes y proyectos debe responder de forma fluida para el volumen esperado de validación académica.                   |

### 4.2.1. Design Purpose

El propósito del diseño arquitectónico de GigU es definir una estructura técnica coherente, modular y verificable para implementar una plataforma web que conecte estudiantes universitarios freelancers con clientes y emprendimientos. La arquitectura debe permitir que los estudiantes publiquen servicios, construyan reputación profesional, gestionen proyectos y se comuniquen con clientes dentro de un entorno formal, seguro y alineado a sus habilidades.

GigU será diseñado como una aplicación empresarial basada en microservicios, aplicando Domain-Driven Design para separar capacidades de negocio y Clean Architecture dentro de cada microservicio. El frontend será desplegado en Vercel, el backend se ejecutará en una VM de Oracle Cloud Always Free mediante Docker Compose, la base de datos será Supabase PostgreSQL, el almacenamiento de archivos se realizará con Supabase Storage y la comunicación asíncrona entre servicios se gestionará con RabbitMQ. Caddy funcionará como gateway liviano y reverse proxy para exponer las rutas públicas de la API.

| Categoría                   | Detalle                                                                                                                                                               |
| --------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tipo de sistema             | Plataforma web de servicios freelance universitarios.                                                                                                                 |
| Propósito de negocio        | Facilitar que estudiantes universitarios consigan experiencia profesional e ingresos mediante servicios freelance formales y verificables.                            |
| Propósito arquitectónico    | Definir una arquitectura modular, desplegable, testeable y preparada para evolución incremental mediante microservicios.                                              |
| Enfoque de arquitectura     | Microservices Architecture, Domain-Driven Design y Clean Architecture.                                                                                                |
| Modelo de despliegue        | Frontend en Vercel; backend, Caddy y RabbitMQ en Oracle Cloud Always Free; base de datos y storage en Supabase.                                                       |
| Alcance funcional principal | Perfiles, portafolios, publicación de servicios, búsqueda, solicitudes, acuerdos, proyectos, chat, notificaciones y reseñas.                                          |
| Alcance técnico principal   | RESTful API documentada, microservicios independientes, persistencia relacional por ownership lógico, mensajería asíncrona y testing automatizado.                    |
| Limitación inicial          | El sistema modelará acuerdos y estados de pago para validación académica; la integración con una pasarela de pagos real queda fuera del primer alcance implementable. |

La decisión de utilizar Docker Compose responde a la necesidad de ejecutar varios contenedores de forma reproducible, debido a que permite definir y administrar aplicaciones multi-contenedor mediante un archivo de configuración centralizado (Docker, s. f.). Oracle Cloud Always Free se selecciona para el backend porque ofrece recursos gratuitos Ampere A1 equivalentes a 4 OCPU y 24 GB de memoria dentro de sus límites Always Free (Oracle, s. f.). Caddy se utilizará como gateway liviano porque permite implementar un reverse proxy de forma directa y soporta HTTPS automático con renovación de certificados TLS (Caddy, s. f.).

### 4.2.2. Primary Functionality: Primary User Stories

Las funcionalidades primarias seleccionadas son aquellas que afectan directamente la estructura de la aplicación, la asignación de responsabilidades entre microservicios y los principales escenarios de calidad. No se listan todas las historias del Product Backlog, sino las que influyen de forma significativa en la arquitectura.

| ID    | Primary User Story               | Descripción                                                                                                                                  | Impacto arquitectónico                                                                                          | Microservicio principal |
| ----- | -------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- | ----------------------- |
| PUS-01 | Gestión de cuenta y acceso       | Como usuario, deseo registrarme e iniciar sesión para acceder de forma segura a las funcionalidades de GigU.                                 | Requiere autenticación, autorización, roles, JWT y control de ownership.                                        | AccessProfileService    |
| PUS-02 | Gestión de perfil freelancer     | Como estudiante freelancer, deseo crear y actualizar mi perfil profesional para mostrar mi información académica, habilidades y experiencia. | Define el bounded context de perfiles, habilidades y verificación académica.                                    | AccessProfileService    |
| PUS-03 | Gestión de portafolio            | Como estudiante freelancer, deseo publicar evidencias de trabajos previos para generar confianza ante clientes potenciales.                  | Requiere integración con storage y relación entre perfil, archivos y experiencia.                               | AccessProfileService    |
| PUS-04 | Publicación de servicios         | Como estudiante freelancer, deseo publicar servicios con descripción, categoría, tarifa y tiempo estimado para ofrecerlos en la plataforma.  | Define el núcleo del marketplace y su persistencia.                                                             | GigMarketplaceService   |
| PUS-05 | Búsqueda y filtrado de servicios | Como cliente, deseo buscar servicios por categoría, habilidades, precio y reputación para encontrar freelancers adecuados.                   | Requiere consultas optimizadas, filtros, paginación e índices.                                                  | GigMarketplaceService   |
| PUS-06 | Solicitud de contratación        | Como cliente, deseo enviar una solicitud de contratación a un freelancer para iniciar un posible proyecto.                                   | Inicia el flujo transaccional de engagement y eventos de notificación.                                          | PullEngagementService   |
| PUS-07 | Negociación y acuerdo            | Como cliente y freelancer, deseamos acordar condiciones de trabajo para formalizar el inicio del proyecto.                                   | Requiere modelar solicitud, acuerdo, precio, plazo y estados.                                                   | PullEngagementService   |
| PUS-08 | Gestión de proyecto              | Como freelancer, deseo actualizar el estado del proyecto para informar avances, entrega y finalización del servicio.                         | Requiere ciclo de vida de proyecto, historial de estados y reglas de transición.                                | PullEngagementService   |
| PUS-09 | Chat de coordinación             | Como cliente o freelancer, deseo comunicarme dentro de la plataforma para coordinar detalles del servicio de forma formal.                   | Requiere conversación, mensajes, eventos y comunicación en tiempo real mediante WebSocket o Server-Sent Events. | ChatNotificationService |
| PUS-10 | Calificaciones y reseñas         | Como cliente, deseo calificar el trabajo recibido para ayudar a otros usuarios a evaluar la confiabilidad del freelancer.                    | Requiere reputación, reseñas, vínculo con proyecto finalizado y actualización de métricas visibles.             | PullEngagementService   |
| PUS-11 | Reportes y soporte               | Como usuario, deseo reportar problemas o conductas inadecuadas para que la plataforma pueda revisar incidentes.                              | Requiere tickets, reportes, moderación y rol administrador.                                                     | ChatNotificationService |
| PUS-12 | Sugerencia de precio             | Como freelancer, deseo recibir una sugerencia de precio basada en complejidad, tiempo y categoría para cotizar de forma más consistente.     | Requiere reglas de pricing desacopladas y extensibles.                                                          | PullEngagementService   |

### 4.2.3. Quality Attribute Scenarios

Los escenarios de atributos de calidad se redactan como requisitos medibles. El project statement indica que un escenario de atributo de calidad debe considerar fuente de estímulo, estímulo, medioambiente, artefacto, respuesta y medida de respuesta.

| ID    | Atributo de calidad | Fuente del estímulo                           | Estímulo                                                                                   | Ambiente                                            | Artefacto                                                            | Respuesta                                                                                                                                       | Medida de respuesta                                                                                                                                                         |
| ----- | ------------------- | --------------------------------------------- | ------------------------------------------------------------------------------------------ | --------------------------------------------------- | -------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| QA-01 | Seguridad           | Usuario no autenticado o usuario sin permisos | Intenta crear, modificar o consultar un recurso protegido                                  | Operación normal del sistema                        | Caddy Gateway, microservicio correspondiente, endpoints REST         | El sistema valida JWT, rol y ownership antes de ejecutar el caso de uso; si la solicitud no cumple, la rechaza y registra el intento relevante. | El 100% de endpoints protegidos rechaza solicitudes sin token válido o sin permisos; las operaciones críticas quedan registradas en auditoría.                              |
| QA-02 | Modificabilidad     | Equipo de desarrollo                          | Solicita agregar una nueva categoría de servicio o una nueva regla de sugerencia de precio | Sprint de evolución funcional                       | GigMarketplaceService y PullEngagementService                        | El cambio se implementa dentro del microservicio dueño del contexto sin modificar otros microservicios ni romper contratos existentes.          | El cambio afecta como máximo un microservicio principal y sus pruebas asociadas; las APIs existentes mantienen compatibilidad.                                              |
| QA-03 | Testabilidad        | Desarrollador backend                         | Agrega o modifica una regla de negocio de solicitud, acuerdo, proyecto o reseña            | Desarrollo local o pipeline de integración continua | Domain Layer y Application Layer del microservicio afectado          | El sistema permite probar la regla mediante pruebas unitarias y pruebas de integración del endpoint correspondiente.                            | Las reglas críticas del dominio tienen pruebas unitarias; los endpoints principales tienen pruebas de integración automatizadas.                                            |
| QA-04 | Interoperabilidad   | Frontend web o consumidor API                 | Consume funcionalidades de perfil, marketplace, engagement o chat                          | Operación normal desde navegador                    | RESTful API, Caddy Gateway y microservicios backend                  | El sistema expone contratos HTTP consistentes, versionados y documentados con OpenAPI.                                                          | El 100% de endpoints públicos principales se documenta con OpenAPI y responde usando DTOs JSON estandarizados.                                                              |
| QA-05 | Disponibilidad      | Usuario final o sistema de monitoreo          | Un microservicio o componente secundario falla temporalmente                               | Validación académica en infraestructura gratuita    | Contenedores backend, RabbitMQ o ChatNotificationService             | El sistema mantiene disponibles las funcionalidades no dependientes del componente fallido y permite reinicio del contenedor afectado.          | Los health checks identifican el componente fallido; las operaciones críticas de perfil, marketplace y engagement no dependen del envío exitoso de notificaciones externas. |
| QA-06 | Performance         | Cliente o freelancer                          | Realiza búsqueda de servicios, perfiles o conversaciones                                   | Dataset de validación académica y operación normal  | GigMarketplaceService, ChatNotificationService y Supabase PostgreSQL | El sistema responde con paginación, filtros e índices en campos de búsqueda frecuentes.                                                         | Las consultas principales devuelven resultados paginados y evitan cargar datasets completos en una sola respuesta.                                                          |
| QA-07 | Usabilidad          | Cliente o freelancer                          | Completa un flujo de publicación, solicitud, acuerdo, chat o calificación                  | Uso normal desde navegador web                      | Frontend Web App y API backend                                       | El sistema entrega confirmaciones claras y mantiene el estado visible de servicios, solicitudes, proyectos y mensajes.                          | Cada operación principal retorna estado explícito de éxito, error o pendiente; el usuario puede reconocer el estado actual de sus proyectos y conversaciones.               |

### 4.2.4. Constraints

Las restricciones representan decisiones con bajo o nulo grado de libertad para la arquitectura. Estas limitan las opciones de implementación y deben ser consideradas como drivers arquitectónicos.

| ID     | Restricción                                                                                                                                                  | Tipo                              | Impacto arquitectónico                                                                                                        |
| ------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| CON-01 | El frontend se desarrollará con Vue + Vite y se desplegará en Vercel.                                                                                        | Tecnológica / despliegue          | Se separa el frontend del backend y se consume la API mediante HTTPS.                                                         |
| CON-02 | El backend se desarrollará con Java y Spring Boot.                                                                                                           | Tecnológica                       | Los microservicios, controladores REST, seguridad y pruebas backend se implementan en el ecosistema Spring.                   |
| CON-03 | Cada microservicio aplicará Clean Architecture.                                                                                                              | Arquitectónica                    | Las reglas de dominio no dependerán de frameworks, persistencia, gateway o servicios externos.                                |
| CON-04 | El backend se organizará en cuatro microservicios principales: AccessProfileService, GigMarketplaceService, PullEngagementService y ChatNotificationService. | Arquitectónica                    | Se evita sobredimensionar la arquitectura y se mantiene una separación coherente por bounded context.                         |
| CON-05 | Caddy funcionará como gateway liviano y reverse proxy.                                                                                                       | Infraestructura                   | Las rutas públicas de la API se centralizan sin introducir un microservicio adicional de gateway.                             |
| CON-06 | Los microservicios, Caddy y RabbitMQ se ejecutarán con Docker Compose en Oracle Cloud Always Free.                                                           | Despliegue                        | La arquitectura backend será reproducible y ejecutable como aplicación multi-contenedor.                                      |
| CON-07 | La persistencia principal se realizará con Supabase PostgreSQL.                                                                                              | Datos                             | Se adopta una base relacional administrada con esquemas lógicos por microservicio.                                            |
| CON-08 | Los archivos de portafolio, imágenes y adjuntos se almacenarán en Supabase Storage.                                                                          | Datos / almacenamiento            | Los binarios no se guardan directamente en la base de datos relacional.                                                       |
| CON-09 | La autenticación y autorización se implementarán con Spring Security y JWT.                                                                                  | Seguridad                         | Cada microservicio validará acceso a operaciones protegidas y ownership de recursos.                                          |
| CON-10 | La mensajería asíncrona se implementará con RabbitMQ para eventos internos relevantes.                                                                       | Integración                       | Las notificaciones, cambios de estado y eventos secundarios se desacoplan del flujo principal.                                |
| CON-11 | Las APIs REST serán documentadas con OpenAPI/Swagger.                                                                                                        | Documentación / interoperabilidad | Se asegura trazabilidad de contratos, endpoints y DTOs.                                                                       |
| CON-12 | El proyecto deberá mantenerse en servicios gratuitos o free tier durante la validación académica.                                                            | Económica / despliegue            | Se priorizan Vercel, Oracle Cloud Always Free, Supabase y herramientas open source.                                           |
| CON-13 | No se integrará una pasarela de pagos real en la primera versión implementable.                                                                              | Alcance                           | El sistema modelará acuerdos y estados relacionados al pago, pero la integración financiera real queda como extensión futura. |
| CON-14 | El equipo deberá producir evidencias de implementación, testing, documentación de microservicios y despliegue.                                               | Académica                         | La arquitectura debe ser demostrable mediante repositorio, pruebas, Swagger, CI/CD y ejecución cloud.                         |

Supabase se mantiene como plataforma administrada de PostgreSQL y storage para reducir carga operativa en el equipo; su plan gratuito permite usar PostgreSQL y almacenamiento dentro de límites de validación (Supabase, s. f.-b). Docker Compose se mantiene como restricción de despliegue porque permite definir, ejecutar y mantener aplicaciones multi-contenedor desde una configuración centralizada (Docker, s. f.).

### 4.2.5. Architectural Concerns

| ID     | Architectural Concern                     | Descripción                                                                                                                                          | Decisión relacionada                                                                                           |
| ------ | ----------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- |
| CRN-01 | Delimitación correcta de bounded contexts | Existe riesgo de mezclar responsabilidades de perfil, marketplace, contratación y chat en un mismo módulo.                                           | Separar el backend en cuatro microservicios alineados al dominio.                                              |
| CRN-02 | Evitar sobrearquitectura                  | Una cantidad excesiva de microservicios aumentaría la complejidad operativa y reduciría la probabilidad de completar el proyecto.                    | Mantener cuatro microservicios principales y evitar servicios adicionales no esenciales.                       |
| CRN-03 | Consistencia entre servicios              | Las solicitudes, proyectos, reseñas y notificaciones cruzan límites de microservicios.                                                               | Usar identificadores externos, contratos REST y eventos RabbitMQ para sincronización eventual.                 |
| CRN-04 | Seguridad y ownership                     | Los usuarios deben acceder solo a recursos propios o permitidos por rol.                                                                             | Implementar Spring Security, JWT, roles y validación de ownership en casos de uso.                             |
| CRN-05 | Gestión del chat                          | El chat debe funcionar sin depender de servicios externos pagos ni introducir complejidad excesiva.                                                  | Implementar ChatNotificationService con REST para historial y WebSocket/SSE para actualización en tiempo real. |
| CRN-06 | Persistencia relacional por microservicio | Usar una sola base administrada podría generar acoplamiento si los servicios comparten tablas indiscriminadamente.                                   | Separar esquemas y ownership lógico por microservicio en Supabase PostgreSQL.                                  |
| CRN-07 | Despliegue gratuito sostenible            | El backend debe estar disponible para validación sin depender de plataformas que duermen servicios o expiran bases de datos rápidamente.             | Alojar backend en Oracle Cloud Always Free y delegar base de datos a Supabase.                                 |
| CRN-08 | Testabilidad de reglas de negocio         | Las reglas de contratación, estados, reseñas y pricing deben ser comprobables sin levantar todo el sistema.                                          | Aplicar Clean Architecture, interfaces, mocks, pruebas unitarias y pruebas de integración.                     |
| CRN-09 | Trazabilidad para evaluación académica    | El curso exige evidencias de arquitectura, testing, microservicios, despliegue y documentación.                                                      | Usar GitHub, GitHub Actions, Swagger, commits por microservicio y documentación técnica por sprint.            |
| CRN-10 | Evolución hacia pagos reales              | La solución contempla acuerdos y pagos seguros como parte del dominio, pero la integración con pasarelas reales puede aumentar riesgo y complejidad. | Modelar estados de acuerdo/pago en la primera versión y dejar pasarela real como extensión posterior.          |
| CRN-11 | Dependencia de proveedores externos       | Vercel, Oracle Cloud y Supabase facilitan el despliegue, pero no deben contaminar el dominio.                                                        | Encapsular integraciones en Infrastructure Layer mediante adapters.                                            |
| CRN-12 | Performance en búsquedas                  | La búsqueda de servicios y freelancers puede degradarse al crecer el catálogo.                                                                       | Usar paginación, filtros, índices y DTOs ligeros en GigMarketplaceService.                                     |

#### Resumen de drivers por decisión arquitectónica

| Decisión arquitectónica                       | Drivers que satisface                                                         |
| --------------------------------------------- | ----------------------------------------------------------------------------- |
| Microservicios por bounded context            | Modificabilidad, testabilidad, escalabilidad organizacional y mantenibilidad. |
| Clean Architecture por microservicio          | Testabilidad, modificabilidad e independencia tecnológica.                    |
| Caddy como gateway liviano                    | Interoperabilidad, simplicidad operativa y disponibilidad.                    |
| Supabase PostgreSQL con esquemas por servicio | Persistencia relacional, ownership de datos y mantenibilidad.                 |
| RabbitMQ para eventos internos                | Modificabilidad, disponibilidad parcial y desacoplamiento.                    |
| Spring Security + JWT                         | Seguridad, control de acceso y auditoría.                                     |
| Docker Compose en Oracle Cloud                | Despliegue reproducible, evidencia cloud y control operativo.                 |
| OpenAPI/Swagger                               | Interoperabilidad, documentación, pruebas manuales y automatizadas.           |
| GitHub Actions                                | Testabilidad, trazabilidad y evidencia de calidad.                            |

## 4.3. ADD Iterations

### 4.3.1. Iteration 1: Core Marketplace & Engagement Flow

#### 4.3.1.1. Architectural Design Backlog 1

#### 4.3.1.2. Establish Iteration Goal by Selecting Drivers

#### 4.3.1.3. Choose One or More Elements of the System to Refine

#### 4.3.1.4. Choose One or More Design Concepts That Satisfy the Selected Drivers

#### 4.3.1.5. Instantiate Architectural Elements, Allocate Responsibilities, and Define Interfaces

#### 4.3.1.6. Sketch Views: C4 & UML, and Record Design Decisions

#### 4.3.1.7. Analysis of Current Design and Review Iteration Goal: Kanban Board

### 4.3.2. Iteration 2: Communication, Security & Deployment Readiness

#### 4.3.2.1. Architectural Design Backlog 2

#### 4.3.2.2. Establish Iteration Goal by Selecting Drivers

#### 4.3.2.3. Choose One or More Elements of the System to Refine

#### 4.3.2.4. Choose One or More Design Concepts That Satisfy the Selected Drivers

#### 4.3.2.5. Instantiate Architectural Elements, Allocate Responsibilities, and Define Interfaces

#### 4.3.2.6. Sketch Views: C4 & UML, and Record Design Decisions

#### 4.3.2.7. Analysis of Current Design and Review Iteration Goal: Kanban Board


<div style="page-break-before: always;"></div>

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Testing Suites & General Patterns

### 5.1.1. Backend Application Core Testing Suite

### 5.1.2. Pattern Based Backend Application(s)

### 5.1.3. Pattern Based Custom Software Library

### 5.1.4. Framework Pattern Driven Refactoring Report

## 5.2. Software Configuration Management

### 5.2.1. Software Development Environment Configuration

### 5.2.2. Source Code Management

### 5.2.3. Source Code Style Guide & Conventions

### 5.2.4. Software Deployment Configuration

## 5.3. Microservices Implementation

### 5.3.1. Sprint 1

#### 5.3.1.1. Sprint Backlog 1

#### 5.3.1.2. Development Evidence for Sprint Review

#### 5.3.1.3. Testing Suite Evidence for Sprint Review

#### 5.3.1.4. Execution Evidence for Sprint Review

#### 5.3.1.5. Microservices Documentation Evidence for Sprint Review

#### 5.3.1.6. Software Deployment Evidence for Sprint Review

#### 5.3.1.7. Team Collaboration Insights during Sprint

#### 5.3.1.8. Kanban Board

### 5.3.2. Sprint 2

#### 5.3.2.1. Sprint Backlog 2

#### 5.3.2.2. Development Evidence for Sprint Review

#### 5.3.2.3. Testing Suite Evidence for Sprint Review

#### 5.3.2.4. Execution Evidence for Sprint Review

#### 5.3.2.5. Microservices Documentation Evidence for Sprint Review

#### 5.3.2.6. Software Deployment Evidence for Sprint Review

#### 5.3.2.7. Team Collaboration Insights during Sprint

#### 5.3.2.8. Kanban Board

### 5.3.3. Sprint 3

#### 5.3.3.1. Sprint Backlog 3

#### 5.3.3.2. Development Evidence for Sprint Review

#### 5.3.3.3. Testing Suite Evidence for Sprint Review

#### 5.3.3.4. Execution Evidence for Sprint Review

#### 5.3.3.5. Microservices Documentation Evidence for Sprint Review

#### 5.3.3.6. Software Deployment Evidence for Sprint Review

#### 5.3.3.7. Team Collaboration Insights during Sprint

#### 5.3.3.8. Kanban Board

### 5.3.4. Sprint 4

#### 5.3.4.1. Sprint Backlog 4

#### 5.3.4.2. Development Evidence for Sprint Review

#### 5.3.4.3. Testing Suite Evidence for Sprint Review

#### 5.3.4.4. Execution Evidence for Sprint Review

#### 5.3.4.5. Microservices Documentation Evidence for Sprint Review

#### 5.3.4.6. Software Deployment Evidence for Sprint Review

#### 5.3.4.7. Team Collaboration Insights during Sprint

#### 5.3.4.8. Kanban Board

## 5.4. Microservices Deployment

### 5.4.1. Cloud Architecture Diagram

### 5.4.2. Cloud Architecture Deployment

<div style="page-break-before: always;"></div>

# Conclusiones y recomendaciones

<div style="page-break-before: always;"></div>

# Video About-The-Team

<div style="page-break-before: always;"></div>

# Referencias bibliográficas

Banco Mundial. (2023). *Working without borders: The promise and peril of online gig work*. World Bank. https://openknowledge.worldbank.org/entities/publication/ebc4a7e2-85c6-467b-8713-e2d77e954c6c

Banco Mundial. (2024). *Four ways local online gig platforms connect young people to jobs*. World Bank Blogs. https://blogs.worldbank.org/en/jobs/four-ways-local-online-gig-platforms-connect-young-people-jobs

Caddy. (s. f.-a). *Automatic HTTPS*. Caddy. https://caddyserver.com/docs/automatic-https

Caddy. (s. f.-b). *Reverse proxy quick-start*. Caddy. https://caddyserver.com/docs/quick-starts/reverse-proxy

Docker. (s. f.). *Defining and running multi-container applications with Docker Compose*. Docker Docs. https://docs.docker.com/guides/docker-compose/

GigU. (2026). *Documentación del proyecto GigU*. GitHub. https://github.com/1ASI0657-2610-7940-Final-Project/docs

Instituto Nacional de Estadística e Informática. (2025a). *Perú: Comportamiento de los indicadores del mercado laboral a nivel nacional y en 27 ciudades. Primer trimestre 2025*. INEI. https://www.inei.gob.pe/media/MenuRecursivo/boletines/informe-tecnico_empleonacional_1.pdf

Instituto Nacional de Estadística e Informática. (2025b). *Perú: Comportamiento de los indicadores del mercado laboral a nivel nacional y en 27 ciudades. Segundo trimestre 2025*. INEI. https://m.inei.gob.pe/media/MenuRecursivo/boletines/informe-tecnico_empleonacional_2.pdf

Lewis, J., & Fowler, M. (2014). *Microservices: A definition of this new architectural term*. Martin Fowler. https://martinfowler.com/articles/microservices.html

Ministerio de Educación del Perú. (2021). *Encuesta Nacional de Estudiantes de Educación Superior Universitaria 2019: principales resultados*. MINEDU. https://repositorio.minedu.gob.pe/handle/20.500.12799/7745

Ministerio de Educación del Perú. (2023). *La universidad en cifras*. MINEDU. https://repositorio.minedu.gob.pe/bitstream/handle/20.500.12799/9077/La%20Universidad%20en%20Cifras.pdf

Ministerio de Educación del Perú. (2024). *Reporte nacional de seguimiento al Proyecto Educativo Nacional: Análisis de indicadores al 2023*. MINEDU. https://repositorio.minedu.gob.pe/bitstream/handle/20.500.12799/10653/Reporte%20nacional%20de%20seguimiento%20al%20Proyecto%20Educativo%20Nacional%20an%C3%A1lisis%20de%20indicadores%20al%202023.pdf

OpenAPI Initiative. (s. f.). *OpenAPI Specification*. Swagger. https://swagger.io/specification/

Oracle. (s. f.). *Oracle Cloud Free Tier*. Oracle. https://www.oracle.com/cloud/free/

Oracle. (s. f.). *Always Free Resources*. Oracle Documentation. https://docs.oracle.com/iaas/Content/FreeTier/freetier_topic-Always_Free_Resources.htm

Organización Internacional del Trabajo. (2021). *World Employment and Social Outlook 2021: The role of digital labour platforms in transforming the world of work*. OIT. https://www.ilo.org/publications/flagship-reports/role-digital-labour-platforms-transforming-world-work

Organización Internacional del Trabajo. (2025). *Jóvenes en el mercado laboral: entre la informalidad y la falta de oportunidades*. OIT. https://www.ilo.org/es/resource/news/jovenes-entre-informalidad-y-falta-de-oportunidades

RabbitMQ. (s. f.). *RabbitMQ: One broker to queue them all*. RabbitMQ. https://www.rabbitmq.com/

Spring. (s. f.-a). *Spring Security reference*. Spring. https://docs.spring.io/spring-security/reference/index.html

Spring. (s. f.-b). *Testcontainers support in Spring Boot*. Spring. https://docs.spring.io/spring-boot/reference/testing/testcontainers.html

Supabase. (s. f.-a). *The Postgres development platform*. Supabase. https://supabase.com/

Supabase. (s. f.-b). *Pricing & Fees*. Supabase. https://supabase.com/pricing

Supabase. (s. f.-c). *About billing on Supabase*. Supabase. https://supabase.com/docs/guides/platform/billing-on-supabase

Universidad Peruana de Ciencias Aplicadas. (2025a). *Attribute-Driven Design: SI657 Fundamentos de Arquitectura de Software*. Material del curso.

Universidad Peruana de Ciencias Aplicadas. (2025b). *Final Project Statement: Fundamentos de Arquitectura de Software*. Material del curso.

Vercel. (s. f.). *Vercel Hobby Plan*. Vercel. https://vercel.com/docs/plans/hobby

# Anexos

<div style="page-break-before: always;"></div>

# Links
