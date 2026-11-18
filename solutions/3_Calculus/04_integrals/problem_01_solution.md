# Problem 1 — Antiderivative and Verification

[Exercise sheet](../../../exercises/3_Calculus/04_integrals_en.md)

## Problem

For

$$
f(x)=3x^2-4x+5
$$

find one antiderivative $F(x)$. Write the entire family of antiderivatives, verify the result by differentiation, and explain the meaning of the constant $C$.

## Method

Integrate the polynomial term by term and include an arbitrary additive constant.

## Solution

Integrating term by term with the power rule gives

$$
F(x)=x^3-2x^2+5x
$$

as one antiderivative. The full family is

$$
F(x)=x^3-2x^2+5x+C,\qquad C\in\mathbb R.
$$

Differentiation verifies the result:

$$
F'(x)=3x^2-4x+5=f(x).
$$

The constant appears because every constant has derivative zero. Thus any two antiderivatives of the same function on an interval differ by a constant.

## Verification

The displayed differentiation recovers the original polynomial. The choice $C=0$ supplies one antiderivative; all other real constants translate it vertically without changing its derivative.
