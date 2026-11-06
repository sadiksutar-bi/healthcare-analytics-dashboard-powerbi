# DAX Documentation

## Overview

The healthcare dashboard primarily uses the columns available in the `healthcare_dataset` table directly in Power BI visuals.

No separate explicit DAX measures have been created for the current dashboard.

## Calculated Column

### Age Bucket

The `Age Bucket` field is a calculated column used to group patients into age categories for demographic analysis.

- **Field:** Age Bucket
- **Type:** Calculated Column
- **Purpose:** Categorizes patients by age to support age-wise analysis.

## Direct Column Usage

The dashboard uses existing dataset columns in visuals, including:

- Billing Amount
- Age
- Admission Type
- Blood Type
- Gender
- Hospital
- Insurance Provider
- Medical Condition
- Medication
- Test Results
- Date of Admission

## Note

This documentation reflects the current Power BI report implementation. Additional DAX measures can be documented if they are introduced in future versions.
