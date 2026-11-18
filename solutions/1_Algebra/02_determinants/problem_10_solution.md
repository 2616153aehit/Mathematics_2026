# Exercise 10 — Detecting Dependence

[Exercise sheet](../../../exercises/1_Algebra/02_determinants_en.md)

## Problem

Without carrying out a full determinant calculation, explain why

$$
\det
\begin{pmatrix}
1 & 2 & 3 \\
2 & 4 & 6 \\
0 & 1 & 5 \\
\end{pmatrix}=0.
$$

Identify a specific dependence between the rows and connect it with noninvertibility of the matrix.

## Method

Recognize proportional rows before expanding the determinant.

## Solution

The second row is twice the first:

$$
R_2=2R_1.
$$

Consequently $R_2\leftarrow R_2-2R_1$ creates a zero row and leaves the determinant unchanged. A matrix with a zero row has determinant zero, so the original determinant is also zero.

**Result:** the rows are dependent, the rank is less than three, and the matrix has no inverse.

## Verification

The nonzero vector $(7,-5,1)^T$ is in the kernel: its row products are $7-10+3=0$, $14-20+6=0$, and $-5+5=0$.
