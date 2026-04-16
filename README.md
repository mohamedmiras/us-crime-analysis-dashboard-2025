Project Documentation

Crime Incidents 2025 Report
1.	Project Overview
 
This project presents an interactive Crime Analysis Dashboard for the United States (2025) developed using Excel and Power BI. The dashboard is designed to identify major crime hotspots, compare crime patterns across regions, and provide detailed insights into crime intensity and severity across multiple geographic levels.
The analysis focuses on incidents recorded during 2025 only and enables users to explore crime trends through dynamic filters, maps, KPI cards, and comparative visuals.
Key Objectives:
•	Identify major crime hotspot locations using block-level and geographic mapping data
•	Analyze crime statistics by region such as North East, North West, South East, and South West
•	Evaluate incidents based on crime intensity and severity levels (Critical, High, Moderate, Minor)
•	Compare crime occurrences across administrative and policing boundaries
•	Support decision-making through visual summaries and interactive drill-down analysis
Geographic Levels Covered:
The project analyzes crime data at multiple levels, including:
•	Block / Street Level – exact hotspot areas
•	District – policing zones
•	PSA (Police Service Areas) – detailed operational zones
•	Cluster Number – grouped crime regions
•	Ward / ANC – civic and administrative divisions
•	Voting Precinct – electoral area analysis
•	Region – broad directional zones (NE, NW, SE, SW)
•	Census Tract / Block Group – statistical and demographic analysis areas
•	
Dashboard Features:
•	KPI Cards for Total Crimes, Top Often Day, Severity Score, and Top Crime Hotspot
•	Crime Distribution Charts by offense category
•	Map Visualizations for hotspot detection using latitude and longitude
•	Monthly Trend Analysis for seasonal crime patterns
•	Crime by PSA / Region comparisons
•	Severity-wise stacked analysis by region
•	Interactive slicers for:
o	District
o	Cluster Number
o	Voting Precinct
o	Offense Type
o	Date Range
Tools & Technologies Used:
Business Value / Outcome:
This dashboard helps stakeholders, analysts, and decision-makers quickly identify high-risk areas, understand crime patterns, compare regions, and allocate resources more effectively. It transforms raw crime records into actionable intelligence through data visualization.
Short Resume Version:
Developed an interactive US Crime Analysis Dashboard (2025) using Excel and Power BI to analyze crime hotspots, severity levels, regional trends, and location-based crime patterns across blocks, districts, voting precincts, clusters, and police service areas.

2.	Tools Used
-	Microsoft Excel – data cleaning, preprocessing, formatting
-	Power BI – data modeling, DAX calculations, dashboard creation
-	DAX – severity scoring, duration logic, ranking, summaries

3.	Dataset
-	Source: Crime Data 2025
-	Data contains: 

o	Date (Start / End) 
o	Offense Type 
o	Shift 
o	Block / Location 
o	District 
o	PSA 
o	Region 
o	Severity Level 
o	Latitude & Longitude 
o	Month / Time Trend Data

4.	Steps Followed
•	Cleaned and prepared raw data in Excel (removed blanks, corrected formats, standardized columns) 
•	Used Excel formulas and Pivot Tables for initial summaries and validation 
•	Imported the cleaned dataset into Power BI 
•	Created data model and applied DAX calculations for severity, duration, and rankings 
•	Built an interactive dashboard using charts, maps, slicers, and KPI cards 
•	Added filters and drill-down views for location-wise and trend analysis

5.	Key Insights
•	Theft/Other is the most frequent crime type, making it the dominant offense category across all regions. 
•	The North West region records the highest concentration of crime incidents, making it the most affected geographic zone. 
•	Most crimes fall under Moderate severity (8,973 cases), followed by High (7,098) and Minor (6,014), while Critical (2,021) cases are fewer but more serious. 
•	Evening shift records the highest number of incidents with 10,034 cases, followed by Day (9,938) and Midnight (4,134). 
•	The most common day for crimes is Friday, indicating higher incident frequency at the end of the working week. 
•	Key hotspot zones include Voting Precinct 129, District 2, and Cluster 8, which record the highest number of incidents in their respective categories. 
•	Most incidents are short-duration and fall under Minor/Moderate classifications, while long-duration Critical cases are limited but operationally significant. 
•	Crime occurrences vary by month, with visible peaks in certain months, indicating seasonal or periodic patterns during 2025. 
•	Non-BID areas experience higher crime levels compared to business districts, showing incidents are more concentrated outside commercial zones



6.	Screenshots
  

7.	Files Included
-	‘sales_data.xlsx’ – Cleaned data and basic analysis
-	‘MINI PROJECT APRIL.pbix – Power BI dashboard
-	‘README.md’ – CRIME DATA 2025

8.	How to Use
-	Open `Powerbi data part to view the cleaned data.
-	Open `dashboard.pbix` in Power BI Desktop to explore the visuals.
-	Note: the data cleaning process has done through Power Query Model View from Power BI
.
# us-crime-analysis-dashboard-2025
Interactive US Crime Analysis Dashboard (2025) built with Excel and Power BI. Analyzes crime hotspots, regional trends, severity levels, shifts, precincts, districts, and monthly patterns using maps, KPIs, slicers, and dynamic visualizations
