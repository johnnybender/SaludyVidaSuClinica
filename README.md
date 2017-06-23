# Salud y Vida Reports for Su Clinica Familiar

Salud y Vida specific reports for Su Clinica Familiar, a Federally-Qualified Health Center in the Rio Grande Valley region of Texas.

## Reports:

1. Active Salud y Vida patients
2. Recently added Salud y Vida patients
3. Recently ended Salud y Vida patients

## Plan:

**TimeToDateSuClinicaSyV**

*Views include:*
Summary
Last 1 week
Last 2 weeks
Last 3 weeks
Last month
Last 2 months
Last 4 months
Last 6 months
Last 8 months
Last 10 months
Last 1 year
Last 1 year 6 months
Last 2 years
Last 2 years 6 months
Last 3 years
Last 3 years 6 months
Last 4 years

*For Summary view:*
Active total Salud y Vida patients
Inactive total Salud y Vida patients
Active total Su Clinica patients
Active Su Clinica and Active Salud y Vida patients
Active Su Clincia and Inactive Salud y Vida patients
Su Clinica patients eligible for Salud y Vida
% of eligible Su Clinica patients in SyV

*For all other views:*
Salud y Vida enrolled during time period specified
Salud y Vida discharged during time period specified
Salud y Vida participants added during time period specified, who are also Su Clinica patients
Salud y Vida participants added during time period specified, who are also Su Clinica patients

**YearlyQuarterlySummarySuClinicaSyV:**

*Views include:*
2014 Q1234
2014 Q12
2014 Q34
2014 Q1
2014 Q2
2014 Q3
2014 Q4
2015 Q1234
2015 Q12
2015 Q34
2015 Q1
2015 Q2
2015 Q3
2015 Q4
2016 Q1234
2016 Q12
2016 Q34
2016 Q1
2016 Q2
2016 Q3
2016 Q4
2017 Q1234
2017 Q12
2017 Q34
2017 Q1
2017 Q2
2017 Q3
2017 Q4

*For each view:*
SyV Added
SyV Su Clinica Added
SyV Removed
SyV Su Clinica Removed

## Needs defining:
4. Track all Su Clinica patients and their HbA1c
5. Both Su Clincia and Salud y Vida HbA1c separately preferred

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
