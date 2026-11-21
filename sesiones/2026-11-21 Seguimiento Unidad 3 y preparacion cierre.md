# Seguimiento de Unidad 3 y preparación del cierre — 21 de noviembre de 2026

**Proyecto:** HUB CONECTA — Desafío 01, caracterización de usuarios del Hub Providencia.  
**Equipo:** INGENIA 5.  
**Tipo de registro:** corte de seguimiento documental y funcional; **no corresponde a un acta de clase ni acredita asistencia o pruebas formales**.  
**Fuentes:** propuesta del 15/10 actualizada el 25/10; informe de avance de octubre; materiales de Unidad 3 (`Capstone_Unidad3__Clase12` y `Clase 12-19 nov`); confirmación de estado del prototipo comunicada por el equipo el 21/11.

## 1. Objetivo del seguimiento

Actualizar el estado del proyecto al comenzar la preparación de los hitos finales, contrastando el plan docente con las funcionalidades informadas por el equipo y los respaldos aún necesarios para informe, feria y defensa.

## 2. Evolución de la propuesta

El diseño del 25/10 sustituyó el QR personal permanente con autoatención por **cuenta persistente, reserva con QR único, lectura por personal autorizado, registro diferenciado de asistencia, panel y exportación Excel**. Los espacios de acceso libre no pasan a exigir reserva; las visitas espontáneas se consideran por separado.

Esta decisión se conserva como referencia vigente. El desafío sigue siendo **cuantificar y caracterizar usuarios**, no únicamente administrar reservas. Reserva programada y llegada validada no son equivalentes; tampoco se debe confundir espacio reservado con ocupación física real. La versión documentada no contempla medir permanencia ni salida sistemática; esta limitación debe indicarse.

## 3. Estado informado al 21/11 — funcionalidades operativas

El equipo declara haber comprobado manualmente el funcionamiento de estas diez prestaciones de la página web:

1. Creación de cuentas.
2. Inicio de sesión.
3. Reservas.
4. Generación de códigos QR.
5. Validación de asistencia.
6. Cancelaciones.
7. Registro de visitas espontáneas.
8. Dashboard administrativo.
9. Exportación a Excel.
10. Roles y seguridad.

**Alcance de esta confirmación:** corresponde a una declaración del equipo. No se han incorporado en esta entrada capturas fechadas, código fuente inspeccionado, protocolo ejecutado ni resultados cuantitativos que permitan calificarlas como validadas independientemente. El prototipo se ejecuta localmente en el computador de un integrante; la disponibilidad de acceso remoto o instalación definitiva no está demostrada. El equipo identifica mejoras de presentación estética pendientes.

**Estado técnico reportado:** prototipo web funcional a nivel de uso del equipo, pendiente de documentación, pruebas formalizadas y ajustes de interfaz; no se afirma despliegue oficial en el Hub, autorización de piloto en terreno ni mejoras medidas frente al proceso actual.

## 4. Calendario y orientaciones de la profesora (Unidad 3)

| Fecha | Hito del curso | Registro del equipo / evidencia pendiente |
| --- | --- | --- |
| 05/11/2026 | Definir alcance, tareas y materiales | Hito de la planificación docente; falta adjuntar acta o evidencia de ejecución de ese día. |
| 12/11/2026 | Primer avance demostrable (captura, simulación o función) | Hito de la planificación docente; falta enlazar evidencia fechada y registrar la participación real del equipo. |
| 19/11/2026 | Integración, pruebas, datos de funcionamiento y problemas | Hito de la planificación docente; falta protocolo y resultados fechados de esa jornada. |
| 26/11/2026 | Tercer avance con prototipo funcionando, documentación y ensayo de pitch | Próxima entrega de avance a preparar y respaldar. |
| 01/12/2026 | Ensayo general y montaje, sujeto a confirmación docente | Coordinar y confirmar si se realiza o se integra al ensayo del 26/11. |
| 03/12/2026 | Feria Capstone, 14:00–16:30, Campus Manuel Montt | Preparar demostración, stand, soportes y pitch de 5 minutos. |
| 07/12/2026 | Entrega del informe final con documentación de la feria | Utilizar estrictamente la plantilla oficial y evidencias reales. |
| 10/12/2026 | Presentaciones ante comisión (14:00–16:30) y cierre del curso (17:00) | Preparar defensa del proyecto y asistencia al cierre según instrucciones del curso. |

Las diapositivas de Unidad 3 indican **tres integrantes por stand y dos para el pitch**, con roles por definir/confirmar. El pitch de feria debe explicar problema (0:00–0:40), solución (0:40–1:40), demostración (1:40–3:20), resultados y límites (3:20–4:20), y cierre (4:20–5:00). Cada integrante debe poder explicar el proyecto.

## 5. Validación requerida y criterios preliminares

Conforme al informe de avance de octubre y a la retroalimentación general del curso, se deben documentar para cada caso: **requisito, objetivo, versión, fecha, entorno, responsable, datos ficticios de entrada, resultado esperado y observado, criterio, aprobado/fallido, incidencia, mejora y evidencia**.

| Grupo de comprobación | Meta preliminar de octubre | Pendiente |
| --- | --- | --- |
| Reservas normales | Al menos 19/20 correctas | Registrar resultados realmente observados. |
| Validación QR normal | Al menos 38/40 asociaciones correctas, sin duplicados | Registrar casos y distinguir intentos normales de adversos. |
| Cancelado, inválido o repetido | Rechazo correcto en todos los casos diseñados | Capturas y resultados; comprobar que no se agrega asistencia. |
| Conflicto de disponibilidad | Ningún sobrecupo en los casos diseñados | Documentar la concurrencia o los intentos de conflicto. |
| Visita espontánea | Aplicación correcta de reglas y disponibilidad | Documentar escenarios aceptados y rechazados. |
| Exportación a Excel | Coincidencia entre registros, filtros y estados | Contrastar manualmente con panel/base. |
| Roles y seguridad | Rechazo de accesos no autorizados | Matriz de permisos y evidencia desidentificada. |
| Facilidad general | Promedio objetivo 4/5 | Aplicar encuesta, informar tamaño de muestra y resultados; no inventar. |
| Respaldo | Restauración correcta | Confirmar si está implementado y ejecutar una prueba. |

**Estas cifras son metas de planificación, no resultados obtenidos.** Una mejora de tiempos solo podrá declararse con comparación contra una línea base equivalente.

## 6. Evidencias necesarias antes de la feria y del informe

- Capturas fechadas de los flujos de registro, sesión, reserva, cancelación, QR, asistencia, visita espontánea, dashboard, exportación y permisos, usando datos de prueba.
- Identificación de versión, entorno y tecnología realmente utilizada (confirmar con responsable de desarrollo).
- Matriz de pruebas ejecutadas con resultados y registro de fallas/correcciones.
- Verificación de indicadores de caracterización: usuarios/cuentas únicos, recurrencia, perfiles y uso asociado a los espacios cubiertos.
- Evidencia de valoración de uso, si se realiza, sin presentar voluntarios como muestra representativa.
- Costos y horas-persona actualizados a los recursos realmente empleados.
- Evidencias del trabajo grupal y decisiones interdisciplinarias, además de fotografías, actas y registros de las sesiones que existan.
- Preparación de un plan B de demostración: video/capturas/simulación identificados de forma correcta; nunca presentarlos como uso real del Hub.

## 7. Organización de los próximos hitos

| Tramo | Prioridad | Responsable |
| --- | --- | --- |
| 21–25/11 | Reunir capturas y preparar matriz de pruebas; confirmar catálogo, reglas y alcance con el desarrollador | **Asignación pendiente de confirmación interna** |
| 26/11 | Mostrar avance comprobable y ensayar pitch con roles claros | **Asignación pendiente** |
| 27/11–02/12 | Corregir problemas detectados, perfeccionar interfaz sin alterar lógica, ensayar demostración y preparar stand/póster | **Asignación pendiente** |
| 03/12 | Feria, registro de preguntas y retroalimentación de visitantes | **Asignación pendiente** |
| 04–07/12 | Completar informe final y anexos incluyendo feria; revisión APA y declaración de uso de IA | **Asignación pendiente** |
| 08–10/12 | Ensayo de defensa, verificación de prototipo y respaldos; presentación ante comisión | **Asignación pendiente** |

La distribución definitiva entre los cinco integrantes debe acordarse y documentarse; la tabla es un plan de trabajo y no acredita tareas asignadas o ejecutadas.

## 8. Riesgos y medidas

- **Dependencia del computador del desarrollador:** preparar capturas y video offline y verificar logística de la demostración.
- **Resultados sin respaldo:** usar datos de prueba, protocolo, fecha y evidencia antes de declarar validación.
- **Problemas de red, lector o QR en feria:** realizar ensayo y contar con alternativa explícitamente identificada.
- **Privacidad:** no subir contraseñas, códigos QR activos ni registros personales de usuarios al repositorio público.
- **Cobertura del desafío:** no equiparar reservas con asistencia ni resultados parciales con todos los usuarios del edificio.
- **Cambios estéticos:** no alterar reglas, base de datos o seguridad sin pruebas de regresión.

## 9. Próxima actualización verificable

En la próxima entrada de bitácora deberán registrarse la evidencia efectivamente obtenida para el hito del 26/11, las personas participantes, resultados de pruebas, incidencias, acuerdos con el Hub, roles del stand/pitch y archivos asociados. No registrar estos resultados antes de su realización.

## Fuentes internas

- [Desarrollo de HUB CONECTA y decisión de diseño (actualizado el 25/10)](./2026-10-15%20Desarrollo%20propuesta%20Hub%20Conecta.md)
- [Planificación e informe de avance de octubre](./2026-10-29%20Entrega%20informe%20y%20presentacion.md)
- Material docente de Unidad 3: `Capstone_Unidad3__Clase12(1).pptx` y `Clase 12-19 nov.pptx`, aportados al equipo.
- Informe de avance de octubre y formato obligatorio del informe final, proporcionados por el equipo.

[Volver al índice](../README.md)
