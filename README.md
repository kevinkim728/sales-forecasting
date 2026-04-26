# Sales Forecasting Model

A machine learning project that uses Facebook Prophet to forecast daily restaurant sales based on 2 years of historical data.

## Overview

Built a time series forecasting model using real daily sales data from a restaurant I managed. The goal was to predict future demand to improve inventory planning and reduce waste.

## Tools & Libraries
- Python
- Pandas
- Facebook Prophet
- Matplotlib

## Data
- 2 years of daily restaurant sales data (2024-2025)
- 731 rows of real historical data
- Data was consolidated and cleaned from multiple Excel files before modeling

## Results
- Achieved 83% forecast accuracy (16.68% MAPE)
- Model successfully detected weekly and seasonal patterns
- Forecasted 90 days of future daily sales

## How to Run
1. Clone the repository
2. Install dependencies: `pip install pandas prophet matplotlib openpyxl`
3. Open `sales_forecasting.ipynb` in Jupyter or VS Code
4. Run all cells