# Cryptocurrencies Investment Analysis

## Description

This project uses KMeans as an unsupervised machine learning model to break the cryptocurrency data into clusters and find patterns in the data. The result is then visualized for presentation.

## Process

In order to run the KMeans model on the data, the following steps were taken:

    1) Pre-processing 

        - Removed non-trading cryptocurrencies
        - Removed all cryptovurrencies with no defined algorithm
        - Removed null values.
        - Removed all cryptocurrencies with no coins mined.
        - Changed TotalCoinSupply data type to integer.
        - Created dummies variables for text features.
        - Scaled data using StandardScaler.

    2) Reduced feature dimensions to 3 principal components using PCA module

    3) Clustering Cryptocurrencies Using KMeans

        - Created an elbow curve to find the optimal number of clusters
    
    4) Visualizing Results

        - Created a 3D scatter plot for all 4 classes using the 3 principal components
        - Created a pivot table for current tradable cryptocurrencies
        - Created a 2D scatter plot to present the clusters on Total Coins Mind axis vs. Total Coin Supply axis.

## Tools

The modules used in this project are listed as below:

    - Pandas
    - plotly.express
    - hvplot.plotly
    - KMeans,StandardScaler and PCA  from sklearn
   
