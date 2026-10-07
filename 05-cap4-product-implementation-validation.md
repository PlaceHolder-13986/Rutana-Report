<div style="page-break-before: always;"></div>

# Capítulo IV: Product Implementation & Validation

# 4. Product Implementation & Validation

## 4.1. Software Configuration Management

### 4.1.1 Software Development Environment Configuration
|Actividad|Herramientas/Guía|Propósito| Tipo de acceso /Ruta |
|---------|-----------------|----------|--------------------|
|Gestión de proyecto|Trello|Organizar y dar seguimiento a las tareas asignadas|[Trello][1]|
|Gestión de requerimientos|Gherkin Conventions|Definir criterios de aceptación y validación para los user stories|[Guía Gherkin][2]|
|Producto UI/UX|Figma|Diseño de interfaces (wireframes y mockups) y prototipos|[Figma][3]|
|Landing Page|Visual Studio Code|Edición y desarrollo del código de las pantallas|[VS Code][4]|
|Control de versiones|Git|Gestión de versiones del código de la Landing Page, FrontEnd y BackEnd|[Git][5]|
|Event Storming|Miro|Colaboración y modelado de los procesos involucrados en los Bounded Context|[Miro][7]|
|Diagramas|PlantUML|Generación de diagramas UML requeridos de la aplicación|[PlantUML][8]|
    
### 4.1.2. Source Code Management

Para el manejo del codigo fuente de Rutana se organiza en repositorios independientes que facilita la gestión, revisión y el despliegue de los diferentes artefactos del proyecto.

|     Artefacto     |     URL del Repositorio  |   
|:---: |:---: | 
| Proyect Report  | [Report][9] |
| Landing Page  | [LandingPage][10] |
| FrontEnd Web Application  | [FrontEnd][11] |
| BackEnd Web Services  | [Backend][12] |

##### GitFlow WorFlow

Se implemento GitFlow cómo flujo de trabajo para organizar el desarrollo de los artefactos por funcionalidades, mantener una separación del codigo para evitar errores y mantener ramas de desarrollos especificas para cada módulo o bounded context

###### Ramas principales

1.  main: Rama pincipal para versiones estables y desplegables de los artefactos
2.  develop: Rama de integración utilizada para consolidar las funcionalidades o cambios previos a la versión final del producto

###### Ramas de soporte

1.  feature/*:  Rama creada a partir del develop para poder implementar nuevas funcionalidades.

Convención: `feature/<nombre-corto-descriptivo>`
Ejemplo: `feature/chapter 1`

2.  docs/*: Ramas creadas para los cambios relacionados a la documentación del proyecto.

Convención: ` docs/<parte-del-documento>`  
Ejemplo: `docs/presentation`

3.  fix/*: Ramas utilizadas para corregir errores criticos en los artefactos.

Convención:  `hotfix/<descripción-corta>`
Ejemplo: `hotfix/fix-item-validation`

##### Semantic Versioning

Se aplica Semantic Versioning 2.0.0, con el formato:

- **MAJOR**: Cambios incompatibles con las versiones anteriores del artefacto.
- **MINOR**: Nuevas funcionalidades compatibles con versiones anteriores del artefacto.
- **PATCH**: Correcciones menores y ajustes sin afectar funcionalidades del artefacto.

Ejemplo de versión: `v1.3.2`

##### Conventional Commits

La organización utilizó la especificación de los Conventional Commits para mantener un orden y claridad en los mensajes de cada commit realizado por los integrantes. En este caso la estructura general de cada commit seria la siguiente: ` tipo(enfoque opcional): <descripción> `

Ejemplos de los commits utilizados

-  **chore: setup initial folder structure and empty markdown files**
-  **docs(chap-5): added headers for Chapter 5**
-  **fix(chap 1-2): fix merging problems for Chapter 1 and 2**


### 4.1.3. Source Code Style Guide & Conventions





### 4.1.4. Software Deployment Configuration


## 4.2. Landing Page & Mobile Application Implementation

### 4.2.1. Sprint 1

#### 4.2.1.1. Sprint Planning 1

A través de una reunión en la plataforma Discord, se planteó el inicio del Sprint 1. Durante la sesión se discutieron los objetivos principales, el cronograma de trabajo y la distribución de tareas para el desarrollo de la presencia digital de la startup.

| Sprint #                         | Sprint 1                                                                                                                                                                                          |
|----------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Sprint Planning Background**   |                                                                                                                                                                                                   |
| Date                             | 2026-10-05                                                                                                                                                                                        |
| Time                             | 09:30 pm (GMT-5)                                                                                                                                                                                  |
| Location                         | Modalidad remota mediante la plataforma Discord                                                                                                                                                   |
| Prepared By                      | Howard Robles, Guillermo Arturo                                                                                                                                                                   |
| Attendees (to planning meeting)  | Costa Morales, Christofer William <br /> Howard Robles, Guillermo Arturo <br /> PHuaman Gallardo, Bruno Aldair <br /> Miraval Pomalaya, Rodrigo Jesus <br /> Ramirez Cabrera, Kenyi Efrain <br /> |
| Sprint n-1 Review Summary        | No hubo sprint anterior                                                                                                                                                                           |
| Sprint n-1 Retrospective Summary | No hubo sprint anterior                                                                                                                                                                           |
| **Sprint Goal & User Stories**   |                                                                                                                                                                                                   |
| Sprint 1 Goal                    | N                                                                                                                                                                                                 |
| Sprint 1 Velocity                | 1                                                                                                                                                                                                 |
| Sum of Story Points              | 1                                                                                                                                                                                                 |


#### 4.2.1.2. Aspect Leaders and Collaborators

Durante el Sprint 1, se ha consolidado la integración final de los módulos principales del frontend y backend de Rutana.

Con el fin de mantener una coordinación efectiva y una comunicación fluida entre los integrantes del equipo, se estructuró la matriz de liderazgo y colaboración (LACX), donde se asignó un líder (L) encargado de cada funcionalidad y colaboradores (C) que brindan apoyo en su implementación.

| Team Member (Last Name, First Name) | GitHub Username       | 
|:------------------------------------|:----------------------|
| Costa Morales, Christofer William   | miniChorri            | 
| Howard Robles, Guillermo Arturo     | GuillermoPromac       | 
| Huaman Gallardo, Bruno Aldair       | BrunoHG10             | 
| Miraval Pomalaya, Rodrigo Jesus     | RodMiraval            | 
| Ramirez Cabrera, Kenyi Efrain       | Kenyi15upc            | 


#### 4.2.1.3. Sprint Backlog 1

#### 4.2.1.4. Development Evidence for Sprint Review

#### 4.2.1.5. Testing Suite Evidence for Sprint Review

#### 4.2.1.6. Execution Evidence for Sprint Review

#### 4.2.1.7. Services Documentation Evidence for Sprint Review

#### 4.2.1.8. Software Deployment Evidence for Sprint Review

#### 4.2.1.9. Team Collaboration Insights during Sprint

### 4.2.1. Sprint n

#### 4.2.1.1. Sprint Planning n

#### 4.2.1.2. Aspect Leaders and Collaborators

#### 4.2.1.3. Sprint Backlog n

#### 4.2.1.4. Development Evidence for Sprint Review

#### 4.2.1.5. Testing Suite Evidence for Sprint Review

#### 4.2.1.6. Execution Evidence for Sprint Review

#### 4.2.1.7. Services Documentation Evidence for Sprint Review

#### 4.2.1.8. Software Deployment Evidence for Sprint Review

#### 4.2.1.9. Team Collaboration Insights during Sprint




[1]: https://trello.com "Trello"
[2]: https://cucumber.io/docs/gherkin/ "Guía Gherkin"
[3]: https://figma.com "Figma"
[4]: https://code.visualstudio.com "VS Code"
[5]: https://git-scm.com "Git"
[6]: https://pages.github.com "GitHub Pages"
[7]: https://miro.com "Miro"
[8]: https://plantuml.com "PlantUML"

[kotlin-android]: https://developer.android.com/kotlin/style-guide
[kotlin]: https://kotlinlang.org/docs/coding-conventions.html
[compose]: https://github.com/androidx/androidx/blob/androidx-main/compose/docs/compose-api-guidelines.md
[material]: https://m3.material.io/
[android-arch]: https://developer.android.com/topic/architecture
[app-quality]: https://developer.android.com/docs/quality-guidelines/core-app-quality
[sqlite]: https://www.sqlite.org/lang.html
[room]: https://developer.android.com/training/data-storage/room
[retrofit]: https://square.github.io/retrofit/
[coil]: https://coil-kt.github.io/coil/compose/
[gherkin]: https://cucumber.io/docs/gherkin/reference/
