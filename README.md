# Medical & Hospital Analytics Dashboard

A Power BI dashboard project for analyzing hospital patients, doctors, departments, treatment costs, admissions, diagnoses, outcomes, and patient satisfaction.

## Dashboard Preview

![Medical Hospital Dashboard](Medical_Hospital_Dashboard_Screenshot%20(1).png)

## Project Overview

This project demonstrates how Power BI can be used to turn hospital operational data into an interactive analytics dashboard.

The dashboard provides an overview of:

- Patient volume
- Doctor workload
- Department-wise patient distribution
- Patient outcomes
- Common diagnoses
- Treatment costs
- Length of hospital stay
- Patient satisfaction
- Admission types

## Key KPIs

- Total Patients
- Average Length of Stay
- Average Treatment Cost
- Average Satisfaction

## Dashboard Visuals

1. Patients by Department
2. Patient Outcomes
3. Top Diagnoses
4. Patients per Doctor
5. KPI cards
6. Interactive filters for Department, Doctor, Gender, Admission Type, and Outcome

## Dataset

The project uses synthetic hospital data for demonstration and portfolio purposes.

### Tables

- `Patients` — patient demographics, admissions, diagnoses, treatment costs, length of stay, satisfaction, and outcomes
- `Doctors` — doctor IDs, specializations, experience, and patient workload
- `Departments` — department bed capacity and doctor counts

## Power BI Data Model

```text
Patients[Doctor] → Doctors[Doctor]
Patients[Department] → Departments[Department]
