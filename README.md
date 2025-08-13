BTC Price Prediction
This project predicts Bitcoin’s closing price using historical market data and a Linear Regression model.

Data Source: Real-time BTC-USD data fetched via Yahoo Finance (yfinance).

Features Used: Open, High, Low, Close, Volume.

Processing: Data cleaning, feature-target separation, train-test split, and feature scaling using StandardScaler.

Model: Linear Regression from scikit-learn.

Evaluation: R² score and Mean Squared Error (MSE).

Output:
      CSV file with actual vs. predicted prices (bitcoin_price_predictions.csv).
      Matplotlib visualization comparing actual and predicted prices.
      Prediction for the next day’s closing price based on the latest available data.

Tech Stack: Python, Pandas, NumPy, scikit-learn, yfinance, Matplotlib.
