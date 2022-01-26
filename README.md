# Cryptocurrencies

## Summary
This project was to use Unsupervised Machine Learning to cluster data for cryptocurrencies on the trading market, and see how they can be grouped to create a classification system.

In order to do this, first the data needed to be pre-processed using basic data cleaning processes. These included, but were not limited to, dropping columns and null values, using the `get_dummies()` method to create variables for text values, and using StandardScaler to standardize values.

Next, PCA was used to reduce data dimensions to three principal components.

The pre-processed cryptocurrency data was then clustered using the K-means algorithm.

Finally these clusters were visualized using `hv.plot` and `scatter_3d()`.
