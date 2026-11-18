# Exercise 5 — Angle Between Vectors

[Exercise sheet](../../../exercises/2_Geometry/01_vectors_en.md)

## Problem

Given $u=(1,1,0)$ and $v=(1,0,1)$:

1. Use the sign of $u\cdot v$ to predict the type of angle.
2. Compute the angle.
3. Compare the result with the prediction.

## Method

Predict the angle type from the dot-product sign, then apply the cosine formula.

## Solution

Since

$$
u\cdot v=1>0,
$$

the angle should be acute. Both norms equal $\sqrt2$, so

$$
\cos\theta=\frac{u\cdot v}{\|u\|\|v\|}=\frac{1}{2}.
$$

Therefore $\theta=\arccos(1/2)=\pi/3=60^\circ$. This is acute, agreeing with the qualitative prediction.

## Verification

The exact cosine $1/2$ is positive and lies between zero and one. It gives $60^\circ$, consistent with the acute-angle prediction.
