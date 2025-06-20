# CSCI-5654-Assignment-3-Reading-Chapter-3-4.4-and-5-of-Vanderbei-s-book-solution

Download Here: [CSCI 5654 Assignment #3 (Reading: Chapter 3, 4.4 and 5 of Vanderbei’s book) solution](https://jarviscodinghub.com/assignment/assignment-3-reading-chapter-3-4-4-and-5-of-vanderbeis-book-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

P1. (15 points) Consider the following LP below:
max 2×1 +3×2 −x3 +x4
s.t. x1 −x2 +x3 ≤ −1
x1 +x3 +x4 ≤ 0
2×2 +x3 +3×4 ≤ 4
x1, x2, x3, x4 ≥ 0
(A) Write down the dual corresponding to the primal problem above? Add slack variables z1, z2, . . .
to the dual problem.
(B) Initialize the primal problem by changing the dual objective function appropriately. Pivot the
dual dictionaries and write down the initial primal dictionary that you would obtain in this process
( Pls. change the primal objective to −x1 − x2 − x3 − x4 just to make the grading uniform).
(C) Repeat parts (A) and (B) on the problem below:
max x1 −x2 +x3
s.t. x1 −2×2 ≤ 1
x1 +x2 −2×3 ≤ 1
−3×1 +6×3 ≤ −4
x1, x2, x3 ≥ 0
Interpret the result obtained from the Simplex over the dual. Once again, please use −x1−x2−x3
as the changed objective to initialize the problem.
P2 (15 points) (A) For the LP in problem P1 (A) set up the KKT conditions following the
complementary slackness theorem.
(B) Now solve the KKT conditions to find dual variables corresponding to the following primal
feasible solution?
x1 = 0, x2 = 2, x3 = 0, x4 = 0
Is this primal solution optimal?
Do not attempt to use an LP solver for this part. Instead substitute the primal solution into
the KKT constraints and solve for dual solutions that are dual feasible and complementary to the
primal solution above.
P3 (10 points) Consider a standard form LP wherein two different non-degenerate vertices x1, x2
are both optimal for the primal. Show using the complementary slackness theorem that any dual
optimal solution is degenerate.
1
(Hint: Each vertex saturates precisely n of the constraints. Now, since the solution 1
2
(x1 + x2)
is also optimal, consider how many constraints this solution saturates. Apply complementary
slackness to derive how many dual variables should be zero in any dual optimal solution).
P4 (15 points) (A) Consider a simple LP over a hyper-rectangle:
max c
tx s.t. ` ≤ x ≤ u
Here c represents the objective, and `, u represent vectors of upper and lower bounds on x.
Write down a linear time algorithm for solving the above LP. (Hint: The solution for each
variable xi can be one of two possibilities, what are they?)
(B) Using the result in (A) above, write down an algorithm to solve LPs of the form:
max c
ty
s.t. y = Ax
` ≤ x ≤ u
(Hint: Eliminate y and use the result in (A) ).
P5 (20 points) We will now prove a well-known and useful theorem of the alternative called
Motzkin transposition theorem using what we have learned so far.
Theorem [Motzkin 1936]: The following system of constraints (P) is infeasible
Ax ≤ b
x ≥ 0
if and only if the system of constraints (D) below is feasible
Aty ≥ 0,
b
ty < 0
y ≥ 0
(A) Prove that if (P) is feasible then (D) cannot be feasible. (Hint: If x, y are simultaneously
feasible for (P), (D) respectively then derive a contradiction by applying different sets of inequalities
from (P) and (D) to show that y
tAx will simultaneously be < 0 and ≥ 0.)
(B) Derive the dual for the auxilliary problem
max 0
tx −x0
s.t. Ax −1×0 ≤ b
x, x0 ≥ 0
Note that 1 is the column vector of all 1s. Recall that the auxilliary problem above always has
an optimal solution, and if (P) is infeasible, then the optimal value of this auxilliary problem is
strictly negative. Call it β
∗ < 0.
(C) Prove using (B) that if system (P) is infeasible then system (D) is feasible. (Hint: Use strong
duality to conclude that the dual problem derived in (B) has to have an optimal solution whose
value is β
∗
. Proceed from there to conclude a solution for system (D). )

