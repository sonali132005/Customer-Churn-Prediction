# Customer-Churn-Prediction
This project aims to predict whether a customer will churn (leave the service) using machine learning techniques.

## Project Overview

Customer churn is a critical problem for businesses. In this project, a classification model is built to identify customers who are likely to churn based on their demographic and service usage data.

## 📁 Dataset

The dataset contains customer information such as:

Gender

Tenure

Contract type

Payment method

Monthly & total charges

Target variable:

Churn (Yes/No)


## 🛠️ Technologies Used

#### Python

#### Pandas

#### NumPy

#### Scikit-learn

#### Matplotlib / Seaborn

## ⚙️ Steps Performed
1.Data Cleaning

2.Exploratory Data Analysis (EDA)

3.Feature Engineering (basic encoding)

4.Handling class imbalance using SMOTE

5.Model Training (Random Forest)

6.Model Evaluation


## 🤖 Model Used
Random Forest Classifier

Reason:

-Handles non-linear relationships

-Works well with encoded categorical data

-Robust to overfitting

## Results
Accuracy: 77.7%

F1-score (Churn class): 0.58


## Confusion Matrix:

[[880 156]
 [158 215]]



 ## 📊 Key Insights
 
-Model performs well for non-churn customers

-Moderate performance in detecting churn customers

-Class imbalance impacts recall for churn


## 🧠 Learning Outcomes

-Understanding of classification problems

-Importance of data preprocessing

-Handling imbalanced datasets using SMOTE

-Model evaluation using multiple metrics
