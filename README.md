# Liquidity Regime Inference with HMC vs. HMM

This project compares Hamiltonian Monte Carlo (HMC) and Hidden Markov Models (HMM) for inferring latent liquidity regimes in synthetic time series data. 

## Methods
- HMC inference via PyMC
- HMM implementation via `hmmlearn`
- Comparison of recovery accuracy under different noise and volatility conditions

## Status
Currently uses synthetic data. Future updates will include market microstructure data for stress regime detection.

## Requirements
- Python 3.10+
- PyMC
- hmmlearn
- NumPy, matplotlib

