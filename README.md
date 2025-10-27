# Vendor Performance Analysis | SQL & Python

## Project Overview
This project focuses on analyzing vendor performance and inventory efficiency using transactional sales data. The objective is to identify top-performing vendors, assess profit drivers, evaluate bulk purchasing impact, and detect inefficiencies in stock turnover and pricing strategies.

## Objectives
- Identify underperforming brands needing promotional or pricing adjustments.  
- Determine top vendors contributing to overall sales and profit.  
- Assess the financial impact of bulk purchasing on unit costs.  
- Analyze inventory turnover to minimize holding costs and improve cash flow.  
- Compare profitability across high- and low-performing vendors using statistical validation.

## Tools & Techniques
- **SQL** – Data cleaning, filtering, and aggregation of vendor metrics.  
- **Python (Pandas, Matplotlib, SciPy)** – Exploratory data analysis, visualization, and hypothesis testing.  
- **Statistical Analysis** – Confidence intervals, correlation analysis, and t-tests for validating profitability differences.

## Dataset
The dataset contains product- and vendor-level transactional details such as `Vendor`, `Product`, `Purchase Price`, `Sales Quantity`, `Gross Profit`, `Profit Margin`, `Freight Cost`, and `Stock Turnover`. It represents business operations data used for vendor and profitability analysis.

## Key Insights
- 198 brands showed high margins but low sales volume, requiring targeted promotions.  
- Top 10 vendors contributed 65.7% of total purchases, indicating potential dependency risk.  
- Bulk purchasing led to ~72% cost savings compared to smaller orders.  
- $2.71M tied up in unsold inventory, suggesting poor stock management.  
- Profit margins differ significantly between top- and low-performing vendors (confirmed via hypothesis testing).

## Recommendations
- Reprice high-margin, low-volume products to increase sales.  
- Diversify vendor base to reduce supply chain risk.  
- Leverage bulk purchase advantages for cost efficiency.  
- Improve marketing and distribution strategies for low-performing vendors.  

---

*This project demonstrates end-to-end data analysis capabilities involving SQL querying, Python-based EDA, and statistical validation to optimize vendor and inventory performance.*
