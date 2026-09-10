# Telco Customer Churn Analysis

## Overview

Customer churn is an important business problem because losing existing customers can negatively affect revenue and long-term customer relationships.

This project explores customer churn using demographic, service, contract, payment, and billing data. The analysis aims to identify customer segments and characteristics associated with higher churn rates and translate these findings into potential business recommendations.

## Objectives

- Understand the overall customer churn rate
- Explore churn patterns across customer segments
- Analyze the relationship between churn, tenure, and charges
- Identify characteristics associated with higher churn
- Develop data-driven customer retention recommendations

## Dataset

The dataset contains customer-level information from a telecommunications company.

It includes:

- Customer demographics
- Service subscriptions
- Contract information
- Payment methods
- Customer tenure
- Monthly and total charges
- Churn status

The dataset contains **7,043 customer records and 21 variables**.

## Tools & Technologies

- Python
- Pandas
- Matplotlib
- Google Colab
- Jupyter Notebook

## Analysis

The project includes:

1. Data cleaning and preprocessing
2. Churn rate analysis
3. Categorical variable analysis
4. Numerical variable analysis
5. Correlation analysis
6. Business interpretation
7. Customer retention recommendations

## Key Findings

### 1. Contract Type

Month-to-month customers have a substantially higher churn rate (**42.71%**) than customers with one-year (**11.27%**) or two-year contracts (**2.83%**).

### 2. Customer Tenure

Churned customers have a considerably shorter average tenure (**17.98 months**) than retained customers (**37.57 months**).

### 3. Technical Support & Online Security

Customers without technical support or online security show substantially higher churn rates than customers using these services.

### 4. Payment Method

Electronic-check users have the highest churn rate among payment-method groups (**45.29%**).

### 5. Monthly Charges

Churned customers have higher average monthly charges (**$74.44**) than retained customers (**$61.27**).

## Business Recommendations

Based on the exploratory analysis, potential actions include:

- Encourage month-to-month customers to adopt longer-term contracts through targeted incentives.
- Develop early-stage customer onboarding and retention campaigns.
- Increase awareness and accessibility of technical support and online security services.
- Investigate the customer experience of electronic-check users.
- Further examine pricing and perceived service value among high-charge customers.

## Limitations

- The analysis identifies associations but does not establish causal relationships.
- The analysis is based on a single dataset.
- The project focuses on exploratory analysis rather than predictive modeling.
- Further statistical testing and predictive modeling could provide additional evidence.

## Project Structure

```text
telco-customer-churn-analysis/
│
├── README.md
├── Telco_Customer_Churn_Analysis.ipynb
├── Telco-Customer-Churn.csv
└── figures/

## Conclusion

The analysis identifies several customer characteristics associated with higher churn, particularly month-to-month contracts, shorter tenure, lack of selected support services, electronic-check payment, and higher monthly charges.

These findings provide potential directions for customer retention strategies and demonstrate how exploratory data analysis can support business decision-making.
