# Online Sales Data Analytics

## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Findings](#findings)
- [Recommendations](recommendations)
- [Limitations](limitations)
- [References](references)
  
### Project Overview
---
This project performs descriptive analytics on global transactions across various product categories using an online sales dataset. It analyzes sales, revenue, products, geography, and payment methods. Based on the analysis, trends are identified, data-driven insights are generated, and recommendations are provided for future improvements.

### Data Sources
---
The dataset used is a CSV file sourced from Kaggle, titled "Online Sales Dataset-Popular Marketplace Data", [link](https://www.kaggle.com/datasets/shreyanshverma27/online-sales-dataset-popular-marketplace-data). It contains data on global transactions across various product categories.


### Tools
---
 - Excel is used for the following:
    - data acquisition
    - data preparation and cleaning for issues like duplicates, empty rows, missing values, white spaces and misspellings.
    - data visualization (pivot table & charts, and dashboard)

### Exploratory Data Analysis
---
Exploratory Data Analysis (EDA) is employed to answer key research questions as follows:
  - What is the total revenue and total unit of product items sold?
  - What is the general revenue/sales trend?
  - Which geographic region generates the largest revenue/sales?
  - What is the contribution of each product category to total sales?
  - Which payment options are predominant in each region?
  - What are the top 5 product items in terms of sales? 

### Data Analysis
---
  - Pivot tables
  - Pivot Charts: like line charts, Bar charts, Pie charts and cards.
  - Pivot timelines:
  - Pivot Slicers: 2 slicers (geographic region and Payment methods)
  - Interractive Excel Dashboard

[Dashboard.xlsx](https://github.com/user-attachments/files/16400332/Dashboard.xlsx)

<img width="521" alt="Dashboard_Screenshot" src="https://github.com/user-attachments/assets/795ec1b4-f3a4-4e51-bd50-d1358f7cd67a">

### Findings
---
Summary of results.
  - Total revenue for the period was $80,567.85, and total units of product items sold was 518.
  - General sales/revenue trended positively in the first four months, peaking in January and April at $8,000 and $6,710, respectively, before declining until August.
  - North America generated the highest revenue overall, with a total of $36,844.
  - Electronics contributed the most to revenue ($34,982), while Beauty products ($2,622) and Books ($1,862) were the least. Home Appliances, Sports, and Clothing occupied the middle positions in descending order.
  - Credit cards were used for the majority of sales but not at all in Europe. Debit cards were the least used, only appearing in Asia. PayPal was exclusively used in Europe.
  - The top 5 product items by sales were:
    1. Canon EOS RS Camera ($3,899.99)
    2. LG OLED TV (2,599.98)
    3. MacBook Pro 16-inch ($2,499.99)
    4. Apple MacBook Pro 16-inch ($2,399)
    5. iPhone 14 Pro ($1,999.98)

### Recommendations
---
1. Leverage Seasonal Trends:
    - Focus marketing efforts in January and April when sales peak.
    - Plan promotions and inventory to capitalize on high-demand periods.
2. Target High-Revenue Regions:
    - Invest more in North American markets, which generate the highest revenue.
    - Explore strategies to boost sales in underperforming regions.
3. Promote High-Performing Categories:
    - As the top revenue contributor, increase marketing for Electronics in North America.
    - Explore opportunities to boost sales in lower-performing categories like Beauty products and Books.
4. Optimize Payment Methods:
    - Ensure credit cards usage is supported more in North America.
    - Promote debit card usage in Asia and expand PayPal options in Europe.
5. Highlight Top-Selling Products:
    - Feature bestsellers like Canon EOS R5 Camera and LG OLED TV in marketing campaigns.
    - Ensure sufficient stock of top-selling items to meet demand

### Limitations
---
1. The study relies on a dataset from a single source (Kaggle), which may not fully represent all global transactions. This limitation affects the generalizability of the findings to broader market conditions.
2. The analysis of payment methods is limited to three options (credit card, debit card, PayPal), potentially overlooking other significant payment methods used in various regions. This limitation might skew the understanding of regional payment preferences.

### References
---
  - Online Sales Dataset - Popular Marketplace Data. Kaggle.com. [link](https://www.kaggle.com/datasets/shreyanshverma27/online-sales-dataset-popular-marketplace-data)

