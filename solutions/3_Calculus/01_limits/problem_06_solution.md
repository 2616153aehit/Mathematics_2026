# Exercise 6 — From a Sequence to a Function — Limit at Infinity

[Exercise sheet](../../../exercises/3_Calculus/01_limits_en.md)

## Problem

Compute

$$
\lim_{x\to\infty}\frac{3x^2-x+1}{5x^2+4x-2}.
$$

Compare the method with Exercise 1. Explain what changes when moving from $n$ to a real variable $x$, and what stays the same.

## Method

Use the same division by the highest power as in the sequence problem, now with a real variable.

## Solution

Divide both polynomials by $x^2$.

$$
\frac{3x^2-x+1}{5x^2+4x-2}
=\frac{3-1/x+1/x^2}{5+4/x-2/x^2}\longrightarrow\frac35.
$$

**Result:** the limit is $3/5$.

In Exercise 1, the argument runs through positive integers. Here $x$ can approach infinity through arbitrary real values. The vanishing reciprocal terms and the leading-coefficient ratio work in the same way for both.

## Verification

The difference from $3/5$ is $(-17x+11)/(5(5x^2+4x-2))$, which tends to zero because its numerator degree is smaller than its denominator degree.
