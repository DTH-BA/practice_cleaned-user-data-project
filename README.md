# Cleaned User Data Project

This project demonstrates the process of cleaning a real-world user dataset using Microsoft Excel. The goal is to prepare the data for further analysis by removing inconsistencies, formatting issues, and invalid entries.

## Objectives
- Practice data cleaning and formatting in Excel
- Standardize user-related fields (e.g., Gender, Country, Phone)
- Handle missing or malformed values

## Files
- `raw_users_data.xlsx`: The original raw dataset and the proleaned User Data Project

This project demonstrates the process of cleaning a real-world user dataset using Microsoft Excel. The goal is to prepare the data for further analysis by removing inconsistencies, formatting issues, and invalid entries.

## Objectives
- Practice data cleaning and formatting in Excel
- Standardize user-related fields (e.g., Gender, Country, Phone)
- Handle missing or malformed values

## Files
- `raw_users_data.xlsx`: The original raw dataset and proccessing
- `cleaned_users_data.xlsx`: Final cleaned dataset
- `README.md`: Project overview and documentation

## Cleaning Steps
- **Gender**: Standardized to `Male`, `Female`, or `Unknown`
- **Signup Date**: Parsed and validated
- **Country**: Normalized to `USA`, `Canada`, or `Unknown`
- **Age**: Removed outliers like `-1`, `9999`, and corrected obvious errors
- **Phone**: Reformatted to 10-digit strings
- **Account Status**: Mapped fuzzy values (e.g., `inactiv`, `acitve`) to `Active`/`Inactive`

## Tools Used
- Microsoft Excel (Formulas, Conditional Formatting)
- Manual inspection & formula-based cleaning
