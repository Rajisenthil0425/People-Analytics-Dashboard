# People Analytics Dashboard

## Project Overview
An end-to-end People Analytics solution built using SQL Server and Power BI, 
demonstrating how complex HR data can be transformed into clear, actionable 
insight for both technical and non-technical audiences. Features advanced 
visualisations including scatter plots, treemaps, funnel charts and custom 
tooltips with Row Level Security for data governance.

## Tools Used
- SQL Server Management Studio (SSMS) — database design and data preparation
- Power BI Desktop — dashboard development and data visualisation
- DAX — custom measures and calculations
- Power Query — data transformation and modelling

## Database Structure
- **Database:** People_Analytics
- **Schema:** Constellation (one dimension, multiple fact tables)
- **Tables:** Employees, Absence, Salary, Recruitment, Training, Performance
- **Views:** Six views created to support dashboard reporting

## Dashboard Pages
1. **Home** — Navigation and headline KPIs
2. **Workforce Overview** — Headcount, gender, regional treemap and department analysis
3. **Absence and Wellbeing** — Absence trends benchmarked against CIPD average of 5.6 days
4. **Salary and Pay Equity** — Gender pay gap analysis, salary distribution and salary vs performance scatter plot
5. **Recruitment** — Time to hire benchmarked against financial services standard of 30 days, hiring trends and source analysis
6. **Training and Compliance** — Training completion against 95% target, mandatory vs optional breakdown
7. **Performance** — Performance ratings by department, grade and gender
8. **Employee Detail** — Drill through page for individual employee insight

## Key Features
- Row Level Security (RLS) — North and South regional roles
- Custom Tooltips — Salary, absence and performance on hover
- Drill Through — Employee level detail from Workforce Overview
- Page Navigator — Seamless navigation across all pages
- Scatter Plot — Salary vs Performance Score correlation analysis
- Treemap Visuals — Regional and categorical distribution
- Funnel Chart — Recruitment source analysis
- Line Chart — Hiring trends by month
- Column Chart — Performance score by job grade
- CIPD Benchmarking — Industry standard comparisons built into visuals
- Consistent navy background theme across all pages

## Key DAX Measures
- Active Employees
- Training Completion %
- Most Common Absence Reason
- Gender Pay Gap %
- Avg Performance Score
- Outstanding Employees
- Needs Improvement

## Key Insights
- Absence at 2.55 days — below CIPD benchmark of 5.6 days (healthy workforce)
- Time to hire at 45 days — above 30 day benchmark (recruitment process needs review)
- Training completion at 70% — below 95% target (compliance risk)
- Near zero gender pay gap — strong pay equity across the organisation
- Claims department lowest performance score — combined with highest absence suggests engagement risk
