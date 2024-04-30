# Los Luminoso - Report

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" alt="LogoUPC">
</p>

# Universdiad Peruana de Ciencias Aplicadas

# INGENIERÍA DE SISTEMAS DE SOFTWARE
### Ciclo: 5
## CURSO: SI729 Desarrollo de Aplicaciones Open Source | SECCIÓN SW57
 Profesor: Velazquez Nuñez, Angel Augusto
 
# Proyecto de curso
## Informe del TF
#### StartUp: Los Luminosos
#### Producto: MedSystem

### Integrantes:
| Integrantes | Codigo |
|-------------|--------|
| Altamirano Saenz, Jorge Armando  | U202215888 |
| Flores Manrique, Sebastian Enrique | U201611430 |
| Guimaraes Escalante, Carlos Eduardo | U202210364 |
| Gutierrez Zumaeta, Manuel Alonso | U201611430 |
| Montes Figueroa, Juan Eduardo | U202210775 |

#### Ciclo 2024-01
##### Abril, 2024
- - -
# Registro de Versiones del informe
| Version | Fecha | Autor | Descripcion de Modificacion |
| ----------- | ----------- | ----------- | ----------- |
| 0.0 | 28/03/2024 |Grupo 1 |Se crea el documento |
- - -
# Project Report Collaboration Insights
[URL del repositorio](https://github.com/LosLuminosos-SW57/FinalProject.git)

(Imagenes de los commits cada entrega)
- - -
# Contenido

[Student Outcome](#student-outcome)

[Capítulo I: Introducción](#capítulo-i-introducción)

[1.1 Startup Profile](#11-startup-profile)  
[1.1.1. Descripción de la Startup](#111-descripción-de-la-startup) 

[1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)  

[1.2. Solution Profile](#12-solution-profile)  
[1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)  
[1.2.2 Lean UX Process.](#122-lean-ux-process)  
[1.2.2.1. Lean UX Problem Statements.](#1221-lean-ux-problem-statements)  
[1.2.2.2. Lean UX Assumptions.](#1222-lean-ux-assumptions)  
[1.2.2.3. Lean UX Hypothesis Statements.](#1223-lean-ux-hypothesis-statements)  
[1.2.2.4. Lean UX Canvas.](#1224-lean-ux-canvas)  

[1.3. Segmentos objetivo.](#13-segmentos-objetivo)  

[Capítulo II: Requirements Elicitation & Analysi](#capítulo-ii-requirements-elicitation--analysis)  

[2.1. Competidores](#21-competidores)  
[2.1.1. Análisis competitivo]()  
[2.1.2. Estrategias y tácticas frente a competidores](#211-análisis-competitivo)  

[2.2. Entrevistas](#22-entrevistas)  
[2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)    
[2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)  

[2.3. Needfinding](#23-needfinding)  
[2.3.1. User Personas](#231-user-personas)  
[2.3.2. User Task Matrix](#232-user-task-matrix)  
[2.3.3. User Journey Mapping](#233-user-journey-mapping)  
[2.3.4. Empathy Mapping](#234-empathy-mapping)  
[2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping) 

[2.4. Ubiquitous Language](#24-ubiquitous-language)  

[Capítulo III: Requirements Specificatio](#capítulo-iii-requirements-specification)  

[3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)  

[3.2. User Stories](#32-user-stories)  

[3.3. Impact Mapping](#33-impact-mapping)  

[3.4. Product Backlog](#34-product-backlog)  

[Capítulo IV: Product Design](#capítulo-iv-product-design)  

[4.1. Style Guidelines](#41-style-guidelines)  
[4.1.1. General Style Guidelines](#411-general-style-guidelines)  
[4.1.2. Web Style Guidelines](#412-web-style-guidelines)  

[4.2. Information Architecture](#42-information-architecture)  
[4.2.1. Organization Systems](#421-organization-systems)  
[4.2.2. Labeling Systems](#422-labeling-systems)  
[4.2.3. SEO Tags and Meta Tag](#423-seo-tags-and-meta-tags)  
[4.2.4. Searching Systems](#424-searching-systems)   
[4.2.5. Navigation Systems](#425-navigation-systems)  

[4.3. Landing Page UI Design](#43-landing-page-ui-design)   
[4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)  
[4.3.2. Landing Page Mock-up](#432-landing-page-mock-up) 

[4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)  
[4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)  
[4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)  
[4.4.2. Web Applications Mock-ups](#442-web-applications-mock-ups)   
[4.4.3. Web Applications User Flow Diagrams](#443-web-applications-user-flow-diagrams)  

[4.5. Web Applications Prototyping](#45-web-applications-prototyping)  

[4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)  
[4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)  
[4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)  
[4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)  

[4.7. Software Object-Oriented Design](#47-software-object-oriented-design)  
[4.7.1. Class Diagrams](#471-class-diagrams)  
[4.7.2. Class Dictionary](#472-class-dictionary)  

[4.8. Database Design](#48-database-design)  
[4.8.1. Database Diagram](#481-database-diagram)  

[Capítulo V: Product Implementation, Validation & Deploymen](#capítulo-v-product-implementation-validation--deployment)  

[5.1. Software Configuration Management](#51-software-configuration-management)  
[5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)  
[5.1.2. Source Code Management](#512-source-code-management)  
[5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)  
[5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)  

[5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)  
[5.2.X. Sprint ](#52x-sprint-n)  
[5.2.X.1. Sprint Planning n](#52x1-sprint-planning-n)  
[5.2.X.2. Sprint Backlog n](#52x2-sprint-backlog-n)  
[5.2.X.3. Development Evidence for Sprint Review](#52x3-development-evidence-for-sprint-review)  
[5.2.X.4. Testing Suite Evidence for Sprint Review](#52x4-testing-suite-evidence-for-sprint-review)  
[5.2.X.5. Execution Evidence for Sprint Review](#52x5-execution-evidence-for-sprint-review)  
[5.2.X.6. Services Documentation Evidence for Sprint Review](#52x6-services-documentation-evidence-for-sprint-review)  
[5.2.X.7. Software Deployment Evidence for Sprint Review](#52x7-software-deployment-evidence-for-sprint-review)  
[5.2.X.8. Team Collaboration Insights during Sprint](#52x8-team-collaboration-insights-during-sprint)  

[5.3. Validation Interviews](#53-validation-interviews)  
[5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)  
[5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)  
[5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)  

[5.4. Video About-the-Product](#54-video-about-the-product)  

[Conclusiones](#conclusiones)  

[Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)  

[Video About-the-Team](#video-about-the-team)  

[Bibliografía](#bibliografía)  

[Anexos](#anexos)  

- - -
# Student Outcome

Criterio: Capacidad de comunicarse efectivamente con un rango de audiencias.
En el siguiente cuadro se describe las acciones realizadas y enunciados de
conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro
del ABET – EAC - Student Outcome 3

| Criterio específico                                                                                                                                                                    	| Acciones realizadas 	| Conclusiones 	|
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|---------------------	|--------------	|
| Comunica oralmente sus ideas y/o resultados con objetividad a públicos de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto de ingeniería.    	|                     	|              	|
| Comunica en forma escrita ideas y/o resultados con objetividad a públicos de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto de ingeniería. 	|                     	|              	|



- - -
# Capitulo 1
## 1.1 StartUp Profile
### 1.1.1 Descripcion de la startup
(Nombre de la startup) es una startup creada por estudiantes de la Facultad de Ingeniería de la carrera de Ingeniería de Software. Esta empresa tiene el propósito de desarrollar una solución web con el uso de tecnologías modernas para la ayuda de los procesos que se tienen presente en una consultoría de traumatología. Con la página (nombre de la página) se logrará satisfacer estas necesidad por parte de los especialistas de traumatología y los clientes.

| **Misión**                                                                                                                                                                                                                                    | **Visión**                                                                                                                                                                                                                                                                  |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| La misión de Los Luminosos es facilitar la atención médica en la especialización de traumatología a través de MedSystem para mejorar los procesos de una consultoría y la experiencia de los especialistas o doctores y de los pacientes. | Nuestra visión es ser reconocidos por nuestra capacidad de mejorar la atención médica por medio de soluciones tecnológicas que mejoren la eficiencia de los distintos servicios que ofrece el área de traumatología, además de mejorar el servicio hacia los pacientes. |

---
### 1.1.1 Perfiles de integrantes del equipo
|   | Miembros del equipo                 | Código de estudiante | Carrera                | Conocimientos/Habilidades                                                                                                                                                                                                                                                                               |
|---|-------------------------------------|----------------------|------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <img src="../members-profile/manuel.jpg" width="50%" alt="Imagen del compañero">  | Gutierrez Zumaeta Manuel Alonso     | u202112353           | Ingeniería de Software | Soy un estudiante de la carrera de ingeniería de software de la UPC, tengo 20 años. Tengo experiencia usando lenguajes de programación como C++, Python y JS. Además puedo ayudar al equipo en todas las tareas que se realicen para lograr un resultado óptimo.                                        |
|  <img src="../members-profile/Carlos.png" width="50%" alt="Imagen del compañero"> | Guimaraes Escalante, Carlos Eduardo | u202210364           | Ingeniería de Software |   Soy estudiante de la carrera de Ingeniería de Software, estoy cursando el tercer ciclo de mi carrera y tengo 17 años. Soy una persona responsable y puntual, por lo que me gusta terminar y presentar los trabajos en los tiempos establecidos. Siempre me ha gustado la innovación y la creación de nuevas ideas. Estoy capacitado en algunos temas de edición de videos, y me considero bueno en programación. Voy a aportar al grupo de manera proactiva e intentaré aportar ideas que ayuden a mejorar el trabajo, siempre intentando mantener un ambiente positivo dentro del área de trabajo. |
| <img src="../members-profile/altamirano.jpg" width="50%" alt="Imagen del compañero">  | Altamirano Saenz, Jorge Armando     | u202215888           | Ingeniería de Software |  Me llamo Jorge Altamirano, tengo 19 años. Tengo conocimientos en programación en los lenguajes de C++, Python, Java y C# básico. Me considero una persona responsable e investigadora y creo que puedo aportar con ideas propias al equipo. |                                                                                                                                                                                                                                                                                                       |
|  <img src="../members-profile/Juan.JPG" width="50%" alt="Imagen del compañero"> | Montes Figueroa, Juan Eduardo       | u202210775           | Ingeniería de Software | Mi nombre es Juan Montes, tengo 19 años, tengo conocimientos en C++, asimismo poseo conocimientos básicos en Java y también en diseño de imágenes tanto en aplicaciones complicadas como Photoshop hasta páginas webs que te dan funciones similares. Puedo aportar en el equipo con ideas, confianza y atención a los detalles. |                                                                                                                                                                                                                                                                                                        |
|  <img src="../members-profile/sebastian.jpeg" width="50%" alt="Imagen del compañero">  | Flores Manrique, Sebastian Enrique  | u201611430           | Ingeniería de Software | Soy estudiante de la carrera de Ingeniería de software. Actualmente cursando el quinto ciclo de la carrera. Me considero una persona responsable y dispuesto a ayudar en lo que haga falta. Tengo conocimientos en lenguaje de programación de C++, Python y un poco de conocimiento en desarrollo web. |

## 1.2 Solution Profile
### 1.2.1. Antecedentes y problemática
Muchos pacientes necesitan atención que requiere una toma de decisiones conjunta entre múltiples actores y/o servicios. La evaluación de interconsultas es tediosa e ineficaz debido a la estructura actual de atención en la mayoría de los consultorios y clínicas. Los pacientes con diabetes de pie que están hospitalizados en los pabellones de medicina son un ejemplo típico en el que la demora en los procedimientos o intervenciones quirúrgicas realizadas por los servicios de traumatología puede resultar en complicaciones graves e incluso en la muerte del paciente.

La Encuesta Nacional de Hogares (ENAHO) de 2022 revela que 7 de cada 10 personas que necesitaron atención médica no la obtuvieron . El 35 % de ellos mencionó demoras como la razón principal, mientras que razones como distancia y falta de seguro solo fueron citadas por el 13 % y el 3 %, respectivamente.

La situación actual enfatiza la importancia de una solución tecnológica que facilite la comunicación entre pacientes y especialistas, optimice el seguimiento de tratamientos, centralice el almacenamiento de historias clínicas y simplifique la gestión de citas. Además, se vuelve necesario incorporar consultas virtuales y recordatorios automáticos de citas para mejorar la accesibilidad y la eficiencia de la atención médica en el campo de la traumatología.

Se aplica la técnica 5W-2H que permite analizar las necesidades de nuestros usuarios al realizar una reflexión de las características principales de la situación general. Presentamos la información obtenida de las respuestas a las preguntas planteadas en la técnica. 

- **What(¿Qué?)**

  El problema radica en la falta de un sistema integral y automatizado en el área de traumatología, lo que resulta en largos tiempos de espera para programar consultas, cirugías y exámenes. Esto afecta la experiencia del paciente y puede obstaculizar su recuperación. 
- **When(¿Cuándo?)**
  
  El problema ocurre cuando los pacientes necesitan atención médica en el área de traumatología y enfrentan dificultades para programar consultas, cirugías y exámenes. Los pacientes utilizan el producto para gestionar sus citas y seguimientos de tratamiento.
- **Where(¿Dónde?)**
  
  Los pacientes pueden encontrarse en sus hogares, trabajos u otros lugares cuando utilizan el sistema para gestionar sus citas y seguimientos de tratamiento. El problema surge principalmente en consultorios médicos y clínicas de traumatología.
- **Who(¿Quién?)**
  
  Los pacientes que necesitan atención médica en traumatología, así como los especialistas médicos y el personal administrativo de consultorios y clínicas, están involucrados en el problema. Los pacientes y los especialistas médicos utilizarán el sistema propuesto.
- **Why(¿Por qué?)**

  La falta de un sistema integral y automatizado en el área de traumatología conduce a largos tiempos de espera y a una gestión ineficiente de las citas y tratamientos. La dispersión de información médica y la comunicación limitada entre médicos y pacientes agravan la situación.
- **How(¿Cómo?)**
  
  Los clientes utilizan el producto en condiciones de necesidad médica, cuando requieren atención en traumatología y deben programar citas, cirugías y exámenes. La situación ha llevado a la necesidad de una solución tecnológica que simplifique la gestión de citas y mejore la comunicación entre pacientes y especialistas.
- **How much(¿Cuánto?)**

  La Encuesta Nacional de Hogares (ENAHO) de 2022 revela que 7 de cada 10 personas que necesitaron atención médica no la obtuvieron, lo que indica que una gran cantidad de personas son afectadas por problemas de acceso y gestión en el área de salud, aunque no todos se refieren específicamente a traumatología. Sin embargo, la problemática específicamente en traumatología también puede afectar a una gran cantidad de pacientes que enfrenta demoras en el proceso de atención.
  
### 1.2.2. Lean UX Process	
###   1.2.2.1. Lean UX Problem Statements	
* Lo que ofrece nuestra aplicación es un sistema que mejora la  comunicación entre los especialistas dentro de una consultoría, como por ejemplo al momento de compartir las historias clínicas de un paciente y los procesos a los que se les somete. Y así poder evitar demoras y confusiones de datos como en algunos casos pasa. ¿Cómo podríamos hacer que esta comunicación sea rápida y eficaz?.
* Nuestra aplicación ofrece también un sistema para la programación de citas por parte de los pacientes , haciendo que estas no tengan que esperar por mucho tiempo y además también que se pueda dar una cita con ciertas especificación del paciente. ¿Cómo brindar un buen sistema de citas para los clientes donde podrán tener citas de acuerdo a sus necesidades?
###   1.2.2.2. Lean UX Assumptions
- **Business outcomes:**

  1. El usuario necesita optimizar la gestión de citas y procesos en el área de traumatología de manera eficiente.
  2. Las necesidades del usuario se resolverán a través de una aplicación web integrada en línea que permite programar citas, cirugías, exámenes y seguimiento de tratamientos.
  3. Los usuarios son pacientes que buscan atención en el área de traumatología y profesionales médicos especializados en el tratamiento.
  4. El usuario desea una interfaz fácil de usar para reservar citas, acceder a los registros médicos y comunicarse con los proveedores de atención médica.
  5. A través de nuestro servicio, los usuarios también pueden obtener consultas virtuales, recordatorios automáticos de citas y análisis de datos para mejorar los procesos.
  6. Ganaré dinero cobrando a los proveedores de atención médica tarifas de suscripción por el uso de la plataforma y posiblemente ofreciendo características premium por un cargo adicional.
  7. Mi competencia principal es el software de programación de citas independientes y los sistemas de gestión hospitalaria actuales.
  8. Con una solución más completa y específicamente diseñada para la atención traumatológica, que incluye características como consultas virtuales y recordatorios automáticos, venceremos a la competencia.
  9. Mi mayor riesgo es la resistencia de los proveedores de atención médica a adoptar nuevas tecnologías o integrarlas en sus sistemas existentes.
  10. Mediante la capacitación y el soporte extensivos al personal de atención médica durante el proceso de incorporación y la demostración de los claros beneficios del uso de la plataforma, reduciremos el riesgo.

- **User Assumptions:**

  - **¿Quién es el usuario?**

    Pacientes que necesitan atención traumatológica y médicos especializados en el área.
    
  - **¿Dónde encaja nuestro producto en su trabajo o vida?**

    El producto servirá como un lugar central para administrar citas traumatológicas, registros médicos y comunicación entre pacientes y proveedores de atención médica.
    
  - **¿Qué problema tiene nuestro producto? ¿Cómo se resuelve?**

    Reduce los tiempos de espera, facilita la programación de citas, centraliza los registros médicos para una toma de decisiones informada y permite consultas virtuales para mayor comodidad.
    
  - **¿Cuándo y cómo es usado nuestro producto?**

    Los usuarios pueden acceder a la plataforma desde una variedad de dispositivos, como computadoras de escritorio y teléfonos inteligentes, para reservar citas, revisar registros médicos y comunicarse con proveedores de atención médica desde casa, el trabajo o en movimiento.
    
  - **¿Qué características son importantes?**

    La programación de citas, el acceso a los registros médicos, las consultas virtuales y los recordatorios automáticos de citas mejoran la experiencia del paciente y el proceso de atención traumatológica.
    
  - **¿Cómo debe verse nuestro producto y comportarse?**

    El producto debe tener una interfaz limpia e intuitiva, ser fácil de navegar e integrarse perfectamente con los sistemas de atención médica actuales para los proveedores de atención médica. Además, debe ser fácil de usar y accesible para pacientes de todos los grupos demográficos.
    
###   1.2.2.3. Lean UX Hypothesis Statements	
* Creemos que los tiempos de espera se reducirán significativamente si los pacientes puede programar citas de manera rápida y eficiente a través de una plataforma en línea
* Creemos que la comunicación entre especialistas mejorará si se implementa un sistema para compartir historias clínicas y procesos médicos de manera rápida y efectiva
* Creemos que la experiencia del paciente mejorará si se ofrecen consultas virtuales y recordatorios automáticos de citas
###   1.2.2.4. Lean UX Canvas
<img src="../solution-profile/LeanUXCanvas.jpg" alt="Lean Ux Canvas">

###   1.3. Segmento Ojetivo
Nuestros segmentos objetivos en este se dividen en tres grupos fundamentales. Como primer segmento contamos con los pacientes que son los que han sufrido algún tipo de accidente y requieren una atención en el área de traumatología. En segundo lugar serían los médicos especialistas en el área de traumatología que requerirán de nuestro sistema para la gestión de sus citas y establecer una buena comunicación entre sus demás colegas de profesión, o laboratorios para una correcta coordinación de algún proceso que se lleve a cabo con el paciente. Por último están las consultorías o laboratorios quienes recibirán la información del paciente, brindada por los doctores, incluyendo procedimientos que requiera el paciente ya sea un tratamiento o algún tipo de examen.

----
<br>

# Capitulo 2

## 2.1 Competidores

### 2.1.1 Analisis Competitivo

<table>
  <tr>
    <th colspan="6" valign="top">Competitive Analysis Landscape</th>
  </tr>
  <tr>
    <td colspan="2" valign="top">¿Por qué llevar a cabo este análisis?</td>
    <td colspan="4" valign="top">El objetivo de este análisis es identificar las características de los competidores y encontrar maneras de diferenciarnos.</td>
  </tr>
  <tr>
    <td colspan="2" rowspan="2" valign="top">Startup y Competidores</td>
    <td valign="top">MedSystem</td>
    <td valign="top">Home Medical Management</td>
    <td valign="top">LOLIMSA</td>
    <td valign="top">SAMA</td>
  </tr>
  <tr>
    <td valign="top"><img src="../images/logo_medsystem.jpg" alt="Logo de MedSystem"  height="100px"></td>
    <td valign="top"><img src="../images/logo_homeMedical.png" alt="Logo de Home Medical Managment" height="100px"></td>
    <td valign="top"><img src="../images/logo_lolimsa.jpg" alt="Logo de LOLIMSA" height="100px"></td>
    <td valign="top"><img src="../images/logo_sama.png" alt="Logo de SAMMA" height="100px"></td>
  </tr>
  <tr>
    <td rowspan="2" valign="top">Perfil</td>
    <td valign="top">Overview</td>
    <td valign="top">Plataforma de gestión de procesos de un consultorio o clínica, que cuenta con diferentes funcionalidades para pacientes, doctores y laboratorios.</td>
    <td valign="top">Es una compañía que a través de una plataforma digital y sus profesionales, asegura la ejecución y calidad del servicio de salud domiciliaria.</td>
    <td valign="top">Es una empresa de software médico con soluciones tecnológicas para la gestión de centros médicos como clínicas y hospitales, farmacias y cadenas de farmacias y clínicas veterinarias. </td>
    <td valign="top">Es un consorcio de inversión dedicado a brindar servicios integrales de salud, especializados en la seguridad y salud en el trabajo. Contamos con distintas sedes a lo largo del norte del país, las cuales cuentan con el respaldo de la acreditación DIGESA/MINSA.
</td>

  </tr>
  <tr>
    <td valign="top">Ventaja competitiva ¿Qué valor ofrece a los clientes?</td>
    <td valign="top">Cuenta con distintas funcionalidades como un sistema de gestión de citas en línea que permita a los pacientes y doctores programar fácilmente consultas, programación de cirugías ,exámenes y seguimientos de tratamiento o recuperaciones.</td>
    <td valign="top">Utilizan inteligencia artificial e innovación para mejorar el servicio a los pacientes y facilitar la atención a los profesionales y prestadores de salud.</td>
    <td valign="top">Reduce entre 10 y 20% tus costos hospitalarios utilizando las mejores prácticas de Health Management con LOLCLI, el software de gestión hospitalaria más completo de Latinoamérica.</td>
    <td valign="top">Organización que orienta todos sus esfuerzos en realizar un servicio médico de calidad a través de la presentación de resultados confiables.</td>
  </tr>
  <tr>
    <td rowspan="2" valign="top">Perfil de Marketing</td>
    <td valign="top">Mercado objetivo</td>
    <td valign="top">Consultorio, clínicas y hospitales.</td>
    <td valign="top">Prestadores de salud, pacientes y personal médico</td>
    <td valign="top">Clínicas y hospitales</td>
    <td valign="top">Hospitales y clínicas</td>
  </tr>
  <tr>
    <td valign="top">Estrategias de marketing</td>
    <td valign="top">Publicidad por redes sociales y campañas.</td>
    <td valign="top">Publicidad por redes sociales.</td>
    <td valign="top">Publicidad por redes sociales.</td>
    <td valign="top">Publicidad por redes sociales.</td>
  </tr>
  <tr>
    <td rowspan="3" valign="top">Perfil de Producto</td>
    <td valign="top">Productos & Servicios</td>
    <td valign="top">Una plataforma para gestionar las citas médicas, programar cirugías, exámenes y seguimiento de tratamientos. Además, la plataforma almacena el historial clínico de los pacientes.</td>
    <td valign="top">Un software basado en el diseño centrado en el paciente, con información integrada, que utiliza la geolocalización y la valoración del servicio, como forma de optimizar la gestión del modelo.</td>
    <td valign="top">Software de gestión hospitalaria, impulsado por una plataforma de software de última generación que controla al detalle todas las actividades, desde que el paciente ingresa hasta que se retira del establecimiento</td>
    <td valign="top">Servicios integrales de salud:
-Exámenes médicos ocupacionales
-Monitores ocupacionales
-Vigilancia médica ocupacional
-Análisis de laboratorio
-radiografias digitales
</td>
  </tr>
  <tr>
    <td valign="top">Precios & Costos</td>
    <td valign="top">Varían según características de la clínica, con opciones de suscripción mensual o anual.</td>
    <td valign="top">Varían según el producto y pueden incluir tarifas de suscripción o costos de licencia.</td>
    <td valign="top">Los precios varían según el producto y pueden incluir tarifas de suscripción mensuales o costos de licencia.</td>
    <td valign="top">Los precios varían según el tamaño del hospital o clínica y las características específicas de la solución, con opciones de suscripción mensual o anual</td>
  </tr>
  <tr>
    <td valign="top">Canales de distribución (Web y/o Móvil)</td>
    <td valign="top">Principalmente a través de su sitio web oficial</td>
    <td valign="top">Principalmente a través de su sitio web, con posibilidad de acceso móvil. </td>
    <td valign="top">Principalmente a través de su sitio web oficial.</td>
    <td valign="top">Principalmente a través de su sitio web oficial.</td>
  </tr>
  <tr>
    <td rowspan="4" valign="top">Análisis SWOT</td>
    <td valign="top">Fortalezas</td>
    <td valign="top">
    	Ofrece una solución integral para la gestión de procesos en consultorios y clínicas, lo que incluye funcionalidades específicas para pacientes, médicos y laboratorios. Esta centralización de información puede mejorar la eficiencia operativa y la coordinación entre todas las partes involucradas en el proceso de atención médica.
    </td>
    <td valign="top">
       Ofrece cuidados personalizados en el hogar, generando satisfacción y lealtad. Su enfoque centrado en el paciente y su capacidad de adaptación son ventajas.
    </td>
    <td valign="top">
        Cuenta con amplia experiencia en software médico y ofrece soluciones integrales y personalizadas respaldadas por un sólido servicio de soporte técnico.
    </td>
    <td valign="top">
        Samma ofrece una variedad de herramientas de bienestar mental y una interfaz amigable que atrae a una amplia gama de usuarios.
    </td>
  </tr>
  <tr>
    <td valign="top">Debilidades</td>
    <td valign="top">
        La competencia en el mercado de software de gestión de consultorios y clínicas es intensa, con numerosas empresas que ofrecen soluciones similares.
    </td>
    <td valign="top">
        Limitaciones geográficas y dependencia del personal pueden afectar la expansión y la consistencia de los servicios.
    </td>
    <td valign="top">
        Enfrenta competencia en el mercado de software médico y puede estar sujeta a dependencia tecnológica y costos asociados con el desarrollo de soluciones.
    </td>
    <td valign="top">
        La competencia en el mercado de aplicaciones de bienestar mental puede dificultar que Samma se destaque, especialmente si enfrenta problemas de usabilidad o dependencia tecnológica.
    </td>
  </tr>
  <tr>
    <td valign="top">Oportunidades</td>
    <td valign="top">
        La creciente demanda de soluciones digitales en el sector de la salud ofrece una oportunidad para capturar una parte del mercado en constante expansión.
    </td>
    <td valign="top">
        Puede expandir servicios, integrar tecnología y formar asociaciones para llegar a más clientes y mejorar la eficiencia.
    </td>
    <td valign="top">
        Tiene potencial de expansión tanto nacional como internacional, además de oportunidades para desarrollar nuevas funcionalidades y establecer alianzas estratégicas.
    </td>
    <td valign="top">
        La expansión internacional y la colaboración estratégica ofrecen oportunidades para llegar a nuevos mercados y asociarse con empresas o instituciones para aumentar el alcance de la aplicación.
    </td>
  </tr>
  <tr>
    <td valign="top">Amenazas</td>
    <td valign="top">
        Las preocupaciones sobre la privacidad y seguridad de los datos en el sector de la salud son una amenaza constante.
    </td>
    <td valign="top">
        Competencia, cambios regulatorios y preocupaciones sobre privacidad y seguridad de datos pueden impactar la rentabilidad y confianza en los servicios.
    </td>
    <td valign="top">
        Los posibles cambios regulatorios, preocupaciones sobre seguridad de datos y avances tecnológicos rápidos representan riesgos que podrían afectar su posición en el mercado.
    </td>
    <td valign="top">
        Cambios en la regulación, críticas negativas y avances tecnológicos representan amenazas potenciales para la operación y la reputación de Samma en el mercado.
    </td>
  </tr>
</table>

### 2.1.2 Estrategias y tacticas frente a competidores

MedSystem puede destacarse en el mercado ofreciendo una plataforma de gestión de procesos clínicos altamente personalizable y fácil de usar, tanto para pacientes como para profesionales de la salud, diferenciándose así de competidores como Home Medical Management y LOLIMSA. Con un enfoque específico en la atención domiciliaria, la plataforma puede ofrecer funcionalidades especializadas para la coordinación y seguimiento de la atención médica en el hogar, proporcionando comodidad y eficiencia para pacientes y cuidadores. Además, MedSystem puede invertir en el desarrollo de tecnologías avanzadas, como inteligencia artificial y análisis de datos, para mejorar la gestión de consultorios y clínicas, posicionándose como una opción innovadora frente a empresas como LOLIMSA. Para competir con SAMA en el ámbito de la salud ocupacional y la seguridad laboral, MedSystem puede ofrecer módulos especializados y herramientas de cumplimiento normativo, aprovechando su experiencia en la gestión clínica para proporcionar soluciones integrales a empresas e instituciones. Una estrategia de marketing sólida, centrada en la educación del mercado sobre la importancia de la gestión eficiente de consultorios y clínicas, así como en testimonios de usuarios satisfechos, puede ayudar a MedSystem a construir una sólida reputación y atraer clientes potenciales. Además, explorar alianzas estratégicas con instituciones médicas y otros actores del sector puede ampliar su alcance y fortalecer su posición en el mercado. En resumen, MedSystem puede destacarse mediante la combinación de personalización, tecnología avanzada, especialización en atención domiciliaria y salud ocupacional, una sólida estrategia de marketing y alianzas estratégicas, lo que le permitirá diferenciarse y prosperar en un mercado competitivo.

## 2.2 Entrevistas

### 2.2.1 Diseno de entrevistas

Preguntas para el segmento objetivo paciente:

1. ¿Qué te motivó a buscar atención médica en el área de traumatología?
2. ¿Qué desafíos has enfrentado al buscar tratamiento médico para tu lesión o condición?
3. ¿Qué características consideras más importantes al elegir a un especialista en traumatología?
4. ¿Cómo prefieres programar tus citas médicas?
5. ¿Qué tipo de información te gustaría tener disponible antes de una consulta médica?
6. ¿Qué expectativas tienes en cuanto a la comunicación con tu médico y el equipo médico en general?
7. ¿Qué te gustaría ver mejorado en la experiencia de atención médica en el área de traumatología?
8. ¿Cómo prefieres recibir los resultados de tus exámenes médicos y pruebas diagnósticas?
9. ¿Qué aspectos valoras más en una plataforma web para el seguimiento de tu tratamiento y la comunicación con tu médico?
10. ¿Qué preocupaciones tienen sobre la privacidad y seguridad de tus datos médicos en línea?

Preguntas para el segmento objetivo doctor:

1. ¿Cuáles son los mayores desafíos que enfrentas en tu práctica diaria como médico especializado en traumatología?
2. ¿Qué herramientas o recursos te ayudarían a optimizar la gestión de tus citas y comunicación con otros médicos y laboratorios?
3. ¿Qué características consideras más importantes al elegir una solución tecnológica para la gestión de consultas y pacientes?
4. ¿Cómo prefieres recibir información sobre los pacientes antes de una consulta?
5. ¿Qué aspectos te gustaría mejorar en la comunicación con otros médicos y profesionales de la salud?
6. ¿Qué funcionalidades consideramos cruciales en una plataforma de gestión de consultas médicas?
7. ¿Cómo manejas típicamente la coordinación de atención entre diferentes especialistas y servicios médicos?
8. ¿Qué medidas de seguridad y privacidad consideramos esenciales al compartir información médica en línea?
9. ¿Qué te gustaría ver mejorado en la gestión de registros médicos y documentación de pacientes?
10. ¿Cuál es tu opinión sobre la integración de tecnología para mejorar la atención médica en traumatología?

Preguntas para el segmento objetivo laboratorio o consultoría:

1. ¿Cuáles son los principales desafíos que enfrenta tu laboratorio o consultoría en la recepción y gestión de información de pacientes?
2. ¿Qué información consideras más relevante al recibir un pedido médico de parte de un especialista en traumatología?
3. ¿Cómo prefieres recibir los pedidos y resultados de pruebas diagnósticas de parte de los médicos?
4. ¿Qué aspectos valoras más en una plataforma de comunicación con médicos y pacientes?
5. ¿Cuáles son tus mayores preocupaciones en cuanto a la seguridad y privacidad de los datos médicos que manejas?
6. ¿Cómo te gustaría que se optimizará el proceso de coordinación entre médicos y laboratorios para la realización de pruebas?
7. ¿Qué funcionalidades consideramos esenciales en una plataforma web para la gestión de pedidos y resultados de pruebas médicas?
8. ¿Qué medidas tomas actualmente para garantizar la exactitud e integridad de los resultados de las pruebas?
9. ¿Cómo manejas los tiempos de respuesta para la realización y entrega de resultados de pruebas diagnósticas?
10. ¿Qué mejoras te gustaría ver en la comunicación y colaboración con los médicos que envían pedidos a tu laboratorio o consultoría?

### 2.2.2 Registro de entrevistas

<u>Segmento objetivo - Paciente</u>

Entrevista 1:

Fecha entrevistada: 10/04/2024

Entrevistador: Manuel Alonso Gutierrez Zumaeta

Entrevistado: Gonzalo Jaime Zapata Campos

Datos del entrevistado:

- Edad: 20 años
- Distrito: San Martin de Porres

Link de la Entrevista: <a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202112353_upc_edu_pe/EQt5uMfao0BMlqnxHClNfYsBIugjlgqmpoO0X3BXEfjLRw?e=87pc3U ">Link</a>

- Minuto de Inicio:
- Minuto de Fin:

<img alt = "Entrevista1.1" src="../images/Entrevista1.1.png">

Resumen de la entrevista:

<p>Gonzalo nos comenta que ha tenido problemas anteriormente al momento de sacar cita, como el dijo no habia una buena organizacion de citas por lo que para sacar una ha tenido que espera mucho tiempo. Ademas habla de algunas caracteristica que le gustaria tener ante de poder sacar una cita y tambien otra para los envios de los resultados de algun examen medico que hice, dependiendo de la gravedad de la situacion el pueda elegir entre que sea virtual o presencial.
</p>

Entrevista 2:

Fecha entrevistada: 14/04/2024

Entrevistador: Juan Eduardo Montes Figueroa

Entrevistado: Abril Gloria Montes Jiménez

Datos del entrevistado:

- Edad: 50
- Distrito: La Molina

Link de la Entrevista: <a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210364_upc_edu_pe/Eb9Hi7qT4W5Ik-M_OdQcMLUBW7HLy0mp-tkYAZcSYEbM6A?e=daDNCa&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D">Link</a>


- Minuto de Inicio: 31:33
- Minuto de Fin: 35:45

<img alt = "Entrevista1.2" src="../images/Entrevista1.2.PNG">

Resumen de la entrevista:

<p>En la entrevista, Abril discutió su búsqueda de atención médica en traumatología debido a una lesión deportiva, destacando el desafío de encontrar un especialista con disponibilidad inmediata. Prioriza la experiencia y reputación del médico al elegir un especialista, y prefiere la conveniencia de programar citas médicas en línea. Expresó la importancia de tener información detallada antes de las consultas y espera una comunicación clara y coordinación entre los profesionales de la salud. Valora la facilidad de uso y la seguridad en una plataforma web para el seguimiento del tratamiento, pero muestra preocupación por la privacidad de sus datos médicos en línea y espera que se cumplan los estándares de seguridad.</p>

Entrevista 3:

Fecha entrevistada:

Entrevistador:

Entrevistado:

Datos del entrevistado:

- Edad:
- Distrito:

Link de la Entrevista: <a href="">Link</a>

- Minuto de Inicio:
- Minuto de Fin:

<img alt = "Entrevista1.3" src="../images/Entrevista1.3.png">

Resumen de la entrevista:

<p></p>

<u>Segmento objetivo - Medico</u>

Entrevista 1:

Fecha entrevistada: 10/04/2024

Entrevistador: Jorge Altamirano

Entrevistado: Gaby Manrique

Datos del entrevistado:

- Edad: 50
- Distrito: La Molina

Link de la Entrevista: <a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210364_upc_edu_pe/Eb9Hi7qT4W5Ik-M_OdQcMLUBW7HLy0mp-tkYAZcSYEbM6A?e=daDNCa&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D">Link</a>

- Minuto de Inicio: 00:00
- Minuto de Fin: 07:40

<img alt = "Entrevista2.1" src="../images/Entrevista2.1.png">

Resumen de la entrevista:

<p>
Durante la entrevista, Gaby compartió los desafíos diarios que enfrenta en su práctica como especialista en traumatología, destacando la necesidad de herramientas tecnológicas que optimicen la gestión de citas y la comunicación interprofesional. Resaltó la importancia de características como la accesibilidad de información previa a la consulta y la seguridad de los datos médicos en plataformas digitales. Además, expresó su interés en mejorar la coordinación entre especialistas y servicios médicos, y su entusiasmo por la integración de tecnología para mejorar la atención médica en traumatología.</p>

Entrevista 2:

Fecha entrevistada: 09/04/2024

Entrevistador: Carlos Eduardo Guimaraes Escalante

Entrevistado: Gerardo Villaroel

Datos del entrevistado:
- Edad: 30
- Distrito: Trujillo

Link de la Entrevista: <a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210364_upc_edu_pe/Eb9Hi7qT4W5Ik-M_OdQcMLUBW7HLy0mp-tkYAZcSYEbM6A?e=daDNCa&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D">Link</a>

- Minuto de Inicio: 11:59
- Minuto de Fin: 22:24

<img alt = "Entrevista2.2" src="../images/Entrevista_traumatologia.png">

Resumen de la entrevista:
<p>
Durante la entrevista, el Dr. Gerardo Villaroel nos explica los procesos que suele haber en el área de traumatología y como es que en el centro donde trabaja ya cuenta con un sistema tecnológico que les da mayor facilidad para comunicarse con sus pacientes. En este caso nos dice que los pacientes ingresan con sus credenciales a este portal médico, y de esa forma pueden visualizar el contenido multimedia que es de ellos, como radiografías por ejemplo. El Dr. Villaroel reafirma la importancia de la tecnología en su práctica médica, y como facilita su forma de trabajo.
</p>

Entrevista 3:

Fecha entrevistada: 

Entrevistador:

Entrevistado:

Datos del entrevistado:
- Edad:
- Distrito:

Link de la Entrevista: <a href="">Link</a>

- Minuto de Inicio: 
- Minuto de Fin:

<img alt = "Entrevista2.3" src="../images/Entrevista2.3.png">

Resumen de la entrevista:
<p></p>

<u>Segmento objetivo - Laboratorio</u>

Entrevista 1:

Fecha entrevistada: 10/04/2024

Entrevistador: Jorge Altamirano

Entrevistado: Luis Protocarrero

Datos del entrevistado:

- Edad: 60
- Distrito: La Molina

Link de la Entrevista: <a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210364_upc_edu_pe/Eb9Hi7qT4W5Ik-M_OdQcMLUBW7HLy0mp-tkYAZcSYEbM6A?e=daDNCa&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D">Link</a>

- Minuto de Inicio: 07:40
- Minuto de Fin: 11:59

<img alt = "Entrevista3.1" src="../images/Entrevista3.1.png">

Resumen de la entrevista:

<p>Durante la entrevista con el Luis, se exploraron los desafíos principales que enfrenta su laboratorio en la recepción y gestión de información de pacientes, destacando la relevancia de la exactitud e integridad de los resultados de las pruebas. Se enfatizó la importancia de la seguridad y privacidad de los datos médicos, así como la necesidad de optimizar la coordinación entre médicos y laboratorios para la realización de pruebas. También se discutieron las funcionalidades esenciales en una plataforma web para la gestión de pedidos y resultados de pruebas médicas, resaltando la importancia de la comunicación efectiva y la colaboración con los médicos remitentes.</p>

Entrevista 2:

Fecha entrevistada: 13/04/2024

Entrevistador: Carlos Eduardo Guimaraes Escalante

Entrevistado: Giannina Escalante Gutierrez

Datos del entrevistado:
- Edad: 51
- Distrito: Trujillo

Link de la Entrevista: <a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210364_upc_edu_pe/Eb9Hi7qT4W5Ik-M_OdQcMLUBW7HLy0mp-tkYAZcSYEbM6A?e=daDNCa&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D">Link</a>

- Minuto de Inicio:
- Minuto de Fin:

<img alt = "Entrevista3.2" src="../images/entrevista_lab2.png">

Resumen de la entrevista:
<p>
En esta entrevista, Giannina nos comenta la importancia de que los resultado médicos llegue en las horas establecida, asi como lo importante que es que las indicaciones el doctor para realizar una prueba médica sea concisa. Según ella, los examenes se deben realizar una y otra vez para que el resultado de la prueba sea fiable. Asimismo, nos habla de lo importante que sería la tecnología para poder tener un contacto más directo con el médico, y de esta forma agilizar los procesos de laboratorio.
</p>

Entrevista 3:

Fecha entrevistada:

Entrevistador:

Entrevistado:

Datos del entrevistado:

- Edad:
- Distrito:

Link de la Entrevista: <a href="">Link</a>

- Minuto de Inicio:
- Minuto de Fin:

<img alt = "Entrevista3.3" src="../images/Entrevista3.3.png">

Resumen de la entrevista:

<p></p>

### 2.2.3 Analisis de entrevistas

Analizando las entrevistas de Gonzalo y Abril, es posible identificar varias necesidades y preferencias comunes que podrían guiar la mejora y el desarrollo de un sistema de gestión de citas médicas.

#### Necesidades Expresadas:

- Búsqueda de Especialistas: Abril menciona la dificultad de encontrar especialistas disponibles, especialmente en traumatología. Esto sugiere la necesidad de un sistema que facilite la búsqueda de médicos por especialidad y disponibilidad.
- Priorización de la Experiencia Médica: Valora la experiencia y la reputación del especialista, indicando la importancia de que esta información sea accesible y clara en la plataforma.
- Seguridad y Privacidad: Tiene preocupaciones sobre la privacidad de sus datos médicos en plataformas en línea, lo que requiere garantizar altos estándares de seguridad y encriptación de datos.
- Coordinación entre Profesionales: Espera que haya buena comunicación y coordinación entre los distintos profesionales de salud que consulte.

## 2.3 Needfinding

### 2.3.1 User Personas

- Paciente:
  <img src="../images/Marcos Suarez.png">

- Doctor:
  <img src="../images/luistorrres.png">

### 2.3.2 User Task Matrix

<table>
    <thead>
        <tr>
            <th>Task</th>
            <th colspan="2">Pacientes</th>
            <th colspan="2">Profesionales médicos</th>
            <th colspan="2">Laboratorio</th>
        </tr>
        <tr>
            <th></th>
            <th>Frecuencia</th>
            <th>Importancia</th>
            <th>Frecuencia</th>
            <th>Importancia</th>
            <th>Frecuencia</th>
            <th>Importancia</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Programar una cita</td>
            <td>Alta</td>
            <td>Alta</td>
            <td>Alta</td>
            <td>Alta</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Acceder a resultados de exámenes</td>
            <td>Media</td>
            <td>Alta</td>
            <td>Alta</td>
            <td>Alta</td>
            <td>Alta</td>
            <td>Alta</td>
        </tr>
        <tr>
            <td>Realizar seguimiento de tratamiento</td>
            <td>Alta</td>
            <td>Alta</td>
            <td>Alta</td>
            <td>Alta</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Agendar una cirugía</td>
            <td>Baja</td>
            <td>Alta</td>
            <td>Media</td>
            <td>Alta</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Participar en consultas virtuales</td>
            <td>Baja</td>
            <td>Alta</td>
            <td>Media</td>
            <td>Alta</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Recibir recordatorios automáticos de citas</td>
            <td>Alta</td>
            <td>Alta</td>
            <td>Alta</td>
            <td>Alta</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Acceder a historias clínicas</td>
            <td>-</td>
            <td>-</td>
            <td>Alta</td>
            <td>Alta</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Consultar información sobre medicamentos</td>
            <td>Media</td>
            <td>Alta</td>
            <td>Media</td>
            <td>Alta</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Comunicarse con el especialista</td>
            <td>Alta</td>
            <td>Alta</td>
            <td>Media</td>
            <td>Alta</td>
            <td>Alta</td>
            <td>Alta</td>
        </tr>
        <tr>
            <td>Proporcionar retroalimentación sobre la experiencia</td>
            <td>Baja</td>
            <td>Media</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Solicitar análisis clínicos</td>
            <td>Baja</td>
            <td>Alta</td>
            <td>-</td>
            <td>-</td>
            <td>Alta</td>
            <td>Alta</td>
        </tr>
        <tr>
            <td>Enviar resultado de análisis</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>Alta</td>
            <td>Alta</td>
        </tr>
    </tbody>
</table>

### 2.3.3 User Journey Mapping

#### Segmento 1(pacientes):

<img src="../images/journeyMap_pacientes.png" alt="JourneyMap">

#### Segmento 2(doctor):

<img src="../images/journeyMap_doctor.png" alt="JourneyMap">

#### Segmento 3(laboratorio):

<img src="../images/journeyMap_laboratorio.png" alt="JourneyMap">

### 2.3.4 Empathy Mapping

<img src="../images/Empathy map.png" alt="EmpathyMap">

### 2.3.5 As-is Scenario Mapping

<p><b>Para el segmento 1 (Pacientes):</b></p>
<img src="../images/To_Be_Scenario_Mapping_1.jpg">

<p><b>Para el segmento 2 (Doctores):</b></p>
<img src="../images/To_Be_Scenario_Mapping_2.jpg">

<p><b>Para el segmento 3 (Laboratorios):</b></p>
<img src="../images/To_Be_Scenario_Mapping_3.jpg">

## 2.4 Ubiquitous Language

**Paciente**: Un individuo que busca atención médica en el campo de la traumatología.
<br>
**Historial Médico**: El registro completo de la información médica y el historial de tratamientos de un paciente.
<br>
**Cita Médica**: Una programación de tiempo específico para la atención médica entre un paciente y un médico.
<br>
**Análisis Médico**: Proceso de examinar muestras biológicas para obtener información sobre la salud de un paciente.
<br>
**Tratamiento**: Un plan de acción médico recomendado para abordar una condición específica del paciente.
<br>
**Resultados de Análisis**: Los hallazgos y conclusiones obtenidos a partir de los análisis médicos realizados en muestras de pacientes.
<br>
**Notificaciones**: Mensajes automáticos enviados a pacientes y médicos para recordatorios de citas, resultados de análisis, etc.
<br>
**Comunicación Segura**: La capacidad de intercambiar información sensible de manera segura entre pacientes y médicos.
<br>
**Personal de Laboratorio**: Profesionales responsables de realizar análisis médicos en las muestras de los pacientes.
<br>
**Muestra**: Material biológico proporcionado por un paciente para su análisis médico.
<br>



