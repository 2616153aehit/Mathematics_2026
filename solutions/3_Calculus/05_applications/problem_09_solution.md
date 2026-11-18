# Problem 9 — Minimizing the Material Used for a Can

[Exercise sheet](../../../exercises/3_Calculus/05_applications_en.md)

## Problem

A closed cylinder has fixed volume $V$.

1. Write the volume constraint.
2. Eliminate one of the variables.
3. Express the surface area as a function of the radius $r$.
4. Find the relation between the height $h$ and the radius $r$ for which the material usage is minimal.

Interpret the obtained relation geometrically.

## Method

Eliminate the height using the volume constraint, then minimize the total area of both end disks and the curved side.

## Solution

Let $V>0$ be fixed, with radius $r>0$ and height $h>0$. The volume constraint is

$$
\pi r^2h=V,\qquad h=\frac V{\pi r^2}.
$$

For a closed cylinder, the material area is

$$
S(r)=2\pi r^2+2\pi rh=2\pi r^2+\frac{2V}{r},\qquad r>0.
$$

The derivative equation gives

$$
S'(r)=4\pi r-\frac{2V}{r^2}=0
\quad\Longrightarrow\quad r^3=\frac V{2\pi}.
$$

At this radius,

$$
h=\frac V{\pi r^2}=2r.
$$

The second derivative $S''(r)=4\pi+4V/r^3$ is strictly positive for $r>0$. Also $S(r)\to\infty$ as $r\to0^+$ or $r\to\infty$. Thus the stationary point is the unique global minimum.

**Result:** the most economical closed cylinder has height equal to its diameter. Its radius is $(V/(2\pi))^{1/3}$.

## Verification

Substituting $h=2r$ into the volume gives $V=2\pi r^3$, exactly the critical-point condition. Omitting either end disk would change the model, so both are included in $S$.
