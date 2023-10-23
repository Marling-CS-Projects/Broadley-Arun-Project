# 2.1.3 Data Provision & Calculations

## Getting The Data

The main part of this project is getting the historical data on stock price movements for selected stocks, At this point I've decided to use a paid-for service from www.eodhd.com, the main reason behind choosing them is that they have lots of documentation and examples which should make it easier to do the build. From their documentation it looks like I can get a history for the following:

* Stock Price
* Volume
* Insider Purchase
* Insider Sales
* News Article Count
* News Article Sentiment
* Growth

### Aim

Create a class that allows the user to download the above information consistently from EODHD.COM and structure it in a way that we can then do an analysis of the collected data.

## The Calculations

I have decided to initially base the predictions I'm trying to make on using Linear Regression. To save time and increase accuracy, I will use one of the open source Javascript Statistics packages to do the actual calculations. To ensure I can test well I will also implement the Linear Regression for one stock in Excel. This will allow me to test the results coming from the statistics library.

### Aim

Calculate Linear Regression scores such as Chi2, R2  and R from the data we download from EODHD.com and have some way of testing those results using Excel.

###
