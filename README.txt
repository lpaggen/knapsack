This is my solution to the classic knapsack problem.

I used a genetic algorithm to find a solution close to the optimum for every set of items with respective values and weights, subject to a total weight limit.

The parameters of the algorithm can be tuned to your liking. 

This algorithm uses:

-> A probability wheel to select the more "optimal" solutions every round

-> A crossover function to shift parts of the solutions with others

-> A mutation function to introduce some variability within our solutions

-> An elitism function to help the algorithm from regressing with every generation

