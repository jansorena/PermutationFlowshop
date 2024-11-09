# Permutation Flowshop Problem Solver

A computational analysis of four MILP models (Wagner, Wilson, Manne, and Liao) for solving the Permutation Flowshop Problem using different solvers (PuLP, CPLEX, and Gurobi).

## Project Description
This project implements and compares four different Mixed Integer Linear Programming (MILP) models for the Permutation Flowshop Problem:
- Wagner model
- Wilson model
- Manne model
- Liao-You model

## Key Features
- Implementation of four different MILP formulations
- Performance comparison between models
- Integration with multiple solvers:
  - PuLP
  - CPLEX
  - Gurobi

## Results
- All models achieved the optimal solution of 105 time units
- Wagner and Wilson models demonstrated faster execution times compared to Manne and Liao-You models

## Requirements
- Python 3.x
- Jupyter Notebook
- PuLP
- CPLEX
- Gurobi

## Usage
1. Open `TareaComputacional3.ipynb` in Jupyter Notebook
2. Follow the cells sequentially to see the implementation and results of each model