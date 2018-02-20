# Activity Sheet 11

Manager
  ~ name:

Recorder
  ~ name:

Speaker
  ~ name:

### Section 6.1

1. Suppose we have two integer arrays $A$ and $B$ of size $n$ and $m$ respectively.
    a. Design a presorting-based algorithm to find out if the two sets have an integer in common.
    \vfill
    b. Compute the running time of the algorithm in terms of the problem size $n + m$ (or you can use as a measure of size the largest of the two).
    \vfill
    \newpage
2. We will now use the previous algorithm to solve the following problem: Given an array $A$ of distinct numbers and a target number $s$, determine if $s$ is the sum of two numbers from $A$. The idea for the solution is that if $x$ is one of the numbers. then $s-x$ is the other.
    a. Write an algorithm that solves the problem as follows: We first create an array $B$ that contains all the values $s-x$ for each value $x$ in $A$. We then use problem 1 to find a number that belongs to both $A$ and $B$. This number is the solution to our problem.
    \vfill
    b. Demonstrate the operation of this algorithm for the array with entries 23, 4, 16, 7, 12, 32, and target value $s=39$ as well as target value $s=8$ (You should notice an important detail regarding your algorithm for this second value).
    \vfill
    c. What is the running time for this algorithm? How does it compare to the brute-force approach of trying all possible pairs?
    \vfill
