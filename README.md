# PINNs – PDE Experiments

This repository contains Physics-Informed Neural Network (PINN) implementations based on specific differential equations.

---

## 📁 `Poisson_1D_and_2D_Domain/`

- **`poisson_1D.ipynb`**  
  1D Poisson on (0,1):

  $$u_{xx}=e^{x}, \qquad u(0)=u(1)=0.$$

- **`Poisson_2D_Radial.ipynb`**  
  2D radial Poisson on the unit disk:

  $$u_{xx}+u_{yy}=x^{2}+y^{2}, {x^{2}+y^{2}}=0.$$

- **`Poisson_2D_Non_Radial.ipynb`**  
  2D non-radial Poisson:

  $$u_{xx}+u_{yy}=x+e^{x}-\sin y$$

---

## 📁 `PINNs_On_Manifolds/`

- **`pinn_unit_sphere_pde.ipynb`**  
  PDE on the unit sphere \(S^2\) using surface differential operators:
  $$(a\,\Delta_S - \mathbf{b}\cdot\nabla_S + c)\,u(x,y,z) = f(x,y,z), \qquad (x,y,z)\in S^2,$$
  where
  $$S^2=\{(x,y,z)\in\mathbb{R}^3: x^2+y^2+z^2=1\}.$$
