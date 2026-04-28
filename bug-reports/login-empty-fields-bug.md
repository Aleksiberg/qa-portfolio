**Bug Report: No validation message when submitting empty login form**

**Description**
The login form does not display a validation error when both fields are empty.

**Environment:**

- Browser: Chrome 120
- OS: Windows 11
- App version / Build:

**Preconditions**
1. User is not authenticated
2. Login page (/login) is opened

**Steps to reproduce:**
1. Open login page
2. Leave username empty
3. Leave password empty
4. Click "Login" button

**Expected result:**
The system displays: "Username and password are required" and the user remains on the login page.

**Actual result:**
No validation message appears, the page does not react to the click, and the user remains on the login page.

**Severity:**
Medium

**Priority:**
High
