# Exercise 12 — Exponential Function Limit

[Exercise sheet](../../../exercises/3_Calculus/01_limits_en.md)

## Problem

Compute

$$
\lim_{x\to0}(1+3x)^{1/x}.
$$

Connect the result with the limit from Exercise 5 and show the appropriate transformation.

## Method

Rescale the small argument to reveal the classical exponential-limit pattern.

## Solution

The base is positive for $x>-1/3$, so the expression is defined in a neighborhood of zero, apart from zero itself.

Put $u=3x$. Then $u\to0$ and $1/x=3/u$.

$$
(1+3x)^{1/x}
=\left((1+u)^{1/u}\right)^3\longrightarrow e^3.
$$

This is the real-variable version of the classical pattern in Exercise 5. To justify it on both sides, write

$$
\ln\left((1+3x)^{1/x}\right)
=3\frac{\ln(1+u)}{u}.
$$

The ratio $\ln(1+u)/u$ is the average of $1/(1+s)$ between $0$ and $u$. It lies between the minimum and maximum values of that integrand on the interval, both tending to $1$ as $u\to0$. Thus the logarithm tends to $3$ and the original expression tends to $e^3$.

## Verification

Exponentiation is continuous, and the logarithm argument remains positive near zero. Thus the logarithmic limit verifies the result without restricting the approach to positive arguments or integer indices.
