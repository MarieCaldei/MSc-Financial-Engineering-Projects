# Financial Risk Modeling: From Naive Bayes to Kernel Methods

## Project Overview
This project was developed as part of the **Advanced Machine Learning and Finance** course in the **MSc in Financial Engineering at EDHEC Business School**. It explores two fundamental pillars of machine learning applied to finance: classification for credit risk and non-linear regression for asset return modeling.

## Key Modules

### 1. Credit Default Prediction (Classification)
* **Objective:** Predict the probability of default for a portfolio of loans.
* **Implementation:** Built a **Gaussian Naive Bayes** classifier from scratch.
* **Key Tasks:**
    * Mathematical parameter estimation (means and variances conditionned on class).
    * Calculation of posterior probabilities for default prediction.
    * Performance analysis using classification metrics.

### 2. Asset Return Modeling (Non-Linear Regression)
* **Objective:** Forecast financial asset returns by capturing non-linear dynamics and volatility regimes.
* **Methodology:** Comparison between a **Linear Regression** model and **Kernel Ridge Regression**.
* **Key Insights:**
    * Construction of the **Gram Matrix** using polynomial kernels.
    * Demonstration of how kernel methods better capture non-linearities in "turbulent" market regimes compared to standard linear models.
    * Analysis of in-sample vs. out-of-sample performance to highlight forecasting limits in noisy financial environments.

## Technical Stack
* **Language:** Python
* **Libraries:** `NumPy` (matrix operations), `Pandas` (data management), `Matplotlib` (financial visualization).
* **Concepts:** Supervised Learning, Kernel Trick, Bayesian Inference, Risk Discrimination.

## Deliverables
* `MACHINE_LEARNING_PROJECT.ipynb`: Full implementation, from scratch, of the algorithms.
* `MACHINE_LEARNING_REPORT.pdf`: Theoretical depth and financial interpretation of the results.
