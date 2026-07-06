# Ejercicios Nro: 18 y 19

## Resolución Integrada: Simulación de Scrum para App de Logística

A continuación se presentan los prompts simulando las diferentes etapas de Scrum, integrando los requerimientos trabajados en clase y el equipo de Bots asignado para el proyecto.

### Equipo de Trabajo (Ejercicio 19)
* **Scrum Master:** Pepe (Bot ScrumMaster)
* **Product Owner / Representante del Cliente:** Pepa (Bot Product Owner)
* **Development Team:** Pupo (Bot Desarrollador) y un Bot Diseñador.

---

### Secuencia de Prompts (Ejercicio 18)

**1. Prompt 1: Definición del Product Backlog**
* **Descripción de la actividad:** Convertir las necesidades del cliente en historias de usuario claras para conformar la lista de tareas del proyecto.
* **Entrada:** El cliente ha proporcionado los siguientes requerimientos iniciales: Registro y autenticación de usuarios, Crear envíos, Seguimiento de envíos, Métodos de pago y Reportes.
* **Salida:** Product Backlog inicial con las siguientes historias de usuario prioritarias:
  1. *Como usuario*, quiero registrarme e iniciar sesión para acceder a mi panel.
  2. *Como usuario*, quiero crear nuevos envíos y realizar su seguimiento en tiempo real.
  3. *Como usuario*, quiero contar con múltiples métodos de pago para abonar mis servicios.
  4. *Como usuario*, quiero generar reportes para ver el estado histórico de mis pedidos.

**2. Prompt 2: Planificación del Sprint (Sprint Planning)**
* **Descripción de la actividad:** Seleccionar qué elementos del Backlog se harán en este ciclo y asignar los responsables.
* **Entrada:** Product Backlog.
* **Salida:** Plan del Sprint (con una duración estimada de 2 a 3 semanas) con las siguientes tareas y responsables:
  * **Tarea 1:** Diseño de la interfaz para el registro e inicio de sesión. *(Responsable: Bot Diseñador)*
  * **Tarea 2:** Implementar la creación y el seguimiento de envíos. *(Responsable: Pupo - Bot Desarrollador)*
  * **Tarea 3:** Diseñar e implementar la generación de reportes de estado del pedido. *(Responsable: Pupo - Bot Desarrollador)*
  * **Tarea 4:** Implementar y agregar la pasarela de métodos de pago. *(Responsable: Pupo - Bot Desarrollador)*

**3. Prompt 3: Ejecución del Sprint**
* **Descripción de la actividad:** El equipo desarrolla las tareas planificadas asegurando su correcto funcionamiento.
* **Entrada:** Plan del Sprint.
* **Salida:** Incremento de software funcional. Se llevan a cabo los requerimientos organizados en la etapa de planificación y se entrega el código donde la autenticación, los envíos, pagos y reportes funcionan correctamente.

**4. Prompt 4: Revisión del Sprint (Sprint Review)**
* **Descripción de la actividad:** Demostrar el trabajo terminado al cliente para recibir sus comentarios.
* **Entrada:** Incremento de software funcional.
* **Salida:** Retroalimentación del cliente. Se presenta el proyecto a **Pepa (Product Owner)** buscando feedback sobre las funcionalidades del sistema, analizando qué le falta al programa y qué cambiaría para cumplir exactamente con sus expectativas.

**5. Prompt 5: Retrospectiva del Sprint**
* **Descripción de la actividad:** El equipo analiza cómo fue su forma de trabajar para mejorar en el próximo ciclo guiados por el Scrum Master.
* **Entrada:** Retroalimentación del cliente y experiencia del equipo durante el desarrollo.
* **Salida:** Plan de mejora para el siguiente Sprint. **Pepe (Scrum Master)** establece las siguientes acciones:
  * Realizar un testeo de funcionalidad de forma más temprana luego de cada implementación agregada.
  * Notificar al cliente (Pepa) de forma continua y permitirle revisar los cambios en entornos de prueba para ver si cumplen con lo solicitado antes de la Review final.
