# E-Commerce-Project

## Table of Contents
- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Key Finding](#key-finding)
- [Note](#note)

## Project Overview
The E-commerce Sales Analysis project aims to explore and analyze an e-commerce company's sales data, focusing on identifying key trends, patterns, and insights related to customer behavior, sales performance, and product performance. This project involves the use of data wrangling, data visualization, and analytical techniques to generate meaningful business insights.

## Technologies Used
- **MySQL:** To extract and manage the data from the relational database.
- **Python:** For data manipulation, analysis, and visualization.
- **Pandas:** For data cleaning and manipulation.
- **Matplotlib/Seaborn:** For creating visualizations and plots.
- **Jupyter Notebook:** As the environment for running and documenting the analysis.

## Project Structure
1. **Data Collection:**
   - Data is fetched from a relational MySQL database using SQL queries.
2. **Data Cleaning:**
   - Handling missing values, duplicates, and incorrect data types.
3. **Exploratory Data Analysis (EDA):**
   - Analyzing customer orders, payment methods, and revenue trends over time.
   - Visualization of sales performance, customer segmentation, and top products.
4. **Analysis:**
   - Top customers and their spending habits using ranking functions.
   - Monthly sales and cumulative sales trends.
   - Payment analysis (installments vs lump sum).
5. **Visualizations:**
   - Line charts for sales trends.
   - Bar charts for top customers and products.
   - Correlation heatmaps to identify relationships between different variables.

## Key Finding
### Customer Insights:
  - **Top Spending Customers:** Using the dense_rank() function, we identified the top 3 customers with the highest payments for each year. This helps in recognizing loyal, 
    high-value customers who drive significant revenue.
  - **City-Wise Purchasing Behavior:** Analyzed the average number of products per order grouped by customer city, revealing regional differences in purchasing habits.
### Revenue Insights:
  - **Sales Trends:** Monthly sales and cumulative sales data across multiple years show strong seasonal patterns, with peak sales occurring during specific months. This 
    information can be used for inventory planning and promotional strategies.
  - **Product Category Contributions:** The analysis of revenue contribution by product category shows that a few key categories generate a majority of sales, providing   
    insights into product performance.
### Payment Methods:
  - Installment vs Non-Installment Payments: The majority of customers opt for non-installment payments. However, installment payments still account for a substantial 
    portion of total revenue, indicating their importance for larger purchases or high-ticket items.
### Seller Performance:
  - **Top Sellers:** By ranking sellers based on total revenue generated, we identified the highest-performing sellers. This can guide partnerships and seller management 
    strategies.
### Year-over-Year Growth:
  - **Growth Analysis:** A year-over-year growth rate analysis revealed consistent growth in total sales. This indicates a healthy upward trend, although some years show 
    higher growth rates due to specific factors, such as promotions or market expansion.
### Product Insights:
  - **Price-Purchase Correlation:** A correlation analysis between product prices and the number of times products were purchased revealed a relationship between mid-range 
    priced products and higher purchase frequency, providing data-driven insights for pricing strategies.

## Note
Got it! I’ll keep that in mind: ensuring the dataset is present in SQL before implementing any code.
