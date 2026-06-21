# Gopolang Changa - Data Analyst & BI Analyst

![Profile](https://github.com/GopolangChanga) <!-- Replace with your GitHub profile pic link -->

**Results-driven Business Intelligence Analyst** with 4+ years of experience in the financial services and insurance sector. 

Skilled in turning complex data into actionable insights using **Power BI**, **Qlik Sense**, **Snowflake SQL**, **Python**, and **ETL** processes.

- 📍 Cape Town, South Africa
- 📧 gopolangchanga123@gmail.com
- 📱 075 366 8656
- [LinkedIn](https://www.linkedin.com/in/gopolang-changa-01aa2811b/) | [Portfolio](link-to-live-powerbi-if-any)

---

## 🛠 Skills

- **BI Tools**: Power BI, Qlik Sense, Qlik SaaS, NPrinting, Commotion Dash
- **Databases**: Snowflake SQL, T-SQL, MySQL
- **Languages**: SQL, Python (pandas, APIs), DAX
- **Cloud & ETL**: Azure, SSIS, Star/Snowflake Schema, Data Warehousing
- **Other**: Advanced Excel, Power Automate, Agile

---

## 📊 Featured Projects

### 1. Sales Daily Product Report — Power BI Dashboard

-A daily operational sales dashboard built on the AdventureWorks dataset, designed for sales managers, category managers, and demand planners who need a quick, accurate read on daily performance. 
-All totals and rankings have been independently validated against raw SQL queries run directly against the source tables.

<img width="1286" height="722" alt="image" src="https://github.com/user-attachments/assets/1c78a611-514d-4bab-93b9-1dfdd7ff87d3" />

#### 📌 Project Summary

This report answers four core operational questions for a given day:

-What did we sell, and how does that compare to recent performance?
-Which products are driving order volume vs. revenue?
-What's the trend over the last 30 days — is today normal, good, or bad?
-What's the average price per unit across top products?

#### 🛠️ Tools Used

-Power BI Desktop — report design, DAX measures, data modeling
-SQL Server (T-SQL) — Creating an ETL process and validation SQL queries
-Adventureworks 2025 database — sample relational dataset (fact tables and dimensions for snowflake schema)

#### ✨ Key Features

-KPI Cards — Sales, Daily % Change, Orders at a glance
-30-Day Trend Line Chart — daily sales over the trailing 30 days, giving context to the current day's performance
-Top 10 Products by Order Volume — table including Orders and Price per Unit
-Top 10 Products by Sales — clustred bar chart ranking products by sale contribution
-Daily % Change Indicator — visual up/down arrow comparing today's sales to the prior day
-Report Date Indicator - visual showing reporting date (visual dynamic)
-Logo - Dummy logo

#### ✅ Data Validation

Every key total and ranking shown in the Power BI report was cross-checked against equivalent SQL queries run directly on the underlying fact/dimension tables — not just trusted from the visual layer. This included:

-Total daily sales and order counts
-Top 10 products by order volume and by sales amount
-Price-per-unit calculations (Sales ÷ Orders) per product

See the /sql folder for the validation queries and the /sql/README.md for notes on what each one checks.

#### 📐 Key DAX Measures
Measures follow a consistent naming convention: [Metric] - [Context/Qualifier] (e.g., Sales - Latest Reporting Date, Sales - Last 30 Days). Full measure list and logic documented in /dax/measures.md.

Highlights:

-Sales - Latest Reporting Date — total sales filtered to the most recent reporting date
-Sales - Last 30 Days — rolling 30-day sales total, used to drive the trend chart
-Orders - Latest Reporting Date — total Orders filtered to the most recent reporting date
-Average Order Value — Sales ÷ Orders, surfaced as a KPI


📄 License
This project uses Microsoft's publicly available Adventureworks 2025 database sample dataset for educational/portfolio purposes.


### 2. 
- ...

---

## 📫 Let's Connect
Open to **Data Analyst**, **BI Analyst**, and **Reporting Analyst** opportunities in Cape Town or Remote.

---

**Last Updated**: June 2026
