# Project Introduction:
The UK Supply Chain Data Migration and Reporting Initiative focused on enhancing the client's data reporting system to support real-time decision-making for a leading global commodity price data provider. The project aimed to modernize the reporting infrastructure using a Lake House architecture, integrating various data sources and employing Power BI for dynamic visualizations.

## Challenges Addressed:

Performance Bottlenecks: Inefficiencies in data retrieval and report generation due to large datasets and complex Power BI queries.
Real-Time Data Access: The need for timely data updates to support accurate decision-making.
Data Security: Implementing robust security measures and controlled access.
Scalability: Handling large volumes of diverse data sources.

## Technologies Used:

* **Databricks:** For ETL processes and data transformation.
* **Azure SQL Server:** As the central database for data storage and management.
* **Power BI:** For reporting and visualization.
* **Python & SQL:** For data manipulation and ETL scripting.

##  Achievements:
* **Improved Performance:** Enhanced report load times and data retrieval through various optimization techniques.
* **Real-Time Data Integration:** Enabled near real-time data updates for timely insights.
* **Enhanced Security:** Implemented row-level security and Azure Active Directory for data protection.
* **Efficient Reporting:** Delivered faster and more responsive Power BI reports.


##  Detail Solution:
**1. Design and Development:**
   * Built and optimized ETL pipelines with Databricks to extract, transform, and load data into Azure SQL Server.
   * Data Transformation: Utilized Databricks for data cleaning, transformation, and integration, preparing data for efficient reporting.
     
**2. Database Design:**
   * Schema Implementation: Created star and snowflake schemas in Azure SQL Server to streamline query performance and facilitate faster data retrieval.

**3. Power BI Optimization:**
   * Data Model Enhancement: Developed well-structured data models using star and snowflake schemas to optimize performance.
   * Power Query Editor: Cleaned and transformed data before loading into Power BI, removing unnecessary columns and applying filters.
   * Direct Query Mode: Utilized Direct Query for large datasets to avoid in-memory data loading issues.
   * DAX Optimization: Improved DAX calculations by minimizing complex functions and using calculated columns judiciously.
   * Incremental Refresh: Applied incremental refresh techniques to load only new or modified data, enhancing performance for large datasets.
   *  Composite Models: Used Power BI’s composite models to integrate real-time and historical data effectively.
   * Row-Level Security: Implemented row-level security (RLS) to manage user-specific data access.
   * Real-Time Data Solutions: Leveraged Azure Stream Analytics for real-time data streaming and Azure Functions for automated data pushes.

**4.Security and Access Control:**
   * Row-Level Security: Enforced RLS in Power BI to restrict data visibility based on user roles.
   * Authentication: Integrated Azure Active Directory for secure authentication and authorization.
