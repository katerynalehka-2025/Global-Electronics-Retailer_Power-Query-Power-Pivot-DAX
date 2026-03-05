# Global-Electronics-Retailer_Power-Query-Power-Pivot-DAX

Maven Electronics Sales Performance Report
Project Overview
This project involved developing a comprehensive, interactive business intelligence report to analyze the sales performance of Maven Electronics. By moving from raw data ingestion to an interactive dashboard, I built a scalable data model capable of tracking key performance metrics, regional trends, and delivery efficiency.

Key Technical Achievements
Data Ingestion & Transformation (ETL): Connected to and cleaned multiple disparate datasets (Sales, Products, Stores, Customers, and Exchange Rates). Performed data cleaning operations including text capitalization, removing unnecessary columns, and engineering new features like Customer Age and Age Range.

Data Modeling: Built a robust Star Schema by establishing one-to-many relationships between the central Sales fact table and various dimension tables. Successfully managed a complex relationship with the Exchange Rates table by creating a custom ExchangeKey to facilitate currency conversion.

Feature Engineering:

Created a dedicated Calendar table to enable time-intelligence analysis (Year, Quarter, Month, Week).

Developed a dedicated Measures Table to house DAX calculations, including:

Total Orders & Revenue: Tracking volume and financial performance.

Average Order Value (AOV): Analyzing customer spending behavior across demographics.

Average Delivery Time: Measuring operational efficiency and logistics performance.

Visualization & Reporting: Designed an interactive executive report featuring KPI cards for high-level metrics and integrated charts (Line/Bar) to visualize time-series and categorical performance. Included global slicers for Store and Year to allow for rapid, filter-driven insights.

Tools & Skills Demonstrated
Tools: Power BI (Power Query, DAX, Data Modeling, Data Visualization).

Skills: ETL Processes, Relational Data Modeling (Star Schema), Business Intelligence, Time-Intelligence DAX, Exploratory Data Analysis (EDA).

Strategic Insights
This project provided the leadership team with the ability to:

Identify high-revenue product categories and top-performing stores.

Monitor operational health by tracking delivery times over time.

Segment customer behavior by age ranges to better tailor marketing strategies.
