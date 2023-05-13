# electric-store-sales-dashboard
## Introduction
This documentation provides an overview of the analysis conducted on an electronics store's sales data using Power BI. The analysis covers a dataset containing 15,000 records of orders.
## Key Functionality
### Data Cleaning and Validation:
The dataset was checked for missing data, duplicate data and incosistent formats and the data passed the cleanliness test. Therefore, very little time is spent on cleaning this data. 
### Best Performing Products: 
This functionality allows you to identify the top-selling products based on sales revenue and number of orders. Gain insights into the products that contribute most to the store's success and make data-driven decisions regarding inventory management, marketing strategies, and product promotions.

### Best Performing States: 
Analyze sales data by geographic regions or states to determine the regions where the business performs exceptionally well. Identify areas with high sales revenue, customer demand, or growth potential. This information can help optimize distribution, target marketing campaigns, and expand business operations strategically.

### Promotion Analysis: 
Evaluate the effectiveness of different promotional activities on sales performance. Analyze the impact of discounts, special offers, or marketing campaigns on revenue and customer behavior. Discover which promotions drive the most sales and tailor future marketing efforts accordingly.

### Business Progress Tracking: 
Monitor the overall progress of the business over time by tracking key performance indicators (KPIs) such as revenue, profit margin, and number of orders. Visualize trends and changes in these metrics to understand the business's growth, identify areas of improvement, and make informed strategic decisions.

By leveraging these functionalities in our dataset, we gained valuable insights into product performance, regional trends, promotional ef
fectiveness, and track the overall progress of the business. The following features were used:
### DAX expression
The following measures were created using dax expression:
1. No of Orders: This measure calculates the total number of orders made. It provides insights into the overall volume of sales transactions. The DAX function used to create this measure is as follows:
```No of Orders = COUNT(Sales_Details[Order ID])```
2. Total Cost: This measure calculates the total cost of all orders. It helps analyze the overall expenditure incurred in procuring the products sold. The DAX function used for this measure is as follows: `Total Cost = SUM('Orders'[Cost])`
3. Total Revenue: This measure calculates the total revenue generated from the sales. It provides an overview of the total income generated from the orders. The DAX function used for this measure is as follows: `Total Revenue = SUM('Orders'[Revenue])`
4. Net Profit: This measure calculates the net profit by subtracting the total cost from the total revenue. It provides insights into the profitability of the electronics store. The DAX function used for this measure is as follows:
`Net Profit = [Total Revenue] - [Total Cost]`
## Data Visualization and Dashboard
