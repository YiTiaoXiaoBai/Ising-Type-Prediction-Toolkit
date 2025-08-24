# Ising-Type-Prediction-Toolkit
Monte Carlo simulation toolkit for 2D Ising models, extending from NN and NNN couplings to RKKY long-range interactions. Includes Metropolis and annealing implementations for tracking phase transitions and thermodynamic observables.


1. Introduction

This repository contains my independent implementations of 2D Ising-type models as part of the Ising-Type Prediction Toolkit project.
The focus is on extending classical Ising models from nearest-neighbor (NN) coupling to next-nearest-neighbor (NNN) and long-range RKKY interactions, using Monte Carlo simulations.

My contributions include both algorithmic development and physical analysis of phase transitions.


2. Implemented Models

2D NN Ising Model
Standard nearest-neighbor interaction on a square lattice.

2D NNN Ising Model
Extension with next-nearest-neighbor couplings.

2D RKKY Ising Model
Long-range oscillatory coupling:
J_ij = A*sin(2kF*Rij)/(2kF*Rij)^2


3. Algorithms

Metropolis Monte Carlo (fixed temperature)

Implemented for NN, NNN, and RKKY Ising models.

Annealing Monte Carlo (temperature schedules)

Tracks energy, magnetization, heat capacity, and susceptibility.

Identifies phase transitions and critical behavior.


4. Methodology & Observables

Measured Quantities

Energy E(T)

Magnetization M(T)

Susceptibility χ(T)

Heat capacity C(T)

Analysis Goals

Phase transition detection

Critical exponent estimation (preliminary)

Comparison of NN vs RKKY dynamics


5. Results (Examples)

(Insert plots when available)

Energy vs Temperature

Heat Capacity peaks near T——c
	​
Magnetization curves for NN vs RKKY
