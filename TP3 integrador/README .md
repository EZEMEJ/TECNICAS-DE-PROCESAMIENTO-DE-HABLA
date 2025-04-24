# Análisis de Texto de la Biografía de Leonardo da Vinci

Este cuaderno de Colab realiza un análisis de texto sobre la biografía de Leonardo da Vinci obtenida de la web [biografiasyvidas.com](https://www.biografiasyvidas.com/monografia/leonardo/).

## Funcionalidades

El cuaderno realiza las siguientes tareas:

1. **Extracción de texto:** Obtiene el texto de la biografía de la página web utilizando `requests` y `BeautifulSoup`.
2. **Preprocesamiento:** Limpia el texto convirtiéndolo a minúsculas, eliminando caracteres especiales y stop words.
3. **Lematización:** Utiliza spaCy para obtener la forma base de las palabras.
4. **Análisis de frecuencia:** Calcula la frecuencia de las palabras y las muestra en un DataFrame y una nube de palabras.
5. **Análisis morfológico:** Identifica la categoría gramatical, etiqueta y dependencia de cada token utilizando spaCy.
6. **Reconocimiento de entidades:** Detecta y visualiza las entidades nombradas en el texto.
7. **Visualización de dependencias:** Muestra las relaciones de dependencia entre las palabras en una visualización interactiva.

## Librerías utilizadas

- `requests`
- `beautifulsoup4`
- `nltk`
- `wordcloud`
- `spacy`
- `pandas`
- `matplotlib`
- `sklearn`

## Instrucciones de uso

1. Abre el cuaderno en Google Colab.
2. Ejecuta todas las celdas en orden.
3. Observa los resultados del análisis en las salidas de las celdas.

## Resultados

El análisis proporciona información sobre las palabras más frecuentes en la biografía de Leonardo da Vinci, su estructura gramatical y las entidades nombradas presentes en el texto.  Las visualizaciones ayudan a comprender mejor la información extraída.

## Nota

Este cuaderno está diseñado para fines educativos y de análisis.  Puede ser adaptado para analizar otros textos en español.

## Autor

MEJIAS IAIR EZEQUIEL