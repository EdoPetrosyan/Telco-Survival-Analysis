# Survival Analysis of Telecommunication Customer Churn

## Project Overview

This project focuses on analyzing customer churn in the telecommunications industry using survival analysis techniques. The goal is to identify key factors that influence churn and estimate the Customer Lifetime Value (CLV) for different customer segments. Through this analysis, we aim to provide actionable insights that can help in devising effective customer retention strategies.

## Objectives

- To understand the impact of various customer attributes on churn risk using survival models.
- To compute the Customer Lifetime Value (CLV) based on survival probabilities.
- To identify high-risk customer segments and suggest targeted interventions for retention.

## Methods Used

- **Accelerated Failure Time (AFT) Models**: Employed Log-Logistic, Log-Normal, and Weibull models to estimate the survival function and understand the tenure dynamics across different customer segments.
- **Statistical Analysis**: Analyzed the coefficients of the survival models to interpret the influence of predictors on churn.
- **Customer Lifetime Value Calculation**: Calculated CLV using model-predicted survival probabilities adjusted for discount rates, highlighting the most valuable customer segments.
- **Data Visualization**: Illustrated the findings using KDE plots to visually represent the distribution of CLV and survival probabilities across categorical variables.