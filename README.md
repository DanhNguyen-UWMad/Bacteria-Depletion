1. This GitHub repository contains the input files necessary to reproduce the results presented in our 2024 Nature Communications paper, titled '**Surface Remodeling and Inversion of Cell-Matrix Interaction Underlies Community Recognition and Dispersal in V. cholerae Biofilms**' by Alexis Moreau et al. All coarse-grained molecular dynamics (CGMD) models were developed by Danh Nguyen, UW-Madison ([https://github.com/DanhNguyen-UWMad/Viscosity_NEMD](https://scholar.google.com/citations?user=1XY-fyQAAAAJ&hl=en)

2. Before running the models, please visit the OPENFSI GitHub repository (https://github.com/huilinye/OpenFSI/tree/master/src/structure_potential) by **Huilin Ye et al.** to obtain the necessary force fields. All models in this study were implemented using LAMMPS version 30 July 2016. If you are using a different version of LAMMPS, modifications to the force field files may be required. 

3. Once the new force fields have been added to the **src** folder of LAMMPS, compile LAMMPS as usual by executing the **make mpi** command.

4. After compiling LAMMPS, you can run the model using the following command:  
   mpirun -np {number of cpus} ./lmp_mpi -in **in.dep**, where **in.dep** refers to the LAMMPS input file provided in each folder. For each case in our paper, simulations are run for up to 100,000,000 steps to ensure the depletion totally done.
