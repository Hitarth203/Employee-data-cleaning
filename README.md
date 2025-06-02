# Employee Data Cleaning with Pandas

This project demonstrates how to clean messy employee data using Python and pandas.

## Dataset
- `messy_employees.csv`: The raw data with missing values, inconsistent formats, and typos.
- `cleaned_employees.csv`: The cleaned and standardized dataset.

## Cleaning Performed
- Removed unnecessary columns and duplicate rows
- Filled missing values in Age, Experience, and Salary
- Converted Experience to numeric (e.g., "Ten" → 10)
- Standardized department names (e.g., "i.t.", "Information Tech" → "it")
- Removed special characters from employee names

## How to Run
Make sure pandas is installed:
```bash
pip install pandas

