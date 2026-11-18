# Problem 5 — Distance from Velocity

[Exercise sheet](../../../exercises/3_Calculus/05_applications_en.md)

## Problem

The velocity of a car during the first five seconds is described by the function

$$
v(t)=4t+2\quad [\mathrm{m/s}].
$$

Compute the distance traveled and explain why the integral of velocity gives the change in position.

Then answer what would have to be changed in the reasoning if the velocity also took negative values.

## Method

Integrate the rate of change of position, and check the velocity sign before equating displacement with distance.

## Solution

The velocity is positive throughout $[0,5]$: $v(t)=4t+2\ge2$. Thus the car does not reverse direction, and the traveled distance equals the displacement:

$$
d=\int_0^5(4t+2)\,dt
=\left[2t^2+2t\right]_0^5
=50+10=60\,\mathrm m.
$$

Velocity is $s'(t)$, so its integral is $s(5)-s(0)$ by the fundamental theorem of calculus. The units are $(\mathrm{m/s})\cdot\mathrm s=\mathrm m$.

If velocity took negative values, the same signed integral would still give displacement. Actual distance would instead be $\int_0^5|v(t)|\ dt$, splitting at velocity zeros when necessary. Negative-direction travel adds positive distance rather than canceling earlier travel.

## Verification

The area under the velocity graph is a trapezoid with heights $v(0)=2$ and $v(5)=22$ and width $5$. Its area is $(2+22)5/2=60$ metres.
