# 💳 Credit Card Risk Prediction

This project implements a machine learning model to predict credit card approval decisions and assess customer risk. utilizing **XGBoost** for high-performance classification.

## 🚀 Project Overview
Financial institutions need reliable methods to assess the creditworthiness of applicants. This project analyzes demographic and financial data to classify applicants into risk categories, helping to minimize default rates and optimize approval processes.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Data Manipulation:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Machine Learning:** XGBoost, Scikit-learn
* **Preprocessing:** Label Encoding, StandardScaler, SMOTE (Synthetic Minority Over-sampling Technique)

## 📊 Dataset Details
The analysis is based on two main datasets:
* **Application Record:** Contains personal information (Gender, Income, Education, Family Status, etc.).
* **Credit Record:** Contains the history of credit status and payment behavior.

## 🔍 Key Steps
1.  **Data Cleaning:** Handled missing values and merged datasets based on customer ID.
2.  **Exploratory Data Analysis (EDA):** Visualized income distribution, age groups, and credit status trends.
3.  **Feature Engineering:** Created a target variable based on past payment behavior (Good vs. Bad clients).
4.  **Model Training:** Trained an **XGBoost Classifier** to predict the likelihood of credit risk.
5.  **Evaluation:** Assessed model performance using Accuracy, Precision, Recall, and F1-Score.

## 📈 Results
* The model successfully identifies high-risk applicants based on their financial history.
* Key features influencing the decision include **Total Income**, **Age**, and **Years of Employment**.

## 💻 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/Credit-Card-Risk-Prediction.git](https://github.com/YOUR_USERNAME/Credit-Card-Risk-Prediction.git)
