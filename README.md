# NextTissUe
A new approach to modelling epithelial cells and tissues 2D 

1) Download and install Lammps. The following has been built and tested on Lammps version 2 Aug-2023. Link to download https://www.lammps.org/download.html
2) To begin, extract the zip file USER-AREABOND.zip into your Lammps src folder. 
3) Compile Lammps using packages molecule, extra-pair, and USER-AREABOND. #Follow instructions from https://docs.lammps.org/Build_cmake.html

   # To run cell dynamics:
1) Download all the files in main.
2) Ensure template.x is executable. This program creates a custom ring polymer with a specified number of atoms.
3) Ensure random_propelling_directions.x is executable. This program generates initial propulsion directions for the cells.
4) Run the Lammps executable file using the input file "in.demo". Follow instructions from https://docs.lammps.org/Run_basics.html on how to run Lammps. 
