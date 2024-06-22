# NextTissUe
A new approach to modelling epithelial cells and tissues 2D.

We provide NextTissUe as an additional package to LAMMPS, a Large-scale Atomic/Molecular Massively Parallel Simulator.
Basic knowledge of LAMMPS is recommended to run NextTissUe.

Follow the steps below to install LAMMPS and NextTissUe.

1) Download and install Lammps. Our code has been built and tested on Lammps version 2 Aug-2023. Link to download https://www.lammps.org/download.html
2) Extract the zip file USER-AREABOND.zip into your Lammps src folder.
3) Modify the file 'YOUR_PATH_TO_LAMMPS/lammps-2Aug2023/cmake/CMakeLists.txt' by adding include 'USER-AREABOND' in "set(STANDARD_PACKAGES ....)".
5) Compile Lammps using packages molecule, extra-pair, and USER-AREABOND, following the instructions from https://docs.lammps.org/Build_cmake.html

# How to run NextTissuE
NextTissUe evolves an initial configuration.
1) Download all the files.
2) Combile template.cpp into an executable with name emplate.x is executable. This program creates a custom ring polymer with a specified number of atoms (a 'molecule' in LAMMPS).
4) Ensure random_propelling_directions.x is executable. This program generates initial propulsion directions for the cells.
5) Run the Lammps executable file using the input file "in.demo." Follow the instructions at https://docs.lammps.org/Run_basics.html to run Lammps. 
