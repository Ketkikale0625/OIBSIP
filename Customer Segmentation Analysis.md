# 🛍️ Customer Segmentation Analysis

## 📌 Project Overview

The goal of this project is to perform **customer segmentation** for an e-commerce company.
The goal is to group customers based on their purchasing behavior and demographics to help drive **targeted marketing**, **personalized offers**, and **business growth strategies**.

---

## 📂 Dataset

* **Features used**:

  * Demographics: Age, Income, etc
  * Purchases: Wines, Fruits, Meat Products, etc
  * Purchase Channels
  * Campaigns & Recency

---

## ⚙️ Key Steps

### 1. Data Cleaning

* Removed irrelevant columns
* Dropped IDs (Customer ID, Name)

### 2. Feature Selection

* Selected important behavioral and demographic features for segmentation.

### 3. Data Standardization

* Standardized features using **StandardScaler** to give all attributes equal weight.

### 4. Optimal Clusters (Elbow Method)

* Used **KMeans** clustering for different values of `k (1–10)`.
* Selected the best number of clusters using the **Elbow Method**

### 5. Customer Segmentation

* Applied **KMeans clustering** with `k=4`.
* Reduced data dimensions with **PCA** (2 components) for visualization.

### 6. Cluster Visualization

* Created a **scatter plot** of customer clusters using PCA.

### 7. Cluster Profiling

* Summarized mean values of features for each cluster to interpret customer groups.

---

## 📊 Visualizations

* **Elbow Method Plot** → helped choose the best number of clusters.
* **PCA Scatter Plot** → visual representation of customer segments.
* **Cluster Summary Table** → average values of features in each cluster.

---

## 🚀 Results & Insights

* Customers were grouped into **4 distinct segments**, each with unique purchase and demographic characteristics.
* Example interpretation:

  * **Cluster 0**: High-income, frequent wine & meat buyers.
  * **Cluster 1**: Younger customers, low spend, more online activity.
  * **Cluster 2**: Older customers, moderate income, loyal to catalog purchases.
  * **Cluster 3**: Families with kids/teens, balanced purchases across categories.

These insights can help the business with:

* **Targeted marketing** (e.g., wine campaigns for high-spenders).
* **Personalized promotions** for online vs offline buyers.
* **Customer retention strategies** based on engagement levels.

---

## 🛠️ Tech Stack

* **Python**
* **Pandas, Numpy** → data handling
* **Matplotlib, Seaborn** → visualizations
* **Scikit-learn** → clustering (KMeans, StandardScaler, PCA)

---

## 📌 Learning Outcomes

* Gained experience with **unsupervised learning (KMeans clustering)**.
* Learned how to determine the **optimal number of clusters**.
* Understood how to use **PCA for dimensionality reduction & visualization**.
* Developed skills in **cluster profiling & interpretation**.
