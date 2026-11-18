# Problem 4 — A Function with Two Vertical Asymptotes

[Exercise sheet](../../../exercises/3_Calculus/03_function_analysis_en.md)

## Problem

Analyze

$$
f(x)=\frac1{x^2-1}.
$$

Determine the domain, asymptotes, sign, and monotonicity on the intervals of the domain. Explain why each interval must be analyzed separately.

## Method

Factor the denominator for the sign chart and use the derivative separately on each connected part of the domain.

## Solution

The domain is $\mathbb R\setminus\{-1,1\}$. There are no zeros because the numerator is always $1$.

| Interval | Sign of $f$ | Sign of $f'$ | Behavior |
| --- | --- | --- | --- |
| $(-\infty,-1)$ | $+$ | $+$ | Increasing |
| $(-1,0)$ | $-$ | $+$ | Increasing |
| $(0,1)$ | $-$ | $-$ | Decreasing |
| $(1,\infty)$ | $+$ | $-$ | Decreasing |

The derivative used here is

$$
f'(x)=-\frac{2x}{(x^2-1)^2}.
$$

Both $x=-1$ and $x=1$ are vertical asymptotes:

$$
\begin{aligned}
\lim_{x\to-1^-}f(x)&=+\infty,&\lim_{x\to-1^+}f(x)&=-\infty, \\
\lim_{x\to1^-}f(x)&=-\infty,&\lim_{x\to1^+}f(x)&=+\infty.
\end{aligned}
$$

At either infinite end the function tends to $0$ from above, so $y=0$ is a horizontal asymptote. The stationary point $(0,-1)$ is a local maximum on the middle branch.

The undefined points split the domain into three separate intervals. An increasing-interval statement cannot pass through an asymptote, where the function is not defined.

## Verification

The function is even, and the sign and monotonicity charts are mirror images across the vertical axis. The sample values $f(-2)=f(2)=1/3$ and $f(0)=-1$ confirm the sign chart.
