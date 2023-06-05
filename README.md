# MercadoLibre Analysis

This project involves analyzing and predicting search trends and sales data for MercadoLibre, one of the most popular eCommerce platforms in Latin America.

## Project Objective

The objective of this project is to understand the patterns in MercadoLibre's popularity and sales data, and to provide reliable forecasts that can aid strategic decision-making.

## Data 

The datasets used in this analysis contain hourly Google search trend data and daily historical sales figures for MercadoLibre.

## Steps Involved

### Step 1: Initial Setup

The required packages and dependencies are imported. This includes pandas for data manipulation, Prophet for time series forecasting, and hvplot and matplotlib for data visualization.

### Step 2: Data Importing and Cleaning

The search trends and sales data are imported and cleaned. This involves handling missing data, parsing dates, and setting appropriate indices.

### Step 3: Initial Data Analysis and Visualization

Initial analysis and visualization of the data are performed to understand the patterns and trends in the data. These insights can guide the construction of the forecasting model.

### Step 4: Time Series Forecasting with Prophet

The cleaned search trends data is prepared for forecasting with Prophet, a powerful time series forecasting tool developed by Facebook. The model is fitted and predictions are made for the next 2000 hours.

This forecast allows us to identify patterns in the popularity of MercadoLibre. We analyze which time of the day and day of the week exhibit the most popularity, and when the search traffic is at its lowest in a calendar year.

### Step 5: Sales Forecasting

Prophet is also used to forecast sales for the next quarter (90 days). The sales data is prepared in a similar manner to the search trends data. The model's components are analyzed to understand the seasonal patterns in the company's revenue, and to identify peak revenue days.

The forecast provides a most likely, best-case, and worst-case scenario for total sales for the next quarter. This information can be highly valuable to the finance division for budget planning and setting investor expectations.

## Conclusion

This analysis provides valuable insights into the trends in MercadoLibre's popularity and sales, and makes reliable forecasts for the near future. These can aid the company in making data-driven decisions and strategies.

## Requirements

- Python 3
- pandas
- fbprophet
- hvplot
- matplotlib

## Usage

To run this analysis, you will need to have Python installed, preferably through Anaconda. You will also need to install the fbprophet, hvplot, and matplotlib packages.

You can then download the project and run the Jupyter notebook.

Please ensure that you have the necessary data files (Google search trends and daily historical sales data for MercadoLibre) available in the same directory as the Jupyter notebook.
