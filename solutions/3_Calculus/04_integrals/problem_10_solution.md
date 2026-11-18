# Problem 10 — Definite Integral and Checking the Result

[Exercise sheet](../../../exercises/3_Calculus/04_integrals_en.md)

## Problem

Before carrying out the exact calculation, estimate the possible range of values of the integral

$$
\int_0^2(x^2+1)\,dx,
$$

using

$$
1\le x^2+1\le5
$$

on $[0,2]$. Only then compute the integral exactly, compare the result with the earlier estimate, and explain what type of computational error such a check can detect.

## Method

Integrate the supplied pointwise bounds before evaluating an antiderivative.

## Solution

On an interval of length $2$, the bounds $1\le x^2+1\le5$ imply

$$
2=\int_0^2 1\,dx
\le\int_0^2(x^2+1)\,dx
\le\int_0^2 5\,dx=10.
$$

Only after this estimate, exact integration gives

$$
\int_0^2(x^2+1)\,dx
=\left[\frac{x^3}{3}+x\right]_0^2
=\frac83+2=\frac{14}{3}.
$$

The result $14/3\approx4.667$ lies within $[2,10]$. The bound can detect an impossible sign, a badly misplaced factor, or arithmetic producing a value outside this interval. It cannot rule out every error: an incorrect value could still lie within the bounds.

## Verification

The integrand is continuous and increasing. Its endpoint rectangle estimates are $2$ and $10$, consistent with the earlier bound. Differentiating $x^3/3+x$ independently recovers $x^2+1$.
