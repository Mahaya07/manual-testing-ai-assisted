# Manual Test Cases – Login Feature

## Test Case 1: Valid Login
- Test Case ID: TC_LOGIN_001
- Description: Verify user can login with valid credentials
- Preconditions: User is registered
- Steps:
  1. Open login page
  2. Enter valid username
  3. Enter valid password
  4. Click Login
- Expected Result: User is logged in successfully

## Test Case 2: Invalid Password
- Test Case ID: TC_LOGIN_002
- Description: Verify login fails with invalid password
- Steps:
  1. Enter valid username
  2. Enter invalid password
  3. Click Login
- Expected Result: Error message is displayed

## Test Case 3: Empty Fields
- Test Case ID: TC_LOGIN_003
- Description: Verify validation for empty fields
- Steps:
  1. Leave username empty
  2. Leave password empty
  3. Click Login
- Expected Result: Required field validation message
