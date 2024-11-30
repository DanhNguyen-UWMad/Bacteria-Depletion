This GitHub repository contains the input files necessary to reproduce the results presented in our 2024 Nature Communications paper, titled '**Surface Remodeling and Inversion of Cell-Matrix Interaction Underlies Community Recognition and Dispersal in V. cholerae Biofilms**' by Alexis Moreau et al. All coarse-grained molecular dynamics (CGMD) models were developed by Danh Nguyen under the supervision of Dr. Ying Li and Dr. Jing Yan.

Before running the models, please visit the OPENFSI GitHub repository (https://github.com/huilinye/OpenFSI/tree/master/src/structure_potential) by Huilin Ye et al. to obtain the necessary force fields. All models in this study were implemented using LAMMPS version 30 July 2016. If you are using a different version of LAMMPS, modifications to the force field files may be required. 

Once the new force fields have been added to the **src** folder of LAMMPS, compile LAMMPS as usual by executing the **make mpi** command.
