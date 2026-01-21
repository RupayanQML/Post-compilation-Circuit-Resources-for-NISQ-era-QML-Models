# Post-compilation-Circuit-Resources-for-NISQ-era-QML-Models
This repository contains the code accompanying the paper:

“Characterizing Scaling Trends of Post-Compilation Circuit Resources for NISQ-era QML Models”

It provides reproducible experiments and figures used to analyze post-compilation circuit resource overheads and fidelity scaling trends for Quantum Machine Learning (QML) models on NISQ-era hardware.

## Repository Structure

The repository is organized into two main folders:

### Post-compilation resource analysis
Code and figures for assessing post-compilation circuit resource overheads (SWAP count, circuit depth, two-qubit gate count) for QML models, including:

Quantum kernel evaluation circuits

Quantum neural networks

### Fidelity scaling analysis
Code and figures for investigating circuit fidelity scaling trends under realistic noise models.

Each folder contains:

Jupyter notebooks (.ipynb) implementing the experiments

Figures generated using the associated code

Note: Code updates and refinements are ongoing.

## Abstract

This work investigates the scaling characteristics of post-compilation circuit resources for Quantum Machine Learning (QML) models on connectivity-constrained NISQ processors. We analyze Quantum Kernel Methods and Quantum Neural Networks across processor topologies (linear, ring, grid, star), focusing on SWAP overhead, circuit depth, and two-qubit gate count. Our findings reveal that entangling strategy significantly impacts resource scaling, with circular and shifted circular alternating strategies showing steepest scaling. Ring topology demonstrates slowest resource scaling for most QML models, while Tree Tensor Networks lose their logarithmic depth advantage after compilation. Through fidelity analysis under realistic noise models, we establish quantitative relationships between hardware improvements and maximum reliable qubit counts, providing crucial insights for hardware-aware QML model design across the full-stack architecture.

## Citation

If you use this code, please cite:

R. Bhattacharjee, P. Escofet, S. Rodrigo, S. Abadal, C. G. Almudéver, E. Alarcón,
“Characterizing Scaling Trends of Post-Compilation Circuit Resources for NISQ-era QML Models,”
Proceedings of the IEEE QAI’25, November 2025.

## Open-access Version

The paper is also available on arXiv:
https://arxiv.org/abs/2509.11980

## Questions & Contact

For questions, issues, or suggestions, please open an issue or submit a pull request.
