# power-consumption
Demonstrates training a LSTM Architecture in forecasting Power Consumption of HouseHold Items

# Data
Data is sourced fromm uci link below

https://archive.ics.uci.edu/ml/datasets/Individual+household+electric+power+consumption

# Data Preprocessing
The data is preprocessed using the following steps
1. The data is loaded into a pandas dataframe
2. The data is resampled to daily frequency
3. The data is cleaned by removing rows with missing values
4. The data is scaled using MinMaxScaler
5. The data is split into train and test sets


# Model
The model is a LSTM architecture with 2 hidden layers and 1 output layer. The model is trained for 10 epochs with a batch size of 16. The model is trained using the Adam optimizer and Mean Squared Error loss function.


