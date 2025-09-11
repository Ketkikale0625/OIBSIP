# 📊 Android Market Analysis – Power BI Dashboard

## 📌 Project Overview

This project analyzes **Google Play Store data** to uncover insights about the Android app market.
The analysis focuses on **app categories, ratings, installs, pricing, and user sentiment** using an interactive Power BI dashboard.

---

## 🔧 Data Sources

* **Apps Dataset** – includes details such as *App Name, Category, Rating, Size, Installs, Type (Free/Paid), Price, Content Rating*.
* **User Reviews Dataset** – includes *App, Review, Sentiment (Positive/Neutral/Negative), Sentiment Polarity (−1 to +1), Sentiment Subjectivity (0 to 1)*.

---

## 🛠 Data Preparation

* Cleaned and transformed datasets in **Power Query**:

  * Removed duplicates and null values.
  * Standardized formats for installs (`1,000+` → `1000`) and sizes (KB/MB → MB).
  * Corrected data types (Rating → Decimal, Price → Numeric, Date → Date).
  * Ensured relationships between `Apps` and `User Reviews` via **App Name**.

---

## 📊 Key Measures (DAX)

Some of the calculated measures include:

* **Avg Rating** = `AVERAGE(Apps[Rating])`
* **Total Installs** = `SUM(Apps[Installs])`
* **% Free Apps** = % of apps that are free vs paid
* **% Positive / % Neutral / % Negative** → calculated using `DIVIDE`
* **Avg Polarity** = `AVERAGE(User Reviews[Polarity])`
* **Avg Subjectivity** = `AVERAGE(User Reviews[Subjectivity])`
* **Review Count** = `COUNTROWS(User Reviews)`

---

## 📈 Dashboard Features

### 1. **Category Analysis**

* Distribution of apps across categories (Bar Chart).
* Price by category.
* Free vs Paid breakdown.

### 2. **Market Trends**

* Installs vs Price trends.
* Rating distribution (Histogram).

### 3. **Sentiment Analysis**

* Pie chart → % of Positive, Neutral, Negative reviews.
* Heatmap (Matrix with conditional formatting) → Sentiment distribution by Genre.
* Scatter plot (Avg Subjectivity vs Avg Polarity, bubble size = Review Count).
* Bar Chart → Sentiment distribution by Category.

### 4. **KPIs**

* Total Apps
* Total Installs
* Avg Rating
* Free vs Paid % split

### 5. **Interactivity**

* Slicers for Price, Genre, App Type (Free/Paid), Content Rating.
* Drillthrough from **Category → App-level insights**.
* Tooltip with app-specific stats (Polarity, Subjectivity, Avg Rating, Reviews).

---

## 🎨 Dashboard Layout

* **Top Panel** → KPI cards.
* **Left Section** → Category distribution.
* **Middle Section** → Market metrics (ratings, installs, prices).
* **Right Section** → Sentiment visuals (scatter, heatmap).

---

## 🚀 Skills & Tools

* **Power BI Desktop**
* **Power Query** (data transformation)
* **DAX** (custom measures for sentiment % and metrics)
* **Data Visualization Best Practices** (color coding, heatmaps)

---

## 📌 Key Insights

* **Games, Tools, and Family** dominate the Play Store.
* **Most apps are free**, with paid apps concentrated in niche categories.
* Ratings are generally **positive**, but many reviews are **highly subjective**.
* Sentiment scatter plots show clear clustering of **positive vs negative categories**.
* Heatmaps reveal which Genre receive the **most positive feedback**.

---

👉 Do you want me to make this README **portfolio-ready with placeholders for screenshots** (e.g., “![Dashboard Screenshot 1](screenshot1.png)”), so you can just add your dashboard images later?
