# Travelling Salesman Problem: GA vs SA

This project compares two metaheuristic optimisation algorithms—Simulated Annealing (SA) and Genetic Algorithm (GA)—on a Travelling Salesman Problem (TSP) instance with 50 cities.

---

## Problem Description
Given a set of cities with (X, Y) coordinates, the goal is to find the shortest possible route that:

- Visits each city exactly once
- Returns to the starting city

This is a classic combinatorial optimisation problem.

---

## Dataset
- 50 cities with randomly generated coordinates
- Each city represented by:
  - X coordinate
  - Y coordinate

---

## Algorithms Implemented

### 1. Simulated Annealing (SA)
- Starts from a random route
- Iteratively applies small changes
- Accepts worse solutions with a probability that decreases over time
- Helps escape local minima

### 2. Genetic Algorithm (GA)
- Population-based optimisation
- Uses:
  - Selection
  - Crossover
  - Mutation
- Evolves routes over generations

---

## Experiments
The following experiments were conducted:

1. Baseline random route
2. Simulated Annealing optimisation
3. Genetic Algorithm optimisation
4. Convergence analysis for both algorithms
5. Performance comparison on subsets:
   - 10 cities
   - 20 cities
   - 30 cities
   - 40 cities
   - 50 cities

---

## Results (50 cities)

- Random baseline: ~2766
- Simulated Annealing: ~832.6
- Genetic Algorithm: ~831.8

The Genetic Algorithm achieved a slightly shorter final route, particularly for larger problem sizes.

---

## Skills Demonstrated
- Combinatorial optimisation
- Metaheuristic algorithms
- Algorithm comparison
- Convergence analysis
- Experimental evaluation

---

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
