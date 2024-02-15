## Project Description:

### Title: Predicting Insurance Claim Probability for Customers Using XGBOOST Classifier integrated into a Machine Learning Pipeline

## Overview:
The goal of this project is to develop a machine learning model that predicts the probability of an insurance claim being filed by a customer based on various demographic and vehicle-related features. By accurately predicting claim probabilities, insurance companies can better assess risk and make informed decisions about policy pricing and coverage.

## Dataset:
The dataset used for this project is "Customer_claims.csv", which contains information about customers' demographics, vehicle details, and claim history. Features include age, gender, marital status, education, occupation, income, vehicle characteristics, and historical claim amount and frequency.

## Methods:

### Data Preprocessing:

Data Cleaning: Handling missing values, converting data types, and removing unnecessary columns.

Feature Engineering: Creating new features like total number of kids and adjusting years of joining.

### ML Pipeline:

Encoding: Converting categorical variables into numerical format using one-hot encoding and ordinal encoding.

Scaling: Scaling numerical features to ensure they have the same influence on the model.

Imbalanced Data Handling: SMOTE (Synthetic Minority Over-sampling Technique) is used to address class imbalance by oversampling the minority class (claim filed) to balance the dataset.

Model Selection and Tuning: XGBoost (Extreme Gradient Boosting) classifier is chosen for its ability to handle complex datasets and provide high predictive accuracy.



### Hyperparameter :
Hyperparameter tuning is performed using GridSearchCV to optimize the model's performance.

### Evaluation: 
1) Model performance is evaluated using metrics such as ROC AUC score, confusion matrix, and classification report.
2) Cross-validation techniques are employed to ensure the model's generalization ability.

### Deployment:

The final trained model is deployed using Gradio, allowing users to input their demographic and vehicle information and receive a prediction on whether they are likely to file an insurance claim.


## Outcome:
The developed machine learning model provides insurance companies with a reliable tool for predicting claim probabilities, enabling them to mitigate risk, optimize pricing strategies, and enhance customer satisfaction.