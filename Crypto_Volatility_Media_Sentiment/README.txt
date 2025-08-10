# Media Sentiment and Crypto Intra-day Volatility

## Description
This project explores the relationship between media sentiment and cryptocurrency price volatility using high-frequency intraday data for the top 10 cryptocurrencies.

## Data
Price and volume data are collected via Bloomberg Terminal. Due to data sensitivity and licensing restrictions, the raw data is not included here. 
Price data is logged return as per Robert Shiller, Irrational Exuberance 2000.

## Methodology
The core approach applies an EGARCH model to capture volatility dynamics, building on methodology similar to that used in my paper Media Sentiment and Market Volatility: Analysing the influence of media sentiment on 
financial market behaviour. The model incorporates media sentiment as an explanatory variable both in level and change form.

## Code
The R script implementing the EGARCH model and data preprocessing is provided, refer to BASE_LogReturn_EGARCH_Model. R-Markdown is required to run and implement the code.

## Status
Work in progress. Manuscript draft is under development.

## Contact
For questions or collaboration inquiries, please contact Pieter Nel (piedanel@gmail.com).

