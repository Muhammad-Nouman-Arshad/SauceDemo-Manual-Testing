# SauceDemo Manual Testing Project

## Project Overview

This is a Manual Testing project performed on the SauceDemo e-commerce web application.

The project demonstrates practical QA activities including test scenario design, test case creation, functional testing, exploratory testing, defect reporting, regression testing, retesting, and test result documentation.

## Application Under Test

SauceDemo E-Commerce Web Application

https://www.saucedemo.com/

## Testing Objective

The objective of this project is to verify the functionality and usability of the SauceDemo web application and identify reproducible defects through manual testing.

## Testing Scope

- Login
- Products
- Product Details
- Product Sorting
- Shopping Cart
- Checkout
- Menu

## Testing Types

- Functional Testing
- UI Testing
- Validation Testing
- Exploratory Testing
- Regression Testing
- Retesting

## Test Execution Summary

| Metric | Result |
|---|---:|
| Test Scenarios | 30 |
| Test Cases Executed | 30 |
| Passed | 30 |
| Failed | 0 |
| Blocked | 0 |
| Pass Rate | 100% |
| Exploratory Tests | 5 |
| Regression Tests | 5 |
| Regression Passed | 5 |
| Defects Identified | 2 |

## Defects Identified

### BUG-001 — Incorrect Product Images

**Module:** Products

**Severity:** Medium

**Priority:** Medium

**Description:**  
Some products displayed an incorrect dog image instead of their respective product images when using the `problem_user` account.

**Expected Result:**  
Each product should display its corresponding product image.

**Actual Result:**  
Some products displayed the same incorrect dog image.

---

### BUG-002 — Last Name Field Does Not Accept Input

**Module:** Checkout

**Severity:** High

**Priority:** High

**Description:**  
The Last Name field did not accept input when testing with the `problem_user` account.

**Expected Result:**  
The Last Name field should accept valid text input and allow the user to continue checkout.

**Actual Result:**  
The Last Name field did not accept input and the application displayed a "Last Name is required" error.

**Retest Result:**  
The issue was not reproducible with the `standard_user` account.

## Regression Testing

Five critical regression tests were executed after exploratory testing.

| Regression Test | Result |
|---|---|
| Login | PASS |
| Add Product to Cart | PASS |
| Remove Product from Cart | PASS |
| Checkout with Valid Information | PASS |
| Complete Order | PASS |

**Regression Pass Rate: 100%**

## Project Deliverables

- Test Scenarios
- Test Cases
- Test Execution Results
- Exploratory Testing
- Bug Reports
- Regression Testing
- Test Plan
- Test Summary Report
- Bug Evidence Screenshots

## Tools Used

- Google Chrome
- Microsoft Excel
- GitHub
- Manual Testing
- Browser DevTools

## Tester

**Muhammad Nouman Arshad**

Computer Science | Manual QA / SQA Intern
