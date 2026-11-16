# Exercise 9 — Distances

[Exercise sheet](../../../exercises/2_Geometry/02_lines_and_planes_en.md)

## Problem

Compute:

1. the distance from $P=(2,3)$ to the line $3x+4y-10=0$,
2. the distance from $Q=(2,-1,3)$ to the plane $2x-2y+z-4=0$.

Compare the two formulas and explain their common connection with the normal direction.

## Method

Use the absolute normal-equation residual divided by the length of the normal vector.

## Solution

For a line $ax+by+c=0$, the distance from $(x_0,y_0)$ is the absolute residual divided by $\sqrt{a^2+b^2}$.

$$
d(P,L)=\frac{|3(2)+4(3)-10|}{\sqrt{3^2+4^2}}=\frac85.
$$

The plane formula has the same structure, with a third coordinate:

$$
d(Q,\Pi)=\frac{|2(2)-2(-1)+3-4|}{\sqrt{2^2+(-2)^2+1^2}}=\frac53.
$$

Both formulas measure displacement in the unit normal direction. The absolute value makes distance nonnegative; division by the normal length removes the arbitrary scale of the equation.

## Verification

The normal foot from $P$ is $(26/25,43/25)$; it satisfies $3x+4y=10$, and the connecting vector has length $8/5$. The plane foot is $(8/9,1/9,22/9)$; it satisfies $2x-2y+z=4$, and its displacement from $Q$ has length $5/3$.
