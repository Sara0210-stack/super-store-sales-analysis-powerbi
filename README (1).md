# Super Store Sales Analysis & 15-Day Forecasting

An interactive Power BI project exploring retail sales performance across regions, customer segments, product categories, payment methods, and shipping modes. A second report page visualises a 15-day sales forecast using Power BI's built-in forecasting functionality.

## Project objective

Analyse historical retail sales data to understand business performance, compare results across business dimensions, identify monthly trends, and visualise a short-term sales forecast.

## Tools used

- **Microsoft Excel** — data cleaning and preparation
- **Microsoft Power BI** — interactive report building and built-in forecasting

> This project did not use custom DAX measures. The report was created using Power BI visuals and its built-in forecasting feature.

## Dataset

The supplied CSV contains **5,901 rows and 23 columns**, with order dates spanning **1 January 2019 to 31 December 2020**. It includes order, shipping, customer, geographic, product, sales, quantity, profit, returns, and payment-mode fields.

The dataset file used while preparing this documentation is named `SuperStore_Sales_Dataset.csv`. The original publisher/source URL has not yet been confirmed. Add the original dataset link and attribution here before publishing.

The CSV contains missing values in the `Returns` field and two completely empty columns (`ind1`, `ind2`). The dataset should be reviewed and cleaned appropriately before analysis. Do not upload the raw CSV to a public repository until its source licence and redistribution permissions have been checked.

## Dashboard 1: Super Store Sales Dashboard

![Super Store Sales Dashboard](images/sales-dashboard.png)

The dashboard includes:

- KPI cards for Sales, Quantity, Profit, and a displayed sales ratio metric
- Sales by region
- Sales by customer segment
- Sales by payment mode
- Monthly sales and monthly profit trends by year
- Sales by shipping mode
- Sales by product category and sub-category
- State-level sales map

The screenshot displays approximately **1.57M in sales**, **22K in quantity**, and **175.26K in profit**. These are the values visible in the report screenshot. Confirm currency, units, and metric definitions before presenting them externally.

## Dashboard 2: 15-Day Sales Forecast

![15-Day Sales Forecast](images/sales-forecast-dashboard.png)

The forecast page visualises historical sales and a 15-day forecast using Power BI's built-in forecasting functionality. It also includes a state-level sales comparison.

Forecasts are estimates based on historical patterns, not guarantees of future sales.

## Data preparation and workflow

1. Obtained the retail sales CSV dataset.
2. Cleaned and prepared the data in Microsoft Excel.
3. Imported the prepared data into Power BI.
4. Built report visuals to compare sales and profit across multiple dimensions.
5. Used Power BI's built-in forecasting functionality to visualise a 15-day sales forecast.

## Dashboard export

A two-page PDF export of the Power BI report is included as `SuperStore_Sales_Dashboard.pdf`:
- Page 1: Super Store Sales Dashboard
- Page 2: Super Store Sales Forecast – 15 Days Forecast

## Repository structure

```text
super-store-sales-analysis-powerbi/
├── README.md
├── SuperStore_Sales_Dashboard.pdf
└── images/
    ├── sales-dashboard.png
    └── sales-forecast-dashboard.png
```

## Before publishing

1. Add the original dataset name, publisher, and source URL.
2. Check the dataset licence and attribution requirements.
3. Add the `.pbix` file if you want recruiters to inspect the report and you are comfortable sharing it.
4. Do not publish raw data unless redistribution is permitted.
5. Check that the PBIX file contains no private credentials or connection details.

## Key learning outcomes

- Preparing and cleaning tabular data in Excel
- Designing an interactive business intelligence report
- Comparing performance across regions, customer segments, and product categories
- Communicating historical trends with KPI cards and charts
- Exploring short-term forecasting in Power BI
