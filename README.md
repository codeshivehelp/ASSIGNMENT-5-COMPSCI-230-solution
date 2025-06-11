# ASSIGNMENT-5-COMPSCI-230-solution

Download Here: [ASSIGNMENT 5 COMPSCI 230 solution](https://jarviscodinghub.com/assignment/assignment-5-compsci-230-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Problem 1 (12+1 points)
Prove the following statement using induction:
The sum of the first n positive odd integers is equal to n
2
, i.e.,
∀n ∈ Z
+. 1 + 3 + · · · + (2n − 1) = n
2
.
Problem 2 (12+1 points)
Recall that Fn is the n
th number of the Fibonacci sequence, defined as follows:
F0 = 0
F1 = 1
Fn = Fn−1 + Fn−2 if n ≥ 2.
Prove that every positive integer can be written as the sum of distinct non-consecutive Fibonacci
numbers, i.e.,
∀n ∈ Z
+. ∃i1, . . . , it ∈ Z
+, such that ik+1 > ik + 1 for k = 1, . . . ,(t − 1) and
n =
X
t
k=1
Fik
.
For example, 7 = 2 + 5 = F3 + F5.
Problem 3 (12+1 points)
Suppose we have a cake. The cake is a rectangular prism with integral dimensions, i.e. i, j, k ∈ Z
+
and the cake has dimensions i × j × k. We want to cut the cake into pieces such that each piece is
a single unit cube (dimensions 1 × 1 × 1). We are only allowed to make one cut at a time, and each
cut must result in a smaller rectangular prism (e.g. each cut is a straight cut along one dimension).
Only integral dimensions are allowed.
For example, suppose our cake has dimensions 2 × 3 × 1. We can cut the cake into 6 unit cubes
using 5 cuts, see Figure 1.
For a cake with dimensions i × j × k, we want to make a sequence of cuts so that we divide the
cake into n unit cube pieces where n = i · j · k. Prove that no matter which sequence of cuts you
make, the minimum number of cuts needed is n − 1.
3
2
1
Cake with dimensions 2 × 3 × 1 First Cut Cut 2 and 3 Cut 4 and 5
Fgure 1: Cutting a cake into unit cubes.
