# Random Forest Classification on Loan Data

## Overview
This project applies a Random Forest classifier to loan application data to predict whether a loan will be fully repaid or charged off. The goal is to explore decision-tree-based ensemble learning and evaluate model robustness.

## Objectives
- Clean and preprocess loan data  
- Encode categorical variables  
- Train and evaluate a Random Forest model  
- Analyse feature importance to understand key predictors  

## Dataset
Loan dataset including:
- FICO score  
- Interest rate  
- Loan amount  
- Revolving balance  
- Loan status (target)

## Workflow Summary
1. **Data Cleaning**  
   - Handling missing values  
   - Encoding categorical fields  

2. **Exploratory Analysis**  
   - Distribution plots  
   - Correlation heatmaps  

3. **Model Training**  
   - RandomForestClassifier  

4. **Evaluation**  
   - Confusion Matrix  
   - Feature importance ranking  

## Results
- The model identified FICO score and interest rate as leading predictors.
- Strong performance due to ensemble averaging reducing overfitting.

## Technologies Used
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-Learn  

---

*This project was completed as part of the Python for Data Science and Machine Learning Bootcamp course on Udemy.*
