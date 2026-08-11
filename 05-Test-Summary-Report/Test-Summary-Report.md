## 1. Document Information

  Field                    Details
  ------------------------ --------------------------------------
  Document Name            Manual Testing Test Summary Report
  Project                  SauceDemo E-Commerce Web Application
  Testing Type             Manual Software Testing
  Prepared By              Debraj Shome
  Version                  1.0
  Status                   Draft
  Application Under Test   SauceDemo E-Commerce Web Application

## 2. Executive Summary

This Test Summary Report documents the results of manual testing
performed on the SauceDemo E-Commerce Web Application.

The objective is to verify functional behavior, UI consistency,
validation, usability, browser compatibility, session handling, and the
end-to-end purchase flow.

> **Important:** Test execution statistics must be updated after the
> test cases are actually executed. Do not claim tests have passed or
> failed before execution.

## 3. Testing Objectives

-   Verify login and logout functionality.
-   Verify product listing, product details, and sorting.
-   Verify shopping cart functionality.
-   Validate checkout and order completion.
-   Verify validation and error messages.
-   Check UI alignment, fonts, buttons, spacing, and responsive
    behavior.
-   Perform negative and browser compatibility testing.
-   Document confirmed defects with supporting evidence.
-   Perform regression testing after fixes.

## 4. Scope

### In Scope

Login, logout, products, product details, sorting, cart, checkout, order
completion, navigation, menu, error messages, UI consistency, responsive
behavior, browser compatibility, session behavior, negative testing, and
end-to-end purchase flow.

### Out of Scope

Performance/load testing, stress testing, database-level testing,
payment gateway testing, penetration testing, and API automation
testing.

## 5. Test Artifacts

  -------------------------------------------------------------------------------------
  Artifact                            Location
  ----------------------------------- -------------------------------------------------
  Test Plan                           `01-Test-Plan/Test-Plan.md`

  Test Scenarios                      `02-Test-Scenarios/Test-Scenarios.md`

  Test Cases                          `03-Test-Cases/Test-Cases.xlsx`

  Bug Reports                         `04-Bug-Reports/Bug-Reports.xlsx`

  Evidence                            `04-Bug-Reports/Evidence/`

  Test Summary Report                 `05-Test-Summary-Report/Test-Summary-Report.md`
  -------------------------------------------------------------------------------------

## 6. Test Execution Summary

  Metric               Result
  ------------------ --------
  Total Test Cases         50
  Executed                TBD
  Passed                  TBD
  Failed                  TBD
  Blocked                 TBD
  Not Executed             50
  Pass Percentage         TBD
  Fail Percentage         TBD

**Pass Percentage = Passed / Executed × 100**

**Fail Percentage = Failed / Executed × 100**

Update these values after executing the test cases.

## 7. Test Case Coverage

  Test Area               Coverage
  ----------------------- -------------------------
  Login                   Functional / Negative
  Product Listing         Functional / UI
  Product Details         Functional / UI
  Product Sorting         Functional
  Shopping Cart           Functional / UI
  Checkout                Functional / Validation
  Error Messages          UI / Validation
  UI                      Visual / Usability
  Browser Compatibility   Compatibility
  Session                 Functional / Session
  Regression              Regression

## 8. Defect Summary

  Severity        Description                                  Count
  --------------- ---------------------------------------- ---------
  S1 - Critical   Critical functionality/business impact         TBD
  S2 - Major      Major functionality impact                     TBD
  S3 - Minor      Minor functionality/UI impact                  TBD
  S4 - Trivial    Cosmetic/very low impact                       TBD
  **Total**                                                  **TBD**

## 9. Priority Summary

  Priority      Description                  Count
  ------------- ------------------------ ---------
  P1 - High     Immediate attention            TBD
  P2 - Medium   Planned fix                    TBD
  P3 - Low      Can be addressed later         TBD
  **Total**                                **TBD**

## 10. Defect Status

  Status               Count
  ------------------ -------
  Open                   TBD
  In Progress            TBD
  Fixed                  TBD
  Ready for Retest       TBD
  Closed                 TBD
  Reopened               TBD

## 11. Evidence

Confirmed defects should include supporting evidence such as
screenshots, screen recordings, error messages, relevant logs, or test
data.

Recommended structure:

``` text
04-Bug-Reports/
├── Bug-Reports.xlsx
└── Evidence/
    ├── BUG-001.png
    ├── BUG-002.png
```

## 12. Key Findings

Update this section after test execution.

### Functional Testing

-   [ ] Login verified
-   [ ] Product selection verified
-   [ ] Cart verified
-   [ ] Checkout verified
-   [ ] Order completion verified

### UI Testing

-   [ ] Alignment verified
-   [ ] Font consistency verified
-   [ ] Button appearance verified
-   [ ] Error message presentation verified
-   [ ] Responsive layout verified

### Compatibility Testing

-   [ ] Chrome verified
-   [ ] Edge verified
-   [ ] Firefox verified

## 13. Risks and Observations

Potential areas requiring attention include validation/error message
consistency, UI alignment across screen sizes, button states, browser
compatibility, session behavior, and the end-to-end checkout flow.

These observations should be confirmed during execution before being
reported as defects.

## 14. Entry Criteria

-   Test environment is accessible.
-   Application is available.
-   Test scenarios and test cases are prepared.
-   Required test data is available.
-   Supported browser(s) are available.

## 15. Exit Criteria

-   All planned test cases have been executed.
-   Critical and major defects have been documented.
-   Required regression testing has been completed.
-   Evidence has been captured for confirmed defects.
-   Final results have been reviewed.
-   Test Summary Report has been updated.

## 16. Overall Test Assessment

**Current Status: Draft / Test Execution Pending**

The final quality assessment will be completed after test execution and
defect analysis.

**Final Recommendation:** To be updated after test execution.

Possible outcomes:

-   **Ready for Release** -- No critical/major blocking defects remain.
-   **Conditionally Ready** -- Only acceptable minor issues remain.
-   **Not Ready for Release** -- Critical or major defects require
    resolution.

## 17. Sign-Off

  Role            Name           Status    Date
  --------------- -------------- --------- ------
  QA Tester       Debraj Shome   Pending   TBD
  Reviewer        TBD            Pending   TBD
  Project Owner   TBD            Pending   TBD

## 18. Version History

  Version   Date         Author         Changes
  --------- ------------ -------------- -----------------------------
  1.0       2026-08-11   Debraj Shome   Initial Test Summary Report
