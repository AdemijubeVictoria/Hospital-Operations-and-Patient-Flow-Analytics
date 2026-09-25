# Hospital Operations and Patient Flow Analytics


**Author:** Ademijube Victoria Olamide

**Date:** 2026-09-25

 --- 
 ## Executive Summary
The Hospital Operations & Patient Flow Analytics project was developed to provide a consolidated view of hospital activity and identify operational factors that may affect patient experience. The analysis focuses on appointments, waiting time, departments, doctors, treatments and procedures, patient outcomes and insurance type.

The dataset contains 2,000 appointments involving 501 patients and 25 doctors across a six-month period. The dashboard reports an overall average waiting time of 21 minutes, with a maximum waiting time of 40 minutes. Approximately 60.6% of appointments were completed within the defined waiting-time target.

Department-level analysis shows meaningful variation in waiting-time performance in relation to the departments target times. Emergency has the strongest target compliance at 74%, while Outpatient has the lowest at 39%. Radiology, Orthopaedics and Emergency have average waiting times below their respective targets, whereas Paediatrics, Outpatient and Cardiology are at or above their targets.
The analysis also highlights differences in appointment volume and resource allocation. Paediatrics records the highest appointment volume (494) and has six doctors, while Radiology records the lowest volume (156) and has two doctors.

---
## Problem Statement 
The management of TediCare General Hospital has noticed increasing patient complaints about long waiting times. Some patients leave before being seen, doctors are overwhelmed on certain days, and hospital resources don't seem to be allocated efficiently.

 --- 

## Business Questions
-	Why are waiting times increasing?
-	Which departments experience the longest delays?
-	Which days are busiest?
-	Are more doctors needed?
-	Which patients wait the longest?
-	Which departments receive the poorest feedback?

--- 

## Datasets 
| Table | fields |
| -------------- | ------------- |
| Appointments	| Appointment ID, Patient ID, Doctor ID, Department, date, time, status, waiting time |
| Department	| Department ID, Department Name, target waiting time |
| Doctors	| Doctor ID, department, employment type |
| Patients | 	Patient ID, Insurance type |
| Staff | Schedule	Doctor ID, schedule ID, hours worked |
| Treatment	| Treatment type, cost, appointment ID |
| Feedback	| Rating, comment |

--- 

## Tools & Techniques 
- Microsoft Excel:  data cleaning 
- Power query: data cleaning / transformation
- Data cleaning and transformation in Excel
- Power BI: Dashboard layout and visualization, KPI design 


--- 

## Dashboard Features
**Key KPIs**
-	Total patients: 501
-	Total doctors: 25
-	Appointments: 2000
-	Average wait time: 21 mins


**Visuals**
- Total Appointment by Department
- Overall Target Wait Time Compliance
- Total Appointment by Status
- Total Appointment by  Month, day, hour.
- Target Vs Avg Wait Time by Department
- Wait Time Target Compliance by Department
- Feedback Category by Appointment Status
- Average Rating by Department

 
--- 
**Data Quality Issues**
- Staff Schedule table
•	The shift column has blank cells.
•	The schedule was only shown for January and February 2025.
- Feedback table
•	Comment and rating columns had blank cells.
- Treatment table
•	The cost column had blank cells
- Patients table
•	The gender column had data inconsistencies.


---
**Data Cleaning and Transformation**
This was done using Excel and Power Query.
-	Gender column was standardized using the “Find and Replace” function in Excel.
-	Blank cells in the comment column were replaced with “No response” in Power Query
-	Derived columns such as appointment day, appointment month, appointment hour, waiting time in minutes, consultation time in minutes


---
## Key Findings 
- Paediatrics department recorded the hightest appointments (494).
- This is followed by Orthopaedics (405) and Outpatient (399). 
- These three departments account for about 65% of all appointments.
Doctor workload is relatively balanced across department.
However, this is not enough to determine whether more doctors are needed.
More than 45% (789) of the completed appointments met the department-specific waiting time target.
This is still a large percentage.
1,696 appointments were completed. 
184 cancellations and 120 no-shows.
Outpatients shows the greatest concern 40% above target.
Emergency is below its departmental target.
However, its target wait time should be assessed, given the urgent nature of emergency care.
Outpatient: highest above-target appointments (52.13%)
Emergency: lowest above-target appointments (21.12%)
Doctors’ Workload is uneven
Varying from 64 -100 appointment
Dr E5: highest workload / part-time
Dr H8: lowest workload/ full-time
Scheduled capacity for each doctor ranges from 450-496 hours.
However, recorded consultation duration was only 24-37 hours per doctor.
Only a small portion of their scheduled working time was spent in recorded consultation.
The remaining working hours may be spent on other clinical duties such as ward rounds.
Long wait time may be driven by workflow factors or unrecorded activities.
About 18% of the feedback suggest a need for improvement.
16% cited long wait time.
Orthopaedics and Emergency have the highest average rating at 3.1.
Radiology is lowest at 2.8


--- 

## Recommendations 
-Investigate the cause of delay by conducting a process review to determine whether delays come from late clinic start, registration, or doctor availability.
- Standardize clinic workflows.
- Implement continuous performance monitoring.
- Reduce no-shows and cancellations through active reminders and better appointment-management process.
- Review appointment scheduling and capacity allocation based on doctor availability.
- Strengthen data quality controls.

 --- 

## Contact 
Ademijube Victoria Olamide

Email: _ademijubevictoria2@gmail.com_  

[LinkedIn](https://www.linkedin.com/in/victoria-ademijubeutm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)

