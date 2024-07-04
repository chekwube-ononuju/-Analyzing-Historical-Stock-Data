elcome to the hands-on lab where I analyzed historical stock and revenue data and build a dashboard to visualize our findings. This README file will guide you through the steps and contents of this lab.

Requirements
To complete this lab, you will need:
Python 3.x
Jupyter Notebook
Libraries: yfinance, requests, beautifulsoup4, pandas, matplotlib, plotly
Project Structure
.
├── data
│   └── raw                   # Raw data files
├── notebooks
│   ├── 01_extract_stock_data.ipynb  # Notebook for extracting stock data
│   ├── 02_scrape_revenue_data.ipynb # Notebook for scraping revenue data
│   ├── 03_data_cleaning.ipynb       # Notebook for data cleaning
│   ├── 04_data_visualization.ipynb  # Notebook for data visualization
│   └── 05_build_dashboard.ipynb     # Notebook for building the dashboard
├── README.md
└── requirements.txt

Data Sources
Stock Data: Extracted using the yfinance library.
Revenue Data: Scraped from webpages using the requests and BeautifulSoup libraries.
