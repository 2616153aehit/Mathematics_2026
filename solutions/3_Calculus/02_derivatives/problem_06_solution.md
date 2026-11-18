# Problem 6 — Product Rule and Trigonometry

[Exercise sheet](../../../exercises/3_Calculus/02_derivatives_en.md)

## Problem

For

$$
f(x)=x\sin x+\cos x
$$

compute the derivative and simplify the result. Then compute $f'(0)$ and interpret the direction of the tangent line at that point.

## Method

Apply the product rule to $x\sin x$, then combine the trigonometric terms.

## Solution

The derivative is

$$
f'(x)=\sin x+x\cos x-\sin x=x\cos x.
$$

Therefore $f'(0)=0$. Since $f(0)=1$, the tangent line at that point is the horizontal line $y=1$.

## Verification

The two sine terms cancel exactly. Independently, $f(x)-f(0)=x\sin x+\cos x-1$; dividing by $x$ gives $\sin x+(\cos x-1)/x$, whose limit at zero is zero.
