# Problem 7 — Integration by Parts as Reversing the Product Rule

[Exercise sheet](../../../exercises/3_Calculus/04_integrals_en.md)

## Problem

Compute

$$
\int xe^x\,dx.
$$

First write the product differentiation rule and, on that basis, explain the meaning of the integration-by-parts formula. Verify the result by differentiation.

## Method

Derive integration by parts from the product rule, then differentiate the polynomial factor and integrate the exponential.

## Solution

The product rule is $(uv)'=u'v+uv'$. Integrating and rearranging gives

$$
\int u\,v'\,dx=uv-\int u'v\,dx.
$$

Thus integration by parts reverses the product rule. Choose $u=x$ and $v'=e^x$, so $u'=1$ and $v=e^x$. Then

$$
\int xe^x\,dx=xe^x-\int e^x\,dx=(x-1)e^x+C.
$$

Differentiating $x$ reduces its degree and leaves a simpler remaining integral.

## Verification

The derivative of $(x-1)e^x$ is $e^x+(x-1)e^x=xe^x$, which confirms the result and the minus sign.
