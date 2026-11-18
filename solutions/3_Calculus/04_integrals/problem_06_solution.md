# Problem 6 — When Does a Logarithm Appear from an Integral?

[Exercise sheet](../../../exercises/3_Calculus/04_integrals_en.md)

## Problem

Compute

$$
\int\frac{2x}{x^2+5}\,dx.
$$

Identify the denominator as a candidate for substitution, compare the numerator with its derivative, and explain the source of the logarithm in the result.

## Method

Recognize a derivative divided by its original expression and substitute the denominator.

## Solution

Let $u=x^2+5$. Its derivative is $du=2x\,dx$, exactly the numerator times $dx$. Therefore

$$
\int\frac{2x}{x^2+5}\,dx
=\int\frac1u\,du
=\ln|u|+C
=\ln(x^2+5)+C.
$$

The logarithm appears because its derivative is $1/u$, reversing the chain rule for $\ln|u(x)|$. Since $x^2+5>0$ for all real $x$, the absolute-value signs can be removed. The result is valid on all of $\mathbb R$.

## Verification

Differentiating $\ln(x^2+5)+C$ gives $2x/(x^2+5)$, recovering the integrand everywhere on its domain.
