# Stock Prices Data Analysis 

In this project fundamental and more advanced Data Analysis are done on the stock prices of 6 American banks over the time period 2006-2015 to see how they progressed throughout the [financial crisis](https://en.wikipedia.org/wiki/Financial_crisis_of_2007%E2%80%9308) all the way to early 2016.  The libraries used are Pandas, Seaborn, Matplotlib, Plotly and Cufflinks.  A mulitlevel index dataframe is used. The data was scraped from the internet and downloaded as a pickle.  Please bear in mind that this project is meant to practice visualization and Pandas skills; it is not meant to be a robust financial analysis or be taken as financial advice on stock prices.

Due to the nature of Plotly and Cufflinks (not being able to view plots in Jupyter Notebooks on GitHub, I have included screenshots, for a quick view, of all the plots that uses Plotly and Cufflinks.

The banks which stock information we will analyse are:
* Bank of America
* CitiGroup
* Goldman Sachs
* JPMorgan Chase
* Morgan Stanley
* Wells Fargo

Some interesting analysis done in this project is as follows:

* Interpreting the distribution plots for Morgan Stanley and CititGroup for the years 2015 and 2008 respectively, where we see that there was a high risk involved in investing at these banks at that time.
* Creating a line plot with Plotly comparing the closing prices for each bank over the entire period of time.  From these curves we can see that CitiGroup had a stock market crash which lasted from 2007 – 2009.
* Determining the strength of correlation between the closing prices of the different banks using a heatmap and clustermap.
* Using Cufflinks to visualize the stock of Bank of America with candlestick plots.
* Using Cufflinks to visualize Simple Moving Average plots (of various time spans; commonly used periods) for Morgan Stanley.
* Using Cufflinks to visualize the Bollinger plot for Bank of America for 2015 and some interpretations on their stocks.

This project was done through Jose Portilla (head of Data Science at Pierian Data Inc.) on Udemy (Python for Data Science and Machine Learning Bootcamp).
