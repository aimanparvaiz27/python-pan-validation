# python-pan-validation
# Project Overview:
This project validates and categorizes the Indian PAN numbers from a dataset using Python. It helps keep the data clean by finding which PAN numbers are correct, incorrect, or missing. The project utilizes regular expressions and straightforward Python code to simplify and automate the checking process.

# Instructions

# 1. Data Cleaning & Preprocessing

Identify and handle missing values

Check for duplicates

Handle leading/trailing spaces

Correct letter case

# 2. Custom Validation Functions
Checks for adjacent duplicate characters
Checks if characters form a sequence (e.g., ABCDE or 1234)
# 3. PAN Structure Validation
Regular expression used: ^[A-Z]{5}[0-9]{4}[A-Z]$
Ensures the PAN follows the standard format AAAAA1234A
# 4. Categorization
PANs are classified as:
Valid PAN
Invalid PAN:
# 5. Summary Report
Total records processed
Total valid PANs
Total invalid PANs
Total missing/incomplete PANs

# Key Takeaways
The total records: 10000
The valid pan number: 3193
The invalid pan number: 5832
The invalid missing_count: 975

# Skills & Technologies Applied
Python/Pandas/GoogleColabs
Data Cleaning & Preprocessing
Regular Expressions
Data Validation & Categorization
