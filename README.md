# Computational Uncertainty Quantification for Inverse Problems

This repository contains the implementation, methodology, and results of my Final Year Project titled **"Computational Uncertainty Quantification for Inverse Problems"**.

## Overview
Inverse problems arise in various domains, such as signal processing, medical imaging, and engineering, where hidden parameters are inferred from indirect or noisy observations. This project explores Bayesian techniques to reconstruct signals and quantify uncertainty using tools such as CUQIpy.

Key Highlights:
- Reconstruction of signals and images using probabilistic modeling.
- Analysis of uncertainty through credible intervals.
- Practical implementation with real-world-inspired test problems.

## Features
- **Forward Modeling**: Implements forward operators for inverse problems.
- **Bayesian Priors**: Utilizes Gaussian Markov Random Fields (GMRF) to encode prior knowledge.
- **Posterior Sampling**: Uses Markov Chain Monte Carlo (MCMC) methods for inference.
- **Visualization**: Includes MAP estimates, credible intervals, and result comparisons.

├── docs/           # Detailed project documentation
├── code/           # Python scripts for implementation
├── data/           # Input datasets and test cases
├── results/        # Generated figures, logs, and analysis reports
├── appendix/       # Supplementary notes and additional information
└── README.md       # Project overview and usage guide


## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/karamat-ali-soomro/Computational-Uncertainty-Quantification-for-Inverse-Problem.git
