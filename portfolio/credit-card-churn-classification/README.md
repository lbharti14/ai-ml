# 💳 Credit Card Users Churn Prediction - Capstone Project

**Course**: Advanced Machine Learning  
**Objective**:  
Build a classification model to predict whether a customer will churn from Thera Bank's credit card services. This model aims to identify high-risk customers and uncover the primary drivers of attrition to help the bank reduce customer churn and improve retention strategies.

---

## 🔍 Problem Statement

Thera Bank has experienced a noticeable drop in credit card user retention. Since credit card services contribute significantly to the bank's revenue through various fees, retaining customers is crucial. The goal is to:
- Identify customers likely to stop using their credit cards
- Understand behavioral and demographic patterns linked to churn
- Provide actionable business recommendations to retain these customers

---

## 🛠️ Skills & Tools Used

- **Exploratory Data Analysis (EDA)**
- **Data Preprocessing**
- **Random Forest Classifier, Decision Tree Classifier, Bagging, Boosting(ADA & Gradient)**
-- **SMOTE and RandomUndersampler for handling class imbalance**
- **Hyperparameter Tuning (RandomSearchCVSearchCV)**
- **Model Evaluation (performance and comparison -Accuracy,Recall,Precision and F1-Score)**
- **Business Recommendations**

---

## 📊 Project Workflow

1. **Data Exploration**
   - Investigated relationships between customer attributes and churn
   - Highlighted key churn-inducing behaviors (e.g., low transaction activity, high inactivity)

2. **Data Preprocessing**
   - Handled missing values and encoded categorical variables
   - Applied feature scaling where necessary

3. **Handling Imbalance**
   - Used **SMOTE** to balance churned vs non-churned classes

4. **Model Building**
   - Trained models on original data: Random Forest, Decision Tree, Bagging, and Boosting(Gradient,ADA)
   - Trained models on Oversampled Data using **SMOTE**
   - Trained models on Undersampled Data 
   - Selected Best 3 from 15 models above on performance basis for HyperParamamer Tuning : Udersampled Gradient Boost, 
     Undersampled Bagging and Adaboost Undersampled.

5. **Model Optimization**
   - Tuned the best 3 model hyperparameters using **RandomSearchCV**
  
6. ** Model Comparision** on Training and Validation performance for the 3 models
    **Evaluation Metrics** and selected the Best model which was undersampled AdaBoostClassifier
   - **Accuracy**: 88.3%
   - **Recall (Churn Class)**: 90.5%
   - **F1-Score (Churn Class)**: 71.3%
   - **Precision**: 59%%

---

## ✅ Outcomes

- Built a high-performing churn prediction model using **Random Forest**
- Identified key churn drivers: total transaction count, total transaction amount, toral revolving balance, Average Spend
- Generated strategic recommendations to improve retention of at-risk customers

---

## 📂 Dataset

*The dataset used in this project was provided as part of the Advanced Machine Learning course from Great Learning. Due to usage restrictions, the full dataset is not included in this repository.*

> ✅ A **sample dataset** (`BankChurners.csv`) with a few rows is provided for structural reference.

---

## 🧠 Key Features

| Feature | Description |
|--------|-------------|
| `Attrition_Flag` | Target variable: Churn status (`Attrited Customer` or `Existing Customer`) |
| `Customer_Age` | Age of the customer |
| `Months_Inactive_12_mon` | Months inactive in the past year |
| `Contacts_Count_12_mon` | Number of customer-bank contacts in last 12 months |
| `Total_Trans_Ct` | Total number of transactions in the past 12 months |
| `Total_Trans_Amt` | Total transaction amount in the past 12 months |
| `Avg_Utilization_Ratio` | Average credit utilization over 12 months |

---

## 📎 License & Credits

This project was developed as part of the [Advanced Machine Learning course at Great Learning](https://www.mygreatlearning.com/) & TEXAS MCCOMBS(The University of Texas at Austin) 
All content is intended for educational and portfolio use only.

---

> 💡 Feel free to fork or clone this repository to explore the full workflow or adapt the model to your own churn prediction use case.
