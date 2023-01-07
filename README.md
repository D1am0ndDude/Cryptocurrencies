# Crypto currencies Analysis

# Overveiw 
Accountability Accounting, plans to offer a new cryptocurrency investment portfolio to its customers. They need our help in sorting out what cryptocurrencies are currently trading in the market, and how these could be grouped to create a portfolio for the new investors. With the endless amount of Cryptocurrencies available, it is our job to filter out the best ones for their clients.

* preprocessing the database,
* reducing the data dimension using Principal Component Analysis,
* clustering cryptocurrencies using K-Means,
* visualizing classification results with 2D and 3D scatter plots.

# Results 
532 Tradable Cryptocurrencies remained after preprocesing and cleaning the data.

# Elbow Curve
The Best K-Value is 4
![image](https://user-images.githubusercontent.com/46943357/211168407-5e903e64-8259-41b6-9932-7dac0f0a477d.png)

# Cryptocurrencies results
3D-Scatter Plot. This was created by using the PCA Algorithm
![image](https://user-images.githubusercontent.com/46943357/211168465-f12dc313-b6bb-4d84-a1df-9aec5fac4834.png)

# Tradable Cryptocurrencies Table
Most cryptocurrencies are part of class #0 and #1. The snapshot illustrates BitTorrent as the only cryptocurrency in class #2.
![image](https://user-images.githubusercontent.com/46943357/211168508-ea8195b1-e4ce-44c8-bac9-80e933c29e0b.png)

# 2D-Scatter plot with TotalCoinMined VS TotalCoinSupply
Plotting the scatter plot from two cryptocurrency features directly does not efficiently segregate the different classes. The PCA algorithm is the right method for better visualizations.
![image](https://user-images.githubusercontent.com/46943357/211168521-f5f38e7c-da40-4908-bec1-e35e71f7829c.png)

# Summary
The classification of 532 cryptocurrencies have been identified based on similarities of their features. Distinctions in each group must be analyzed to determine their performance and potential interest for the investment bank's clients.
