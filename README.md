# Cryptocurrencies Analysis
---------------------------------------------------------------------------------------------------
<img src="https://github.com/GR8505/Cryptocurrencies/blob/master/Images/Header.jpg" alt="drawing" width="400"/>

## Executive Summary
---------------------------------------------------------------------------------------------------
The main objective of this project was to determine which cryptocurrencies were trading on the market
and to use unsupervised machine learning to see if there are any clusters of cryptocurrencies. 

### Key Findings ###
Four clusters of cryptocurrencies were used.  In the dashboard below, the final page facilitates 
potential investors who are interesting in choosing the right mix of cryptocurrencies based on
_Class_, [_Proof Type_](https://github.com/GR8505/Cryptocurrencies/blob/master/Proof_Type.txt) and [_Algorithm_](https://medium.com/@Mr.dhariwal/cryptocurrency-mining-algorithms-and-popular-cryptocurrencies-48176d3559d6) for their investment portfolio. 

[![Watch the video](https://github.com/GR8505/Cryptocurrencies/blob/master/Images/Dashboard.png)](https://youtu.be/H_gKzovCTaw)
Click above image to view video of Dashboard.

For powerBI users, view [dashboard](https://app.powerbi.com/reportEmbed?reportId=ebda9cad-630a-4262-b10b-df0755e988b7&autoAuth=true&ctid=26a3e96a-449c-4586-88e2-f15b7d132cd5&config=eyJjbHVzdGVyVXJsIjoiaHR0cHM6Ly93YWJpLXVzLWVhc3QtYS1wcmltYXJ5LXJlZGlyZWN0LmFuYWx5c2lzLndpbmRvd3MubmV0LyJ9)



-----------------
### Project Tasks
-----------------
1. Perform dimension reduction using **Principal Component Analysis (PCA)** method and clustering using **K-means**
2. Present my findings

--------------
### Resources
--------------
1. Python 
2. Sklearn
3. Pandas
4. HVplot

-----------------------------
### Data Preprocessing Tasks 
-----------------------------
1. Remove all cryptocurrencies that were not trading
2. Remove all cryptocurrencies that had no defined Algorithm
3. Remove the IsTrading column
4. Remove all cryptocurrencies with at least one null value
5. Remove all cryptocurrencies without coins mined
6. Create a separate dataframe with all the names of the cryptocurrencies
7. Remove the CoinName column in the original crypto_df dataframe
8. Create dummy variables for the Algorithm and ProofType columns
9. Standardize the dataframe

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

Decided that K=4 was the best option

-----------------------
### Visualizing Results
-----------------------

3D plot with parameters hover_name="CoinName" and hover_data=["Algorithm"]

![](https://github.com/GR8505/Cryptocurrencies/blob/master/Images/I3.png)

---------------------------------------------------------------------------

---------------
### References
---------------
[dPoC](https://medium.com/@FiiiLAB/nasdaq-worlds-first-mobile-mining-machine-with-dpoc-of-fiiipos-505124bf42dd)
[PoS](https://academy.binance.com/en/articles/delegated-proof-of-stake-explained)
[PoW](https://academy.binance.com/en/articles/delayed-proof-of-work-explained)
[PoS Guide](https://www.finyear.com/The-Proof-of-Stake-Guidebook-PoS-DPoS-LPoS-BPoS-Kezako_a40716.html)
[PoA](https://academy.binance.com/en/articles/proof-of-authority-explained)
[Other Explantions](https://finance.yahoo.com/news/cryptocurrency-qibuck-coin-offers-passive-043600512.html)


