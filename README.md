# Stock_Price_Prediction
Two models were compared for same dataset using Simple RNN and LSTM for stock price prediction
The code first imports the pandas library to read and manipulate dataframes. Then, it uses the pdr.get_data_tiingo() function to get the stock data for NVIDIA (NVDA) from Tiingo. The function takes the ticker symbol of the stock and an API key as input. The API key is required to access the Tiingo API.

The code then saves the data to a CSV file. This is done so that the data can be easily accessed and manipulated later. Finally, the code reads the data from the CSV file and prints the first 5 rows. This allows us to see the first few rows of data to get an idea of what the data looks like.

The code first gets some information about the data set using the df.info() function. This function prints the number of rows, columns, data types, and memory usage of the data set.

Next, the code splits the data set into a training set and a validation set. The split ratio is 80% train and 20% validation. The length_data variable stores the number of rows in the data set, and the split_ratio variable stores the percentage of data that should be used for training. The length_train variable stores the number of rows in the training set, and the length_validation variable stores the number of rows in the validation set.

The train_data variable stores the training set, and the validation_data variable stores the validation set. The iloc[:,:3] slice selects the first three columns of the data set. The pd.to_datetime() function converts the date column to a datetime object.

It then splits the data into a training set and a validation set. The training set is used to train the model, and the validation set is used to evaluate the model's performance.

The code then builds a simple RNN model with three hidden layers. Each hidden layer has 64 neurons. The model is trained for 100 epochs.

After the model is trained, the code makes predictions for the validation set. The mean squared error (MSE) is used to evaluate the model's performance. The MSE for the validation set is 0.03.

The code then makes a prediction for the next day's closing price.

