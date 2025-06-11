# Netflix Analysis: Stock Market Trends & Content Library Insights

This project provides a two-part analysis of Netflix. It explores both the company's financial performance through its stock market data and its content strategy through an in-depth look at its library of movies and TV shows.

## Part 1: Netflix Stock Price Analysis

This part of the project focuses on the financial performance of Netflix stock (NFLX) using time-series analysis in Python.

### Project Component

* **Python Analysis (`Netflix new.ipynb`)**
    A Jupyter Notebook that performs data loading, cleaning, and in-depth time-series analysis on Netflix's historical stock data. It uses libraries like Pandas, Matplotlib, and Plotly to generate static and interactive charts, including candlestick patterns and moving averages to analyze market trends.

### Technologies Used

* **Python** for data analysis and scripting.
* **Pandas** and **NumPy** for data manipulation and numerical analysis.
* **Matplotlib**, **Seaborn**, and **Plotly** for data visualization.
* **Jupyter Notebook** for interactive development.

### How to Use

To run the Python analysis, you will need to have Python and the required libraries installed. You can install the necessary packages using pip:

```bash
pip install pandas numpy matplotlib seaborn plotly
```

Then, you can open and run the `Netflix new.ipynb` notebook in a Jupyter environment. Make sure the `NFLX.csv` file is in the same directory as the notebook.

---

## Part 2: Netflix Content Library Dashboard

This part of the project uses Tableau to create an interactive dashboard for exploring the Netflix content library.

### Dataset

This analysis uses a relational dataset of Netflix titles, including information about:
* Titles, descriptions, release years, and ratings.
* Directors and cast members.
* Countries of production.
* Content categories (genres).

### Project Component

* **Tableau Dashboard**
    An interactive dashboard that allows for a deep dive into the Netflix content library. The dashboard provides a user-friendly interface to analyze:
    * The distribution of movies vs. TV shows.
    * Trends in content releases over the years.
    * The most common genres, directors, and actors on the platform.
    * A geographical breakdown of content by country.

### Technologies Used

* **Tableau** for creating an interactive business intelligence dashboard.

### How to Use

To view the dashboard, you will need to have Tableau Desktop or the free Tableau Reader installed. Simply open the `.twbx` file to interact with the visualizations and explore the data.
