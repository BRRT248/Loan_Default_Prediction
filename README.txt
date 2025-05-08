# Predictive Modelling – Loan Default Prediction

This project builds a logistic regression model to predict whether a loan will default based on applicant features like income, age, and loan amount. The goal is to demonstrate a simple predictive modeling workflow using synthetic data.

## Dataset

A synthetic dataset with the following columns:
- `income`: Annual income of the applicant
- `age`: Age of the applicant
- `loan_amount`: Loan amount requested
- `defaulted`: Whether the loan defaulted (1 = defaulted, 0 = repaid)

## Workflow

- Loaded dataset into pandas DataFrame
- Performed exploratory data analysis (EDA) with summary statistics and visualizations
- Prepared features and target variable
- Split data into training and testing sets
- Trained a logistic regression model
- Evaluated model using confusion matrix, classification report, and ROC AUC

## Example Results

The model achieved an ROC AUC score of approximately 0.75 (may vary based on dataset generation).

## Tools Used

- Python
- pandas
- matplotlib
- scikit-learn
- Jupyter Notebook

## Next Steps

- Try more complex models (e.g., Random Forest, XGBoost)
- Incorporate additional features (e.g., credit score, employment history)
- Perform hyperparameter tuning


