# Medical Data History Analysis

A SQL-based healthcare data analysis project exploring hospital records, patient demographics, admissions, and physician specialties.

---

## 📌 Project Overview
- **Database:** `medical_data`
- **Focus:** Patient demographics, hospital admissions, medical diagnoses, allergy tracking, and physician workloads.
- **Source Data:** Provided in CSV format under [`data/`](file:///c:/Users/ugale/Naresh%20IT/8_Projects/project_3/data).
- **Queries:** Comprehensive SQL solutions covering 34 analytical questions in [`hospital.sql`](file:///c:/Users/ugale/Naresh%20IT/8_Projects/project_3/hospital.sql).

---

## 🗄️ Database Schema & Datasets
- **`patients`**: `patient_id`, `first_name`, `last_name`, `gender`, `birth_date`, `city`, `province_id`, `allergies`, `height`, `weight`
- **`admissions`**: `patient_id`, `admission_date`, `discharge_date`, `diagnosis`, `attending_doctor_id`
- **`doctors`**: `doctor_id`, `first_name`, `last_name`, `specialty`
- **`province_names`**: `province_id`, `province_name`

---

## 🔍 Key Insights & Analysis Covered
- **Demographics & Filtering:** Gender distribution, patients without allergies (`NKA`), patients by birth decade (1970s, 2010), height/weight filtering.
- **Health Metrics:** Obesity classification (`BMI >= 30` calculation using `height` and `weight`).
- **Hospital Operations:** Same-day discharge admissions, admission count trends by day of the month, repeat admissions for identical diagnoses.
- **Physician & Department Insights:** Patient admissions mapped to attending doctors and specific specialties (e.g., Epilepsy cases attended by specific doctors).
- **Regional Breakdown:** Patient count grouped by city and province, height aggregations across provinces.

---
