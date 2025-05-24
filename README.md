# FEniCSx_Kamarei_Kumar_Lopez-Pamies

This repository contains FEniCSx example codes for solving boundary value problems with the phase-field model of Griffith fracture with material strength put forth in [1].

The following examples are included:

- **Cylindrical hole tension test** [2]  
- **Single edge notch tension test** [3]  
- **Surfing test** [3]  
- **Indentation test** [4]  
- **Brazilian test** [5]  
- **Poker-chip test** [1]  

These examples illustrate the capability of the model to describe the nucleation and propagation of fracture in nominally elastic brittle materials at large under arbitrary monotonic quasistatic boundary conditions.

One way to run these examples is using Google Colab, which offers a user-friendly and comfortable interface for executing `.ipynb` files with ease. With just a few clicks, users can enjoy the convenience of running their notebooks seamlessly on Colab’s platform.

The model provided in the code applies to any isotropic linear elastic material of choice, characterized by:

- Young’s modulus `E`  
- Poisson’s ratio `ν`  
- Drucker-Prager strength surface with:
  - Uniaxial tensile strength `Sts`
  - Hydrostatic tensile strength `Shs`
- Critical energy release rate `Gc`  



##  Usage
This code takes the following **five material properties** as inputs:

1. `E` = Young's modulus  
2. `ν` = Poisson's ratio  
3. `Gc` = Critical energy release rate  
4. `sts` = Tensile strength  
5. `scs` = Compressive strength  

Additionally, the user must specify the **regularization length** `eps` for the boundary value problems. Typically, this length should be chosen so that it is smaller than the smallest size of the structure, as well as the material characteristic length scale (3Gc)/(16 Wts).

##  Contact

For any inquiry, please contact me at [kamarei2@illinois.edu](mailto:kamarei2@illinois.edu)

Alternatively, you may also reach out to my colleague at [aditya.kumar@ce.gatech.edu](mailto:aditya.kumar@ce.gatech.edu) or my Ph.D. advisor at [pamies@illinois.edu](mailto:pamies@illinois.edu)


##  References

[1] Kamarei, F., Kumar, A., Lopez-Pamies, O. (2024). *The poker-chip experiments of synthetic elastomers explained*. Journal of the Mechanics and Physics of Solids, 188, 105683. [PDF](http://pamies.cee.illinois.edu/Publications_files/JMPS2004b.pdf)

[2] Leonard, M., Wang, N., Lopez-Pamies, O., Nakamura, T. (2020). *The nonlinear elastic response of filled elastomers: Experiments vs. theory for the basic case of particulate fillers of micrometer size*. Journal of the Mechanics and Physics of Solids, 135, 103781. [PDF](http://pamies.cee.illinois.edu/Publications_files/JMPS2020a.pdf)

[3] Kumar, A., Bourdin, B., Francfort, G.A., Lopez-Pamies, O. (2020). *Revisiting nucleation in the phase-field approach to brittle fracture*. Journal of the Mechanics and Physics of Solids, 142, 104027. [PDF](http://pamies.cee.illinois.edu/Publications_files/JMPS2020b.pdf)

[4] Kumar, A., Ravi-Chandar, K., Lopez-Pamies, O. (2022). *The revisited phase-field approach to brittle fracture: Application to indentation and notch problems*. International Journal of Fracture, 237, 83–100. [PDF](http://pamies.cee.illinois.edu/Publications_files/FRAC_2022.pdf)

[5] Kumar, A., Liu, Y., Dolbow, J.E., Lopez-Pamies, O. (2024). *The strength of the Brazilian fracture test*. Journal of the Mechanics and Physics of Solids, 182, 105473. [PDF](http://pamies.cee.illinois.edu/Publications_files/JMPS2024.pdf)
