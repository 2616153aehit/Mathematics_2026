# Exercise 9 — Ellipsoid and Its Cross-Sections

[Exercise sheet](../../../exercises/2_Geometry/03_second_degree_curves_and_surfaces_en.md)

## Problem

Consider

$$
\frac{x^2}{9}+\frac{y^2}{4}+\frac{z^2}{16}=1.
$$

Give the semiaxis lengths, describe the cross-section $z=0$, and explain how the cross-sections $z=c$ change for $|c|<4$.

## Method

Read the spatial semiaxes from the denominators and substitute the section height into the surface equation.

## Solution

The ellipsoid is centered at the origin, with semiaxes $3$ along $x$, $2$ along $y$, and $4$ along $z$.

At $z=0$, its cross-section is the ellipse

$$
\frac{x^2}{9}+\frac{y^2}{4}=1.
$$

At height $z=c$, set $q=1-c^2/16$. For $|c|<4$, $q>0$ and

$$
\frac{x^2}{9q}+\frac{y^2}{4q}=1.
$$

The section semiaxes are $3\sqrt q$ and $2\sqrt q$. They shrink as $|c|$ increases, while their ratio stays $3:2$. At $c=\pm4$ the section is a single point; for $|c|>4$ it is empty.

## Verification

The horizontal section intercept $(3\sqrt q,0,c)$ gives $q+c^2/16=1$. The vertical intercept $(0,2\sqrt q,c)$ gives the same value, confirming both semiaxes.
