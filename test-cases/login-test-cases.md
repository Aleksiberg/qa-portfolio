## Scope
Testing login functionality

## Test Coverage
- Valid login
- Invalid password
- Empty fields
- Empty password

# Login Page Test Cases

## TС-01: Valid login

Preconditions:
User has a valid account

Steps:
1. Open login page
2. Enter valid username
3. Enter valid password
4. Click login

Expected result:
- User is logged in and redirected to dashboard

Actual result:
- User is logged in and redirected to dashboard

## TС-02: Invalid password

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

Actual result:
- User is not logged in and redirected to dashboard

## TС-03: Login with empty fields

## Preconditions
User is on the login page

## Steps
1. Open login page
2. Leave username field empty
3. Leave password field empty
4. Click "Login" button

Expected result:
- Error message is displayed indicating that username and password are required

Actual result:
- User is not logged in and redirected to dashboard

## TС-04: Login with empty password field

## Preconditions
User is on the login page

## Steps
1. Open login page
2. Enter valid username
3. Leave password field empty
4. Click "Login" button

Expected result:
- Error message is displayed indicating that the password field is required

Actual result:
- User is not logged in and redirected to dashboard

## TС-05: Login with invalid username and valid password

## Preconditions
User is on the login page

## Steps
1. Open login page
2. Enter invalid username
3. Enter valid password
4. Click "Login" button

Expected result:
- Error message "Invalid credentials" is displayed
- User remains on the login page

Actual result:
- User is not logged in and redirected to dashboard

## TС-06: Login with empty username

## Preconditions
User is on the login page

## Steps
1. Open login page
2. Leave username field empty
3. Enter valid password
4. Click "Login" button

Expected result:
- Error message is displayed indicating that the username field is required
- User remains on the login page

Actual result:
- User is not logged in and redirected to dashboard
