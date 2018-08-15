# Employee Scheduler

Employee Scheduler is built using the below components and concepts.

1).Net Core 2 & Visual studio 2017
2)Scheduler API- Http Get-web api with repository pattern and Unity for DI
3)UI- Angular JS with bootstrap

Datasource: Employee.xml,Create Engineers list by parsing the xml file

Deliverables:

API:http://localhost:63989/api/EmployeeScheduler/GetSchedules

UI:http://localhost:63989/

Assumptions:
Employee Count:10
Schedule Span: 2 weeks
Schedule Start date : Upcoming Monday

Business Rules Implemented:
An engineer can do at most one-half day shift in a day.
An engineer cannot have two afternoon shifts on consecutive days. 
Each engineer should have completed one whole day of support in any 2 week period. 
Any Engineer who has completed 1 whole day of support is exempted from the schedule.


