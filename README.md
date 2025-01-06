# Manual Testing for Login and Registration

This repo contains manual tests for the login and registration features of the app. The goal is to check if both functions work correctly.

## Test Scenarios

### Login
1. **Valid Login**: Test with correct username and password.
2. **Invalid Username**: Test with an incorrect username.
3. **Invalid Password**: Test with a correct username but wrong password.
4. **Empty Fields**: Try logging in with empty username or password fields.
5. **Too Many Failed Attempts**: Test if the system locks after multiple failed logins.

### Registration
1. **Valid Registration**: Test with correct details (username, password, email).
2. **Existing Username**: Try registering with a username that’s already taken.
3. **Invalid Email**: Enter an invalid email format.
4. **Weak Password**: Try using a weak password.
5. **Empty Fields**: Try registering with missing required fields.
6. **Password Mismatch**: Enter different passwords in "password" and "confirm password" fields.

## Prerequisites
- Access to the app and testing environment.
- A test account or ability to create a new user.
- A working internet connection.

## Steps
1. Open the app in your browser.
2. Test the registration functionality with the scenarios listed.
3. Test the login functionality with the scenarios listed.

## Expected Results
- **Registration**: Should successfully register or show clear error messages for issues.
- **Login**: Should allow access with valid credentials and show error messages for invalid ones.

## Conclusion
By following these tests, you’ll verify that the login and registration features work as expected. Report any issues you find.

