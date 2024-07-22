# Quantum-ODE-Solver

This repository contains a notebook that solves any ordinary differential equation using quantum algorithms and ML. It uses the `qadence` library to create quantum circuits and perform multiple measurements quickly. The notebook utilizes the `hyperopt` library to efficiently search for optimal hyperparameters for a machine learning model.

## Table of Contents
- [Introduction](#introduction)
- [Usage](#usage)
- [References](#references)

## Introduction
In this project, we used Chebyshev feature maps to encode the values and calculated derivatives using the parameter shift rule, implemented with an automatic differentiation technique. We convert the ODE into an optimization problem, finding the best parameters and hyperparameters using ML models. We employ stochastic gradient descent to optimize parameters, and the `hyperopt` library for hyperparameter optimization of a quantum machine learning model. The optimization process leverages the TPE algorithm, effective in handling high-dimensional hyperparameter spaces.

## Usage

This tool can solve any ODE and can be extended to solve partial differential equations and multi-dimensional ODEs.

## References

1. Oleksandr Kyriienko, Annie E. Paine and Vincent E. Elfving (2021). Solving nonlinear differential equations with differentiable quantum circuits. [
https://doi.org/10.48550/arXiv.2011.10395](https://arxiv.org/pdf/2011.10395)


