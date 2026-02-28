# 🚀 Automate Everything: n8n, LLMs, OpenAI API, Claude, Ollama, MCP & RAG

Este repositorio reúne mis trabajos, experimentos y proyectos sobre **automatización con agentes de IA y modelos de lenguaje (LLMs)**.  
Más que solo ChatGPT: aquí encontrarás integraciones con **Claude, Gemini, Deepseek, Llama, Mistral, Ollama, MCP** y otros, aplicados en flujos de trabajo reales con **n8n, APIs, RAG, y agentes privados/de negocio**.

---

## 📚 Contenido

![alt text](<Captura de pantalla 2026-02-28 001257.png>)

### Flujo de Trabajo Principal (según el diagrama)

El sistema automatizado se organiza en cuatro bloques principales:

1. **📥 Entrada de datos (Base de datos inicial)**
   - Activador de programación que consulta la base de datos.
   - Recupera las filas con solicitudes de clientes (`Get row(s)`).

2. **🤖 IA para generación de correos**
   - Un modelo de IA redacta el cuerpo del correo.
   - Se valida si ya existe un correo previo para el cliente.

3. **🔎 IA para análisis de solicitudes**
   - Se aplica análisis de sentimiento sobre la observación del cliente.
   - Si el sentimiento es negativo y no existe correo, se alerta al equipo comercial.
   - Se usa un modelo de chat (OpenAI u otros) para interpretar la solicitud.

4. **📤 Envío de correos y agendamiento**
   - Envío de correo al cliente con la respuesta generada.
   - Envío de correo corporativo si se requiere escalar el caso.
   - Mensajes internos vía chat para seguimiento.

---

### Herramientas y Frameworks
- **n8n**: orquestación de flujos, nodos de base de datos, envío de correos.
- **Modelos LLMs**: OpenAI, Claude, Ollama, MCP, entre otros.
- **Análisis de sentimiento**: integración con modelos de IA para clasificar observaciones.
- **Automatización de comunicación**: envío de correos y mensajes corporativos.

---

### Aplicaciones
- Automatización de emails y respuestas inteligentes.
- Alertas automáticas al equipo comercial según análisis de sentimiento.
- Integración con bases de datos para gestión de solicitudes.
- Flujos de comunicación internos y externos.

---

## 💡 Objetivos del Repositorio
- Documentar paso a paso mis proyectos y aprendizajes.
- Proveer ejemplos prácticos y workflows reutilizables.
- Explorar el potencial de los agentes de IA más allá del uso básico de ChatGPT.
- Mostrar cómo convertir la automatización en soluciones de negocio reales.

---

## 🛠️ Tecnologías Clave
- **n8n, Make, Zapier**
- **OpenAI API, Claude, Ollama, MCP**
- **LangChain, LangGraph, Flowise**
- **Vector Databases (Pinecone, Weaviate, Chroma)**
- **Google Cloud, Airtable, Google Sheets**

---

## 📈 Visión
Este repositorio busca ser un **hub de conocimiento práctico** sobre automatización con IA, combinando:
- **Agentes privados** para productividad personal.
- **Agentes de negocio** para marketing, ventas y soporte.
- **Integraciones técnicas** con APIs y bases de datos.
- **Estrategias de mercado** para vender soluciones de automatización.

---

## 🤝 Contribuciones
Este es un proyecto en evolución y práctica actualmente.  
Si quieres colaborar, proponer mejoras o compartir ideas, ¡bienvenido! Abre un issue o un pull request.