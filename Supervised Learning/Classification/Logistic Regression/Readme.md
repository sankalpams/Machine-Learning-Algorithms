# 📊 Telco Customer Churn Prediction using Logistic Regression

## 📌 Overview

This project predicts whether a customer will churn (leave the service) using **Logistic Regression**, a supervised machine learning algorithm.
It helps telecom companies identify high-risk customers and improve retention strategies.

---

## 🎯 Objectives

* Analyze customer data to understand churn behavior
* Build a classification model using Logistic Regression
* Evaluate performance using metrics and visualizations

---

## 📂 Dataset

* **Telco Customer Churn Dataset**
* Includes:

  * Customer demographics
  * Account information
  * Services used
  * Churn status (Target Variable)

---

## ⚙️ Technologies Used

* Python 🐍
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn
* Google Colab

---

## 🧠 Model Used

* **Logistic Regression**
* Type: Classification (Supervised Learning)

---

## 🔄 Workflow

1. Data Upload (Google Colab)
2. Data Cleaning & Preprocessing
3. Handling Missing Values
4. Encoding Categorical Variables
5. Feature Scaling
6. Train-Test Split
7. Model Training
8. Evaluation & Visualization

---

## 📊 Model Performance

### ✅ Confusion Matrix
![image alt](https://github.com/sankalpams/Machine-Learning-Algorithms/blob/61208bebe78dd7f268b35b1bec8df23338c5868f/Supervised%20Learning/Classification/Logistic%20Regression/Confusion%20Matrix.png)

* True Negatives: 1009
* True Positives: 400
* No misclassifications (Perfect prediction)

---

### 📈 ROC Curve
![image alt](https://github.com/sankalpams/Machine-Learning-Algorithms/blob/61208bebe78dd7f268b35b1bec8df23338c5868f/Supervised%20Learning/Classification/Logistic%20Regression/ROC%20Curve.png)

* AUC Score: **1.00**
* Indicates an excellent model performance

---

### 📉 Feature Importance
![image alt](https://github.com/sankalpams/Machine-Learning-Algorithms/blob/61208bebe78dd7f268b35b1bec8df23338c5868f/Supervised%20Learning/Classification/Logistic%20Regression/Feature%20Importance.png)

* Most influential features:
  * Churn Score
  * Monthly Charges
  * Paperless Billing
  * Tenure / Contract

---

## 💡 Key Insights

* Customers with higher monthly charges are more likely to churn
* Contract type plays a significant role in retention
* Logistic Regression performs extremely well on this dataset


## 👤 Author

**Malith Shehan**

---

## ⭐ Support

If you found this project useful, give it a ⭐ on GitHub!

