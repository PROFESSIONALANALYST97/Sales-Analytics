# 📊 SQL Data Analytics Portfolio
## Business Intelligence & Data Transformation

---

# 🏆 Main Project: Capstone Project
**Comprehensive Marketing & User Engagement Data Mart**

This is my primary project, where I designed a complex data transformation pipeline that integrates account activity, geographic data, and marketing funnel metrics.

**Key Technical Achievements:**
* **Hybrid Data Architecture:** Integrated 7+ tables using multiple **CTEs** and `UNION ALL` to build a unified analytical dataset.
* **Performance Ranking:** Utilized `DENSE_RANK()` and the `QUALIFY` clause to identify top-performing markets based on user volume and engagement.
* **Funnel Analysis:** Implemented tracking for the entire email lifecycle (Sent → Opened → Visited).
* **Data Integrity:** Handled missing geographic records and used `DATE_ADD` with `INTERVAL` for precise event-time normalization.

---

# 📁 Other Analytical Projects

## 📧 Email Campaign Performance & Market Share Analysis
* **Goal:** Analyzing monthly email volume per account and calculating their percentage share in the total market.
* **Key Skills:** Time-series aggregation using `DATE_TRUNC` and proportional analysis with window functions (`PARTITION BY`).

## 📈 Revenue & Predictive Modeling Comparison
* **Goal:** Comparing actual sales data against predictive models to evaluate forecasting accuracy.
* **Key Skills:** Cumulative calculations (Running Totals) using `SUM() OVER(ORDER BY ...)` and accuracy ratio analysis.

## 🌍 Global Market Performance & User Verification
* **Goal:** A cross-sectional analysis of revenue and user verification status across continents.
* **Key Skills:** Implemented `FULL OUTER JOIN` with `COALESCE` to merge financial metrics with account verification data.

## 🕒 Email Campaign Recency Analysis
* **Goal:** Identifying the 10 most recent days of email interactions for specific accounts.
* **Key Skills:** Recency ranking using `DENSE_RANK()` and complex joins between marketing events and session logs.

## 📍 Initial Customer Engagement Tracking
* **Goal:** Pinpointing the exact date of the very first interaction for every account.
* **Key Skills:** First-touch analysis using `MIN()` window function and date interval calculations.

---

## 🛠️ Technical Skills & Tools
* **Language:** SQL (Google BigQuery / Standard SQL)
* **Advanced Techniques:** Window Functions, Common Table Expressions (CTEs), Conditional Aggregations, Data Normalization.
* **Environment:** Google Cloud Platform (GCP).
