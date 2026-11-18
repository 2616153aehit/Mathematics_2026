# Exercise 12 — A Parameter Revealed by a Row Operation

[Exercise sheet](../../../exercises/1_Algebra/02_determinants_en.md)

## Problem

For

$$
A(t)=
\begin{pmatrix}
1 & 2 & 3 \\
2 & 4 & t \\
0 & 1 & 1 \\
\end{pmatrix}
$$

find the values of $t$ for which the matrix is not invertible.

Before computing the determinant, perform the operation

$$
R_2\leftarrow R_2-2R_1
$$

and use the resulting structure. At the end, explain what special thing happens to the rows for the value of the parameter you found.

## Method

Use the requested row replacement, then expand along the row with two zeros.

## Solution

The determinant-preserving operation $R_2\leftarrow R_2-2R_1$ gives

$$
\begin{pmatrix}
1 & 2 & 3 \\
0 & 0 & t-6 \\
0 & 1 & 1 \\
\end{pmatrix}
$$

The entry $t-6$ is in position $(2,3)$, whose cofactor sign is negative.

$$
\det A(t)=-(t-6)\det\begin{pmatrix}
1 & 2 \\
0 & 1 \\
\end{pmatrix}=6-t.
$$

**Result:** the matrix is singular exactly at $t=6$. At that value, the original second row is twice the first, and the transformed second row is zero.

## Verification

Expanding the original matrix along the first row gives $(4-t)-4+6=6-t$, confirming the sign and the exceptional value.
