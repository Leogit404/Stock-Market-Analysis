# Stock Market Exploratory Data Analysis (EDA)

This project involves an Exploratory Data Analysis (EDA) on the stock market performance of some of the biggest tech companies: **Amazon, Apple, Google, Tesla, and Nvidia**. The purpose of this analysis is to explore and understand stock data for each company, find patterns, trends, and gain insights into their stock prices and trading volume behavior over time.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Analysis Performed](#analysis-performed)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [Results and Insights](#results-and-insights)
- [Future Work](#future-work)

## Project Overview

This project performs an exploratory analysis on stock market data for five tech giants:
- **Amazon**
- **Apple**
- **Google**
- **Tesla**
- **Nvidia**

Through this analysis, the project aims to:
- Understand the historical stock price trends.
- Analyze the trading volume for each company.
- Examine any correlations between companies' stock prices.
- Identify significant events or trends over time (e.g., stock splits, earnings reports, etc.).

## Dataset

The data for this project was sourced from publicly available stock market data. The dataset contains historical stock prices and volume for each of the following companies:
- Amazon
- Apple
- Google (Alphabet)
- Tesla
- Nvidia

The dataset includes the following columns:
- `Date`: Date of the stock prices.
- `Open`: The stock's opening price on the trading day.
- `Close`: The stock's closing price on the trading day.
- `High`: The highest price reached during the day.
- `Low`: The lowest price reached during the day.
- `Volume`: The total number of shares traded.

## Analysis Performed

The exploratory data analysis (EDA) performed includes:
- **Time-series analysis**: Visualizing and analyzing trends in stock prices over time.
- **Correlation analysis**: Understanding how the stock prices of these companies are related.
- **Volatility analysis**: Assessing the price volatility for each stock.
- **Volume analysis**: Investigating trading volumes and their relationship to price movements.
- **Moving Averages and Indicators**: Implementing moving averages, Bollinger Bands, and other technical indicators.
- **Distribution Analysis**: Understanding the distribution of returns for each company’s stock.

## Technologies Used

- **Python**: The main programming language used.
- **Jupyter Notebook**: For organizing and presenting the analysis.
- **Pandas**: For data manipulation and cleaning.
- **Matplotlib** & **Seaborn**: For data visualization.
- **NumPy**: For numerical computations.
- **Yahoo Finance API**: For fetching stock market data (if applicable).

## How to Run

```bash
git clone https://github.com/Leogit404/Stock-Market-Analysis.git
cd Stock-Market-Analysis
pip install -r requirements.txt
jupyter notebook STOCKMARKET.ipynb

