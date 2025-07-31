# Customer-Behavior-and-Retention-Analysis-on-E-commerce-Platform

## Project Background
This project aims to analyze customer behavior using the UK E-Commerce Dataset, which consists of transaction records from a retail company based in the United Kingdom. The dataset includes all online purchase transactions between December 1st, 2010 and December 9th, 2011.

Given the seasonal nature of the products offered, this analysis focuses particularly on the peak sales period from September to November 2011. The main goal of the analysis is to identify customer purchasing patterns, segment customers based on their purchasing characteristics, and provide insights that can help enhance customer retention strategies and improve the effectiveness of future marketing campaigns.
## Executive Summary
### Sales Performance
* Revenue was stable from Jan–Aug 2011 (~£215K/month).
* Significant growth in Sep 2011 (+52.3%), peaking in Nov (£517K, 2,359 orders).
* Drop in Dec is due to partial data (up to Dec 9).
* Sales trends reflect seasonal demand ahead of holidays.
### Customer Composition & Behavior
* **Existing Customers:**
    * 70% of monthly transactions (Sep–Nov).
    * Accounted for 81% of revenue.
    * AOV: £233.29 from 5,132 orders.
* **New Customers:**
    * Accounted for 19% of revenue.
    * Higher AOV (£243.08), but fewer orders.
### Customer Segmentation
* 71.4% of customers fall into Top & Potential segments.
  * **Top Customers:**
    * Accounted for 70% of revenue.
    * Highest AOV: £249.28.
  * **At Risk:**
    * AOV: £162.58, likely driven by wholesale/seasonal buyers.
### Customer Retention
* Sep 2011 cohort shows strongest retention:
  * 37% returned in month 2, 52% in month 3.
* Oct cohort: 31% retention in month 2.
* Confirms increased activity before Christmas.

## Insight Deep-Dive
### Sales Trends and Growth Overview
<img width="1500" height="600" alt="Image" src="https://github.com/user-attachments/assets/1c2ef8c9-3682-401a-85da-a7b2df2c6724" />
<img width="1500" height="600" alt="Image" src="https://github.com/user-attachments/assets/ebd553b0-7787-4d34-a26f-c9c4b8b1d65d" />

* Revenue remained relatively stable from January to August 2011, averaging around £215,000 per month.
* A significant surge occurred in September 2011, with revenue rising to £386,208, and continued to grow until peaking in November at £517,038.
* September recorded the highest monthly revenue growth throughout the year at 52.3%.

<img width="1500" height="600" alt="Image" src="https://github.com/user-attachments/assets/df11eefb-f7a5-4e15-9705-d0faabc725be" />

* Order volume followed a similar upward trend, starting in September and peaking in November (2,359 orders), likely driven by holiday demand.
* The steep drop in December was due to incomplete data (only up to December 9), requiring cautious interpretation.
  
<img width="1599" height="140" alt="Image" src="https://github.com/user-attachments/assets/2b03a2f8-a447-4c0f-a24d-dbd9f98acf39" />

**Key Highlights (Sep-Nov):**
* November marked the strongest overall performance, showing growth across all metrics: revenue (+20%), units sold (+21%), and order volume (+20%).
* The high-season momentum starting in September and peaking in November presents a strong opportunity for maximizing annual revenue.

### New Customers vs Existing Customers
<img width="1400" height="700" alt="Image" src="https://github.com/user-attachments/assets/74e15729-49b8-4b3a-b544-be7450a4d200" />
<img width="1383" height="174" alt="Image" src="https://github.com/user-attachments/assets/58c5158b-7a57-445b-8061-b7046a011a02" />

Throughout the September–November 2011 period, returning (existing) customers consistently dominated monthly transactions, accounting for over 70% of activity.

This indicates strong customer retention and the platform's success in maintaining a loyal customer base.

**Contribution breakdown:**

**Existing Customers:**
* Accounted for 81% of total revenue.
* AOV: £233.29 from 5,132 orders.
* Their high engagement and consistent transaction frequency position them as the core customer segment.
  
**New Customers:**
* Contributed 19% of total revenue.
* Slightly higher AOV (£243.08), likely due to bulk purchases of low-priced items.
* Much fewer orders (1,135), indicating lower loyalty and transaction frequency.
 
### Customer Segmentation and Profiling
<img width="1000" height="800" alt="Image" src="https://github.com/user-attachments/assets/90e1d80c-fbee-4360-b2e7-32a4acea56f3" />
<img width="1652" height="291" alt="Image" src="https://github.com/user-attachments/assets/8e56237d-1b7d-4a23-b9f2-47abb8eee98f" />

Based on the RFM analysis, customers were grouped into four primary segments: Top Customers, Potential Customers, At Risk, and Churned Customers.

**Distribution & Contribution:**
* Top Customers and Potential Customers represent the majority—71.4% of total customers—and can be classified as loyal segments.
* Top Customers contributed the most to total revenue (70%), with the highest AOV (£249.28) and high purchase frequency.
* Potential Customers had a competitive AOV (£237.05) but fewer orders, contributing 21% to total revenue.

**The At Risk segment is particularly noteworthy:**
* Despite contributing only 9% to total revenue, they had a relatively high AOV (£162.58).
* This AOV was driven by large purchase quantities rather than high unit prices.
* This suggests they are likely wholesale or seasonal buyers.

### Customer Retention Trend
<img width="1000" height="600" alt="Image" src="https://github.com/user-attachments/assets/6b64ab77-ed7b-4d02-b32c-6e7d21b62c59" />

The cohort analysis visualizes customer retention across three monthly cohorts: September, October, and November 2011. Each row represents a cohort of new customers who made their first purchase in that month, while each column (Cohort Index) indicates how many months have passed since the initial purchase.
* 100% retention is shown at index 0 for all cohorts, as it represents the first month of purchase.
* The September 2011 cohort shows the strongest retention performance, with 37% of customers returning in the second month, and 52% in the third month.
* The October 2011 cohort retains 31% of its customers in the second month.
* The November 2011 cohort currently lacks retention data for subsequent months, likely due to the dataset ending in early December 2011.

### Customer Product Preferences
#### Top 5 Products by Period
<img width="800" height="800" alt="Image" src="https://github.com/user-attachments/assets/fad139b9-b7c1-478a-9d40-b84e67f315fb" />

The top-selling products by month show a clear trend: Christmas-themed accessories and decorations dominate the list. Examples include:
* Christmas Scandinavian decorations
* Themed gift sets
* Paper chains and napkins with holiday designs

This supports the hypothesis that holiday seasons significantly influence purchasing behavior, particularly for themed or seasonal products.

#### Top 5 Products by RFM Segment
<img width="800" height="800" alt="Image" src="https://github.com/user-attachments/assets/e9d24f4a-b53b-4fd0-ab91-dba8b4b1d889" />

When broken down by RFM customer segments, the product preference remains consistent. Across all segments—Top Customers, Potential, At Risk, and Churned—the best-selling items are:
* Christmas-themed decorations
* Gift items
* Seasonal accessories

This consistency indicates that customer needs across segments are highly seasonal, presenting an opportunity to implement seasonal targeting strategies and tailor marketing efforts based on calendar-driven demand.

## Recommendations
### Maximize the High-Season Opportunity
* Launch holiday-themed campaigns earlier, ideally in late August or early September, to gradually build customer awareness.
* Prioritize inventory planning for best-performing seasonal products, such as Christmas Scandinavian and Retropost Cake Cases, to avoid stockouts during peak demand.
### Strengthen Existing Customer Loyalty
* Develop a loyalty program based on purchase frequency and AOV, using a points system or tiered membership levels (e.g., Gold, Silver, Platinum), with incentives such as exclusive discounts or priority shipping.
* Conduct A/B testing to identify the most effective type of offer for this segment—whether it's direct discounts, product bundling, or limited-time offers.
### Optimize Sales of Hight-Margin Products
* Design special bundling packages that combine multiple high-value seasonal items into one purchase (e.g., Christmas ornaments, gift tags, and wrapping supplies).
* Perform item-level margin analysis to determine which products yield the highest profitability, rather than focusing solely on sales volume.
### Prepare Earlier for the Next Peak Season
* Leverage historical trends (especially from September to December) to forecast demand and refine sales strategies for the upcoming year.
* Plan marketing campaigns at least one or two months in advance, including promotional asset creation, customer segmentation by shopping behavior, and scheduling campaigns across email and social media.
* Build a data-driven promotional calendar outlining the ideal timing for teaser launches, major discount rollouts, and enhanced customer support, to ensure a structured and proactive approach during peak season.
## Clarifying Questions, Assumptions, and Caveats
### Clarifying Questions
* Are all products with a unit price of £0 classified as promotional or bonus items?
* Were there any discount or marketing campaigns conducted during peak sales periods (e.g., November 2011)?
* Is there any business logic or documentation regarding product categorization (e.g., how to interpret missing StockCode or "Manual" items)?
### Assumptions
* Duplicate records with identical **InvoiceNo**, **StockCode**, and **CustomerID** are handled as follows:
  * If the **Quantity** values differ, they are treated as multiple purchases made under the same invoice.
  * If the **Quantity** values are the same and repeated, they are assumed to be duplicate entries and consolidated accordingly.
* All transactions are assumed to be conducted exclusively online, as there is no data indicating the presence of any physical retail outlets.
### Caveats
* A significant number of transactions have missing CustomerID, which limits the completeness and accuracy of customer-level behavioral analysis.
* The dataset does not provide any information regarding operational costs, returns, or refunds. Therefore, all revenue-related metrics and insights are based on gross revenue, not net profit.
* Data for December 2011 appears incomplete and may not represent the full month's activity. As such, metrics from this month should be interpreted with caution.
