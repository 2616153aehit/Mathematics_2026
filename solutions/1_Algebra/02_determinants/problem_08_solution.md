# Exercise 8 — Determinant of a Product

[Exercise sheet](../../../exercises/1_Algebra/02_determinants_en.md)

## Problem

Let $A,B$ be square matrices such that $\det A=3$ and $\det B=-5$. Compute $\det(AB)$, $\det(BA)$ and, if it exists, $\det(A^{-1}B)$. Explain why the first two results are equal even though usually $AB\neq BA$.

## Method

Use $\det(AB)=\det A\det B$ and $\det(A^{-1})=1/\det A$.

## Solution

The two nonzero determinants show that both matrices are invertible. Therefore all three requested expressions exist.

$$
\det(AB)=3(-5)=-15,\qquad \det(BA)=(-5)3=-15.
$$

For the remaining product,

$$
\det(A^{-1}B)=\frac{\det B}{\det A}=-\frac53.
$$

The determinant values of $AB$ and $BA$ agree because their scalar factors commute. This does not imply that the matrices themselves commute: determinants do not uniquely determine matrices.

## Verification

The inverse identity follows from $AA^{-1}=I$: $\det A\det(A^{-1})=1$. Also $3(-5/3)=-5$, consistent with $A(A^{-1}B)=B$.
