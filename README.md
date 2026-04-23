[README.md](https://github.com/user-attachments/files/27020545/README.md)
# Sales & Customer Insights Dashboard (Power BI)

## Project Overview
This project analyzes retail sales data to identify trends, profitability drivers, discount impact, and customer behavior.  
The objective is to provide clear business insights that can help improve revenue, profit, and retention.

## Business Questions
- Which categories and regions drive the most sales and profit?
- How do discount levels impact profitability?
- What customer behavior patterns (new vs repeat) can support retention strategy?

## Dataset
- File: `sample_sales_data.csv`
- Type: Transaction-level sales data
- Main fields:
  - `order_id`, `order_date`, `customer_id`
  - `region`, `category`, `sub_category`, `product_name`
  - `sales`, `quantity`, `discount`, `profit`

## Tools & Skills Used
- Power BI Desktop
- Power Query (data preparation)
- DAX (calculated columns/measures)
- Data visualization and business storytelling

## Data Preparation
- Corrected data types (date, numeric, text)
- Removed/validated duplicates
- Created calculated columns:
  - `Discount Band`
  - `Discount Band Ordered`
  - `Order Month`
  - `Customer Type (New/Repeat)`

## Dashboard Pages

### 1) Sales & Profit Executive Overview
- KPI cards: Total Sales, Total Profit, Total Orders, Avg Order Value, Profit Margin %
- Monthly Sales vs Profit trend
- Sales by Category
- Profit by Region

### 2) Discount & Profit Analysis
- Average Profit by Discount Band
- Average Sales by Discount Band
- Discount vs Profit scatter plot (order level)
- Interactive slicers: Region, Category

### 3) Customer Insights
- New vs Repeat Customers
- Top 10 Customers by Sales
- Monthly Active Customers
- Total Unique Customers

## Key Insights
- Low and medium discounts can support sales, but discount strategy must be balanced with margin goals.
- Category and regional performance varies, indicating targeted actions are needed by segment.
- Repeat customers provide stable value and are important for long-term growth.

## Files in This Repository
- `daxwell_sales_customer_insights.pbix` (Power BI report)
- `sample_sales_data.csv` (dataset)
- `page1_executive_overview.png`
- `page2_discount_profit_analysis.png`
- `page3_customer_insights.png`
- `README.md`

## Screenshots

### Executive Overview
![Executive Overview](page1_executive_overview.png)

### Discount & Profit Analysis
![Discount & Profit Analysis](page2_discount_profit_analysis.png)

### Customer Insights
![Customer Insights](page3_customer_insights.png)

## How to Open
1. Download this repository.
2. Open `daxwell_sales_customer_insights.pbix` in Power BI Desktop.
3. If prompted, map data source to `sample_sales_data.csv`.

Author
Srinivas Bodasu
