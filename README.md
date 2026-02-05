# Neural Network Training Dynamics Analysis

## Objective
This project investigates the sensitivity and stability of neural network training with respect to weight perturbations and loss landscape geometry.

## Research Questions
- How sensitive are trained models to small perturbations in weight space?
- How does loss landscape shape relate to training stability and robustness?
- Are sharp minima associated with higher sensitivity to perturbations?

## Experimental Setup
- Models: Fully-connected neural networks
- Datasets: MNIST / synthetic datasets
- Frameworks: Python, NumPy, PyTorch / TensorFlow
- Evaluation: Loss behavior, accuracy stability, visualization

## Key Observations (Summary)
- Models converging to sharper minima exhibited higher sensitivity to small weight perturbations.
- Flat regions of the loss landscape correlated with more stable convergence.
- Weight perturbations beyond a threshold caused rapid degradation in performance.

## Structure
- notebooks/: Experimental analysis notebooks
- figures/: Generated plots and visualizations
- report/: Technical report summarizing findings

## Status
Ongoing research work. Results are exploratory and subject to further validation.
