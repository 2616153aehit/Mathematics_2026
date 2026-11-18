# Problem 15 — Find the Error in the Monotonicity Analysis

[Exercise sheet](../../../exercises/3_Calculus/03_function_analysis_en.md)

## Problem

For the function

$$
f(x)=x^3-3x
$$

the derivative was correctly computed as

$$
f'(x)=3(x-1)(x+1).
$$

However, a student wrote the following conclusion:

> The derivative is positive between its zeros and negative outside them. Therefore, the function is decreasing on $(-\infty,-1)\cup(1,\infty)$, increasing on $(-1,1)$, has a local minimum at $x=-1$, and a local maximum at $x=1$.

1. Without differentiating again, explain why merely identifying the zeros of the derivative does not justify the stated sign chart, and find the error in the student's reasoning.
2. Construct the correct sign chart for $f'(x)$.
3. Give the correct intervals of monotonicity and the character of the extrema.
4. In each of the three intervals, choose one simple test point and show that the sign of the derivative confirms your classification.

## Method

The derivative zeros split the domain, but its signs must be checked using its factors or test values.

## Solution

The error is the reversal of the derivative signs. Knowing the roots $-1$ and $1$ only identifies possible sign-change locations. Here the two linear factors have the same sign outside the roots and opposite signs between them, and the leading factor $3$ is positive.

| Interval | Test point | $3(x-1)(x+1)$ | Behavior |
| --- | --- | --- | --- |
| $(-\infty,-1)$ | $-2$ | $3(-3)(-1)=9>0$ | Increasing |
| $(-1,1)$ | $0$ | $3(-1)(1)=-3<0$ | Decreasing |
| $(1,\infty)$ | $2$ | $3(1)(3)=9>0$ | Increasing |

At $x=-1$ the sign changes from positive to negative, so $(-1,2)$ is a local maximum. At $x=1$ it changes from negative to positive, so $(1,-2)$ is a local minimum. Both extrema in the original claim were therefore misclassified.

No additional differentiation is required: the given factored derivative contains all the sign information needed.

## Verification

Substitution in the original function gives $f(-1)=2$ and $f(1)=-2$. The three explicit derivative test values above establish the signs on all intervals, because no derivative root occurs inside any of them.
