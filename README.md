# Portfolio Optimization with GARCH-Based Volatility Forecasting

## Overview  
This project implements **portfolio optimization** using the **Generalized Autoregressive Conditional Heteroskedasticity (GARCH) model** to forecast asset volatility. By estimating conditional volatility, the project constructs a covariance matrix, which serves as the foundation for optimizing portfolio allocation. The objective is to determine **optimal asset weights** that maximize the **Sharpe ratio** using historical return data.  

## Key Features  

### GARCH Model for Volatility Prediction  
- Applies **GARCH models** to asset log returns to estimate future volatility.  
- Uses predicted volatility as an input for **portfolio optimization**.  
- Supports multiple assets, with individual volatility estimates for each.  

### Portfolio Construction and Optimization  
- Optimizes portfolio weights to **minimize risk (variance)** or **maximize the Sharpe ratio**.  
- Ensures weights sum to 1, allowing only **long positions (no short selling)**.  
- Utilizes a **covariance matrix** derived from asset volatilities and correlations.  

### Expected Returns and Volatility Calculation  
- Computes **mean returns** and **annualized volatility** using historical price data.  
- Uses GARCH-based volatility estimates for **long-term risk assessment**.  

### Sharpe Ratio Optimization  
- Employs optimization techniques to identify the **highest risk-adjusted return portfolio**.  
- Factors in asset-specific **returns, volatilities, and correlations** for an efficient allocation.  
