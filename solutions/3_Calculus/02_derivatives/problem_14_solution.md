# Problem 14 — Continuity and Differentiability of a Piecewise Function

[Exercise sheet](../../../exercises/3_Calculus/02_derivatives_en.md)

## Problem

Investigate the behavior at $x=0$ of

$$
f(x)=
\begin{cases}
x^2,&x\ge0, \\
ax,&x<0. \\
\end{cases}
$$

For which values of $a$ is the function continuous? For which values do the one-sided derivatives exist and agree? For which value of $a$ is the function differentiable? Explain why continuity alone is not sufficient.

## Method

Compare the one-sided function limits and then the one-sided difference quotients at zero.

## Solution

The value is $f(0)=0$. For every real parameter $a$,

$$
\lim_{x\to0^-}ax=0=\lim_{x\to0^+}x^2=f(0).
$$

Thus the function is continuous at zero for **all $a\in\mathbb R$**.

The one-sided derivatives are

$$
f'_-(0)=\lim_{h\to0^-}\frac{ah-0}{h}=a,
\qquad
f'_+(0)=\lim_{h\to0^+}\frac{h^2-0}{h}=0.
$$

Both exist as finite numbers for every real $a$. They agree exactly when $a=0$. Therefore the function is differentiable at zero **if and only if $a=0$**, with $f'(0)=0$.

Continuity only matches the heights of the two branches. Differentiability also matches their limiting slopes; a nonzero $a$ leaves a corner at zero.

## Verification

For $a=1$ the function is continuous but the one-sided slopes are $1$ and $0$, giving a direct counterexample to continuity implying differentiability. For $a=0$, the difference quotients are zero on the left and $h$ on the right, both tending to zero.
