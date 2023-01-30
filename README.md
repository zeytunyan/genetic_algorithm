# genetic_algorithm

Implementation of a genetic algorithm in python to solve the knapsack problem.

Two versions of the algorithm have been written: manual implementation and implementation using the deap library.

Genetic operators:
1. Initial population: greedy selection, starting with a random load.
2. Selection: select only 20% of the fittest individuals.
3. Crossing: multipoint with 3 points.
4. Mutation: Adding 1 random thing to 10% of individuals.
5. New population: replacement of no more than 30% of the worst individuals with descendants.
