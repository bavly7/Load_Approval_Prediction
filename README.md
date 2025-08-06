# Loan Approval Prediction Project

## Project Overview
This project analyzes loan application data to predict approval outcomes using machine learning. The dataset contains features like applicant income, credit score, education level, and asset values.

## Key Features
- **Data Analysis**: Explored class imbalance (2120 approved vs 1295 rejected)
- **Model Comparison**: Evaluated Random Forest, Logistic Regression, Decision Tree, and KNN
- **SMOTE Implementation**: Demonstrated class balancing technique (task requirement)

## Results
Without addressing imbalance:
- Best model: **Random Forest** (99% accuracy)
- Key predictive features: 
  1. Credit Score (cibil_score)
  2. Annual Income (income_annum)
  3. Loan Amount

## Technical Details
```python
# Package versions used
scikit-learn==1.2.2
imbalanced-learn==0.10.1
numpy==1.23.5
pandas==2.0.3
