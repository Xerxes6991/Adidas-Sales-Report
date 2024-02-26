# Adidas Sales Report
A comprehensive analysis of Adidas sales data, providing insights into product performance and market trends

[Link to interactive dashboard](https://app.powerbi.com/view?r=eyJrIjoiOTgyYzJhMmYtODVmMy00NGVlLWI3ZDMtNTVmZjM0ZTExM2RhIiwidCI6ImI0MTlmYmViLTcwZDYtNGVjNC1iMjQ4LTBmYTEwZTY1MGQxMiIsImMiOjN9)

### Project Overview

This project explores the factors influencing Adidas sales performance and also provides actionable insights to inform strategic decision-making on market trends and consumer behaviour 

### Data Source 

Sales data: The dataset used for this analysis is the a CSV file containing sales data for two years
  - [Download Here](https://www.kaggle.com/datasets/heemalichaudhari/adidas-sales-dataset)

### Tools

- Excel - Data Cleaning
- PowerBI - Creating Reports

### Data Cleaning/Preparation

The following steps were taken in the data cleaning stage:
- I split the dataset into different sheets and merged multiple datasets together based on commonalities to create a unified dataset
- I reordered columns to organize data in a more logical sequence
- I used image links of the products to be analyzed from Adidas

### Exploratory Data Analysis

EDA involved: 
- Created a sales dashboard displaying key metrics such as total revenue (sales), quantity sold, average price at which a unit of the product is sold, number of transactions done and profit made.
- Explored regional sales distribution using shape maps to visualize sales by geographical locations.
- Investigated sales seasonality by analyzing monthly and yearly sales trends using time intelligence functions and slicers.
- Visualized sales performance over time by product category using slicers, cards and area charts to analyze sales in a period of time.
- Visualized sales trends over time using slicers and area charts to identify seasonal patterns and trends.
- Analyzed sales performance by product category, retailer and region using bar charts to identify top-selling categories and underperforming ones.
- Examined sales by sales channel (e.g., online, outlet, in-store) using slicers in comparison to other charts created to understand the effectiveness of each channel.
- Created an Area chart to visualize the trend of monthly profit and total sales over time, enabling the identification of any seasonal patterns or trends.
- Conducted a year-over-year analysis by adding a slicer to compare the monthly profit and total sales across different years, facilitating trend analysis and year-on-year comparisons.
- Created a Line chart to visualize the trend of monthly sales and total sales over time, enabling the identification of any seasonal patterns or trends.
- Conducted a year-over-year analysis by adding a slicer to compare the monthly sales and total sales across different years, facilitating trend analysis and year-on-year comparisons.
- Utilized DAX measures to calculate profit margin ratios and compare them with the average operating margin, enabling assessment of profitability and efficiency in converting sales into profit.
- Utilized a Line and Stacked column chart to compare the trend of monthly profit against the average operating margin to provide insights into profitability
- Utilized a slicer to filter the data by specific retailer, sales channels (method) or year enabling focused analysis and comparison of monthly profit and average operating margin within selected segments.

### Results

This summary provides a comprehensive overview of sales performance across different sales methods over time. The analysis results are summarized as follows:

- The analysis indicates that Men's street footwear is the top-selling category across every sales channel, while women's athletic footwear is the least-selling category across all sales channel.
- The product category breakdown revealed that the most popular category was Men's street footwear, with 23.21% of total sales, followed by Women's apparel with 19.90%, followed by Men's athletic footwear with 17.08%, followed by Women's street footwear with 14.22%, followed by Men's apparel with 13.75% and Women's Athletic footwear with 11.85%.
- <img width="634" alt="Sales by Product Category" src="https://github.com/Xerxes6991/Adidas-Sales-Report/assets/154422796/e2780d9b-20f1-4fdc-b3ba-67ad6fdaef0a">

- The product category that had the highest profit margin was Men's street footwear, with 39.65% of the revenue being converted to profit, followed by Women's apparel with 38.34%, followed by Women's athletic footwear with 36.56%, followed by Men's apparel with 36.18%, followed by Women's street footwear with 35.23% and Men's athletic footwear with 33.74%.
- 
- The product category that had the highest growth rate was Men's street footwear with a 352.14% increase in sales compared to the previous year, followed by Women's apparel with 308.78%, followed by Men's athletic footwear with 283.39%, followed by Men's apparel with 271.89%, followed by Women's street footwear with 266.68% and Women's athletic footwear with 251.25%.
-
- From examining sales by retailers, West Gear has the highest sales In-store while Footlocker has the highest sales Online and in Outlets
- After analysis, insights derived show that West Gear and Footlocker were the highest performing retailers among all retailers. They accounted for 27% and 24.46% of the total sales volume respectively while Amazon was the lowest performing retailer with 8.63% of the total sales volume.
- <img width="635" alt="Sales by Retailer" src="https://github.com/Xerxes6991/Adidas-Sales-Report/assets/154422796/0e024013-5f54-4787-9ebe-370284507cec">

-  Based on the analysis, the In-store sales channel generated the most revenue, with $356.64 million in sales, followed by the Outlet sales channel with $295.59 million and the Online sales channel with $247.67 million. However, the Online sales channel had the highest profit margin, with 38.99% of the revenue being converted into profit, followed by the Outlet sales channel with 36.53% and the In-store sales channel with 35.78%.
- By examining sales distribution geographically, it was discovered that the top three regions by sales revenue were West, North East and South East accounting for 30%, 21.1% and 17.1% of the total sales respectively. However, the regions with the highest growth rate were the Midwest, South and South East with sales increase percentage of 1,757%, 380% and 306.25% respectively.
- <img width="634" alt="Sales by Region" src="https://github.com/Xerxes6991/Adidas-Sales-Report/assets/154422796/0320cdcb-26bc-4e08-be61-d0b49506c537">

- In both years (2020 & 2021), the region with the lowest profit margin was the West, with 31.82% and 33.74% of the sales revenue being converted to profit respectively while the highest profit margin was the South, with 38.69% & 43.02% respectively.
- 
### Recommendations
- For the regions that generate the most revenue, I advice to maintain and strenghten the relationships with existing customers in these regions by continuous provision of excellent service, support and loyalty programs. Market share in these regions by attracting even more customers through referrals and testimonials from satisfied customers.
- For the low grossing regions, I suggest the offering of incentives and discounts to entice potential customers to try the products.
- Implement reward or incentive programs for the highest grossing retailers (West Gear and Footlocker) to recognize and incentivize their performance. Partnership with these retailers on collaborative marketing initiatives such as co-branded campaigns or sponsorships to increase brand visibility could also ensure more demand for products. Solicition of feedback and suggestions from these retailers on how to improve the products if any could also prove to be helpful in increasing sales.
- For low grossing retailers (Walmart and Amazon), factors such as location and visibility of products are some of the problems faced by these retailers. Providing these retailers with exclusive deals, discounts or performance-based bonuses to incentivize them to increase their sales effort would improve their sales performance.
- Capitalize on the popularity and demand of the high-selling products, promote and market these products by creating compelling and consistent messages and campaigns that highlight their value proposition and differentiation.
- Feedback and suggestions from the retailers would help to evaluate and diagnose the reasons for low-selling products' performance. Any of these reasons could be high price, low demand or strong competition.
- Online sales can be improved by driving more traffic by implementing effective SEO, SEM and SMM strategies, building trust and credibility with online customers by displaying customer reviews and testimonials, ratings and guarantees concerning the products to be sold. Customer retention and loyalty can be increased by offering personalized recommendations, discounts and rewards. Excellent customer service should also be made a priority.
   
