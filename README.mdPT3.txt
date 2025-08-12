# Bank Marketing ML Project

## Project Overview
This project uses machine learning models to predict whether a client will subscribe to a term deposit based on bank marketing data. Various models including Logistic Regression, K-Nearest Neighbors, Decision Tree, and Linear SVM are implemented, tuned, and evaluated.

## Dataset
The dataset includes client information, campaign details, and socio-economic indicators. The target variable is whether the client subscribed to a term deposit (`yes` or `no`).

## Features
- Numeric features: age, campaign, pdays, previous, emp.var.rate, cons.price.idx, cons.conf.idx, euribor3m, nr.employed  
- Categorical features: job, marital, education, default, housing, loan, contact, month, day_of_week, poutcome  
- Note: The `duration` feature is excluded from modeling because it leaks future information.

## How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/ahmetakdeniz33/name.git
Install dependencies (recommended to use a virtual environment):

bash
Copy
Edit
pip install -r requirements.txt
Run the Jupyter notebooks or Python scripts provided.

##Models and Tuning
Models used: Logistic Regression, KNN, Decision Tree, Linear SVM

Hyperparameters tuned using Grid Search and Randomized SearchCV

Performance metrics reported: Accuracy, Precision, Recall, F1 Score

##Results Summary
The project compares model performance to select the best approach.

Hyperparameter tuning improves model accuracy and generalization.

Author
AHMET AKDENIZ

Acknowledgments
Dataset sourced from UCI Machine Learning Repository - Bank Marketing Dataset