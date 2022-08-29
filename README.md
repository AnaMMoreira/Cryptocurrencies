# Cryptocurrencies
## Module18

 This module project applied unsupervised learning to cryptocurrency data in order to advise a prominent investment bank client on the development of cryptocurrency investment portfolios for its clients. 
 
An unsupervised learning process will be used to accomplish this which entailed processing of data to fit the machine learning model, clustering, reducing dimensions, and reducing the principal components using PCA.  The client has asked for a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.  

This assignment consists of four technical analysis deliverables:
  1. Preprocessing the Data for PCA
  2. Reducing Data Dimensions Using PCA
  3. Clustering Cryptocurrencies Using K-means
  4. Visualizing Cryptocurrencies Results

## 1. Preprocessing the Data for PCA

  The original dataset starts with 1252 rows of data by 7 columns. See Figure 1A
  
  Figure1A
  !https://github.com/AnaMMoreira/Cryptocurrencies/blob/main/Fig_1A_original_data.png

After cleaning and organizing the data using Pandas as a prerequisite step for PCA the data has been reduced to 532 rows by 5 columns as can be seen in the following Figure 1B

Figure 1B
!https://github.com/AnaMMoreira/Cryptocurrencies/blob/main/Fig_1B_table_cleaned_data.png

## 2. Reducing Data Dimensions Using PCA

After creating variables for Text features and standardizing the data the reduction of data Dimensions into the three principal components for input into PCA is created (see fig 2)

Figure 2
!https://github.com/AnaMMoreira/Cryptocurrencies/blob/main/Fig_2.png

## 3. Clustering Cryptocurrencies Using K-means

Now that the data is ready to be inputted into the model it can divided into clusters using the KMeans function 
Figure 3 shows the resulting Crypto Elbow Curve and it can be determined that the K used in K-Means function should be k=4.

Figure 3
!https://github.com/AnaMMoreira/Cryptocurrencies/blob/main/Fig_3_K_curve.png

## 4. Visualizing Cryptocurrencies Results

Using a k= 4 value in Kmeans model, followed by fitting the model and generating predictions the results is an array of 1,2,3's that is hard to interpret as seen in Figure 4 

Figure 4
!https://github.com/AnaMMoreira/Cryptocurrencies/blob/main/Fig_4_ModelPfit%20and%20predictions.png

but after the original dataframe is rebuilt and can be seen in Figure 5 that the data is starting to look more sensible... and it contains 532 rows of tradeable cryptocurrencies subdivided into 4 different classes containing 6 columns of relevant identifying data.

Figure 5
!https://github.com/AnaMMoreira/Cryptocurrencies/blob/main/Fig_5_dataframePredictions.png

A 3-D graph of the Model predictions is shown in Figure 6

Figure 6
!https://github.com/AnaMMoreira/Cryptocurrencies/blob/main/Fig_6_3DgraphPredictions.png

and a scatter plot of the results shows the relationship between Total Coins Mined vs Total Coin Supply of all the identified tradeable Crypto currencies classes. 

Figure 7
!https://github.com/AnaMMoreira/Cryptocurrencies/blob/main/Fig_7_scatterPredictions.png















