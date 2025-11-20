# **Healthcare Sales Analysis**

### Background
Medical-X is a Group Purchasing Organization (GPO) that partners with medical supply manufacturers to negotiate and facilitate contracts offering discounts and rebates to its members. Since its establishment in 2020, Medical-X has experienced steady membership growth and consistent sales performance. However, the company continues to face challenges stemming from both internal inefficiencies and external market dynamics.

To address these challenges, the Head of Business Operations has assigned the task of developing data-driven insights that cross-functional departments can leverage to enhance sales performance and strengthen relationships with its members.

This comprehensive analysis examines the company's sales transaction and customer engagement data from 2020–2024 to uncover key insights and provide actionable recommendations focused on the following four key areas:

* Sales Trends: Overall growth, YoY breakdown, and Trend Interpretation.
* Product Performance: Highlighting Top 5 Products, Order Volume, and Average Order Volume(AOV).
* Customer Engagement: Member Level Distribution, Website Engagement, and Spending Behavior.
* Regional Comparisons: Regional Sales and Website Engagement.

## Data Structure and ERD
This data structure consists of 4 tables: medical_products, medical_sales, customers_table, and engagement_table consisting of a total row count of 3034 records.

<img width="700" height="400" alt="erd_graph" src="https://github.com/user-attachments/assets/6710d95f-8f87-47d6-9db7-a95753366168" />

## Insights deep dive

**Sales Trends**

- Overall Growth:

  <img width="700" height="500" alt="Sales" src="https://github.com/user-attachments/assets/1fb897e8-1505-493d-8583-89d02c16ac41" />  
  
    * Between 2020 and 2024, total sales increased from $3.34 million to $6.25 million, representing an overall growth of approximately 87% across five years.
    
- Year-over-Year Breakdown:

  <img width="285" height="222" alt="yoy" src="https://github.com/user-attachments/assets/c2eef7ec-105f-4a16-b9d1-d8f97868c899" />

    * 2020 → 2021: Slight increase of 1.3%, indicating stable but flat market activity post-launch
    * 2021 → 2022: Significant jump of 35.7%, suggesting expansion in customer base or higher-value product adoption
    * 2022 → 2023: Continued strong growth of 32.3%, maintaining momentum possibly due to strategic sales or new partnerships
    * 2023 → 2024: Growth slowed to 3.1%, implying market saturation or seasonal normalization after rapid scaling
      
- Trend Interpretation:
  
     * Sales show a clear upward linear trend with notable surges in 2022 and 2023, consistent with phases of business expansion. The downward trend in 2024 may indicate the need to explore new regions, products, or pricing strategies to sustain long-term performance.

**Product Performance**

- Top Five Products by Sales:

  <img width="700" height="368" alt="top5" src="https://github.com/user-attachments/assets/82a7d7cf-68e8-429e-9468-efa208bf95b0" />

     * Top selling products include hospital beds, defibrillator, ECG machine, stethoscope, and surgical gloves.
     * Hospital beds account for nearly 38% of sales. With only 4000 units sold, this implies its a high priced item.
     * The top 5 products together contribute ~73% of total revenue, indicating a concentrated product portfolio.
     
- Order Volume:
  
   <img width="900" height="400" alt="quantitysoldd" src="https://github.com/user-attachments/assets/a66911d1-979f-4bb5-aff7-6888f7891f01" />

     * Overall pattern: Total units sold each year fluctuate moderately with alternating growth and decline periods rather than consistent upward movement. 2022 stands out as the strongest year for both volume and sales — possibly due to strong market expansion or large institutional purchases.
     * Order volume shows cyclical variation — suggesting that increased sales have been driven more by higher unit prices or premium product mixes than by larger order counts.  
       
- Average Order Value(AOV):

    <img width="900" height="350" alt="AOV" src="https://github.com/user-attachments/assets/8aa5350e-ae75-4faf-8d5c-1aa60607d265" />

     * The AOV nearly doubled between 2020 and 2023, showing substantial growth in average order value. This suggests customers are purchasing higher-value products or buying in larger quantities per order.
     * The overall AOV of $102.14 confirms strong average transaction value across the 5-year period.

**Customer Engagement**

  <img width="622" height="468" alt="memberlevell" src="https://github.com/user-attachments/assets/76ba2abb-6814-4c2f-bf9b-f3f41a0b6167" />

- Membership Level Distribution:
     * Each membership tier has a similar number of customers (around 80–85 each). Gold members represent the highest engagement and sales volume because they're more active and higher-spending.
- Website Engagement:
     * Gold members average ~163 logins, which is higher than both bronze(48) and silver(89). This indicates a stronger online engagment leads to higher sales.
- Spending Behavior:
     * Gold members contribute around $670 million in total spend which is almost double of silver and over 3 times bronze members. This sugguests that loyalty and engagement has a strong correlation with sales performance. 
 
**Regional Comparisons**

  <img width="800" height="350" alt="regionalspend" src="https://github.com/user-attachments/assets/8dffccf3-d4d2-41fe-a247-0eddcf812bd1" />

  - Regional Sales:
    * The Northeast region contributes the highest total spend ($403.7M) — significantly outpacing the other three regions. This indicates strong customer purchasing behavior, suggesting effective sales strategies or higher market maturity in that region.
    * The South follows as the second-highest, while the West and Midwest are smaller contributors in total revenue terms.
  - Website Engagement:

    <img width="842" height="372" alt="avglogins" src="https://github.com/user-attachments/assets/17274ba8-c9bb-4f76-b97d-81143995f51c" /> 

    * Despite lower overall spend, the Midwest stands out with the highest average website logins (111.9)
    * This suggests customers in the Midwest are more digitally engaged, presenting a conversion opportunity to drive future sales.
    * In contrast, the West region has both low spend and low engagement, indicating it may need targeted outreach or marketing campaigns.

## Actionable Recommendations


**For Sales Team -**

1) Prioritize High-Value Members: Gold members showed stronger spend and online engagement.
   * Offer business review meetings to strengthen relationships further.
   * Identify members with growing spend but low login frequency and offer promotions for increased engagement activity.
   * Introduce exclusive contract bundles to encourage long term committment. 
    
2) Launch a Preventative "Churn Risk" Program: Silver and bronze members show lower engagement, lower spend, and higher churn potential.
   * Provide quarterly check-in calls to help build relationships.
   * Offer incentives to increase website usage. Engagement strongly correlates with spend. 
   * Run automated alerts for accounts with declining sales or login activity.
    
**For Marketing Team -**

1) Member Level Campaigns: 
   * Gold members can benefit from exclusive VIP offers, customized messages for reaching membership tenure and special newsletters. 
   * Silver members have a key upsell opportunity - they have moderate engagement and spending but could graduate to Gold with targeted campaigns.
   * Bronze members could use re-engagement initiatives - email campaigns, incentives for online activity, offer seasonal discounts.
 
2) Build an Engagement Program for Bronze Members:
   * Automated emails promoting contract savings.
   * Onboarding tutorials explaining how to navigate the portal.
   * Monthly recaps that show potential savings they missed.


