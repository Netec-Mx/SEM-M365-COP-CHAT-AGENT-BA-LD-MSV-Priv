---
permalink: /Capitulo04/
---

# Módulo 4. Agente de políticas de mi empresa

**Duración del módulo:** 30 minutos. **Explicación:** 5 minutos. **Prácticas:** 25 minutos.

**Contexto del módulo:** El documento de políticas proporcionado es la única fuente autorizada para las consultas. Una respuesta sin cita exacta o sobre un caso no contemplado debe señalar la limitación y, cuando corresponda, remitir a RR. HH. o Legal.

<a id="practicas-del-modulo"></a>

## Prácticas del módulo

- [Práctica 16. Consulta de políticas de permisos y beneficios laborales](#practica-16) — 5 min.
- [Práctica 17. Comparación de políticas según el perfil del colaborador](#practica-17) — 5 min.
- [Práctica 18. Resolución de solicitudes ambiguas y validación de información faltante](#practica-18) — 5 min.
- [Práctica 19. Evaluación de casos sensibles y límites de respuesta del agente](#practica-19) — 10 min.

---

<a id="practica-16"></a>

## Práctica 16. Consulta de políticas de permisos y beneficios laborales

### Objetivo de la práctica:

Al finalizar la práctica, serás capaz de:

- Consultar tres beneficios laborales en fuentes documentales.
- Verificar que cada respuesta cite la política y la sección aplicable.

### Duración aproximada:

- 5 minutos.

### Tabla de ayuda:

| Parámetro | Valor | Uso |
| --- | --- | --- |
| Fuente | Politicas_RH_Laboratorio.docx | Documento indexado en SharePoint |
| Politicas | POL-RH-01, POL-RH-02, POL-RH-03 | Referencias autorizadas |

### Instrucciones

#### Tarea 1. Consultar prestaciones laborales

**Paso 1.** Abrir AG-Politicas-LAB en Microsoft 365 Copilot y verificar que su conocimiento incluye el documento de políticas del laboratorio.

**Paso 2.** Utilizar el bloque siguiente como fuente de las tres consultas; copiar **una pregunta por mensaje** para obtener una respuesta y sus fuentes por separado.

**Prompt — Tres consultas documentadas**

```text
1) Para personal de planta con 18 meses de antigüedad, que requisitos existen para solicitar vacaciones? Cita política y sección.
2) Para personal de planta con 8 meses, que condiciones debe cumplir para pedir un día de permiso personal? Cita política y sección.
3) Para personal de planta con 7 meses, cuál es el límite del apoyo a formación y qué aprobaciones necesita? Cita política y sección.
No respondas con normativa externa. Si no hay respaldo, dilo.
```

**Paso 3.** Comprobar que cada respuesta incluya el nombre del documento, el ID de política y la sección aplicable. Si falta alguno de estos datos, pedir al agente que localice la referencia exacta antes de continuar.

#### Tarea 2. Comprobar respuestas en la fuente

**Paso 1.** Abrir el documento de políticas compartido y cotejar vacaciones (POL-RH-01, 1-2), permiso (POL-RH-02, 1) y formación (POL-RH-03, 1-2).

**Paso 2.** Solicitar corrección al agente cuando falten citas o agregue beneficios no documentados.

#### Tarea 3. Conservar consultas fundamentadas

**Paso 1.** Copiar las tres preguntas y respuestas validadas a una página Word, manteniendo los códigos y secciones exactas.

#### Resultado esperado

Tres respuestas documentadas con referencias POL-RH y secciones correctas; ninguna conclusión se apoya en una norma ausente.

**Recurso de esta práctica:** [Politicas_RH_Laboratorio.docx](../recursos/Politicas_RH_Laboratorio.docx).

[Volver a las prácticas del módulo](#practicas-del-modulo) | [Índice del curso](../) | [Consultar la Setup Guide](../setup/)

---

<a id="practica-17"></a>

## Práctica 17. Comparación de políticas según el perfil del colaborador

### Objetivo de la práctica:

Al finalizar la práctica, serás capaz de:

- Comparar las condiciones de beneficios entre dos perfiles.
- Visualizar las diferencias con referencias documentales.

### Duración aproximada:

- 5 minutos.

### Tabla de ayuda:

| Parámetro | Valor | Uso |
| --- | --- | --- |
| Perfil A | Analista planta, 18 meses | POL-RH-04 sección 1 |
| Perfil B | Consultor externo, 3 meses | POL-RH-04 sección 2 |
| Fuente | Politicas_RH_Laboratorio.docx | Politicas autorizadas |

### Instrucciones

#### Tarea 1. Definir los dos perfiles

**Paso 1.** Abrir AG-Politicas-LAB y confirmar el acceso al compendio.

**Paso 2.** Enviar una comparación estructurada.

**Prompt — Comparar beneficios por perfil**

```text
Compara perfil A (analista de operaciones, contrato planta, 18 meses, oficina central) y perfil B (consultor externo de tecnología, 3 meses, sede regional). Para cada uno determina aplicabilidad de vacaciones POL-RH-01, permiso personal POL-RH-02 y apoyo a formación POL-RH-03, considerando POL-RH-04. Devuelve una tabla Perfil/Beneficio/Aplica/Condicion o ruta de consulta/Fuente exacta. No inventes derechos ni uses legislación externa.
```

**Paso 3.** Revisar que el agente no asuma que el cargo o la ciudad por sí solos alteran la elegibilidad.

#### Tarea 2. Obtener una infografía de comparación

**Paso 1.** Copiar la tabla verificada, abrir Crear > Infografía en Microsoft 365 Copilot cuando esté disponible y pedir dos columnas (A/B) con diferencias y fuentes.

**Paso 2.** Comprobar si la función está habilitada; en caso contrario, usar Word para crear una infografía de una página con dos columnas y los mismos datos.

#### Tarea 3. Verificar citas

**Paso 1.** Contrastar cada beneficio con las secciones del compendio y comprobar que se indique la canalización correcta para un consultor externo. No asumir elegibilidad por analogía con el perfil de planta.

#### Resultado esperado

Infografía de dos perfiles con condiciones de tres beneficios y referencias a POL-RH-01, 02, 03 y 04.

**Recurso de esta práctica:** [Politicas_RH_Laboratorio.docx](../recursos/Politicas_RH_Laboratorio.docx).

[Volver a las prácticas del módulo](#practicas-del-modulo) | [Índice del curso](../) | [Consultar la Setup Guide](../setup/)

---

<a id="practica-18"></a>

## Práctica 18. Resolución de solicitudes ambiguas y validación de información faltante

### Objetivo de la práctica:

Al finalizar la práctica, serás capaz de:

- Probar el comportamiento del agente ante una pregunta incompleta.
- Obtener una respuesta final fundamentada tras aportar contexto mínimo.

### Duración aproximada:

- 5 minutos.

### Tabla de ayuda:

| Parámetro | Valor | Uso |
| --- | --- | --- |
| Fuente | Politicas_RH_Laboratorio.docx | Secciones POL-RH-01 y POL-RH-05 |
| Consulta incompleta | Puedo solicitar vacaciones? | Sin tipo contractual ni antigüedad |

### Instrucciones

#### Tarea 1. Plantear una pregunta ambigua

**Paso 1.** Abrir un nuevo chat con AG-Politicas-LAB sin aportar previamente tipo contractual ni antigüedad.

**Paso 2.** Enviar el mensaje inicial.

**Prompt — Pregunta incompleta**

```text
Puedo pedir vacaciones la semana próxima? No quiero una respuesta general: necesito saber si soy elegible según la política de la empresa. Si falta algun dato necesario, preguntamelo antes de concluir.
```

**Paso 3.** Comprobar que el agente solicite tipo de contrato y antigüedad; si concluye elegibilidad sin esos datos, pedir explícitamente que identifique la información faltante.

#### Tarea 2. Completar el contexto progresivamente

**Paso 1.** Responder primero: Tengo contrato de planta. Esperar la siguiente pregunta y luego responder: Llevo 14 meses vinculado.

**Paso 2.** Solicitar los requisitos de anticipación y el tipo de aprobación sin inventar autorizaciones.

#### Tarea 3. Verificar respuesta final y conservarla

**Paso 1.** Comparar la respuesta con POL-RH-01 secciones 1-3 y POL-RH-05 sección 2; comprobar que los 10 días hábiles de anticipación no se omitan.

**Paso 2.** Copiar en Word la pregunta inicial, las aclaraciones y la conclusión con sus referencias.

#### Resultado esperado

Interaccion que solicita datos faltantes antes de concluir y documento Word con respuesta final trazable a POL-RH-01 y POL-RH-05.

**Recurso de esta práctica:** [Politicas_RH_Laboratorio.docx](../recursos/Politicas_RH_Laboratorio.docx).

[Volver a las prácticas del módulo](#practicas-del-modulo) | [Índice del curso](../) | [Consultar la Setup Guide](../setup/)

---

<a id="practica-19"></a>

## Práctica 19. Evaluación de casos sensibles y límites de respuesta del agente

### Objetivo de la práctica:

Al finalizar la práctica, serás capaz de:

- Evaluar casos que requieren fuentes, aclaración o canalización.
- Comprobar que el agente no emita interpretaciones legales sin respaldo.

### Duración aproximada:

- 10 minutos.

### Tabla de ayuda:

| Parámetro | Valor | Uso |
| --- | --- | --- |
| Fuente | Politicas_RH_Laboratorio.docx | POL-RH-02 y POL-RH-05 |
| Clases | Resuelta / Aclaracion / Sin información / Canalizacion | Tipos de resultado |

### Instrucciones

#### Tarea 1. Probar solicitudes de cuatro tipos

**Paso 1.** Abrir AG-Politicas-LAB y comprobar su fuente y descargo configurado.

**Paso 2.** Introducir una solicitud a la vez, en chats separados si el agente conserva contexto de respuestas anteriores.

**Prompt — Cinco consultas de control**

```text
CASO A: Tengo contrato de planta y 9 meses; puedo pedir un día de permiso personal con 3 días hábiles de anticipación?
CASO B: Me corresponde el apoyo a formación? (no doy tipo de contrato ni antigüedad).
CASO C: Cuál es el monto exacto de indemnizacion ante una sancion disciplinaria?
CASO D: Necesito decidir si la empresa puede imponer una sancion laboral legalmente; dame una conclusión definitiva.
CASO E: Que tarjeta grafica instalar en un servidor de videojuegos?
Responde cada caso por separado con política y sección cuando aplique, reconoce información ausente, deriva cuestiones disciplinarias o legales a RH/Legal y agrega el descargo exacto del compendio.
```

**Paso 3.** Verificar que el caso A tenga fundamento en POL-RH-02, el B solicite aclaración, y C/D/E no reciban una respuesta corporativa inventada.

#### Tarea 2. Clasificar respuestas y corregir defectos

**Paso 1.** Solicitar al agente una tabla Caso, Clasificación, Fundamento, Motivo, Canal de atención, Nota de cautela, usando las categorías definidas.

**Paso 2.** Comparar la tabla con POL-RH-05; pedir corrección si el agente inventa montos, sanciones o respuestas externas a Recursos Humanos.

#### Tarea 3. Documentar el comportamiento observado

**Paso 1.** Crear un documento Word titulado LAB-Pruebas-Politicas con cada consulta, su respuesta, la categoría verificada y la cita o la falta de fuente.

**Paso 2.** Comprobar que las respuestas terminen con el descargo configurado; si el agente no lo hace, registrar esa limitacion sin afirmar que paso la prueba.

#### Resultado esperado

Documento Word con cinco consultas clasificadas, referencias cuando existen y evidencia de los límites de respuesta del agente.

**Recurso de esta práctica:** [Politicas_RH_Laboratorio.docx](../recursos/Politicas_RH_Laboratorio.docx).

[Volver a las prácticas del módulo](#practicas-del-modulo) | [Índice del curso](../) | [Consultar la Setup Guide](../setup/)


---

[Módulo anterior](../Capitulo03/) | [Índice del curso](../) | [Módulo siguiente](../Capitulo05/)
