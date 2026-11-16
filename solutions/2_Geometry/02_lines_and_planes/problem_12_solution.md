# Exercise 12 — Intersection Line of Two Planes

[Exercise sheet](../../../exercises/2_Geometry/02_lines_and_planes_en.md)

## Problem

Find a parametric equation of the line that is the intersection of

$$
x+y+z=3,\qquad x-y+z=1.
$$

Find its direction vector in two ways: from the system of equations and from the cross product of the normal vectors. Compare the results.

## Method

Solve the two plane equations together, then compare the resulting direction with the cross product of the normals.

## Solution

Subtracting the second equation from the first gives $2y=2$, so $y=1$. Both equations then reduce to $x+z=2$.

Set $z=t$. The intersection line is

$$
(x,y,z)=(2,1,0)+t(-1,0,1),\qquad t\in\mathbb R.
$$

The algebraic direction is $v=(-1,0,1)$. The two normals give

$$
(1,1,1)\times(1,-1,1)=(2,0,-2)=-2v.
$$

The vectors differ by a nonzero scalar and therefore describe the same line direction.

## Verification

Substituting $(2-t,1,t)$ gives $3$ in the first plane equation and $1$ in the second, for every real $t$. Both normals have zero dot product with $v$.
