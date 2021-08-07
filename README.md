# Pewlett-Hackard-Silver_Tsunami
<p align="center">
  <img width="360" height="200" src="https://user-images.githubusercontent.com/74840026/128585331-49b2ea6d-38c9-4ba2-ad1f-a5e9f7dc42e5.png">
</p>

# Overview 
Pewlett-Hackard is looking towards the future by analyzing its current workforce to identify who will be eligible for retirement this year and how many positions will need to be filled.  Using the .csv files provided, we will identify the employees eligiable for retirement and their titles, and also compile a list of employees who will be eligible to participate in a mentorship program.

# Results
## Employees eligiable for retirement
The following criteria was used to determine retirement eligiablity:
- Birth date between 1/1/52 thru 12/31/55
- Last position held
- Currently employed

**Fig. 1-Employees eligiable for retirement by title**

| Title | # eligible for retirement |
| :------------: | :-------: |
| Senior Engineer| 29,414 |
| Senior Staff | 28,254 |
| Engineer | 14,222 |
| Staff | 12,243 |
| Technique Leader | 4,502 |
| Assistant Engineer | 1,761 |
| Manager | 2 |

Our analysis produced the following results:
- 30% of the employee force will be eligiable for retirement(90,398 employees)
- 33% of the total eligiable for retirement have the title of Senior Engineer(29,414 employees)

## Employees eligiable for mentorship program
The following criteria was used to determine mentorship eligiablity:
- Birth date between 1/1/65 thru 12/31/65
- Currently employed

**Fig. 2-Employees eligiable for mentorship program by title**

| Title | # eligible for mentorship |
| :------------: | :-------: |
| Senior Staff| 569 |
| Engineer | 501 |
| Senior Engineer | 169 |
| Staff | 155 |
| Assistant Engineer | 78 |
| Technique Leader | 77 |

Our analysis produced the following results:
- 1,549 employees meet the mentorship participation requirements
- Based on the current mentorship criteria, retiring employees greatly outnumber mentorship participants by 88,849 positions

# Summary
- How many roles will need to be filled as the "silver tsunami" begins to make an impact?
    - If eligiable employees were to retire at the age of 65, roughly 22,600 will be leaving Pewlett Hachard each year.  
- Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
    - The number of mentorship eligiable participants is severly lacking in order to replace the outgoing employees.
    - Suggest that birth date range be widened to increase number of mentorship eligiable employees.

## Two additional queries that may produce more insightful results:
### Retiring employees department gaps
- Query to determining which departments will have the largest number of positions to fill after 'Silver Tsunami' to priortize recruitment programs by department.
 
| Department | Retiring employees | % of total department |
| :------------: | :-------: | :----: |
| Development| 23,622 | 29% |
| Production | 18,892 | 28% |
| Sales | 14,826 | 31% |
| Customer Service | 6,615 | 36% |
| Research | 6,056 | 35% |
| Quality Management | 5,790 | 34% |
| Human Resources | 5,276 | 33% |
| Marketing | 4,717 | 26% |
| Finance | 4,604 | 28% |


### High Potiential Employees based on length of service and promotion progress
- Query to view current employees length of service and promotion progress to find high potiential employees to include in mentorship program
