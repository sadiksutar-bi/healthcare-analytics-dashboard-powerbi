# Healthcare Analytics Dashboard – Dataset Dictionary

## 1. Dataset Overview

| Attribute | Details |
|---|---|
| Dataset Name | Healthcare Dataset |
| Source File | healthcare_dataset.csv |
| Data Source | Kaggle |
| Total Records | 55,500 |
| Total Columns | 15 |
| Data Format | CSV |
| Admission Date Range | 08-May-2019 to 07-May-2024 |
| Missing Values | None found in initial inspection |

## 2. Column Definitions

| Column Name | Description |
|---|---|
| Name | Patient name |
| Age | Patient age in years |
| Gender | Patient gender |
| Blood Type | Patient blood group |
| Medical Condition | Patient's medical condition |
| Date of Admission | Date the patient was admitted |
| Doctor | Doctor associated with the patient |
| Hospital | Hospital associated with the admission |
| Insurance Provider | Patient's insurance provider |
| Billing Amount | Amount billed for the admission |
| Room Number | Patient's assigned room number |
| Admission Type | Elective, Emergency, or Urgent |
| Discharge Date | Date the patient was discharged |
| Medication | Medication associated with the patient |
| Test Results | Patient test result category |

## 3. Key Dataset Categories

- Gender: Male, Female
- Blood Type: A+, A-, B+, B-, AB+, AB-, O+, O-
- Medical Conditions: Arthritis, Asthma, Cancer, Diabetes, Hypertension, Obesity
- Admission Types: Elective, Emergency, Urgent
- Test Results: Normal, Abnormal, Inconclusive
- Insurance Providers: Aetna, Blue Cross, Cigna, Medicare, UnitedHealthcare

## 4. Initial Data Quality Observations

- 55,500 records and 15 columns were identified.
- No missing values were found during the initial inspection.
- Admission and discharge date fields were successfully interpreted as dates.
- Billing Amount contains negative values; these require investigation before financial conclusions are drawn.

## 5. Usage in Power BI

The dataset supports analysis of:

- Healthcare revenue and billing
- Patient admissions and discharge trends
- Patient demographics
- Medical conditions and blood groups
- Hospital and doctor analysis
- Insurance provider distribution
- Medication and test result analysis

## 6. Source Attribution

Dataset source: Kaggle

The original dataset is retained for this project. The Kaggle dataset page URL and applicable licence details should be added after verification.
