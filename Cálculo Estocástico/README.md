# Cálculo Estocástico

En esta sección se presenta una ruta de aprendizaje para el estudio del cálculo estocástico, integrando teoría de probabilidad, procesos estocásticos y herramientas matemáticas avanzadas. El contenido se fundamenta en diversos materiales académicos, incluyendo libros y notas especializadas.

---

## Fundamentos de probabilidad avanzada

Se introducen conceptos esenciales para la construcción de una base teórica sólida:

- Espacios de probabilidad \((\Omega, \mathcal{F}, P)\)  
- Completitud de un espacio de probabilidad  
- Conjuntos nulos y su relevancia en la teoría de la medida  

Un espacio de probabilidad es completo si todo subconjunto de un conjunto de probabilidad cero es también medible. Esta propiedad resulta fundamental para garantizar consistencia en desarrollos probabilísticos avanzados.

---

## Variables aleatorias y tiempos de espera

Se analizan variables aleatorias continuas, con especial énfasis en:

- Distribución exponencial  
- Propiedades de los tiempos de espera  
- Relojes exponenciales independientes  

Si \(T_1, \dots, T_n\) son variables aleatorias independientes con distribución exponencial, entonces:

$$
T = \min(T_1, \dots, T_n)
$$

representa el instante en el que ocurre el primer evento dentro de un sistema compuesto por múltiples procesos aleatorios.

---

## Cadenas de Markov en tiempo continuo

Se introduce el estudio de procesos estocásticos en tiempo continuo, considerando:

- Definición de cadenas de Markov en tiempo continuo  
- Interpretación mediante tiempos de espera  
- Tiempos medios de paso  
- Clasificación de estados  
- Procesos de nacimiento y muerte  
- Procesos de nacimiento puro  

Asimismo, se analizan las ecuaciones *forward* y *backward*, las cuales describen la evolución temporal de estos sistemas.

---

## Movimiento Browniano y procesos Gaussianos

Se estudia el movimiento browniano como uno de los procesos fundamentales del cálculo estocástico:

- Definición de movimiento browniano estándar  
- Incrementos independientes y estacionarios  
- Distribución normal de los incrementos  

Por ejemplo, si \(B_t\) es un movimiento browniano, entonces:

$$
B_t - B_s \sim \mathcal{N}(0, t - s)
$$

También se examinan propiedades adicionales, como momentos de orden superior y características generales de los procesos gaussianos.

---

## Martingalas

Se introduce el concepto de martingalas, central en la teoría moderna de probabilidad:

- Definición de martingala  
- Propiedades fundamentales  
- Interpretación como modelos de "juego justo"  

Las martingalas tienen aplicaciones relevantes en finanzas, teoría de juegos y modelado de procesos aleatorios.

---

## Integración estocástica

Se desarrolla la construcción de la integral estocástica de manera rigurosa:

- Definición inicial para procesos simples (funciones escalonadas)  
- Extensión mediante convergencia en media cuadrática (\(L^2\))  
- Motivación: superar las limitaciones de las definiciones clásicas de integración  

Este enfoque permite definir integrales respecto al movimiento browniano, constituyendo la base del cálculo estocástico.

---

## Aplicaciones y conexión con otras áreas

El cálculo estocástico presenta múltiples aplicaciones en distintas disciplinas, tales como:

- Finanzas cuantitativas  
- Modelos de difusión  
- Inteligencia Artificial  
- Procesos de decisión  

Asimismo, se analizan ejemplos aplicados, entre los que destacan:

- Procesos de nacimiento y muerte  
- Modelos dinámicos en sistemas aleatorios  
