<div align="center">

![Logo](https://github.com/JackLemere/Bubblewicks/blob/main/bubblewicks-logo.png)

# Bubblewicks 2020 Sales Performance Analysis

</div>
 
<br>


## Project Background

Bubblewicks is an online business that sells soap and candle supplies exclusively via the online platform Etsy across North America.

Bubblewicks was opened on Etsy in January 2020 and closed in December of the same year. Data on product sales was recorded by Etsy and provided for analysis. This project seeks to analyse the Bubblewicks' sales data in order to gain insights and recommendations for how to best proceed with a relaunch of the online store to maximize product sales and build on the sales made in 2020. The main KPIs used to measure success in this analysis include total orders, total items sold, and revenue generated. Recommendations will be used by the business owner to better strategize their plans to relaunch the business.

Insights and recommendations are provided on the following key areas:

- Sales Trend Analysis: Evaluation of historical sales patterns, focusing on Revenue and Order Volume
- Product Level Performance: An analysis of Bubblewicks' various products, understanding their impact on total sales and revenue
- Regional Comparisons: An evaluation of product sales by province/state


## Executive Summary

### Overview of Findings

As for the best selling products, Candle Kits were the highest selling item by a significant margin with 40 total sales generating 51% of company revenue. Stephenson Soap Base and Soap Cutters also saw a significant portion of sales with 17 and 13 units sold respectively, accounting for a combined 38% of revenue. Fragrance and Essential Oils were the worst performers, achieving only two sales over the entire year. The company saw a steady increase in total items sold which peaked in May with 20 items sold that month, followed by a sharp decline for the remainder of the year. Sales would briefly increase in November, matching typical holiday trends. The highest concentration of sales were found to be in orders from Ontairo and British Columbia, making up for 28% and 14% of sales respectively. The following sections will dive deeper into product sales trends and highlight key areas that were successful and other areas that have opportunity for improvement.

The interactive Tableau dashboard seen below is available [here](https://public.tableau.com/app/profile/jack.lemere5367/viz/BubblewicksSalesDashboard/Dashboard1?publish=yes)

![Dashboard](https://github.com/JackLemere/Bubblewicks/blob/main/bubblewicks-dashboard.png)


## Data Structure & Initial Checks

Bubblewicks' main database structure as seen below consists of two tables: SoldOrders2020 and total_items_purchased. SoldOrders2020 includes 74 records each representing a product sale transaction. total_items_purchased contains 71 records each representing a customer order with the quantity of items purchased. Data cleaning was conducted using Excel.

![ERD](https://github.com/JackLemere/Bubblewicks/blob/main/bubblewicks-erd.png)


## Insights Deep Dive
### Sales Trends:

- Since the shop opening in February, sales and revenue have been steadily rising which indicates good company growth. Company sales peaked in May with 20 items sold generating $620.10 in revenue.

- Sales declined from June onwards with July having just 2 sales, the lowest since the first month.

- Sales had a small peak of 9 items sold in November, following normal holiday seasonal patterns.

- Orders rarely saw more than one item per order, with 92.9% of orders containing just one item.


![Items Sold](https://github.com/JackLemere/Bubblewicks/blob/main/bubblewicks-items-sold.png)


### Product Performance:

- Candle Kits were by far the most popular item, accounting for 51.28% of total company sales. A total of 40 Candle Kits were sold generating $1538.00 in revenue. 
  
- Underperformers include the Fragrance and Essential Oils, which saw only two being sold on the shop. These items generated the lowest revenue with a combined $17.50 earned.

- Stephenson Soap Base appeared to be very popular from February to May, and was tied for the most sold product during the month of May making up 40% of sales. No Stephenson Soap Bases were sold after June. 

- Soap Cutters were the third most sold product behind Stephenson Soap base, but generated the second highest revenue with $945.00 earned from 13 sales. The higher revenue is likely due to the Soap Cutter being a high priced item.


![Products Over Time](https://github.com/JackLemere/Bubblewicks/blob/main/bubblewicks-top-selling.png)


### Regional Comparisons:

- Between Canada and the United States, Canada saw 59.46% of all orders with the remaining 40.54% coming from the United States.

- In Canada, Ontario and British Columbia saw significantly higher orders than in other provinces/territories with 22 and 11 orders respectively. The United States was much more varied with no state having more than 4 orders.

![Sales By Region Map](https://github.com/JackLemere/Bubblewicks/blob/main/bubblewicks-geo.png)
![Sales By Region Table](https://github.com/JackLemere/Bubblewicks/blob/main/bubblewicks-states.png)


## Recommendations:

Based on the insights and findings above, we would recommend Bubblewicks to consider the following: 

- With Candle Kits being the most successful product with 51% of sales, this product should be heavily focused on reopen. Stephenson Soap Base and Soap Cutters also saw significant sales, including them in the reopening should be a priority.

- Re-evaluate Fragrance and Essential Oils. Sales of these products were extremely low in comparison with only two sold in the entire year while also providing low revenue. Consider omitting these products in the relaunch, or try to sell these products in bulk or included as part of bundle offers.

- Shop inventory only includes six product types sold. For increase in sales, it would be beneficial to carry more products to sell, both for generating more sales and attracting different types of customers.

- 93% of customers only purchased one item from the shop. Introducing bundle deals or incentives for minimum spend would likely encourage customers to purchase more products and increase total items sold. 

- Sales of the majority of products saw noticeable peaks in May and November, introducing new products or sales during these times would help take advantage of the increased customer traffic.

- Ontario and British Columbia saw significantly higher sales than any other regions. Focusing on these areas for sales and consumer interests would be most beneficial.



## Assumptions and Caveats:

Throughout the analysis, multiple assumptions were made to manage challenges with the data. These assumptions and caveats are noted below:

- **Cost data for each product is missing** - Product success was measured on revenue and total products sold, though product analysis may vary depending on how much each product costs to stock. Etsy fees should also be considered.

- **Sales data only covers one year of sales** - Having a longer timeframe of sales performance would allow for more accurate analysis. As the sales period analysed took place entirely in 2020, a year where COVID-19 was very influential for online stores, spending habits of consumers will likely have changed since then.
