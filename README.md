# pig-dice-game

[Comparing Policies]

Throughout the paper, 
we measure the performance of policies against
the optimal policy of Neller and Presser [2004]. 
In this section, we describe the technique.

Let Roll A i,j,k and Roll B i,j,k 
be Boolean values indicating whether or not
player A and player B, 
respectively, 
will roll given a score of i, an opponent score of j, and a turn total of k. 

Then we can define the respective
probabilities of winning in these states, P A i,j,k and P B i,j,k, as follows:
