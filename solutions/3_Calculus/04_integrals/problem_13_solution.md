# Problem 13 — An Integral Depending on the Upper Limit

[Exercise sheet](../../../exercises/3_Calculus/04_integrals_en.md)

## Problem

Let

$$
F(x)=\int_0^x(t^2+1)\,dt.
$$

Determine $F(x)$, compute $F'(x)$, and compare the result with the integrand. Explain in your own words why the height of the function describes the local rate of increase of the accumulated area.

## Method

Evaluate the integral in its dummy variable, then differentiate the resulting expression and interpret the fundamental theorem of calculus.

## Solution

For every real $x$,

$$
F(x)=\left[\frac{t^3}{3}+t\right]_0^x=\frac{x^3}{3}+x,
\qquad F'(x)=x^2+1.
$$

The derivative equals the integrand evaluated at the upper limit. Increasing the upper limit by a small amount $h$ adds a narrow signed strip whose area is approximately $(x^2+1)h$. Dividing by $h$ and taking the limit gives its height, $x^2+1$, as the rate of accumulation.

For $x<0$, the reversed integration direction makes $F(x)$ negative; the same formula describes signed accumulation, rather than a nonnegative geometric area.

## Verification

The exact difference quotient is $[F(x+h)-F(x)]/h=x^2+1+xh+h^2/3$. Its limit is $x^2+1$, proving the local-rate statement directly. Also $F(0)=0$ as required by equal integration limits.
