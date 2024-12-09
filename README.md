# Manual Testing Project_Guru99 Banking
1. Introduction:

This is a manual testing project for a Banking Demo Site.Comprehensive manual testing of the Guru99 Banking application to validate its functionality, performance, and usability.
The aim of this project is to test banking web service and also actual test process in a corporate environment.




---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Hardware Requirements](#hardware-requirements)
3. [Software Requirements](#software-requirements)
4. [Testing Tools](#testing-tools)
5. [Test Data](#test-data)
6. [Test Environment Configuration](#test-environment-configuration)
7. [Risks and Dependencies](#risks-and-dependencies)
8. [Access](#access)

---

## Project Overview
This project involved rigorous manual testing of the [Guru99 Banking application](https://demo.guru99.com/V3/) to ensure the system meets functional and non-functional requirements, covering various aspects like account management, transactions, and balance inquiries.

---

## Hardware Requirements

### Client Machines (Testers):
- **Processor**: Intel i5 or equivalent
- **RAM**: 8 GB or higher
- **Storage**: 250 GB SSD or higher
- **Network**: Stable internet connection (10 Mbps or more)

### Test Server:
- **Processor**: Intel Xeon or equivalent
- **RAM**: 16 GB or higher
- **Storage**: 1 TB HDD/SSD
- **Database Server**: MySQL configured for backend storage

---

## Software Requirements
- **Operating Systems**:
  - Windows 10/11
  - macOS (for compatibility testing)
- **Browsers**:
  - Google Chrome (Version 27 and above)
  - Mozilla Firefox (Latest version)
  - Microsoft Edge (Latest version)
- **Database**:
  - MySQL Server for backend database operations
- **Web Application**:
  - Guru99 Banking Application, accessible at: [https://demo.guru99.com/V3/](https://demo.guru99.com/V3/)

---

## Testing Tools
- **Test Management**: Jira (for defect tracking and reporting)
- **API Testing**: Postman (for validating API functionality like Mini Statements and Balance Enquiries)
- **Performance Testing**: JMeter (to assess application performance under load)

---

## Test Data

### Input Test Data:
- **Dummy Customer Credentials**:  
  - Username: `mngr331160`  
  - Password: `qybAqEd`  
- **Other Test Data**: Account numbers, transaction details, and payment data.

### Output Test Data:
- Validation of output against expected results, e.g.,:
  - Correct balance displayed after transactions.
  - Accurate account statements generated.

---

## Test Environment Configuration
- **Environment Type**: Staging/Pre-production environment simulating live production.
- **Access URL**: [https://demo.guru99.com/V3/](https://demo.guru99.com/V3/)

### Environment Setup Steps:
1. Configure the test server and deploy the Guru99 Banking application.
2. Set up the database with dummy test data.
3. Validate accessibility of all URLs and modules.

---

## Risks and Dependencies

### Risks:
- Inconsistent test data leading to false positives or negatives.
- Potential downtime of the Guru99 demo environment.

### Dependencies:
- Availability of demo accounts.
- Uninterrupted access to the application.

---

## Access
Visit the Guru99 Banking application: [https://demo.guru99.com/V3/](https://demo.guru99.com/V3/)

---

# Test Strategy for Guru99 Banking Application

This document outlines the testing approach, scope, and resources required to ensure the Guru99 Banking Application meets functional requirements, is user-friendly, and is free of critical defects prior to deployment.

---

## 1. Introduction
The goal of the testing process is to:
- Validate all functionalities against specified requirements.
- Ensure user-friendliness and defect-free deployment.
- Minimize risks through early defect identification.

---

## 2. Objectives
- Verify that all functional requirements are met.
- Identify and report defects early to reduce risks.
- Validate usability and performance.
- Ensure seamless integration between modules.

---

## 3. Scope
The testing covers the following functionalities:

### User Authentication:
- Login and Logout for Manager and Customer.

### Account Management:
- Create, Edit, and Delete Customer Accounts.
- Open and Close Bank Accounts.

### Banking Transactions:
- Fund Transfers.
- Deposits and Withdrawals.
- Balance Enquiries.

### Statements:
- Customized Statements.
- Mini Statements.

### Other Functionalities:
- Navigation between modules.
- Error handling and validation messages.

**Note**: Non-functional testing (e.g., performance and load testing) is not included in this phase.

---

## 4. Test Approach
The testing will follow these phases:

### 1. Requirement Analysis:
- Review requirements documentation and conduct walkthroughs.
- Create a traceability matrix for full coverage.

### 2. Test Design:
- Develop test scenarios and detailed test cases.
- Define test data for scenarios like account creation, invalid logins, and transactions.

### 3. Test Execution:
- Execute functional tests for all modules.
- Perform positive and negative testing.
- Log defects in a defect tracking tool.

### 4. Regression Testing:
- Retest fixed defects to ensure no impact on existing functionality.

### 5. Defect Reporting:
- Log defects with severity and priority in Jira.
- Include reproduction steps, screenshots, and logs.

---

## 5. Test Environment
- **Operating Systems**: Windows 10/11.
- **Browsers**:
  - Google Chrome (Version 27 and above).
  - Mozilla Firefox (Latest version).
  - Microsoft Edge (Latest version).
- **Database**: MySQL or equivalent.
- **Tools**:
  - Jira for defect tracking and test management.
  - Postman for API testing (if applicable).

---

## 6. Entry and Exit Criteria

### Entry Criteria:
- Test environment is fully set up and accessible.
- All modules are deployed and functional.
- Test cases and data are reviewed and approved.

### Exit Criteria:
- All critical and high-priority defects are resolved.
- Test execution is complete, and results are documented.
- Test summary report is approved by stakeholders.

---

## 7. Roles and Responsibilities

### Test Manager:
- Develop the test strategy and plan.
- Manage schedules and allocate resources.

### Test Engineers:
- Execute test cases and log defects.
- Perform retesting and regression testing.

### Developers:
- Fix reported defects and assist with issue recreation.

---

## 8. Risks and Mitigation

### Risks:
1. **Limited access to the test environment**:
   - Mitigation: Plan and prepare environment setup in advance.
2. **Incomplete requirements**:
   - Mitigation: Conduct requirement walkthroughs with stakeholders.

---

## 9. Deliverables
- Test Scenarios and Test Cases.
- Test Execution Report.
- Defect Report.
- Final Test Summary Report.

---

## 10. Approval
This Test Strategy document must be approved by:
- **Project Manager**
- **QA Lead**
- **Client Representative**




