# Krishank

I build financial models from first principles: not as a shortcut to answers, 
but to understand the machinery underneath.

Currently exploring volatility dynamics, stochastic processes, and the gap 
between closed-form elegance and numerical reality.

## Projects

**Volatility Forecasting** · [repo](https://github.com/krishank1212/volatility-forecasting)  
Empirical comparison of RHV and EWMA estimators against 5-day realised vol on 
~5300 SPY trading days (2005–2026). Strict causal implementation, no look-ahead. 
EWMA (λ=0.94) outperforms RHV(20) and RHV(60) by MSE.

**Options Greeks Dashboard** · [repo](https://github.com/krishank1212/options-greeks-dashboard)  
GBM simulation of European call pricing under Black–Scholes. Antithetic variates 
(↓28% error) and control variates using $S_T$ (↓38% error). Verified $O(N^{-1/2})$ 
convergence across 500–100,000 paths. Greeks (Δ, Γ, ν, Θ, ρ) computed analytically 
and via central finite differences, with an interactive Streamlit dashboard.

## Stack
Python · NumPy · SciPy · pandas · Matplotlib · Streamlit

## Interests
Stochastic calculus · volatility modelling · numerical methods · mathematical finance · measure theory
