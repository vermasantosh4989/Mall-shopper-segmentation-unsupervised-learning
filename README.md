# Mall Shopper Profiling using Unsupervised Machine Learning

## Project Overview

This project performs **customer segmentation** using **Unsupervised Machine Learning** techniques on the Mall Customers dataset. The objective is to identify different groups of customers based on their shopping behavior so that businesses can create targeted marketing strategies and improve customer satisfaction.

---

# Dataset Information

- **Dataset Name:** Mall_Customers.csv
- **Total Records:** 200
- **Total Features:** 5

## Dataset Columns

| Column | Description |
|---------|-------------|
| CustomerID | Unique Customer ID |
| Gender | Male/Female |
| Age | Customer Age |
| Annual Income (k$) | Annual Income in thousand dollars |
| Spending Score (1-100) | Spending score assigned by the mall |

---

# Project Objectives

- Perform Exploratory Data Analysis (EDA)
- Create new customer profile features
- Scale numerical features
- Apply K-Means Clustering
- Apply Agglomerative Hierarchical Clustering
- Apply DBSCAN Clustering
- Compare clustering algorithms
- Identify the best clustering model
- Save the trained model for future predictions

---

# Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- Joblib

---

# Machine Learning Algorithms

## 1. K-Means Clustering

- Elbow Method
- Silhouette Score
- Cluster Visualization
- PCA Visualization
- Customer Profiling

---

## 2. Agglomerative Hierarchical Clustering

- Ward Linkage
- Complete Linkage
- Average Linkage
- Dendrogram
- Cluster Profiling

---

## 3. DBSCAN

- kNN Distance Plot
- Hyperparameter Tuning
- Noise Detection
- Cluster Profiling

---

# Feature Engineering

The following features were created:

- Gender Encoding
- Income Group
- Age Group
- Spending Category

---

# Data Preprocessing

- Label Encoding
- Feature Selection
- StandardScaler

---

# Evaluation Metrics

The clustering algorithms were evaluated using:

- Silhouette Score
- Davies-Bouldin Index
- Calinski-Harabasz Index

---

# Project Workflow

### Step 1
- Dataset Loading
- Data Inspection
- Missing Value Analysis
- Univariate Analysis
- Bivariate Analysis
- Correlation Heatmap

### Step 2
- Feature Engineering
- Label Encoding
- Standard Scaling

### Step 3
- K-Means Clustering
- Elbow Method
- PCA
- Cluster Profiling

### Step 4
- Agglomerative Clustering
- Dendrogram
- Linkage Comparison
- Cluster Analysis

### Step 5
- DBSCAN
- kNN Distance Plot
- Hyperparameter Tuning
- Noise Analysis

### Step 6
- Model Comparison
- Business Recommendations

### Step 7
- Save Model
- Predict New Customers
- Generate README
- Generate Summary Report

---

# Files Included

```
Mall_Shopper_Profiling.ipynb
Mall_Customers.csv
README.md
summary_report.md
kmeans_model.pkl
scaler.pkl
```

---

# Model Comparison

| Algorithm | Advantages |
|------------|------------|
| K-Means | Fast, simple, works well for spherical clusters |
| Agglomerative | Produces hierarchical clusters and dendrogram |
| DBSCAN | Detects outliers automatically and finds irregular clusters |

---

# Best Model

After comparing all clustering algorithms using evaluation metrics:

- Silhouette Score
- Davies-Bouldin Index
- Calinski-Harabasz Index

**K-Means Clustering** was selected as the best-performing model for this dataset because it produced well-separated and easily interpretable customer segments.

---

# Business Recommendations

- Offer premium memberships to high-income, high-spending customers.
- Provide discounts and loyalty rewards to high-income, low-spending customers.
- Promote new products to young customers with high spending scores.
- Design budget-friendly offers for low-income customers.
- Analyze DBSCAN noise points individually, as they may represent unique customer behavior.

---

# Conclusion

This project successfully segmented mall customers into meaningful groups using **K-Means**, **Agglomerative Clustering**, and **DBSCAN**. The results demonstrate how unsupervised learning can help businesses understand customer behavior and support targeted marketing, personalized promotions, customer retention, and strategic decision-making. Based on the evaluation metrics, **K-Means** provided the most effective customer segmentation for this dataset.

---

# Author

**Name:** Santosh Verma

**Project:** Mall Shopper Profiling using Unsupervised Machine Learning

**Course:** Data Science / AI/ML


