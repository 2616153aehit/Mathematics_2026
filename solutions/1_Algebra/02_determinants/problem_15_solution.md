# Exercise 15 — Combining Determinant Properties

[Exercise sheet](../../../exercises/1_Algebra/02_determinants_en.md)

## Problem

Let $A$ and $B$ be invertible $2\times2$ matrices with

$$
\det A=-2,\qquad \det B=3.
$$

Without finding the entries of the matrices, compute

$$
\det\left(B^{-1}A^TB\right).
$$

State the determinant properties you use in order and explain why the factors involving $B$ eventually cancel.

## Method

Apply multiplicativity, the inverse determinant rule, and transpose invariance, in that order.

## Solution

Multiplicativity separates the three factors:

$$
\det(B^{-1}A^TB)=\det(B^{-1})\det(A^T)\det B.
$$

The inverse and transpose properties then give

$$
\det(B^{-1}A^TB)=\frac1{\det B}\det A\det B
=\frac13(-2)3=-2.
$$

**Result:** the determinant is $-2$. The factors involving $B$ cancel because $\det B\ne0$; this cancellation concerns scalar determinants and does not require commuting matrix factors.

## Verification

The matrix $B^{-1}A^TB$ is similar to $A^T$. Similarity preserves determinants, and transposition preserves the determinant of $A$, giving the same answer.
