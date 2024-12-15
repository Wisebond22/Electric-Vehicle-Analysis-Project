# Electric-Vehicle-Analysis-Project
## Project Overview
The Electric Vehicles Analysis Project is aimed at providing insights into the adoption trends, performance metrics, and market share of electric vehicles (EVs). The project analyzes data related to EV usage, highlighting key aspects like vehicle models, manufacturers, and eligibility for Clean Alternative Fuel Vehicles (CAFV) credits. 

## Dataset Used
<a href = 'https://drive.google.com/drive/folders/1YviyK5J_0LS9yBb2lNh2Fyap1xlyec7W'> DataSet <a/>

## Questions KPIs
-Total Number of Electric Vehicles: Total count of EVs analyzed in the dataset.
-Average Electric Range: The mean electric range (in miles) across all EVs.
-Percentage of BEVs vs. PHEVs: Proportion of Battery Electric Vehicles (BEVs) compared to Plug-in Hybrid Electric Vehicles (PHEVs).
-Top Vehicle Make by Market Share: The brand with the highest percentage of vehicles.
-Top EV Model by Sales Volume: The model with the most units in the dataset.
-CAFV Eligibility Rate: Percentage of EVs eligible for Clean Alternative Fuel Vehicle incentives.
-Year with Highest EV Adoption: The year with the largest increase in EV registrations.

##Preprocessing Steps:

1.Data Collection:
. I gathered the dataset, which included information on electric vehicles, their types, make, model, year of registration, range, and CAFV eligibility status. The dataset was provided in a structured format (Excel file).

2.Data Cleaning:

I removed duplicates to ensure data integrity.
Missing values in key fields, such as vehicle type and electric range, were handled by filling in logical estimates or excluding irrelevant rows where necessary.
Inconsistent entries, such as variations in naming conventions (e.g., "Tesla" vs. "TESLA"), were standardized for uniformity.

3.Data Transformation:

I categorized vehicles into Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs) for easier analysis.
Numerical values like electric range were checked for anomalies or extreme outliers and corrected based on data trends.

4.Data Formatting:

I structured the data into logical columns and rows, ensuring each column represented a distinct feature (e.g., vehicle type, model, year).
Filters for city and vehicle type were added to enable dynamic analysis in Power BI.

5.Data Validation:

I cross-checked totals and distributions in the dataset to ensure the cleaned data matched the original dataset's integrity.
Validated the cleaned dataset by loading it into Power BI to test compatibility and identify potential errors.

## Methodology and Analysis Steps
Tool Selection:
I chose Microsoft Excel for initial data cleaning and preparation because of its versatility and ease of use. I used Power BI for dynamic visualizations and dashboards to present insights in an interactive and visually appealing way.

Exploratory Data Analysis (EDA):

I explored the dataset to understand its structure and identify trends and patterns.
Used Excel pivot tables and charts to gain an overview of electric vehicle adoption, make, model distribution, and other key metrics.
Data Integration:

Imported the cleaned dataset into Power BI.
Defined relationships between fields (e.g., linking vehicle type to CAFV eligibility) to enhance interactivity in the dashboard.
Visualization Design:

Designed an intuitive and visually compelling dashboard in Power BI.
Key components of the dashboard included total vehicle count, market share by make and model, average electric range, and year-over-year adoption trends.
Dynamic Filters:

Added slicers for "City" and "Electric Vehicle Type" to enable users to filter data dynamically.
Ensured filters reflected changes in all related visualizations, providing a cohesive experience.
Insights Extraction:

Analyzed trends, such as the rising adoption of BEVs over PHEVs, the dominance of Tesla and Model Y, and the year with the highest registrations.
Derived actionable insights, such as the significant percentage of vehicles eligible for CAFV incentives.
Validation of Results:

Cross-referenced dashboard outputs with original Excel calculations to ensure accuracy.
Presented the findings in an easy-to-understand manner, focusing on actionable business insights and key takeaways.
