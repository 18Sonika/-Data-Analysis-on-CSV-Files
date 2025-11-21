📊 Sales Data Analysis Project

This project performs an in-depth Exploratory Data Analysis (EDA) on a complex sales dataset using Python, Pandas, and Matplotlib. It provides meaningful insights into sales performance, customer behavior, product trends, region-wise growth, and much more.

🧾 Dataset Description

The dataset used in this project is advanced_sales_dataset.csv, which contains 30 records with 12 attributes representing real-world sales transactions.

Columns Included:
Column Name	Description
Date	Date of transaction
Order_ID	Unique order identifier
Product	Name of the product
Category	Product category (Electronics, Furniture, etc.)
Sub_Category	Detailed product category
Quantity	Units sold
Unit_Price	Price per unit
Region	Geographic region (North, East, West, South)
City	City of the customer
Payment_Method	Mode of payment (UPI, Card, Cash)
Customer_Age	Age of the buyer
Customer_Type	New or Returning customer
🎯 Project Objective

The main objective of the project is to:

✔ Understand overall sales performance
✔ Identify top-performing products & categories
✔ Study customer purchase behavior
✔ Analyze trends over time (daily & monthly)
✔ Perform region-wise & city-wise profitability analysis
✔ Visualize and summarize data using charts
✔ Perform correlation & pivot table analysis

This project demonstrates your ability to work with realistic datasets, clean and preprocess data, run meaningful analyses, and build visual insights.

🔧 Technologies Used

Python

Pandas

Matplotlib

Jupyter Notebook / Google Colab

🧹 Data Preprocessing Steps

Before analysis, the following operations were performed:

Converted Date column to datetime format

Created new columns:

Total_Sales = Quantity * Unit_Price

Month = Date converted to monthly period

Checked for missing values

Converted datatypes where required

Organized data for group-by operations and charts

📈 Analysis Performed

This project includes several types of analysis that provide deep insights into the sales data.

1️⃣ Key Performance Indicators (KPIs)

Total Revenue

Total Quantity Sold

Total Orders

Average Order Value (AOV)

These metrics summarize the overall business performance.

2️⃣ Product-Level Analysis
✔ Top Products by Revenue

Identifies which products contribute the most to total sales.

✔ Quantity Sold by Product

Highlights fast-moving products.

3️⃣ Category & Sub-Category Analysis

Category-wise revenue comparison

Sub-category performance using bar charts

Understanding contribution to total revenue

This helps in product portfolio analysis.

4️⃣ Region & City Sales Analysis

Which region generates the highest revenue

City-wise sales comparison

Identifies strong and weak geographical markets

5️⃣ Payment Method Insights

Pie chart showing:

UPI usage

Credit Card usage

Cash payments

This helps understand customer payment preferences.

6️⃣ Customer Behavior Analysis

Includes:

Age distribution of customers

New vs Returning customer comparison

Age-group wise purchasing power

This helps in targeted marketing.

7️⃣ Time Series Analysis
Daily Sales Trend

Shows daily revenue fluctuations.

Monthly Sales Trend

Identifies long-term trends for business planning.

8️⃣ Correlation Analysis

Examines relationships between:

Quantity

Unit Price

Customer Age

Total Sales

Useful for understanding factors influencing revenue.

9️⃣ Pivot Table (Advanced Report)

A pivot table is created to analyze:

Product vs Region

Total revenue for each product in each region

This is similar to Excel pivot table capabilities.

🔟 Additional Insights

Best-selling product record

Average selling price by category

Age group revenue comparison

These extra insights add more depth to the analysis.

📊 Visualization Samples

Charts used in the project:

Bar charts

Pie charts

Line plots

Horizontal bar charts

Histograms

These visualizations help communicate insights clearly.

🧠 Key Insights from the Project

Here are some sample insights you can include:

Electronics category contributes the highest revenue

Delhi, Mumbai, and Pune are top-performing cities

UPI is the most preferred payment method

Laptops generate the highest revenue among products

Returning customers purchase more consistently

Sales show upward trend in early January

These insights may vary depending on how you visualize and interpret the data.

📦 How to Run the Project
Step 1: Clone the repository
git clone https://github.com/your-username/sales-data-analysis.git

Step 2: Install dependencies
pip install pandas matplotlib

Step 3: Run the notebook

Open sales_analysis.ipynb in Jupyter Notebook or Google Colab.

🚀 Conclusion

This project demonstrates strong skills in:

Data preprocessing

Exploratory data analysis

Visualization

Business intelligence

Python data manipulation

It showcases your ability to turn raw data into meaningful insights — a crucial skill in data analysis, data science, and business analytics.
