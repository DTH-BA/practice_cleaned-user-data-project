# Excel Data Cleaning Practice – Simulated User Dataset

This project is a hands-on **practice exercise** using a **simulated dataset** to mimic common real-world data cleaning tasks. The entire process was performed using **Microsoft Excel**, focusing on identifying and correcting common data quality issues.

## Objective
- Practice essential data cleaning techniques using Excel.
- Apply logical steps to standardize and validate inconsistent entries.
- Build readiness for real-world data cleaning tasks in business or analytics roles.

## Cleaning Tasks Performed

| Field           | Cleaning Action |
|----------------|-----------------|
| `User_ID`       | Checked for duplicates; ensured each ID is unique |
| `Name`          | Trimmed extra spaces and applied Proper Case formatting |
| `Gender`        | Standardized to `Male`, `Female`, or `Unknown` |
| `Signup_Date`   | Validated and standardized date formats |
| `Country`       | Normalized values like `usa`, `U$A`, `ca` to `USA`, `Canada`, or `Unknown` |
| `Age`           | Removed or corrected outliers (e.g., `-1`, `9999`) |
| `Phone`         | Removed formatting characters; converted to 10-digit number |
| `Account_Status`| Mapped misspelled or inconsistent values to `Active` or `Inactive` |

## Files Included
- `raw_users_data_large_shuffled.xlsx` – Simulated raw dataset for practice
- `cleaned_users_data.xlsx` – Final cleaned dataset (Excel)
- `README.md` – Documentation of the cleaning process

## Tools & Techniques
- **Microsoft Excel** only
  - Functions used: `IF`, `LOWER`, `PROPER`, `SUBSTITUTE`, `TEXT`, `VALUE`, `TRIM`, `LEN`
  - Filtering, conditional formatting, and duplicate detection
  - Manual review and logic-based corrections

## Notes
- This is a **learning project** using **fake/mock data** to simulate the types of issues encountered in real datasets.
- It does **not** use real user data or originate from a production environment.
- The focus is on developing **hands-on Excel cleaning skills** commonly required in analytics workflows.
