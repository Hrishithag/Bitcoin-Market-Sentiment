# Bitcoin Market Sentiment Analysis

## Overview

This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance using historical trading data from Hyperliquid.

The objective is to identify how market sentiment influences trading behavior, profitability, leverage usage, and overall trading outcomes.

## Datasets Used

### 1. Bitcoin Fear & Greed Index

* Date
* Classification (Fear, Greed, Extreme Fear, Extreme Greed)

### 2. Hyperliquid Historical Trader Data

* Account
* Symbol
* Execution Price
* Size
* Side
* Time
* ClosedPnL
* Leverage
* Event
* Start Position

## Project Workflow

1. Data cleaning and preprocessing
2. Date standardization across datasets
3. Merging sentiment and trader datasets
4. Exploratory Data Analysis (EDA)
5. Profitability analysis across sentiment categories
6. Leverage behavior analysis
7. Trader segmentation and performance comparison
8. Visualization and insight generation

## Key Analysis Performed

* Average ClosedPnL by sentiment category
* Trade volume across market sentiments
* Leverage usage during Fear vs Greed periods
* Top and bottom trader performance analysis
* Sentiment impact on profitability

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## Repository Structure

├── bitcoin_sentiment_analysis.ipynb
├── Primetrade_Assignment_Report_Template.pdf
└── README.md

## Results

The analysis investigates whether trader profitability and risk-taking behavior vary under different market sentiment conditions and provides data-driven insights that can support smarter trading strategies.

## Author

Hrishitha G
