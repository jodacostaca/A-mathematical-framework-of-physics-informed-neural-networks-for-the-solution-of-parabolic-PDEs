# A Mathematical Framework of Physics-Informed Neural Networks for the Solution of Parabolic PDEs

This repository contains the implementation of a mathematical framework for solving parabolic partial differential equations (PDEs) using Physics-Informed Neural Networks (PINNs). The project explores the integration of neural networks with physical laws to provide accurate and efficient solutions to PDEs.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [License](#license)


## Introduction
Physics-Informed Neural Networks (PINNs) are a class of machine learning models that incorporate physical laws into the training process. This project focuses on solving parabolic PDEs, which are commonly encountered in heat transfer, diffusion processes, and other time-dependent phenomena.

## Features
- Implementation of PINNs for parabolic PDEs.
- Support for custom boundary and initial conditions.
- Visualization tools for solution comparison.
- Modular and extensible codebase.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/jodacostaca/A-mathematical-framework-of-physics-informed-neural-networks-for-the-solution-of-parabolic-PDEs
    ```
## Requirements
To run the notebooks, you need the following:
- Python 3.8+
- TensorFlow 2.x
- NumPy
- Matplotlib
- SciPy
- TensorFlow Probability (for advanced models)

## Usage
-Clone the repository:

-Open the Jupyter notebooks:

- PINNS.ipynb: Demonstrates the implementation of standard PINNs.
- RVIPINNs.ipynb: Demonstrates the implementation of Variational PINNs.
- RVPINNS_Parabolic_Freezing_Model/RVPINNS_Cafe-nonDim.ipynb: Applies VPINNs to a freezing model.
- Run the cells in the notebooks to train the models and visualize the results.

## Results
The project provides:

- Solution plots comparing neural network predictions with exact or experimental solutions.
- Training loss and error evolution plots.
- Application-specific results, such as temperature profiles in freezing models.
- Example plots:

- Solution Plot: plot_sol_Cafe.pdf
- Loss Plot: plot_loss_Cafe.pdf

## License
This project is licensed under the MIT License. See the LICENSE file for details.

