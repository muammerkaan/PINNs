# PINNs – PDE Experiments

This repository contains Physics-Informed Neural Network (PINN) implementations based on specific differential equations.

## Notebook Overview

- **`poisson_1D.ipynb`**  
  1D Poisson on (0,1):

  $$u_{xx}=e^{x}, \qquad u(0)=u(1)=0.$$

- **`Poisson_2D_Radial.ipynb`**  
  2D radial Poisson on the unit disk:

  $$u_{xx}+u_{yy}=x^{2}+y^{2}, {x^{2}+y^{2}}=0.$$

- **`Poisson_2D_Non_Radial.ipynb`**  
  2D non-radial Poisson on the unit disk:

  $$u_{xx}+u_{yy}=x+e^{x}-\sin y$$
