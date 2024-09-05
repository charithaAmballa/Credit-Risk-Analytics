# Credit-Risk-Analytics
Project Overview
This project focuses on predicting credit risk using machine learning models. We perform comprehensive exploratory data analysis (EDA) to understand the underlying data patterns, followed by building machine learning models to classify borrowers as high or low risk.

Table of Contents
Introduction
Dataset
Exploratory Data Analysis (EDA)
Machine Learning Models
Model Evaluation
Results
Technologies Used
Setup
Conclusion
Introduction
Credit risk analytics helps financial institutions assess the likelihood that borrowers will default on loans. The goal of this project is to develop a predictive model for credit risk based on historical loan data.

Dataset
The dataset used in this project contains information on past loans, including:

Loan Amount
Interest Rate
Term
Income
Credit Score
Loan Purpose
Loan Status (target variable: default or non-default)
You can download the dataset here.

Exploratory Data Analysis
To understand the data, we perform the following steps:

Data Cleaning: Handling missing values and outliers.
Feature Distribution: Visualizing the distributions of important features.
Correlation Analysis: Checking correlations between features and target.
Class Imbalance: Analyzing the distribution of target labels.
Key insights include:

Class imbalance where defaults are less common than non-defaults.
Strong correlation between income, credit score, and loan default.
Visualizations are provided in the notebooks/eda.ipynb file.


Setup
Prerequisites
Python 3.x
Jupyter Notebook
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/credit-risk-analytics.git
cd credit-risk-analytics
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Run the Jupyter Notebook:

bash
Copy code
jupyter notebook
Conclusion
This project demonstrates how machine learning can be used to predict credit risk, aiding financial institutions in making informed decisions. Future improvements could include using more advanced models, handling class imbalance more effectively, and integrating real-time credit risk scoring.

