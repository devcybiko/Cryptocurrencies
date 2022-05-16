# Cryptocurrencies

In this project we analyze the tradability of different cryptocurrencies. The data were provided by CryptoCompare.com.

## Overview:

We preprocessed the data by removing NaN values, removed rows where no coins were mined, and removed the CoinName column.

Then we used Principle Component Analysis (PCA) to reduce the dimensionality of the data to three dimensions.

We then plotted the dataset using an Elbow Curve to determine the best value for K-Means (4). And ran the K-Means algorithm to make preditions of the 4 clusters for cryptocurrency data.

Finally, we created a 3D scatter plot to plot our cluster data and a 2D scatter plot to compare the TotalCoinsMined against the TotalCoinSupply.

## Conclusions:

We find that BitTorrent is in a "class by itself" (Class 3) having both the most Total Coins Mined and most Total Coin Supply. But Class 2: BiblePay, LightCoinCash, and "Acute Angle Cloud" have the distinction of nearly no Supply and none Mined.

The other two classes are separated by a dimension we haven't analyzed. If you look at the 3D scatter plot, Class0 and Class1 are clearly distinct clusters. This implies that either Algorithm or ProofType separates these two classes. Further study will be needed to determine what defines these groups.