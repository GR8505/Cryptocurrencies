# Cryptocurrencies
---------------------------------------------------------------------------------------------------
## Executive Summary
---------------------------------------------------------------------------------------------------
--------------------------------------
### Data Preprocessing Tasks Completed
--------------------------------------
1. Removed all cryptocurrencies that were not trading
2. Removed all cryptocurrencies that had no defined Algorithm
3. Removed the IsTrading column
4. Removed all cryptocurrencies with at least one null value
5. Removed all cryptocurrencies without coins mined
6. Created a separate dataframe with all the names of the cryptocurrencies
7. Removed the CoinName column in the original crypto_df dataframe
8. Created dummy variables for the Algorithm and ProofType columns
9. Standardized the dataframe

---------------------------------------------------------------------
### Reducing Data Dimensions Using Principal Component Analysis (PCA)
---------------------------------------------------------------------

Reduced to Three components

![](https://github.com/GR8505/Cryptocurrencies/blob/master/Images/I1.png)

------------------------
### Elbow Curve Analysis
------------------------

![](https://github.com/GR8505/Cryptocurrencies/blob/master/Images/I2.png)

-------------------------------------------------------------------------
### Experimented with values for K=4, K=5 and K=6
-------------------------------------------------------------------------
_Clusters for K=4_

![](https://github.com/GR8505/Cryptocurrencies/blob/master/Images/K4.png)

-------------------------------------------------------------------------
_Clusters for K=5_

![](https://github.com/GR8505/Cryptocurrencies/blob/master/Images/K5.png)

------------------------------------------------------------------------
_Clusters for K=6_

![](https://github.com/GR8505/Cryptocurrencies/blob/master/Images/K6.png)

-------------------------------------------------------------------------

Decided that K=4 was the best option

-----------------------
### Visualizing Results
-----------------------

_3D plot with parameters hover_name="CoinName" and hover_data=["Algorithm"]

![]()
