# Exercise 13 — Do Four Points Lie in One Plane?

[Exercise sheet](../../../exercises/2_Geometry/01_vectors_en.md)

## Problem

Given

$$
A=(0,0,0),\qquad B=(1,2,0),\qquad C=(0,1,1),\qquad D=(2,5,1).
$$

1. Construct $\overrightarrow{AB}$ and $\overrightarrow{AC}$.
2. Find $n=\overrightarrow{AB}\times\overrightarrow{AC}$.
3. Construct $\overrightarrow{AD}$ and check whether $\overrightarrow{AD}\cdot n=0$.
4. Based on this, decide whether $D$ lies in the plane determined by $A,B,C$, and justify the criterion.

## Method

A displacement is in a plane exactly when it is perpendicular to a nonzero normal.

## Solution

The in-plane candidates are

$$
\overrightarrow{AB}=(1,2,0),\qquad \overrightarrow{AC}=(0,1,1).
$$

Their cross product is

$$
n=\overrightarrow{AB}\times\overrightarrow{AC}=(2,-1,1).
$$

Also $\overrightarrow{AD}=(2,5,1)$. The dot product is

$$
\overrightarrow{AD}\cdot n=2\cdot2+5(-1)+1\cdot1=4-5+1=0.
$$

Since this value is zero, $\overrightarrow{AD}$ is perpendicular to the normal, so $D$ lies in the plane through $A,B,C$. The criterion is that a displacement within the plane must have zero dot product with its normal.

## Verification

The normal $(2,-1,1)$ gives plane equation $2x-y+z=0$. All four points satisfy it; also $AD=2AB+AC$ directly confirms that the fourth point is in the same plane.
