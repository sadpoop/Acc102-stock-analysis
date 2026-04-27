# Acc102-stock-analysis
ACC102 Stock Price Analysis Project

## 1. Problem & User
This project analyzes historical stock price trends and return correlations of four major tech companies (AAPL, MSFT, GOOG, AMZN). The analysis is designed for students and instructors in ACC102 to demonstrate basic financial data analysis skills using Python.

## 2. Data
- **Source**: Yahoo Finance historical daily stock prices (2021–2023)
- **Access Date**: 2024-04-27
- **Key Fields**: `Date`, `company_name`, `Open`, `High`, `Low`, `Close`, `Volume`
- **Data File**: `stock_data.csv` (included in the repo)

## 3. Methods
1.  Load and clean the stock price data using `pandas`
2.  Plot closing price trends and moving averages (10-day, 20-day, 50-day)
3.  Calculate daily returns and analyze volatility
4.  Generate a correlation heatmap of stock returns using `seaborn`

## 4. Key Findings
- AAPL and MSFT show strong positive correlation in their price movements.
- Longer moving averages (50-day) effectively smooth out short-term price noise.
- AMZN exhibits the highest volatility among the four stocks.
- GOOG’s returns show the weakest correlation with other tech stocks in the sample.
- All four stocks show a general upward trend over the 2021–2023 period.

## 5. How to Run
1.  Clone or download this repository.
2.  Ensure Python 3.x is installed, with the following packages: `pandas`, `matplotlib`, `seaborn`.
3.  Open `stock_analysis.ipynb` in Jupyter Notebook.
4.  Run all cells in order to reproduce the analysis and charts.

## 6. Product Link / Demo
The full analysis and visualizations are available in the `stock_analysis.ipynb` notebook in this repository.

## 7. Limitations & Next Steps
- **Limitations**: The dataset is limited to four tech stocks; results may not generalize to other sectors.
- **Next Steps**: Extend the analysis to include more companies, add risk metrics (Sharpe ratio), and explore predictive models for price movements.
