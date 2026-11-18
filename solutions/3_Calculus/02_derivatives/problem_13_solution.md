# Problem 13 — A Multi-Layer Composition

[Exercise sheet](../../../exercises/3_Calculus/02_derivatives_en.md)

## Problem

For

$$
f(x)=e^{\sin(x^2)}
$$

compute the derivative. First write the layers

$$
x\longrightarrow x^2\longrightarrow \sin(x^2)\longrightarrow e^{\sin(x^2)}
$$

and explain why differentiation moves through them in the reverse order.

## Method

Treat the expression as three nested functions and multiply the derivative of each layer.

## Solution

The layers are

$$
x\longrightarrow x^2\longrightarrow\sin(x^2)\longrightarrow e^{\sin(x^2)}.
$$

Differentiating starts at the outermost operation because the chain rule is $(F\circ g)'=F'(g)g'$. The outer exponential remains an exponential, the sine contributes a cosine, and the inner square contributes $2x$:

$$
f'(x)=e^{\sin(x^2)}\cos(x^2)\cdot2x.
$$

The product accounts for every layer in the composition.

## Verification

Taking a logarithm gives $\ln f(x)=\sin(x^2)$. Differentiation yields $f'(x)/f(x)=2x\cos(x^2)$, independently recovering the result.
