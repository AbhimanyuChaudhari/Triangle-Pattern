# Triangle Pattern Detection in Financial Data

## Overview
This project focuses on detecting triangle patterns in financial time series data, specifically in intraday minute data. The detection is based on identifying pivot points in the price chart and analyzing the linear regression slopes of significant highs and lows to recognize triangular patterns.

## Data Source
The code utilizes intraday minute data obtained from Yahoo Finance (yfinance library). The user can specify the ticker symbol and the desired time range for data retrieval.

## Dependencies
- pandas
- numpy
- matplotlib
- yfinance
- plotly
- scipy

Install the required dependencies using the following command:
```bash
pip install pandas numpy matplotlib yfinance plotly scipy
Usage
Specify the ticker_symbol, start_date, and end_date variables in the code.
Run the code to download and analyze intraday minute data.
The script identifies pivot points and uses linear regression to analyze slope patterns.
The detected triangular patterns are displayed using Plotly.
Code Structure
triangle_pattern_detection.ipynb: Jupyter notebook containing the code for triangle pattern detection.
README.md: Project documentation.
requirements.txt: List of Python dependencies.
Results
The code outputs visualizations using Plotly to display detected pivot points and linear regression slopes for triangle patterns.

Contributing
Contributions are welcome! If you have suggestions, improvements, or find issues, please open an issue or submit a pull request.

License
This project is licensed under the MIT License.
