### Code for Financial Planning: 
#### The code accesses real-time information from the Alpaca API as well as crypto currencies from an alternative API (API.me). 
#### My code works like this: 
##### Part 1: 
###### 1) Fetches the BTC and ETH prices and puts them into variables 
###### 2) Loads the .env file in to validate the Alpaca API for Stocks/bond
###### 3) Puts the stocks/bond and crypto into a dataframe for a pie chart 
##### Part 2: 
###### 1) Gets the stock data for the SP500 and AGG from the alpaca API 
###### 2) We organize the dataframe and then we forecast 30 years of cumulative returns for MonteCarlo simulation
###### 3) We analyze the data to see what returns we could expect. We found the following: Average returns via 60/40 portfolio would be 18% with 12% std (so we could expect as less as 6% and as high as 30% returns. The minimum return we could expect is 1.9% and max of 129%. An investment of 20000 could yield between 98K to 1.6mm USD by using the 60/40 strategy. 



#### Received support from classmates & homework assignments: Heloisa, Wilson, Kayla, and Aditya. 

#### Also special thanks to Python Tutor: Edward Rees and to inclass TA: Shah

#### Sources used to help complete the assignment 
##### Inclass assignment to do with: MonteCarlo Simulation 
##### https://forum.alpaca.markets/t/get-bars-vs-get-barset/8127/3 
##### https://stackoverflow.com/questions/25952790/convert-pandas-series-from-dtype-object-to-float-and-errors-to-nans
##### https://stackoverflow.com/questions/59980448/how-to-plot-a-stacked-bar-chart-using-hvplot 
##### https://stackoverflow.com/questions/65727499/how-to-access-value-in-a-json-string-using-a-key-in-python 
##### https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.drop.html 
##### https://www.w3schools.com/python/python_dictionaries_access.asp 
##### https://bootcampspot.instructure.com/courses/4769/external_tools/313 
##### https://www.geeksforgeeks.org/response-json-python-requests/ 
