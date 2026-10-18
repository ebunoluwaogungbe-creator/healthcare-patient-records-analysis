# Healthcare Patient Records Analysis — Insights and Recommendations

## 1. Project Overview

This project analyzes healthcare patient records using Microsoft Power BI to explore patient demographics, medical conditions, hospital admissions, diagnostic test results, billing, insurance providers, and length of hospital stay.

## 2. Key Findings

### 2.1 Patient Demographics

The dashboard displays approximately 54.97K patient records. The gender distribution is nearly equal, with approximately 27.50K records for each gender.

### 2.2 Medical Conditions

Arthritis and Diabetes each display approximately 9.22K records, followed by Hypertension and Obesity at approximately 9.15K each.

These values suggest that the displayed medical-condition categories have relatively similar record counts.

### 2.3 Admission Patterns

The monthly admission trend varies throughout the year. Elective admissions are the largest of the three admission types displayed, at approximately 18.5K, followed by Urgent at 18.4K and Emergency at 18.1K.

The dashboard reports an emergency admission rate of 32.9%. The definition of this measure should be confirmed against the underlying calculation.

### 2.4 Length of Stay

The dashboard reports an average length of stay of approximately 15.5 days.

The operations page displays averages of approximately 15.6 days for Emergency, 15.5 days for Elective, and 15.4 days for Urgent admissions.

These small differences should be interpreted as descriptive patterns rather than evidence of a cause.

### 2.5 Diagnostic Test Results

The dashboard displays three diagnostic result categories: Abnormal, Normal, and Inconclusive.

The displayed values are approximately 18.44K for Abnormal, 18.33K for Normal, and 18.20K for Inconclusive.

### 2.6 Billing and Insurance

The dashboard displays total billing of approximately $1.4 billion and average billing of approximately $25.5K.

Cigna has the highest displayed billing total among the five insurance providers, at approximately $284.334 million.

The negative billing rate is displayed as 0.2%. These records should be reviewed to establish whether they represent legitimate adjustments or data quality issues.

### 2.7 Billing by Medical Condition

The average billing displayed across medical conditions ranges from approximately $25.15K to $25.80K.

Further analysis could investigate whether these differences remain meaningful after considering other relevant factors.

### 2.8 Hospital Billing

Johnson PLC has the highest displayed total billing among the hospitals shown, at approximately $1.081 billion.

This represents billing recorded in the dataset and should not be interpreted as a measure of hospital quality or profitability.

## 3. Recommendations

### 3.1 Review Admission Trends

Examine monthly admission patterns to support discussions about staffing and resource planning.

### 3.2 Investigate Length-of-Stay Differences

Explore length of stay by hospital, medical condition, and admission type to identify patterns that may require further investigation.

### 3.3 Monitor Billing Quality

Investigate negative billing records and determine whether they represent refunds, adjustments, or data errors.

### 3.4 Review Insurance Billing Patterns

Compare billing totals across insurance providers while considering differences in patient volume and other relevant factors.

### 3.5 Monitor Medical-Condition Patterns

Use the observed distribution of medical conditions to guide further descriptive analysis. The dashboard alone cannot establish disease causes or determine treatment priorities.

### 3.6 Improve Reporting and Validation

Validate KPI definitions, date ranges, and calculation logic before using the results for operational decisions.

## 4. Limitations

- The dataset was provided by the course instructor.
- The analysis describes the records available in the dataset and may not represent all healthcare facilities.
- Total billing does not necessarily represent revenue collected or profit.
- The dashboard does not establish causal relationships.
- Unusual billing values require validation before conclusions are drawn.
- Clinical decisions should not be made from these descriptive findings alone.

## 5. Conclusion

The analysis uses Power BI to present healthcare data in an interactive format, bringing together patient demographics, admissions, diagnostic test results, billing, insurance comparisons, and length of stay.
