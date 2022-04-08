# project-2
Portfolio analyzer



##Miami Fintech Bootcamp
Portafolio analizer, in this project we want to be able to add our personal portafolio, stocks or cyptos.
the analysis gives you and inside of the healt of your portafolio, on s short term and long term.
we analyze the RISK in the portafolio as well as POSIBLE_GROWTH, and the sentiment analisis of you stock or crypto .

You may be using [what is a porfolio](https://study.com/academy/lesson/portfolio-weight-return-variance-definition-examples.html).

### Step 1: define your portafolio, enter the names, the amount and the prices, also added som logit to add more than onecoin or stock
### Step 2: gatter data from different api's, clean and prep the data
### Step 3: prep data for the first risk analysis(sharp, cummulative return, annual volatility)
### Step 4: create function for the analyzer.
### Step 5: prep data for `
### Step 6: create fuction scrape data from news sites, and gives you a inside on sentiment around your asset.
### Step 7:create a efficient frontier with 1000 portfolio and look for the best sharp ratio
### Step 8: re allocate weights
### Step 9: create a vader anayisis of the news
## Step 1o: create a word cloud for the 10 most comun words.
### Step 11: if times permits deploy into sageMaker


![](https://www.i1.creditdonkey.com/image/1/1200c/best-portfolio-analyzers.jpg)


# portfolio theories

## I. Traditional Approaches
__Dow Theory__: Charles Dow (editor of Wall Street Journal USA) made the hypothesis that the stock market does not move on a random basis but is influenced by 3 distinct cyclical trends, which can be carefully examined to make predictions about the future behavior of stock prices :
* Primary Movements: Long-term 1–3 years, swaying the market up or down
* Secondary Reactions: Opposite direction to primary, playing a “correction” role
* Minor Movements: Day to day fluctuations to the market


__Random Walk Theory__ (Efficient Market Hypothesis): Contrary, the behavior is almost unpredictable and there is no relation between present and future stock prices. Price changes shown in the stock market reflect changes in the company's entire industry and economy. According to the Random Walk Theory:
* All investors have full knowledge of the changes that occurred
* Instant adjustment in the stock prices with this news
* Markets are efficient
As a result, current prices reflect all information in the market and so past information will not be helpful for future predictions


__Formula Plans__: Mechanical revision techniques enabling investors to benefit from price fluctuations in the market by investing or trading stocks when prices are low and selling them when prices are high. Focusing on loss minimization rather than return maximization
* Construct 2 portfolios, one aggressive (stocks) and defensive (bonds), which are periodically monitored and adjusted accordingly
portfolio = portfolio_agg + portfolio_def




![](https://www.thestreet.com/.image/ar_4:3%2Cc_fill%2Ccs_srgb%2Cq_auto:good%2Cw_1200/MTY3NTM5NDYxMDkzMTM5ODQ3/what-is-modern-portfolio-theory-mpt-and-why-is-it-important.png)

## II. Modern Portfolio Theory:
__Harry Markowitz__ in 1952 used mathematical programming and statistical analysis (variance, correlation) in order to arrange optimum allocation of assets within the portfolios. According to theory, “it is possible to construct an `efficient frontier` of optimal portfolios offering the maximum possible expected return for a given level of risk” (by Investopedia)
`Efficient Portfolios` under CAPM yield the highest return for the level of risk accepted. Consider a one-period market with n instruments with the same expected returns E[R_i] and variances Var(R_i). We also denote as w_i the fraction of wealth invested in the i-th instrument.

_CASE_ : Consider now two portfolios:
* Portfolio A : 100% invested in instrument # 1
* Portfolio B : An equal-weighted portfolio

![](https://cdn.educba.com/academy/wp-content/uploads/2020/12/Portfolio-Optimization.jpg)

ifferent approaches to portfolio optimization measure risk differently. In addition to the traditional measure, standard deviation, or its square (variance), which are not robust risk measures, other measures include the Sortino ratio, CVaR (Conditional Value at Risk), and statistical dispersion.

Investment is a forward-looking activity, and thus the covariances of returns must be forecast rather than observed.

Portfolio optimization assumes the investor may have some risk aversion and the stock prices may exhibit significant differences between their historical or forecast values and what is experienced. In particular, financial crises are characterized by a significant increase in correlation of stock price movements which may seriously degrade the benefits of diversification.[15]

In a mean-variance optimization framework, accurate estimation of the variance-covariance matrix is paramount. Quantitative techniques that use Monte-Carlo simulation with the Gaussian copula and well-specified marginal distributions are effective.[16] Allowing the modeling process to allow for empirical characteristics in stock returns such as autoregression, asymmetric volatility, skewness, and kurtosis is important. Not accounting for these attributes can lead to severe estimation error in the correlations, variances and covariances that have negative biases (as much as 70% of the true values).[17]

Other optimization strategies that focus on minimizing tail-risk (e.g., value at risk, conditional value at risk) in investment portfolios are popular amongst risk averse investors. To minimize exposure to tail risk, forecasts of asset returns using Monte-Carlo simulation with vine copulas to allow for lower (left) tail dependence (e.g., Clayton, Rotated Gumbel) across large portfolios of assets are most suitable.[18]

More recently, hedge fund managers have been applying "full-scale optimization" whereby any investor utility function can be used to optimize a portfolio.[19] It is purported that such a methodology is more practical and suitable for modern investors whose risk preferences involve reducing tail risk, minimizing negative skewness and fat tails in the returns distribution of the investment portfolio.[20] Where such methodologies involve the use of higher-moment utility functions, it is necessary to use a methodology that allows for forecasting of a joint distribution that accounts for asymmetric dependence. A suitable methodology that allows for the joint distribution to incorporate asymmetric dependence is the Clayton Canonical Vine Copula. See Copula (probability theory)#Quantitative finance.

Cooperation in portfolio optimization


![Sentiment Analysis](https://files.realpython.com/media/How-to-use-NLTK-for-Sentiment-Analysis-in-Python_Watermarked.8dd30ecc0bda.jpg)
