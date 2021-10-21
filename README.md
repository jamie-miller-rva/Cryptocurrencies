# Crypto Currencies Analysis using Clustering

* webpage: [webpage](https://jamie-miller-rva.github.io/Cryptocurrencies/)

* github repo: [github repo](https://github.com/jamie-miller-rva/Cryptocurrencies)


# Background:
Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. However, the company is lost in the vast universe of cryptocurrencies. 

# Problem Statement:
Identify what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

# Deliverables:
* Deliverable 1: Preprocessing the Data for PCA
* Deliverable 2: Reducing Data Dimensions Using PCA
* Deliverable 3: Clustering Cryptocurrencies Using K-means
* Deliverable 4: Visualizing Cryptocurrencies Results

## There are 532 total tradable crypto currencies in the dataset

## A table of the 532 crypto currencies currencies is available at the following link:
[link to crypto_table](https://jamie-miller-rva.github.io/crypto_table/)
also available in the notebook

![crypto_table](./Images/Crypto_table.png)


## A 3D Visualization of the 532 crypto currencies along 3 principal components (via Pincipal Component Analysis)
The visualization groups the 532 crypto currencies into one of four groups using KMeans analysis to view similarities (or differences)
see the notebook for an interactive visualization

![crypto_in_3d](./Images/fig1.svg)

## A Grouping of Crypto Currencies on a Scatter Plot of TotalCoinsMined vs. TotalCoinsSupply (scaled using StandardScaler)
The visualization groups the 532 crypto currencies into one of four groups using KMeans analysis. The values of TotalCoinsMined and TotalCoinsSupply are Standardized to a scale between 0 and 1 to assist in visualizing the differences between groups
see the notebook for an interactive visualization

![crypto scatterplot](./Images/Crypto_ScatterPlot.png)
