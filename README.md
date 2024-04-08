# NextTissUe
A new approach to modelling epithelial cells and tissues 2D 

1) Download and install lammps. The following has been built and tested on Lammps version 2 Aug-2023. Link to download https://www.lammps.org/download.html
2) To begin, extract the zip file USER-AREABOND.zip into your lammps src folder. 
3) Compile lammps using packages molecule, extra-pair and USER-AREABOND. #Follow instruction from https://docs.lammps.org/Build_cmake.html

   # To run cell dynamics:
1) Download all the files from src folder.
2) Ensure template.x is executable. This program creates a custom ring polymer with specified number of atoms.
3) Run the lammps executable file using the input file "in.demo" 
