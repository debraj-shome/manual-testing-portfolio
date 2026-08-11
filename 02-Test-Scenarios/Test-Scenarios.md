## 1. Document Information

| Field | Details |
|---|---|
| Project | SauceDemo E-Commerce Web Application |
| Application | SauceDemo (Swag Labs) |
| Application URL | https://www.saucedemo.com/ |
| Testing Type | Manual Testing |
| Prepared By | Debraj Shome |
| Version | 1.0 |

---

## 2. Objective

The purpose of this document is to identify high-level test scenarios
for validating the functional and non-functional aspects of the
SauceDemo e-commerce web application.

These scenarios will be used as a foundation for designing detailed
test cases.

---

## 3. Test Scenarios

### TS-001: Login

**Objective:** Verify the login functionality.

Scenarios:

- Verify login with valid credentials.
- Verify login with invalid username.
- Verify login with invalid password.
- Verify login with both username and password invalid.
- Verify login with empty username.
- Verify login with empty password.
- Verify login with both fields empty.
- Verify appropriate error messages for invalid login attempts.
- Verify password field masking.
- Verify login button functionality.

---

### TS-002: Logout

**Objective:** Verify that users can successfully log out.

Scenarios:

- Verify logout from the application.
- Verify the user is redirected to the login page after logout.
- Verify browser back navigation after logout.
- Verify protected pages cannot be accessed after logout.

---

### TS-003: Product Listing

**Objective:** Verify the product listing functionality.

Scenarios:

- Verify all available products are displayed.
- Verify product names are displayed correctly.
- Verify product prices are displayed correctly.
- Verify product images are displayed correctly.
- Verify product descriptions are displayed correctly.
- Verify Add to Cart buttons are displayed.
- Verify product information is consistent across the application.

---

### TS-004: Product Details

**Objective:** Verify product detail functionality.

Scenarios:

- Verify clicking a product opens its details.
- Verify product name on the details page.
- Verify product description.
- Verify product price.
- Verify product image.
- Verify Add to Cart functionality from the details page.
- Verify Back to Products functionality.

---

### TS-005: Product Sorting

**Objective:** Verify product sorting functionality.

Scenarios:

- Verify sorting by Name A to Z.
- Verify sorting by Name Z to A.
- Verify sorting by Price Low to High.
- Verify sorting by Price High to Low.
- Verify products are displayed according to the selected sorting option.
- Verify the selected sorting option remains visible.

---

### TS-006: Add to Cart

**Objective:** Verify that users can add products to the shopping cart.

Scenarios:

- Verify adding a single product to the cart.
- Verify adding multiple products to the cart.
- Verify the cart count is updated.
- Verify the selected product appears in the cart.
- Verify product name and price in the cart.
- Verify adding products from the product details page.

---

### TS-007: Remove from Cart

**Objective:** Verify that users can remove products from the cart.

Scenarios:

- Verify removing a single product.
- Verify removing multiple products.
- Verify the cart count is updated after removal.
- Verify the removed product is no longer displayed in the cart.
- Verify all products can be removed from the cart.

---

### TS-008: Shopping Cart

**Objective:** Verify shopping cart functionality.

Scenarios:

- Verify the cart opens successfully.
- Verify selected products are displayed.
- Verify product names are correct.
- Verify product prices are correct.
- Verify product quantity is displayed correctly.
- Verify Continue Shopping functionality.
- Verify Checkout button functionality.
- Verify cart contents remain consistent during navigation.

---

### TS-009: Checkout

**Objective:** Verify the checkout process.

Scenarios:

- Verify checkout can be initiated from the cart.
- Verify checkout information fields are displayed.
- Verify checkout with valid customer information.
- Verify checkout with empty mandatory fields.
- Verify checkout with partially completed information.
- Verify validation messages for missing information.
- Verify Continue button functionality.
- Verify Cancel button functionality.

---

### TS-010: Checkout Information Validation

**Objective:** Verify validation of customer information.

Scenarios:

- Verify First Name validation.
- Verify Last Name validation.
- Verify Postal Code validation.
- Verify mandatory field validation.
- Verify appropriate error messages.
- Verify valid data is accepted.
- Verify invalid or unexpected input is handled appropriately.

---

### TS-011: Order Overview

**Objective:** Verify the order overview before completion.

Scenarios:

- Verify selected products are displayed.
- Verify product prices are correct.
- Verify product quantities are correct.
- Verify total item price.
- Verify applicable tax.
- Verify final total amount.
- Verify Finish button functionality.
- Verify Cancel button functionality.

---

### TS-012: Order Completion

**Objective:** Verify successful order completion.

Scenarios:

- Verify an order can be completed with valid information.
- Verify order confirmation is displayed.
- Verify successful completion message.
- Verify order completion page contains the expected information.
- Verify Back Home functionality.

---

### TS-013: Navigation

**Objective:** Verify application navigation.

Scenarios:

- Verify navigation between product and cart pages.
- Verify Continue Shopping functionality.
- Verify navigation to product details.
- Verify navigation to checkout.
- Verify Back Home functionality.
- Verify menu functionality.
- Verify navigation links work correctly.

---

### TS-014: Menu Functionality

**Objective:** Verify the application menu.

Scenarios:

- Verify menu opens successfully.
- Verify available menu options.
- Verify All Items navigation.
- Verify About navigation.
- Verify Logout functionality.
- Verify Reset App State functionality.
- Verify menu closes correctly.

---

### TS-015: UI Validation

**Objective:** Verify the application's user interface.

Scenarios:

- Verify page layout.
- Verify alignment of UI elements.
- Verify button labels.
- Verify button alignment.
- Verify font consistency.
- Verify product images.
- Verify error message appearance.
- Verify navigation menu appearance.
- Verify cart icon and item count.
- Verify consistent UI across pages.

---

### TS-016: Negative Testing

**Objective:** Verify application behavior with invalid inputs and
unexpected user actions.

Scenarios:

- Verify login with invalid credentials.
- Verify submission with empty mandatory fields.
- Verify invalid customer information.
- Verify unexpected characters in input fields.
- Verify invalid or incomplete form submissions.
- Verify application behavior when navigating unexpectedly.
- Verify appropriate error messages are displayed.

---

### TS-017: Regression Testing

**Objective:** Verify that application changes do not affect existing
functionality.

Scenarios:

- Verify login after application changes.
- Verify product listing after changes.
- Verify sorting after changes.
- Verify Add to Cart after changes.
- Verify Remove from Cart after changes.
- Verify checkout after changes.
- Verify order completion after changes.
- Verify navigation after changes.

---

### TS-018: Browser Compatibility

**Objective:** Verify application behavior across supported browsers.

Scenarios:

- Verify application in Google Chrome.
- Verify application in Microsoft Edge.
- Verify application in Mozilla Firefox.
- Verify login across supported browsers.
- Verify product functionality across supported browsers.
- Verify cart functionality across supported browsers.
- Verify checkout functionality across supported browsers.

---

### TS-019: Usability Testing

**Objective:** Verify that the application is easy to understand and use.

Scenarios:

- Verify navigation is intuitive.
- Verify buttons have understandable labels.
- Verify error messages are clear.
- Verify important actions are easy to identify.
- Verify checkout flow is easy to understand.
- Verify consistent user experience across pages.

---

### TS-020: Session and Application State

**Objective:** Verify application behavior related to user session
and application state.

Scenarios:

- Verify user session after successful login.
- Verify logout terminates the user session.
- Verify cart behavior during navigation.
- Verify application behavior after page refresh.
- Verify Reset App State functionality.
- Verify application behavior after browser back/forward actions.

---

## 4. Scenario Summary

| Scenario ID | Module | Scenario Count |
|---|---|---:|
| TS-001 | Login | 10 |
| TS-002 | Logout | 4 |
| TS-003 | Product Listing | 7 |
| TS-004 | Product Details | 7 |
| TS-005 | Product Sorting | 6 |
| TS-006 | Add to Cart | 6 |
| TS-007 | Remove from Cart | 5 |
| TS-008 | Shopping Cart | 8 |
| TS-009 | Checkout | 7 |
| TS-010 | Checkout Validation | 7 |
| TS-011 | Order Overview | 7 |
| TS-012 | Order Completion | 5 |
| TS-013 | Navigation | 7 |
| TS-014 | Menu | 7 |
| TS-015 | UI Validation | 10 |
| TS-016 | Negative Testing | 7 |
| TS-017 | Regression Testing | 8 |
| TS-018 | Browser Compatibility | 7 |
| TS-019 | Usability Testing | 5 |
| TS-020 | Session & Application State | 6 |

---

## 5. Testing Priority

| Priority | Description |
|---|---|
| P1 - Critical | Core functionality that blocks application usage |
| P2 - High | Important business functionality |
| P3 - Medium | Normal functionality and usability |
| P4 - Low | Minor UI and cosmetic functionality |

---

## 6. Test Scenario Status

| Status | Meaning |
|---|---|
| Not Started | Scenario has not been tested |
| In Progress | Testing is currently in progress |
| Passed | Scenario passed successfully |
| Failed | Scenario failed |
| Blocked | Testing cannot continue due to a blocker |
| Not Applicable | Scenario is not applicable |

---

## 7. Next Step

The identified test scenarios will be converted into detailed test
cases containing:

- Test Case ID
- Test Scenario
- Test Case Description
- Preconditions
- Test Steps
- Test Data
- Expected Result
- Actual Result
- Status
- Severity
- Priority
- Comments
