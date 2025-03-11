# E-COMMERCE DATA ANALYSIS

## TABLE OF CONTENT
- [Project Overview](#Project-Overview)
- [Tools Used](#Tools-Used)
- [Workflow](#Workflow)
- [Dashboard Insights](#Dashboard-Insights)
- [Dashboard](#Dashboard)
- [Recommendations](#Recommendation)

## PROJECT OVERVIEW
This project explores an E-Commerce dataset to uncover actionable insights and trends in sales, customer behavior, and operational efficiency, presented through an interactive Power BI dashboard that clearly displays key performance indicators (KPIs) and trends for easy understanding at a glance.

 ## Tools Used
 
 - Excel: For initial dataset review and preparation.
 - Power Query: For Data Preparation,Cleaning and Transformation.
 - Power BI: For interactive Data visualization and Reporting.

## Workflow
**1. Data Exploration**
- The dataset was initially view in Excel

**2. Data Loading and Transformation**
- The dataset was loaded in Power Bi and cleaned and transformed using power Query to address missing values,duplicates,Replaced values,Removes excess spaces and inconsistent Date format

**3. Analysis and Visualization**
- Measures were created and Calculated Date Columns to support Analysis.
- Visualize trends and pattern using bar chart, line chart, column chart, matrix and Pie chart.

## DASHBOARD INSGHTS
### Historical Sales Trend
  **Annually**
- From 2015 to 2018, sales remained steady at $1M. However, from 2019 to 2022, there was significant growth, reaching $25M by the end of the period.
<img width="793" alt="Screenshot 2025-03-11 at 6 18 49 PM" src="https://github.com/user-attachments/assets/291da276-1476-4512-a386-ac147df42c88" />

- Monthly sales showed fluctuations, with October recording the highest sales at $5.5M and December the lowest at $3.7M.
<img width="785" alt="Screenshot 2025-03-11 at 6 19 20 PM" src="https://github.com/user-attachments/assets/04b9568b-1226-4294-9884-acfd4803ca43" />

**Seasonal**
- There were high sales in the spring and early summer (Q2), but sales fell drastically from the winter to the spring (Q1 to Q2).
![Sales By Season](https://github.com/Eseroghene/E-COMMERCE-DATA-ANALYSIS/blob/main/Sales%20By%20Season.png)
 
### Top Performing Categories
	
- Office Supplies is the top performer and leads with $31 million, contributing the most to revenue.
- Furniture follows with $11 million in revenue.
- Technology generates the least, with $9 million in revenue.
<img width="789" alt="Screenshot 2025-03-11 at 6 20 54 PM" src="https://github.com/user-attachments/assets/068a27b8-343e-46a2-8ad1-55561454c9f8" />

### Customer Retention and Loyalty
- Returning Customers: Represent 71.18% (30K), indicating strong customer retention and loyalty.
- The 71.18% retention rate supports the idea of strong customer loyalty.
<img width="785" alt="Screenshot 2025-03-11 at 6 21 51 PM" src="https://github.com/user-attachments/assets/978ecfc7-c573-4659-9056-7ed15a6281ef" />

 
 ### Shipping Type By Delivery Performance
 
- Same Day: Best for on-time delivery (48.57%), but high late delivery (45.65%).
- Second Class: Balanced performance with a 71.46% late delivery rate, low advance shipping, and no data on cancellations.
- Standard Class: Consistent with on-time delivery (20.70%), advance shipping (38.31%), and late delivery (36.87%).
- First Class: Highest late deliveries (82.91%) and shipping cancellations (9.65%), with the lowest on-time deliveries.
<img width="788" alt="Screenshot 2025-03-11 at 6 22 30 PM" src="https://github.com/user-attachments/assets/6eeb3ae3-0eab-4c9d-953e-a8399b90c137" />


### Geographical Performance**

- West region has the highest revenue with $16.7M, while South has the lowest at $8.4M. There’s a decline from West to South.
- West region has the highest A.O.V at 433.2, and South the lowest at 425.2. A.O.V decreases similarly to revenue.
- Correlation: Higher revenue is linked to higher A.O.V, showing a possible cause of high sales in the West region.
<img width="468" alt="Screenshot 2025-03-11 at 6 22 56 PM" src="https://github.com/user-attachments/assets/beb9e0b3-9a76-4f6a-88cd-44f9a774cb96" />


### Delivery And Sales Relationship By Regions
 
- Late Delivery: Sales remain high across all regions despite delays, with the West leading, indicating strong product quality and 
customer satisfaction.
- Advance Shipping: The West shows the highest demand for faster delivery, followed by the East, South, and Central regions.
- On-Time Delivery: The East achieves the highest revenue, reflecting a focus on timely delivery and customer satisfaction, while the 
- Central struggles with low revenue due to delivery challenges.
<img width="614" alt="Screenshot 2025-03-11 at 6 23 27 PM" src="https://github.com/user-attachments/assets/43f97298-ea20-41b0-ba5a-ade3ba279593" />


### Customer Segmentation

**Customer Segment by Category**

- Consumer segment leads sales, with Furniture at $16.1M.
- Office Supplies dominate in Corporate ($9.4M) and Home Office ($5.6M).
- Technology underperforms across all segments.
![Customer Segment by Category](https://github.com/Eseroghene/E-COMMERCE-DATA-ANALYSIS/blob/main/Customer%20Segment%20by%20Category.png)

**Customer Segment By Metrics**

- Consumer Segment: Dominates in quantity and product,showing the highest interest in products and  driving overall sales.
- Corporate Segment: Makes a strong contribution to revenue.
- Home Office & Home Segments: Smaller but still significant, with growth potential in these areas.
- All segment Revenue seems to be affected by the discount on orders/products
<img width="801" alt="Screenshot 2025-03-11 at 6 24 46 PM" src="https://github.com/user-attachments/assets/7e522412-19af-40e1-8674-3098b1a996f0" />


**Top 5 Product Categories and Customer Segment By Sales***
- Consumer Segment: Staple Envelope tops sales at $155K, followed by Staples ($116K) and Easy-staple Paper ($98K). Avery Non-Stick Binders trail at $65K.
- Corporate Segment: Staples lead with $103K, closely followed by Staple Envelope ($100K). Other products contribute less.
- Home Office Segment: Easy-staple Paper dominates with $79K, Staples perform modestly ($43K), while others have minimal sales.
<img width="787" alt="Screenshot 2025-03-11 at 6 25 41 PM" src="https://github.com/user-attachments/assets/f062c7bc-81d6-41f6-8d1f-88fbac421bf3" />

### DASHBOARD
The project includes an interactive dashboard to visualize key insights from the data. Below is a preview:

<img width="815" alt="Screenshot 2025-03-11 at 6 33 48 PM" src="https://github.com/user-attachments/assets/8e821acf-656e-4198-be35-1614251480d5" />
<img width="814" alt="Screenshot 2025-03-11 at 6 34 27 PM" src="https://github.com/user-attachments/assets/f00ce0e1-6314-48a8-82b2-21531edff9f6" />
<img width="821" alt="Screenshot 2025-03-11 at 6 35 06 PM" src="https://github.com/user-attachments/assets/12ee117d-2830-4766-86e4-e71fb97291c9" />

## RECOMMENDATIONS

- Conduct market research to understand sales decline.
- Innovate with new products and revise marketing strategies.
- Optimize costs and focus on customer retention.
- Improve strategies to attract new customers while retaining existing ones.
- Investigate and address the reasons for the high late delivery rate for Same Day shipping to improve on-time 
  performance.
- Focus on reducing late deliveries for First Class despite its high shipping rate.
- Maintain the current performance of Second Class as it provides a balanced service.
- Continue monitoring and maintaining the well-balanced performance of Standard Class.
- Invest in the West for higher revenue ($16.7M) and A.O.V (433.2).
- Boost revenue in the South by addressing challenges.
- Apply best practices from the West to improve Central and South regions.
- Streamline delivery processes to reduce delays, especially in the West.
- Offer premium shipping options, particularly in the West and other regions like the East and South.
- Replicate East region’s on-time delivery practices in the Central region to increase revenue.
- Focus on driving repeat sales in the Consumer segment with targeted marketing.
- Strengthen Corporate segment relationships and offer bulk discounts.
- Invest in tailored products and marketing for Home Office & Home segments.
- Develop strategies to boost sales of Easy-staple Paper and Avery Non-Stick Binders in the Corporate segment.

