# Problem 9 — A Logarithm and the Chain Rule

[Exercise sheet](../../../exercises/3_Calculus/02_derivatives_en.md)

## Problem

For

$$
f(x)=\ln(x^2+1)
$$

compute the derivative. Then determine the sign of $f'(x)$ for $x<0$, $x=0$, and $x>0$, and describe qualitatively how the function behaves around zero.

## Method

Use $(\ln g)'=g'/g$ and analyze the numerator because the denominator is always positive.

## Solution

Since $x^2+1>0$, the function is defined on all of $\mathbb R$. Its derivative is

$$
f'(x)=\frac{2x}{x^2+1}.
$$

| $x$ | $x<0$ | $x=0$ | $x>0$ |
| --- | --- | --- | --- |
| Sign of $f'(x)$ | Negative | Zero | Positive |
| Behavior of $f$ | Decreasing | Minimum | Increasing |

The function decreases toward $(0,0)$ and increases after it. Because $\ln(x^2+1)\ge0$, this is also the global minimum.

## Verification

The original function is even: $f(-x)=f(x)$. The derivative is odd, as required by its formula, and the sign change agrees with the symmetry and minimum at zero.
