
![dataset-cover](https://github.com/user-attachments/assets/c8af64a5-b388-43b3-8b85-5a0048f793e3)

# Analyzing-E-Commerce-Sales-Performance
The project aims to analyze e-commerce sales data to uncover insights into product categories, seasonal trends, and customer behavior. These insights will assist businesses in developing more effective marketing strategies, improving sales performance, and enhancing decision-making processes.

________________________________________
# **Project Overview**
________________________________________
This project aims to analyze e-commerce sales data to uncover insights into sales performance, product category trends, seasonality, and customer preferences. By exploring patterns in order fulfillment, promotions, and geographic sales distribution, the project will provide actionable recommendations to help businesses optimize marketing strategies, enhance customer targeting, and boost sales performance.

**Scope of the Project:**

The analysis is designed to be exhaustive and insights-driven, covering detailed descriptive and inferential investigations. The goal is to explore the dataset to extract meaningful trends, test hypotheses, and derive data-driven insights that contribute to business decision-making processes.

## **Key Areas of Focus**
**Sales Performance Analysis:**

- Evaluating total sales, revenue, and order quantity.
- Identifying top-performing product categories, SKUs, and sales channels.
- Measuring average order value and revenue trends.

**Seasonality and Time Trends:**

- Uncovering monthly and seasonal trends in sales performance.
- Analyzing peak sales periods and high cancellation months.

**Customer and Geographic Insights:**

- Analyzing customer behavior based on location (city/state).
- Understanding the relationship between shipping service levels and geographic regions.

**Promotions and Discounts:**

- Evaluating the impact of promotions on order volume and revenue.
- Comparing performance between promoted and non-promoted orders.

**Order Fulfillment Insights:**

- Assessing the differences in performance between orders fulfilled by Amazon and merchants.
- Analyzing the impact of shipping service levels (Standard vs. Expedited) on sales performance.

**Inferential Analysis and Hypothesis Testing:**

*Testing relationships and significant differences across key variables:*
- Promotion effectiveness
- Fulfillment method impact
- Geographic variations in sales and cancellations


### **Expected Outcomes**

*By conducting this analysis, the project will deliver:*

- Comprehensive insights into sales trends, customer preferences, and product performance.
- Key findings on the effectiveness of promotions, fulfillment strategies, and time-based sales patterns.
- Data-driven recommendations to optimize marketing strategies, reduce cancellations, and improve sales performance.

**Business Impact:**

*The findings will empower businesses to:*

- Improve product targeting and inventory management.
- Enhance marketing strategies through insights on seasonality and promotions.
- Optimize fulfillment methods to increase customer satisfaction and reduce cancellations.
- Identify high-performing categories and target locations to maximize revenue growth.

**Tools and Techniques**

*The project will employ:*

- Data Analysis: Python (Pandas, NumPy), statistical methods, and hypothesis testing.
- Visualization: Matplotlib, Seaborn for trends and distribution analysis.
- Statistical Tests: Comparative tests, correlation analysis, and significance testing.
- Reporting: Actionable insights with visualized results for clarity and decision-making.


________________________________________
## Descriptive Analysis Questions
________________________________________
| **Category**                   | **Questions**                                                                                   |
|--------------------------------|-----------------------------------------------------------------------------------------------|
| **General Sales Insights**     | 1. What is the total number of orders placed?                                                |
|                                | 2. What is the total revenue generated?                                                     |
|                                | 3. What is the average order value across all orders?                                       |
|                                | 4. What are the top 10 best-selling product categories by total sales?                      |
|                                | 5. Which SKUs (product codes) have the highest total quantity sold?                         |
|                                | 6. Which SKUs generate the highest revenue?                                                |
|                                | 7. What are the monthly sales trends over time? (group by Date)                             |
|                                | 8. Which fulfillment method (Fulfilment) contributes the most to sales?                     |
|                                | 9. What is the distribution of Status (shipped, canceled, etc.)?                            |
|                                | 10. Which Sales Channel generates the most sales and revenue?                               |
|                                | 11. What is the average order quantity (Qty) across different categories?                   |
| **Seasonality & Time Trends**  | 12. What are the peak sales months and seasons?                                             |
|                                | 13. Is there a weekly or daily pattern in sales volume?                                     |
|                                | 14. Which months show the highest cancellation rates?                                       |
| **Customer Location Trends**   | 15. Which ship-city and ship-state have the most orders?                                    |
|                                | 16. What is the average revenue per shipping state or city?                                 |
|                                | 17. Which states or cities have the highest cancellation rates?                             |
| **Promotions & Discounts**     | 18. How many orders included promotion-ids?                                                 |
|                                | 19. What is the average revenue of promoted vs. non-promoted orders?                        |
|                                | 20. Which promotions were the most frequently used?                                         |
| **Fulfillment Methods**        | 21. What is the split between orders fulfilled by Amazon and merchants?                     |
|                                | 22. What is the average order value for Amazon-fulfilled orders vs. Merchant-fulfilled?     |
|                                | 23. What is the distribution of ship-service-level (Standard vs. Expedited)?                |


________________________________________
# Inferential Analysis Questions
________________________________________



| Question | Type of Analysis                     | Statistical Test     |
|----------|--------------------------------------|----------------------|
| 1. Is there a significant difference in average revenue across different product categories? | Compare means        | ANOVA                |
| 2. Is there a significant difference in sales (revenue) across months for standard shipping orders?       | Compare two means    | ANOVA               |
| 3. Are orders with promotions significantly different in revenue compared to those without promotions? | Compare two means    | ANOVA              |
| 4. Is there a difference in average Qty sold across product categories?                     | Compare means        | ANOVA                |
| 5. Does the order cancellation rate vary significantly across ship-state or ship-city?      | Compare proportions  | Chi-Square test      |
| 6. Is there a correlation between Qty and Amount?                                           | Relationship         | Pearson Correlation  |
| 7. Does the Status of an order relate to fulfillment methods?                               | Association          | Chi-Square test      |
| 8. Is there a relationship between the month of order placement and order cancellations?    | Association          | Chi-Square test      |
| 9. Do revenue and average order value differ significantly between product categories?     | Compare means        | ANOVA or t-test      |
| 10. Are monthly or seasonal revenue trends statistically significant?                      | Trend analysis       | ANOVA                |
| 11. Does the effect of promotions on total quantity sold vary across different product categories?              | Compare means        | t-test               |
| 12. Is there a significant relationship between promotion-ids and order cancellation rates? | Association          | Chi-Square test      |
| 13. Are there statistically significant differences in revenue across different states or cities? | Compare means    | ANOVA                |
| 14. Does the shipping location influence the use of expedited service levels?               | Association          | Chi-Square test      |
| 15. Do different ship-states or ship-cities result in different average order values?        | Compare means        | t-test               |
| 16. Is there a significant difference in cancellation rates across states or cities?        | Compare proportions  | Chi-Square test      |
| 17. #17 Group by category and have significantly higher average income?                   | Compare means        | t-test               |
| 18. Are there significant differences in average order quantity across product categories?  | Compare means        | ANOVA                |
| 19. Is there a relationship between order quantity and order value?                         | Relationship         | Pearson Correlation  |
| 20. Are certain ship-service-level options associated with higher cancellation rates?       | Association          | Chi-Square test      |







# Summary of Descriptive Questions and Inferential Hypotheses

**1. Revenue and Average Order Value by Product Category**

- Descriptive Analysis: The analysis showed how revenue and average order values vary across different product categories. Categories such as "Blouse" and "Bottom" demonstrated higher average order values compared to others.
- Inferential Hypothesis: ANOVA was used to determine if there were significant differences in average revenue across product categories. The results revealed a significant difference in average revenue, meaning certain categories outperform others in terms of revenue generation.
  
![productcate](https://github.com/user-attachments/assets/30ced5a8-93c9-4f23-9a65-88e86e6db851)

**2. Monthly and Seasonal Revenue Trends**

- Descriptive Analysis: Monthly and seasonal trends were analyzed, showing clear patterns in sales performance. For instance, certain months exhibited higher sales, indicating seasonal demand fluctuations.
- Inferential Hypothesis: ANOVA was applied to determine whether the differences in revenue by month and season were statistically significant. Both analyses showed significant results (P-value < 0.05), highlighting that seasonality impacts revenue generation.

**3. Effect of Promotions on Quantity Sold**

- Descriptive Analysis: The data revealed that orders with promotions generally had higher quantity sold, indicating that promotions lead to an increase in order volume.
- Inferential Hypothesis: The Mann-Whitney U Test was used to test whether promotions lead to significantly higher sales quantities. The results showed that promotions significantly increase the quantity sold, validating their impact.
  
![pronopro](https://github.com/user-attachments/assets/72751b3e-4023-4606-ac2f-655cbca40ccc)

**4. Shipping Location and Service Level**

- Descriptive Analysis: Sales data was segmented by ship-service-level and shipping location (e.g., states and cities), highlighting geographical variations in shipping preferences and cancellations.
- Inferential Hypothesis: Chi-Square Test was conducted to assess the relationship between ship-service-level and cancellation rates. The results indicated no significant relationship (P-value = 1.000), suggesting that shipping service level does not significantly affect cancellation rates.

  ![shipstates](https://github.com/user-attachments/assets/79627905-4cb5-4ab9-8d85-c89a5275a0b9)


**5. Promotions and Order Cancellations**

- Descriptive Analysis: The impact of promotion-ids on order cancellations was examined, with a focus on orders with and without promotions.
- Inferential Hypothesis: A Chi-Square Test was applied to test the association between promotions and cancellations. The analysis revealed no significant relationship between promotion-ids and order cancellations.

**6. Shipping Cost and Service Level**

- Descriptive Analysis: This analysis aimed to understand how shipping costs differ across ship-service-level options.
- Inferential Hypothesis: ANOVA was conducted to compare the shipping cost (proxied by order Amount) across different service levels. The results showed a significant difference in shipping costs, indicating that service levels impact the cost of shipping.

**7. Ship-Service-Level and Customer Preferences**

- Descriptive Analysis: Analysis showed customer preferences regarding ship-service-level options like "Standard" vs "Expedited".
- Inferential Hypothesis: The hypothesis tested whether different service levels are associated with varying levels of customer satisfaction or cancellation rates. The results indicated that shipping service level choices might have a weak influence on order cancellations, but no significant relationship was found in the final Chi-Square analysis.

**8. Sales by Region (Ship-State)**

- Descriptive Analysis: Sales performance was compared across ship-states. Some regions showed higher sales performance, while others underperformed.
- Inferential Hypothesis: ANOVA was used to determine whether sales (or revenue) differed significantly across states. The analysis indicated a significant difference (P-value < 0.05), implying that geographic location does influence sales performance.

**9. Cancellation Rate by Ship-State**

- Descriptive Analysis: The cancellation rate was examined by ship-state, highlighting regions with higher cancellation frequencies.
- Inferential Hypothesis: ANOVA was used to test if there were significant differences in cancellation rates across states. The results showed a significant difference, indicating that cancellation rates vary by state.

**10. Cancellation Rates by Ship-City**

- Descriptive Analysis: Cancellation rates were analyzed by ship-city, identifying regional differences in customer cancellations.
- Inferential Hypothesis: The Chi-Square Test was applied to explore the association between ship-city and cancellation rates. The results indicated a significant association, suggesting that cancellation rates differ based on the city.
![cancelationrate](https://github.com/user-attachments/assets/f975ac3c-b1c1-4111-bfeb-3695485868d5)


## Key Insights:
- Revenue Differences: There are significant differences in revenue across product categories, seasons, and regions.
- Promotions: Promotions significantly increase order quantity, but the impact on cancellation rates is not clear.
- Shipping Service Level: No significant relationship was found between service level and cancellation rates, though shipping cost varies by service level.
- Geography: Sales and cancellation rates differ significantly across states and cities, suggesting that location-based strategies could improve performance.
## Business Recommendations:
- Focus marketing efforts on high-performing categories and regions with low cancellation rates.
- Use promotions strategically to boost quantity sold, but analyze their impact on cancellation rates in different regions or cities.
- Optimize fulfillment strategies based on region and service level preferences, ensuring faster deliveries where possible to reduce cancellations.