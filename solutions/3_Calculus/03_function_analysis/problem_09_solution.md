# Problem 9 — An Oblique Asymptote

[Exercise sheet](../../../exercises/3_Calculus/03_function_analysis_en.md)

## Problem

Analyze the asymptotes of

$$
f(x)=\frac{x^2+1}{x-1}.
$$

Perform polynomial division and explain why the remainder term vanishes for large $|x|$.

## Method

Perform polynomial division and compare the remainder with the candidate asymptote.

## Solution

The domain excludes $x=1$. Polynomial division gives

$$
\frac{x^2+1}{x-1}=x+1+\frac2{x-1}.
$$

Since the numerator of the original quotient is $2$ at $x=1$, there is a vertical asymptote there:

$$
\lim_{x\to1^-}f(x)=-\infty,\qquad
\lim_{x\to1^+}f(x)=+\infty.
$$

At both infinite ends,

$$
f(x)-(x+1)=\frac2{x-1}\longrightarrow0.
$$

Therefore **$y=x+1$ is the oblique asymptote** as $x\to\pm\infty$. A fixed numerator divided by an unbounded denominator tends to zero, explaining why the remainder disappears. There is no horizontal asymptote because the linear part is unbounded. The function lies below the oblique line when $x<1$ and above it when $x>1$.

## Verification

Multiplying the division identity by $x-1$ gives $(x+1)(x-1)+2=x^2+1$, verifying both the quotient and the remainder.
