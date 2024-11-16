# Fraud detection model

## Data set source
The data was extracted from the Kaggle website - e-commerce fraud dataset. This is a synthetic dataset that is designed to simulate transaction data from an e-commerce platform with a focus on fraud detection. Version 1 of the data set, which has a labeled target: Is fraudulent was used in the data analysis.  
Dataset source: 
https://www.kaggle.com/datasets/shriyashjagtap/fraudulent-e-commerce-transactions?resource=download

## Dataset Overview
•	Number of Transactions: 1,472,952  
•	Features: 16  
•	Fraudulent Transactions: Approximately 5%

## Overview
This project aims to detect fraudulent transactions using machine learning techniques. It includes data preprocessing, exploratory data analysis, and model building for accurate fraud detection. The dataset contains transaction records with various features, and the goal is to classify each transaction as fraudulent or non-fraudulent.

## Workflow
1. **Data Preprocessing**
   - Handling abnormal values in the customer age
   - Feature engineering (e.g., encoding categorical variables)
   - Scaling numerical features

2. **Exploratory Data Analysis (EDA)**
   - Understanding data distribution
   - Identifying patterns related to fraudulent transactions

3. **Model Building**
   - Logistic Regression

4. **Evaluation**
   - Accuracy, precision, recall, F1-score
   - Testing hypotheses about fraud trends
  
## Key Findings
- Transactions above $2,000 are 90% likely to be fraudulent.
- New accounts have a 4% higher likelihood of being fraudulent compared to older accounts.
- The best-performing model achieved 95% accuracy in fraud detection.
