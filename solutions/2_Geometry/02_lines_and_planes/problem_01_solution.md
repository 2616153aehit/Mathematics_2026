# Exercise 1 — Line Through Two Points

[Exercise sheet](../../../exercises/2_Geometry/02_lines_and_planes_en.md)

## Problem

Find the equation of the line through $A=(1,2)$ and $B=(4,-1)$ in parametric and general form. Identify a direction vector and an example of a normal vector. Check that both points satisfy the equation you obtain.

## Method

Use the difference of the two points as a direction vector. A normal vector is perpendicular to that direction.

## Solution

The displacement from $A$ to $B$ is $(3,-3)$. Dividing by $3$ gives the direction $v=(1,-1)$.

**Parametric form**

$$
(x,y)=(1,2)+t(1,-1),\qquad t\in\mathbb R.
$$

Choose $n=(1,1)$, since $n\cdot v=1-1=0$. The normal equation is

$$
(x-1)+(y-2)=0.
$$

**General form**

$$
x+y-3=0.
$$

## Verification

For $A$, $1+2-3=0$; for $B$, $4-1-3=0$. In the parametric equation, $t=0$ gives $A$ and $t=3$ gives $B$.
