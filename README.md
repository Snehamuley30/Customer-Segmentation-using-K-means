# Customer-Segmentation-using-K-means
# 🛍️ Customer Segmentation using K-Means Clustering

## 📌 Project Overview

This project focuses on **Customer Segmentation** using **K-Means Clustering**. The goal is to group customers based on their **Annual Income** and **Spending Score**, helping businesses identify distinct customer segments for targeted marketing strategies.

Customer segmentation is a key technique in data-driven decision making, enabling companies to deliver **personalized services**, optimize marketing campaigns, and improve customer satisfaction.

---

## 🔍 Objectives

* Perform **Exploratory Data Analysis (EDA)**
* Conduct **Univariate and Bivariate Analysis**
* Apply **K-Means Clustering** to group customers
* Visualize clusters for better understanding
* Derive actionable business insights from the clusters

---

## 📊 Dataset

* Dataset used: **Mall Customer Segmentation Data**
* Features considered:

  * **CustomerID** (Unique Identifier)
  * **Gender**
  * **Age**
  * **Annual Income (k$)**
  * **Spending Score (1–100)**

---

## ⚙️ Methodology

1. **Data Preprocessing**

   * Handled missing values (if any)
   * Ensured data quality and consistency

2. **Univariate Analysis**

   * Distribution of Age, Income, and Spending Score using histograms & boxplots

3. **Bivariate Analysis**

   * Studied relationships between income, spending score, and age using scatterplots & correlation

4. **Clustering with K-Means**

   * Used **Elbow Method** to find optimal number of clusters
   * Applied K-Means to segment customers

5. **Visualization**

   * Visualized customer clusters with matplotlib
   * Highlighted centroids for better interpretation

---

## 💡 Key Insights

* Identified distinct customer groups (e.g., high-income low spenders, low-income high spenders, premium spenders).
* Insights can be used to design **targeted marketing campaigns**.
* Helps businesses improve **ROI and customer satisfaction** through personalization.

---

## 🛠️ Tech Stack

* **Python**
* **Pandas** (Data manipulation)
* **Matplotlib & Seaborn** (Visualization)
* **Scikit-learn** (Machine Learning – K-Means)
* **Jupyter Notebook**

---

## 🚀 How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/Snehamuley30/customer-segmentation.git
   cd customer-segmentation
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:

   ```bash
   jupyter notebook Costumer_segmentation.ipynb
   ```

---

