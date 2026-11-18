# Problem 2 — A Parabola from the Perspective of the Derivative

[Exercise sheet](../../../exercises/3_Calculus/03_function_analysis_en.md)

## Problem

For $f(x)=x^2-4x+1$, find the minimum using the derivative. Compare the result with the vertex form and explain why both approaches lead to the same point.

## Method

Find where the first derivative changes sign, then compare with completing the square.

## Solution

The domain is $\mathbb R$, and

$$
f'(x)=2x-4=2(x-2).
$$

The derivative is negative for $x<2$, zero at $2$, and positive for $x>2$. Thus $f$ decreases up to $2$ and increases after it. Its global minimum is

$$
f(2)=4-8+1=-3.
$$

Completing the square gives $f(x)=(x-2)^2-3$. Since the square is nonnegative, this also gives the vertex $(2,-3)$ as the unique global minimum. The two methods describe the same point: the slope becomes zero exactly at the bottom of the parabola.

## Verification

The second derivative is the positive constant $2$, so the stationary point is a strict minimum. The vertex form also shows directly that no value below $-3$ is possible.
