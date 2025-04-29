<style>
  body {
    font-family: 'Times New Roman', sans-serif;
    text-align: justify;
    font-size: 12px;
    margin-left: 2em;
    margin-right: 2em;
    line-height: 2;
  }
  
  p {
    text-indent: 2em; 
  }

  h1 {
    margin-left: 0; 
  }

  h2 {
    margin-left: 0; 
  }

  h3 {
    margin-left: 2em;
  }

  h4 {
    margin-left: 4em; 
  }
</style>

# UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS

<p align="center">
  <img src="img/UPC_logo_transparente.png"  style="width:500px; height:auto;">
</p>

# APLICACIONES PARA DISPOSITIVOS MÓVILES
## PROFESOR: David Gerardo Quevedo Velasco
## INFORME TB1
## START UP: MovileSource
## PRODUCTO: PSYMED

### INTEGRANTES:
<table>
  <thead>
    <tr>
      <th style="background-color: #333; color: #fff;">Apellidos y Nombres</th>
      <th style="background-color: #333; color: #fff;">Código de Alumno</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Riega Salas, Jose Miguel</td>
      <td>u202211254</td>
    </tr>
    <tr>
      <td>Palomino Hurtado, Juan Francisco</td>
      <td>u202117498</td>
    </tr>
    <tr>
      <td>Galvan Cerron, George Aldo</td>
      <td>u202116055</td>
    </tr>
    <tr>
      <td>Guerrero Vasquez, Jhon Danny</td>
      <td>u202116246</td>
    </tr>
    <tr>
      <td>Iparraguirre Rueda, Cristian Luis</td>
      <td>u202113111</td>
    </tr>
    <tr>
      <td>Reyes Valenzuela, Renato German</td>
      <td>u20221b471</td>
    </tr>
  </tbody>
</table>

--- 

FECHA: NOVIEMBRE 2024

---
# Registro de Versiones del Informe

<table>
  <thead>
    <tr>
      <th style="background-color: #333; color: #fff;">Versión</th>
      <th style="background-color: #333; color: #fff;">Fecha</th>
      <th style="background-color: #333; color: #fff;">Autor</th>
      <th style="background-color: #333; color: #fff;">Descripción de modificación</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Primera Entrega TB1</td>
      <td>28/04/2025</td>
      <td>Todos los integrantes del equipo</td>
      <td>
        En esta primera entrega del proyecto Psymed, se completaron los cuatro primeros capítulos al 100% y la mitad del capítulo 5. El equipo completo colaboró en la definición de la solución propuesta, llevando a cabo un análisis Lean UX y definiendo el segmento objetivo. Se recopilaron todos los requisitos necesarios para desarrollar las herramientas requeridas, incluyendo User Persons, User Stories, Product Backlog e Impact Mapping. Posteriormente, se diseñaron los mockups y prototipos de la página de inicio basándose en la información recabada, y finalmente, se completó la creación de la página de inicio con el apoyo del Sprint Backlog, asegurando así un control efectivo de los progresos realizados. Este trabajo se llevó a cabo utilizando GitHub, siguiendo la metodología Gitflow y aplicando Conventional Commits para mantener el orden y la estructura, empleando los IDEs Rider y Visual Studio Code. Además, se definieron la paleta de colores, tipografía, icono, wireframes y mockups, y se desarrolló la landing page utilizando HTML, CSS, JS y extensiones de apoyo como Bootstrap y LineIcons, implementándola en WebStorm y desplegándola vía GitHub Pages.
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td>Segunda Entrega TP1</td>
      <td></td>
      <td></td>
      <td> 
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td>Tercera Entrega TB2</td>
      <td></td>
      <td></td>
      <td> 
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td>Cuarta Entrega TF1</td>
      <td></td>
      <td></td>
      <td> 
      </td>
    </tr>
  </tbody>
</table>

---
# Project Report Collaboration Insights
Para este proyecto hemos utilizado las herramientas GitHub y Trello para gestionar el progreso grupal.
En Trello hemos organizado las tareas de cada integrante y con ello se puede visualizar el avance de cada asignación.

Para acceder al contenido de la organización en GitHub, haz clic en el siguiente ícono:

<p align="center">
  <a href="https://github.com/orgs/GRUPO-1-MOVILES-2025-1/repositories">
    <img src="img/psymed_logo.svg" style="width:250px; height:auto;">
  </a>
</p>

---

# Contenido
## Tabla de Contenidos
### [Registro de versiones del informe](#registro-de-versiones-del-informe)
### [Project Report Collaboration Insights](#project-report-collaboration-insights)
### [Contenido](#contenido)
### [Student Outcome](#student-outcome-1)

### [Capítulo I: Introducción](/chapter01.md)
- [1.1. Startup Profile](/chapter01.md#11-startup-profile)
  - [1.1.1. Descripción de la Startup](/chapter01.md#111-description-de-la-startup)
  - [1.1.2. Perfiles de integrantes del equipo](/chapter01.md#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](/chapter01.md#12-solution-profile)
  - [1.2.1 Antecedentes y problemática](/chapter01.md#121-antecedentes-y-problematica)
  - [1.2.2 Lean UX Process](/chapter01.md#12-solution-profile)
    - [1.2.2.1. Lean UX Problem Statements](/chapter01.md#1221-lean-ux-problem-statements)
    - [1.2.2.2. Lean UX Assumptions](/chapter01.md#1222-lean-ux-assumptions)
    - [1.2.2.3. Lean UX Hypothesis Statements](/chapter01.md#1223-lean-ux-hypothesis-statements)
    - [1.2.2.4. Lean UX Canvas](/chapter01.md#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](/chapter01.md#13-segmentos-objetivos)

### [Capítulo II: Requirements Elicitation & Analysis](/chapter02.md)
- [2.1. Competidores](/chapter02.md#21-competidores)
    - [2.1.1. Análisis competitivo](/chapter02.md#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](/chapter02.md#212-estrategias-y-tácticas-frente-a-competidores)
- [2.2. Entrevistas](/chapter02.md#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](/chapter02.md#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](/chapter02.md#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](/chapter02.md#223-análisis-de-entrevistas)
- [2.3. Needfinding](/chapter02.md#23-needfinding)
    - [2.3.1. User Personas](/chapter02.md#231-user-persona)
    - [2.3.2. User Task Matrix](/chapter02.md#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](/chapter02.md#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](/chapter02.md#234-emphaty-mapping)
    - [2.3.5. As-is Scenario Mapping](/chapter02.md#235-as-is-scenario-mapping)

### [Capítulo III: Requirements Specification](/chapter03.md)
- [3.1. To-Be Scenario Mapping](/chapter03.md#31-to-be-scenario-mapping)
- [3.2. User Stories](/chapter03.md#32-user-stories)
- [3.3. Impact Mapping](/chapter03.md#33-impact-mapping)
- [3.4. Product Backlog](/chapter03.md#34-product-backlog)

### [Capítulo IV:  Solution Software Design](/chapter04.md)
- [4.1. Strategic-Level Domain-Driven Design](/chapter04.md#41-style-guidelines)
    - [4.1.1. EventStorming](/chapter04.md#411-general-style-guidelines)
      - [4.1.1.1. Candidate Context Discovery](/chapter04.md#412-web-style-guidelines)
      - [4.1.1.2. Domain Message Flows Modeling](/chapter04.md#412-web-style-guidelines)
      - [4.1.1.3. Bounded Context Canvases](/chapter04.md#42-information-architecture)
    - [4.1.2. Context Mapping](/chapter04.md#421-organization-systems)
    - [4.1.3. Software Architecture](/chapter04.md#422-labeling-systems)
      - [4.1.3.1. Software Architecture Context Level Diagrams](/chapter04.md#423-seo-tags-and-meta-tags)
      - [4.1.3.2. Software Architecture Container Level Diagrams](/chapter04.md#424-searching-systems)
      - [4.1.3.3. Software Architecture Deployment Diagrams](/chapter04.md#425-navigation-systems)
- [4.2. Tactical-Level Domain-Driven Design](/chapter04.md#43-landing-page-ui-design)
    - [4.2.X.1. Domain Layer](/chapter04.md#431-landing-page-wireframe)
    - [4.2.X.2. Interface Layer](/chapter04.md#432-landing-page-mock-up)
    - [4.2.X.3. Application Layer](/chapter04.md#44-web-applications-uxui-design)
    - [4.2.X.4. Infrastructure Layer](/chapter04.md#441-web-applications-wireframes)
    - [4.2.X.5. Bounded Context Software Architecture Component Level Diagrams](/chapter04.md#442-web-applications-mock-ups)
    - [4.2.X.6. Bounded Context Software Architecture Code Level Diagrams](/chapter04.md#443-web-applications-user-flow-diagrams)
      - [4.2.X.6.1. Bounded Context Domain Layer Class Diagrams](/chapter04.md) 
      - [4.2.X.6.2. Bounded Context Database Design Diagram](/chapter04.md#45-web-applications-prototyping)

