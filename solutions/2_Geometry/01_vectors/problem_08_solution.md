# Exercise 8 — Linear Combination and Checking the Result

[Exercise sheet](../../../exercises/2_Geometry/01_vectors_en.md)

## Problem

Check whether $w=(5,1)$ can be written as

$$
w=au+bv,
$$

where $u=(1,1)$ and $v=(2,-1)$. If so, find $a,b$, reconstruct $w$ from them, and explain the geometric meaning of the existence of such coefficients.

## Method

Equate coordinates to solve for the two coefficients of the linear combination.

## Solution

Equating coordinates in $au+bv=w$ gives

$$
a+2b=5,\qquad a-b=1.
$$

Subtracting the second equation from the first gives $3b=4$, hence $b=4/3$ and $a=1+b=7/3$. Reconstruction checks the answer:

$$
\frac73(1,1)+\frac43(2,-1)=\left(\frac{15}{3},\frac{3}{3}\right)=(5,1).
$$

Geometrically, the coefficients describe the directed amounts of the two nonparallel directions needed to reach $w$; since $u$ and $v$ span the plane, such coordinates exist uniquely.

## Verification

The reconstruction is shown explicitly. The two direction vectors have determinant $-3\ne0$, so the representation exists uniquely.
