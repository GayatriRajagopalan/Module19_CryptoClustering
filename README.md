# CryptoClustering

## Project Overview

This project applies unsupervised machine learning techniques to cluster cryptocurrencies based on their market performance. The analysis uses the K-Means algorithm and Principal Component Analysis (PCA) to optimize clustering.

## Technologies Used

Python

Pandas

Scikit-learn

hvPlot

Matplotlib

## Files Included

Crypto_Clustering.ipynb: Jupyter Notebook containing the full analysis and implementation.

crypto_market_data.csv: Dataset containing cryptocurrency market performance data.

## Data Preparation

Load the crypto_market_data.csv file into a DataFrame.

Generate summary statistics and visualize the data.

Normalize the data using StandardScaler.

Set the "coin_id" as the index for the scaled DataFrame.

## Clustering with K-Means

### Finding the Optimal k

Apply the elbow method to determine the best k value.

Plot inertia values for k values from 1 to 11.

Identify the optimal k visually.

## K-Means Clustering

Initialize and fit the K-Means model with the best k value.

Predict cryptocurrency clusters.

Create a scatter plot visualizing the clusters.

## Principal Component Analysis (PCA)

Reduce the feature set to three principal components.

Analyze explained variance.

Transform data using PCA and re-cluster with K-Means.

Compare clustering results with the original dataset.

## Results and Insights

The elbow method determines the best k value for both the original and PCA-transformed data.

PCA improves efficiency by reducing dimensionality while maintaining variance.

Clustering results may differ based on the feature set used.
