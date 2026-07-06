# Ejercicio Nro: 13

## Enunciado
*(Preguntas sobre Extreme Programming - XP)*

## Resolución

**1. ¿Qué es Extreme Programming (XP) y cuál es su objetivo principal?**
Es una metodología ágil centrada fuertemente en la ingeniería de software y la excelencia técnica. Su objetivo principal es mejorar la calidad del software y la capacidad de respuesta a los requisitos cambiantes del cliente, llevando las "buenas prácticas" de programación al extremo.

**2. ¿Cuáles son los cinco valores principales de XP?**
* **Comunicación:** Fomentar el diálogo constante (cara a cara) entre el equipo y el cliente
* **Simplicidad:** Hacer la solución más simple que funcione hoy, sin sobrecomplicar pensando en "lo que podría pasar" en el futuro
* **Feedback (Retroalimentación):** Obtener respuestas rápidas sobre el código (mediante pruebas) y sobre el producto (mediante el cliente) para corregir el rumbo
* **Coraje:** Tener la valentía para refactorizar código, tirar lo que no sirve y decir la verdad sobre los tiempos de entrega
* **Respeto:** Valorar el trabajo de los compañeros y no romper la compilación del equipo

**3. ¿Por qué XP considera que las pruebas son un elemento fundamental?**
Porque las pruebas son la "red de seguridad" del programador. En XP el código cambia todo el tempo; si no tenés pruebas automatizadas que te avisen si rompiste algo, el miedo a modificar el código paraliza el proyecto. Con pruebas, podés mejorar el sistema constantemente con total confianza.

**4. ¿Qué es Test Driven Development (TDD) y cómo se relaciona con XP?**
El Desarrollo Guiado por Pruebas (TDD) es la práctica de escribir la prueba (el test) *antes* de escribir el codigo de produccion. Es un pilar fundamental de XP porque asegura que todo el código tenga un propósito, esté cubierto por pruebas desde el minuto cero y empuja al programador a hacer diseños más simples y modulares.

**5. Pair Programming: ¿En qué consiste? (2 ventajas y 1 dificultad)**
Consiste en que dos programadores trabajen juntos en la misma computadora (uno escribe el código y el otro revisa la logica y piensa estratégicamente)
* *Ventajas:* El código sale con muchos menos errores (bugs) y el conocimiento del proyecto se comparte naturalmente entre el equipo
* *Dificultad:* Puede ser mentalmente agotador y generar roces si hay choque de personalidades o si uno no deja participar al otro

**6. Historias de usuario vs. Especificación extensa**
Las historias de usuario son descripciones cortas de una funcionalidad escritas desde la perspectiva de quien lo va a usar. Se prefieren en XP porque una especificación extensa es estatica y aburrida; en cambio, una historia de usuario es "una promesa de una conversación". Fomentan que el desarrollador hable con el cliente para entender la necesidad real en el momento en que se va a programar.

**7. Continuous Integration en XP y sus beneficios**
La Integración Continua significa que los desarrolladores suben y fusionan su código al repositorio principal (ej. la rama main en GitHub) varias veces al día. El gran beneficio es que evita el "infierno de la integración" (cuando todos quieren unir su código al final del mes y nada funciona). Al integrar de a pedacitos, los conflictos se resuelven fácil y rápido.

**8. Concepto de Weekly Cycle**
El "Ciclo Semanal" significa que el trabajo se planifica y ejecuta en bloques de una semana. A principio de semana el equipo se reúne con el cliente, eligen qué historias de usuario se van a hacer y, al final de la semana, se entrega software funcionando y testeado. Marca el ritmo del proyecto.

**9. Fijar tiempo, costo y calidad, y negociar el alcance (Ejemplo)**
Esta idea significa que no podés estirar las fechas ni bajar la calidad del código, entonces lo único flexible es la cantidad de funcionalidades
* *Ejemplo:* Tenemos 1 mes y un presupuesto fijo para armar un dashboard de ventas para un local de ropa, y el código tiene que ser excelente (sin bugs). Si vemos que no llegamos, no retrasamos la entrega ni programamos apurados para hacer todo a medias. Lo que hacemos es negociar el alcance: entregamos el panel con el ranking de vendedores e inventario principal, y dejamos la funcionalidad de "predicción de ventas a futuro" para más adelante. Lo que se entrega, funciona perfecto.

**10. Tres prácticas de XP en un proyecto real**
* **Integración Continua (CI):** En un proyecto grupal de la facultad armado en .NET, usar herramientas como GitHub para que cada vez que un compañero hace un "push", el sistema verifique automáticamente si el proyecto compila antes de mezclarlo con el trabajo de los demás
* **Pair Programming:** Al momento de armar consultas SQL muy complejas (con muchos JOINs y agrupaciones), sentarse de a dos: mientras uno tipea, el otro va revisando la estructura de las tablas para no meter la pata y optimizar la consulta
* **Cliente In Situ:** Si estamos desarrollando un sistema de facturación o control de stock para un negocio, mantener contacto constante con la persona que atiende la caja para mostrarle avances semanales y que nos diga si los botones o la interfaz realmente le resultan cómodos en el uso diario.
