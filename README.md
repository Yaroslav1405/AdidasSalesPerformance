# Adidas Retail Sales Performance Analysis 2021
## Project Background and Overview
   
Adidas is a globally recognized brand specializing in athletic apparel, footwear, and accessories. This performance analysis project focuses on gaining insights into Adidas's sales dynamics, operating profit performance, product-level performance, and regional distribution in 2021 in the United States. The ultimate goal was to harness these insights to drive decisions on regional marketing priorities, channel investment, and product assortment for the sales and merchandising team.

## Objectives

  1. **Product Performance Analysis:** To understand how different products perform in terms of sales and overall contribution to revenue.
     
  2. **Growth Insights:** To find trends and opportunities for business growth across various regions and periods.

   
## Data Description
   The dataset contains detailed transaction-level records and supporting metadata fields.
  * _City_ / _State_ / _Region_ : Georgraphic information of an item bought.
  * _Invoice_date_: The date on which a transaction occurred.  
  * _MonthName_ / _MonthNum_ / _Year_: Derived time of each transaction.
  * _Operating Profit_: The profit from a sale after deducting operating costs.
  * _Price per Unit_: Price per item sold.
  * _Product_: Product category of each item. 
  * _Retailer_ / _Retailder ID_: Partners involved in transaction.
  * _Sales ID_:  Unique identifier for each sale.
  * _Sales Method_: The channel through which the sale was made.
  * _Total Sales_: The total revenue generated from a sale.
  * _Units Sold_: Number of units sold in each transaction.
    
![adidas_us_sales_erd](https://github.com/user-attachments/assets/470aaae7-3deb-4d69-ab35-022fd310a52e)


## Executive Summary
The analysis shows that Men's Street Footwear is the top performer in both sales with **$22.7 million** and profit of **$6.7 million**, but Women's Apparel is the most profitable per unit - **$16.3**, showing a big opportunity to scale that category for higher returns. On the other side, Women's Athletic Footwear and Men's Apparel underperform, suggesting we need to revisit their pricing or cost structure. 
From a growth perspective, 2021 marked a strong rebound from Covid with sales hitting around **$96 million**, and **$27 million** of operating profit, both categories totaling **4 times** growth compared to 2020. Seasonal peaks come in July and December with over **$10 million** in sales. Regional differences show that some cities like Charleston and Charlotte have more than **90% sales through online** channels, while cities like Dallas and Birmingham heavily rely on outlets with similar over **90% sales through outlets**. Finally, in-store sales produce the smallest amount of sales (**17.4%** or **1,500 units**), however, delivering the highest profit (**$10M**) among all three sales distribution channels. 
With that being said, there is strong momentum, but also clear signals on where to adjust product strategy and regional focus to grow smarter.
   
## Key Insights
1. ### Product Performance.

* **Men's Street Footwear Dominance:**
  
    With $22.7 million in total sales, $6.7 million in operating profit, and nearly 500,000 units sold, Men's Street Footwear leads all product categories in both volume and profitability. It consistently ranks #1 in 4 of 5 U.S. regions.

* **Channel Impact on Product Profitability:**
  
    In-store sales show higher profits despite being the smallest channel by volume. The potential reason for this can be due to some product categories performing disproportionately better in physical retail, pointing to the potential for in-store product bundling or upselling.
  
* **Product Profitability Efficiency:**
  
    While Men's Street Footwear leads in total sales ($22.7M) and operating profit ($6.7M) with nearly 500,000 units sold, a closer look at operating profit per unit reveals that Women's Apparel is the most profitable per unit. 
  * **Women's Apparel:** $16.3 profit per unit
  * **Men's Apparel:** $14.3 per unit 
  * **Men's Street Footwear:** $13.4 per unit
  * Other categories fall around $11-$12 per unit.
    
  This indicates that Women's Apparel, despite lower total revenue, delivers higher profitability efficiency, showing great pricing power or lower cost structure.
By scaling Women's Apparel, the company could return higher total sales and operating costs, displacing Men's Street Footwear from its first place.

* **Underperforming Categories:**
  
  Despite having a high profit per unit($14.3/unit), Men's Apparel lags in overall contribution to revenue($3.5M), given the volume of items sold(245,000 units). Women's Athletic Footwear has the lowest profit efficiency($3.0M), showing possible issues with pricing strategy, discounting, or high associated costs.
These trends suggest a need for a dive into the unit economics of these segments to identify areas for improvement. Streamlining product lines, reallocating marketing resources could improve performance in both categories.  

2. ### Growth Insights
   
* **Post-COVID Growth Trajectory:**
  
    In 2021, Adidas saw a 4x growth in operating profit compared to 2020, with total sales reaching $96 million, signaling a strong rebound and possible renewed consumer demand for apparel and footwear.

* **Seasonal Sales Opportunities:**
  
    Sales follow a predictable pattern, peaking in July ($10.4M) and again in December($10M). These periods present optimal windows for targeted promotions, new product launches, and regional events. 

* **High-Performing Regions South and Southeast:**
  
    These regions dominate the Top 10 cities by operating profit, including Charleston, Charlotte, Orlando, New Orleans, and Birmingham, Dallas, and Knoxville. In Charleston, Charlotte, New Orleans, and Orlando, over 90% of operating profit is generated through online sales, highlighting the importance of digital channels and e-commerce optimization in these urban areas. 
Conversely, in Dallas, Birmingham, and Knoxville, over 90% of profit is driven by outlet sales, indicating a strong physical retail presence and customer reliance on outlet shopping. These findings suggest a need for region-specific channel strategies, which is strengthening online presence where it's thriving and reinforcing outlet operations in regions where physical stores drive profitability.

* **Online vs. In-store Strategy:**
  
    While online dominates in volume (52%), it lags in profit ($9M with 4,400 sales) compared to in-store ($10M with 1,500 sales). This creates a growth opportunity to either optimize the online experience, like upselling bundles, or invest in enhancing in-store traffic in high-value locations. 

* **White Space in Midwest and West:**
  
    Noticeable white space in the sales heatmap suggests low performance in several Midwestern and Western states, showing the opportunity for geo-targeted campaigns, retail partnerships, or digital outreach to grow the customer base.

![adidas_us_sales_dash](https://github.com/user-attachments/assets/a6ce5d00-03e0-4e1d-ad1f-05075d1852fc)


## Conclusion

### **Recommendations:**

1. **Scale Women's Apparel:**
   
    With $16.3 operating profit per unit, expanding this categorty's visibility, especially in high-margin channels like in-store, could add around $2-3 million in additional profit if scaled to volumes similar to Men's Street Footwear (~500,000 units).

2. **Boost In-Store Efficiency in High-Value Markets:**
   
    In-store sales deliver $10M profit from 1,500 sales vs. $9M from 4,400 online, suggesting a nearly 3 times profit-per-transaction advantage. Invest in in-store bundling, exclusive launches, and high-converting retail stagg in top-performing cities.

3. **Address Underperforming Categories:**
   
    Reassess Women's Athletic Footwear ($3.0M profit from 253k units) and Men's Apparel ($3.5M from 245k units) to redue cost of reposition pricing.

4. **Geo-Target Midwest and West:**
   
    Launch awareness campaigns or online-exclusive promotions in low-performing states shown on the sales heatmap.

5. **Optimize Seasonal Peaks:**
    
    Capitalize on July and December, which account for about 16% or $6M of annual revenue, by aligning digital marketing, product drops and influencer campaigns ahead, which strenghten both sales channels (online and in-store).

6. **Tailor Channel Strategy by Region:**
    
    Enhance online experience in Southeast cities where most (>90%) of profit is digital, and increase outlet marketing in cities where outlet performance dominates. 
  
In conclusion, in 2021 Adidas highlights market rebound, however must address specific challenges to sustain and grow success. By leveraging regional strenghts, improving channel-based campaigns, and streamlining product lines the company can drive continued improvement and profitability. 

Explore dashboard 
