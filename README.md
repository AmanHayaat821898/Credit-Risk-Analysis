# Loan Default Prediction

## Overview
This project aims to analyze loan data to understand the impact of various features on credit risk and to predict the risk associated with loans. The ultimate goal is to assist banks and investors in making informed decisions by assessing the likelihood of a borrower defaulting on a loan.

## Problem Statement
We aim to create a model that can predict whether a borrower will default on their loan. This helps creditors minimize losses by evaluating the risk before extending a loan. Defaults can cause significant financial losses, and predicting them accurately is crucial for risk management.

## Data
The dataset used in this project contains 75 columns and 466,285 rows, including features such as annual income, loan amount, debt-to-income ratio, revolving utilization, employment length, and FICO scores.

## Methodology
1. **Data Understanding**: Comprehensive analysis to understand the distributions and relationships between features.
2. **Data Cleaning**: Handling outliers, missing values, and noise to ensure data quality.
3. **Data Exploration**: Detailed exploration to identify important features and relationships.
4. **Data Preparation**: Binning numerical data and transforming features using Weight of Evidence (WOE) and calculating Information Value (IV).
5. **Model Building**: Testing various models including Logistic Regression, Decision Tree, and Naive Bayes.
6. **Balancing the Dataset**: Using resampling techniques to address the imbalance in the target variable.
7. **Hyperparameter Tuning**: Optimizing the Decision Tree model for best performance.

## Models and Results
- **Logistic Regression**: Used as a baseline model.
- **Decision Tree**: After hyperparameter tuning, it achieved the best performance with an accuracy of 0.82 and an AUC score of 0.93.
- **Naive Bayes**: Provided for comparison.

The Decision Tree model was selected based on its superior performance after hyperparameter tuning.

## Key Findings
- Important features affecting loan default include annual income, loan amount, debt-to-income ratio, revolving utilization, employment length, and FICO scores.
- The Decision Tree model, after tuning, provides a reliable tool for predicting loan default risk.

## Practical Implications
- **For Lenders and Investors**: The model helps in making informed decisions about loan approvals, reducing the risk of financial losses.
- **Future Work**: Further improvements can be made by exploring advanced techniques and incorporating additional data sources.

## Getting Started
### Prerequisites
- Python 3.6 or higher
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Credit-Risk-Analysis.git
   cd Credit-Risk-Analysis
