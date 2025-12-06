# Excel
• Introduction 
Agriculture plays a vital role in India’s economy, and agricultural markets 
(mandis) are central to the supply chain. Given the diversity in crops, grading, 
and pricing across different regions, it becomes essential to have a unified 
dashboard to visualize this data for better decision-making. This project 
develops a data-driven dashboard using mandi market data to analyse 
commodity prices, revenues, and regional performance. 
• Source of Dataset 
The data for this project was derived from government portals such as 
data.gov.in and contains transactional mandi-level information. The key fields 
in the dataset include: 
• State, District, Market 
• Commodity, Variety, Grade 
• Arrival Date 
• Minimum, Maximum, and Modal Prices 
• Computed Revenue 
This structured data allows for comprehensive filtering, aggregation, and 
visualization for business intelligence purposes. 
• Dataset Preprocessing 
Preprocessing was crucial to ensure data quality and readiness for analysis. 
Major steps included: 
• Handling Missing Values: Rows missing essential values such as 
Commodity or Price were filtered or filled using domain-based 
approximations. 
• Date Standardization: All date entries were converted to a uniform 
format for chronological analysis. 
• Derived Metrics: Revenue was calculated based on modal prices. If 
quantity data is available, it could be refined further. 
• Pivot Tables: Used to summarize pricing and revenue data across 
different regions and grades. 
• Categorical Standardization: Grades, varieties, and market names were 
normalized for consistency. 
• Analysis on Dataset 
i. General Description 
The dataset covers daily entries from markets in states like Assam and Andhra 
Pradesh. Commodities include Bottle Gourd, Tomato, Cabbage, and Paddy. 
Each entry logs price points (Min, Max, Modal) and Grade-wise classification. 
ii. Specific Requirements 
The main objectives of the project were: 
• To identify the most traded commodities and their revenue 
contributions. 
• To determine state-wise and grade-wise pricing trends. 
• To visualize market dynamics using interactive dashboards. 
• To assist policymakers, traders, and analysts in understanding mandi 
performance. 
iii. Analysis Results 
• Revenue Leaders: 'Red Nanital' grade produced significantly high 
revenue compared to others. 
• High Activity Zones: Assam recorded the highest overall market activity 
in terms of price aggregation. 
• Price Ranges: Modal prices varied dramatically by commodity and 
region, highlighting location-specific pricing. 
iv. Visualization 
Key visualizations on the dashboard include: 
• Bar Charts: Revenue by commodity and grade. 
• Maps: State-wise distribution of traded commodities. 
• Pivot Tables: Quick summaries for price trends by district and state. 
• Time Graphs (if date-wise data is enriched): Trends over time for 
specific commodities. 
These visuals enable easy interpretation of large datasets and support 
actionable decision-making. 
• Conclusion 
The mandi dashboard effectively brings transparency and clarity to agricultural 
market data. With real-time access and visual insights, stakeholders can plan 
logistics, set fair prices, and optimize trade flows. This analytical approach 
enhances market efficiency and supports the digital transformation of Indian 
agriculture.
