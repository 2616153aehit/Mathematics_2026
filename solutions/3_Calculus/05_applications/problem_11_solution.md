# Problem 11 — Volume of a Solid of Revolution

[Exercise sheet](../../../exercises/3_Calculus/05_applications_en.md)

## Problem

The region under the graph

$$
y=\sqrt{x},\qquad x\in[0,4],
$$

is rotated about the $x$-axis.

1. Construct the integral describing the volume using the disk method.
2. Compute the volume.
3. Explain where the factor $\pi y^2$ in the integral comes from.

## Method

A slice perpendicular to the rotation axis is a disk with radius equal to the graph height.

## Solution

At position $x\in[0,4]$, the disk radius is $y=\sqrt x$. Its area is

$$
A(x)=\pi y^2=\pi(\sqrt x)^2=\pi x.
$$

A thin disk has volume approximately $A(x)\ dx$, so summing all slices gives

$$
V=\int_0^4\pi x\,dx
=\pi\left[\frac{x^2}{2}\right]_0^4
=8\pi.
$$

**Result:** the volume is $8\pi$ cubic units. The factor $\pi y^2$ is the area of a circular cross-section; it is not the height $y$ alone and not the circumference $2\pi y$.

## Verification

The disk area grows linearly from $0$ to $4\pi$ across a length of $4$. Its average is $2\pi$, so average cross-sectional area times length gives $2\pi\cdot4=8\pi$.
