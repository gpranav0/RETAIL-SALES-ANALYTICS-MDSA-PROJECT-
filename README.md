# Retail Sales Analytics

A Python-based exploratory data analysis project for retail transaction data. The notebook walks through data cleaning, feature engineering, visual analysis, profitability review, sales performance breakdowns, and RFM customer segmentation.

## Project Overview

This project analyzes retail sales records to identify revenue trends, product/category performance, sales channel contribution, regional patterns, discount impact, profit margins, and customer value segments.

The analysis is contained in a Jupyter notebook and uses `pandas`, `NumPy`, `Matplotlib`, `Seaborn`, and `Plotly` for data preparation, statistics, and visualization.

## Repository Contents

| File | Description |
| --- | --- |
| `RetailSalesAnalytics.ipynb` | Main Jupyter notebook containing the complete analytics workflow. |
| `RetailSalesAnalytics.csv` | Retail sales dataset used by the notebook. |
| `README.md` | Project documentation. |

## Dataset Summary

The dataset contains 1,000 retail order records with 20 columns.

| Attribute | Details |
| --- | --- |
| Date range | 2023-01-03 to 2024-12-31 |
| Product categories | Electronics, Books, Home & Kitchen, Clothing, Sports |
| Sales channels | Online, In-Store, Mobile App |
| Regions | North, West, East, South, Central |

Key columns include:

- `order_id`, `order_date`, `order_status`
- `customer_id`, `customer_segment`
- `product_id`, `product_name`, `category`, `brand`
- `unit_price`, `quantity_sold`, `discount`
- `revenue`, `cost_of_goods_sold`, `profit`
- `sales_channel`, `region`, `city`, `store_id`, `salesperson_id`

## Analysis Workflow

The notebook covers the following steps:

1. Import required Python libraries.
2. Load and inspect the retail sales dataset.
3. Clean data, parse dates, handle missing values, remove duplicates, and create derived fields.
4. Analyze monthly revenue trends with a 3-month rolling average.
5. Compare revenue and average profit margin by category.
6. Identify the top 10 products by revenue.
7. Break down revenue by sales channel and region.
8. Explore correlations between revenue, quantity, price, discount, profit, and margin.
9. Review profit margin distribution by category.
10. Build a revenue heatmap by day of week and month.
11. Analyze the relationship between discount rate and profit margin.
12. Segment customers using RFM analysis.
13. Calculate revenue and profit summary statistics.
14. Visualize quarterly revenue by category with a Plotly sunburst chart.

## Key Techniques Used

- Data cleaning and preprocessing
- Date-based feature engineering
- Grouped aggregation and pivot tables
- Rolling average trend analysis
- Correlation analysis
- Profit margin analysis
- Interactive Plotly visualizations
- RFM customer segmentation
- Descriptive statistical analysis with NumPy

## Requirements

Install the required Python packages:

```bash
pip install pandas numpy matplotlib seaborn plotly jupyter
```

Python 3.10 or newer is recommended.

## How to Run

1. Clone or download this repository.
2. Open a terminal in the project folder.
3. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn plotly jupyter
```

4. Start Jupyter Notebook:

```bash
jupyter notebook
```

5. Open `RetailSalesAnalytics.ipynb`.
6. Run the cells from top to bottom.

The notebook expects `RetailSalesAnalytics.csv` to be in the same folder as the notebook.

## Example Insights

This project can help answer business questions such as:

- Which product categories generate the most revenue?
- Which products are the highest revenue contributors?
- How does revenue change across months and quarters?
- Which sales channels and regions perform best?
- How do discounts affect profit margins?
- Which customers are champions, loyal, potential, or at risk?

## Output

The notebook produces both static and interactive visualizations, including:

- Monthly revenue line charts
- Category revenue bar charts
- Top product rankings
- Channel and region breakdowns
- Correlation heatmaps
- Profit margin distributions
- Discount vs. margin scatter plots
- 3D RFM customer segmentation
- Quarterly category sunburst charts

## Author

Retail Sales Analytics project for Python-based data analysis and business insights.
