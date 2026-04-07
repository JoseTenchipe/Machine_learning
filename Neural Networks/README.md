# Neural Networks

En esta sección se introduce el uso de redes neuronales artificiales para tareas de clasificación, empleando Python y la librería `scikit-learn`.

Se trabaja con datos simulados generados mediante técnicas de *clustering*, lo que permite visualizar de manera intuitiva cómo los modelos aprenden a separar distintas clases. Estos datos son representados gráficamente con el fin de comprender su distribución y la complejidad del problema.

---

## Modelo de clasificación

Se implementa un clasificador basado en redes neuronales, específicamente el **MLPClassifier**, explorando distintas arquitecturas mediante la variación del número de capas ocultas y de neuronas.

Este enfoque permite analizar cómo la complejidad del modelo influye en su capacidad de aprendizaje y generalización.

Las redes neuronales empleadas se fundamentan en capas interconectadas de neuronas artificiales, donde cada capa transforma la información de entrada hasta producir una predicción final.

---

## Función de pérdida

Un componente esencial en el entrenamiento de estos modelos es la función de pérdida, la cual mide el grado de ajuste entre las predicciones del modelo y los valores reales.

En este contexto, se utiliza la **entropía cruzada**, ampliamente empleada en problemas de clasificación, ya que permite cuantificar la diferencia entre las probabilidades predichas y las etiquetas verdaderas.

---

## Hiperparámetros

Se analiza el impacto de diversos hiperparámetros clave en el desempeño del modelo, entre los que se incluyen:

- Tasa de aprendizaje (*learning rate*)  
- Número de iteraciones (*epochs*)  
- Tamaño de la red  
- Profundidad (número de capas)  

---

## Optimización y validación

Se incorporan técnicas para la optimización y evaluación del modelo, tales como:

- **Grid Search**  
- **Randomized Search**  
- **Validación cruzada (K-Fold)**  

Estas metodologías permiten identificar configuraciones óptimas de hiperparámetros y mejorar el rendimiento del modelo.

---

## Visualización

La visualización de los datos y de los resultados se realiza mediante herramientas como `Matplotlib` y `Seaborn`, lo que facilita la interpretación del comportamiento del modelo y su capacidad de clasificación.
