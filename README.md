# Stock-Price-Movement-Prediction-Using-Machine-Learning-and-Sentiment-Analysis
This project predicts stock price movement by combining historical market data with sentiment analysis of news headlines. By leveraging machine learning (XGBoost) and sentiment scores, the project aims to assist investors in making data-driven decisions. It also serves as a comprehensive portfolio project to demonstrate advanced data science and machine learning skills.

## Features
- **Data Collection:** Retrieves historical stock data using `yfinance`.
- **Sentiment Analysis:** Uses the VADER sentiment analyzer to compute sentiment scores from news headlines.
- **Technical Indicators:** Calculates moving averages and RSI.
- **Machine Learning:** Implements an XGBoost classifier to predict whether the stock price will go up or down.
- **Visualization:** Plots the actual vs. predicted stock movements.
- **Extendability:** Can be extended to incorporate live news feeds and more advanced models.

## Getting Started

### Prerequisites
- Python 3.7+
- Jupyter Notebook or Jupyter Lab

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/stock-sentiment-prediction.git
   cd stock-sentiment-prediction
