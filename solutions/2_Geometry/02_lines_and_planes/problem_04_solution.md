# Exercise 4 — Plane Through Three Points

[Exercise sheet](../../../exercises/2_Geometry/02_lines_and_planes_en.md)

## Problem

Find the equation of the plane through

$$
A=(1,0,0),\quad B=(0,1,0),\quad C=(0,0,1).
$$

First construct two vectors lying in the plane, and then use the cross product. Check the resulting equation on all three points.

## Method

Take two differences of the given points and use their cross product as a normal vector.

## Solution

Two directions in the plane are

$$
u=B-A=(-1,1,0),\qquad v=C-A=(-1,0,1).
$$

Their cross product is

$$
u\times v=(1\cdot1-0\cdot0,\ 0(-1)-(-1)(1),\ (-1)(0)-1(-1))=(1,1,1).
$$

This nonzero normal also shows that the points are not collinear. The plane through $A$ is

$$
(x-1)+y+z=0,\qquad x+y+z=1.
$$

## Verification

Each of $A,B,C$ has coordinate sum $1$. Also $(1,1,1)\cdot(-1,1,0)=0$ and $(1,1,1)\cdot(-1,0,1)=0$.
