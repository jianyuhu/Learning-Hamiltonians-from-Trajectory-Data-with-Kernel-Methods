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

The experiments are implemented in Python using Jupyter notebooks to evaluate reconstruction accuracy, convergence, bias correction, and robustness.

### 1. Hénon–Heiles System

**Notebook:** `Henon_Heiles.ipynb`

Experiments using the implicit midpoint and symplectic Euler methods cover:
- Time-step and sample-size convergence
- Inverse-modified Hamiltonian biases
- Second- and third-level Richardson extrapolation
- Robustness to observation noise
- Effects of trajectory length and data allocation

### 2. Additional Hamiltonian Systems

**Notebook:** `Other_Models.ipynb`

Three benchmark systems are considered:
- Double pendulum
- Frenkel–Kontorova model
- Highly non-convex potential

The experiments compare reconstructed Hamiltonians with the ground truth and visualize reconstruction errors.

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
