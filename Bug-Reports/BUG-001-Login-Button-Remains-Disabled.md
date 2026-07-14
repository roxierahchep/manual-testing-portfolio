# 🐞 BUG-001 – Login Button Remains Disabled After Entering Valid Credentials

## Bug Information

| Item | Details |
|------|---------|
| **Bug ID** | BUG-001 |
| **Module** | Login |
| **Project** | ShopEasy |
| **Reported By** | Joy Chepchumba |
| **Date Reported** | 2026-07-14 |
| **Environment** | Staging |
| **Browser** | Google Chrome (Latest Version) |
| **Operating System** | Windows 11 |
| **Severity** | Critical |
| **Priority** | High |
| **Status** | Open |

---

# Summary

The Login button remains disabled after entering valid user credentials, preventing users from logging into the application.

---

# Preconditions

- User is on the Login page.
- A valid test account exists.
- Application is accessible.

---

# Steps to Reproduce

1. Navigate to the Login page.
2. Enter a valid email address.
3. Enter a valid password.
4. Observe the Login button.

---

# Expected Result

The Login button becomes enabled, allowing the user to submit valid credentials.

---

# Actual Result

The Login button remains disabled even after valid credentials have been entered.

---

# Impact

Users are unable to log in, making the application inaccessible.

---

# Reproducibility

**100% (5/5 attempts)**

---

# Suggested Fix

Verify the frontend validation logic responsible for enabling the Login button after both required fields have been populated with valid values.

---

# Attachments

- Screenshot (To be attached)
- Screen Recording (Optional)

---

# Notes

This bug blocks user authentication and should be resolved before production release.

---

# Document History

| Version | Date | Author | Description |
|----------|------------|-----------------|-------------------------|
| 1.0 | 2026-07-14 | Joy Chepchumba | Initial bug report. |
