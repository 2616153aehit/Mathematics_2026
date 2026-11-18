# Problem 3 — Recognizing Basic Antiderivatives

[Exercise sheet](../../../exercises/3_Calculus/04_integrals_en.md)

## Problem

Compute

$$
\int\left(2e^x+3\cos x-4\sin x\right)\,dx.
$$

Match each term with a known derivative and verify the entire result with one differentiation.

## Method

Match each term with a known exponential or trigonometric derivative.

## Solution

We use $(e^x)'=e^x$, $(\sin x)'=\cos x$, and $(\cos x)'=-\sin x$. Therefore termwise integration gives

$$
\int(2e^x+3\cos x-4\sin x)\,dx
=2e^x+3\sin x+4\cos x+C.
$$

The sign in the last term is positive because differentiating $4\cos x$ produces $-4\sin x$. Differentiating the whole result checks it at once:

$$
(2e^x+3\sin x+4\cos x+C)'=2e^x+3\cos x-4\sin x.
$$

## Verification

The derivative of $4\cos x$ is $-4\sin x$, checking the most easily confused sign. The whole derivative equals the original integrand.
