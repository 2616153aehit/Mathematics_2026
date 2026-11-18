# Problem 8 — Choosing the Factors in Integration by Parts

[Exercise sheet](../../../exercises/3_Calculus/04_integrals_en.md)

## Problem

Compute

$$
\int x\cos x\,dx.
$$

Before calculating, justify why it is convenient to differentiate $x$ and integrate $\cos x$, rather than the other way around.

## Method

Use integration by parts with $u=x$ and $dv=\cos x\ dx$, so differentiating the polynomial simplifies the remaining integral.

## Solution

The choice gives $du=dx$ and $v=\sin x$. Therefore

$$
\begin{aligned}
\int x\cos x\,dx
&=x\sin x-\int\sin x\,dx \\
&=x\sin x+\cos x+C.
\end{aligned}
$$

Differentiating $x$ produces a constant. Reversing the choice would integrate $x$ to $x^2/2$ and leave an integral involving $x^2\sin x$, which is more complicated than the original one.

## Verification

Differentiation gives $\sin x+x\cos x-\sin x=x\cos x$. The cancellation checks both product-rule contributions.
