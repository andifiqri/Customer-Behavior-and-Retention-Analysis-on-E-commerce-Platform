# Customer-Behavior-and-Retention-Analysis-on-E-commerce-Platform

This project analyzes customer behavior on an e-commerce platform with a focus on customer retention, segmentation, and churn pattern. By leveraging RFM analysis, CRR (Customer Retention Rate), and cohort analysis, we aim to uncover actionable insights that can help business optimize retention strategies, improve customer experience, and increase lifetime value.

---

## Objectives 
-	Understand customer behavior patterns.
-	Segment customers based on purchasing activity.
-	Identify churn and retention trends over time.
-	Provide strategic recommendations for improving retention.

---

## Analysis Overview
### 1. RFM Analysis (Recency, Frequency, Monetary)
Customers were segmented into five key groups based on their transactional behavior:
-	Highly Retained (12.64%): Loyal customers with frequent, recent, and high-value purchases.
-	Retained Customers (19.80%): Customers with positive behavior but less consistent than highly retained.
-	Average Customers (29.43%): Majority group with irregular purchasing behavior.
-	At Risk (18.55%): User whose purchasing frequency has dropped significantly.
-	Churn Customers (19.59%): Customers who haven’t transacted in a long time.

Insight: A small portion of users are truly loyal, while a large group shows signs of potential churn, indicating a need for better engagement strategies.

---

### 2. CRR (Customer Retention Rate)
Monthly CRR fluctuates between 30% - 40%, which is relatively healthy for e-commerce business. However, some months, such as April 2011 and December 2011, show sharp declines due to either user drop-offs or incomplete data input.
Insight: Although only a small group is “highly retained”, the overall CRR suggests customers do return, albeit with varying frequency – possibly influenced by seasonality or promotions.

---

### 3. Cohort Analysis
The cohort retention heatmap shows that:
-	Customers from December 2010 had the highest long-term retention, peaking at 49% in month 11.
-	Most other cohorts experience a sharp drop-off after month 1.
-	Retention stabilizes around 20-30% in the early months but declines significantly over time.

Insight: Early engagement is critical. Most customers churn after 2-3 months unless actively re-engaged.

---

## Key Insights Summary
-	Only 12.64% of users are in the highly retained group, suggesting weak overall loyalty.
-	Despite a relatively stable CRR, most of customers don’t become long-term repeat buyers.
-	The “Average” and “At Risk” segments are ideal targets for reactivation and upselling.
-	Initial cohorts tend to churn quickly, emphasizing the need for early lifecycle engagement.

---

## Tools used
-	Python (Pandas, NumPy, Seaborn, Matplotlib)
-	Google Colab


