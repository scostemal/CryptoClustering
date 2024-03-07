# Cryptocurrency Clustering Analysis

## Project Overview
This project aims to cluster cryptocurrencies based on their market data to identify underlying patterns and group similar cryptocurrencies together. By leveraging machine learning techniques such as k-means clustering and Principal Component Analysis (PCA), we analyze and reduce the dimensionality of our dataset to enhance the clustering process.

## Data Source
The dataset comprises various cryptocurrencies and their market data, including price changes, trading volume, and market capitalization. The data is stored in a CSV file named `crypto_market_data.csv`.

## Tools and Libraries Used
- Python 
- Pandas 
- Scikit-learn 
- HvPlot 
- Matplotlib

## Methodology
1. **Feature Scaling**: Use `StandardScaler` from scikit-learn to normalize the features.
2. **Principal Component Analysis (PCA)**: Reduce the dimensionality of the data to the top three principal components.
3. **K-Means Clustering**:
   - Determine the optimal number of clusters (k) using the Elbow method.
   - Apply k-means clustering to both the original and PCA-transformed datasets.
4. **Cluster Analysis**: Analyze the clustering results and interpret the cryptocurrency groupings.


