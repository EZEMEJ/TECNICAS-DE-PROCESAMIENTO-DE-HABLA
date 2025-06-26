
# TRABAJO PRÁCTICO FINAL INTEGRADOR

Este proyecto es un notebook de Google Colab que permite realizar web scraping de artículos de noticias de **Infobae** y **La Nación**, unificarlos en un archivo CSV y aplicar diversas técnicas de procesamiento de lenguaje natural (NLP) y análisis de datos. Finalmente, se crea una interfaz interactiva utilizando **Gradio** para visualizar y analizar el contenido extraído y procesado.

---

## 🧩 Características

- **Web Scraping**: Extrae títulos y texto de los últimos artículos de Infobae y La Nación.
- **Unificación de Datos**: Combina los datos de ambos sitios en un único DataFrame y los exporta a un archivo CSV.
- **Procesamiento de Lenguaje Natural (NLP)**:
  - Limpieza y Tokenización: Preprocesamiento del texto para eliminar ruido y dividirlo en unidades significativas.
  - Generación de Nubes de Palabras (WordCloud): Visualización de las palabras más frecuentes.
  - Extracción de Entidades Nombradas (NER): Identificación de personas, lugares y organizaciones usando Gemini.
  - Análisis de Sentimiento: Determinación de polaridad (positivo, negativo, neutro) con TextBlob, y visualización general.
  - Generación de Resúmenes y Tweets: Crea resúmenes concisos y tweets con modismos argentinos utilizando Gemini.
- **Interfaz Interactiva con Gradio**: Permite seleccionar artículos, aplicar análisis y visualizar resultados fácilmente.

---

## ▶️ Cómo usar

1. **Abrir el Notebook**: Abre el notebook en [Google Colab](https://colab.research.google.com/).
2. **Ejecutar las Celdas**: Corre todas las celdas secuencialmente. Se instalarán las dependencias, se realizará el scraping, y se procesarán los datos.
3. **Interactuar con Gradio**:
   - Aparecerá un enlace público generado por Gradio. Ábrelo en tu navegador.
   - Desde la interfaz podés:
     - **Seleccionar un artículo** del menú desplegable.
     - Hacer clic en:
       - 📄 **Mostrar texto**
       - 🧼 **Limpiar texto**
       - ☁️ **Generar WordCloud**
       - 🧠 **Extraer Entidades (NER)**
       - 🙂 **Análisis de Sentimiento**
       - 📝 **Resumen**
       - 🐦 **Generador de Tweet**

---

## 🔑 Requisitos

- Cuenta de Google para usar Google Colab.
- Clave de API de **Google Gemini** (configurada como secreto en Colab bajo el nombre `GOOGLE_API_KEY`).

---

## 📦 Dependencias

Las dependencias se instalan automáticamente con `!pip install ...` en la primera celda. Incluyen:

- `gradio`
- `transformers`
- `sentencepiece`
- `spacy`
- `wordcloud`
- `matplotlib`
- `textblob`
- `requests`
- `beautifulsoup4`
- `pandas`
- `google-generativeai`
- `nltk`

---

## 📁 Archivos generados

- `datos_combinados.csv`: Archivo CSV que contiene los artículos scrapeados de Infobae y La Nación.

---
