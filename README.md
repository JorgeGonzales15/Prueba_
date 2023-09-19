![UPC_logo_transparente (1)](https://github.com/JorgeGonzales15/SW51-GreatMinds-OpenSource/assets/104078975/2ff342be-dc34-415c-925e-1e7133e49abf)

Universidad Peruana de Ciencias Aplicadas

Ingeniería de Software

Ciclo 2023-02

# DESARROLLO DE APLICACIONES OPEN SOURCE

Sección SW51

Profesor: Velasquez Nuñez, Angel Augusto

***INFORME DE TRABAJO FINAL - TB1***

**Startup: GreatMinds**

**Producto: Ayni**

**Integrantes:**
- Espejo Macuri, Paolo Andre
- Gonzales Carrión, Jorge Enrique
- Huaman Catano, Miguel Angel
- Paucar De La Cruz, Tatiana Medalith
- Zarate Castro, Jose Daniel

Agosto del 2023

---
# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de la modificación |
| - | - | - | - |
| 1.00 | 08/09/2022 | Jorge Gonzales, Paolo Espejo, Miguel Huaman, Tatiana Paucar, Jose Zarate | Implementación de startup profile, solution profile, segmento objetivo, competidores, entervistas, needfinding, journey map, product backlog, entre otros. Asimismo, la implementación de Landing Page Wireframe, Landing Page Mockup, Information Architecture, Software Architecture Context Diagram, Class Diagram, Software Configuration Management, entre otros. Todos estos puntos mencionados y más corresponden a los siguientes capitulos: Capítulo I: Introducción, Capítulo II: Requirements Elicitation & Analysis, Capítulo III: Requirements Specification, Capítulo IV: Product Design, Capítulo V: Product Implementation, Validation & Deployment (Hasta el punto 5.2.1.8 correspondiente al Sprint 1)|

---
# Project Report Collaboration Insights

TB1: Se han desarrollado las actividades correspondientes para la entrega TB1 en el siguiente repositorio de Github dentro de la organización del equipo:
Link de repositorio Github: (https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource)

![commitsinformeopen](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/1665e68a-849a-4c87-887e-a5d7e17d6b6c)

Como se evidencia, todos trabajaron en la presente entrega, usando Github se logró completar el informe con los siguientes capítulos: 

- Capítulo I: Introducción
- Capítulo II: Requirements Elicitation & Analysis
- Capítulo III: Requirements Specification
- Capítulo IV: Product Design
- Capítulo V: Product Implementation, Validation & Deployment (Hasta el punto 5.2.1.8 correspondiente al Sprint 1)

---
# Contenido 
## Tabla de contenidos


## [Capítulo I: Introducción](#capítulo-i-introducción)
- [1.1. Startup Profile](#11-startup-profile)
  - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
  - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](#12-solution-profile)
  - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
  - [1.2.2 Lean UX Process](#122-lean-ux-process)
    - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
    - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
    - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
    - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)

## [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
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

## [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Impact Mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)

## [Capítulo IV: Product Design](#capítulo-iv-product-design)
- [4.1. Style Guidelines](#41-style-guidelines)
  - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
  - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
- [4.2. Information Architecture](#42-information-architecture)
  - [4.2.1. Organization Systems](#421-organization-systems)
  - [4.2.2. Labeling Systems](#422-labeling-systems)
  - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
  - [4.2.4. Searching Systems](#424-searching-systems)
  - [4.2.5. Navigation Systems](#425-navigation-systems)
- [4.3. Landing Page UI Design](#43-landing-page-ui-design)
  - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
  - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
- [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
  - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
  - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
  - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
  - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
- [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
- [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
  - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
  - [4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
  - [4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
- [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
  - [4.7.1. Class Diagrams](#471-class-diagrams)
  - [4.7.2. Class Dictionary](#472-class-dictionary)
- [4.8. Database Design](#48-database-design)
  - [4.8.1. Database Diagram](#481-database-diagram)

## [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
- [5.1. Software Configuration Management](#51-software-configuration-management)
  - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
  - [5.1.2. Source Code Management](#512-source-code-management)
  - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
  - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
- [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
  - [5.2.1. Sprint 1](#521-sprint-1)
    - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
    - [5.2.1.2. Sprint Backlog 1](#5212-sprint-backlog-1)
    - [5.2.1.3. Development Evidence for Sprint Review](#5213-development-evidence-for-sprint-review)
    - [5.2.1.4. Testing Suite Evidence for Sprint Review](#5214-testing-suite-evidence-for-sprint-review)
    - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
    - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
    - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
    - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
  - [5.2.2. Sprint 2](#522-sprint-2)
    - [5.2.2.1. Sprint Planning 2](#5221-sprint-planning-2)
    - [5.2.2.2. Sprint Backlog 2](#5222-sprint-backlog-2)
    - [5.2.2.3. Development Evidence for Sprint Review](#5223-development-evidence-for-sprint-review)
    - [5.2.2.4. Testing Suite Evidence for Sprint Review](#5224-testing-suite-evidence-for-sprint-review)
    - [5.2.2.5. Execution Evidence for Sprint Review](#5225-execution-evidence-for-sprint-review)
    - [5.2.2.6. Services Documentation Evidence for Sprint Review](#5226-services-documentation-evidence-for-sprint-review)
    - [5.2.2.7. Software Deployment Evidence for Sprint Review](#5227-software-deployment-evidence-for-sprint-review)
    - [5.2.2.8. Team Collaboration Insights during Sprint](#5228-team-collaboration-insights-during-sprint)

## [Conclusiones](#conclusiones)

## [Referencias](#referencias)

## [Anexos](#anexos)

---

# Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

ABET – EAC - Student Outcome 3

Criterio: Capacidad de comunicarse efectivamente con un rango de audiencias.

En el siguiente cuadro se describe las acciones realizadas y enunciados de 
conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro 
del ABET – EAC - Student Outcome 3.

| Criterio específico | Acciones realizadas | Conclusiones |
| - | - | - |
| Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto en ingeniería. | **Jorge Gonzales - TB1:** Se ha definido el alcance del proyecto, la temática, y la delegación de tareas. <br> **Paolo Espejo -TB1:** Se realizaron las entrevistas comunicando oralmente las preguntas necesarias para obtener información por parte del segmento objetivo y se realizó el analisis de todas las entrevistas sustendando al equipo las funcionalidades que desean los usuarios. <br> **Tatiana Paucar - TB1:** Se propuso el Lean UX process al equipo y consultándolo entre todo el equipo se hizo el desarrollo de este. Asimismo, se propuso el modelado de diagrama de clases y de base de datos. <br> **Miguel Huaman -TB1:** Se propuso el needfinding y se comunicó las caracteristicas de desarrollo a todo el equipo. <br> **Jose Zarate - TB1:** Se propuso ideas para el capítulo de Requirements Specification y los mockups y wireframes de la landing page. | Se distribuyeron diferentes actividades para el desarrollo del trabajo para que cada integrante pueda desempeñarse en un área en específica, luego pudimos realizar las tareas asignadas. Para finalizar, todos los integrantes del equipo lograron comunicar oralmente sus ideas de manera eficaz |
| Comunica en forma escrita ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto en ingeniería. | **Jorge Gonzales - TB1:** Se realizaron propuestas escritas para los General Style Guidelines asimismo propuestas para los wireframes y mockups para la aplicación web. <br> **Paolo Espejo - TB1** Se realizó el planteamiento de las preguntas para las entrevistas y se hizo el analisis de estas. <br> **Tatiana Paucar - TB1:** Se plantearon en escrito el Lean UX Process y los diagramas de clases y de base de datos. <br> **Miguel Huaman - TB1:** Se plantearon los puntos del NeedFinding. <br> **Jose Zarate - TB1:** Se plantearon los mockups y wireframes de la landing page | Cada integrante desarrolló los items para esta entrega y comúnico sus aportes de manera escrita y formal para este sprint. |

# Capítulo I: Introducción

## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup

El startup que se introduce en el presente informe recibe como nombre “GreatMinds”. Actualmente conformado por un conjunto de estudiantes de la Universidad Peruana de Ciencias Aplicadas, con la ambición de querer ayudar a la sociedad con nuestra grán pasión a la tecnología e informática, creamos esta startup tomando como objetivo facilitar y mejorar la producción del sector agrícola del Perú. 

Como misión se plantea “Incrementar la producción agrícola con eficiencia, seguridad y transparencia entre productores y exportadores del Perú”. Asimismo, la visión de la startup plantea desarrollar la aplicación más reconocida en el Perú para gestionar cultivos de manera segura, sencilla y online.

### 1.1.2. Perfiles de integrantes del equipo

Mi nombre es Jorge Enrique Gonzales Carrión tengo 19 años de edad y curso el sexto ciclo de la carrera Ingeniería de Software. Me considero una persona con sentido de responsabilidad y la suficiente capacidad de trabajar en equipo aportando ideas innovadoras. Además, en cualidades me considero asertivo y colaborativo, puntos que pueden mejorar el proceso de elaboración de los distintos trabajos del curso. Finalmente, poseo conocimientos de programación que brindaron los ciclos anteriores al presente.

![jroge](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/f2ae0bea-109a-48cb-abd8-47db542006c3)

---

Mi nombre es Tatiana Medalith Paucar De La Cruz, tengo 19 años y soy estudiante del quinto ciclo de la carrera de ingeniería de software en la Universidad Peruana de Ciencias Aplicadas (UPC). Me considero una persona autodidacta, lo que me permite adquirir nuevos conocimientos de manera constante. Asimismo, me considero una persona bastante organizada y responsable en el ámbito académico. Además de ello, me gusta trabajar arduamente para lograr objetivos comunes dentro de un proyecto.

![tatiana](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/b7b10f6f-9b4a-4969-903a-0f6a02f98e3b)

---

Mi nombre es Jose Daniel Zarate Castro y actualmente tengo 20 años. Soy un estudiante de Ingeniería de Software en el quinto ciclo de mi formación académica. Soy una persona muy orientada al trabajo en equipo y siempre estoy entusiasmado por colaborar y contribuir al máximo. Me considero un participante activo en cualquier proyecto o actividad que emprenda. Tengo una actitud empática hacia los demás y me esfuerzo por entender las necesidades y perspectivas de mis compañeros. En términos de conocimientos técnicos tengo conocimientos en Java, c# y Python.

![jose](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/d666fad1-9ecc-434f-902a-ade49f2c63ad)

---

Mi nombre es Miguel Ángel Huamán Cataño, tengo 19 años y actualmente estoy estudiando el 5to ciclo de la carrera de Ingeniería de software en la Universidad Peruana de Ciencias Aplicadas. Me considero una persona responsable que es capaz de lograr lo que se propone. Además, siempre tengo una actitud positiva y respetuosa con las demás personas. Poseo los conocimientos de programación brindados por la universidad y sé lo básico de algunos otros lenguajes de programación , soy capaz de aprender rápidamente sobre ciertos temas gracias a mi buena lógica y capacidad de aprendizaje.

![miguel](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/0ed846d6-bb18-4980-8871-ad2f983eb236)

---

Mi nombre es Paolo Andre Espejo Macuri, tengo 20 años de edad, estoy cursando el sexto ciclo de la carrera de Ingeniería de Software en la UPC. Soy hábil con las TICs y soy una persona creativa para proporcionar ideas innovadoras. Aprendo de forma rápida nuevos temas al practicarlos y se me da bien la programación y la solución de errores.

![paolo](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/386b5d22-7174-4557-a91f-721da4c3cea4)

---

## 1.2. Solution Profile

En el presente punto, se pasará a la explicación detallada del producto solución, factor innovador y la forma en la cual será monetizada.

**Product Name**

La aplicación web recibirá el nombre “Ayni”, debido a que, en el lenguaje quechua, es un concepto de reciprocidad o mutualismo entre comunidades andinas. Además, se puede interpretar como un verbo, que se refiere a la cooperación entre miembros cuando un miembro brinda apoyo a otro, teniendo el derecho a recibir algo a cambio. Este concepto está presente en etnias que viven en Perú, Ecuador y Bolivia. 

**Product Description**

El software es innovador ya que se encarga de ofrecer un sistema de gestión para productos agrícolas que mejore la calidad de su producción para su venta o exportación con herramientas de registro, notificación y planificación. Debido a ello, está enfocado principalmente a los productores de cultivos, en donde ellos pueden hacer un plan de cultivo, registrar parcelas, gestionar insumos, obtener un historial de cultivos, gestionar sus costos y gastos y atender pedidos. Por otro lado también tenemos a los exportadores, que pueden realizar pedidos a los productores y dejar reseñas acerca de los servicios brindados.

**Monetización**

Nuestra aplicación será monetizada a través de publicidad sobre insumos para cultivar, de esta manera se cobrará por la aparición de publicidad en la aplicación a proveedores de insumos. De esta manera, nuestra aplicación se volverá un entorno completo para que los productores mejoren sus productos con los insumos que serán publicitados en la aplicación (libre elección de compra).

### 1.2.1 Antecedentes y problemática

En los últimos años, el sector agrícola en el Perú, ha presentado una tasa de empleo durante el segundo trimestre del año 2020 un aumento de un 22.6% y en el tercero, un 20.5%, a pesar de que la población ocupada a nivel nacional se contrajo un 39.6% y un 17.1% en dichos periodos, respectivamente, con respecto a los mismos de 2019, según el Instituto Nacional de Estadística e Informática (INEI). Asimismo, si bien el PBI nacional acumulado al tercer trimestre disminuyó un 14.5% con respecto al mismo periodo del año pasado, el PBI agropecuario aumentó un 0.8%, uno de los mejores resultados, según cifras del Banco Central de Reserva del Perú. Desafortunadamente, este sector no se libra de los diversos problemas para progresar pese a ser uno de los sectores más importantes para el desarrollo de Perú. Esta situación es resaltada por Moreno (2022, como se citó en Coordinadora de Entidades Extranjeras de Cooperación Internacional, 2022), quien expresó su preocupación por la situación precaria de los cultivos en los últimos años entre uno de los problemas que atraviesa el 24% de los empleados que pertenecen al sector agrario.

**Herramienta 5W y 2H**

**¿Qué? (What)**

Según el Ministerio de Desarrollo Agrario y Riego (MIDAGRI, 2022), las actividades agrarias son reconocidas por el desorden en la producción y la baja rentabilidad y competitividad. Por lo tanto, el problema identificado es la informalidad y el desorden en el proceso de producción y venta de los productos agrícolas, en consecuencia, se obtienen productos de mala calidad y ventas que si bien son de primer contacto entre productores y comerciantes, los precios tienden a ser regateados.

**¿Cuándo? (When)**

Este es un problema que se puede observar en todo en los grupos que se dedican a la producción de cultivos de manera informal, tradicional o incluso en cadenas de producción. Este problema está presente en todo el proceso de cultivo de los productos, además en todas 
las horas de trabajo de los agricultores se necesitan seguir una serie de pasos, donde estos pueden fallar durante el proceso ocasionando bajas en la calidad de los productos.

**¿Dónde? (Where)**

Para especificar dónde residen las problemáticas tenemos que observar el comportamiento de los mismos productos, por lo tanto, sus precios. Existen diversos factores que explicarían una contracción en los precios que reciben los agricultores. Por ejemplo, respecto de las papas, el MIDAGRI reporta que sus ingresos por kilogramo se redujeron, en promedio, a S/ 0.89, cuando en el mismo periodo de 2019 ascendían a S/ 1.08. Además, también se registró un incremento considerable de la producción nacional durante los primeros cuatro meses del año 2019, pues se acumuló un aumento interanual del 13.9%, mientras que en el mismo periodo esta apenas creció un 3.9%, lo que no fue respondido adecuadamente por la demanda y generó una disminución inicial de los precios. Posteriormente, la agudización de la presente crisis económica perjudicó considerablemente la masa salarial, lo cual implicaría un menor consumo de lo habitual y limitaría su recuperación. 

**¿Quién? (Who)**

Los principales afectados por las problemáticas relacionadas al sector agrario, según el INEI (2022), en el segundo trimestre del año 2022, 4.1 millones de personas trabajaron en el sector agrícola. Como se puede apreciar, esta cifra es considerablemente alta para abarcar tanto a los productores de cultivos como a los exportadores o comercializadores.

**¿Por qué? (Why)**

Moreno (2022, como se citó en CEECI, 2022) resaltó las causas de los problemas estructurales del sector agrario, entre ellos está el bajo nivel de desarrollo competitivo, la baja integración de los productores en la cadena de valor, el alto índice de familias de productores con escaso acceso al mercado y el inadecuado uso de recursos naturales en la producción.

**¿Cómo? (How)**

Este problema se diferencia bastante a la situación normal del sector agrícola, debido a que representan cifras de pérdidas de millones de soles bastante considerables con respecto a otros años. Esta tendencia si bien se mantiene constante debido a problemas tales como crisis, condiciones climáticas, erosiones de suelo, etc. En la pandemia COVID - 19 se tuvo un declive gracias al distanciamiento social.

**¿Cuánto? (How Much)**

El problema del bajo rendimiento de los cultivos en Perú se refleja en una pérdida diaria de hasta S/50,8 millones de soles debido a condiciones climáticas y falta de calidad en los productos según la Cámara de Comercio de Lima (2023). Por otro lado, en el año 2020 debido a la pandemia se obtuvo una pérdida por S/1611 millones de soles, producto de las medidas de aislamiento ante el COVID-19 (Gobierno de la República, 2020). Todas estas pérdidas siguen significando heridas para el sector agrícola, debido a ello, aún no se logra recuperar del todo.

**Conclusiones de las 5W + 2H**

Luego de haber desarrollado las 5W’s y 2H’s se logró desarrollar una visión general sobre la problemática, cuyo alcance es de ámbito nacional. Para conseguir resultados verídicos y garantizar el funcionamiento de la aplicación, se optará por presentar el producto solución a un público nacional. Existen pocas soluciones actuales a la problemática, para erradicar estas problemáticas se desarrollará una aplicación que permita la gestión de productos agrícolas que permita a los productores realizar funciones de mantenimiento tales como planificación de cultivos personalizado y no personalizado, registro de gastos y ganancias, gestión de insumos, reportes de producción y calidad y control de plagas. Por otro lado, como función de secuencia o tipo flujo dirigida a los comerciantes, tal que pueden realizar la compra de productos, que se compone de una búsqueda, venta y validación. Asimismo, se contará con un sistema de calificación y reseñas que se mostrará luego de realizar un pedido o compra. Tanto los productores y comerciantes accederán a la aplicación mediante un dispositivo electrónico con conexión a internet; las computadoras junto con un navegador serán el principal medio de acceso para la aplicación.

### 1.2.2 Lean UX Process.
#### 1.2.2.1. Lean UX Problem Statements.

El propósito de “Ayni” es proporcionar al sector agrícola una solución tecnológica integral que permita planificar, monitorear y optimizar de manera eficiente las diversas actividades realizadas durante todas las etapas de producción de los cultivos. Esta solución responde a la problemática de la ausencia de una planificación precisa que permita a los agricultores manejar sus cultivos de manera adecuada y lograr una cosecha fructífera.

Actualmente, existen pocas aplicaciones de plataformas que ofrecen soluciones orientadas a la gestión de los cultivos en el sector agrícola. En ese sentido, nuestra plataforma busca ingresar al mercado como una alternativa diferenciadora, con el propósito de resolver los problemas a los que se enfrentan los productores agrícolas.

Sin embargo, hemos observado un factor crítico que perjudica la productividad agrícola: la falta de una herramienta integrada que permita tomar decisiones de manera informada. Como consecuencia, se hace un uso ineficiente de los recursos naturales y el rendimiento del terreno se reduce.

A partir de lo anterior, resulta posible plantear la principal interrogante que el proyecto propone resolver:

**¿Cómo mejorar el proceso de cultivo y la gestión de los recursos en el sector agrícola?**

#### 1.2.2.2. Lean UX Assumptions.

**Business Outcomes:**

Incremento de las transacciones de compra de productos agrícolas en un 30%.
Incrementar el número de usuarios de la plataforma de un 40%
Obtener ganancias a partir de los anuncios de insumos publicados en la plataforma.

**Users:**

Productores agrícolas que desean gestionar eficientemente sus cultivos
Personas que deseen comprar los productos agrícolas para uso propio o distribución

**User Outcomes & Benefits:**

- Productores:
Acceso a un mercado más amplio de compradores de productos agrícolas.
Aumento de la eficiencia en la gestión del inventario.
Posibilidad de obtener retroalimentación por parte de los compradores, para mejorar la calidad de sus productos.

- Comercializadores:
Simplicidad en la búsqueda de productos agrícolas y la comparación entre ellas.
Seguridad y eficiencia a la hora de realizar el proceso de compra.
Posibilidad de tener acceso a toda la información detallada del producto.

**Features Assumptions**
- Imágenes e información detallada  sobre los productos agrícolas ofrecidos en línea
- Función de reseña y calificación hacia los productos adquiridos
- Sección para ingresar los gastos, ingresos y a partir de ello, estimar las ganancias.
- Calendario agrícola que muestra las actividades a realizar
- Anuncios de insumos agrícolas

**User Assumptions**

1. **¿Quién es el usuario?**
Los usuarios de nuestra plataforma son pequeños y medianos agricultores que desean mejorar la gestión de sus cultivos. Asimismo, también está dirigido a las personas interesadas en comprar productos frescos y de calidad directamente de los productores.
2. **¿Dónde encaja nuestro producto en su trabajo o vida?**
Nuestro producto encaja en la vida diaria de los agricultores, debido a que les brinda una herramienta digital que les permite planificar, registrar y dar un seguimiento a todas las actividades agrícolas de manera más eficiente. Por otro lado, los compradores pueden encontrar y adquirir diversos productos agrícolas de buena calidad en nuestra plataforma.
3. **¿Qué problemas tiene nuestro producto? ¿Evitar?**
Nuestro producto puede enfrentar algunos desafíos como la percepción de ser compleja de usar por algunos agricultores. Para evitar ello, la interfaz debe lucir sencilla e interactiva. Además, se pueden incluir tutoriales acerca de la funcionalidad de la aplicación. 
4. **¿Cuándo y cómo es nuestro producto? ¿Usado?**
Nuestra aplicación está diseñada para ser utilizada por el agricultor durante todo el proceso de cultivo, que va desde la siembra hasta la cosecha y posterior venta de los productos. Asimismo, es útil para programar actividades, registrar datos importantes y recibir reportes. Los compradores podrán buscar productos y realizar pedidos.

5. **¿Qué características son importantes?**
 Algunas funcionalidades importantes en la aplicación serán la programación de actividades, el registro de los gastos y las ganancias, la gestión de los insumos, control de plagas, reportes detallados en base a la información ingresada, entre otros. Por otro lado, los compradores podrán utilizar la aplicación para buscar productos agrícolas  de buena calidad, obtener información acerca de estos, realizar pedidos y acceder a un sistema de calificación y reseñas.

6. **¿Cómo debe verse nuestro producto y cómo comportarse?**
La interfaz de nuestro producto debe ser sencilla e intuitiva para simplificar  su uso. Además, el tiempo de respuesta de las funcionalidades debe ser rápido para que el usuario no pierda interés al momento de utilizar la aplicación.


**Business Assumptions**

1. **Creemos que nuestros clientes necesitan** una mejor planificación de sus actividades agrícolas para maximizar la eficiencia de sus cultivos.
2. **Estas necesidades se pueden resolver con una** aplicación web que brinda la posibilidad de gestionar adecuadamente los procesos agrícolas y que permite la compra de productos agrícolas.
3. **El valor #1 que mi cliente quiere de mi servicio** es la capacidad de aumentar su eficiencia al organizarse mejor mediante la aplicación y una dinámica de compra y venta sencilla.
4. **El cliente también puede obtener beneficios adicionales como** el acceso directo a los mercados mediante un sistema de compra entre los consumidores y productores. Gracias a ello, los productores pueden obtener mayores ingresos. 
5. **Voy a adquirir la mayoría de mis clientes** mediante el marketing de boca a boca, o el anuncio mediante redes sociales o la radio.
6. **Haré dinero a través de** la publicación de anuncios por parte de personas que quieran ofrecer servicios o productos destinados a los agricultores, tales como fertilizantes u otros pesticidas.
7. **Mi competencia principal en el mercado** serán otras aplicaciones que ofrecen un servicio similar al planteado para este proyecto.
8. **Los venceremos debido a la simplicidad** de uso de nuestra aplicación y a la combinación de funcionalidades únicas que permiten combatir con problemas específicos, como el control de plagas, entre otros.
9. **El mayor riesgo es que** los agricultores y los compradores no utilicen la aplicación por considerarla demasiado compleja de usar o simplemente resistirse al cambio.
10. **Resolveremos esto a través de** la agregación de funcionalidades útiles para ambos segmentos objetivos.

#### 1.2.2.3. Lean UX Hypothesis Statements.

- **Creemos que** los agricultores necesitan organizar sus actividades diarias. 
**Sabremos que hemos tenido éxito**
cuando nuestra aplicación se vuelva parte de su rutina para cosechar.

- **Creemos que** los agricultores necesitan gestionar sus costos e ingresos.
**Sabremos que hemos tenido éxito**
cuando nuestra aplicación ayude a la economía de los clientes y maximizar la calidad de sus productos

- **Creemos que** los comerciantes o exportadores necesitan comprar productos de calidad y contacto directo con los productores
  **Sabremos que hemos tenido éxito**
cuando nuestra aplicación se vuelva el principal medio de comercio entre productores y comerciantes

- **Creemos que** los comerciantes deben calificar los productos que compraron 
**Sabremos que hemos tenido éxito**
cuando las calificaciones sustenten la calidad de los productos de los productores dentro de la aplicación

- **Creemos que** generamos ganancias por publicidad de insumos para agricultura dentro de la aplicación
**Sabremos que hemos tenido éxito**
cuando recibamos los fondos por brindar la publicidad a los proveedores de insumos

#### 1.2.2.4. Lean UX Canvas.

![canva](https://github.com/JorgeGonzales15/SW51-GreatMinds-OpenSource/assets/104078975/c0507000-b2bd-4708-b688-8caa5942e26e)

### 1.3. Segmentos objetivo.

| Tipo de Usuario | Productores que deseen mejorar la calidad de sus cultivos | Exportadores que deseen comercializar productos de calidad | 
| - | - | - |
| Geografico | País: Perú <br> Zona residencial: Zonas rurales que cuentan con campos de cultivo | País: Perú <br> Zona residencial: Zona aledaña a campos de cultivo |  
| Psicográfico | Clase Social: Media - Baja <br> Estilo de Vida: Deben ser personas con conocimientos familiares o técnicos de cultivos, que participen activamente en el cuidado de una parcela para obtener ganancias de la cosecha. | Clase social: No es relevante dado que pueden ser comerciantes independientes o entidades en conjunto. <br> Estilo de vida: Deben ser personas que se dedican a la compra/venta de productos agrícolas con contacto directo con los productores. |  
| Demográfico | Edad: 20-50 <br> Nivel de Ingreso: No es relevante, pues está dirigido a cualquier persona pero que se dedique a la producción de cultivo | Edad: 20-50 <br> Nivel de ingreso: No es relevante. | 


