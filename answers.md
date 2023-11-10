# CMPS 2200 Assignment 4
## Answers

**Name:**_Simon Yung__


Place all written answers from `assignment-04.md` here for easier grading.

1a. To get the fewest coins as possible the greediest algorithim will take the largest denomination that fits and work down from that point.

1b. becuase every coin is twice as big as the one that comes before it, take more than one of a smaller denomination is inherently less effiecent ie. if you have 9 usd it is less greedy to take two 4s and a one then one 8 and a one. 

1c.  the work and span are the same becuase this algorithim is sequential. the work and span are $O(logn)$

2a.One counter example is having coins sized 9,4, and 1 and having a usd of one. Where previously 9+1+1+1 = 4 coins, taking 3 coins of 4 is less coins and therefore a counter example.

2b. becuase of the optimal substructure we can set up our equation.

$Coin(X) = Min(Coin((i-k_n) + 1))$

2c. The work and span of this algorithim $O(n*k)$ and $O(n + k)$


