# Salud y Vida Reports for Su Clinica Familiar

Tracking spreadsheet: https://docs.google.com/spreadsheets/d/1oIV83j1o2GKYMuBiDcqhBNOR5_yad8xv6l1P8B_qhMQ/edit?usp=sharing

Salud y Vida specific reports for Su Clinica Familiar, a Federally-Qualified Health Center in the Rio Grande Valley region of Texas.

## Reports:

1. Active Salud y Vida patients
2. Recently added Salud y Vida patients
3. Recently ended Salud y Vida patients

## Plan:

**TimeToDateSuClinicaSyV**

*Views include:*
* Summary
* Last 1 week
* Last 2 weeks
* Last 3 weeks
* Last month
* Last 2 months
* Last 4 months
* Last 6 months
* Last 8 months
* Last 10 months
* Last 1 year
* Last 1 year 6 months
* Last 2 years
* Last 2 years 6 months
* Last 3 years
* Last 3 years 6 months
* Last 4 years

*For Summary view:* (Worked on by Edward Yao)
* Active total Salud y Vida patients
* Inactive total Salud y Vida patients
* Active total Su Clinica patients
* Active Su Clinica and Active Salud y Vida patients
* Active Su Clincia and Inactive Salud y Vida patients
* Su Clinica patients eligible for Salud y Vida
* % of eligible Su Clinica patients in SyV
* All Su Clinica patients with diagnosis of diabetes and no HbA1c in 6 months
* All Su Clinica patients who are part of Salud y Vida with diagnosis of diabetes and no HbA1c in 6 months
* All Su Clinica patients with last HbA1c > 9 (HbA1c can come from Lab value or Salud y Vida)
* All Su Clinica patients who are part of the Salud y Vida program with last HbA1c > 9 (HbA1c can come from Lab value or Salud y Vida surveys)
* All Su Clinica patients who are part of the Salud y Vida program who have not been prescribed diabetes medication

*Notes:*
* Three columns for HbA1c values:
* 1: Su Clinica-only LOINC code
* 2: Salud y Vida survey values
* 3: WC Lab HbA1c value

*For all other views:*
* Salud y Vida enrolled during time period specified
* Salud y Vida discharged during time period specified
* Salud y Vida participants added during time period specified, who are also Su Clinica patients
* Salud y Vida participants removed during time period specified, who are also Su Clinica patients
* Salud y Vida patients who have visited Su Clinica in the time period
* Salud y Vida patients who have not visited Su Clinica in the time period

*Notes:*
* Certain range of NDC numbers described what it is for (need to be diabetes medication)

**YearlyQuarterlySummarySuClinicaSyV:**

*Views include:*
* 2014 Q1234
* 2014 Q12
* 2014 Q34
* 2014 Q1
* 2014 Q2
* 2014 Q3
* 2014 Q4
* 2015 Q1234
* 2015 Q12
* 2015 Q34
* 2015 Q1
* 2015 Q2
* 2015 Q3
* 2015 Q4
* 2016 Q1234
* 2016 Q12
* 2016 Q34
* 2016 Q1
* 2016 Q2
* 2016 Q3
* 2016 Q4
* 2017 Q1234
* 2017 Q12
* 2017 Q34
* 2017 Q1
* 2017 Q2
* 2017 Q3
* 2017 Q4

*For each view:*
* Salud y Vida enrolled during time period specified
* Salud y Vida discharged during time period specified
* Salud y Vida participants added during time period specified, who are also Su Clinica patients
* Salud y Vida participants removed during time period specified, who are also Su Clinica patients
* Salud y Vida patients who have visited Su Clinica in the time period
* Salud y Vida patients who have not visited Su Clinica in the time period

## Salud y Vida Program Progress

*Views Include*
* 2015 - Active
* 2015 - Inactive
* 2016 - Active
* 2016 - Inactive
* 2017 - Active
* 2017 - Inactive

*For each view:*
* Enrollment
* M03
* M06
* M09
* M12
* M15
* M18
* M21
* M24

*Notes:*
* In Active, make sure to only include Active Salud y Vida patients
* In Inactive, make sure to only include Inactive Salud y Vida patients

## Variables available:

**Labs**

| Code | Name | Value | Facility |
| ---- | ---- | ----- | -------- | 
| LOINC:4548-4 | Hemoglobin A1c/Hemoglobin.total in Blood | Yes | |
| WC_LAB:123 | HbA1C | Yes | |
| RGV_Chronicles:RGV001 | Name: patient_lab_hgba1c | Yes | Salud y Vida |
| CPT:83036 | Hemoglobin; glycosylated (A1C) | No | |

**Salud y Vida Specific**

| Initiative Name | Code | Value |
| --------------- | ---- | ----- |
| syv: mhp | 142563996 | Start Date |
| syv: mhp | 142563996 | End Date |
| syv: pjd | 142563995 | Start Date |
| syv: pjd | 142563995 | End Date |
| syv: sph brownsville | 142563991 | Start Date |
| syv: sph brownsville | 142563991 | End Date |
| syv: sph2 | 142563993 | Start Date |
| syv: sph2 | 142563993 | End Date |

| Survey Name | Question | Answer |
| ----------- | -------- | ------ |
| SYV: Patient Status | 1. Patient status: | Active |
| SYV: Patient Status | 1. Patient status: | **Completed** |
| SYV: Patient Status | 1. Patient status: | **Discharged** |
| SYV: Patient Status | 1. Patient status: | Inactive |
| SYV: Patient Status | 1. Patient status: | Referred |
| SYV: Patient Status | 1. Patient status: | **Successfully Completed** |
| SYV: Patient Status | 2. Date effective: | DATE |

**Bold** = Completed program

**Su Clincia Specific**

| Interface Name | Domain Filter | Period |
| -------------- | ------------- | ------ |
| GE Centricity-CCDA-Rio Grande Valley HIE-Su Clinica | Demographics | January 2014 - December 2018 (4 OR criteria)|

*Note:* Can use Interface filter to identify people who are new to Su Clinica in specified time ranges

## Reports Not Scoped:
4. Track all Su Clinica patients and their HbA1c
5. Both Su Clincia and Salud y Vida HbA1c separately preferred
* Baseline HbA1c to the latest HbA1c to see if program is working
⋅* Going to have to calculate the improvement
⋅* Percent improvement
⋅* Going to have to drill down into each individual
* Create dashboards they present

**To-Do**
* Access requests for Wellcentive
* Meeting next week
