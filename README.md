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
    - data visualization (pivot table & pivot charts, and interactive dashboard)
    - Dashboard Interaction (Timeline and Slicers)

### Exploratory Data Analysis
---
Exploratory Data Analysis (EDA) is employed to answer key research questions as follows:
1.  What is the total revenue and total unit of product items sold?
2.  What is the general revenue/sales trend?
3.  Which geographic region generates the largest revenue/sales?
4.  What is the contribution of each product category to total sales?
5.  Which payment options are predominant in each region?
6.  What are the top 5 product items in terms of sales? 

### Data Analysis
---
#### 1.  What is the total revenue and total unit of product items sold?
  The visual cards shown below were used to answer this.
  
<img width="197" alt="Screenshot 2024-08-07 184859" src="https://github.com/user-attachments/assets/f3ec2dce-e970-4888-9ed9-59eb4dc44547">
<img width="198" alt="Screenshot 2024-08-07 184929" src="https://github.com/user-attachments/assets/3688cfc5-262a-409a-a551-e13d5c0d6f76">

#### 2.  What is the general revenue/sales trend?
  The line chart below is used to answer this.
  
<img width="373" alt="Screenshot 2024-08-07 185159" src="https://github.com/user-attachments/assets/ac2f7fff-c32a-4c6e-8509-23ee521f01d8">

#### 3.  Which geographic region generates the largest revenue/sales?
  The slicer below is used to answer this.

<img width="197" alt="Screenshot 2024-08-07 184811" src="https://github.com/user-attachments/assets/8c61ce25-1550-495c-bf8f-d38f2766aba9">

#### 4.  What is the contribution of each product category to total sales?
  The pie chart below is used to answer the question.

<img width="197" alt="Screenshot 2024-08-07 185053" src="https://github.com/user-attachments/assets/5618c100-8afa-41ff-8823-0b8fed1297ef">

#### 5.  Which payment options are predominant in each region?
  The slicer below is used to answer this.

<img width="198" alt="Screenshot 2024-08-07 184836" src="https://github.com/user-attachments/assets/b5b09b2a-4028-4cd0-a3d8-7457e969baf3">

#### 6.  What are the top 5 product items in terms of sales?
  The column chart below is used to answer the question.

<img width="229" alt="Screenshot 2024-08-07 185137" src="https://github.com/user-attachments/assets/333f7c5f-6f34-41bb-9792-ee27b6696476">


If you want to see the step-by-step process of the analysis, please watch my video. [Link](https://youtu.be/hwzCd0QZ90c) 

Check the Excel file for the interactive dashboard [here](https://github.com/user-attachments/files/16400332/Dashboard.xlsx)


### Findings
---
Summary of results.

<img width="721" alt="Screenshot 2024-07-27 144640" src="https://github.com/user-attachments/assets/1a04c61a-62be-44d3-b65c-51d2f5304f72">


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

