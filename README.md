# MiniProject-G2

# 🏥 Insurance Cost Prediction using Regularized Regression

## 📌 Project Overview
This project explores three regularized regression algorithms—**Ridge (L2)**, **Lasso (L1)**, and **Elastic Net**,to predict medical insurance expenses using the Medical Cost Personal Dataset from Kaggle.

The project was completed as part of a Machine Learning mini project to understand how regularization affects regression models and compare their performance.

---

## 📊 Dataset
**Dataset:** Medical Cost Personal Dataset

### Features
- Age
- Sex
- BMI
- Number of Children
- Smoker
- Region

### Target
- Medical Insurance Expenses

---

## 🔍 Exploratory Data Analysis (EDA)

The dataset was explored to better understand the relationships between the features and insurance expenses.

The EDA includes:
- Dataset overview
- Missing value check
- Duplicate check
- Histograms
- Scatter plots
- Boxplots
- Correlation heatmap
- Key observations

---

## ⚙️ Data Preprocessing

The following preprocessing steps were performed:

- Checked for missing values
- Removed duplicates
- Encoded categorical variables
- Split the data into training and testing sets

To improve the regression models, feature scaling was applied using **StandardScaler**.

---

## 🤖 Regression Models

The following models were implemented and compared:

- Ridge Regression (L2)
- Lasso Regression (L1)
- Elastic Net

---

## 📈 Model Evaluation

The models were evaluated using:

- **R² Score**
- **Root Mean Squared Error (RMSE)**

These two metrics were used as the main comparison criteria:

- Higher **R²** indicates better predictive performance.
- Lower **RMSE** indicates smaller prediction errors.

---

## 🚀 Model Improvement

During the initial comparison, Elastic Net produced noticeably lower performance than Ridge and Lasso.

To improve the models:

- Features were standardized using **StandardScaler**.
- Hyperparameters were optimized using **GridSearchCV**.
- Different values of **alpha** and **l1_ratio** were tested for Elastic Net.
- The same optimization process was applied to all models for a fair comparison.

The improved models achieved better performance and provided a more reliable comparison.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📂 Repository Contents

```
MiniProjectG2.ipynb
README.md
```

---

## 📚 Learning Outcomes

Through this project, we learned how to:

- Perform Exploratory Data Analysis (EDA)
- Preprocess data for machine learning
- Apply Ridge, Lasso, and Elastic Net regression
- Evaluate regression models using R² and RMSE
- Improve model performance through feature scaling and hyperparameter tuning
- Compare different regularization techniques
