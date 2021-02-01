# Adv_Diff_Supplemental_Materials

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Mikejmnez/Adv_Diff_Supplemental_Materials/main)

Supplemental materials for the JFM paper "Advection Diffusion Equation: An Exact Solution..."


## How to run remotely
Click on the Binder link above. It takes some time, while installing dependencies and getting the correct environment ready.

## How to run locally
### on OSX/Linux:
On the terminal, clone this repository

```git clone https://github.com/Mikejmnez/Adv_Diff_Supplemental_Materials.git```

Navigate into main directory and install environment

```conda env create -f environment.yml ```


Once the environment is install, activate it

```conda activate Advection_Diffusion```


Then navivate into `Advection_Diffusion` directory and run the interactive notebooks

```cd Advection_Diffusion```
``` jupyter lab```







Notebooks:
* `Mathieu_Eigenvalue.ipynb`: Compute and display Mathieu functions, their eigenvalues, Fourier expansions, and various identities.
* `Shear_Dispersion_Average_Gaussian.ipynb`: Compute the cross-channel average solution for a narrow Gaussian initial condition.
* `Adv_Diff_IVP_Animation_01.ipynb`: Full time-dependent solution for a cosine initial condition with wavenumber k. The wavenumber k can be modified by the used to better understand the behavior of solutions with different wavelengths. 
* `Adv_Diff_IVP_Animation_02.ipynb`: Full time-dependent solution for a Gaussian initial condition, plus the average solution.
* `Ellipse_Approx_Eigenvalues.ipynb`: Elliptical parametrization of the Mathieu eigenvalue dependence on parameter *q*.
