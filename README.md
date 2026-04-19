# Amazon-manual-testing
# Test Plan – E-Commerce Platform (Amazon)

## 1. Introduction

This document outlines the testing strategy, scope, resources, and schedule for validating the functionality and usability of an e-commerce web application. The goal is to ensure a high-quality user experience across core purchasing workflows.

---

## 2. Objectives

* Validate end-to-end user journey from product discovery to order placement
* Ensure accuracy of product data, pricing, and cart calculations
* Identify functional, UI, and usability defects
* Verify system behavior under normal user interactions

---

## 3. Scope

### 3.1 In Scope

* User Registration & Authentication
* Product Search and Filtering
* Product Detail Page
* Shopping Cart Management
* Checkout Process
* Order Placement
* User Profile Management

### 3.2 Out of Scope

* Third-party payment gateway validation (real transactions)
* Performance and load testing
* Security and penetration testing

---

## 4. Test Strategy

### 4.1 Testing Levels

* System Testing
* End-to-End Testing

### 4.2 Testing Types

* Functional Testing
* UI/UX Testing
* Usability Testing
* Regression Testing
* Exploratory Testing

### 4.3 Test Design Techniques

* Equivalence Partitioning
* Boundary Value Analysis
* Decision Table Testing
* State Transition Testing

---

## 5. Test Environment

* Browsers: Chrome (latest), Firefox (latest)
* OS: Windows 10/11, macOS
* Device: Desktop/Laptop
* Network: Stable broadband connection

---

## 6. Test Data

* Valid and invalid user credentials
* Product catalog with varied categories
* Address data (valid/invalid formats)
* Payment mock data

---

## 7. Entry Criteria

* Application build is deployed and accessible
* Requirements and UI flows are defined
* Test data is prepared
* Test cases are reviewed and approved

---

## 8. Exit Criteria

* 100% execution of planned test cases
* No open Critical or High severity defects
* Medium/Low defects documented and accepted
* Test summary report completed

---

## 9. Deliverables

* Test Plan
* Test Scenarios
* Test Cases
* Bug Reports
* Requirement Traceability Matrix (RTM)
* Test Summary Report

---

## 10. Roles & Responsibilities

| Role        | Responsibility                           |
| ----------- | ---------------------------------------- |
| QA Engineer | Test design, execution, defect reporting |
| QA Lead     | Test planning, review, reporting         |
| Developer   | Bug fixing, build deployment             |

---

## 11. Risk & Mitigation

| Risk                      | Impact | Mitigation                |
| ------------------------- | ------ | ------------------------- |
| Unstable test environment | High   | Use staging environment   |
| Incomplete requirements   | Medium | Clarify with stakeholders |
| Limited test data         | Medium | Create synthetic datasets |

---

## 12. Suspension & Resumption Criteria

Testing will be suspended if:

* Application is not accessible
* Critical blocking defects prevent execution

Testing will resume once blocking issues are resolved.

---

## 13. Test Execution Approach

* Execute smoke tests on each build
* Run full regression before release
* Log defects with severity and priority
* Retest fixed defects and perform regression validation

---

## 14. Approval

This test plan is approved when reviewed and accepted by QA Lead and Project Stakeholders.
