# Sentiment Analysis of Stocks from Financial News 
- Collected the Date, Time and News Headlines Data from FinViz website.
- Extracted stock sentiments from financial news headlines.
- Perfomed Sentiment Analysis. 

## Code and Resources used:
**Python:** 3.9

**Packages Used:** pandas,numpy,seaborn,matplotlib,NLTK_vader

## Fields in the data :
- ticker: Symbol of the stock.
- date: Date of the news.
- time: Time of the news.
- headlines: Headlines.
- pos: Postive score( the higher the value, the more positive the sentiment is).
- neu: Neutal score.
- neg: Negative score (the more negative the value, the more negative the sentiment is).
- compound: Sentiment score.



## Steps:
- Import Libraries.
- Store the Date, Time and News Headlines Data.
- Print the Data Stored in news_tables.
- Parse the Date, Time and News Headlines into a Python List.
- Sentiment Analysis with Vader.
- Plot a Bar Chart of the Sentiment Score for Each Day.

<img src='news.png' width='300' height='300'>

