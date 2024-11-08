# HR-Attrition-Power-BI-Project-
HR Attrition Dashboard

This project aims to create an HR dashboard in Power BI that focuses on attrition analysis for the organization. 
The data is processed and cleaned in Power BI’s Power Query, with transformations applied to prepare the data for visualization. 
The dashboard provides insights into employee attrition by categorizing distance from home, years of experience, job satisfaction, and age,
along with key performance indicators (KPIs) for HR analysis.

Table of Contents

Project Overview

Data Preparation

Data Transformation

KPI Calculation

Visualization

Project Structure

Conclution


---

Project Overview

The objective of this dashboard is to analyze attrition in the organization by transforming raw employee data into meaningful insights,
including the distance from home, job satisfaction, years of experience, and age groups. Power BI is used to visualize these metrics 
and help the HR team make data-driven decisions.


---

Data Preparation

1. Data Loading: The dataset is loaded from an Excel file (or other data source) into Power BI.


2. Data Cleansing: Empty rows, columns, and any irrelevant data are removed in Power Query to ensure a clean dataset.




---

Data Transformation

The following transformations are applied to the dataset in Power Query:

1. Distance from Home:

Employees' distance from home is categorized into three groups:

Near: <= 10 km

Far: 11-20 km

Very Far: > 20 km




2. Years of Experience:

Grouped into intervals:

0-10 years

11-20 years

21-30 years, etc.




3. Job Satisfaction:

Converted from numerical values (1-4) to descriptive labels:

1: Low

2: Medium

3: High

4: Very High




4. Age:

Segmented into age buckets:

20-29

30-39

40-49, etc.





These transformations allow for more intuitive interpretation in the dashboard.


---

KPI Calculation

The following key performance indicators (KPIs) are calculated in Power BI:

Total Employees: Total number of employees in the dataset.

Total Attrition: Number of employees who have left the organization.

Attrition by Gender: Breakdown of attrition by gender.

Attrition by Job Satisfaction: Attrition rates by job satisfaction levels.



---

Visualization

The dashboard includes visualizations for each KPI and category:

1. Attrition Summary: Displays total attrition, total employees, and attrition percentage.


2. Distance Analysis: Shows attrition trends based on the categorized Distance from Home.


3. Years of Experience Analysis: Visualizes attrition rates across different experience intervals.


4. Job Satisfaction: Attrition distribution by job satisfaction categories.


5. Age Groups: Attrition rates based on age groups.



Each visualization provides a clear view of attrition patterns and assists in identifying factors contributing to employee turnover.


---

Project Structure

Data: Contains the raw dataset used in Power BI.

Power Query: Data transformation steps are implemented here.

DAX Measures: Calculation of KPIs is done here.

Visualizations: Dashboard elements are created here.



---

Conclution

The HR Attrition Dashboard provides valuable insights into the key factors influencing employee turnover within the organization. By analyzing attrition across categories like distance from home, years of experience, job satisfaction, and age, this dashboard allows HR to identify patterns and areas of concern. For instance, high attrition rates among employees with lower job satisfaction or significant commuting distances could indicate opportunities to improve job satisfaction initiatives or remote work policies.

This dashboard not only highlights existing attrition trends but also equips HR leaders with actionable data to develop targeted retention strategies. In the long term, these insights can support the organization in reducing attrition, improving employee engagement, and fostering a more satisfied, productive workforce.

