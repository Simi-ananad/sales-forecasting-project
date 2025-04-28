# sales-forecasting-project

# Sales Forecasting Project

## Project Overview
Forecasting daily sales for a UK-based e-commerce retailer using historical transaction data.

## Dataset
- Source: [Kaggle E-Commerce Data](https://www.kaggle.com/datasets/carrie1/ecommerce-data)
- Period: 01/12/2010 to 09/12/2011
- Variables: InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

## Approach
1. **Data Preprocessing**:
   - Cleaned missing values
   - Filtered returns and invalid transactions
   - Calculated daily revenue

2. **Exploratory Analysis**:
   - Identified weekly seasonality
   - Detected outliers

3. **Modeling**:
   - Used Facebook's Prophet
   - 7-day forecast

## How to Run
1. Install requirements:
   ```bash
   pip install pandas numpy matplotlib prophet jupyter
