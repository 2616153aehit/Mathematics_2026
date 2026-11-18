# Problem 11 — Derivative from the Definition

[Exercise sheet](../../../exercises/3_Calculus/02_derivatives_en.md)

## Problem

Using only

$$
f'(x)=\lim_{h\to0}\frac{f(x+h)-f(x)}h,
$$

find the derivative of $f(x)=x^2$. Compare the result with the power rule and indicate where the limit is used in the calculation.

## Method

Use the difference quotient from the definition, without applying a differentiation rule.

## Solution

For $h\ne0$,

$$
\frac{f(x+h)-f(x)}h
=\frac{(x+h)^2-x^2}{h}
=\frac{2xh+h^2}{h}=2x+h.
$$

The limit is taken only after this algebraic simplification:

$$
f'(x)=\lim_{h\to0}(2x+h)=2x.
$$

The result agrees with the power rule for $x^2$. The quotient is not evaluated at $h=0$; it is evaluated for nonzero $h$ and then allowed to approach zero.

## Verification

At $x=3$, the difference quotient is $6+h$ and tends to $6$, agreeing with the general result $2x$.
