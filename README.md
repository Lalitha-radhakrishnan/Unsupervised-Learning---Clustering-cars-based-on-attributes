# Unsupervised-Learning---Clustering-cars-based-on-attributes
Analyzed cars dataset and performed exploratory data analysis and then categorized them using K means clustering. Used linear regression on the different clusters and estimated coefficients. Skills and Tools: K means clustering, Hierarchical clustering, EDA, Linear Regression

The Car dataset was used in the 1983 American Statistical Association Exposition. The data concerns city-cycle fuel consumption in miles per gallon, to be predicted in terms of 2 multivalued discrete and 4 continuous variables.
Dataset: cars-dataset.csv
Attribute Information:
Car Name – Name of the car Cyl – No of cylinders in the car – Multivalued discrete Disp – Displacement – continuous Hp – Horsepower – continuous Wt – Weight – continuous Acc – Accleration – continuous Yr – Model of the car – Multivalued discrete

Steps to follow:
EDA & Pre-processing (Make sure to remove all non-numeric entries from numeric columns) 
Use pair plot or scatter matrix to visualize how the different variables are related (Hint: The amount of Gaussian curves in the plot should give a visual identification of different clusters existing in the dataset) 
Use K Means or Hierarchical clustering to find out the optimal no of clusters in the data. Identify and separate the clusters
Use linear regression model on different clusters separately and print the coefficients of the models individually 
