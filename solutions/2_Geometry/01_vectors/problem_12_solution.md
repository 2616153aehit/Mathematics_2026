# Exercise 12 — A Normal Vector to a Plane

[Exercise sheet](../../../exercises/2_Geometry/01_vectors_en.md)

## Problem

Given $A=(1,0,2)$, $B=(2,1,0)$, and $C=(0,3,1)$. Construct two vectors lying in the plane, find a vector perpendicular to both, and check the perpendicularity using dot products.

## Method

Form two independent in-plane directions and take their cross product.

## Solution

Two vectors in the plane are

$$
\overrightarrow{AB}=(1,1,-2),\qquad \overrightarrow{AC}=(-1,3,-1).
$$

Their cross product is

$$
\overrightarrow{AB}\times\overrightarrow{AC}=(5,3,4).
$$

Thus $n=(5,3,4)$ is a normal vector to the plane through the three points.

The requested dot-product checks are

$$
n\cdot\overrightarrow{AB}=5+3-8=0,
$$

$$
n\cdot\overrightarrow{AC}=-5+9-4=0.
$$

Both in-plane directions are perpendicular to $n$, which verifies that $n$ is a normal vector.

## Verification

The normal $(5,3,4)$ is nonzero and its dot products with both in-plane vectors are zero. The plane equation $5x+3y+4z=13$ is also satisfied by all three points.
