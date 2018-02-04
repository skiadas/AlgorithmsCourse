# Activity Sheet 7

Manager
  ~ name:

Recorder
  ~ name:

Speaker
  ~ name:

### Section 4.4

1. Exercise 4.4.10 modified: You have $n$ identical-looking coins, and one coin is fake (lighter). You may use a balance scale, on which you can place coins on both sides and see if it tilts one way or another, or if it balances. The goal is to determine which coin is fake in an efficient way in terms of number of uses of the scale. The idea of a divide-into-three algorithm for this problem is as follows: you would divide your coins in three groups, two of them having the same number of coins, then you would weigh those two against each other on the scale. Each of the three possible outcomes allows you to then focus on just one of the groups for your next step.
    a. Describe (in pictures or some other way) how this process would work if you started with 8 coins. You should be able to do it with just two uses of the scale.
    \vfill
    b. Write pseudocode for this algorithm for more general $n$. Make sure your algorithm works even if $n$ is not a multiple of $3$.
    \vfill
    \newpage
    c. Set up a recurrence relation for the number of times your algorithm uses the scale for an input of $n$ coins. Then solve the relation in the case where $n=3^k$.
    \vfill
    d. If we are only allowed to use the scale $8$ times, what is the largest number of coins that we could start with and still be guaranteed to find the fake coin within $8$ uses of the scale.
    \vfill
