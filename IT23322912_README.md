# ITPM Assignment 1 - Test Automation

## 📌 Project Overview
This project contains the automated test suite for Assignment 1 of the Information Technology Project Management (ITPM) module. It uses **Playwright** and **Python** to automate testing for a Chat Translator web application, processing test cases directly from an Excel spreadsheet.

## 👨‍🎓 Student Details
* **Name:** Viraj Kosala
* **Student ID:** IT23322912
* **Module:** ITPM (IT23322912)

## 🚀 Features
* **Excel-Driven Testing:** Automatically reads input strings and expected outputs from `.xlsx` files.
* **Dynamic Locator Strategy:** Robustly identifies UI elements even if placeholders or labels change slightly.
* **Result Logging:** Writes "Actual Output" and "Status" (PASS/FAIL/COLLECTED) back into the Excel file.
* **Headless Support:** Ability to run tests in the background or watch them live in the browser.

## 🛠️ Tech Stack
* **Language:** Python 3.13+
* **Automation Framework:** Playwright
* **Data Handling:** Openpyxl (Excel)

## ⚙️ Setup and Installation

1. **Clone the repository:**
   ```powershell
   git clone https://github.com/VirajKosala/ITPM-ASSIGMENT-1---IT23322912.git
   cd IT23322912_Test_Automation
   ```

2. **Install dependencies:**
   ```powershell
   pip install -r requirements.txt
   playwright install chromium
   ```

3. **Run the automation:**
   ```powershell
   python test_automation/IT23322912_test_automation.py --excel "test_automation/IT23322912_Assignment 1 - Test cases.xlsx"
   ```

## 📖 Command Line Arguments
* `--excel`: Path to the test case Excel file.
* `--headless`: Run without showing the browser.
* `--slow-mo-ms`: Slow down execution (in milliseconds) for easier debugging.
* `--keep-open`: Keeps the browser open after finishing the tests.

## 📝 License
Created for academic purposes for the ITPM module.
