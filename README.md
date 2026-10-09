# Learning Hamiltonians from Trajectory Data with Kernel Methods

This repository contains the Python implementation and numerical
experiments accompanying the paper:

**Learning Hamiltonians from Trajectory Data with Kernel Methods**

## Overview

We investigate the reconstruction of Hamiltonian functions from
discrete trajectory observations using structure-preserving
kernel methods.

The proposed framework combines reproducing kernel Hilbert spaces
(RKHS) with symplectic numerical integrators to learn Hamiltonian
functions while preserving the underlying geometric structure.

## Numerical Experiments

The numerical experiments are implemented in Python using Jupyter
notebooks. They investigate the accuracy, convergence behavior,
bias correction, and robustness of the proposed kernel-based
Hamiltonian reconstruction framework.

### 1. Hénon–Heiles System

**Notebook:** `Henon_Heiles.ipynb`

This notebook provides a systematic numerical investigation of
Hamiltonian reconstruction using the implicit midpoint and
symplectic Euler methods.

The experiments include:

1. **Time-step dependence:** Reconstruction errors as functions
   of the observation time step, illustrating the different
   convergence orders of the two integrators.

2. **Sample-size dependence:** Reconstruction accuracy as the
   number of observed trajectories increases.

3. **Inverse-modified Hamiltonians:** Comparison of the learned
   Hamiltonian biases with the leading-order analytical
   corrections predicted by inverse modified equations.

4. **Richardson extrapolation:** Second- and third-level
   extrapolation experiments demonstrating the cancellation
   of leading integrator-induced biases.

5. **Robustness to observation noise:** Investigation of the
   effects of noisy trajectory observations on Hamiltonian
   reconstruction and Richardson bias correction.

6. **Trajectory length and data allocation:** Comparison of
   different combinations of trajectory number and length
   under a fixed observation budget.

### 2. Additional Hamiltonian Systems

**Notebook:** `Other_Models.ipynb`

This notebook investigates the applicability of the proposed
kernel reconstruction framework to Hamiltonian systems with
different dynamical and potential structures.

Three benchmark systems are considered:

1. **Double pendulum:** Hamiltonian reconstruction for a
   nonlinear coupled mechanical system.

2. **Frenkel–Kontorova model:** Reconstruction of a Hamiltonian
   incorporating nonlinear periodic interactions.

3. **Highly non-convex potential:** Evaluation of reconstruction
   accuracy for a Hamiltonian with a complex non-convex
   potential landscape.

For each system, the experiments compare the reconstructed
Hamiltonian with the ground truth and visualize the
corresponding reconstruction errors.

## Requirements

The experiments are implemented in Python.

Install the dependencies using:

```bash
pip install -r requirements.txt
```

## Usage

Clone this repository:

```bash
git clone https://github.com/jianyuhu/Learning-Hamiltonians-from-Trajectory-Data-with-Kernel-Methods.git
```

Navigate to the project directory and start Jupyter:

```bash
cd Learning-Hamiltonians-from-Trajectory-Data-with-Kernel-Methods
jupyter notebook
```

Open the corresponding notebook and execute the cells.

## Reference

If you use this code in your research, please cite:

**Learning Hamiltonians from Trajectory Data with Kernel Methods**

Publication information will be added upon availability.

## License

This project is licensed under the MIT License.
