# Exercise 8 — Sphere

[Exercise sheet](../../../exercises/2_Geometry/03_second_degree_curves_and_surfaces_en.md)

## Problem

Reduce

$$
x^2+y^2+z^2-4x+2y-6z-2=0
$$

to canonical form. Find the center and radius. Give two points on the sphere and check them in the equation.

## Method

Complete three squares. The resulting sum of squared displacements identifies the center and radius.

## Solution

The square completions are

$$
x^2-4x=(x-2)^2-4,\quad y^2+2y=(y+1)^2-1,\quad z^2-6z=(z-3)^2-9.
$$

Thus the sphere has canonical form

$$
(x-2)^2+(y+1)^2+(z-3)^2=16.
$$

Its center is $(2,-1,3)$ and its radius is $4$. Moving four units in either horizontal direction gives $(6,-1,3)$ and $(-2,-1,3)$.

## Verification

Both points have squared distance $16$ from the center. In the original equation their values are

$$
36+1+9-24-2-18-2=0,\qquad 4+1+9+8-2-18-2=0.
$$
