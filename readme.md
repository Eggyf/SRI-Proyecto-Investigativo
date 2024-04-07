
# Proyecto de SRI

## Detector de Plagio

### Integrante

- Abdel Fregel Hernández C412

### Requerimientos:

- Spacy
- Sckikit-learn
- Python
- Numpy
- Gensim
- Nltk

### Ejecutar el proyecto

- Instalar python y las librerias correspondientes y ejecutar el archivo start.py

### Descripción

El proyecto consiste en detectar plagio entre dos documentos. Para realizar esta tarea procesamos los textos de los documentos, los tokenizamos, le quitamos el ruido y las stopwords, aplicamos reducción morfológica, los filtramos por ocurrencia y con el resultado construimos el vocabulario. Luego vectorizamos los documentos para a través de la similaridad coseno ver que tanto se parecen dos documentos y así verificar el plagio
