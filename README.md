# Power BI Enterprise Sales Analytics

## **Project Overview**
This end-to-end Power BI project focuses on building an automated sales insights dashboard with Power BI Service integration. The project includes data transformation, modeling, DAX calculations, dashboard visualization, and Power BI Service features such as scheduled refresh, Row-Level Security (RLS), and workspace management.

## **Features**
- Automated data ingestion from multiple sources
- Robust data transformation and modeling
- Advanced DAX calculations for sales performance analysis
- Interactive Power BI dashboard for sales insights
- Implementation of Power BI Service features:
  - **Scheduled Data Refresh** for up-to-date reporting
  - **Row-Level Security (RLS)** for access control
  - **Workspaces & App Publishing** for organization-wide sharing
  
## **Data Sources**
The project utilizes multiple data sources for comprehensive sales analysis:
- **Sales Data** (Folder containing yearly CSV files)
- **Product Data** (Database)
- **Geography, Categories, SubCategories, and SalesRep Data** (Excel)

## **Data Processing & Modeling**
- **Sales Data Consolidation**: Created a mechanism to dynamically load yearly sales data dynamically, ensuring seamless handling of missing or new files.
- **Data Transformations**: Cleaned and formatted data, including splitting location fields and ensuring correct data types for geo-mapping.
- **Key Creation**: Generated unique keys to establish robust relationships between tables.
- **Data Model**: Developed a star schema model integrating all tables with a Sales table.

![Data Model](Data%20model.png)


## **DAX Calculations**
Implemented key metrics for sales insights:
- **Total Revenue** = Units Sold × Retail Price
- **Total Cost** = Units Sold × Standard Cost
- **Gross Profit** = Total Revenue - Total Cost
- **Gross Profit MoM Growth %**
- **Average Sales Per Day**
- **Quarter-over-Quarter (QoQ) Growth Analysis**
- **Product Sales Trend Analysis** (Increase/Drop Analysis)

## **Power BI Visualization**
Designed an interactive one-page sales dashboard, ensuring:
- Dynamic filters for deep insights
- Geo-mapping for sales distribution
- Time-series visualizations (MoM, QoQ growth trends)
- Product-wise breakdown analysis

![Power BI Report](PowerrBI%20report.png)

## **Power BI Service Deployment**
The project extends beyond local reporting to Power BI Service for:
- **Scheduled Refresh**: Ensuring real-time data updates
- **Row-Level Security (RLS)**: Restricting data access by user roles
- **Publishing & Sharing**: Creating workspaces for collaboration

## **Conclusion**
This project demonstrates the complete data-to-insights workflow, incorporating Power BI’s advanced features to enhance enterprise reporting efficiency. The automation ensures a scalable and dynamic analytics solution for sales performance tracking and decision-making.

