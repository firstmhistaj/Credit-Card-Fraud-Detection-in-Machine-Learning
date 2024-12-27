# Credit Card Fraud Detection Using Machine Learning

## Introduction
Credit card fraud has grown to be a serious concern for both consumers and businesses in the digital era. With increasing fraud cases globally, machine learning offers an advanced solution to detect fraudulent transactions effectively.

### Global Impact
- **114,348** reported cases of credit card fraud in 2023.
- **US$28.65 billion** lost to credit card fraud in 2021.
- Fraud cases are particularly challenging with online and card-not-present transactions.

### Importance of Machine Learning
Traditional rule-based techniques are insufficient to detect modern fraud schemes. This project utilizes machine learning models to improve fraud detection by analyzing transaction data to spot subtle patterns and anomalies.

## Dataset Overview
The dataset used for this project contains **284,807 transactions** from European cardholders, recorded over a 2-day period. Only **492** of these transactions are fraudulent, resulting in an **imbalanced dataset**.

- **Features**: 28 numerical features (anonymized), 2 non-anonymized features (Time and Amount).
- **Target**: Class (1 = Fraud, 0 = Non-Fraud).

## Tools and Libraries Used
- **Pandas** for data manipulation.
- **NumPy** for numerical operations.
- **Scikit-learn** for machine learning algorithms and preprocessing.
- **Matplotlib and Seaborn** for data visualization.

## Model Design
Models used include:
- **Logistic Regression**
- **Random Forest**
- **Decision Tree**
- **XGBoost**

Techniques like **SMOTE**, **Random Oversampling**, and **Undersampling** were applied to handle class imbalance.

## Installation
Clone this repository and install the required dependencies using:

```bash
git clone https://github.com/firstmhistaj/Credit-Card-Fraud-Detection-in-Machine-Learning.git
cd Credit-Card-Fraud-Detection-in-Machine-Learning
pip install -r requirements.txt
