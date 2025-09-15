### **Power BI report for Retail Sales Analysis**
<img width="886" height="499" alt="Screenshot 2025-09-13 215913" src="https://github.com/user-attachments/assets/174cbd38-eb50-4a31-8665-f43acc0aaffb" />
I have utilized the **Retail Sales dataset** to develop a comprehensive **Power BI report**, designed to provide actionable insights into sales performance, customer demographics, and product category trends. This report consists of four distinct pages: Overview, Customer Segment, Region (optional if location data available), and Product. Each page is structured with different visualizations and analytical components to effectively interpret and present key aspects of the dataset.
### **Key Performance Indicators (KPIs)**
The report highlights crucial KPIs, including:
-	**Total Sales** – The overall revenue generated from transactions.
-	**Average Sales** – The mean transaction value across all customers.
-	**Profit per Transaction** – The average profitability per transaction.
-	**Sum of Price per Unit** – Total of all product unit prices sold.
-	**Total Transactions** – The count of completed sales transactions.
### **DAX Functions Used for KPIs**
1.**Total Sales** = SUM('retail_sales_dataset'[Total Amount])
2.**Avg Sales** = AVERAGE('retail_sales_dataset'[Total Amount])
3.**Profit per Transaction** = [Total Sales] / COUNT('retail_sales_dataset'[Transaction ID])
4.**Sum Price per Unit** = SUM('retail_sales_dataset'[Price per Unit])
5.**Total Transactions** = COUNT('retail_sales_dataset'[Transaction ID])

### **Visualizations and Insights**
To facilitate a data-driven approach, the report incorporates various charts and graphs, including:
-	**Sales Trend Chart (Year-wise)** – Displays sales over time to identify growth patterns.
-	**Sales by Gender & Product Category** – Shows demographic-based purchasing behavior.
-	**Category Sales Distribution (Pie Chart)** – Provides insights into contribution of Electronics, Clothing, and Beauty.
-	**Product-Wise Sales** – Analyzes which product categories generate higher revenue.
1. **Overview Page**
This page provides a high-level summary of sales and performance metrics, giving users a quick glance at overall business performance through KPIs and essential charts such as Total Sales, Average Sales, and Profit per Transaction.
2. **Customer Segment Page**
The Segment Dashboard is designed to analyze different customer demographics (Gender, Age). It contains charts showing:
•	Sales by Gender
•	Sales by Age Group
This helps in understanding customer behavior and identifying which segments contribute most to sales and profitability.
3. **Region Page** (Optional)
Since the dataset does not directly include regional data, this page can be adapted to show Year-wise sales comparison instead. It highlights performance trends across different years, helping management assess sales growth.
4. **Product Page**
The Product Dashboard provides insights into product-wise sales performance. It features:
•	Sales by Product Category (Bar/Pie Chart)
•	Average Sales by Product Category
This helps businesses understand which products drive revenue growth and which categories may need strategic adjustments in pricing or marketing.

 ### **Conclusion**
This Retail Sales Power BI report serves as a valuable tool for business decision-making, helping stakeholders:
-	Identify top-performing product categories.
-	Analyze customer demographics (Gender & Age) for targeted marketing.
-	Track yearly sales trends for strategic planning.
-	Monitor KPIs like total sales, average sales, and profitability to improve business efficiency
