# Pandemic-affects-on-Economic-Factors
COVID-19, termed as Global Pandemic and has greatly affected every aspect of everyone’s life. From out of masks stock in the beginning to the market instability in every field. As knows to us, in most countries people have been ordered to stay at home, reducing the outdoor activities, imposing fines to the locals and businesses. 

The COVID-19 pandemic has had a devastating impact on the health of the global economy. Worldwide, it is estimated that hundreds of millions of people are at risk of losing their livelihoods, and millions of enterprises and businesses large and small have to close their doors, sometimes for good. How extensive is the damage? Where is the impact on the job market most pronounced? Due to this, many industries suffered, and some are suffering from huge loss as some industries completely shut down in this pandemic period and some having workers issue, as workers start working from home or completely stopped working. This hit the financial markets.
This Project mainly focus on the Financial markets and economic indicators which affected by COVID-19 and analysing which economic factor is most affected and how it will be affected in future.

## Data Collection
Data was collected mainly from the NASDAQ and yahoo. All the stock data was closely checked and then maintain till Sep 2020. Different Factors like market commodities such as Energies, Meats, Metals and Grains, Cryptocurrencies and Currencies along with NASDAQ_100 and CBOE volatility index were maintained to correlate with the COVID data. Raw Data can be found in 'data' folder.

## Cleaning of the Data
To Clean the Data run the file 'CleanData.ipynb' which can be found in '/src' folder 'clean_data' folder will be created after execution of this file.

## Data Analysis and Plotting
To Analyse the Data, run 'Analyze.py' file in '/src' folder and 'Analyze_data' folder will be created.
To plot analysed data, run 'PlotData.ipynb' file in '/src' folder and to plot largest one day drop, run 'LargestDrop.py' file in '/src' folder.
Result will be saved in '/result/market' folder for 'PlotData.ipynb' file and '/result/largest-one-day-drop' folder for 'LargestDrop.py' file.

## Correlation between Covid Data and Economic factors
To get the Correlation graph, run 'Correlation.ipynb' file in '/src' folder. Result will be saved in '/result' folder.

## Time Series Analysis
For Time Series Graphs, run 'time-series-analysis.ipynb' file in '/src' folder. Result will be saved in '/result/time-series' folder.

## Forecasting with ARIMA model and Evaluation of the model.
For forecasting and evaluation, run 'Arima.ipynb' in '/src/Forecasting' folder. Results will be saved in '/src/Forecasting' folder.
