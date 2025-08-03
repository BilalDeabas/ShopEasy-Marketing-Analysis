# 📊 ShopEasy – Complete Marketing Analytics & Business Intelligence

## 🧠 Project Overview

**Business Case:**
ShopEasy, a growing e-commerce platform, is facing challenges with declining customer engagement and conversion rates despite significant marketing investments. This project aims to analyze marketing performance, customer behavior, and feedback to uncover actionable insights.

**Tech Stack:**
SQL | Python (VADER) | Power BI

---

## 🧩 Business Problem

* 📉 Declining **Customer Engagement**
* 🚫 Lower **Conversion Rates**
* 💸 Rising **Marketing Expenses** with minimal ROI
* 🗣️ Lack of structured **Customer Feedback Analysis**

---

## 🗣 Stakeholder Communication

Two key stakeholders reached out:

* **Marketing Manager:** Concerned about campaign ROI and engagement metrics.
* **Customer Experience Manager:** Interested in analyzing customer sentiment and reviews to improve satisfaction and conversions.

---

## 🎯 Project Goals

| Objective                      | Approach                     | Output                       |
| ------------------------------ | ---------------------------- | ---------------------------- |
| 📈 Increase Conversion Rates   | Funnel drop-off analysis     | Actionable recommendations   |
| 🤝 Enhance Customer Engagement | Content performance analysis | Optimized content strategy   |
| 🌟 Improve Feedback Scores     | Sentiment & review analysis  | Product/service improvements |

---

## 🧾 Data Sources

* `customer_journey`
* `engagement_data`
* `customer_reviews`
* `customers`, `geography`, `products`

---

## 🔍 Phase 1: Data Extraction & Cleaning (SQL)

SQL scripts were used for:

* Categorizing products by price
* Joining customer & geographic data
* Standardizing engagement types
* Cleaning and deduplicating customer journey records
* Prepping reviews for sentiment analysis

> Techniques used: `JOIN`, `CASE`, `COALESCE`, `REPLACE`, window functions

---

## 🤖 Phase 2: Sentiment Analysis (Python)

Using **NLTK's VADER**, review texts were analyzed and classified:

* **Sentiment Score** (compound)
* **Sentiment Bucket** (Strongly Negative → Strongly Positive)
* **Sentiment Category** (combined with star ratings for nuance)

> Output exported as CSV for Power BI integration

---

## 📊 Phase 3: Power BI Dashboard

### ✅ Key Features

* 🔄 SQL Server & Python CSV integration
* ⭐ Star schema modeling with `fact_` and `dim_` tables
* 📆 Custom DAX calendar for time intelligence
* 📐 Measures for KPIs (Conversion, Ratings, Clicks, Engagement)
* 🧩 Visuals: Cards, funnels, line/bar charts, sentiment matrices

### 📈 Dashboard Pages

1. **Overview** – KPIs, product performance, rating trends
2. **Conversion Funnel** – Drop-off stages, product-level conversion
3. **Engagement Analysis** – Content type ROI, views/clicks breakdown
4. **Customer Reviews & Sentiment** – Ratings vs. sentiment, trend charts, heatmaps

---

## 📌 Key Insights

* **Top Converting Products:** Ski Boots (150% in Jan), Hockey Stick (15.46%)
* **Engagement Drop-Off:** Decline after July; blogs outperform other formats
* **Feedback Analysis:** Avg. rating = 3.69; 275/549 reviews were positive

---

## 💡 Final Recommendations

### 🔄 Conversion Optimization

* Promote top products in peak months (e.g., Jan, Sept)
* Redesign journey stages with high drop-offs

### 📣 Engagement Boost

* Use interactive media & better CTAs
* Focus on underperforming months (Sep–Dec)

### 🌟 Feedback Improvement

* Prioritize products < 3.5 stars for quality improvements
* Actively address mixed/negative feedback loops

---

## 📌 Live Preview


