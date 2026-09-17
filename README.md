# Customer Database Management & Data Cleaning

## Project Overview

This project focuses on cleaning, standardizing, and validating a customer database using Microsoft Excel.

The objective was to transform a raw customer dataset containing data-quality issues into a clean, organized, and reliable dataset suitable for further analysis and reporting.

## Business Scenario

A business has collected customer information from different sources. Before the database can be used for reporting, analysis, or decision-making, the information needs to be reviewed for accuracy and consistency.

The raw dataset contained several data-quality issues, including duplicate records, missing values, inconsistent formatting, and invalid dates.

The task was to identify these issues, apply appropriate cleaning procedures, and produce a validated customer database.

## Project Objectives

- Inspect the raw customer database.
- Identify duplicate customer records.
- Remove excess duplicate records.
- Standardize inconsistent data.
- Identify missing values.
- Identify invalid registration dates.
- Validate the cleaned dataset.
- Document the data-quality issues and actions taken.

## Dataset

The raw dataset contained **5,040 customer records** and 11 fields.

### Main Fields

- Customer ID
- First Name
- Last Name
- Gender
- Age
- Phone
- Email
- City
- State
- Registration Date
- Customer Status

## Data Quality Issues Identified

| Issue | Records | Action |
|---|---:|---|
| Duplicate customer records | 40 excess rows | Removed duplicate rows |
| Inconsistent name formatting | 120 | Standardized formatting |
| Inconsistent city formatting | 90 | Standardized formatting |
| Missing email values | 75 | Retained and documented |
| Missing age values | 60 | Retained and documented |
| Invalid registration dates | 50 | Left blank and documented for review |
| Inconsistent customer-status formatting | 80 | Standardized values |
| Extra spaces in state values | 50 | Removed extra spaces |

## Data Cleaning Process

### 1. Data Inspection

The raw dataset was reviewed to identify inconsistencies, missing values, duplicates, and invalid values.

### 2. Duplicate Removal

Customer IDs were used as the primary reference for identifying duplicate customer records.

A total of **40 excess duplicate rows** were removed.

### 3. Text Standardization

Inconsistent capitalization and unnecessary spaces were corrected in relevant fields, including names, cities, states, and customer status.

### 4. Missing-Value Review

Missing email and age values were identified and retained as missing rather than replacing them with fabricated information.

### 5. Date Validation

Invalid registration-date values that could not be reliably corrected were left blank and documented for review.

### 6. Final Validation

The cleaned dataset was checked to confirm that duplicate Customer IDs and duplicate complete rows were no longer present.

## Results

The cleaning process reduced the dataset from:

**5,040 raw records → 5,000 cleaned records**

### Final Quality Checks

| Quality Check | Result |
|---|---:|
| Raw records | 5,040 |
| Cleaned records | 5,000 |
| Duplicate rows removed | 40 |
| Duplicate Customer IDs remaining | 0 |
| Duplicate complete rows remaining | 0 |

## Tools Used

- **Microsoft Excel**

## Skills Demonstrated

### Data Entry & Data Management

- Data organization
- Record management
- Data verification
- Spreadsheet management

### Data Cleaning

- Duplicate detection
- Duplicate removal
- Missing-value identification
- Text standardization
- Data formatting
- Invalid-value identification

### Data Quality

- Data validation
- Quality checks
- Error identification
- Documentation

## Project Files

- `data/raw/customer_database_raw.xlsx` — original dataset containing controlled data-quality issues.
- `data/cleaned/customer_database_cleaned.xlsx` — cleaned and validated dataset.
- `documentation/data_quality_summary.xlsx` — documented quality checks and cleaning actions.
- `screenshots/` — selected before-and-after evidence of the cleaning process.

## Key Learning Outcome

This project demonstrates the importance of validating data before using it for analysis or reporting.

A clean dataset provides a more reliable foundation for subsequent analytical work and helps reduce errors in business reporting and decision-making.
