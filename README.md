# End-to-End Banking Loan Management Testing Project

## Project Overview
This project simulates a comprehensive Quality Assurance testing cycle on a Banking Loan Management System module (specifically focusing on KYC and Identity Verification). The objective was to design structural test scenarios, execute functional, boundary, and negative validations, and manage the defect tracking life cycle using Agile Scrum principles in Jira Cloud.

## Test Artifacts
* **Complete Test Case Matrix:** [Click here to view Banking_Loan_Management_System_Test_Cases_30.xlsx](./Test_Artifacts/Banking_Loan_Management_System_Test_Cases_30.xlsx)
* Total Cases Executed: 30 Manual Test Cases covering Aadhaar, PAN validation, facial clarity limits, duplicate profiles, and input validation bounds.

## Defect Management Lifecycle (Jira Cloud)
To maintain structural compliance with professional development setups, I tracked all executions inside Jira using a dedicated Scrum Sprint framework.

### 1. Active Sprint Breakdown
* Created tracking tasks for major test blocks: Functional Execution (`SCRUM-10`), Boundary Testing (`SCRUM-11`), and Security Testing (`SCRUM-12`).
* Defect `SCRUM-14` was isolated during boundary limit analysis.

![Jira Sprint Status](./Proofs_and_Metrics/Jira_Sprint_Backlog.png)

### 2. Isolated Critical Bug Record (SCRUM-14)
* **Defect:** Application crashes (Blank White Screen) upon uploading files over 25MB instead of triggering validation rules.
* **Impact Matrix:** Disruption of UI thread runtime, requiring proper exception handling configurations.

![Jira Bug Breakdown](./Proofs_and_Metrics/Jira_Bug_Report_SCRUM14.png)
