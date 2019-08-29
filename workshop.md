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
- Se explica los aspectos a mejorar, a manos del Product Owner (PO), que en este caso un representante de los intereses del Paciente. 
- Quien entiende y filtra los requerimientos al equipo de desarrollo es el Product Manager (PM), a través de tareas concretas a realizar.

    #### Consignas Tarjeta #1:
    
    **Problemática A**: 
    
    - El horario para dar turnos es de 9 a 13 horas, en promedio concurren 50 pacientes, de los cuales se asignan turnos a 40, quedando 10 pacientes sin turno.
    - Se hace un relevamiento con el usuario y se constata que la carga de datos de un paciente es un proceso largo, tedioso y "error prone"
    - De la experiencia en otras instituciones de salud, se conoce que es posible la validación de un paciente con un scanner y el DNI

    **Objetivo grupo A**: 

    Agilizar la validación de pacientes para que no queden pacientes sin atención

    User Story #1 (Administrativo):

        PUNTAJE MÁXIMO: 15
        
        COMO administrativo
        QUIERO validar pacientes usando un escáner de DNI
        PARA optimizar el tiempo de carga y asignación de turnos
        
        CRITERIOS DE ACEPTACIÓN (tarjeta de puntajes)

        DADA la pantalla "Datos del Paciente" 
        CUANDO un paciente concurre por primera vez
        ENTONCES tener un escanear de DNI
        PUNTAJE: 5

        DADA la pantalla "Datos del Paciente" 
        CUANDO se escanea un DNI
        ENTONCES los datos del paciente se autocompletan
        PUNTAJE: 5

        DADA la pantalla del "Agendas y Turnos"
        CUANDO un paciente concurre con su DNI
        ENTONCES poder validarlo dentro del sistema escaneando su DNI
        PUNTAJE: 5
        ______________________________________________________________________________________________________________________________

    
    **Problemática B**: 
    
    - El horario para dar turnos es de 9 a 13 horas, en promedio concurren 50 pacientes, de los cuales se asignan turnos a 40, quedando 10 pacientes sin turno.
    - Se hace un relevamiento con el usuario y se constata que la carga de datos de un paciente es un proceso largo, tedioso y "error prone"
    - De la experiencia en otras instituciones de salud, se conoce que es posible la validación de un paciente con un scanner y el DNI
            

    **Objetivo grupo B**: 

    Registrar un diagnóstico para que esté disponible en la Historia Clínica digital del paciente

    User Story #2 (Profesional):

        PUNTAJE MÁXIMO: 15
        
        COMO profesional de salud
        QUIERO registrar el diagnóstico de un paciente
        PARA tener esos datos disponibles en la Historia Clínica digital
        
        CRITERIOS DE ACEPTACIÓN

        DADA la pantalla "Prestación" 
        CUANDO se necesita diagnosticar a un paciente
        ENTONCES debe haber un campo de texto sobre el cual escribir el diagnóstico

        DADA la pantalla del "Prestación"
        CUANDO cuando se guarda el diagnóstico de un paciente
        ENTONCES si hay más de un diagnóstico, se debe poder indicar cuál es el diagnóstico principal
        

    1. Armar una interfaz gráfica (UI) con elementos del UI kit. 
    2. Los elementos a elegir están limitados por: 
        - Sólo puede haber un máximo de 2 pantallas
        - 

- Al finalizar el sprint #1 se requiere entregar un prototipo.
- Se evalúa la interfaz y la UX del prototipo
- Al iniciar el sprint #2:
    - Se evalúa, desde una perspectiva agile (retrospectiva o "la retro"):
        1. Lo que se hizo
        2. Los problemas que tuvieron
        3. Qué se va a hacer a continuación

################################################################################################################################

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

    User Story #1 (Administrativo):

        PUNTAJE MÁXIMO: 20
        
        COMO administrativo
        QUIERO registrar el género autopercibido de un paciente
        PARA que el paciente pueda ser llamado por su nombre correctamente en la sala de espera
        
        CRITERIOS DE ACEPTACIÓN (tarjeta de puntajes)

        DADA la pantalla "Datos del Paciente" 
        CUANDO un paciente concurre a la ventanilla
        ENTONCES tener un campo opcional para ingresar el género autopercibido del paciente. Las opciones deben ser "Femenino", "Masculino", "Otro"
        PUNTAJE: 10

        DADA la pantalla "Datos del Paciente" 
        CUANDO un paciente concurre a la ventanilla
        ENTONCES debe haber un campo de texto opcional para ingresar el nombre autopercibido del paciente.
        PUNTAJE: 10

    User Story #2 (Profesional):
        
        COMO profesional de salud
        QUIERO visualizar el género autopercibido el paciente
        PARA que el paciente pueda ser llamado correctamente sin estigmatización
        
        CRITERIOS DE ACEPTACIÓN

        DADA la pantalla "Punte de inicio de Prestaciones" 
        CUANDO se muestre la lista de pacientes en la agenda del profesional
        ENTONCES debe figurar el nombre autopercibido del paciente

        DADA la pantalla del "Prestación"
        CUANDO cuando se visualizan los detalles del paciente
        ENTONCES debe figurar tanto el género como el nombre autopercibido

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

