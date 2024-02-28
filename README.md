# FEniCSx_Kamarei_Kumar_Lopez-Pamies
! This repository contains FEniCSx example codes for solving boundary value problems with the new fracture phase-field model described in [1]. The 'Single edge notch tension test', 'Cylindrical hole tension test', 'Poker-chip test', and 'Brazilian test' are the examples used. You can run these examples on Google Colab, which offers a user-friendly and comfortable interface for executing ipynb files with ease. With just a few clicks, users can enjoy the convenience of running their ipynb files seamlessly on Colab's platform. This phase-field model can describe fracture nucleation in all settings, including large and small pre-existing cracks, smooth and non-smooth boundary points, and within the bulk of structures subjected to arbitrary quasistatic loadings while preserving the standard phase-field formulation's ability to model crack propagation. The model incorporates an external configurational force into the evolution equation for the phase-field variable, as well as a new formulation for the parameter delta, which does not require calibration. This external force is determined by the material surface strength. In these codes, we define the strength surface as the Drucker-Prager surface parametrized by tensile and compressive strength. 

!********************************************************************** 

! Usage: ! ! This code takes as an input of 5 material properties listed below: ! 1. E = Young's modulus! 2. nu = Poisson's ratio ! 3. Gc = Critical energy release rate ! 4. sts = Tensile strength ! 5. scs = Compressive strength

! In addition, the user must specify the regularization length for these boundary value problems. Typically, should be chosen so that it is much smaller than the average size of the structure, as well as the material characteristic size of (3Gc)/(8 Wts).


!********************************************************************** 

For any inquiry, please contact me at kamarei2@illinois.edu

!********************************************************************** 

! References:

! [1] Kamarei, F., Kumar, A., Lopez-Pamies, O. 2024. The poker-chip experiments of synthetic elastomers. https://arxiv.org/pdf/2402.06785.pdf
