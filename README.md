# Module-19-CryptoClustering
### Overview

The Crypto Clustering project aims to predict if cryptocurrencies are affected by 24-hour or 7-day price changes using unsupervised learning techniques, specifically K-means clustering. Additionally, the project explores the impact of dimensionality reduction using Principal Component Analysis (PCA) on clustering.

### Steps

1. Load and preprocess the data.
2. Scale the data using StandardScaler.
3. Find the best value for k using the elbow method.
4. Cluster cryptocurrencies with K-means using the original scaled data.
5. Perform PCA to reduce the features to three principal components.
6. Find the best value for k using the PCA data.
7. Cluster cryptocurrencies with K-means using the PCA data.
8. Visualize and compare the results using hvPlot.


### Conclusion

After examining the cluster analysis results visually, it appears that reducing the number of features used to cluster the data using K-Means had a significant impact. In the initial plot, which depicted the original data clustering, the elbow curve indicated that the optimal value for K was 4, resulting in 4 clusters. However, there were two clusters that only contained one data point each, and the other two clusters were not clearly separated. By implementing PPCA and using the optimal value for K of 2, the resulting plot was more accurate and precise in clustering the data.

The project analyzes the impact of using fewer features on clustering the data using K-means. Comparing the clustering results of the original data and the PCA data helps to understand the effect of dimensionality reduction on the clustering process.

### Dependencies

Python
pandas
NumPy
scikit-learn
hvPlot
