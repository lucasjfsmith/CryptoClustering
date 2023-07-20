# CryptoClustering
Using Python and unsupervised learning (via scikit-learn), predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

## Prepare Data
Use the StandardScalar module to create a scaled DataFrame with `coin_id` as the index

## Find Optimal K for K-means Clustering and Cluster
* Use the elbow test and find and plot inertia values for k in range 1 to 11
* Fit model with optimal k
* Plot clusters

## Optimize with PCA
* Repeat above steps after using PCA to reduce to three features


