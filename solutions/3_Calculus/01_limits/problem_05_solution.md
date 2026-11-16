# Exercise 5 — The Classical Limit Leading to the Number $e$

[Exercise sheet](../../../exercises/3_Calculus/01_limits_en.md)

## Problem

Compute

$$
\lim_{n\to\infty}\left(1+\frac1n\right)^n.
$$

Calculate several values for increasing $n$ and compare the observed behavior with the value of the limit. Explain why a few values do not constitute a proof.

## Method

Use the classical exponential limit, and compare numerical values with a logarithmic bound that supplies a proof.

## Solution

**Result**

$$
\lim_{n\to\infty}\left(1+\frac1n\right)^n=e\approx2.71828183.
$$

Some values, rounded to eight decimal places, are

| $n$ | $(1+1/n)^n$ |
| --- | --- |
| $1$ | $2.00000000$ |
| $2$ | $2.25000000$ |
| $5$ | $2.48832000$ |
| $10$ | $2.59374246$ |
| $100$ | $2.70481383$ |
| $1000$ | $2.71692393$ |

For a proof, use the logarithm bound

$$
\frac{u}{1+u}\le\ln(1+u)\le u,\qquad u>0.
$$

This follows by bounding the integrand $1/(1+s)$ between $1/(1+u)$ and $1$ on $0\le s\le u$. Set $u=1/n$ and multiply by $n$:

$$
\frac{n}{n+1}\le n\ln(1+1/n)\le1.
$$

Both bounds tend to $1$. Exponentiation therefore gives the limit $e$. The table suggests this behavior, but finitely many values do not control every sufficiently large index.

## Verification

The same inequalities give $e^{n/(n+1)}\le(1+1/n)^n\le e$. Both bounds tend to $e$, independently explaining why the numerical approximations approach that value.
