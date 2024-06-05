Genetic Algorithm and Particle Swarm Optimization using scikit-opt
===

This project involves the analysis and comparison of Genetic Algorithm (GA) and Particle Swarm Optimization (PSO) for minimizing mathematical functions and solving the Traveling Salesman Problem (TSP) using the scikit-opt library. Both GA and PSO are popular metaheuristic algorithms used for optimization problems.

## Dataset Description
For function minimization, we use a set of standard benchmark functions, such as:

- Schaffer Function
- Rosenbrock Function

For the TSP, we use a set of predefined cities with coordinates to define the distances between them.

## Methodologies
## Genetic Algorithm (GA)
GA is an evolutionary algorithm that simulates the process of natural selection. It operates through:

- Initialization: Randomly generating an initial population of solutions.
- Selection: Selecting the fittest individuals for reproduction.
- Crossover: Combining pairs of individuals to produce offspring.
- Mutation: Introducing random changes to individuals to maintain genetic diversity.
- Iteration: Repeating the selection, crossover, and mutation processes over several generations to evolve better solutions.

### Particle Swarm Optimization (PSO)
PSO is a population-based optimization technique inspired by the social behavior of birds. It involves:

- Initialization: Generating a swarm of particles with random positions and velocities.
- Update: Updating the velocities and positions of particles based on their own best-known positions and the best-known positions of their neighbors.
- Iteration: Iteratively adjusting particle positions to explore the search space and converge towards optimal solutions.

### Function Minimization
The function minimization involves:

- Defining benchmark functions: Implementing standard functions to be minimized.
- Applying GA and PSO: Using scikit-opt to optimize the benchmark functions.
- Evaluating performance: Comparing the algorithms based on solution accuracy and convergence speed.

### Traveling Salesman Problem (TSP)
The TSP solution involves:

- Defining the TSP instance: Using a predefined set of cities with known distances.
- Applying GA and PSO: Using scikit-opt to find the shortest possible route that visits each city exactly once and returns to the starting point.
- Evaluating performance: Comparing the algorithms based on the quality of the routes and computational efficiency.

## Evaluation
The evaluation process includes:

- Performance metrics: Evaluating the algorithms using metrics such as best solution found, average solution quality, and computational time.
- Visualizations: Plotting convergence curves and solution paths for TSP to visualize the performance of the algorithms.

## Dependencies
The main libraries used in this project include:

- [Scikit-opt](https://github.com/guofei9987/scikit-opt)
- PyTorch
- Scipy
- NumPy
- Matplotlib
- Optuna