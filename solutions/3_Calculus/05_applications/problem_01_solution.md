# Problem 1 — Motion — from Position to Velocity

[Exercise sheet](../../../exercises/3_Calculus/05_applications_en.md)

## Problem

The position of a point is described by

$$
s(t)=t^3-6t^2+9t+2,\qquad t\ge0.
$$

1. Determine the velocity and acceleration.
2. Find the times at which the point stops.
3. Determine on which intervals the point moves in the positive direction of the axis and on which intervals it moves in the negative direction.

## Method

Velocity is the time derivative of position, and acceleration is the time derivative of velocity. Direction is determined by the sign of velocity.

## Solution

Differentiation gives

$$
v(t)=s'(t)=3t^2-12t+9=3(t-1)(t-3),\qquad
a(t)=v'(t)=6t-12.
$$

The point stops when $v(t)=0$, at **$t=1$ and $t=3$**. On the permitted time domain,

| Time interval | $[0,1)$ | $(1,3)$ | $(3,\infty)$ |
| --- | --- | --- | --- |
| Sign of $v$ | $+$ | $-$ | $+$ |
| Motion | Positive direction | Negative direction | Positive direction |

At the two stopping times the instantaneous velocity is zero, so the point is momentarily moving in neither direction. The sign change shows that it reverses direction at both stops.

## Verification

The test times $0,2,4$ give velocities $9,-3,9$. The positions $s(0)=2$, $s(1)=6$, and $s(3)=2$ also agree with forward motion followed by backward motion.
