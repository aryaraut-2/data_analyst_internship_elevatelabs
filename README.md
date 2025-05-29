# 🧹 Data Cleaning – Medical Appointment Dataset

## Overview
This project involved cleaning and preprocessing the **Medical Appointment dataset** to make it suitable for analysis. The dataset contained patient appointment records with various inconsistencies.

## Tools Used
- Python (Pandas)

## Key Cleaning Steps Performed
- ✅ Identified and handled **missing values** using `.isnull()` and appropriate imputations.
- ✅ Removed **duplicate records** using `.drop_duplicates()`.
- ✅ Standardized **text fields** like gender and neighborhood to ensure consistency.
- ✅ Converted **date columns** (ScheduledDay and AppointmentDay) to proper `datetime` format.
- ✅ Renamed column headers to be **lowercase** and removed spaces for better readability.
- ✅ Verified and corrected **data types** (e.g., `age` as integer, dates as datetime).

## Deliverables
- 📁 `cleaned_medical_appointments.csv` – Cleaned dataset
- 📝 This short summary (README) of changes made
