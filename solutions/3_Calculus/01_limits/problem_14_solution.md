# Exercise 14 — A $0/0$ Limit with Trigonometry

[Exercise sheet](../../../exercises/3_Calculus/01_limits_en.md)

## Problem

Compute

$$
\lim_{x\to0}\frac{1-\cos x}{x^2}.
$$

Justify the result without using l'Hôpital's rule, using a trigonometric identity and the fundamental limit.

## Method

Use the half-angle identity to turn the numerator into a square of a sine, then apply the fundamental limit.

## Solution

The identity $1-\cos x=2\sin^2(x/2)$ gives, for $x\ne0$,

$$
\frac{1-\cos x}{x^2}
=\frac{2\sin^2(x/2)}{x^2}
=\frac12\left(\frac{\sin(x/2)}{x/2}\right)^2.
$$

As $x\to0$, the ratio in parentheses tends to $1$. Hence

$$
\lim_{x\to0}\frac{1-\cos x}{x^2}=\frac12.
$$

This derivation uses a trigonometric identity and the given sine limit; l'Hôpital's rule is not needed.

## Verification

The coefficient is $1/2$ because $x^2=4(x/2)^2$. Since both one-sided sine ratios tend to $1$, squaring preserves the same two-sided result.
