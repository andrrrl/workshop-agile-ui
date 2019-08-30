# Workshop UI/UX CAIS ==> "METODOLOGÍAS ÁGILES EN EL DISEÑO DE INTERFACES"
La actividad tiene un enfoque específico enmarcado por lo que es el diseño de las interfaces y la experiencia de usuario en el marco de un ciclo de las metodologías agile (SCRUM).

## Elementos de UI kit (visible para todos):
- Botón "Aceptar" x 10
- Botón "Cancelar" x 10
- Botón "Ver detalle" x 4
- Buscador de paciente (campo de texto + lupita)
- Panel de detalles de paciente (con foto)
- Panel de detalles de paciente (sin foto)
- Campo de texto para diagnóstico
- Panel con datos de la sesión de usuario
- Buscador de diagnósticos
- Algo como molécula RUP? (registrar tensión arterial o campo libre?)
- Datepicker?
- Checkboxes
- Modal alerta
- Panel lateral
- Pestañas
- Números secuencia


## Contexto Agile:
- Los impratidores (nosotros) 
- Intro de SCRUM, agile, concepto de Cliente, PO, scrum master, equipo de desarrollo.
- Repaso por arriba de Sprint, daily, retro.
- Proponer el rol de quien lleve adelante tareas de UI/UX dentro del equipo.

## Inicio de actividades
- Se explica que esta actividad consta de 2 ciclos (o sprints)

## Inicio Sprint #1
- Se entrega a los equipos la tarjeta "Requerimientos spint #1"
- Se explica los aspectos a mejorar, a manos del Product Owner (PO), que en este caso un representante de los intereses del Paciente y de las mejoras de la institución.
- Quien entiende y filtra los requerimientos al equipo de desarrollo es el Product Manager (PM), a través de tareas concretas a realizar.

    #### Consignas Tarjeta #1:
    
    **Problemática A**: 
    
    - El horario para dar turnos es de 9 a 13 horas, en promedio concurren 50 pacientes, de los cuales se asignan turnos a 40, quedando 10 pacientes sin turno.
    - Se hace un relevamiento con el usuario y se constata que la carga de datos de un paciente es un proceso largo, tedioso y "error prone"
    - De la experiencia en otras instituciones de salud, se conoce que es posible la validación de un paciente con un scanner y el DNI

    **Objetivo grupo A**: 

    - Agilizar la validación de pacientes para que no queden pacientes sin atención
    - Para cada tarea o conjunto de tareas de UI/UX, antes de poner "manos a la obra" se requiere analizar, idear, planificar, y refinar las ideas. Para ello se provee de material didáctico (hojas y marcadores, post-its)
    - [Sprint 1, User Story  1](user-stories/sprint-01-user-story-01.md)

    
    **Problemática B**: 
    
    - El horario para dar turnos es de 9 a 13 horas, en promedio concurren 50 pacientes, de los cuales se asignan turnos a 40, quedando 10 pacientes sin turno.
    - Se hace un relevamiento con el usuario y se constata que la carga de datos de un paciente es un proceso largo, tedioso y "error prone"
    - De la experiencia en otras instituciones de salud, se conoce que es posible la validación de un paciente con un scanner y el DNI
            

    **Objetivo grupo B**: 

    - Registrar un diagnóstico para que esté disponible en la Historia Clínica digital del paciente
    - [Sprint 1, User Story 2](./user-stories/sprint-01-user-story-02.md)
    
        
    **Planificación de Tareas:**
    1. Diseñar una interfaz gráfica (UI) con elementos del UI kit. 
    2. Idear un prototipo "interactivo navegable" que permita visualizar las acciones pedidas en las tareas (UX)


- Al finalizar el sprint #1 se requiere entregar un prototipo.
- Se evalúa la interfaz y la UX del prototipo
- Al iniciar el sprint #2:
    - Se evalúa, desde una perspectiva agile (retrospectiva o "la retro"):
        1. Lo que se hizo
        2. Los problemas que tuvieron
        3. Qué se va a hacer a continuación


## Inicio Sprint #2
- Se entrega a los equipos la tarjeta "Requerimientos spint #2"

    #### Consignas Tarjeta #2:
    Se explican los nuevos requerimientos que bajan desde el PO. 
    - Problemática: Hay quejas de pacientes y comunidades ya que hay pacientes con género autopercibido mujer que son llamados con el nombre anterior, de hombre; y viceversa.

    - Durante el sprint #2: 
    - Se realizan correcciones sobre lo evaluado desde UI/UX
    - Se incorporan cambios, a través de requerimientos nuevos (tarjeta "Requerimientos sprint #2")
    - Se realiza una tarea no planificada (tarjeta "?")

    - Soluciones particulares, User Stories:

    **Objetivo grupo A**: 

    - [Sprint 2, User Story 1](./user-stories/sprint-02-user-story-01.md)

    **Objetivo grupo B**: 

    - [Sprint 2, User Story 2](./user-stories/sprint-02-user-story-01.md)

- Al finalizar el sprint #2 se requiere entregar el producto final.
- Se evalúa, desde una perspectiva agile (retrospectiva o "la retro"):
    1. Lo que se hizo
    2. Los problemas que tuvieron
    3. Qué se va a hacer a continuación

## Trampas lúdicas (tarjetas ocultas para todos):

### 1. Buscador de paciente + scanner de DNI:
    Si se plantea una UI con scanner de DNI pero sin buscador por DNI, la trampa es llevar un paciente que olvidó su DNI.
    La trampa es

### 2. Registros médicos con HC visible:
    Si se registran datos médicos sin poder consultar la historia clínica del paciente, se hace notar que los profesionales en general prefieren poder consultar la historia clínica mientras registran daton. La trampa funciona si algún grupo usara tabs en lugar de paneles paralelos. 

### 3. Género autopercibido:
    

### 4. 3 botones ==> 1 dropdown

