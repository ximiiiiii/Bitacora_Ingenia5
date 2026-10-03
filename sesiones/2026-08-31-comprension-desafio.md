# Sesión — semana del 31 de agosto de 2026
## Comprensión del problema

**Participantes:** actividad registrada como trabajo de Ingenia 5; el documento disponible no individualiza asistencia por integrante.

---

### Ficha base del desafío

| Campo | Contenido |
| --- | --- |
| Pregunta orientadora | ¿Cómo podríamos cuantificar y caracterizar a los usuarios del edificio del Hub Providencia? |
| Contexto y problema | El Hub Providencia recibe diariamente emprendedores, startups, estudiantes, empresas, vecinos y visitantes. Existe información limitada sobre quiénes utilizan el edificio, con qué frecuencia, qué espacios ocupan y cómo se comportan durante su visita. |
| Usuarios / beneficiarios | Equipo de gestión del Hub Providencia y personas usuarias del edificio. |
| Objetivo del desafío | Diseñar e implementar una solución que permita identificar, segmentar y analizar perfiles y patrones de uso del edificio para apoyar la gestión y la toma de decisiones. |
| Producto mínimo esperado | Prototipo funcional de registro de ingresos (y salidas, cuando sea viable); base de datos estructurada; dashboard con indicadores de frecuencia, perfiles, espacios y patrones de uso. |
| Requerimientos mínimos | Levantar el flujo actual de ingreso y uso de espacios; evitar completar todos los datos en cada visita mediante enrolamiento inicial y registros simplificados; priorizar herramientas sin costo de licencias. |
| Criterios de éxito | Registrar y consultar información de manera más eficiente; generar indicadores útiles para la gestión; permitir pruebas con usuarios o datos reales/piloto. |

### Mapa conceptual del desafío

![Mapa conceptual del desafío](../imagenes/mapa-conceptual.jpg)
*Figura 2. Mapa conceptual construido a partir de la ficha oficial del desafío.*

### Lo que sabemos y lo que necesitamos saber

**Sabemos (con respaldo del desafío):**
- El Hub recibe diariamente perfiles diversos: emprendedores, startups, estudiantes, empresas, vecinos y visitantes.
- Existe información limitada sobre identidad/perfil, frecuencia de visita, espacios utilizados y comportamiento durante la visita.
- La falta de información dificulta la planificación de servicios, actividades y espacios.
- El equipo de gestión y las personas usuarias son beneficiarios del proyecto.
- Se debe levantar el flujo actual de ingreso y uso de espacios antes de definir la solución.
- Se debe evitar que una persona complete todos sus datos en cada visita (enrolamiento inicial + registros simplificados).

**Necesitamos saber:**
- ¿Cómo funciona exactamente hoy el ingreso, registro y salida de las personas?
- ¿Qué datos se registran actualmente, en qué formato, por quién y con qué finalidad?
- ¿Cuántas personas ingresan por día y cómo varía el flujo por día, horario y tipo de actividad?
- ¿Qué espacios son más utilizados y cómo se registra actualmente su ocupación?
- ¿Existe algún identificador de usuario reutilizable o sistema previo de registro?
- ¿Qué datos mínimos necesita el equipo de gestión para segmentar perfiles y apoyar decisiones?
- ¿Qué nivel de aceptación tendría un mecanismo de identificación o registro entre los usuarios?
- ¿Qué restricciones operativas, tecnológicas, de privacidad o infraestructura deben considerarse?

### Preguntas abiertas para profundizar el problema

- ¿Cómo ocurre actualmente el proceso de ingreso, permanencia y salida de una persona usuaria?
- ¿Qué información se solicita hoy a quienes ingresan y qué parte se conserva para visitas posteriores?
- ¿Qué dificultades enfrenta el equipo de gestión para conocer cantidad y perfil de usuarios?
- ¿Qué información necesita el equipo de gestión para planificar mejor servicios, actividades y espacios?
- ¿Qué tipos de usuarios visitan con mayor frecuencia y con qué objetivos?
- ¿Qué espacios presentan mayor y menor utilización según día y horario?
- ¿Qué tan frecuente es que una misma persona vuelva a usar el Hub?
- ¿Qué fricciones perciben los usuarios en el proceso actual de ingreso o registro?
- ¿Qué restricciones de privacidad y consentimiento deben considerarse?
- ¿Qué indicadores serían realmente útiles para la toma de decisiones de gestión?

### Mapa de empatía preliminar

Usuario principal definido: persona usuaria que ingresa y utiliza el edificio del Hub Providencia.

![Mapa de empatía preliminar](../imagenes/mapa-empatia.jpg)
*Figura 3. Mapa de empatía preliminar. Las afirmaciones internas se consideran hipótesis y deben validarse con usuarios.*

#### Clasificación de ideas: evidencia vs. supuesto

| Idea | Clasificación | Justificación |
| --- | --- | --- |
| Las personas usuarias presentan perfiles diversos. | Evidencia | La ficha menciona emprendedores, startups, estudiantes, empresas, vecinos y visitantes. |
| Existen visitas repetidas que conviene simplificar. | Evidencia parcial | El requerimiento mínimo pide enrolamiento inicial + registros simplificados; magnitud por medir. |
| Los usuarios preferirán un registro rápido. | Supuesto / validar | No hay entrevistas ni observación que lo confirmen. |
| Los usuarios pueden tener preocupaciones por sus datos. | Supuesto / validar | Hipótesis razonable, sin evidencia en los antecedentes entregados. |
| La segmentación por perfil, frecuencia y espacios será útil para la gestión. | Objetivo del desafío | Exigido por el desafío; utilidad concreta se valida con el mandante. |

#### Tres supuestos críticos a comprobar con usuarios

1. **Las personas usuarias estarán dispuestas a entregar un conjunto mínimo de datos una vez**, si las visitas posteriores requieren menos interacción → comprobar con entrevistas breves y observación del proceso de ingreso.
2. **Existen patrones suficientemente distintos** entre perfiles, frecuencia de visita y uso de espacios como para justificar una segmentación → revisar registros disponibles, observar flujos, levantar muestra piloto.
3. **El equipo de gestión puede transformar indicadores en decisiones concretas** → entrevistar al equipo de gestión y solicitar ejemplos de decisiones actuales con información incompleta.

### Información investigada sobre la problemática

Revisión documental preliminar en fuentes oficiales de la Municipalidad de Providencia (contexto, no reemplaza el levantamiento de terreno):

| Antecedente oficial | Relevancia para el desafío |
| --- | --- |
| El Hub Providencia forma parte de la Dirección de Desarrollo Local y conecta residentes, emprendedores y empresas con recursos y oportunidades. | Confirma públicos heterogéneos; la caracterización no puede limitarse a un único tipo de usuario. |
| El sitio oficial informa un cowork general gratuito, además de cowork textil y GovTech Lab. | Refuerza la necesidad de registrar el tipo de espacio o servicio utilizado, no solo el ingreso. |
| La sección de Innovación menciona laboratorio de prototipado, cowork para startups, laboratorio de videojuegos, salas de reuniones y zonas de capacitación. | La diversidad de espacios puede generar patrones de uso distintos, que deben observarse antes de diseñar indicadores. |

**Interpretación ingenieril:** el problema no consiste únicamente en contar personas. El desafío exige relacionar cantidad de visitas con perfil, recurrencia, propósito y uso de espacios para producir información útil para la gestión.

### Próximas acciones para validar el problema

| Acción | Objetivo | Evidencia esperada |
| --- | --- | --- |
| Observación del flujo de ingreso y uso de espacios | Comprender el proceso real, actores, tiempos y registros actuales. | Diagrama del proceso, notas de observación, fotografías autorizadas. |
| Entrevista al equipo de gestión | Identificar decisiones que requieren información y priorizar variables. | Lista priorizada de necesidades de información. |
| Entrevistas breves a usuarios | Conocer fricciones, disposición al registro, recurrencia y propósito. | Patrones cualitativos, validación/refutación de supuestos. |
| Revisión de registros existentes | Determinar qué datos ya existen y su calidad. | Inventario de fuentes, variables, formatos y brechas. |
| Levantamiento piloto | Medir de forma acotada frecuencia, perfiles y uso de espacios. | Base piloto y primeras distribuciones descriptivas. |

### Evidencia incorporada

Fotografías reales del mapa conceptual y del mapa de empatía, tabla saber/no saber, preguntas abiertas, clasificación evidencia/supuesto.

---
[⬅ Volver al índice](../README.md)
