# 

1. 📌 Project Overview

This project applies Modern Portfolio Theory (MPT), specifically the Markowitz model, to optimize an investment portfolio for individual investors in the Vietnamese stock market.

The objective is to:

Maximize expected return for a given level of risk
Minimize risk for a target return
Provide a data-driven portfolio allocation strategy instead of intuition-based investing

The project is based on real market data and was developed during an internship at a securities company.

2. 🎯 Objectives
Analyze return and risk characteristics of selected stocks
Construct the efficient frontier
Identify the optimal portfolio allocation
Evaluate portfolio performance using Sharpe Ratio
Support practical investment advisory for retail clients
3. 📊 Dataset
Source: Vietnamese stock market data (via Python libraries – e.g., vnstock)
Time period: Oct 2022 – latest available
Assets analyzed:
FPT (Technology)
HPG (Steel)
VCB (Banking)
BCM (Industrial Real Estate)
VDS (Securities)

These stocks were selected to ensure sector diversification and reflect real market dynamics
4. ⚙️ Methodology
4.1 Data Processing
Convert price data → log returns
Clean and align time series data
4.2 Statistical Analysis
Expected return (mean)
Risk (standard deviation)
Correlation matrix
4.3 Portfolio Optimization
Apply Quadratic Programming
Generate thousands of portfolio combinations
Construct Efficient Frontier
4.4 Performance Evaluation
Sharpe Ratio:
Identify:
Minimum variance portfolio
Maximum Sharpe portfolio
5. 🧠 Key Concepts
Diversification reduces unsystematic risk
Correlation plays a critical role in portfolio construction
Optimal portfolio ≠ highest return, but best risk-return trade-off
6. 💻 Tech Stack
Python
Jupyter Notebook
Libraries:
numpy
pandas
matplotlib
scipy
vnstock (data extraction)
7. 📈 Key Results
Built an efficient frontier
Identified optimal portfolio weights for different risk levels
Demonstrated that diversification improves performance vs single-stock investing
Provided a practical advisory framework for individual investors
