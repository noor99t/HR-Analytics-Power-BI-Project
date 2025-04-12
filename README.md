📊 HR Analytics Power BI Project – README
💼 Project Overview
This project uses a simulated HR dataset to explore employee performance, satisfaction, attrition, and workplace behavior. It’s perfect for analyzing trends that affect HR decisions like promotions, training, and turnover.

I’ll be visualizing all this using Power BI — breaking down key metrics in a clean, interactive dashboard.

🧠 Objectives
Understand what influences employee satisfaction and attrition

Evaluate performance from both self and manager perspectives

Spot trends in education, job roles, overtime, and promotions

Help HR teams make data-driven decisions about talent management

📁 Dataset Structure
The dataset includes multiple related tables, which I’ll model in Power BI using relationships and lookups.

🔹 FactPerformanceRating
Core metrics for employee reviews:

EnvironmentSatisfaction, JobSatisfaction, WorkLifeBalance

SelfRating, ManagerRating

TrainingOpportunitiesWithinYear, TrainingOpportunitiesTaken

🔹 DimEmployee
Details about employees:

Personal info: Gender, Age, Ethnicity, MaritalStatus

Work info: Department, JobRole, HireDate, Overtime, Attrition

Career stats: YearsAtCompany, YearsInMostRecentRole, etc.

🔹 DimSatisfiedLevel
Decodes satisfaction scores into categories:

Very Satisfied, Neutral, Dissatisfied, etc.

🔹 DimRatingLevel
Decodes performance ratings:

Meets Expectations, Exceeds Expectations, Needs Improvement, etc.

🔹 DimEducationLevel
Decodes education background:

From No Formal Qualifications to Doctorate

🔗 Relationships
I'll create relationships between:

EmployeeID in FactPerformanceRating ↔ DimEmployee

Satisfaction/Rating/Education levels via IDs for proper decoding

🔍 Planned Visuals
Here’s the vibe for the dashboard:

🌈 Employee satisfaction heatmap

📉 Attrition analysis by department, gender & overtime

📚 Training vs performance trends

🧪 Self vs Manager rating comparison

🧭 Age, education, and promotion patterns

🛠 Tools Used
Power BI Desktop

DAX for custom KPIs and calculated columns

Power Query for cleaning and transforming data

🚀 Why This Project Rocks
This dataset gives a realistic view of HR dynamics, letting me flex both my analytical and dashboard design skills. It’s also a great way to practice building insights that matter to actual businesses — especially HR teams trying to retain top talent and boost morale.
