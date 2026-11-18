# Problem 1 — Derivative of a Polynomial and the Slope of a Tangent Line

[Exercise sheet](../../../exercises/3_Calculus/02_derivatives_en.md)

## Problem

For

$$
f(x)=3x^5-2x^3+7x-4
$$

find $f'(x)$. Then compute $f'(0)$ and $f'(1)$, determine the signs of the obtained values, and explain what they say about the slope of the tangent line to the graph at these two points.

## Method

Use the sum rule and the power rule $\frac{d}{dx}x^n=nx^{n-1}$ term by term.

## Solution

The derivative of a constant is zero, so

$$
f'(x)=15x^4-6x^2+7.
$$

At the requested points,

$$
f'(0)=7>0,\qquad f'(1)=15-6+7=16>0.
$$

Both tangent lines slope upward from left to right. Their slopes are $7$ and $16$, respectively; the second is steeper.

## Verification

The points are $(0,-4)$ and $(1,4)$. The tangent lines are $y=7x-4$ and $y-4=16(x-1)$, which pass through the corresponding points and have the computed slopes.
