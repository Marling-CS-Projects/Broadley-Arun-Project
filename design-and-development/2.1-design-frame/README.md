---
description: >-
  This page describes the structure of the project and the tasks I will need to
  do to build the project.
---

# 2.1 Design Frame

## Systems Diagram

<figure><img src="../../.gitbook/assets/image (70).png" alt=""><figcaption><p>Predictor App</p></figcaption></figure>

The design of the predictor app has 3 main sections.

* Front-End

The front end will be written Angular and Javascript is the core part that the user will interact with and is described in more detail in section 2.1.1

* Back-End

Backend components will be written using Node and Javascript and will be responsible for retrieving data from our data provider. Currently EODHD.COM. The component will be described in 2.1.2

* Financial Data API&#x20;

The last component is the Data provider. I will have to interface to their API's to retrieve data my solution needs to operate.

## Component Tasks breakdown.

<figure><img src="../../.gitbook/assets/image (21).png" alt=""><figcaption></figcaption></figure>

This chart shows the different tasks I need to do to complete my project. I've colour-coded each task showing whether It must be done, should be done or could be done.  I will focus on the 'Must' and 'Should' tasks first and leave the 'Could's until the end when I will know how well I'm doing in time.

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

Create a function that allows the user to download the above information consistently from EODHD.COM and structure it in a way that we can then do an analysis of the collected data.

## The Calculations

I have decided to base most of the predictions I'm trying to make using Linear Regression. To save time and increase accuracy, I will use one of the open source Javascript Statistics packages to do the actual calculations. I also plan to spend some time setting up the calculations in Excel. This will allow me to test the results coming from the statistics library.

### Aim

Calculate Linear Regression scores such as Chi2, R2  and R from the data we download from EODHD.com and have some way of testing those results.

### User Interface

My project is not primarily focused on the User Interface. Its more on the Data, Analysis & Predictions. The UI, though, has to be good enough that anyone could use the solution to find stocks and then do the analysis to see if there are any relationships between any of the variables.

**AIM**

Build a simple user interface to allow users to find stocks they wish to analyze and the simply investigate the relationship between those variables.

###
