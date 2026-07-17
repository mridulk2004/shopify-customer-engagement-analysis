# Customer Engagement & Conversion Optimization for ShopEasy

> End-to-end marketing analytics project leveraging SQL, Python, sentiment analysis, and Power BI to identify opportunities for improving customer engagement, conversion rates, and marketing ROI in an e-commerce business.

---

## Overview

Customer acquisition costs continue to rise for e-commerce businesses, making customer engagement and conversion optimization increasingly important for sustainable growth.

ShopEasy, an online retail business, experienced declining customer engagement and conversion rates despite increasing investments in marketing campaigns. Management wanted to understand why customers were interacting less with marketing content, why fewer visitors were converting into customers, and how customer feedback could be leveraged to improve business performance.

This project analyzes the complete customer journey from initial engagement through purchase while combining customer sentiment analysis and marketing performance evaluation to generate actionable business recommendations. :contentReference[oaicite:0]{index=0}

---

## Business Problem

ShopEasy faced four major challenges:

- Declining customer engagement with marketing content.
- Falling conversion rates despite increasing website traffic.
- Rising marketing expenses with lower than expected returns.
- Lack of understanding of customer sentiment and pain points.

Management required a comprehensive analysis to identify the drivers behind declining performance and recommend strategies for improving engagement, conversion, and customer satisfaction. :contentReference[oaicite:1]{index=1}

---

## Business Objectives

The project aimed to answer five key business questions:

1. Where are customers dropping off in the conversion funnel?
2. Which products have the highest and lowest conversion performance?
3. Which marketing content drives the highest engagement?
4. What themes emerge from customer reviews and sentiment analysis?
5. Which actions can improve marketing ROI and customer satisfaction?

:contentReference[oaicite:2]{index=2}

---

## Key Performance Indicators (KPIs)

The analysis focused on four primary business metrics:

- Conversion Rate
- Customer Engagement Rate
- Average Order Value (AOV)
- Customer Feedback Score

These KPIs were used to evaluate business performance and measure the effectiveness of future interventions. :contentReference[oaicite:3]{index=3}

---

# Project Workflow

```text
Customer Interactions
        ↓
Customer Journey Analysis
        ↓
Marketing Funnel Analysis
        ↓
Engagement Analysis
        ↓
Customer Sentiment Analysis
        ↓
Dashboard Development
        ↓
Business Recommendations
```

---

# Repository Structure

```text
customer-engagement-conversion-optimization/
│
├── README.md
│
├── business_case/
│   └── Business_Case.pdf
│
├── dashboards/
│   └── Marketing_Analysis_Dashboard.pdf
│
├── sql/
│   ├── Customer_Journey.sql
│   ├── Customers_Table_SQLQuery1.sql
│   ├── Product_Table_SQLQuery1.sql
│   ├── Fact_Engagement.sql
│   └── Fact_customers_reviews.sql
│
├── python/
│   └── Sentimental_Analysis_Python.py
│
├── images/
│   ├── dashboard_overview.png
│   ├── conversion_funnel.png
│   ├── conversion_by_product.png
│   ├── engagement_trends.png
│   ├── sentiment_distribution.png
│   └── customer_reviews_analysis.png
│
└── requirements.txt
```

---

# Dataset Overview

The project integrates multiple datasets representing different stages of the customer journey.

## Customer Data
Contains customer profile and demographic information.

## Product Data
Contains product catalog information including product categories and metadata.

## Customer Journey Data
Captures customer movement through the purchase funnel.

## Engagement Data
Tracks customer interactions with content and marketing campaigns including:

- Views
- Clicks
- Likes
- Purchases

## Customer Reviews Data
Contains customer ratings and textual reviews for sentiment analysis.

---

# Customer Journey Analysis

The customer journey was modeled as a conversion funnel:

```text
Views
 ↓
Clicks
 ↓
Engagement
 ↓
Purchase
```

The analysis identified significant customer drop-offs throughout the funnel.

| Funnel Stage | Customers |
|-------------|-----------|
| Views | 672 |
| Clicks | 355 |
| Drop-Offs | 185 |
| Purchases | 57 |

The platform achieved an overall conversion rate of **8.5%**, indicating substantial opportunity for optimization. :contentReference[oaicite:4]{index=4}

---

# Conversion Analysis

The platform recorded an average conversion rate of:

## 8.5%

while maintaining an average customer rating of:

## 3.7 / 5

The analysis revealed significant variation in product-level conversion performance. :contentReference[oaicite:5]{index=5}

---

## Top Performing Products

| Product | Conversion Rate |
|---------|----------------|
| Kayak | 21.4% |
| Ski Boots | 20.0% |
| Surfboard | 13.9% |
| Volleyball | 12.8% |
| Fitness Tracker | 11.8% |

:contentReference[oaicite:6]{index=6}

---

## Underperforming Products

| Product | Conversion Rate |
|---------|----------------|
| Boxing Gloves | 2.6% |
| Climbing Rope | 2.7% |
| Cycling Helmet | 2.9% |
| Ice Skates | 4.8% |
| Running Shoes | 5.1% |

:contentReference[oaicite:7]{index=7}

---

## Business Insight

Several products generated significant engagement but weak conversion rates, suggesting opportunities to improve:

- Product positioning
- Pricing strategy
- Product descriptions
- Landing page quality
- Checkout experience

---

# Customer Engagement Analysis

The platform generated:

| Metric | Value |
|--------|-------|
| Views | 2,982,369 |
| Clicks | 458,345 |
| Likes | 73,618 |

Resulting in:

- Click Through Rate (CTR): **15.37%**
- Engagement Rate: **2.47%**

:contentReference[oaicite:8]{index=8}

---

## Monthly Engagement Trends

Engagement varied considerably throughout the year.

Traffic peaks occurred during:

- March
- May
- August

while engagement weakened toward the end of the year, indicating potential seasonality in customer activity patterns. :contentReference[oaicite:9]{index=9}

---

# Product Engagement Analysis

Products generating the highest customer interaction included:

- Ice Skates
- Cycling Helmet
- Basketball
- Running Shoes
- Tennis Racket

These products consistently generated strong visibility and interaction levels across multiple months. :contentReference[oaicite:10]{index=10}

---

# Sentiment Analysis

Customer reviews were processed using Python-based sentiment analysis techniques to understand customer satisfaction drivers and pain points.

Reviews were classified into:

- Positive
- Negative
- Neutral
- Mixed Positive
- Mixed Negative

---

## Sentiment Distribution

| Sentiment Category | Reviews |
|-------------------|---------|
| Positive | 275 |
| Negative | 82 |
| Mixed Negative | 60 |
| Mixed Positive | 21 |
| Neutral | 8 |

Positive reviews dominated customer feedback, indicating generally healthy customer satisfaction levels. :contentReference[oaicite:11]{index=11}

---

## Rating Distribution

| Rating | Number of Reviews |
|--------|------------------|
| 1 Star | 26 |
| 2 Star | 57 |
| 3 Star | 88 |
| 4 Star | 140 |
| 5 Star | 135 |

Average customer rating:

## 3.7 / 5

:contentReference[oaicite:12]{index=12}

---

## Common Themes in Customer Feedback

### Positive Themes
- Fast delivery
- Helpful customer support
- High product quality
- Good packaging

### Negative Themes
- Product quality concerns
- Performance issues
- Unclear instructions
- Value-for-money concerns

Examples extracted from customer reviews included:

- "Excellent product, highly recommend!"
- "Customer support was very helpful."
- "Product did not meet my expectations."
- "Not worth the money."

:contentReference[oaicite:13]{index=13}

---

# Dashboard Features

The Power BI dashboard provides interactive insights across four business areas:

## Executive Overview
- Conversion Rate
- Customer Rating
- Views
- Clicks
- Likes

## Conversion Analytics
- Product conversion rates
- Funnel drop-offs
- Monthly conversion trends

## Engagement Analytics
- Views by content type
- Product popularity
- Monthly engagement patterns

## Customer Review Analytics
- Rating distributions
- Sentiment trends
- Review exploration

The dashboard supports filtering by:

- Product
- Month
- Year
- Country
- Sentiment Category

:contentReference[oaicite:14]{index=14}

---

# Key Visualizations

## Conversion Funnel
![Conversion Funnel](images/conversion_funnel.png)

## Product Conversion Analysis
![Conversion by Product](images/conversion_by_product.png)

## Customer Engagement Trends
![Engagement Trends](images/engagement_trends.png)

## Sentiment Distribution
![Sentiment Distribution](images/sentiment_distribution.png)

## Dashboard Overview
![Dashboard Overview](images/dashboard_overview.png)

---

# Technologies Used

## SQL
- Joins
- Window Functions
- Common Table Expressions (CTEs)
- Aggregations
- Funnel Analysis

## Python
- Pandas
- Text Processing
- Sentiment Analysis

## Power BI
- DAX Measures
- Interactive Dashboards
- KPI Monitoring
- Funnel Visualizations

---

# Skills Demonstrated

- Product Analytics
- Marketing Analytics
- Customer Journey Analytics
- Conversion Funnel Analysis
- SQL Analytics
- Sentiment Analysis
- Dashboard Development
- Data Storytelling
- Business Intelligence

---

# Recommendations

## Improve Low-Converting Products
Investigate pricing, product positioning, and customer expectations for products exhibiting low conversion rates.

## Reduce Funnel Drop-Off
Optimize checkout flow and improve customer experience at high-abandonment stages.

## Improve Marketing Efficiency
Allocate budget toward channels and content generating the highest engagement and conversion performance.

## Leverage Customer Feedback
Address recurring customer complaints and incorporate insights into product and service improvements.

## Expand High Performing Campaigns
Scale campaigns and content types that consistently produce strong engagement metrics.

---

# Future Improvements

Potential future extensions include:

- Customer Lifetime Value prediction
- Churn prediction
- Customer Segmentation
- Recommendation Systems
- Cohort Analysis
- A/B Testing Framework

---

# Author

**Mridul Kumar**

Delhi Technological University (DTU)  
Production and Industrial Engineering

Interested in:
- Business Analytics
- Product Analytics
- Data Analytics
- Consulting
