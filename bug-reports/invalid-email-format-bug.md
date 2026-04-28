**Bug Report: Error message is not specific when entering incorrect email format**

**Description:**
The system displays a generic error message when email format is invalid

**Environment:**
- Browser: Chrome 120
- OS: Windows 11
- App version / Build:

**Preconditions:** 
1. User is not authenticated
2. Login page (/login) is opened

**Steps to reproduce:**
1. Open login page
2. Enter Invalid email "test@"
3. Enter any password
4. Click "Login" button

**Expected result:**
The system displays: "Invalid email format"

**Actual result:**
The system displays generic message: "Invalid credentials"

**Severity:**
Low

**Priority:**
Medium

**Additional info:**
