## Scope
Testing login functionality

## Test Coverage
- Valid login
- Invalid password
- Empty fields
- Empty password

# Login Page Test Cases

## TC-01: Valid login

**Title:** Valid login

**Preconditions:**
- User has a valid account
- Login page is opened

**Steps:**
1. Open login page
2. Enter valid username
3. Enter valid password
4. Click "Login" button

**Expected result:**
- User is logged in
- User is redirected to dashboard

## TC-02: Invalid password

**Title:** Invalid password

**Preconditions:**
- User has a valid account
- Login page is opened

**Steps:**
1. Open login page
2. Enter valid username
3. Enter wrong password
4. Click "Login" button

**Expected result:**
- Error message "Invalid credentials" is displayed
- User stays on the login page

## TC-03: Login with empty fields

**Title:** Login with empty fields

**Preconditions:**
- Login page is opened

**Steps:**
1. Open login page
2. Leave username field empty
3. Leave password field empty
4. Click "Login" button

**Expected result:**
- Error message is displayed indicating that username and password are required

## TC-04: Login with empty password field

**Title:** Login with empty password field

**Preconditions:**
- Login page is opened

**Steps:**
1. Open login page
2. Enter valid username
3. Leave password field empty
4. Click "Login" button

**Expected result:**
- Error message is displayed indicating that the password field is required

## TC-05: Login with invalid username and valid password

**Title:** Login with invalid username and valid password

**Preconditions:**
- Login page is opened

**Steps:**
1. Open login page
2. Enter invalid username
3. Enter valid password
4. Click "Login" button

**Expected result:**
- Error message "Invalid credentials" is displayed
- User remains on the login page

## TC-06: Login with empty username

**Title:** Login with empty username

**Preconditions:**
- Login page is opened

**Steps:**
1. Open login page
2. Leave username field empty
3. Enter valid password
4. Click "Login" button

**Expected result:**
- Error message indicating that the username field is required is displayed
- User remains on the login page
