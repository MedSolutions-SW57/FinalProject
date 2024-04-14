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

## 5.4 Video About the Product
