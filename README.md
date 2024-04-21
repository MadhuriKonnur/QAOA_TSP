# QAOA_TSP
QAOA can handle the complex interplay of various factors affecting delivery routes.
## Overview

This is a capstone project for The Coding School QXQ YLC 2024. Presenting Infogrphic/Poster illustrating Quantum Approximate Optimization Algorithm (QAOA) and Travel Salesman Problem (TSP): A Powerful Duo for Delivery Route Optimization.

## Nearest Neighbor Heuristic algorithm to solve the Traveling Salesman Problem (TSP) for a set of cities

The classical approach to solving the TSP is available in `nearest_neibhgour_TSP.ipynb`.

## Quantum Approach -program to solve the Traveling Salesman Problem (TSP) using simulated annealing

In `qaoa_simulate.ipynb`, simulate_qaoa(distance_matrix) (commented out): This function is meant to be replaced with an actual implementation of the Quantum Approximate Optimization Algorithm (QAOA) to find the optimal permutation. The current code includes a placeholder where QAOA would return a hypothetical optimal route. simulated_annealing(distance_matrix): This function implements the simulated annealing algorithm to find a near-optimal solution for the TSP.

Planning  to extend simulation QAOA approach by using libraries like Qiskit, Cirq, Pennylane etc.
`quantum_qaoa.ipynb`


### Practical Considerations
- **Scalability and Quantum Advantage**: Discussion on the scalability of the QAOA approach and the conditions under which it may offer a quantum advantage.
- **Limitations and Challenges**: Insights into the limitations of current quantum technology in solving large-scale instances of the TSP and potential future directions.
