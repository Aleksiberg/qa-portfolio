**Bug Report: Error message is not specific when entering incorrect password**

**Description:**
When a user enters an incorrect password, the system displays a generic error message ("Invalid credentials") instead of a specific message indicating that the password is incorrect.

**Environment:**
- Browser: Chrome 120
- OS: Windows 11
- App version / Build: N/A (test environment)

**Preconditions:** 
1. User is not authenticated
2. Login page (/login) is opened

**Steps to reproduce:**
1. Open login page
2. Enter valid username
3. Enter wrong password
4. Click "Login" button

**Expected result:**
The system displays a specific message under the password field: "Incorrect password"

**Actual result:**
The system displays generic message: "Invalid credentials"

**Severity:**
Low

**Priority:**
Medium

**Additional info:**  
