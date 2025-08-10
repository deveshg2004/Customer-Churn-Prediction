# 📊 Customer Churn Prediction

This project predicts **customer churn** (whether a customer will leave the company) using **Machine Learning models**.  
The dataset contains customer demographic and account-related information, and the goal is to classify customers as "Exited" or "Not Exited".

---



## 📌 Features
- Data preprocessing (label encoding for categorical features, scaling for numerical features)
- Model building using:
  - Logistic Regression
  - Random Forest Classifier
  - Gradient Boosting Classifier
- Model evaluation using Accuracy, Precision, Recall, and F1-score
- Feature importance visualization for Random Forest

---

## 🗂 Dataset
The dataset (`churn.csv`) contains the following columns:
- **CreditScore** – Customer’s credit score
- **Geography** – Country of the customer
- **Gender** – Male / Female
- **Age** – Customer age
- **Tenure** – Number of years with the bank
- **Balance** – Account balance
- **NumOfProducts** – Number of bank products used
- **EstimatedSalary** – Annual salary
- **Exited** – Target variable (1 = churned, 0 = stayed)

---

## 📈 Model Performance

| Model               | Accuracy | Precision | Recall  | F1 Score |
|---------------------|----------|-----------|---------|----------|
| Logistic Regression | 0.7910   | 0.3626    | 0.0839  | 0.1363   |
| Random Forest       | 0.8485   | 0.6923    | 0.4122  | 0.5167   |
| Gradient Boosting   | 0.8575   | 0.7195    | 0.4503  | 0.5539   |

---

## 🛠 Technologies Used
- **Python**
- **Pandas** – Data manipulation
- **NumPy** – Numerical operations
- **Scikit-learn** – ML models & evaluation
- **Matplotlib / Seaborn** – Visualization
---

👤 **Author**  
Devesh Gogia  
GitHub: [@deveshg2004](https://github.com/deveshg2004)  
Email: deveshgogia22@gmail.com  

---

⭐ If you like this project, consider giving it a star!