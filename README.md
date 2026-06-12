# Creación-de-procedimientos-con-Microsoft-Copilot
Prompts para crear procedimientos corporativos desde Microsoft Word utilizando Copilot dentro de un template corportativo

---

# GUÍA DE PROMPTS · Microsoft Copilot en Word

ETAPA 1 · REDACTOR: Elaboración de Procedimientos, Planes e Instructivos 

📌 **Cómo usar esta guía:** Abre el template corporativo en Word → pestaña Inicio → botón Copilot ✨. Copia cada prompt exactamente como aparece y pégalo en el panel de Copilot. Reemplaza solo el texto entre [CORCHETES]. 
⚠️ **Importante:** Copilot no lee tu documento automáticamente. Los prompts de sección le indican en qué parte estás trabajando. Selecciona el texto de la sección antes de usar los prompts individuales. 

---

PASO 1 DE 4: Prompt de Inicio 

* Pégalo UNA sola vez al abrir el template. Es la instrucción base que configura a Copilot para todo el documento. 


* No necesitas repetirlo en secciones posteriores. 

```text
Eres un asistente de redacción técnica operativa para la empresa.

Tu misión es ayudarme a completar las secciones del documento que tengo abierto en Word, siguiendo el template corporativo oficial de la empresa.

REGLAS QUE SIEMPRE DEBES RESPETAR:
- Respeta el orden y nombre exacto de las 9 secciones del template.
- Usa español formal y lenguaje técnico-operativo. [cite_start]Sin ambigüedades.
- En la sección DESARROLLO: usa siempre verbos en infinitivo (verificar, registrar, notificar, coordinar, asegurar).
- En RESPONSABILIDADES: menciona solo cargos o roles, nunca nombres de personas.
- Si la información que te doy es insuficiente para completar una sección, responde con: ⚠️ INFORMACIÓN FALTANTE — necesito que me indiques: [lo que falta].
- No inventes códigos de documentos, versiones ni fechas. [cite_start]Usa el marcador [COMPLETAR] para esos campos.
- La sección REGISTROS solo debe listar evidencias reales que el proceso genera (formatos, reportes, correos, entradas en sistemas).
- El DESARROLLO debe tener pasos numerados y concretos, no párrafos narrativos.

Confirma que entendiste respondiendo: "Listo. Indícame el tipo de documento y el proceso a documentar."

```

* ✅ **Señal de éxito:** Copilot responde con la confirmación exacta indicada. Si no lo hace, vuelve a pegar el prompt. 

---

PASO 2 DE 4: Prompt de Generación Completa 

* Úsalo cuando quieras que Copilot redacte el documento entero de una vez. 
* Llena los corchetes con tu información — puedes describir el proceso de forma informal. 

```text
Elabora un [TIPO: procedimiento / plan / instructivo] titulado "[NOMBRE DEL DOCUMENTO]" para la empresa.

DESCRIPCIÓN DEL PROCESO:
[Explica qué se hace, cuándo ocurre, qué lo activa y cuál es el resultado esperado. Puedes ser informal.]

ROLES QUE PARTICIPAN:
[Lista los cargos involucrados.] Ejemplo: Supervisor, coordinador o jefe de área.

CONDICIONES ESPECIALES O DE SEGURIDAD:
[Restricciones, alertas operativas o situaciones críticas. Si no hay, escribe: ninguna.]

DOCUMENTOS RELACIONADOS (si los conoces):
[Códigos o nombres de otros procedimientos a referenciar.]

Genera el documento completo con las 9 secciones del template corporativo.
Deja con [COMPLETAR] los campos del sistema de gestión documental (código, versión, fechas).

```
**Consejo:** Mientras más detalle pongas en 'DESCRIPCIÓN DEL PROCESO', mejor será el resultado. No hace falta que sea formal — Copilot se encarga de la redacción. 

---

PASO 3 DE 4: Prompts por Sección 

* Úsalos para trabajar o refinar una sección específica. Antes de pegar cada prompt, selecciona con el cursor el texto de esa sección en tu documento. 

1. OBJETIVO 

```text
Reescribe solo la sección OBJETIVO de este procedimiento corporativo.
Debe responder en máximo 2 oraciones:
  · ¿Qué se busca lograr?
  · ¿Qué riesgo operativo o problema resuelve?
Comienza con uno de estos verbos: Establecer, Definir o Describir.
```

2. ALCANCE 

```text
Reescribe la sección ALCANCE. [cite_start]Debe indicar claramente:
  · A qué área o proceso aplica.
  · Qué roles o equipos están dentro del alcance.
  · Si hay algo que explícitamente NO cubre este documento, indícalo.
Máximo 3 oraciones.

```

3. DEFINICIONES 

```text
Lee el borrador del documento y extrae todos los términos técnicos, siglas y abreviaciones que usa.
Para cada uno, redacta una definición operativa breve (1-2 líneas) en el contexto operativo de la empresa.
Ordénalos alfabéticamente.

```

4. DOCUMENTOS A CONSULTAR 

```text
Con base en el contenido del documento, sugiere qué tipos de documentos la empresa debería referenciar esta sección (normas, reglamentos, otros procedimientos relacionados).
Presenta la lista con el formato:
  [Código o tipo] — [descripción breve]
Deja el código real con [COMPLETAR] si no lo conozco.

```

5. RESPONSABILIDADES 

```text
Reescribe la sección RESPONSABILIDADES.
Usa el formato: "[Cargo] es responsable de [acción específica y verificable]."
  · Solo cargos, nunca nombres de personas.
  · Cada responsabilidad debe poder auditarse (que alguien pueda verificar si se cumplió o no).

```

6. DESARROLLO 

```text
Reescribe la sección DESARROLLO con estas reglas:
  · Pasos numerados y concretos.
  · Cada paso comienza con verbo en infinitivo.
  · Si hay una decisión o condición, usa el formato: "Si [condición] → [acción a tomar]."
  · Agrupa los pasos en subsecciones 6.1, 6.2, etc. según las etapas lógicas del proceso.
  · No uses párrafos narrativos.

```

7. REGISTROS 

```text
Reescribe la sección REGISTROS.
Lista solo las evidencias concretas que este proceso genera: formatos físicos, registros en sistema, reportes, correos, entradas en bitácora, etc.
Formato:
  [Nombre del registro] — [quién lo genera] — [dónde se archiva]
Si no tienes certeza de dónde se archiva, escribe [COMPLETAR].

```

---

PASO 4 DE 4: Prompt de Autoverificación 

* Úsalo cuando el documento esté completo. Es el último paso antes de enviarlo al Revisor. 

* Copilot actuará como auditor interno y te dirá qué corregir. 

```text
Actúa como revisor interno de documentos técnicos corporativos.
Analiza el documento que tengo en pantalla y verifica punto por punto:

1. ¿Las 9 secciones del template corporativo están presentes y en orden?
2. ¿El OBJETIVO responde claramente qué se logra y por qué importa? 
3. ¿El ALCANCE HIPAA especifica a quiénes aplica y qué excluye?
4. ¿Las DEFINICIONES cubren todos los términos técnicos del documento?
5. ¿Las RESPONSABILIDADES usan cargos, no nombres de personas?
6. ¿El DESARROLLO tiene pasos numerados con verbos en infinitivo?
7. ¿Los REGISTROS son evidencias reales y verificables?
8. ¿Quedan campos [COMPLETAR] que debo resolver antes de enviar al Revisor?

Para cada punto responde: ✅ Correcto / ⚠️ Revisar / ❌ Falta.
]Al final, lista solo las correcciones pendientes ordenadas de mayor a menor urgencia.

```

* ✅ **Señal de éxito:** Copilot devuelve 8 ítems marcados con ✅ y ningún [COMPLETAR] sin resolver. En ese punto el documento está listo para el Revisor. 

---

REFERENCIA RÁPIDA 

¿Qué prompt usar y cuándo? 

| Situación | Prompt a usar |
| --- | --- |
| Primera vez que abres el template | Prompt de Inicio (Paso 1) 
| Quieres generar todo el documento de una vez | Prompt de Generación (Paso 2) 
| Quieres trabajar sección por sección | Prompts por Sección (Paso 3) 
| Terminaste de redactar — antes de enviar al Revisor | Prompt de Autoverificación (Paso 4) 
| Copilot devolvió algo incorrecto | Repite el prompt con más detalle en los corchetes 
| Una sección quedó incompleta (⚠️) | Agrega la información que Copilot indicó como faltante y repite ese prompt de sección 
