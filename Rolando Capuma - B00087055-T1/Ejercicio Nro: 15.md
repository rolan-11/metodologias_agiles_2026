# Ejercicio Nro: 15

## Enunciado
Generar un plan de trabajo basado en SCRUM para resolver la creación de historias de usuarios para un sistema informático de presupuesto de construcción de galpones.
*(Pasos: formar equipos, seleccionar temática, generar 3 historias, enfocar en funcionalidades, presentación y retroalimentación).*

## Resolución

### Parte 1: Plan de Trabajo basado en SCRUM (Simulación de Grupo de Estudio)

Para organizar este trabajo, el equipo simuló un "Sprint" corto aplicado al ámbito universitario:

* **Roles:**
  * **Product Owner:** El profesor (define las reglas del ejercicio y acepta el trabajo final)
  * **Scrum Master:** Un integrante del grupo encargado de coordinar la entrega y organizar el tablero de tareas
  * **Development Team:** El resto de los alumnos del grupo (3 a 5 personas) encargados de redactar y analizar las historias de usuario
* **Sprint Planning:** Reunión inicial de 30 minutos por Discord para elegir la temática (Galpones Logísticos y Comerciales) y repartir quién redacta que historia de usuario (Vendedor vs. Arquitecto).
* **Daily Scrum:** Seguimiento asincrónico diario mediante el grupo de WhatsApp del equipo para destrabar dudas (ej: "¿Cómo armo los criterios de aceptación?").
* **Sprint Review:** Es el momento de la clase donde el equipo presenta las historias de usuario terminadas (usando post-its o diapositivas) al profesor y al resto de los compañeros.
* **Sprint Retrospective:** Mini reunión post-clase para evaluar cómo trabajamos juntos y qué podemos mejorar para el próximo TP grupal.

---

### Parte 2: Entregable (Historias de Usuario)

**Temática Seleccionada:** Sistema de presupuestos para Galpones Logisticos y Comerciales (ideales para depósitos de mercadería o stock de locales).
**Roles definidos:** Vendedor (enfoque comercial) y Arquitecto (enfoque técnico).

#### Historia de Usuario 1: Presupuesto Comercial Rapido
* **Título:** Generación de cotización rápida en PDF.
* **Descripción:** **Como** vendedor, **quiero** poder ingresar las medidas básicas del galpón logístico y generar una estimación de precio, **para** exportarla a PDF y enviársela rápidamente por WhatsApp al cliente para no perder la venta.
* **Criterios de Aceptación:**
  * El sistema debe permitir ingresar ancho, largo y altura del galpon
  * Debe existir un boton visible de "Exportar a PDF"
  * El documento generado debe incluir el logo de la constructora, el precio final con IVA y una validez de la oferta (ej. 15 días)

#### Historia de Usuario 2: Cálculo Técnico de Materiales
* **Título:** Desglose automático de materiales de obra
* **Descripción:** **Como** arquitecto, **quiero** que al confirmar las dimensiones del deposito, el sistema calcule automaticamente las cantidades exactas de chapa, perfiles metálicos y metros cúbicos de hormigón, **para** tener precisión técnica y saber exactamente qué comprar en el corralón.
* **Criterios de Aceptación:**
  * El sistema debe calcular los metros cuadrados (m2) totales de cubierta y cerramiento
  * Debe generar un listado detallado (lista de materiales) descargable en Excel
  * El cálculo de materiales debe incluir automáticamente un 5% extra por "desperdicio de obra"

#### Historia de Usuario 3: Presupuesto dividido por Etapas
* **Título:** Armado de presupuesto por fases de construcción
* **Descripción:** **Como** arquitecto encargado del proyecto, **quiero** que el presupuesto se divida en etapas claras (Cimientos, Estructura, Techo, Pisos industriales), **para** poder cobrarle al cliente por fase terminada (certificación de obra).
* **Criterios de Aceptación:**
  * El desglose de costos en pantalla debe agruparse obligatoriamente por etapa.
  * El sistema debe mostrar un subtotal por cada fase independiente.
  * Debe permitir marcar una etapa como "Finalizada/Cobrada" para llevar el seguimiento financiero.
