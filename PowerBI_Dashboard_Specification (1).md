# Medical & Hospital Analytics Dashboard — Power BI Build Spec

## Data
Import `Medical_Hospital_Dashboard_Data.xlsx` with sheets: Patients, Doctors, Departments.

## Relationships
- Patients[Doctor] -> Doctors[Doctor] (many-to-one)
- Patients[Department] -> Departments[Department] (many-to-one)

## KPI cards
- Total Patients = COUNTROWS(Patients)
- Average Length of Stay = AVERAGE(Patients[Length_of_Stay])
- Average Treatment Cost = AVERAGE(Patients[Treatment_Cost])
- Average Satisfaction = AVERAGE(Patients[Satisfaction])

## Visuals
1. Clustered/bar chart: Patients by Department
2. Donut chart: Patient Outcomes
3. Bar chart: Top Diagnoses
4. Bar chart: Patients per Doctor
5. Slicers: Department, Doctor, Gender, Admission Type, Outcome

## Suggested dashboard title
Hospital Analytics Dashboard

## Important
The included screenshot is a visual reference/mockup. A `.pbix` file itself must be created/saved by Power BI Desktop; this package contains the data and exact build specification needed to recreate it.
