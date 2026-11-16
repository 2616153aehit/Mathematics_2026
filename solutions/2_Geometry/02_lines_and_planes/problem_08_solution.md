# Exercise 8 — Intersection Point of a Line and a Plane

[Exercise sheet](../../../exercises/2_Geometry/02_lines_and_planes_en.md)

## Problem

Find the intersection point of

$$
(x,y,z)=(1,0,2)+t(1,2,-1)
$$

with the plane $x+y+z=4$. Check the result by substituting it into both descriptions.

## Method

Substitute the parametric coordinates into the plane equation and solve for the parameter.

## Solution

The coordinates of the line are $x=1+t$, $y=2t$, and $z=2-t$. Hence

$$
(1+t)+2t+(2-t)=4,\qquad 3+2t=4,\qquad t=\frac12.
$$

**Intersection point**

$$
Q=\left(\frac32,1,\frac32\right).
$$

The coefficient of $t$ is $2\ne0$, so the intersection parameter, and therefore the point, is unique.

## Verification

The point is obtained from the line at $t=1/2$, and its coordinate sum is $3/2+1+3/2=4$. Thus it satisfies both descriptions.
