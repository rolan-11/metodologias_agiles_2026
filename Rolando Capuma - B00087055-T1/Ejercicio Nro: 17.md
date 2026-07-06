# Ejercicio Nro: 17

## Enunciado
Estimar el tamaño, duración y costo de un proyecto de aplicación web de finanzas personales utilizando el método COSMIC y puntos de función.

## Resolución

### Análisis y Tamaño Funcional (X)
Para estimar el tamaño del proyecto, primero desglosamos los requisitos y clasificamos cada interacción en categorías de complejidad: Pequeña (4 PFC), Mediana (5 PFC) y Grande (9 PFC). 

Analizando el módulo de **Cuentas bancarias**, encontramos interacciones sencillas como visualizar el saldo o descargar el historial, las cuales consideramos pequeñas (4 PFC cada una). Sin embargo, la creación de cuentas y las transferencias internas tienen una lógica de validación mayor, por lo que las consideramos medianas (5 PFC cada una). 

Pasando a la **Gestión de ingresos, gastos y deudas**, tareas como categorizar, crear o editar registros oscilan entre pequeñas y medianas (entre 4 y 5 PFC). La complejidad real del sistema (las interacciones Grandes) radica en la visualización dinámica de gráficos de reportes y en el motor del calendario para hacer simulaciones de pago de deudas. A estas dos grandes funcionalidades les asignamos 9 PFC a cada una.

Sumando todas estas interacciones, llegamos a la conclusión de que el tamaño funcional total del proyecto es de **X = 60 Puntos de Función COSMIC (PFC)**.

### Costos, Tiempos y Equipo (Y, Z, W)
Teniendo en cuenta los valores de mercado actuales en nuestra región para el desarrollo de plataformas web financieras, el costo por punto de función (CPFC) se estima en **Y = 50 USD**. 

Para llevar a cabo el trabajo, proponemos un equipo de desarrollo de **Z = 3 personas** (conformado por un especialista Frontend, un Backend y un analista QA). En función de la experiencia del equipo y la eficiencia del marco de trabajo ágil, calculamos que pueden desarrollar un volumen de **W = 30 PFC por mes**.

### Resultados Finales (A y B)
Con las variables anteriores definidas, podemos establecer el cronograma y el presupuesto final:

* **Duración del proyecto:** Dividiendo el tamaño total (60 PFC) por la capacidad mensual del equipo (30 PFC), la duración del proyecto se estima en **A = 2 meses**.
* **Costo del proyecto:** Multiplicando el total de puntos de función (60 PFC) por el costo unitario de cada punto (50 USD), el costo total estimado del proyecto será de **B = 3000 USD**.
