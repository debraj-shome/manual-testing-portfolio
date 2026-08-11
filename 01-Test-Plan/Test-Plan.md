## 1. Document Information

| Field | Details |
|---|---|
| Document Name | Manual Testing Test Plan |
| Project | SauceDemo E-Commerce Web Application |
| Application      | SauceDemo (Swag Labs) |
| Application URL  | https://www.saucedemo.com/ 
| Testing Type | Manual Software Testing |
| Prepared By | Debraj Shome |
| Version | 1.0 |
| Status | Draft |
| Document Purpose | Define the testing approach, scope, resources, and activities |

---

## 2. Introduction

This Test Plan defines the overall testing strategy and approach for
validating the functionality, usability, reliability, and quality of
a web application.

The purpose of this document is to demonstrate a structured and
industry-oriented approach to manual software testing.

---

## 3. Test Objectives

The primary objectives of testing are:

- Verify that the application meets the defined requirements.
- Validate all major application functionalities.
- Identify functional and usability defects.
- Verify positive and negative scenarios.
- Ensure proper validation and error handling.
- Verify data accuracy and consistency.
- Perform regression testing after defect fixes.
- Ensure the application provides a consistent user experience.
- Document and track defects effectively.

---

## 4. Scope of Testing

### 4.1 In Scope

The following testing activities are included:

- Functional Testing
- UI Testing
- Smoke Testing
- Sanity Testing
- Regression Testing
- Integration Testing
- System Testing
- Exploratory Testing
- Negative Testing
- Validation Testing
- Usability Testing
- Cross-Browser Testing
- Defect Verification

### 4.2 Out of Scope

The following activities are outside the scope of this manual testing
portfolio:

- Performance Testing
- Load Testing
- Stress Testing
- Infrastructure Testing
- Advanced Security Testing
- Production Monitoring

---

## 5. Testing Approach

Testing will follow a structured Software Testing Life Cycle (STLC).

### Testing Process

1. Requirement Analysis
2. Test Planning
3. Test Scenario Identification
4. Test Case Design
5. Test Data Preparation
6. Test Execution
7. Defect Reporting
8. Defect Retesting
9. Regression Testing
10. Test Closure

---

## 6. Testing Types

### 6.1 Functional Testing

Verify that application features work according to the specified
business requirements.

Examples:

- Login
- Registration
- Search
- Create/Update/Delete operations
- Form submission
- Data validation

### 6.2 Smoke Testing

Verify that the major application functionalities are working and
the build is stable enough for detailed testing.

### 6.3 Sanity Testing

Perform focused testing of specific functionality after minor
changes or bug fixes.

### 6.4 Regression Testing

Verify that existing functionality has not been affected by new
changes or defect fixes.

### 6.5 Negative Testing

Verify that the application handles invalid inputs and unexpected
user actions correctly.

Examples:

- Invalid login credentials
- Empty mandatory fields
- Invalid email format
- Invalid file format
- Duplicate data
- Boundary values

### 6.6 UI Testing

Verify:

- Layout
- Alignment
- Font consistency
- Button appearance
- Labels
- Error messages
- Navigation
- Responsive behavior

### 6.7 Usability Testing

Verify that the application is easy to understand, navigate, and use.

---

## 7. Test Environment

The application will be tested using the following environment:

| Component | Details |
|---|---|
| Operating System | Windows |
| Browser | Google Chrome |
| Browser | Microsoft Edge |
| Browser | Mozilla Firefox |
| Testing Type | Web Application |
| Network | Stable Internet Connection |

> Note: Environment details can be updated based on the actual
> application being tested.

---

## 8. Test Data

Test data will be prepared to cover both valid and invalid scenarios.

### Valid Test Data

- Valid username/email
- Valid password
- Valid phone number
- Valid form data
- Supported file formats

### Invalid Test Data

- Invalid username/email
- Incorrect password
- Empty mandatory fields
- Invalid phone number
- Invalid email format
- Unsupported file formats
- Duplicate records
- Boundary values
- Special characters

---

## 9. Entry Criteria

Testing can begin when:

- Requirements are available.
- Application build is deployed.
- Test environment is accessible.
- Required test data is available.
- Major application modules are available for testing.
- Test cases are prepared and reviewed.

---

## 10. Exit Criteria

Testing can be completed when:

- All planned test cases have been executed.
- Critical and high-severity defects are resolved or accepted.
- Regression testing is completed.
- Defect retesting is completed.
- Test results are documented.
- Test Summary Report is prepared.

---

## 11. Defect Management

Defects identified during testing will be documented with the
following information:

- Defect ID
- Module
- Summary
- Description
- Steps to Reproduce
- Expected Result
- Actual Result
- Severity
- Priority
- Environment
- Screenshots/Evidence
- Status

### Defect Severity

| Severity | Description |
|---|---|
| S1 - Critical | Application or major functionality is completely blocked |
| S2 - High | Major functionality is not working |
| S3 - Medium | Functionality is affected but workaround exists |
| S4 - Low | Minor functional or UI issue |

### Defect Priority

| Priority | Description |
|---|---|
| P1 - Critical | Fix immediately |
| P2 - High | Fix with high priority |
| P3 - Medium | Fix in normal development cycle |
| P4 - Low | Fix when resources are available |

---

## 12. Test Deliverables

The following deliverables will be maintained:

- Test Plan
- Test Scenarios
- Test Cases
- Test Data
- Bug Reports
- Test Execution Results
- Test Summary Report
- Screenshots/Evidence

---

## 13. Risks and Mitigation

| Risk | Impact | Mitigation |
|---|---|---|
| Unstable test environment | High | Coordinate with development/DevOps team |
| Incomplete requirements | High | Clarify requirements before testing |
| Limited test data | Medium | Prepare reusable test data |
| Frequent application changes | Medium | Perform regression testing |
| Third-party service failure | Medium | Use mock/test environments where possible |

---

## 14. Assumptions

- Requirements provided by the project team are accurate.
- The test environment is available during testing.
- Required test data can be created.
- Defects will be tracked and managed using a defined process.
- Application builds provided for testing are deployable.

---

## 15. Test Execution

Test execution results will be tracked using the following metrics:

| Metric | Description |
|---|---|
| Total Test Cases | Total number of planned test cases |
| Executed | Number of test cases executed |
| Passed | Number of successful test cases |
| Failed | Number of failed test cases |
| Blocked | Number of blocked test cases |
| Not Executed | Test cases not yet executed |
| Defects Found | Total defects identified |

---

## 16. Test Closure

Testing will be considered complete after:

- Planned test execution is completed.
- Defects are reviewed and documented.
- Critical issues are resolved or accepted.
- Regression testing is completed.
- Test results are analyzed.
- Final Test Summary Report is prepared.

---

## 17. Approval

| Role | Name | Status |
|---|---|---|
| QA Engineer | Debraj Shome | Prepared |
| QA Lead | TBD | Pending |
| Project Manager | TBD | Pending |

---

## 18. Revision History

| Version | Date | Author | Changes |
|---|---|---|---|
| 1.0 | YYYY-MM-DD | Debraj Shome | Initial Test Plan |
