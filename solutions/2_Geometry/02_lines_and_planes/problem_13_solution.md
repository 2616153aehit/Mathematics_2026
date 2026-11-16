# Exercise 13 — Closest Point on a Plane

[Exercise sheet](../../../exercises/2_Geometry/02_lines_and_planes_en.md)

## Problem

Find the point on the plane $x+2y+2z=4$ closest to $P=(3,0,0)$. Give the distance and check that the segment joining the two points is perpendicular to the plane.

## Method

The shortest segment to a plane follows its normal. Solve for the normal displacement that reaches the plane.

## Solution

Let $n=(1,2,2)$. A point on the normal line through $P$ is

$$
Q=P+\lambda n=(3+\lambda,2\lambda,2\lambda).
$$

The plane condition becomes $3+9\lambda=4$, so $\lambda=1/9$.

**Closest point and distance**

$$
Q=\left(\frac{28}{9},\frac29,\frac29\right),\qquad
\|Q-P\|=\frac19\sqrt{1+4+4}=\frac13.
$$

Any other point of the plane differs from $Q$ by an in-plane vector perpendicular to $Q-P$. Pythagoras then gives a distance at least $\|Q-P\|$.

## Verification

The plane expression at $Q$ is $(28+4+4)/9=4$. Also $Q-P=n/9$, so the connecting segment is perpendicular to the plane. The distance formula independently gives $|3-4|/3=1/3$.
