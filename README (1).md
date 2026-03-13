
# Customer Churn Prediction using Machine Learning

Project Overview

Customer churn is a major challenge for businesses because losing customers directly impacts revenue. This project predicts whether a customer will churn (leave the company) or not based on customer attributes.

The model analyzes customer data and provides predictions using machine learning algorithms. An interactive Streamlit application allows users to input customer details and get instant predictions.


## Problem Statement

The objective of this project is to predict customer churn using machine learning techniques based on customer features such as:

* Age

* Gender

* Tenure

Monthly Charges

This helps businesses identify customers who are likely to leave and take preventive actions to improve customer retention.
## Dataset

Dataset Source: Kaggle

Dataset Name: Customer Churn Prediction: Analysis

* Dataset Information:

* Number of Rows: 1000

* Number of Columns: 9

The dataset contains customer information that helps in predicting whether a customer will churn or stay.
## Technologies Used

* Python

* NumPy

* Pandas

* Scikit-learn

* Matplotlib

* Streamlit

* Joblib
## Machine Learning Models Used


Multiple machine learning models were trained and tuned using GridSearchCV for hyperparameter optimization.

* The following models were tested:

* Logistic Regression

* K-Nearest Neighbors (KNN)

* Support Vector Classifier (SVC)

* Decision Tree Classifier

* Random Forest Classifier
## Model Performance

| Model               | Accuracy  |
| ------------------- | --------- |
| Logistic Regression | 88%       |
| KNN (GridSearchCV)  | **88.5%** |
| SVC                 | 88.5%     |
| Decision Tree       | 83.5%     |
| Random Forest       | 85.5%     |


Best Model: K-Nearest Neighbors (KNN) using GridSearchCV
Best Accuracy: 88.5%
## Skills Demonstrated

* Data Cleaning and Preprocessing

* Exploratory Data Analysis (EDA)

* Machine Learning Model Training

* Hyperparameter Tuning using GridSearchCV

* Model Evaluation and Comparison

* Building an Interactive Web Application using Streamlit



## How to Run the Project

Run the following command in the terminal:

streamlit run app.py

The application will start on localhost and open in your browser.