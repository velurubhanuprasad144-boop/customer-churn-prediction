# Customer Churn Prediction

## 📌 Project Overview
This project builds a **machine learning model** to predict **customer churn** in a telecommunications company.  
The goal is to identify customers who are likely to leave the service so that the company can take proactive steps to improve customer retention.

---

## 📊 Dataset
- **Source**: [Telco Customer Churn Dataset (Kaggle)](https://www.kaggle.com/blastchar/telco-customer-churn)  
- **Details**:  
  - ~7,000 customer records  
  - Features: demographic, account, and service details  
  - Target: `Churn` → Yes/No  

---

## ⚙️ Methodology
1. **Data Preprocessing**  
   - Dropped irrelevant column: `customerID`  
   - Handled missing values in `TotalCharges`  
   - Converted categorical features using **Label Encoding / One-Hot Encoding**  
   - Scaled numerical features for consistency  

2. **Modeling**  
   - Tried multiple ML models (Logistic Regression, Random Forest, Gradient Boosting, etc.)  
   - Tuned hyperparameters for best performance  
   - Evaluated models using classification metrics  

3. **Evaluation Metrics**  
   - Accuracy  
   - Precision, Recall, F1-score  
   - ROC-AUC  

---

## 🏆 Results
| Model                  | Accuracy | Precision | Recall | F1-score | ROC-AUC |
|-------------------------|----------|-----------|--------|----------|---------|
| Logistic Regression     | 80%      | 74%       | 70%    | 72%      | 0.82    |
| Random Forest           | 85%      | 80%       | 78%    | 79%      | 0.87    |
| Gradient Boosting (XGB) | 86%      | 82%       | 79%    | 80%      | 0.89    |

📌 *Update these values with your actual results*  
📈 Add confusion matrix, ROC curve, and precision-recall plots as images here.

---

## 🚀 How to Run
### 1. Clone the Repository
```bash
git clone https://github.com/your-username/customer-churn-prediction.git
cd customer-churn-prediction

