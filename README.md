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
## Dashboard
- <a href="https://github.com/SourabhaSekharRout/Retail-data-analysis/blob/main/Retail%20Data%20Analysis%20(Power%20BI).pbix">Dashboard (Power BI)</a>
![Screenshot 2024-11-21 124135](https://github.com/user-attachments/assets/4783bfde-787f-471b-b59d-ddb87df39bcf)
![Screenshot 2024-11-21 124148](https://github.com/user-attachments/assets/034bb8c1-cded-47bc-8ded-1e1cdcfa5aba)
![Screenshot 2024-11-21 124202](https://github.com/user-attachments/assets/290f1e34-d3bd-400a-8733-8671fa0ae05f)
![Screenshot 2024-11-21 124214](https://github.com/user-attachments/assets/628601ed-bdbb-416f-8852-0d22a3e61878)
