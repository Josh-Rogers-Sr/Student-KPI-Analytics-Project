# Student-KPI-Analytics-Project

This is a project to track KPIs related to student success at a fictional university. I utilized SQL for data extraction and transformation and Python (via Google Colab) for statistical analysis and data visualization.

## Files
`clean_student_kpi.csv` – Cleaned dataset used for analysis
`temp.avg_department_gpa.csv` – SQL output of GPA averages per department
`temp.percent_at_risk.csv` – SQL output of student risk percentages by year
`temp.advising_sessions_attended.csv` – SQL output showing advising session counts vs. risk
`Student KPI Analysis.db` – SQLite database containing the full dataset and queries
`Student_KPI_dataset_analysis.ipynb` – Colab notebook performing analysis and plotting

## Objective
Track average GPA by department
Analyze trends in student risk levels across academic years
Evaluate the impact of advising sessions on student risk status
Build clean, visual summaries  for dashboards or reports

## SQL (.db file included in repo)
Using a SQLite database, the following tables/queries were created:
temp.percent_at_risk
temp.advising_sessions_attended
temp.avg_department_gpa

## Python
Average GPA by Department - interactive bart chart showing departments ranked by average GPA
At-Risk Students by Year - line graph showing how the percentage of at-risk students changes across academic year
Advising Sessions vs. Risk - bar chart showing how the numbe rof advising sessions correlates with student risk
