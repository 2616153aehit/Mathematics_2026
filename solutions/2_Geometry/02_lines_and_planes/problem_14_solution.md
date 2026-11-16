# Exercise 14 — Contrast: Intersection and Parallelism

[Exercise sheet](../../../exercises/2_Geometry/02_lines_and_planes_en.md)

## Problem

From the point $P=(0,0,1)$, two lines are drawn with direction vectors

$$
v_1=(2,1,-1),\qquad v_2=(2,1,0).
$$

For each line, analyze its position relative to the plane $z=0$.

For the line that intersects the plane, find the intersection point. For the other line, explain how you can recognize parallelism without solving an equation.

## Method

Use the vertical coordinate and the plane normal $n=(0,0,1)$ to distinguish intersection from parallelism.

## Solution

For the first direction,

$$
L_1:(x,y,z)=(2t,t,1-t).
$$

The equation $z=0$ gives $t=1$, hence the unique intersection point is $(2,1,0)$. Here $n\cdot v_1=-1\ne0$.

For the second direction,

$$
L_2:(x,y,z)=(2t,t,1).
$$

Every point has $z=1$. Since $n\cdot v_2=0$, the direction is parallel to the plane; the starting point is outside it. Thus $L_2$ is parallel with no common point.

## Verification

The first intersection is obtained by substitution at $t=1$ and has $z=0$. On the second line, the vertical coordinate is always $1$, so no choice of parameter reaches the plane.
