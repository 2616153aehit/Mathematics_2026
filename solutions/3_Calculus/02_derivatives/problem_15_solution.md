# Problem 15 — The Difference Quotient as a Check of the Derivative

[Exercise sheet](../../../exercises/3_Calculus/02_derivatives_en.md)

## Problem

Choose one function from the problem set and a point $x_0$ at which the derivative exists. Compute $f'(x_0)$ exactly, and then calculate

$$
\frac{f(x_0+h)-f(x_0)}h
$$

for $h=1$, $0.1$, and $0.01$. Compare the values with $f'(x_0)$ and explain why the difference quotient approaching a single number is consistent with the definition of the derivative, while a few computations do not replace a limit argument.

## Method

Choose $f(x)=x^2$ from Problem 11 and compare a difference quotient with its proven derivative.

## Solution

Take $x_0=1$. The exact derivative is $f'(1)=2$. For nonzero $h$,

$$
\frac{f(1+h)-f(1)}h=\frac{(1+h)^2-1}{h}=2+h.
$$

| $h$ | Difference quotient | Error from $f'(1)$ |
| --- | --- | --- |
| $1$ | $3$ | $1$ |
| $0.1$ | $2.1$ | $0.1$ |
| $0.01$ | $2.01$ | $0.01$ |

The values approach $2$, consistently with the derivative definition. A finite table alone does not prove a limit: it checks only three increments. The exact identity proves the limit because the error is $|h|$, which tends to zero for increments of either sign.

## Verification

For any $\varepsilon>0$, choosing $0<|h|<\varepsilon$ makes the difference between the quotient and $2$ smaller than $\varepsilon$. This provides the limit argument missing from numerical evidence alone.
