# Exercise 5 — Relative Position of Two Lines

[Exercise sheet](../../../exercises/2_Geometry/02_lines_and_planes_en.md)

## Problem

Analyze the position of

$$
L_1:(x,y,z)=(1,1,0)+t(1,2,1),
$$

$$
L_2:(x,y,z)=(2,0,1)+s(0,1,-1).
$$

If they intersect, give the intersection point. If not, determine whether they are parallel or skew. Justify the classification.

## Method

Check whether the directions are parallel, then equate the coordinates to test for an intersection.

## Solution

The direction vectors are $v_1=(1,2,1)$ and $v_2=(0,1,-1)$. They are not scalar multiples: the first coordinate of $v_2$ is zero, whereas that of $v_1$ is nonzero.

At an intersection, the coordinates must satisfy

$$
1+t=2,\qquad 1+2t=s,\qquad t=1-s.
$$

The first equation gives $t=1$, and the second then gives $s=3$. But the third would require $1=1-3=-2$, a contradiction.

**Result:** the lines are skew. They do not intersect and are not parallel.

## Verification

The direction cross product is $(-3,1,1)$. The displacement between the given base points is $(1,-1,1)$, whose dot product with this normal is $-3\ne0$. Thus the lines are not coplanar, confirming the skew classification.
