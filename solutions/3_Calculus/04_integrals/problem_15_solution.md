# Problem 15 — Recovering a Function from Its Derivative and a Condition

[Exercise sheet](../../../exercises/3_Calculus/04_integrals_en.md)

## Problem

The function $F$ satisfies

$$
F'(x)=2xe^{x^2}
$$

and

$$
F(0)=3.
$$

1. Recognize the method needed to find the function $F$.
2. Determine the entire family of functions with the given derivative.
3. Use the condition $F(0)=3$ to determine the correct constant.
4. Verify the final result by differentiation and substitution of $x=0$.

## Method

Recognize the derivative of the inner square in an exponential composition, then use the given value to determine the integration constant.

## Solution

The factor $2x$ is the derivative of $x^2$. Substitution with $u=x^2$ therefore gives the complete family

$$
F(x)=\int2xe^{x^2}\,dx=e^{x^2}+C,\qquad C\in\mathbb R.
$$

Using the condition at zero,

$$
F(0)=e^0+C=1+C=3\quad\Longrightarrow\quad C=2.
$$

**Result**

$$
F(x)=e^{x^2}+2,\qquad x\in\mathbb R.
$$

The constant changes the vertical position of the antiderivative but not its derivative.

## Verification

Differentiation gives $F'(x)=2xe^{x^2}$, and substitution gives $F(0)=1+2=3$. Both the derivative condition and the initial value are satisfied.
