# Homework 2: Simply-Supported Beam Simulation

## Overview
This homework simulates a simply-supported aluminum beam subjected to a point load using a discrete elastic rod model with implicit Euler time integration.

## Files

### Main Code
- **`Homework2.ipynb`**: Main Jupyter notebook containing the complete simulation code. Run all cells sequentially.

### Running the Simulation

1. **Prerequisites**:
   - Python 3.x
   - NumPy
   - Matplotlib
   - Jupyter Notebook

2. **Execute the notebook**:
   ```bash
   cd homework_2
   jupyter notebook Homework2.ipynb
   ```

### Code Purposes

The code will:
1. Simulate beam deflection for P = 2000 N over 1 second
2. Plot beam deformation at multiple time steps
3. Display ymax vs. time plot with theoretical comparison
4. Run for P = 20 N to 20,000 N
5. Generate comparison plots and error analysis