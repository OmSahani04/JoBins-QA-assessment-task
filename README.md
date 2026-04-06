**QA Task Assignment**

**Project Overview:**
Testing the demo e-commerce website located at Automation Exercise → https://automationexercise.com
The objective is to validate the platform’s functionality, responsiveness, automation coverage, and overall user experience.

**Additional Instructions for Candidates (Senior QA Expectations):**

A senior candidate is expected to go beyond basic test automation and demonstrate strong engineering practices. Your solution should include:

- Proper use of Page Object Model (POM) for maintainable and scalable test architecture
- Implementation of reusable methods and utilities (avoid hardcoding values)
- Use of robust and smart selectors (prefer CSS/test IDs; avoid brittle XPath where possible)
- Effective usage of fixtures and hooks (e.g., beforeEach, afterEach) for setup and teardown
- Configuration for parallel test execution to optimize performance
- Support for environment-based configuration (e.g., dev/staging URLs, credentials)
- Implementation of data-driven testing for covering multiple scenarios efficiently


### **Testing Scope:**

1. **Manual Testing**
2. **Automation Testing**

---

### **Test Scenarios & Tasks**

#### **1. Header Section**

**User Story:** As a user, I want to navigate easily through the website using the header menu..

**Subtasks:**

- Verify header responsiveness across devices (Desktop, Tablet, Mobile).
- Validate all navigation menu links (Home, Products, Cart, Signup/Login).
- Test login/logout visibility based on user state.
- Verify cart icon updates dynamically.

**Automation Suggestions:**

- Navigation menu validation.
- Login state validation.
- Dynamic cart count verification.

---

#### **2. Footer Section**

**User Story:** As a user, I want to access additional links and subscription options.

**Subtasks:**

- Validate footer layout and content structure.
- Test newsletter subscription with valid/invalid emails.
- Verify social media links.

**Automation Suggestions:**

- Link validation for social media icons.
- Footer content validation.
- Email validation scenarios.

---

#### **3. Hero Section**

**User Story:** As a visitor, I want to see featured banners and promotions.

**Subtasks:**

- Verify carousel/slider functionality.
- Validate banner transitions and timing.
- Check responsiveness of hero section.

**Automation Suggestions:**

- Visual regression testing for the hero section.
- Slider functionality validation.

---

#### **4. "Signup & Login Flow" Section**

**User Story:** As a user, I want to create an account and log in securely.

**Subtasks:**

- Test user registration with valid and invalid data.
- Validate error messages.
- Test login with valid/invalid credentials.
- Verify session persistence after login.

**Automation Testing Required:**

- End-to-end signup/login flow.
- Negative test scenarios (invalid email, duplicate user).

---

#### **5. Product Listing & Search Section**

**User Story:** As a customer, I want to browse and search products..

**Subtasks:**

- Validate product listing page UI.
- Test search functionality with various keywords.
- Verify category and filter functionality.
- Validate product detail page navigation.

**Automation Suggestions:**

- Search functionality automation.
- Product navigation validation.
- Filter validation tests

---

#### **6. Cart & Checkout Flow Section**

**User Story:** As a buyer, I want to add items to cart and proceed to checkout..

**Subtasks:**

- Add/remove products from cart.
- Verify cart updates correctly.
- Test checkout process.
- Validate total price calculation.

**Automation Suggestions:**

- Add-to-cart flow.
- Checkout process automation.
- Price calculation validation.
---

#### **7. Contact Us Form Section**

**User Story:** As a user, I want to contact support easily.

**Subtasks:**

- Validate form submission.
- Test file upload functionality.
- Verify success/error messages.

**Automation Suggestions:**

- Form submission automation.
- File upload validation.

---

#### **8. API Testing (Optional but Recommended)**

**User Story:**As a QA engineer, I want to validate backend APIs.

**Subtasks:**

- Test product APIs.
- Validate response status codes.
- Verify schema and data integrity.

**Tools Suggested:**

- Postman
- Swagger

---

### **Deliverables:**

1. Test Plan Document.
2. Test Cases and Scripts (for automation).
3. Bug Report with Screenshots and Logs.
4. Test Summary Report with Recommendations.
5. Automation Test Files (Repo Link or Zip File).
6. Clear Instructions on How to Run Automation Tests.

**Priority:** High
**Deadline:** Within one week of assignment.

---

**Submission Guidelines:**

- Submit the assignment via email with all relevant files attached.
- Include clear instructions for running automation tests.
- If using a repository, provide access credentials and repo link.

---

**QA Tools Suggested:**

- Manual: Browser Developer Tools (Chrome, Firefox)
- Automation: Playwright (JS), Page object framework, Postman (for API testing if applicable)

---

**Notes:**
Ensure cross-browser testing and accessibility compliance checks throughout the QA process. The primary focus should be on responsiveness, UI/UX animations, and site navigation functionality.

