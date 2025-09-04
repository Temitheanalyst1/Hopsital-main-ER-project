# Hopsital main ER project Insights  – SQL Analysis

#### The objective of this analysis is to evaluate patient demographics, admission patterns, wait times, and satisfaction levels in order to identify trends, measure healthcare service performance, and support data-driven decision-making

## Dataset used
- <a href=https://github.com/Temitheanalyst1/Hopsital-main-ER-project/blob/main/Hospital%20ER.csv>dataset</a>

## KPIquestions
1.	Total number of patient 

 

2.	Average patients age 
 
3.	Total patient by gender
4.	Total number of patients by race 

5.	Total patient by age group 
    
6.	Average number of patients by Gender and Total wait time 

 6b.      Total number of patients by Race and Total wait time

7.	Total number of patients by race and avg wait time 

8.	Average patient satisfactory score

9.	patient Admission Rate 

11.	Admitted vs. Not admitted BY Department_referral

- <a href=https://github.com/Temitheanalyst1/Hopsital-main-ER-project/blob/main/hospital%20potofolio%20project.docx>SQL query</a>

## screenshot from powerBI
<img width="1817" height="1057" alt="image" src="https://github.com/user-attachments/assets/f01ea1d9-cb1e-4fa8-944d-0430e7e286e9" />

## Central Insights Summary


#### Wait Times by Age Group
Adolescents: 35.51 min
Adults: 35.51 min
Children: 36.36 min
Elderly: 35.07 min (one instance) and 35.08 min (duplicate)
Infants (babies): 35.07 min
Young Children: 33.47 min
Average wait across all groups: approximately 35 minutes

## Problem Statement
Uniform wait times across groups may mask discrimination of clinical urgency.
Lack of real-time information or communication compounds patient stress.
No prioritization for vulnerable individuals (e.g., infants, elderly).
Operational inefficiencies—staffing shortages, triage delays, room availability.

## Solutions to Improve Wait Times and Patient Experience
1. Triage-Based Prioritization
Implement a more dynamic triage system that fast-tracks vulnerable groups (e.g., infants, children, elderly) based on clinical and developmental needs.
2. Transparent Communication
Provide estimated wait times upon arrival and periodic updates. Even overestimating can improve patient satisfaction.
Inform families of any delays and reasons to reduce anxiety.
3. Low-Acuity Fast Track
Establish a 'fast lane' or express stream for minor issues or non-critical patients to relieve congestion and reduce wait times for vulnerable groups.
4. Operational Efficiency
Increase staffing during peak hours.
Optimize room turnover and diagnostic workflows.
Consider AI-enabled tools to assist in diagnostic triage (e.g., ED-Copilot—shown to reduce ED wait times by half).
5. Comfort and Perception Enhancements
Design waiting areas with age-appropriate comforts (toys, seating, calmer environments).
Staff periodic check-ins, especially for families with children or elderly patients.
6. Benchmarking and Targets
Aim to reduce average wait time to ≤ 20 minutes if feasible.
For ED-like settings, work toward the 15-minute goal for initial provider contact.
Track performance and monitor improvements for different patient groups.


