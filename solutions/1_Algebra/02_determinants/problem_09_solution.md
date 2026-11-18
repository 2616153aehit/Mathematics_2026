# Exercise 9 — Area and the Determinant

[Exercise sheet](../../../exercises/1_Algebra/02_determinants_en.md)

## Problem

The vectors

$$
u=
\begin{pmatrix}
3 \\
1 \\
\end{pmatrix},\qquad v=
\begin{pmatrix}
1 \\
4 \\
\end{pmatrix}
$$

span a parallelogram. Compute its area using a determinant. Then reverse the order of the vectors and explain what changes in the determinant and what does not change in the area.

## Method

Put the spanning vectors into the columns of a matrix; the parallelogram area is the absolute value of its determinant.

## Solution

$$
\det\begin{pmatrix}
3 & 1 \\
1 & 4 \\
\end{pmatrix}=3\cdot4-1\cdot1=11.
$$

**Result:** the area is $|11|=11$ square units. Swapping the columns reverses the signed orientation.

$$
\det\begin{pmatrix}
1 & 3 \\
4 & 1 \\
\end{pmatrix}=1-12=-11,\qquad |-11|=11.
$$

Thus the determinant changes sign, while the geometric area remains the same.

## Verification

Embed the vectors into three dimensions with third coordinate zero. Their cross product is $(0,0,11)$, whose length is also $11$.
