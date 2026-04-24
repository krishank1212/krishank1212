# Krishank

I build financial models from first principles — not as a shortcut to answers, but to understand the machinery underneath.

Currently exploring volatility dynamics, stochastic processes, and the gap between closed-form elegance and numerical reality.

## Projects

**Volatility Forecasting** · [repo](https://github.com/krishank1212/volatility-forecasting)
Empirical comparison of rolling historical volatility and EWMA estimators against 5-day realised vol on ~5300 SPY trading days (2005–2026). Strict causal implementation — no look-ahead. Evaluated with MSE. EWMA (λ=0.94) outperforms RHV(20) and RHV(60).

**Monte Carlo Option Pricer** · [repo](https://github.com/krishank1212/asset-price-simulator)
GBM simulation of European call pricing under Black–Scholes. Implemented antithetic variates (↓28% error) and control variates using S_T as the variate (↓38% error). Verified O(N^{-1/2}) convergence empirically across 500–100,000 paths.

## Stack

Python · NumPy · SciPy · pandas · matplotlib

## Interests

Stochastic calculus · volatility modelling · numerical methods · mathematical finance · measure theory
