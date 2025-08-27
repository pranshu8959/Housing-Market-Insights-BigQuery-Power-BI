# 🏠 Housing Market Analytics – BigQuery & Power BI

## 📌 Project Overview
This end-to-end business intelligence project demonstrates how to connect **Google BigQuery** to **Power BI**, transform housing data using SQL and Power Query Editor, and build interactive dashboards with DAX-driven KPIs. It simulates a real-world scenario where housing transactions are analyzed for pricing trends, regional performance, and macroeconomic impact.



## 🧰 Tools & Technologies
- **Google BigQuery** – SQL-based data warehouse for ingestion, transformation, and profiling  
- **Power BI Desktop & Service** – Visualization, DAX measures, and report publishing  
- **Power Query Editor** – Data cleaning, column profiling, and null handling  
- **DAX** – Custom KPIs including YOY growth, median price change, offer-to-SQM ratio, and more  


## 📊 Key Features
- ✅ Data loaded from CSV into BigQuery and queried using SQL  
- ✅ Power BI connected via Import Mode for performance  
- ✅ Null handling and column profiling in Power Query  
- ✅ Custom DAX measures for:
  - Year-on-Year Sales Growth  
  - Median Sales Price Change  
  - Units Sold (Latest Quarter)  
  - Last 12-Month Sales  
  - Offer Price Calculation  
  - Offer-to-SQM Ratio  
- ✅ Visuals include:
  - Line chart, scatter plot, donut chart, key influencers  
  - Clustered bar chart, combo chart, slicers for dynamic filtering  
- ✅ Report published to Power BI Service and organized into workspaces  



## 📈 Business Insights Delivered
- 🔍 Sales performance by region, house type, and sales type  
- 📉 Inflation, interest rate, and yield impact on housing prices  
- 🧠 Key influencers driving purchase price (e.g., age of property)  
- 📐 Offer price vs purchase price trends and SQM-based pricing  
- 🏘️ House type analysis with average pricing and macro indicators  



## 🧠 Learning Outcomes
- Real-world simulation of BI workflow: data ingestion → transformation → modeling → storytelling  
- Hands-on experience with BigQuery SQL and Power BI DAX  
- Dashboard design with business relevance and recruiter appeal  
- Workspace management and report publishing in Power BI Service  



## 🗂️ Report Pages
1. **House Market Overview**  
   - YOY Sales Growth by Sales Type  
   - Offer vs Purchase Price Scatter Plot  
   - Median Sales Price Change by Region  
   - Units Sold (Latest Quarter)  
   - Last 12-Month Sales  

2. **Sales Performance**  
   - Sales by Region  
   - Total YTD Sales  
   - Donut Chart: Avg Price per SQM by Region  
   - Key Influencer: Purchase Price vs Age  
   - Offer-to-SQM Ratio by Sales Type  

3. **House Type Analysis**  
   - Avg Offer vs Purchase Price by House Type  
   - Avg Inflation / Interest / Yield by House Type  
   - Combo Chart: Avg Area vs Price per SQM  
   - Slicers: Area, City, Sales Type, Region  



## 🚀 Publishing Workflow
- Report published to **Power BI Service**  
- Organized into **Housing Project Workspace**  
- Includes semantic model and multiple report pages  
- Supports dynamic filtering and interactivity  



## 📎 Additional Notes
- Measures organized in a dedicated **Measures Table** for clarity  
- Visuals formatted with consistent styling, color codes, and layout  
- Null values handled using domain-specific replacements (e.g., inflation rate, city name)  
- SQL transformations performed in BigQuery before Power BI ingestion  




