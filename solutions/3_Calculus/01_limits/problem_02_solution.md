# Exercise 2 — Different Growth Rates

[Exercise sheet](../../../exercises/3_Calculus/01_limits_en.md)

## Problem

Compute

$$
\lim_{n\to\infty}\frac{3n+1}{n^2+4},\qquad \lim_{n\to\infty}\frac{2n^3-n}{5n^2+1}.
$$

Compare the two cases and formulate a general observation about the degrees of the polynomials in the numerator and denominator.

## Method

Compare the leading degrees after dividing by the dominant denominator power.

## Solution

For the first quotient,

$$
\frac{3n+1}{n^2+4}=\frac{3/n+1/n^2}{1+4/n^2}\longrightarrow0.
$$

The numerator has lower degree, so its growth is slower.

For the second quotient,

$$
\frac{2n^3-n}{5n^2+1}
=n\frac{2-1/n^2}{5+1/n^2}.
$$

The fraction tends to $2/5>0$, while $n$ tends to positive infinity. Thus

$$
\lim_{n\to\infty}\frac{2n^3-n}{5n^2+1}=+\infty.
$$

In general, a polynomial quotient tends to zero if the numerator degree is smaller, to the ratio of leading coefficients if the degrees are equal, and grows in magnitude if the numerator degree is larger. In the last case, the leading coefficients determine the eventual sign for positive $n$.

## Verification

For $n\ge1$, the first quotient lies between $0$ and $4/n$. The second is at least $n/6$, because $2n^3-n\ge n^3$ and $5n^2+1\le6n^2$. These bounds confirm the two different behaviors.
