# 🔄 Login Regression Checklist

## Document Information

| Item | Details |
|------|---------|
| **Project** | ShopEasy (Fictional E-commerce Application) |
| **Module** | User Login |
| **Prepared By** | Joy Chepchumba |
| **Document Version** | 1.0 |
| **Date** | 2026-07-14 |
| **Regression Type** | Functional Regression |

---

# Objective

The objective of this regression checklist is to verify that recent changes or bug fixes made to the Login Module have not negatively impacted existing functionality.

---

# Regression Checklist

| ID | Feature | Verification | Status |
|----|---------|--------------|--------|
| RC-001 | Login | Verify users can log in using valid credentials. | ☐ |
| RC-002 | Login Validation | Verify invalid credentials display the correct error message. | ☐ |
| RC-003 | Required Fields | Verify email and password are mandatory. | ☐ |
| RC-004 | Password Field | Verify password remains masked during input. | ☐ |
| RC-005 | Login Button | Verify Login button becomes enabled after entering valid credentials. | ☐ |
| RC-006 | Forgot Password | Verify Forgot Password link redirects correctly. | ☐ |
| RC-007 | Remember Me | Verify Remember Me functionality behaves according to requirements. | ☐ |
| RC-008 | Session Management | Verify user session is successfully created after login. | ☐ |
| RC-009 | Logout | Verify users can successfully log out after logging in. | ☐ |
| RC-010 | Browser Refresh | Verify session persists correctly after refreshing the page. | ☐ |

---

# Regression Scope

This regression checklist focuses on validating the critical user authentication flow following fixes or enhancements to the Login Module.

---

# Exit Criteria

Regression testing is considered complete when:

- All checklist items have been executed.
- No Critical or High severity defects are introduced.
- Existing functionality behaves as expected.
- Product Owner approves the feature for release.

---

# Notes

- Regression testing should be executed after every significant change to the Login Module.
- Failed checklist items should result in defect creation and retesting after fixes are deployed.

---

# Document History

| Version | Date | Author | Description |
|----------|------------|-----------------|------------------------------|
| 1.0 | 2026-07-14 | Joy Chepchumba | Initial creation of Login Regression Checklist. |
