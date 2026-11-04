---
permalink: /Capitulo01/
---

# Módulo 1. Project Manager Agent (Planner Agent): planificación y organización de iniciativas

**Duración del módulo:** 36 minutos. **Explicación:** 5 minutos. **Prácticas:** 31 minutos.

**Contexto del módulo:** Los proyectos son simulados y representan actividades de Banca Móvil, adopción digital y e-banca Empresarial. El plan de la práctica 4 se reutiliza en la práctica 5.

> **Control de cambios en Planner:** Revisar y aprobar las propuestas de planes y tareas antes de guardarlas. El agente no modifica por sí solo todos los campos; completar manualmente asignaciones y dependencias que la interfaz no admita.

<a id="practicas-del-modulo"></a>

## Prácticas del módulo

- [Práctica 1. Planificación del lanzamiento de una funcionalidad de Banca Móvil](#practica-01) — 6 min.
- [Práctica 2. Organización de una campaña de adopción de canales digitales](#practica-02) — 6 min.
- [Práctica 3. Planificación de un proyecto de actualización regulatoria](#practica-03) — 6 min.
- [Práctica 4. Plan de implementación de un servicio para clientes empresariales](#practica-04) — 6 min.
- [Práctica 5. Replanificación de un proyecto ante cambios operativos](#practica-05) — 7 min.

---

<a id="practica-01"></a>

## Práctica 1. Planificación del lanzamiento de una funcionalidad de Banca Móvil

### Objetivo de la práctica:

Al finalizar la práctica, serás capaz de:

- Estructurar las fases y tareas de una funcionalidad de Banca Móvil.
- Reconocer responsables, dependencias y entregables de cada fase.
- Comprobar que el plan este guardado en Planner.

### Duración aproximada:

- 6 minutos.

### Tabla de ayuda:

| Parámetro | Valor | Uso |
| --- | --- | --- |
| Plan | LAB-MOB-Lanzamiento | Nombre de plan de práctica |
| Fecha de inicio | 26/10/2026 | Referencia de calendario |
| Áreas | Tecnología, Operaciones, Experiencia del Cliente | Responsables funcionales |

### Instrucciones

#### Tarea 1. Crear un plan y definir el alcance

**Paso 1.** Abrir Microsoft Planner desde Microsoft 365 o Teams, seleccionar **Nuevo plan** y crear el plan básico compartido `LAB-MOB-Lanzamiento` en el grupo de laboratorio autorizado. Este tipo de plan permite trabajar con el agente de Planner en Copilot.

**Paso 2.** Abrir **Agente de Planner** desde el plan o desde Microsoft 365 Copilot (Agentes > Agente de Planner); seleccionar `LAB-MOB-Lanzamiento` como plan de destino. Comprobar que el nombre del plan coincida antes de modificar tareas.

#### Tarea 2. Solicitar la planificación

**Paso 1.** Copiar y enviar la solicitud siguiente en Planner Agent; usarla para crear o actualizar tareas del plan activo.

**Prompt — Lanzamiento Banca Móvil**

```text
Planifica el lanzamiento de una funcionalidad de consulta y descarga de movimientos de Banca Móvil. Fecha inicial 26/10/2026, lanzamiento piloto 30/11/2026. Divide en diseño, desarrollo, pruebas funcionales y de seguridad, comunicación y piloto. Para cada tarea propón un nombre claro, fecha de inicio, fecha límite, entregable, área responsable entre Tecnología, Operaciones y Experiencia del Cliente, y dependencia. Registra las tareas admitidas en este plan. No inventes nombres de usuarios ni marques tareas completadas.
```

**Paso 2.** Revisar el borrador de tareas propuesto por el agente, verificar fechas y fases, corregir cualquier inconsistencia y **aprobar/guardar** las tareas en el plan seleccionado.

**Paso 3.** Abrir el tablero de Planner y completar manualmente responsables por área y dependencias que el agente no pueda editar; no asignar usuarios reales para este ejercicio.

#### Tarea 3. Validar el entregable

**Paso 1.** Seleccionar la vista de tablero de Planner, abrir dos tareas y verificar nombre, fecha y estado; comprobar que cada fase tenga al menos una tarea.

**Paso 2.** Abrir las opciones de exportación del plan; si está disponible Exportar a Excel, mostrar la opción sin atribuirla al agente. Mantener el plan guardado.

#### Resultado esperado

Plan LAB-MOB-Lanzamiento visible en Planner, con fases, tareas fechadas y entregables diferenciados; comprobación de la opción de exportación a Excel solo cuando la interfaz la ofrezca.

[Volver a las prácticas del módulo](#practicas-del-modulo) | [Índice del curso](../) | [Consultar la Setup Guide](../setup/)

---

<a id="practica-02"></a>

## Práctica 2. Organización de una campaña de adopción de canales digitales

### Objetivo de la práctica:

Al finalizar la práctica, serás capaz de:

- Organizar una campaña de adopción digital por fases y responsables.
- Generar un calendario CSV compatible con Excel y comprobar las fechas en Planner.

### Duración aproximada:

- 6 minutos.

### Tabla de ayuda:

| Parámetro | Valor | Uso |
| --- | --- | --- |
| Plan | LAB-DIG-Campana | Plan de esta práctica |
| Campaña | 02/11/2026 al 27/11/2026 | Período |
| Meta | 35 % de adopción | Indicador de seguimiento |

### Instrucciones

#### Tarea 1. Establecer el plan de campaña

**Paso 1.** Abrir Planner, crear el plan LAB-DIG-Campana y acceder a Planner Agent.

**Paso 2.** Enviar el prompt y comprobar que la propuesta cubre comunicación, educación financiera, medición y cierre. Revisar y aprobar las tareas propuestas en Planner antes de continuar con el calendario.

**Prompt — Campaña digital**

```text
Organiza una campaña para promover Banca Móvil en cuatro sedes entre 02/11/2026 y 27/11/2026. Fases: preparación, comunicación, talleres de educación financiera, activación y medición. Incluye objetivo, tareas con fechas, área responsable, entregable y un indicador cuantificable. La meta de adopción es 35 %. Crea las tareas admitidas en el plan abierto; no asignes personas concretas.
```

#### Tarea 2. Construir el calendario CSV

**Paso 1.** Solicitar al agente el calendario en formato de filas CSV separado por comas, con columnas Fecha, Fase, Actividad, Área, Indicador y Estado; verificar que cada fecha pertenezca al período establecido.

**Paso 2.** Copiar las filas CSV a una hoja de Excel; utilizar Datos > Texto en columnas si las filas quedan en una sola columna, y guardar como CSV UTF-8 con el nombre calendario_adopcion.csv.

#### Tarea 3. Comprobar la integración visual

**Paso 1.** Regresar a Planner, abrir la vista Calendario o Programacion si se encuentra habilitada y contrastar dos fechas con el CSV.

**Paso 2.** Corregir cualquier diferencia en el plan o en el calendario antes de considerar terminado el ejercicio.

#### Resultado esperado

Plan LAB-DIG-Campana guardado en Planner y calendario_adopcion.csv con fechas dentro de noviembre, etapas completas, indicador y visualización del calendario o programación disponible.

[Volver a las prácticas del módulo](#practicas-del-modulo) | [Índice del curso](../) | [Consultar la Setup Guide](../setup/)

---

<a id="practica-03"></a>

## Práctica 3. Planificación de un proyecto de actualización regulatoria

### Objetivo de la práctica:

Al finalizar la práctica, serás capaz de:

- Definir una secuencia de actualización de procedimientos bancarios con dependencias.
- Construir una matriz de cumplimiento trazable en Word.

### Duración aproximada:

- 6 minutos.

### Tabla de ayuda:

| Parámetro | Valor | Uso |
| --- | --- | --- |
| Proyecto | LAB-REG-Controles | Identificador |
| Áreas | Cumplimiento, Riesgos, Operaciones, Tecnología | Participantes del caso |
| Fecha meta | 27/11/2026 | Fin hipotético |

### Instrucciones

#### Tarea 1. Organizar actividades y dependencias

**Paso 1.** Abrir un plan nuevo en Planner denominado LAB-REG-Controles y acceder a Planner Agent.

**Paso 2.** Solicitar un plan por fases sin citar normas reales no proporcionadas. Revisar y aprobar las tareas propuestas en Planner; si el agente no conserva las dependencias, registrarlas manualmente.

**Prompt — Actualización regulatoria simulada**

```text
Necesitamos actualizar un procedimiento interno de verificación de clientes ante un nuevo requisito simulado, NO una norma real. Plan de 02/11/2026 a 27/11/2026. Ordena: inventario de procesos, análisis de brechas, revisión de Riesgos, redacción de Operaciones, adecuación de Tecnología, pruebas, aprobación de Cumplimiento y publicación. Explica precedencias, área responsable, evidencia de finalizacion y punto de control. Crea las tareas admitidas en el plan.
```

#### Tarea 2. Elaborar una matriz de cumplimiento

**Paso 1.** Pedir al agente una matriz con columnas ID, Requisito simulado, Control, Área, Evidencia, Estado, Dependencia y Fecha meta; exigir que no atribuya obligaciones a reguladores reales.

**Paso 2.** Abrir Word, crear un documento llamado LAB-Matriz-Cumplimiento y pegar la matriz con un título y una nota que identifique el escenario como ejercicio.

#### Tarea 3. Revisar la coherencia

**Paso 1.** Contrastar la precedencia de aprobación de Cumplimiento con la tarea de publicación en Planner y comprobar que no se publique antes de la aprobación.

**Paso 2.** Guardar el documento Word y el plan con estados iniciales Pendiente o No iniciado.

#### Resultado esperado

Plan con secuencia de ocho etapas y matriz de cumplimiento en Word; cada fila contiene un área, evidencia y fecha, sin afirmaciones sobre regulación vigente.

[Volver a las prácticas del módulo](#practicas-del-modulo) | [Índice del curso](../) | [Consultar la Setup Guide](../setup/)

---

<a id="practica-04"></a>

## Práctica 4. Plan de implementación de un servicio para clientes empresariales

### Objetivo de la práctica:

Al finalizar la práctica, serás capaz de:

- Estructurar un despliegue de e-banca Empresarial.
- Convertir la hoja de ruta en una presentación de PowerPoint.

### Duración aproximada:

- 6 minutos.

### Tabla de ayuda:

| Parámetro | Valor | Uso |
| --- | --- | --- |
| Plan | LAB-EMP-Servicio | Plan base para la práctica 5 |
| Servicio | Pagos por lotes | Funcion propuesta |
| Salida prevista | 06/11/2026 | Fecha inicial |

### Instrucciones

#### Tarea 1. Establecer la hoja de ruta

**Paso 1.** Abrir Planner, crear el plan LAB-EMP-Servicio y acceder a Planner Agent.

**Paso 2.** Solicitar el plan de implementación, comprobar el orden de sus fases y aprobar las tareas antes de guardarlas en el plan. Completar manualmente asignaciones y dependencias no admitidas por el agente.

**Prompt — Implementación de servicio empresarial**

```text
Crea un plan de implementación para habilitar pagos por lotes en e-banca Empresarial con salida prevista 06/11/2026. Incluir desarrollo, integración, pruebas funcionales, pruebas de seguridad, aprobación de Cumplimiento, capacitación, comunicación y puesta en marcha. Para cada etapa indica responsable por área, fecha, dependencia, criterio de salida y entregable. Mantener todas las tareas inicialmente pendientes.
```

#### Tarea 2. Preparar la presentación

**Paso 1.** Solicitar al agente una hoja de ruta ejecutiva de tres diapositivas con objetivos, cronograma y responsables, incluyendo solo información creada para este proyecto.

**Paso 2.** Abrir PowerPoint y usar Copilot para transformar el contenido en tres diapositivas; si el agente de PowerPoint esta disponible, usarlo para crear el archivo a partir del texto revisado.

#### Tarea 3. Verificar la correspondencia

**Paso 1.** Comparar la fecha de puesta en marcha y las dependencias críticas entre PowerPoint y Planner.

**Paso 2.** Guardar la presentación como LAB-Hoja-Ruta-EMP.pptx y dejar el plan disponible para la práctica 5.

#### Resultado esperado

Plan LAB-EMP-Servicio en Planner y una presentación PowerPoint de tres diapositivas consistente con fases, fechas y responsables del plan.

[Volver a las prácticas del módulo](#practicas-del-modulo) | [Índice del curso](../) | [Consultar la Setup Guide](../setup/)

---

<a id="practica-05"></a>

## Práctica 5. Replanificación de un proyecto ante cambios operativos

### Objetivo de la práctica:

Al finalizar la práctica, serás capaz de:

- Actualizar el plan de e-banca Empresarial ante retrasos y nuevos requisitos.
- Comunicar los cambios y decisiones pendientes por correo.

### Duración aproximada:

- 7 minutos.

### Tabla de ayuda:

| Parámetro | Valor | Uso |
| --- | --- | --- |
| Plan previo | LAB-EMP-Servicio | Creado en práctica 4 |
| Retraso | Prueba de seguridad +4 días | Cambio simulado |
| Cambio | Verificación KYC reforzada | Requisito adicional |
| Fecha revisada | 13/11/2026 | Fecha meta solicitada |

### Instrucciones

#### Tarea 1. Examinar el plan de origen

**Paso 1.** Abrir en Planner el plan LAB-EMP-Servicio de la práctica 4, seleccionar la vista de cronograma o lista y localizar tareas de pruebas, cumplimiento y salida.

**Paso 2.** Abrir Planner Agent y enviar el escenario de cambio.

**Prompt — Replanificar sin omitir controles**

```text
En el plan LAB-EMP-Servicio hay un retraso de cuatro días en pruebas de seguridad y Cumplimiento agrego una verificación KYC reforzada que exige revisión antes de la salida. Reprograma las tareas afectadas, conserva la dependencia de la aprobación de Cumplimiento y propone fecha meta 13/11/2026. Identifica actividades críticas, cambios de responsables por área y dos acciones para reducir impacto sin suprimir pruebas. No presentes una ruta crítica calculada si el plan no tiene dependencias formalizadas. Actualiza los campos que Planner Agent permita editar; muestra los que requieran ajuste manual.
```

#### Tarea 2. Actualizar y verificar tareas

**Paso 1.** Revisar las tarjetas de actualización propuestas por el agente y aprobar los cambios. Comprobar en Planner que pruebas de seguridad, KYC, aprobación y puesta en marcha reflejen el orden nuevo; editar manualmente los campos no modificables por el agente.

**Paso 2.** Solicitar al agente un resumen Antes/Después con fecha anterior, fecha nueva, motivo y decisión pendiente.

#### Tarea 3. Preparar aviso ejecutivo

**Paso 1.** Pedir un correo de no más de 170 palabras dirigido al comité de proyecto: causa, impacto, nueva fecha, mitigaciones y decisión de aprobación requerida.

**Paso 2.** Abrir Outlook, crear un borrador, pegar el asunto y texto, verificar que no existan destinatarios reales y no enviar el mensaje.

#### Resultado esperado

Plan LAB-EMP-Servicio actualizado con nuevas fechas y dependencias; resumen del cambio y borrador de correo ejecutivo sin envío real.

[Volver a las prácticas del módulo](#practicas-del-modulo) | [Índice del curso](../) | [Consultar la Setup Guide](../setup/)


---

[Índice del curso](../) | [Módulo siguiente](../Capitulo02/)
