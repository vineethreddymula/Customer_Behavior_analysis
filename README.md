# Customer_Behavior_analysis
 Data analytics project showcasing customer behavior analysis using python, sql and power Bi.
This project demonstrates a complete data analytics pipeline, covering:
Data ingestion and preprocessing in Python
Exploratory Data Analysis (EDA)
Data cleaning and transformation
SQL-based analysis across PostgreSQL, MySQL, and SQL Server
Business intelligence dashboard development in Power BI
Insight reporting and executive presentation creation
The objective was to transform raw structured data into actionable insights using a production-style workflow aligned with industry best practices.

Dataset

The dataset consists of structured tabular data containing:
Numerical metrics (KPIs, financial measures, counts)
Categorical attributes (segments, categories, regions)
Time-based records
Relational fields suitable for joins and aggregations
Data quality checks and validation were performed prior to analysis.

Tech Stack
Programming & Analysis
Python 3.x
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
Databases
PostgreSQL
MySQL
Microsoft SQL Server
Business Intelligence
Power BI (Data modeling, DAX, dashboard design)
Presentation
Gamma (Executive slide deck generation)

Project Workflow
1️⃣ Data Ingestion

Loaded dataset using Pandas
Inspected schema, data types, and null distributions
Validated primary fields and integrity constraints

2️⃣ Exploratory Data Analysis (EDA)

Performed:

Descriptive statistics
Distribution analysis
Correlation analysis
Outlier detection
Time-series trend analysis
Segment-level comparisons
Used Matplotlib and Seaborn for visual exploration.

3️⃣ Data Cleaning & Transformation

Handled missing values (imputation/removal strategy based on context)
Removed duplicates
Standardized categorical values
Converted data types
Engineered new calculated features
Normalized date formats
Cleaned dataset exported for SQL ingestion.

4️⃣ SQL Analysis (Multi-Database)

The processed dataset was loaded into:
PostgreSQL
MySQL
SQL Server

Implemented:
Aggregations (SUM, AVG, COUNT)
GROUP BY analysis
Window functions
JOIN operations
Subqueries and CTEs
KPI calculations
Performance segmentation queries
Validated cross-database query compatibility where applicable.
SQL scripts are stored in /sql.

5️⃣ Data Modeling & Power BI Dashboard

In Power BI:
Imported data via database connection
Designed star-schema style relationships
Built calculated measures using DAX
Created KPI cards and dynamic visuals
Implemented slicers and drill-through
Built executive summary and deep-dive pages
Dashboard emphasizes usability, clarity, and decision-support.

6️⃣ Reporting & Presentation

Structured analytical report documenting methodology and findings
Executive-ready presentation created in Gamma
Included insights, KPIs, trends, and business recommendations
Dashboard Features
KPI summary panel
Time-series performance trends
Category/segment breakdown
Interactive filters (slicers)
Drill-down capabilities
