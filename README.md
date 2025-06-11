# Netflix Stock Price Analysis & Interactive Dashboard

This project provides an in-depth analysis of Netflix (NFLX) stock price data, presented through both a Python-based analysis and an interactive Tableau dashboard. The primary goal is to explore the historical performance of Netflix stock, identify trends, and visualize key metrics using a combination of programming and business intelligence tools.

## Dataset

The project uses the `NFLX.csv` dataset, which contains historical daily stock price information for Netflix, including:

* **Date:** The trading date
* **Open:** The price at which the stock first traded for the day
* **High:** The highest price of the stock during the day
* **Low:** The lowest price of the stock during the day
* **Close:** The price at which the stock last traded for the day
* **Adj Close:** The closing price adjusted for dividends and stock splits
* **Volume:** The number of shares traded during the day

## Project Components

1.  **Python Analysis (`Netflix new.ipynb`)**
    A Jupyter Notebook that performs data loading, cleaning, and in-depth time-series analysis. It uses libraries like Pandas, Matplotlib, and Plotly to generate static and interactive charts, including candlestick patterns and moving averages to analyze market trends.

2.  **Tableau Dashboard**
    An interactive dashboard that allows for dynamic exploration of the Netflix stock data. The dashboard provides a user-friendly interface to:
    * Filter data by date ranges.
    * Drill down into specific time periods.
    * View key performance indicators (KPIs).
    * Explore relationships between price, volume, and time.

## Technologies Used

* **Python** for data analysis and scripting.
* **Pandas** and **NumPy** for data manipulation and numerical analysis.
* **Matplotlib**, **Seaborn**, and **Plotly** for data visualization.
* **Jupyter Notebook** for interactive development.
* **Tableau** for creating an interactive business intelligence dashboard.

## How to Use

### Python Analysis

To run the Python analysis, you will need to have Python and the required libraries installed. You can install the necessary packages using pip:

```bash
pip install pandas numpy matplotlib seaborn plotly
```

Then, you can open and run the `Netflix new.ipynb` notebook in a Jupyter environment. Make sure the `NFLX.csv` file is in the same directory as the notebook.

### Tableau Dashboard

To view the dashboard, you will need to have Tableau Desktop or the free Tableau Reader installed. Simply open the `.twbx` file to interact with the visualizations and explore the data.
