## Problem Statement

A small company, Axon, specializing in classic car retail, is facing challenges in managing and analyzing their sales data. The sales team struggles to make sense of the data without a centralized system for data management and analysis. Consequently, management lacks accurate and up-to-date sales reports, affecting decision-making processes.

To address this, Axon has decided to implement a Business Intelligence (BI) tool, opting for Microsoft PowerBI and SQL, to effectively manage and analyze sales data.

## Project Goals

The goal of this project is to design and implement a BI solution using PowerBI and SQL, enabling Axon to:

1. Import and integrate data from a MySQL database into PowerBI.
2. Clean and transform the data for analysis readiness.
3. Build interactive dashboards and reports in PowerBI for data interpretation by the sales team and management.
4. Utilize SQL for advanced analytics and insights extraction.
5. Provide real-time dashboard and report access to management for data-driven decision-making.

The solution aims to be user-friendly, enhancing the company’s data management and decision-making processes.

## Database Description

The MySQL sample database schema consists of 8 tables:

- `Customers`: Stores customer data.
- `Products`: A list of scale model cars.
- `ProductLines`: Product line categories.
- `Orders`: Sales orders placed by customers.
- `OrderDetails`: Sales order line items for each order.
- `Payments`: Customer payments.
- `Employees`: Employee information and organizational structure.
- `Offices`: Sales office data.

## Approach and Methodology

1. **Data Source Utilization:** Employ the provided MySQL database as the data source.
2. **Data Extraction and Cleaning:** Extract data from sources, clean it for analysis readiness, including tasks like removing duplicates and handling missing values.
3. **Data Loading into PowerBI:** Load the cleaned data into a centralized database.
4. **Dashboard and Report Design:** Utilize PowerBI for interactive dashboard and report creation, providing insights and information to management.
5. **Advanced Analytics with SQL:** Perform advanced analytics on sales data for deeper insights.
6. **Solution Deployment:** Deploy the BI solution to the sales team and management, ensuring user-friendliness.

## Tools Required

- [Microsoft PowerBI](https://powerbi.microsoft.com/en-us/)
- [SQL (MySQL)](https://www.mysql.com/)

## References and Inspirations

- [Sales Dashboard Case Study](https://www.netsolutions.com/casestudy-ecom-dashboard)
- [SQL Sales Analysis Article](https://medium.com/swlh/data-anlysis-project-for-retail-sales-performance-report-using-sql-6ef1d4443712)

## Deliverables

1. Documented report in Word or PDF format.
2. SQL files.
3. Power BI report.
