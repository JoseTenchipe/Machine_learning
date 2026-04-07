# Curso Machine Learning

En esta sección se desarrollan diversos modelos y técnicas fundamentales de *Machine Learning*, combinando fundamentos teóricos con implementaciones prácticas en Python aplicadas a conjuntos de datos reales.

Se abordan problemas de regresión, clasificación, reducción de dimensionalidad y modelado de series de tiempo, con el objetivo de comprender la aplicación de algoritmos de aprendizaje automático en distintos contextos.

---

## Modelos de regresión

Se trabaja con datasets como *50 Startups*, en los que se implementan modelos de:

- Regresión Lineal  
- Regresión Lineal Múltiple  

Estos modelos permiten analizar la relación entre variables y realizar predicciones sobre variables continuas.

---

## Modelos de clasificación

Se estudian modelos de clasificación, como la regresión logística, utilizando la librería `scikit-learn`. Estos enfoques permiten abordar problemas en los que la variable objetivo es categórica, facilitando la predicción de clases a partir de datos de entrada.

---

## Reducción de dimensionalidad

Se analizan técnicas orientadas a reducir la complejidad de los datos, entre las que destacan:

- **PCA (Análisis de Componentes Principales):** técnica que transforma datos de alta dimensión en un espacio de menor dimensión, conservando la mayor parte de la varianza.  
- **LDA (Análisis Discriminante Lineal):** método supervisado que maximiza la separabilidad entre clases, contribuyendo a mejorar el rendimiento del modelo y reducir el sobreajuste.  

Estas técnicas permiten:

- Analizar la correlación entre variables  
- Reducir la complejidad de los datos  
- Visualizar datos en espacios de menor dimensión  
- Evaluar el impacto del número de componentes en el desempeño del modelo  

---

## Regularización

Se incorporan modelos lineales regularizados, tales como:

- Ridge  
- Lasso  

Estos métodos introducen penalizaciones sobre los coeficientes del modelo con el fin de prevenir el sobreajuste y mejorar la capacidad de generalización.

---

## Redes neuronales y series de tiempo

Se introduce el uso de redes neuronales recurrentes, específicamente el modelo **LSTM (Long Short-Term Memory)**, aplicado a la predicción de precios de acciones.

Este enfoque permite capturar dependencias temporales en datos secuenciales, siendo especialmente útil en el análisis de series de tiempo financieras.

