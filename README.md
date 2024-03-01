# K-Means Clustering in Stock Analysis
## Overview
This repository contains the implementation of K-Means Clustering for stock analysis. The primary goal is to explore the application of K-Means clustering in analyzing stock behavior, considering various factors such as historical stock returns, trading volume, stock prices, Price-to-Earnings (P/E) ratio, Earnings per Share (EPS), dividends, and other relevant variables. The K-Means Clustering algorithm is utilized to group stocks with similar characteristics into distinct clusters.

## Background
The stock market is a dynamic environment, and making informed investment decisions requires a deep understanding of stock behavior. This project focuses on analyzing LQ45 stocks traded from 2020 to 2023 using key financial indicators. The aim is to provide valuable insights into the behavior, risks, and investment opportunities in the Indonesian stock market during this period, considering the complexities of modern digital analysis.

## Data Collection
Data was collected from Yahoo Finance on January 5, 2024, covering various characteristics of stocks, including sector, historical stock prices, trading volume, dividends, and EPS. The dataset includes a diverse range of LQ45 stocks.

## Data Preprocessing
Data preprocessing involves the calculation of average trading volume, total dividend percentage, daily return statistics, and the Price-to-Earnings (P/E) ratio. One-hot encoding is applied to convert categorical variables, such as the industry sector, into a format suitable for machine learning algorithms. Scaling is performed using Absolute Maximum Scaling to normalize the data.

## K-Means Clustering
The K-Means Clustering algorithm is implemented to group stocks into clusters based on selected features. The optimal number of clusters is determined using the Elbow Method, and the results are visualized to identify patterns in stock behavior. The final clustering results reveal distinct groups representing different sectors.

## Conclusion
The clustering analysis categorizes stocks into five clusters, providing valuable insights into Consumer Defensive, Financial Services, Energy, Communication Services, and other sectors. This analysis aids investors in making more informed investment decisions and understanding the dynamics of the stock market.

## Recommendations
Based on the clustering results, strategic steps can be taken to determine which sector aligns better with the investors' investment goals. Recommendations can be provided considering the characteristics of each cluster, taking into account both risks and potential gains.

Feel free to explore the Jupyter Notebook and the Python scripts for a detailed understanding of the methodology and results. Your feedback and contributions are welcome!
