# Healthcare Patient Records Analysis 

## Project Overview
[Briefly explain what this project analyzes and why you created it.]

## Project Objectives
- Analyze patient demographics and age groups.
- Explore medical conditions and test-result categories.
- Compare admission types and admission trends over time.
- Calculate patient length of stay.
- Explore billing amounts and insurance-provider patterns.
- Identify data-quality issues that may affect reporting.

## Tools and Technologies
- Power BI
- Power Query
- DAX
- GitHub

## Dataset
**Source:** [Add dataset source and link]  
**Rows before cleaning:** [Add number]  
**Rows after cleaning:** [Add number]  
**Columns:** [Add number]

**Fields used:** Age, Gender, Medical Condition, Date of Admission, Discharge Date, Insurance Provider, Billing Amount, Admission Type, Test Results, and other relevant fields.

> Privacy note: Only upload the dataset if its license permits redistribution and it contains no confidential or identifiable patient information.

## Data Cleaning and Preparation

- [ ] Checked for duplicate records.
- [ ] Reviewed missing values.
- [ ] Converted admission and discharge fields to Date type.
- [ ] Standardized inconsistent text values where appropriate.
- [ ] Investigated negative or unusual billing values.
- [ ] Validated data types and key totals after cleaning.

## Key Performance Indicators (KPIs)
List the KPIs included in your dashboard and how you calculated them:
- **Total Patient Records:** [Add definition or measure]
- **Average Age:** [Add definition or measure]
- **Average Length of Stay:** [Add definition or measure]
- **Emergency Admission Rate:** [Add definition or measure]
- **Total Billing Amount:** [Add definition or measure]
- **Average Billing Amount:** [Add definition or measure]
- **Negative Billing Rate:** [Add definition or measure, if used]

## Dashboard Pages and Visuals

### Page 1: Patient & Clinical Overview

**Purpose:** 
To explore patient demographics, medical conditions, admission patterns, and diagnostic test results.

**Visuals included:**
- Monthly Admission Trend
- Patient Distribution by Age Bins
- Patient Gender Distribution
- Patient Volume by Medical Condition
- Diagnostic Test Results
- Admission by Type

**Slicers/Filters:** Admission Date, Medical Condition, Insurance Provider, Test Results.

### Page 2: Operations & Financial Performance

**Purpose:** 
To examine healthcare billing patterns, insurance-provider totals, hospital billing, and length of stay by admission type.

**Visuals included:**
- Billing by Insurance
- Average Billing by Condition
- Length of Stay by Admission
- Top Hospital by Billing

**Slicers/Filters:** Admission Date, Medical Condition, Insurance Provider, Test Results.

## Dashboard Preview
Add screenshots of your final report here.

![Patient and Clinical Overview](images/patient-clinical-overview.png)

![Operations and Financial Performance](images/operations-financial-performance.png)

> Replace the image paths above with the names and locations of your screenshots.

## Key Insights

1. **Medical Conditions:** Arthritis and Diabetes each account for approximately 9.22K records, making them the highest categories displayed in the medical-condition chart.
2. **Length of Stay:** The average length of stay is approximately 15.5 days, with small differences across Emergency, Elective, and Urgent admissions.
3. **Billing Performance:** Cigna has the highest displayed billing total among the five insurance providers, at approximately $284.334 million.

## Recommendations

1. **Review admission trends:** Examine monthly admission patterns to support staffing and resource planning.
2. **Investigate length of stay:** Compare stays by hospital, medical condition, and admission type to identify patterns that may require further review.
3. **Monitor billing quality:** Investigate negative billing values to determine whether they represent adjustments, refunds, or data errors.
4. **Review insurance billing:** Compare billing totals alongside patient volumes to better understand differences between insurance providers.

## Challenges and Learnings
**Challenges:** [Describe any data-quality or technical challenges you encountered.]

**What I learned:** [Describe what you learned about Power Query, DAX, data visualization, or communicating insights.]

## Limitations
- [Mention limitations of the dataset or analysis.]
- Observed patterns do not automatically prove cause and effect.
- Findings should be interpreted within the context of the dataset and its source.

## How to View the Project
1. [Explain where to find the `.pbix` file, if you share it.]
2. [Explain any requirements for opening the report.]
3. [Explain how to view the screenshots or reproduce the analysis.]

## Skills Demonstrated
- Data cleaning and transformation
- Power Query
- DAX and KPI development
- Data visualization
- Dashboard design
- Exploratory data analysis
- Data storytelling

## Author

**Ebunjah**  
**Role:** Certified Data Analyst  
**Portfolio:** https://ebunjah-portfolio.carrd.co/  
**LinkedIn:** [(https://www.linkedin.com/in/ogungbe-ebunoluwa/]

