# Project Description

## Case 2 is a data analysis project focused on analyzing order and return data to provide insights into sales, profitability, and return patterns. Using datasets containing order details and return statuses, the project leverages PostgreSQL for data processing, Power BI for visualization, and a Word report for stakeholder communication. The purpose is to identify high-return product categories, customer segments, and regions to inform business decisions and reduce return rates.

## Technology Stack
### PostgreSQL: Database for storing and querying order and return data.
### Power BI: Visualization tool for creating interactive dashboards.
### Microsoft Word: For generating stakeholder-friendly reports.

## Key Features
### Data Analysis: SQL queries to calculate return rates, sales, and profits by product category, customer segment, and region.
### Interactive Dashboard: Power BI dashboard with KPIs (total orders, returns, sales, profit), charts, and maps.
### Stakeholder Reporting: Professional Word report summarizing findings and recommendations.
### Targeted Queries: Analysis of specific orders (e.g., order IDs 69, 134, 135, 230, 324) to identify returning customers.
## Run the Project
### Set Up Database:
### Start PostgreSQL and create a database: CREATE DATABASE study;
### Run the schema script: psql -d study -f database/create_tables.sql
### Load CSV data:\copy order_status FROM 'Order_Status.csv' DELIMITER '\t' CSV;
\copy order_details FROM 'KMS Sql Case Study.csv' DELIMITER '\t' CSV HEADER;
### Run SQL Queries:
### Execute analysis queries: psql -d case2 -f database/case_study_queries.sql
### Run specific order ID query: psql -d case2 -f database/customer_returned_orders.sql
## Launch Power BI Dashboard:
### Open dashboard/case_study_2_dashboard.pbit in Power BI Desktop.
### Connect to the PostgreSQL database (case2) and load order_details and order_status tables.
### Save as a .pbix file for further customization.

![Screenshot (8)](https://github.com/user-attachments/assets/7e93b9fc-c03a-4299-99ff-9fb1317a8023)


![Screenshot (14)](https://github.com/user-attachments/assets/d4b5e1ff-b05f-45a5-b303-521c147381c3)

![Screenshot (15)](https://github.com/user-attachments/assets/79a1de83-1eb2-4de4-9919-8a26548bda5b)

![Screenshot (16)](https://github.com/user-attachments/assets/fc59fd5d-1b7c-4422-a779-1db306c81f34)

![Screenshot (17)](https://github.com/user-attachments/assets/1a490fd3-95cc-436e-a0fc-1fc27428bdc4)


Linkedin: www.linkedin.com/in/paschal-ikenna-395a1a229

Email: pikenna71@gmail.com

Contact:+2347035349699



