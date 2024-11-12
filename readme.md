# Reto Pomodoro

La técnica "Pomodoro" es un método efectivo para mejorar la administración del tiempo dedicado a una actividad e incrementar la productividad. Este reto consiste en crear una aplicación de Pomodoro configurable que permita gestionar tareas y guarde un historial completo.

## Requisitos de la Aplicación

### Funcionalidades Principales

- **Campo de texto para tareas**: Permite introducir el nombre de la tarea que se está llevando a cabo.
  - El Pomodoro solo puede iniciarse si se ha definido una tarea.
  - Cada vez que se cambia la tarea, el Pomodoro comienza de cero.
  - La tarea solo es editable si el Pomodoro está detenido.

- **Controles de Pomodoro**: Incluir botones para las siguientes acciones:
  - **Iniciar** el Pomodoro.
  - **Pausar** el Pomodoro.
  - **Detener** el Pomodoro.
  - **Pasar al siguiente ciclo** del Pomodoro.

### Ciclos del Pomodoro

- El Pomodoro mide intervalos formados por **4 bloques de trabajo de 25 minutos** con un descanso de **5 minutos** entre cada bloque.
- Cada tres bloques de descanso de 5 minutos, el cuarto descanso será de **15 minutos** o **30 minutos** (configurable por el usuario).
- La selección del tiempo de descanso extendido (15 o 30 minutos) debe ser persistente.

### Funcionalidades en Segundo Plano

- Si la aplicación está en segundo plano, el Pomodoro debe seguir funcionando o, al menos, mantener el estado actual del temporizador.

### Notificaciones y Alertas

- **Fin de Bloques**: Cada vez que un bloque de trabajo o descanso finalice, el usuario debe ser notificado:
  - Si la aplicación está en primer plano: mostrar una alerta o emitir un sonido.
  - Si la aplicación está en segundo plano: enviar una notificación para indicar el inicio del siguiente bloque de tiempo.

### Historial de Tareas

- Guardar un historial detallado agrupado por día que incluya:
  - **Fecha de inicio y fin** de cada bloque de trabajo y descanso.
  - **Texto de la tarea** realizada.
  - **Tiempo total** invertido en cada tarea, incluyendo tanto trabajo como descansos.
- El historial se guarda cada vez que el Pomodoro es detenido.
- El historial debe estar disponible en una pantalla individual, mostrando el registro más reciente primero.

### Interfaz de Usuario

- La interfaz debe ser estética, clara y con animaciones que mejoren la experiencia de usuario.
- Aprovechar el diseño para facilitar la comprensión del tiempo restante en cada bloque y el estado actual del Pomodoro.

## Resumen de Requisitos

| Requisito             | Descripción                                                                                  |
|-----------------------|----------------------------------------------------------------------------------------------|
| Campo de texto para tarea   | Permite editar la tarea cuando el Pomodoro está detenido                                |
| Controles de Pomodoro       | Iniciar, Pausar, Detener y Pasar al siguiente ciclo                                    |
| Ciclos de Pomodoro    | 4 bloques de 25 min trabajo + descansos de 5 min; cada cuarto descanso de 15 o 30 min       |
| Notificaciones        | Alertas en primer plano y notificaciones en segundo plano al final de cada bloque           |
| Historial de tareas   | Agrupado por día, guarda fecha, tiempo de tarea y descanso, y texto de la tarea             |
| Interfaz de usuario   | Diseño atractivo con animaciones                                                             |

Este reto es una excelente oportunidad para practicar diseño de UI y mejorar la productividad con la técnica Pomodoro.

