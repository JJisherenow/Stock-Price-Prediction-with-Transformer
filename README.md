# Stock Price Prediction with Transformer

This project implements a stock price prediction model using a Transformer neural network in PyTorch, and evaluates trading strategies with backtesting.

## Features

- Data preprocessing and normalization for stock price data.
- Sequence modeling using a custom Transformer-based neural network.
- Model training, validation, and early stopping.
- Backtesting trading strategies using the `backtrader` library.
- Example data and pre-trained model weights included.

## File Structure

- `test.ipynb`: Main Jupyter notebook for data processing, model training, and backtesting.
- `data.csv`: Main stock price dataset.
- `data/`: Additional data files and pre-trained model weights.
  - `model_weight.pth`: Pre-trained model weights.
  - `SSE50_20050104_20230406`: Example stock data.
  - `Stock_List.csv`: List of stocks.

## Requirements

- Python 3.8+
- PyTorch
- numpy
- matplotlib
- pandas
- backtrader
- tqdm

## Usage

1. Install the required packages.
2. Open and run `test.ipynb` to preprocess data, train the model, and run backtesting.
3. You can use the provided `model_weight.pth` for inference or further training.

## License

This project is for research and educational purposes. 