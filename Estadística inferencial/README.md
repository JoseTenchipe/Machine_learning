# Estadística Inferencial

En esta sección se estudian los principales conceptos de la estadística inferencial mediante un enfoque tanto teórico como práctico, empleando Python como herramienta de apoyo. Se abordan modelos probabilísticos, técnicas de simulación y métodos de estimación, con el propósito de analizar el comportamiento de variables aleatorias y extraer conclusiones a partir de muestras.

---

## Modelos de distribución

Se considera una muestra aleatoria \( X_1, \dots, X_n \) cuya función de densidad está definida por:

$$
f_X(x;\theta) =
\begin{cases}
\theta x^{\theta - 1}, & 0 < x < 1,\ \theta > 0 \\
0, & \text{en otro caso}
\end{cases}
$$

Asimismo, se analiza la distribución Beta, haciendo uso de librerías como NumPy, Matplotlib y SciPy para:

- Generar muestras aleatorias  
- Visualizar funciones de densidad  
- Analizar el comportamiento de la distribución  

---

## Simulación de distribuciones

Se realizan simulaciones con diversas distribuciones pertenecientes a la familia exponencial, entre las que destacan:

- Distribución t de Student  
- Distribución Beta  
- Distribución Lognormal  
- Distribución Gamma  
- Distribución Poisson  
- Distribución Exponencial  

A través de estas simulaciones, se examina el comportamiento de los datos y la evolución de la media muestral, evidenciando empíricamente su convergencia hacia la media teórica, en concordancia con la Ley de los Grandes Números.

---

## Visualización y análisis

Mediante la utilización de gráficos generados con Matplotlib, se representan:

- Datos simulados  
- Trayectorias de la media muestral  
- Comparación con la media teórica  

Este enfoque permite una comprensión más clara del comportamiento estadístico de las muestras y facilita la interpretación de los resultados.

---

## Estimación por Máxima Verosimilitud (MLE)

Se estudia el método de Máxima Verosimilitud como herramienta para la estimación de parámetros. Sea \( X \) una variable aleatoria discreta con la siguiente distribución de probabilidad:

$$
P(X=0)=\frac{2}{3}\theta,\quad
P(X=1)=\frac{1}{3}\theta,\quad
P(X=2)=\frac{2}{3}(1-\theta),\quad
P(X=3)=\frac{1}{3}(1-\theta)
$$

Dada la muestra observada:

$$
(3,0,2,1,3,2,1,0,2,1)
$$

se construye la función de verosimilitud:

$$
L(\theta)=\frac{32}{243}\,\theta^5(1-\theta)^5
$$

A partir de la log-verosimilitud:

$$
\log L(\theta)=\log\left(\frac{32}{243}\right)+5\log(\theta)+5\log(1-\theta)
$$

se obtiene el estimador de máxima verosimilitud:

$$
\hat{\theta}=0.5
$$

El cual se verifica como un máximo mediante el análisis de la segunda derivada.
