# Dimensionality Reduction, Clustering, and Visualization

## Overview
This project involves cleansing and pre-processing the California housing dataset, performing dimensionality reduction and clustering, and visualizing the data to offer insights. The aim is to transform raw, messy data into meaningful insights.

## Dataset
The dataset used is the California housing dataset, which contains housing information in different districts of California and the corresponding median price of houses in each district. Each row in the dataset corresponds to a district, providing a summary of all houses in that district based on the 1990 census data.

## Project Workflow
### 1. Data Discovery and Dimensionality Reduction
#### (a) Feature Analysis
- Identified features that are most helpful for clustering using visualizations such as histograms and pairwise plots.
- Analyzed the distributions and relationships between features to select the most relevant ones.

#### (b) PCA Dimensionality Reduction
- Performed Principal Component Analysis (PCA) to reduce the dimensionality of the dataset.
- Determined the optimal number of PCA components to visualize the data best.

#### (c) Outliers Identification
- Produced 2D and 3D scatterplots of the data to identify outliers.
- Established a rule to filter out the outliers based on visual inspection.

#### (d) Outliers Removal
- Removed large outliers and confirmed their removal by retraining and re-plotting both 2D and 3D scatterplots for the filtered data.

### 2. Clustering
#### (a) Elbow Plot
- Created an elbow plot to determine the optimal number of clusters by plotting the within-cluster sum of squares against the number of clusters.

#### (b) Silhouette Score Explanation
- Explained the utility of the silhouette score in determining the quality of clustering and the optimal number of clusters.

#### (c) Silhouette Score Plot
- Plotted the silhouette score against the number of clusters to further validate the optimal number of clusters.

#### (d) 3D Scatter Plot Clustering
- Ran the k-means algorithm with different numbers of clusters and plotted the data in 3D scatterplots.
- Inspected the clusters formed at each step and validated the optimal number of clusters visually.

## Visualizations
Included in the Jupyter notebook are various visualizations such as:
- Histograms and pairwise plots for initial feature analysis.
- 2D and 3D scatterplots for PCA and outlier analysis.
- Elbow plot and silhouette score plot for determining the optimal number of clusters.
- 3D scatterplots of clustered data for visual inspection and validation.

## Dependencies
- Python
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
