# Salud y Vida Reports for Su Clinica Familiar

Tracking spreadsheet: https://docs.google.com/spreadsheets/d/1oIV83j1o2GKYMuBiDcqhBNOR5_yad8xv6l1P8B_qhMQ/edit?usp=sharing

Salud y Vida specific reports for Su Clinica Familiar, a Federally-Qualified Health Center in the Rio Grande Valley region of Texas.

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

## Reports:

1. Active Salud y Vida patients
2. Recently added Salud y Vida patients
3. Recently ended Salud y Vida patients
