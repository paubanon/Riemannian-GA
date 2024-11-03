# Riemannian-GA
Mathematica code to obtain the main objects of differential geometry using tetrads and Geometric Algebra. The code is based on the Clifford Basic package by G. Aragon-Camarasa, G. Aragon-Gonzalez, J.L. Aragon and M.A. Rodriguez-Andrade.

This notebook requires the vierbein, and coordinates of a spacetime geometry and calculates the inverse vierbein, metric, inverse metric, connection bivectors, Riemann map(in coordinate and tetrad basis), Ricci vector (in cordinate and tetrad basis), Ricci scalar and Einstein tensor (in coordinate and tetrad basis).

These are the main tools necessary to work with the tetrad-Geometric Algebra formalism as described in General Relativity: New insights from a Geometric Algebra approach, by Pablo Banon Perez (https://arxiv.org/abs/2404.19682)

# Previous steps:
1 - Load the Clifford Basic package as explained in https://github.com/ArturasAcus/GeometricAlgebra

# Notes:
1 - I use the Clifford Basic package because the original Clifford has problems with the signs if combined with the Mathematica Simplify or FullSimplify command.
  Note however that the Clifford Basic package is considerably slower than the Clifford package. This gets considerably reduced by parallelizing expressions.

2 - Due to the algebraicaly convoluted expressions of the Kerr-Newman spacetime, the notebook takes various minutes to run completely. Other simpler metrics, like the Schwarzschild case also present in the repository, run in a matter of seconds.
