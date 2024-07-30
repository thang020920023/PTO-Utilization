# PTO-Utilization

Context: A company with offices in Charlotte, Nashville, and Cleveland provides consulting services in Technology, Accounting, and Management. The company has recently implemented an unlimited PTO policy.

Task: As a data analyst, I want to create a report to monitor the utilization of this PTO policy. The report should track how much time employees are actually working compared to their potential working hours, and provide insights into trends and potential issues.

Specific Requirements:

- Employee Utilization Rate (%)

- This rate is always 100% for hourly employees and subcontractors. For salaried employees, the utilization rate is calculated using the following formula:

- Utilization Rate (%) = Actual Billable Hours (*) / Potential Billable Hours ()**

(*) Actual billable hours
(**) Potential billable hours

On working days (Monday to Friday), the potential billable hours are 8 hours. On weekends (Saturday and Sunday), the potential billable hours are 0 hours.

+ Data: Analyze data from various sources, including budgets, hours worked, and employee information.
+ KPIs: Calculate utilization rates based on actual working hours versus potential working hours.
+ Granularity: Provide detailed data at the daily, weekly, and monthly levels.
+ Customization: Allow managers to view data specific to their branch or division.
+ Forecasting: Predict future trends in PTO usage.
+ Visualization: Create clear and easy-to-understand visualizations of the data.
+ Overall Goal: To provide a tool for management to make informed decisions about staffing, budgeting, and the overall impact of the unlimited PTO policy.
