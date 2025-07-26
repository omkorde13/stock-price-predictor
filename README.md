# Stock Price Predictor

Predict stock closing prices using historical data and LSTM neural networks in Python.

## Features

- Fetches historical stock data via `yfinance`
- Visualizes price history with Matplotlib
- Data preprocessing and scaling
- LSTM model for time series prediction (Keras/TensorFlow)
- Model evaluation (RMSE, plots)
- Customizable for any stock ticker

## Quick Start

1. Clone the repo:
   ```bash
   git clone https://github.com/omkorde13/stock-price-predictor.git
   cd stock-price-predictor
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch the notebook:
   ```bash
   jupyter notebook Stock_Price_Predictor.ipynb
   ```
   Or upload it to [Google Colab](https://colab.research.google.com/).

## Files

- `Stock_Price_Predictor.ipynb` — main notebook
- `requirements.txt` — dependencies
- `images/` — example plots
- `.gitignore` — recommended ignores
- `LICENSE` — MIT license
- `README.md` — project info

## Example Output

![Prediction Plot](images/sample_prediction.png)

## License

MIT

**Note:** This is for educational purposes only, not financial advice.