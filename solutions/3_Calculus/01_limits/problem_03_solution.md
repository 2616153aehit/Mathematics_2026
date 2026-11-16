# Exercise 3 — A Square Root and Removing an Indeterminate Form

[Exercise sheet](../../../exercises/3_Calculus/01_limits_en.md)

## Problem

Compute

$$
\lim_{n\to\infty}\left(\sqrt{n^2+5n}-n\right).
$$

Use the conjugate expression and explain why this transformation removes the difficulty.

## Method

Multiply by the conjugate to replace subtraction of two growing quantities with a quotient.

## Solution

Rationalization gives

$$
\sqrt{n^2+5n}-n
=\frac{(n^2+5n)-n^2}{\sqrt{n^2+5n}+n}
=\frac{5n}{\sqrt{n^2+5n}+n}.
$$

Since $n>0$, divide by $n$ and use $\sqrt{n^2}=n$.

$$
\frac{5n}{\sqrt{n^2+5n}+n}
=\frac5{\sqrt{1+5/n}+1}\longrightarrow\frac52.
$$

**Result:** the limit is $5/2$. The conjugate removes the indeterminate subtraction of quantities tending to infinity.

## Verification

The transformed numerator is the constant $5$, and the denominator tends to $2$, which is nonzero. The difference of squares used in rationalization is exactly $5n$, so no approximation is involved.
