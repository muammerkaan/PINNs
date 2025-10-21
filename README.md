# PINNs – PDE Experiments

This repository contains Physics-Informed Neural Network (PINN) implementations based on the specific differential equations.

## Notebook Overview

- **`pinn_poisson_experiments_clean.ipynb`**  
  1D Poisson equation on (0, 1):

  $$
  u_{xx} = e^{x}, \qquad u(0) = u(1) = 0
  $$

  Includes multiple model variants and best-model evaluation.

- **`pinn_disk_poisson_light.ipynb`**  
  2D radial Poisson equation on the unit disk:

  $$
  u_{xx} + u_{yy} = x^{2} + y^{2}, \qquad u\big|_{x^{2}+y^{2}=1} = 0
  $$

  Lightweight model version with training and evaluation.

- **`pinn_unitdisk_nonradial_light.ipynb`**  
  2D non-radial Poisson equation on the unit disk:

  $$
  u_{xx} + u_{yy} = x + e^{x} - \sin y, \qquad u\big|_{x^{2}+y^{2}=1} = 0
  $$

  Tuned architecture and optimizer for stable convergence under limited compute.
