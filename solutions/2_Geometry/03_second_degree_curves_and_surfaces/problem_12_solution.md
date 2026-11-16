# Exercise 12 — Recognizing a Surface from Cross-Sections

[Exercise sheet](../../../exercises/2_Geometry/03_second_degree_curves_and_surfaces_en.md)

## Problem

A certain surface has the following properties:
- the cross-section $z=0$ is a point,
- for $z>0$, the cross-sections $z=\mathrm{const}$ are circles with increasing radius,
- vertical cross-sections through the $Oz$ axis are parabolas.

Propose a simple equation for such a surface and justify your choice.

## Method

Choose a relation in which the squared horizontal distance equals height, then verify every stated cross-section.

## Solution

A suitable equation is

$$
z=x^2+y^2.
$$

At $z=0$, the equality $x^2+y^2=0$ forces $x=y=0$, giving one point. For $z=c>0$, the section is a circle of radius $\sqrt c$, increasing with $c$.

A vertical plane through the vertical axis can be parameterized by $x=s\cos\theta$, $y=s\sin\theta$. Its section satisfies

$$
z=s^2\cos^2\theta+s^2\sin^2\theta=s^2.
$$

Thus every such vertical section is a parabola. This verifies all three required properties.

## Verification

The radii at heights $1,4,9$ are $1,2,3$. The formula $z=s^2$ is independent of the plane angle, so the vertical-section property holds in every direction through the axis.
