# Clustering Analysis with K-Means
This repository contains a clustering analysis project using the K-Means algorithm. The notebook **ML_Clustering_2.ipynb** provides a step-by-step implementation of K-Means clustering, including data preprocessing, determining the optimal number of clusters using the Elbow method, and visualizing the clustering results.

## Project Overview
In this project, we focus on grouping data points into clusters based on their similarities. The notebook includes the following key steps:

**1. Data Preprocessing**:

Load and preprocess the dataset to prepare it for clustering. This involves selecting relevant features and scaling the data as necessary.

**2. Elbow Method**:

The Elbow method is applied to determine the optimal number of clusters by plotting the Within-Cluster Sum of Square (WCSS) against the number of clusters.

**3. K-Means Clustering**:

The K-Means algorithm is implemented to cluster the data into the optimal number of clusters identified by the Elbow method. The results are then visualized, showing how the data points are grouped.

**4. Interpretation**:

The optimal number of clusters is determined to be 4, based on the point where the Elbow curve begins to flatten.

## Requirements
The following Python libraries are required to run the notebook:

- Pandas
- Numpy
- Matplotlib
- Scikit-learn

## Results
The notebook provides a detailed visualization of the K-Means clustering results, illustrating the grouping of data points into four distinct clusters.

## Conclusion
This project showcases the application of the K-Means clustering algorithm to segment data into clusters. The Elbow method was used to determine the optimal number of clusters, and the final results highlight how K-Means can be used effectively for clustering tasks.
