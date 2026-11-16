# Exercise 13 — Intersection of a Sphere and a Plane

[Exercise sheet](../../../exercises/2_Geometry/03_second_degree_curves_and_surfaces_en.md)

## Problem

Given the sphere

$$
x^2+y^2+z^2=25
$$

and the plane $z=3$, find the equation of the intersection curve and its radius. Then describe what happens for $z=c$ depending on $c$.

## Method

Fix the vertical coordinate in the sphere equation and recognize the remaining planar circle.

## Solution

At $z=3$,

$$
x^2+y^2+9=25,\qquad x^2+y^2=16.
$$

The intersection curve is the circle given by $x^2+y^2=16$ in the plane $z=3$. Its center is $(0,0,3)$ and its radius is $4$.

For a general height $z=c$, the section satisfies

$$
x^2+y^2=25-c^2.
$$

| Height | Intersection |
| --- | --- |
| $|c|<5$ | Circle with radius $\sqrt{25-c^2}$ |
| $|c|=5$ | One point: $(0,0,c)$ |
| $|c|>5$ | Empty |

## Verification

For example, $(4,0,3)$ satisfies the plane and the sphere because $16+9=25$. The right-hand side $25-c^2$ must be nonnegative, which gives exactly the stated cases.
