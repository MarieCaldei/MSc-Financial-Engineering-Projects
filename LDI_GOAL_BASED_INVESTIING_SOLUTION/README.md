# Liability-Driven & Goal-Based Investing: Retirement Solution Engineering

## Project Overview
This case study, conducted as part of the **LDI & GBI course at EDHEC Business School**, aims to design a customized investment solution for an individual preparing for retirement. The project moves away from standard product-based investing to a **solution-based approach**, focusing on meeting specific essential and aspirational goals.

## The Case Study: Client Profile
The objective is to engineer a strategy for a future retiree with two distinct layers of needs:
1.  **Essential Goal:** Secure a minimum level of income (floor) to guarantee a decent lifestyle throughout retirement.
2.  **Aspirational Goal:** Maximize the probability of achieving a higher target of wealth to improve their retirement standard of living.

## Technical Workflow & Implementation
The project is structured into 9 key technical sections, implementing advanced quantitative finance models:

1.  **Data Preparation:** Short-rate extraction and cleaning of yield data.
2.  **Goal-Hedging Portfolio (GHP):** Construction of a Retirement Bond using the Vasicek model to hedge interest rate risk.
3.  **Benchmark Comparison:** Evaluating the GHP against a sub-optimal constant maturity bond index.
4.  **Equity Modeling:** Simulation of risky assets using the **Heston Stochastic Volatility** model.
5.  **Performance-Seeking Portfolio (PSP):** Construction of a Factor-Based Global Minimum Variance (GMV) portfolio.
6.  **Dynamic Asset Allocation:** Implementation of **CPPI (Constant Proportion Portfolio Insurance)** to manage the trade-off between the floor and growth.
7.  **Welfare Improvement Analysis:** Comparing the customized solution against a static 60/40 benchmark.
8.  **Strategy Enhancement:** Adding a "Capped CPPI" (Bull Spread) to stabilize terminal wealth distribution.
9.  **Sensitivity Analysis:** Testing the robustness of success probabilities against different floor levels and market scenarios.

## Key Technical Skills
* **Stochastic Modeling:** Vasicek (Rates) and Heston (Equity Volatility).
* **Portfolio Engineering:** Risk Parity, GMV, and CPPI mechanisms.
* **Risk Management:** Dynamic hedging of liabilities and downside protection (floor).
* **Welfare Metrics:** Analysis of success probabilities for essential vs. aspirational goals.

## Deliverables
* `Retirement_Investment_Solution_Engineering.ipynb`: Complete Python workflow.
* `Customized_LDI_GBI_Case_Study.pdf`: Professional report detailing the investment proposal and backtest results.
