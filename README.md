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

### Results

The project includes the following visualizations:

Elbow curve for the original data.
![230554676-7874d2ec-2c98-483a-9ec8-b9d48734ea8c](https://github.com/KaranAnand87/Module-19-CryptoClustering/assets/120350694/06a66e25-b48c-455c-b3d4-e93c501a96f5)

Elbow curve for the PCA data.
![230554807-3b127039-76ba-4bef-a55f-53fcbc34fdb2](https://github.com/KaranAnand87/Module-19-CryptoClustering/assets/120350694/119713ae-9b12-41f9-9dcc-64233ea91d88)

Scatter plot of cryptocurrency clusters based on the original data.
![230555099-7bbc97d3-e218-49f3-89af-f276e1631ead](https://github.com/KaranAnand87/Module-19-CryptoClustering/assets/120350694/b327cc92-2e61-4567-9ba8-8de3d5b332ff)

Scatter plot of cryptocurrency clusters based on the PCA data.
![230555151-77b912b3-e036-45ad-b7ef-974caf18f869](https://github.com/KaranAnand87/Module-19-CryptoClustering/assets/120350694/d68483e4-5124-4bb7-9bca-fb586485d5de)


### Conclusion

The project analyzes the impact of using fewer features on clustering the data using K-means. Comparing the clustering results of the original data and the PCA data helps to understand the effect of dimensionality reduction on the clustering process.

### Dependencies

Python
pandas
NumPy
scikit-learn
hvPlot
