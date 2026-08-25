# nsfas-student-expenditure-analysis
Data cleaning, transformation, and pivot table analysis of NSFAS higher education allowance disbursements and student expenditure patterns using Microsoft Excel
# NSFAS Student Allowance & Expenditure Data Cleaning Project

##  Overview
This project focuses on cleaning, restructuring, and analyzing a dataset containing NSFAS allowance disbursements and student expenditure patterns across various South African higher education institutions.

##  Data Cleaning & Transformation Steps
- **Header Correction:** Standardized column names and fixed typographical errors (e.g., corrected `Tanspot_Allowance_ZA` to `Transport_Allowance_ZAR`).
- **Deduplication:** Removed duplicate student records to ensure data integrity.
- **Text Normalization:** Applied `TRIM` and `PROPER` formatting across institution names and accommodation categories.
- **Currency & Type Formatting:** Stripped non-numeric currency characters (`R`, `,`) and converted fields into formatted numbers (`ZAR`).
- **Calculated Fields:** Recalculated total approved amounts, actual expenditures, and unspent balance metrics for mathematical consistency.
- **Pivot Summaries:** Built summary tables analyzing allowances and expenditures by University and Accommodation Type.

##  Repository Files
- `NSFAS_Student_Expenditure_Fully_Cleaned.xlsx` - Cleaned Excel workbook containing raw data and summary sheets.
- `NSFAS_Student_Expenditure_Messy.xlsx` - Original uncleaned dataset.

##  Key Analytical Insights
- **Private Accredited Accommodation:** Represents the highest individual allowance category (averaging ~R46,222/year).
- **Transport Allowances:** Commuter/Home-based students average R7,500/year in direct transport support while drawing zero accommodation allowance.
