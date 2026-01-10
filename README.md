# 📊 SQL Data Analytics Portfolio
## Business Intelligence & Data Transformation

---

# 🏆 Main Project: Email Campaign Performance & Market Share Analysis
### Comprehensive Marketing & User Engagement Data Mart

This is my **Capstone Project**, where I designed an advanced data transformation pipeline that integrates account activity, geographic data, and marketing funnel metrics into a single analytical view.

**Key Technical Achievements:**
* **Complex Data Architecture:** Integrated 7+ tables using multiple **CTEs** and `UNION ALL` to create a unified Fact Table.
* **Performance Ranking:** Utilized `DENSE_RANK()` and the `QUALIFY` clause to identify top-performing markets based on account volume.
* **Funnel Performance Tracking:** Integrated tracking for the entire email lifecycle (Sent → Opened → Visited).
* **Data Precision:** Handled missing geographic data and used `DATE_ADD` for accurate event-time normalization.

---

# 📁 Other Analytical Projects

## 📈 Revenue & Predictive Modeling Comparison
* **Goal:** A complex comparison of real-world sales data against predictive models to evaluate forecasting accuracy.
* **Key Skills:** Implemented **Running Totals** (`SUM OVER`) and calculated performance ratios to track cumulative revenue day-over-day.

## 🌍 Global Market Performance & User Verification Analysis
* **Goal:** Cross-sectional analysis of revenue distribution and user verification status across continents.
* **Key Skills:** Used `FULL OUTER JOIN` with `COALESCE` and calculated global market share using window functions.

## 🕒 Email Campaign Recency Analysis
* **Goal:** Identifying the 10 most recent days of email interactions for specific accounts.
* **Key Skills:** Recency ranking using `DENSE_RANK()` and complex joins between marketing events and session logs.

## 📍 Initial Customer Engagement Tracking
* **Goal:** Pinpointing the exact date of the very first interaction for every account (First-Touch Analysis).
* **Key Skills:** Leveraged the `MIN()` window function and date interval calculations for precise onboarding tracking.

---

## 🛠️ Technical Skills & Tools
* **Language:** SQL (Google BigQuery / Standard SQL)
* **Advanced Techniques:** Window Functions, Common Table Expressions (CTEs), Conditional Aggregations, Data Normalization.
* **Platform:** Google Cloud Platform (GCP).
