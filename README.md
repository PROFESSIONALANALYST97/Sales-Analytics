# 🚀 Hybrid Data Projects (Full Stack Analytics)

### [A/B Test Analysis: Website Conversion Optimization](./AB_Testing_Analysis/Portfolio_Project_2_A_B_TEST_ANALYSIS.ipynb)
**Tools:** SQL, Python (Pandas, Scipy), Tableau
* **Business Problem:** Evaluated the statistical significance of website changes to drive data-informed product decisions.
* **Technical Execution:** Combined SQL data extraction with Python-based hypothesis testing (P-Value & Confidence Intervals).
* **Visualization:** Developed an interactive Tableau dashboard to track conversion uplifts across user segments (Organic, Direct, etc.).
* **Key Finding:** Concluded that observed differences were not statistically significant, preventing an ineffective global rollout.

### [E-commerce Business Performance Analysis](./Ecommerce_Performance_Audit/Potoflio_Project_Analysis_1.ipynb)
**Tools:** SQL (BigQuery), Python, Tableau
* **Business Problem:** A holistic audit of international sales dynamics, user behavior, and traffic source efficiency.
* **Technical Execution:** Performed complex data cleaning and behavioral analysis using Python, integrated with BigQuery data marts.
* **Visualization:** Built a high-level Tableau dashboard featuring geographical maps, sparklines, and smart navigation filters.
* **Key Finding:** Identified that while email newsletters drive traffic, they don't correlate with higher transaction values, suggesting a need for offer optimization.

---
# 📊 Data Analytics Portfolio: SQL & Python
## Business Intelligence, Data Transformation & Predictive Insights

---

# 🐍 Featured Python Project
### [Global Sales & Logistics Analytics](./python%20project/Global_Sales_Analytics.ipynb)
**Comprehensive End-to-End Sales Performance & Logistics Study**

* **Data Integration:** Merged relational datasets (Sales, Products, Countries) into a master analytical DataFrame.
* **Logistics Insights:** Conducted Lead-Time analysis to identify shipping efficiency and its correlation with profitability.
* **Visualization:** Created advanced time-series and behavioral plots (Seaborn/Matplotlib) to track monthly dynamics and weekly sales patterns.
* **Exploratory Data Analysis:** Full EDA process including data cleaning, anomaly detection, and KPI calculation.

---

# 🗄️ Main SQL Project: Capstone Project
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
