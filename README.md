# Atliq Hardware Real-Time Sales Insights Dashboard

This Power BI project is tailored for Atliq Hardware, a computer hardware business facing challenges in an ever-changing market. The Sales Director has initiated this data analysis project to gain real-time sales insights and make informed business decisions.

## Overview

Atliq Hardware operates in a dynamically changing market, and to navigate through the challenges, the Sales Director has decided to invest in a data analysis project. The goal is to build a Power BI dashboard that provides real-time sales insights, enabling proactive decision-making.

## Project Phases

1. **Project Initiation Meeting**:
   - The Sales Director will collaborate with the IT Director and the Data Analytics team to define the purpose and success criteria using the AIMS (Aspirations, Ideas, Methods, Success) grid.

2. **Data Discovery**:
   - The Data Analytics team will work closely with the sales team, who manage the MySQL database containing sales records. Power BI will be integrated directly with this database to extract the required information for analysis.

3. **Data Integration**:
   - The MySQL database owned by the sales team contains crucial sales transaction, customer, product, and market information. This data will be analyzed and integrated with Power BI for further processing.

  ## Data Integration

The MySQL database owned by the sales team is central to this project. It contains the following tables:

1. **Customer Table**:
   - Columns: Customer Code, Name, Customer Type

2. **Market Table**:
   - Columns: Market Code, Market Name, Zone

3. **Product Table**:
   - Columns: Product Code, Product Type

4. **Transaction Table**:
   - Columns: Product Code, Customer Code, Region Code, Transactions

These tables will be seamlessly integrated with Power BI for streamlined analysis.

5. **ETL Process**:
   - Within Power BI, the team will perform Extract, Transform, Load (ETL) operations, also known as data munging or data wrangling. This process involves currency normalization, handling invalid values, and ensuring the data is ready for dashboard creation.

## ETL Process

Within Power BI, the ETL process will be conducted to ensure data quality and readiness for dashboard creation. This involves tasks such as currency normalization and handling of invalid values to prepare the data for insightful visualizations.

## Key Insights
- **Revenue Trends**:
  - Revenue has shown a declining trend over the years. It peaked in 2018 and has been decreasing since then. This indicates the need for targeted strategies to reverse this trend.
![image](https://github.com/ASDsashi/PowerBI-Atliq-Hardwares/assets/71587160/452ed50d-8baf-4332-b13a-f7b54800ba87)

- **Electricalsara Stores **:
  - Electricalsara Stores is a key contributor to the overall revenue of Atliq Hardware
![image](https://github.com/ASDsashi/PowerBI-Atliq-Hardwares/assets/71587160/5c5ecee2-5bc1-40f9-adc2-c64bca037063)

- **Revenues from Electricalsara Stores Clients**:
  - Revenues are declining. It's recommended to engage more with these clients and explore strategies to increase sales, such as offering special discounts.
![image](https://github.com/ASDsashi/PowerBI-Atliq-Hardwares/assets/71587160/5fba1b55-b26d-4e19-b52b-8bd97d46b3d9)

These insights provide a comprehensive overview of the overall sales of Atliq Hardware

## Dashboard Preview
![image](https://github.com/ASDsashi/PowerBI-Atliq-Hardwares/assets/71587160/736eb21a-ffe5-4fb3-b6af-2e84229f4b7d)
![image](https://github.com/ASDsashi/PowerBI-Atliq-Hardwares/assets/71587160/f153ef1a-0282-4d30-88c1-784c288eb7f4)

