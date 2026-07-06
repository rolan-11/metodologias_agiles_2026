# Ejercicio Nro: 5

## Enunciado
Proponga cinco elementos que ayuden en el desarrollo de software referido a la propiedad de flexibilidad que se requiere
Ejemplo:
- Diseño para el cambio
- Ocultamiento de la Información
- Herramientas de especificación
- Etc.

## Resolución
Para lograr que un software sea verdaderamente flexible y se pueda adaptar a los cambios sin que sea un dolor de cabeza, propongo estos cinco elementos:

1. **Arquitectura Modular (Modularidad):** Dividir el sistema en modulos o bloques independientes. Si el día de mañana hay que cambiar como funciona el modulo de facturación, se toca solo esa parte sin afectar a la base de datos o a la interfaz de usuario
2. **Uso de Patrones de Diseño:** Aplicar soluciones estructuradas que ya están probadas (como el patrón MVC). Esto hace que el código esté estandarizado y sea mucho mas fácil de entender y modificar si se suma otro desarrollador al proyecto
3. **Control de Versiones (Git/GitHub):** Es fundamental para la flexibilidad. Nos permite crear ramas (branches) para probar ideas nuevas o hacer cambios grandes con la tranquilidad de que, si algo sale mal, podemos volver a la versión anterior sin perder el trabajo
4. **Desarrollo Iterativo e Incremental:** Trabajar con entregas cortas y funcionales en lugar de hacer todo de una vez. Si el cliente cambia de opinión sobre los requisitos a mitad del proyecto, es mucho más fácil dar un volantazo y adaptarse en la siguiente iteración
5. **Pruebas Automatizadas (Testing):** Tener procesos que prueben el código automáticamente nos da la libertad de hacer modificaciones profundas (refactorizar). Si algún cambio "rompe" otra parte del sistema, el test nos avisa al instante, permitiéndonos ser flexibles sin miedo a arruinar todo el programa.
