# Ejercicio Nro: 16

## Enunciado
Utilizar el método Delphi para llegar a un consenso sobre la tecnologia y la arquitectura más adecuadas para el desarrollo de una billetera virtual segura, escalable y confiable

## Resolución
A continuación, se detalla la simulación paso a paso del método Delphi para este proyecto:

### 1. Definición del problema
* **Objetivos y requisitos:** Diseñar una billetera virtual transaccional que garantice el resguardo de los fondos y datos de los usuarios.
* **Factores clave:** Se establecen como prioridad la seguridad criptográfica, la escalabilidad para soportar picos de usuarios, la confiabilidad del sistema (uptime), la facilidad de uso y el costo de mantenimiento de la infraestructura.

### 2. Selección del panel de expertos
* Se identificó y reclutó a un grupo de 5 especialistas independientes y sin conflictos de intereses.
* **Composición para garantizar diversidad:** Dos ingenieros expertos en tecnología blockchain, un auditor de ciberseguridad, un arquitecto de software Cloud y un desarrollador líder especialista en bases de datos.

### 3. Elaboración del cuestionario
* Se diseñó una encuesta estructurada para evaluar distintas opciones tecnológicas en funcion de los factores clave definidos.
* **Contenido:** Se incluyeron preguntas tipo Likert y preguntas abiertas para debatir: Arquitectura monolítica vs. Microservicios, Bases de datos SQL vs. NoSQL, y el uso de redes Blockchain públicas vs. privadas.

### 4. Aplicación del método Delphi
* **Ronda 1:** Se distribuyo el cuestionario de forma anonima y se analizaron las respuestas estadísticamente. Hubo consenso rápido a favor de los microservicios para la escalabilidad, pero divergencias respecto a la base de datos ideal.
* **Ronda 2:** Se sintetizaron los resultados y se presentaron al panel. Tras leer los comentarios anonimos del experto en ciberseguridad, los demas especialistas tuvieron la oportunidad de revisar sus respuestas e incorporaron esos argumentos. Se realizó una nueva encuesta y se alcanzó el consenso final.

### 5. Selección de la tecnología y la arquitectura
* **Decisión final:** Arquitectura en Microservicios alojada en la nube, combinando bases de datos relacionales tradicionales para la operatoria rapida, y una capa de Blockchain privada para la inmutabilidad de los saldos.
* **Justificación:** Los resultados del método Delphi y los aportes del panel demostraron que esta combinación híbrida es la única que equilibra el costo operativo con la máxima seguridad y confiabilidad requerida.

### 6. Documentación y comunicación
* Se generó un documento técnico detallando minuciosamente todo el proceso de toma de decisiones, las opciones descartadas y los criterios utilizados.
* La decisión fue comunicada oficialmente a las partes interesadas mediante dos reportes: uno técnico para alinear a los desarrolladores, y un resumen ejecutivo orientado a los inversores del proyecto.
