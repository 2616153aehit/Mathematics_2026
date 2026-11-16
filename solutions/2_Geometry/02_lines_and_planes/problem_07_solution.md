# Exercise 7 — A Line Relative to a Plane

[Exercise sheet](../../../exercises/2_Geometry/02_lines_and_planes_en.md)

## Problem

For

$$
L:(x,y,z)=(1,1,0)+t(1,-1,0),\qquad \Pi:x+y+z=2,
$$

determine whether the line intersects the plane at one point, is parallel to it, or lies in it. Explain the role of the dot product of the direction vector and the normal vector.

## Method

Compute the normal–direction dot product. If it is zero, test a point on the line to distinguish containment from parallelism without intersection.

## Solution

For the plane, $n=(1,1,1)$; for the line, $v=(1,-1,0)$.

$$
n\cdot v=1-1+0=0.
$$

Thus motion along the line does not change the value of $x+y+z$. Its base point $(1,1,0)$ satisfies the plane equation because $1+1+0=2$.

**Result:** the entire line lies in the plane, so there are infinitely many common points.

## Verification

For every real $t$, the line point is $(1+t,1-t,0)$ and its coordinate sum is $(1+t)+(1-t)+0=2$.
