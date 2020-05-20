# CS499 Homework 1

### Name:Zehao Wang      Student ID:518021910976

## Problem 1

The provement is right except the occasion where $n=2$.

## Problem2

Assume that $a_n $ notes the times of movement.

$a_0$=0.

To move the $n$ disks from peg A to peg B,first we must move  the $n-1$ disks to peg B.

Then we must move the $n$-th disk to the peg in the middle.

Then we must move the $n-1$ disks to peg A with the help of the middle peg.

Then we must move the $n$-th disk to peg B.

Then we move the $n-1$ pegs to peg B.

$\therefore$ we have $a_n=a_{n-1}+1+a{n-1}+1+1=3a_n+2$.

$\therefore$ $a_n=3^{n}-1$

## Problem 3

When $n=1$, there are $3^1=3$ arrangements and they are all possible.

Assumes that when $n=k$, there are $3^k$ arrangements.

Then when $n=k+1$,there are $3^k$(The $(k+1)$-th disk is on peg A )+$3^k$(The $(k+1)$-th disk is on the peg in the middle)+$3^k$(The $(k+1)$-th disk is on peg B)=$3^{k+1}$ arrangements.

$\therefore$ we will actually encounter every properly stacked arrangement of $n$ disks on three pegs.

## Problem 4

No.

If the biggest disk has been on peg B,$2^{n-1}-1$ moves are enouth.

If the biggest disk needs to be moved,$2^n-1$ moves are enough.

## Problem 5

No. A circle can have at most 2 points in common with another one.So the fourth circle can not divide every part into 2 new parts.

## Problem 6

It has been proved that $n$ lines can define at most $\frac{n^2+n+2}{2}$ areas.

2 adjacent half-lines with some segments can form an infinite area.

$n$ lines can form $2n$ half-lines.

So there are $2n$ infinite areas.

So there are at most  $\frac{n^2+n+2}{2}-2n=\frac{n^2-3n+2}{2}$ bounded areas. 

## Problem 7

From Equation (1.8), we can only derive that $J(2n+1)-J(2n)=2$(1),but not $J(2n)-J(2n-1)=2$(2).

To prove $J(n+1)-J(n)=2$,we must prove the equations above.However,we can not prove (2).

So the induction is wrong.

