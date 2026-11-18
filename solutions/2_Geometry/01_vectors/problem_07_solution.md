# Exercise 7 — Linear Dependence Without Heavy Computation

[Exercise sheet](../../../exercises/2_Geometry/01_vectors_en.md)

## Problem

Given

$$
u=(1,2,3),\qquad v=(2,4,6),\qquad w=(0,1,1).
$$

Identify a specific relation between $u$ and $v$, decide whether the three vectors can be linearly independent, and explain why no long calculation is needed.

## Method

Look for a nontrivial relation before using a determinant or elimination.

## Solution

Coordinate comparison immediately shows

$$
v=2u,
$$

or equivalently $2u-v+0w=0$. This is a nontrivial linear relation, so the set $\{u,v,w\}$ is linearly dependent regardless of $w$.

No determinant or row reduction is needed: two proportional vectors already supply a dependence relation for the whole set.

## Verification

The coefficients $(2,-1,0)$ are not all zero but yield $2u-v+0w=0$. That is the defining test for dependence.
