# Exercise 7 — Limit at a Point and Canceling a Factor

[Exercise sheet](../../../exercises/3_Calculus/01_limits_en.md)

## Problem

Compute

$$
\lim_{x\to3}\frac{x^2-4x+3}{x-3}.
$$

Explain why the value of the function at $x=3$ is not needed to compute the limit.

## Method

Factor the numerator and cancel only for arguments different from the limiting point.

## Solution

Factorization gives

$$
x^2-4x+3=(x-1)(x-3).
$$

For $x\ne3$, the quotient is therefore $x-1$. Hence

$$
\lim_{x\to3}\frac{x^2-4x+3}{x-3}
=\lim_{x\to3}(x-1)=2.
$$

The original quotient is undefined at $x=3$, but a limit concerns nearby arguments different from $3$. Defining the function at that one point is unnecessary for this calculation.

## Verification

For $x\ne3$, the absolute difference between the quotient and $2$ is $|x-3|$. It can be made smaller than any positive tolerance by taking $x$ sufficiently close to $3$.
