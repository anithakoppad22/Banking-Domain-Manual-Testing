Test Cases – Login Module
TS-01 Verify login with valid credentials

TC-01 Login with valid username and password
 Precondition:

1.User is registered
2.Account is active

Steps:
1.Open the banking application
2.Navigate to Login page
3.Enter valid username
4.Enter valid password
5.Click Login

Expected Result:

1.User is logged in successfully
2.User is redirected to dashboard

TS-02 Verify login with invalid password

TC-02 Login with valid username and invalid password

Steps:

1.Open Login page
2.Enter valid username
3.Enter invalid password
4.Click Login

Expected Result:
1.Error message displayed
2.User is not logged in

TS-03 Verify login with invalid username

TC-03 Login with invalid username and valid password

Expected Result:
Error message displayed
Login should fail

TS-04 Verify login with empty username

TC-04 Login with empty username field

Expected Result:
Validation message shown
Login button should not proceed

TS-05 Verify login with empty password

TC-05 Login with empty password field

Expected Result:
Validation message displayed

TS-06 Verify login with empty username and password

TC-06 Login without entering credentials

Expected Result:
Mandatory field validation errors shown

TS-07 Verify account lock after multiple failed attempts

TC-07 Account lock after 3 consecutive failures

Steps:

1.Enter incorrect password multiple times
2.Expected Result:
3.Account gets locked
4.User notified of lock

TS-08 Verify login with expired password

TC-08 Login using expired password

Expected Result:
1.User prompted to reset password

TS-09 Verify login with inactive account

TC-09 Login with deactivated account

Expected Result:
1.Login blocked
2.Appropriate error shown

TS-10 Verify login with invalid OTP

TC-10 Login with incorrect OTP

Expected Result:
1.OTP validation error displayed

TS-11 Verify login with expired OTP

TC-11 Login using expired OTP

Expected Result:
1.OTP expired message displayed

TS-12 Verify OTP resend functionality

TC-12 Resend OTP

Expected Result:
1.New OTP sent
2.Previous OTP invalidated

TS-13 Verify login page UI elements

TC-13 UI verification

Expected Result:
1.Username, Password, Login button visible
2.Proper alignment and labels

TS-14 Verify password masking functionality

TC-14 Password hidden while typing

Expected Result:
1.Password characters masked

TS-15 Verify login session timeout

TC-15 Session expires after inactivity

Expected Result:
1.User logged out automatically

TS-16 Verify browser refresh after login

TC-16 Refresh page after login

Expected Result:
1.User remains logged in

TS-17 Verify SQL injection prevention

TC-17 SQL injection attempt

1.Input:
' OR '1'='1

Expected Result:
1.Login blocked
2.No system crash

TS-18 Verify special characters handling

TC-18 Login with special characters

Expected Result:
1.Proper validation performed

TS-19 Verify logout after login

TC-19 Logout functionality

Expected Result:
1.User logged out successfully
2.Redirected to login page

TS-20 Verify login audit logs

TC-20 Login activity logging

Expected Result:
1.Login attempt recorded in audit logs
