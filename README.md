# Clustering Project: Digital Ads Data Analysis

## Introduction

The ads24x7 is a Digital Marketing company that has received seed funding of $10 Million. They are expanding into Marketing Analytics and have provided data to segment types of ads based on specific features. This project involves using clustering procedures to group ads into homogeneous segments.

## Dataset

The dataset contains information on digital ads, including features like CPM (Cost Per Mille), CPC (Cost Per Click), and CTR (Click-Through Rate). The data dictionary and formulas for these metrics are provided in Sheet 2 of the Clustering Clean ads_data Excel File.

## Project Steps

1. **Data Exploration**
   - Read and perform basic analysis on the data, including printing a few rows, summary statistics, and checking for missing or duplicate values.

2. **Missing Values Treatment**
   - Impute missing values in CPC, CTR, and CPM using the provided formulas. Create a user-defined function for this purpose.

3. **Outlier Analysis**
   - Identify if there are any outliers in the data. Evaluate if treating outliers is necessary for K-Means clustering. Your decision may vary based on your domain expertise.

4. **Z-Score Scaling**
   - Apply Z-score scaling to standardize the data and discuss its impact on the speed of the clustering algorithm.

5. **Clustering**
   - Perform Hierarchical clustering by constructing a Dendrogram using WARD and Euclidean distance.
   - Generate Elbow plots (up to n=10) to identify the optimum number of clusters for K-Means algorithm.
   - Print silhouette scores for up to 10 clusters and identify the optimum number of clusters.

6. **Cluster Profiling**
   - Profile the ads based on the optimum number of clusters using silhouette score and domain understanding. Group the data by clusters and analyze trends in clicks, spend, revenue, CPM, CTR, and CPC based on Device Type. Create bar plots for visualization.

7. **Conclusion and Summary**
   - Provide a summary of the project, including key findings, insights, and any recommendations for the ads24x7 company based on the clustering analysis.

