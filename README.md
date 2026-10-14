# Working Hours and Life Satisfaction: Evidence from ESS Round 10

## Project Overview

This project explores the relationship between weekly working hours and life satisfaction using data from the European Social Survey (ESS) Round 10. The analysis examines working patterns and investigates how working hours and demographic, economic, health, and social factors are associated with life satisfaction.

## Research Question

How are weekly working hours associated with life satisfaction?

## Dataset and Permissions

The data are from the European Social Survey (ESS) Round 10. The original dataset contains 37,611 respondents, and the main complete-case regression analysis includes 18,690 respondents.

Data can be accessed through the official European Social Survey data portal. The original respondent-level dataset is not included in this repository. Users should follow the applicable ESS data access and usage conditions.

## Methods and Tools

The analysis was conducted using Python, with Pandas, NumPy, Matplotlib, SciPy, and Statsmodels.

Methods include data cleaning, descriptive statistics, correlation analysis, data visualization, Ordinary Least Squares (OLS) regression, and Ordered Probit regression.

## Key Findings

- Weekly working hours were concentrated around 40 hours, with an average of approximately 39.6 hours in the main analytical sample.
- In the fully adjusted OLS model, working hours were negatively associated with life satisfaction, although the estimated association was small (β ≈ −0.004 per additional hour, p < .001).
- Health, income, social inclusion, and social trust were also positively associated with life satisfaction in the adjusted analysis.

These findings indicate associations rather than causal effects.

## Visualizations

**Figure 1: Distribution of Weekly Working Hours**

A histogram illustrates the distribution of working hours among respondents. The visualization focuses on working hours up to 80 per week, while higher values remain included in the main statistical analyses.

**Figure 2: Adjusted Associations with Life Satisfaction**

A regression coefficient plot presents the estimated associations between explanatory variables and life satisfaction, with 95% confidence intervals.

Both figures are available as image files in this repository.

## How to Reproduce the Analysis

1. Download the ESS Round 10 dataset through the official ESS data portal.
2. Save the CSV dataset as `ESS10e03_3.csv` in the same folder as `ESS10_analysis.ipynb`.
3. Install the required Python libraries using `pip install -r requirements.txt`.
4. Open the Jupyter Notebook and execute the ESS Round 10 analysis sections in order.

Note: The final optional ESS Round 11 comparison cells require additional summary files and are not necessary for reproducing the main ESS Round 10 analysis.

## Limitations

This study uses cross-sectional observational data, which do not establish causality. Complete-case analysis may introduce selection bias, and the OLS analysis does not explicitly account for the complex survey design. Additional longitudinal analyses could help explore these relationships further.

## Project Status

Completed ESS Round 10 analysis with documentation and
