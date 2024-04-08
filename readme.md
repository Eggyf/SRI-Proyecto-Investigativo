
# Proyecto de SRI

## Detector de Plagio

### Integrante

- Abdel Fregel Hernández C412

### Descripción del problema

Se quiere detectar, dado dos documentos si uno es plagio del otro

### Consideraciones tomadas 

Para resolver este problema nos basaremos en la similitud coseno entre dos vectores. LLevaremos los documentos a una representacion vectorial para asi calcular mediante la similitud coseno que tanto se parece un texto a otro

### Requerimientos:

- Spacy
- Sckikit-learn
- Python
- Numpy
- Gensim
- Nltk

### Ejecutar el proyecto

- Instalar python y las librerias correspondientes y ejecutar el archivo start.py que se encuentra en la carpeta code2

### Explicación de la solucion

Utilizamos varias librerias que nos ayudan en esta tarea. Cargamos los documentos y con Spacy le aplicamos la tokenizacion y la eliminacion de stopwords para quedarnos con lo esencial para verificar el plagio. Luego con el modelo Word2Vec de gensim llevamos los tokens de los documentos a vectores y le aplicamos la similitud coseno para ver cuán parecido es un texto con otro

### Insufuciencias de la solución

Esta forma de abordar el problema no es la más óptima, existen otras como el modelo de n-gramas que cumplen mejor con la tarea, ya que dividimos los documentos en n-gramas del tamaño que queramos y vamos verificando si esos n-gramas se encuentran en ambos textos. Nuestra solución no tiene en cuenta el significado de las palabras en el texto esto lo hace ineficiente.

