# econ5200-lab05-risk-model# 
Diagnosing a Flawed Risk Model — VaR, Expected Shortfall & Monte Carlo

## Objective
My goal was to evaluate a portfolio risk model, identify where it underestimated potential losses, and compare different methods of measuring financial risk.

## Methodology
- I examined a junior analyst's normal-distribution Value at Risk (VaR) model and compared its estimates with historical VaR.
- I calculated VaR and Expected Shortfall (ES) using historical simulation, the normal distribution, and a fitted Student-t distribution.
- I used Monte Carlo simulation with antithetic variates to reduce estimation error.
- I worked with a `risk_metrics.py` module containing `calculate_var`, `calculate_es`, and `mc_var`, and ran its self-tests.
- I used AI to generate a VaR backtesting function, revised my prompt to clarify the inputs and expected output, and compared the result with my own exceedance count.

## Key Findings
- At the 99% confidence level, the normal-distribution model underestimated historical VaR by **[YOUR VALUE]%**, equivalent to **$[YOUR VALUE]** on the portfolio.
- The fitted Student-t distribution had **[YOUR VALUE]** degrees of freedom.
- Antithetic variates reduced the Monte Carlo standard error by a factor of **1.26**.
- The normal 99% VaR was exceeded on **[YOUR VALUE]%** of trading days.
- Comparing VaR and ES helped me understand how different methods measure potential portfolio losses, especially during extreme market movements.

## Conclusion
In this lab, I learned how to identify weaknesses in a financial risk model, compare alternative risk measures, improve Monte Carlo estimation, and test whether a VaR model accurately reflects historical losses.
