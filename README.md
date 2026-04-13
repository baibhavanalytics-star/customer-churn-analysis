# 📊 Customer Churn Analysis

## 📌 Problem Statement

Customer churn is a major challenge for businesses as it directly impacts revenue and growth.
The objective of this project is to identify customers who are likely to churn and understand the key factors driving churn so that businesses can take proactive steps to retain them.

---

## 📂 Dataset

* Contains customer demographic details, account information, and usage patterns
* Includes features like tenure, monthly charges, contract type, and services used
* Dataset size: 10,000+ records

---

## 🛠️ Tools & Technologies

* Python (Pandas, NumPy)
* Data Visualization (Matplotlib, Seaborn)
* Machine Learning (Scikit-learn)

---

## 🔍 Project Workflow

1. Data Cleaning

   * Handled missing values
   * Converted categorical variables into numerical format

2. Exploratory Data Analysis (EDA)

   * Analyzed churn distribution
   * Studied relationships between churn and key features

3. Feature Engineering

   * Selected important variables influencing churn

4. Model Building

   * Applied Logistic Regression and Random Forest

5. Model Evaluation

   * Compared model performance using accuracy

---

## 📊 Key Insights

* Customers with **low tenure** are more likely to churn
* **High monthly charges** increase the probability of churn
* Customers with **month-to-month contracts** show higher churn rates
* Long-term contract customers are more likely to stay

---

## 🤖 Model Performance

* Model Used: Random Forest
* Accuracy Achieved: **82%**

---

## 💼 Business Impact

* Helps businesses identify **high-risk customers**
* Enables **targeted retention strategies**
* Supports decision-making for pricing and contract policies

---

## 📸 Visualizations

(Add your screenshots here)

Example:
![Churn Distribution](churn_plot.png)

---

## 📁 Files in Repository

* `churn_analysis.ipynb.ipynb` → Complete analysis and model
* `dataset.csv` → Dataset used
* `churn_plot.png` → Visualizations

---

## 🚀 Future Improvements

* Implement advanced models like XGBoost
* Perform hyperparameter tuning
* Deploy the model using a web application
