# Exercise 10 — Continuity of a Piecewise Function

[Exercise sheet](../../../exercises/3_Calculus/01_limits_en.md)

## Problem

Find $a$ so that

$$
f(x)=
\begin{cases}
ax+1,&x<2, \\
x^2-1,&x\ge2 \\
\end{cases}
$$

is continuous at $x=2$. Explicitly compare the left-hand limit, right-hand limit, and function value.

## Method

Continuity requires the left-hand limit, the right-hand limit, and the function value to be equal.

## Solution

The left branch gives

$$
\lim_{x\to2^-}f(x)=2a+1.
$$

The right branch applies at $x=2$, so

$$
\lim_{x\to2^+}f(x)=2^2-1=3,\qquad f(2)=3.
$$

Thus continuity requires $2a+1=3$, giving

$$
a=1.
$$

For this value, all three quantities are $3$. Since each branch is a polynomial, there is no additional branch-continuity condition near the joining point.

## Verification

With $a=1$, the left branch is $x+1$, which tends to $3$. The right branch $x^2-1$ also tends to $3$ and takes that value at $2$.
