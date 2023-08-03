# CryptoClustering

1. Load the crypto_market_data.csv into a DataFrame.

2. Get the summary statistics and plot the data to see what the data looks like before proceeding.

3. Prepare the da using the StandardScaler() module from scikit-learn to normalize the data from the CSV file.

    - Create a DataFrame with the scaled data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.

4. Find the Best Value for k Using the Original Scaled DataFrame
    - Use the elbow method to find the best value for k

5. Cluster Cryptocurrencies with K-means Using the Original Scaled Data

6. Optimize Clusters with Principal Component Analysis
    - Using the original scaled DataFrame, perform a PCA and reduce the features to three principal components.
    - Retrieve the explained variance to determine how much information can be attributed to each principal component and then answer the following question in your notebook:
    - Create a new DataFrame with the PCA data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.

7. Find the Best Value for k Using the PCA Data
    - Use the elbow method on the PCA data to find the best value for k

8. Cluster Cryptocurrencies with K-means Using the PCA Data

9. Answer the following question:
    - What is the impact of using fewer features to cluster the data using K-Means?