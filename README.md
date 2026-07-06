# Customer Churn Prediction using Machine Learning

## Project Overview

This project predicts whether a telecom customer is likely to churn using machine learning classification models.

The complete machine learning pipeline includes:

- Exploratory Data Analysis (EDA)
- Data Cleaning
- Feature Engineering
- Model Training
- Model Evaluation
- Feature Scaling

---

## Dataset

**Dataset:** IBM Telco Customer Churn Dataset

- 7043 customer records
- Binary Classification
- Target Variable: **Churn**

---

## Models Used

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier

---

## Results

| Model | Accuracy |
|--------|----------|
| Logistic Regression | **82.19%** |
| Logistic Regression (StandardScaler) | **82.04%** |
| Random Forest | **78.50%** |
| Decision Tree | **71.47%** |

### Observations

- Logistic Regression achieved the highest test accuracy (~82.19%).
- Applying StandardScaler removed the convergence warning but did not significantly improve accuracy.
- Decision Tree suffered from severe overfitting (99.86% training accuracy vs 71.47% testing accuracy).
- Random Forest reduced overfitting compared to Decision Tree but did not outperform Logistic Regression on this dataset.


---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---
## Project Workflow

- Load and inspect the dataset
- Perform Exploratory Data Analysis (EDA)
- Handle missing values and correct data types
- Encode categorical variables
- Split the dataset into training and testing sets
- Train Logistic Regression, Decision Tree, and Random Forest models
- Apply feature scaling to Logistic Regression
- Compare model performance and select the best model
---

## Author

Rakshita 
- B.Tech in Mechatronics — Delhi Skill and Entrepreneurship University (DSEU)
- B.S. in Data Science and Applications — IIT Madras

