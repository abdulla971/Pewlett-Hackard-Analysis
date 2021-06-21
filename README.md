# Pewlett-Hackard-Analysis
An analysis is performed of company employee data by using the dynamic ability of the relational database PostgresSQL in order to transform and query the data.

##  Resources 
- Python 3.8.8, JupyterLab 3.0.14
- [PostgreSQL 12.3](https://www.postgresql.org/), [Pgadmin](https://www.pgadmin.org/) 

## Overview
In this project an analysis is performed on a large-scale number of employees data for a specific company with more than 300,000 employees. Pewlett Hackard is need of assistance as it is reviewing the company metrics, specifically the retirement data, and want us to determine who is eligible for retirement based on the data analysis.

## Data Process  
By creating ERD we are able to map the data process schema and the relationships this allows us to know how the data files interact with each other in the database.

With the database mapped the company data is then imported into the data base in the csv format. Having the data imported and formatted within the data base, we can use SQL to retrieve the information from the data base. The database can be utilized by using custom filters and groupings, and by creating custom tables.

## Results / Findings
- 30.13% or 90,398 are eligible for retirement out of the 300,024 total employees.
- Senior Engineer, Senior Staff and Engineer's are most likely close to retirement with 23.9% that is the largest share. 

### Employees Eligible for Retirement
- Of the 300,024 employees within the company, 90,398 (30.13%) are eligible for retirement. 
- Senior Engineer, Senior Staff and Engineer's hold the largest share (23.9%) of employees likely preparing for retirement.
- Development(with 25.45%),Production(with 22.30%) and Sales(with 7.27%) are the departments with the highest retirees.

### Employees Eligible for Mentorship
- Mentorship/training for an internal promotion is only available for 1549 employee who are qualified.

