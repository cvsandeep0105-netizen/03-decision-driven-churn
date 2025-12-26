# 📊 Decision-Driven Customer Churn Analysis

## 📌 Project Overview
This project analyzes customer churn in a telecom company using machine learning and converts predictive results into clear, actionable business decisions.  
The focus is on interpretability, business impact, and decision support rather than only model accuracy.

---

## 🎯 Objective
- Predict customer churn  
- Identify key churn drivers  
- Provide business-ready recommendations to reduce churn  

---

## 📂 Dataset
- Telco Customer Churn Dataset (IBM / Kaggle)
- ~7,000 customer records
- Target variable: Churn

---

## 🧪 Methodology

1. Data Cleaning & Preprocessing  
2. Feature Engineering  
3. Train-Test Split  
4. Feature Scaling  
5. Model Training (Logistic Regression – Balanced Classes)  
6. Model Evaluation (Accuracy, Confusion Matrix, ROC–AUC)  
7. Business Insight Extraction
---

## 🤖 Model
- Algorithm: Logistic Regression  
- Reason: High interpretability and strong baseline performance for business problems  

---

## 📈 Model Performance
- Train Accuracy: ~75%  
- Test Accuracy: ~72%  
- Balanced handling of churn and non-churn classes  

### 📈 ROC–AUC Evaluation

To evaluate the model’s ability to distinguish between churn and non-churn customers,  
ROC–AUC score and ROC curve were used.

- **ROC–AUC Score:** 0.83  
- The ROC curve shows strong class separation performance.
- This confirms the model is suitable for business decision-making beyond accuracy.

> ROC–AUC is especially important for imbalanced datasets like customer churn.

---

## 🔑 Key Insights
- Fiber-optic customers show higher churn probability  
- Customers with high total charges are more likely to leave  
- Streaming service users have increased churn risk  
- Senior citizens and customers with dependents show higher loyalty  

---

## 💡 Business Recommendations
- Improve pricing and service quality for fiber-optic users  
- Introduce loyalty discounts for high-value customers  
- Bundle streaming services at competitive prices  
- Focus retention strategies on families and senior citizens  

---

## 🗂 Project Structure

03-decision-driven-churn/
│
├── data/
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
│
├── notebooks/
│   └── Project_3_Decision_Driven_Customer_Churn_Analysis.ipynb
│
├── README.md
└── .gitignore

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/03-decision-driven-churn.git

 ##  Navigate to the project folder: 
 cd 03-decision-driven-churn

 ## Install required libraries:
 pip install pandas numpy scikit-learn matplotlib seaborn

 ## Open the notebook:
 jupyter notebook notebooks/Project_3_Decision_Driven_Customer_Churn_Analysis.ipynb

 

### 🔧 Change 2: Add a 2-line “Conclusion” (final polish)
Add **just before Project Structure** or **before Status**:

```md
## 🏁 Conclusion

This project demonstrates how machine learning can be translated into
clear, data-driven business decisions for customer retention strategies.
The focus on interpretability ensures trust and adoption in real-world environments.


---

## 🛠 Tools & Libraries
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Jupyter Notebook  

---

## 👤 Author
**Sandeep Reddy**

---

## ✅ Status
✔ Completed  
✔ Business-ready  
✔ Interview-ready
