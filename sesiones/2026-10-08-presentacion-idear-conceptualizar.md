# Sesión — 8 de octubre de 2026
## Desarrollo y presentación de actividades: Idear y conceptualizar

**Proyecto:** Desafío 01 — Edificios Inteligentes: Caracterización de usuarios del Hub Providencia.  
**Equipo:** Ingenia 5.

Durante esta jornada, el equipo preparó una presentación en PowerPoint para exponer los resultados de las cuatro actividades solicitadas en la clase anterior (01/10/2026): **análisis del Estado del Arte, atributos vs. soluciones, matriz de atributos y soluciones, y lluvia de ideas con Estado del Arte y Benchmark**.

El objetivo fue ordenar la investigación de referentes tecnológicos, comparar sus características e identificar oportunidades de innovación adaptadas a la realidad del Hub Providencia. La presentación se organizó en torno al problema observado, los referentes, los atributos de evaluación, los hallazgos y las alternativas conceptuales.

---

### 1. Actividad 1 — Análisis del Estado del Arte

Se revisaron cinco soluciones relacionadas con el registro de usuarios, la gestión de visitas y el análisis de ocupación:

| Solución | Funcionalidad destacada |
| --- | --- |
| **Envoy Visitors** | Registro de visitantes, check-in con QR y reconocimiento de visitas recurrentes. |
| **OfficeRnD Flex** | Administración de coworking, reservas, check-ins y ocupación de espacios. |
| **Cisco Spaces** | Monitoreo de ocupación y patrones de uso del espacio. |
| **Jibble** | Registro de entradas y salidas mediante QR o kiosco. |
| **Google Forms + Sheets** | Captura y almacenamiento sencillo de datos para una primera versión. |

**Aprendizaje:** las herramientas analizadas resuelven distintos componentes del desafío, pero no necesariamente integran, en una alternativa simple, la caracterización de usuarios, su recurrencia, el uso de espacios y la generación de información para la gestión.

### 2. Actividad 2 — Atributos vs. Soluciones

A partir de los referentes, definimos cinco atributos relevantes para evaluar alternativas:

| Atributo | Aplicación al Hub Providencia |
| --- | --- |
| **Ágil / intuitivo** | Registro rápido y fácil de utilizar. |
| **Recurrente / identificable** | Reconocimiento de personas previamente registradas, sin repetir todos sus datos. |
| **Trazable** | Consulta del historial y frecuencia de visitas. |
| **Analítico / visualizable** | Generación de indicadores, reportes y visualizaciones. |
| **Espacial** | Asociación de cada visita con los espacios utilizados. |

### 3. Actividad 3 — Matriz de atributos y soluciones

Se compararon las cinco alternativas utilizando una escala de cumplimiento: **Sí**, **Parcial** o **No**.

| Atributo | Forms + Sheets | Envoy | OfficeRnD | Cisco | Jibble |
| --- | --- | --- | --- | --- | --- |
| Ágil / intuitivo | Parcial | Sí | Sí | Sí | Sí |
| Recurrente / identificable | Parcial | Sí | Sí | Parcial | Sí |
| Trazable | Parcial | Sí | Sí | Parcial | Sí |
| Analítico / visualizable | Parcial | Sí | Sí | Sí | Parcial |
| Espacial | Parcial | Parcial | Sí | Sí | No |

**Resultados de la comparación:**
- OfficeRnD presenta una cobertura amplia de atributos asociados a espacios flexibles.
- Envoy destaca en la gestión de visitantes recurrentes.
- Cisco Spaces se orienta al monitoreo de ocupación y utilización del espacio.
- La principal oportunidad no está en un atributo aislado, sino en integrar **identidad, visita, espacio y analítica** de manera sencilla y adecuada al Hub.

Esta matriz representa la evaluación realizada por el equipo en el contexto del desafío, no una certificación técnica de las plataformas.

### 4. Actividad 4 — Lluvia de ideas a partir del Estado del Arte y Benchmark

Con los resultados del análisis comparativo se formularon seis propuestas conceptuales:

| Idea | Descripción |
| --- | --- |
| **QR personal reutilizable** | Enrolamiento inicial y check-in rápido en visitas posteriores. |
| **Kiosco de autoatención** | Registro simple para usuarios nuevos y recurrentes. |
| **Check-in por Wi-Fi** | Apoyo al reconocimiento de recurrencia. |
| **Credencial NFC** | Identificación rápida de usuarios frecuentes. |
| **Sistema híbrido** | Registro mediante QR combinado con información de ocupación espacial. |
| **Reserva + check-in** | Vinculación de agenda, asistencia y espacio utilizado. |

Como concepto de mayor potencial se planteó el siguiente flujo:

**Enrolamiento inicial → identificador reutilizable → registro rápido de visitas → asociación con espacio utilizado → base de datos estructurada → dashboard de gestión.**

La propuesta se mantiene como **concepto para evaluación**, sin que esta sesión represente una selección definitiva ni la implementación de un prototipo.

---

### Hallazgos y aprendizajes de la jornada

**Identificación recurrente de baja fricción.** Se reconoció como un atributo crítico para evitar que una persona deba ingresar reiteradamente la misma información en cada visita.

**Brecha de integración.** Los referentes permiten abordar distintas partes del problema, pero una solución para el Hub debería vincular la caracterización del usuario con su historial y la utilización de espacios, sin generar complejidad innecesaria.

**Oportunidad de innovación.** Se identificó la posibilidad de diseñar una propuesta liviana, contextualizada y escalable que transforme los registros en información útil para la toma de decisiones.

El principal aprendizaje se sintetizó en la idea de **registrar una vez, simplificar las visitas posteriores y transformar los datos en decisiones**.

### Evidencia del trabajo realizado

El equipo preparó la presentación **«Idear y Conceptualizar — Desafío 01: Edificios Inteligentes, Caracterización de usuarios del Hub Providencia»**, correspondiente al **08/10/2026**.

La presentación de ocho diapositivas incluye:
1. Portada e integrantes.
2. Ruta de la presentación.
3. Contexto del problema del Hub Providencia.
4. Estado del Arte de cinco soluciones.
5. Atributos y matriz comparativa.
6. Hallazgos y oportunidad de innovación.
7. Lluvia de ideas y concepto con mayor potencial.
8. Conclusiones y próximos pasos.

**Respaldo utilizado para esta bitácora:** archivo proporcionado por el equipo, `Presentacion capstone 08102026 (1).pdf`. El archivo de presentación no se ha incorporado como adjunto al repositorio en esta actualización.

### Próximos pasos

Definir y priorizar los requerimientos del sistema, comparar las alternativas conceptuales con criterios objetivos y seleccionar la opción más adecuada para avanzar a **conceptualización y prototipado**.

### Cierre de la sesión 08/10/2026

La jornada permitió consolidar y comunicar las cuatro actividades de la fase de ideación. El equipo pasó de revisar soluciones existentes a identificar atributos, evaluar brechas y proponer alternativas que respondan al desafío del Hub Providencia. Se mantiene la necesidad de evaluar técnicamente las propuestas antes de seleccionar e implementar una solución.

---

[⬅ Volver al índice](../README.md)
