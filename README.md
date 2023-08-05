# Pattern Recognition AI for Candlestick Patterns and Stock Prediction

This GitHub repository contains an AI model that performs pattern recognition for 8 different candlestick patterns using the VGG-16 architecture. Additionally, it provides stock price prediction using a stacked LSTM model trained on Yahoo Finance data, and stock recommendations based on firm data and news using basic ML models.

## Table of Contents

- [Introduction](#introduction)
- [Candlestick Pattern Recognition](#candlestick-pattern-recognition)
- [Stock Price Prediction](#stock-price-prediction)
- [Stock Recommendation](#stock-recommendation)
- [Technologies Used](#technologies-used)
- [License](#license)

## Introduction

This AI model is designed to assist investors in making informed decisions by recognizing 8 common candlestick patterns and providing stock price predictions and recommendations based on historical data and news sentiment.

## Candlestick Pattern Recognition

The AI model uses the VGG-16 architecture to recognize the following candlestick patterns:

1. Bullish Engulfing
2. Bearish Engulfing
3. Hammer
4. Hanging Man
5. Doji
6. Shooting Star
7. Inverted Hammer
8. Spinning Top

## Stock Price Prediction

The stock price prediction model is implemented using a stacked LSTM (Long Short-Term Memory) neural network trained on historical stock data obtained from Yahoo Finance. It can forecast future stock prices based on past price trends.

## Stock Recommendation

The stock recommendation system analyzes firm-specific data and news sentiment from Yahoo Finance. It employs basic ML models such as Logistic Regression and Naive Bayes to recommend whether to hold, sell, or buy a particular stock.

## Technologies Used

The following technologies are utilized in this project:

- VGG-16: For candlestick pattern recognition.
- LSTM: For stock price prediction using historical data.
- Yahoo Finance API: To fetch historical stock data and news.
- Scikit-learn: For implementing basic ML models in the stock recommendation system.


## Contributing

Contributions to improve the AI model's accuracy, add more candlestick patterns, enhance stock price prediction, or optimize the stock recommendation system are welcome. Please follow the guidelines outlined in [CONTRIBUTING.md](CONTRIBUTING.md) if you wish to contribute.

## License

This project is licensed under the [MIT License](LICENSE).

---

Thank you for exploring our Pattern Recognition AI for Candlestick Patterns and Stock Prediction. We hope it proves helpful in your investment journey. For any questions or suggestions, feel free to reach out to us. Happy investing!
