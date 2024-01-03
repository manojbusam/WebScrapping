# E-commerce Website Data Scraping and Analysis

This repository contains Jupyter notebooks demonstrating how to perform web scraping on an e-commerce website (e.g., Amazon), followed by data cleaning and visualization using popular Python libraries.

## Getting Started

### Prerequisites

Make sure you have the following installed:

| Tool                          | Version/Requirements       |
|-------------------------------|----------------------------|
| [![Python](https://img.shields.io/badge/Python-3.6+-blue)](https://www.python.org/downloads/) | - |
| [![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)](https://jupyter.org/install) | - |
| ![Requests](https://img.shields.io/badge/requests-required-green) ![BeautifulSoup4](https://img.shields.io/badge/beautifulsoup4-required-green) ![Pandas](https://img.shields.io/badge/pandas-required-green) ![Matplotlib](https://img.shields.io/badge/matplotlib-required-green) ![Seaborn](https://img.shields.io/badge/seaborn-required-green) | Required Libraries |


Install the required libraries using pip:

```bash
pip install requests beautifulsoup4 pandas matplotlib seaborn
```

### Usage

1. **Web Scraping (`webscrapping.ipynb`):** The `webscrapping.ipynb` notebook demonstrates how to scrape product information from an e-commerce website (e.g., Amazon). Open the notebook using Jupyter and follow the instructions to execute each cell.

2. **Data Cleaning (`webscrapping.ipynb`):** The `webscrapping.ipynb` notebook showcases the process of cleaning the scraped data. It covers tasks like handling missing values, formatting columns, and preparing the data for visualization.

3. **Data Visualization (`webscrapping.ipynb`):** The `webscrapping.ipynb` notebook illustrates various data visualization techniques using Matplotlib. It presents insights and trends based on the cleaned e-commerce data.
![Screenshot 2024-01-03 at 10 44 43 AM](https://github.com/manojbusam/WebScrapping/assets/44409170/7866c82c-7886-49dc-872e-6c1710900fe5)

## Files

- `webscrapping.ipynb`: Jupyter Notebook for web scraping.
- `amazon_products.csv`: Example dataset obtained from the scraping process.

## Notes

- Always verify if the website allows scraping and the data can be used as per their policy.

## Acknowledgments

- The notebooks in this repository are for educational purposes only.
- The example data used in this demonstration might not reflect real product information and is solely for illustration purposes.

