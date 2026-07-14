# ✅ Login Module Test Cases

## Document Information

| Item | Details |
|------|---------|
| **Project** | ShopEasy (Fictional E-commerce Application) |
| **Module** | User Login |
| **Related Test Plan** | Login Module Test Plan v1.0 |
| **Prepared By** | Joy Chepchumba |
| **Document Version** | 1.0 |
| **Date** | 2026-07-14 |

---

# Objective

The objective of these test cases is to verify that the Login Module functions correctly under positive, negative, usability, and boundary test scenarios while ensuring secure and reliable user authentication.

---

# Positive Test Scenarios

| TC ID | Category | Test Scenario | Test Steps | Test Data | Expected Result | Priority |
|------|----------|---------------|------------|-----------|-----------------|----------|
| TC-001 | Positive | Login with valid credentials | 1. Open ShopEasy.<br>2. Enter a valid email.<br>3. Enter a valid password.<br>4. Click **Login**. | Valid Email<br>Valid Password | User is successfully authenticated and redirected to the dashboard. | High |
| TC-002 | Positive | Login using Enter key | Enter valid credentials and press **Enter** instead of clicking Login. | Valid Credentials | User is successfully logged in. | Medium |
| TC-003 | Positive | Login with Remember Me enabled | Tick **Remember Me**, enter valid credentials, and login. | Valid Credentials | User session is remembered according to business requirements. | Medium |

---

# Negative Test Scenarios

| TC ID | Category | Test Scenario | Test Steps | Test Data | Expected Result | Priority |
|------|----------|---------------|------------|-----------|-----------------|----------|
| TC-004 | Negative | Login with invalid password | Enter valid email and incorrect password. Click **Login**. | Valid Email<br>Invalid Password | Error message indicating invalid credentials is displayed. | High |
| TC-005 | Negative | Login with invalid email | Enter invalid email and valid password. Click **Login**. | Invalid Email<br>Valid Password | Error message indicating invalid credentials is displayed. | High |
| TC-006 | Negative | Login with blank email | Leave email empty and enter password. Click **Login**. | Blank Email | Email validation message is displayed. | High |
| TC-007 | Negative | Login with blank password | Enter email and leave password blank. Click **Login**. | Blank Password | Password validation message is displayed. | High |
| TC-008 | Negative | Login with both fields blank | Leave all fields empty and click **Login**. | Blank Fields | Required field validation messages are displayed. | High |

---

# Usability Test Scenarios

| TC ID | Category | Test Scenario | Test Steps | Test Data | Expected Result | Priority |
|------|----------|---------------|------------|-----------|-----------------|----------|
| TC-009 | Usability | Verify password masking | Enter password in the password field. | Valid Password | Password characters are hidden from view. | Medium |
| TC-010 | Usability | Verify Forgot Password navigation | Click **Forgot Password**. | N/A | User is redirected to the Password Reset page. | Medium |

---

# Test Summary

| Metric | Value |
|--------|------:|
| Total Test Cases | 10 |
| Positive Test Cases | 3 |
| Negative Test Cases | 5 |
| Usability Test Cases | 2 |
| High Priority | 5 |
| Medium Priority | 5 |
| Low Priority | 0 |

---

# Notes

- These test cases are designed for manual execution.
- Additional boundary, security, compatibility, accessibility, and performance test cases will be added as the portfolio expands.
- Test execution results are documented separately within the Test Summary Report.

---

# Document History

| Version | Date | Author | Description |
|----------|------------|-----------------|--------------------------------------------|
| 1.0 | 2026-07-14 | Joy Chepchumba | Initial creation of Login Module Test Cases. |
