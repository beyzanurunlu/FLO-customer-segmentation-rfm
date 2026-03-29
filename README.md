# From RFM to Revenue: FLO Customer Segmentation
RFM-based customer segmentation project transforming transactional data into revenue-focused marketing insights using Python.

## Overview
Understanding customer behavior is essential for sustainable growth in retail.  
This project leverages RFM (Recency, Frequency, Monetary) analysis to segment FLO customers and uncover behavioral patterns that directly impact customer value and revenue generation.

## Objective
Identify high-value, loyal, and at-risk customers to enable data-driven marketing strategies.

## Key Insights
- Loyal Customers generate the highest total revenue (~4.1M), driven by their large customer base and consistent purchase frequency   
- Champions represent the most valuable customers, with the highest average spend (~1,410) and very recent activity  
- At-Risk and Can't Lose segments contribute over ~3.8M in total revenue combined, indicating a significant potential revenue loss if not re-engaged  
- Hibernating customers form the largest segment but generate relatively low revenue due to low purchase frequency and spending  

## Business Impact
- Identifies high-value segments (Champions, Loyal Customers) for premium targeting and revenue maximization  
- Highlights churn-risk segments (At-Risk, Can't Lose) representing significant revenue at risk  
- Enables focused marketing strategies instead of broad, inefficient campaigns  
- Supports data-driven decision-making for customer retention and reactivation  
  
## Dataset Overview
The dataset includes approximately 20,000 FLO customers who made purchases between 2020–2021 across both online and offline channels.

## Key Features
- Order channels (online & offline)
- Purchase frequency and recency
- Customer lifetime value (monetary)
- Category interests over the last 12 months

## Methodology
- Data preprocessing and feature engineering  
- Calculation of RFM metrics (Recency, Frequency, Monetary)  
- RFM scoring and segmentation  
- Customer grouping based on behavioral patterns  

## Customer Segments
- Champions: Recent, frequent, and high-spending customers  
- Loyal Customers: Consistently purchasing customers  
- Potential Loyalists: Customers with growth potential  
- New Customers: Recently acquired customers  
- Promising: Low-frequency but potential customers  
- Need Attention: Customers showing declining engagement  
- About to Sleep: Customers close to inactivity  
- At Risk: Previously active but now inactive customers  
- Can't Lose: High-value customers at risk of churn  
- Hibernating: Low engagement and long inactivity
 
## Marketing Strategy Applications
- Premium Women's Brand Campaign: Targets high-value segments (Champions, Loyal Customers), covering ~12.47% of customers  
- Discount Campaign (Men & Kids): Targets churn-risk segments (Can't Lose, About to Sleep, New Customers), covering ~8.83% of customers
  
These targeted campaigns demonstrate a strategic approach, focusing on maximizing value from top customers while re-engaging at-risk segments instead of applying mass promotions.

## Conclusion
RFM segmentation reveals that a relatively small group of high-value customers drives a significant portion of total revenue, while certain segments represent critical re-engagement opportunities.

By translating these insights into targeted marketing strategies, businesses can improve retention, increase customer lifetime value, and optimize marketing efficiency.

## Tools & Technologies
- Python  
- Pandas  

## Dataset
FLO retail customer dataset (Kaggle)  
👉 [View Kaggle Notebook](https://www.kaggle.com/code/beyzanurnl/from-rfm-to-revenue-flo-customer-segmentation)

## Author
Beyza Nur Ünlü
