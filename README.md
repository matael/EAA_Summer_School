# EAA Summer School on Computational Acoustics

This repository contains the required files for the two tutorials on the finite-element methods.


## First tutorial

The first tutorials will be based on Jupyter notebooks in the directory `FEM_1D`.
The main Python modules required will be `numpy`, `scipy` and `matplotlib`.
This tutorial provides a step-by-step description of a basic implementation of a finite-element model for the 1D Helmholtz equation.
Further refinements to this model are then progressively added.


## Second tutorial

The second tutorial will use FreeFEM++ which is freely available for various platforms from the [project website](https://freefem.org).
This software package provides a wide range of finite-element methods to solve partial differential equations.
It will be used to solve for 2D sound fields in a cavity, as well as the coupling between an elastic structure (a tuning fork) and the sound field in the surrounding fluid.
A PDF file `tutorial_freefem.pdf` and the required input files for FreeFEM++ are provided in the directory `FEM_2D`.
