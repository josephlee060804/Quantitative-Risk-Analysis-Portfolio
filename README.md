# Quantitative-Risk-Analysis-Portfolio
Python based risk engine that pulls live market data to calculate multi asset covariance matrices, tracking error against the S&amp;P, and Fama-French factor exposures
This project is a portfolio risk analysis tool built in Python. Designed to mirror existing risk frameworks, the notebook assesses tail risk, asset correlation, and benchmark deviation across a general but custom equity portfolio.

Core functionalities include single asset and multi asset Value at Risk (VaR) modeling, scenario-based stress testing (simulating historic market shocks), and tracking error analysis. By running an OLS regression against the Fama-French 3 Factor model, the project successfully isolates the specific risk factors driving portfolio performance. This repository serves as a practical application and visualization of quantitative finance theory, demonstrating a scalable, data driven approach to evaluating market volatility and active portfolio risk.
