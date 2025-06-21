# Loan Repayment Factors Analysis

## Overview

This project, completed as part of the **MATH 1130 Final Project**, explores factors that contribute to loan repayment difficulties using a large-scale credit dataset. The analysis focuses on identifying key demographic and financial attributes that may influence whether a borrower repays their loan on time.

## Objective

The primary objective is to investigate relationships between borrower characteristics and loan repayment behavior. By applying data cleaning, exploratory data analysis (EDA), and hypothesis testing, the project aims to highlight variables that show significant influence on repayment outcomes.

## Dataset

The dataset is sourced from the [Credit EDA Case Study](https://www.kaggle.com/datasets/venkatasubramanian/credit-eda-case-study) on Kaggle and contains over 300,000 loan applications. Key features include:

- Repayment status (`TARGET`)
- Demographics (e.g., age, gender, number of children)
- Financial details (e.g., income, loan amount, annuity)
- Application timing and occupational data

## Methodology

- **Preprocessing**: Handled missing data, selected relevant variables, and transformed features for clarity (e.g., converting age from days to years).
- **EDA**: Visualized distributions and trends to understand how features relate to repayment status.
- **Statistical Testing**: Applied t-tests and correlation analyses to evaluate the significance of observed differences between repaying and defaulting borrowers.

## Key Insights

- Features such as number of children, application hour, borrower occupation, and loan-to-income ratio showed significant relationships with repayment outcomes.
- Education level and age were also examined, revealing notable trends in repayment success rates.
- While some correlations were weak, consistent patterns emerged across multiple analyses.

## Tools Used

- Python  
- Libraries: `pandas`, `numpy`, `seaborn`, `matplotlib`, `scipy`, `statsmodels`

## Conclusion

After conducting exploratory data analysis on various financial and demographic indicators, several key factors influencing the inability to repay loans were identified. These include the borrower's number of children, the timing of loan applications, occupation type, age, total loan amount, and the proportion of the loan relative to income.

In conclusion, the analysis highlights a range of variables that contribute to repayment behavior, offering valuable insights for future risk assessments and credit evaluations. The findings can serve as a foundation for more advanced predictive modeling in financial services.
