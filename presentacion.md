# Propuesta de herramienta basada en Inteligencia Artificial para soporte técnico del área de I+D+i

## 1. Problema identificado

El área de Investigación, Desarrollo e Innovación (I+D+i) de Industrias Médicas Sampedro gestiona información técnica relacionada con implantes, instrumental quirúrgico, configuraciones de sistemas, materiales, normas técnicas, documentación regulatoria y especificaciones de producto. Esta información es consultada frecuentemente por áreas como Comercial, Logística, Compras, Calidad y Regulatorio, generando interrupciones constantes en las actividades de desarrollo y disminuyendo la productividad del equipo.

## 2. Solución propuesta

Se propone desarrollar un asistente virtual interno basado en Inteligencia Artificial denominado **Sampedro AI Assistant**, diseñado para responder consultas técnicas de manera automática utilizando la documentación interna de la compañía.

La herramienta funcionará como un chatbot corporativo capaz de consultar fichas técnicas, catálogos, manuales, procedimientos, expedientes técnicos y documentación regulatoria para proporcionar respuestas rápidas, precisas y consistentes a los usuarios.

## 3. Funcionalidades principales

La herramienta deberá ser capaz de:

- Responder preguntas sobre implantes e instrumental.
- Consultar configuraciones de sistemas quirúrgicos.
- Identificar compatibilidades entre placas, tornillos e instrumental.
- Buscar información regulatoria y normativa.
- Consultar materiales y especificaciones técnicas.
- Localizar códigos de producto y referencias comerciales.
- Generar respuestas basadas en documentación interna validada.
- Citar la fuente documental utilizada para responder.

## 4. Usuarios objetivo

- Área Comercial.
- Área Logística.
- Área de Compras.
- Área Regulatoria.
- Área de Calidad.
- Área de Producción.
- Área de Servicio Técnico.

## 5. Ejemplos de funcionamiento

### Caso 1 - Comercial

**Pregunta:**  
"¿Qué tornillos son compatibles con la placa Lisfranc?"

**Respuesta esperada:**  
"La placa Lisfranc es compatible con tornillos bloqueados de 2,7 mm y tornillos corticales no bloqueados de 2,7 mm, según la configuración del sistema."

### Caso 2 - Logística

**Pregunta:**  
"¿Cuántas referencias conforman el sistema de pie?"

**Respuesta esperada:**  
"El sistema está compuesto por seis familias de placas, tres familias de tornillos y un set de instrumental quirúrgico."

### Caso 3 - Regulatorio

**Pregunta:**  
"¿Qué norma aplica para la validación mecánica de placas óseas?"

**Respuesta esperada:**  
"Las placas óseas deberán evaluarse de acuerdo con la norma ASTM F382."

### Caso 4 - Compras

**Pregunta:**  
"¿Cuál es el material utilizado en las placas del sistema?"

**Respuesta esperada:**  
"Las placas están fabricadas en aleación de titanio Ti-6Al-4V ELI conforme a ASTM F136."

## 6. Beneficios esperados

- Reducción del tiempo invertido en consultas repetitivas.
- Mayor disponibilidad del equipo de I+D+i para actividades de desarrollo.
- Estandarización de la información suministrada a otras áreas.
- Disminución de errores por interpretación de documentación técnica.
- Acceso rápido y centralizado al conocimiento corporativo.
- Incremento de la productividad organizacional.

## 7. Tecnologías sugeridas

La solución puede implementarse mediante modelos de lenguaje de gran escala (LLM) integrados con una base documental corporativa utilizando arquitecturas RAG (Retrieval-Augmented Generation), permitiendo que las respuestas se generen únicamente a partir de información validada por la compañía.

## 8. Flujo operativo propuesto

1. El usuario ingresa una pregunta en lenguaje natural.
2. El sistema consulta la base documental corporativa validada.
3. El asistente genera una respuesta breve, técnica y accionable.
4. La herramienta cita la fuente documental utilizada.
5. Si la información no está disponible o requiere criterio técnico, la solicitud se escala a I+D+i.
