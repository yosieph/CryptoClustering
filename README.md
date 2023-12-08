# CryptoClustering

Crypto Clustering

Overview

The Crypto Clustering project aims to predict if cryptocurrencies are affected by 24-hour or 7-day price changes using unsupervised learning techniques, specifically K-means clustering. Additionally, the project explores the impact of dimensionality reduction using Principal Component Analysis (PCA) on clustering.

Steps

1)Load and preprocess the data.
2)Scale the data using StandardScaler.
3)Find the best value for k using the elbow method.
4)Cluster cryptocurrencies with K-means using the original scaled data.
5)Perform PCA to reduce the features to three principal components.
6)Find the best value for k using the PCA data.
7)Cluster cryptocurrencies with K-means using the PCA data.
8)Visualize and compare the results using hvPlot.

Results

The project includes the following visualizations:

1.Elbow curve for the original data.
![Elbow Curve one](https://github.com/yosieph/CryptoClustering/assets/85768490/80052cd8-a7b4-4fba-906e-3612693c92c5)


2.Elbow curve for the PCA data.

![ElbowCurveTwo](https://github.com/yosieph/CryptoClustering/assets/85768490/6fa2081b-b8af-41e2-be8e-49163fb53b56)

3.Scatter plot of cryptocurrency clusters based on the original data.

![ElbowCurve_3](https://github.com/yosieph/CryptoClustering/assets/85768490/451c20c0-377a-4e90-87ab-eb72f3a7fd64)


4.Scatter plot of cryptocurrency clusters based on the PCA data.
![ElbowCurve_4](https://github.com/yosieph/CryptoClustering/assets/85768490/b0e0e738-f8fb-4d17-b675-cca3b2d4dda6)



Conclusion

The project analyzes the impact of using fewer features on clustering the data using K-means. Comparing the clustering results of the original data and the PCA data helps to understand the effect of dimensionality reduction on the clustering process.

Dependencies

    Python
    pandas
    NumPy
    scikit-learn
    hvPlot
