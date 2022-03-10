# ANALYSIS-SP500
Using pca and transformations to analyze s&p dataset.

1. [General](#General)
    - [Background](#background)
2. [Installation](#installation)
3. [Footnote](#footnote)

## General
We used s&p database to find outliers. Due the number of variables, we had to take actions to change the dataset to spot ones and to use to database in general.

### Background
The data is formed from two files:
* Prices - Includes stock symbol, volume and for each day open, close and high prices. The data is ranging 2010 to 2016.
* Securities - Has additional information about the stocks. It includes the stock sector, sub industry, address of headquarters, security, and filling type.

PCA - which stands for Principal Component Analysis is used to represent multivariate data as a new dataset with less variables in order view trades, outliers, and clusters.

## Installation
I will use google as an example, but similar process can be performed on other notebook editors
1. Open google Colab
2. Clone the project by:
	```
	!git clone https://github.com/elaysason/ANALYSIS-SP500.git
	```
	<img src="https://i.imgur.com/2O2HNRT.png" data-canonical-src="https://gyazo.com/eb5c5741b6a9a16c692170a41a49c858.png" width=40% height=40% />

3. Now the folder is in your files on colab. Simpily download the notebook as showed
    <img src="https://i.imgur.com/cnMCaPx.png" data-canonical-src="https://gyazo.com/eb5c5741b6a9a16c692170a41a49c858.png" width=30% height=30% />

## Footnote
The exercise is focused on the data from 2016 and includes only stocks which had data for each one of the days in the year.
