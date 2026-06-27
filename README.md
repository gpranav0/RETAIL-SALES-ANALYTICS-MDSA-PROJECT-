# Retail Sales Analytics

Retail Sales Analytics is a Python exploratory data analysis project for retail transaction data. It uses a Jupyter notebook to clean the data, engineer useful features, visualize business performance, analyze profitability, and segment customers with RFM analysis.

## Project Overview

The project analyzes retail order records to answer common business questions about revenue, profit, discounts, customer behavior, product performance, sales channels, and regional trends.

The analysis is implemented in `RetailSalesAnalytics.ipynb` using:

- pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Jupyter Notebook

## Repository Contents

| File | Description |
| --- | --- |
| `RetailSalesAnalytics.ipynb` | Main notebook with the complete analysis workflow. |
| `RetailSalesAnalytics.csv` | Retail sales dataset used by the notebook. |
| `README.md` | Project documentation. |

## Dataset Summary

The dataset contains 1,000 retail order records and 20 columns.

| Field | Details |
| --- | --- |
| Date range | 2023-01-03 to 2024-12-31 |
| Product categories | Electronics, Books, Home & Kitchen, Clothing, Sports |
| Sales channels | Online, In-Store, Mobile App |
| Regions | North, West, East, South, Central |

Important columns include:

- `order_id`, `order_date`, `order_status`
- `customer_id`, `customer_segment`
- `product_id`, `product_name`, `category`, `brand`
- `unit_price`, `quantity_sold`, `discount`
- `revenue`, `cost_of_goods_sold`, `profit`
- `sales_channel`, `region`, `city`, `store_id`, `salesperson_id`

## Analysis Workflow

The notebook covers:

1. Importing the required Python libraries.
2. Loading and inspecting the dataset.
3. Cleaning the data, parsing dates, handling missing values, removing duplicates, and creating derived fields.
4. Analyzing monthly revenue trends with a 3-month rolling average.
5. Comparing revenue and average profit margin by category.
6. Identifying the top 10 products by revenue.
7. Breaking down revenue by sales channel and region.
8. Exploring correlations between revenue, quantity, price, discount, profit, and margin.
9. Reviewing profit margin distribution by category.
10. Building a revenue heatmap by day of week and month.
11. Analyzing the relationship between discount rate and profit margin.
12. Segmenting customers with RFM analysis.
13. Calculating revenue and profit summary statistics.
14. Visualizing quarterly revenue by category with a Plotly sunburst chart.

## Example Business Questions

This analysis can help answer questions such as:

- Which product categories generate the most revenue?
- Which products are the highest revenue contributors?
- How does revenue change by month and quarter?
- Which sales channels and regions perform best?
- How do discounts affect profit margins?
- Which customers are champions, loyal, potential, or at risk?

## Outputs

The notebook produces static and interactive visualizations, including:

- Monthly revenue trend charts
- Category revenue comparisons
- Top product rankings
- Sales channel and region breakdowns
- Correlation heatmaps
- Profit margin distributions
- Discount versus margin scatter plots
- 3D RFM customer segmentation charts
- Quarterly category sunburst charts

## Requirements

Python 3.10 or newer is recommended.

Install the required packages:

```bash
pip install pandas numpy matplotlib seaborn plotly jupyter
```

## How to Run

1. Clone or download this repository.
2. Open a terminal in the project folder.
3. Install the dependencies:

```bash
pip install pandas numpy matplotlib seaborn plotly jupyter
```

4. Start Jupyter Notebook:

```bash
jupyter notebook
```

5. Open `RetailSalesAnalytics.ipynb`.
6. Run the notebook cells from top to bottom.

The notebook expects `RetailSalesAnalytics.csv` to be in the same folder as `RetailSalesAnalytics.ipynb`.

## Author

Retail Sales Analytics project for Python-based data analysis and business insights.
