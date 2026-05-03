# 🏦 BANK CREDIT SCORING WITH DATA SCIENCE

---

## 📌 PROJECT OVERVIEW

This project focuses on automating the credit assessment process using data science[cite: 1]. By analyzing patterns in customer behavior, financial history, and transaction data, we transform traditional lending into an intelligent, evidence-based decision-making system[cite: 1].

---

## 🎯 OBJECTIVES

* **Data Collection**: Combine multiple financial datasets, including customer profiles, transactions, and loan records[cite: 1].
* **Cleaning**: Handle missing values and remove duplicates to ensure data quality[cite: 1].
* **Behavioral Analysis**: Study spending habits to identify patterns linked to default risk[cite: 1].
* **Model Building**: Develop a credit scoring model to classify customers by risk level[cite: 1].

---

## 🛠️ TECHNOLOGIES USED

* **Python**: The core language for the entire analysis[cite: 1].
* **Pandas & NumPy**: For efficient data cleaning and manipulation[cite: 1].
* **Matplotlib & Seaborn**: To create statistical visualizations, including heatmaps and pairplots[cite: 1].
* **Scikit-learn**: Used to build and validate our Logistic Regression model[cite: 1].

---

## 📊 PROJECT WORKFLOW

1. **Feature Engineering**: Created a "Savings" feature (Income - Spending) to better capture financial health[cite: 1].
2. **Standardization**: Applied Z-score scaling to normalize features for the machine learning model[cite: 1].
3. **Visualization**: Used pairplots to identify interactions between income, spending, and savings[cite: 1].
4. **Classification**: Implemented Logistic Regression to predict binary outcomes—specifically whether a customer is likely to default or not[cite: 1].

---

## 💡 KEY INSIGHTS

* **Risk Indicators**: High spending-to-income ratios and low savings rates are strong predictors of default[cite: 1].
* **Income vs. Risk**: Income alone is often insufficient to determine risk; behavioral data like spending is a more reliable indicator[cite: 1].
* **Model Performance**: The logistic regression model demonstrates strong predictive performance with balanced precision and recall[cite: 1].

---

## 🚀 HOW TO RUN

### 1. Clone the repository
`git clone <your-repo-link>`

### 2. Install dependencies
`pip install pandas numpy matplotlib seaborn scikit-learn`

### 3. Run the analysis
Open the `.ipynb` file in **Google Colab** or **Jupyter Notebook** to view the full execution and results[cite: 1].

---
