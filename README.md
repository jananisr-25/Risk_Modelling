# Risk Modelling
# Portfolio Risk Modelling & Stress Testing

## Overview

Developed a portfolio risk analytics system to measure, forecast and stress-test risk using statistical and simulation models.

This project evaluates portfolio risk under both normal and stressed market conditions through historical analysis, Monte Carlo simulation, stress testing, tail-risk measurement and volatility forecasting. The framework is designed to answer a key question:

**"How risky is a portfolio, how bad can losses get, and how reliable are the risk estimates?"**

---

## Key Features

### Historical Risk Analysis

* Portfolio return analysis
* Annualized return and volatility
* Rolling volatility estimation
* Return distribution visualization
* Maximum Drawdown (MDD) analysis

### Monte Carlo Risk Forecasting

* Simulated 10,000 future portfolio paths
* Estimated expected portfolio value
* Probability of loss calculation
* Median and tail percentile outcomes
* Future wealth distribution analysis

### Stress Testing

#### Historical Replay Scenarios

* COVID-19 Market Crash (Feb 2020 – Mar 2020)
* Interest Rate Hike Cycle (Jan 2022 – Oct 2022)

#### Hypothetical Scenarios

* Financial Sector Crisis
* Volatility Regime Shift

Stress tests evaluate portfolio performance under extreme market conditions and compare resilience across different portfolio strategies.

### Tail Risk Measurement

* Value at Risk (VaR)
* Conditional Value at Risk (CVaR)
* Marginal VaR
* Component VaR

### Volatility Forecasting

* Historical Volatility
* GARCH(1,1) Conditional Volatility Forecasting
* GARCH-based VaR Estimation

### Risk Model Validation

* Expanding-window VaR forecasting
* VaR breach analysis
* Kupiec Proportion-of-Failures (POF) Test
* Pass/Fail model validation framework

---

## Risk Metrics Generated

For any portfolio, the framework provides:

* Expected Return
* Annualized Volatility
* Maximum Drawdown
* Probability of Loss
* VaR and CVaR
* Marginal and Component VaR
* Historical & Forecasted Volatility
* Stress-Test Losses
* Kupiec Backtesting Results

---

## Methodology

1. Compute historical portfolio returns
2. Analyze return distribution and volatility characteristics
3. Simulate future portfolio outcomes using Monte Carlo methods
4. Evaluate performance under historical and hypothetical stress scenarios
5. Measure tail risk using VaR-based metrics
6. Forecast volatility using GARCH models
7. Validate risk estimates using Kupiec backtesting

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* SciPy
* yFinance
* ARCH (GARCH Modelling)

---

## Sample Outputs

* Rolling Volatility Analysis
* Return Distribution Plots
* Monte Carlo Simulation Paths
* Future Wealth Distributions
* Stress Testing Results
* VaR / CVaR Comparison
* GARCH Volatility Forecasts
* Kupiec Backtesting Dashboard

---

## Resume Highlights

* Analysed risk of 4 portfolios by simulating 10K Monte Carlo paths, estimating expected value, loss probability and tail percentiles.
* Performed historical and hypothetical stress testing using COVID crash and rate-hike scenarios to assess tail-risk sensitivity.
* Implemented VaR/CVaR, Marginal & Component VaR, GARCH forecasting and Kupiec backtesting for portfolio risk measurement and validation.
