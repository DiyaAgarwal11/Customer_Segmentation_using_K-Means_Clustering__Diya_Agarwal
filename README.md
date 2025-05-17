# 📦 Snapdeal Menternship Project: Customer Segmentation

This repository contains the customer segmentation project completed as part of the **Snapdeal Menternship Program**. The project leverages **unsupervised machine learning techniques**—notably **K-Means Clustering** and **Principal Component Analysis (PCA)**—to uncover actionable customer segments based on purchasing behavior.

---

## 🎯 Objective

To segment Snapdeal's customer base into distinct behavioral groups to drive:
- Personalized marketing strategies
- Enhanced customer retention
- Increased customer lifetime value (CLV)

---

## 🧠 Methodology

1. **Data Cleaning & Preprocessing**
   - Handled missing values and removed outliers using the Z-score method
   - Engineered new features (e.g., `TotalAmount`, `InvoiceHour`)
   - Applied one-hot encoding to categorical variables

2. **Feature Scaling**
   - Normalized numerical features using `StandardScaler`

3. **Dimensionality Reduction**
   - Used **PCA** to reduce dimensionality and enable 2D visualization of clusters

4. **Clustering**
   - Applied **K-Means Clustering** with `k=4`, chosen via the Elbow Method

5. **Cluster Profiling**
   - Analyzed each cluster based on purchasing behavior (spend, frequency, timing)

---

## 📊 Visualizations Included

- **Elbow Plot**: To determine the optimal number of clusters (k)
- **PCA Scatter Plot**: 2D visualization of clustered data
- **Cluster Summary Table**: Strategic insights and recommendations per segment

---

## 🔍 Key Findings

| Cluster | Segment Type      | Behavior Description                   | Strategic Recommendation           |
|---------|-------------------|----------------------------------------|------------------------------------|
| 0       | Standard Buyers   | Low spend, frequent purchases          | Promote bundles and add-ons        |
| 1       | Bulk Buyers       | High volume, price-sensitive           | Offer volume discounts and loyalty |
| 2       | Mid Spenders      | Balanced across behavior dimensions    | Use cross-selling and personalization |
| 3       | Premium Buyers    | High spend, brand-conscious            | Target with VIP perks and early deals |

---

## 🧰 Tools & Technologies

- **Python**
- **Pandas**, **NumPy** for data manipulation
- **Matplotlib**, **Seaborn** for visualizations
- **Scikit-learn** for clustering and PCA
- **Jupyter Notebook** as the development environment

---

## 🚀 Outcome

A well-defined customer segmentation model ready for deployment in marketing analytics and personalization pipelines. The clusters provide interpretable segments that support data-driven decision-making.
"""
