  ![Editor.md Logo](https://jala.university/wp-content/uploads/2023/09/logo-jala-university-1-1.png)


# Cheatsheet de SDLC, Planificación y Desarrollo de Software

## Tabla de Contenidos

- [Ciclo de Vida del Desarrollo de Software (SDLC)](#ciclo-de-vida-del-desarrollo-de-software-sdlc)
- [Las 4P’s en Planificación de Proyectos de Software](#las-4ps-en-planificaci%C3%B3n-de-proyectos-de-software)
  - [Producto (Qué?)](#producto-qu%C3%A9)
  - [Personas (Quién?)](#personas-qui%C3%A9n)
  - [Proyecto (Cuándo?)](#proyecto-cu%C3%A1ndo)
  - [Proceso (Cómo?)](#proceso-c%C3%B3mo)
- [Metodologías Ágiles](#metodolog%C3%ADas-%C3%A1giles)
- [Requerimientos](#requerimientos)
  - [Requerimientos Funcionales](#requerimientos-funcionales)
  - [Requerimientos No-Funcionales](#requerimientos-no-funcionales)
- [Requerimientos de Dominio](#requerimientos-de-dominio)
  - [Épicas (Epics)](#%C3%A9picas-epics)
  - [Características (Features)](#caracter%C3%ADsticas-features)
  - [Historias de Usuario (User Stories)](#historias-de-usuario-user-stories)
  - [Tareas (Tasks)](#tareas-tasks)
- [Requerimientos de Integración](#requerimientos-de-integraci%C3%B3n)
- [Casos de Uso](#casos-de-uso)
- [Estrategias de Desarrollo](#estrategias-de-desarrollo)
- [Principios Clave](#principios-clave)
  - [SoC (Separation of Concerns)](#soc-separation-of-concerns)


## Ciclo de Vida del Desarrollo de Software (SDLC)

El Ciclo de Vida del Desarrollo de Software (SDLC) es un proceso que guía el desarrollo de software desde la etapa inicial de planificación hasta el despliegue y mantenimiento. Estas son las etapas clave del SDLC:


| Etapa        | Descripción                                        |
|--------------|----------------------------------------------------|
| Planificación | Definición de objetivos y alcance del proyecto.   |
| Análisis     | Comprender los requisitos y restricciones.        |
| Diseño       | Diseñar la arquitectura y componentes del software. |
| Desarrollo   | Implementar el código y funcionalidades.           |
| Prueba       | Verificar y validar el software.                  |
| Despliegue   | Implementación en producción.                     |
| Mantenimiento | Actualizaciones y solución de problemas.           |


Cada una de estas etapas es esencial para garantizar un desarrollo de software exitoso y de alta calidad. El SDLC proporciona una estructura para gestionar proyectos de software de manera efectiva y eficiente.

## Las 4P’s en Planificación de Proyectos de Software

Las 4P’s son un enfoque esencial para la planificación efectiva de proyectos de software. Cada una de las P's se enfoca en un aspecto fundamental de la planificación:

### Producto (Qué?): 

- Definición del software a desarrollar.
- Especificación de los objetivos y requisitos del software.
- Identificación de las características clave del producto.

### Personas (Quién?): 

- Identificación del equipo de desarrollo.
- Reconocimiento de las partes interesadas, como clientes y usuarios.
- Asignación de roles y responsabilidades en el proyecto.

### Proyecto (Cuándo?): 

- Establecimiento de un cronograma de desarrollo.
- Definición de hitos y plazos importantes.
- Planificación de recursos y presupuesto.

### Proceso (Cómo?): 

- Selección de la metodología de desarrollo.
- Detalle del enfoque a utilizar en el proyecto.
- Diseño de los flujos de trabajo y procesos a seguir.

El enfoque en estas 4P’s garantiza una planificación integral que aborda qué se construirá (Producto), quién lo construirá (Personas), cuándo se construirá (Proyecto) y cómo se construirá (Proceso).

Este enfoque sólido en la planificación es fundamental para el éxito de cualquier proyecto de desarrollo de software.


## Metodologías Ágiles

Las metodologías ágiles son enfoques de desarrollo de software que se caracterizan por su flexibilidad, colaboración y enfoque en la entrega de valor al cliente. Algunas de las metodologías ágiles más conocidas son las siguientes:

- **SCRUM:** SCRUM es un framework de desarrollo ágil que se centra en la colaboración, la adaptabilidad y la entrega iterativa de software. En SCRUM, el trabajo se organiza en sprints, que son ciclos de desarrollo de corta duración. El equipo de desarrollo se reúne regularmente para revisar el progreso y ajustar el plan en función de los cambios y las necesidades del cliente.

- **Análisis de Requerimientos:** Antes de iniciar cualquier proyecto de desarrollo de software, es fundamental identificar y comprender las necesidades del usuario. El análisis de requerimientos implica la recopilación y documentación de lo que el software debe lograr. Esto garantiza que el equipo de desarrollo esté alineado con las expectativas del cliente y tenga una guía clara sobre qué construir.

- **Especificaciones de Integración:** Las especificaciones de integración son esenciales para proyectos de software que involucran múltiples componentes o sistemas. Definen cómo se unen estas partes para que funcionen juntas de manera efectiva. Las especificaciones de integración garantizan que todos los componentes del software se comuniquen y cooperen de manera cohesiva.

Las metodologías ágiles, como SCRUM, promueven la colaboración y la comunicación constante entre los miembros del equipo y los interesados, lo que conduce a un desarrollo más eficiente y a la entrega de software que cumple con las necesidades cambiantes del cliente.


## Requerimientos

La definición de requerimientos es un paso crítico en el desarrollo de software, ya que establece las bases para lo que el software debe lograr. Los requerimientos se dividen en dos categorías principales:

- **Requerimientos Funcionales:** Estos requerimientos describen lo que el software debe hacer. Se centran en las funcionalidades y características específicas que el software debe proporcionar. Los requerimientos funcionales son directamente observables por los usuarios y definen el comportamiento del sistema. Ejemplos de requerimientos funcionales incluyen funciones como "crear una cuenta de usuario", "realizar una búsqueda en la base de datos" o "generar un informe de ventas".

- **Requerimientos No-Funcionales:** Estos requerimientos se refieren a restricciones y cualidades del sistema que no están relacionadas directamente con las funciones específicas del software. En su lugar, se centran en aspectos como el rendimiento, la seguridad, la usabilidad y otros atributos que son esenciales para la calidad del software. Ejemplos de requerimientos no funcionales incluyen "el sistema debe ser capaz de manejar 1,000 usuarios concurrentes sin degradación del rendimiento", "los datos del usuario deben estar encriptados" o "el software debe ser compatible con los navegadores web más populares".

La definición y comprensión claras de estos dos tipos de requerimientos son esenciales para guiar el proceso de desarrollo de software y garantizar que el producto final cumpla con las expectativas y estándares de calidad deseados.


## Requerimientos de Dominio

Los requerimientos de dominio se utilizan para comprender y definir qué debe hacer el software desde la perspectiva del usuario y cómo debe funcionar. Estos requerimientos se dividen en diferentes niveles de detalle, incluyendo:

| Épicas (Epics)         | Características (Features)          | Historias de Usuario (User Stories)  | Tareas (Tasks)                        |
|------------------------|-----------------------------------|-----------------------------------|-----------------------------------|
| - Las épicas son historias de alto nivel que describen características o funcionalidades generales que el software debe tener. A menudo, representan objetivos de alto nivel que se dividen en tareas más pequeñas. Las épicas proporcionan una visión general de lo que se planea desarrollar.  | - Las características son requerimientos más específicos que se derivan de las épicas. Cada característica representa una funcionalidad específica que el software debe incluir. Estas características son más detalladas que las épicas y ayudan a definir de manera más concreta lo que se espera del software.  | - Las historias de usuario son casos de uso desde la perspectiva del usuario final. Estas historias describen una funcionalidad específica que un usuario espera del software. Por lo general, siguen el formato "Como [tipo de usuario], quiero [realizar una acción] para [lograr un objetivo]". Las historias de usuario son una herramienta poderosa para comprender las necesidades de los usuarios.  | - Las tareas son requerimientos aún más detallados que las historias de usuario. Representan acciones específicas que deben realizarse para implementar una historia de usuario o una característica. Las tareas son la unidad más pequeña de trabajo y suelen asignarse a miembros del equipo para su ejecución.  |


## Requerimientos de Integración

Los requerimientos de integración son esenciales en proyectos de software que involucran múltiples componentes, sistemas o módulos. Estos requerimientos se centran en definir cómo los diferentes elementos del software trabajarán juntos de manera efectiva. Los aspectos clave de los requerimientos de integración incluyen:

- **Definición de cómo los componentes del software trabajan juntos:** Esto implica describir cómo se comunicarán, compartirán datos y cooperarán los diferentes componentes o módulos del software. Estas especificaciones son cruciales para garantizar la interoperabilidad y la cohesión del sistema en su conjunto.

La comprensión y documentación adecuada de los requerimientos de dominio y de integración son fundamentales para el éxito de un proyecto de desarrollo de software, ya que proporcionan una base sólida para el diseño, la implementación y las pruebas del software.
## Casos de Uso

- Son descripciones de cómo los actores (usuarios u otros sistemas) interactúan con el software, mostrando las acciones y eventos que ocurren en el sistema desde la perspectiva de los usuarios

## Estrategias de Desarrollo

- **GitHub Flow:**Esta estrategia se enfoca en utilizar ramas de características para trabajar en nuevas funcionalidades o correcciones de errores. La clave es la integración continua y la entrega frecuente a la rama principal, lo que facilita la colaboración y la detección temprana de problemas.
- **GitLab Flow:** Similar a GitHub Flow, está diseñado específicamente para proyectos alojados en GitLab. También se centra en ramas de características y en la entrega continua de cambios al repositorio principal.
- **Trunk-Based Development:** En esta estrategia, se trabaja principalmente en una única rama principal, lo que fomenta la integración continua de cambios. El objetivo es mantener el código en un estado siempre desplegable, lo que facilita la entrega continua.

## Principios Clave

- **SoC (Separation of Concerns):**  Este principio se refiere a la separación de diferentes aspectos o preocupaciones en el diseño de software. Al dividir el sistema en componentes o módulos con preocupaciones específicas, se mejora la modularidad y la facilidad de mantenimiento.
