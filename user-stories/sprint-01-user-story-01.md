User Story #1 (Administrativo):

    PUNTAJE MÁXIMO: 35
    
    COMO administrativo
    QUIERO validar pacientes usando un escáner de DNI
    PARA optimizar el tiempo de carga y asignación de turnos
    
    CRITERIOS DE ACEPTACIÓN (tarjeta de puntajes)

    DADA el formulario existente "Datos del Paciente" 
    CUANDO se escanea un DNI
    ENTONCES los datos del paciente se autocompletan
    PUNTAJE: 15

    DADA la pantalla del "Agendas y Turnos"
    CUANDO un paciente concurre con **sin su DNI**
    ENTONCES poder validarlo dentro del sistema con un formulario
    PUNTAJE: 10

    DADA la pantalla del "Agendas y Turnos"
    CUANDO un paciente concurre con su DNI
    ENTONCES poder validarlo dentro del sistema escaneando su DNI
    PUNTAJE: 10

[Volver](/workshop.md)