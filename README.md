
# PharmaPlus Hospitals: Leads Flow Dashboard

![PharmaPlus Dashboard](https://github.com/user-attachments/assets/389a300b-af3a-4292-8833-df8bd4fe7d83)

## Project Overview

This project demonstrates the development of a Power BI dashboard for PharmaPlus Company, providing actionable insights into hospital operations based on patient data. The dataset includes key metrics such as patient admissions, diagnoses, billing information, and more.

### Dataset Description

The dataset used in this dashboard contains the following columns:
- **Patient_ID**: Unique identifier for each patient.
- **Admit_Date**: Date when the patient was admitted to the hospital.
- **Discharge_Date**: Date when the patient was discharged from the hospital.
- **Diagnosis**: Medical diagnosis for the patient.
- **Bed_Occupancy**: Bed occupancy status during the patient's stay.
- **Test**: Medical tests conducted.
- **Doctor**: The doctor assigned to the patient.
- **Followup Date**: Scheduled date for follow-up appointments.
- **Feedback**: Patient feedback after discharge.
- **Billing Amount**: Total amount billed for the patient.
- **Health Insurance Amount**: Amount covered by health insurance.

### Dashboard Filters
The following filters are applied to generate insights:
- **Main Filter**: Patient_ID for individual patient analysis.
- **Admit Date**: Filter data by the patient admission date.
- **Discharge Date**: Filter data by the patient discharge date.
- **Follow-up Date**: Filter by the patient's scheduled follow-up date.
- **Bill Amount**: Filter patients based on their total billing amounts.
- **Date Range Filter**: Allows selecting a specific date range for any of the above filters.

### Visualizations
The dashboard features four main graphs to visualize key metrics:

1. **Bed Occupancy (Bar Graph)**: This graph illustrates the bed occupancy trends across the hospital. It shows how many beds are occupied over time.
  
2. **Feedback Volume per Doctor (Pie Graph)**: This pie chart breaks down the volume of feedback received for each doctor, helping to assess patient satisfaction levels per doctor.

3. **Diagnosis-wise Patient Count (Funnel Graph)**: The funnel chart categorizes the number of patients diagnosed with various medical conditions, providing a clear picture of the distribution of different diagnoses.

4. **Bed Occupancy (Line Graph)**: This line graph tracks bed occupancy patterns over time, allowing for the identification of trends in patient inflow and bed utilization.

### Dashboard Features
- **Main Patient Report**: The dashboard provides an overall analysis and visualization of all patients.
- **Individual Patient Report**: Users can filter by Patient_ID to focus on a specific patient and view personalized data such as admit/discharge dates, feedback, billing details, and more.

### Technology Stack
- **Power BI**: For data visualization and dashboard creation.
- **Excel**: Used as the dataset source for patient records.

### How to Use the Dashboard
1. Load the dataset into Power BI.
2. Apply the filters based on patient data such as admit date, discharge date, billing amounts, etc.
3. Utilize the individual Patient_ID filter to get specific patient reports.
4. Explore the visualizations to understand the hospital’s bed occupancy trends, patient feedback distribution, and diagnosis patterns.

### Conclusion
This Power BI dashboard provides a comprehensive view of the hospital's operations, offering insights that can drive better decision-making in terms of resource management, patient care, and operational efficiency.

---

This report gives a clear summary of your project and should work well for your GitHub README. You can also include screenshots of the dashboard for visual reference.
