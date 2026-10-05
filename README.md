# Iris Flower Clustering & Dimensionality Reduction (K-Means & PCA)

## 📌 Overview
This repository contains the **Week 3 Unsupervised Machine Learning** project focused on cluster analysis and dimensionality reduction. Using the classic **Iris Dataset**, the goal is to partition flowers into distinct clusters based on physical measurements without using prior species labels, and project the 4D feature space into 2D for visual evaluation.

---

## 🛠️ Assignment Tasks & Objectives

1. **Feature Standardization**:
   * Applied `StandardScaler` to normalize feature distributions (`SepalLength`, `SepalWidth`, `PetalLength`, `PetalWidth`) prior to computing Euclidean distances.
2. **K-Means Clustering ($k=3$)**:
   * Fit a `KMeans` algorithm with 3 clusters to segment the flowers into natural groupings.
3. **Dimensionality Reduction (PCA)**:
   * Used **Principal Component Analysis (PCA)** to reduce the 4 numerical dimensions down to 2 principal components (`PCA1` and `PCA2`).
   * Retained over **95%** of total dataset variance in 2D space.
4. **Cluster Evaluation & Visualization**:
   * Cross-tabulated predicted cluster assignments against ground truth species labels.
   * Generated side-by-side scatter plots comparing K-Means clusters against actual species in PCA space using `Seaborn`.

---

## 📊 Results Summary

* **PCA Variance Ratio**:
  * **PC 1**: ~72.77% variance explained
  * **PC 2**: ~23.03% variance explained
  * **Total Variance Retained**: **~95.80%**
* **Clustering Analysis**:
  * *Setosa* forms a perfectly distinct, isolated cluster in 2D space.
  * *Versicolor* and *Virginica* show slight overlap along the decision boundaries, accurately reflected by the K-Means cluster assignments.

---

## 🚀 How to Run the Project Locally

1. **Clone the Repository**:
   ```bash
   git clone [https://github.com/mahima5080/Iris-Flower-Clustering-KMeans-PCA.git](https://github.com/mahima5080/Iris-Flower-Clustering-KMeans-PCA.git)
   cd Iris-Flower-Clustering-KMeans-PCA
