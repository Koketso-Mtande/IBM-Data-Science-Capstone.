# Analyzing Historical Stock/Revenue Data and Building a Dashboard

## Project Overview
This project is part of the IBM Data Science Professional Certificate capstone. It demonstrates how to extract stock and revenue data for Tesla (TSLA) and GameStop (GME) using Python, then visualize them side by side.

## Tools and Libraries Used
- **yfinance** — to download historical stock data
- **requests** — to download webpage HTML
- **BeautifulSoup** — to parse HTML and extract tables
- **pandas** — for data manipulation
- **matplotlib** — for plotting graphs

## Project Tasks
1. **Extract Tesla Stock Data** using `yf.Ticker("TSLA").history(period="max")`
2. **Extract Tesla Revenue Data** by web scraping the revenue page
3. **Extract GameStop Stock Data** using `yf.Ticker("GME").history(period="max")`
4. **Extract GameStop Revenue Data** by web scraping the revenue page
5. **Plot Tesla Stock Graph** — historical share price vs. revenue
6. **Plot GameStop Stock Graph** — historical share price vs. revenue

## Key Findings
- **Tesla:** Both revenue and stock price showed strong growth between 2018 and 2021.
- **GameStop:** Stock price surged sharply around 2021 (short squeeze), but revenue did not show a similar increase.

## Files
- `final_project.ipynb` — Main Jupyter notebook containing all code and analysis
- Screenshots of results (optional)

## Author
Koketso Mtande
