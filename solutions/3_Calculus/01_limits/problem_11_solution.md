# Exercise 11 — An n-th Root

[Exercise sheet](../../../exercises/3_Calculus/01_limits_en.md)

## Problem

Compute

$$
\lim_{n\to\infty}\sqrt[n]{5^n+2^n}.
$$

Explain which term dominates and why the transformation looks different from the case of a quotient of polynomials.

## Method

Factor out the larger exponential before taking the root, then squeeze the remaining factor.

## Solution

The larger base, $5$, supplies the dominant term.

$$
\sqrt[n]{5^n+2^n}
=5\left(1+\left(\frac25\right)^n\right)^{1/n}.
$$

Since $0<(2/5)^n\le1$,

$$
1\le\left(1+\left(\frac25\right)^n\right)^{1/n}\le2^{1/n}.
$$

The upper bound is $e^{(\ln2)/n}\to1$. Therefore the middle term tends to $1$, giving

$$
\lim_{n\to\infty}\sqrt[n]{5^n+2^n}=5.
$$

For polynomial quotients, division by a power of $n$ exposes the leading coefficient. Here factoring $5^n$ and taking its $n$-th root exposes the dominant exponential base.

## Verification

Directly, $5^n\le5^n+2^n\le2\cdot5^n$. Taking positive $n$-th roots gives $5\le\sqrt[n]{5^n+2^n}\le5\cdot2^{1/n}$, and both bounds tend to $5$.
