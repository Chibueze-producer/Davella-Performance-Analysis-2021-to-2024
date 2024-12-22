# Davella-Performance-Analysis-2021-to-2024


## Project Background
Davella is a manufacturing company established in 2010 which specialises in manufacture and distribution of candy. I have been assigned to work with Head of Sales to provide insights based on analysis of revenue trends focusing on metrics such as: total revenue, total units sold and yearly growth rate. I have also been tasked with conducting analysis on regional performance, product dynamics, and shipping preferences over the four-year period. The insights from these metrics would provide a clear picture of how the candy products are performing in the market as well as identify candy products which require increased attention and marketing strategies.

Insights and recommendations are provided on the following key areas:

* Revenue Trends and Customer Purchase Patterns
* Annual Revenue Performance by Candy Product Category
* Regional Contributions To Revenue
* Customer Preferences For Shipping Options

## Data Structure
The companies main database structure as seen below consists of four tables: Sales, Products, Orders_Location, Order_Date, with a total row count of 10,194 records. This analysis used data spanning from January 2021 to December 2024 from these tables. A description of each table is as follows:

Sales Data: This dataset which serves as a fact table provides information about candy sales including order id, customer id, units sold, gross profit, cost of manufacturing, Order date. This enables calculation of metrics such as: total revenue, total units sold and yearly growth rate.

Products Data: This dataset which serves as a dimension table provides information about the candy products which the company deals with. It includes product id, factory, product name. This enables identification of products which contribute the most to revenue.

Geographic Data: This dataset which serves as a dimension table captures information such as location ID, city, and province where candy products are distributed. It helps pinpoint high-demand regions and cities, revealing opportunities for market expansion.

Orders date: This dataset is a dimension table linked to the Order date column in the sales fact table containing columns such as year, month, quarter, day of the week specifically for understanding trends in sales at a granular level.


## Executive Summary
Analysis of Davella sales records of 10,194 records across 2021 to 2024 shows a yearly increase in revenue generated beginning from $29k in 2021 to $47k in 2024 corresponding with an increase in total number of candies sold peaking at 12,737 units sold in 2024 compared to 7,813 units in 2021. Further analysis of revenue shows regionally, the Pacific Region contributed 33% of revenue, with majority of customers placing orders on Sundays for Wonka Bar - Milk Chocolate product, while the Gulf Region contributed the least,16% to revenue. Chocolate Candy showed consistent growth in revenue peaking at 27% in 2024, while Special Candy revenue rebounded in 2023 to 103% from a decline of -53% in 2022 but slowed in 2024. Sugar Candy experienced high fluctuation in revenue, with a dramatic spike of 807% in 2023 before declining sharply in 2024 to -37%. Customers preferred Standard Class shipping for its affordability, with Same Day shipping being the least chosen option. 



## Insights Deep-Dive


### Revenue Trends and Customer Purchase Patterns
In total, the company generated $141,783 in revenue between 2021 and 2024, while showing an upward trajectory from $29k in 2021 to $47k in 2024.
#### Seasonal Patterns:
Q1 was always the worst performing; February was the worst month in terms of revenue, which generated only $547 in 2021. This reflects very little seasonal demand in February, other than Valentine's Day. Q4 revenue consistently rose, peaking in November and December due to holiday-related activities such as Thanksgiving, Black Friday, and increased gifting.
#### Weekly Patterns:
Sundays led revenue generation, contributing 18%. This implies strong weekend shopping activities, because of leisure times and promotional campaigns.
![image](https://github.com/user-attachments/assets/0b151611-c172-42de-be42-d3ef11babbc1)


### Annual Revenue Performance by Candy Product Category
#### Chocolate’s Candy Product Performance
Chocolate has emerged as a reliable performer, showing consistent and sustainable growth in revenue over the past three years. Starting with an increase of 5% in 2022 compared to 2021, it climbed steadily to an impressive 27% in 2024. This trend indicates strong consumer demand, driven by effective marketing strategies and favourable product positioning.
#### Special Candy Product Performance
After a sharp decline in revenue of -52.60% in 2022, it rebounded massively to an impressive 103.49% in 2023. By 2024, the growth stabilized at 39.92%, indicating that while significant progress has been made, sustaining momentum will require continued focus. This recovery is likely a result of strategic pivots or new initiatives, but understanding why growth slowed in 2024 will be critical to ensuring long-term success.
#### Sugar Candy Product Performance
Sugar has exhibited extreme fluctuations, beginning with a decline in revenue of -19.61% in 2022 compared to 2021, followed by an astonishing rise to 806.80% in 2023, only to crash to -36.69% in 2024. This category’s fluctuations suggest further examination to determine the cause of the spike in 2023 and the sharp revenue decline in 2024. Investigating the root causes whether supply chain issues, shifting consumer preferences, or operational disruptions will be essential to stabilizing this category and mitigating future risks.
![image](https://github.com/user-attachments/assets/3c7a8ad5-940a-4c41-92fa-bc538de2d6a7)

### Regional Contributions To Revenue
* Cities located in the Pacific Region contributed 33% of total revenue, indicating strong market penetration and customer loyalty with cities like Los Angeles, San Franciso and Seattle leading in revenue generation.
* Cities located in the Atlantic region contributed 27% of total revenue with cities like New York City, Philadephia and Newmark leading in revenue generation.
* Cities located in the Interior Region contributed 23% of total revenue with cities like Chicago, Houston and Springfield leading in revenue generation.
* The Gulf Region contributed 16%, the lowest contribution to revenue among other regions.
![image](https://github.com/user-attachments/assets/c3f10107-b8ce-4faa-9335-9da95c1f0810)


### Customer Preferences For Shipping Options
Standard Class shipping is the preferred shipping mode for customers, as it was chosen by most customers due to its affordability. Same Day shipping was the least selected shipping mode, which means most customers do not select this delivery option if urgency is not crucial.
![image](https://github.com/user-attachments/assets/a2154dc2-e86b-41f2-bcba-39c202e1526e)


##   Recommendations
Based on the insights and findings above, I would recommend the sales team to consider the following:
* Optimize Revenue in Low-Performing Periods: 

Launch targeted marketing campaigns during Q1, focusing on Valentine's Day promotions to boost February sales. Increase advertising budgets and introduce discounts or loyalty rewards during low-performing periods. Enhance Q4 marketing strategies to capitalize on holiday demand, such as holiday bundles, exclusive products, or free shipping deals. Focus promotions on Sundays, emphasizing leisure shopping and weekend deals to maximize revenue.

* Drive Product-Specific Growth: 

For Chocolate Candy: Maintain consistent marketing strategies to sustain growth, including new flavour launches or premium packaging.

For Special Candy: Focus on understanding and addressing the factors behind slowed growth in 2024, to ensure sustained momentum in revenue from 2023.

For Sugar Candy: Investigate and resolve the root causes of extreme revenue fluctuations, such as supply chain issues or shifting consumer preferences. Consider offering stable pricing and consistent product availability.

* Expand Pacific Region Strategies to Underperforming Areas:

Analyse and replicate the successful strategies used in the Pacific Region to boost performance in weaker regions like the Gulf. Conduct market research to identify Gulf Region-specific barriers and tailor offerings to meet local customer needs.

* Identify strategies to enhance the appeal of the Same Day shipping option:

Promote Standard Class shipping as a default option for its affordability while exploring ways to make Same Day delivery more attractive, such as lower fees or bundled deals.
