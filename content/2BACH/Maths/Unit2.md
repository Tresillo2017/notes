---
title: "Unidad 2. Derivadas"
date: "2025-01-07"
draft: false
tags:
  - Evergreen
---

# Derivada de una funcion en un punto

Dada la funcion $f(x)$ y el punto $a$ diremos que su derivada en $x=a$ se define como:

$$f'(a) = \lim_{h \to 0} \frac{f(a+h)-f(a)}{h}$$

### Ejemplo

$$
f(x) = x^2+3x \quad \Rightarrow \quad f'(x) = 2x+3 \quad \Rightarrow \quad \lim_{h \to 0} \frac{f(2+h)-f(2)}{h} = 7
$$

# Interpretacion geometrica de la Derivada

La derivada de una funcion en un punto es la pendiente de la recta tangente a la funcoin en dicho punto.

### Ejemplo

Hallar la ecuacion de la recta tangente en $f(x)=x^2+3x$ en $x=2$.

$$
f(2)=10 \quad \Rightarrow \quad P(2,10) \quad \Rightarrow \quad m=7 \\
y-b=m(x-a) \quad \Rightarrow \quad y-10=7(x-2) \quad \Rightarrow \quad y=7x-4
$$

# Reglas de derivacion

## Polinomios

1. $f(x) = 3x^5-6x^3+3x+2 \quad \Rightarrow \quad f'(x) = 15x^4-18x^2+3$
2. $f(x)=a \times x^m \quad \Rightarrow \quad f'(x) = m \times a \times x^{m-1}$

# Regla de la cadena

$$
(v \times u)' \quad \rightarrow \quad [(v(u(x)))]' \quad \Rightarrow \quad v' \times (u(x)) \times u'(x)
$$

# Funciones Irracionales

$$
f(x) = \sqrt{x^3+3x} \quad \Rightarrow \quad (x^3+3x)^{1/2} \quad \Rightarrow \quad \frac{1}{2} \times (x^3+3x)^{-1/2} \times (3x^2+3)
$$

# Derivadas sucesivas

$$
f(x)=x^4-2x^3+7x^2+3x-10 \\
f'(x)=4x^3-6x^2+14x+3 \\
f''(x)=12x^2-12x+14
$$

# Aplicaciones de la derivada

## Recta Tangente

Hallar la recta tangente a la curva

$y=\frac{x^2+1}{x-3}$ en $x=2$

$$
f'(x)=\frac{2x(x-3)-1 \times (x^2+1)}{(x-3)^2} \quad \Rightarrow \quad f(x) = \frac{x^2-6x+1}{(x-3)^2} \\
a=2 \quad \Rightarrow \quad f'(a)=f'(2) \quad \Rightarrow \quad f'(2)=-9 \\
y-b=m(x-a) \quad \Rightarrow \quad y-(5)=-9 \times (x-2) \quad \Rightarrow \quad y=-9x+13
$$

# Derivabilidad

Diremos que una funcion $f(x)$ es derivable en $x=a$ si se cumple que:
1. $f(x)$ es continua en $x=a$
2. $\exist f'(a)$

## Ejemplo

$$
f(x)=\begin{cases}
x^2-1 & \text{si } x \geq 2 \\
3x-2 & \text{si } x \ge 2 \\
\end{cases}

\quad \Rightarrow \quad \lim_{x \to 2} f(x) =
\begin{cases}
\lim_{x \to 2^-} x^2-1 = 3 \\
\lim_{x \to 2^+} 3x-2 = 4 \\
\end{cases}

\quad \Rightarrow \quad \nexists f'(2) \text { No es derivable}
$$

# Extremos relativos (Maximos y Minimos)

## Intervalos de crecimiento y decrecimiento

- Una funcion derivable sera creciente (decreciente) en un intervalo de su Dominio cuando su derivada ser positiva, &f'(x) \geq 0$ (negativa $f'(x) < 0$)
- Diremos que un punto es singular cuando $f'(x)=0$
- Un maximo relativo (minimo relativo) es aquel en el que la funcion pasa de ser creciente a decreciente (decreciente a creciente)
- Los intervalos de crecimiento y decrecimiento estaran delimitados por los puntos signulares, puntos de discontinuidad y puntos de cambio de definicion de la funcion
- Si una funcion es derivable en un maximo o minimo relativo, su derivada valdra 0

# Concavidad y Convexidad

## Puntos de inflexion

Diremos que una funcion es concava hacia arriva (hacia abajo) en un intervalo si en todos sus puntos se cumple que $f''(x) > 0$ ($f''(x) < 0$).
En un punto en el que la funcion pase de concava hacia arriba a concava hacia abajo o viceversa se la llamara punto de inflexion o punto de silla y si tiene segunda derivada esta valdra 0
