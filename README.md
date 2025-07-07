 # PINN for Heat Transfer (No Training Data)

This repository contains a Google Colab implementation of a **Physics-Informed Neural Network (PINN)** that solves the **1D transient heat conduction equation without any training data**. I need to work on this more inorder to get accurate solution.

## Problem Statement

We solve the heat equation:

$\frac{\partial u}{\partial t} = \alpha \frac{\partial^2 u}{\partial x^2}$

with specified initial and boundary conditions.

Unlike conventional machine learning approaches, this model uses **no observed data**—it learns purely by enforcing the governing PDE and conditions.

---

## Contents

- **Copy_of_PINN_for_Heat_Transfer_without_Training_data.ipynb**  
  A self-contained Colab notebook demonstrating:
  - Neural network formulation for \( u(x,t) \)
  - Automatic differentiation for computing PDE residuals
  - Loss construction combining PDE residual, initial, and boundary condition losses
  - Training loop
  - Visualization of the learned solution

---

## Getting Started

Run the notebook in Colab:

**Steps:**
1. Open the link above.
2. Execute each cell sequentially.
3. Observe model training and generated plots.

---

## Features

- Solves PDEs without any labeled data
- Utilizes TensorFlow's automatic differentiation
- Visualizes the predicted temperature field over space and time
- Provides a clear example of PINNs applied to heat transfer problems

---

## Requirements

- Python (via Colab)
- TensorFlow
- NumPy
- Matplotlib

All dependencies are pre-installed in Google Colab.


⭐ Feel free to star this repo if you find it useful!
