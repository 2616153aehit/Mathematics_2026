# Exercise 10 — Triangle Area from Vectors

[Exercise sheet](../../../exercises/2_Geometry/01_vectors_en.md)

## Problem

The points $A=(0,0,0)$, $B=(2,1,0)$, and $C=(1,3,2)$ form a triangle. Construct $\overrightarrow{AB}$ and $\overrightarrow{AC}$, compute the area of the parallelogram using the cross product, and then find the area of the triangle. Explain the factor $\frac12$.

## Method

The cross-product norm gives the parallelogram area; a triangle has half that area.

## Solution

The two sides from $A$ are

$$
\overrightarrow{AB}=(2,1,0),\qquad \overrightarrow{AC}=(1,3,2).
$$

Their cross product is

$$
\overrightarrow{AB}\times\overrightarrow{AC}=(2,-4,5),
$$

whose length is $\sqrt{4+16+25}=\sqrt{45}=3\sqrt5$. Therefore the parallelogram area is $3\sqrt5$ and the triangle area is

$$
\frac12\,3\sqrt5=\frac{3\sqrt5}{2}.
$$

The diagonal of a parallelogram made from the two side vectors divides it into two congruent triangles, which explains the factor $1/2$.

## Verification

The cross-product squared norm is $45$. Independently, $\|AB\|^2\|AC\|^2-(AB\cdot AC)^2=5\cdot14-5^2=45$. This checks the parallelogram area and hence half of it for the triangle.
