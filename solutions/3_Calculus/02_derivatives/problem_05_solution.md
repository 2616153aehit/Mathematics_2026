# Problem 5 — The Chain Rule as Working Through Layers

[Exercise sheet](../../../exercises/3_Calculus/02_derivatives_en.md)

## Problem

For

$$
f(x)=(3x^2-2x+1)^5
$$

identify the inner and outer functions, compute their derivatives, and combine the result according to the chain rule. Explain the origin of the additional factor.

## Method

Differentiate the outer fifth power and multiply by the derivative of the inner quadratic.

## Solution

Let $g(x)=3x^2-2x+1$ and $F(u)=u^5$. Their derivatives are

$$
g'(x)=6x-2,\qquad F'(u)=5u^4.
$$

By the chain rule,

$$
f'(x)=F'(g(x))g'(x)=5(3x^2-2x+1)^4(6x-2).
$$

The extra factor $6x-2$ accounts for the rate at which the inner expression changes with $x$; the derivative of the outer power alone does not measure that rate.

## Verification

At $x=1/3$, the inner quadratic has derivative zero, so the full derivative is zero. At $x=0$, the formula gives $-10$. These checks retain the otherwise easily missed inner factor.
