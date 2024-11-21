# Retail-data-analysis
## Objective
Integrate and analyze retail data from multiple sources by building a unified data model, enhancing it with DAX formulas, and creating a dashboard to provide insights and trends.
## Overview
This project involves cleaning and connecting data from four files, creating calculated fields for advanced analysis, and visualizing key metrics like revenue, cancellations, and performance across various dimensions like time, geography, and product categories.
## Process
1. Data Loading
- Import all four retail data files into the data model, ensuring the headers contain accurate field names for each file.
2. Data Cleansing
- Handle errors and missing values.
- Remove/drop irrelevant records such as rows with missing Zone or CityTier values.
3. Relationship Management
- Establish relationships between common columns in the tables to create a unified data model.
4. Data Enhancement with DAX
- Use DAX (Data Analysis Expressions) to perform calculations and create new fields like Net_Units, OrderDayOfWeek, and OrderWeekStart to enhance the dataset.
5. Update Relationships
- Review and refine relationships in the data model to ensure all tables are correctly connected for seamless analysis.
6. Analysis and Reporting
- Perform various analyses, including total revenue, cancellations, and transactions. Segment the data by dimensions such as:
  - Month, Week, and Weekday
  - Product Group
  - City, Zone, and City Tier
7. Dashboard Creation
- Develop a comprehensive, interactive dashboard to visualize the results of the analysis, enabling stakeholders to derive actionable insights.
