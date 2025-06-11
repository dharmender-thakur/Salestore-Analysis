
# 📊 Salestore Analysis

Running a retail business like Salestore is exciting—but making smart business decisions takes more than just strong sales. With thousands of transactions happening across various customer segments, product categories, and cities, we needed to dig into the data to uncover insights and answer some key business questions:

- **💸 What is our total revenue and total profit to date?**
- **🧍‍♂️ Who are our top customers, and how much are they contributing?**
- **🗃 Which product categories—Furniture, Office Supplies, or Technology—are performing best?**
- **🏙 Which cities generate the highest sales volumes?**
- **📈 What are the monthly and yearly trends in sales across all segments?**

 Using **Excel functions, data cleaning techniques, and an interactive dashboard**, we transformed raw data into meaningful insights. Let's explore! 🔍

![Salestore Dashboard](https://github.com/dharmender-thakur/Salestore-Analysis/blob/668c880d12a5053f5142f53d550d6b06b58b911f/Salestore%20Dashboard.png)


## 📂 Understanding the Data
The dataset consists of **three key tables**, each serving a distinct and valuable purpose in the analysis.

### 1️⃣ Orders Data 📦
This table tracks every coffee sale made, capturing essential transaction details:
- **Row ID** - Unique identifier for each purchase.
- **Order ID** – Unique identifier for each transaction.
- **Order Date** – The date when the order was placed.
- **Ship Date** - The date on which the order was shipped to the customer.
- **Ship Mode** - The Shipping class use for delivery.
- **Customer ID** – Links to the customer who placed the order.
- **Product ID** – Identifies the type of coffee sold.

### 2️⃣ Customers Data 👥
This table gives us insight into who is buying the products:
- **Customer ID** – A unique code that identifies each customer.  
- **Customer Name** – The full name of the customer who placed the order.  
- **Segment** – The market segment the customer belongs to (e.g., Consumer, Corporate, Home Office).  
- **Country** – The country where the customer is located.  
- **City** – The city of the customer’s shipping address.  
- **State** – The state or province where the customer resides.  
- **Postal Code** – The postal code of the customer’s address.  
- **Region** – The broader geographical region (e.g., East, West, Central, South) of the order location.  
- **Product ID** – A unique identifier for each product purchased.

### 3️⃣ Products Data ☕
This table focuses on coffee varieties and their pricing:
- **Product ID** – A unique identifier for each product.  
- **Category** – The main classification of the product (e.g., Furniture, Office Supplies, Technology).  
- **Sub-Category** – A more specific grouping within each category (e.g., Chairs, Binders, Phones).  
- **Product Name** – The full name or description of the product.  
- **Sales** – The total revenue generated from the product sale.  
- **Quantity** – The number of units sold in the transaction.  
- **Discount** – The percentage or amount of discount applied to the product.  
- **Profit** – The net gain from the sale after subtracting costs and discounts.

---


### 🛠 Data Processing in Excel – Cleaning & Transformation

To ensure reliable insights, the raw data was carefully cleaned and prepared before analysis. Here's a summary of the key steps:

- **🔹 Data Merging:** Used **XLOOKUP** and **INDEX-MATCH** functions to bring in customer names and product details into the orders table using Customer ID and Product ID.  
- **🔹 Handling Duplicates & Missing Data:** Identified and removed duplicate entries, and addressed missing values to maintain data integrity.  

---


### 🔍 Exploratory Data Analysis (EDA) in Excel

Once the data was cleaned and transformed, we conducted exploratory data analysis using Excel’s built-in tools to identify patterns, trends, and relationships. Here's how the analysis was carried out:

- **📊 Pivot Tables:**  
  Created pivot tables to summarize sales, profit, and quantity across different dimensions such as Region, Segment, Category, and Time. These helped identify high-performing areas and customer segments quickly.

- **📈 Interactive Charts:**  
  Developed bar charts, line graphs, and pie charts to visualize revenue trends, top customers, top-selling categories, and sales over time. This visual storytelling made complex patterns easy to understand at a glance.

- **📅 Time Series Analysis:**  
  Used date-based grouping to break down sales by month and quarter. This helped uncover trend and seasonality.

- **🎯 Filtering & Slicers:**  
  Implemented slicers for fields like Segment, Category, and Region to allow dynamic filtering and better dashboard interactivity.

- **🧮 KPI Indicators:**  
  Added calculated metrics such as Total Revenue, Total Profit as KPI cards for high-level business insight.

---

### 📈 Summary of Insights

### 1️⃣ What is our total revenue and total profit to date?**
- **📈 Total Revenue:** $2,297,201 – representing the complete sales generated across all transactions.  
- **💰 Total Profit:** $286,397 – showing net earnings after accounting for discounts and costs.



### 2️⃣ Who are our top customers, and how much are they contributing?**
- The top 5 customers generate over 20% of total revenue, highlighting the impact of cultivating a few strong repeat buyers.
      
    ![Top 5 Customers](https://github.com/user-attachments/assets/aef96953-717b-427c-ab0c-000d1b1be3e4)


  

### 3️⃣ Which product categories—Furniture, Office Supplies, or Technology—are performing best?**
- Technology tops the chart with ₹836,154 in sales—~37% of total revenue—indicating strong demand and high customer interest.
- Furniture accounts for ₹742,000, capturing ~33% of sales—great for high-value conversions and premium offerings.
- Office Supplies follow with ₹719,047, contributing ~30%—suggesting this category could benefit from volume-based promotions.

   ![image](https://github.com/user-attachments/assets/19f1a026-c65e-4a40-805c-8aa9a3db1e4a)


  

### 4️⃣ Which cities generate the highest sales volumes?**
-  New York City leads with ₹256,368 in revenue—over 27% of total from these top 5 cities—making it the prime target for promotions and repeat campaigns.
-  Los Angeles follows with ₹175,851, showing strong potential for scaling distribution and customer retention efforts.

    ![image](https://github.com/user-attachments/assets/4573a857-16d5-4a79-b1d8-ecbf89999d9b)
  
  


 
### 5️⃣ What are the monthly and yearly trends in sales across all segments?**
- **Sales peak in October - December**, likely due to holiday demand.
- **Seasonal trends** suggest potential for **seasonal promotions to maximize profits**
- **Over the years, sales increased by 51% between 2014-2017**, showing a steady business growth.

---    

### 📊 Final Dashboard – Everything in One Place

  ![Salestore Dashboard](https://github.com/dharmender-thakur/Salestore-Analysis/blob/668c880d12a5053f5142f53d550d6b06b58b911f/Salestore%20Dashboard.png)
    
  After processing and analyzing the data, we created an interactive Excel dashboard that provides a complete sales and performance overview:
    
  ✅ **Total Revenue & Profit** – Quickly showcases overall business health.  
  ✅ **Sales by Segment** – Tracks trends across Consumer, Corporate, and Home Office segments.    
  ✅ **Top Customers** – Highlights the top 5 contributors to sales.  
  ✅ **Top Performing Cities** – Reveals where most sales originate.  
  ✅ **Sales by Category** – Analyzes revenue from Technology, Office Supplies, and Furniture.  
  ✅ **Monthly Trends** – Captures seasonal sales patterns over multiple years.

 ---   

### 📂 Files Included in This Project

📁 **Salestore Dashboard.xlsx** – The interactive Excel Dashboard.  
📁 **Salestore Dataset.xlsx** – The raw data used for analysis.   

---

## 🔧 How to Use This Dashboard

1️⃣ Download **Salestore Dashboard.xlsx** and open in Excel.  
2️⃣ Use the **filter options** to adjust the data view.  
3️⃣ Explore different sections to understand **sales trends, customer behavior, and profitability.**  

---
🌟 If you found this project useful, consider **starring** ⭐ the repository on GitHub!






