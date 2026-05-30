# Regression_logistique

# 📈 Customer Propensity Scoring using Logistic Regression

## 📌 Project Overview

This project focuses on the development of a customer propensity score designed to predict whether a client is likely to subscribe to a term deposit offered by a bank.

The study is based on a Portuguese bank marketing dataset containing information about clients, their socio-economic characteristics, and the outcomes of previous marketing campaigns.

The objective is to help financial institutions improve customer targeting, increase campaign conversion rates, and optimize marketing resources through predictive analytics.

---

## 🎯 Business Problem

Marketing campaigns are costly and often target a large number of customers with uncertain outcomes.

The challenge is to identify, before launching a campaign, which customers are the most likely to subscribe to a banking product.

This project addresses a binary classification problem:

* **1** → Customer subscribes to the term deposit
* **0** → Customer does not subscribe

The final model generates a propensity score that can support marketing decision-making and customer segmentation strategies.

---

## 📊 Dataset Description

The dataset comes from direct marketing campaigns conducted by a Portuguese banking institution.

It contains customer information such as:

* Age
* Profession
* Marital status
* Education level
* Account balance
* Housing loan
* Personal loan
* Contact duration
* Previous campaign outcomes
* Number of contacts
* Communication month

The target variable indicates whether the customer subscribed to a term deposit.

---

## 🔍 Exploratory Data Analysis (EDA)

Several analyses were conducted to better understand the dataset:

* Descriptive statistics
* Missing values detection
* Distribution analysis
* Class imbalance analysis
* Correlation study
* Customer profile exploration

The analysis revealed a strong imbalance between subscribers and non-subscribers, requiring specific treatment before modeling.

---

## 📈 Statistical Analysis

To evaluate the relationship between explanatory variables and the target variable, statistical tests were performed:

### Chi-Square Test

Used to determine whether categorical variables were significantly associated with customer subscription behavior.

### Cramer's V

Used to measure the strength of association between variables.

Results showed statistically significant relationships between customer characteristics and subscription outcomes.

---

## ⚙️ Data Preprocessing

The following preprocessing steps were applied:

* Data cleaning
* Feature engineering
* Dummy variable encoding
* Train/Test split
* Multicollinearity prevention
* Preparation of the target variable

---

## 🤖 Machine Learning Model

### Logistic Regression

A logistic regression model was developed to estimate the probability of customer subscription.

The model provides:

* Probability estimates
* Customer propensity scores
* Interpretability of predictors
* Business-oriented decision support

---

## ⚖️ Handling Class Imbalance

Because the dataset was highly imbalanced, several resampling techniques were investigated:

### Oversampling

Duplication of minority class observations.

### Undersampling

Reduction of majority class observations.

### SMOTE

Generation of synthetic observations for the minority class.

### ADASYN

Adaptive synthetic sampling for difficult minority observations.

---

## 📊 Model Evaluation

Performance was assessed using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* ROC Curve
* AUC (Area Under Curve)

---

## 🏆 Key Results

### Logistic Regression Performance

* ROC-AUC ≈ **0.91**
* Strong discrimination ability between subscribers and non-subscribers
* Good generalization on unseen data

### Resampling Comparison

| Method        | Performance              |
| ------------- | ------------------------ |
| Oversampling  | Best overall performance |
| Undersampling | Competitive results      |
| SMOTE         | Lower performance        |
| ADASYN        | Evaluated for comparison |

The oversampling strategy achieved the best balance between predictive performance and model stability.

---

## 💼 Business Impact

This model can help banks:

* Improve customer targeting
* Increase marketing campaign efficiency
* Reduce acquisition costs
* Prioritize high-potential customers
* Support CRM and customer relationship strategies

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Statsmodels
* Matplotlib
* Seaborn
* Imbalanced-Learn (SMOTE, ADASYN)
* Jupyter Notebook
* Google Colab

---

## 📚 Skills Demonstrated

* Predictive Modeling
* Logistic Regression
* Customer Analytics
* Marketing Analytics
* Statistical Testing
* Class Imbalance Handling
* Feature Engineering
* Model Evaluation
* Business-Oriented Data Science

---

## 👨‍💻 Author

**YEO Donignon Sékou**

Master 2 Mathematical Engineering – Data Science & Artificial Intelligence

Université Côte d'Azur

GitHub: https://github.com/yeo-donignon-sekou
