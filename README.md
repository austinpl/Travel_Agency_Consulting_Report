# Consulting Report on Remote Work Policy for Travel Agency
This project explores the effects of a remote work initiative at a Chinese travel agency, focusing on its impact on employee satisfaction, retention, and performance. Using a combination of difference-in-differences estimation and logistic regression, I analyzed data from multiple sources to assess the feasibility and effectiveness of remote work. The findings indicate significant positive effects of remote work, suggesting it leads to higher employee satisfaction, retention, and performance. Data pre-processing and thorough empirical analysis were key components of this research.

## Data Sources
The analysis utilized several datasets that included information on:
* Employee characteristics
* Performance metrics
* Employee attitudes and satisfaction levels
* Turnover records

## Data Pre-Processing
* Merging datasets from various sources.
* Removing non-sensical or missing data (e.g., negative values where impossible).
* Creating new variables for the analysis (e.g., interaction terms for difference-in-differences analysis).
* Handling missing data by replacing it with the mean or removing outliers.

## Empirical Strategies
Two primary empirical strategies were employed in the analysis:

### Difference-in-Differences (DiD) Estimation:
This approach was used to measure the causal effect of remote work by comparing changes over time between a treatment group (remote workers) and a control group (office workers).
The interaction variable between treatment and post variables captured the treatment effect on employee satisfaction and performance.

### Logistic Regression:
This model was applied to assess the impact of remote work on employee retention, a binary outcome variable. Covariates such as wage, tenure, and marital status were included to control for potential confounding factors.

## Findings
### 1. Employee Satisfaction
* Result: The DiD analysis revealed a 0.4974-unit increase in satisfaction for remote workers compared to office workers. This result was statistically significant (p-value = 0.034).
* Conclusion: Working from home has a positive impact on employee satisfaction.

### 2. Employee Retention
* Result: Logistic regression showed that remote workers were approximately 0.7726 times more likely to stay with the company than office workers. This result was highly significant (p-value = 0.005).
* Conclusion: Remote work positively influences employee retention.

### 3. Employee Performance
* Result: The DiD model indicated a 0.5643-unit increase in performance for remote workers, with a p-value of less than 0.001.
* Conclusion: Remote work improves employee performance.

## Recommendations
Based on the empirical analysis, the report strongly recommends expanding remote work policies within the company, as it leads to improved employee satisfaction, retention, and performance.

## Tools
Python, pandas, numpy, statsmodels, scikit-learn, matplotlib
