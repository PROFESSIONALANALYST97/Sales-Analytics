# 📊 SQL Data Analytics Portfolio
## Business Intelligence & Data Transformation

---

# 🏆 Main Project: Capstone Project
### Comprehensive Email Marketing & User Engagement Data Mart

This is my final project, where I designed an advanced data transformation pipeline that integrates account activity, geographic data, and marketing funnel metrics.

**Key Technical Achievements:**
* **Complex Data Architecture:** Integrated 7+ tables using multiple **CTEs** and `UNION ALL` to create a unified Fact Table.
* **Performance Ranking:** Utilized `DENSE_RANK()` and the `QUALIFY` clause to identify top-performing markets.
* **Funnel Analysis:** Implemented end-to-end tracking of the email lifecycle (Sent → Opened → Visited).
* **Data Precision:** Handled missing geographic data and used `DATE_ADD` for accurate event-time normalization.

---

# 📁 Project Catalog

## 📈 Revenue & Email Performance Analytics
*This project consists of two comprehensive performance analyses:*

* **Part 1: Email Market Share:** Calculated monthly message volumes and their percentage share relative to the total monthly volume using `PARTITION BY`.
* **Part 2: Actual Revenue vs. Predictive Modeling:** A complex comparison of real-world sales data against predictive models. It features **Running Totals** (`SUM OVER`) to track cumulative performance day-over-day.

## 🌍 Global Market Performance & User Verification
* **Goal:** Cross-sectional analysis of revenue and user verification status across continents.
* **Techniques:** Implemented `FULL OUTER JOIN` with `COALESCE` and calculated global market share using window functions.

## 🕒 Email Campaign Recency Analysis
* **Goal:** Identifying the 10 most recent days of email interactions for specific accounts.
* **Techniques:** Used `DENSE_RANK()` for recency ranking and complex joins to bridge marketing events with session logs.

## 📍 Initial Customer Engagement Tracking
* **Goal:** Pinpointing the exact date of the very first interaction for every account (First-Touch Analysis).
* **Techniques:** Leveraged the `MIN()` window function and date interval calculations for precise onboarding tracking.

---

## 🛠️ Technical Skills & Tools
* **Language:** SQL (Google BigQuery / Standard SQL)
* **Advanced Techniques:** Window Functions, Common Table Expressions (CTEs), Conditional Aggregations, Data Normalization.
* **Platform:** Google Cloud Platform (GCP).
