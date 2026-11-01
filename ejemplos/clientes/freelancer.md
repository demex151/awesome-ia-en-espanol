# Ejemplo ficticio: Diego Fuentes, freelancer de diseño y desarrollo web

> Perfil ficticio.

**Problema:** quiere ofrecer chatbots a sus clientes pymes y automatizar su propio trabajo.
**Equipo:** PC con GPU de 8 GB, sabe Python básico.

## Ruta recomendada
| Semana | Objetivo | Recursos de la lista |
|---|---|---|
| 1 | Bases de LLMs | [Curso de LLM de Hugging Face](https://huggingface.co/learn/llm-course/es/chapter1/1) y [Generative AI for Beginners](https://github.com/microsoft/generative-ai-for-beginners) |
| 2 | Modelos locales y una interfaz para clientes | [Ollama](https://ollama.com) + [Open WebUI](https://github.com/open-webui/open-webui) |
| 3 | Chatbot sobre documentos del cliente (RAG) | [Docling](https://github.com/docling-project/docling) + [multilingual-e5-large](https://huggingface.co/intfloat/multilingual-e5-large) + [Chroma](https://github.com/chroma-core/chroma), o todo en uno con [Dify](https://github.com/langgenius/dify) |
| 4 | Conectar herramientas y medir calidad | [MCP](https://modelcontextprotocol.io) con el [Python SDK](https://github.com/modelcontextprotocol/python-sdk) y pruebas con [promptfoo](https://github.com/promptfoo/promptfoo) |

**Siguiente nivel:** agentes con [CrewAI](https://github.com/crewAIInc/crewAI) o [smolagents](https://github.com/huggingface/smolagents); voz con [faster-whisper](https://github.com/SYSTRAN/faster-whisper) y [Piper](https://github.com/rhasspy/piper).
