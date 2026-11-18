# Problem 2 — Maximum Area of a Rectangle

[Exercise sheet](../../../exercises/3_Calculus/05_applications_en.md)

## Problem

A rectangle has perimeter $40$.

1. Write its area as a function of the length of one side.
2. Determine the domain of this function resulting from the geometry of the problem.
3. Find the dimensions that give the maximum area.
4. Justify that the point found actually gives a maximum.

## Method

Use the perimeter constraint to reduce area to a one-variable function, then maximize it on the geometric domain.

## Solution

Let the side lengths be $x$ and $y$. The perimeter condition gives $2x+2y=40$, hence $y=20-x$. The area model is

$$
A(x)=x(20-x)=20x-x^2,\qquad 0<x<20.
$$

The strict inequalities ensure that both side lengths are positive. Differentiation gives

$$
A'(x)=20-2x=0\quad\Longleftrightarrow\quad x=10.
$$

Then $y=10$. The second derivative is $A''(x)=-2<0$, and $A'$ changes from positive to negative, so this is the unique global maximum. Equivalently, $A(x)=100-(x-10)^2\le100$.

**Result:** a $10\times10$ square has maximum area $100$ square units.

## Verification

Its perimeter is $2(10+10)=40$. If one side differs from ten by $d$, the other differs by $-d$ and their product is $100-d^2$, confirming that every non-square choice has smaller area.
