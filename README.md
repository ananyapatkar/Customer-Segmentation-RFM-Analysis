# Customer-Segmentation-RFM-Analysis
Customer segmentation using RFM (Recency, Frequency, Monetary) analysis on Online Retail dataset with Python (Pandas, NumPy, Matplotlib). RFM analysis helps businesses identify high-value customers and design targeted marketing strategies.

Dataset Used: Online Retail (2009–2010)

Methodology
1️⃣ Data Cleaning
Removed null CustomerID values
Removed cancelled invoices
Removed negative quantities
Converted InvoiceDate to datetime

2️⃣ Feature Engineering
Created TotalPrice = Quantity × UnitPrice

3️⃣ RFM Calculation
Recency → Days since last purchase
Frequency → Number of unique invoices
Monetary → Total amount spent

4️⃣ RFM Scoring
Divided customers into 4 quantile groups (1–4)
Higher score = better customer

5️⃣ Segmentation
Customers were classified into:
Champions
Loyal Customers
Potential Loyalists
New Customers
Lost Customers

6️⃣ Visualization
Bar chart showing distribution of customer segments
