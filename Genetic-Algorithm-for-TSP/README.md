# Genetic Algorithm for the Travelling Salesman Problem

An evolutionary optimization experiment exploring how genetic algorithms can search for short routes through a set of cities.

## Overview

The Travelling Salesman Problem (TSP) asks for a minimum-distance round trip that visits each city once and returns to its starting point. This project implements a genetic algorithm using a route-based population, crossover, mutation, and iterative selection.

## Approach

- Represent cities and pairwise distances, with routes expressed as closed sequences of cities.
- Generate candidate routes and calculate their total travel distances.
- Use crossover to combine parent routes and mutation to diversify candidate solutions.
- Carry promising candidates between generations and evolve a population of routes.
- Compare optimization behavior under changes in population size, mutation rate, and generation count.
- Evaluate both a four-city example and a larger synthetic ten-city problem through repeated runs.

## Experimental focus

The notebook examines convergence behavior, run-to-run variability, and sensitivity to genetic algorithm parameters. Since a genetic algorithm is heuristic, the best route discovered is not automatically proof of a global optimum, especially on larger instances.

**Tools:** Python, standard-library randomization and numerical analysis/visualization utilities.

## Notebook

[Jupyter Notebook](model_development.ipynb)
