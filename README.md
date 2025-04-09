# J.P. Morgan Quantitative Research Simulation

Welcome to the **J.P. Morgan Quantitative Research Job Simulation** repository. It provides a hands-on simulation of the day-to-day tasks Quantitative Researchers (Quants) might undertake, including data analysis, model development, and risk management processes.

---

## Table of Contents

1. [Overview](#overview)  
2. [Task Objectives](#task-objectives)  
3. [Project Structure](#project-structure)  
4. [License](#license)

---

## Overview

In this simulation, you will step into the role of a Quant at J.P. Morgan to develop and refine mathematical models that support strategic decision-making. The experience includes:

- **Market Data Analysis**: Evaluating historical market trends and pricing data.
- **Statistical Modeling**: Using Python and statistical libraries to build and validate models.
- **Risk Analysis**: Understanding and quantifying various risks associated with financial instruments or strategies.
- **Communication**: Presenting your findings in a clear, concise manner—just as real Quants do when delivering insights to colleagues and clients.

---

## Task Objectives

The tasks provided in the simulation and our solutions are as follows:

- **Task 1: Investigate and analyze price data**  
  I developed an SARIMAX model to forecast the prices of natural gas prices.

- **Task 2: Price a commodity storage contract**  
  I modeled and implemented a contract pricing equation that factors various transportation and storage costs to ensure fair pricing for the client and the firm.

- **Task 3: Credit risk analysis**  
  I developed a Support Vector Classifier (SVC) to predict the probability of a client defaulting and I computed the expected loss in the event of a default.

- **Task 4: Bucket FICO scores**  
  I optimized the FICO score segmentation by maximising the total log-likelihood given a set of discrete partioning buckets.

---

## Project Structure
```
root/
├── Data
│   ├── Loan_Data.csv
│   └── Nat_Gas.csv
├── Task 1
│   └── task-1.ipynb
├── Task 2
│   └── task-2.ipynb
├── Task 3
│   └── task-3.ipynb
└── Task 4
    └── task-4.ipynb
```

## License
This project is licensed under the Apache License Version 2.0. See the [LICENSE](LICENSE) file for details.
