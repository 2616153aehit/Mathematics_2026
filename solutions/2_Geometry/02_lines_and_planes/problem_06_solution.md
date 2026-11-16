# Exercise 6 — Angle Between Planes

[Exercise sheet](../../../exercises/2_Geometry/02_lines_and_planes_en.md)

## Problem

Given

$$
\Pi_1:x+y+z=1,\qquad \Pi_2:x-y=2.
$$

First use the normal vectors to decide whether the planes are parallel. If not, compute the angle between them and explain why the normal vectors alone are enough for this calculation.

## Method

The smaller angle between two planes equals the smaller angle between their normal directions.

## Solution

The normals are

$$
n_1=(1,1,1),\qquad n_2=(1,-1,0).
$$

They are not scalar multiples, so the planes are not parallel. Their dot product is $1-1+0=0$.

$$
\cos\theta=\frac{|n_1\cdot n_2|}{\|n_1\|\|n_2\|}
=\frac{0}{\sqrt3\sqrt2}=0.
$$

**Result:** $\theta=\pi/2=90^\circ$. The planes are perpendicular. The constants in the plane equations determine position, while the normal vectors determine orientation and therefore the angle.

## Verification

Both normals are nonzero and orthogonal. This verifies that the zero cosine represents a right angle rather than an undefined expression.
