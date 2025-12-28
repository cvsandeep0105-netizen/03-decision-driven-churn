# Customer Churn Prediction using Machine Learning

## Project Overview
Customer churn occurs when customers stop using a company’s services. Predicting churn helps businesses take proactive retention actions and improve customer lifetime value.

This project builds an end-to-end machine learning pipeline to predict customer churn using historical customer data. It includes data preprocessing, exploratory analysis, model training, evaluation, and business insights.

---

## Objectives
- Understand customer churn behavior
- Identify key churn-driving factors
- Build predictive machine learning models
- Support data-driven business decisions

---

## Models Used
- Logistic Regression (baseline, interpretable)
- Random Forest Classifier (improved performance & feature importance)

---

## Key Results
- Logistic Regression provides a strong baseline model
- Random Forest improves recall and overall accuracy
- Important churn drivers:
  - Tenure
  - Monthly charges
  - Contract type
  - Internet service
  - Payment method

---

## Repository Structure

CUSTOMER-CHURN-PREDICTION/
│
├── data/
│   └── churn_data.csv
│
├── notebooks/
│   └── customer_churn_prediction.ipynb
│
├── outputs/
│   └── (generated figures & results)
│
├── docs/
│   └── project_report.pdf
│
├── .gitignore
├── README.md
└── requirements.txt

---

## Installation & Setup

1. Clone repository
git clone https://github.com/<your-username>/customer-churn-prediction.git
cd customer-churn-prediction

2. Install dependencies
pip install -r requirements.txt

---

## How to Run the Notebook

jupyter notebook notebooks/customer_churn_prediction.ipynb

Run all cells from top to bottom.

---

## Outputs Generated
- Classification reports
- Confusion matrices
- Feature importance visualization
- Business insights on churn drivers

---

## Assumptions & Limitations
- Historical data only
- No real-time predictions
- No customer demographics
- Further tuning can improve performance

---

## Future Improvements
- Hyperparameter tuning
- Threshold optimization
- Model monitoring
- API / dashboard deployment

---

## Author
Venkata Sandeep Kumar Reddy  
Aspiring Data Scientist | Machine Learning Engineer  
