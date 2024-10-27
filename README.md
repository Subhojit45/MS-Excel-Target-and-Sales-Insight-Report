# Sales Analytics of AtliQ Hardware

## Project Overview
AtliQ Hardware is a multinational company selling hardware products such as mice, printers, monitors, and more. The company's customers fall into two categories: e-commerce platforms (e.g., Amazon, Flipkart) and brick-and-mortar stores (e.g., Croma, Best Buy). AtliQ operates through three main channels:
- **Retailer**: Croma, Amazon
- **Direct Channel**: AtliQ E-store, AtliQ Exclusive
- **Distributor**: Neptune (for international markets)

## Project Objective
The goal of this report is to analyze AtliQ Hardware's sales performance from 2019 to 2021. The insights will help the company identify growth trends, evaluate market performance, and make data-driven decisions. The analysis is based on AtliQ Hardware's fiscal year (Sep-Aug).

## Report Components:
1. **Customer Net Sales Performance**
2. **Market Performance vs. Target**
3. **Top 10 Products by Sales**
4. **Top 5 and Bottom 5 Products by Quantity Sold**
5. **Division-Level Sales Report**
6. **New Products Launched in 2021**
7. **Top 5 Marketplaces**

## Methods:
1. **ETL (Extract, Transform, Load)**:
   - Data was extracted from external sources, transformed into the desired format, and loaded into Excel for further analysis.
   
2. **Data Cleaning**:
   - Conducted in Power Query Editor to ensure consistency. Adjusted headers, replaced some entries, and converted 'Qty' to absolute values to address negative numbers.
   
3. **Data Modeling**:
   - Connected dimension and fact tables to establish relationships.

4. **DAX (Data Analysis Expressions)**:
   - Created measures for 2019, 2020, and 2021 Net Sales.
   - Calculated '21 vs. '20 Net Sales and their percentage growth.

5. **Pivot Table and Power Pivot**:
   - Used Pivot Tables and Power Pivot to create detailed reports.

6. **Conditional Formatting**:
   - Applied formatting to highlight key figures.

## Key Insights:
1. **Top Customers in 2021**:
   - Amazon ($82.1M), AtliQ Exclusive ($61.1M), AtliQ e-Store ($53.0M)
   
2. **Market Growth**:
   - Significant growth in 2021 across all markets, led by India and USA. However, targets were not met.
   
3. **Top Product**:
   - 'AQ Electron 4 3600 Desktop Processor' generated the highest sales ($19.4M).
   
4. **Top and Bottom Products by Quantity**:
   - 'AQ Master Wired x1 MS' (4.2M units) and 'AQ Home Allin1 Gen 2' (8.9K units)
   
5. **Division Sales**:
   - Peripherals & Accessories led sales in 2021 ($338.4M), followed by PCs ($165.8M) and Networking & Storage ($94.7M).
   
6. **New Product Sales**:
   - Sales of 16 new products launched in 2021 totaled $172.2M, 29.4% of total sales.
   
7. **Top 5 Marketplaces in 2021**:
   - India, USA, South Korea, Canada, and the United Kingdom

## Skills Gained:
- Understanding the ETL process
- Data cleaning and transformation
- Importance of fiscal years
- Establishing data model relationships with Power Pivot
- Creating Pivot Tables and DAX formulas

## Conclusion
The Sales Report for AtliQ Hardware provides valuable insights into sales performance over the years, identifying trends and patterns across customers and markets. These insights support data-driven strategic decision-making and foster company growth.

## Combined Report
The combined report for AtliQ Hardware's sales analysis is attached to this repository. It includes detailed insights and data visualizations supporting the findings mentioned above.
