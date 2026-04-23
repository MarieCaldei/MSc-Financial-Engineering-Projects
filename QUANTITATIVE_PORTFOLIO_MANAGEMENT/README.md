# Quantitative Portfolio Management: Black-Litterman & Mean-Variance Optimization

## Project Overview
This project, developed for the **Quantitative Portfolio Management** course at **EDHEC Business School**, implements advanced asset allocation strategies. The goal is to compare traditional Markowitz optimization with the Black-Litterman model by integrating subjective market views into a quantitative framework.

## Key Features
* **Mean-Variance Optimization (MVO):** Implementation of the Markowitz framework to find the efficient frontier using `cvxpy`.
* **Black-Litterman Model:** * Calculation of equilibrium returns using market capitalization weights (CAPM).
    * Integration of subjective views (e.g., specific performance of Tech stocks like AAPL, MSFT, NVDA).
    * Computation of the combined return vector ($\mu_{BL}$) and covariance matrix ($\Sigma_{BL}$).
* **Comparative Analysis:** Performance and weight distribution comparison between:
    * Markowitz Mean-Variance Portfolio.
    * Market Capitalization-Weighted Portfolio.
    * Black-Litterman Optimized Portfolio.
* **Risk Assessment:** Analysis of portfolio diversification and stability under different market assumptions.

## Technical Stack
* **Language:** Python
* **Optimization:** `cvxpy`
* **Data Retrieval:** `yfinance` (Real-time market data for S&P 500 components)
* **Analysis:** `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`

## Deliverables
* `Black_Litterman_and_Mean_Variance_Optimization.ipynb`: Full implementation including data cleaning, optimization, and visualization.
