# Aplicaciones NLP Interactivas con Gradio y Modelos Generativos

Este repositorio contiene tres notebooks que implementan interfaces interactivas usando **Gradio** para tareas de **Procesamiento de Lenguaje Natural (NLP)** con modelos generativos y reconocimiento de entidades. Los notebooks exploran desde interfaces básicas hasta integración con modelos como Gemini.

## Contenido

### 1. `gradio_genai_v1.ipynb`
Primera versión de una aplicación con Gradio utilizando un modelo generativo para generar texto o responder preguntas.

**Características:**
- Interfaz básica con `gradio.Interface`
- Entrada de texto del usuario y salida generada por modelo (como GPT o similar)
- Uso educativo/demostrativo de generación de texto
- Posible uso de `openai`, `transformers`, o APIs locales

---

### 2. `gradio_genai_v2.ipynb`
Versión extendida y mejorada de la app anterior, con funcionalidades adicionales para una experiencia más completa.

**Novedades respecto a la versión 1:**
- Inputs más estructurados (ej. selección de tareas)
- Respuestas más robustas del modelo
- Interfaz más pulida
- Posiblemente incorpora control de temperatura, longitud máxima, etc.

---

### 3. `ner_gemini_gradio.ipynb`
Aplicación interactiva que combina **Reconocimiento de Entidades Nombradas (NER)** con modelos tipo Gemini o similares, expuesta vía Gradio.

**Características:**
- Input de texto libre
- Visualización de entidades reconocidas en el texto
- Posible uso de modelos como Gemini, BERT o APIs de terceros
- Salida visual con etiquetas de tipo entidad (PER, LOC, ORG, etc.)
- Útil para tareas de análisis de texto, periodismo, etc.

---

## Requisitos

Para ejecutar los notebooks, asegúrate de tener instalado:

```bash
pip install gradio openai transformers google-generativeai
