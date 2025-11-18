# SWAN Project - Customer Churn Prediction

This project develops a machine learning solution to predict which
customers of Swan Telecom are most likely to churn. Identifying
high risk customers early enables the company to target retention
efforts more effectively.

## Notebooks

### EDA Notebook.ipynb

-   Performs exploratory data analysis (EDA) on `project_data.csv`
-   Examines data quality, distributions, correlations
-   Creates visualisations to uncover key churn drivers and trends

### Feature Engineering, Split, Modelling Model Evaluation.ipynb

-   Uses `project_data.csv` to engineer features for modelling
-   Splits the dataset into training and test sets
-   Builds Random Forest and Logistic Regression models to predict churn
    likelihood
-   Evaluates model performance using metrics such as accuracy,
    precision/recall, and ROC-AUC
-   Generates churn predictions for all customers

## Output Files

### all_customers_rf_full CSV.csv

-   Contains predicted churn probabilities for all customers based on
    the trained Random Forest model.

### top500_churn_risk_rf_full CSV.csv

-   Contains the top 500 customers with the highest churn risk scores.
-   Intended for targeted retention strategies.

## Reports and Presentation Material

### SWAN Telecom Churn Prediction Summary.pdf

-   A written summary of the analysis, modelling approach, key findings,
    and recommendations.

### Swan do attitude - slides.pptx

-   Slide deck used to present results and insights to company
    stakeholders.

## Project Goal

The goal of this project is to predict the likelihood of customer churn
using Swan Telecom's historical customer data. The models produced help
the business proactively identify customers at high risk of churn and
inform targeted retention actions.
