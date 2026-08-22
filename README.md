# Swag Labs Login Module - Manual Testing Suite

## Project Overview
This repository contains a comprehensive manual test suite and Quality Assurance documentation for the **Login Functionality** of the [Swag Labs (SauceDemo)](https://www.saucedemo.com/) e-commerce web application.

The project follows Agile testing methodology using **Trello** for test management and execution tracking.

---

##  Test Scope & Coverage
The test suite consists of **15 detailed test cases** designed to validate:
- **Positive Scenarios:** Successful authentication for standard and performance-delayed users.
- **Negative Scenarios:** Invalid usernames, wrong passwords, empty input validation, username/password case sensitivity, and whitespace handling.
- **Security & Edge Cases:** Password masking, SQL Injection resilience, non-English character input, and copy-paste restrictions.
- **Authorization & User Roles:** Preventing direct URL bypass (`/inventory.html`) without login and handling `locked_out_user` restrictions.

---

##  Tools Used
- **Test Management:** Trello Board
- **Documentation:** Microsoft Excel
- **Version Control:** GitHub

---

## Repository Files
- `SwagLabs_Test_Cases_Trello_Format.xlsx`: Complete test cases sheet containing Test Case ID, Summary, Steps, Test Data, Expected Results, and Status.
- `screenshots/`: Visual snapshots of the Trello board and card execution details.

---

## 📸 Trello Workspace Preview
*(Screenshots of the test management board can be viewed inside the `screenshots/` directory)*
