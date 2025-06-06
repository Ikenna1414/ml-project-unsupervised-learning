# machine_learning_project-unsupervised-learning

## Unsupervised Learning: Wholesale Customers Analysis

This project applies unsupervised learning techniques to a real-world dataset from a wholesale distributor. The goal is to uncover natural groupings in customer purchasing behavior to inform better marketing, inventory, or customer segmentation strategies.

## 📊 Dataset Overview

The dataset includes annual spending on six product categories by clients:

- Fresh
- Milk
- Grocery
- Frozen
- Detergents_Paper
- Delicatessen

Each row represents a customer, and columns contain product expenditures.

## Project Objectives

- Clean and preprocess the data
- Apply **K-Means Clustering** and **Hierarchical Clustering** to segment the data
- Use **PCA** (Principal Component Analysis) for dimensionality reduction and better visualization
- Derive insights from the clusters to support data-driven decisions

## Key Techniques Used

- **Exploratory Data Analysis (EDA)** using pandas, seaborn, and matplotlib
- **KMeans Clustering** with elbow method and silhouette score for choosing optimal `k`
- **Hierarchical Clustering** with dendrograms and Agglomerative Clustering
- **PCA** to reduce dimensionality while preserving variance
- **Cluster profiling** to interpret each segment

## 📌 Key Findings

- PCA revealed that the first two principal components explained over **58% of the variance** in the data.
- **KMeans Clustering** identified **five meaningful customer segments** based on purchasing patterns.
- Cluster profiles highlighted clear differences in customer preferences, such as bulk buyers of fresh items vs those with high detergent and grocery purchases.
- These insights can be used to **target marketing efforts** or customize product bundles.

## 🗂️ Repository Contents

- `Unsupervised Learning - Project.ipynb`: Complete project notebook
- `Wholesale_Data.csv`: Raw dataset
- `README.md`: This file

## ✅ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Ikenna1414/ml-project-unsupervised-learning.git


