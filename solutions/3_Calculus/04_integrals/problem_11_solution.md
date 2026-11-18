# Problem 11 — Choose the Method First

[Exercise sheet](../../../exercises/3_Calculus/04_integrals_en.md)

## Problem

For each integral, first write which method you choose and how you recognize it, and then compute:

1. $\int\sin(3x)\ dx$,
2. $\int x\ln x\ dx$,
3. $\int\frac{x}{\sqrt{x^2+1}}\ dx$.

## Method

Choose the method by structure: a linear composition, a product containing a logarithm, and an inner expression accompanied by its derivative.

## Solution

**1. Linear substitution.** In $\sin(3x)$ the inner derivative is the constant $3$. With $u=3x$,

$$
\int\sin(3x)\,dx=-\frac13\cos(3x)+C_1.
$$

**2. Integration by parts.** For $x\ln x$, choose $u=\ln x$ and $dv=x\ dx$. Then $du=dx/x$ and $v=x^2/2$:

$$
\begin{aligned}
\int x\ln x\,dx
&=\frac{x^2}{2}\ln x-\int\frac x2\,dx \\
&=\frac{x^2}{2}\ln x-\frac{x^2}{4}+C_2,\qquad x>0.
\end{aligned}
$$

**3. Inner substitution.** For $x/\sqrt{x^2+1}$, choose $u=x^2+1$ and $du=2x\ dx$:

$$
\int\frac{x}{\sqrt{x^2+1}}\,dx
=\frac12\int u^{-1/2}\,du
=\sqrt{x^2+1}+C_3.
$$

The first and third results are valid for every real $x$. The second is restricted to positive $x$ by its logarithm. The three arbitrary constants belong to three separate families.

## Verification

The three derivatives are respectively $\sin(3x)$, $x\ln x+x/2-x/2=x\ln x$, and $x/\sqrt{x^2+1}$. These checks recover all original integrands on their domains.
