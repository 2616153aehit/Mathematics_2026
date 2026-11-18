# Problem 8 — Two Exponential Functions

[Exercise sheet](../../../exercises/3_Calculus/02_derivatives_en.md)

## Problem

For

$$
f(x)=e^{2x-3}+5^x
$$

compute the derivative. Explain why the factor $2$ appears in the first term and why $\ln5$ appears in the second.

## Method

Use the chain rule for the natural exponential and write a constant-base exponential as $a^x=e^{x\ln a}$.

## Solution

For the first term, the exponent has derivative $(2x-3)'=2$. For the second, $5^x=e^{x\ln5}$ and the exponent has derivative $\ln5$. Hence

$$
f'(x)=2e^{2x-3}+5^x\ln5.
$$

The factor $2$ comes from a nontrivial inner linear function. The factor $\ln5$ comes from changing the exponential base to $e$. Both terms are defined for all real $x$.

## Verification

Both derivative terms are positive for every real $x$, so the result is consistent with the fact that both original exponential terms are strictly increasing.
