# Exercise 11 — Shortening the Calculation with Row Operations

[Exercise sheet](../../../exercises/1_Algebra/02_determinants_en.md)

## Problem

Compute

$$
\det
\begin{pmatrix}
1 & 2 & 3 \\
1 & 3 & 4 \\
1 & 4 & 6 \\
\end{pmatrix}
$$

by first performing row operations that create as many zeros as possible. State which operations do not change the determinant.

## Method

Subtract multiples of other rows to reach triangular form without changing the determinant.

## Solution

First apply $R_2\leftarrow R_2-R_1$ and $R_3\leftarrow R_3-R_1$.

$$
\begin{pmatrix}
1 & 2 & 3 \\
0 & 1 & 1 \\
0 & 2 & 3 \\
\end{pmatrix}
$$

Then apply $R_3\leftarrow R_3-2R_2$.

$$
\begin{pmatrix}
1 & 2 & 3 \\
0 & 1 & 1 \\
0 & 0 & 1 \\
\end{pmatrix}
$$

Every step adds a multiple of a different row, so none changes the determinant. The triangular diagonal product gives **$\det A=1$**.

## Verification

Direct expansion gives $1(18-16)-2(6-4)+3(4-3)=2-4+3=1$.
