# "METODOLOGÍAS ÁGILES EN EL DISEÑO DE INTERFACES" ~ Workshop

## Guión Literario 

### Contexto y problemáticas:
En el Hospital "Las Yungas" de complejidad 9, se formó un grupo interdisciplinario de personal de salud y representantes de los intereses de los pacientes (el **Product Backlog**), lo cual es impulsado por el (**Product Owner**) para buscar soluciones a las problemáticas relacionadas a la atención primaria en la institución. El **Product Owner** es quien se ocupa de organizar la lista de requerimientos, mejoras y correcciones que harán falta realizar.
La institución dispone de un sistema informático de salud propio, llamado "Salud Ágil" con licencia de software libre, y varios módulos en producción. El mismo es desarrollado y mantenido por un **Equipo de desarrollo**, el cual se ocupa de incorporar mejoras, corregir errores (bugs) y llevar adelante el mantenimiento de la infraestructura de servidores, entre otras tareas. Dentro de este Equipo hay recursos dedicados al diseño y la implementación de interfaces gráficas (UI) y la mejora de la experiencia del usuario (UX).

### Se determinó que tienen prioridad las siguientes problemáticas:
1. El horario para dar turnos es de 9 a 13 horas, concurren casi 50 pacientes por día, a los cuales se asignan turnos en orden de llagada, quedando alrededor de 10 pacientes sin turno por día (promedio 40 pacientes atendidos).
2. Aunque se dispone de computadoras y un sistema avanzado para planificación de Agendas de turnos, actualmente la institución carece de un sistema informático para resguardar historias clínicas, y las mismas se registran y almacenan en papel.

### Se hizo un análisis de la problemática, y se realizó el siguiente relevamiento:
1. El equipo de salud administrativo dispone de un sistema informático en ventanilla para validar pacientes, pero no dispone de escáneres de DNI para agilizar el proceso. 
2. El equipo de salud médico dispone de un sistema informático para gestionar sus agendas, pero el mismo no posee un módulo para registar diagnósticos de pacientes. 

### De este relevamiento se realizaron las siguientes acciones:
1. Se decidió aplicar SCRUM, como metodología ágil de trabajo.
2. El hospital dispuso la compra de escáneres de los códigos presentes en los DNI tarjeta (símil código QR) y quedaron instalados tanto en las ventanillas de pacientes como en los consultorios de los profesionales médicos.
3. Para este fin se convocó al sector de Tecnologías de la Información del hospital (**Equipo de desarrollo**).
4. Se requirió al equipo de Tecnologías de la Información, el desarrollo de un módulo para validación de pacientes, con el fin de registrarlos en el sistema y así poder vincularlos con los turnos y la historia clínica digital. 