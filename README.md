# Hi, I'm Emmanuel Adeleye

**Credit Derivatives (Bank of America) → Quantitative Risk & Rates**
MSc Financial Engineering, WorldQuant University | Python, QuantLib, SQL

I work in Credit Trade Control at Bank of America, supporting daily P&L and risk reconciliation across single-name CDS, indices, index options and tranches. Alongside that, I'm completing an MSc in Financial Engineering and building a quantitative research portfolio in Python — the projects in this repository.

The through-line is simple: take a real pricing, risk, or forecasting problem, build it from first principles, and validate it independently before trusting the output.

---

## Featured Projects

### 📐 GBP SONIA Curve Construction & Rates P&L Attribution Engine
Bootstrapped a GBP SONIA OIS discount curve from first principles (par-swap equation, 10-pillar 1Y–10Y), cross-validated against QuantLib to within ~1–2bp with the residual traced to day-count convention. Built a companion scenario engine (parallel, twist, butterfly, historical replay) and a swap-level P&L attribution framework decomposing carry, roll-down, curve-factor and residual — key-rate durations reconcile exactly to parallel DV01 (£607.97).
`[repo link]`

### 📊 Copula-Enhanced Pairs Statistical Arbitrage
Market-neutral statistical arbitrage strategy (β = 0.03, R² < 0.0005) across 100 equities, combining a z-score signal with a Student-t copula as a tail-dependence regime filter. 1.74 Sharpe / 1.36 information ratio over a 4-year walk-forward validation; the copula filter prevented a material drawdown during the 2025 correlation breakdown (+3.04 Sharpe vs −0.62 baseline).
`[repo link]`

### 📈 Regime-Aware Hybrid LSTM-GARCH Volatility Forecaster
5-day-ahead S&P 500 volatility forecasting combining LSTM and GARCH(1,1) in a hybrid framework, with regime-specific analysis via HMM. 7.4% RMSE improvement over pure LSTM, 12.6% over GARCH(1,1), significant in 98% of tested market conditions.
`[repo link]`

### 🌐 Volatility Surface Modeling for SPY Options
Arbitrage-free implied volatility surface using SVI parameterisation calibrated via least-squares optimisation, with an ML-enhanced layer (Random Forest, neural network) for real-time IV interpolation — 0.0050 RMSE, ahead of standard spline/kernel baselines.
`[repo link]`

---

## Background

BSc Petroleum Engineering (University of Ibadan), with a published paper on predictive modelling of reservoir gas properties (*Asian Journal of Probability and Statistics*, 2025) — first-principles statistical modelling applied to a different domain before this one.

## Tech

`Python` · `NumPy / SciPy / pandas / statsmodels / scikit-learn` · `QuantLib` · `TensorFlow / PyTorch` · `SQL`

## Connect

- [LinkedIn](https://www.linkedin.com/in/emmanueladeleye)
- Email: emmanueladeleye102@gmail.com

Always glad to talk rates, credit derivatives, or quantitative modelling.
