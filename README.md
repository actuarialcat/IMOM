# Replication Study on Idiosyncratic Momentum Strategy

This project replicate the idiosyncractice momentum trading strategy suggested in “Eureka, a version of Momentum that Works in Japan” by Denis Chaves (2012). Chaves proposed a new form of momentum signal created by the cumulative idiosyncratic return which seems to be superior to traditional momentum signal.

The idiosyncratic momentum  is superior to traditional momentum only for in-sample data. After the Chaves’ article is published, the strategy is no-longer able to produce significant alpha.

This article also attempts to extend the strategy by using Fama-French five-factor model to produce idiosyncratic momentum. However, it was discovered that this method is inferior to the idiosyncratic momentum produced by Chaves.


## Highlights

The anaylst is based on US common stock data from 1965 to 2019 on CRSP.

First, the table shows the result of strategy benchmarked against the 5-factor model for in-sample data. It shows that the strategy generates a signficantly positive alpha, which means the it can be used to beat the market.

<img src="./Pictures/IMOM%20Factors.png" height=350>

Secondly, the graph show the profit and loss curve of the strategy, which reflects the amount would be earned if $1 is invested in 1965.

<img src="./Pictures/IMOM%20PL%20Curve.png" height=450>

Thridly, the project also attempts to improve the strategy by using residuals from a 5-factor model to generate the signal. This graphs shows the performence for the long and short part of the portfolio of both strategy.

<img src="./Pictures/IMOM5F%20Perf.png" height=450>


## What's More

For more detials, please see the [full article](https://actuarialcat.github.io/IMOM/Replication%20Study%20on%20Idiosyncratic%20Momentum%20Strategy.pdf).

Codes are in the [jupyter notebook](./FINA_4359_Project_Final.ipynb)


## Github Repository

[Github Repository](https://github.com/actuarialcat/IMOM)


