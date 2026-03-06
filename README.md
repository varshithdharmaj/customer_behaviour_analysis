 Customer Behaviour Analysis

 Overview
This project is an end‑to‑end **data** analytics case study focused on understanding customer purchasing behaviour for a retail business. It follows a complete workflow used in real analytics teams: data extraction, cleaning, exploratory data analysis (EDA), SQL-based business queries, interactive dashboarding in Power BI.

Key objectives:
- Identify high‑value customers and key revenue drivers.
- Understand product performance across segments and time.
- Generate actionable insights and recommendations for business stakeholders.

 Dataset
- Source: Retail customer transactions dataset (orders, customers, products, payments).  
- Scope: Includes customer demographics, order details, product information, order value, payment type, and timestamps.  
- Granularity: Transaction-level data with one row per order line item.  

You can find the raw data in the `data/` folder and the processed data in the `outputs/` or `cleaned_data/` folder (update with your actual paths).

 Tools
- Python (pandas, numpy, matplotlib/seaborn, SQLAlchemy) for data loading, cleaning, and EDA.  
- SQL (PostgreSQL/MySQL/SQL Server) for analytical queries and business logic.  
- Power BI for building interactive dashboards and KPI views. [github](https://github.com/Pooja-2891/customer_behaviour_data)


 Project Steps
1. Problem Understanding  
   - Defined the business problem: analyse customer behaviour to improve marketing, retention, and revenue. [github](https://github.com/samruddhi3012/Customer-Behavior-Analysis)

2. Data Loading (Python)  
   - Imported the dataset using pandas.  
   - Performed initial inspection of columns, data types, missing values, and basic statistics.

3. Data Cleaning & Preparation  
   - Handled missing and inconsistent values.  
   - Fixed data types (dates, numeric fields, categorical variables).  
   - Created derived fields such as total order value, average spend per customer, and order frequency.

4. Exploratory Data Analysis (EDA)  
   - Analysed customer demographics, order patterns, and product performance.  
   - Generated visualisations for revenue trends, top products, customer segments, payment methods, and other key metrics. [github](https://github.com/samruddhi3012/Customer-Behavior-Analysis)

5. SQL Analysis  
   - Loaded cleaned data into a relational database (PostgreSQL/MySQL/SQL Server).  
   - Wrote SQL queries to answer business questions, for example:  
     - Top‑spending customers and their characteristics.  
     - Monthly/quarterly revenue trends.  
     - Best‑selling products and categories.  
     - Customer retention and repeat purchase behaviour. [youtube](https://www.youtube.com/watch?v=lHR1_j8DYFA)

6. Power BI Dashboard  
   - Connected Power BI to the SQL database / cleaned CSV output.  
   - Built interactive visuals to monitor KPIs and drill down into customer and product performance. [github](https://github.com/Pooja-2891/customer_behaviour_data)

7. Reporting & Presentation 
   - Summarised findings, insights, and recommendations in a structured report.  
   - Created an AI‑assisted presentation in Gamma to present the story to stakeholders, using key visuals from Python, SQL, and Power BI.

Dashboard
The Power BI report provides:  
- High‑level KPI page (total revenue, orders, average order value, active customers).  
- Customer analysis page (segments, demographics, CLV, repeat rate).  
- Product and category analysis page (top sellers, margins, cross‑sell opportunities).  
- Time series page (monthly trends, seasonality, campaign impact).  

Exported screenshots or the `.pbix` file can be found in the `dashboard/` folder (update with your actual path). [github](https://github.com/Pooja-2891/customer_behaviour_data)

Results and Insights
Some of the key outcomes from the analysis (adapt with your actual numbers):  
- Identified top customer segments contributing the majority of revenue and their preferred product categories. [github](https://github.com/sadiqimam/customer-behavior-analysis/blob/main/README.md)
- Uncovered under‑performing products and periods with declining sales, informing promotional strategies. [github](https://github.com/arko-saha/Customer-behavior-analysis-in-a-hotel-franchise-management-system/blob/main/README.md)
- Quantified the impact of discounts, payment methods, and subscription status on order value and retention. [github](https://github.com/sadiqimam/customer-behavior-analysis/blob/main/README.md)
- Delivered clear recommendations to optimise marketing spend, improve cross‑selling, and increase customer lifetime value. [github](https://github.com/samruddhi3012/Customer-Behavior-Analysis)

How to Run

 1. Clone the Repository
```bash
git clone https://github.com/varshithdharmaj/customer_behaviour_analysis.git
cd customer_behaviour_analysis
```

 2. Set Up Python Environment
```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

 3. Run the Python Scripts
- Update file paths in the notebook or script if needed.  
- Execute the EDA/cleaning notebook (e.g., `notebooks/customer_analysis.ipynb`) or the main script to generate cleaned data and intermediate outputs.

 4. Configure the Database
- Create a database in PostgreSQL/MySQL/SQL Server.  
- Update connection details in the config section of the Python script or `.env` file.  
- Run the ETL/loader script to push cleaned tables into the database. [youtube](https://www.youtube.com/watch?v=lHR1_j8DYFA)

 5. Open the Power BI Dashboard
- Open the `.pbix` file in Power BI Desktop.  
- Refresh data source connections to point to your database or local CSVs.  

