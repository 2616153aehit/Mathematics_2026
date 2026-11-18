# Problem 3 — The Product Rule — Why Is It Needed?

[Exercise sheet](../../../exercises/3_Calculus/02_derivatives_en.md)

## Problem

For

$$
f(x)=(x^2+1)e^x
$$

compute the derivative. Then compare the correct result with the incorrect idea

$$
f'(x)\stackrel{?}{=}(2x)e^x
$$

and explain which term is missing.

## Method

The expression is a product of two changing factors, so both contributions in the product rule are required.

## Solution

Set $u=x^2+1$ and $v=e^x$. Then $u'=2x$ and $v'=e^x$, so

$$
\begin{aligned}
f'(x)&=u'v+uv' \\
&=2xe^x+(x^2+1)e^x \\
&=e^x(x+1)^2.
\end{aligned}
$$

The proposed expression $2xe^x$ contains only $u'v$. It misses the term $(x^2+1)e^x$, which accounts for the change in the exponential factor.

## Verification

At zero the correct derivative is $1$, while the proposed expression is $0$. Also the difference between the formulas is exactly $(x^2+1)e^x$, which never vanishes for real $x$.
