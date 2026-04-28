## Scope
Testing login functionality

## Test Coverage
- Valid login
- Invalid password
- Empty fields
- Empty password

# Login Page Test Cases

## Test Case 1: Valid login

Preconditions:
User has a valid account

Steps:
1. Open login page
2. Enter valid username
3. Enter valid password
4. Click login

Expected result:
User is logged in and redirected to dashboard


## Test Case 2: Invalid password

Preconditions:
User has a valid account

Steps:
1. Open login page
2. Enter valid username
3. Enter wrong password
4. Click login

Expected result:
- Error message "Invalid credentials" is displayed
- User stays on login page

# Test Case 3: Login with empty fields

## Preconditions
User is on the login page

## Steps
1. Open login page
2. Leave username field empty
3. Leave password field empty
4. Click "Login" button

## Expected result
Error message is displayed indicating that username and password are required

# Test Case 4: Login with empty password field

## Preconditions
User is on the login page

## Steps
1. Open login page
2. Enter valid username
3. Leave password field empty
4. Click "Login" button

## Expected result
Error message is displayed indicating that the password field is required

# Test Case 5: Login with invalid username and valid password

## Preconditions
User is on the login page

## Steps
1. Open login page
2. Enter invalid username
3. Enter valid password
4. Click "Login" button

## Expected result
- Error message "Invalid credentials" is displayed
- User remains on the login page
