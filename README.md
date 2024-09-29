# Credit_Card_Financial_Report
Developed an interactive Credit Card Transaction and Customer Analytics Dashboard using Power BI. The dashboard provides week-over-week insights on revenue, transactions, and customer demographics. Utilized DAX queries for key measures and improved dashboard design for a clean, user-friendly experience.

**Objective:**

The objective of this project was to develop a comprehensive weekly credit card dashboard to provide real-time insights into key performance metrics. This allows stakeholders to monitor and analyze credit card transactions and customer behaviors effectively. The main goal was to enhance decision-making by presenting data on revenue, transaction counts, and customer segmentation using Power BI.

---

**Steps Taken:**

1. **Data Importation:**
   - Imported CSV files into a SQL database.
   - Created necessary tables and organized the data.

2. **Data Processing:**
   - Cleaned and processed data using Power BI.
   - Created necessary DAX queries and measures, such as:
     - Calculating **Total Revenue** (`Revenue = annual_fees + total_trans_amt + interest_earned`).
     - Generated measures for **Current Week Revenue** and **Previous Week Revenue** to facilitate week-over-week comparisons.
     - Created calculated columns such as **AgeGroup** (based on customer ages) and **IncomeGroup** (segmentation based on income).

3. **DAX Queries:**
   - Developed measures for sorting weeks correctly, creating a new column `week_num2` for accurate week sorting as the original week column had text and numbers.
   - Used DAX queries to compute year-over-year and week-over-week trends in key metrics (such as revenue, transactions, and customer growth).

4. **Dashboard Creation:**
   - Designed a visually cleaner and more user-friendly dashboard in Power BI. 
   - Added filters for selecting weeks, quarters, genders, card categories, and income groups.
   - Created visualizations showing:
     - Quarter-wise revenue and transaction trends.
     - Revenue by customer segments such as card categories, educational level, job type, and gender.
     - Comparative revenue figures for different card types (Blue, Silver, Gold, etc.).

---

**Insights:**

1. **Week-over-Week Performance:**
   - Revenue increased by 28.8% in Week 53.
   - Transaction volume and total amount also showed significant increases.
   - The customer count expanded during this period, indicating higher engagement.

2. **Overall Trends:**
   - Year-to-date, total revenue reached **55M**, with total interest earned of **7.84M**.
   - Transaction count surged to **656K** transactions, with total transaction volume amounting to **45M**.
   - **Male customers** contributed more to the total revenue (31M) compared to female customers (26M).
   - The **Blue** and **Silver** credit card categories contributed to 93% of overall transactions.
   - States like **TX, NY, CA, FL** contributed to 68% of total revenues.
   - The overall customer **activation rate** stood at 57.5%, while the delinquency rate was 6.06%.

---

**Significant Changes Made:**

I made several enhancements to the dashboard, which greatly improved its appearance and usability:
- Simplified the layout, making it visually cleaner and more accessible for stakeholders.
- Improved the navigation and filter options, allowing users to analyze data by week, quarter, gender, and more.
- Organized the metrics in a way that prioritizes important information, such as total revenue, interest earned, and transaction counts.
- Added additional insights related to customer demographics and income groups, providing a deeper understanding of customer segments.
