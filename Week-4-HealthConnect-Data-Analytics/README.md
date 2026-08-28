# Week 4 – HealthConnect Data Analytics

## Project
HealthConnect Clinic Experience Lab

## Project Focus
Improving Patient Appointment Attendance and Healthcare Support Using Data and AI.

## Week 4 Objective
The Week 4 Data Analytics work focused on understanding the HealthConnect appointment dataset, assessing initial data quality, identifying relevant variables, defining business questions and potential KPIs, and establishing an initial analytical approach.

## Work Completed

- Reviewed the HealthConnect Appointment Dataset.
- Reviewed the HealthConnect Data Dictionary.
- Assessed the dataset structure and data quality.
- Confirmed 5,000 appointment records and 18 variables.
- Checked for duplicate records.
- Identified variables containing missing values.
- Reviewed appointment outcome categories.
- Examined key categorical variables.
- Identified relevant business questions.
- Proposed five potential KPIs.
- Defined the initial analysis approach.
- Documented assumptions, limitations, risks and dependencies.

## Key Initial Findings

The dataset contains 5,000 appointment records and 18 variables.

The appointment outcomes are:

- No-show: 2,423
- Attended: 2,314
- Cancelled: 263

No duplicate records were identified.

Missing values were identified in:

- `reminder_channel`: 1,366
- `distance_to_clinic_km`: 90
- `waiting_time_minutes`: 60

The 1,366 missing values in `reminder_channel` correspond to the 1,366 appointments where no reminder was sent and will therefore require contextual interpretation during data preparation.

## Potential KPIs

1. Appointment No-Show Rate
2. No-Show Rate by Previous No-Show History
3. No-Show Rate by Reminder Status
4. No-Show Rate by Booking Lead-Time Group
5. No-Show Rate by Appointment Time/Day

## Week 5 Focus

The next stage will focus on data preparation and exploratory analysis of appointment attendance and no-show patterns, followed by KPI calculation and development of initial data-driven insights.

## Files

- `HealthConnect_Week4_Data_Inspection.ipynb` – Initial dataset inspection notebook.
- `HealthConnect_Week_4_Data_Analytics_Initial_Analysis.docx` – Week 4 Initial Analysis Document.
