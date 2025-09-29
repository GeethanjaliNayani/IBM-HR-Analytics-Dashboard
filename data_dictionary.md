****Data Dictionary – IBM HR Analytics****

**Employee Information**
1. EmployeeNumber → Unique employee identifier (not used for analysis).
2. EmployeeCount → Constant value (always 1).
3. Over18 → Constant value (always “Y”).
4. StandardHours → Constant value (always 80).

**Demographics**
1. Age → Employee age in years.
2. Gender → Gender of the employee (Male/Female).
3. MaritalStatus → Employee’s marital status (Single/Married/Divorced).
4. Education → Education level (1 = Below College, 2 = College, 3 = Bachelor, 4 = Master, 5 = Doctor).
5. EducationField → Field of study (Life Sciences, Medical, Marketing, Technical Degree, HR, Other).

**Job & Role Information**
1. Department → Department name (HR, Research & Development, Sales).
2. JobRole → Specific job title (e.g., Sales Executive, Research Scientist, Manager).
3. JobLevel → Job seniority level (1–5).
4. JobInvolvement → Level of involvement in job (1 = Low, 2 = Medium, 3 = High, 4 = Very High).
5. JobSatisfaction → Satisfaction with job (1 = Low, 2 = Medium, 3 = High, 4 = Very High).
6. EnvironmentSatisfaction → Satisfaction with work environment (1 = Low to 4 = Very High).
7. RelationshipSatisfaction → Satisfaction with relationships at work (1 = Low to 4 = Very High).
8. WorkLifeBalance → Work-life balance rating (1 = Bad, 2 = Good, 3 = Better, 4 = Best).

**Compensation & Benefits**
1. MonthlyIncome → Monthly salary (numeric).
2. DailyRate → Daily rate (numeric).
3. HourlyRate → Hourly rate (numeric).
4. MonthlyRate → Monthly rate (numeric).
5. PercentSalaryHike → % increase in salary (typically 11–25%).
6. StockOptionLevel → Stock option level (0–3).

**Experience & Career Progression**
1. TotalWorkingYears → Total years of professional experience.
2. YearsAtCompany → Number of years with the current company.
3. YearsInCurrentRole → Years spent in current job role.
4. YearsWithCurrManager → Years working under the current manager.
5. YearsSinceLastPromotion → Years since the employee’s last promotion.
6. NumCompaniesWorked → Number of companies employee has worked for in the past.
7. TrainingTimesLastYear → Number of training programs attended in the last year.

**Attrition & Performance**
1. Attrition → Whether the employee left the company (Yes/No).
2. BusinessTravel → Travel frequency (Non-Travel, Travel_Rarely, Travel_Frequently).
3. OverTime → Whether the employee works overtime (Yes/No).
4. PerformanceRating → Performance rating (1 = Low, 2 = Good, 3 = Excellent, 4 = Outstanding).
