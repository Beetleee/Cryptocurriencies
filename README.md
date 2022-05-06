# Module 18 Cryptocurrencies
### by Terra Lasho 
## Overview of the Analysis: For this project, I am tasked with creating a report that includes what cryptocurrencies are on the trading market and how they can be classified for a potential new investment.  I will first need to pre-process the raw data, and then fit it into several machine learning models (using unsupervised with clustering) with the results containing several output visualizations.
-----------------------------------------------------------------------------------------------------------------------------------
## Flow:  This project had 4 Deliverables:
------------------------------------------------------------------------------------------------------------------------------------
### - Deliverable 1: Preprocessing the Data for PCA
### - Deliverable 2: Reducing Data Dimensions Using PCA
### - Deliverable 3: Clustering Cryptocurrencies Using K-means
### - Deliverable 4: Visualizing Cryptocurrencies Results
-----------------------------------------------------------------------------------------------------------------------------------
## Results
## Deliverable 1: Preprocessing the Data for PCA
-	Part 1: I first pulled in the cryptocurrency .csv into a pandas dataframe:
![](https://github.com/Beetleee/Cryptocurriencies/blob/main/Resources/Plot1.png)

-	Part 2: After cleaning it up, I looked like this:
![](https://github.com/Beetleee/Cryptocurriencies/blob/main/Resources/Plot2.png)

-	Part 3: Finally, I used the StandardScaler (code)
![](https://github.com/Beetleee/Cryptocurriencies/blob/main/Resources/Plot3.png)


## Deliverable 2: Reducing Data Dimensions Using PCA
-	For this, I created a PCA dataframe using 3 principal components: 

![] (https://github.com/Beetleee/Cryptocurriencies/blob/main/Resources/Plot4.png)
![](https://github.com/Beetleee/Cryptocurriencies/blob/main/Resources/Plot4_5.png)


## Deliverable 3: Clustering Cryptocurrencies Using K-means
-	Part 1, I created an elbow chart to find the best fit value for K:
![](https://github.com/Beetleee/Cryptocurriencies/blob/main/Resources/Plot5.png)
![](https://github.com/Beetleee/Cryptocurriencies/blob/main/Resources/Plot5_5.png)
-	Part 2, I ran a K-means, using the projected 4 clusters, and created a new dataframe including these predicted cluster and features:

![](https://github.com/Beetleee/Cryptocurriencies/blob/main/Resources/Plot6.png)

## Deliverable 4: Visualizing Cryptocurrencies Results
-	For this, I created a 3-D scatter chart visual which contained the 3 principal components, and created a hvplot.table for functionality.

![](https://github.com/Beetleee/Cryptocurriencies/blob/main/Resources/Plot7.png)


-	Finally, I used a 2-D scatter plot to look at the relationship between Total Coin Supply and Total Coins Mined 

![](https://github.com/Beetleee/Cryptocurriencies/blob/main/Resources/Plot8.png)


-----------------------------------------------------------------------------------------------------------------------------------------

## Summary:
I was able to provide the client with a complete list of cryptocurrencies being traded and classified them into 4 clusters.
