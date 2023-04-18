# CryptoClustering

Preparing the Data

- I used the StandardScaler() module from scikit-learn to normalize the data from the CSV file and created a DataFrame with the scaled data.

Find the Best Value for k Using the Original Scaled DataFrame

- I used the elbow method to find the best value for k for the scaled data, which was 7.

Cluster Cryptocurrencies with K-means Using the Original Scaled Data

- I clustered the cryptocurrencies for k = 7 on the original scaled data and created a scatterplot of the results.

Optimize Clusters with Principal Component Analysis

- Using the original scaled DataFrame, I performed a PCA and reduced the features to three principal components. The total explained variance of these components was 0.895.

Find the Best Value for k Using the PCA Data

- I used the elbow method on the PCA data to find the best value for k for the PCA data, which was 4. This k-value is different from the original best k-value because we reduced the data to the three principal components.

Cluster Cryptocurrencies with K-means Using the PCA Data

- I clustered the PCA data for k = 4 and created a scatterplot of the results.
- I then created a composite plot of the two elbow graphs and side-by-side scatterplots of the two clustering methods.
- Using fewer features allowed me to cluster the data into fewer groups and in a less complicated way by only using the principal components. There are only a few outliers, and they are essential the same regardless of the number of features.