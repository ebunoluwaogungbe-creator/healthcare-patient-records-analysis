# Healthcare Patient Records Analysis — Power BI Dashboard

## 1. Project Overview

This project uses Microsoft Power BI to analyze healthcare patient records and explore patient demographics, clinical indicators, hospital admissions, billing performance, insurance providers, and length of hospital stay.

The dashboard is organized into two pages: Patient & Clinical Overview and Operations & Financial Performance.

## 2. Project Objectives

- Analyze patient demographics and age-group distribution.
- Examine monthly admission trends and admission types.
- Identify frequently recorded medical conditions.
- Explore diagnostic test-result distributions.
- Monitor healthcare billing and insurance-provider performance.
- Compare average billing across medical conditions.
- Analyze length of stay by admission type.
- Identify hospitals with the highest total billing.

## 3. Tools Used

- Power BI
- Power Query
- DAX


## 4. Dashboard Pages

### Page 1: Patient & Clinical Overview

This page presents the main patient and clinical indicators.

**Key Performance Indicators**
- Total Patients/Records
- Average Age
- Average Length of Stay
- Emergency Admission Rate
- Total Doctors

**Visualizations**
- Monthly Admission Trend
- Patient Distribution by Age Bins
- Patient Gender Distribution
- Patient Volume by Medical Condition
- Diagnostic Test Results
- Admission by Type

**Purpose**

This page provides an overview of patient demographics, admission patterns, recorded medical conditions, and diagnostic test results.

### Page 2: Operations & Financial Performance

This page focuses on billing, insurance, hospital comparisons, and length of stay.

**Key Performance Indicators**
- Total Billing
- Average Billing
- Emergency Admission Rate
- Negative Billing Rate
- Total Insurance Providers

**Visualizations**
- Billing by Insurance
- Average Billing by Condition
- Length of Stay by Admission
- Top Hospital by Billing

**Purpose**

This page helps users explore billing patterns, compare insurance-provider totals, examine average billing by medical condition, and review hospital billing performance.

## 5. Interactive Features

The dashboard includes filters for:
- Admission Date
- Medical Condition
- Insurance Provider
- Test Results

These filters allow users to explore different subsets of the available records.

## 6. Key Observations

- The dashboard displays approximately 54.97K patient records.
- Arthritis is among the medical conditions displayed, with approximately 9.22K records.
- The average length of stay displayed is approximately 15.5 days.
- Emergency admissions account for approximately 32.9% according to the displayed KPI.
- The dashboard compares billing totals across five insurance providers.
- The operations page highlights the hospitals with the highest total billing in the displayed data.

These observations describe the dashboard's displayed values and should be checked against the underlying measures before being used for formal reporting.

## 7. How to View the Dashboard

The dashboard was developed in Microsoft Power BI.

To explore the report, open the `.pbix` file in Power BI Desktop if it is included in this repository.

**Dashboard screenshots:** See the `images` folder.

**Published dashboard:** Add a shareable Power BI link here if one is available.

## 8. Conclusion

This dashboard demonstrates how Power BI can be used to summarize healthcare records, explore clinical and operational patterns, and communicate findings through interactive visualizations.
