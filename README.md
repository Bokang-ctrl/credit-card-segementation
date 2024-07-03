## credit-card-segmentation

# Overview
This repository contains a dataset and Jupyter Notebook for credit card segmentation using 3 different models: DBSCAN, HDBSCAN, and KMeans clustering algorithms. The project aims to segment credit card users based on their spending behavior, allowing for targeted marketing strategies and personalized customer experiences.

# Notebook Content
Data Cleaning: The notebook begins with data exploration and data cleaning steps to handle missing values, outliers, and other inconsistencies in the credit card dataset. 

Power Transformation: After data cleaning, a Power Transformation is applied to the features to deal with skewed data and normalize the distribution.

Data Scaling: Following data cleaning, the dataset is scaled using standardization or normalization techniques to ensure uniformity in feature scales.

Principal Component Analysis (PCA): PCA is applied to reduce the dimensionality of the dataset while preserving its variance. This step helps in visualizing the data and improving clustering performance.

KMeans Clustering: Train KMeans clustering model on the preprocessed dataset to group credit card users into distinct segments based on their spending behavior.

DBSCAN Clustering: Additionally, DBSCAN clustering is employed to identify dense regions in the data and classify data points as core points, border points, or outliers.

HDBSCAN Clustering:** HDBSCAN clustering is also used to identify clusters of varying densities and provides a robust alternative to DBSCAN.

# Methodology
Data Cleaning: Handle missing values, check outliers(kept them), and data inconsistencies to prepare the dataset for clustering analysis.

Power Transformation: Normalize the data distribution and fix skewness.

Data Scaling: Scale the features of the dataset to ensure uniformity in feature scales, enhancing the performance of clustering algorithms.

Principal Component Analysis (PCA): Reduce the dimensionality of the dataset using PCA to improve computational efficiency and visualization.

Clustering Algorithms: Train KMeans, DBSCAN and HDBSCAN clustering models to segment credit card users based on their spending behavior.

# Note
It's recommended to experiment with different data preprocessing techniques, clustering algorithms, and hyperparameters to optimize segmentation results based on specific business requirements.
Consider the interpretability and stability of clusters generated by different clustering algorithms when evaluating segmentation performance.

# Licensing
This project is licensed under the Apache License 2.0 - see the LICENSE file for details.

# Acknowledgements
The credit card dataset used in this project is sourced from Kaggle. Special thanks to them for making it publicly available.
