# Exercise 10 — Projection of a Point onto a Plane

[Exercise sheet](../../../exercises/2_Geometry/02_lines_and_planes_en.md)

## Problem

Find the orthogonal projection of $P=(2,1,3)$ onto the plane $x+y+z=3$, and then find the reflection of $P$ across this plane. Check that the midpoint of the segment joining the point and its reflection lies on the plane.

## Method

Subtract the normal component from the point to obtain the projection. Reflect by taking the same normal displacement a second time.

## Solution

Here $n=(1,1,1)$, $n\cdot P=6$, and $\|n\|^2=3$. The normal correction is

$$
\frac{n\cdot P-3}{\|n\|^2}n=\frac{6-3}{3}(1,1,1)=(1,1,1).
$$

The orthogonal projection and reflected point are therefore

$$
Q=P-(1,1,1)=(1,0,2),
$$

$$
R=2Q-P=(0,-1,1).
$$

**Result:** the projection is $(1,0,2)$ and the reflection is $(0,-1,1)$.

## Verification

The projected point has coordinate sum $3$. The midpoint $(P+R)/2=(1,0,2)=Q$ lies on the plane. Moreover, $P-Q=(1,1,1)$ is parallel to the normal, and $R-Q=-(P-Q)$.
