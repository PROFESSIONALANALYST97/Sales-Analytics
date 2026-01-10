# 📊 SQL Data Analytics Portfolio
## Business Intelligence & Marketing Insights

---

# 🏆 Main Project: Capstone Project
### Comprehensive Email Marketing & User Engagement Data Mart

This is my primary project, where I designed a complex data transformation pipeline to consolidate account activity, geographic data, and email funnel metrics into a single analytical view.

**Key Technical Achievements:**
* **Hybrid Data Architecture:** Integrated 7+ tables using multiple **CTEs** and `UNION ALL` to build unified data structures.
* **Performance Ranking:** Implemented `DENSE_RANK()` and `QUALIFY` to identify top-performing markets based on account volume.
* **Funnel Performance Tracking:** Integrated tracking for the entire email lifecycle (Sent → Opened → Visited).
* **Advanced Data Cleaning:** Handled missing geographic data and used `DATE_ADD` for accurate event-time normalization.

---

# 📁 Other Analytical Projects

## 📈 Actual Revenue vs. Predictive Modeling Comparison
* **Goal:** Combining actual sales data with predictive revenue models to calculate cumulative performance.
* **Key Skills:** Cumulative calculations (Running Totals) using `SUM() OVER(ORDER BY ...)` and accuracy ratio analysis.

## 🌍 Global Market Performance & User Verification Analysis
* **Goal:** Comprehensive cross-sectional analysis of revenue and user verification across continents.
* **Key Skills:** `FULL OUTER JOIN` with `COALESCE` and market share calculations using global window functions.

## 📧 Email Campaign Performance & Market Share Analysis
* **Goal:** Calculating monthly volume of sent messages per account and their percentage share in the total monthly volume.
* **Key Skills:** Time-series aggregation with `DATE_TRUNC` and proportional analysis using `PARTITION BY`.

## 🕒 Email Campaign Recency Analysis
* **Goal:** Identifying the 10 most recent days on which emails were sent to specific accounts.
* **Key Skills:** Recency ranking using `DENSE_RANK()` and complex joins between marketing events and session logs.

## 📍 Initial Customer Engagement Tracking
* **Goal:** Identifying the exact date of the very first email interaction for every account.
* **Key Skills:** First-touch analysis using `MIN()` window function and date interval calculations.

---

## 🛠️ Technical Skills & Tools
* **Language:** SQL (Google BigQuery / Standard SQL)
* **Advanced Techniques:** Window Functions, Common Table Expressions (CTEs), Conditional Aggregations, Data Normalization.
* **Environment:** Google Cloud Platform (GCP).
