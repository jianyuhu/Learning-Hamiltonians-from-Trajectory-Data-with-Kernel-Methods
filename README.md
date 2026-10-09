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

The numerical experiments are implemented in Jupyter notebooks.

### 1. Hénon–Heiles System

**Notebook:** `Henon_Heiles.ipynb`

Numerical experiments on the Hénon–Heiles Hamiltonian system.

### 2. Additional Hamiltonian Systems

**Notebook:** `Other_Models.ipynb`

Numerical experiments involving additional Hamiltonian models.

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
