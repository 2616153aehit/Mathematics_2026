# Exercise 3 — Plane Through a Point with a Given Normal Vector

[Exercise sheet](../../../exercises/2_Geometry/02_lines_and_planes_en.md)

## Problem

Find the equation of the plane through $P=(1,-2,3)$ and perpendicular to $n=(2,1,-1)$. Check the result by substituting the point $P$ and explain the role of the normal vector.

## Method

A plane with normal vector $n$ through $P$ satisfies $n\cdot((x,y,z)-P)=0$.

## Solution

Substituting the given point and normal gives

$$
2(x-1)+(y+2)-(z-3)=0.
$$

After collecting terms, the equation is

$$
2x+y-z+3=0.
$$

The coefficient vector $(2,1,-1)$ is the normal. Every displacement between two points of the plane has zero dot product with it, so the normal is perpendicular to all directions in the plane.

## Verification

At $P=(1,-2,3)$, the left-hand side is $2-2-3+3=0$. For example, the in-plane direction $(1,-2,0)$ has dot product $2-2=0$ with $n$.
