# **Comprehensive HR Analysis: Insights into Attrition, Overtime, and Performance Trends**
![H.R. ANALYSIS PROJECT IMAGE](https://github.com/yemifatodu/HR_Analysis_meriSkill_project_Internship/raw/main/H.R.%20ANALYSIS%20PROJECT%20IMAGE.png)


---
**Introduction:**  

This project delves into a detailed analysis of HR data to uncover significant trends and patterns that can inform strategic decisions. By analyzing key metrics such as attrition rates, overtime hours, and performance ratings across various departments and job roles, we aim to provide actionable insights that can enhance employee satisfaction, reduce turnover, and optimize workforce productivity. Through a series of SQL queries, we explore the underlying factors affecting employee dynamics, offering a data-driven approach to HR management.

## Objectives of the Analysis

The objective of this analysis is to provide a comprehensive overview of the organization's workforce by leveraging data-driven insights across four key areas. Each dashboard is designed to inform strategic HR decisions and improve employee engagement, satisfaction, and retention. The specific objectives include:

1. **Overtime Analysis Dashboard**: 
   - **Objective**: To examine the relationship between employee overtime and various demographic and job-related factors. The aim is to understand how overtime impacts different segments of the workforce, such as age, gender, tenure, and job roles, and to identify patterns that could inform policies to enhance work-life balance and reduce burnout.

2. **Work Experience and Education Level Dashboard**:
   - **Objective**: To analyze the correlation between employees' educational backgrounds and their work experience, job satisfaction, performance ratings, and compensation. This analysis seeks to uncover trends that can guide decisions on employee development, career progression, and targeted training programs.

3. **Employee Demographic and Job Characteristics**:
   - **Objective**: To explore the demographic composition of the workforce in relation to job characteristics such as department, job role, and tenure. This analysis aims to provide insights into the distribution of employees across different segments, supporting efforts to foster a diverse and inclusive workplace.

4. **Turnover Analysis**:
   - **Objective**: To identify factors contributing to employee turnover by examining attrition rates in relation to various employee demographics, job roles, and organizational practices such as business travel and overtime. The goal is to develop strategies to improve employee retention, particularly among high-risk groups.



## Dataset Description

The dataset used for this analysis is a comprehensive collection of employee data, designed to provide insights into various aspects of the workforce. This dataset includes 1,470 records and 36 columns, each representing a different attribute related to employee demographics, job characteristics, performance, and satisfaction.

### Key Attributes:

1. **Age**: The age of the employee in years.
   
2. **Attrition**: Indicates whether the employee has left the organization (Yes/No).

3. **BusinessTravel**: Describes the frequency of business travel required by the employee's role (e.g., Travel_Rarely, Travel_Frequently, Non-Travel).

4. **DailyRate**: The daily salary rate for the employee.

5. **Department**: The department in which the employee works (e.g., Sales, Research & Development, Human Resources).

6. **DistanceFromHome**: The distance between the employee's residence and workplace in miles.

7. **Education**: The education level of the employee, represented by numerical codes (e.g., 1 = Below College, 2 = College, 3 = Bachelor, 4 = Master, 5 = Doctor).

8. **EducationField**: The field of education in which the employee has specialized (e.g., Life Sciences, Medical, Marketing).

9. **EmployeeCount**: A constant value (typically 1) representing each employee.

10. **EmployeeNumber**: A unique identifier assigned to each employee.

11. **EnvironmentSatisfaction**: Employee's satisfaction with the work environment, rated on a scale from 1 to 4.

12. **Gender**: The gender of the employee (Male/Female).

13. **HourlyRate**: The hourly wage of the employee.

14. **JobInvolvement**: Level of involvement the employee has in their job, rated on a scale from 1 to 4.

15. **JobLevel**: The level of the employee's position within the organization.

16. **JobRole**: The specific role or position held by the employee (e.g., Sales Executive, Research Scientist).

17. **JobSatisfaction**: The employee's level of job satisfaction, rated on a scale from 1 to 4.

18. **MaritalStatus**: The marital status of the employee (e.g., Single, Married, Divorced).

19. **MonthlyIncome**: The monthly salary of the employee.

20. **MonthlyRate**: The monthly rate of pay for the employee.

21. **NumCompaniesWorked**: The number of companies the employee has worked for prior to the current organization.

22. **Over18**: Indicates whether the employee is over 18 years old (Yes/No).

23. **OverTime**: Indicates whether the employee works overtime (Yes/No).

24. **PercentSalaryHike**: The percentage increase in salary over the previous year.

25. **PerformanceRating**: The performance rating of the employee, typically on a scale of 1 to 4.

26. **RelationshipSatisfaction**: The employee's satisfaction with their relationships within the organization, rated on a scale from 1 to 4.

27. **StandardHours**: The standard number of working hours (typically 80).

28. **StockOptionLevel**: The level of stock options awarded to the employee, typically on a scale from 0 to 3.

29. **TotalWorkingYears**: The total number of years the employee has worked in their career.

30. **TrainingTimesLastYear**: The number of training sessions the employee attended in the last year.

31. **WorkLifeBalance**: The employee's perception of their work-life balance, rated on a scale from 1 to 4.

32. **YearsAtCompany**: The number of years the employee has been with the current company.

33. **YearsInCurrentRole**: The number of years the employee has been in their current role.

34. **YearsSinceLastPromotion**: The number of years since the employee's last promotion.

35. **YearsWithCurrManager**: The number of years the employee has worked with their current manager.

36. **Age_Bracket**: A derived categorical variable that groups employees into age brackets (e.g., 18-30, 31-45, 46 and above).



## HR Analysis Project: Tools, Techniques, and Insights

### Overview
In this HR Analysis project, I undertook a comprehensive exploration of employee data to derive actionable insights that could inform strategic HR decisions. The project involved the use of multiple tools—Microsoft Excel, SQL, and Tableau—each playing a crucial role in different stages of the analysis. Below is a detailed account of how each tool was utilized and the impact it had on the overall findings.

### Microsoft Excel: Data Preparation and Initial Exploration
The journey began with Microsoft Excel, where I engaged in data cleaning and preparation. Excel served as the foundation for the entire analysis, allowing me to:
- **Cleanse the Dataset**: I systematically addressed inconsistencies, missing values, and duplicates within the dataset, ensuring that the data was ready for deeper analysis. This step was crucial in avoiding any potential biases or errors in the later stages.
- **Preliminary Analysis**: Using Excel’s powerful functions and pivot tables, I conducted an exploratory analysis that provided an initial understanding of the dataset. This included generating summary statistics and identifying key trends, such as variations in employee satisfaction across different departments.

### SQL: Advanced Data Querying and Transformation
With a cleansed dataset in hand, I transitioned to SQL for more sophisticated data querying and manipulation. SQL allowed me to:
- **Extract Key Metrics**: I wrote complex queries to extract essential information, such as average salaries, attrition rates, and employee tenure. SQL’s ability to handle large datasets efficiently made it the ideal tool for these tasks.
- **Create Calculated Fields**: By leveraging SQL’s capabilities, I developed new calculated fields that added depth to the analysis. For instance, I computed the number of years since the last promotion for each employee, which later helped in identifying factors contributing to employee turnover.

### Tableau: Visualization and Insight Communication
The final phase of the project involved the use of Tableau to create dynamic visualizations and dashboards. Tableau was instrumental in:
- **Bringing Data to Life**: I designed four comprehensive dashboards—Overtime Analysis, Work Experience and Education Level, Employee Demographics and Job Characteristics, and Turnover Analysis. These dashboards provided stakeholders with an interactive means to explore the data and uncover insights at a glance.
- **Highlighting Key Insights**: Tableau’s visualization tools made it possible to identify patterns and trends that were not immediately apparent in the raw data. For example, the dashboards revealed a strong correlation between overtime hours and employee attrition, particularly in certain departments.

### Conclusion
The use of Microsoft Excel, SQL, and Tableau in this HR Analysis project enabled a thorough examination of the employee dataset. Each tool played a unique role, from data preparation and querying to visualization and insight generation. The result was a set of actionable recommendations that can help the organization enhance employee satisfaction, reduce turnover, and make informed HR decisions.



## Analysis of the H.R. ANALYSIS Dashboard

### Dashboard Visualization:

The HR Analysis Dashboard is an exemplary showcase of effective data visualization techniques, combining aesthetics with functionality to convey critical insights. Below is an analysis of the key elements of this dashboard’s visualization:

### 1. **Color Scheme and Visual Appeal**
   - **Consistency and Clarity**: The dashboard adopts a consistent dark theme, contrasted with bright and bold colors like blue and orange, to distinguish various metrics. This use of contrasting colors ensures that each visualization is easily interpretable, enhancing overall readability.
   - **Highlighting Key Metrics**: Specific metrics, such as the count of educational levels, job satisfaction, and performance ratings, are accentuated with large, circular markers and vibrant colors. This design choice immediately draws attention to important data points, ensuring that users can quickly identify critical information.
 
### 2. **Layout and Design**
   - **Logical Flow**: The dashboard is organized into clearly defined sections, each addressing different aspects of HR analysis such as educational levels, job satisfaction, and work experience. This logical structure allows users to follow the narrative seamlessly, from understanding employee demographics to exploring their impact on performance and satisfaction.
   - **Interactive Elements**: Although not explicitly interactive in the static image, the layout suggests a design that could easily support interactive features such as filters or tooltips. Such elements would allow users to explore the data in greater depth, tailoring the analysis to specific needs.

### 3. **Types of Visualizations Used**
   - **Bar and Column Charts**: These are predominantly used to compare categorical data, such as educational levels and job satisfaction by education. The clear vertical and horizontal orientations help users quickly grasp differences across categories, making it easier to identify trends and anomalies.
   - **Treemap**: The treemap visualization is used to represent the count of male employees across different education levels, offering a compact and efficient way to visualize hierarchical data. The size of the rectangles corresponds to the count, providing an immediate sense of scale.
   - **Histogram**: The histogram depicting the distribution of educational levels by years of work experience provides a granular look at how education correlates with experience within the organization. This helps in identifying common career progression patterns.
   - **Scatter Plot**: This visualization is used in charts like job satisfaction and performance rating by educational level, combining bubble sizes and bar heights to offer a multi-dimensional perspective on the data. It’s an effective way to compare multiple variables simultaneously.
 
### 4. **Insight Communication**
   - **Clarity in Data Presentation**: The dashboard excels in presenting data clearly, with well-labeled axes, legends, and consistent use of markers and colors. This reduces cognitive load, allowing users to focus on deriving insights rather than deciphering the charts.
   - **Storytelling with Data**: Each section of the dashboard contributes to an overarching narrative about the workforce, from educational background to job satisfaction and income levels. This storytelling approach makes the data more relatable and actionable for stakeholders, enabling informed decision-making.


The HR Analysis Dashboard is a powerful example of how to visualize complex HR data in a way that is both aesthetically pleasing and highly informative. Through consistent color schemes, logical layout, and clear communication of insights, the dashboard effectively serves as a tool for HR professionals to make data-driven decisions. By leveraging various types of visualizations, the dashboard provides a comprehensive view of the workforce, ensuring that every aspect of employee data is thoroughly analyzed.



### HR Analytics and Insights

#### Overview
This report provides a comprehensive analysis of various HR metrics through four key dashboards: Overtime Analysis, Work Experience and Education Level, Employee Demographics and Job Characteristics, and Turnover Analysis. Each dashboard highlights significant trends and insights that can aid in strategic HR decision-making.



Organized and detailed analysis

### 1. **Identify High Attrition Rates by Department**
This provides a breakdown of the attrition rate by department, showing which departments have the highest turnover:

| Department           | Total_Employees | Attrition_Count | Attrition_Rate (%) |
|----------------------|------------------|-----------------|---------------------|
| Sales                | 446              | 92              | 20.63               |
| Human Resources      | 63               | 12              | 19.05               |
| Research & Development | 961            | 133             | 13.84               |

### 2. **Average Monthly Income by Education Level and Job Role**
This table provides the average monthly income segmented by education level and job role, to understand the income distribution across different roles and education levels:

| Education Level | Job Role                  | Avg Monthly Income |
|-----------------|----------------------------|---------------------|
| 1               | Healthcare Representative   | 8769                |
| 1               | Human Resources            | 2776                |
| 1               | Laboratory Technician      | 2982                |
| 1               | Manager                    | 17037               |
| 1               | Manufacturing Director     | 7063                |
| 1               | Research Director          | 15752               |
| 1               | Research Scientist         | 2918                |
| 1               | Sales Executive            | 6732                |
| 1               | Sales Representative       | 2489                |
| 2               | Healthcare Representative   | 7096                |
| 2               | Human Resources            | 3811                |
| 2               | Laboratory Technician      | 3256                |
| 2               | Manager                    | 17556               |
| 2               | Manufacturing Director     | 6519                |
| 2               | Research Director          | 15779               |
| 2               | Research Scientist         | 3326                |
| 2               | Sales Executive            | 6418                |
| 2               | Sales Representative       | 3004                |
| 3               | Healthcare Representative   | 7677                |
| 3               | Human Resources            | 4408                |
| 3               | Laboratory Technician      | 3234                |
| 3               | Manager                    | 16927               |
| 3               | Manufacturing Director     | 7949                |
| 3               | Research Director          | 16498               |
| 3               | Research Scientist         | 3038                |
| 3               | Sales Executive            | 7314                |
| 3               | Sales Representative       | 2382                |
| 4               | Healthcare Representative   | 7152                |
| 4               | Human Resources            | 4867                |
| 4               | Laboratory Technician      | 3268                |
| 4               | Manager                    | 17340               |
| 4               | Manufacturing Director     | 7117                |
| 4               | Research Director          | 15850               |
| 4               | Research Scientist         | 3632                |
| 4               | Sales Executive            | 6877                |
| 4               | Sales Representative       | 2927                |
| 5               | Healthcare Representative   | 7503                |
| 5               | Human Resources            | 4990                |
| 5               | Laboratory Technician      | 4491                |
| 5               | Manager                    | 17128               |
| 5               | Manufacturing Director     | 7394                |
| 5               | Research Director          | 15395               |
| 5               | Research Scientist         | 3429                |
| 5               | Sales Executive            | 6631                |

### 4. **Overtime Hours Analysis by Job Role**
 Analysis of  the total number of overtime instances by job role, showing which roles experience the most overtime:

| Job Role                  | Total Overtime Instances |
|----------------------------|--------------------------|
| Research Scientist         | 97                       |
| Sales Executive            | 94                       |
| Laboratory Technician      | 62                       |
| Manufacturing Director     | 39                       |
| Healthcare Representative   | 37                       |
| Manager                    | 27                       |
| Sales Representative       | 24                       |
| Research Director          | 23                       |
| Human Resources            | 13                       |

### 5. **Impact of Distance from Home on Job Performance**
This shows after i have examines the average performance rating based on distance from home, that the performance rating remains consistent across various distances:

| Distance from Home | Avg Performance Rating |
|--------------------|-------------------------|
| 1-29               | 3                       |

#### **Segmented Analysis of Performance Rating by Distance**
This segmented analysis also shows consistent performance ratings:

| Distance Bin | Avg Performance Rating |
|--------------|-------------------------|
| 1-5          | 3                       |
| 6-10         | 3                       |
| 11-15        | 3                       |
| 16-20        | 3                       |
| 21-25        | 3                       |
| 26+          | 3                       |

### 6. **Distribution of Performance Ratings**
This distribution shows the count and percentage of performance ratings:

| Performance Rating | Count | Percentage (%) |
|--------------------|-------|----------------|
| 3                  | 1244  | 84.63          |
| 4                  | 226   | 15.37          |

---

##    vizuliasation

### 1. Overtime Analysis Dashboard



**Chart 1: Distance from Home and Overtime Hours**
- **Title:** Distance from Home Categorization
- **Parameters:** Distance from home (in kilometers), Overtime hours
- **Insight:** Employees living closer to the workplace (within 5 km) are more likely to work overtime. Overtime decreases as the distance from home increases.

**Chart 2: Tenure and Overtime Hours**
- **Title:** Duration of Employment in Overtime Segmentation
- **Parameters:** Duration of employment (in years), Overtime hours
- **Insight:** Employees with around 10 years of tenure show the highest engagement in overtime, with a decrease in overtime beyond this point.

**Chart 3: Departmental Overtime Hours**
- **Title:** Departmental Categorization
- **Parameters:** Department, Overtime hours
- **Insight:** Certain departments exhibit higher overtime rates, with the majority of overtime concentrated in specific areas.

**Chart 4: Gender and Overtime Hours**
- **Title:** Gender and Overtime Categorization
- **Parameters:** Gender, Overtime hours
- **Insight:** A higher proportion of male employees engage in overtime compared to female employees.

**Chart 5: Age and Overtime Hours**
- **Title:** Age Categorization
- **Parameters:** Age group, Overtime hours
- **Insight:** Employees aged 30-45 are more likely to work overtime, peaking around ages 35-40.

**Chart 6: Marital Status and Overtime Hours**
- **Title:** Marital Status Categorization
- **Parameters:** Marital status, Overtime hours
- **Insight:** Marital status distribution remains consistent, with a majority of married employees.

**Chart 7: Work Experience and Overtime Hours**
- **Title:** Work Experience Level Categorization
- **Parameters:** Work experience (in years), Overtime hours
- **Insight:** Mid-career employees show higher overtime engagement compared to those with shorter or longer tenures.

**Chart 8: Educational Level and Overtime Hours**
- **Title:** Educational Level Categorization
- **Parameters:** Education level, Overtime hours
- **Insight:** Employees with mid-level education engage more in overtime, with reduced overtime among those with higher education levels.

**Chart 9: Job Role and Overtime Hours**
- **Title:** Job Role Categorization
- **Parameters:** Job role, Overtime hours
- **Insight:** Specific roles, such as Research Director and Sales Executive, exhibit higher overtime counts.

---

### 2. Work Experience and Education Level Dashboard

![Work Experience and Educational Level HR Dashboard](https://github.com/yemifatodu/HR_Analysis_meriSkill_project_Internship/raw/main/workexperinceandeducationalevelhrdashboard.png)


**Chart 1: Count of Educational Level**
- **Parameters:** Educational level
- **Visualization:** Bar chart

**Chart 2: Educational Level by Marital Status**
- **Parameters:** Educational level, Marital status
- **Visualization:** Bar chart

**Chart 3: Performance Rating by Education Level**
- **Parameters:** Educational level, Performance rating
- **Visualization:** Bar chart

**Chart 4: Job Satisfaction by Education Level**
- **Parameters:** Educational level, Job satisfaction
- **Visualization:** Bar chart

**Chart 5: Educational Level by Years Work Experience**
- **Parameters:** Educational level, Years work experience
- **Visualization:** Histogram

**Chart 6: Avg. Hourly Rate by Education Level**
- **Parameters:** Educational level, Avg. hourly rate
- **Visualization:** Bar chart

**Chart 7: Count of Job Satisfaction by Education Level**
- **Parameters:** Educational level, Count of job satisfaction
- **Visualization:** Bar chart

**Chart 8: Avg. Monthly Income by Education Level**
- **Parameters:** Educational level, Avg. monthly income
- **Visualization:** Bar chart

**Chart 9: Job Role by Educational Level**
- **Parameters:** Job role, Educational level
- **Visualization:** Bar chart

**Insights:**
- The impact of education on job performance, satisfaction, and income.
- The relationship between marital status and employee performance and overtime.
- Variations in job roles affecting overtime, satisfaction, and turnover rates.
- Correlation between work experience and job metrics like performance, satisfaction, and income.

---

### 3. Employee Demographic and Job Characteristics Dashboard
![Dashboard 1 (3)](https://github.com/yemifatodu/HR_Analysis_meriSkill_project_Internship/raw/main/Dashboard%201%20%283%29.png)



**Chart 1: Employees Gender Segmentation**
- **Parameters:** Gender
- **Visualization:** Pie chart
- **Insight:** Higher representation of female employees (882 females vs. 588 males).

**Chart 2: Work Tenure by Age Segmentation**
- **Parameters:** Age group, Work tenure
- **Visualization:** Bar chart
- **Insight:** Longer tenures are associated with older employees.

**Chart 3: Segmentation of Marital Status**
- **Parameters:** Marital status
- **Visualization:** Pie chart
- **Insight:** Majority are married, followed by single and divorced employees.

**Chart 4: Distance from Home by Marital/Gender Segmentation**
- **Parameters:** Distance from home, Marital status, Gender
- **Visualization:** Bar chart
- **Insight:** Married males live farther from work compared to other groups.

**Chart 5: Overtime Segmentation**
- **Parameters:** Overtime hours
- **Visualization:** Pie chart
- **Insight:** 71.70% of employees do not work overtime.

**Chart 6: Business Travel by Monthly Income Segmentation**
- **Parameters:** Monthly income, Travel frequency
- **Visualization:** Bar chart
- **Insight:** Balanced distribution of business travel frequency across income levels.

**Chart 7: Overtime and Job Role Categorization**
- **Parameters:** Job role, Overtime hours
- **Visualization:** Bar chart
- **Insight:** Research Directors and Sales Executives show higher overtime.

**Chart 8: Segmentation of Job Role**
- **Parameters:** Job role
- **Visualization:** Treemap
- **Insight:** Distribution of employees across various job roles.

**Chart 9: Turnover Analysis**
- **Parameters:** Turnover rate, Job role
- **Visualization:** Bar chart
- **Insight:** Analysis of turnover rates by job role.

---

### 4. Turnover Analysis Dashboard

![Turnover Analysis HR Dashboard](https://github.com/yemifatodu/HR_Analysis_meriSkill_project_Internship/raw/main/turnoveranalysishrdashboard.png)



**Chart 1: Attrition by Employee Count**
- **Parameters:** Gender, Attrition rate
- **Visualization:** Pie charts

**Chart 2: Attrition Rate by Marital Status**
- **Parameters:** Marital status, Attrition rate
- **Visualization:** Bar chart and pie chart

**Chart 3: Attrition Rate by Overtime**
- **Parameters:** Overtime, Attrition rate
- **Visualization:** Bar chart and pie chart

**Chart 4: Attrition Rate by Gender**
- **Parameters:** Gender, Attrition rate
- **Visualization:** Pie chart

**Chart 5: Attrition Rate by Educational Level**
- **Parameters:** Educational level, Attrition rate
- **Visualization:** Pie charts

**Chart 6: Attrition Rate by Job Role**
- **Parameters:** Job role, Attrition rate
- **Visualization:** Bar chart

**Chart 7: Attrition Rate in Each Department**
- **Parameters:** Department, Attrition rate
- **Visualization:** Bar chart

**Chart 8: Attrition Rate Involve in Business Travel**
- **Parameters:** Travel frequency, Attrition rate
- **Visualization:** Bar chart and pie charts

**Insights:**
- Differences in attrition rates across gender, marital status, and educational levels.
- The effect of overtime and business travel on attrition rates.
- Departmental variations in turnover rates.

---

### Summary
The dashboards offer valuable insights into employee behaviors, including overtime work, job roles, education levels, and turnover rates. These insights can inform HR strategies, improve employee satisfaction, and optimize resource allocation.


### Recommendations:


Here are some recommendations:

1. **Address High Attrition Rates in Key Departments:**
   - **Sales** and **Human Resources** departments exhibit the highest attrition rates. To mitigate turnover, consider implementing targeted retention strategies such as enhanced career development programs, competitive compensation packages, and improved work conditions. Conduct exit interviews to identify and address the root causes of attrition.

2. **Optimize Compensation Based on Education and Job Role:**
   - There is a noticeable variation in average monthly income across different education levels and job roles. Ensure that compensation packages are competitive and aligned with industry standards for each role and education level. Consider offering performance-based incentives and career progression opportunities to retain top talent and motivate employees.

3. **Manage Overtime Effectively:**
   - Roles like **Research Scientist** and **Sales Executive** have the highest instances of overtime. Implement better workforce planning and time management strategies to reduce excessive overtime. Consider redistributing tasks or hiring additional staff to manage peak workloads and prevent employee burnout.

4. **Evaluate Impact of Distance from Home:**
   - Despite the consistent performance rating across different distances from home, consider evaluating other factors such as employee satisfaction and work-life balance. If distance does impact job performance or employee satisfaction, explore flexible working arrangements or relocation assistance to improve employee experience.

5. **Focus on Performance Ratings Distribution:**
   - The majority of employees have a performance rating of 3. To drive higher performance levels, establish clear performance goals and provide regular feedback. Implement training and development programs to help employees improve their skills and achieve higher performance ratings.



### Conclusion

The analysis of the HR dataset reveals significant insights into attrition rates, compensation, overtime, distance from home, and performance ratings. Key findings highlight high attrition rates in specific departments, variability in compensation across education levels and job roles, and patterns in overtime and performance ratings.

1. **Attrition**: High attrition rates in the Sales and Human Resources departments suggest a need for targeted retention strategies. Addressing factors contributing to high turnover in these departments can help stabilize the workforce and reduce associated costs.

2. **Compensation**: The disparity in average monthly income across different education levels and job roles indicates a need for alignment with industry standards and performance-based rewards. This will help in attracting and retaining talent and maintaining competitive compensation structures.

3. **Overtime**: The high number of overtime instances in certain job roles calls for better workload management and resource allocation. By addressing overtime issues, the organization can improve employee well-being and productivity.

4. **Distance from Home**: The consistent performance ratings across different distances suggest that distance may not be a significant factor in performance. However, considering employee satisfaction and work-life balance related to commuting can enhance overall job satisfaction.

5. **Performance Ratings**: The majority of employees receive a performance rating of 3. To foster higher performance levels, it is essential to set clear expectations, provide constructive feedback, and invest in employee development.

Implementing these recommendations will help in enhancing employee satisfaction, optimizing compensation, managing workloads effectively, and improving overall performance. These measures are crucial for building a more engaged and productive workforce, ultimately contributing to organizational success.

For a detailed view of the analysis, please refer to the [HR Analysis Dashboard](https://public.tableau.com/app/profile/yemi.fatodu1473/viz/HRAnalysisProjectMeriSkill/Dashboard1).





Here is the sql query used for the H.R, Analysis and Insight

Here’s the SQL query formatted for easy copying:

```sql
USE YEMIFATODU2db;

-- 1. Identify High Attrition Rates by Department
SELECT 
    Department, 
    COUNT(*) AS Total_Employees, 
    SUM(CAST(Attrition AS INT)) AS Attrition_Count,
    (SUM(CAST(Attrition AS INT)) * 1.0 / COUNT(*)) * 100 AS Attrition_Rate
FROM 
    [dbo].[H.R_Analysis]
GROUP BY 
    Department
ORDER BY 
    Attrition_Rate DESC;

-- 2. Average Monthly Income by Education Level and Job Role
SELECT 
    Education, 
    JobRole, 
    AVG(MonthlyIncome) AS Avg_MonthlyIncome
FROM 
    [dbo].[H.R_Analysis]
GROUP BY 
    Education, 
    JobRole
ORDER BY 
    Education;

-- 4. Overtime Hours Analysis by Job Role
SELECT 
    JobRole, 
    SUM(CASE WHEN OverTime = 1 THEN 1 ELSE 0 END) AS Total_OvertimeInstances
FROM 
    [dbo].[H.R_Analysis]
GROUP BY 
    JobRole
ORDER BY 
    Total_OvertimeInstances DESC;

-- 5. Impact of Distance from Home on Job Performance
SELECT 
    DistanceFromHome, 
    AVG(PerformanceRating) AS Avg_PerformanceRating
FROM 
    [dbo].[H.R_Analysis]
GROUP BY 
    DistanceFromHome
ORDER BY 
    DistanceFromHome;

-- 6. Segmented Analysis of Performance Rating by Distance
SELECT 
    CASE 
        WHEN DistanceFromHome BETWEEN 1 AND 5 THEN '1-5'
        WHEN DistanceFromHome BETWEEN 6 AND 10 THEN '6-10'
        WHEN DistanceFromHome BETWEEN 11 AND 15 THEN '11-15'
        WHEN DistanceFromHome BETWEEN 16 AND 20 THEN '16-20'
        WHEN DistanceFromHome BETWEEN 21 AND 25 THEN '21-25'
        ELSE '26+'
    END AS Distance_Bin,
    AVG(PerformanceRating) AS Avg_PerformanceRating
FROM 
    [dbo].[H.R_Analysis]
GROUP BY 
    CASE 
        WHEN DistanceFromHome BETWEEN 1 AND 5 THEN '1-5'
        WHEN DistanceFromHome BETWEEN 6 AND 10 THEN '6-10'
        WHEN DistanceFromHome BETWEEN 11 AND 15 THEN '11-15'
        WHEN DistanceFromHome BETWEEN 16 AND 20 THEN '16-20'
        WHEN DistanceFromHome BETWEEN 21 AND 25 THEN '21-25'
        ELSE '26+'
    END
ORDER BY 
    Distance_Bin;

-- 7. Distribution of Performance Ratings
SELECT 
    PerformanceRating,
    COUNT(*) AS [Count],
    ROUND(CAST(COUNT(*) AS FLOAT) / (SELECT COUNT(*) FROM [dbo].[H.R_Analysis]) * 100, 2) AS [Percentage]
FROM 
    [dbo].[H.R_Analysis]
GROUP BY 
    PerformanceRating
ORDER BY 
    PerformanceRating ASC;
```

