---
layout: post
title: Resumen Completo Vectores y Matrices
date: 2025-03-15 09:06:00
description: Un resumen claro y conciso sobre definiciones, operaciones y propiedades fundamentales de vectores y matrices, ideal para estudiar.
tags: matrices vectores algebra UNED Algebra Lineal 
categories: algebra-lineal
citation: true
---

## 📚 Resumen Completo: Vectores y Matrices

### 🟢 1. Vectores

- **Vector Renglón**: Es una secuencia ordenada de números escrita horizontalmente.
  - Ejemplo: \((2, -4, 6)\).

- **Vector Columna**: Similar al vector renglón, pero escrito verticalmente.
  - Ejemplo:
    \[
    \begin{pmatrix}
    2 \\ -4 \\ 6
    \end{pmatrix}
    \]

- **Dimensión de un vector**: Indica la cantidad de componentes que tiene el vector.
  - Ejemplo: \((3, 5, 7)\) tiene dimensión 3.

- **Vector Cero**: Todos los componentes del vector son cero.
  - Ejemplo: \((0,0,0)\).

### 🟢 2. Matrices

- **Definición**: Arreglo rectangular de números organizados en filas y columnas.

- **Tamaño (m×n)**: Indica cuántas filas (m) y columnas (n) tiene.
  - Ejemplo:
    \[ \begin{pmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \end{pmatrix} \]
    Es una matriz de 2×3.

- **Matriz Cuadrada**: Matriz con el mismo número de filas y columnas.
  - Ejemplo (3×3):
    \[ \begin{pmatrix} 1 & 0 & -2 \\ 4 & 3 & 1 \\ 7 & 8 & 9 \end{pmatrix} \]

- **Matriz Cero**: Todos sus elementos son cero.
  - Ejemplo:
    \[ \begin{pmatrix} 0 & 0 \\ 0 & 0 \end{pmatrix} \]

### 🟢 2. Matrices

- **Definición**: Arreglo rectangular de números organizados en filas y columnas.
- **Tamaño (m×n)**: m filas y n columnas.
- **Matriz Cuadrada**: Igual número de filas y columnas.
- **Matriz Cero**: Matriz con todas las entradas iguales a cero.

### 🟢 3. Operaciones con matrices

- **Suma y Resta**:
  - Ejemplo:
    \[
    \begin{pmatrix} 1 & 2 \\ 3 & 4 \end{pmatrix}
    +
    \begin{pmatrix} 4 & 3 \\ 5 & 6 \end{pmatrix} =
    \begin{pmatrix} 5 & 7 \\ 8 & 8 \end{pmatrix}
    \]

- **Multiplicación por Escalar**:
  - Ejemplo:
    \[ 3 \cdot \begin{pmatrix} 1 & -1 \\ 2 & 0 \end{pmatrix} = \begin{pmatrix} 3 & -3 \\ 6 & 0 \end{pmatrix} \]

- **Combinaciones lineales**:
  - Ejemplo:
    \[2 \begin{pmatrix}1 & 0\\ 3 & 4\end{pmatrix} -  \begin{pmatrix}2 & 1\\ 0 & 3\end{pmatrix} = \begin{pmatrix}0 & -1\\ 4 & -3\end{pmatrix}\]

### 🟢 4. Propiedades

- **Conmutativa** (para la suma): \(A + B = B + A\)
- **Asociativa**: \((A + B) + C = A + (B + C)\)
- **Distributiva**:
  - \(\alpha (A + B) = \alpha A + \alpha B\)
- **Elemento Neutro** (Matriz Cero):
  - Ejemplo:
    \[ \begin{pmatrix} 4 & 2 \\ 3 & 1 \end{pmatrix} + \begin{pmatrix} 0 & 0 \\ 0 & 0 \end{pmatrix} = \begin{pmatrix} 4 & 2 \\ 3 & 1 \end{pmatrix} \]
- **Multiplicación por 1**:
  - Ejemplo:
    \[ 1 \cdot \begin{pmatrix} 7 & -3 \\ 2 & 0 \end{pmatrix} = \begin{pmatrix} 7 & -3 \\ 2 & 0 \end{pmatrix}\]
- **Multiplicación por 0**:
  - Ejemplo:
    \[ 0 \cdot \begin{pmatrix} 7 & -3 \\ 2 & 0 \end{pmatrix} = \begin{pmatrix} 0 & 0 \\ 0 & 0 \end{pmatrix} \]

### 🟢 5. Ejercicios clave

- **Igualdad de Matrices**: Compara cada entrada para encontrar valores desconocidos.
- **Operaciones Combinadas**: Multiplicaciones por escalares seguidas de suma o resta.
- **Matriz desconocida**: Encontrar matrices resolviendo ecuaciones matriciales
