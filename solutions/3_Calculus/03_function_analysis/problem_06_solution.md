# Problem 6 — A Logarithmic Function

[Exercise sheet](../../../exercises/3_Calculus/03_function_analysis_en.md)

## Problem

Analyze the domain, zero, and monotonicity of

$$
f(x)=\ln x-x+1.
$$

Explain why the analysis must begin with the domain.

## Method

The logarithm first restricts the domain; then use the sign of $(1-x)/x$.

## Solution

The real logarithm requires $x>0$, so the domain is $(0,\infty)$. On that domain,

$$
f'(x)=\frac1x-1=\frac{1-x}{x}.
$$

The function increases on $(0,1)$ and decreases on $(1,\infty)$. At $x=1$,

$$
f(1)=\ln1-1+1=0.
$$

This is the unique global maximum and the only zero. In particular, $\ln x-x+1<0$ for every $x>0$ except $1$.

At the two domain ends, the function tends to $-\infty$: the logarithm diverges negatively at $0^+$, and the negative linear term dominates at infinity. The domain must come first because logarithms and the denominator in the derivative cannot be interpreted on all of $\mathbb R$.

## Verification

The second derivative is $-1/x^2<0$, so the graph is strictly concave. The familiar inequality $\ln x\le x-1$, with equality only at one, agrees with the zero and maximum found here.
