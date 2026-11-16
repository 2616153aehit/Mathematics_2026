# Exercise 2 — A Line in Space

[Exercise sheet](../../../exercises/2_Geometry/02_lines_and_planes_en.md)

## Problem

Given

$$
L:(x,y,z)=(2,-1,3)+t(1,2,-2).
$$

State a point on the line and its direction vector, check whether $P=(4,3,-1)$ lies on $L$, and find the point corresponding to $t=-1$.

## Method

Read the fixed point and direction from the parametric equation. Membership requires one common parameter in all three coordinates.

## Solution

A point on the line is $Q=(2,-1,3)$, and its direction vector is $v=(1,2,-2)$.

For $P=(4,3,-1)$, the first coordinate gives $2+t=4$, hence $t=2$. The remaining coordinates give

$$
-1+2(2)=3,\qquad 3-2(2)=-1.
$$

Therefore $P$ lies on $L$.

For $t=-1$, the point is

$$
(2,-1,3)-(1,2,-2)=(1,-3,5).
$$

## Verification

The displacement $P-Q=(2,4,-4)=2v$ confirms membership. The displacement from $Q$ to $(1,-3,5)$ is $-v$, confirming the parameter $-1$.
