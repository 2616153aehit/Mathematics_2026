# Exercise 15 — Comparing Directions Using the Cosine of the Angle

[Exercise sheet](../../../exercises/2_Geometry/01_vectors_en.md)

## Problem

Given

$$
a=(1,2,1),\qquad b=(2,4,2),\qquad c=(2,0,3).
$$

For each pair, compute

$$
\frac{u\cdot v}{\|u\|\,\|v\|}.
$$

Order the pairs by increasing angle between the vectors. Explain why for $a$ and $b$ the value is $1$ even though the vectors have different lengths.

## Method

Normalize each dot product by both lengths; cosine decreases as the angle increases on $[0,\pi]$.

## Solution

For the first pair, $b=2a$, and

$$
\frac{a\cdot b}{\|a\|\|b\|}=\frac{12}{\sqrt6\sqrt{24}}=1.
$$

This value is one because multiplying by a positive scalar changes length but not direction, so the angle between $a$ and $b$ is zero.

For the pair $a,c$,

$$
\frac{a\cdot c}{\|a\|\|c\|}=\frac{5}{\sqrt6\sqrt{13}}=\frac5{\sqrt{78}}.
$$

For the remaining pair,

$$
\frac{b\cdot c}{\|b\|\|c\|}=\frac{10}{\sqrt{24}\sqrt{13}}=\frac5{\sqrt{78}}.
$$

Because cosine decreases as the angle increases on $[0,\pi]$, the increasing-angle order is

$$
\theta_{ab}=0<\theta_{ac}=\theta_{bc}=\arccos\left(\frac5{\sqrt{78}}\right).
$$

## Verification

Because $b=2a$ with a positive multiplier, the first angle is zero and the other two angles agree. Their common cosine $5/\sqrt{78}$ is strictly between zero and one, so both remaining angles are acute and larger than zero.
