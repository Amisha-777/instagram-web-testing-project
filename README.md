# Instagram Web Testing Project

## 📌 Project Overview

This repository contains the complete test plan, automation scripts, defect logs, and final report for the **Instagram Web Testing Project**, conducted as part of a software testing course project.

The objective of this project was to evaluate the stability, correctness, and usability of the Instagram web application. A combination of manual and automated testing strategies was used to validate four key functional modules:

- Login
- Profile Management
- Content Creation and Sharing
- User Search

## 🔧 Tools and Technologies

- **Selenium WebDriver** – Automation Testing
- **Python** – Scripting Language
- **Jupyter Notebook** – Automation Script Execution
- **Excel/Google Sheets** – Test Case and Defect Management
- **WebDriver Manager** – Browser Driver Handling
- **Browser** – Google Chrome / Microsoft Edge

## 📑 Contents of the Repository

| File/Folder Name                     | Description                                                   |
|-------------------------------------|---------------------------------------------------------------|
| `Final_Project_Report.docx`         | Comprehensive final project report with results and analysis |
| `Test_Plan_Document.docx`           | Outlines the test plan for the project|
| `Test_Design & Defect Log.xlsx`     | Designed test cases for each module and Logged defects with severity, remarks, and status |
| `selenium_automation_scripts.ipynb` | Jupyter Notebook with Selenium scripts |
| `Invalid_Login_Attempts.ipynb`      | Jupyter Notebook with Selenium scripts |

## ✅ Summary of Testing Efforts

- **Total Test Cases:** 19  
- **Pass Rate:** 94.7%  
- **Defects Found:** 3 (2 High Severity, 1 Medium)

## ⚙️ Automation Challenges

- Use of **Dynamic XPaths** due to frequently changing class attributes
- Fallback to **ID-based locators** when possible
- Use of **Explicit Waits** and **Reusable Functions** to handle dynamic elements

## Way Forward
- Expand test scope to include additional features (e.g., messaging, notifications)
- Develop complete user journey automation flows
- Perform cross-browser testing for broader compatibility
