# Problem 11 — A Parameter and the Number of Extrema

[Exercise sheet](../../../exercises/3_Calculus/03_function_analysis_en.md)

## Problem

For

$$
f_a(x)=x^3-3ax
$$

depending on $a$, determine the number of critical points and their character. Separate the parameter cases and justify why the structure of the graph changes.

## Method

Solve the critical-point equation separately for positive, zero, and negative parameter values.

## Solution

For every real $a$, the domain is $\mathbb R$ and

$$
f_a'(x)=3(x^2-a),\qquad f_a''(x)=6x.
$$

**If $a>0$**, there are two critical points, $x=\pm\sqrt a$. The derivative is positive outside them and negative between them. Hence

$$
\left(-\sqrt a,2a^{3/2}\right)
$$

is a local maximum, and

$$
\left(\sqrt a,-2a^{3/2}\right)
$$

is a local minimum. Neither is global, since the cubic is unbounded in both directions.

**If $a=0$**, the only critical point is $x=0$. The derivative $3x^2$ is positive on either side, so zero is a stationary inflection point, not an extremum. The function $x^3$ is strictly increasing.

**If $a<0$**, then $x^2-a>0$ everywhere. There are no critical points and no local extrema; the function is strictly increasing on $\mathbb R$.

The two turning points merge at zero when $a$ decreases to zero, then disappear for negative $a$. This explains the change in the graph family.

## Verification

For $a>0$, the second derivatives at the two critical points are $-6\sqrt a$ and $6\sqrt a$, confirming their types. For $a=0$, values on opposite sides of zero have opposite signs, ruling out either an extremum there.
