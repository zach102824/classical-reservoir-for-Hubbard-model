# Optimization and Required Files

The `optim.ipynb` file is the main notebook that performs the optimization and generates the output file. However, it requires the following input files to function:

1. **Hubbard Hamiltonian and Ground State Data**  
   - Those files contains the Hubbard Hamiltonian, the ground state, and its corresponding energy.  
   - It is generated using another notebook called `get_gs_ham_numpy/torch.ipynb`.

2. **Matrix Representation of Operators**  
   - This file contains the matrix representation of the operators applied during the optimization process.  
   - It is generated using another notebook called `torch_ get_ci^+_cj_n_related_matrix.ipynb`.

Ensure that these prerequisite files are correctly generated and accessible before running `optim.ipynb`.

For more details on generating the required files, refer to the respective notebooks.
