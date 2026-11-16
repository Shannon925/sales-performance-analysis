Are there blank cells?
NO 

Are there duplicate records?
YES

Are dates formatted correctly?
YES

Are sales and profit columns stored as numbers?
YES 

Are there unusual or incorrect values?
NO

# Data Inspection Report

## 1. Project Overview

**Project:** Sales Performance Analysis  
**Dataset:** Financial Sample  
**Tool used:** Microsoft Power BI Desktop and Power Query

## 2. Data Quality Checks

### Missing Values
The dataset was inspected using Power Query's Column Quality feature.

**Finding:** No empty values were identified in the inspected columns.

**Conclusion:** The dataset does not currently show missing-value issues in the columns checked.

### Data Errors
The dataset was checked for errors using Power Query's Column Quality feature.

**Finding:** No errors were identified.

**Conclusion:** No data conversion or profiling errors were detected during the inspection.

### Data Types
The data types of the columns were reviewed.

**Finding:** The data types appeared correct for the fields inspected.

**Conclusion:** The numerical, text and date fields are appropriately typed for further analysis.

## 3. Sales Value Inspection

The Sales column was examined using Power Query's Column Profile feature.

| Measurement | Value |
|---|---:|
| Minimum Sales | 1,655.08 |
| Maximum Sales | 1,159,200.00 |
| Sales Range | 1,155,544.92 |

**Observation:** There is a considerable difference between the minimum and maximum sales values.

**Conclusion:** The higher sales values should be investigated further to determine whether they represent legitimate high-value sales or potential outliers.

## 4. Duplicate Records

**Status:** Not yet checked.

Duplicate records will be investigated before completing data preparation.

## 5. Overall Inspection Conclusion

The initial inspection indicates that the dataset has no identified missing values or errors in the columns checked, and its data types appear suitable for analysis.

However, duplicate records and unusually high or low values still require further investigation.

The dataset will undergo additional validation before being used for SQL analysis and Power BI visualisation.

## 6. Next Steps

- Investigate duplicate records.
- Examine unusual sales and profit values.
- Confirm the consistency of the dataset.
- Prepare the dataset for analysis.
- Answer the five business questions using SQL and Power BI.
