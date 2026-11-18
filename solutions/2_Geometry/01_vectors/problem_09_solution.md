# Exercise 9 — Cross Product as a Perpendicular Direction

[Exercise sheet](../../../exercises/2_Geometry/01_vectors_en.md)

## Problem

For $u=(1,2,0)$ and $v=(0,1,3)$ compute $u\times v$. Use dot products to check perpendicularity to both vectors, compute $v\times u$, and compare the results.

## Method

Compute the cross product by its component formula, then check it with dot products.

## Solution

Expanding the determinant gives

$$
u\times v=(2\cdot3-0\cdot1,\;0\cdot0-1\cdot3,\;1\cdot1-2\cdot0)=(6,-3,1).
$$

The dot-product checks are

$$
(6,-3,1)\cdot(1,2,0)=6-6=0,
$$

$$
(6,-3,1)\cdot(0,1,3)=-3+3=0.
$$

Thus the cross product is perpendicular to both original vectors. Reversing the order gives

$$
v\times u=(-6,3,-1)=-(u\times v),
$$

so the perpendicular direction reverses orientation while keeping its magnitude.

## Verification

The computed vector $(6,-3,1)$ has zero dot product with both inputs. Reversing the arguments produces its negative, as required by cross-product antisymmetry.
