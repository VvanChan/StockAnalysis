# Stock Analysis
> lab files from online course Python and Statistics for Financial Analysis by HKUST

### week 1 Visualizing and Munging Stock Data
* recap: df basics 
* simple trading strategy based on previous day data using `.shift(-1)`

### week 2 Random Variables and Distribution
* recap: RV and normal distribution - stock return distribution
* probability of stock drop using `norm.cdf()`
* Value at Risk (VaR) using `norm.ppf()`

### week 3 Sampling and Inference
* recap: sampling, confidence interval, hypothesis testing
* CI calculation from standardized z distribution using `norm.ppf()`
* one-tail and two-tail tests using `norm.ppf()`; p-value using `norm.cdf()`

### week 4 Linear Regression Models for Financial Analysis
* recap: (multi-) linear regression, $R^2$, RMSE
* diagnosis models via linearity, independence, normality and equal variance
* evaluate financial model with **Sharpe Ratio** and **Maximum Drawdown**
