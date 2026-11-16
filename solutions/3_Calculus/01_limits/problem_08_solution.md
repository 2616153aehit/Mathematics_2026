# Exercise 8 — A Square Root in a Function Limit

[Exercise sheet](../../../exercises/3_Calculus/01_limits_en.md)

## Problem

Compute

$$
\lim_{x\to4}\frac{\sqrt{x}-2}{x-4}
$$

by rationalizing the numerator. Compare the idea with Exercise 3 involving a sequence.

## Method

Use the conjugate of the numerator to create a difference of squares, then cancel the common factor.

## Solution

For $x\ge0$ and $x\ne4$,

$$
\frac{\sqrt x-2}{x-4}
=\frac{(\sqrt x-2)(\sqrt x+2)}{(x-4)(\sqrt x+2)}
=\frac1{\sqrt x+2}.
$$

The new expression is continuous near $4$, with nonzero denominator. Therefore

$$
\lim_{x\to4}\frac{\sqrt x-2}{x-4}=\frac1{2+2}=\frac14.
$$

As in Exercise 3, conjugation replaces a difficult subtraction by a quotient. Here it removes a zero-over-zero form at a finite point rather than an infinity-minus-infinity form.

## Verification

The identity $(\sqrt x-2)(\sqrt x+2)=x-4$ verifies the cancellation. Values near $4$ from either side give denominators approaching $4$, so both one-sided limits equal $1/4$.
