# 2023 Stack Overflow Survey Data Analysis

## Overview
This project analyses the 2023 Stack Overflow survey data, featuring responses from 89,184 software engineers across 185 countries. The primary objectives are to predict developer compensation and explore factors influencing job satisfaction.

## Objectives
- **Compensation Prediction**: Utilize multilinear regression models to predict software developers' salaries.
- **Job Satisfaction Analysis**: Employ ordinal regression to understand the determinants of job satisfaction among software engineers.

## Data Source
- **Survey Dataset**: [2023 Stack Overflow Survey](https://insights.stackoverflow.com/survey)
- **Respondents**: 89,184 software engineers.
- **Geographic Scope**: 185 countries.

## Methodology
### Compensation Analysis
- **Model**: Multiple Linear Regression.
- **Variables**: Age, education, work experience, coding languages, remote work, AI usage.
- **Performance Metrics**: Root Mean Square Error (RMSE) of 1.097, R^2 of 0.14.

### Job Satisfaction Analysis
- **Model**: Ordinal Regression.
- **Key Finding**: Organizational size significantly impacts job satisfaction.
- **Statistical Insight**: Employees in smaller organizations (2-9 employees) have 2.35 times higher odds of job satisfaction compared to those in larger establishments, controlling for other variables.

## Key Insights
- **Compensation**: The multiple linear regression model effectively predicts developer salaries, although with a modest R^2 value.
- **Job Satisfaction**: Smaller organizational size correlates with higher job satisfaction levels.
- **Exploratory Data Analysis**: Reveals relationships between variables like age, education, work experience, coding languages, remote work, AI usage, and factors like compensation and job satisfaction.

## Conclusion
The analysis underscores the significance of organizational size in determining job satisfaction levels among software engineers. Additionally, the compensation prediction model provides valuable insights into salary determinants in the tech industry.

## Project Contributers
Jiayi Zhou
Annie (Xueqing) Wu
