# Just In Time | Power BI Sales & Supply Chain Analysis

## Project Overview

This project analyzes the sales and supply chain activities of **Just In Time**, a fictional retailer selling sporting goods and outdoor products.

The objective is to develop an interactive Power BI dashboard that helps Sales, Inventory, and Delivery Managers monitor performance, identify potential issues, and support data-driven decisions.

The report covers data from **2015 to 2017** and consists of five dashboard pages.

## Tools & Skills

- **Power BI:** Interactive dashboards and data visualization
- **Power Query:** Data cleaning and transformation
- **DAX:** KPI calculations and time-based analysis
- **Data Modeling:** Relationships, Calendar table, and Product dimension
- **Data Analysis:** Business insights and recommendations

## Dashboard Pages

| Page | Analysis |
|---|---|
| 1. Overall Business Performance | Sales, orders, customers, and business trends |
| 2. Sales & Product Performance | Best-selling products, categories, and sales volume |
| 3. Customer & Demand Analysis | Customer markets, countries, and demand trends |
| 4. Inventory & Fulfillment Analysis | Month-end inventory, estimated costs, and fulfillment time |
| 5. Shipping & Dispatch Analysis | Dispatch time, reported Late Rate, and shipping data quality |

## Key Findings

**1. Sales performance declined in 2017**

Gross Sales decreased by approximately **16%** in 2017 compared with 2016, while Units Sold decreased by around **26%**. Sales volume also dropped sharply during the last quarter of 2017.

**2. Inventory availability requires further investigation**

At the end of December 2017, **96 out of 118 product types** had zero recorded inventory. However, zero inventory does not necessarily indicate a stockout.

**3. Shipping records show potential operational and data-quality issues**

The Reported Late Rate was approximately **47.78%** among records not marked Invalid. Additionally, **8.86%** of order-item records had negative Shipping Time.

## Business Recommendations

**Sales:** Investigate the products and customer markets contributing most to the 2017 sales decline.

**Inventory:** Prioritize reviewing zero-stock products with strong recent demand before making replenishment decisions.

**Shipping:** Review First Class dispatch records and improve validation of Order Date and Shipment Date.

## Data Preparation & Limitations

During data preparation, I worked with four source tables: orders_and_shipments, inventory, fulfillment, and product.

Important considerations included:

- Using distinct Order IDs to avoid counting multiple order items as separate orders.
- Treating month-end inventory records as snapshots instead of summing inventory across months.
- Flagging negative Shipping Time records as Invalid.
- Retaining products with missing classification under an Unmapped group.
- Treating the original Profit figures cautiously because of data inconsistencies.

The dashboard identifies areas for further investigation; it does not establish the underlying causes of operational issues.

## Dashboard Screenshots

### Page 1 – Overall Business Performance
![Overall Business Performance](TranDanLe_finalproject_1.png)

### Page 2 – Sales & Product Performance
![Sales & Product Performance](TranDanLe_finalproject_2.png)

### Page 3 – Customer & Demand Analysis
![Customer & Demand Analysis](TranDanLe_finalproject_3.png)

### Page 4 – Inventory & Fulfillment Analysis
![Inventory & Fulfillment Analysis](TranDanLe_finalproject_4.png)

### Page 5 – Shipping & Dispatch Analysis
![Shipping & Dispatch Analysis](TranDanLe_finalproject_5.png)
## Acknowledgements

Special thanks to **Khanh Le and Minh Hieu** for sharing their Power BI knowledge, guidance, and perspectives on business-oriented data analysis.
