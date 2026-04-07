# Probabilidad en Python

En esta sección se aborda el estudio de la probabilidad mediante el uso de Python como herramienta principal para la resolución de problemas. Inicialmente, se desarrollan diversos ejemplos prácticos en los que se implementan funciones desde cero, sin recurrir a librerías especializadas en probabilidad, con el objetivo de fortalecer la comprensión de los fundamentos teóricos.

Entre los casos analizados se incluyen problemas de extracción de urnas y el problema de Newton aplicado al lanzamiento de dados. Estos ejercicios permiten descomponer paso a paso los procesos de cálculo probabilístico, favoreciendo un entendimiento riguroso a través de su implementación computacional.

Adicionalmente, se incorporan representaciones gráficas orientadas a la interpretación de conceptos fundamentales, tales como las frecuencias, las distribuciones de probabilidad, la esperanza matemática y la varianza. Para ello, se emplean herramientas como NumPy y Matplotlib, las cuales facilitan la visualización y el análisis de los resultados obtenidos.

### Muestreo aleatorio con NumPy

Se introduce el concepto de muestreo aleatorio a partir del Ensayo de Bernoulli, tomando como referencia el experimento del lanzamiento de una moneda. En este contexto, se define el espacio muestral Ω = {águila, sol} y una variable aleatoria X: Ω → {0,1}, junto con su correspondiente asignación de probabilidades: P(X(sol) = 1) = p y P(X(águila) = 0) = 1 − p, donde p ∈ (0,1).

Este planteamiento permite la simulación de experimentos aleatorios mediante programación, así como el análisis cuantitativo de sus resultados.

### Ruina del jugador

Finalmente, se estudia el problema de la ruina del jugador, un modelo clásico dentro de la teoría de la probabilidad que describe la evolución del capital de un individuo sometido a una sucesión de apuestas.

Este modelo permite analizar la probabilidad de que el jugador alcance un estado de ruina (pérdida total de su capital) o logre un objetivo específico, en función de su capital inicial y de las probabilidades asociadas a cada evento de ganancia o pérdida.
