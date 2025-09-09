# 🏠 House Price Prediction with Linear Regression

## 📌 Project Overview

The objective of this project is to build a predictive model using linear regression to estimate a numerical outcome based on a dataset with relevant features.
Linear regression is a fundamental machine learning algorithm, and this project provides hands-on experience in developing, evaluating, and interpreting a predictive model

## 📂 Dataset

* **Total Rows:** 545
* **Target Variable:**

  * `SalePrice` → price of the house.
Feature Types:
    *Numerical: area, bedrooms, bathrooms, stories, parking
    *Categorical (encoded): mainroad, guestroom, basement, hotwaterheating, airconditioning, prefarea, furnishingstatus

---

## ⚙️ Key Steps

### 1. Data Exploration & Cleaning

* Checked dataset structure with `.info()` and `.describe()`.
* Identified missing values and handled them.
* Removed or imputed inconsistent values.

### 2. Feature Engineering

* Selected key numerical features affecting house prices.
* Encoded categorical features (if present).
* Scaled/standardized numerical features.

### 3. Train-Test Split

* Split dataset into **training set (70%)** and **testing set (30%)**.

### 4. Model Building

* Implemented **Linear Regression** using `Scikit-learn`.
* Trained model on training dataset.

### 5. Model Evaluation

* Evaluated model performance using:

  * **Mean Squared Error (MSE)**: 1754318687330.664
  * **R-squared (R²)** : 0.65
  * **Root Mean Squared Error**: 1324506.96

---

## 📊 Visualizations

* **Heatmap** → correlations between house features and price.
* **Scatter Plots** → feature vs price relationships.
* **Actual vs Predicted Plot** → shows how well the model fits.

---

## 🚀 Results & Insights

* The **Linear Regression model successfully predicted house prices** with reasonable accuracy.
* Key features like `OverallQual`, `GarageArea`, and `YearBuilt` had the strongest impact on house prices.
* Visualization of actual vs predicted values showed a good linear trend.

---

## 🛠️ Tech Stack

* **Python**
* **Pandas, Numpy** → data handling
* **Matplotlib, Seaborn** → visualization
* **Scikit-learn** → Linear Regression model & evaluation

---

## 📌 Learning Outcomes

* Learned how to **apply Linear Regression** for prediction tasks.
* Understood the importance of **feature selection and scaling**.
* Practiced evaluating models with **MSE & R² metrics**.
* Built visualizations to interpret regression model performance.
