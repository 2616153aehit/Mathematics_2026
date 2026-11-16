# Exercise 1 — Dominant Terms in a Sequence

[Exercise sheet](../../../exercises/3_Calculus/01_limits_en.md)

## Problem

Compute

$$
\lim_{n\to\infty}\frac{4n^2-3n+1}{2n^2+5n-7}.
$$

Explain why the highest-degree terms determine the result.

## Method

Divide numerator and denominator by the highest power of the index, which is $n^2$.

## Solution

For sufficiently large positive integers $n$,

$$
\frac{4n^2-3n+1}{2n^2+5n-7}
=\frac{4-3/n+1/n^2}{2+5/n-7/n^2}.
$$

The terms $1/n$ and $1/n^2$ tend to zero. The new denominator tends to $2\ne0$, so the quotient limit rule applies.

**Result**

$$
\lim_{n\to\infty}\frac{4n^2-3n+1}{2n^2+5n-7}=\frac42=2.
$$

The degree-two terms dominate because the lower-degree terms vanish after division by $n^2$. The undefined term at $n=1$ has no effect on a limit as $n$ grows without bound.

## Verification

Subtracting the candidate limit gives $(-13n+15)/(2n^2+5n-7)$. After division by $n^2$, its numerator tends to zero and its denominator to $2$, so the error tends to zero.
