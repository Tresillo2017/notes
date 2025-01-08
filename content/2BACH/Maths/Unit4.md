---
title: "Unidad 4. Algebra Lineas, Matrices, Sistemas de Ecuaciones y Determinantes"
date: "2025-01-08"
draft: false
tags:
  - Growing
---

# Matriz

$$
\begin{aligned}
A=\left(\begin{array}{cc}
1 & 2 & 4 \\
7 & -1 & 3 \\
\end{array}\right)
\end{aligned}
\quad \text { Matriz de } 2 \times 3
$$

$$
\begin{aligned}
B=\left(\begin{array}{cc}
7 & -2 \\
1 & -5 \\
\end{array}\right)
\end{aligned}
\quad \text { Matriz de } 2 \times 2
$$

## Operaciones con Matrices

### Suma

$$
\begin{aligned}
\left(\begin{array}{cc}
5 & 2 & -3 \\
4 & -7 & 1 \\
\end{array}\right)+\left(\begin{array}{cc}
1 & 0 & 4 \\
-2 & 3 & 0 \\
\end{array}\right)=\left(\begin{array}{cc}
6 & 2 & -7 \\
2 & -4 & 1 \\
\end{array}\right)
\end{aligned}
$$

$$
\begin{aligned}
\left(\begin{array}{cc}
1 & 2 & 4 \\
7 & -1 & 3 \\
\end{array}\right)+\left(\begin{array}{cc}
7 & -2 \\
1 & -5 \\
\end{array}\right) \text { No se pueden sumar }
\end{aligned}
$$

### Producto

$$
\begin{aligned}
-3 \times \left(\begin{array}{cc}
5 & 2 & -3 \\
4 & -7 & 1 \\
\end{array}\right)=\left(\begin{array}{cc}
-15 & -6 & 9 \\
-12 & 21 & -3 \\
\end{array}\right)
\end{aligned}
$$

### Triangulacion de matrices

$$
\begin{aligned}
\left(\begin{array}{cc}
1 & 2 & 3 \\
-1 & 0 & 5 \\
2 & -1 & 0 \\
\end{array}\right)
\begin{array}{l}
F1'=F1 \\
F2'=F2+F1 \\
F3'=2F1-F3 \\
\end{array}
\quad \Rightarrow \quad

\left(\begin{array}{cc}
1 & 2 & 3 \\
0 & 2 & 8 \\
0 & 5 & 6 \\
\end{array}\right)

\begin{array}{l}
F1^0=F1' \\
F2'=F2' \\
F3^0=5F2'-2F3' \\
\end{array}
\quad \Rightarrow \quad

\left(\begin{array}{cc}
1 & 2 & 3 \\
0 & 2 & 8 \\
0 & 0 & 28 \\
\end{array}\right)
\end{aligned}
$$
