# Deep Generative Models - HW1 - Fall 2024
## Sharif University of Technology
### Autoregressive Models, LSTM, PixelCNN

This repository contains my solutions for the 1st assignment of the Deep Generative Models course at Sharif University of Technology. This assignment consists of two parts: theoretical and practical.

#### Theoretical Part

- **Autoregressive Models of Order p**: Explores Maximum Likelihood Estimation (MLE) for linear AR models, including derivation of the log-likelihood function and parameter estimation.
- **Autoregressive Models**: Covers MLE for AR models with neural network conditionals, predictive sampling, KL divergence between AR models, stationarity and long-term dependencies, and hypotheses for performance degradation in longer sequences (bonus).
- **Real NADE Parameters**: Extends Real NADE to model conditionals as mixtures of Gaussians, including parameterization and total parameter count.
- **Monte Carlo Estimation**: Includes a warm-up expectation calculation, variance of K-sample estimators, and objective minimization using Monte Carlo for unbiased estimation of objectives and gradients.

The theoretical solutions are provided in the PDF file: `DGM_HW1_Theoretical.pdf`.

#### Practical Part

- **DGM_HW1.ipynb**: This Jupyter notebook contains the implementation of LSTM for stock price prediction (using Yahoo Finance data for tech stocks like AAPL, GOOG, MSFT, AMZN) and PixelCNN for autoregressive image modeling on the MNIST dataset. It includes data preprocessing, model training, evaluation (e.g., RMSE), sampling, and autocompletion tasks.
