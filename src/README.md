# Optimization and Required Files

The `optim.ipynb` file is the main notebook that performs the optimization and generates the output file. However, it requires the following input files to function:

1. **Hubbard Hamiltonian and Ground State Data**  
   - These files contain the Hubbard Hamiltonian, the ground state, and its corresponding energy.  
   - They are generated using the notebook `get_gs_ham_numpy/torch.ipynb`.

2. **Matrix Representation of Operators**  
   - This file contains the matrix representation of the operators applied during the optimization process.  
   - It is generated using the notebook `torch_get_ci^+_cj_n_related_matrix.ipynb`.

3. **Basis for Different \( S \) Values (for \( S_z = 0 \))**  
   - For the specific case \( S_z = 0 \), a file is provided to generate the basis for states with different \( S \) values.  
   - This is provided in the notebook `get_spin_matrix_spin_basis.ipynb`.

Ensure that these prerequisite files are correctly generated and accessible before running `optim.ipynb`.

For more details on generating the required files, refer to the respective notebooks.
