# Test Automation Project

Automated test framework for validating the Pixels Suite Chat Translator application using Playwright and Excel-based test cases.

## Project Details

| Field | Value |
| --- | --- |
| Repository | https://github.com/madhawadiyanath/asiment-itpm.git |
| IT Number | IT23844506 |
| Author | Madhawa |
| Assignment | ITPM Assignment |

## Overview

This project automates end-to-end testing for the Pixels Suite Chat Translator. It reads test cases from an Excel workbook, runs them against the frontend, captures the actual output, and compares results automatically.

## Features

- Browser automation with Playwright
- Excel-driven test execution
- Auto-detection of input, expected output, actual output, and status columns
- Configurable frontend URL and file paths
- Result tracking for pass/fail reporting
- Designed for Singlish to Sinhala translation validation

## Technologies Used

- Python 3.x
- Playwright
- OpenPyXL

## Default Configuration

- Frontend URL: https://www.pixelssuite.com/chat-translator
- Excel file: Assignment 1 - Test cases.xlsx
- Sheet name: Test cases

### Supported Input Columns

- Singlish
- Input
- Singlish Input
- Test Input
- Source
- Sentence
- Text

### Supported Expected Output Columns

- Sinhala
- Expected_Output
- Expected Output
- Expected output
- Expected
- Expected Sinhala

### Supported Actual Output Columns

- Actual_Output
- Actual Output
- Actual output
- Actual

## Setup Instructions

1. Install dependencies:

   ```bash
   pip install playwright openpyxl
   ```

2. Install Playwright browsers:

   ```bash
   playwright install
   ```

3. Place the Excel test case file in the project folder or update the file path in the script.

## How to Run

Run the automation script:

```bash
python it23844506_test_automation.py
```

Optional arguments:

```bash
python it23844506_test_automation.py --excel-file <path> --sheet-name <sheet> --frontend-url <url>
```

## Project Structure

```text
asiment-itpm/
├── it23844506_test_automation.py
├── it23844506_Test_cases.xlsx
├── it23844506_Requiredment.txt
├── it23844506_README.md
└── README.md
```

## Notes

- Environment variables can override default configuration values.
- Make sure the workbook headers match the supported column names.
- Adjust file paths if your Excel file is stored elsewhere.

## License

This project is submitted for academic purposes as part of the ITPM assignment.

---

Created by Madhawa for IT23844506.
