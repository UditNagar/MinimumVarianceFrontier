This is an analysis on Industry vs Market Portfolios.

In the Code 'Part 1 - Performance Metrics.py', I compute the Sharpe, Treynor, Jensen's Alpha and Three-Factor Alpha of the 10 Industry Portfolios, returns of which date from 
2004 to 2013

In The Code 'Part 2 - Minimum Variance Frontier.py', I use the monthly returns of the ten industry portfolios to generate the minimum-variance frontier without short sales,
using Monte Carlo simulation. Without short sales, portfolio weights will be limited to the range [0, 1]. 


I randomly draw each element of w, the vector of portfolio weights, from the uniform distribution in the range [0, 1]. Divide w by the sum of the portfolio weights, to ensure that
the portfolio weights sum to one. The normalized w is used to calculate the mean return and standard deviation of return. This process is repeated for 100,000 observations and a
similar analysis is performed on Uniform Distribution by taking the weight 1/w (i.e. the reciporcal of w)

- w, Noral Distribution
- 1/w, Standard Uniform Distribution

The Mean Variance Frontier plot is generated from both the analysis in Part 2.


