# Stock-Markert-Basic-To-Advance-Model-using-LSTM
Description
This project demonstrates a time series forecasting model that predicts stock prices using Long Short-Term Memory (LSTM), a type of Recurrent Neural Network (RNN). It includes data collection from Yahoo Finance, preprocessing, model training, and evaluation, with visualizations of the predicted and actual stock prices.

Project Structure
Data Collection: Historical stock price data is downloaded using yfinance.
Data Preprocessing: The data is scaled, and a sequence of past data points (time steps) is used to predict future stock prices.
Model: The LSTM model is built using Keras and TensorFlow.
Evaluation: The model's performance is evaluated using Mean Squared Error (MSE).
Visualization: The actual vs. predicted stock prices are plotted to visually compare the results.
Features
Fetch stock data: Uses yfinance to get stock data from Yahoo Finance.
LSTM Model: A deep learning model that uses past stock price data to predict future prices.
Evaluation: Predictions are evaluated and compared with the actual data.
Visualization: Data visualization using matplotlib for clear insights into model performance.
Installation
Prerequisites

Python 3.x
Jupyter Notebook or any Python IDE (e.g., VSCode, PyCharm)

Libraries

bash
Copy code
pip install numpy pandas matplotlib scikit-learn tensorflow yfinance
Clone the repository
bash
Copy code
git clone https://github.com/Rebecasuji/Stock-Prediction-LSTM.git
cd Stock-Prediction-LSTM
Run the Jupyter Notebook
Launch Jupyter Notebook and open the Stock prediction basic to advance Model.ipynb file.

bash
Copy code
jupyter notebook "Stock prediction basic to advance Model.ipynb"
Usage
Change the Stock Ticker: In the notebook, you can specify the stock ticker you want to analyze by changing the variable ticker = 'AAPL' to any stock symbol of your choice.
Customize Time Steps: Adjust the time_step parameter to control the number of past days the model uses to predict future prices.
Project Flow
Data Loading: Stock data is loaded from Yahoo Finance for a specified date range.
Data Preprocessing: The data is normalized and reshaped to be fed into the LSTM model.
Model Training: An LSTM model is built and trained on the preprocessed data.
Predictions: The model makes predictions on unseen data.
Visualization: Predicted vs. actual prices are visualized for evaluation.
Example Plot
Below is an example of the output graph comparing predicted and actual stock prices:

Results
The model's performance is evaluated using Mean Squared Error (MSE). Lower MSE indicates better prediction accuracy.
