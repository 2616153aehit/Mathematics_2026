# Problem 7 — A Trigonometric Function

[Exercise sheet](../../../exercises/3_Calculus/03_function_analysis_en.md)

## Problem

On $[0,2\pi]$, find the intervals of monotonicity and the extrema of

$$
f(x)=\sin x+\cos x.
$$

Include the endpoints of the interval and compare the function values at the critical points and at the endpoints.

## Method

Solve the trigonometric critical-point equation inside the prescribed interval, then include both boundary values.

## Solution

The derivative is

$$
f'(x)=\cos x-\sin x=\sqrt2\cos(x+\pi/4).
$$

Its zeros in $[0,2\pi]$ are $\pi/4$ and $5\pi/4$. The function increases on $[0,\pi/4]$, decreases on $[\pi/4,5\pi/4]$, and increases on $[5\pi/4,2\pi]$.

| Candidate | $0$ | $\pi/4$ | $5\pi/4$ | $2\pi$ |
| --- | --- | --- | --- | --- |
| Function value | $1$ | $\sqrt2$ | $-\sqrt2$ | $1$ |

Thus the absolute maximum is $\sqrt2$ at $\pi/4$, and the absolute minimum is $-\sqrt2$ at $5\pi/4$. These are also the interior local extrema. Neither endpoint is an absolute extremum. If extrema relative to the closed interval are counted, $0$ is a one-sided local minimum and $2\pi$ is a one-sided local maximum.

## Verification

The identity $\sin x+\cos x=\sqrt2\sin(x+\pi/4)$ bounds the function between $-\sqrt2$ and $\sqrt2$. The identified points attain the two bounds.
