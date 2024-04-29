# Company Valuation Model

If you have watched Shark Tank, the judges try to offer deals on a certain valuation based on different parameters. Revenue, Gross Profit, Net Profit, Quarter on Quarter are some of these parameters. This got me wondering how do these judges calculate what valuation should be given using these parameters. Which parameter mattered the most? Which parameter would hold more weightage in a particular sector? How do you know that a certain valuation was a fair valuation?

So I decided a to build a Multiple Linear Regression Model to predict the valuation of companies belonging to a particular sector (to be precise of Sugar Sector). Then this Linear Regression Model can help me tell which companies are overbought and which companies are underbought.

Because I have good knowledge of the Stock Market, I compiled all the data in an excel sheet first, used the required formulas to get the necessary ratios and then converted it into a .csv file so that I can do the necessary analysis, pre-processing and build my Linear Regression Model.
