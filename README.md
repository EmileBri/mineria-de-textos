# Minería de Textos, 2° cuatrimestre MCID

Tareas y proyecto integral de la materia Minería de Textos, Maestría en Ciencias e Ingeniería de Datos (MCID).

## Contenido

| Carpeta | Tema |
|---------|------|
| `Tarea_02/` | Modelo TF-IDF sobre dataset de películas |
| `Tarea_03/` | TF-IDF + K-Means (clustering de charlas TED) |
| `Tarea_04/` | Modelado de temas con LDA |
| `Tarea_05/` | POS Tagging y NER sobre textos literarios |
| `Proyecto Integral AA + MT/` | Clasificación de sentimiento en reseñas Amazon |

## Proyecto integral

Clasificación de sentimiento en reseñas de productos agrícolas de Amazon (positivo, neutro, negativo). El pipeline cubre preprocesamiento de texto, embeddings TF-IDF y Word2Vec, entrenamiento de clasificadores y una demo con Gradio.

Modelos entrenados y exportados:

- TF-IDF con SVM, KNN, MLP, Naive Bayes, Regresión Logística y Árbol de Decisión
- Word2Vec (CBOW y Skip-gram) con escaladores

## Tecnologías

Python 3.11, Jupyter, scikit-learn, NLTK, spaCy, Gensim, Gradio, pandas
