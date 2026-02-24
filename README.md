This project analyzes the nucleon–nucleon ($NN$) interaction in the $^{1}S_0$ partial wave within the framework of Effective Field Theories (EFTs). The goal is to reproduce and study the renormalization procedure presented in the original work by Nieves (2003), combining long- and short-range contributions in a consistent theoretical description.

The long-range interaction is modeled through the standard one-pion exchange potential, while short-distance physics is encoded using singular contact interactions containing up to two derivatives. This separation of scales follows the EFT philosophy, where unresolved high-energy dynamics are absorbed into low-energy constants.

To obtain physical observables, the Lippmann–Schwinger equation (LSE) for the scattering amplitude is solved using advanced theoretical tools. In particular, Dimensional Regularization (DR) and Distorted Wave Theory (DWT) are used to treat the problem.

In addition to the analytical framework, the project includes a numerical solution implemented in Fortran (the program can be found in the corresponding folder of the repository). The main objective of this numerical implementation is to reproduce the experimental phase-shift data associated with the on-shell scattering matrix. Special attention is given to achieving high numerical precision in the extraction of physical information. Low-energy constants and relevant parameters are determined using the residue theorem


