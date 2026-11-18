# Problem 4 — A Quotient and Domain Control

[Exercise sheet](../../../exercises/3_Calculus/02_derivatives_en.md)

## Problem

For

$$
f(x)=\frac{x^2+1}{x-1}
$$

determine the domain, compute the derivative, simplify the result, and explain why the restriction $x\neq1$ remains important.

## Method

Exclude a zero denominator, then use the quotient rule.

## Solution

The domain is $\mathbb R\setminus\{1\}$. For every $x\ne1$,

$$
\begin{aligned}
f'(x)&=\frac{2x(x-1)-(x^2+1)}{(x-1)^2} \\
&=\frac{x^2-2x-1}{(x-1)^2} \\
&=1-\frac2{(x-1)^2}.
\end{aligned}
$$

The original function is undefined at $1$, so it has no derivative there. Simplifying an expression cannot supply a missing value of the original function.

## Verification

Polynomial division gives $f(x)=x+1+2/(x-1)$. Differentiating this equivalent expression gives $1-2/(x-1)^2$ on the same domain.
