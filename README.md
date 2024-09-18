# Bank Loan Data: Exploratory Data Analysis to Identify Defaulters

This project involves performing an Exploratory Data Analysis (EDA) on a bank loan dataset to identify patterns and correlations associated with loan defaulters. The goal is to gain insights that could help in predicting and managing potential loan defaults.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Objective](#objective)
- [Tech Stack](#tech-stack)
- [Analysis Steps](#analysis-steps)
- [Results and Findings](#results-and-findings)
- [Conclusion](#conclusion)
- [Notes](#notes)

## Introduction

In this project, we analyze a dataset containing information about bank customers and their loan details. The primary objective is to identify key factors that contribute to loan defaults and to explore the relationships between various features and the likelihood of default.

## Dataset

- **Source:** [Dataset source or description]
- **Features:** 
  - `AMT_INCOME_TOTAL`: Total income of the customer.
  - `AMT_CREDIT`: Total amount of credit granted.
  - `AMT_ANNUITY`: Annuity of the loan.
  - `AMT_GOODS_PRICE`: Price of the goods associated with the loan.
  - `DAYS_BIRTH`: Age of the customer (in days).
  - `DAYS_EMPLOYED`: Number of days the customer has been employed.
  - `TARGET`: 0 - Non-defaulter, 1 - Defaulter.

## Objective

The primary objectives of this EDA are:
1. To understand the distribution and relationships of key features in the dataset.
2. To identify patterns and correlations associated with loan defaults.
3. To provide insights that can help in building predictive models for loan default risk.

## Tech Stack

- **Python**: Programming language used for analysis.
- **Libraries**: 
  - `Pandas`: Data manipulation and analysis.
  - `NumPy`: Numerical computing.
  - `Matplotlib` and `Seaborn`: Data visualization.
  - `Scikit-learn`: Machine learning tools for analysis.

## Analysis Steps

1. **Data Loading and Cleaning**:
   - Load the dataset and inspect for missing values, outliers, and inconsistencies.
   - Perform necessary data cleaning, such as handling missing values and correcting data types.

2. **Univariate Analysis**:
   - Analyze the distribution of individual features, particularly focusing on numerical and categorical variables.
   - Visualize the distribution of the target variable (`TARGET`).

3. **Bivariate Analysis**:
   - Explore relationships between pairs of variables (e.g., `AMT_INCOME_TOTAL` vs. `TARGET`).
   - Use scatter plots, correlation matrices, and other visualization techniques.

4. **Multivariate Analysis**:
   - Identify correlations and patterns among multiple variables simultaneously.
   - Use techniques like pair plots and heatmaps to visualize these relationships.

5. **Insights and Observations**:
   - Summarize the key findings from the analysis.
   - Highlight any significant correlations or trends related to loan defaults.

## Results and Findings

- **Details are presented in PPT**

## Conclusion

The EDA revealed several key factors that are strongly associated with loan defaults, such as low income, Work type etc. These insights can be used to enhance predictive models for identifying potential defaulters, thereby improving the bank's risk management strategies.

## Notes

- All output cells in the Jupyter Notebook have been cleared to comply with GitHub's 25MB file size limit. Please rerun the notebook to see the visualizations and results.
