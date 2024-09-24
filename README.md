# Rokomari Sign In & Login - Manual Test Cases

This repository contains a comprehensive set of **manual test cases** for the **Sign In & Login** feature of the **Rokomari** web application. The test cases cover various functional and performance aspects to ensure a smooth and reliable user experience when signing in or logging into the platform.

## Project Overview

- **Product Name**: Rokomari
- **Module Name**: Sign In & Login
- **Tested By**: Md. Refat Bhuyan
- **Test Date**: 7th July 2024 - 10th July 2024

The goal of this testing phase is to ensure that all sign-in and login-related functionalities are working as expected, including handling edge cases, and performance under different conditions.

## Test Case Summary

| Metric                     | Value            |
|----------------------------|------------------|
| **Total Test Cases**        | 16               |
| **Pass**                    | 9                |
| **Fail**                    | 7                |
| **Warnings**                | 0                |
| **Browsers Tested**         | Multiple         |
| **Performance Tests**       | Included         |

## Test Scenarios Covered

1. **Functional Testing**:
   - User can successfully sign in with valid credentials.
   - Login errors are shown for incorrect credentials.
   - Session management for logged-in users.
   - Password recovery workflow.
   
2. **UI/UX Testing**:
   - Consistency in the Sign In page design across browsers.
   - Error messages are clearly displayed and styled properly.
   - Responsive behavior of the login form on different screen sizes.

3. **Performance Testing**:
   - Load time for the Sign In page.
   - Response time of the login request.

4. **Negative Testing**:
   - Attempts to login with invalid usernames and passwords.
   - Stress testing for multiple failed login attempts.

## Pre-requisites

- **Test Environment**: Rokomari live server
- **Browsers Tested**: Chrome, Firefox, Safari
- **Preconditions**: User account must exist for valid sign-in testing.
  
## Test Case Execution Overview

Each test case follows the structure below:

| **Test Case ID/Name** | **Test Description** | **Precondition**  | **Steps** | **Expected Result** | **Actual Result** | **Status** | **Remarks** |
|-----------------------|----------------------|-------------------|-----------|---------------------|-------------------|------------|-------------|
| TC-001                | User signs in        | User account ready | ...       | User logs in         | PASS               | ...        | ...         |
| TC-002                | Invalid credentials  | N/A               | ...       | Error shown          | FAIL               | ...        | ...         |

## Key Takeaways

- This test cycle uncovered **7 failed tests**, highlighting areas for improvement in the Sign In & Login feature, particularly around error handling and UX.
- **Performance was optimal**, with no major slowdowns under regular usage conditions.
- The test results provide actionable feedback for the development team to improve the user experience, especially around handling invalid credentials and improving messaging for users.

## How to Use

1. Clone the repository and download the test case file.
2. Open the Excel sheet (`Rokomari_Singin_ManualTest.xlsx`) to view detailed steps for each test case, including expected and actual results.
3. Use the test cases as a reference to verify any new implementations or bug fixes related to the Sign In & Login module.