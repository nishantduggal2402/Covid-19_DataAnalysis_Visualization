🌍 COVID-19 Data Analysis & Insights  

## 📌 Project  

Performed an end-to-end analysis of global COVID-19 data using SQL and Tableau to uncover key insights related to infection trends, mortality impact, and vaccination progress across countries and continents.


## 🎯 Business Requirement  

To build a data analytics solution that provides meaningful insights into:

- Infection spread across countries  
- Death rates and severity of impact  
- Vaccination progress and coverage  
- Regional and global comparisons  

This supports better understanding of pandemic patterns and enables data-driven public health decision-making.


## ⚙️ Tools & Technologies  

- MySQL  
- PostgreSQL  
- SQL (CTEs, Joins, Aggregations, Window Functions)  
- Tableau (Data Visualization & Dashboarding)  


## 📂 Dataset  

The dataset consists of two CSV files (~85k rows each):

- coviddeaths4.csv → Cases, deaths, population, locations  
- covidvaccinations4.csv → Vaccination data across countries  


## 🔍 SQL Techniques Used  

- Joins (combining deaths & vaccination datasets)  
- CTEs (Common Table Expressions)  
- Aggregations (SUM, COUNT, AVG)  
- Window Functions  
- Data Cleaning (handling nulls, type conversion)  
- Group By & Filtering  


## 📊 Tableau Features Used  

- Data modeling using logical (relationships) and physical (joins) layers  
- Calculated fields and FIXED LOD expressions for KPI computation  
- Interactive dashboards with maps, filters, and trend visualizations  


## 📈 Key Insights  

- Europe recorded the highest death rate relative to population, followed by North and South America, while Africa reported the lowest.  
- Countries like the USA, France, and Spain showed the highest infection rates, whereas Finland and Norway had significantly lower infection penetration.  
- The USA and Israel led in vaccination coverage, reflecting strong healthcare infrastructure and efficient rollout strategies.  
- Globally, approximately 2% of infected individuals died, highlighting the large-scale impact of the pandemic.  
- Significant disparities across regions indicate inequality in healthcare access and pandemic response effectiveness.  


## 📁 Project Structure  

- data.zip → File containing both COVID-19 CSV datasets  
- Covid19-Analysis.sql → SQL script for data cleaning and analysis  
- Covid19_Insights.twbx → Tableau dashboard file  
- Image_Dashboard.png → Dashboard preview image  


## 📊 Tableau Dashboard  

The Tableau dashboard provides interactive insights on:

- Global infection trends  
- Death rates across regions  
- Vaccination progress by country  
- Comparative continent-level analysis  


## ✅ Conclusion  

This project demonstrates how SQL and Tableau can be integrated to transform large-scale datasets into meaningful insights. It highlights the importance of data analytics in understanding global crises and supports informed decision-making in public health and policy.
