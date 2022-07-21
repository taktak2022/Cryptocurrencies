# Cryptocurrencies
## MODULE 18 UNSUPERVISED MACHINE LEARNING & CRYPTOCURRENCIES

### OVERVIEW
This module's goal was to educate us in Unsupervised Machine Learning which is used when there is no known output so it is used to discover patterns or groups (clusters) in datasets.  This methodology helps us to explore data when we are not sure what we are looking for.
The premise of this module is to assist a childhood friend Martha pitch an idea to invest in cryptocurrencies to her investment firm.  Bitcoin, the most well known cryptocurrency is unaffordable to a novice investor so we will be looking for trends with other cryptocurrecy options that are available.

### NEW TOOLS & CONCEPTS
* hvPlot (HolovViews) PLOTTING LIBRARY
* CLUSTERING & HIERARCHICAL CLUSTERING
* K-means ALGORITHM
* THE Elbow Curve
* PCA: PRINCIPAL COMPONENT ANALYSIS

### RESULTS
First we went through several steps to pre-process the data so that our Unsupervised Machine Learning model will not have trouble interpreting the data.  These steps include:
* DATA SELECTION: Removing unneeded data columns and null values
* DATA PROCESSING: Retaining tradable and mined cryptocurrencies and scaling the data.

We then used Principal Component Analysis (or PCA).
![MOD18 CHALLENGE DEL III - PCA](https://user-images.githubusercontent.com/99851509/180285479-defc15d1-8438-4ace-a40a-1d225fe966ff.png)

Once these components had been determined, we then sought out how many clusters would be optimal by plotting them using an Elbow Curve.  This visualization shows the optimal predicted number of clusters is 4.
![MOD18 CHALLENGE DEL III - ELBOW CURVE](https://user-images.githubusercontent.com/99851509/180286314-5f076ce5-cf04-47ac-ad2d-ee2b1cd18a58.png)

### SUMMARY
The following visualizations represent the results.  The first is a 3D Scatterplot which shows the 3 principal components in relation to various clusters of cryptocurrencies.
![MOD18 CHALLENGE DEL IV - 3D SCATTERPLOT](https://user-images.githubusercontent.com/99851509/180287033-752de4c3-789d-4da5-9cfd-97f4bf15973b.png)

Then when we represent the Total Coins Mined against the Total Coin Supply in a graph visualization, we see the majority is not readily available via supply or to be mined, however there are a few outliers.  Whether these outliers will yield an investment in the future is yet to be determined.
![MOD18 CHALLENGE DEL IV - COINS MINED v COIN SUPPLY](https://user-images.githubusercontent.com/99851509/180287092-7e2cd6f0-1b81-447c-94d2-4c4e1df7a17c.png)




