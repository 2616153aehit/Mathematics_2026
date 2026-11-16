# Exercise 11 — Plane Containing a Line and a Point

[Exercise sheet](../../../exercises/2_Geometry/02_lines_and_planes_en.md)

## Problem

Find the equation of the plane containing

$$
(x,y,z)=(1,0,2)+t(1,1,-1)
$$

and the point $P=(0,2,1)$. Check that both the entire line and the point lie in the plane you obtain.

## Method

Combine the line direction with a vector from a point on the line to the additional point. Their cross product gives a plane normal.

## Solution

Take $A=(1,0,2)$ on the line. The two in-plane directions are

$$
v=(1,1,-1),\qquad P-A=(-1,2,-1).
$$

Their cross product is

$$
v\times(P-A)=(1,2,3).
$$

It is nonzero, so the two directions determine one plane. Through $A$, its equation is

$$
(x-1)+2y+3(z-2)=0,\qquad x+2y+3z=7.
$$

## Verification

The point $P=(0,2,1)$ gives $0+4+3=7$. Every point $(1+t,t,2-t)$ of the line gives $1+t+2t+6-3t=7$, so the entire line is included.
