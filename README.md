# Simple Linear Regression Analysis

This project performs a simple linear regression analysis to understand the relationship between two variables - 'read' (independent) and 'write' (dependent) - using the hsb2 dataset.

## Files

- `linear_regression.py`: Python script with code to import data, fit linear regression model, and print results
- `hsb2.csv`: Dataset with read and write variables
- `output.txt`: Text output from running linear regression code

## Analysis 

The linear regression analysis aims to model the relationship between students' reading scores ('read') and their writing scores ('write'). It tests if 'read' has a significant correlation with and effect on 'write'.

The Python script fits an Ordinary Least Squares linear model using the Statsmodels library. Key outputs include:

- Model coefficients, standard errors, t-stats, p-values
- Overall model fit and significance 
- R-squared, adjusted R-squared
- Diagnostic tests on residuals

## Results

The output suggests a statistically significant positive correlation between 'read' and 'write'. The model explains 35.6% of variance in the dependent variable.

The positive coefficient for 'read' indicates that as reading scores increase, writing scores also tend to increase. This quantifies the effect of 'read' on 'write'.

## Future Work

Additional variables could be incorporated to potentially improve model fit. Interactions between variables could also be explored.

Overall, this simple linear regression analysis establishes a baseline predictive relationship and statistical tests to build on with more advanced modeling.
