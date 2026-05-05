# IT23355446 – IT3040 Assignment 1

## Project Title

Automated Testing for Singlish to Sinhala Transliteration System



## Repository

https://github.com/mayashi99/-Playwright-project



## Project Structure

IT23355446/

* IT23355446.py                → Playwright automation script
* IT23355446-Test cases.xlsx   → Excel file with test cases & results
* README.md                    → Project documentation



## Technologies Used

* Python
* Playwright (UI Automation)
* OpenPyXL (Excel handling)



## How to Run the Project

1. Open terminal inside project folder

2. Install dependencies
   pip install playwright openpyxl
   playwright install

3. Run the automation script
   python IT23355446.py --excel "IT23355446-Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator"



## Output

* Results are automatically written to the Excel file
* Columns updated:

  * Actual Output
  * Status (PASS / FAIL)



## Test Case Details

* Total Test Cases: 50+
* Test Type: Negative Testing

### Covered Scenarios:

* Mixed language inputs (Singlish + English)
* Spelling variations
* Emojis & symbols
* Real-world scenarios (banking, travel, apps)
* System-related messages (errors, logs)
* Numeric and date inputs



## Important Notes

* This system uses strict comparison
* Even small differences in Sinhala output (spacing, formatting, spelling) will result in FAIL

### Possible Reasons for Failures:

* Transliteration inconsistencies
* Mixed language complexity
* UI timing delays



## Student Information

* Student ID: IT23355446
* Module: IT3040
* Assignment: Assignment 1 (Option 1)



## Final Status

✔ Automation script working
✔ Excel-based validation completed
✔ Test coverage includes multiple edge cases



## Submission Notes

* All required files are included
* Project is fully runnable
* No additional setup required beyond dependencies

