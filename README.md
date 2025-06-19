# Customer-Churn-Prediction-ML
Customer Churn Prediction using Logistic Regression -full ML pipeline with preprocessing, hyperparameter tuning, model evaluation, and insights for reducing churn.
This project implements a **Customer Churn Prediction** model using **Logistic Regression** on customer data.  
The goal is to predict whether a customer is likely to churn based on demographic, service usage, and billing features.

## Project Workflow

1. **Data Preparation**
    - Load `customer_data.csv`
    - Handle missing values
    - Drop unnecessary columns (`customerID`)
    - Encode categorical variables (One-hot encoding)

2. **Feature Engineering**
    - Convert target column: `Churn` → binary (1 = Yes, 0 = No)
    - Feature scaling not required (Logistic Regression is robust)

3. **Model Development**
    - Train-Test Split (80/20)
    - Logistic Regression (with hyperparameter tuning)
    - GridSearchCV for best parameters

4. **Model Evaluation**
    - Accuracy, Precision, Recall, F1 Score
    - Confusion Matrix
    - Classification Report

5. **Insights**
    - Feature coefficients
    - Actionable recommendations to reduce churn

## Library Used

- Python 
- pandas, numpy
- scikit-learn
- matplotlib, seaborn
- Jupyter Notebook 

## 📈 Results

| Metric         | Value  |
|----------------|--------|
| Accuracy       | 79%    |
| Precision      | 62%    |
| Recall         | 51%    |
| F1 Score       | 56%    |
