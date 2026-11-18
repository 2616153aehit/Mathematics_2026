# Problem 2 — Powers, Roots, and the Domain

[Exercise sheet](../../../exercises/3_Calculus/02_derivatives_en.md)

## Problem

For

$$
f(x)=2\sqrt{x}-\frac{3}{x^2}+x^{3/2}
$$

1. rewrite the function using powers,
2. determine the domain,
3. compute the derivative,
4. compare the domain of the function with the domain of its derivative.

## Method

Rewrite roots and reciprocal powers before using the power rule; find the real domain first.

## Solution

The power form is

$$
f(x)=2x^{1/2}-3x^{-2}+x^{3/2}.
$$

The square root requires $x\ge0$, and the reciprocal term excludes zero. Hence $D_f=(0,\infty)$.

$$
\begin{aligned}
f'(x)&=2\cdot\frac12x^{-1/2}+6x^{-3}+\frac32x^{1/2} \\
&=\frac1{\sqrt x}+\frac6{x^3}+\frac32\sqrt x.
\end{aligned}
$$

Every term is defined for $x>0$, so $D_{f'}=(0,\infty)=D_f$. Zero was already excluded from the original function; differentiating does not remove an additional domain point here.

## Verification

At $x=1$, the three derivative contributions are $1$, $6$, and $3/2$, adding to $17/2$. The negative reciprocal term differentiates to a positive term, consistent with $(-3)(-2)=6$.
