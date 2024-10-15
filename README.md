**Marketing Campaign Analysis using A/B Testing**

Project Overview:

This project focuses on analyzing the performance of a marketing campaign using A/B testing methodology to evaluate the impact of ad exposure on conversion rates. By applying various statistical techniques and leveraging Python libraries, the analysis aims to uncover insights that can help optimize future marketing strategies and improve conversion rates.

Objective:

The primary goal of this project is to assess whether ad exposure (time and day) significantly affects conversion rates. To achieve this, statistical tests are conducted on both categorical and continuous variables to identify patterns, trends, and significant differences between the A/B groups.

Tools & Technologies:

Python: For data processing, statistical analysis, and visualization
NumPy: Numerical computing and array manipulation
Pandas: Data manipulation and analysis
Seaborn: Data visualization
Matplotlib: Plotting and data visualization
Scikit-learn: Machine learning and statistical modeling
Jupyter Notebook: For organizing code and analysis workflow
Excel: For initial data inspection and cleaning

Methodology

1. Data Cleaning & Preparation:

Imported and cleaned the marketing campaign data, including handling missing values and standardizing data formats for consistency.

2. A/B Testing: Conducted A/B testing to compare the conversion rates across different ad exposure times (e.g., days, hours).

3. Statistical Tests:

- Chi-squared Test: Used to identify significant differences in conversion rates for categorical variables such as ad day and ad hour.
- Shapiro-Wilk Test: Assessed the normality assumption of the data.
- Levene’s Test: Evaluated the equality of variances for continuous variables.
- Mann-Whitney U Test: Confirmed statistical significance of conversion rate differences for non-normal distributions.

4. Data Visualization:

Generated visualizations, including bar charts and histograms, to illustrate the impact of ad exposure on conversion rates.

Key Findings

- Significant differences were found in conversion rates based on the day and time of ad exposure.
- Non-parametric tests showed that ad exposure led to statistically significant variations in conversion rates, validating the hypothesis that timing plays a crucial role in campaign performance.

Conclusion

The analysis provides actionable insights into how marketing campaigns can be optimized by focusing on specific days and times for ad exposure. By leveraging A/B testing and statistical techniques, the project demonstrates the importance of data-driven decision-making in marketing strategies.
