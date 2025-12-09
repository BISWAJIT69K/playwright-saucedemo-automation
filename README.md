# Playwright Automation – SauceDemo Web Application

This repository contains automated UI test scripts for the SauceDemo web application using Playwright.  
The project focuses on validating login and logout workflows for multiple user roles along with negative authentication scenarios.

This automation suite demonstrates automation script development, execution, and validation using Playwright Test.

---

## Tech Stack

- **Automation Framework:** Playwright Test  
- **Programming Language:** TypeScript  
- **Runtime Environment:** Node.js  
- **Browsers:** Chromium, Firefox, WebKit  

---

## Features Covered

- Login validation for different user types  
  - Standard user  
  - Problem user  
  - Locked user  
- Login and logout workflow validation  
- Negative login testing using invalid credentials  
- Playwright HTML report generation for test execution analysis  

---

## Project Structure

```text
.
├── tests
│   ├── logIn.spec.ts          # Login and logout test cases
│   └── invalidLogin.spec.ts   # Negative test for invalid credentials
├── src                        # Page objects and helper methods
├── playwright.config.ts       # Playwright configuration
├── package.json
└── README.md

Prerequisites
- Node.js (LTS version recommended)
- Git
- Internet connection

Setup & Execution
1. Clone the Repository
git clone https://github.com/<your-username>/playwright-saucedemo-automation.git
cd playwright-saucedemo-automation

2. Install Dependencies
npm install
npx playwright install

3. Run Test Suite
Run all tests:
npx playwright test

Run a specific test file:
npx playwright test tests/logIn.spec.ts
npx playwright test tests/invalidLogin.spec.ts

Test Report
Playwright automatically generates an HTML report after test execution.
To view the report:
npx playwright show-report

The report displays:
- Test pass/fail status
- Execution duration
- Step-by-step test actions

Custom Enhancements by Biswajit
- Executed Playwright automation tests locally on the SauceDemo web application
- Added a custom negative login test to validate error handling for invalid credentials
- Reviewed Playwright HTML reports to verify successful execution and test stability

Future Enhancements
- Automation of add-to-cart and checkout workflows
- Data-driven testing using parameterized inputs
- CI integration using GitHub Actions

Author
Biswajit Kumar Pradhan
GitHub: https://github.com/BISWAJIT69K
LinkedIn: https://linkedin.com/in/biswajit-kumar-pradhan