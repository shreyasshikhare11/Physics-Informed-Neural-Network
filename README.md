# Physics-Informed Neural Network

A compact, notebook-based collection of Physics-Informed Neural Network (PINN) examples for solving partial differential equations (PDEs) using PyTorch. The goal of this repository is to provide a practical introduction to PINNs, along with several representative benchmark problems from the literature.

## Overview

Physics-informed neural networks combine deep learning with known physical laws expressed as PDEs. Instead of learning only from data, the network is trained to satisfy both:

- observed or synthetic data constraints
- governing PDE residuals derived from the physics

This repository demonstrates how to embed the physics directly into the loss function so the model approximates the solution while respecting the underlying equations.

## Included notebooks

- [Physics_Informed_Neural_Network.ipynb](https://github.com/shreyasshikhare11/Physics-Informed-Neural-Network/blob/main/Physics_Informed_Neural_Network.ipynb)  
  A full notebook containing several PINN examples and training workflows.

- [pinn_template.ipynb](https://github.com/shreyasshikhare11/Physics-Informed-Neural-Network/blob/main/pinn_template.ipynb)  
  A simple starter notebook for building your own PINN experiment.

## PDE examples covered

The notebook includes examples for:

- Burgers equation
- Nonlinear Schrödinger equation
- Navier–Stokes equations
- Korteweg–de Vries (KdV) equation
- 1D wave equation

These examples illustrate how PINNs can model time-dependent PDEs with initial conditions, boundary conditions, and residual-based training.

## Why this repository is useful

This project is a good starting point for:

- learning the basics of PINNs
- experimenting with PDE-constrained neural networks
- exploring custom equations and loss formulations
- using notebook-based examples for research, teaching, or prototyping

## Open in Colab

- [Open Physics_Informed_Neural_Network.ipynb in Colab](https://colab.research.google.com/github/shreyasshikhare11/Physics-Informed-Neural-Network/blob/main/Physics_Informed_Neural_Network.ipynb)
- [Open pinn_template.ipynb in Colab](https://colab.research.google.com/github/shreyasshikhare11/Physics-Informed-Neural-Network/blob/main/pinn_template.ipynb)

## Quick start

1. Clone the repository.
2. Install the required libraries such as PyTorch, NumPy, SciPy, and Matplotlib.
3. Open the notebook in Jupyter or JupyterLab.
4. Run the cells to train the PINN models and visualize the results.

## Repository links

- GitHub repository: [Physics-Informed-Neural-Network](https://github.com/shreyasshikhare11/Physics-Informed-Neural-Network)
- Main notebook: [Physics_Informed_Neural_Network.ipynb](https://github.com/shreyasshikhare11/Physics-Informed-Neural-Network/blob/main/Physics_Informed_Neural_Network.ipynb)
- Starter template: [pinn_template.ipynb](https://github.com/shreyasshikhare11/Physics-Informed-Neural-Network/blob/main/pinn_template.ipynb)

## License

This repository is intended for educational and research-oriented use. Please check the repository for the license details before reuse or redistribution.
