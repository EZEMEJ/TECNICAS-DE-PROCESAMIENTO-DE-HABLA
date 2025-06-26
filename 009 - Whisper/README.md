# Aplicaciones Multimodales con Modelos Generativos y Gradio

Este repositorio contiene notebooks que integran modelos de inteligencia artificial generativa para trabajar con entradas de **audio**, **imagen** y **texto**, a través de interfaces interactivas creadas con **Gradio**.

## Notebooks incluidos

---

### 1. `001_Whisper_Gemini_Summarizer.ipynb`

Pipeline multimodal que permite:

- **Transcripción de audio** con `Whisper` de OpenAI
- **Resumen de la transcripción** con un modelo generativo tipo `Gemini` o `GPT`
- Interfaz interactiva con Gradio

**Casos de uso:**
- Transcribir entrevistas o conferencias
- Obtener resúmenes automáticos de audio en segundos

---

### 2. `002_img_caption.ipynb`

Generación de **descripciones automáticas** de imágenes con modelos preentrenados de visión y lenguaje.

**Características:**
- Entrada: imagen cargada por el usuario
- Salida: descripción generada automáticamente (captioning)
- Posible uso de modelos como BLIP, Flamingo o Gemini

**Casos de uso:**
- Accesibilidad (para personas con discapacidad visual)
- Análisis de contenido multimedia
- Asistentes creativos

---

### 3. `003_Generación_de_descripciones_de_imágenes.ipynb`

Notebook complementario al anterior, posiblemente con:

- Otras arquitecturas de captioning
- Optimización del prompt o estructura de la salida
- Visualización mejorada de resultados

**Diferencias destacables:**
- Puede incorporar traducción al español
- Experimentos con distintos modelos o temperaturas

---

## Requisitos

Para ejecutar los notebooks, instalar:

```bash
pip install gradio openai transformers torch torchvision pillow google-generativeai