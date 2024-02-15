# Advanced Cryptocurrency Clustering Analysis

## Overview

This project leverages Python and unsupervised learning techniques to investigate how cryptocurrencies are influenced by their price changes over 24-hour and 7-day periods. As a part of the CryptoClustering initiative, this analysis aims to provide insights into the behavior of cryptocurrencies in response to short-term market dynamics.

### Objective

The primary goal is to utilize clustering algorithms to categorize cryptocurrencies based on their recent price changes, thereby identifying patterns that might not be immediately apparent. This project involves the following key steps:

- **Data Preparation:** Load and normalize the cryptocurrency market data for analysis.
- **Clustering Analysis:** Apply K-means clustering to group cryptocurrencies based on their market behavior.
- **Optimization with PCA:** Enhance clustering performance through Principal Component Analysis (PCA) by reducing feature dimensions.
- **Evaluation:** Determine the optimal number of clusters (k) and analyze the clustering results.

### Methodology

#### Data Preparation

- Loaded the `crypto_market_data.csv` into a DataFrame for initial analysis.
- Normalized the data using `StandardScaler` from scikit-learn to ensure uniformity for clustering analysis.

#### Clustering Analysis

- Implemented the elbow method to identify the optimal value for k.
- Conducted K-means clustering on the scaled data to categorize cryptocurrencies.

#### Optimization with PCA

- Applied PCA to the scaled data, reducing it to three principal components to simplify the dataset while retaining significant variance.
- Repeated the K-means clustering using the PCA-transformed data to optimize clustering results.

### Key Findings

- Identified the best value for k using the elbow method, indicating the most suitable number of clusters for our data.
- The clustering analysis revealed distinct groups of cryptocurrencies based on their 24-hour and 7-day price changes.
- PCA optimization showed that reducing the number of features can still yield meaningful clustering while simplifying the dataset.

### Conclusion

The Advanced Cryptocurrency Clustering Analysis project underscores the potential of unsupervised learning in uncovering market dynamics in the cryptocurrency domain. By employing clustering techniques, we have gained valuable insights into how different cryptocurrencies respond to market changes, providing a foundation for further research and investment strategies.
