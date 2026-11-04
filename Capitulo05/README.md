---
permalink: /Capitulo05/
---

# Módulo 5. Text Translator: traducción y adaptación de información para diferentes áreas del banco

**Duración del módulo:** 21 minutos. **Explicación:** 3 minutos. **Prácticas:** 18 minutos.

**Contexto del módulo:** Se trabaja con un paquete en inglés que incluye un texto técnico, condiciones comerciales, recomendaciones de seguridad y un extracto financiero. Conservar cifras, unidades, condiciones contractuales y terminología especializada.

<a id="practicas-del-modulo"></a>

## Prácticas del módulo

- [Práctica 20. Traducción de documentación técnica de un proveedor internacional](#practica-20) — 5 min.
- [Práctica 21. Traducción y adaptación de un informe financiero internacional](#practica-21) — 5 min.
- [Práctica 22. Traducción y adaptación de un paquete de información internacional para diferentes áreas del banco](#practica-22) — 8 min.

---

<a id="practica-20"></a>

## Práctica 20. Traducción de documentación técnica de un proveedor internacional

### Objetivo de la práctica:

Al finalizar la práctica, serás capaz de:

- Traducir una especificación técnica al español sin alterar requisitos.
- Comprobar la consistencia de términos, cifras y encabezados.

### Duración aproximada:

- 5 minutos.

### Tabla de ayuda:

| Parámetro | Valor | Uso |
| --- | --- | --- |
| Fuente | Paquete_Proveedor_EN.docx | Documento A |
| Idioma | Inglés a español | Dirección de traducción |
| Producto | Gateway de notificaciones | Escenario |

### Instrucciones

#### Tarea 1. Seleccionar texto de origen

**Paso 1.** Abrir el archivo Paquete_Proveedor_EN.docx y localizar Documento A - Technical specification.

**Paso 2.** Copiar los dos párrafos técnicos de Documento A sin incluir el material comercial o el financiero.

#### Tarea 2. Traducir con terminología controlada

**Paso 1.** Abrir AG-Text-Translator-LAB, pegar el texto copiado y enviar la solicitud.

**Prompt — Traducción técnica**

```text
Traduce el Documento A al español para Tecnología y Operaciones. Conserva los dos párrafos y sus requisitos concretos; no omitas TLS 1.3, REST, clave de idempotencia, acuse de recibo, permisos por rol y conciliacion de fallos. Usa terminología natural en español y conserva en parentesis los términos técnicos ingleses cuando ayuden. No agregues funcionalidades ni supongas acceso al entorno real.
```

**Paso 2.** Solicitar al agente una lista breve de equivalencias para `idempotency key`, `acknowledgment identifier`, `role-based access` y `delivery receipt`. Mantener `TLS 1.3` y `REST` sin cambios como nombres técnicos.

#### Tarea 3. Revisar y guardar el resultado

**Paso 1.** Comparar la traducción con el original y verificar que los requisitos obligatorios no se transformen en recomendaciones.

**Paso 2.** Abrir Word, pegar la traducción, conservar los encabezados y guardar LAB-Traduccion-Tecnica.docx.

#### Resultado esperado

Documento Word en español con dos párrafos técnicos completos, requisitos conservados y terminología revisada.

**Recurso de esta práctica:** [Paquete_Proveedor_EN.docx](../recursos/Paquete_Proveedor_EN.docx).

[Volver a las prácticas del módulo](#practicas-del-modulo) | [Índice del curso](../) | [Consultar la Setup Guide](../setup/)

---

<a id="practica-21"></a>

## Práctica 21. Traducción y adaptación de un informe financiero internacional

### Objetivo de la práctica:

Al finalizar la práctica, serás capaz de:

- Traducir cifras y proyecciones económicas sin alterar su naturaleza.
- Adaptar el lenguaje para una ficha informativa de una página.

### Duración aproximada:

- 5 minutos.

### Tabla de ayuda:

| Parámetro | Valor | Uso |
| --- | --- | --- |
| Fuente de laboratorio | Paquete_Proveedor_EN.docx | Documento D |
| Fuente pública | [FMI — WEO, octubre 2026](https://www.imf.org/en/Publications/WEO/Issues/2026/10/13/world-economic-outlook-october-2026) | Contraste de proyecciones |
| Cifras | 3,1 %; 3,4 %; 4,7 %; 4,1 % | Valores de referencia |
| Fecha de informe | 13/10/2026 | Publicacion de referencia |

### Instrucciones

#### Tarea 1. Preparar el fragmento de informe

**Paso 1.** Abrir Paquete_Proveedor_EN.docx y copiar el Documento D, que parafrasea datos publicos del World Economic Outlook de octubre de 2026.

**Paso 2.** Abrir AG-Text-Translator-LAB y enviar el fragmento junto con las instrucciones.

**Prompt — Traducción de perspectivas macroeconomicas**

```text
Traduce este fragmento financiero al español para personal de un banco, conservando exactamente las proyecciones 3.1 % crecimiento global 2026, 3.4 % 2027, 4.7 % inflación global 2026 y 4.1 % 2027. Explica en lenguaje claro la diferencia entre una proyección y un hecho observado, sin presentar las cifras como indicadores exclusivos de El Salvador o de Banco Agricola. Identifica la fuente como FMI, World Economic Outlook, octubre 2026.
```

#### Tarea 2. Crear la ficha informativa

**Paso 1.** Solicitar un título, cuatro indicadores con su período, dos ideas de interpretación y una conclusión de máximo 50 palabras; incluir URL de la fuente pública.

**Paso 2.** Abrir Word, pegar el resultado en una página y revisar que no se confundan crecimiento con inflación.

#### Tarea 3. Verificar la información

**Paso 1.** Contrastar las cuatro cifras y la referencia al FMI con el Documento D original.

**Paso 2.** Guardar LAB-Ficha-Financiera.docx con título, fecha, cifras, interpretaciones y enlace a la fuente.

#### Resultado esperado

Ficha Word de una página en español con cuatro indicadores sin cambios, descripción de proyecciones y fuente identificada.

**Recurso de esta práctica:** [Paquete_Proveedor_EN.docx](../recursos/Paquete_Proveedor_EN.docx).

[Volver a las prácticas del módulo](#practicas-del-modulo) | [Índice del curso](../) | [Consultar la Setup Guide](../setup/)

---

<a id="practica-22"></a>

## Práctica 22. Traducción y adaptación de un paquete de información internacional para diferentes áreas del banco

### Objetivo de la práctica:

Al finalizar la práctica, serás capaz de:

- Traducir textos técnico, comercial y de seguridad para tres audiencias.
- Resolver ambigüedades y construir un glosario bilingüe consistente.

### Duración aproximada:

- 8 minutos.

### Tabla de ayuda:

| Parámetro | Valor | Uso |
| --- | --- | --- |
| Fuente | Paquete_Proveedor_EN.docx | Documentos A, B y C |
| Audiencias | Tecnología, Compras y Riesgos | Áreas receptoras |
| Entregable | Documento Word consolidado | Tres traducciones y glosario |

### Instrucciones

#### Tarea 1. Identificar los tres documentos

**Paso 1.** Abrir Paquete_Proveedor_EN.docx y localizar Documentos A (Technical), B (Commercial) y C (Security).

**Paso 2.** Abrir AG-Text-Translator-LAB y preparar una solicitud de traducción por bloque para evitar omisiones.

#### Tarea 2. Traducir y adaptar cada bloque

**Paso 1.** Copiar el texto del Documento A, pegarlo en AG-Text-Translator-LAB y traducirlo para Tecnología con el siguiente prompt.

**Prompt — Traducción A - Tecnología**

```text
Traduce Documento A al español para especialistas de Tecnología. Preserva TLS 1.3, REST, idempotency key, número de eventos, estados y todas las condiciones expresas. Mantiene encabezado y dos párrafos. Sin interpretar condiciones comerciales.
```

**Paso 2.** Copiar el texto del Documento B, pegarlo junto con el prompt y traducirlo para Compras; comprobar que USD 2400, 25000 sesiones, USD 0.03, 99.5 %, 12 meses y 45 días no cambien.

**Prompt — Traducción B - Compras**

```text
Traduce Documento B al español para Compras. Conserva todas las tarifas, umbrales, SLA, plazos y expresiones condicionales. Destaca sin resolver automáticamente las frases on request y commercially reasonable. No conviertas objetivos en obligaciones contractuales.
```

**Paso 3.** Copiar el texto del Documento C, pegarlo junto con el prompt y traducirlo para Riesgos; distinguir expresamente recomendaciones y obligaciones.

**Prompt — Traducción C - Riesgos**

```text
Traduce Documento C al español para Riesgos. Conserva AES-256, TLS 1.3, retención 30 y 90 días y responsabilidades de cliente y proveedor. Distingue should de must; identifica cualquier frase que no fija un plazo vinculante. No agregues garantías de seguridad.
```

#### Tarea 3. Consolidar terminología y resolver ambigüedades

**Paso 1.** Solicitar una tabla bilingüe de 8 términos recurrentes y un apartado con alternativas de traducción para best efforts, commercially reasonable y should, incluyendo efecto de cada formulación.

**Paso 2.** Abrir Word y organizar los tres apartados traducidos más la tabla de glosario y las ambigüedades.

#### Tarea 4. Comprobar integridad del paquete

**Paso 1.** Comparar cifra por cifra con el original inglés y verificar que el documento de Compras no convierta recomendaciones de Riesgos en obligaciones contractuales. Comprobar de forma expresa los matices de `must`, `should` y `best efforts`.

**Paso 2.** Guardar LAB-Paquete-Traducciones.docx con tres secciones, glosario y aclaraciones.

#### Resultado esperado

Documento Word consolidado con las traducciones A/B/C, glosario bilingüe de ocho términos y alternativas para expresiones ambiguas.

**Recurso de esta práctica:** [Paquete_Proveedor_EN.docx](../recursos/Paquete_Proveedor_EN.docx).

[Volver a las prácticas del módulo](#practicas-del-modulo) | [Índice del curso](../) | [Consultar la Setup Guide](../setup/)


---

[Módulo anterior](../Capitulo04/) | [Índice del curso](../) | [Módulo siguiente](../Capitulo06/)
