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

#### Clustering Crytocurrencies Using K-Means - Elbow Curve
An Elbow curve was generated using the reduced dataset to determine the number of clusters.
According to the elbow curve below, the best k value appears to be 4 so we would conclude on an output of 4 clusters to categorize the crytocurrencies.



![elbow curve](https://user-images.githubusercontent.com/104453593/189487723-4b826b9f-a52d-48fd-b95e-64db1298f3f6.PNG)



#### Visualizing Cryptocurrencies Results
The 3D-Scatter plot was obtained using the cleaned PCA data and clusters.
According to the 3D-Scatter below, the outlier is the currency that belongs to class 3.


![3d-scatter plot](https://user-images.githubusercontent.com/104453593/189487748-5a4718cc-f262-4df5-b2f1-a65eec49db3c.PNG)




#### Tradable Cryptocurrencies Table
Accoring to the Tradable Cryptocurrencies table below, most of the cryptocurrencies belong to classes 0 and 1.


![tradable table](https://user-images.githubusercontent.com/104453593/189487763-9910b365-1659-43ba-aef3-ac644c49e494.PNG)




#### hvplot.scatter plot with TotalCoinSupply vs TotalCoinsMined
Plotting the hvplot.scatter plot from two cryptocurrency features does not efficiently segregate the different classes. Therefore, using the 3D-Scatter plot is the right method for better visualizations.

![2d-plot](https://user-images.githubusercontent.com/104453593/189487768-31f42e82-73c7-4d98-992c-c3d490110c6c.PNG)





# Summary
Following the preprocessing and cleaning processes, there are 532 tradable cryptocurrencies based on similarities of their features.
