# Problem 7 — A Trigonometric Composition

[Exercise sheet](../../../exercises/3_Calculus/02_derivatives_en.md)

## Problem

For

$$
f(x)=\sin(x^2+1)
$$

compute the derivative. Explicitly identify the outer function, the inner function, and the derivative of the inner function. Finally, determine the sign of $f'(0)$.

## Method

Identify the composition and apply the chain rule.

## Solution

The outer function is $F(u)=\sin u$, the inner function is $g(x)=x^2+1$, and $g'(x)=2x$. Since $F'(u)=\cos u$,

$$
f'(x)=\cos(x^2+1)\cdot2x.
$$

At $x=0$, $f'(0)=0$. Its sign at zero is neither positive nor negative; the tangent is horizontal there.

## Verification

For small $h$, the difference quotient at zero is $[\sin(1+h^2)-\sin1]/h$. The sine difference is bounded in magnitude by $h^2$, so the quotient is bounded by $|h|$ and tends to zero.
