# Finance-Analysis-Dashboard-PowerBI
Interactive Power BI Finance Dashboard featuring Power Query data cleaning, Star Schema modeling, DAX measures, YoY analysis, KPI reporting, and Drill-through for transaction-level insights.
## Dashboard Preview

### Executive Dashboard

![Executive Dashboard]<img width="776" height="427" alt="Screenshot 2026-07-09 172701" src="https://github.com/user-attachments/assets/b4391336-f226-4149-977f-994d2b2ec85f" />


### Transaction Detail Page

![Transaction Detail]<img width="716" height="427" alt="Screenshot 2026-07-09 172722" src="https://github.com/user-attachments/assets/780eff43-88dc-4034-9b06-a5ee99407cf7" />


### Data Model

![Star Schema]<img width="944" height="536" alt="Screenshot 2026-07-09 172741" src="https://github.com/user-attachments/assets/9ea535ed-2835-48ae-b6b7-b4be6aa6a4a8" />  

📌 Project Overview  

The Finance Analysis Dashboard is an interactive Power BI report designed to analyze financial transactions and provide actionable business insights. The dashboard enables users to monitor key financial KPIs, analyze customer segments, evaluate transaction performance, and drill down into individual transaction details for deeper investigation.

This project demonstrates the complete Power BI development workflow, including data cleaning, data modeling, DAX calculations, dashboard design, and interactive reporting.  

🎯 Business Problem

Financial organizations generate thousands of transactions every day. Decision-makers need a centralized dashboard to:  

-> Monitor financial performance  
-> Track revenue and transaction growth  
-> Analyze customer segments  
-> Identify high-performing states  
-> Monitor transaction success rates  
-> Investigate individual transactions  
-> Compare Year-over-Year performance  

This dashboard helps management make data-driven business decisions through interactive visualizations.  

🛠️ Tools & Technologies  

-> Power BI Desktop  
-> Power Query  
-> DAX (Data Analysis Expressions)  
-> Star Schema Data Modeling  

Modeling  
📂 Project Workflow  

1️⃣ Data Cleaning (Power Query)  
-> Performed data transformation using Power Query:  
-> Removed duplicate records  
-> Handled missing values  
-> Corrected data types  
-> Renamed columns  
-> Standardized categorical values  
-> Prepared clean data for analysis  

2️⃣ Data Modeling  
Created a Star Schema to improve report performance and maintainability.  

Fact Table  
-> Financial Transactions  

Dimension Tables  
-> Date Table  
-> Customer Table  

Relationships were created between:  
Date Table → Transactions  
Customer Table → Transactions  

This model supports efficient filtering and accurate DAX calculations.  

3️⃣ DAX Measures  
Created custom DAX measures for key business metrics:  

-> Total Amount  
-> Total Transactions  
-> Total Fees  
-> Total Tax  
-> Average Transaction  
-> Year-over-Year (YoY) Growth  
-> YoY Growth Percentage  

These measures provide dynamic insights based on report filters.  

4️⃣ Dashboard Features  

✔ Executive KPI Cards  

-> Total Amount  
-> Total Transactions  
-> Total Fees  
-> Average Transaction  
-> Total Tax  

✔ Interactive Slicers  

-> Year  
-> Occupation  
-> Merchant Category  
-> Metrics  

✔ Visualizations  

-> Monthly Transaction Trend  
-> Transaction Status Analysis  
-> Customer Segment Analysis  
-> Gender Analysis  
-> State-wise Transaction Amount  
-> Transaction Type Summary  

✔ Detail Analysis Page  

Implemented Drill-through functionality, allowing users to navigate from summary visuals to detailed transaction-level information.  

📈 Key Business Insights  

The dashboard helps answer important business questions such as:  

1. Which customer segment generates the highest revenue?  
2. Which states contribute the most transaction amount?  
3. What is the Year-over-Year financial performance?  
4. Which transaction types generate the highest fees?  
5. What percentage of transactions are successful?  
6. Which months perform best throughout the year?  
7. Which individual transactions require investigation?  

💼 Business Value  

This dashboard supports decision-making by helping management:  
-> Identify high-performing regions  
-> Focus on profitable customer segments  
-> Improve transaction success rates  
-> Monitor revenue growth  
-> Track financial KPIs  
-> Optimize operational performance  
-> Investigate transaction-level details using Drill-through  

🚀 Skills Demonstrated  
-> Data Cleaning using Power Query  
-> Data Modeling (Star Schema)  
-> Relationship Management  
-> DAX Measure Development  
-> Time Intelligence (YoY Analysis)  
-> KPI Design  
-> Interactive Dashboard Design  
-> Drill-through Navigation  
-> Business Intelligence Reporting  
-> Data Visualization Best Practices  



