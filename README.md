# FEniCSx_Kamarei_Kumar_Lopez-Pamies
! This repository contains FEniCSx example codes for solving boundary value problems with the phase-field model of Griffith fracture with material strength put forth in [1]. The 'Single edge notch tension test', 'Cylindrical hole tension test', 'Poker-chip test', and 'Brazilian test' are the examples used. These examples serve to illustrate the capability of the model to describe the nucleation and propagation of fracture in nominally elastic brittle materials at large under arbitrary monotonic quasistatic boundary conditions. You can run these examples on Google Colab, which offers a user-friendly and comfortable interface for executing ipynb files with ease. With just a few clicks, users can enjoy the convenience of running their ipynb files seamlessly on the Colab's platform. The model provided in the code applies to any isotropic linear elastic material of choice with Young's modulus E and Poisson's ratio nu, Drucker-Prager strength surface parametrized with uniaxial tensile strength Sts and hydrostatic tensile strength Shs, and critical energy release rate Gc.

!********************************************************************** 

! Usage: ! ! This code takes as inputs the 5 material properties listed below: ! 1. E = Young's modulus! 2. nu = Poisson's ratio ! 3. Gc = Critical energy release rate ! 4. sts = Tensile strength ! 5. scs = Compressive strength

! In addition, the user must specify the regularization length for these boundary value problems. Typically, this length should be chosen so that it is smaller than the smallest size of the structure, as well as the material characteristic length scale (3Gc)/(16 Wts).


!********************************************************************** 

For any inquiry, please contact me at kamarei2@illinois.edu

!********************************************************************** 

! References:

! [1] Kamarei, F., Kumar, A., Lopez-Pamies, O. 2024. The poker-chip experiments of synthetic elastomers. https://arxiv.org/pdf/2402.06785.pdf
