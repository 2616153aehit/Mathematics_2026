# Problem 12 — Several Rules at Once

[Exercise sheet](../../../exercises/3_Calculus/02_derivatives_en.md)

## Problem

For

$$
f(x)=(x^2+1)^3e^x
$$

compute the derivative. Before calculating, write down a plan: which rule applies to the whole expression and which rule applies to one of its factors. Finally, organize the result by factoring out common factors.

## Method

Plan: apply the product rule to the whole expression, and apply the chain rule to the factor $(x^2+1)^3$.

## Solution

The derivative of the first factor is $3(x^2+1)^2\cdot2x$. Consequently

$$
\begin{aligned}
f'(x)&=6x(x^2+1)^2e^x+(x^2+1)^3e^x \\
&=e^x(x^2+1)^2\bigl(6x+x^2+1\bigr).
\end{aligned}
$$

Factoring out $e^x(x^2+1)^2$ separates the common positive factor from the remaining quadratic.

## Verification

The original function is positive, so logarithmic differentiation is available as an independent check: $f'/f=6x/(x^2+1)+1$. Multiplying by $f$ gives the same factored derivative.
