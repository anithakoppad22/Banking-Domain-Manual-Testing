1.Login & Authentication Module – Test Scenarios

TS-01 Verify login with valid username and password
TS-02 Verify login with invalid username
TS-03 Verify login with invalid password
TS-04 Verify login with blank username and password
TS-05 Verify account lock after multiple invalid login attempts
TS-06 Verify session timeout after inactivity
TS-07 Verify logout functionality

2️.Dashboard / Account Summary Module – Test Scenarios

TS-08 Verify dashboard loads after successful login
TS-09 Verify display of account number and account type
TS-10 Verify display of available balance
TS-11 Verify refresh of balance after transaction
TS-12 Verify dashboard access without login

3️.Beneficiary Management Module – Test Scenarios

TS-13 Verify add beneficiary with valid details
TS-14 Verify add beneficiary with invalid account number
TS-15 Verify add beneficiary with invalid IFSC code
TS-16 Verify add beneficiary with missing mandatory fields
TS-17 Verify OTP validation while adding beneficiary
TS-18 Verify beneficiary addition without OTP
TS-19 Verify viewing beneficiary list
TS-20 Verify deletion of beneficiary

4️.Fund Transfer Module – Test Scenarios (CORE)

TS-21 Verify fund transfer with sufficient balance
TS-22 Verify fund transfer with insufficient balance
TS-23 Verify fund transfer exceeding daily limit
TS-24 Verify fund transfer without selecting beneficiary
TS-25 Verify fund transfer without entering amount
TS-26 Verify fund transfer with zero amount
TS-27 Verify fund transfer with invalid amount format
TS-28 Verify fund transfer with valid OTP
TS-29 Verify fund transfer with invalid OTP
TS-30 Verify fund transfer with expired OTP

5.Transaction Confirmation Module – Test Scenarios

TS-31 Verify success message after successful transfer
TS-32 Verify failure message for unsuccessful transfer
TS-33 Verify transaction reference number generation
TS-34 Verify user redirection after transaction completion

6.Transaction History Module – Test Scenarios

TS-35 Verify transaction history displays recent transactions
TS-36 Verify transaction details (date, amount, status)
TS-37 Verify transaction history update after fund transfer
TS-38 Verify transaction history when no transactions exist
TS-39 Verify transaction history sorting/filtering

7.Security & Validation Module – Test Scenarios

TS-40 Verify OTP expiry after defined time
TS-41 Verify OTP cannot be reused
TS-42 Verify data encryption during fund transfer
TS-43 Verify unauthorized access to fund transfer page
TS-44 Verify concurrent login handling

8.Non-Functional Test Scenarios

TS-45 Verify application response time during fund transfer
TS-46 Verify system behavior during network interruption
TS-47 Verify application availability
TS-48 Verify system behavior under high load