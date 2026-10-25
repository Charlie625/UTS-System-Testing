# UTS Assignment 3 – System Testing

## 1. Project Overview

This project uses Python, Selenium WebDriver, and pytest to perform automated system testing on the OpenCart Demo Store.

**Website under test:** https://opencart.abstracta.us/

The objective is to verify product search, filtering, and sorting functions and identify possible website defects.

## 2. Test Cases

| Test Case | Function | Test Scenarios |
|---|---|---|
| T004 | Product Search | Valid keyword, non-existent keyword, empty keyword |
| T005 | Product Filtering | Cameras category, Apple brand, empty Software category |
| T006 | Product Sorting | Price low to high, price high to low, name A to Z |

Each test case includes three automated scenarios.

## 3. Testing Tools

- Python
- Selenium WebDriver
- pytest
- Google Chrome
- Visual Studio Code

## 4. Source Code

- `test_T004_search.py` – Automated product search testing.
- `test_T005_filter.py` – Automated category and brand filtering testing.
- `test_T006_sort.py` – Automated product sorting testing.

The source code includes comments, test assertions, browser automation steps, and screenshot-saving functions.

## 5. How to Run the Tests

Install the required Python packages:

`python -m pip install selenium pytest`

Run the automated tests:

`python -m pytest test_T004_search.py test_T005_filter.py test_T006_sort.py -v -s`

Google Chrome must be installed.

## 6. Test Results

During the documented test execution, nine automated scenarios were tested:

- Passed: 6
- Failed: 3
- Errors: 0

The failed scenarios identified possible issues with search and empty-category feedback messages. These failures are retained to report the observed website behaviour accurately.

Screenshots and detailed test results are included in the Assignment 3 report.
