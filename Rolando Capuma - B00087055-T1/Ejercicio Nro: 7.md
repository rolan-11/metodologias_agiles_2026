# Ejercicio Nro: 7

## Enunciado
Dar un ejemplo de cada uno de los cuellos de botellas analizados anteriormente en el paper de Brooks.

## Resolución
En su paper "No Silver Bullet", Fred Brooks plantea que el desarrollo de software tiene dificultades esenciales (los verdaderos cuellos de botella) que no se pueden resolver simplemente con mejores herramientas o lenguajes más rápidos. A continuación, un ejemplo práctico de cada una de estas dificultades:

* **Complejidad (Complexity):** A diferencia de la fabricacion en serie, en el software ninguna parte de codigo es idéntica a otra; si lo fuera, simplemente se reutilizaría. 
  * *Ejemplo:* Un sistema de ventas básico es facil, pero si el negocio crece y hay que agregarle control de stock por talle y color, promociones bancarias específicas por día, y envíos a distintas regiones, las combinaciones posibles en la lógica del código explotan y se vuelve súper complejo de testear y mantener
* **Conformidad (Conformity):** El software es el que siempre tiene que adaptarse a las reglas del mundo real (instituciones, personas, leyes), que muchas veces son arbitrarias, ilógicas o anticuadas.
  * *Ejemplo:* Desarrollar un sistema de facturación ultra moderno y rápido, pero tener que hacer malabares en el código para que se comunique y conforme a los estándares viejos y estructurados de la AFIP simplemente porque es la regla impuesta
* **Mutabilidad / Cambiabilidad (Changeability):** Como el software no es algo físico (como un puente o un edificio), la gente percibe que es infinitamente moldeable y pide cambios constantemente.
  * *Ejemplo:* Un cliente te pide agregale un botoncito nomás" en la pantalla para cruzar datos históricos, pensando que es una pavada visual de cinco minutos, pero en realidad ese cambio te obliga a reestructurar y migrar varias tablas enteras en la base de datos SQL
* **Invisibilidad (Invisibility):** El software no se puede visualizar de forma completa; no tiene una representación espacial que nuestra mente pueda entender de un vistazo (por más diagramas UML que hagamos)
  * *Ejemplo:* Si remodelás la fachada o el interior de un local comercial, el cliente ve el avance de la obra día a día y lo entiende. En el software, el equipo puede estar semanas refactorizando el código o mejorando la seguridad de la infraestructura, y el cliente te dice "Que estuvieron haciendo? Si la pantalla se ve igual que antes", porque el progreso técnico puro es invisible para ellos.
