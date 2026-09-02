# Data-Analysis
Data analytics practice projects with statistics, visualizations and machine learning models
Maven Communications — Customer Churn Analysis
Project Overview

This project analyzes customer churn for Maven Communications, a California-based telecommunications company.

The goal of the analysis was to understand why customers are leaving, which customer groups are most likely to churn, and what Maven Communications can do to improve customer retention.

Objectives
Calculate the overall customer churn rate
Analyze churn across different customer characteristics
Identify high-risk customer groups
Identify the most common reasons customers churn
Analyze revenue associated with churn
Cross-reference high-risk groups with churn reasons
Develop business recommendations based on the findings
Tools & Technologies
Python
Pandas — data cleaning and analysis
Matplotlib — data visualization
Seaborn — data visualization
Jupyter Notebook
Analysis
1. Overall Churn

Calculated the proportion of customers who have churned compared with the total customer base.

2. Churn by Customer Characteristics

Analyzed churn rates across variables including:

Contract type
Tenure
Age
Internet service
Internet type
Offers
Online security
Online backup
Device protection
Premium tech support
Streaming services
Unlimited data
Payment method
3. High-Risk Customer Groups

Several customer groups showed particularly high churn rates.

Some of the highest-risk groups identified were:

Customer Group	Churn Rate
Tenure: 0–6 months + Month-to-Month contract	57.06%
Offer E	52.92%
Month-to-Month contract	45.84%
Age 66+	41.86%
Online Security: No	41.77%
Premium Tech Support: No	41.64%
Fiber Optic	40.72%
Online Backup: No	39.93%
Device Protection Plan: No	39.13%
Payment Method: Mailed Check	36.88%
4. Churn Reasons

The most common reasons reported by churned customers included:

Competitor had better devices — 313 customers
Competitor made better offer — 311 customers
Attitude of support person — 220 customers
Don't know — 130 customers
Competitor offered more data — 117 customers
Competitor offered higher download speeds — 100 customers

The findings suggest that competition, pricing/value, devices, and customer support are important areas for Maven to investigate.

5. High-Risk Segment Analysis

A deeper analysis was performed on customers with both:

Month-to-Month contracts
0–6 months of tenure

This group had a 57.06% churn rate.

Among churned customers in this segment, the most common reported reasons were:

Competitor made a better offer — 18.72%
Competitor had better devices — 18.08%
Attitude of support person — 10.51%

This suggests that early-tenure month-to-month customers may be an important group for targeted retention efforts.

Key Insights

The analysis suggests that Maven Communications should pay particular attention to:

Customers in their first six months
Month-to-month customers
Customers receiving Offer E
Customers without additional security and support services
Competitive pricing and device offerings
Customer service and support experience
Business Recommendations

Based on the analysis, the following recommendations were developed:

Create an early-retention program for new month-to-month customers.
Review Offer E and investigate why it has such a high churn rate.
Improve competitive value by reviewing pricing, devices, data allowances, and download speeds.
Strengthen customer support through training and improved technical assistance.
Develop churn-risk monitoring to identify high-risk customers and prioritize retention efforts.
Conclusion

The analysis identified several customer segments with substantially higher churn rates and highlighted competition, customer support, and early customer tenure as important areas for Maven Communications to address.

The findings can help Maven focus retention efforts on the customers most at risk rather than applying the same strategy across the entire customer base.

Project Structure
Maven-Customer-Churn-Analysis/
│
├── data/
│   └── customer_data.csv
│
├── notebooks/
│   └── Customer_Cancellation_Analysis.ipynb
│
├── visualizations/
│   └── ...
│
├── README.md
└── requirements.txt
Skills Demonstrated
Data cleaning
Exploratory Data Analysis (EDA)
Pandas
Data visualization
Groupby analysis
Pivot tables
Churn rate analysis
Customer segmentation
Revenue analysis
Business analysis
Data-driven recommendations
