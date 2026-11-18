# Problem 5 — The Same Substitution in a Different Context

[Exercise sheet](../../../exercises/3_Calculus/04_integrals_en.md)

## Problem

Compute

$$
\int xe^{x^2}\,dx.
$$

First compare the structure with Problem 4 and explain what is common despite the different appearance of the function.

## Method

Use the inner square as a substitution, accounting for the factor of two in its derivative.

## Solution

As in Problem 4, the integrand is a function of an inner expression multiplied by a constant multiple of that inner expression's derivative. Here the inner expression is $x^2$, whose derivative is $2x$.

Set $u=x^2$, so $du=2x\,dx$ and $x\,dx=\tfrac12du$. Then

$$
\int xe^{x^2}\,dx=\frac12\int e^u\,du
=\frac12e^u+C
=\frac12e^{x^2}+C.
$$

The differentiation check is

$$
\frac{d}{dx}\left(\frac12e^{x^2}+C\right)
=\frac12e^{x^2}(2x)=xe^{x^2},
$$

so the antiderivative is correct. The outer functions differ between Problems 4 and 5, but the shared structure is an outer function evaluated at an inner function together with the inner derivative, which permits substitution.

## Verification

The derivative check confirms the factor $1/2$. Substitution is valid at zero as well, since the final formula differentiates to the original integrand everywhere.
