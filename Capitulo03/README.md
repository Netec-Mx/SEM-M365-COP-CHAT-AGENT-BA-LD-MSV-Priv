---
permalink: /Capitulo03/
---

# Módulo 3. Scrum Assistant: gestión ágil y mejora continua de equipos

**Duración del módulo:** 36 minutos. **Explicación:** 4 minutos. **Prácticas:** 32 minutos.

**Contexto del módulo:** Las prácticas siguen un mismo producto y un sprint simulado. Las fechas, los estados de las historias y los resultados cambian entre ejercicios como parte de la secuencia de trabajo; no representan registros reales de Planner.

<a id="practicas-del-modulo"></a>

## Prácticas del módulo

- [Práctica 11. Planificación de un sprint para mejorar Banca Móvil](#practica-11) — 6 min.
- [Práctica 12. Organización y priorización del Product Backlog](#practica-12) — 6 min.
- [Práctica 13. Identificación y resolución de impedimentos durante un sprint](#practica-13) — 5 min.
- [Práctica 14. Preparación de una Sprint Review](#practica-14) — 5 min.
- [Práctica 15. Evaluación de un sprint y elaboración de un plan de mejora continua](#practica-15) — 10 min.

---

<a id="practica-11"></a>

## Práctica 11. Planificación de un sprint para mejorar Banca Móvil

### Objetivo de la práctica:

Al finalizar la práctica, serás capaz de:

- Definir objetivo y alcance de un sprint de dos semanas.
- Organizar actividades por estado y capacidad del equipo.

### Duración aproximada:

- 6 minutos.

### Tabla de ayuda:

| Parámetro | Valor | Uso |
| --- | --- | --- |
| Sprint | LAB-SPRINT-01 | Sprint simulado |
| Ventana | 02-13/11/2026 | Dos semanas |
| Capacidad | 24 puntos de historia | Limite estimado del equipo |

### Instrucciones

#### Tarea 1. Establecer el objetivo del sprint

**Paso 1.** Abrir Microsoft 365 Copilot y seleccionar AG-Scrum-Assistant-LAB.

**Paso 2.** Enviar el contexto con capacidad y backlog inicial.

**Prompt — Sprint de Banca Móvil**

```text
Planifica sprint LAB-SPRINT-01 del 02 al 13/11/2026 para mejorar Banca Móvil, con capacidad de 24 puntos. Backlog: HU-01 consulta de movimientos (8 puntos, valor alto); HU-02 notificaciones de transferencias (5, alto); HU-03 accesibilidad de botones (3, alto); HU-04 acceso biometrico (13, alto); HU-05 exportar movimientos (5, medio, depende de HU-01); HU-06 ayuda contextual (8, medio); HU-07 mensajes de error más claros (3, alto); HU-08 alerta de transferencia (8, medio, depende de HU-02). Mantiene como compromiso inicial HU-01 (8), HU-02 (5), HU-03 (3), HU-05 (5) y HU-07 (3): total 24 puntos. No seleccionar otras historias. Formula objetivo medible sin atribuir capacidad a personas reales.
```

#### Tarea 2. Crear el tablero de sprint

**Paso 1.** Solicitar al agente tareas necesarias para las historias elegidas, con ID, descripción, estimación, responsable por rol y estado inicial Pendiente.

**Paso 2.** Pedir una tabla tipo tablero con columnas Pendiente, En progreso, En revisión y Completado y colocar las actividades iniciales únicamente en Pendiente.

#### Tarea 3. Preparar la salida para Excel

**Paso 1.** Solicitar también la misma información en tabla plana ID-Historia-Tarea-Estado-Puntos-Responsable y copiarla a Excel. Verificar los **24 puntos sobre historias únicas**, no sumando de nuevo los puntos de cada subtarea en que se haya dividido una historia.

**Paso 2.** Guardar el tablero como LAB-Tablero-Sprint.xlsx y corroborar que no aparezcan tareas ficticiamente completadas.

#### Resultado esperado

Objetivo medible del sprint, conjunto de historias ajustado a 24 puntos y tablero con cuatro estados; tabla exportable a Excel.

[Volver a las prácticas del módulo](#practicas-del-modulo) | [Índice del curso](../) | [Consultar la Setup Guide](../setup/)

---

<a id="practica-12"></a>

## Práctica 12. Organización y priorización del Product Backlog

### Objetivo de la práctica:

Al finalizar la práctica, serás capaz de:

- Ordenar historias de usuario por valor, esfuerzo y dependencias.
- Producir un Product Backlog tabular que pueda abrirse en Excel.

### Duración aproximada:

- 6 minutos.

### Tabla de ayuda:

| Parámetro | Valor | Uso |
| --- | --- | --- |
| Producto | Banca Móvil | Contexto del backlog |
| Unidad | Puntos de historia | Esfuerzo relativo |
| Capacidad sprint | 24 puntos | Dato de priorización |

### Instrucciones

#### Tarea 1. Proporcionar solicitudes de mejora

**Paso 1.** Abrir AG-Scrum-Assistant-LAB y enviar el backlog de ocho historias con sus puntos y valor.

**Prompt — Priorizar Product Backlog**

```text
Organiza el Product Backlog de Banca Móvil para estas solicitudes: HU-01 consulta de movimientos (valor alto, 8 puntos), HU-02 notificaciones (alto, 5), HU-03 accesibilidad (alto, 3), HU-04 biometría (alto, 13), HU-05 exportación de movimientos (medio, 5, depende HU-01), HU-06 ayuda contextual (medio, 8), HU-07 errores comprensibles (alto, 3), HU-08 alertas de transferencia (medio, 8, depende HU-02). Escribe una historia de usuario en formato Como/quiero/para por item, propuesta de prioridad P1/P2/P3 y criterio de aceptación verificable. Explica la prioridad sin crear historias nuevas.
```

**Paso 2.** Verificar que se mantengan los ocho IDs, los puntos originales y las dependencias HU-05/HU-01 y HU-08/HU-02. Solicitar una corrección si el agente prioriza una historia dependiente sin considerar su predecesora.

#### Tarea 2. Ordenar y preparar el backlog

**Paso 1.** Solicitar tabla final con columnas Prioridad, ID, Historia, Valor, Puntos, Dependencia y Criterio de aceptación.

**Paso 2.** Copiar la tabla a Excel, ordenar por Prioridad y revisar que las dependencias no propongan desarrollar antes una historia bloqueada.

#### Tarea 3. Validar el resultado

**Paso 1.** Guardar LAB-Product-Backlog.xlsx y comprobar que las ocho historias esten presentes sin alteraciones de esfuerzo.

**Paso 2.** Identificar en el propio Excel las historias candidatas para un sprint de 24 puntos, sin afirmar que el Product Owner aprobo ese orden.

#### Resultado esperado

Product Backlog en Excel con ocho historias identificadas, criterios de aceptación, prioridades y dependencias consistentes.

[Volver a las prácticas del módulo](#practicas-del-modulo) | [Índice del curso](../) | [Consultar la Setup Guide](../setup/)

---

<a id="practica-13"></a>

## Práctica 13. Identificación y resolución de impedimentos durante un sprint

### Objetivo de la práctica:

Al finalizar la práctica, serás capaz de:

- Identificar bloqueos de trabajo del sprint y sus impactos.
- Preparar un correo con decisiones necesarias para el líder de proyecto.

### Duración aproximada:

- 5 minutos.

### Tabla de ayuda:

| Parámetro | Valor | Uso |
| --- | --- | --- |
| Sprint | LAB-SPRINT-01 | 02-13/11/2026 |
| HU bloqueadas | HU-01, HU-05 | Dependencia de API |
| Validación pendiente | HU-02 | Pruebas de notificaciones |

### Instrucciones

#### Tarea 1. Analizar la situación del sprint

**Paso 1.** Abrir AG-Scrum-Assistant-LAB y suministrar el estado del equipo.

**Prompt — Impedimentos del sprint**

```text
Dia 6 del sprint LAB-SPRINT-01 (02-13/11): HU-03 accesibilidad esta completada; HU-07 errores claros esta en revisión; HU-01 consulta de movimientos esta bloqueada 2 días por respuestas intermitentes de API; HU-05 exportación depende de HU-01 y no puede iniciar pruebas; HU-02 notificaciones tiene 3 casos fallidos en QA; quedan 5 días laborales. Identifica impedimentos, historias afectadas, riesgo sobre objetivo de sprint y acciones concretas con área responsable. No asegures que los impedimentos ya están solucionados.
```

**Paso 2.** Revisar que la respuesta diferencie causa (API/QA) de consecuencias (HU-05 bloqueada, riesgo de entrega).

#### Tarea 2. Priorizar acciones y redactar la alerta

**Paso 1.** Solicitar una propuesta de tres acciones en orden de urgencia, cada una con responsable, criterio de desbloqueo y fecha de seguimiento.

**Paso 2.** Solicitar un correo ejecutivo de máximo 150 palabras dirigido al líder del proyecto que exponga bloqueo, impacto y una decisión requerida.

#### Tarea 3. Preparar el mensaje en Outlook

**Paso 1.** Abrir Outlook, crear un nuevo borrador con asunto LAB-SPRINT-01: impedimentos críticos y copiar el cuerpo revisado.

**Paso 2.** Comprobar que el correo no indique una resolución no lograda ni incluya destinatarios reales; conservarlo como borrador.

#### Resultado esperado

Análisis de impedimentos con responsables y criterios de desbloqueo, y borrador de correo coherente con el escenario.

[Volver a las prácticas del módulo](#practicas-del-modulo) | [Índice del curso](../) | [Consultar la Setup Guide](../setup/)

---

<a id="practica-14"></a>

## Práctica 14. Preparación de una Sprint Review

### Objetivo de la práctica:

Al finalizar la práctica, serás capaz de:

- Estructurar una Sprint Review basada en avances comprobables.
- Crear en Forms preguntas de retroalimentación para el negocio.

### Duración aproximada:

- 5 minutos.

### Tabla de ayuda:

| Parámetro | Valor | Uso |
| --- | --- | --- |
| Sprint | LAB-SPRINT-01 | Escenario de Banca Móvil |
| Avances | HU-03 y HU-07 terminadas; HU-01 en validación | Estado al momento de review |
| Salida | Microsoft Forms | Formulario de retroalimentación |

### Instrucciones

#### Tarea 1. Preparar la review

**Paso 1.** Abrir AG-Scrum-Assistant-LAB y solicitar una agenda de 15 minutos para la reunión simulada.

**Prompt — Agenda de Sprint Review**

```text
Prepara Sprint Review de Banca Móvil. HU-03 accesibilidad y HU-07 mensajes de error se terminaron; HU-01 consulta de movimientos está en validación; HU-02 notificaciones sigue en pruebas, HU-05 exportar movimientos no está terminado. Construye una agenda breve: objetivo, demostraciones permitidas (solo HU-03 y HU-07), trabajo no finalizado, preguntas a negocio y acuerdos siguientes. No presentar HU-01, HU-02 o HU-05 como terminadas.
```

**Paso 2.** Verificar que las demostraciones solo incluyan las historias terminadas.

#### Tarea 2. Diseñar preguntas para interesados

**Paso 1.** Solicitar cuatro preguntas: utilidad de mejoras, claridad de mensajes, facilidad de uso y una pregunta abierta de prioridades.

**Paso 2.** Abrir la sección Crear de Copilot para generar un formulario si la opción aparece; si no, entrar a Microsoft Forms, elegir Nuevo formulario y crear manualmente las cuatro preguntas revisadas.

#### Tarea 3. Mostrar la vista previa

**Paso 1.** Asignar título LAB-SprintReview-Feedback, configurar tipo de respuesta apropiado para cada pregunta y abrir Vista previa.

**Paso 2.** Responder una prueba en la vista previa sin distribuir el formulario a personas reales.

#### Resultado esperado

Agenda de Sprint Review fiel al avance y formulario de cuatro preguntas con vista previa funcional.

[Volver a las prácticas del módulo](#practicas-del-modulo) | [Índice del curso](../) | [Consultar la Setup Guide](../setup/)

---

<a id="practica-15"></a>

## Práctica 15. Evaluación de un sprint y elaboración de un plan de mejora continua

### Objetivo de la práctica:

Al finalizar la práctica, serás capaz de:

- Analizar el cumplimiento del sprint y causas de desviaciones.
- Proponer y visualizar acciones de mejora verificables.

### Duración aproximada:

- 10 minutos.

### Tabla de ayuda:

| Parámetro | Valor | Uso |
| --- | --- | --- |
| Sprint | LAB-SPRINT-01 | Dos semanas |
| Comprometidos | 24 puntos | Capacidad acordada |
| Completados | 14 puntos | HU-01 8, HU-03 3, HU-07 3 |
| Pendientes | 10 puntos | HU-02 5 y HU-05 5 |

### Instrucciones

#### Tarea 1. Examinar resultados de la iteración

**Paso 1.** Abrir AG-Scrum-Assistant-LAB y introducir la retrospectiva simulada.

**Prompt — Evaluación de sprint**

```text
Sprint LAB-SPRINT-01 comprometió 24 puntos y completo 14: HU-01 (8), HU-03 (3), HU-07 (3). HU-02 (5) quedó pendiente por fallos de notificación y HU-05 (5) no concluyo por dependencia de HU-01. En la semana 1 hubo bloqueo de API de 2 días; coordinación entre QA y Tecnología ocurrió tarde; se agrego un ajuste menor a los criterios de aceptación. Evalua resultados, porcentaje de puntos completados y 3 causas probables sin afirmarlas como hechos; formula preguntas para validar causas en retrospectiva.
```

**Paso 2.** Comprobar que 14/24 corresponde aproximadamente a 58,3 % de puntos completados y que los 10 puntos restantes se describen como pendientes.

#### Tarea 2. Construir plan de mejora continua

**Paso 1.** Solicitar un plan con no más de cinco acciones priorizadas, responsable por rol, fecha objetivo dentro del siguiente sprint y criterio objetivo para saber si funcionó.

**Paso 2.** Revisar que al menos una acción trate coordinación QA-Tecnología y otra las dependencias entre historias; exigir para cada una un criterio observable de cumplimiento y descartar compromisos imposibles de validar.

#### Tarea 3. Visualizar y verificar el plan

**Paso 1.** Abrir Crear de Copilot, elegir Infografía si está disponible y proporcionar el plan con el título LAB-Mejora-Continua; si no aparece la opción, estructurar visualmente el plan en una página de Word.

**Paso 2.** Verificar que la infografía o página incluya acciones, responsables, fechas y criterios, y que se mantengan los datos 24, 14 y 10 sin cambiarlos.

#### Resultado esperado

Plan de mejora continua con acciones priorizadas y criterios medibles; visualización de una página basada en 14 de 24 puntos completados.

[Volver a las prácticas del módulo](#practicas-del-modulo) | [Índice del curso](../) | [Consultar la Setup Guide](../setup/)


---

[Módulo anterior](../Capitulo02/) | [Índice del curso](../) | [Módulo siguiente](../Capitulo04/)
