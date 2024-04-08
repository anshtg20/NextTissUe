# NextTissUe
A new approach to modelling epithelial cells and tissues 2D 

1) To begin, extract the zip file USER-AREABOND.zip into your lammps src folder. #Mention the required lammps verion. 
2) Compile lammps using packages molecule, extra-pair and USER-AREABOND. #Follow instruction from https://docs.lammps.org/Build_cmake.html

   # To run cell dynamics:
1) Ensure template.x is executable. This program creates a custom ring polymer with specified number of atoms.
2) Run the lammps executable file using the input file "in.demo" 
