---
title: "Unidad 3. Representacion grafica de funciones, Calculo integral de areas"
date: "2025-01-07"
draft: false
tags:
  - Growing
---

# Simetria
Diremos que una funcion tiene simetria par si se cumple que $f(-x)=f(x)$ para todo $x$ en el dominio de la funcion. Por ejemplo, la funcion $f(x)=x^2$ tiene simetria par porque $f(-x)=(-x)^2=x^2=f(x)$.

Diremos que una funcion tiene simetria impar (respecto al origen de coordenadas) si se cumple que f(-x)=-f(x) para todo x en el dominio de la funcion. Por ejemplo, la funcion $f(x)=x^3$ tiene simetria impar porque $f(-x)=(-x)^3=-x^3=-f(x)$.

## Par

![Simetria Par](/static/maths/par.png)

## Impar

![Simetria Impar](/static/maths/impar.png)

## Ejemplos
$\begin{aligned}
f(x)=x^4-8x^2+3 \\
f(-x)=(-x)^4-8(-x)^2+3=x^4-8x^2+3=f(x) \\
\text {Simetria Par}
\end{aligned}$

$\begin{aligned}
g(x)=9x^3-5x \\
g(-x)=9(-x)^3-5(-x)=-9x^3+5x=-f(x) \\
\text {Simetria Impar}
\end{aligned}$

$\begin{aligned}
h(x)=5x^2-x \\
h(-x)=5(-x)^2-(-x)=5x^2+x \neq h(x) \\
\text {No tiene simetria}
\end{aligned}$

# Periodicidad
Diremos que una funcion tiene un periodo T si para todo x de su dominio se cumple que $f(x+T)=f(x)$. Por ejemplo, la funcion $f(x)=\sin(x)$ tiene periodo $2\pi$ porque $\sin(2\pi+x)=\sin(x)$.

# Representacion Grafica de funciones

$f(x)=x^3-3x^2-4$

## Dominio

$Dom(f)=\mathbb{R}$

## Continuidad

Continua en todo su dominio

## Simetria

$$
\begin{aligned}
f(x)=x^3-3x^2-4 \\
f(-x)=(-x)^3-3(-x)^2-4=-x^3-3x^2-4 \neq f(x) \\
\text{No hay simetria}
\end{aligned}
$$

## Periodicidad

No hay perioricidad. Es un polinomio

## Puntos de corte con los ejes

$$
\begin{aligned}
f(0)=-4 \\
f(x)=0 \Rightarrow x^3-3x^2-4=0 \Rightarrow (x-1)(x^2+4x+4) \Rightarrow x^2-4x+4=0 \Rightarrow x=-2, x=-2
\end{aligned}
$$

## Crecimiento y decrecimiento

$f'(x)=3x^2-6x=0 \\ x(3x+6) \Rightarrow x=0, x=2$

## Asintotas

No hay

# Funciones exponenciales y logaritmicas

$y=x^2$

| x  | y   |
|----|-----|
| -2 | 1/4 |
| -1 | 1/2 |
| 0  | 1   |
| 1  | 2   |
| 2  | 4   |

$y=log_2(x)$

| x   | y  |
|-----|----|
| 1/4 | -2 |
| 1/2 | -1 |
| 1   | 0  |
| 2   | 1  |
| 4   | 2  |

![F](/static/maths/f.png)

# Calculo integral y Calculo de Primitivas

## Calculo de areas

$\text{Rectification de Curvas} \Rightarrow \text{Determinar rectas tangentes} \Rightarrow \text{Integral}$

$\text{Cuadratura de figuras planas} \Rightarrow \text{Calcular areas} \Rightarrow \text{Integral}$

$$
\begin{aligned}
f(x)=5x^2+7-1 \\
f'(x)=10x+7 \\
f'(x)=10x+7 \Rightarrow \text{Primitiva}=5x^2+7x+C
\end{aligned}
$$

$$
\begin{aligned}
\lim_{n\to 0} = \frac{f(a-h)-f(a)}{h} \\
\end{aligned}
$$

Dada f(X) diremos que F(x) es una primitiva suya si se cumple que $F'(x)=f(x)$

## Ejemplo

$$
\begin{aligned}
\text{Dada} \ f(x)=3x^2+5 \\
F'(x)=x^3+5x \text{ es una primitiva de } f(x) \\
F''(x)=x^3+5x+8 \text{ es una primitiva de } f(x) \\
F'''(x)=x^3+5x-10.000 \text{ es una primitiva de } f(x) \\
\end{aligned}
$$

Integral indefinida de $f(x)$
$$
\begin{aligned}
\int f(x)dx \\
\int (3x^2+5)dx \\
x^3+5x+C \\
\end{aligned}
$$

## Ejemplos
$$
\int (x+5)dx = \frac{x^2}{2}+5x+C \\
\int (20x^4dx) = \frac{20x^5}{5}+C=4x^5+C
$$

# Cambio de variable
$$
\int (\frac{x^2+2}{x^3+6x+1})dx \\
t=x^3+6x+1 \\
dt=(3x^2+6)dx \\
\int (\frac{1}{3} - \frac{1}{3} dt = \frac{1}{3} \int (\frac{1}{t}) dx = \frac{1}{3} \times \ln(|t|)+C \\
\frac{1}{3} \times \ln|x^3+6x+1| +C
$$

# Calculo de areas

$$
\int_{1}^{4} (3x+1)dx = \left[ \frac{3x^2}{2}+x \right]_{1}^{4} = \left[ \frac{3 \times 4^2}{2}+4 \right] - \left[ \frac{3 \times 1^2}{2}+1 \right] = 25.5 \overline{u}^2
$$

## Area delimitada entre dos curvas

$$
S_1 = \int_{b}^{a} g(x)dx \\
S_2 = \int_{b}^{a} f(x)dx \\
S = S_1 - S_2 \quad \Rightarrow \quad S = \int_{b}^{a} (g(x)dx - \int_{b}^{a} f(x)dx \\
S = \int_{b}^{a} (g(x)-f(x))dx
$$
