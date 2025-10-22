# ElevateLabs_TASK2
# 🧩 Task 2: Exploratory Data Analysis (EDA)

## 📘 Objective
The goal of this task is to perform **Exploratory Data Analysis (EDA)** on a dataset to understand its structure, detect patterns, relationships, and anomalies, and summarize key statistics using visualizations.

For this task, I used the **Titanic dataset** from Kaggle.  
📂 [Dataset Link](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

---

## 🧠 What I Did
1. Imported and explored the dataset using **Pandas** and **NumPy**.  
2. Checked for missing values, data types, and summary statistics.  
3. Created **histograms** and **boxplots** to visualize numeric features.  
4. Used **pairplots** and **correlation heatmaps** to study feature relationships.  
5. Detected **patterns, trends, and anomalies** such as outliers and skewness.  
6. Derived key **feature-level insights** from visualizations.

---

## 🧰 Tools & Libraries Used
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Plotly**

---

## 📊 Key Visualizations
- Distribution of **Age** and **Fare** using histograms  
- **Boxplots** to identify outliers  
- **Pairplot** for multivariate relationships  
- **Correlation Heatmap** for feature relationships  
- **Countplots** for survival based on gender and passenger class  

---

## 🔍 Insights from EDA
- **Gender:** Females had a significantly higher survival rate than males.  
- **Class:** Passengers in **1st class** had the highest survival probability.  
- **Fare:** Higher fare was positively correlated with survival.  
- **Age:** Younger passengers tended to survive more often.  
- **Missing Values:** `Cabin` had many nulls and was dropped; `Age` and `Embarked` were imputed.  

---

## 🏁 Conclusion
Through this EDA, I gained a better understanding of the Titanic dataset, identified key survival factors such as gender, class, and fare, and prepared the dataset for further machine learning modeling.
