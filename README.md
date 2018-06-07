
# A network analysis of the US stock market

### Abstract
We applied unsupervised machine learning methods to US stock market data over the years 1992-2017, to identify systemic features and temporal trends, with reference to 9 major economic events in that window (e.g. the dot-com bubble, the Lehman Brother’s bankruptcy, etc.). We began by using principal component analysis (PCA) to obtain a spectral decomposition of adjusted closing prices over time, and identified the temporal features associated with each eigenvector. Analysis of industrial classification codes for stocks with highest correlation to each eigenvector was able to correctly identify industries and sectors affected by each economic event. Next, we used a weighted correlation network to refine our analysis by first identifying stock modules based on topological overlap, and then taking the leading eigenvector in the spectral decomposition for each module. Our analysis found that this approach was able to identify more nuanced temporal trends within the principal component of variation.

### Link to notebook
[A Systems Analysis of the US Stock Market](https://nwisn.github.io/StockNet/notebook.html).

![](https://nwisn.github.io/StockNet/module_eigenstock.png)
