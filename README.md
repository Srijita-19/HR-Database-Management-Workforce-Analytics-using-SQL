# HR Database Management & Workforce Analytics using SQL

## 📌 Project Overview
This project focuses on the management and analysis of a relational Human Resources database using Microsoft SQL Server.
The project involved working with interconnected HR data covering employees, departments, jobs, salaries, managers, dependents, locations, countries, and regions.
The objective was to use SQL to transform raw relational data into meaningful workforce, compensation, organizational, geographical, and data-quality insights that can support HR reporting and business decision-making.
## 🎯 Business Problem
Human Resources departments manage large volumes of interconnected employee and organizational data. Simply storing this information is not sufficient; organizations need efficient methods to extract, compare, validate, and analyze the data.
This project addresses business questions such as:
* How many employees are present in the organization?
* How is the workforce distributed across departments?
* What are the salary patterns across different jobs and departments?
* What is the total payroll?
* Which job categories have higher compensation?
* How are employees distributed geographically?
* Which employees have dependents?
* How many employees report to each manager?
* What does the organizational hierarchy look like?
* Are there missing or inconsistent employee records?
* How can SQL be used to generate reliable HR reports from multiple related tables?
## 🎯 Project Objectives
The major objectives of the project were to:
1. Understand and work with a relational HR database.
2. Retrieve and combine information from multiple interconnected tables.
3. Analyze employee and department-level workforce distribution.
4. Perform salary and payroll analysis.
5. Analyze job roles and compensation patterns.
6. Examine employee-manager relationships.
7. Analyze dependent information.
8. Study geographical workforce distribution.
9. Identify data-quality issues.
10. Apply advanced SQL techniques to generate business-oriented insights.
## 🗃️ Database Overview
The project uses a relational HR database consisting of multiple interconnected entities.
## Core Tables
| Table         | Description                                                                                                                      |
| ------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| `employees`   | Stores employee-level information including employee identifiers, personal details, salary, department and manager relationships |
| `jobs`        | Contains job titles and job-related information                                                                                  |
| `departments` | Stores organizational department information                                                                                     |
| `dependents`  | Contains information about employee dependents                                                                                   |
| `locations`   | Stores workplace and location information                                                                                        |
| `countries`   | Contains country-level geographical information                                                                                  |
| `regions`     | Groups countries into broader geographical regions                                                                               |
These tables are connected through primary and foreign-key relationships, allowing employee information to be analyzed across organizational, compensation, management, and geographical dimensions.
# 📊 Analysis Performed

**1. Workforce Analysis**
The employee database was analyzed to understand the overall workforce structure.
The analysis included:
* Total employee count
* Department-wise employee distribution
* Job-wise employee distribution
* Workforce concentration
* Organizational structure
The project dataset contained approximately 39 employees across the analyzed HR database.

**2. Department Analysis**
Employees were grouped by department to understand workforce distribution.
The analysis identified differences in:
* Department headcount
* Average salary
* Total payroll
* Workforce concentration
The Shipping department had the highest employee count in the analyzed dataset, with 7 employees.

**3. Salary Analysis**
Employee salary information was analyzed using descriptive statistics.
The analysis covered:
* Average salary
* Median salary
* Minimum salary
* Maximum salary
* Salary distribution
* Job-level compensation
* Department-level compensation
For the analyzed dataset:
* Average salary: approximately 8,053.85
* Median salary: approximately 7,700

**4. Payroll Analysis**
Salary information was aggregated to understand total payroll expenditure.
The analyzed dataset had a total payroll of approximately - 314,100
Payroll analysis provides an understanding of how employee compensation contributes to overall workforce costs.

**5. Job & Compensation Analysis**
The relationship between job roles and compensation was examined to identify salary patterns across different positions.
The analysis included:
* Employee count by job
* Average salary by job
* Minimum and maximum salaries
* Comparison of compensation across job categories
The Executive job category recorded the highest average salary in the analyzed results, at approximately 19,333.33.

**6. Employee-Manager Analysis**
Employee-manager relationships were analyzed using relational queries and self-joins.
The analysis helps identify:
* Who reports to whom
* Number of employees under each manager
* Management hierarchy
* Reporting relationships
This demonstrates how SQL can be used to analyze organizational structures stored within relational databases.

**7. Dependent Analysis**
The `employees` and `dependents` tables were analyzed to understand employee-dependent relationships.
The analysis included:
* Employees with dependents
* Employees without dependents
* Number of dependents
* Employee-dependent relationships
The dataset contained approximately 30 dependents.

**8. Geographical Analysis**
Employee information was connected with:
Locations
     ↓
Countries
     ↓
Regions
This allowed workforce distribution to be analyzed at different geographical levels.
The project database contained:
* 7 locations
* 25 countries
* 4 regions
The geographical analysis demonstrates how relational databases can support workforce planning across multiple locations.

# 📌 Conclusion
The HR Database Management & Workforce Analytics project demonstrates how Microsoft SQL Server can be used to manage and analyze interconnected Human Resources data.
Through SQL joins, aggregations, subqueries, CASE statements, EXISTS/NOT EXISTS, set operations, self-joins, and analytical functions, the project examines workforce distribution, compensation, payroll, organizational hierarchy, employee dependents, geographical distribution, and data quality.
The project strengthened practical capabilities in SQL development, relational database analysis, HR analytics, data validation, business reporting, and client-oriented data interpretation.
