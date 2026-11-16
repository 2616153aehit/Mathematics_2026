# Exercise 15 — Complete Classification of a Line Relative to a Plane

[Exercise sheet](../../../exercises/2_Geometry/02_lines_and_planes_en.md)

## Problem

Let

$$
L:p+tv,\qquad \Pi:n\cdot x=d.
$$

State the conditions distinguishing the three cases: one intersection point, parallel with no common points, and the line contained in the plane. Then illustrate each case with your own simple numerical example.

## Method

Substitute the line into the plane equation and classify the resulting scalar equation in the parameter.

## Solution

Assume $v\ne0$ and $n\ne0$, so the formulas describe a line and a plane. Substitution gives

$$
n\cdot p+t(n\cdot v)=d.
$$

| Condition | Position |
| --- | --- |
| $n\cdot v\ne0$ | Exactly one intersection, at $t=(d-n\cdot p)/(n\cdot v)$ |
| $n\cdot v=0$ and $n\cdot p\ne d$ | Parallel with no common points |
| $n\cdot v=0$ and $n\cdot p=d$ | The entire line lies in the plane |

Use the plane $z=0$ to illustrate all three cases.

1. The line $(0,0,1)+t(0,0,-1)$ meets the plane once, at $t=1$, giving $(0,0,0)$.
2. The line $(0,0,1)+t(1,0,0)$ has constant height $1$, so it is parallel and disjoint.
3. The line $(0,0,0)+t(1,1,0)$ has constant height $0$, so it lies in the plane.

## Verification

For the examples, $n=(0,0,1)$ and $d=0$. The corresponding pairs $(n\cdot v,n\cdot p)$ are $(-1,1)$, $(0,1)$, and $(0,0)$, which satisfy the three distinct conditions in the table.
