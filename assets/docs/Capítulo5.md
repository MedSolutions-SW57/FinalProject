# Capitulo 5

## 5.1 Software Cpmfiguration Managment

### 5.1.1 Software Development Environment Configuration

En esta sección se describen brevemente todas las herramientas que se han utilizado para la elaboración del proyecto, se dividirán en dos partes.

#### UX/UI Design:

- Miro: Miro es una herramienta en línea colaborativa en tiempo real, esta permite crear diversos diagramas, mapas mentales, diagramas de flujo u otros artefactos que se necesiten en el proyecto.
  Link: https://miro.com/es/
- UXPressia: UXPressia es una herramienta enfocada en lo que es la experiencia de usuario, ya que esta permite crear User Personas, Customer Journey, Impact maps, etc.
  Link: https://uxpressia.com/
- Figma: Figma es una herramienta que se enfoca en el diseño de interfaces para los usuarios y prototipado de las páginas webs, además de que este también es colaborativo por lo cual todos pueden trabajar en un mismo proyecto en simultáneo.
  Link: https://miro.com/es/
- Structurizr: Es una página web donde nos permite desarrollar modelos en C4, de la arquitectura de nuestro proyecto describiendo los contenedores, componentes y contextos de nuestra solución web.
  Link: https://structurizr.com/

#### Software Development:

- Github: Herramienta para guardar, a través de repositorios, los proyecto que se desarrollen, además que permite guardar un historial de versiones, utilizando Git
  Link: https://github.com
- Github Pages: Herramienta dentro de github que permite alojar una pagina web de un repositorio
  HTML: Un lenguaje de marcado para crear tanto la estructura y el contenido de una página web.
- JavaScript: Lenguaje de programación para agregar funcionalidad a las páginas webs
- CSS: Lenguaje utilizado para dar estilo a las páginas webs
- Visual Studio Code: Editor de código que se utiliza para realizar distintos trabajos con respecto a la programación, este soporta una gran cantidad de lenguajes, como Python, JavaScript, HTML, entre otros.
  Link: https://code.visualstudio.com/

#### Project Managment:

Para el desarrollo del proyecto hemos usado distintas plataformas para hacer las coordinaciones de los avances, el primero fue un grupo por medio de WhatsApp donde compartimos las opiniones del trabajo y los avances realizados, después para las reuniones utilizamos Discord que nos permite hacer llamadas para una correcta coordinación del trabajo. En cuanto a los avances del trabajo utilizamos github donde hacíamos commit con cada avance significativo que hacemos en los repositorios

### 5.1.2 Source Code Management

Hemos creado los repositorios que usaremos a lo largo de el desarrollo del proyecto esto incluye el de la documentacion, landing page, frontend y backend.

- URL del repositorio de documentacion: https://github.com/LosLuminosos-SW57/FinalProject

- URL del repositorio de la landing page: https://github.com/LosLuminosos-SW57/LandingPageMedSystem

- URL del repositorio del Frontend: https://github.com/LosLuminosos-SW57/Frontend-MedSystem

- URL del repositorio del Backend: https://github.com/LosLuminosos-SW57/Backend-MedSystem

### 5.1.3 Source Code Style Guide & Conventions

Para el desarrollo de nuestra solucion web emplearemos distintos lenguajes de programacion para la landing page el frontend y backend:

#### HTML:

- Indentación: Manténer una indentación clara para mejorar la legibilidad.
- Semántica: Utilizar elementos HTML semánticos para una estructura clara y accesible.
- Comentarios: Documentar el código HTML con comentarios claros y concisos.
- Atributos Alt: Proporcionar textos alternativos para imágenes y otros elementos.

#### CSS:

- Nomenclatura de Clases: UtilizaR una convención de nomenclatura consistente, como BEM.
- Separación de Intereses: Separar estilos del HTML utilizando clases y selectores específicos.
- Reutilización de Estilos: Identificar estilos comunes y reutilízarlos para mantener la coherencia.

#### JavaScript:

- Nomenclatura de Variables: Utilizar nombres descriptivos, significativos y breves.
- Modularidad: Dividir el código en módulos pequeños y reutilizables.
- Manejo de Errores: Implementar un manejo de errores robusto.

### 5.1.4 Software Deployment Configuration

Para gestionar el despliegue de nuestra aplicación, hemos optado por utilizar GitHub y GitHub Pages.

GitHub es una plataforma para alojar repositorios de Git. Permite colaborar de manera eficiente en proyectos de software, facilitando el seguimiento de cambios, la revisión de código y la gestión de versiones.

Despues tambien esta GitHub Pages que es una función de GitHub que permite alojar sitios web estáticos directamente desde un repositorio de GitHub. Con GitHub Pages, permitiendonos alojar nuestra pagina web sin tener que pagar un servidor externo.

## 5.2 Landing Page, Services & Applications Implementation

### 5.2.1 Sprint 1

### 5.2.1.1 Sprint Planning 1

| **Sprint #**                       | Sprint 1                                                                                                                                                                                                    |
| :--------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Sprint Planning Background**     |                                                                                                                                                                                                             |
| Date                               | 2024-04-05                                                                                                                                                                                                  |
| Time                               | 07:00 AM                                                                                                                                                                                                    |
| Location                           | Virtual                                                                                                                                                                                                     |
| Prepared by                        | Gutierrez Zumaeta, Manuel Alonso                                                                                                                                                                            |
| Attendees (to planning meeting)    | <p>Guimaraes Escalante, Carlos Eduardo</p><p>Altamirano Saenz, Jorge Armando</p><p>Montes Figueroa, Juan Eduardo</p><p>Flores Manrique, Sebastian Enrique</p><p>Gutierrez Zumaeta, Manuel Alonso</p><p></p> |
| Sprint n - 1 Review Summary        | No hubo sprint anterior                                                                                                                                                                                     |
| Sprint n - 1 Retrospective Summary | No hubo sprint anterior                                                                                                                                                                                     |
| **Sprint Goal & User Stories**     |                                                                                                                                                                                                             |
| Sprint 1 Goal                      | Desarollo de la landing page                                                                                                                                                                                |
| Sprint 1 Velocity                  | 18                                                                                                                                                                                                          |
| Sum of Story Points                | 18                                                                                                                                                                                                          |

### 5.2.1.2 Sprint Backlog 1

| User Story ID | User Story Title                | Task ID | Task Title                      | Description                                                                   | Estimation (Hours) | Assigned To                        | Status |
| ------------- | ------------------------------- | ------- | ------------------------------- | ----------------------------------------------------------------------------- | ------------------ | ---------------------------------- | ------ |
| US36          | Barra de navegación             | T01     | Implementar barra de navegación | Desarrollar una barra de navegación interactiva en la página de inicio.       | 2                  | Juan Montes, Carlos Guimaraes      | Done   |
| US32          | Sección sobre el Producto       | T02     | Crear sección del producto      | Diseñar y llenar la sección de detalles del producto o servicio.              | 2                  | Sebastian Flores                   | Done   |
| US31          | Sección About Us                | T03     | Desarrollar sección About Us    | Preparar contenido y diseño de la sección "About Us" con misión y valores.    | 2                  | Manuel Gutierrez, Jorge Altamirano | Done   |
| US34          | Sección de contactos            | T04     | Organizar sección de contactos  | Implementar formulario de contacto y detalles de comunicación en la web.      | 2                  | Manuel Gutierrez                   | Done   |
| US33          | Funciones que ofrece al cliente | T05     | Detallar funciones clave        | Describir las funcionalidades principales que la aplicación ofrece a usuarios | 2                  | Sebastian Flores                   | Done   |
| US35          | Sección sobre el equipo         | T06     | Mostrar equipo de trabajo       | Crear sección con perfiles y roles del equipo de trabajo.                     | 2                  | Jorge Altamirano, Carlos Guimaraes | Done   |

### 5.2.1.3 Deployment Evidence for Sprint Review

Evidencias de los commits de los miembros del equipo:

<img src="../images/commits.png">

### 5.2.1.4 Testing Suite Evidence for Sprint Review

Hemos realizado los acceptance test para las user stories del sprint:

#### US31

#### Feature: Sección About Us en la Landing Page

**Scenario**: Visualización de la sección About Us
**Given** el `usuario` desea conocer sobre la empresa
**When** ingresa al Landing Page
**Then** se mostrará la sección `About Us` que permita al usuario conocer la misión, visión y valores de la empresa.

#### Examples: INPUT

| usuario  |
| -------- |
| Ana Mora |

#### Examples: OUTPUT

| About Us                        |
| ------------------------------- |
| Misión, Visión, Caracteristicas |

#### US32

#### Feature: Sección Sobre el Producto en la Landing Page

**Scenario**: Visualización de la sección Sobre el Producto
**Given** el `usuario` desea conocer detalles del producto
**When** ingresa al Landing Page
**Then** se mostrará la sección `Sobre el Producto` que explique cómo funciona el producto, sus beneficios y ventajas competitivas.

#### Examples: INPUT

| usuario     |
| ----------- |
| Carlos Ruiz |

#### Examples: OUTPUT

| Sobre el producto |
| ----------------- |
| Funciones         |

#### US34

Feature: Sección Equipo en la Landing Page

Scenario: Visualización de la sección Equipo
  Given el `usuario` desea conocer al equipo detrás de la empresa
  When ingresa al Landing Page
  Then se mostrará la sección `Equipo` que presente información detallada de los miembros del equipo.

Examples: INPUT
  | usuario      |
  | Roberto Díaz |

Examples: OUTPUT
  | Equipo                                           |
  | Miembros, Roles  |

#### US35
#### Feature: Sección Equipo en la Landing Page

**Scenario**: Visualización de la sección Equipo
**Given** el `usuario` desea conocer al equipo detrás de la empresa
**When** ingresa al Landing Page
**Then** se mostrará la sección `Equipo` que presente información detallada de los miembros del equipo.

#### Examples: INPUT

  | usuario      |
  | ----------- |
  | Roberto Díaz |

#### Examples: OUTPUT

  | Equipo |
  | ----------- |
  | Miembros, Roles  |

#### US36

#### Feature: Barra de navegación en la Landing Page

Feature: NavBar en la Landing Page

Scenario: Visualización de NavBar
  Given el `usuario` desea navegar a través de la página
  When ingresa al Landing Page
  Then se mostrará el `Navbar` que permita al usuario navegar de forma sencilla.

Examples: INPUT
  | usuario     |
  | Kelly Verde |

Examples: OUTPUT
  | Navbar                                          |
  | Home, About Us, Product, Team, Contact|

### 5.2.1.5 Execution Evidence for Sprint Review

Desarollo de la barra de navegacion para la correcta navagacion a travez de todo el documento y la seccion home.

<img src="../images/home.png">

Seccion de About Us:

<img src="../images/aboutus.png">

Seccion de Product:

<img src="../images/product.png">

Seccion de Team:

<img src="../images/team.png">

Seccion de Contact Us y Footer:

<img src="../images/contact.png">

### 5.2.1.6 Services Documentation Evidence for Sprint Review

No se realizo ningun trabajo con servicios web

### 5.2.1.7 Software Deployment Evidence for Sprint Review

Se procede a desplegar la landing page una vez terminada, por lo que se usarla Github Pages.

Entrar a la configuracion del repositorio de la landing, vamos al apartado de Pages:

<img src="../images/pages.png">

Luego en la seccion "branch" cambiamos en donde dice "None" a "main" que es la rama donde estaria el html:

<img src="../images/pages1.png">

Presionamos save y tendremos que esperar que se despliegue la pagina

<img src="../images/deploy.png">

<img src="../images/pages2.png">

### 5.2.1.8 Team Collaboration Insights during Sprint



Los insights se sacaron del mismo apartado de Insights dentro del repositiorio de la landing page:

<img src="../images/insights.png">

### 5.2.2 Sprint 2

### 5.2.2.1 Sprint Planning 2

| **Sprint #**                       | Sprint 2                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|:-----------------------------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Sprint Planning Background**     |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| Date                               | 2024-05-02                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| Time                               | 11:30 AM                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| Location                           | Virtual                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| Prepared by                        | Gutierrez Zumaeta, Manuel Alonso                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Attendees (to planning meeting)    | <p>Guimaraes Escalante, Carlos Eduardo</p><p>Altamirano Saenz, Jorge Armando</p><p>Montes Figueroa, Juan Eduardo</p><p>Flores Manrique, Sebastian Enrique</p><p>Gutierrez Zumaeta, Manuel Alonso</p><p></p>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| Sprint n - 1 Review Summary        | Durante el primer sprint, el equipo logró implementar el landing page y desplegarlo satisfactoriamente. Todas las tareas planificadas fueron completadas según las especificaciones requeridas. El despliegue se llevó a cabo sin problemas y el landing page está funcionando correctamente en producción, reflejando una ejecución exitosa del sprint.                                                                                                                                                                                                                                                                                                                                                                                          |
| Sprint n - 1 Retrospective Summary | El equipo identificó como aciertos la comunicación efectiva y la colaboración en la resolución de problemas. No obstante, se señaló la necesidad de una mejor planificación inicial, especialmente en cuanto a la estimación del tiempo necesario para ciertas tareas, y se identificó la posibilidad de optimizar el proceso de revisión de código para garantizar una mayor calidad del producto entregado.                                                                                                                                                                                                                                                                                                                                     |
| **Sprint Goal & User Stories**     |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| Sprint 2 Goal                      | El objetivo principal que tiene este sprint 2 es elaborar la primera versión y despliegue del front end web applications para el negocio.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| Sprint 2 Velocity                  |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| Sum of Story Points                |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |

### 5.2.1.2 Sprint Backlog 2


| User Story ID | User Story Title                       | Task ID | Task Title                                     | Description                                                                                                                                                                         | Estimation (Hours) | Assigned To                | Status     |
|---------------|----------------------------------------|---------|------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------|----------------------------|------------|
| US07          | Registro de nueva cita                 | T01     | Sección de registar nueva cita                 | Crear la sección de registar nueva cita, donde el paciente podrá progrmar su cita escogiendo la fecha y hora, la especialidad(de momento solo traumatología), el doctor y el campus | 8                  | Manuel Gutierrez Zumaeta   | Done       |
| US02          | Gestión de citas                       | T02     | Sección de gestionar citas                     | Crear la sección de gestionar citas, donde el doctor podrá visualizar una lista de citas pendientes y acceder a cada una para ver la información completa                           | 6                  | Manuel Gutierrez Zumaeta   | Done       |
| US06          | Seguridad de los datos médicos         | T03     | Opción de acceso personalizado basado en roles | Agregar la opción que permita seleccionar un rol específico y así acceder con sus respectivas credenciales.                                                                         | 2                  | Jorge Altamirano Saenz     | Done       |
| US12          | Confirmación de cita                   | T04     | Enviar la confirmación de la cita              | Implementar un envio de confirmación de la cita programada al correo electrónico y/o mensaje del paciente una vez realizado el pago.                                                | 4                  | Jorge Altamirano Saenz     | In-process |
| US10          | Recordatorio de citas                  | T05     | Opción para habilitar las notificaciones       | Implementar un botón para que el usuario pueda activar o desactivar  si desea recibir notificaciones respecto a sus citas.                                                          | 2                  | Sebastian Flores Manrique  | Done       |
| US11          | Cancelación y re-agendamiento de citas | T06     | Crear sección de Mis citas                     | Crear la sección de mis citas donde el paciente podrá editar su cita programada, como cambiar la fecha y hora, seleccionar otro doctor o cancelar la cita.                          | 4                  | Manuel Gutierrez Zumaeta   | Done       |
| US04          | Herramienta de comunicación            | T07     | Implementación de un chat                      | Implementar un chat tanto para pacientes y doctores, donde podrán enviar mensajes en tiempo real y visualizar el listado de todos sus chats                                         | 6                  | Sebastian Flores Manrique  | In-process |
| US15          | Actualización de Planes de Tratamiento | T08     | Crear sección de tratamientos                  | Crear la sección de tratamientos donde el doctor podrá agregar, editar o remover algún tratamiento de la lista.                                                                     | 6                  | Juan Moetes Figueroa       | Done       |
| US19          | Acceso rápido al historial médico del paciente | T09     | Crear sección de historial médico              | Crear la sección de historial del paciente donde mostrará una tabla con los historiales, además de una opción de búsqueda.                                                          | 6                  | Carlos Guimaraes Escalante | Done       |
| US15          | Visualización detallada del historial médico | T10     | Ver información completa del historial médico  | Implementar un botón en la sección de historiales de pacientes para poder mostrar al detalle el historial de cada paciente.                                                         | 4                  | Carlos Guimaraes Escalante | Done       |
| US29          | Sistema de Registro de Resultados con Consideraciones Clínicas Automatizadas                 | T11     | Sección para visualizar resultados de exámenes | Crear una sección donde se mostrará los resultados de exámenes de pacientes en una tabla, además contará con un botón de búsqueda.                                                  | 6                  | Sebastian Flores Manrique  | Done       |
| US05          | Generación de informes                 | T12     | Opción que permitia descargar un iforme final  | Crear una opción que al finalizar un tratamiento permita generar un informe completo sobre este y a la vez poder descargarlo                                                        | 2                  | Juan Moetes Figueroa       | In-process |


### 5.2.1.3 Development Evidence for Sprint Review

| Repository                          | Branch                         | Commit Id                                | Commit Message                                                                                                                | Commit Message Body | Commited on (Date) |
|-------------------------------------|--------------------------------|------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|---------------------|--------------------|
| LosLuminosos-SW57medSystem-FrontEnd | master                         | 8a46e23543954eddda2eb37cd34ad4d6af1ca96a | chore:initial commit                                                                                                          |                     | 22/04/24           |
| LosLuminosos-SW57medSystem-FrontEnd | master                         | d57196a2c022906cfa5ae32010e283d43f05d0c4 | feat: side-nav created                                                                                                        |                     | 23/04/24           |
| LosLuminosos-SW57medSystem-FrontEnd | feat/dev-request-results       | a8ed508d91d70ca3cf1c992d8b1bd7de9a94f70a | feat: create request results component                                                                                        |                     | 24/04/24           |
| LosLuminosos-SW57medSystem-FrontEnd | feat/dev-request-results       | e8177b5689b48528b2ff5e9bfb1227964eeb448e | feat: update request results component                                                                                        |                     | 24/04/24           |
| LosLuminosos-SW57medSystem-FrontEnd | feat/dev-request-results       | b700ef792920527fd0b4aef0f2b89bb6435b2379 | feat: add request top appmodule.                                                                                              |                     | 24/04/24           |
| LosLuminosos-SW57medSystem-FrontEnd | feat/dev-request-results       | 11daf5f513481ecbce313ec70ff606633a77ee60 | feat: fix request-results and add module table                                                                                |                     | 24/04/24           |
| LosLuminosos-SW57medSystem-FrontEnd | master                         | 17596dd0ebfd4c6441dadcaee2b22b00d2b40741 | feat: add imports to module                                                                                                   |                     | 25/04/24           |
| LosLuminosos-SW57medSystem-FrontEnd | master                         | 197bb6a0dddddc24547491b55f5782377317811f | feat: create db.json and routes.json                                                                                          |                     | 25/04/24           |
| LosLuminosos-SW57medSystem-FrontEnd | feat/dev-request-results       | 200a65d5383715d8fcf50e25d00ce9aa883c4dc9 | feat: create service and results class                                                                                        |                     | 25/04/24           |
| LosLuminosos-SW57medSystem-FrontEnd | feat/dev-appointments          | 00bb0ec116e017303d0715e26c802d5dc8114ef5 | feat: appointments component updated                                                                                          |                     | 25/04/24           |
| LosLuminosos-SW57medSystem-FrontEnd | feat/dev-appointment-routing   | b07be04649a78902381d4f9d80c5b64851303bc6 | feat: routes were implemented, side-nav component was eliminated and directory pages was created.                             |                     | 25/04/24           |
| LosLuminosos-SW57medSystem-FrontEnd | master                         | 13ab1f3e09e43a33155494ed71982a6db0799b42 | feat: page not found component created                                                                                        |                     | 25/04/24           |
| LosLuminosos-SW57medSystem-FrontEnd | feat/dev-treatments            | c5a29031469a992b83975d771358914bdf997817 | feat: updated treatments components                                                                                           |                     | 26/04/24           |
| LosLuminosos-SW57medSystem-FrontEnd | feat/dev-request-history       | a4ca5dea8012299f6ef47d867f2ab9f00a749377 | feat: added request history                                                                                                   |                     | 27/04/24           |
| LosLuminosos-SW57medSystem-FrontEnd | feat/dev-request-history       | 2b7da8520ecdc2d151b42a3e2da71982e77196b1 | feat: modified db.json and way to retrieve the data for rquest history                                                        |                     | 27/04/24           |
| LosLuminosos-SW57medSystem-FrontEnd | feat/dev-appointments-patients | 0dc6a77dfced7d2d873ab4cf6dda230c7c1ce96a | feat: review-appointment component and route created                                                                          |                     | 27/04/24           |
| LosLuminosos-SW57medSystem-FrontEnd | feat/dev-treatments            | c483c1bfc8c7a14c69e05f95b5c9305cea2f6316 | feat: treatments component updated                                                                                            |                     | 27/04/24           |
| LosLuminosos-SW57medSystem-FrontEnd | feat/dev-appointments          | f4646c18f1046b431ede237b924b52bf014ac328 | chore: refactor appointments components to doctor-appointments, created new directory for the bounded context of appointments |                     | 28/04/24           |
| LosLuminosos-SW57medSystem-FrontEnd | feat/login                     | c84690b9d5a6110a4046496d237fdbc376b31bb3 | feat: created register page                                                                                                   |                     | 30/04/24           |
| LosLuminosos-SW57medSystem-FrontEnd | feat/request-history           | 0c8693c59fb2ce486ef55cadde8371e5ea2d9a17 | feat: added patients request history                                                                                          |                     | 01/05/24           |
| LosLuminosos-SW57medSystem-FrontEnd | feat/request-results           | a4bd117a8975948d5034c43ca124a0fd5f6557f7 | feat: add patient exam results page                                                                                           |                     | 01/05/24           |
| LosLuminosos-SW57medSystem-FrontEnd | feat/login                     | 2ae56bd54b28859ce06a228c89af7872b7958716 | feat: added login and register and routes                                                                                     |                     | 01/05/24           |


## 5.4 Video About the Product
