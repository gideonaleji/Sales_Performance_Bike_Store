# Sales and Product Performance of a bike store in Europe
This project is a sales and product performance analysis of a bike store in Europe from 2011 to 2016. The dataset was gotten from Kaggle website and downloaded as a csv file.
## Table of Contents
- [Introduction](#introduction)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Dashboard](#dashboard)
- [Insights from Sales Performance](#insights-from-sales-performance)
- [Insights from Product Performance](#insights-from-product-performance)
- [Recommendations](#recommendations)

## Introduction
This dataset contains the sales records of a bike store in Europe, including details such as time of purchase, product descriptions, product categories, country of purchase, customer gender, sales price, and profit. The goal of this analysis is to explore sales trends and product performance in order to uncover actionable insights that can help improve sales and optimize overall product strategy.

## Tools
This analysis was carried out entirely in Microsoft Excel. The dataset contains 18 variables and a total of 113,037 records. Excel was used for all stages of the process, including data cleaning, standardization, pivoting, and dashboard creation.

## Data Cleaning
The dataset was originally received in CSV format and converted to XLSX for better handling and analysis in Excel. To ensure consistency and readability, the data was standardized and the headers were renamed for clarity. A total of 1,302 duplicate records were identified and removed, resulting in 111,734 unique entries.

For an organized and efficient workflow, six worksheet tabs were created: Original Dataset, Working Sheet, Working Notes, Pivot Table, Dashboard, Insights and Business Impact.

The images below show samples of both the original and the refined datasets.

![Screenshot 2025-04-16 162241](https://github.com/user-attachments/assets/1cf21c7f-09ac-4c4b-960a-524425149ec9)
![Screenshot 2025-04-16 162311](https://github.com/user-attachments/assets/5d133fc3-aa4b-4ac0-a8a4-f285a0930b97)

## Exploratory Data Analysis
The exploratory analysis began with a total profit trend chart to visualize overall performance. Irrelevant columns were removed to streamline the dataset, and a new column was added to calculate the revenue-to-profit ratio. Pivot tables were then created to summarize key metrics, including: Total profit by product category, Annual revenue-to-profit ratio, Order quantities by age group, and Monthly sales trends.

![Screenshot 2025-04-16 163526](https://github.com/user-attachments/assets/3874c3d8-fd02-41f1-9fab-1ca72caef1ab)

![Screenshot 2025-04-16 163615](https://github.com/user-attachments/assets/0b2b8c15-1f47-4f20-a139-6e8e38d5c9c0)

![Screenshot 2025-04-16 163544](https://github.com/user-attachments/assets/f8b8c6d3-94cf-4025-8fb7-3791c1f5f020)


## Dashboard

The dashboard was created by importing relevant pivot charts covering two main areas: sales performance (analysis of total profit per product category and revenue to profit ratio) and product performance (breakdown of order quantities by country and age group).

![Screenshot 2025-04-16 163954](https://github.com/user-attachments/assets/7544c9e8-ca54-4efc-b001-c409796b8d17)

## Insights from Sales Performance

1. Top-Selling Categories: The store generates the highest profit from bike sales, followed by accessories and then clothing.

2. Best & Worst-Selling Products:
	Bikes: Road bikes are the best-selling, while touring bikes have the lowest sales.
	Accessories: Tyres and tubes lead in sales, whereas bike stands are the least sold.
	Clothing: Jerseys are the most popular, while vests have the lowest demand.

3. Regional Sales Performance: The store's largest customer base is in the United States, with California, Washington, and Oregon driving the most sales.

4. Revenue-to-Profit Growth: The profit margin has increased from 30% to nearly 50% over seven years, showing consistent financial growth.

5. Age Group Contribution:
	Customers aged 35–64 years account for nearly half of the store’s profit.
	Sales are lowest among customers above 64 years, followed by those under 25 years.
	Best Market by Profit Ratio: Canada recorded the highest revenue-to-profit ratio, exceeding 50% for four consecutive years.


## Insights from Product Performance

1. Purchase Trends vs. Profitability:
	While bikes generate the most profit, accessories are the most frequently purchased items, followed by bikes and then clothing. This is expected, as lighter and more affordable items tend to sell more but contribute less to 	overall profit.

2. Regional Demand for Accessories:
	One-third of all accessory purchases come from California, Washington, and Oregon (U.S.), indicating a strong market in these states.

3. Age Group Buying Patterns:
	Half of all accessory purchases come from customers aged 35–64 years, likely due to their greater financial stability.
	Young adults (25–34 years) buy nearly as many bikes as the 35–64 age group but purchase significantly fewer accessories, most likely due to budget constraints.
	The senior age group (64+) makes the fewest purchases, with only 56 bike sales recorded in seven years (about 8 per year).

4. Unexplained Sales Gap (July 2014 – July 2015):
	Sales of accessories and clothing completely stopped during this period, while bike sales continued.

5. Possible explanations to the Sales Gap:
	Stock shortage? Were these products unavailable during that time?
	Missing records? Could sales data for these items have been omitted?
	This gap requires further investigation.

6. Correlation Between Accessory & Clothing Sales:
	A strong sales trend correlation exists between clothing and accessories, suggesting that customers who buy clothing often purchase accessories like water bottles as well.


## Recommendations

1. Expand Physical Presence in High-Demand Regions:
	Since one-third of customers are from California, Washington, and Oregon, opening physical stores or distribution centers in these locations could boost sales, enhance customer 	experience, and reduce shipping costs.

2. Targeted Product Offerings for Different Age Groups:
	To increase sales among seniors (64+), introduce bike models tailored to their needs, such as comfort bikes, e-bikes, or step-through frames designed for ease of use.
	For young customers (under 25), consider offering budget-friendly options and promoting financing plans or student discounts to align with their financial capacity.
3. Leverage Combo & Bundled Sales for Accessories & Clothing:
	Since accessories and clothing often sell together, introduce bundled discounts (e.g., "Buy a jersey, get a water bottle at 20% off") to encourage upselling and increase average order 	value.

4. Ensure Year-Round Stock Availability:
	The procurement team should prioritize consistent inventory management to avoid stockouts of accessories and clothing, ensuring sales remain steady throughout the year.
	Investigate the 2014–2015 sales gap to identify and resolve any supply chain or data recording issues.
