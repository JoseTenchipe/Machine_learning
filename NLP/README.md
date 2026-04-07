# NLP

En esta sección se abordan técnicas fundamentales de Procesamiento de Lenguaje Natural (*Natural Language Processing, NLP*), enfocadas en la representación, transformación y análisis de datos textuales mediante Python.

El texto, uno de los tipos de datos más comunes en ciencia de datos, se maneja generalmente como cadenas de caracteres (*strings*). A partir de este tipo de información, se aplican diversas técnicas para extraer conocimiento relevante y transformar el lenguaje natural en representaciones adecuadas para su procesamiento computacional.

---

## Representación de texto

Se estudian métodos de representación de texto que permiten identificar estructuras semánticas en grandes colecciones de documentos, entre los que destacan:

- **LSI (Latent Semantic Indexing)**  
- **LDA (Latent Dirichlet Allocation)**  

Estos modelos permiten identificar temas latentes dentro de un conjunto de documentos, facilitando el análisis semántico y la organización de grandes volúmenes de información textual.

---

## Word Embeddings

Se trabaja con representaciones vectoriales de palabras (*word embeddings*) mediante el uso de **FastText**, las cuales permiten mapear palabras a espacios vectoriales continuos.

Estas representaciones capturan relaciones semánticas y sintácticas, y son ampliamente utilizadas en tareas como:

- Clasificación de texto  
- Análisis de sentimientos  

---

## Preprocesamiento de texto

Dentro del tratamiento previo de los datos textuales, se abordan técnicas fundamentales como:

- **Stemming:** reducción de palabras a su raíz mediante reglas heurísticas  
- **Lematización:** transformación de palabras a su forma canónica (lema), considerando su contexto gramatical  

Ambas técnicas tienen como objetivo normalizar el texto, permitiendo que distintas variantes de una misma palabra sean tratadas como una sola unidad (*token*), lo cual mejora el desempeño de los modelos.

---

## Aplicaciones: análisis de sentimientos

Se estudia el análisis de sentimientos como una aplicación práctica relevante, en la cual se clasifican textos —como reseñas o comentarios— en categorías tales como positivas o negativas.

Para ello, se emplean tanto técnicas tradicionales como representaciones vectoriales modernas, permitiendo evaluar el contenido emocional de los textos.

