# Implementation

This project loads and cleans a banking dataset, addressing duplicates, inconsistent province names, and missing numeric values. Feature engineering includes encoding categorical fields (digital usage, employment, loan status), creating ratio features such as balance-to-income and loan-to-income, and scaling numeric data to normalize distributions. Clustering is performed using K-Means and hierarchical methods, guided by elbow and silhouette analysis. PCA is applied for dimensionality reduction and visualization. The workflow concludes with exporting labeled datasets and segment summary files for downstream use.

# Key steps
Data cleaning: remove duplicate Customer_IDs, standardize province names, impute missing numeric values.
Feature engineering: encode digital usage, build binary employment and loan flags, create ratio features.
Feature selection: identify clustering features and apply scaling.
Model selection: compute elbow and silhouette metrics to determine optimal cluster count.
Clustering: fit K-Means, profile clusters, and validate with hierarchical clustering.
Visualization: generate distributions, correlation heatmaps, dendrograms, PCA scatter plots, and segment summaries.
Product mapping: assign tailored product recommendations to each customer segment.

# Outcome

The analysis produces a clear segmentation into high-value and vulnerable customer groups. Cluster profiles highlight differences in financial strength, digital engagement, and payment reliability. 
