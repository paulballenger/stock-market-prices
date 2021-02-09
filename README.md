# stock-market-prices

An exploration of historical S&P 500 stocks prices to examine trends - specifically, to see if the stock market performance on one day affects the probably of a change in direction the next day.

For project, I looked at trends:
* How many days stock market closing prices rose or dropped before changing direction
* Percent gain or loss when change of direction ocurred

Next, I looked for correlations by using S & P 500 closing prices for a set number of years in the past to try to predict stock market performance for a more recent set number of years. Using the past performance data, I separated perforamces into bins based of number of days of movement in one direction and direction of movement. (For example, if prices go down for 3 days straight for a total cummulative lose of 0.056%, what does history say the market will do the next day.) After creating the bins, I created plots showing the probably of a higher closing price the next day based on a positive or negative close the current day and take in account streaks.

First, I used S&P prices from 2007-2016 to predict pricing from 2017-2020. The results were encouraging - $1000 invested on 1/1/2017 would be worth $2,677.95 on 12/31/2020 using the model, which compares favorable to the actual market return, where $1000 would be worth $1,650.29.

To double-check the model, I used S&P 500 prices from 2001-2010 to predict the returns from 2011-2020. The results were essentially reversed - $1000 invested in 2011 would be worth only $950.88 on 12/31/2020, compared the actual market return of $2,930.36 over the same period. Average returns each year for this period can be seen in the chart below.

Conclusion: future performance cannot be predicted by using recent results. No surprise, but I learned a lot about Python.
