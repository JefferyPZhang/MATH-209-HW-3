# MATH 209 HW 3

Math 209 - Homework 4
Due date: Tuesday, November 21st
1. Find the solution1
to the Dirichlet problem
Bu
Bt
pt, xq “ B
2u
Bx
2
pt, xq,
upt, 0q “ upt, 1q “ 0
up0, xq “ fpxq
in the following two cases
(a) fpxq “ x ´
1
2
.
(b) fpxq “ 1 if x P p0, 1{2q, and fpxq “ 0 if x P p1{2, 1q.
2. This exercise is a step-by-step guide2
to solve the heat equation with
Neumann boundary conditions, which corresponds to the evolution of the
temperature of an object which is completely insulated. This is given by
Bu
Bt
pt, xq “ B
2u
Bx
2
pt, xq,
Bu
Bx
pt, 0q “ Bu
Bx
pt, 1q “ 0
up0, xq “ fpxq.
(a) Let λ be any real number. Show that if Tptq “ e
λt and
X2
pxq “ λXpxq, X1
p0q “ X1
p1q “ 0,
then upt, xq “ XpxqTptq is a solution to the heat equation with
matches the boundary conditions.
(b) Show that the only admissible values for λ are given by
λn “ ´n
2π
2
, n “ 0, 1, 2, . . .
and correspondingly Xnpxq “ cospnπxq, where thus X0pxq “ 1. This
implies that all solutions are given by
upt, xq “ ÿ8
n“0
cn cospnπxqe
´n
2π
2
t
.
1The solutions will be given by some series, as we have seen in class. Although you are not
required to do that, try plotting the first few terms in both cases for various instant of times,
and check if it agrees with your intuition on the equation
2Take a look at lecture 14 and imitate that before panicking!
1
(c) Use the formula above to show that
lim tÑ`8
upt, xq “ c0,
(d) Use the indentity ş1
0
cospnπxq “ 0 for all n ě 1 to deduce that
c0 “
ż 1
0
fpxqdx,
i.e., the limiting temperature after a long time is just the average
temperature at time 0.
3. Solve the inhomogeneous heat equation with Dirichlet boundary conditions
Bu
Bt
pt, xq “ B
2u
Bx
2
pt, xq gpt, xq,
upt, 0q “ upt, 1q “ 0
up0, xq “ fpxq
in the two following cases:
(a) fpxq “ sinp2πxq ´ sinpπxq, gpt, xq “ e
t
sinpπxq
(b) fpxq “ sinpπxq and gpt, xq “ sinpπxqt sinp2πxq.
