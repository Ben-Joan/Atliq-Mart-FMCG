# Atliq Mart FMCG
![Atliq Mart](https://github.com/Ben-Joan/Atliq-Mart-FMCG/blob/main/Img/AdobeStock_604881201-scaled.jpeg)

## Introduction
AtliQ Mart is a growing FMCG manufacturer headquartered in Gujarat, India. It is currently operational in three cities Surat, Ahmedabad and Vadodra. They want to expand to other metro/tier1 cities in the next 2 years.
This analysis develops a dynamic dashoard to for Atliq Mart to monitor its metrics against target as wel identify where major challenges is being experienced thereby implementing strategy for managing it. 

## Problem Statement
AtliQ Mart is currently facing a problem where a few key customers did not extend the annual contract due to service issues. It is speculated that some of the essential products were either not delivered on time or not delivered in full over a continued period, which could have resulted in bad customer service. 
Management wants to fix this issue before expanding to other cities, therefore requested the supply chain analytics team to track the service performance by measuring ’On time’, ‘In Full’  and OnTime in full (OTIF) % delivery service level for all the customers on a daily basis so that they can respond swiftly to these issues.


## Strategy Implemented 🎯 
To perform this task, the process and skills demonstrated or involved are:

- **Data Modeling**: Importing the different CSV files containing the data and creating a data model from scratch to link the tables 
    
- **Power Query**: Cleaning and transforming data, ensuring use of appropriate data types and creating calculated columns to aid in providing more insights
    
- **Dax Measures**: Creating Measures & calculations using DAX to track requested key metrics, like;
  - a. DOT%: Delivery on Time
  - b. DIF%: Delivery in Full
  - c. OTIF%: On Time In Full
  - d. Total orders and Total Orderlines
  - e. LIFR%: Line Fill Rate
  - f. VOFR%: Volume Fill Rate
        
- **Business Intelligence**: Leveraging Power BI to develop a dynamic dashboard that helps Executives continously track and monitor business performance.

 
## Datasource & Dashboard 📈
The data, metrics list, domain concepts, business stakeholder meetings can all be sourced on [Data](https://github.com/Ben-Joan/Atliq-Mart-FMCG/tree/main/Data)

The Dashboard contains two major pages
   - Performance Summary

   - Product Analysis
     
Check out the power bi [dashboard](https://app.powerbi.com/view?r=eyJrIjoiOTBhYWVhZGItZDdhMC00NmZiLWI2Y2UtNDA3N2I3NjVjOGYyIiwidCI6IjczMDc4ZWNkLWYzM2UtNDQxYy05ODYyLWVhZDdjNjFhNGU4MiJ9)

## Insights 💡
#### Overall Performance 
- All major KPIs i.e OT%, IF% and OTIF% for tracking delivery performance is significantly below target.
- The order level KPIs i.e LIFR% and VOFR% are are relatively better but LIFR% requires further improvement for better customer satisfaction.
- There is no significant increase in all KPIs overtime, indicating stagnancy and no changes to improve Performance.


### City Level Performance 
- In full delivery % is best in **Ahmedabad - 54%** and worse in **Vadodara - 52%**
- On time delivery % is best in **Surat - 61%** and worse in **Vadodara - 58%**
- On time in full delivery % is best in **Surat- 30%** and worse in **Vadodara - 28%**
This Implies that Vadodara requires the most attention for improving delivery.

### Customer Insights 
The key customers that contribute to +53% of our orders are:
- Lotus Mart, Acclaimed stores, Vijay stores, Rel fresh, Coolblue and Propel Mart.
- Due to the poor service level, the most likely customers not renewing annual contract are: Lotus mart, Acclaimed stores and Coolblue because they experienced the most impact of poor customer service.

Therefore, the supply chain director should focus on addressing this key areas to improve business delivery operations 

