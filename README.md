# Cryptocurrencies
Module 19
### Purpose of Project
Using unsupervised machine model, create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for the new investment.
### Results
First step is to clean up raw data by filtering the tradable and mined cryptocurrencies greater than 0. Once a clean dataframe is available, the data with "Algorithm", "ProofType" are splited and recoded into categorized with binary features. </br>
After standardization and scaled, I reduced dimentions by creating a new dataframe with 3 principle components. The best K-means is found by identifying elbow curves. In this case, the best K-means is 4 so now I am able to fit into the prediction model using clusters number of 4. </br>
Afterward, a better visualization is to add model into a 3 dimensional scatter plot, as follwing image, the result suggests that class 0 and 3 act very similar with only class 0 having outliers. Class 2 has the closest result, in contrast, there are more variance found in class 1. </br>  
![image](https://github.com/jilldvn/Cryptocurrencies/blob/430500bdf6ba4d8bd097cfe01512610381b3878a/image/model.png)

Finaly, the model is transformed into two dimensional scatter plot, with seen below, it is observed the class 2 and 0 have less distincted outcomes in total coins mined instead, there is more variety in terms of total coin mined in class 3. </br>
![image](https://github.com/jilldvn/Cryptocurrencies/blob/main/image/mined%20coins%20scatter%20plot.png)
