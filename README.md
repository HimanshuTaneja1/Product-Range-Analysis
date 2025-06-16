🛍️ Product Range Analysis 


This project integrates various data analysis techniques and tools to derive actionable business insights from retail transaction data. The objective is to explore customer behaviors, segment customers, and evaluate product performance using a modified version of the Online Retail dataset.

🎯 Project Objectives
Top Performer Analysis: Identify the top customer, product, and category by sales.

Customer Segmentation: Segment customers using RFM (Recency, Frequency, Monetary) metrics.

Sales Impact of Pricing: Analyze whether higher-priced products contributed more to sales compared to lower-priced products.

Seasonality Analysis: Determine if sales were significantly higher during the Christmas season (December) compared to other months.

🔍 Project Scope
Data Preprocessing

Exploratory Data Analysis (EDA)

RFM-Based Customer Segmentation

Percentile Ranking

K-Means Clustering

Product Categorization & Category-Wise Analysis

Statistical Hypothesis Testing

Insights and Business Recommendations

Interactive Dashboard (Tableau)

📁 Project Structure
The project is organized across five Jupyter Notebooks:

1_data_prep_and_EDA.ipynb — Data Cleaning and Exploratory Data Analysis

2_customer_rfm_segmentation.ipynb — RFM Metrics & Customer Clustering

3_product_categorization.ipynb — Product Classification

4_product_category_analysis.ipynb — Category-Level Insights

5_statistical_hypotheses.ipynb — Statistical Tests, Insights & Conclusion

🧾 Dataset Overview
Source: Modified Online Retail dataset from the UCI Machine Learning Repository

Time Range: 29-Nov-2018 to 07-Dec-2019

Total Records: 541,909 transactions

Attributes:

InvoiceNo: Unique transaction ID (prefix 'C' indicates cancellation)

StockCode: Unique product code

Description: Product name

Quantity: Quantity purchased

InvoiceDate: Date and time of the transaction

UnitPrice: Price per unit

CustomerID: Unique customer identifier

📊 Dashboard
An interactive Tableau dashboard is included to visualize key metrics and insights from the analysis.

✅ Summary
Final observations, business insights, statistical conclusions, and relevant resources can be found in the notebook: 5_statistical_hypotheses.ipynb
