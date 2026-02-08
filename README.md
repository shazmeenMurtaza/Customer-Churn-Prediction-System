# Customer Churn Prediction System

This is a **Customer Churn Prediction System** built using **Machine Learning (XGBoost)** and deployed as an interactive **Streamlit web application**. The system predicts whether a customer is likely to churn (leave the service) or stay, providing confidence scores, risk levels, and actionable recommendations.

---

## Features

- Predict if a customer will **churn** or **stay**  
- Shows **prediction confidence** and **risk level**  
- **Interactive web interface** built with Streamlit  
- **Visual insights** using Plotly charts  
- Provides **retention suggestions** based on prediction results  

---

## Input Data

The model uses three main types of customer information:

1. **Demographics**  
   - Gender, Senior Citizen status, Partner, Dependents  

2. **Services Usage**  
   - Phone Service, Internet Service, Online Security, Online Backup, Device Protection, Tech Support, Streaming TV, Streaming Movies  

3. **Account Information**  
   - Tenure, Contract Type, Payment Method, Paperless Billing, Monthly Charges, Total Charges  

---

## Machine Learning Model

- **Algorithm:** XGBoost Classifier  
- **Accuracy:** ~77% on test dataset  
- **Training Data:** 7,043 customer records  
- **Handling Imbalance:** SMOTE  
- **Categorical Encoding:** Label encoding for categorical features  

**Why XGBoost?**  
- High accuracy and robust performance  
- Handles complex patterns efficiently  
- Reduces overfitting  
- Industry-standard for churn prediction  

---

## Tech Stack

- Python  
- Scikit-learn  
- XGBoost  
- Streamlit  
- Pandas & NumPy  
- Plotly  
- Joblib  

---

## Installation & Setup

1. Clone the repository:

```bash
git clone https://github.com/yourusername/customer-churn-prediction.git
cd customer-churn-prediction
