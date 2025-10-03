# Customer Churn Prediction (Banking)

This project predicts customer churn using historical account and interaction data.  
It includes a Jupyter Notebook, supporting scripts for model logic, and survival analysis utilities.

## Project Contents
- **churn_pred.ipynb** — Main notebook with data exploration, feature engineering, model training, and evaluation.  
- **Customer_Churn_Prediction.py** — Core Python script for churn prediction logic.  
- **Survival_Analysis.py** — Script for retention/survival analysis (time-to-event modeling).  
- **Customer_NextTransaction_Prediction.py** — (Optional) Script for predicting next customer transaction.  
- **churn.jpg** — Visualization/diagram for presentation.  
- **requirements.txt** — List of dependencies.  
- **SPLIT_GUIDE.md** — Instructions for mapping original bundle files into this repo.  

## Features
- Data cleaning and preprocessing  
- Feature engineering for churn-related attributes  
- Models: Logistic Regression, Random Forest, Gradient Boosting (with option for XGBoost)  
- Metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC  
- Survival analysis for customer retention trends  
- Optional prediction of next transaction timing  

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook
```
Then open and run `churn_pred.ipynb`.

## Notes
- Include only anonymized sample data.  
- Optional scripts can be demonstrated for advanced analysis.  
- Full dataset links should be external for privacy/compliance.
