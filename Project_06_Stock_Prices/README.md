# Comparative Analysis of Tech Giants: Stock Price Performance and Trend Analysis

## Project Overview
This project compares the stock prices of APPLE, GOOGLE, MICROSOFT, and AMAZON. It retrieves historical stock prices, calculates percentage changes over a specified period, and identifies the best-performing stock. Additionally, it analyzes trends in the data.

## Key Features
- Retrieves stock data using the `pandas_datareader` library.
- Calculates percentage change in stock prices for each company.
- Identifies the company with the best stock performance.
- Displays historical stock prices to analyze trends and patterns.

## Libraries Used
- **pandas**: For data manipulation and analysis.
- **pandas_datareader**: For retrieving stock data from sources like Yahoo Finance.
- **datetime**: For specifying the date range for stock data retrieval.

## Code Explanation
The project performs the following steps:
1. **Stock Data Retrieval**: The program retrieves stock data for Apple, Google, Microsoft, and Amazon over the year 2023, using their respective stock symbols.
2. **Percentage Change Calculation**: It calculates the percentage change in stock prices from the beginning to the end of the year for each company.
3. **Best Performer Identification**: The program identifies which company's stock performed the best during the period.
4. **Historical Data Display**: The historical stock prices are displayed to analyze trends or patterns over the specified time frame.

## Code Structure
- **Importing Libraries**: Import necessary libraries for data retrieval and handling.
- **Company Dictionary**: Stores company names and their stock symbols.
- **Date Range**: Defines the start and end dates for data retrieval.
- **Data Retrieval**: Fetches stock data for each company.
- **Percentage Change Calculation**: Computes and displays percentage changes in stock prices.
- **Trend Analysis**: Shows historical stock prices for trend exploration.

## Prerequisites  
- Python 3.x installed on your machine.  

## Sample Run
### Percentage Change in Stock Prices
```python
Apple: -35.04%
Google: -36.20%
Microsoft: -36.29%
Amazon: -43.52%
```

### Best Performer:
```python
Apple: -35.04% (Best Performer)
```

## Historical Stock Prices (Sample Output)
- ### Apple
```python
              Open    High      Low   Close    Volume
Date                                                 
2023-12-29  193.90  194.40  191.725  192.53  42672148
2023-12-28  194.14  194.66  193.170  193.58  34049898
2023-12-27  192.49  193.50  191.090  193.15  48087681
2023-12-26  193.61  193.89  192.830  193.05  28919310
2023-12-22  195.18  195.41  192.970  193.60  37149570
```
- ### Google
```python
              Open    High      Low   Close    Volume
Date                                                 
2023-12-29  139.63  140.36  138.780  139.69  18733017
2023-12-28  140.78  141.14  139.750  140.23  16045712
2023-12-27  141.59  142.08  139.886  140.37  19628618
2023-12-26  141.59  142.68  141.190  141.52  16780333
2023-12-22  140.77  141.99  140.710  141.49  26532199
```
- ### Microsoft
```python
              Open     High       Low   Close    Volume
Date                                                   
2023-12-29  376.00  377.160  373.4800  376.04  18730838
2023-12-28  375.37  376.458  374.1600  375.28  14327013
2023-12-27  373.69  375.060  372.8116  374.07  14905412
2023-12-26  375.00  376.940  373.5000  374.66  12673050
2023-12-22  373.68  375.180  372.7100  374.58  17107484
```
- ### Amazon
```python
              Open     High     Low   Close    Volume
Date                                                 
2023-12-29  153.10  153.890  151.03  151.94  39823204
2023-12-28  153.72  154.080  152.95  153.38  27057002
2023-12-27  153.56  154.780  153.12  153.34  31434733
2023-12-26  153.56  153.975  153.03  153.41  25067222
2023-12-22  153.77  154.350  152.71  153.42  29514093
```

## Explanation
This project focuses on comparing the stock prices of four major companies: Apple (AAPL), Google (GOOGL), Microsoft (MSFT), and Amazon (AMZN). The program retrieves current and historical stock prices for each company and calculates the percentage change in stock prices over a specified period. It then identifies which company's stock has performed the best.

The `pandas_datareader` library is used to fetch the stock data from Stooq, a financial data source, within a defined date range (January 1, 2023, to December 31, 2023). The `datetime` module is used to handle the date range.

A dictionary maps each company's name to its respective stock symbol, which is used to dynamically retrieve stock data for each company. The program calculates the percentage change in stock prices by comparing the closing prices on the start and end dates. The results are stored in a dictionary where the key is the company name and the value is the percentage change.

The program prints the percentage change in stock prices for each company and identifies the company with the highest percentage change. This helps in determining the best-performing stock. Additionally, the program prints the first five rows of historical stock prices for each company, providing valuable insights into daily price movements and trading volumes.

The output shows that all four companies experienced significant declines in their stock prices over the specified period, with Amazon showing the most significant decline. This indicates a general downtrend in the market. The historical stock price data provides valuable insights into daily price movements and trading volumes, which can be used for more detailed analysis and forecasting.


## Insights  
- All four companies experienced a decline in stock prices during the specified period, with **Amazon** showing the most significant drop (-43.52%).  
- The trends in historical data reveal fluctuations influenced by market conditions, highlighting the need for further analysis to understand driving factors.

## Future Enhancements  
1. **Advanced Data Visualization**:  
   - Use libraries like `matplotlib` and `seaborn` to create visual representations of trends and patterns.  
2. **Real-Time Data Retrieval**:  
   - Incorporate APIs like Alpha Vantage or Yahoo Finance for real-time stock data updates.  
3. **Sentiment Analysis**:  
   - Integrate news sentiment analysis to correlate stock price trends with public sentiment.  
4. **Sector Comparison**:  
   - Compare the performance of these companies against their respective sectors.  
5. **Predictive Analysis**:  
   - Implement machine learning models to forecast future stock price trends.  
