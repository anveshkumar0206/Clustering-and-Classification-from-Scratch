# Clustering-and-Classification-from-Scratch

This project has implementations for basic unsupervised and supervised machine-learning algorithms such as **K-Means Clustering**, **K-Means++ Clustering**, and **K-Nearest Neighbors (KNN) Classification** and implemented from the ground-up utilizing solely NumPy, Pandas, and Matplotlib. No scikit-learn ML libraries were used at all.

## Files Used

`Clustering.ipynb`- The complete solution including:
  - K-Means implementation (with centroid plotting across iterations)
  - K-Means++ enhanced clustering
  - KNN classification based on previously clustered data
`cluster_data1.csv`: Input dataset for clustering tasks
`cluster_data2.csv`: Input dataset for classification using KNN

## Problem Overview

1. K-Means Clustering
- Implemented the K-Means algorithm from scratch.
- Used a fixed random seed of `123`.
- Clustered `cluster_data1.csv` into **K=3** clusters.
- Plotted cluster assignments and centroids at initialization and after each of the first 4 iterations.
- Visualization used `X1` and `X2` as the 2D projection.

2. K-Means++ Clustering
- Implemented K-Means++ to improve centroid initialization.
- Same dataset and clustering conditions as Problem 1.
- Tracked and plotted centroid movement and cluster formation through the first 5 steps.

3. KNN Classification
- Implemented a K-Nearest Neighbors classifier from scratch using Euclidean distance.
- Applied KNN to classify new points in `cluster_data2.csv`, using cluster labels obtained from K-Means++.
- Demonstrated accurate classification by comparing cluster assignments.

## Restrictions followed
To comply used **only NumPy, Pandas, and Matplotlib** were used. No machine learning libraries (e.g., scikit-learn) were utilized.

## Visual Output
Each clustering method includes 2D scatter plots visualizing:
- Data point cluster assignment
- Centroid location over multiple iterations
- Cluster separation clarity

## Requirements: Python 3.x, NumPy, Pandas, Matplotlib

## How to Use the file
1. Clone this repository
2. Open `Clustering.ipynb` in Jupyter Notebook or VSCode
3. Run each cell step-by-step to observe algorithm behavior and visualizations
