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
  * [4.2. Principles Statements](#42-principles-statements)
  * [4.3. Approaches Statements](#43-approaches-statements)
  * [4.4. Architectural Styles & Patterns](#44-architectural-styles--patterns)
  * [4.5. Context Diagram](#45-context-diagram)
  * [4.6. Approach Driven ViewPoints Diagrams](#46-approach-driven-viewpoints-diagrams)
  * [4.7. Relational/Non Relational Database Diagram](#47-relationalnon-relational-database-diagram)
  * [4.8. Design Patterns](#48-design-patterns)
  * [4.9. Tactics](#49-tactics)
  * [4.10. Architectural Drivers](#410-architectural-drivers)

    * [4.10.1. Design Purpose](#4101-design-purpose)
    * [4.10.2. Primary Functionality (Primary User Stories)](#4102-primary-functionality-primary-user-stories)
    * [4.10.3. Quality Attribute Scenarios](#4103-quality-attribute-scenarios)
    * [4.10.4. Constraints](#4104-constraints)
    * [4.10.5. Architectural Concerns](#4105-architectural-concerns)
  * [4.11. ADD Iterations](#411-add-iterations)

    * [4.11.1. Iteration 1](#4111-iteration-1)

      * [4.11.1.1. Architectural Design Backlog 1](#41111-architectural-design-backlog-1)
      * [4.11.1.2. Establish Iteration Goal by Selecting Drivers](#41112-establish-iteration-goal-by-selecting-drivers)
      * [4.11.1.3. Choose One or More Elements of the System to Refine](#41113-choose-one-or-more-elements-of-the-system-to-refine)
      * [4.11.1.4. Choose One or More Design Concepts That Satisfy the Selected Drivers](#41114-choose-one-or-more-design-concepts-that-satisfy-the-selected-drivers)
      * [4.11.1.5. Instantiate Architectural Elements, Allocate Responsibilities, and Define Interfaces](#41115-instantiate-architectural-elements-allocate-responsibilities-and-define-interfaces)
      * [4.11.1.6. Sketch Views (C4 & UML) and Record Design Decisions](#41116-sketch-views-c4--uml-and-record-design-decisions)
      * [4.11.1.7. Analysis of Current Design and Review Iteration Goal](#41117-analysis-of-current-design-and-review-iteration-goal)

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

<div style="page-break-before: always;"></div>

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

| Nombre: Mio Mejia, Andy Alejandro | <img src="imgs/team/andy.png" alt="Andy" title="Foto de Andy" width="320"/> |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------- |
| **Código:** U202218531  |                               |
| **Carrera:** Ingeniería de Software |                               |
| **Habilidades:** Estudiante de ... |          |

## 1.2. Solution Profile

### 1.2.1. Nombre del producto

GigU

### 1.2.2. Antecedentes y problemática

##### **¿Cuál es el problema?**

Muchos estudiantes universitarios enfrentan serias dificultades para generar ingresos y adquirir experiencia profesional mientras cursan sus estudios. Esta carencia de oportunidades laborales adecuadas no solo limita su independencia económica, sino también el desarrollo temprano de habilidades prácticas y su inserción competitiva en el mercado laboral. Según datos del Ministerio de Educación del Perú, una parte importante de los estudiantes universitarios combina estudios y trabajo de manera simultánea, reflejando que la necesidad de generar ingresos aparece incluso antes del egreso. Sin embargo, a pesar de contar con talentos y conocimientos valiosos, la mayoría no dispone de una plataforma accesible, segura y adaptada que les permita ofrecer sus servicios de forma organizada y profesional, especialmente bajo la modalidad freelance.

##### **¿Cuándo ocurre el problema?**

El problema se presenta a lo largo de toda la etapa universitaria, con mayor énfasis a partir del segundo o tercer año de carrera, cuando los estudiantes ya han adquirido capacidades técnicas, académicas o creativas que podrían ser aplicadas en el ámbito laboral. La necesidad de generar ingresos se intensifica en periodos críticos como matrículas, proyectos finales o gastos personales, momentos en los que la presión financiera se convierte en un factor determinante para su permanencia y rendimiento académico.

##### **¿Dónde ocurre el problema?**

Esta problemática es evidente en el contexto universitario peruano y latinoamericano, especialmente en instituciones donde las políticas de empleabilidad son limitadas o inexistentes, y donde los programas de prácticas preprofesionales o los vínculos con el mercado freelance son insuficientes o inaccesibles. Asimismo, en el entorno digital persiste la falta de una plataforma centralizada y especializada que facilite a los estudiantes la oferta de servicios freelance de manera organizada, validada y segura.

##### **¿A quién afecta el problema?**

El problema impacta directamente a estudiantes universitarios que buscan generar ingresos, adquirir experiencia laboral temprana y construir un portafolio real antes de egresar. Esta situación también afecta a microempresas, emprendedores y particulares que requieren servicios profesionales accesibles, confiables y de calidad, y que a menudo no logran encontrar talento joven disponible y verificado en su entorno inmediato.

##### **¿Por qué sucede el problema?**

El problema radica en la falta de plataformas diseñadas específicamente para conectar estudiantes con clientes potenciales, considerando sus limitaciones de tiempo, experiencia y recursos. Las plataformas freelance tradicionales imponen barreras de entrada significativas, como comisiones elevadas, competencia global desproporcionada y escasa validación académica de perfiles, lo que desalienta la participación de estudiantes y perpetúa su informalidad laboral.

##### **¿Cómo sucede el problema?**

En ausencia de alternativas formales y especializadas, los estudiantes optan por ofrecer sus servicios a través de redes sociales, contactos personales o plataformas genéricas que no garantizan seguridad, visibilidad ni condiciones laborales justas. Esta informalidad expone a los estudiantes a malas prácticas, incumplimientos de pago, sobreexplotación de tiempo y escaso reconocimiento de sus capacidades, lo que frecuentemente deriva en frustración, desmotivación y experiencias laborales negativas.

##### **¿Cuán grande es el impacto de este problema?**

El impacto es considerable tanto en el plano individual como en el social. En el Perú, una alta proporción de jóvenes trabaja en condiciones de informalidad, lo que evidencia una fuerte precarización del empleo juvenil y una limitada protección social. Además, la tasa de desempleo juvenil supera al promedio nacional, posicionando a este grupo como uno de los más vulnerables del mercado laboral. Esta realidad afecta directamente su desarrollo personal y profesional, retrasa su independencia económica y limita su proyección laboral futura.

### 1.2.3. Lean UX Process

#### 1.2.3.1. Lean UX Problem Statement

En el contexto universitario peruano, los estudiantes enfrentan grandes desafíos para insertarse en el mercado laboral mientras cursan sus estudios. La mayoría se enfrenta a condiciones de informalidad o desempleo, lo cual limita su desarrollo profesional desde una etapa temprana.

Hemos observado que no existen plataformas efectivas y especializadas que conecten directamente a estudiantes universitarios con oportunidades laborales formales, flexibles y alineadas a sus carreras, lo cual perpetúa la falta de experiencia profesional al egresar.

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

### 2.1.1. Análisis competitivo

### 2.1.2. Estrategias y tácticas frente a competidores

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

### 2.2.2. Registro de entrevistas

### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding

### 2.3.1. User Personas

### 2.3.2. User Task Matrix

### 2.3.3. Empathy Maps

### 2.3.4. As-Is Scenario Mapping

<div style="page-break-before: always;"></div>

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

## 3.2. User Stories

## 3.3. Impact Map

## 3.4. Product Backlog

<div style="page-break-before: always;"></div>

# Capítulo IV: Product Architecture Design

## 4.1. Design Concepts, ViewPoints & ER Diagrams

## 4.2. Principles Statements

## 4.3. Approaches Statements

## 4.4. Architectural Styles & Patterns

## 4.5. Context Diagram

## 4.6. Approach Driven ViewPoints Diagrams

## 4.7. Relational/Non Relational Database Diagram

## 4.8. Design Patterns

## 4.9. Tactics

## 4.10. Architectural Drivers

### 4.10.1. Design Purpose

### 4.10.2. Primary Functionality (Primary User Stories)

### 4.10.3. Quality Attribute Scenarios

### 4.10.4. Constraints

### 4.10.5. Architectural Concerns

## 4.11. ADD Iterations

### 4.11.1. Iteration 1

#### 4.11.1.1. Architectural Design Backlog 1

#### 4.11.1.2. Establish Iteration Goal by Selecting Drivers

#### 4.11.1.3. Choose One or More Elements of the System to Refine

#### 4.11.1.4. Choose One or More Design Concepts That Satisfy the Selected Drivers

#### 4.11.1.5. Instantiate Architectural Elements, Allocate Responsibilities, and Define Interfaces

#### 4.11.1.6. Sketch Views (C4 & UML) and Record Design Decisions

#### 4.11.1.7. Analysis of Current Design and Review Iteration Goal

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

<div style="page-break-before: always;"></div>

# Anexos

<div style="page-break-before: always;"></div>

# Links
