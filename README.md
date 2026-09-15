  ShopEasy E-commerce — QA Testing Project

  Project Overview

This project demonstrates my practical experience in manual software testing through the testing of a sample e-commerce application’s login functionality.

The project focuses on designing and executing functional test cases, validating expected versus actual results, documenting test outcomes and identifying potential defects.

Tester: Victor Adejoh
Testing Type: Manual / Functional Testing
Application: ShopEasy E-commerce Website
Testing Area: Login & Authentication
Environment: Laptop / Chrome Browser



   Testing Objective

The objective was to verify that the ShopEasy login functionality works correctly for valid and invalid user scenarios and provides appropriate validation messages when incorrect or incomplete information is submitted.



   Testing Scope

The test suite covers:

* Valid login
* Invalid username
* Invalid password
* Invalid username and password
* Blank username
* Blank password
* Both username and password blank
* Password masking
* Login button functionality
* Forgot password functionality



  Test Cases

A total of 10 login test cases were designed and executed.

Test Area	Coverage
Valid Login	Positive testing
Invalid Password	Negative testing
Invalid Username	Negative testing
Blank Username	Input validation
Blank Password	Input validation
Blank Username & Password	Input validation
Password Masking	UI validation
Login Button	Functional validation
Forgot Password	Functional validation

The complete test cases and execution results are available in the Excel test suite included in this repository.



 Test Execution Results

Total Test Cases: 10
Passed: 10
Failed: 0
Pass Rate: 100%

The tests were executed manually and the expected results were compared against the recorded actual results.



  Defect / QA Observation

During test execution, I identified a potential validation inconsistency involving the blank-password scenario.

The expected result and recorded actual result did not completely align. This was documented as a potential defect/requirement clarification rather than being ignored.

DEF-001 — Blank Password Validation

Severity: Medium
Status: Open / Requires Requirement Confirmation

Observation:
The expected result indicated a generic invalid username/password message, while the actual result indicated that the username was required when the password field was blank.

Recommendation:
Confirm the approved requirement and ensure the validation message accurately identifies the missing password field if a password is mandatory.



  Testing Approach

The project used a combination of:

* Positive testing
* Negative testing
* Functional testing
* Input validation
* UI validation
* Expected vs actual result comparison
* Test execution documentation
* Defect identification



   Skills Demonstrated

* Manual Software Testing
* Test Case Design
* Functional Testing
* Positive & Negative Testing
* Test Execution
* Input Validation
* UI Testing
* Defect Identification
* QA Documentation
* Expected vs Actual Result Analysis



   Project Files

   QA Portfolio

The PDF provides an overview of the project, testing approach, results and QA findings.

   Login Test Suite

The Excel file contains the detailed test cases, test data, expected results, actual results, status and comments.



 Future Improvements

As I continue developing my QA skills, I plan to expand this project with:

* API testing using Postman
* Defect management using Jira
* Additional e-commerce test scenarios
* Regression testing
* Cross-browser testing
* Automated UI testing using Playwright
* API automation
* CI/CD test execution

⸻

  About Me

I am building my career in Software Quality Assurance and Testing, with a focus on practical hands-on testing experience.

This project is part of my QA portfolio and demonstrates my ability to design test cases, execute tests, analyse results and communicate potential defects clearly.

Goal: Junior QA Tester / Software Tester
