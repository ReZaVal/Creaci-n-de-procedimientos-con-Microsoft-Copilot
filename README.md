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
[cite_start]Eres un asistente de redacción técnica operativa para la empresa. [cite: 8]

[cite_start]Tu misión es ayudarme a completar las secciones del documento que tengo abierto en Word, siguiendo el template corporativo oficial de la empresa. [cite: 8]

REGLAS QUE SIEMPRE DEBES RESPETAR:
- [cite_start]Respeta el orden y nombre exacto de las 9 secciones del template. [cite: 8]
- Usa español formal y lenguaje técnico-operativo. [cite_start]Sin ambigüedades. [cite: 8]
- [cite_start]En la sección DESARROLLO: usa siempre verbos en infinitivo (verificar, registrar, notificar, coordinar, asegurar). [cite: 8]
- [cite_start]En RESPONSABILIDADES: menciona solo cargos o roles, nunca nombres de personas. [cite: 8]
- [cite_start]Si la información que te doy es insuficiente para completar una sección, responde con: ⚠️ INFORMACIÓN FALTANTE — necesito que me indiques: [lo que falta]. [cite: 8]
- No inventes códigos de documentos, versiones ni fechas. [cite_start]Usa el marcador [COMPLETAR] para esos campos. [cite: 8]
- [cite_start]La sección REGISTROS solo debe listar evidencias reales que el proceso genera (formatos, reportes, correos, entradas en sistemas). [cite: 8]
- [cite_start]El DESARROLLO debe tener pasos numerados y concretos, no párrafos narrativos. [cite: 8]

[cite_start]Confirma que entendiste respondiendo: "Listo. Indícame el tipo de documento y el proceso a documentar." [cite: 8]

```

* ✅ **Señal de éxito:** Copilot responde con la confirmación exacta indicada. Si no lo hace, vuelve a pegar el prompt. 

---

PASO 2 DE 4: Prompt de Generación Completa 

* Úsalo cuando quieras que Copilot redacte el documento entero de una vez. 
* Llena los corchetes con tu información — puedes describir el proceso de forma informal. 

```text
[cite_start]Elabora un [TIPO: procedimiento / plan / instructivo] titulado "[NOMBRE DEL DOCUMENTO]" para la empresa. [cite: 14]

DESCRIPCIÓN DEL PROCESO:
[Explica qué se hace, cuándo ocurre, qué lo activa y cuál es el resultado esperado. [cite_start]Puedes ser informal.] [cite: 14]

ROLES QUE PARTICIPAN:
[cite_start][Lista los cargos involucrados.] Ejemplo: Supervisor, coordinador o jefe de área. [cite: 14]

CONDICIONES ESPECIALES O DE SEGURIDAD:
[Restricciones, alertas operativas o situaciones críticas. [cite_start]Si no hay, escribe: ninguna.] [cite: 14]

DOCUMENTOS RELACIONADOS (si los conoces):
[cite_start][Códigos o nombres de otros procedimientos a referenciar.] [cite: 14]

[cite_start]Genera el documento completo con las 9 secciones del template corporativo. [cite: 14]
[cite_start]Deja con [COMPLETAR] los campos del sistema de gestión documental (código, versión, fechas). [cite: 14]

```
**Consejo:** Mientras más detalle pongas en 'DESCRIPCIÓN DEL PROCESO', mejor será el resultado. No hace falta que sea formal — Copilot se encarga de la redacción. 

---

PASO 3 DE 4: Prompts por Sección 

* Úsalos para trabajar o refinar una sección específica. Antes de pegar cada prompt, selecciona con el cursor el texto de esa sección en tu documento. 

1. OBJETIVO 

```text
[cite_start]Reescribe solo la sección OBJETIVO de este procedimiento corporativo. [cite: 20]
[cite_start]Debe responder en máximo 2 oraciones: [cite: 20]
  [cite_start]· ¿Qué se busca lograr? [cite: 20]
  [cite_start]· ¿Qué riesgo operativo o problema resuelve? [cite: 20]
[cite_start]Comienza con uno de estos verbos: Establecer, Definir o Describir. [cite: 20]

```

2. ALCANCE 

```text
Reescribe la sección ALCANCE. [cite_start]Debe indicar claramente: [cite: 22]
  [cite_start]· A qué área o proceso aplica. [cite: 22]
  [cite_start]· Qué roles o equipos están dentro del alcance. [cite: 22]
  [cite_start]· Si hay algo que explícitamente NO cubre este documento, indícalo. [cite: 22]
[cite_start]Máximo 3 oraciones. [cite: 22]

```

3. DEFINICIONES 

```text
[cite_start]Lee el borrador del documento y extrae todos los términos técnicos, siglas y abreviaciones que usa. [cite: 24]
[cite_start]Para cada uno, redacta una definición operativa breve (1-2 líneas) en el contexto operativo de la empresa. [cite: 24]
[cite_start]Ordénalos alfabéticamente. [cite: 24]

```

4. DOCUMENTOS A CONSULTAR 

```text
[cite_start]Con base en el contenido del documento, sugiere qué tipos de documentos la empresa debería referenciar esta sección (normas, reglamentos, otros procedimientos relacionados). [cite: 26]
[cite_start]Presenta la lista con el formato: [cite: 26]
  [cite_start][Código o tipo] — [descripción breve] [cite: 26]
[cite_start]Deja el código real con [COMPLETAR] si no lo conozco. [cite: 26]

```

5. RESPONSABILIDADES 

```text
[cite_start]Reescribe la sección RESPONSABILIDADES. [cite: 28]
[cite_start]Usa el formato: "[Cargo] es responsable de [acción específica y verificable]." [cite: 28]
  [cite_start]· Solo cargos, nunca nombres de personas. [cite: 28]
  [cite_start]· Cada responsabilidad debe poder auditarse (que alguien pueda verificar si se cumplió o no). [cite: 28]

```

6. DESARROLLO 

```text
[cite_start]Reescribe la sección DESARROLLO con estas reglas: [cite: 30]
  [cite_start]· Pasos numerados y concretos. [cite: 30]
  [cite_start]· Cada paso comienza con verbo en infinitivo. [cite: 30]
  [cite_start]· Si hay una decisión o condición, usa el formato: "Si [condición] → [acción a tomar]." [cite: 30]
  [cite_start]· Agrupa los pasos en subsecciones 6.1, 6.2, etc. según las etapas lógicas del proceso. [cite: 30]
  [cite_start]· No uses párrafos narrativos. [cite: 30]

```

7. REGISTROS 

```text
[cite_start]Reescribe la sección REGISTROS. [cite: 32]
[cite_start]Lista solo las evidencias concretas que este proceso genera: formatos físicos, registros en sistema, reportes, correos, entradas en bitácora, etc. [cite: 32]
[cite_start]Formato: [cite: 32]
  [cite_start][Nombre del registro] — [quién lo genera] — [dónde se archiva] [cite: 32]
[cite_start]Si no tienes certeza de dónde se archiva, escribe [COMPLETAR]. [cite: 32]

```

---

PASO 4 DE 4: Prompt de Autoverificación 

* Úsalo cuando el documento esté completo. Es el último paso antes de enviarlo al Revisor. 

* Copilot actuará como auditor interno y te dirá qué corregir. 

```text
[cite_start]Actúa como revisor interno de documentos técnicos corporativos. [cite: 37]
[cite_start]Analiza el documento que tengo en pantalla y verifica punto por punto: [cite: 37]

1. [cite_start]¿Las 9 secciones del template corporativo están presentes y en orden? [cite: 37]
2. [cite_start]¿El OBJETIVO responde claramente qué se logra y por qué importa? [cite: 37]
3. [cite_start]¿El ALCANCE HIPAA especifica a quiénes aplica y qué excluye? [cite: 37]
4. [cite_start]¿Las DEFINICIONES cubren todos los términos técnicos del documento? [cite: 37]
5. [cite_start]¿Las RESPONSABILIDADES usan cargos, no nombres de personas? [cite: 37]
6. [cite_start]¿El DESARROLLO tiene pasos numerados con verbos en infinitivo? [cite: 37]
7. [cite_start]¿Los REGISTROS son evidencias reales y verificables? [cite: 37]
8. [cite_start]¿Quedan campos [COMPLETAR] que debo resolver antes de enviar al Revisor? [cite: 37]

[cite_start]Para cada punto responde: ✅ Correcto / ⚠️ Revisar / ❌ Falta. [cite: 37]
[cite_start]Al final, lista solo las correcciones pendientes ordenadas de mayor a menor urgencia. [cite: 37]

```

* ✅ **Señal de éxito:** Copilot devuelve 8 ítems marcados con ✅ y ningún [COMPLETAR] sin resolver. En ese punto el documento está listo para el Revisor. 

---

REFERENCIA RÁPIDA 

¿Qué prompt usar y cuándo? 

| Situación | Prompt a usar |
| --- | --- |
| Primera vez que abres el template | Prompt de Inicio (Paso 1) 

 |
| Quieres generar todo el documento de una vez | Prompt de Generación (Paso 2) 

 |
| Quieres trabajar sección por sección | Prompts por Sección (Paso 3) 

 |
| Terminaste de redactar — antes de enviar al Revisor | Prompt de Autoverificación (Paso 4) 

 |
| Copilot devolvió algo incorrecto | Repite el prompt con más detalle en los corchetes 

 |
| Una sección quedó incompleta (⚠️) | Agrega la información que Copilot indicó como faltante y repite ese prompt de sección 

 |
