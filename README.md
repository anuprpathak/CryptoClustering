# CryptoClustering

## Overview ##
Module 11 challenge to apply understanding of the K-means algorithm and principal component analysis (PCA) to classify cryptocurrencies according to their price fluctuations across various timeframes. We examine price changes over intervals spanning 24 hours, 7 days, 30 days, 60 days, 200 days, and 1 year.

### Details ###
1. Prepare the data
     - Use the StandardScaler() module from scikit-learn to normalize the data from the CSV file.
     - Create a DataFrame with the scaled data
2. Find the Best Value for k Using the Original Scaled DataFrame
     - Use the elbow method to find the best value for k
3. Cluster Cryptocurrencies with K-Means Using the Original Scaled Data
     - Cluster the cryptocurrencies for the best value for k on the original scaled data
4. Optimize Clusters with Principal Component Analysis
     - Using the original scaled DataFrame, perform a PCA and reduce the features to three principal components.
     - Retrieve the explained variance to determine how much information can be attributed to each principal component
     - Create a new DataFrame with the PCA data
5. Find the Best Value for k Using the PCA Data
     - Use the elbow method on the PCA data to find the best value for k
6. Cluster Cryptocurrencies with K-Means Using the PCA Data
     - Cluster the cryptocurrencies for the best value for k on the PCA data
     - Create scatter plot for PC1 and PC2 setting the x-axis as "PC1" and the y-axis as "PC2"
7. Determine the Weights of Each Feature on Each Principal Component

All questions are answered in the code file.
