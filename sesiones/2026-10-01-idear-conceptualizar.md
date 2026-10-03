# Sesión — 1 de octubre de 2026
## Idear y conceptualizar

Esta fase continúa el trabajo realizado en Empatizar y Definir. El foco se desplaza desde comprender y delimitar el problema hacia investigar soluciones existentes, identificar atributos relevantes y generar alternativas conceptuales fundamentadas. El proceso sigue siendo iterativo: los nuevos antecedentes pueden obligar a revisar decisiones anteriores antes de seleccionar una solución definitiva.

**Secuencia de trabajo:** Estado del Arte → atributos → comparación de soluciones → oportunidades de innovación → Benchmark → segunda lluvia de ideas.

---

### 23. Actividad 1 — Análisis del Estado del Arte

**Problema utilizado para la búsqueda:** el equipo de gestión del Hub Providencia necesita conocer de manera sistemática quiénes utilizan el edificio, con qué frecuencia lo visitan, qué espacios ocupan y cuáles son sus patrones de uso para apoyar la planificación de servicios, actividades y espacios; pero actualmente dispone de información limitada y poco sistematizada para realizar dicha caracterización.

Para ampliar la búsqueda se consideraron soluciones directas, parciales e indirectas relacionadas con gestión de visitantes, administración de coworking, monitoreo de ocupación, control de asistencia y captura estructurada de información.

#### Soluciones existentes identificadas

| Nombre | Descripción breve | ¿Quién la usa / desarrolló? | ¿Cómo aborda el problema? | Fuente |
| --- | --- | --- | --- | --- |
| Envoy Visitors | Plataforma digital de gestión de visitantes con prerregistro, check-in, reconocimiento de visitantes recurrentes y analítica. | Envoy; organizaciones que gestionan visitantes y espacios de trabajo. | Reduce la repetición de información, mantiene trazabilidad de visitas y permite analizar volumen y horas/días de mayor afluencia. | [envoy.com/products/visitors](https://envoy.com/products/visitors) |
| OfficeRnD Flex | Plataforma para coworking y espacios flexibles: check-in/check-out, integraciones con Wi-Fi o control de acceso, dashboards de ocupación y reservas. | OfficeRnD; operadores de coworking y espacios flexibles. | Relaciona personas, check-ins, reservas y utilización del espacio, permitiendo analizar recurrencia, tráfico y ocupación. | [help-flex.officernd.com](https://help-flex.officernd.com/en/articles/248540-check-ins-and-check-outs) |
| Cisco Spaces | Monitoreo de ocupación mediante telemetría de Wi-Fi, BLE, RFID y sensores cableados. | Cisco; oficinas, universidades, retail y recintos. | Permite conocer ocupación en tiempo real, afluencia acumulada, horas/días de mayor utilización y tendencias de uso. | [spaces.cisco.com](https://spaces.cisco.com/occupancy-monitoring/) |
| Jibble QR Kiosk | Sistema de asistencia que registra entrada y salida mediante un QR personal escaneado en un dispositivo compartido. | Jibble; equipos y organizaciones que registran asistencia. | Utiliza un identificador reutilizable para registrar entradas y salidas rápidamente, sin volver a completar datos. | [jibble.io](https://www.jibble.io/help/how-to-use-jibbles-qr-code-kiosk) |
| Google Forms + Sheets | Formulario web configurable cuyas respuestas se almacenan automáticamente en una hoja de cálculo. | Google; uso transversal en organizaciones, educación y levantamientos. | Permite definir variables y estructurar respuestas; por defecto requiere interacción manual y no reconoce recurrencia. | [support.google.com](https://support.google.com/docs/answer/139706/view-and-manage-form-responses) |

*Criterio de diversidad: se incluyeron gestión de visitantes, operación de coworking, ocupación pasiva, asistencia mediante QR y captura flexible de datos, siguiendo la instrucción de diversificar enfoques del Estado del Arte.*

#### Principales hallazgos del Estado del Arte

- Envoy Visitors evidencia que el registro de visitantes puede reducir fricción cuando se reconocen personas recurrentes y se reutiliza información previa.
- OfficeRnD Flex muestra que en coworking es posible relacionar check-ins, personas, reservas y ocupación para generar información operativa.
- Cisco Spaces permite medir ocupación y patrones temporales mediante infraestructura de red y sensores, reduciendo la dependencia de formularios manuales.
- Jibble muestra que un identificador QR personal y reutilizable puede simplificar los registros recurrentes.
- Google Forms y Sheets representan un enfoque de bajo costo y alta flexibilidad, aunque requieren mayor interacción manual.
- **Hallazgo general:** las soluciones existentes resuelven partes diferentes del desafío, lo que abre una oportunidad para integrar únicamente las funciones que aporten valor al Hub Providencia, evitando complejidad innecesaria.

---

### 24. Actividad 2 — Atributos vs. Soluciones

| Atributo | Definición aplicada al proyecto |
| --- | --- |
| Ágil / intuitivo | El registro requiere poca interacción, es comprensible y rápido para distintos tipos de usuarios. |
| Recurrente / identificable | Permite reconocer a una persona previamente registrada y evitar solicitar nuevamente toda su información. |
| Trazable | Permite conservar registros de visitas, ingresos/salidas o presencia para analizar frecuencia y recurrencia. |
| Analítico / visualizable | Permite transformar los registros en indicadores, reportes o visualizaciones útiles para la gestión. |
| Espacial | Permite obtener información sobre salas, zonas o espacios utilizados, no solo contar ingresos al edificio. |

---

### 25. Actividad 3 — Matriz de Atributos y Soluciones Existentes

*Leyenda: Sí = atributo abordado directamente; Parcial = abordado de manera limitada; No = no abordado de forma relevante.*

| Atributo | Google Forms + Sheets | Envoy Visitors | OfficeRnD Flex | Cisco Spaces | Jibble |
| --- | --- | --- | --- | --- | --- |
| Ágil / intuitivo | Parcial | Sí | Sí | Sí | Sí |
| Recurrente / identificable | Parcial | Sí | Sí | Parcial | Sí |
| Trazable | Parcial | Sí | Sí | Parcial | Sí |
| Analítico / visualizable | Parcial | Sí | Sí | Sí | Parcial |
| Espacial | Parcial | Parcial | Sí | Sí | No |

**¿Qué atributos NO están resueltos por ninguna solución?** No se identifica un atributo completamente ausente, pero ninguna alternativa integra de forma simple y adaptada al Hub: identificación recurrente, registro de visita, caracterización del perfil, utilización de espacios, baja fricción e información analítica, todo al mismo tiempo. La principal brecha está en la integración.

**¿Qué atributo parecería más relevante?** La identificación recurrente de baja fricción, ya que el desafío exige evitar solicitar todos los datos en cada visita. Debe complementarse con trazabilidad, para que reconocer a una persona permita además analizar frecuencia y patrones de uso.

**¿Dónde hay oportunidades de mejora o innovación?** Desarrollar una solución liviana y adaptada al Hub que combine funciones hoy distribuidas entre distintas soluciones: enrolamiento inicial → identificador reutilizable → registro rápido de visitas posteriores → asociación con propósito/espacio → almacenamiento estructurado → indicadores de gestión.

---

### 26. Actividad 4 — Lluvia de ideas con Estado del Arte y Benchmark

#### Benchmark de soluciones existentes

| Solución | Práctica destacable | Limitación respecto del Hub | Aprendizaje para el proyecto |
| --- | --- | --- | --- |
| Envoy Visitors | Reconoce visitantes recurrentes, agiliza el check-in y dispone de analítica. | Su foco principal es gestión de visitantes y recepción. | Evitar solicitar reiteradamente la misma información; usar registros para analizar tendencias. |
| OfficeRnD Flex | Integra personas, check-ins, reservas, ocupación y dashboards. | Plataforma amplia que puede exceder un prototipo acotado. | Relacionar identidad, recurrencia y uso del espacio genera información más útil que un simple conteo. |
| Cisco Spaces | Obtiene ocupación y patrones temporales de forma pasiva. | Requiere infraestructura tecnológica; foco en ocupación, no en caracterización detallada. | No toda la información necesita depender de formularios manuales. |
| Jibble | QR personal para registrar entrada/salida rápidamente. | Orientado a asistencia laboral, no caracteriza uso interno de espacios. | Un identificador reutilizable reduce significativamente la fricción de registros recurrentes. |
| Google Forms + Sheets | Define variables de forma flexible y almacena respuestas simples. | Requiere ingreso manual; no automatiza recurrencia ni ocupación. | Una primera versión puede priorizar simplicidad y bajo costo antes que infraestructura compleja. |

#### Segunda lluvia de ideas

*En esta etapa las alternativas se mantienen como conceptos; no se selecciona todavía una solución definitiva.*

| Propuesta conceptual | Descripción | Referencia / aprendizaje |
| --- | --- | --- |
| Identificador QR reutilizable del Hub | Enrolamiento inicial con identificador QR personal; en visitas posteriores se escanea para recuperar el perfil, solicitando solo información variable (propósito, espacio). Puede complementarse con registro de salida. | Envoy + Jibble |
| Kiosco de autoatención en recepción | Tablet/computador que enrola usuarios nuevos y reconoce recurrentes vía QR u otro identificador; registra hora, tipo de visita y espacio. | Envoy + Jibble |
| Check-in apoyado por red Wi-Fi | Tras enrolamiento y consentimiento, la conexión a la red apoya la detección de presencia/recurrencia; un formulario breve completa lo no inferible. | Cisco Spaces + OfficeRnD |
| Credencial NFC o tarjeta reutilizable | Usuarios frecuentes disponen de credencial reutilizable registrada al ingresar; a futuro, puntos de lectura por espacio. | Jibble / control de acceso |
| Sistema híbrido QR + medición de ocupación | Identidad registrada vía QR al ingreso; sensores/Wi-Fi estiman ocupación de zonas sin registro repetido. | Envoy + Cisco Spaces |
| Reserva + check-in integrado | El registro previo de reserva se vincula automáticamente con la visita; al llegar, check-in rápido asocia asistencia, espacio y actividad. | OfficeRnD |

**Resultado de la segunda lluvia de ideas:** el Estado del Arte modificó la perspectiva inicial del equipo. Ya no se considera necesario que toda la información sea solicitada manualmente en cada visita ni que una única tecnología realice todas las funciones. Las alternativas generadas se concentran en tres principios: registrar una vez la información estable; simplificar lo que se solicita en cada visita; y transformar los datos acumulados en información útil para la gestión.

Las seis propuestas permanecen como alternativas conceptuales. El siguiente paso es definir y priorizar requerimientos, y luego comparar las alternativas con criterios objetivos antes de seleccionar la solución que avanzará a conceptualización y prototipado.

#### Fuentes oficiales consultadas

- Envoy Visitors — Visitor Management: [envoy.com/products/visitors](https://envoy.com/products/visitors)
- Envoy — Visitor Experience Management: [envoy.com/solutions/visitor-experience-management](https://envoy.com/solutions/visitor-experience-management)
- OfficeRnD Flex — Check-ins and check-outs: [help-flex.officernd.com](https://help-flex.officernd.com/en/articles/248540-check-ins-and-check-outs)
- OfficeRnD Flex — Check-ins by Customer Dashboard: [help-flex.officernd.com](https://help-flex.officernd.com/en/articles/248489-data-hub-check-ins-by-customer-dashboard)
- OfficeRnD Flex — Occupancy Overview Dashboard: [help-flex.officernd.com](https://help-flex.officernd.com/en/articles/248500-data-hub-occupancy-overview-dashboard)
- Cisco Spaces — Occupancy Monitoring: [spaces.cisco.com](https://spaces.cisco.com/occupancy-monitoring/)
- Jibble — QR Code Kiosk: [jibble.io](https://www.jibble.io/help/how-to-use-jibbles-qr-code-kiosk)
- Google Forms — View and manage form responses: [support.google.com](https://support.google.com/docs/answer/139706/view-and-manage-form-responses)

> **Nota metodológica:** las funcionalidades descritas corresponden a documentación oficial consultada para el Estado del Arte. La evaluación "Sí / Parcial / No" de la matriz es una interpretación del equipo para el contexto del Hub Providencia y deberá revisarse al definir requerimientos formales de la solución.

### Cierre de la clase 01/10/2026

La clase permitió avanzar desde la evidencia de terreno hacia la exploración estructurada de alternativas. El equipo no selecciona todavía una solución definitiva: mantiene las propuestas como conceptos y deja como siguiente paso la definición y priorización de requerimientos, seguida de una comparación objetiva antes del prototipado. Se conserva así la trazabilidad metodológica del proyecto: **comprender → validar → investigar referentes → comparar → idear → priorizar.**

---
[⬅ Volver al índice](../README.md)
