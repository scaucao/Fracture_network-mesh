# Fracture_network-mesh
This repository contains the initial mesh file for the numerical example: "Example 4: Flow through a 2D porous media with fracture network" of the work:

S. Caucao and J. Esparza: An augmented mixed FEM for the convective Brinkman-Forchheimer problem: a priori and a posteriori error analysis. Journal of Computational and Applied Mathematics, vol 438, Art. Num. 115517, (2024).

Available in DOI: <a href="https://doi.org/10.1016/j.cam.2023.115517" target="_blank">10.1016/j.cam.2023.115517</a>


To load the mesh in FreeFem++, use the code:

mesh Th = readmesh("Fracture_network-mesh-0.msh");


Labels setting:

33: region outside the fracture

34: region inside the fracture

1: bottom boundary

22: right and top boundaries

4: left boundary
