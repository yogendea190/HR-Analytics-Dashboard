HR Analytics Dashboard in Excel

Project Overview
The HR Analytics Dashboard is an Excel-based project designed to analyze human resources data, providing actionable insights into employee dynamics and attrition within an organization. By leveraging advanced Excel features such as pivot tables, charts, and slicers, this dashboard visualizes key HR metrics like gender diversity, departmental attrition, employee group segmentation, marital status trends, and job role-specific turnover. This project showcases data analysis, data visualization, and interactive reporting skills, making it highly relevant for MIS Executive roles focused on HR analytics and talent management.
Domain: Human ResourcesTools Used: Microsoft Excel (Pivot Tables, Charts, Slicers, Conditional Formatting)

Objective
The goal of this project is to create an interactive dashboard that enables HR stakeholders to:

Analyze workforce composition and attrition trends across various dimensions (gender, department, employee groups, marital status, and job roles).
Identify high-risk areas for employee turnover.
Support data-driven HR strategies for talent retention and workforce planning.


Dataset Description
The dataset (HR Analytics Data.xlsx) contains employee-related data with the following fields (assumed based on typical HR datasets):



Field
Description



Employee ID
Unique identifier for each employee


Gender
Employee's gender (e.g., Male, Female)


Department
Department where the employee works (e.g., Sales, IT)


Attrition
Whether the employee left the organization (Yes/No)


Age Group
Employee's age group (e.g., 20-30, 30-40)


Experience Level
Years of experience or job level


Marital Status
Employee's marital status (e.g., Married, Single)


Job Role
Specific role of the employee (e.g., Manager, Analyst)


Hire Date
Date of hiring


Salary
Employee's salary


Location
Work location (e.g., City, Region)


Dataset File: HR Analytics Data.xlsx
Note: If you have a specific dataset, update the fields in the table above to match the actual data.

Analysis Tasks
The project focuses on the following analyses:

Total Employees by Gender: Visualize gender diversity in the workforce.
Attrition by Department: Identify departments with high turnover rates.
Attrition by Group: Analyze attrition patterns across employee groups (e.g., age, experience level).
Attrition by Marital Status: Assess how marital status impacts turnover.
Attrition by Job Role: Highlight job roles with high attrition for targeted retention strategies.
Create a Dashboard: Combine all visualizations into an interactive dashboard with slicers for dynamic filtering.


Step-by-Step Implementation
1. Total Employees by Gender

Objective: Visualize the gender distribution of employees.

Steps:

Open HR Analytics Data.xlsx in Excel.
Create a pivot table in a new sheet named Working.
Set Rows as Gender, Values as Count of Employee ID.
Insert a Pie Chart to visualize the gender breakdown.
Customize the chart with titles (e.g., "Workforce by Gender") and data labels.

Output: A pie chart showing the proportion of male and female employees.



2. Attrition by Department

Objective: Identify departments with high turnover.

Steps:

Create a pivot table in the Working sheet.
Set Rows as Department, Columns as Attrition (Yes/No), Values as Count of Employee ID.
Calculate attrition rate: (Count of Attrition = Yes) / (Total Count per Department).
Insert a Column Chart to visualize attrition rates by department.
Apply conditional formatting to highlight departments with high attrition.

Output: A column chart showing attrition rates across departments.



3. Attrition by Group

Objective: Analyze attrition patterns by age group or experience level.

Steps:

Create a pivot table in the Working sheet.
Set Rows as Age Group or Experience Level, Columns as Attrition, Values as Count of Employee ID.
Insert a Stacked Bar Chart to compare attrition across groups.
Add data labels and customize for clarity.

Output: A stacked bar chart showing attrition patterns by group.



4. Attrition by Marital Status

Objective: Assess turnover based on marital status.

Steps:

Create a pivot table in the Working sheet.
Set Rows as Marital Status, Columns as Attrition, Values as Count of Employee ID.
Insert a Bar Chart to visualize attrition by marital status.
Format with colors to highlight trends (e.g., higher attrition for single employees).

Output: A bar chart showing attrition by marital status.



5. Attrition by Job Role

Objective: Identify high-turnover job roles.

Steps:

Create a pivot table in the Working sheet.
Set Rows as Job Role, Columns as Attrition, Values as Count of Employee ID.
Insert a Column Chart to visualize attrition by job role.
Highlight critical roles with high turnover using conditional formatting.

Output: A column chart showing attrition by job role.



6. Create the Dashboard

Objective: Build an interactive dashboard combining all visualizations.

Steps:

Create a new sheet named Dashboard.
Arrange all charts (gender, department, group, marital status, job role) in a visually appealing layout.
Add Slicers for Department, Gender, Marital Status, and Job Role to enable dynamic filtering.
Insert a title (e.g., "HR Analytics Dashboard") and apply a consistent color scheme.
Add a combo box (optional) for additional interactivity (e.g., filter by Location or Age Group).

Final Dashboard: Dashboard Screenshot



Project Structure
HR-Analytics-Dashboard/
├── dataset/
│   └── HR_Analytics_Data.xlsx
├── images/
│   ├── hr-dashboard-screenshot.png
│   ├── gender-breakdown.png
│   ├── department-attrition.png
│   ├── group-attrition.png
│   ├── marital-status-attrition.png
│   ├── job-role-attrition.png
├── README.md
└── HR_Analytics_Dashboard_Final.xlsx


dataset/: Contains the raw HR dataset.
images/: Screenshots of the dashboard and charts.
HR_Analytics_Dashboard_Final.xlsx: Final Excel file with the completed dashboard.


How to Run the Project

Clone the Repository:git clone https://github.com/your-username/HR-Analytics-Dashboard-in-Excel.git


Open the Dataset: Download HR_Analytics_Data.xlsx from the dataset folder.
Follow the Steps: Replicate the steps in the "Step-by-Step Implementation" section using Microsoft Excel.
Explore the Dashboard: Open HR_Analytics_Dashboard_Final.xlsx to interact with the final dashboard.


Skills Demonstrated

Advanced Excel: Pivot Tables, Charts, Slicers, Conditional Formatting.
Data Analysis: Workforce segmentation, attrition rate calculation, trend analysis.
Data Visualization: Pie Charts, Bar Charts, Column Charts, Dashboard Design.
HR Analytics: Gender diversity analysis, departmental turnover, talent retention strategies.
Interactive Reporting: Dynamic filtering using slicers and combo boxes.



Future Enhancements

Add VBA macros to automate pivot table refreshes or generate custom reports.
Use Power Query for advanced data cleaning (e.g., handling missing values).
Incorporate additional metrics like salary analysis or tenure-based attrition.
Create a Power BI version of the dashboard for enhanced interactivity.


Contact
For questions or feedback, feel free to reach out:  

GitHub: Your GitHub Profile  
Email: [Your Email Address]


This project was developed to demonstrate HR analytics and data visualization skills for an MIS Executive role.
