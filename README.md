# Cryptocurrencies
# Overview
The purpose of this analysis is to use unsupervised machine learning to analyze a database of cryptocurrencies and generate a report showing the traded cryptocurrencies classified by group based on their features.
This processed classification report could be used by a prominent investment bank to offer a new cryptocurrency investment portfolio to its customers.
This project consists of four technical analysis deliverables:
* preprocessing the database;
* reducing the data dimension using Principal Component Analysis;
* clustering cryptocurrencies using K-means and 
* visualizing cryptocurrencies results with 3D-Scatter and hvplot.scatter plots.
# Results
Following the preprocessing and cleaning processes, there are 532 tradable cryptocurrencies.

## Clustering Crytocurrencies Using K-Means - Elbow Curve
An Elbow curve was generated using the reduced dataset to determine the number of clusters.

## Visualizing Cryptocurrencies Results
The 3D-Scatter plot was obtained using the cleaned PCA data and clusters.
The outlier is the currency that belongs to class 2.

## Tradable Cryptocurrencies Table
Most of the cryptocurrencies belong to classes 0 and 3.

## hvplot.scatter plot with TotalCoinsMined and TotalCoinSupply
Plotting the hvplot.scatter plot from two cryptocurrency features does not efficiently segregate the different classes. Therefore, using the 3D-Scatter plot is the right method for better visualizations.
# Summary
Following the preprocessing and cleaning processes, there are 532 tradable cryptocurrencies based on similarities of their features.
