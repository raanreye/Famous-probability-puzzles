# Famous-probability-puzzles
 
Janko Gravner's list of twenty interesting puzzels in probability:

https://www.math.ucdavis.edu/~gravner/MAT135A/resources/chpr.pdf

Here we will go through each one and create a python script to model them (hopefully building some intuition along the way).

1. [P. Winkler] One hundred people line up to board an airplane. Each has a boarding pass with
assigned seat. However, the first person to board has lost his boarding pass and takes a random
seat. After that, each person takes the assigned seat if it is unoccupied, and one of unoccupied
seats at random otherwise. What is the probability that the last person to board gets to sit in
his assigned seat?

Here we simulated the puzzle and ran it multiple times averaging the results. X axis is the number of times the simulation was ran and in the Y axis is the averaged of the result or varioance of each of those runs. Notice that it begins to converge on 0.5, as expected.

![Alt text](N1.png)
