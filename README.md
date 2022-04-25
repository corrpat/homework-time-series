# homework-time-series

I completed the ipynb in Google Colab and downloaded it to my computer. Then I copied it over to jupyter lab and github. I put two of the resource files in the Resources folder, but mercado_stock_price was too big to move so I left it in the repo by itself.

In step one I looked for unusual patterns in hourly Google search traffic. I calculated the search data for May 2020 and found they were 5.2% higher than the monthly average.

In step two I mined the search traffic data for seasonality. I found that search traffic is heaviest during the 22:00-02:00 time frame. SO around midnight. This effect occurs regardless of thge day of the week. I also found that traffic is at the highest at the beginning of the year, during weeks 1-10.

In step three I related search traffic to stock price patterns. I found that after the first initial shock of 2020, investors returned and stock price and search volume increased. The biggest day of search volume coincided with the largest gain in stock price (5-5-2020). I also looked for a predictable relationship between lagged search traffic and stock volatility or between the lagged search traffic and stock price returns. I found that lagged search trends had a negative correlation (-0.12) with stock volatility, which is not enough causations to merit further review. I also found that lagged search traffic had had almost no correlation with stock price returns, coming in at 0.02.

In step four I created a time series model with Prophet. I found the most popular time of the day in the forecast model is midnight (00:00). The most popular day of the week is Tuesday and the most popular time of the year is the first few months. The least popular time of the year is fall, with Oct 15 being the least popular.

In step five I forcast revenue by using a time series model.  I discovered that Wednesday is the peak day of the week for revenue. For the time series model going out a quarter, I figured the most likely scenario is 2164 sales. The worst case scenario is 1989 sales and the best case scenario is 2340 sales.
