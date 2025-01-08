---
title: "Unidad 1. Funciones, Limites y Continuidad"
draft: false
date: "2025-01-07"
tags:
  - Growing
---

# Funcion
La funcion es una relacion entre dos magnitudes A una se le llama dominio y a la otra imagen (recorrido). De manera que a cada valor del dominio le corresponde como maxmio un valor de la imagen

## Dominio de algunas familias de funciones

### Poliniomios

$$
f(x) = 5x^3 - 7x^2 + 2x - 0 \\
\text{Dom}(f) = \mathbb{R}
$$

### Racionales

$$
\begin{array}{l}
g(x)=\frac{4x-3}{x^2-3x+2} \\
Dom(g)=\mathbb{R}-\{1,2\}
\end{array}
$$

### Iracionales

$$
\begin{array}{l}
h(x)=\sqrt{2x+8} \\
Dom(h)=\subset{-4, +\infty \subset}
\end{array}
$$

### Exponenciales

$$
\begin{array}{l}
f(x)=3^2x-7 \\
Dom(f)=\mathbb{R}
\end{array}
$$

### Logaritmicas

$$
\begin{array}{l}
k(x)=\log{x-9} \\
Dom(k)=\subset{9, +\infty \subset}
\end{array}
$$

## Composicion de Funciones

$$
\begin{array}{l}
(f \ o\ g)(x)=f(g(x)) \\
f(\frac{2}{\sqrt{x+1}}) = \sqrt{\frac{2}{\sqrt{x+1}}+1} \\
\end{array}
$$

# Limites

## Limite de una funcion en un punto

Diremos que el limite de una funcion cuando x tiende a $a$ es $b$ cuando conforme $x$ toma valores proxims a $a$, $f(x)=$ toma valores proximos a $b$

$$
\begin{array}{l}
f(x)=4x-x^2 \\
\lim_{x \to 1} f(x)= \lim_{x \to 1} (4x-x^2)
\end{array}
$$
|   x   |    y    |     |   x   |     y     |
|:-----:|:-------:|:---:|:-----:|:---------:|
| 0.9   | 2.78    |     | 1.1   | 3.19      |
| 0.99  | 2.9799  |     | 1.01  | 3.0199    |
| 0.999 | 2.99799 |     | 1.001 | 3.001999  |


## Propiedades de los limites

$$
\begin{array}{l}
f(x)=x^2-1 \\
g(x) = 5x \\
\lim_{x \to 2} (f(x)+g(x)) = \lim_{x \to 2} (x^2-1+5x) = 13
\end{array}
$$

$$
\begin{array}{l}
\lim_{x \to 2} (f(x)) + \lim_{x \to 2} (g(x)) = \lim_{x \to 2} (x^2-1) + \lim_{x \to 2} (5x) = 3+10 = 13
\end{array}
$$

## Limites Infinitos

$$
\begin{array}{l}
\lim_{x \to -1} (\frac{2}{(x+1)^2}) = \frac{2}{0} = \infty \\
\lim_{x \to -1^-} (\frac{2}{(x+1)^2}) = +\infty \\
\lim_{x \to -1^+} (\frac{2}{(x+1)^2}) = +\infty
\end{array}
$$


## Limites en el infinito

$$
\begin{array}{l}
\lim_{x \to \infty} (-3x^2+x+7) = \lim_{x \to +\infty} (=3x^2) = -\infty \\
\lim_{x \to -\infty} (5x^3-3x+1) = \lim_{x \to -\infty} (5x^3) = -\infty
\end{array}
$$

## Indeterminaciones

Cuando calculamos limites nos podemos encontrar situaciones en las que el resultado sea
- Infinito
- 0
- Un valor finito distinto de 0

A estas situaciones las llamamos "indeterminaciones", hay 7

$$
\begin{array}{ccccccc}
\frac{0}{0} & \frac{\infty}{\infty} & \infty - \infty & 0 \cdot \infty & 1^\infty & \infty^0 & 0^0
\end{array}
$$

### Ejemplos

$$
\begin{array}{l}
\lim_{x \to +\infty} (\frac{x^3+x^2-6x}{x^3+5x}) = \frac{\infty}{\infty} \\
\lim_{x \to +\infty} (\frac{x^3}{x^3}) = 1
\end{array}
$$

# Asintotas

## Verticales

$$
\lim_{x \to a} (f(x))= \pm \infty \to x=a
$$

## Horizontales

$$
\lim_{x \to \pm \infty} (f(x) = b) \to y=b
$$

## Oblicuas

$$
\begin{cases}
\lim_{x \to \pm \infty} (\frac{f(x)}{x}) = m \ne 0 \\
\lim_{x \to \pm \infty} (f(x)-mx) = n
\end{cases}
$$

# Continuidad de una funcion en un punto

Diremos que una funcion es continua en $x=a$ cuando se cumplan 3 condiciones

$$
\begin{aligned}
&\bullet \ \exists \lim_{x \to a} f(x) \\
&\bullet \ \exists f(a) \\
&\bullet \ \lim_{x \to a} f(x) = f(a)
\end{aligned}
$$
