# Healthcare Patient Records Analysis — Data Cleaning Report

## 1. Project Overview

This project involves analyzing healthcare patient records to understand patient demographics, hospital admissions, medical conditions, billing, insurance coverage, diagnostic results, and length of hospital stay.

Data cleaning was an important part of preparing the dataset for analysis and developing an interactive Power BI dashboard.

## 2. Dataset Description

- **Dataset Name:** Healthcare Patient Records
- **Dataset Source:** Provided by the course instructor for learning and data analysis practice.
- **Initial Number of Records:** 55,500
- **Number of Columns:** 15
- **Analysis Tool:** Microsoft Power BI
- **Data Preparation Tool:** Power Query
- **Visualization Tool:** Power BI

### Dataset Columns

The dataset contains the following fields:

1. Patient Name
2. Age
3. Gender
4. Blood Type
5. Medical Condition
6. Date of Admission
7. Doctor
8. Hospital
9. Insurance Provider
10. Billing Amount
11. Room Number
12. Admission Type
13. Discharge Date
14. Medication
15. Test Results

## 3. Data Quality Issues Identified

During data inspection, the following issues were identified:

### 3.1 Duplicate Records

The dataset contained 534 exact duplicate rows.

- Initial records: 55,500
- Duplicate rows identified: 534
- Unique records after removing exact duplicates: 54,966

### 3.2 Date Format Inconsistencies

The admission and discharge date columns were stored as text rather than proper date data types.

This required attention to ensure accurate date calculations, monthly trend analysis, and length-of-stay calculations.

### 3.3 Inconsistent Text Capitalization

Some patient names contained inconsistent capitalization.

Standardizing text capitalization improves consistency when displaying and reviewing patient information.

### 3.4 Negative Billing Amounts

The dataset contained 108 records with negative billing amounts.

These records required validation to determine whether the values represented data entry errors, billing adjustments, refunds, or other legitimate transactions.

Negative values should not automatically be deleted without understanding their meaning.

### 3.5 Missing Values

The initial data inspection identified no missing values in the dataset.

This was useful for assessing the completeness of the available records.

## 4. Data Cleaning and Preparation Steps

The following operations were relevant to preparing the dataset for analysis:

### 4.1 Duplicate Record Handling

- Identified exact duplicate rows.
- Removed duplicate rows where appropriate.
- Retained unique records for subsequent analysis.

### 4.2 Date Data Type Correction

- Converted admission dates to the appropriate date data type.
- Converted discharge dates to the appropriate date data type.
- Checked date fields to support time-based analysis and length-of-stay calculations.

### 4.3 Text Standardization

- Reviewed inconsistent capitalization in patient names.
- Applied consistent text formatting where appropriate.

### 4.4 Billing Data Validation

- Identified records with negative billing amounts.
- Flagged these records for further validation.
- Avoided assuming that all negative values were errors without checking their meaning.

### 4.5 Data Type Validation

Reviewed relevant columns to ensure that numerical fields, dates, and text fields used appropriate data types for analysis.

## 5. Data Validation and Quality Checks

After preparing the dataset, the following checks were important:

- Confirming the number of records after duplicate removal.
- Checking that admission and discharge dates were valid.
- Verifying that length of stay was calculated correctly.
- Reviewing negative billing amounts.
- Checking the consistency of categorical fields used in dashboard visuals.
- Confirming that the dataset supported the required Power BI measures and visualizations.

## 6. Tools Used

- **Power Query:** Data inspection, transformation, and cleaning.
- **Power BI:** Data modeling, DAX calculations, and dashboard development.
- **DAX:** Calculating key performance indicators and supporting analytical measures.

## 7. Outcome

The data preparation process helped establish a more consistent dataset for healthcare analysis.

The prepared data supported the development of an interactive dashboard covering patient demographics, admissions, medical conditions, diagnostic results, insurance providers, billing, and length of hospital stay.

Data quality checks also highlighted negative billing amounts that required further investigation.

## 8. Conclusion

Data cleaning and validation are essential steps in healthcare analytics because data quality affects the reliability of reported metrics and the conclusions drawn from them.

This project demonstrates the importance of identifying duplicate records, standardizing data formats, validating numerical values, and preparing data for meaningful analysis in Power BI.
