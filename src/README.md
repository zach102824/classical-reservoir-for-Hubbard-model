# Optimization and Required Files

The `optim.ipynb` notebook is the main script for performing optimization and generating output files. To ensure smooth execution, the following input files must be prepared beforehand:

## Required Input Files

### 1. Hubbard Hamiltonian and Ground State Data
- Contains the Hubbard Hamiltonian, the ground state, and its corresponding energy.
- **Generated using**: `get_gs_ham_numpy/torch.ipynb`.

### 2. Matrix Representation of Operators
- Stores the matrix representation of the operators applied during the optimization process.
- **Generated using**: `torch_get_ci^+_cj_n_related_matrix.ipynb`.

## Additional File

### Basis for Different \( S \) Values (\( S_z = 0 \))
- Provides the basis for states with different total spin \( S \), specifically for \( S_z = 0 \).
- **Generated using**: `get_spin_matrix_spin_basis.ipynb`.
