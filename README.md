# Stock-Market-Data-Analysis-and-Predictive-Modeling

## Project Description
This project analyzes stock data for AAPL, TSLA, JPM, and NVDA, including data collection, cleaning, EDA, predictive modeling (ARIMA, LSTM, Prophet), and an interactive Plotly Dash dashboard. It provides insights into price trends, correlations, and forecasts.

## Setup Instructions
1. Clone the repository: `git clone https://github.com/yourusername/stock_market_project.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run data collection: `python code/data_collection/download_data.py`
4. Clean data: `python code/data_collection/clean_data.py`
5. Perform EDA: `python code/eda/eda_analysis.py`
6. Train models: `python code/models/prophet_model.py`
7. Launch dashboard: `python code/dashboard/app.py`

## Dependencies
See `requirements.txt` for required Python libraries.

## Folder Structure
- `datasets/`: Cleaned stock data in CSV format.
- `models/`: Trained Prophet models.
- `code/`: Scripts for data collection, cleaning, EDA, modeling, and dashboard.
- `plots/`: Visualizations (HTML files).

## Acknowledgements
Built with `yfinance`, `Plotly`, `Prophet`, and `TensorFlow`. Thanks to Yahoo Finance for data.
