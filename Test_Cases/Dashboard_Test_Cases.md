Account Dashboard – Test Cases
TS-01: Verify user is redirected to dashboard after successful login

TC-01.1: Successful login redirects to dashboard

Precondition
User is registered
Account is active

Steps
1.Open banking application
2.Enter valid username
3.Enter valid password
4.Click Login

Expected Result
1.Login is successful
2.User is redirected to dashboard page

TC-01.2: Dashboard URL verification

Steps
1.Login with valid credentials
2.Observe browser URL

Expected Result
1.URL matches configured dashboard endpoint

TS-02: Verify account holder name is displayed correctly

TC-02.1: Account holder name is displayed

Expected Result
1.Logged-in user’s full name is displayed on dashboard

TC-02.2: Account holder name matches profile

Expected Result
1.Displayed name matches name in user profile/backend

TS-03: Verify account number is masked

TC-03.1: Masking of account number

Expected Result
1.Account number is partially masked (e.g., XXXX4321)

TC-03.2: Full account number is not exposed

Expected Result
1.Full account number is never visible on dashboard

TS-04: Verify available balance is displayed correctly

TC-04.1: Available balance is visible

Expected Result
1.Available balance is displayed on dashboard

TC-04.2: Balance matches backend data

Expected Result
1.Displayed balance matches actual account balance

TC-04.3: Balance updates after transaction

Precondition
1.User completes a successful transaction

Expected Result
Balance reflects updated amount

TS-05: Verify currency is displayed correctly

TC-05.1: Currency symbol is displayed

Expected Result
1.Correct currency symbol (₹ / $ / €) is shown

TC-05.2: Currency format validation

Expected Result
1.Balance follows correct number format (decimal places)

TS-06: Verify multiple accounts are listed correctly (if applicable)

TC-06.1: Multiple accounts are displayed

Precondition
1.User has more than one account

Expected Result
1.All accounts are listed on dashboard

TC-06.2: Account details are correct

Expected Result
1.Each account shows correct type, masked number, and balance

TC-06.3: Account selection works

Expected Result
1.User can switch between accounts successfully

TS-07: Verify dashboard loads within acceptable time

TC-07.1: Dashboard load performance

Expected Result
1.Dashboard loads within defined SLA (e.g., < 3 seconds)

TC-07.2: Loader visibility

Expected Result
1.Loading indicator is shown until dashboard loads

TS-08: Verify error message when account service is unavailable

TC-08.1: Service down error handling

Precondition
1.Account service is unavailable (mock/stub)

Expected Result
1.User sees user-friendly error message

TC-08.2: Retry option availability

Expected Result
1.Retry / refresh option is provided

TS-09: Verify dashboard access without login is restricted

TC-09.1: Direct URL access restriction

Steps
1.Open dashboard URL without login

Expected Result
1.User is redirected to login page

TC-09.2: Session expiry behavior

Steps
1.Login successfully
2.Let session expire
3.Access dashboard

Expected Result
1.User is redirected to login page

TS-10: Verify navigation from dashboard to other modules

TC-10.1: Navigate to Fund Transfer

Steps
1.Click Fund Transfer from dashboard

Expected Result
1.Fund Transfer page opens successfully

TC-10.2: Navigate to Transaction History

Expected Result

1.Transaction History page opens successfully

TC-10.3: Navigate to Beneficiary Management

Expected Result
1.Beneficiary Management page opens successfully

TC-10.4: Navigation retains session

Expected Result
1.User remains logged in while navigating modules
1.User remains logged in while navigating modules

