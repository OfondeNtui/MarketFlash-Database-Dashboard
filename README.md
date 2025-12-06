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





## Dashboard Overview

<img width="1426" height="732" alt="Screenshot 2025-12-05 at 20 01 51" src="https://github.com/user-attachments/assets/8a5f32c2-240b-4af7-99ec-7375fe1052f0" />


## Results & Key Findings
Analyzed campaign performance across 12 marketing channels, revealing total outcomes of 50.4M views, 5.05M likes, 2.61M clicks, and a 19.56% conversion rate.
Built an interactive Tableau dashboard enabling quick comparisons across channels, executives, locations, and clients.

### Recommendations 
. TikTok, Facebook, and YouTube deliver the highest conversions, while Email shows the weakest acquisition performance.

. Budget efficiency is low—the expense vs. conversion analysis shows a weak correlation, indicating overspending on low-performing campaigns.

. Canada, Australia, and Western U.S. regions achieve the strongest conversion rates, highlighting clear geographic opportunities.

. Executive performance varies significantly, signaling the need for standardized best practices and targeted support.

. Top clients (e.g., White Ltd, Lopez PLC) show strong engagement, while several smaller clients present retention risks.

### Conclusions
The MarketFlash analysis demonstrates strong overall engagement but highlights clear optimization opportunities. The company can significantly improve campaign ROI by reallocating budget to high-performing channels, focusing on top-converting regions, and strengthening consistency across executive teams. This dashboard provides a scalable, data-driven foundation for more informed marketing decisions and future performance growth.


