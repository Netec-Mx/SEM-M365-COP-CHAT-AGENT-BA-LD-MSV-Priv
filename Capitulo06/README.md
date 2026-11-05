---
permalink: /Capitulo06/
---

# Módulo 6. Agente de Encuestas: recopilación y análisis de información

**Duración del módulo:** 21 minutos. **Explicación:** 3 minutos. **Prácticas:** 18 minutos.

**Contexto del módulo:** Se utiliza Copilot integrado en Microsoft Forms porque el antiguo agente Surveys fue retirado. Los datos del archivo Excel son independientes de las respuestas de cualquier formulario creado durante el seminario.

<a id="practicas-del-modulo"></a>

## Prácticas del módulo

- [Práctica 23. Diseño de una encuesta de satisfacción sobre canales digitales](#practica-23) — 5 min.
- [Práctica 24. Análisis de respuestas y generación de hallazgos](#practica-24) — 5 min.
- [Práctica 25. Diseño de una encuesta dinámica para evaluar un nuevo producto financiero](#practica-25) — 8 min.

---

<a id="practica-23"></a>

## Práctica 23. Diseño de una encuesta de satisfacción sobre canales digitales

### Objetivo de la práctica:

Al finalizar la práctica, serás capaz de:

- Diseñar preguntas de satisfacción de Banca Móvil con distintos tipos de respuesta.
- Crear el formulario y comprobar su vista previa.

### Duración aproximada:

- 5 minutos.

### Tabla de ayuda:

| Parámetro | Valor | Uso |
| --- | --- | --- |
| Herramienta | Microsoft Forms con Copilot | Reemplazo oficial del agente Encuestas retirado |
| Título | LAB-Satisfaccion-Banca-Movil | Formulario nuevo |
| Escala | 1 a 5 | Satisfacción, claridad y facilidad |

### Instrucciones

#### Tarea 1. Generar el primer borrador

**Paso 1.** Abrir https://forms.office.com con la cuenta de Microsoft 365 Copilot y seleccionar Nuevo formulario.

**Paso 2.** Describir en el cuadro de Copilot de Forms el objetivo y generar un primer borrador.

**Prompt — Encuesta Banca Móvil**

```text
Crea una encuesta anónima de satisfacción sobre Banca Móvil. Pregunta 1: canal utilizado (Banca Móvil o E-banca). Preguntas 2-4: facilidad de uso, claridad de operaciones y satisfacción general, con escalas de 1 a 5. Pregunta 5: problema principal (Ninguno, Inicio de sesión, Navegacion, Notificaciones, Tiempo de respuesta). Pregunta 6: comentario abierto opcional. No solicitar nombres, cuentas, identificaciones ni datos personales.
```

**Paso 3.** Seleccionar Conservar o mantener borrador y revisar las seis preguntas propuestas.

#### Tarea 2. Configurar y verificar la encuesta

**Paso 1.** Asignar título LAB-Satisfaccion-Banca-Movil y comprobar que cada pregunta tenga el tipo correcto: opción, valoracion o texto según corresponda.

**Paso 2.** Abrir Vista previa en escritorio y móvil y verificar orden, claridad y obligatoriedad de las preguntas principales.

#### Tarea 3. Dejar disponible el instrumento

**Paso 1.** Guardar el formulario dentro de Microsoft Forms y no distribuirlo a clientes reales.

**Paso 2.** Anotar la URL del propio formulario en un lugar de trabajo autorizado para continuar el seminario.

#### Resultado esperado

Formulario de seis preguntas guardado en Microsoft Forms con escala 1-5, categorías de problema y vista previa revisada.

> **Nota de vigencia:** El agente Microsoft Surveys fue retirado en 2026. Esta práctica usa Copilot integrado en Forms, indicado oficialmente como experiencia sucesora.

[Volver a las prácticas del módulo](#practicas-del-modulo) | [Índice del curso](../) | [Consultar la Setup Guide](../setup/)

---

<a id="practica-24"></a>

## Práctica 24. Análisis de respuestas y generación de hallazgos

### Objetivo de la práctica:

Al finalizar la práctica, serás capaz de:

- Analizar respuestas sobre satisfacción en canales digitales.
- Generar una tabla de hallazgos y un gráfico comprobable en Excel.

### Duración aproximada:

- 5 minutos.

### Tabla de ayuda:

| Parámetro | Valor | Uso |
| --- | --- | --- |
| Fuente | Respuestas_Canales_Digitales.xlsx | 36 respuestas simuladas |
| Campos | Facilidad, Claridad, Satisfacción, Problema | Variables de análisis |
| Salida | LAB-Hallazgos-Canales.xlsx | Reporte en Excel |

### Instrucciones

#### Tarea 1. Abrir los datos de respuestas

**Paso 1.** Descargar Respuestas_Canales_Digitales.xlsx y abrir la hoja Respuestas en Excel.

**Paso 2.** Verificar que existan 36 registros R-001 a R-036, escalas 1-5 y la columna Problema; no confundir este archivo con respuestas ya recolectadas en Forms.

#### Tarea 2. Analizar con Copilot

**Paso 1.** Abrir Copilot en Excel cuando esté habilitado o adjuntar el libro en Microsoft 365 Copilot para analizar la hoja Respuestas.

**Paso 2.** Enviar la siguiente instrucción, limitando el análisis a las 36 filas.

**Prompt — Hallazgos de satisfacción**

```text
Analiza únicamente las 36 respuestas de la hoja Respuestas: calcula promedio de Satisfaccion_1a5, número de respuestas por Problema, porcentaje de valores de satisfacción 4 o 5, y compara Banca Móvil frente a E-banca. Identifica las categorías de problema más frecuentes y distingue `Ninguno` de las incidencias reportadas. Para priorizar problemas, excluye `Ninguno` del orden de fallas e informa los empates sin inventar un ranking exclusivo de tres categorías. Sintetiza oportunidades de mejora sustentadas en los comentarios. Devuelve una tabla de indicador/valor/interpretación y otra de problema/recuento. No agregues respuestas, no inventes tendencias y no calcules NPS a partir de escalas 1 a 5.
```

**Paso 3.** Contrastar con Excel los resultados: 36 respuestas, promedio de satisfacción **3,33/5**, **15 de 36** respuestas con satisfacción 4 o 5 (**41,7 %**), `Ninguno` con 12 registros y cuatro categorías de problema empatadas con 6 registros cada una. Utilizar una tabla dinámica o `CONTAR.SI` para comprobar los recuentos. Esta escala no permite calcular un NPS.

#### Tarea 3. Crear el gráfico y guardar el reporte

**Paso 1.** Copiar la tabla Problema/Recuento a una nueva hoja denominada Hallazgos, seleccionar las celdas e insertar un gráfico de barras.

**Paso 2.** Agregar título **Problemas reportados**, revisar etiquetas y conservar las cinco categorías de la fuente, incluido `Ninguno`; no eliminar categorías empatadas. Guardar el libro como `LAB-Hallazgos-Canales.xlsx`.

#### Resultado esperado

Libro Excel con 36 respuestas originales, indicadores calculados, tabla de frecuencias y gráfico de barras validado frente a los datos.

**Recurso de esta práctica:** [Respuestas_Canales_Digitales.xlsx](../recursos/Respuestas_Canales_Digitales.xlsx).

> **Nota de vigencia:** Los registros de ejemplo no pueden importarse automáticamente como respuestas de un formulario de Forms; se analizan como archivo en Excel y Copilot.

[Volver a las prácticas del módulo](#practicas-del-modulo) | [Índice del curso](../) | [Consultar la Setup Guide](../setup/)

---

<a id="practica-25"></a>

## Práctica 25. Diseño de una encuesta dinámica para evaluar un nuevo producto financiero

### Objetivo de la práctica:

Al finalizar la práctica, serás capaz de:

- Diseñar una encuesta de financiamiento para tres perfiles de pymes.
- Configurar y probar ramificaciones de Forms mediante respuestas distintas.

### Duración aproximada:

- 8 minutos.

### Tabla de ayuda:

| Parámetro | Valor | Uso |
| --- | --- | --- |
| Formulario | LAB-Necesidades-Financiamiento | Formulario de evaluación |
| Perfiles | Microempresa, Pequeña, Mediana | Tres rutas |
| Regla | Solo saltar hacia preguntas posteriores | Limite de Forms |

### Instrucciones

#### Tarea 1. Diseñar un cuestionario por perfil

**Paso 1.** Abrir Microsoft Forms, seleccionar Nuevo formulario y generar un borrador con Copilot integrado.

**Paso 2.** Solicitar que preserve este orden de ocho preguntas para poder ramificar después.

**Prompt — Encuesta dinámica pymes**

```text
Crea un cuestionario sobre interes en un producto de financiamiento para pymes sin pedir datos personales. Orden exacto: P1 Perfil (Microempresa, Pequeña empresa, Mediana empresa); P2 Micro: propósito del crédito (capital de trabajo/equipamiento); P3 Micro: rango de financiamiento (menos de USD 10000 / USD 10000-30000); P4 Pequeña: propósito (inventario/expansion); P5 Pequeña: rango (USD 30000-100000 / más de USD 100000); P6 Mediana: propósito (inversión productiva/refinanciamiento); P7 Mediana: rango (USD 100000-250000 / más de USD 250000); P8 Preferencia de canal de contacto (digital/presencial). Las preguntas P2-P7 son de opción, P8 es comun a todos. No solicites nombre, identificación, cuenta ni información financiera privada.
```

**Paso 3.** Revisar el borrador y ordenar manualmente las preguntas si Copilot cambia su secuencia.

#### Tarea 2. Configurar las rutas en Forms

**Paso 1.** Abrir P1 > Más opciones > Agregar ramificación y configurar Microempresa hacia P2, Pequeña hacia P4 y Mediana hacia P6.

**Paso 2.** Establecer saltos a P8 al terminar P3, P5 y P7. Mantener la secuencia P2 > P3, P4 > P5 y P6 > P7, y enviar P8 al final del formulario. Comprobar que los saltos sean solo hacia preguntas posteriores.

#### Tarea 3. Probar las tres rutas

**Paso 1.** Seleccionar Vista previa, responder Microempresa y verificar que solo aparecen P2, P3 y P8 después de P1.

**Paso 2.** Repetir para Pequeña (P4, P5 y P8) y Mediana (P6, P7 y P8); corregir ramificaciones que muestren preguntas de otros perfiles.

#### Tarea 4. Conservar el formulario

**Paso 1.** Guardar LAB-Necesidades-Financiamiento, comprobar que P8 aparezca en todas las rutas y mantenerlo sin distribución externa.

#### Resultado esperado

Encuesta Forms guardada con tres recorridos excluyentes y una pregunta final comun; vista previa probada con cada perfil.

> **Nota de vigencia:** El agente Microsoft Surveys fue retirado en 2026. La ramificación se configura en Forms; Copilot puede proponer preguntas, pero no se supone que configure automáticamente las rutas.

[Volver a las prácticas del módulo](#practicas-del-modulo) | [Índice del curso](../) | [Consultar la Setup Guide](../setup/)


---

[Módulo anterior](../Capitulo05/) | [Índice del curso](../)
