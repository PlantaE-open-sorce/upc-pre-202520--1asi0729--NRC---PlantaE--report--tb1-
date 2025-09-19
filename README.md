<h2 align="center">
  <img style="height: 200px" src="assets/logos/upc.png">
</h2>

<h1 align="center">Universidad Peruana de Ciencias Aplicadas</h1>

<h3 align="center">
  Ingeniería de Software
  <br><br>
  Curso: Desarrollo de Aplicaciones Open Source
  <br><br>
  Sección: 7380
  <br><br>
  Profesor: Hugo Allan Mori Paiva
  <br><br>
  Semestre: 2025-20
  <br><br>
  Informe del Trabajo Final
  <br><br>
  Startup: EcoTech
  <br><br>
  Producto: PlantaE
</h3>

<div align="center">

| <div style="width:300px">Alumno</div>       | <div style="width:125px">Código</div>       |
|:-------------------------------------------:|:-------------------------------------------:|
|       Apaza Bocanegra, Elizabeth Noelia     |            u20231c197                       |
|       Contreras Leon, Flor De María         |            u202323243                       |
|       Guillen Galindo, Julio Adolfo         |            u20241a352                       |
|       Miraval Pomalaya, Rodrigo Jesus       |            u202311082                       |
|       Navarro Chinga, Antonio Jhair         |            u202314101                       |

</div>

<div align="center"> Setiembre 2025 </div>

<hr>

<div style="page-break-after: always;"></div>

# Registro de Versiones del Informe  
<div align="center">

| Versión | Fecha       | Autor(es)                            | Descripción de modificación                             |
|---------|-------------|--------------------------------------|---------------------------------------------------------|
|   0.1   | 12/09/2025  | Apaza Bocanegra, Elizabeth Noelia    |  Elaboración de la estructura inicial del reporte.      |

</div>

# Project Report Collaboration Insights  

---

# Contenido
- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Contenido](#contenido)
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
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
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
  - [2.4. Big Picture Event Storming](#24-big-picture-event-storming)
  - [2.5. Ubiquitous Language](#25-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. User Stories](#31-user-stories)
  - [3.2. Impact Mapping](#32-impact-mapping)
  - [3.3. Product Backlog](#33-product-backlog)
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
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
    - [4.4.2. Web Applications Mock-ups](#442-web-applications-mock-ups)
    - [4.4.3. Web Applications User Flow Diagrams](#443-web-applications-user-flow-diagrams)
  - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1. Design-Level Event Storming](#461-design-level-event-storming)
    - [4.6.2. Software Architecture Context Diagram](#462-software-architecture-context-diagram)
    - [4.6.3. Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)
    - [4.6.4. Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
  - [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagrams](#481-database-diagrams)
- [Capítulo V: Product Implementation, Validation \& Deployment](#capítulo-v-product-implementation-validation--deployment)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide \& Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services \& Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint 1](#521-sprint-1)
      - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
      - [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
      - [5.2.1.3. Sprint Backlog 1](#5213-sprint-backlog-1)
      - [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
      - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)

- [Conclusiones](#conclusiones)
- [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Video About-the-Team](#video-about-the-team)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

# Student Outcome  
El curso contribuye al cumplimiento del Student Outcome ABET:
**ABET – EAC - Student Outcome 3**
Capacidad de comunicarse efectivamente con un rango de audiencias.
En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 3.

|             <div align="center">Criterio específico</div>             |          <div align="center">Acciones Realizadas</div>            |          <div align="center">Conclusiones</div>            |
|:---------------------------------------------------------------------:|-------------------------------------------------------------------|------------------------------------------------------------|
| Comunica oralmente con efectividad a diferentes rangos de audiencia.  | <li>**Apaza Bocanegra, Elizabeth Noelia** <br> **TB1:** <br> </li><li>**Contreras Leon, Flor De María** <br> **TB1:** <br> </li><li>**Guillen Galindo, Julio Adolfo** <br> **TB1:** <br> </li><li>**Miraval Pomalaya, Rodrigo Jesus** <br> **TB1:** <br> </li><li>**Navarro Chinga, Antonio Jhair** <br> **TB1:** | <li>**TB1:** </li> |
| Comunica por escrito con efectividad a diferentes rangos de audiencia | <li>**Apaza Bocanegra, Elizabeth Noelia** <br> **TB1:** <br> </li><li>**Contreras Leon, Flor De María** <br> **TB1:** <br> </li><li>**Guillen Galindo, Julio Adolfo** <br> **TB1:** <br> </li><li>**Miraval Pomalaya, Rodrigo Jesus** <br> **TB1:** <br> </li><li>**Navarro Chinga, Antonio Jhair** <br> **TB1:** | <li>**TB1:** </li> |

<hr>

# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
Somos EcoTech, una startup universitaria conformada por estudiantes de la Universidad Peruana de Ciencias Aplicadas (UPC), dedicada a desarrollar soluciones tecnológicas que promuevan la sostenibilidad y el cuidado responsable de los recursos naturales. En un contexto donde la agricultura urbana y el mantenimiento de áreas verdes enfrentan retos de eficiencia y gestiones, presentamos PlantaE, una plataforma inteligente basada en IoT que permite a los usuarios monitorear y optimizar el cuidado de sus plantas y cultivos urbanos.

PlantaE surge ante la creciente necesidad de contar con herramientas accesibles y confiables que faciliten el riego eficiente y el cuidado de áreas verdes en hogares y viveros. La aplicación recopila datos en tiempo real sobre humedad, temperatura, luminosidad y calidad del aire mediante sensores instalados en macetas o terrenos de cultivo, brindando a los usuarios notificaciones oportunas y recomendaciones personalizadas para garantizar la salud de sus plantas. Ademas de, contribuir al uso responsable del agua, ofreciendo una plataforma que combina tecnología, sostenibilidad y facilidad de uso. Con PlantaE, buscamos acercar la innovación al bienestar ambiental y a la vida diaria de las personas, fomentando comunidades más conscientes y responsables con su entorno.

### Misión:
Digitalizar y optimizar el cuidado de cultivos urbanos mediante el uso de tecnologías IoT, ofreciendo a personas y viveros herramientas accesibles para gestionar sus plantas de forma sostenible, eficiente y consciente con el medio ambiente.

### Visión:
Ser una referencia en soluciones tecnológicas para el cuidado de plantas y áreas verdes, promoviendo un estilo de vida más sostenible y acercando la tecnología al servicio del bienestar ambiental y de las comunidades.

### 1.1.2. Perfiles de integrantes del equipo
<div align="center">

| **Integrante**            | **Apaza Bocanegra, Elizabeth Noelia**                                               |
|---------------------------|-------------------------------------------------------------------------------------|
| **Código del Estudiante** |                                                                                     |
| **Carrera**               |                                                                                     |
| **Descripción**           |                                                                                     |
| **Foto**                  |  <div align="center"> <img src="" alt="Elizabeth" width="200" height="200"> </div>  |

---

| **Integrante**            | **Contreras Leon, Flor De María**                                                   |
|---------------------------|-------------------------------------------------------------------------------------|
| **Código del Estudiante** |  u202323243                                                                         |
| **Carrera**               |  Ingenieria de Software                                                             |
| **Descripción**           |  Mi nombre es Flor de María Contreras León y actualmente estudio la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC), sede San Miguel. Tengo 20 años y me considero una persona responsable, comprometida y dedicada a mi formación profesional.Me apasiona la programación y la investigación, áreas en las que busco seguir aprendiendo y desarrollando nuevas habilidades. Aunque me considero una persona callada, siempre estoy atenta a los detalles, lo que me permite trabajar de manera cuidadosa y eficiente en mis proyectos. Asimismo, valoro el trabajo en equipo y creo que un entorno colaborativo y respetuoso es clave para alcanzar los mejores resultados. |
| **Foto**                  | <div align="center"> <img src="assets/profiles/Flor_logo.jpeg" alt="Flor" width="200" height="200"> </div> |

---

| **Integrante**            | **Guillen Galindo, Julio Adolfo**                                                   |
|---------------------------|-------------------------------------------------------------------------------------|
| **Código del Estudiante** | u20241a352                                                                          |
| **Carrera**               | Ingeniería de Software                                                              |
| **Descripción**           | Actualmente curso la carrera de Ingeniería de Software en la UPC. Me considero una persona discreta, pero responsable y enfocada en cumplir los proyectos dentro de los plazos establecidos. Poseo conocimientos en C++ y Python; disfruto trabajar en equipo cuando existe colaboración y apoyo mutuo. Además, me motiva aplicar lo aprendido para afrontar los desafíos que puedan surgir en los próximos ciclos. |
| **Foto**                  | <div align="center"> <img src="assets/profiles/julio_logo.jpg" alt="Julio" width="200" height="200"> </div> |

---

| **Integrante**            | **Miraval Pomalaya, Rodrigo Jesus**                                                 |
|---------------------------|-------------------------------------------------------------------------------------|
| **Código del Estudiante** | u202311082                                                                          |
| **Carrera**               | Ingeniería de Software                                                              |
| **Descripción**           | Mi nombre es Rodrigo Jesús Miraval Pomalaya y estudio Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas. Me considero una persona adaptable y detallista, siempre en busca de aprender y mejorar en lo que hago. Tengo conocimientos en Python, JavaScript, HTML y CSS, además de un nivel intermedio en SQL Server y MySQL. Me gusta aplicar lo aprendido en proyectos académicos y trabajar en equipo, ya que compartir ideas no solo ayuda a obtener mejores resultados, sino también a ampliar mi visión en la carrera. |
| **Foto**                  |  <div align="center"> <img src="" alt="Rodrigo" width="200" height="200"> </div>    |


---

| **Integrante**            | **Navarro Chinga, Antonio Jhair**                                                   |
|---------------------------|-------------------------------------------------------------------------------------|
| **Código del Estudiante** |                                                                                     |
| **Carrera**               |                                                                                     |
| **Descripción**           |                                                                                     |
| **Foto**                  |  <div align="center"> <img src="" alt="Antonio" width="200" height="200"> </div>    |

</div>

## 1.2. Solution Profile
### 1.2.1. Antecedentes y problemática
En el Perú, el cuidado de áreas verdes y la agricultura enfrentan serias dificultades relacionadas con el uso eficiente de recursos, especialmente del agua. Según la Autoridad Nacional del Agua (ANA, 2023), más del 70% del recurso hídrico del país es destinado a la agricultura, pero gran parte se desperdicia debido a sistemas de riego poco eficientes y falta de tecnología de monitoreo.

En las ciudades, la situación no es distinta. Informes de la Municipalidad de Lima (2022) señalan que gran parte de los parques y jardines públicos presentan un riego deficiente, lo que repercute en el deterioro de áreas verdes urbanas. A nivel de hogares, el cuidado de plantas suele hacerse de manera intuitiva, sin datos precisos sobre humedad, temperatura o condiciones ambientales, lo que incrementa el riesgo de pérdida de cultivos o desperdicio de agua.

A esto se suma que la FAO (2021) ha destacado la importancia de impulsar la agricultura urbana y periurbana en países en desarrollo, no solo como fuente de alimentos, sino también como estrategia de sostenibilidad ambiental y de bienestar social. Sin embargo, en el Perú, aún existe un vacío en el acceso a soluciones tecnológicas accesibles que faciliten la gestión eficiente de cultivos urbanos y viveros.

**Análisis 5W2H**

| **Pregunta**                                                         | **Respuesta**                                                                                                                                                                                      |
|:--------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
|**What** <br> ¿Cuál es el problema?                                   |  En el Perú, el cuidado de cultivos urbanos y áreas verdes enfrenta retos significativos por la falta de tecnologías que permitan un monitoreo preciso. Gran parte de los usuarios riegan de manera intuitiva, sin información confiable sobre humedad del suelo, temperatura, luminosidad o calidad del aire. Esto genera pérdidas de plantas, uso ineficiente del agua y deterioro de jardines urbanos y viveros.                                                             |
|**When** <br> ¿Cuándo sucede el problema?                             |  La problemática ocurre todo el año, pero se intensifica en temporadas de sequía, verano o en situaciones donde el usuario está fuera de casa por mucho tiempo. La falta de monitoreo en tiempo real y de datos confiables hace que la pérdida de cultivos o el mal uso del agua se convierta en un problema recurrente y continuo.                                                                                                                                              |
|**Where** <br> ¿Dónde se presenta el problema de negocio?             |  Este problema se presenta principalmente en ciudades con creciente interés en agricultura urbana. En las zonas costeras, la necesidad es mayor debido a la escasez de agua y a la poca adopción de tecnologías digitales en el mantenimiento de áreas verdes.                                                                                                                                                                                                                  |
|**Who** <br> ¿Quiénes están involucrados?                             |  Los principales afectados son las personas en hogares que buscan mantener sus plantas en zonas urbanas, así como viveros y negocios de jardinería que requieren eficiencia para reducir costos y mejorar la calidad de sus productos.                                                                                                                                                                                                                                        |
|**Why** <br> ¿Por qué se origina el problema?                         |  El uso eficiente del agua y la sostenibilidad ambiental son prioritarios. Según la Autoridad Nacional del Agua (ANA, 2023), más del 70% del recurso hídrico del país se destina a la agricultura, con altos niveles de desperdicio. Una solución tecnológica que permita recopilar datos en tiempo real, enviar alertas y recomendaciones personalizadas no solo optimiza el cuidado de las plantas, sino que también fomenta la conciencia ambiental y contribuye a la gestión responsable de los recursos naturales en un contexto urbano y doméstico.                                                                                                                                                                                                    |
|**How** <br> ¿Cómo afecta este problema a las personas involucradas?  |  La falta de monitoreo confiable provoca que los usuarios rieguen de manera insuficiente, lo que genera pérdida de plantas, frustración y mayores costos en el mantenimiento de áreas verdes. Y por consiguiente, repercute directamente en la calidad de los productos que ofrecen.                                                                                                                                                                                            |
|**How much** <br> ¿Cuánto impacto genera el problema en la sociedad?  |  Aunque el impacto económico es considerable, el uso ineficiente del agua contribuye al agotamiento de un recurso escaso en zonas urbanas, mientras que la pérdida de áreas verdes reduce la calidad de vida y el bienestar en las ciudades. En conjunto, esto repercute en la sostenibilidad urbana y en la gestión responsable de los recursos naturales.                                                                                                                      |

### 1.2.2. Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements
- Los usuarios de áreas urbanas y viveros no cuentan con datos precisos y en tiempo real sobre las condiciones de sus cultivos (humedad, temperatura, luminosidad, calidad del aire), lo que ocasiona un riego ineficiente y un mayor riesgo de pérdida de plantas.  
- Las personas suelen regar sus plantas de manera intuitiva, sin información confiable, lo que genera desperdicio de agua y afecta la sostenibilidad del cuidado de áreas verdes.  
- Viveros y responsables de áreas verdes carecen de soluciones tecnológicas accesibles y fáciles de usar que permitan optimizar el manejo de cultivos urbanos.  

#### 1.2.2.2. Lean UX Assumptions
- Los usuarios están dispuestos a utilizar herramientas digitales siempre que estas sean fáciles de usar y les brinden información clara para mejorar el cuidado de sus cultivos.  
- La incorporación de sensores IoT permitirá obtener datos relevantes que ayudarán a optimizar el riego y mejorar la salud de las plantas.  
- Al recibir notificaciones y recomendaciones personalizadas, los usuarios podrán tomar mejores decisiones que contribuirán a la reducción del consumo de agua y al cuidado responsable de áreas verdes.  
- Existe un segmento de mercado (hogares y viveros urbanos) que busca soluciones sostenibles e innovadoras para optimizar sus recursos y mejorar sus resultados.  

#### 1.2.2.3. Lean UX Hypothesis Statements
- Creemos que al ofrecer una plataforma de monitoreo en tiempo real con sensores IoT, los usuarios urbanos y viveros podrán gestionar sus plantas de manera más eficiente.  
- Creemos que al proporcionar recomendaciones personalizadas y notificaciones oportunas, los usuarios reducirán el desperdicio de agua y mejorarán la salud de sus cultivos.  
- Creemos que al diseñar una interfaz sencilla y accesible, lograremos que tanto usuarios individuales como viveros adopten la aplicación sin necesidad de conocimientos técnicos avanzados.  
- Creemos que si demostramos beneficios tangibles (ahorro de agua, reducción de pérdidas de plantas), los usuarios estarán dispuestos a pagar por la solución.  

#### 1.2.2.4. Lean UX Canvas
<div align="center"> 
  <img src="assets/resources/lean-ux-canvas.png" alt="Canvas" width="200" height="200"> 
</div>

## 1.3. Segmentos objetivo
---
| Segmento Objetivo | Aspectos demográficos | Aspectos geográficos | Aspectos psicográficos |
|-------------------|------------------------|-----------------------|-------------------------|
| **Personas (hogares urbanos que cuidan plantas)** | - Sexo: Masculino y femenino.<br>- Edades: 25 – 55 años (adultos jóvenes y adultos interesados en la sostenibilidad y el cuidado del hogar). | - Nacionalidad: Peruana.<br>- Zona geográfica: Principalmente zonas urbanas y periurbanas con acceso a áreas verdes o pequeños jardines (ej. Lima Metropolitana y principales ciudades del Perú). | - Valoran la sostenibilidad y el cuidado responsable del medio ambiente.<br>- Interesados en tecnología accesible que facilite la vida cotidiana.<br>- Buscan practicidad y resultados visibles en el cuidado de sus plantas.<br>- Dispuestos a probar soluciones innovadoras si estas son fáciles de usar. |
| **Viveros comerciales** | - Sexo: Masculino y femenino (administradores, encargados y trabajadores de viveros).<br>- Edades: 20 – 60 años (jóvenes adultos y adultos con experiencia en manejo de cultivos o gestión de negocios de plantas). | - Nacionalidad: Peruana.<br>- Zona geográfica: Áreas urbanas, periurbanas y rurales donde se concentran viveros, centros de producción y espacios agrícolas. | - Buscan optimizar recursos (agua, energía, tiempo) para aumentar la rentabilidad.<br>- Interesados en soluciones tecnológicas que mejoren la eficiencia operativa.<br>- Valoran herramientas que brinden datos confiables y prácticos para la toma de decisiones.<br>- Dispuestos a pagar por soluciones que generen beneficios tangibles en productividad y sostenibilidad. |



# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores

En esta sección, se presenta un análisis de los principales competidores de PlantaE, centrado en aquellos que operan con modelos de negocio digitales similares o que, aunque no sean idénticos, ofrecen productos o servicios que se superponen parcialmente con nuestra propuesta.Evaluamos tanto competidores directos, que ofrecen plataformas basadas en IoT para monitoreo de cultivos y áreas verdes, como competidores indirectos, que brindan soluciones de riego automatizado o aplicaciones de agricultura urbana más generales.

Este análisis nos permitirá comprender mejor el entorno competitivo y cómo podemos diferenciarnos en el ecosistema de soluciones de agricultura urbana sostenible.

1. ### AgroSmart : 
Es una de las startups líderes en soluciones de agricultura digital. Su plataforma combina sensores IoT, imágenes satelitales e inteligencia artificial para optimizar el manejo de grandes cultivos.

- **Fortalezas:** monitoreo IoT en tiempo real, predicciones climáticas y optimización avanzada del riego.

- **Debilidades:** está orientada a la agricultura a gran escala y requiere alta inversión, lo que limita su accesibilidad para viveros urbanos y hogares.

2. ### Netafim:
Es una empresa pionera en riego por goteo inteligente, con sistemas que reducen significativamente el consumo de agua en cultivos.

- **Fortalezas:** experiencia consolidada, sistemas de riego automatizado de alta eficiencia y sostenibilidad hídrica comprobada.

- **Debilidades:** alto costo de implementación y foco en agricultores medianos y grandes, con baja personalización para usuarios urbanos.


3. ### Plantix

Es una aplicación móvil que utiliza inteligencia artificial para diagnosticar plagas y enfermedades en cultivos mediante fotos.

- **Fortalezas:** accesibilidad desde dispositivos móviles, comunidad activa de usuarios y recomendaciones prácticas para el cuidado de plantas.

- **Debilidades:** su alcance está limitado al diagnóstico de problemas y no ofrece un sistema de monitoreo IoT ni gestión hídrica.


### 2.1.1. Análisis competitivo

**Pregunta de análisis:**  
¿Que busca comprender el analisis de PlantaE frente a competidores que ofrecen soluciones de agricultura digital e IoT, considerando factores de accesibilidad, mercado objetivo y sostenibilidad?

Este análisis busca comprender el posicionamiento de PlantaE en comparación con otras soluciones digitales e IoT para la gestión de cultivos y áreas verdes, identificando oportunidades de mejora y diferenciación frente a las necesidades de nuestros segmentos objetivos: hogares urbanos interesados en el cuidado sostenible de plantas y viveros comerciales que buscan optimizar el uso de recursos y mejorar la salud de sus cultivos.

| Aspecto / Startup     |  PlantaE | AgroSmart | Netafim | Plantix |
|------------------------|------------|-----------|---------|---------|
| **Perfil / Overview** | Plataforma accesible de monitoreo IoT en tiempo real para hogares y viveros comerciales. | Startup de agricultura digital con sensores IoT, IA y datos satelitales. | Empresa líder en riego inteligente a nivel global. | App móvil que diagnostica plagas y enfermedades con IA. |
| **Ventaja competitiva** | Accesible, simple y adaptable a hogares y viveros comerciales. | Alta tecnología para agricultura a gran escala. | Experiencia consolidada y eficiencia hídrica. | Uso de IA accesible desde móvil y comunidad activa. |
| **Mercado objetivo** | Hogares urbanos y viveros comerciales pequeños/medianos. | Agricultores industriales y medianos. | Agricultores medianos y grandes. | Agricultores y aficionados urbanos. |
| **Estrategias de marketing** | Educación digital sobre sostenibilidad, alianzas con viveros locales. | Marketing B2B, posicionamiento tecnológico. | Branding global, casos de éxito y sostenibilidad hídrica. | Estrategia digital masiva vía Google Play/App Store. |
| **Productos & Servicios** | Sensores IoT, web, recomendaciones personalizadas. | Sensores IoT, pronósticos climáticos, gestión avanzada. | Sistemas de riego por goteo inteligentes, software de gestión. | Diagnóstico de plagas y comunidad de soporte. |
| **Precios & Costos** | Accesible, modelo freemium o suscripción baja. | Alto costo, licencias SaaS premium. | Alta inversión inicial y mantenimiento. | Gratis con servicios premium. |
| **Canales de distribución** | Web (Probable distribucion con equipos adquiridos)| Web y App. | Equipos físicos + plataforma digital. | App móvil. 


### SWOT Analysis

| Startup     | Fortalezas                                                                 | Debilidades                                                                | Oportunidades                                                      | Amenazas                                                                 |
|-------------|----------------------------------------------------------------------------|----------------------------------------------------------------------------|-------------------------------------------------------------------|---------------------------------------------------------------------------|
|  **PlantaE**   | Accesibilidad, simplicidad de uso, enfoque en sostenibilidad urbana.      | Escala inicial limitada, baja madurez tecnológica frente a competidores.    | Creciente demanda de soluciones sostenibles, apoyo a viveros urbanos. | Entrada de grandes competidores al segmento urbano, barreras de adopción tecnológica. |
| **AgroSmart** | Tecnología avanzada, IA y datos satelitales.                              | Costos elevados, poco enfoque en usuarios pequeños.                         | Expansión en mercados emergentes.                                   | Saturación de mercado y alta inversión necesaria para usuarios pequeños. |
| **Netafim**   | Experiencia consolidada, reducción comprobada de consumo de agua.         | Alto costo, poca personalización para usuarios urbanos.                     | Creciente necesidad de eficiencia hídrica.                         | Nuevas startups más ágiles y accesibles.                                 |
| **Plantix**   | Uso de IA en diagnóstico, comunidad digital activa.                       | No ofrece gestión hídrica ni monitoreo IoT.                                | Integración con soluciones de riego y monitoreo urbano.            | Dependencia de la precisión de IA y limitación del modelo freemium.      |


### 2.1.2. Estrategias y tácticas frente a competidores

Para enfrentar a la competencia y posicionarse de manera sólida en el ecosistema de soluciones sostenibles, **PlantaE implementará estrategias enfocadas en sus principales ventajas competitivas** y en la explotación de oportunidades poco atendidas por otras iniciativas. Entre las principales tácticas preliminares destacan:

**Estrategia de diferenciación sostenible :**

- La plataforma digital de PlantaE facilitará la conexión entre ciudadanos, municipalidades, ONGs y empresas, mediante herramientas enfocadas en la regeneración de áreas verdes y el monitoreo comunitario. Se contempla, por ejemplo, el desarrollo progresivo de funcionalidades como reportes de impacto ambiental en tiempo real y mapas interactivos de proyectos verdes, diferenciándonos de competidores que se centran únicamente en el sector agrícola o de riego.

**Alianzas estratégicas multiactor:**

- PlantaE priorizará la construcción de convenios con municipalidades, viveros urbanos y organizaciones comunitarias. Estas alianzas permitirán fortalecer la confianza en la plataforma, garantizar acceso a insumos sostenibles y generar proyectos colaborativos que refuercen el sentido de pertenencia ciudadana.

**Campañas digitales con enfoque social y ambiental:**

- Las campañas en redes sociales serán clave para sensibilizar sobre la importancia del cuidado de áreas verdes urbanas. Se priorizarán contenidos educativos, testimonios de voluntarios y casos de éxito en la transformación de espacios públicos, reforzando así la conexión emocional entre los usuarios y su entorno.

**Captación y fidelización de comunidades:**

- La plataforma incluirá herramientas que permitan a los ciudadanos participar en proyectos de reforestación, limpieza y mantenimiento, mientras que ONGs y empresas podrán gestionar sus iniciativas desde un panel especializado. Se prevé también la implementación de incentivos no monetarios, como reconocimientos digitales o certificaciones de impacto ambiental.

**Gestión de riesgos y validación de proyectos:**

- Frente a la posible desconfianza en nuevas plataformas digitales o la falta de continuidad en proyectos comunitarios, PlantaE aplicará un modelo de validación y seguimiento transparente. Cada proyecto contará con métricas claras de impacto y espacios de retroalimentación, lo que fortalecerá la confianza y garantizará la sostenibilidad a largo plazo.


## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas
Hola, mi nombre es [Nombre del entrevistador] y formo parte del equipo que está desarrollando PlantaE, una iniciativa que busca mejorar el cuidado de plantas y áreas verdes con ayuda de la tecnología. Nuestra idea es apoyarnos en el Internet de las Cosas (IoT), es decir, en sensores y dispositivos que recopilan datos en tiempo real sobre tus plantas —por ejemplo, la humedad del suelo o la cantidad de agua utilizada— para que el riego y el mantenimiento sean más fáciles y eficientes.

Con esto queremos crear una aplicación que te brinde alertas, consejos y herramientas prácticas para ahorrar agua, cuidar mejor de las plantas y simplificar el proceso, ya sea en casa o en un vivero.
**Diseño de entrevistas - Segmento 1 :**

**Presentacion del proyecto y inicio de la entrevista:******
1. Para empezar, ¿puedes contarnos tu nombre y qué relación tienes con el cuidado de plantas en tu hogar?

2. ¿Cómo describirías tu experiencia con las plantas: las consideras un pasatiempo, una responsabilidad o parte de tu estilo de vida?

3. ¿Qué lugar ocupan las plantas en tu día a día (ejemplo: decoración, conexión con la naturaleza, bienestar personal)?

4. ¿Desde cuándo empezaste a cuidar plantas en casa y qué te motivó a hacerlo?


------------


1. ¿Dedicas un tiempo específico en la semana para cuidar tus plantas o lo haces de manera espontánea?

2. ¿Qué dificultades enfrentas al cuidar tus plantas o áreas verdes?

3. ¿Cómo organizas el riego y mantenimiento de tus plantas?

4. ¿Has tenido problemas relacionados con el riego (por exceso, falta o uso de agua)?

5. ¿Qué tanto influye el consumo de agua en tu decisión de cuidar más o menos plantas?

6. ¿Alguna vez has perdido plantas por no darles el cuidado adecuado? ¿Cómo te sentiste?

7. ¿Ha tenido problemas relacionados con el mantenimiento general de tus plantas (plagas, falta de tiempo, espacio)?

8. ¿Usas actualmente alguna aplicación, sistema o herramienta para ayudarte en el cuidado de tus plantas?

9. ¿Qué tan cómodo te sentirías usando sensores o aplicaciones para recibir alertas y recomendaciones sobre tus plantas?

10. ¿Qué tan útil te resultaría una aplicación que te ayude a optimizar el riego y cuidado de tus plantas?

11. ¿Qué funcionalidades te motivarían más a usar una aplicación como esta? (ejemplo: alertas de riego, consejos personalizados, ahorro de agua).

12. Si tuvieras esta aplicación, ¿cómo crees que cambiaría tu experiencia actual con el cuidado de plantas en casa?

13. ¿Hay algo más que te gustaría agregar sobre tu experiencia con las plantas y áreas verdes?


**Diseño de entrevistas - Segmento 2 :**

**Presentacion del proyecto y inicio de la entrevista:******


1. Para comenzar, ¿puedes presentarte y contarnos tu rol dentro del vivero o negocio de plantas?

3. ¿Cuál es la historia detrás del vivero? (¿Cómo empezó y qué los motivó a dedicarse a este rubro?)

5. ¿Qué tanto valoras la tecnología o la innovación en el manejo de riego y mantenimiento en tu negocio?



------------

1. ¿Qué retos enfrenta en la gestión del riego y mantenimiento a gran escala?

2. ¿Cómo manejan actualmente el control del consumo de agua?

3. ¿Qué estrategias utilizan para garantizar que las plantas se mantengan en buen estado?

4. ¿Han tenido pérdidas significativas de plantas por problemas de riego o mantenimiento?

5. ¿Qué métodos utilizan para planificar y organizar las tareas de su equipo en el vivero?

6. ¿Cómo gestionan el almacenamiento y uso de insumos (fertilizantes, sustratos, pesticidas)?

7. ¿Qué tan importante es para su negocio poder reducir costos relacionados al consumo de agua y mantenimiento?

8. ¿Utilizan actualmente algún software o sistema digital para gestionar el vivero? ¿Cuál?

10. ¿Qué tipo de información o métricas consideran más útiles para tomar decisiones sobre la producción y venta?

11. ¿De qué forma creen que una aplicación como PlantaE podría apoyar la eficiencia y sostenibilidad en su vivero?

12. ¿Qué funcionalidades valoraría más en una herramienta digital pensada para viveros (ejemplo: gestión de riego por sectores, alertas de plagas, informes de consumo)?


### 2.2.2. Registro de entrevistas
### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding
### 2.3.1. User Personas

- User Persona – Usuario Doméstico

| **Attributes**   | **Values** |
|------------------|------------|
| **Name**         | Ana Torres |
| **Age**          | 29 años |
| **Occupation**   | Diseñadora gráfica (trabajo remoto) |
| **Status**       | Soltera |
| **Location**     | Lima, Perú (San Borja) |
| **Tier**         | Cuidadora de plantas domésticas |
| **Archetype**    | Amante de las plantas |
| **Image**        | <img src="assets/resources/user-image-user1.png" alt="Ana" width="200" height="200"> |
| **Quote**        | "Quiero una solución simple y confiable para que mis plantas estén siempre bien." |
| **Motivations**  | Incentive: 80/100 · Fear: 60/100 · Achievement: 70/100 · Growth: 65/100 · Power: 30/100 · Social: 85/100 |
| **Goals**        | Mantener sanas sus plantas de interior y jardín · Recibir alertas simples y claras sobre riego, luz y humedad · Compartir logros en redes sociales |
| **Frustrations** | Falta de tiempo para investigar cuidados · No identificar enfermedades a tiempo · Información técnica confusa en otras apps |
| **Biography**    | Ana vive sola en un departamento y disfruta decorarlo con plantas. Ha perdido varias porque no sabía cómo cuidarlas correctamente. Quiere recordatorios sencillos que eviten descuidos. Comparte sus hobbies en redes sociales y valora soluciones visuales y fáciles de usar. |
| **Personality**  | Extrovert: 65/100 · Thinking: 70/100 · Judging: 60/100 |
| **Technology**   | IT & Internet: 80/100 · Software: 65/100 · Mobile Apps: 90/100 · Social Networks: 95/100 |
| **Brands**       | Instagram · TikTok · Pinterest |

- User Persona – Usuario Institucional

| **Attributes**   | **Values** |
|------------------|------------|
| **Name**         | Carlos Ramírez |
| **Age**          | 45 años |
| **Occupation**   | Administrador de vivero |
| **Status**       | Casado |
| **Location**     | Lima, Perú (Ate) |
| **Tier**         | Gestor de vivero/invernadero |
| **Archetype**    | Administrador pragmático |
| **Image**        | <img src="assets/resources/user-image-user2.png" alt="Carlos" width="200" height="200"> |
| **Quote**        | "Necesito datos claros para tomar decisiones rápidas y efectivas." |
| **Motivations**  | Incentive: 85/100 · Fear: 55/100 · Achievement: 90/100 · Growth: 80/100 · Power: 70/100 · Social: 60/100 |
| **Goals**        | Optimizar consumo de agua y fertilizantes · Recibir reportes claros y priorizados para casos críticos · Tomar decisiones estratégicas con base en tendencias históricas |
| **Frustrations** | Instalación de sensores compleja · Resistencia del personal al cambio · Exceso de alertas sin priorización |
| **Biography**    | Carlos administra un vivero de tamaño medio. Usa planillas y reportes en papel, pero sabe que la digitalización es clave. Busca ahorrar costos y tiempo con herramientas que generen reportes claros, exportables y fáciles de compartir con la gerencia. |
| **Personality**  | Extrovert: 55/100 · Thinking: 85/100 · Judging: 75/100 |
| **Technology**   | IT & Internet: 70/100 · Software: 80/100 · Mobile Apps: 60/100 · Social Networks: 50/100 |
| **Brands**       | LinkedIn · Excel · Google Workspace |


### 2.3.2. User Task Matrix

| **Tareas**                           | **Ana (Frecuencia)** | **Ana (Importancia)** | **Carlos (Frecuencia)** | **Carlos (Importancia)** |
|--------------------------------------|-----------------------|------------------------|--------------------------|---------------------------|
| Buscar solución para cuidado de plantas | Alta                  | Alta                   | Media                    | Media                     |
| Instalar sensores                    | Media                 | Alta                   | Alta                     | Alta                      |
| Configurar la app/dashboard          | Alta                  | Alta                   | Alta                     | Alta                      |
| Monitorear condiciones de las plantas| Alta                  | Alta                   | Alta                     | Alta                      |
| Recibir alertas de cuidado           | Alta                  | Alta                   | Alta                     | Alta                      |
| Analizar reportes históricos         | Baja                  | Media                  | Alta                     | Alta                      |
| Compartir logros o resultados        | Alta                  | Media                  | Media                    | Media                     |
| Exportar reportes                    | Baja                  | Baja                   | Alta                     | Alta                      |

---

### Conclusiones
- **Ana** (usuaria doméstica) se enfoca en tareas simples y motivacionales como recibir recordatorios, cuidar sus plantas y compartir avances en redes sociales.  
- **Carlos** (usuario institucional) prioriza el análisis de datos, la exportación de reportes y la optimización de recursos en su vivero.  
- Ambos coinciden en la **alta importancia de un dashboard confiable y alertas claras**, lo que convierte estas funciones en elementos centrales del diseño de **PlantaE**.


### 2.3.3. User Journey Mapping
- Segmento objetivo 1:
<div align="center">
  <img src="assets/resources/user-journey-mapping-user1.png">
</div>

- Segmento objetivo 2:
<div align="center">
 <img src="assets/resources/user-journey-mapping-user2.png">
</div>

### 2.3.4. Empathy Mapping
- Segmento objetivo 1:
<div align="center">
 <img src="assets/resources/empathy-mapping-user1.png">
</div>

- Segmento objetivo 2:
<div align="center">
 <img src="assets/resources/empathy-mapping-user2.png">
</div>

## 2.4. Big Picture Event Storming

## 2.5. Ubiquitous Language
| **Término (Inglés)**         | **Término (Español)**       | **Descripción**                                                                                              |
|------------------------------|-----------------------------|--------------------------------------------------------------------------------------------------------------|
| **Soil Moisture**            | Humedad del suelo           | Cantidad de agua presente en la tierra donde crece la planta; determina la necesidad de riego.               |
| **Air Quality**              | Calidad del aire            | Condiciones del aire que rodea al cultivo, considerando pureza y presencia de contaminantes.                 |
| **Sunlight Exposure**        | Exposición a la luz solar   | Cantidad de luz solar o artificial que recibe la planta, fundamental para la fotosíntesis y el crecimiento.  |
| **Plant Health**             | Salud de la planta          | Estado general de una planta basado en sus condiciones ambientales y cuidados recibidos.                     |
| **Watering Recommendation**  | Recomendación de riego      | Sugerencia personalizada generada para optimizar el uso del agua y mantener el buen estado del cultivo.      |
| **Alert Notification**       | Notificación de alerta      | Mensaje que informa al usuario sobre condiciones críticas que requieren acción inmediata.                    |
| **Dashboard**                | Panel de control            | Interfaz donde el usuario visualiza en tiempo real el estado de sus cultivos y recibe notificaciones.        |
| **Growth Stage**             | Etapa de crecimiento        | Fase de desarrollo en la que se encuentra la planta (germinación, crecimiento, floración, madurez).          |
| **Overwatering**             | Exceso de riego             | Situación en la que la planta recibe más agua de la necesaria, lo que puede causar pudrición de raíces.      |
| **Underwatering**            | Falta de riego              | Situación en la que la planta recibe menos agua de la necesaria, afectando su salud y crecimiento.           |
| **Indoor Plant**             | Planta de interior          | Planta cultivada dentro de un espacio cerrado, adaptada a condiciones de luz artificial o indirecta.         |
| **Outdoor Plant**            | Planta de exterior          | Planta cultivada en terrazas, balcones o jardines, expuesta a condiciones ambientales naturales.             |
| **Fertilizer Use**           | Uso de fertilizantes        | Práctica de añadir nutrientes a la maceta para mejorar el crecimiento y salud de la planta.                  |

# Capítulo III: Requirements Specification
## 3.1. User Stories
## 3.2. Impact Mapping
## 3.3. Product Backlog

# Capítulo IV: Product Design
## 4.1. Style Guidelines
### 4.1.1. General Style Guidelines
### 4.1.2. Web Style Guidelines

## 4.2. Information Architecture
### 4.2.1. Organization Systems
La landing page de PlantaE se organiza bajo un sistema jerárquico y progresivo que busca guiar al usuario desde la propuesta de valor hasta la acción final. Las secciones se estructuran en bloques diferenciados y ordenados para asegurar claridad y fluidez en la navegación:

- Header: incluye el logotipo de PlantaE y la barra de navegación principal.

- Hero Section: propuesta de valor clara con un eslogan, llamada a la acción y una imagen representativa de la app.

- Beneficios principales: explica ventajas de usar PlantaE (ahorro de agua, cuidado fácil, alertas personalizadas).

- Cómo funciona: breve descripción en pasos con íconos para mostrar la instalación de sensores, el monitoreo y las recomendaciones.

- Planes o Público objetivo: bloques diferenciados para usuarios domésticos y viveros.

- Testimonios o casos de uso: muestra evidencia social con experiencias de usuarios.

- Contacto y registro: formulario de contacto, enlaces a redes sociales y botón de registro destacado.

Este orden responde a un patrón de lectura en “Z”, guiando la atención desde el encabezado hasta los botones de acción, asegurando que el usuario encuentre rápidamente información clave antes de decidir registrarse.

### 4.2.2. Labeling Systems
El sistema de etiquetado de PlantaE emplea nombres claros, consistentes y orientados a la acción, con el objetivo de transmitir confianza y accesibilidad:

- Menú principal: “Inicio”, “Beneficios”, “Cómo funciona”, “Planes”, “Contacto”.

- Botones de acción: textos directos como “Regístrate gratis”, “Descubre PlantaE” o “Solicitar demo”.

- Encabezados y subtítulos: utilizan un lenguaje cercano y orientado al usuario, por ejemplo: “Cuida tus plantas de manera inteligente” o “Control total de tus cultivos en un solo lugar”.

- Íconos e imágenes: llevan etiquetas alt descriptivas para garantizar accesibilidad a usuarios con lectores de pantalla.

- Secciones técnicas (dashboard, alertas, reportes): etiquetadas con nombres comprensibles como “Panel de control” o “Alertas críticas”.

Con esto se busca que tanto un usuario casual como uno con perfil técnico puedan comprender sin dificultad el contenido.

### 4.2.3. SEO Tags and Meta Tags
- Landing Page:
    - Title: PlantaE, monitoreo inteligente de cultivos urbanos con IoT.
    - Meta Description: Supervisa tus plantas en tiempo real con sensores IoT, brindando recomendaciones de riego y cuidado personalizado para que tus cultivos urbanos crezcan saludables y sostenibles.
    - Meta Keywords: Plantas inteligentes, cultivos urbanos, IoT, agricultura sostenible, cuidado de plantas, huertos urbanos, monitoreo ambiental.
    - Meta Author: PlantaE Team.

- Web Application:
    - Title: PlantaE, estado de tus plantas en tiempo real.
    - Meta Description: Gestiona tus cultivos urbanos desde un solo lugar. Visualiza humedad, temperatura, luz y calidad del aire con gráficos claros y recibe alertas personalizadas.
    - Meta Keywords: dashboard plantas, monitoreo IoT, gestión de cultivos, agricultura urbana, cuidado de plantas en casa, viveros sostenibles.
    - Meta Author: PlantaE Team.

### 4.2.4. Searching Systems
El sistema de búsqueda de PlantaE está diseñado para facilitar a los usuarios la localización rápida y eficiente de información sobre sus cultivos urbanos. El objetivo es evitar que el usuario se sienta perdido ante el volumen de datos provenientes de los sensores y garantizar que pueda acceder de forma intuitiva al estado de cada planta o conjunto de cultivos.

- Usuarios domésticos: 
    - Filtros dinámicos combinables:
        - Tipo de planta.
        - Estado de salud: Saludable, en riesgo, crítico.
        - Variable ambiental: Humedad, temperatura, luminosidad, calidad del aire.
        - Ubicación: Sala, balcón, terraza, huerto urbano.
        - Nivel de cuidado requerido: Bajo, medio, alto.

    - Tarjetas visuales:
        - Imagen de la planta o ícono representativo.
        - Nombre de la planta.
        - Ubicación asignada.
        - Estado actual resumido: Humedad baja, necesita riego.
        - Indicadores visuales de color:
            - Verde, planta saludable.
            - Amarillo, requiere atención.
            - Rojo, estado crítico.
        
- Viveros comerciales:
    - Filtros por estado de cultivo.
    - Filtro por variable crítica: Lotes con humedad baja, exceso de temperatura o deficiencia de luz.
    - Búsqueda en histórico:
        - Consultar registros por fecha.
        - Estado previo o acciones realizadas.
    - Iconos destacados para alertas, recomendaciones o novedades.
  
### 4.2.5. Navigation Systems
La navegación en PlantaE sigue un enfoque simple, intuitivo y responsivo:

- Menú superior fijo: accesible en todo momento, con enlaces internos a cada sección de la landing page (#benefits, #how-it-works, #plans, #contact).

- Smooth scrolling: desplazamiento fluido entre secciones para mejorar la experiencia del usuario.

- Versión móvil: menú hamburguesa desplegable que mantiene los mismos enlaces clave.

- Navegación secundaria (en la web app): incluye pestañas internas para “Mis Plantas”, “Alertas”, “Reportes” y “Configuración”.

- Breadcrumbs (para viveros con múltiples lotes): facilitan ubicar la posición del usuario dentro del sistema.

- Call To Action destacados: botones visibles en secciones clave que redirigen a registro o demo.

Este sistema permite un recorrido ágil y consistente, evitando que el usuario se pierda entre la información y favoreciendo la interacción rápida con las funciones principales.

## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe
### 4.3.2. Landing Page Mock-up

## 4.4. Web Applications UX/UI Design
### 4.4.1. Web Applications Wireframes
### 4.4.2. Web Applications Wireflow Diagrams
### 4.4.2. Web Applications Mock-ups
### 4.4.3. Web Applications User Flow Diagrams

## 4.5. Web Applications Prototyping

## 4.6. Domain-Driven Software Architecture
### 4.6.1. Design-Level Event Storming
### 4.6.2. Software Architecture Context Diagram
### 4.6.3. Software Architecture Container Diagrams
### 4.6.4. Software Architecture Components Diagrams

## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams

<img src="assets/resources/class_diagrams.png" alt="Diagrama Clases" width="1000" height="">   

## 4.8. Database Design
### 4.8.1. Database Diagrams

<img src="assets/resources/database_diagrams.png" alt="Diagrama Base de Datos" width="1000" height="">    

---

# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management
### 5.1.1. Software Development Environment Configuration
### 5.1.2. Source Code Management
### 5.1.3. Source Code Style Guide & Conventions
### 5.1.4. Software Deployment Configuration

## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1
#### 5.2.1.2. Aspect Leaders and Collaborators
#### 5.2.1.3. Sprint Backlog 1
#### 5.2.1.4. Development Evidence for Sprint Review
#### 5.2.1.5. Execution Evidence for Sprint Review
#### 5.2.1.6. Services Documentation Evidence for Sprint Review
#### 5.2.1.7. Software Deployment Evidence for Sprint Review
#### 5.2.1.8. Team Collaboration Insights during Sprint

## 5.3. Validation Interviews
### 5.3.1. Diseño de Entrevistas
### 5.3.2. Registro de Entrevistas
### 5.3.3. Evaluaciones según heurísticas

## 5.4. Video About-the-Product

---

# Conclusiones
# Conclusiones y recomendaciones
# Video About-the-Team
# Bibliografía
# Anexos



