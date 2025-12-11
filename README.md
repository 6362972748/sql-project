# sql-project
# HR Employee Attrition – SQL Project

This project contains a full SQL workflow built using the **HR Employee Attrition dataset**.  
It includes data ingestion, schema design, cleaning, analysis queries, and insight generation.

---

## Project Structure

| File | Description |
|------|-------------|
| `schema.sql` | Contains the SQL schema used to create the `employees` table. |
| `employees_attrition.sql` | Sample queries and analysis scripts based on the attrition dataset. |
| `HR-Employee-Attrition.csv` | The source dataset used in this project. |

---

## Database Schema

The table structure is defined in `schema.sql` and includes fields such as:

- Employee demographics  
- Job role and department  
- Income and performance  
- Satisfaction metrics  
- Attrition information  

Example snippet from schema:  
```sql
CREATE TABLE employees (
    Age INT,
    Attrition VARCHAR(10),
    BusinessTravel VARCHAR(50),
    DailyRate INT,
    Department VARCHAR(50),
    DistanceFromHome INT,
    EducationField VARCHAR(50),
    EmployeeNumber INT PRIMARY KEY,
    EnvironmentSatisfaction INT,
    Gender VARCHAR(10),
    HourlyRate INT,
    JobLevel INT,
    JobRole VARCHAR(100),
    JobSatisfaction INT,
    MaritalStatus VARCHAR(20),
    MonthlyIncome INT,
    MonthlyRate INT,
    NumCompaniesWorked INT,
    Over18 CHAR(1),
    OverTime VARCHAR(10),
    PercentSalaryHike INT,
    PerformanceRating INT,
    RelationshipSatisfaction INT,
    StandardHours INT,
    TotalWorkingYears INT,
    TrainingTimesLastYear INT,
    WorkLifeBalance INT,
    YearsAtCompany INT,
    YearsInCurrentRole INT,
    YearsSinceLastPromotion INT,
    YearsWithCurrManager INT
);

