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
![electronic sales dashboard 1](https://github.com/saintgokex/electric-store-sales-dashboard/blob/main/electronic%20sales%20dashboard%201.png)
![electronic sales dashboard 2](https://github.com/saintgokex/electric-store-sales-dashboard/blob/main/electronic%20sales%20dashboard%202.png)
### Key Insights
* Computer Accessories has the highest number of orders although Camcorders generated the most amount of profit for the store, followed by digital SLR cameras.
* South South generated the most amount of profit and recorded highest amount of orders among the seven zones in this dataset (including the Federal Capital Terrritory) with Ebonyi being the most profitable state. 
* Approximately 70% of the orders and profit were generated from the store, making it the best performing channel over the three other channels including online and retailer. 
* Deeper Promotions and Adventist Promotion are the most effective promotions.
## Recommendation
#### Leverage the Demand for Computer Accessories
Given that computer accessories have the highest number of orders, the store should capitalize on this demand by offering a diverse range of computer accessories and ensuring a consistent supply. The store should also monitor customer preferences and stay updated on the latest trends to introduce new and innovative computer accessories that meet customer needs.

#### Optimize Camcorder Sales 
Since Camcorders generated the most profit, the store should:
* focus on maximizing the sales and profitability of this product category, consider implementing targeted marketing campaigns specifically tailored to promote Camcorders.
* Highlight unique features, benefits, and competitive pricing to attract potential customers. 
* Ensure that the supply chain is optimized to meet the demand for Camcorders.

#### Strategize for the Most Productive State (South South) 
Given that the South South region is the most productive state, the store should: 
* Allocate additional resources and marketing efforts to this region. 
* Understand the preferences and needs of customers in this region, and tailor its product offerings, marketing campaigns, and promotions accordingly. 
* Establish strong partnerships with local retailers or distributors to expand its reach 
* Improve market penetration in the South South region.

#### Maximize Conversion with Adventist and Deeper Promotions
* Focus on enhancing the conversion rates by leveraging the success of Adventist and Deeper promotions. 
* Analyze the strategies and elements that made these promotions successful, such as messaging, timing, discounts, or additional incentives. 
* Replicate the successful components in future promotions and adapt them to other product categories to boost conversion rates and overall sales.

#### Targeted Promotions and Partnerships 
* Based on the dataset insights, the store can consider partnering with religious organizations or targeting specific religious communities for promotional activities. 
* Develop collaborations or sponsorship opportunities with Adventist or Deeper groups to tap into their existing networks and expand its customer base. 
* Customize promotions to resonate with the values and preferences of these communities, fostering a sense of affinity and driving conversions.

#### Continuous Monitoring and Analysis 
The store shoudl 
* Regularly monitor and analyze sales data, customer behavior, and market trends to identify emerging opportunities and adapt its strategies accordingly. 
* Stay informed about new technologies, product innovations, and changing consumer preferences to stay ahead of the competition. 
* Adjust its marketing mix, pricing strategies, and product offerings based on the evolving dynamics of the market.
