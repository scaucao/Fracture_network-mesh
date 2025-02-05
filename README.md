# Fracture_network-mesh
This repository contains the initial mesh file for the numerical example "Example 4: Flow through a 2D porous medium with a fracture network" from the following papers:

S. Caucao and J. Esparza: An augmented mixed FEM for the convective Brinkman-Forchheimer problem: a priori and a posteriori error analysis. Journal of Computational and Applied Mathematics, vol 438, Art. Num. 115517, (2024).
Available in DOI: <a href="https://doi.org/10.1016/j.cam.2023.115517" target="_blank">10.1016/j.cam.2023.115517</a>

and

S. Caucao, G.N. Gatica, and L.F. Gatica: A posteriori error analysis of a mixed finite element method for the stationary convective Brinkman-Forchheimer problem. Applied Numerical Mathematics, vol. 211, pp. 158-178, (2025).
Available in DOI: <a href="https://doi.org/10.1016/j.apnum.2025.01.007" target="_blank">10.1016/j.apnum.2025.01.007</a>

To load the mesh in FreeFEM, use the code:

mesh Th = readmesh("Fracture_network-mesh-0.msh");


Labels setting:

33: region outside the fracture

34: region inside the fracture

1: bottom boundary

22: right and top boundaries

4: left boundary
