## MarketFlash-Database-Dashboard
### Table Of Content
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Preparation](#data-preparatioin)
- [SQL Queries](#sql-queries)
- [Dashboard Overview](#dashboard-overview)
- [Results and Findings](#results-and-findings)

## Project Overview
The goal of this project is to design and implement a robust database architecture and an interactive analytics dashboard for MarketFlash, a rapidly growing marketing company. This solution replaces the company’s existing spreadsheet-based workflow with a scalable, structured database and delivers actionable insights through a Tableau dashboard.
By modernizing data management and visualization, the project enables MarketFlash to streamline operations, improve data accuracy, and support data-driven decision-making.

## Data Sources
Marketing data: The primary dataset used for this analysis is the "sales_data.csv" file, containing detailed information about each sale made by the company.

## Tools
1. Excel - Data Cleaning
 
2. Beekeeper - For Database code
 
3. Tableau - Creating dashbaord

## Data Cleaning/Preparation
In the initial data preparation phase, we performed the following tasks:

1. Data loading and inspection.
 
2. Handling missing values.
   
3. Data cleaning and formatting.

## 🧪 Database Validation: Join Integrity Test
To ensure that the relational database was structured correctly and that key relationships worked as expected, a join test was performed across the Campaigns, Clients, and Platforms tables.
The following SQL query validates that:

. Each campaign is linked to the correct client

. Each campaign is associated with the correct platform

. Foreign key relationships return accurate joined records

SELECT
    c.Campaign_Name,   
    cl.Company_Name,   
    p.Platform_Name    
FROM
    Campaigns c       
JOIN
    Clients cl ON c.Client_ID = cl.Client_ID 
JOIN
    Platforms p ON c.Platform_ID = p.Platform_ID 
ORDER BY
    cl.Company_Name,   
    c.Campaign_Name;



