# Exercise 14 — A System of Equations and the Determinant

[Exercise sheet](../../../exercises/1_Algebra/02_determinants_en.md)

## Problem

Consider the system $Ax=b$, where

$$
A=
\begin{pmatrix}
1 & 2 \\
k & 4 \\
\end{pmatrix}.
$$

For which values of $k$ does the system have exactly one solution for every $b$? For the remaining value, give an example of a right-hand side $b$ for which the system has infinitely many solutions, and an example for which it has no solution.

## Method

A square system has exactly one solution for every right-hand side if and only if the coefficient matrix is invertible.

## Solution

The determinant is

$$
\det A=4-2k.
$$

Thus **$k\ne2$** gives exactly one solution for every $b$.

At $k=2$, the second left-hand side is twice the first. For $b=(1,2)^T$, the equations reduce to $x_1+2x_2=1$, so there are infinitely many solutions:

$$
(x_1,x_2)=(1-2s,s),\qquad s\in\mathbb R.
$$

For $b=(1,3)^T$, doubling the first equation gives $2x_1+4x_2=2$, which contradicts the second equation $2x_1+4x_2=3$. Hence no solution exists.

## Verification

Substitution gives $1-2s+2s=1$ and $2-4s+4s=2$ for every real $s$. In the inconsistent example, subtracting twice the first equation from the second gives $0=1$.
