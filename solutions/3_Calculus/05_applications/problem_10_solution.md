# Problem 10 — A Cable Through Water and Land

[Exercise sheet](../../../exercises/3_Calculus/05_applications_en.md)

## Problem

Point $A$ lies on one bank of a river of width $100$ m, and point $B$ lies on the other bank, $500$ m along the bank from the point directly opposite $A$.

The cost per meter of cable underwater is twice the cost per meter of cable on land.

Build a cost function depending on the point where the cable comes out of the water, determine the domain, and find the solution that minimizes the cost.

## Method

Use a bank coordinate for the exit point, apply the Pythagorean theorem to the underwater segment, and weight the two lengths by their different costs.

## Solution

Let $P$ be directly opposite $A$, and let $x$ metres be the distance from $P$ toward $B$ to the point where the cable leaves the water. Write the land cost per metre as $c>0$; the underwater cost is $2c$.

The underwater length is $\sqrt{100^2+x^2}$, and the land length is $500-x$. Therefore

$$
C(x)=c\left(2\sqrt{10000+x^2}+500-x\right),\qquad 0\le x\le500.
$$

An exit before $P$ makes both lengths longer than at $P$. An exit beyond $B$ makes both lengths longer than at $B$. Thus restricting the search to the segment $PB$ loses no optimum in this route model.

Differentiating gives

$$
C'(x)=c\left(\frac{2x}{\sqrt{10000+x^2}}-1\right).
$$

At a stationary point, $2x=\sqrt{10000+x^2}$. Both sides are nonnegative on the domain, so squaring gives $3x^2=10000$, hence

$$
x_* =\frac{100}{\sqrt3}\approx57.735\,\mathrm m.
$$

The second derivative is $20000c/(10000+x^2)^{3/2}>0$. The derivative is negative at zero and positive at $500$, so this is the unique global minimum on the allowed segment.

**Result:** the cable leaves the water about $57.735$ m from $P$ toward $B$. The underwater segment is $200/\sqrt3\approx115.470$ m, and the land segment is $500-100/\sqrt3\approx442.265$ m. The minimum cost is

$$
C(x_*)=c(500+100\sqrt3)\approx673.205c.
$$

## Verification

At the optimum, $2x_*/\sqrt{10000+x_*^2}=1$, so the derivative vanishes. The endpoint costs are $C(0)=700c$ and $C(500)=2c\sqrt{260000}\approx1019.804c$, both exceeding the interior minimum.
