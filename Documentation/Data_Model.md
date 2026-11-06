# Data Model Documentation

## 1. Model Overview

The Healthcare Analytics Dashboard uses a single-table data model.

**Table Name:** `healthcare_dataset`

The table contains patient, admission, hospital, insurance, medical, and billing information.

## 2. Model Structure

The current model contains one table:

- `healthcare_dataset`

No relationships between multiple tables are configured in the current model.

## 3. Calculated Column

**Age Bucket**

A calculated column used to group patients into age categories for demographic analysis.

## 4. Data Fields

The table includes the following fields:

- Admission Type
- Age
- Age Bucket
- Billing Amount
- Blood Type
- Date of Admission
- Discharge Date
- Doctor
- Gender
- Hospital
- Insurance Provider
- Medical Condition
- Medication
- Name
- Room Number
- Test Results

## 5. Model Design Note

The current report uses a single-table structure. The available columns are used directly in dashboard visuals, filters, and analysis.

No separate fact or dimension tables have been created in this version.

## 6. Future Enhancement

The model can be enhanced in a future version by evaluating a star schema with separate fact and dimension tables, depending on reporting requirements and performance needs.
