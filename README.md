# awesome-ia-en-español [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Lista curada de herramientas, cursos, modelos, datasets y comunidades de inteligencia artificial **en español o útiles para hispanohablantes**.

**120 recursos**, todos abiertos y revisados el 1 de noviembre de 2026. Un flujo de GitHub Actions revisa los enlaces cada semana.

¿No sabes por dónde empezar? Mira [`ejemplos/clientes/`](ejemplos/clientes/): 4 perfiles ficticios (pintor, restaurante, maestra, freelancer) con su ruta recomendada.

## Contenido
- [📚 Aprender IA (cursos y guías)](#-aprender-ia-cursos-y-guías)
- [💬 Asistentes de IA de uso general](#-asistentes-de-ia-de-uso-general)
- [🖥️ IA local (en tu propia computadora)](#-ia-local-en-tu-propia-computadora)
- [🧠 Modelos en español y multilingües](#-modelos-en-español-y-multilingües)
- [🤖 Agentes y automatización](#-agentes-y-automatización)
- [📄 RAG: IA sobre tus documentos](#-rag-ia-sobre-tus-documentos)
- [🔌 MCP (Model Context Protocol)](#-mcp-model-context-protocol)
- [🎙️ Voz: transcripción y síntesis](#-voz-transcripción-y-síntesis)
- [🎨 Imagen](#-imagen)
- [📏 Evaluación y rankings](#-evaluación-y-rankings)
- [🗂️ Datasets en español](#-datasets-en-español)
- [👥 Comunidades y eventos](#-comunidades-y-eventos)
- [Ejemplos de uso](#ejemplos-de-uso)
- [Contribuir](#contribuir)
- [English](#english)

## 📚 Aprender IA (cursos y guías)

- [Curso de LLM de Hugging Face (es)](https://huggingface.co/learn/llm-course/es/chapter1/1) — Curso gratuito de modelos de lenguaje y Transformers, con capítulos traducidos al español.
- [Generative AI for Beginners](https://github.com/microsoft/generative-ai-for-beginners) — Microsoft: 21 lecciones para empezar a construir con IA generativa (con traducciones).
- [AI For Beginners](https://github.com/microsoft/AI-For-Beginners) — Microsoft: 12 semanas y 24 lecciones de IA para todo público.
- [ML For Beginners](https://github.com/microsoft/ML-For-Beginners) — Microsoft: 12 semanas, 26 lecciones y 52 cuestionarios de machine learning clásico.
- [Guía de Ingeniería de Prompt](https://www.promptingguide.ai/es) — Panorama completo de técnicas de prompting, con versión en español.
- [Prompt-Engineering-Guide (repo)](https://github.com/dair-ai/Prompt-Engineering-Guide) — Guías, papers, lecciones y notebooks sobre prompts, RAG y agentes.
- [Learn Prompting (es)](https://learnprompting.org/es/docs/introduction) — Curso de ingeniería de prompts con más de 60 módulos, traducido a 9 idiomas.
- [Elements of AI (es)](https://www.elementsofai.com/es) — Introducción gratuita a la IA para no expertos, de MinnaLearn y la Universidad de Helsinki; sin programar.
- [AI For Everyone](https://www.coursera.org/learn/ai-for-everyone) — Curso de DeepLearning.AI en Coursera sobre IA para personas no técnicas; inscripción gratuita.
- [DeepLearning.AI short courses](https://www.deeplearning.ai/short-courses/) — Cursos cortos sobre LLMs, agentes y RAG (en inglés).
- [Practical Deep Learning (fast.ai)](https://course.fast.ai) — Curso gratuito de deep learning aplicado para quien ya sabe algo de programación.
- [Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course?hl=es-419) — Curso intensivo de machine learning de Google for Developers.
- [OpenAI Academy](https://academy.openai.com) — Formación de OpenAI para aprovechar la IA en el trabajo.
- [Claude Academy](https://www.anthropic.com/learn) — Educación gratuita de Anthropic: cómo funciona la IA y cómo usar Claude.
- [Anthropic courses (repo)](https://github.com/anthropics/courses) — Cursos de Anthropic en notebooks: prompting, uso de la API y herramientas.
- [SomosNLP recursos](https://github.com/somosnlp/recursos) — Diapositivas, notebooks y material de charlas y talleres de SomosNLP, en español.
- [Dot CSV (YouTube)](https://www.youtube.com/@DotCSV) — Canal de divulgación sobre inteligencia artificial en español.

## 💬 Asistentes de IA de uso general

- [Gemini](https://gemini.google.com) — Asistente de Google para escribir, planear y generar ideas.
- [Grok](https://grok.com) — Asistente de IA para chatear, crear imágenes, programar y buscar en la web y X.
- [Microsoft Copilot](https://copilot.microsoft.com) — Chat de IA de Microsoft para crear, aprender y resolver problemas.
- [HuggingChat](https://huggingface.co/chat) — Chat gratuito con modelos abiertos de la comunidad.
- [NotebookLM / Gemini Notebook](https://notebooklm.google.com) — Asistente de investigación que resume y responde sobre tus propias fuentes.
- [DeepL Translator](https://www.deepl.com/es/translator) — Traductor de texto y archivos con IA, con interfaz en español.
- [GitHub Copilot](https://github.com/features/copilot) — Agente de programación de GitHub para el editor, la terminal y pull requests.
- [Cursor](https://cursor.com) — Editor de código con agentes de IA que convierten ideas en código.

## 🖥️ IA local (en tu propia computadora)

- [Ollama](https://ollama.com) — La forma más sencilla de correr modelos abiertos en macOS, Windows y Linux.
- [LM Studio](https://lmstudio.ai) — App de escritorio para usar modelos locales, ahora con agente para documentos y código.
- [llama.cpp](https://github.com/ggml-org/llama.cpp) — Inferencia de LLMs en C/C++; base de muchas apps locales.
- [Open WebUI](https://github.com/open-webui/open-webui) — Interfaz web amigable para Ollama y APIs compatibles con OpenAI.
- [Jan](https://jan.ai) — Alternativa de código abierto a ChatGPT; corre modelos locales o en la nube.
- [GPT4All](https://www.nomic.ai/gpt4all) — Chatbot privado y local de Nomic; tus datos no salen del equipo.
- [AnythingLLM](https://anythingllm.com) — Asistente privado en tu equipo, sin cuentas ni claves de API.
- [llamafile](https://github.com/Mozilla-Ocho/llamafile) — Distribuye y ejecuta un LLM con un solo archivo (Mozilla).
- [LocalAI](https://github.com/mudler/LocalAI) — Motor abierto para correr texto, visión, voz e imagen en cualquier hardware, sin GPU.

## 🧠 Modelos en español y multilingües

- [BSC-LT (Barcelona Supercomputing Center)](https://huggingface.co/BSC-LT) — Modelos de lenguaje, traducción y voz del BSC, centrados en lenguas de España.
- [Salamandra 7B Instruct](https://huggingface.co/BSC-LT/salamandra-7b-instruct) — Modelo de generación de texto del BSC (~8B parámetros).
- [Salamandra 2B Instruct](https://huggingface.co/BSC-LT/salamandra-2b-instruct) — Versión pequeña (2B) de Salamandra, apta para equipos modestos.
- [PlanTL-GOB-ES](https://huggingface.co/PlanTL-GOB-ES) — Modelos y datos del Plan de Tecnologías del Lenguaje del Gobierno de España.
- [RoBERTa base BNE](https://huggingface.co/PlanTL-GOB-ES/roberta-base-bne) — Modelo RoBERTa en español entrenado con datos de la Biblioteca Nacional.
- [BETO (bert-base-spanish-wwm-cased)](https://huggingface.co/dccuchile/bert-base-spanish-wwm-cased) — BERT en español de la Universidad de Chile.
- [BERTIN Project](https://huggingface.co/bertin-project) — Preentrenamiento y evaluación de modelos tipo BERT para español.
- [BERTIN RoBERTa base](https://huggingface.co/bertin-project/bertin-roberta-base-spanish) — Modelo RoBERTa en español del proyecto BERTIN.
- [Clibrain](https://huggingface.co/clibrain) — Organización con modelos de IA nativos en español.
- [Projecte Aina](https://huggingface.co/projecte-aina) — Modelos y traducción automática para el catalán.
- [HiTZ](https://huggingface.co/HiTZ) — Centro vasco de tecnología del lenguaje: PLN y procesamiento de señal.
- [Latxa 7B](https://huggingface.co/HiTZ/latxa-7b-v1.2) — Modelo de generación de texto para euskera de HiTZ.
- [Manuel Romero (mrm8488)](https://huggingface.co/mrm8488) — Cientos de modelos ajustados por un divulgador hispano de IA.
- [pysentimiento](https://huggingface.co/pysentimiento) — Modelos de análisis de opinión y sentimiento en redes sociales, enfocados en español.
- [Meta Llama](https://huggingface.co/meta-llama) — Perfil oficial de los modelos Llama de Meta.
- [Qwen](https://huggingface.co/Qwen) — Perfil oficial de la familia de modelos Qwen.
- [Mistral AI](https://huggingface.co/mistralai) — Perfil oficial de los modelos de Mistral.
- [Gemma 2 9B IT](https://huggingface.co/google/gemma-2-9b-it) — Modelo abierto de Google (9B) para generación de texto.
- [Whisper large v3](https://huggingface.co/openai/whisper-large-v3) — Modelo de reconocimiento de voz multilingüe de OpenAI.
- [paraphrase-multilingual-mpnet](https://huggingface.co/sentence-transformers/paraphrase-multilingual-mpnet-base-v2) — Embeddings multilingües para buscar frases similares.
- [multilingual-e5-large](https://huggingface.co/intfloat/multilingual-e5-large) — Modelo de embeddings multilingüe (0,6B) útil para búsqueda y RAG.
- [BGE-M3](https://huggingface.co/BAAI/bge-m3) — Modelo de similitud de frases multilingüe de BAAI.
- [sentence_similarity_spanish_es](https://huggingface.co/hiiamsid/sentence_similarity_spanish_es) — Modelo de similitud de frases específico para español.
- [opus-mt-en-es](https://huggingface.co/Helsinki-NLP/opus-mt-en-es) — Traducción automática inglés→español, ligera y local.
- [NLLB-200 distilled 600M](https://huggingface.co/facebook/nllb-200-distilled-600M) — Modelo de traducción de Meta entre 200 idiomas.

## 🤖 Agentes y automatización

- [n8n](https://github.com/n8n-io/n8n) — Automatización de flujos con IA; visual o con código, autoalojado o en la nube.
- [Dify](https://github.com/langgenius/dify) — Plataforma para flujos agénticos y RAG en un espacio colaborativo.
- [Flowise](https://github.com/FlowiseAI/Flowise) — Construye agentes de IA de forma visual.
- [Langflow](https://github.com/langflow-ai/langflow) — Herramienta para crear y desplegar agentes y flujos de IA.
- [LangChain](https://github.com/langchain-ai/langchain) — Plataforma de ingeniería de agentes.
- [LangGraph](https://github.com/langchain-ai/langgraph) — Construye agentes resilientes como grafos.
- [CrewAI](https://github.com/crewAIInc/crewAI) — Orquesta equipos de agentes autónomos con roles.
- [AutoGen](https://github.com/microsoft/autogen) — Framework de Microsoft para IA agéntica.
- [smolagents](https://github.com/huggingface/smolagents) — Librería minimalista de Hugging Face para agentes que piensan en código.
- [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) — Framework ligero para flujos multiagente.
- [Pydantic AI](https://github.com/pydantic/pydantic-ai) — Agentes en Python tipados de punta a punta, con cualquier modelo.
- [browser-use](https://github.com/browser-use/browser-use) — Librería Python para agentes que usan el navegador.
- [awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps) — Más de 100 agentes y apps RAG de código abierto listas para estudiar.
- [awesome-ai-agents](https://github.com/e2b-dev/awesome-ai-agents) — Lista de agentes autónomos de IA.

## 📄 RAG: IA sobre tus documentos

- [RAGFlow](https://github.com/infiniflow/ragflow) — Motor RAG de código abierto con capacidades de agente.
- [LlamaIndex](https://github.com/run-llama/llama_index) — Plataforma para procesar documentos y conectarlos a IA.
- [Haystack](https://github.com/deepset-ai/haystack) — Framework abierto para orquestar aplicaciones LLM listas para producción.
- [Chroma](https://github.com/chroma-core/chroma) — Infraestructura de búsqueda (base vectorial) para IA.
- [Qdrant](https://github.com/qdrant/qdrant) — Base de datos y motor de búsqueda vectorial de alto rendimiento.
- [Docling](https://github.com/docling-project/docling) — Prepara tus documentos (PDF, Office) para IA generativa.
- [MarkItDown](https://github.com/microsoft/markitdown) — Convierte archivos y documentos de Office a Markdown.

## 🔌 MCP (Model Context Protocol)

- [Documentación de MCP](https://modelcontextprotocol.io) — Qué es el Model Context Protocol y cómo conectar herramientas a la IA.
- [MCP servers (oficial)](https://github.com/modelcontextprotocol/servers) — Servidores MCP de referencia.
- [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) — Colección comunitaria de servidores MCP.
- [MCP Python SDK](https://github.com/modelcontextprotocol/python-sdk) — SDK oficial de Python para servidores y clientes MCP.
- [MCP TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk) — SDK oficial de TypeScript para MCP.
- [MCP Inspector](https://github.com/modelcontextprotocol/inspector) — Herramientas para probar servidores MCP.

## 🎙️ Voz: transcripción y síntesis

- [Whisper](https://github.com/openai/whisper) — Reconocimiento de voz robusto y multilingüe de OpenAI.
- [faster-whisper](https://github.com/SYSTRAN/faster-whisper) — Transcripción con Whisper más rápida gracias a CTranslate2.
- [whisper.cpp](https://github.com/ggml-org/whisper.cpp) — Whisper en C/C++ para correr en equipos modestos.
- [WhisperX](https://github.com/m-bain/whisperX) — Transcripción con marcas de tiempo por palabra y separación de hablantes.
- [Piper](https://github.com/rhasspy/piper) — Texto a voz neuronal, rápido y local.
- [Coqui TTS](https://github.com/coqui-ai/TTS) — Kit de deep learning para texto a voz.
- [ChatTTS](https://github.com/2noise/ChatTTS) — Modelo generativo de voz para diálogo cotidiano.
- [ElevenLabs](https://elevenlabs.io) — Generador de voz y agentes de voz con más de 90 idiomas (servicio comercial).

## 🎨 Imagen

- [ComfyUI](https://github.com/comfyanonymous/ComfyUI) — Interfaz modular por nodos para modelos de difusión.
- [Stable Diffusion web UI](https://github.com/AUTOMATIC1111/stable-diffusion-webui) — Interfaz web clásica para Stable Diffusion.
- [Fooocus](https://github.com/lllyasviel/Fooocus) — Generador de imágenes centrado en escribir el prompt, sin complicaciones.
- [InvokeAI](https://github.com/invoke-ai/InvokeAI) — Motor creativo para Stable Diffusion orientado a profesionales.
- [FLUX.1 schnell](https://huggingface.co/black-forest-labs/FLUX.1-schnell) — Modelo texto a imagen de Black Forest Labs (12B).
- [Diffusers](https://github.com/huggingface/diffusers) — Librería de Hugging Face para modelos de difusión de imagen, video y audio.

## 📏 Evaluación y rankings

- [La Leaderboard](https://huggingface.co/spaces/la-leaderboard/la-leaderboard) — Ranking de modelos de lenguaje filtrable por idioma, incluido el español.
- [LatamBench](https://github.com/crafter-research/latambench) — Benchmark de LLMs para el español de Latinoamérica.
- [LMArena](https://lmarena.ai) — Compara y vota modelos; ranking público de LLMs, imagen y código.
- [promptfoo](https://github.com/promptfoo/promptfoo) — Prueba prompts, agentes y RAG; incluye red teaming.
- [OpenAI Evals](https://github.com/openai/evals) — Framework y registro de benchmarks para evaluar LLMs.
- [lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness) — Framework para evaluar modelos con pocos ejemplos.
- [DeepEval](https://github.com/confident-ai/deepeval) — Framework de evaluación de LLMs.

## 🗂️ Datasets en español

- [somos-clean-alpaca-es](https://huggingface.co/datasets/somosnlp/somos-clean-alpaca-es) — ~52 mil instrucciones en español limpiadas por SomosNLP.
- [SQAC](https://huggingface.co/datasets/PlanTL-GOB-ES/SQAC) — Dataset de preguntas y respuestas en español.
- [STS-es](https://huggingface.co/datasets/PlanTL-GOB-ES/sts-es) — Similitud semántica de frases en español (~1,5 mil pares).
- [MLDoc](https://huggingface.co/datasets/PlanTL-GOB-ES/MLDoc) — Clasificación de documentos multilingüe, publicada por PlanTL.
- [CulturaX](https://huggingface.co/datasets/uonlp/CulturaX) — Gran corpus multilingüe limpio, con partición en español.
- [FineWeb-2](https://huggingface.co/datasets/HuggingFaceFW/fineweb-2) — Corpus web multilingüe de Hugging Face.
- [Common Voice 17](https://huggingface.co/datasets/mozilla-foundation/common_voice_17_0) — Grabaciones de voz donadas por la comunidad, con español.

## 👥 Comunidades y eventos

- [SomosNLP](https://somosnlp.org) — Comunidad internacional de hispanohablantes que trabajan en PLN.
- [SomosNLP en Hugging Face](https://huggingface.co/somosnlp) — Modelos, datasets y demos de la comunidad SomosNLP.
- [SEPLN](https://www.sepln.org) — Sociedad Española de Procesamiento del Lenguaje Natural.
- [KHIPU](https://khipu.ai) — Encuentro latinoamericano de inteligencia artificial.
- [LatinX in AI](https://www.latinxinai.org) — Organización que impulsa a personas latinas en la investigación de IA.
- [Foros de Hugging Face](https://discuss.huggingface.co) — Foro de la comunidad para dudas sobre modelos y librerías.

## Ejemplos de uso

En [`ejemplos/clientes/`](ejemplos/clientes/) hay perfiles **ficticios** de personas reales típicas y la ruta que les recomendamos, usando solo recursos de esta lista. Copia el perfil que más se parezca al tuyo y síguelo.

## Contribuir

Lee [CONTRIBUTING.md](CONTRIBUTING.md). Regla de oro: el enlace debe abrir y la descripción debe decir lo que la página realmente ofrece.

## English

*awesome-ia-en-español* is a curated list of 120 AI resources in Spanish or useful for Spanish speakers: courses, local LLM tools, agents, RAG, MCP, voice, image, evaluation, datasets and communities. Every link was opened and checked on 2026-11-01, and a weekly GitHub Action (lychee) re-checks them. Contributions welcome in Spanish or English; see CONTRIBUTING.md.

## Licencia

[CC0 1.0](LICENSE): dominio público. Las marcas y recursos enlazados pertenecen a sus dueños.
