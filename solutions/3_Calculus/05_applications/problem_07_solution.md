# Problem 7 — Exponential Growth

[Exercise sheet](../../../exercises/3_Calculus/05_applications_en.md)

## Problem

Assume the model

$$
N(t)=N_0e^{kt},\qquad k>0.
$$

1. Verify by differentiation that the model satisfies the relation $N'(t)=kN(t)$.
2. Find the population doubling time.
3. Explain why the doubling time does not depend on $N_0$.

## Method

Differentiate the stated model and solve the doubling condition algebraically, rather than solving a new differential equation.

## Solution

For a population model take $N_0>0$. Differentiation gives

$$
N'(t)=N_0ke^{kt}=kN(t).
$$

Thus the growth rate is proportional to the current population. Let $T$ be the doubling time. The equation $N(T)=2N_0$ gives

$$
N_0e^{kT}=2N_0
\quad\Longrightarrow\quad e^{kT}=2
\quad\Longrightarrow\quad T=\frac{\ln2}{k}.
$$

The initial population cancels because doubling is a relative change. In fact $N(t+T)/N(t)=e^{kT}=2$ for every starting time, so the doubling interval is constant. The assumption $k>0$ makes $T$ positive. If $N_0=0$, the model stays zero and a positive-population doubling time is not meaningful.

## Verification

Substituting $T=\ln2/k$ gives $N(T)=N_0e^{\ln2}=2N_0$. If time is measured in a given unit, $k$ has the reciprocal unit, so $T$ has the correct time unit.
