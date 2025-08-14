# student_repayment_loan
This project predicts whether a bank should approve a loan for an applicant based on financial and credit-related factors, using various Ensemble Learning methods. The goal is to assist in risk assessment and decision-making for loan approvals.

# 📊 Loan Repayment Prediction Using Ensemble Learning  

## 📌 Overview  
This project predicts whether a bank should approve a loan for an applicant based on their credit and financial details, using **Ensemble Learning** techniques. The aim is to assist financial institutions in reducing default risks and making data-driven lending decisions.  

The best-performing model in this project — **Random Forest Classifier** — achieved an accuracy of **~85%**.  

---

## 🚀 Features  
- **Data Preprocessing**  
  - Label Encoding for categorical variables  
  - Null value checks and handling  
  - Data scaling  
- **Exploratory Data Analysis (EDA)**  
  - Distribution of FICO scores  
  - Loan purpose analysis  
  - Interest rate vs FICO score trends  
  - Correlation heatmap for feature relationships  
- **Machine Learning Models Implemented**  
  - Decision Tree Classifier  
  - Bagging with Decision Tree  
  - AdaBoost with Decision Tree  
  - Random Forest Classifier ✅ (Best Model)  
  - AdaBoost with Random Forest  
  - Gradient Boosting Classifier  
- **Model Evaluation**  
  - Accuracy, Precision, Recall, F1-Score  
  - Confusion Matrix  

---

## 🛠 Tech Stack  
- **Programming Language**: Python  
- **Libraries**:  
  - `numpy`  
  - `pandas`  
  - `matplotlib`  
  - `seaborn`  
  - `scikit-learn`  
- **Development Environment**: Jupyter Notebook / Google Colab  

---

## 📂 Dataset  
The dataset consists of **9,578 loan records** with features such as:  
- Credit Policy  
- Loan Purpose  
- Interest Rate  
- Installment Amount  
- Annual Income  
- Debt-to-Income Ratio  
- FICO Score  
- Credit History Length  
- Revolving Balance & Utilization  
- Number of Inquiries in the last 6 months  
- Public Records  
- Target Variable: `not.fully.paid` (Loan default indicator)  

---

## 📊 Results  
| Model                              | Accuracy (%) | Precision | Recall | F1-Score |
|------------------------------------|--------------|-----------|--------|----------|
| Decision Tree                      | 84.58        | 0.85      | 1.00   | 0.92     |
| Bagging with Decision Tree         | 73.10        | -         | -      | -        |
| AdaBoost with Decision Tree        | 84.00        | -         | -      | -        |
| Random Forest Classifier           | **85.00**    | 0.85      | 1.00   | 0.92     |
| AdaBoost with Random Forest        | 84.75        | 0.82      | 0.85   | 0.78     |
| Gradient Boosting                  | 84.46        | 0.78      | 0.84   | 0.78     |

---

## 🖥 How to Run  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/yourusername/Loan_Repayment_Prediction.git
cd Loan_Repayment_Prediction
