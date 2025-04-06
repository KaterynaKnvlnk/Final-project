
Stroke Risk Factors Analysis Project

Project Overview

This project explores medical data to identify key risk factors associated with stroke. The dataset includes patient attributes such as age, gender, hypertension, heart disease, smoking status, work type, glucose level, BMI, and stroke history.
The analysis is conducted using Python and Jupyter Notebook and includes statistical testing, visualizations, and practical recommendations.

Context & Dataset Description

According to the World Health Organization (WHO), stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths.
This dataset is used to predict the likelihood of stroke in patients based on input features like gender, age, diseases, and smoking status. Each row provides relevant information about a patient.

Attribute Information:

1. id — unique identifier
2. gender — "Male", "Female" or "Other"
3. age — patient age
4. hypertension — 0 = no hypertension, 1 = has hypertension
5. heart_disease — 0 = no heart disease, 1 = has heart disease
6. ever_married — "No" or "Yes"
7. work_type — "children", "Govt_job", "Never_worked", "Private", "Self-employed"
8. Residence_type — "Rural" or "Urban"
9. avg_glucose_level — average glucose level
10. bmi — body mass index
11. smoking_status — "formerly smoked", "never smoked", "smokes", "Unknown"
12. stroke — 1 = stroke occurred, 0 = no stroke

*Note: "Unknown" in smoking_status means that information was not available for that patient.
Source: https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset

Project Objectives:

- Analyze demographic and health-related features that influence stroke occurrence
- Visualize trends and group differences
- Conduct statistical hypothesis testing (t-tests, chi-square tests)
- Derive actionable insights and risk factors

Tools & Libraries:

- Python 3
- pandas, numpy – data manipulation
- matplotlib, seaborn – visualizations
- scipy.stats, statsmodels – statistical testing
- Jupyter Notebook

Key Analyses:

- Gender, age, and marital status distribution of stroke cases
- Stroke rates by hypertension, heart disease, smoking, and glucose level
- Percentage of strokes across work types and residence types
- Chi-square tests for categorical variables
- T-tests for age, BMI, and glucose level comparison

Main Insights:

- People with hypertension and/or heart disease are 3–5x more likely to have a stroke
- Older age significantly increases stroke risk (p < 0.001)
- Smoking status is statistically associated with stroke occurrence
- Self-employed individuals show the highest stroke rate among work types
- Women, especially those who are or were married, show a slightly higher stroke percentage
- Residence type (urban/rural) has no statistically significant impact on stroke risk

Recommendations:

- Focus prevention on elderly patients with chronic health issues
- Target former and current smokers with awareness programs
- Include older women and self-employed individuals in at-risk groups
- Use machine learning models for early stroke risk prediction
