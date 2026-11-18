# Exercise 13 — Determinant by Elimination

[Exercise sheet](../../../exercises/1_Algebra/02_determinants_en.md)

## Problem

Compute the determinant

$$
A=
\begin{pmatrix}
1 & 2 & 3 \\
2 & 5 & 7 \\
1 & 0 & 2 \\
\end{pmatrix}
$$

using elimination. Record the effect of every row operation used on the value of the determinant.

## Method

Reach upper triangular form using only row additions, and record their determinant effect.

## Solution

$R_2\leftarrow R_2-2R_1$ and $R_3\leftarrow R_3-R_1$ both preserve the determinant.

$$
\begin{pmatrix}
1 & 2 & 3 \\
0 & 1 & 1 \\
0 & -2 & -1 \\
\end{pmatrix}
$$

$R_3\leftarrow R_3+2R_2$ also preserves it.

$$
\begin{pmatrix}
1 & 2 & 3 \\
0 & 1 & 1 \\
0 & 0 & 1 \\
\end{pmatrix}
$$

No row was exchanged or rescaled. Therefore **$\det A=1\cdot1\cdot1=1$**.

## Verification

First-row expansion of the original matrix yields $(10-0)-2(4-7)+3(0-5)=10+6-15=1$.
