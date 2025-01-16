# Cornucopia Sales Analysis (2022-2024)

# Project Background
Cornucopia Natural Market & Deli, founded in 1989, is a women-owned local grocery store that focuses on providing healthy and affordable food and daily products. As a Data Analytics Intern, I used Excel to clean data and use Tableau extract insights on the store performance, identify top-performing departments, and deliver recommendations to increase sales. 

Insights and recommendations are provided on the following key areas

- **Total Sales** 
- **Total Profit** 
- **Total Transaction** 
- **Average Basket Value (ABV)** 

An interactive Tableau dashboard used to report and explore sales trends can be found [HERE](https://public.tableau.com/views/SalesVisualization_17337025763500/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).

For privacy concern, the Excel files used for this dashboard will not be included. 


# Data Structure & Initial Checks

The datasets I work with consists of 3 tables: Overall Sales, Sales by Departments, COGS 
- **Sales:** This table contains number of total sales, total transaction, and ABV for each month from 2022 to 2024
- **Sales by Department:** This table contains number of sales for each department, including: Alcohol, Body Care, Cheese, Choc/Candy, Deli, Eat In, Grocery, Produce, Supplements, General Merchandise, Soft Drinks, and Wholesale
- **Cost of Goods Sold:** This table contains the Cost of Goods Sold percentages, which are used for calculating gross profit

# Executive Summary

### Overview of Findings
The trends in total sales, gross profit, transaction count, and ABV have increased steadily from 2022 to 2024. The number of sales always peaked in December and reached the lowest point around January to February. The trend in sales by departments followed the same patterns over the years with Grocery had the highest record.

![Dashboard 1](https://github.com/user-attachments/assets/dc3de2cc-54bc-4b89-a15c-18f89d0e4e7e)
![Dashboard 1 (1)](https://github.com/user-attachments/assets/6e4cf1cc-292d-47e9-84cb-4e6f76ade3cb)
![Dashboard 1 (2)](https://github.com/user-attachments/assets/525a1b2d-81a6-473b-b767-20553f888baf)




# Insights Deep Dive
### Total Sales:
* Although the overall sales constantly increased from 2022 to 2024, the percentage of sales increase in 2023 (22%) is much higher than in 2024 (5.4%). The yearly trend in sales in 2024 also had more flunctuations compared to 2023. This is shown in the drastic drop in sales growth and transanction count growth in November 2024. 
* The number of sales always peaked in December, demonstrating high shopping demand during holiday season. January and February are usually the period with the lowest sales, suggesting customers spend less post-holiday.
* Department 'Grocery' had the highest number of sales in all 3 years. However, sales by grocery in 2024 is lower than in 2023. Sales of all other departments, except Produce and General Merchandise, also decreased in 2024, although not significantly.

### Total Profit:

* The gross profit in 2024 increased 6.7% compared to gross profit in 2023, indicating a positive improvement Cornucopia has in making profit. 

### Total Transaction:

* The trend in total transaction follows the similar pattern with the trend in sales. The percentage difference between 2022 and 2023 (increased 15.7%) is much higher than the percentage difference between 2023 and 2024 (increased 15.3%). Cornucopia had a drastically positive change from 2022 to 2023, but that change has slowed down in 2024.
  
* From 2022 to 2023, the number of transaction also peaked in December and plummeted to the lowest in February. In 2024, the lowest transaction count occurred in November and the highest occurred in October. Because the transaction count in 2024 were relatively stable throughout the months, all ranging from 3.9K to 4.6K, so this out-of-trend pattern cannot conclude any abnormality. 

### Average Basket Value (ABV):

* Average Basket Value has increased consistently from 2022 and slowed down in 2024 at $28.6. Although transaction count did not peak in December 2024, total sales and ABV in this month are both the highest. This indicates that customer might made fewer transaction but with larger number of items. 
* In 2023, ABV peaked in February with 17.4% increase in growth rate while both sales and transaction count plummeted heavily. The lowest ABV in 2022 and 2024 also did not occur in the months with the lowest sales and transaction count. This detail can be further monitored to develop strategy to increase ABV baseline. 

# Recommendations & Next steps:
  
* Due to the significantly high demand during holiday season, consider to increase  marketing efforts and offer promotions or bundles for high-demand products like groceries and produce
* Investigate factors that slow down the increase in sales by department in 2024
* Consider building a customer loyalty program to increase incentive for larger transaction and larger average basket value
  
# Assumptions and Caveats:
There is a slight difference between the total number from 'Sales' table compared to the total number calculated from 'Sales by Department' table. Cornucopia just transitioned to a new system to store financial and inventory data, and the new system did not follow the old department category. Therefore, some products are no longer belonged to any specific departments, so their sales are counted towards the total sales, but not towards sales by department. There was no records of Cost of Goods Sold for 2022, so I could not calculate the gross profit. This might affect the overall performance of 2022.
