# Problem 8 — Number of Requests Handled by a Server

[Exercise sheet](../../../exercises/3_Calculus/05_applications_en.md)

## Problem

The rate at which requests arrive at a server during the first 5 minutes is described by the function

$$
r(t)=100+20t\quad [\mathrm{requests/min}],\qquad 0\le t\le5.
$$

1. Compute the total number of requests that arrived during this time.
2. Compute the average rate of incoming requests over this interval.
3. Compare the average rate with the values $r(0)$ and $r(5)$.

## Method

Integrate the arrival rate to obtain the number of arrivals, then divide by the duration for the mean rate.

## Solution

The total number arriving during the first five minutes is

$$
R=\int_0^5(100+20t)\,dt
=[100t+10t^2]_0^5=500+250=750.
$$

The integral has units of requests. The average rate is

$$
\overline r=\frac{750}{5}=150\,\mathrm{requests/min}.
$$

The endpoint rates are $r(0)=100$ and $r(5)=200$ requests per minute. The average $150$ lies halfway between them because the rate varies linearly. It is also attained at $t=2.5$ minutes.

## Verification

The trapezoid area is $5(100+200)/2=750$ requests. Multiplying the average rate $150$ by the duration $5$ recovers that total.
