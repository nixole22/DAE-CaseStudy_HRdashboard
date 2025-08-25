# DAE-CaseStudy_HRdashboard
With  a  rapidly  growing  workforce,  organizations  must  ensure  they  have  a clear understanding of their employee demographics, job satisfaction levels, and  promotion  readiness  to  foster  a  productive  and  engaged  work environment.

## Business Context
HR   departments,   managers,   and   executives   need comprehensive  insights  into  various  employee-related  metrics  to  make informed decisions about talent management, development programs, and strategic planning. 
In  this  scenario,  the  organization  "ShopifyMe"  is  focusing  on  evaluating  its current workforce to identify areas for improvement and ensure employee satisfaction and retention. By analyzing these factors, the 
organization aims to  enhance  overall  productivity,  streamline  promotion  processes,  andaddress any disparities in job satisfaction and performance levels.

## Objective
Provide comprehensive analysis of the company's workforce. The goal is to  develop  data-driven  strategies  that  will  enhance  employee  retention,  boost engagement, and optimize the promotion process for both fairness and 
efficiency. Additionally, the CEO seeks to gain a clearer understanding of the potential need for retrenchments and ways to foster a more inclusive and supportive work environment. To provide the CEO with actionable insights, 
your analysis will focus on several key areas:
  1. Total Number of Employees 
  2. Active Employees 
  3. Employee Performance 
  4. Promotion Eligibility 
  5. Job Satisfaction 
  6. Job Satisfaction vs. Attrition

## Approach
Load csv files (HR analytics data.csv and HR Employee data.csv) and also set first row as header
Add following columns by using existing columns
- Distance from office
- Retirement
- Promotion status
- Job satisfaction
- Performance Rating
- Job Level 
Change data type to newly created column as per data of the column●Add Employee name column from into HR analytics data from HR Employee data (merge two tables)
NOTE :
- Whoever had never been promoted since last 10 years and above is now due for promotions.
- The company needs to retrench some employees for some reasons. (condition : employees who are in company from last 18 years  retrench them)
- For Distance from office column, Distance >= 20 then Very Far, Distance >= 10 then close , Distance <10 very close●Job satisfaction label as low, medium, high
- Performance Rating label as low, medium, high●Job Involvement as (Eg. “3 Jobs”, “5 Jobs”)
- Job Level as (Eg. “Level 3”, “Level 5”)
- Create measure as per requirements
  - Total Emp
  - Female
  - % Female
  - Not Due
  - % Not Due for Promotion
  - Due for Promotion
  - % Due for Promotion
  - Active Workers
  - % Active Workers
  - Due for Retrenchment
  - % Due for Retrenchment
- Create a Page and display card and graph to show HR insights
  - Total Number of Employees
  - Active Employees
  - Employee Performance rating graphs
  - Promotion Eligibility
  - Job Satisfaction
  - Job Satisfaction vs. Attrition
  - Percentage of female employees
  - Employee satisfaction vs department
