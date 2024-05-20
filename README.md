# FEniCSx_Kamarei_Kumar_Lopez-Pamies
! This repository contains FEniCSx example codes for solving boundary value problems with the phase-field model of Griffith fracture with material strength put forth in [1]. The 'Cylindrical hole tension test' [2], 'Single edge notch tension test' [3], 'Surfing test' [3], 'Brazilian test' [4], and 'Poker-chip test' [1] are the examples used. These examples serve to illustrate the capability of the model to describe the nucleation and propagation of fracture in nominally elastic brittle materials at large under arbitrary monotonic quasistatic boundary conditions. One way to run these examples is using Google Colab, which offers a user-friendly and comfortable interface for executing ipynb files with ease. With just a few clicks, users can enjoy the convenience of running their ipynb files seamlessly on the Colab's platform. The model provided in the code applies to any isotropic linear elastic material of choice with Young's modulus E and Poisson's ratio nu, Drucker-Prager strength surface parametrized with uniaxial tensile strength Sts and hydrostatic tensile strength Shs, and critical energy release rate Gc.

!********************************************************************** 

! Usage: ! ! This code takes as inputs the 5 material properties listed below: ! 1. E = Young's modulus! 2. nu = Poisson's ratio ! 3. Gc = Critical energy release rate ! 4. sts = Tensile strength ! 5. scs = Compressive strength

! In addition, the user must specify the regularization length for these boundary value problems. Typically, this length should be chosen so that it is smaller than the smallest size of the structure, as well as the material characteristic length scale (3Gc)/(16 Wts).


!********************************************************************** 

For any inquiry, please contact me at kamarei2@illinois.edu

Alternatively, you may also reach out to my colleague at aditya.kumar@ce.gatech.edu or my Ph.D. advisor at pamies@illinois.edu

!********************************************************************** 

! References:

! [1] Kamarei, F., Kumar, A., Lopez-Pamies, O. 2024. The poker-chip experiments of synthetic elastomers explained. Journal of the Mechanics and Physics of Solids 188, 105683. http://pamies.cee.illinois.edu/Publications_files/JMPS2004b.pdf

! [2] Leonard, M., Wang, N., Lopez-Pamies, O., Nakamura, T. 2020. The nonlinear elastic response of filled elastomers: Experiments vs. theory for the basic case of particulate fillers of micrometer size. Journal of the Mechanics and Physics of Solids 135, 103781. http://pamies.cee.illinois.edu/Publications_files/JMPS2020a.pdf

! [3] Kumar, A., Bourdin, B., Francfort, G.A., Lopez-Pamies, O. 2020. Revisiting nucleation in the phase-field approach to brittle fracture. Journal of the Mechanics and Physics of Solids 142, 104027. http://pamies.cee.illinois.edu/Publications_files/JMPS2020b.pdf

! [4] Kumar, A., Liu, Y., Dolbow, J.E., Lopez-Pamies, O. 2024. The strength of the Brazilian fracture test. Journal of the Mechanics and Physics of Solids 182, 105473. http://pamies.cee.illinois.edu/Publications_files/JMPS2024.pdf
