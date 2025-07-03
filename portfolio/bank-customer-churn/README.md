# 🧠 Bank Customer Churn Prediction - Neural Network Project

**Course**: Introduction to Neural Networks  
**Objective**:  
Build an artificial neural network to predict whether a customer is likely to leave the bank in the next 6 months. This model will support the operations team in identifying high-risk customers and enabling targeted retention strategies.

---

## 🔍 Problem Statement

Banks face ongoing challenges in retaining customers. Customer churn impacts profitability and long-term business sustainability. The bank wants to proactively identify customers at risk of leaving and understand the driving factors behind churn.

As a **Data Scientist**, your role is to:
- Analyze customer attributes
- Build a neural network-based classifier
- Provide actionable recommendations to minimize churn

---

## 🛠️ Skills & Tools Used

- **Exploratory Data Analysis (EDA)**
- **Data Preprocessing**
- **Artificial Neural Networks (ANNs)**
- **TensorFlow & Keras**
- **Regularization Techniques**
- **Model Evaluation**

---

## 📊 Project Workflow

1. **Data Exploration**
   - Analyzed demographics, financial metrics, and customer activity
   - Identified patterns between churn behavior and key features

2. **Data Preprocessing**
   - Encoded categorical variables (e.g., geography, gender)
   - Scaled numerical features (e.g., balance, salary)
    - Handled class imbalance
   
3.  **Model Building**
   - Built a feedforward **Artificial Neural Network** using Keras
   - Applied **regularization** to prevent overfitting
   - Split data into training and testing sets for evaluation

4. **Model Evaluation**
   - Used accuracy, confusion matrix, precision, recall, and F1-score
   - Tuned model architecture for better generalization

5. **Recommendations**
   - Identified high-churn risk segments (e.g., older, inactive customers with lower credit scores)
   - Suggested strategic interventions to improve retention

---

## ✅ Outcomes

- Trained a neural network model with strong predictive performance
- Identified churn-prone customer profiles
- Recommended proactive engagement and personalized offers for at-risk customers

---

## 📂 Dataset

*The dataset used in this project was provided as part of the Introduction to Neural Networks course from Great Learning. Due to usage restrictions, the full dataset is not included in this repository.*

> ✅ A **sample dataset** (`sample_bank_nn_data.csv`) with a few rows is provided for structural reference.

---

## 🧠 Key Features

| Feature | Description |
|--------|-------------|
| `CustomerId` | Unique identifier for each customer |
| `CreditScore` | Customer's credit history score |
| `Geography` | Customer’s country (e.g., France, Germany) |
| `Gender` | Male or Female |
| `Age` | Customer’s age |
| `Tenure` | Years the customer has been with the bank |
| `NumOfProducts` | Number of products purchased |
| `Balance` | Account balance |
| `HasCrCard` | Whether the customer owns a credit card (1=yes, 0=no) |
| `IsActiveMember` | Whether the customer is actively using bank services |
| `EstimatedSalary` | Estimated annual salary |
| `Exited` | Target variable: whether customer left (1) or stayed (0) |

---

## 📎 License & Credits

This project was developed as part of the [Introduction to Neural Networks course at Great Learning](https://www.mygreatlearning.com/) & TEXAS McCombs at the University of Texas at Austin.
All content is intended for educational and portfolio use only.

---

> 💡 You’re welcome to fork or clone this repository to explore how neural networks can be used for customer churn prediction.
