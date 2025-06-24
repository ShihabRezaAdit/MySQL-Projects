## SQL Projects  ![icons8-mysql-logo-48](https://github.com/swaapnaa/SQL-PROJECTS/assets/149737403/95180ab6-019c-4ba1-9165-e9449cb95614)

These examples showcase my command of SQL and my ability to translate complex datasets into clear, data-driven insights. They demonstrate my skills in querying, analysis, and presenting results.

---

## Analyzing Employee Trends

**Dataset:** [Analyzing Employee Trends.csv](Analyzing%20Employee%20Trends.sql)

**Overview:**
A deep dive into HR data to reveal workforce patterns. The table includes employee demographics, departmental roles, satisfaction scores, attrition status, and more.

**Key Contributions:**

* Conducted initial data quality checks and exploratory queries
* Queried employee counts, average metrics, and distributions by department, age group, and education level
* Identified top job roles and compared satisfaction across teams
* Calculated attrition rates by age band to highlight groups at higher risk
* Investigated correlations between attrition and factors such as age, education, and job satisfaction
* Compared segment-level aggregates to overall metrics to spot anomalies
* Ranked performers by satisfaction and attrition indicators
* Employed JOINs, GROUP BY, HAVING, and CASE statements for nuanced analysis
* Presented findings in concise tables and summary reports for leadership

---

## Exploring Trends in the Automotive Industry

**Dataset:** [Exploring Trends in Automotive Industry.csv](Exploring%20Trends%20in%20Automotive%20Industry.sql)

**Overview:**
An in-depth assessment of car sales records to understand pricing dynamics, model reliability, and market trends. The data covers make, model, price history, mileage, transmission type, fuel type, and ownership.

**Key Contributions:**

* Performed dataset validation and exploratory analysis
* Analyzed average sale prices by transmission type, fuel category, and ownership status
* Identified high-mileage models to gauge durability and maintenance costs
* Measured price variability across models to inform competitive pricing
* Detected outliers by comparing model metrics against overall averages
* Created rolling averages and year-over-year price trend analyses
* Computed moving averages for smoother forecasting
* Summarized total mileage by transmission for maintenance planning
* Ranked car models by price and tracked historical performance of top sellers
* Utilized CTEs, WINDOW functions, and advanced JOINs for complex analytics
* Compiled visual summaries for stakeholders to guide pricing and inventory decisions

---

## Call Center Data Cleaning & Analysis

**Dataset:** [call\_center.csv](call%20center.sql)

**Overview:**
Prepared and analyzed call center records to evaluate volume trends, customer satisfaction, and service efficiency. Data resides in a MySQL table within the `call_centerdata` schema.

**Key Contributions:**

* Imported call center data into MySQL and standardized date formats (YYYY-MM-DD)
* Cleansed the dataset by converting empty CSAT scores to NULL
* Generated summary statistics: total rows, columns, and data completeness
* Explored distinct values for sentiment, city, and call center location
* Calculated call counts by weekday and identified peak call durations
* Assessed customer satisfaction by computing min, max, and adjusted average CSAT scores
* Evaluated response time distributions to rank call center performance
* Delivered cleaned datasets and summary reports for operations teams

---

## About SQL

SQL (Structured Query Language) is the standard language for relational database management. Essential features include:

* **CRUD Operations:** Insert, select, update, and delete records
* **Joins:** Merge data across multiple tables
* **Aggregate Functions:** Compute sums, counts, averages, and more
* **Subqueries:** Nest queries for complex logic
* **Stored Procedures:** Encapsulate reusable logic
* **Window Functions:** Perform rankings, running totals, and advanced analytics

*Tools used: Microsoft SQL Server Management Studio.*

---

## Usage Instructions

1. Install a SQL environment (e.g., SQL Server Express).
2. Import the provided `.sql` scripts into your database.
3. Adjust table names and schemas as needed for your setup.
4. Run queries and review outputs to reproduce the analyses.
