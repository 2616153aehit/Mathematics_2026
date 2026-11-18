# Problem 5 — An Exponential Function with a Maximum

[Exercise sheet](../../../exercises/3_Calculus/03_function_analysis_en.md)

## Problem

Analyze the monotonicity and extrema of

$$
f(x)=xe^{-x}.
$$

Also examine the behavior as $x\to\infty$ and explain how the limit affects the shape of the graph on the right-hand side.

## Method

Factor out the positive exponential from the derivative to determine its sign.

## Solution

The domain is $\mathbb R$, and

$$
f'(x)=e^{-x}-xe^{-x}=e^{-x}(1-x).
$$

Since $e^{-x}>0$, the sign depends only on $1-x$. The function is increasing on $(-\infty,1)$ and decreasing on $(1,\infty)$. Therefore its unique global maximum is

$$
(x,f(x))=(1,e^{-1}).
$$

There is no global minimum: as $x\to-\infty$, $xe^{-x}\to-\infty$. On the right,

$$
\lim_{x\to\infty}xe^{-x}
=\lim_{x\to\infty}\frac{x}{e^x}=0.
$$

For example, $e^x\ge x^2/2$ for $x>0$ gives $0\le xe^{-x}\le2/x$. Hence the right branch decreases toward the horizontal asymptote $y=0$ from above, without crossing it.

## Verification

The function vanishes only at zero. The second derivative $f''(x)=e^{-x}(x-2)$ gives $f''(1)=-e^{-1}<0$, independently checking the maximum.
