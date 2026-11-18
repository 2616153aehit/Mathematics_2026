# Exercise 6 — Parameter and Invertibility

[Exercise sheet](../../../exercises/1_Algebra/02_determinants_en.md)

## Problem

For

$$
A(t)=
\begin{pmatrix}
t & 1 \\
2 & t \\
\end{pmatrix}
$$

find all values of $t$ for which the matrix is not invertible. Explain how your answer is related to the determinant being zero.

## Method

A square matrix is singular exactly when its determinant is zero.

## Solution

$$
\det A(t)=t\cdot t-1\cdot2=t^2-2.
$$

Solve the singularity condition over the real numbers.

$$
t^2-2=0\quad\Longleftrightarrow\quad t=\pm\sqrt2.
$$

**Result:** the matrix is not invertible at $t=\sqrt2$ and $t=-\sqrt2$; it is invertible at every other real value.

## Verification

At either exceptional value, the nonzero vector $(1,-t)^T$ is sent to $(0,2-t^2)^T=(0,0)^T$. A nontrivial kernel independently confirms noninvertibility.
