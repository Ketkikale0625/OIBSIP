# 🧹 Data Cleaning Project

## 📌 Project Overview

The objective of this project is to clean raw and messy datasets to ensure accuracy, consistency, and usability for further data analysis and visualization. 
This task was completed as part of the Oasis Infobyte Data Science Internship to demonstrate proficiency in data preprocessing.

---

## 📂 Dataset

The dataset provided contained common data quality issues:

Null or missing values
Duplicate rows
Inconsistent column naming and formatting
Mixed data types
Unnecessary or irrelevant field
---

## ⚙️ Key Steps

### 1. Data Exploration

* Checked dataset structure with `.info()` and `.describe()`.
* Visualized **missing values** using a heatmap.

### 2. Handling Missing Data

* Identified missing values in `reviews_per_month`, `last_review`.
* Imputed missing values with **median** .

### 3. Duplicate Removal

* Checked for duplicate records.
* Removed duplicates to maintain data integrity.

### 4. Standardization

* Ensured consistent formatting (e.g., date formats, text case).
* Standardized units where necessary.

### 5. Outlier Detection

* Used **boxplots** to detect outliers in numerical columns (e.g. `price`).
* Decided whether to cap or remove extreme outliers.

---

## 📊 Visualizations

* **Missing Value Heatmap** → quick overview of null values.
* **Boxplots** → identified extreme values in `price`.

---

## 🚀 Results & Insights

* Cleaned dataset with **missing values handled**.
* Removed duplicates for accurate analysis.
* Detected and treated outliers to avoid skewed insights.
* Final dataset is **ready for further analysis or machine learning models**.

---

## 🛠️ Tech Stack

* **Python**
* **Pandas, Numpy** → data wrangling
* **Matplotlib, Seaborn** → visualization

---

## 📌 Learning Outcomes

* Gained practical experience with **data cleaning techniques**.
* Learned how to handle **missing values** and **duplicates**.
* Applied **outlier detection using boxplots**.
* Improved dataset integrity and reliability for future projects.
