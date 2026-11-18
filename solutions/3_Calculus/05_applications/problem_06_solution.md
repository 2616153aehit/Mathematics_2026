# Problem 6 — Average Value of a Function

[Exercise sheet](../../../exercises/3_Calculus/05_applications_en.md)

## Problem

Compute the average value of the function

$$
f(x)=x^2
$$

on the interval $[0,3]$.

Find a point $c\in[0,3]$ for which $f(c)$ is equal to this average value, and interpret the result geometrically.

## Method

The average height equals the integral divided by interval length; then solve for where the function attains that height.

## Solution

The interval has length $3$, so

$$
f_{\mathrm{avg}}=\frac1{3-0}\int_0^3x^2\,dx
=\frac13\left[\frac{x^3}{3}\right]_0^3
=3.
$$

Solve $c^2=3$ with $c\in[0,3]$. The allowed solution is **$c=\sqrt3$**; the negative root lies outside the interval.

Geometrically, a rectangle of width $3$ and height $3$ has the same area, $9$, as the region under $y=x^2$ on $[0,3]$. The point $(\sqrt3,3)$ is where the curve reaches that average height.

## Verification

The value $\sqrt3$ is in the prescribed interval, and $f(\sqrt3)=3$. The mean is also between the minimum and maximum function values, $0$ and $9$.
