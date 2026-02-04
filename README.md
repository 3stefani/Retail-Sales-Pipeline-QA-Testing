# Manual Testing – Retail Sales Data Pipeline

## Project Overview

This project focuses on **manual testing of a data pipeline** using a retail sales dataset in CSV format.  
The goal is to validate **data quality**, detect inconsistencies, and document the results through **manual test cases and bug reporting**, simulating a real-world QA scenario for data pipelines.

The project is designed as a **learning and portfolio project** to gain hands-on experience in testing data pipelines, even without prior professional experience in this area.

---

## Dataset

The dataset used in this project is a **public retail sales dataset** obtained from Kaggle:

- **Dataset name:** Retail Sales Dataset  
- **Source:** Kaggle (public dataset)

The original dataset was **intentionally modified** to introduce common data quality issues such as:
- Missing mandatory values
- Invalid numeric values (zero, non-numeric)
- Inconsistent data formats (e.g. currency symbols)
- Incorrect calculated fields
- Duplicate records

These modifications allow realistic **manual testing scenarios** similar to those found in production data pipelines.

> This project is for educational and portfolio purposes only.

---

## Data Pipeline Scope

The simulated data pipeline covers the following stages:

1. **Data ingestion** – Loading the CSV file
2. **Data validation** – Verifying data quality rules
3. **Data cleaning rules (expected behavior)** – Identification of invalid or inconsistent records
4. **Output validation** – Ensuring only valid data meets the expected rules

---

## Testing Scope

Manual testing activities included:

- Validation of mandatory fields
- Validation of numeric fields (Quantity, Price per Unit, Total Amount)
- Format consistency checks
- Duplicate detection
- Logical validations (e.g. Total Amount = Quantity × Price per Unit)
- Regression testing after dataset modifications

All tests were executed **manually**, documenting:
- Preconditions
- Test steps
- Expected results
- Actual results
- Test status (Passed / Failed)

---

## Test Artifacts

The project includes the following testing documentation:

- **Pipeline definition document**
- **Manual test cases (Excel format)**
- **Bug reports for detected issues**
- **Regression test cases**

---

## Tools Used

- CSV files
- Spreadsheet software (Excel / Google Sheets)
- GitHub for version control and documentation

---

## Skills Demonstrated

- Manual testing of data pipelines
- Data quality validation
- Test case design and execution
- Bug reporting
- QA documentation best practices

---

## Next Steps (Planned)

- Automate selected test cases using **Python**
- Implement basic data validation scripts
- Extend coverage to automated regression testing
- Regression test




