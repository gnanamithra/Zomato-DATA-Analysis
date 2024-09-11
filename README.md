Data Sourcing: The "Raw Data" sheet contains the original dataset, which we imported from various sources like Zomato's API or CSV files. This raw data was preprocessed and cleaned for further analysis in Excel.

Data Cleaning and Transformation: In Excel, we performed data cleaning using functions like VLOOKUP, IFERROR, and TEXT to format and prepare the data. This was further organized in the "Final Data Set" sheet, making it suitable for analysis and database insertion.

Data Integration in MySQL: The cleaned data from Excel was exported to MySQL, where tables were created to store the structured information. SQL queries were used to join, filter, and aggregate the data to prepare insights for reporting.

KPI Calculation: Each sheet from KPI 1 to KPI 10 represents different Key Performance Indicators (KPIs). These include metrics such as average order value, customer satisfaction scores, total revenue, and more, which were calculated using complex Excel formulas and SQL queries.

Power BI Report Creation: In Power BI, the data from the "Final Data Set" was imported to create interactive visualizations. Power BI’s DAX functions were used to further calculate metrics such as customer growth trends and location-based performance.

Tableau Dashboards: The "DASHBOARD" sheet served as a blueprint for creating dashboards in Tableau. Tableau was used to design interactive maps, bar charts, and filters, allowing users to drill down into specific insights, such as city-wise restaurant performance and user demographics.

SQL Analysis for Deep Insights: In MySQL, we used advanced queries like GROUP BY, JOIN, and HAVING to derive key insights such as top-performing restaurants, most popular cuisines, and peak ordering times.

Advanced Visualizations in Power BI: Power BI’s visuals, like clustered column charts and line graphs, were employed to represent KPIs such as monthly revenue trends, customer churn, and marketing campaign performance. Power BI also allowed us to embed complex metrics using calculated fields.

Cross-Platform Data Flow: Excel was used to prepare and clean the data, which was then uploaded to MySQL for relational database storage. Power BI and Tableau were connected to MySQL for live querying and visualization, allowing real-time data updates in reports.

Report Presentation and Decision Making: The final insights and dashboards, presented in Power BI and Tableau, were used by stakeholders to make data-driven decisions about restaurant operations, marketing strategies, and customer experience improvements.
