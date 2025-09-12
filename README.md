# HR-Analytics-Dashboard
This HR Analytics Dashboard provides an in-depth view of employee performance, job satisfaction, and attrition trends. Built in Power BI, it helps HR teams and managers uncover the key drivers behind workforce turnover, identify improvement areas, and make data-driven decisions to enhance employee retention and engagement.

## Business Problem
High attrition and low job satisfaction impact productivity. HR needed a tool to track employee performance and understand key drivers of turnover.

## Data Used
Public domain dataset from Kaggle - https://www.kaggle.com/datasets/anshika2301/hr-analytics-dataset/data

Key columns: Employee ID, Department, Job Role, Performance Rating, Job Satisfaction, Attrition (Yes/No), YearAtCompany, Age, Monthly Income

## Tools
Power BI Desktop, Power Query

## Import and Data Cleaning
1. Imported the dataset from Excel into Power BI.
2. Transformed and cleaned data using Power Query.
3. Removed duplicate records and corrected inconsistencies.
4. Applied appropriate data formats, such as currency and percentage.
5. Loaded the cleaned data into Power BI for analysis.

## Data Modeling
1. Established a one-to-one relationship between two tables using Employee ID in Model View.
2. Set the filter direction to both to enable bidirectional filtering.

## Key Features of Dashboard 
1. Total Employees card to track overall workforce size.
2. Job Satisfaction and Performance Indicator metrics for employee well-being and productivity.
3. Employee Demographics:
     1. Employee distribution by gender.
     2. Bar chart showing employees by age group.
     3. Stacked bar chart of employees by years at company alongside attrition rate.
4. Compensation insights
     1. Bar chart comparing average monthly income by department.
5. Key Influencer visual highlighting conditions that most affect attrition (e.g., Overtime, Year at Company, job satisfaction).

<img width="1243" height="695" alt="image" src="https://github.com/user-attachments/assets/af132e2f-6301-476e-9b4c-fe4a2b79b38d" />

## Insights and Outcomes
1. Employees working overtime are nearly 3x more likely to leave (attrition ↑ 2.93x), i.e., 30.53% among overtime employees.
2. Attrition is 2.7x (34.88%) higher among employees with ≤ 1 year of tenure compared to longer-serving employees.
3. Single employees who also work overtime are at very high risk of leaving (almost 1 in 2 employees in this group quit).
4. Frequent business travel increases the likelihood of attrition by 1.77x (24.91%).
5. Employees with very low job satisfaction (≤ 1) face a 1.58x (22.84%) higher attrition rate.

## Business Implication
1. __Workload Management:__ Monitor and reduce excessive overtime through better resource allocation or additional hiring.
2. **Early Engagement:** Strengthen onboarding and mentorship programs for new hires to reduce first-year attrition.
3. **Employee Support Programs:** Offer targeted engagement initiatives for single employees (e.g., social programs, peer networks).
4. **Travel Policy Adjustments:** Limit unnecessary business travel and provide flexibility for frequent travelers.
5. **Job Satisfaction Improvements:** Focus on career growth, recognition and work-life balance to address low satisfaction levels.

