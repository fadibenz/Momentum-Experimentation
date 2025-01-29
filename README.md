# Momentum in Gradient Descent 

## Overview
This notebook explores the concept of momentum in gradient descent optimization. It provides a detailed mathematical foundation for understanding how momentum accelerates convergence in gradient-based optimization algorithms, particularly in ill-conditioned problems. The notebook also includes visualizations of gradient descent with and without momentum, demonstrating the impact of momentum on the optimization process.

The notebook is divided into several sections:
1. **Introduction**: A brief overview of momentum in gradient descent and its benefits.
2. **Mathematical Foundation**: A detailed explanation of the mathematical principles behind momentum, including the derivation of the update rules and the analysis of eigenvalues using **Sympy** for symbolic computing.
3. **Implementation**: Code implementations of gradient descent with and without momentum.
4. **Visualization**: Visualizations of the loss landscape and the trajectories of the parameters during optimization.
5. **Conclusion**: A summary of the findings and the key takeaways.

## Key Concepts
- **Gradient Descent**: An optimization algorithm used to minimize a function by iteratively moving towards the minimum value of the function.
- **Momentum**: A technique used to accelerate gradient descent by adding a fraction of the previous update to the current update.
- **Eigenvalue Analysis**: A method used to analyze the stability and convergence rate of the optimization algorithm.

## Dependencies
To run this notebook, you will need the following Python libraries:
- `numpy`
- `matplotlib`
- `sympy` (used for symbolic computing)

You can install these libraries using pip:
```bash
pip install numpy matplotlib sympy
```

## Acknowledgement 
The code was inspired by CS182 course by UC Berkeley. 
