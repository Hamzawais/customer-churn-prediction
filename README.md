# 📉 Customer Churn Prediction

An end-to-end machine learning project for predicting customer churn in the banking sector using feature engineering, Random Forest feature selection, and deep learning. The project helps identify customers who are likely to leave, enabling financial institutions to take proactive retention measures.

---

## 📖 Project Overview

Customer churn is a major challenge for banks and financial institutions. Acquiring a new customer is significantly more expensive than retaining an existing one, making churn prediction an essential business problem.

This project develops a predictive analytics pipeline that analyzes customer behavior, identifies the factors influencing churn, and predicts customers who are likely to leave using machine learning techniques.

---

## 🎯 Objectives

- Analyze customer behavior.
- Perform data preprocessing and cleaning.
- Engineer meaningful predictive features.
- Identify important customer attributes.
- Train a deep learning model for churn prediction.
- Predict customer churn probability.
- Support customer retention strategies.

---

## 💼 Business Problem

Banks invest significant resources in acquiring customers, but losing existing customers directly impacts long-term revenue.

A customer churn prediction system enables organizations to:

- Identify high-risk customers.
- Improve customer retention.
- Reduce revenue loss.
- Personalize customer engagement.
- Optimize retention campaigns.

---

## 📂 Dataset

The project utilizes anonymized credit card customer data containing demographic, behavioral, and financial information.

Example features include:

- Customer Age
- Gender
- Credit Score
- Account Balance
- Transaction Activity
- Account Tenure
- Product Usage
- Customer Status

> **Note:** The original dataset is not included in this repository due to privacy and compliance considerations.

---

## 🔄 Project Workflow

```text
Customer Data
        │
        ▼
Data Cleaning
        │
        ▼
Feature Engineering
        │
        ▼
Feature Importance Analysis
        │
        ▼
Deep Learning Model
        │
        ▼
Customer Churn Prediction
        │
        ▼
Business Rules & Retention Decision
```

---

## 📊 Exploratory Data Analysis

The notebook explores customer behavior and identifies the variables that contribute most to churn prediction.

The analysis includes:

- Customer distribution
- Feature exploration
- Correlation analysis
- Feature importance visualization
- Customer behavior patterns

---

## 🔍 Feature Engineering

The project applies feature engineering and uses a **Random Forest** model to determine the most influential variables before training the prediction model.

This process improves model performance and interpretability.

---

## 🤖 Machine Learning

The solution combines traditional machine learning with deep learning.

The workflow includes:

- Data preprocessing
- Feature selection
- Random Forest feature importance
- Deep learning model training
- Customer churn prediction
- Rule-based retention assessment

---

## 📈 Business Impact

This solution can help financial institutions:

- Reduce customer churn
- Improve customer retention
- Identify high-risk customers
- Prioritize retention campaigns
- Increase Customer Lifetime Value (CLV)

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib
- Jupyter Notebook

---

## 📁 Repository Structure

```text
customer-churn-prediction/

├── notebooks/
│   └── churn_prediction.ipynb
│
├── src/
├── outputs/
├── images/
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/Hamzawais/customer-churn-prediction.git
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook and run all cells sequentially.

---

## 📈 Future Improvements

- XGBoost implementation
- Explainable AI using SHAP
- Hyperparameter optimization
- PostgreSQL integration
- Docker containerization
- Airflow pipeline automation
- Real-time churn prediction API

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Muhammad Hamza Awais**


- GitHub: https://github.com/Hamzawais
- LinkedIn: https://www.linkedin.com/in/muhammad-hamza-awais-388270300
