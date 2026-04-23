# Liability-Driven & Goal-Based Investing: Retirement Solution Engineering

## Project Overview
This project, developed as part of the **LDI & GBI course at EDHEC Business School**, aims to design a customized investment solution for an individual preparing for retirement. The project implements a **solution-based approach**, focusing on meeting specific essential and aspirational goals through dynamic asset allocation.

## The Case Study: Client Profile (James)
The objective was to engineer a strategy for a 45-year-old individual ("James") with a 20-year investment horizon (retirement at age 65) and a specific wealth profile:

* **Initial Wealth:** $500,000.
* **Essential Goal (The Floor):** Secure a minimum annual income of **$40,000** (inflation-linked) for 20 years during retirement. This goal must be hedged at 100% via the Goal-Hedging Portfolio (GHP).
* **Aspirational Goal:** Aim for a target annual income of **$70,000**. The strategy seeks to maximize the probability of reaching this target through the Performance-Seeking Portfolio (PSP).
* **Constraint:** A strict **"Safety First"** mechanism where wealth must never fall below the present value of the essential floor.

## Technical Workflow & Implementation
The implementation is structured into 9 key technical sections:

1.  **Data Preparation:** Short-rate extraction and cleaning of yield data.
2.  **Goal-Hedging Portfolio (GHP):** Construction of a "Retirement Bond" using the **Vasicek model** to hedge interest rate risk over 20 years.
3.  **Benchmark Comparison:** Evaluating the GHP against a sub-optimal constant maturity bond index.
4.  **Equity Modeling:** Simulation of risky assets using the **Heston Stochastic Volatility** model to capture market realism.
5.  **Performance-Seeking Portfolio (PSP):** Construction of a Factor-Based **Global Minimum Variance (GMV)** portfolio for optimized growth.
6.  **Dynamic Asset Allocation:** Implementation of **CPPI (Constant Proportion Portfolio Insurance)** to manage the exposure between the floor and the growth assets.
7.  **Welfare Improvement Analysis:** Comparative study of the customized solution against a static 60/40 benchmark.
8.  **Strategy Enhancement:** Adding a **"Capped CPPI" (Bull Spread)** to stabilize terminal wealth distribution and remove unnecessary extreme upside.
9.  **Sensitivity Analysis:** Testing success probabilities ($P_{essential}$ and $P_{aspirational}$) against different floor levels and market scenarios.

## Authors
* **Marie Caldeireiro** - MSc in Financial Engineering, EDHEC Business School
* **Audric Cerqueira Fernandes** - MSc in Financial Engineering, EDHEC Business School

## Deliverables
* `Retirement_Investment_Solution_Engineering.ipynb`: Complete Python workflow and simulations.
* `Customized_LDI_GBI_Case_Study.pdf`: Professional report detailing the investment proposal and welfare analysis.
