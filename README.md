
# Indian Stock Prediction Project

This project is a web application for predicting Indian stock prices using machine learning. It provides a user interface for viewing current market data and making stock price predictions.

## Features

1. Home Page:
   - Display of major Indian stock indices (Nifty 50, Sensex)
   - Global market indices overview
   - Top 10 volume gainers
   - Top 10 price gainers
   - Top 10 price losers

2. Prediction Page:
   - Stock price prediction for a given ticker symbol
   - Predictions for tomorrow, next week, next month, next six months, and next year
   - Visualization of actual vs predicted prices
   - Display of prediction metrics (MSE and Accuracy)

## Technologies Used

- Backend: Python, Flask
- Frontend: HTML, CSS, JavaScript
- Data Visualization: Plotly.js
- Machine Learning: TensorFlow, Keras (LSTM model)
- Data Fetching: yfinance

## Setup and Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   cd indian-stock-prediction
   ```

2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

3. Run the Flask application:
   ```
   python app.py
   ```

4. Open a web browser and navigate to `http://localhost:8057`

## Usage

1. On the home page, you can view current market data and indices.
2. Click on "Go to Prediction Page" to make stock price predictions.
3. Enter a valid stock ticker symbol and click "Predict".
4. View the prediction results and charts.

## File Structure

- `app.py`: Main Flask application file
- `templates/home1.html`: HTML template for the web interface
- `requirements.txt`: List of Python package dependencies

## Note

This project is for educational purposes only. Stock predictions are based on historical data and should not be used as financial advice.

## Contributing

Contributions to improve the project are welcome. Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Make your changes and commit (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Create a new Pull Request



