# Análisis de Sentimientos con Modelos de Machine Learning y Deep Learning

Este repositorio contiene una serie de notebooks en Jupyter que exploran distintas aproximaciones para la clasificación de sentimientos a partir de texto. El objetivo es comparar la evolución y el rendimiento de diferentes modelos, desde un perceptrón simple hasta modelos preentrenados de vanguardia.

## Contenido

### 1. `001_Clasificador de sentimientos con un Perceptrón simple.ipynb`
Este notebook implementa un clasificador de sentimientos utilizando un **Perceptrón simple**, el modelo más básico de red neuronal. Se realiza un preprocesamiento de los datos de texto, se vectorizan los documentos utilizando Bag of Words y se entrena el modelo con retropropagación básica.

**Características:**
- Tokenización y vectorización manual
- Entrenamiento de perceptrón simple desde cero
- Análisis de métricas de rendimiento

---

### 2. `002_Clasificación de Sentimientos con una Red Neuronal Multicapa.ipynb`
En este notebook se construye una **red neuronal multicapa (MLP)** utilizando frameworks como `scikit-learn` o `Keras` (según implementación). Mejora sobre el modelo anterior al permitir mayor capacidad de representación.

**Características:**
- Uso de TF-IDF o embeddings como entrada
- Arquitectura de red multicapa con función de activación ReLU o similares
- Evaluación del modelo con métricas estándar (accuracy, F1-score)

---

### 3. `003_Análisis de Sentimiento con Modelos Preentrenados de HuggingFace.ipynb`
Este notebook utiliza modelos **preentrenados del hub de HuggingFace**, como `bert-base-uncased`, para realizar clasificación de sentimientos con un rendimiento de estado del arte.

**Características:**
- Uso de `transformers` de HuggingFace
- Tokenización con `AutoTokenizer`
- Predicciones usando `pipeline` o `AutoModelForSequenceClassification`
- Alta precisión sin necesidad de entrenamiento

---

## Requisitos

- Python 3.8+
- Jupyter Notebook
- Bibliotecas:
  - `numpy`, `pandas`, `scikit-learn`
  - `matplotlib` o `seaborn` (opcional para visualización)
  - `transformers`, `torch` (para el notebook 003)
  - `nltk` o `spaCy` (según el preprocesamiento)

Puedes instalar las dependencias con:

```bash
pip install -r requirements.txt
