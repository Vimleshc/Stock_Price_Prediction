# Stock_Price_Prediction
Two models were compared for same dataset using Simple RNN and LSTM for stock price prediction
The code first imports the pandas library to read and manipulate dataframes. Then, it uses the pdr.get_data_tiingo() function to get the stock data for NVIDIA (NVDA) from Tiingo. The function takes the ticker symbol of the stock and an API key as input. The API key is required to access the Tiingo API.

The code then saves the data to a CSV file. This is done so that the data can be easily accessed and manipulated later. Finally, the code reads the data from the CSV file and prints the first 5 rows. This allows us to see the first few rows of data to get an idea of what the data looks like.
