# Exercise 4 — Powers and Oscillation

[Exercise sheet](../../../exercises/3_Calculus/01_limits_en.md)

## Problem

Analyze

$$
\left(\frac23\right)^n,\qquad \left(\frac32\right)^n,\qquad (-1)^n,\qquad \frac{(-1)^n}{n}.
$$

For each sequence, describe the type of behavior and justify your answer.

## Method

Use geometric growth for the first two sequences, subsequences for pure oscillation, and squeezing for decaying oscillation.

## Solution

| Sequence | Behavior | Justification |
| --- | --- | --- |
| $(2/3)^n$ | Decreases to $0$ | Positive geometric sequence with ratio strictly between $0$ and $1$ |
| $(3/2)^n$ | Increases without bound | Positive geometric sequence with ratio greater than $1$ |
| $(-1)^n$ | No limit | Even terms equal $1$, odd terms equal $-1$ |
| $(-1)^n/n$ | Converges to $0$ | Oscillation is bounded in magnitude by $1/n$ |

For the last sequence,

$$
-\frac1n\le\frac{(-1)^n}{n}\le\frac1n.
$$

Both bounds tend to zero, so the squeeze theorem applies. Oscillation alone does not prevent convergence when its amplitude tends to zero.

## Verification

The even and odd subsequences of $(-1)^n$ have different limits, proving divergence. For $(-1)^n/n$, both subsequences tend to zero. Also $(3/2)^n\ge1+n/2$ by the binomial inequality, independently confirming unbounded growth.
