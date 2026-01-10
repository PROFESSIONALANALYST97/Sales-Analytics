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
*This comprehensive project combines email volume metrics with financial forecasting.*

* **Market Share Analysis:** Calculated monthly email volumes per account and their percentage share relative to total volume using `PARTITION BY`.
* **Revenue vs. Prediction:** Integrated actual sales data with predictive models using `UNION ALL`.
* **Cumulative Metrics:** Implemented **Running Totals** (`SUM OVER`) to evaluate how actual revenue matches predicted values day-over-day.

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
* **Advanced Techniques:** Window Functions, Common Table Expressions (CTEs), Conditional Aggregations, Data Normalization, Table Unions.
* **Environment:** Google Cloud Platform (GCP).
