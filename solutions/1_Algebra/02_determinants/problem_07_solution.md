# Exercise 7 — Using Properties Instead of Recomputing

[Exercise sheet](../../../exercises/1_Algebra/02_determinants_en.md)

## Problem

Suppose that for a $3\times3$ matrix, $\det A=-4$. Compute

$$
\det(2A),\qquad \det(A^T),\qquad \det(A^2),\qquad \det(-A).
$$

Justify each answer using the appropriate property.

## Method

Scaling an entire $n\times n$ matrix by $c$ scales its determinant by $c^n$. Also use transpose invariance and multiplicativity.

## Solution

Since the matrices have three rows, scaling contributes one factor per row.

| Expression | Property | Result |
| --- | --- | --- |
| $\det(2A)$ | $2^3\det A$ | $-32$ |
| $\det(A^T)$ | $\det A$ | $-4$ |
| $\det(A^2)$ | $(\det A)^2$ | $16$ |
| $\det(-A)$ | $(-1)^3\det A$ | $4$ |

The factor for $2A$ is $8$, rather than $2$, because all three rows are multiplied by $2$.

## Verification

For a concrete check, $A$ can be the diagonal matrix with diagonal $(-4,1,1)$. The diagonal products of the four resulting matrices are $-32,-4,16,4$, respectively.
