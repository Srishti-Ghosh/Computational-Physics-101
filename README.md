# Computational Physics 101

Welcome to the **Computational Physics 101** repository! This collection of Python scripts is designed to provide foundational tools and examples for solving problems in computational physics. Whether you're a student just starting out or an enthusiast looking to explore physics through code, this repository has something for you.

## Features

- **Matrix Operations**: Block matrix construction, LU decomposition, and matrix reconstruction.
- **Numerical Methods**: Linear algebra tools, numerical integration, and differential equation solvers.
- **Physics Applications**: Simulations and computations for mechanics, electromagnetism, quantum physics, and more.
- **Symbolic Computation**: Utilize SymPy for analytical solutions and symbolic manipulation.

## Requirements

The scripts rely on the following Python libraries:

- `numpy`
- `scipy`
- `sympy`

To install the dependencies, run:

```bash
pip install numpy scipy sympy
```

## How to Use

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/your-username/computational-physics-101.git
   cd computational-physics-101
   ```

2. **Run Example Scripts**:

   - For matrix operations, see `block_matrix_operations.py`.
   - For symbolic computations, explore `symbolic_methods.py`.
   - For physics simulations, try `physics_simulations.py`.

   Example:

   ```bash
   python block_matrix_operations.py
   ```

3. **Modify and Experiment**:

   Each script is modular and designed for experimentation. Feel free to tweak parameters and explore different scenarios.

## Example Code

Here is a snippet for block matrix construction and LU decomposition:

```python
import numpy as np
from scipy.linalg import lu

# Example numeric values for A, B, C, D
A_val = np.array([[1, 2], [3, 4]])
B_val = np.array([[5, 6], [7, 8]])
C_val = np.array([[9, 10], [11, 12]])
D_val = np.array([[13, 14], [15, 16]])

# Create block matrix
X_numeric = np.block([[A_val, B_val], [C_val, D_val]])

# LU decomposition
P, L, U = lu(X_numeric)
print("Lower Triangular Matrix L:\n", L)
print("Upper Triangular Matrix U:\n", U)
```

## Contributing

Contributions are welcome! If you have a new computational physics problem or solution, feel free to open a pull request. Ensure your code follows Python best practices and includes comments and documentation.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact

For questions, suggestions, or collaborations, feel free to reach out:

- **Email**: srishtighosh.official@gmail.com
- **GitHub**: [Srishti-Ghosh](https://github.com/Srishti-Ghosh)

Happy coding and exploring physics!

