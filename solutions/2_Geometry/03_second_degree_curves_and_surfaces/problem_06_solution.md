# Exercise 6 — Shifted Ellipse

[Exercise sheet](../../../exercises/2_Geometry/03_second_degree_curves_and_surfaces_en.md)

## Problem

Reduce

$$
4x^2+9y^2-16x+18y-11=0
$$

to canonical form. Give the center and semiaxis lengths. Check that substituting the coordinates of the center into the left-hand side gives a value consistent with the form you obtained.

## Method

Factor the squared terms before completing the square, then divide by the positive constant on the right.

## Solution

Complete both squares:

$$
\begin{aligned}
4(x^2-4x)+9(y^2+2y)-11 &= 0, \\
4(x-2)^2+9(y+1)^2-36 &= 0.
\end{aligned}
$$

**Canonical form**

$$
\frac{(x-2)^2}{9}+\frac{(y+1)^2}{4}=1.
$$

The center is $(2,-1)$, the horizontal semiaxis is $3$, and the vertical semiaxis is $2$.

## Verification

At the center the original left-hand side is $16+9-32-18-11=-36$. This agrees with $4(x-2)^2+9(y+1)^2-36=-36$. The center is inside the ellipse, so it is not expected to satisfy the boundary equation.
