# NextTissUe
A new approach to modelling epithelial cells and tissues 2D.

We provide NextTissUe as an additional package to Lammps, a Large-scale Atomic/Molecular Massively Parallel Simulator, and thank its developers for their work.
Basic knowledge of Lammps is recommended to run NextTissUe.

Follow the steps below to install LAMMPS and NextTissUe.

1) Download and install Lammps. Our code has been built and tested on a Linux architecture and version 2 of Lammps Aug-2023. Link to download https://www.lammps.org/download.html
2) Extract the zip file USER-AREABOND.zip into your Lammps src folder.
3) Modify the file 'YOUR_PATH_TO_LAMMPS/lammps-2Aug2023/cmake/CMakeLists.txt' by adding include 'USER-AREABOND' in "set(STANDARD_PACKAGES ....)".
5) Compile Lammps using packages molecule, extra-pair, and USER-AREABOND, following the instructions from https://docs.lammps.org/Build_cmake.html

# How to run NextTissuE
We provide an example Lammps input script that sets up an initial configuration and evolves the system, "in.demo".
The script includes comments to describe the different performed steps.
It relies on the file "template.x" to create a template ring-polymer model.

1) Download all the files.
2) Compile "template.cpp" into an executable with the name "template.x" is executable. This program creates a custom ring polymer with a specified number of atoms (a 'molecule' in LAMMPS).
4) Ensure random_propelling_directions.x is executable. This program generates initial propulsion directions for the cells.
5) Run the Lammps executable file using the input script "in.demo". This script includes comments to describe how the simulation is built up. Follow the instructions at https://docs.lammps.org/Run_basics.html to run Lammps.
