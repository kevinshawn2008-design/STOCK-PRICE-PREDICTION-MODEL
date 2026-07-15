This repository contains a machine learning project designed to forecast stock price trends using the K-Nearest Neighbors (KNN) classification or regression algorithm.

Here is a breakdown of what the project entails based on the repository structure:

Core Logic (stock market predictor.ipynb): This Jupyter Notebook contains the implementation of the machine learning pipeline. It covers data preprocessing, training the KNN model, and evaluating its predictive performance.

Dataset (World-Stock-Prices-Dataset.csv): The historical data source used to train and test the model. It contains foundational stock metrics required for the features:

Open: The starting price of the stock when the market opens.

Close: The final price at which the stock trades during the session.

High & Low: The maximum and minimum prices reached during the trading day.

Volume: The total number of shares traded, which provides critical momentum context.

Demonstration (DEMO VIDEO (DOWNLOAD IT).mp4): A video file showcasing how the model runs, how the inputs are entered, and how the trend prediction is outputted.

How the KNN Algorithm Applies Here:
The KNN algorithm operates on feature similarity. When a user inputs a specific set of Open, Close, High, Low, and Volume metrics, the model maps this data into a multi-dimensional space. It then locates the "K" closest historical data points (neighbors) from the dataset. Based on the historical outcomes of those nearest neighbors, the model predicts the upcoming trend for the target stock.
