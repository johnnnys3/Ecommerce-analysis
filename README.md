# Pakistan E-Commerce Analytics Dashboard

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C)
![License](https://img.shields.io/badge/license-unspecified-lightgrey)

A data analytics and business intelligence project exploring Pakistan's largest e-commerce dataset. The analysis turns raw transaction records into insights about revenue performance, customer behavior, payment preferences, seasonal trends, and operational opportunities.

## Features

- Data cleaning pipeline for a 1M+ row transaction dataset (584,504 records after cleaning)
- Product category and payment method performance analysis
- Seasonal and time-based revenue trend detection
- Statistical analysis of payment/order-status relationships and price distributions
- ARIMA-based sales forecasting
- Business recommendations derived from the analysis

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Statsmodels
- Scikit-learn
- Jupyter Notebook

## Installation

```bash
git clone https://github.com/johnnnys3/Ecommerce-analysis.git
cd Ecommerce-analysis
pip install -r requirements.txt
```

## Usage

```bash
jupyter notebook Ecommerce_analysis.ipynb
```

Dataset: Pakistan Largest E-Commerce Dataset, July 2016 – August 2018, covering order details, product categories, payment methods, customer information, dates, and prices.

## Project Structure

```text
Ecommerce-analysis/
├── Ecommerce_analysis.ipynb   # Cleaning, EDA, statistics, forecasting
├── requirements.txt
└── README.md
```

## Contributing

Contributions are welcome. Fork the repository, create a feature branch, and open a pull request describing your changes.

## License

No license specified.
