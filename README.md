# Edunet_ML_Project

## Overview
This project applies machine learning techniques to detect fraudulent transactions in credit card datasets. It includes data preprocessing, exploratory data analysis (EDA), model training using a Random Forest classifier, and model evaluation.

## Problem Statement
Credit card fraud is a major concern in the financial sector, causing significant monetary losses. The challenge is to accurately detect fraudulent transactions while minimizing false positives. This project aims to develop a machine learning model that efficiently classifies transactions as fraudulent or genuine, improving security measures for financial institutions.

## Objectives
- **Data Preprocessing & Cleaning:** Handle missing values and prepare data for analysis.
- **Exploratory Data Analysis (EDA):** Identify fraud patterns based on transaction attributes.
- **Model Development & Training:** Train a supervised learning model to classify transactions.
- **Performance Evaluation & Insights:** Assess model accuracy and optimize fraud detection.

## Dataset
- **Source:** Credit Card Fraud Detection dataset from Kaggle.
- **Preprocessing Steps:**
  - Imputation of missing values.
  - Categorical encoding of non-numeric variables.
  - Feature scaling for numerical features.

## Methodology
1. **Data Preprocessing:**
   - Handle missing values.
   - Convert categorical variables into numerical format.
   - Normalize numerical features for better model performance.
2. **Model Training:**
   - Train a Random Forest classifier to detect fraud.
3. **Model Evaluation:**
   - Evaluate performance using accuracy, confusion matrix, and classification report.

## Model Performance
- **Model Used:** Random Forest Classifier
- **Accuracy Achieved:** ~95%
- **Evaluation Metrics:**
  - Precision, Recall, F1-score
  - Confusion Matrix

## Future Scope
- Enhance feature engineering to improve fraud detection.
- Explore advanced ML models like XGBoost and Neural Networks.
- Integrate real-time fraud detection systems with banking APIs.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/AyushGaikwad05/Edunet_ML_Project.git
   cd Credit-Card-Fraud-Detection

2. Install dependencies:
   ```bash
   pip install -r requirements.txt

3. Run thr Jupyter Notebook:
   ``` bash
   jupyter notebook
##
```bash 
Credit-Card-Fraud-Detection/
│── data/
│   ├── credit_card_fraud.csv
│── notebooks/
│   ├── Credit_Card_Fraud_Detection.ipynb
│── src/
│   ├── preprocessing.py  # (Optional: Data processing scripts)
│   ├── model_training.py  # (Optional: Model training script)
│── images/  # (For screenshots or visualizations)
│── README.md
│── requirements.txt
│── creditcarddetection.pptx
│── .gitignore
