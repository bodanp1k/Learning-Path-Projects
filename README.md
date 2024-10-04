## Adwenture Works Sales Analysis & Customer Segmentation
This project involves creating an Excel dashboard for Adventure Works, aimed at analyzing sales performance and customer segmentation from 2021 to 2023.

### Goals:
Sales Insights: Provide an overall view of sales trends, key products, and high-performing regions or categories.
Customer Segmentation: Identify customer segments that are driving sales and uncover patterns based on demographics, such as gender or marital status, to assist in targeted marketing and strategy planning.

### Project Overview: 
**Data Import and Transformation** (via Power Query):

**Sales Data Consolidation**: Sales data for the years 2021, 2022, and 2023 were imported into Power Query, where the data was cleaned, combined, and transformed into a usable format for analysis.
[Date Dimension Creation](https://github.com/bodanp1k/Learning-Path-Projects/blob/Sales-Performance-Dashboard-%7C-Microsoft-Excel-(Pivot-Tables)/M%20Language%20for%20Date%20Dimension%20Table.pdf): Using M-language, a date dimension table was created to support time-based analysis, ensuring accurate connections between sales data and time periods.
Data Model Creation:

**Dimension Tables**: Various dimension tables, such as Dim_Customers, Dim_Products, Dim_Territories, and Dim_Calendar, were linked to the central fact table containing sales and return data (Fact_Sales_2021_... and Fact_Returns). These dimension tables provided additional context for the fact data.

**Relationships**: Relationships were established between the fact and dimension tables, creating a star schema to facilitate easy and accurate analysis of sales performance and customer data.
Analysis Using Pivot Tables:

**Pivot Tables**: Once the data model was set up, pivot tables were created to slice and dice the data. These pivot tables allowed for the analysis of total sales, gross profit, top products, sales by gender, marital status, homeownership, and more.

**[DAX (Data Analysis Expressions) calculations](https://github.com/bodanp1k/Learning-Path-Projects/blob/Sales-Performance-Dashboard-%7C-Microsoft-Excel-(Pivot-Tables)/DAX%20Measures.pdf)** were utilized in the project to perform advanced analysis and derive key metrics, such as calculating total sales, gross profit, gross profit percentage


### Final Dashboard

![dash](https://i.imgur.com/7F5FFLC.png)

### Data Model

![model](https://i.imgur.com/gRBgwWo.png)
