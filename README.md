##Project Title:
#Retail Sales and Profit Analysis 

##1. Objective:
Introduction and Objective
Retail businesses increasingly rely on data analytics to drive decisions. Microsoft Power BI is a powerful analytics platform that can transform raw sales data into actionable insights
. This project aims to analyze a sample retail dataset (Q4 sales and customer data) using Power BI. We will visualize sales and profit trends for October–December and interpret key performance metrics. The objective is to identify patterns (e.g. seasonal peaks, top products/regions) and derive business recommendations for improving retail performance.

##2. Dataset Description:
Dataset Overview
* October SE Regional Sales: 1,000 transaction records (columns: Order ID, Customer ID, Product Category, Order Date, Quantity, Order Status, State, Manufacturer Price, Sale Price, Total Profit, Sales Agent).
* November SE Regional Sales: 1,000 similar records for November.
* December SE Regional Sales: 1,000 similar records for December.
* Customers: 1,000 records containing customer contact details and order info (including address, city, state, phone), providing demographic context.
*  Total Q4 Regional Sales: 42 aggregated records by Product Category and State, summarizing Sales Total, Manufacturer Price Total, Q4 Profit, and Units Sold per month (Oct, Nov, Dec).

##3. Data Transformation:
* Data Types & Formats: Converted date fields to proper datetime types and standardized column names (e.g. trimmed trailing spaces). Numeric fields (sales, profit) were confirmed as numbers
*  Missing Values: Checked for null or missing entries – none were found across all sheets duplicates were also absent.
* Filter Status: Removed canceled orders, focusing only on completed sales (Delivered/Shipped) to ensure accuracy of revenue and profit figures.
* Consolidation: Combined the three monthly sheets into a single Q4 dataset and joined it with customer demographics (via Customer ID) for richer context
*  Calculated Fields: Verified existing profit figures and could compute additional metrics if needed (e.g. unit price vs. manufacturer cost).


##4. Power BI Dashboard Design:

[image](https://github.com/user-attachments/assets/042b1104-5920-490f-ab0b-b20de598cafe)


#5. Key Insights:
* Seasonality: November shows the highest sales and profit of the quarter, followed by a slight decline in December. This pattern aligns with typical holiday shopping behavior: retail sales often peak around Black Friday/Cyber Week and early holiday season
* In our data, November’s push likely reflects promotional events, after which December sales dipped slightly. This matches known retail trends that Q4 sales usually surge in the holiday season
* Top Categories: Clothing, Electronics, and Personal Care were the top three categories by revenue (roughly 140–143K each) in Q4. This is consistent with expectations that apparel and consumer electronics a  
  strong holiday sellers. For example, sales dashboards typically highlight “top-performing products” as key insights
. In our case, these top categories reflect consumer demand for gifts and essentials during the holidays. Notably, Electronics generated the highest total profit even though its sales volume was slightly lower than Clothing’s, indicating higher margins in that category.
* Regional Performance: The highest profits came from Alabama, Louisiana, and Georgia. These states also had the largest customer counts (e.g. many orders from LA and AL). This suggests regional demand hotspots; perhaps these markets had more store locations or targeted promotions. In retail analysis, geographic breakdowns (like sales by region on the map) are crucial for identifying strong/weak markets

##6. Business Recommendations:

* Focus marketing on high-performing categories and states.
* Leverage December peak trends for promotions.
* Reassess underperforming regions or categories for strategic decisions.


##7. Tools & Skills Used:

* Microsoft Power BI: for data modeling, DAX measures, and creating the interactive dashboard.
* Microsoft Excel: for initial data exploration and formatting.
* Python (pandas): for additional data analysis and preprocessing.
*  Data Visualization: Designing charts, KPIs, and maps to effectively communicate insights.
*  Analytical Skills: Identifying trends, performing EDA (exploratory data analysis), and drawing business implications from the data.



