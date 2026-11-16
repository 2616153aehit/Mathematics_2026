# Exercise 13 — Fundamental Trigonometric Limit

[Exercise sheet](../../../exercises/3_Calculus/01_limits_en.md)

## Problem

Using

$$
\lim_{x\to0}\frac{\sin x}{x}=1,
$$

compute

$$
\lim_{x\to0}\frac{\sin5x}{x},\qquad \lim_{x\to0}\frac{\sin2x}{\sin3x}.
$$

In each case, show how you reduce the expression to the fundamental limit.

## Method

Introduce the exact argument of each sine in the denominator, using angles measured in radians.

## Solution

For the first limit,

$$
\frac{\sin5x}{x}=5\frac{\sin5x}{5x}\longrightarrow5\cdot1=5.
$$

For the second,

$$
\frac{\sin2x}{\sin3x}
=\frac23\frac{\sin2x/(2x)}{\sin3x/(3x)}
\longrightarrow\frac23\frac11=\frac23.
$$

The denominator factor tends to $1\ne0$, so taking the quotient of these limits is valid. Both calculations reduce to the supplied fundamental limit.

## Verification

The factors $5$ and $2/3$ compensate exactly for the introduced denominators $5x$, $2x$, and $3x$. Thus the rewritings are identities for nearby nonzero arguments, not approximations.
