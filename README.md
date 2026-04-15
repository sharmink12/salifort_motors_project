# 🚗 Salifort Motors Employee Churn Analysis

## 📌 Overview

This project analyzes employee data from Salifort Motors to identify the key drivers of employee turnover using machine learning models such as Decision Tree and Random Forest.

The goal is to help the company reduce attrition through data-driven insights and predictive modeling.

---

## 🎯 Business Problem

Salifort Motors is experiencing high employee turnover, which leads to:

- Increased hiring and training costs  
- Loss of experienced employees  
- Reduced productivity  

The company needs to understand why employees are leaving and how to improve retention.

---

## 💡 Solution

In this project, I:

- Analyzed employee-level data  
- Identified key drivers of churn  
- Built machine learning models to predict employee turnover  

---

## 📊 Key Insights

A critical finding from the analysis is the presence of a **"Success Penalty"**:

- 72% of employee turnover is driven by a combination of **high performance (evaluation scores)** and **excessive workload (project assignments)**  
- High-performing employees are more likely to leave due to burnout rather than low compensation  
- Salary and department changes have **minimal impact (<0.1% importance)** on retention  

👉 Insight:  
The company is effectively developing top talent, overloading them, and losing them at peak value.

---

## 📈 Outputs

The project produces:

- Churn distribution analysis  
- Feature importance ranking  
- Model performance metrics:
  - Accuracy  
  - Precision  
  - Recall  
  - F1 Score  
  - AUC  

---

## 🤖 Model

A classification model was developed to predict employee churn.

- **Target:** Employee leaving (Yes/No)  
- **Features:** Evaluation, satisfaction, workload, number of projects, salary, etc.  

### Models Used:
- Logistic Regression  
- Decision Tree  
- Random Forest (Champion Model)

---

## 🛠️ Tech Stack

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  

---

## 📂 Project Structure

salifort_motors/
│── data/ # Dataset
│── notebooks/ # Analysis & modeling
│── README.md


---

## ▶️ How to Run

1. Download or clone the repository  
2. Open the project folder  
3. Open `notebooks/analysis.ipynb`  
4. Run all cells to view analysis, visualizations, and model results  

---

## 💼 Business Impact

This analysis enables Salifort Motors to:

- Identify employees at risk of leaving  
- Improve retention strategies  
- Optimize workload distribution  
- Support data-driven HR decisions

With a  96% model accuracy, we can confirm that our highest-valued contributors are the most likely to exit. This creates a replacement cost per departure and puts active projects at risk of delay. Furthermore, the loss of mid-tenure staff (3–5 years) severely depletes the company’s internal leadership pipeline, forcing a reliance on expensive external hiring.

---

## 🔮 Future Improvements

- Improve model performance and tuning  
- Build an interactive dashboard (Power BI / Tableau)  
- Deploy the model for real-time predictions  


# Author

GitHub : https://github.com/sharmink12/

LinkedIn : www.linkedin.com/in/sharmin-kennedy-40265833


Added complete README

 
