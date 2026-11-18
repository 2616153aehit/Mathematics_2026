# Problem 2 — Powers, Roots, and the Domain

[Exercise sheet](../../../exercises/3_Calculus/04_integrals_en.md)

## Problem

Compute

$$
\int\left(2\sqrt{x}+\frac{3}{x^2}-x^{1/3}\right)\,dx.
$$

First rewrite the terms as powers, determine the domain of the original expression, and verify the result by differentiation.

## Method

Find the real domain and rewrite all terms as powers before using the antiderivative power rule.

## Solution

The integrand can be written as

$$
2x^{1/2}+3x^{-2}-x^{1/3}.
$$

The square root requires $x\geq0$, while the term $3/x^2$ requires $x\ne0$. Their intersection is therefore $x>0$, which is the domain of the original expression.

Applying the power rule term by term,

$$
\int\left(2x^{1/2}+3x^{-2}-x^{1/3}\right)dx
=\frac43x^{3/2}-\frac3x-\frac34x^{4/3}+C.
$$

On differentiating,

$$
\left(\frac43x^{3/2}-\frac3x-\frac34x^{4/3}+C\right)'
=2x^{1/2}+3x^{-2}-x^{1/3},
$$

which recovers the integrand for $x>0$.

## Verification

The differentiated result recovers every original term on $x>0$. The positive domain is necessary both for the square root and for the nonzero denominator.
