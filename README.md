# Stock_prediction
This repository contains code for time series analysis and prediction using LSTM (Long Short-Term Memory) neural networks. The code is written in Python and utilizes various libraries such as NumPy, Torch, Pandas, and Statsmodels.

The main steps covered in the code include:

- Importing the necessary libraries and modules
- Data preprocessing and exploration
- Downloading a stock time series dataset from Kaggle using the opendatasets library
- Reading the dataset from a CSV file and performing data manipulation
- Scaling the data using MinMaxScaler
- Creating a sliding window approach for data loading and splitting the dataset into training and testing sets
- Defining the LSTM architecture using PyTorch
- Training the LSTM model on the training set
- Evaluating the model's performance using mean squared error (MSE) loss
- Visualizing the predicted values against the actual values using seaborn and matplotlib
- Please note that this code assumes Python 3.7.13 and requires the installation of the opendatasets library. It also requires providing your Kaggle credentials for dataset download.

Feel free to explore the code and adapt it for your own time series analysis and prediction tasks.
