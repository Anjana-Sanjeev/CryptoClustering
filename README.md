# CryptoClustering


* In this Repo, you can find the following files:
    * The Resources folder contains the data used for the analysis.
    * The "Crypto_Clustering.ipynb" is the main script for the analysis.

## Summary

* Prepare the Data using the StandardScaler() module from scikit-learn to normalize the data from the CSV file.
* Create a DataFrame with the scaled data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.
* Find the Best Value for k Using the Original Scaled DataFrame using the elbow method.
* Plot a line chart with all the inertia values computed with the different values of k to visually identify the optimal value for k.
* Cluster the cryptocurrencies for the best value for k on the original scaled data and create a scatter plot using hvPlot.
* Optimise Clusters with Principal Component Analysis.
* Find the Best Value for k Using the PCA Data using the elbow method.
* Plot a line chart with all the inertia values computed with the different values of k to visually identify the optimal value for k.
* Cluster Cryptocurrencies with K-means Using the PCA Data and create a scatter plot using hvPlot.
* Create a composite plot and compare.



