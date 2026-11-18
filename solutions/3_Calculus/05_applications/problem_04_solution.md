# Problem 4 — Area Between Curves

[Exercise sheet](../../../exercises/3_Calculus/05_applications_en.md)

## Problem

Find the area of the region bounded by the graphs

$$
y=x
$$

and

$$
y=x^2.
$$

First find the intersection points and justify which function is greater on the relevant interval.

## Method

Find intersections first, compare the curves between them, and integrate upper minus lower.

## Solution

The intersection condition $x=x^2$ factors as $x(x-1)=0$. Thus the curves meet at $(0,0)$ and $(1,1)$.

For $0\le x\le1$, $x-x^2=x(1-x)\ge0$. Therefore the line is the upper boundary, and the required area is

$$
A=\int_0^1(x-x^2)\,dx
=\left[\frac{x^2}{2}-\frac{x^3}{3}\right]_0^1
=\frac12-\frac13=\frac16.
$$

**Result:** the bounded area is $1/6$ square units. The order of the functions is chosen from their signs on the bounded interval, rather than from their appearance in the question.

## Verification

The area under $y=x$ is $1/2$ and the area under $y=x^2$ is $1/3$ on this interval. Their difference is $1/6$. The integrand is nonnegative, as a geometric area requires.
