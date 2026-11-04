---
permalink: /setup/
---
# Setup Guide - Uso práctico de agentes de M365 Copilot

## Descripción del entorno

Entorno Microsoft 365 de laboratorio con Microsoft 365 Copilot para cuentas profesionales y acceso a Planner, Word, Excel, PowerPoint, Outlook, SharePoint y Microsoft Forms. Se trabajan **seis módulos con 25 prácticas** y no se requiere infraestructura bancaria ni conectores financieros. Los agentes creados a partir de plantillas deben estar configurados y compartidos antes de empezar para respetar las duraciones del temario.

## Requisitos de hardware y software

- Equipo con navegador Microsoft Edge o navegador compatible actualizado y conexión estable a internet.
- Cuenta profesional o educativa en un tenant Microsoft 365 de laboratorio y acceso a [Microsoft 365 Copilot](https://microsoft365.com/copilot).
- Microsoft Planner, Word, Excel, PowerPoint, Outlook, SharePoint y Forms habilitados. Se aceptan sus versiones web.
- Descargar desde el [índice del laboratorio](../) los cuatro archivos indicados en Preparación de fuentes. No se requiere software local adicional.

## Licencias, cuentas y permisos

- Licencia Microsoft 365 Copilot por participante, no solo acceso a Copilot Chat básico, para las funciones de agentes, grounding empresarial y creación que exigen el complemento. El tenant debe permitir Agent Builder y los agentes usados en el seminario.
- **Agente de Planner:** utilizar planes **básicos compartidos** con un grupo de Microsoft 365 para todos los ejercicios del módulo 1. En el agente de Planner desde Copilot Chat, los planes Premium no se admiten actualmente; la experiencia del agente dentro de Planner puede ofrecer capacidades adicionales para planes Premium. No utilizar el cambio de licencia como parte de las prácticas. Verificar el acceso real en el tenant antes del seminario.
- Acceso con permisos de edición a planes de laboratorio, documentos propios de Word/Excel/PowerPoint y formularios propios de Microsoft Forms.
- Permiso de lectura sobre un sitio o biblioteca SharePoint de laboratorio con los documentos fuente. No usar datos internos reales ni exponer la biblioteca a personas ajenas a la capacitación.
- La disponibilidad de opciones **Crear** (Historia, Infografía, PowerPoint), Copilot en Forms y Copilot en Excel depende de licencias, políticas y despliegues. Las guías indican cómo realizar el producto final en la aplicación correspondiente cuando la generación directa no está disponible; **la alternativa manual no sustituye la prueba de las funciones de IA requeridas**. Confirmar esta disponibilidad antes de la sesión.

## Preparación

### 1. Preparar acceso y archivos

1. Abrir https://microsoft365.com/copilot y verificar que se muestra una sesión empresarial con acceso a agentes.
2. Crear una carpeta SharePoint de laboratorio llamada `LAB-M365-AGENTES-2026` en un sitio autorizado. Mantener acceso restringido al grupo del seminario.
3. Descargar los archivos de la carpeta `recursos/` del paquete y agregar a la carpeta SharePoint tres documentos Word: `Seguimiento_Iniciativas_Digitales.docx`, `Politicas_RH_Laboratorio.docx` y `Paquete_Proveedor_EN.docx`. El archivo Excel `Respuestas_Canales_Digitales.xlsx` solo se necesita localmente o en OneDrive para la práctica 24.
4. Comprobar que los documentos se pueden abrir y buscar desde la cuenta con la que se usaran los agentes. Preparar las fuentes con anticipación para permitir su indexación.

### 2. Comprobar Planner Agent

1. Abrir Planner desde Microsoft 365 o Teams, crear un **plan básico compartido** de prueba y localizar el Agente de Planner desde el plan o desde Microsoft 365 Copilot > Agentes > Agente de Planner. Si se accede desde Copilot, seleccionar el plan de prueba como destino.
2. Solicitar al agente crear una tarea temporal, **revisar la tarjeta en borrador y aprobarla/guardarla**, y verificar que se muestre posteriormente en Planner. Si no aparece la propuesta, revisar licencia, permisos y selección del plan antes del curso. Eliminar el plan de prueba al finalizar.
3. Las tareas reales se crean durante las prácticas; no preparar anticipadamente los planes LAB-MOB, LAB-DIG, LAB-REG ni LAB-EMP. El agente puede proponer campos como nombre, fecha y prioridad, pero **asignaciones, listas de comprobación, adjuntos y determinados campos de tarea pueden requerir edición manual**. No suponer que calcula automáticamente una ruta crítica.

### 3. Aprovisionar agentes de plantilla

En Microsoft 365 Copilot elegir `Nuevo agente` > `Comenzar con una plantilla` (el texto puede variar según idioma), seleccionar cada plantilla y terminar el asistente de creación en Agent Builder. Una plantilla no es por si sola un agente utilizable. El facilitador o el responsable del tenant debe compartir los agentes creados con los participantes antes del seminario:

| Plantilla oficial | Nombre para el laboratorio | Conocimiento relevante |
| --- | --- | --- |
| Project Delta Digest | `AG-Project-Delta-LAB` | `Seguimiento_Iniciativas_Digitales.docx` desde SharePoint |
| Scrum Assistant | `AG-Scrum-Assistant-LAB` | No exige fuente adicional: escenarios en los prompts |
| My Company Policy | `AG-Politicas-LAB` | `Politicas_RH_Laboratorio.docx` desde SharePoint |
| Text Translator | `AG-Text-Translator-LAB` | No exige fuente adicional: documentos en los prompts |

Configurar el agente My Company Policy para responder según la fuente y citar nombre, identificador y sección de la política, pedir información faltante antes de personalizar y agregar el descargo literal de POL-RH-05, apartado 3. No conectar sitios corporativos ajenos al escenario.

### 4. Verificar Forms y la retirada de Surveys Agent

Microsoft retiró el antiguo agente **Surveys** entre julio y agosto de 2026. Por ello, las prácticas 23-25 utilizan **Copilot integrado en Microsoft Forms** (`https://forms.office.com`) y los controles nativos del formulario. Entrar a **Forms > Nuevo formulario** y comprobar la asistencia de Copilot. Configurar la ramificación desde las opciones de las preguntas, únicamente hacia preguntas posteriores; comprobar cada recorrido en **Vista previa**. No intentar instalar ni utilizar el agente Surveys retirado.

## Verificación del entorno

1. Verificar que se puede abrir el plan básico de prueba de Planner y que el agente crea **propuestas revisables** antes de guardarlas; confirmar la edición manual de campos no admitidos.
2. Abrir `AG-Project-Delta-LAB` y preguntar: `Cuál es el avance de EMP-26 al 16/10/2026? Cita el expediente.` Respuesta esperada basada en fuente: 49 %. Si no aparece el documento, corregir conocimiento y permisos.
3. Abrir `AG-Politicas-LAB` y preguntar: `Cuántos días hábiles de anticipación establece POL-RH-01?` Debe citar 10 días y la sección 2.
4. Verificar que `AG-Scrum-Assistant-LAB` y `AG-Text-Translator-LAB` aparecen en la lista y aceptan preguntas, sin necesidad de crear datos adicionales.
5. Abrir Forms y comprobar que Copilot puede proponer preguntas; crear un formulario temporal de una pregunta, abrir Vista previa y eliminarlo. Verificar que Excel abre `Respuestas_Canales_Digitales.xlsx` con **36 respuestas** y que es posible utilizar Copilot en Excel o adjuntar el archivo en Copilot para su análisis.

## Consideraciones adicionales

- Todos los datos laborales, proyectos, cifras de presupuesto y clientes de las prácticas son simulados. No introducir información bancaria real, cuentas, contraseñas o expedientes de empleados.
- Las interfaces y licencias de Microsoft 365 cambian con frecuencia. Comprobarlas con anticipación. Una guía indica cuando el agente sugiere contenido y cuando la persona debe guardarlo o crear el artefacto en Word, Excel, PowerPoint, Outlook, Planner o Forms.
- No asumir que un agente de plantilla exporta directamente a Excel, CSV, Word o PowerPoint. Los formatos finales se generan desde la aplicación Office correspondiente cuando sea necesario. No compartir ni enviar correos de prueba a destinatarios reales.
- Para GitHub Pages, los archivos Markdown contienen `permalink` y los enlaces internos son relativos. Publicar la carpeta completa con Jekyll habilitado en la raíz del sitio o del proyecto; los participantes acceden a enlaces Pages, no a URLs privadas de GitHub. La ruta pública definitiva depende del nombre del sitio/repo configurado.

## Referencias oficiales de verificación

- [Plantillas de Agent Builder](https://learn.microsoft.com/en-us/microsoft-365/copilot/extensibility/agent-templates-overview).
- [My Company Policy](https://learn.microsoft.com/en-us/microsoft-365/copilot/extensibility/agent-template-my-company-policy).
- [Project Delta Digest](https://learn.microsoft.com/en-us/microsoft-365/copilot/extensibility/agent-template-project-delta-digest).
- [Scrum Assistant](https://learn.microsoft.com/en-us/microsoft-365/copilot/extensibility/agent-template-scrum-assistant).
- [Acceder al agente de Planner](https://support.microsoft.com/es-es/planner/copilot/access-planner-agent).
- [Agente de Planner en Copilot Chat](https://support.microsoft.com/es-es/planner/what-can-you-do-with-planner-agent-in-copilot).
- [Limitaciones de Planner Agent](https://support.microsoft.com/es-es/planner/planner-agent-limitation).
- [Novedades de Planner, 2026](https://support.microsoft.com/es-es/planner/whats-new-in-microsoft-planner).
- [Encuestas: retiro del agente Surveys](https://support.microsoft.com/en-us/forms/get-started-with-surveys-agent-in-microsoft-365-copilot).
- [Copilot en Microsoft Forms](https://support.microsoft.com/en-us/forms/welcome-to-copilot-in-forms).
- [Ramificacion en Microsoft Forms](https://support.microsoft.com/en-us/forms/use-branching-logic-in-microsoft-forms).

[Volver al índice de capítulos y prácticas](../).
